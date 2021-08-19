+++
title = "Emacs mu4e 配置"
author = ["Zenith John"]
publishDate = 2021-08-19T00:00:00+08:00
draft = false
+++

## Offlineimap {#offlineimap}

首先我们需要使用 Offlineimap 来获取服务器上的邮件。我们需要准备几个文件，一是 ~/.offlineimaprc 如下

```conf
[general]
accounts = Foxmail, Tsinghua
pythonfile = ~/.offlineimap.py

[Account Foxmail]
localrepository = LocalFoxmail
remoterepository = RemoteFoxmail
proxy = SOCKS5:172.26.240.1:10800

[Repository LocalFoxmail]
type = Maildir
localfolders = ~/Documents/Mail/Foxmail

[Repository RemoteFoxmail]
type = IMAP
remotehost = imap.qq.com
remoteuser = zenith-john@foxmail.com
remotepasseval = mailpasswd("foxmail")
ssl = yes
maxconnection = 1
sslcacertfile = /etc/ssl/certs/ca-certificates.crt

[Account Tsinghua]
localrepository = LocalTsinghua
remoterepository = RemoteTsinghua

[Repository LocalTsinghua]
type = Maildir
localfolders = ~/Documents/Mail/Tsinghua

[Repository RemoteTsinghua]
type = IMAP
remotehost = mails.tsinghua.edu.cn
remoteuser = znt21@mails.tsinghua.edu.cn
remotepasseval = mailpasswd("tsinghua")
ssl = yes
maxconnection = 1
sslcacertfile = /etc/ssl/certs/ca-certificates.crt
```

其中的各项含义都较为显然，有趣的是我直接登入 Foxmail 经常获取邮件失败，挂了代理反而没有问题。注意这里没有使用原文存放密码，而是使用 ~/.offlineimap.py 中的 mailpasswd 函数使用 gpg 来获得密码。~/.offlineimap.py 代码如下：

```python
import os
import subprocess

def mailpasswd(acct):
  acct = os.path.basename(acct)
  path = "/home/zenith-john/.passwd/%s.gpg" % acct
  args = ["gpg", "--use-agent", "--quiet", "--batch", "-d", path]
  try:
    return subprocess.check_output(args).strip()
  except subprocess.CalledProcessError:
    return ""
```

其中主要是使用 gpg 来获得密码。我们可以通过

```bash
# 创建密钥
gpg --full-generate-key

# 加密
gpg -e -r RECIPIENT ~/.passwd/file
```

来创建加密后的文件。


## 使用 mu4e {#使用-mu4e}

使用 <https://github.com/djcb/mu> 获得代码，编译得到最新版本，并将 mu4e 加入加载路径。我们要将加入 smtp 服务器加入 ./.authinfo 其每一行类似

```conf
machine * login * port * password **
```

注意要使用 mu4e 查看邮件，在编译时最好使用 xml2 以及 --with-mailutils 选项。

同时为了使用不同的邮件我加入了函数，使得在发送邮件时选择邮箱。一个样例配置如下。其中选择 `mu4e-sent-message-behavior` 需要设置为 `\'delete` 来使得在下载邮件时不会导致出现重复。

```elisp
(setq mail-user-agent 'mu4e-user-agent
      user-full-name "Zenith John"
      message-send-mail-function 'smtpmail-send-it
      send-mail-function 'smtpmail-send-it)

(setq mu4e-get-mail-command "offlineimap"
      mu4e-update-interval 600
      mu4e-maildir-list "~/Documents/Mail"
      mu4e-view-use-old nil
      mu4e-sent-messages-behavior 'delete)

(setq mu4e-sent-folder "/Foxmail/Sent Messages"
      mu4e-drafts-folder "/Foxmail/Drafts"
      user-mail-address "zenith-john@foxmail.com"
      smtpmail-smtp-server "smtp.qq.com"
      smtpmail-local-domain "qq.com"
      smtpmail-smtp-service 465
      smtpmail-stream-type 'ssl)

(defvar zenith/mu4e-account-alist
  '(("Foxmail"
     (mu4e-sent-folder "/Foxmail/Sent Messages")
     (mu4e-drafts-folder "/Foxmail/Drafts")
     (user-mail-address "zenith-john@foxmail.com")
     (smtpmail-smtp-server "smtp.qq.com")
     (smtpmail-local-domain "qq.com")
     (smtpmail-smtp-service 465)
     (smtpmail-stream-type ssl))
    ("Tsinghua"
     (mu4e-sent-folder "/Tsinghua/Sent Items")
     (mu4e-drafts-folder "/Tsinghua/Drafts")
     (user-mail-address "znt21@mails.tsinghua.edu.cn")
     (smtpmail-smtp-server "mails.tsinghua.edu.cn")
     (smtpmail-local-domain "mails.tsinghua.edu.cn")
     (smtpmail-smtp-service 465)
     (smtpmail-stream-type ssl))))

(defun zenith/mu4e-set-account ()
  "Set the account for composing a message."
  (let* ((account
          (if mu4e-compose-parent-message
              (let ((maildir (mu4e-message-field mu4e-compose-parent-message :maildir)))
                (string-match "/\\(.*?\\)/" maildir)
                (match-string 1 maildir))
            (completing-read (format "Compose with account: (%s) "
                                     (mapconcat #'(lambda (var) (car var))
                                                zenith/mu4e-account-alist "/"))
                             (mapcar #'(lambda (var) (car var)) zenith/mu4e-account-alist)
                             nil t nil nil (caar zenith/mu4e-account-alist))))
         (account-vars (cdr (assoc account zenith/mu4e-account-alist))))
    (if account-vars
        (mapc #'(lambda (var)
                  (set (car var) (cadr var)))
              account-vars)
      (error "No email account found"))))

(add-hook 'mu4e-compose-pre-hook 'zenith/mu4e-set-account)

(require 'smtpmail)
(require 'mu4e)
```

接下来，就能很好地使用 mu4e 了。
