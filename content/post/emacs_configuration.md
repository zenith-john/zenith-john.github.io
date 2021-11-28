+++
title = "Emacs"
author = ["Zenith John"]
publishDate = 2021-08-19
tags = ["Computer"]
draft = false
showtoc = true
+++

## 版本 {#版本}

Emacs 是我最常用的编码工具。我使用的是 Emacs 27 版本，自己编译，编译选项为

```bash
./configure --with-dbus --with-gif --with-jpeg --with-png --with-rsvg --with-tiff --with-xft --with-xpm --with-xml2 --with-xwidgets --with-modules --with-native-compilation --with-pgtk --with-json --with-mailutils CFLAGS="-O3 -mtune=native -march=native -fomit-frame-pointer"
```


## 配置文件主体 {#配置文件主体}

对于新手而言，不建议自己从头开始配置。因为很有可能会迷失在配置文件之中，建议先使
用其他人的配置，同时通过学习其他人的代码来进行学习，在一定时间之后再逐渐积累形成
自己的配置。就我个人而言最开始使用的是purcell的配置文件。
<https://github.com/purcell/emacs.d> 又尝试了Spacemacs，
<https://github.com/syl20bnr/spacemacs>, 但是由于Spacemacs启动速度过慢，同时有过多
的冗余设置，加入自己的配置也不够方便，因此，开始了自己的配置。从各个repo中抄了很
多的代码，途中也学习了不少关于Emacs和Lisp的知识。最近发现了
Doom-emacs,<https://github.com/hlissner/doom-emacs/>。 相比于Spacemacs，Doom-emacs
启动较快，同时利用Doom-emacs提供的各种宏，能够更好地在不改变原始仓库代码的同时进
行配置。 ~~目前我的配置就建立在Doom-emacs的基础上~~ 。目前我已经重新使用完全由自己
编码的配置来换取精确的控制。就我现在来看，我更加推荐 Purcell 的配置，并从他的配
置中逐步学习。这是因为他的配置额外的结构较少，不容易像学习 spacemacs 一样陷入配
置的重重引用中。


## 好的字体是成功的一半 {#好的字体是成功的一半}

推荐字体 **更纱黑体** ，中英文等宽等高避免Org-mode的各种错位。虽然个人感觉英文字体
没有那么好看，但还是可以接受的。(中文还是非常漂亮的)附链接:[Sarasa Gothic](https://github.com/be5invis/Sarasa-Gothic)

可以这样配置（中文使用更纱黑体，英文使用 Iosevka 与 Source Code Pro 的混合）：

```emacs-lisp
(defvar zenith-font (font-spec :family "Iosevka Term SS09" :size 16 :weight 'semi-bold))
(defvar zenith-unicode-font (font-spec :family "Sarasa Term SC" :weight 'bold))
(setq inhibit-x-resources t)

(defun zenith/init-font ()
  (add-to-list 'default-frame-alist `(font . ,(font-xlfd-name zenith-font)))
  (set-fontset-font t 'unicode zenith-unicode-font nil 'prepend))

(zenith/init-font)
```

在GTK环境中，EMACS在打开后会根据GConf重新设置字体格式，因此要有效的设置字体必须在.emacs或者init.el中加入

```emacs-lisp
(define-key special-event-map [config-changed-event] 'ignore)
```

更具体的说明请看<https://emacs.stackexchange.com/questions/32641/something-changes-the-default-face-in-my-emacs/32664#32664>


## Writeroom-mode and others {#writeroom-mode-and-others}

至少在Ubuntu 18.04中，这些使文字居中的模式(Writeroom )不能够很好地与ibus协作，
ibus的选单会发生偏移。原因和解决方案有待进一步观察。（目前我已经使用
darkroom-mode 但是会遇到同样的问题）

事实上，这个问题可以使用 Emacs 的内置输入法来解决。但是内置输入法太弱，因此我们
使用 <https://github.com/tumashu/pyim> 。事实上，pyim 除了输入法外还提供了很多非常
有用的功能。比如根据环境切换中英文状态，比如将英文字符串转变为输入法的输入等。配
置可以参考我的 config/init-pyim.el 。其中我使用的 pyim 后端是 rime， rime 是一个
非常好用的输入法。


## 在Emacs中使用使用Microsoft Python Language Server {#在emacs中使用使用microsoft-python-language-server}


### Why {#why}

目前来看 Microsoft 的 Python Language Server 由于使用 C# 写成，因此速度最快，卡顿较少，补全效果较好。


### How {#how}

主要的过程都在这篇文章之中：<https://vxlabs.com/2018/11/19/configuring-emacs-lsp-mode-and-microsofts-visual-studio-code-python-language-server/> ,但是有必要对于一些步骤进行改进。

首先在代码中对于 lsp-ui-sideline--format-info 和 lsp-ui-doc--extract 这两个函数添加了 advice，而这advice在输入的 doc 为 nil 时会报错，因此在ccls时这两个函数不能够正常工作，因此需要添加 (when doc ……) 这样的判定条件才能够保证其正确性。
另一方面，在我的电脑上，python language server 在补全时会加入一些莫名其妙的东西。在字符较短时，会列出所有的关键字(不知道为什么)。因此需要修改 company-transformers 为了保证模糊匹配的效果，加入了 company-flx-transformer 来对所获得的序列进行排序。效果尚可。


### 补充 {#补充}

~~由于目前emacs的lsp-mode速度较慢，因此我在使用Doom-emacs并没有开启lsp选项~~ 。 目前
我使用的是 nox 是 eglot 的阉割版，自动支持 mspyls。


## Org-mode {#org-mode}


### 一些有用的功能 {#一些有用的功能}

首先就是 [org-bullets](https://github.com/sabof/org-bullets)
还有就是为了配合 ivy 等补全工具设置

```emacs-lisp
(setq org-outline-path-complete-in-steps nil
      org-goto-interface 'outline-path-completion)
```

放大 latex preview 的公式，并让公式背景与主体适应：

```emacs-lisp
(setq org-format-latex-options (plist-put org-format-latex-options :scale 1.5))
(setq-default
 org-format-latex-options
 (plist-put org-format-latex-options
            :background
            (face-attribute (or (cadr (assq 'default face-remapping-alist))
                                'default)
                            :background nil t)))
```

在字体使用粗体时，emphasis 的效果加粗无法很好的显示出来。因此我通过配置
org-emphasis-alist改变了原来应该加粗的字体的颜色，并使得能够这一效果可以换行。代码如下：

```emacs-lisp
(add-to-list 'org-emphasis-alist
             '("*" (:foreground "pink")))
(setcar (nthcdr 4 org-emphasis-regexp-components) 4)
(org-set-emph-re 'org-emphasis-regexp-components org-emphasis-regexp-components)
```

还有很多细碎的小配置就不赘述了。


### Org mode Easy Templates {#org-mode-easy-templates}

在 Org-mode 9.2 中，easytemplate的使用方式发生了改变。从 `<s <TAB>` ;变成了 ~C-c C-,~ 。
不得不说 Org-babel 是个很好用的功能，可以探索一下。


### org-refile {#org-refile}

由于我个人倾向于将笔记放在一起，因此使用了一个笔记本文件夹，为了使得 refile 能够
与此配合需要一些配置。

```emacs-lisp
(defun zenith/refile-targets-notes ()
  (directory-files zenith/note-directory t ".*\\.org\\'"))

(setq-default org-refile-targets
              '((nil :maxlevel 3)
                (org-agenda-files :maxlevel 3)
                (zenith/refile-targets-notes :maxlevel 3)))
```


### GTD {#gtd}

Emacs Org-mode 的一个卖点就是 GTD。其中需要 org-agenda, org-capture, org-tags 等
部分互相配合。关于关键词可以参考，在 Tag 中创建了一个 Group Must 来管理不得不做
的一些事的 Tag：

```emacs-lisp
(setq org-todo-keywords
      '((sequence "TODO(t)" "WAITING(w@/!)" "PAUSE(p)" "SOMEDAY(s)" "NEXT(n)" "|" "DONE(d!)" "CANCELLED(c@)")
        (sequence "[ ](T)" "[-](P)" "[?](m)" "|" "[X](D)"))
      org-todo-keyword-faces
      '(("[-]" :inherit (font-lock-constant-face bold))
        ("[?]" :inherit (warning bold))
        ("WAITING" :inherit bold)
        ("LATER" :inherit (warning bold))))

(setq org-capture-templates
      '(
        ("h" "Homework" entry (file+headline "~/Dropbox/task.org"  "Homework")
         "* TODO %? :Homework:\n")
        ("s" "Schedule" entry (file+headline "~/Dropbox/task.org" "Schedule")
         "* %?\n")
        ("r" "Project" entry (file+headline "~/Dropbox/task.org" "Project")
         "* TODO %?\n")
        ("q" "Question" entry (file+headline "~/Dropbox/task.org" "Question")
         "* TODO %? :Question:\n")
        ("d" "Idea" entry (file+headline "~/Dropbox/task.org" "Idea")
         "* TODO %? :Idea:\n")))

;; Org tag
(setq org-tag-alist
      '(("Improvement" . ?i)
        (:startgrouptag)
        ("Must")
        (:grouptags)
        ("Homework" . ?h)
        ("Job" . ?j)
        (:endgrouptag)
        ("Personal" . ?p)
        ("Question" . ?q)
        ("Idea" . ?d)))
```

关于 Agenda 可以参考，在代码中创建了一个 "b" 视图，并且将紧急的事情，最近的
Deadline 较遥远的 Deadline 等整合到了一起。

```emacs-lisp
;; Org agenda settings
(setq org-agenda-start-on-weekday nil
      org-agenda-skip-scheduled-if-deadline-is-shown t
      org-agenda-skip-deadline-prewarning-if-scheduled (quote pre-scheduled)
      org-agenda-skip-scheduled-if-done t
      org-agenda-skip-deadline-if-done t
      org-agenda-span 7
      org-agenda-compact-blocks t
      org-agenda-show-all-dates nil
      org-deadline-warning-days 365
      org-agenda-show-future-repeats t
      org-agenda-window-setup 'only-window)


(setq org-agenda-custom-commands
      '(("b" "Agenda View" ((tags "AGENDAHEADER"
                                  ((org-agenda-overriding-header "Today's Schedule:")))
                            (agenda ""
                                    ((org-agenda-show-all-dates t)
                                     (org-agenda-span 'day)
                                     (org-deadline-warning-days 0)
                                     (org-agenda-start-day "+0d")))
                            (todo "NEXT"
                                  ((org-agenda-overriding-header "========================================\nNext Tasks:")))
                            (tags-todo "Must/!-NEXT"
                                       ((org-agenda-overriding-header "========================================\nMust Do:")))
                            (tags "BEFOREWEEKGLANCE"
                                  ((org-agenda-overriding-header "========================================\nNext Week Glance:")))
                            (agenda ""
                                    ((org-agenda-show-all-dates t)
                                     (org-agenda-span 6)
                                     (org-agenda-start-day "+1d")))
                            (tags "BEFOREDEADLINE"
                                  ((org-agenda-overriding-header "========================================\nFar Away Tasks:")))
                            (agenda ""
                                    ((org-agenda-span 180)
                                     (org-agenda-time-grid nil)
                                     (org-agenda-show-all-dates nil)
                                     (org-agenda-entry-types '(:deadline :scheduled))
                                     (org-agenda-start-day "+7d")))))
        ("i" "Improvement" ((tags-todo "Question"
                                       ((org-agenda-overriding-header "Unsolved Questions:")))
                            (tags-todo "Improvement" ((org-agenda-overriding-header "\n\nImprovment:")))
                            (tags-todo "Idea+TODO<>\"NEXT\"|Personal+TODO<>\"NEXT\""
                                       ((org-agenda-overriding-header "\n\nPersonal Project:")))))))
```


### GTD 补充 {#gtd-补充}

由于 Org-mode 本身并不带有更加可视化的视图以及提醒系统，我个人通过 org-icalendar
和 KOrganizer 来做到这一点。确切来说，在使用 Org-agenda 时会将目前的配置导出到
icalendar 文件中，然后再使用 KOrganizer 读取来达到目的。

```emacs-lisp
;; ox-icalendar
(with-eval-after-load 'ox-icalendar
  (setq org-icalendar-combined-agenda-file (expand-file-name "~/Dropbox/agenda.ics")
        org-icalendar-include-todo t
        org-icalendar-use-deadline '(event-if-not-todo todo-due)
        org-icalendar-use-scheduled '(event-if-not-todo todo-start)
        org-icalendar-alarm-time 15
        org-icalendar-store-UID t
        org-agenda-default-appointment-duration 90))
(add-hook 'org-agenda-finalize-hook 'org-icalendar-combine-agenda-files)
```


### Org-attach {#org-attach}

attach 是将文件附与某个 headline 的方法，这样可以在 Org-mode 中将标题和文件关联
起来，可以看成是另一种 Link. 我定义了一个方法，这个方法可以在 org-agenda 中更快
地打开 attach 的文件，这也是它相对于一般的 Link 的优势所在。

```emacs-lisp
;; Org attach
(setq org-attach-method 'lns)

(zenith/autoload '(org-attach org-attach-open) "org-attach")

(defun org-agenda-attach-open ()
  "Open attachment with one-key stroke."
  (interactive)
  (unless (eq major-mode 'org-agenda-mode)
    (let ((debug-on-quit nil))
      (signal 'quit '("This was written expressly for `*Org Agenda*`."))))
  (let ((marker (or (get-text-property (point) 'org-hd-marker)
                    (get-text-property (point) 'org-marker))))
    (if marker
        (save-excursion
          (set-buffer (marker-buffer marker))
          (goto-char marker)
          (org-back-to-heading t)
          (call-interactively 'org-attach-open))
      (error "No task in current line"))))
```


### Org-id {#org-id}

一般的 Org-mode 之间的 Link 是依赖于文件结构的。这样当文件结构变化时其链接有可能
会失效，因此 Org-Mode 提供了 Org-id 这一模块来实现更加健壮的链接。

```emacs-lisp
(setq org-id-track-globally t
      org-id-link-to-org-use-id t
      org-id-locations-file (expand-file-name ".org-id-locations" zenith-emacs-local-dir))

(with-eval-after-load 'org-id
  (setq org-id-extra-files (directory-files-recursively zenith/note-directory ".*\\.org"))
  (org-id-update-id-locations)
  (defun org-id-complete-link (&optional arg)
    "Create an id: link using completion"
    (concat "id:"
            (org-id-get-with-outline-path-completion org-refile-targets)))
  (org-link-set-parameters "id"
                           :complete 'org-id-complete-link)
  (defun zenith/search-id-reverse-link ()
    "Search the id in the directory"
    (interactive)
    (let ((query
           (cdr (first (org-entry-properties nil "ID")))))
      (rg-project query "*.org")))
  (defun zenith/org-insert-link-by-id ()
    "Insert the link by id"
    (interactive)
    (let ((link (org-link--try-special-completion "id")))
      (org-insert-link nil link))))
```


### Org 与 LaTeX {#org-与-latex}

Org 有着非常丰富的导出选项，比如导出到 PDF，这一功能通过 LaTeX 实现。因此需要对
于 ox-latex 进行一定的配置。

```emacs-lisp
(with-eval-after-load 'ox-latex
  (add-to-list 'org-latex-classes
               '("myart"
                 "\\documentclass{article}
[DEFAULT-PACKAGES]
[PACKAGES]
\\usepackage[backend=biber,style=alphabetic]{biblatex}
\\addbibresource[location=local]{~/Dropbox/Library.bib}
\\setCJKmainfont{Source Han Sans CN}
\\setmonofont{Source Code Pro}
\\gappto{\\UrlBreaks}{\\UrlOrds}
"
                 ("\\section{%s}" . "\\section*{%s}")
                 ("\\subsection{%s}" . "\\subsection*{%s}")
                 ("\\subsubsection{%s}" . "\\subsubsection*{%s}")
                 ("\\paragraph{%s}" . "\\paragraph*{%s}")
                 ("\\subparagraph{%s}" . "\\subparagraph*{%s}")))
  (setq org-latex-compiler "xelatex"
        org-latex-default-class "myart"
        org-export-with-sub-superscripts nil
        org-latex-listings 'minted
        org-latex-minted-options '(("breaklines" "true")
                                   ("frame" "single")
                                   ("breakanywhere" "true"))
        org-latex-pdf-process
        '("latexmk -g -pdf -pdflatex=\"%latex\" -shell-escape -outdir=%o %f"))
  (setq org-latex-packages-alist '(("" "minted")
                                   ("" "xcolor")
                                   ("" "xeCJK")
                                   ("" "fontspec")
                                   ("" "etoolbox"))))
```


### org-download in WSL {#org-download-in-wsl}

由于一些 Windows 下所必须的软件，我有很多时候是在 WSL 中使用 Emacs，为了更好地在 WSL 中使用 org-download 我进行了一些必要的 Trick。首先要在 Windows 中安装 [IrfanView](https://www.irfanview.com/)。然后需要使用我的 init-wsl.el 文件，其中包含了对文件路径进行一定的处理的函数。最后，再修改一下 org-download-yank 以及 org-download-screenshot 函数即可。当然，最好用的 drag-and-drop 还是无法使用的。


## Emacs换行问题 {#emacs换行问题}

关闭 auto-fill-mode，使用 visual-line-mode，因为visual-line-mode在操作hjkl时更加直观。

```emacs-lisp
(remove-hook! org-mode
              #'auto-fill-mode)
(global-visual-line-mode)
```

现在我同时使用 auto-fill 和 visual-fill-column。事实上 auto-fill-mode 有很多的优
点，在自己编辑时会感觉更加舒服，但是问题在于 auto-fill 后的文件给别人就会不舒服。
这是 visual-fill-column 就派上了用场。

```emacs-lisp
(defun zenith/fill-and-indent-region ()
  "Fill paragraph and indent region at once"
  (interactive)
  (when (or
         (derived-mode-p 'text-mode)
         (nth 4 (syntax-ppss))
         (nth 8 (syntax-ppss)))
    (call-interactively 'fill-paragraph))
  (call-interactively 'indent-region))

;; visual fill column
(autoload 'visual-fill-column-mode "visual-fill-column" "" t)
(setq-default visual-fill-column-width (+ fill-column 20))
(add-hook 'visual-line-mode-hook 'visual-fill-column-mode)
(add-hook 'auto-fill-mode-hook 'visual-line-mode)
```


## 关于注释问题 {#关于注释问题}

Doom-emacs默认的注释插件是evil-commentary，但是我觉得evil-nerd-commenter <https://github.com/redguardtoo/evil-nerd-commenter> 更加便于使用，因为它能够toggle，注释和非注释状态。因此我使用evil-nerd-commenter取代了evil-commentary。

```emacs-lisp
;; evil-nerd-commenter
;; dependencies: evil
(zenith/autoload
 '(evilnc-comment-operator
   evilnc-comment-or-uncomment-lines
   evilnc-comment-or-uncomment-paragraphs
   evilnc-comment-or-uncomment-to-the-line
   evilnc-copy-and-comment-lines
   evilnc-copy-and-comment-operator
   evilnc-copy-to-line)
 "evil-nerd-commenter")
```

其中 zenith/autoload 是我自己写的一个函数是 autoload 的一个封装，可以同时对多个
函数进行 autoload。


## Evil-mode {#evil-mode}

由于我已经使用了个人的配置，就不得不对于 Evil-mode 来进行一番配置了，事实上使用
evil-collection 后基本上就按着默认来了。值得注意的是
<https://github.com/emacs-evil/evil-surround> 和
<https://github.com/redguardtoo/evil-matchit> 两个包，非常好用值得一试。

```emacs-lisp
;; evil
;; dependencies: undo-tree goto-chg
(setq evil-want-integration t  ; This is optional since it's already set to t by default.
      evil-want-keybinding nil ; loading keybindings
      evil-disable-insert-state-bindings t ; Use emacs's binding in insert state
      evil-want-C-d-scroll nil ; Use emacs's C-d
      evil-want-C-u-scroll nil ; Use emacs's C-u
      evil-want-C-i-jump t     ; Use vim's C-i
      evil-want-fine-undo t    ; Don not aggregate changes when exiting insert state
      evil-want-C-w-delete t   ; Use emacs's C-w
      evil-toggle-key ""       ; C-z not entering emacs state
      )

(require 'evil)

(evil-mode 1)
```


## 自动保存 {#自动保存}

Emacs 的保存非常反人类，不如让他自己来保存吧。不过这个功能最好和版本控制系统一起
使用，否则后果自负。这里调用了 evil 的 api， 每 2 秒没有操作就保存一次。

```emacs-lisp
;; The code is adjusted from https://github.com/manateelazycat/auto-save. The
;; problem of the original code is that it calls buffer-modified-p which makes
;; ws-butler unhappy.
(setq auto-save-idle 2)

(defun zenith/auto-save-buffers ()
  (interactive)
  (when (and
         (not (minibufferp))
         (or (not (boundp 'yas--active-snippets))
             (not yas--active-snippets))
         (or (not (boundp 'company-candidates))
             (not company-candidates)))
    (with-temp-message ""
      (let ((inhibit-message t))
        (evil-write-all nil)))))

(defun zenith/auto-save-enable ()
  (interactive)
  (run-with-idle-timer auto-save-idle t #'zenith/auto-save-buffers))

(zenith/auto-save-enable)
```


## LaTeX {#latex}

Ebib 是 bib 文件的查看器，但是我感觉用处并没有很大，很多时候我都是直接编辑的。

Auctex + reftex 是非常强大的 LaTeX 处理器，其中的功能非常强大而复杂。这里的代码
使得 Reftex 能够更好地在写数学论文时进行引用。

```emacs-lisp
(add-hook 'LaTeX-mode-hook 'turn-on-reftex)
;; Get ReTeX working with biblatex
;; http://tex.stackexchange.com/questions/31966/setting-up-reftex-with-biblatex-citation-commands/31992#31992
(setq reftex-cite-format
      '((?a . "\\autocite[]{%l}")
        (?b . "\\blockcquote[]{%l}{}")
        (?c . "\\cite[]{%l}")
        (?f . "\\footcite[]{%l}")
        (?n . "\\nocite{%l}")
        (?p . "\\parencite[]{%l}")
        (?s . "\\smartcite[]{%l}")
        (?t . "\\textcite[]{%l}"))
      reftex-plug-into-AUCTeX t
      reftex-toc-split-windows-fraction 0.3
      reftex-bibpath-environment-variables '("/home/zenith-john/Dropbox/")
      reftex-bibliography-commands '("bibliography" "nobibiliography" "addbibresource")
      reftex-label-alist
      '(("theorem" ?m "thm:" "~\\ref{%s}" nil (regexp "[Tt]heorem" "[Tt]h\\.") -3)
        ("lemma"   ?m "lem:" "~\\ref{%s}" nil (regexp "[Ll]emma"   "[Ll]m\\.") -3)
        ("proposition" ?m "prop:" "~\\ref{%s}" nil (regexp "[Pp]roposition" "[Pp]rop\\.") -3)
        ("remark"      ?m "rmk:"  "~\\ref{%s}" nil (regexp "[Rr]emark" "[Rr]mk\\.") -3)
        ("definition"  ?m "def:"  "~\\ref{%s}" nil (regexp "[Dd]efinition" "[Dd]ef\\.") -3)
        ("corollary"   ?m "cor:"  "~\\ref{%s}" nil (regexp "[Cc]orollary" "[Cc]or\\.") -3))
      reftex-ref-macro-prompt nil)
```

这里设置了自动补全的后端，注意顺序在这里是重要的。

```emacs-lisp
(with-eval-after-load 'tex
  ;; the order of company-backend is important.
  ;; company-auctex
  ;; dependencies: yasnippet company auctex
  (require 'company-auctex)
  ;; company-math
  ;; dependencies: company math-symbol-lists
  (require 'company-math)

  (add-to-list '+latex-company-backends 'company-auctex-labels)
  (add-to-list '+latex-company-backends 'company-math-symbols-latex)
  (add-to-list '+latex-company-backends '(company-auctex-macros company-auctex-environments)))

(defun zenith/latex-company-setup ()
  "Setup company backends for latex editing."
  (make-local-variable 'company-backends)
  (setq zenith/local-company-backends nil)
  (dolist (backend +latex-company-backends)
    (add-to-list 'company-backends backend)))

(add-hook 'LaTeX-mode-hook 'zenith/latex-company-setup)
```

在 auctex 中比较重要的设置是 TeX-source-correlate-mode，
LaTeX-fill-break-at-separators 以及 TeX-command-extra-options，详情可以参考我的
配置 config/init-latex.el 。值得注意的是其中我的几个函数，

```emacs-lisp
(defun LaTeX-star-environment-dwim ()
  "Convert between the starred and the not starred version of the current environment."
  (interactive)
  ;; If the current environment is starred.
  (if (string-match "\*$" (LaTeX-current-environment))
      ;; Remove the star from the current environment.
      (LaTeX-modify-environment (substring (LaTeX-current-environment) 0 -1))
    ;; Else add a star to the current environment.
    (LaTeX-modify-environment (concat (LaTeX-current-environment) "*"))))

(defun zenith/latex-toggle-section-with-star ()
  (interactive)
  (if (member '("section" 2) LaTeX-section-list) ;; TODO: Make it more robust.
      (setq LaTeX-section-list
            '(("part" 0)
              ("chapter" 1)
              ("section*" 2)
              ("subsection*" 3)
              ("subsubsection*" 4)
              ("paragraph" 5)
              ("subparagraph" 6)
              ("section" 2)
              ("subsection" 3)
              ("subsubsection" 4)))
    (setq LaTeX-section-list
          '(("part" 0)
            ("chapter" 1)
            ("section" 2)
            ("subsection" 3)
            ("subsubsection" 4)
            ("paragraph" 5)
            ("subparagraph" 6)))))
(defvar zenith/equation-env-list
  '(("\\begin{equation}\n" . "\n\\end{equation}")
    ("\\[" . "\\]")
    ("\\(" . "\\)"))
  "The pairs of equation environment")

(defun zenith/regex-or (l)
  (let ((regex "\\(?:")
        (first-one t))
    (dolist (e l)
      (if (not first-one)
          (setq regex
                (concat regex "\\\|"))
        (setq first-one nil))
      (setq regex
            (concat regex (regexp-quote e))))
    (concat regex "\\)")))

(defun zenith/equation-match (beg end)
  "Check whether `beg' and `end' matches as equation"
  (let ((beg-string (buffer-substring-no-properties beg (min (+ beg 20) (point-max))))
        (end-string (buffer-substring-no-properties (max (point-min) (- end 20)) end))
        ret)
    (dolist (e zenith/equation-env-list)
      (when (and
             (string-prefix-p (car e) beg-string)
             (string-suffix-p (cdr e) end-string))
        (setq ret e)))
    ret))

(defun zenith/cycle-equation ()
  (interactive)
  (if-let* ((regex (zenith/regex-or (append (mapcar 'car zenith/equation-env-list)
                                            (mapcar 'cdr zenith/equation-env-list))))
            (beg (save-excursion (re-search-backward regex nil t)))
            (end (save-excursion (re-search-forward regex nil t)))
            (kind (zenith/equation-match beg end))
            (len (safe-length zenith/equation-env-list))
            (pos (cl-position kind zenith/equation-env-list))
            (next (nth (if (= pos (- len 1))
                           0
                         (+ pos 1)) zenith/equation-env-list)))
      (progn
        (save-excursion
          (goto-char beg)
          (delete-char (length (car kind)))
          (insert (car next))
          (re-search-forward (zenith/regex-or (mapcar
                                               'cdr zenith/equation-env-list)))
          (delete-backward-char (length (cdr kind)))
          (insert (cdr next))))
    (message "No match equation environment found.")))
```

其中 LaTeX-star-environment-dwim 可以为 environment 加上星号，
zenith/latex-toggle-section-with-star 可以使得插入的 section 带上星号。而
zenith/cycle-equation 可以使得公式在三种状态下切换。


## 版本控制 {#版本控制}

Magit 是我见过的最好用的 git 前端，是我离不开 Emacs 的重要理由。同时 Emacs 还有
两个插件 <https://github.com/syohex/emacs-git-gutter> 和
<https://github.com/emacsmirror/git-timemachine> 来进一步强化 Emacs 和 Git 之间的
协作。


## UI {#ui}

我使用了 <https://github.com/seagle0128/doom-modeline> ，总体而言还是非常好用的，
但是必须进行一定的 tweak 否则和 Org-mode 之间会有一定的冲突

```emacs-lisp
;; Redefine `doom-modeline-redisplay' to ignore `doom-modeline--size-hacked-p'
;; to fix the problem caused by reuse of some buffer, for example *Org Tags*
(defun zenith/doom-modeline-always-redisplay ()
  "Check whether this buffer should always display"
  (or (string-equal (buffer-name) " *Org tags*")
      (string-equal (buffer-name) " *Org todo*")))
(defun doom-modeline-redisplay (&rest _)
  "Call `redisplay' to trigger mode-line height calculations.

Certain functions, including e.g. `fit-window-to-buffer', base
their size calculations on values which are incorrect if the
mode-line has a height different from that of the `default' face
and certain other calculations have not yet taken place for the
window in question.

These calculations can be triggered by calling `redisplay'
explicitly at the appropriate time and this functions purpose
is to make it easier to do so.

This function is like `redisplay' with non-nil FORCE argument.
It accepts an arbitrary number of arguments making it suitable
as a `:before' advice for any function.  If the current buffer
has no mode-line or this function has already been called in it,
then this function does nothing."
  (when (and (bound-and-true-p doom-modeline-mode)
             mode-line-format
             (not doom-modeline--size-hacked-p))
    (redisplay t)
    (unless (zenith/doom-modeline-always-redisplay)
      (setq doom-modeline--size-hacked-p t))))
```

除此之外，我对于 hl-line-mode 也进行了一定的定制。由于某些主体 highlight 的颜色
和 Mark 的颜色较为相似，造成分辨上的困难，我通过重定义使得在选择文本时关闭
hl-line-highlight。

```emacs-lisp
;; Redefine `hl-line-highlight' to disable highlight line when selection is
;; active.
(defun hl-line-highlight ()
  "Activate the Hl-Line overlay on the current line."
  (if
      (and hl-line-mode	; Might be changed outside the mode function.
           (not (region-active-p)))
      (progn
        (unless hl-line-overlay
          (setq hl-line-overlay (hl-line-make-overlay))) ; To be moved.
        (overlay-put hl-line-overlay
                     'window (unless hl-line-sticky-flag (selected-window)))
	(hl-line-move hl-line-overlay))
    (hl-line-unhighlight)))
```


## 自动补全 {#自动补全}

自动补全使用的是 <https://github.com/company-mode/company-mode> 和
<https://github.com/sebastiencs/company-box> 。其中的配置可以参考
config/init-company.el 。事实上，在其中我自己实现了一个 company 的模糊匹配但是效
果不让人满意。

另一部分的自动补全是所谓的模板，模板使用的是
<https://github.com/joaotavora/yasnippet>。 同时我自己编写了一个插件实现模板的自动
展开，其要求是前一个单词以 , 开始然后按下空格键。函数会尝试展开，如果展开失败，
那么原封不动，如果展开成功，逗号就会消失。

```emacs-lisp
;; Make yasnippet expandsion easy for me.
(defvar zenith/snippet-prefix ?,
  "The first character of expanding yasnippet")

(defun zenith/may-expand ()
  "Auto expand if the word before the point are started with
`zenith/snippet-prefix'. Return `t' if the expansion is successful
and `nil' otherwise."
  (interactive)
  (let* ((word-end (point))
         (word-start (save-excursion
                       (save-restriction
                         (narrow-to-region (line-beginning-position 0) (line-end-position))
                         (search-backward-regexp "^\\|[[:blank:]]\\|(\\|)\\|\\[\\|]\\|{\\|}" nil t))))
         (word)
         (len))

    (when word-start
      (if (eq (char-after word-start) zenith/snippet-prefix)
          (setq word (buffer-substring-no-properties word-start word-end))
        (setq
         word-start (+ word-start 1)
         word (buffer-substring-no-properties word-start word-end)))
      (when (eq zenith/snippet-prefix (string-to-char word))
        (delete-region word-start (+ word-start 1))
        (if (call-interactively 'yas-expand)
            t
          (setq len (- (length word) 1))
          (backward-char len)
          (insert-char zenith/snippet-prefix)
          (forward-char len)
          nil)))))

(defun zenith/post-command-hook ()
  "Check whether or not to expand after insertion of ~SPC~."
  (interactive)
  (when
      (and
       yas-minor-mode
       (eq last-command 'self-insert-command)
       (eq (char-before) ?\s))
    (delete-backward-char 1)
    (unless (zenith/may-expand)
      (insert-char ?\s)
      (when (boundp company-mode)
        (company-abort)))))

(define-minor-mode auto-expand-mode
  "Minor mode for zenith/may-expand"
  nil nil nil
  (if auto-expand-mode
      ;; Priority of the function should be high enough to run before fill
      ;; column
      (add-hook 'post-command-hook 'zenith/post-command-hook 0 t)
    (remove-hook 'post-command-hook 'zenith/post-command-hook t)))
(define-globalized-minor-mode global-auto-expand-mode auto-expand-mode auto-expand-mode-on)

(defun auto-expand-mode-on ()
  (auto-expand-mode 1))

(global-auto-expand-mode 1)
```


## Ivy-mode {#ivy-mode}

<https://github.com/abo-abo/swiper> ivy, swiper, counsel 是强大的工具是对于 ido 的
加强。<https://github.com/DarwinAwardWinner/amx> 进一步加强了 execute-command。值
得提到的有两点，一是

```emacs-lisp
(defun zenith/open-by-external-program (path)
  "Open file in external program"
  (let ((display-buffer-alist '(("*Async Shell Command*" . (display-buffer-no-window)))))
    (async-shell-command (format "nohup xdg-open \"%s\" >/dev/null 2>&1"
                                 (file-relative-name path default-directory)))))
```

这里个函数在 Linux 中通过系统默认的程序来打开文件。二是

```emacs-lisp
;; https://github.com/tumashu/emacs-helper/commit/1932a9e8a64f08bb9603cf244df41f6c0bbc3dac
;; Search chinese with pinyin
(defun zenith/ivy-cregexp-helper (str)
  (cons (pyim-cregexp-build str) t))

(defun zenith/ivy-cregexp-ignore-order (str)
  (let ((str-list (split-string str)))
    (if str-list
      (mapcar 'zenith/ivy-cregexp-helper (split-string str))
      "")))

(setq ivy-re-builders-alist '((counsel-company . ivy--regex-fuzzy)
                              (t . zenith/ivy-cregexp-ignore-order)))
```

这样就可以在 ivy 的补全中直接使用拼音搜索，非常的好用。（事实上，在 ivy-posframe
中，pyim 莫名地不可用）


## Programming {#programming}

编码主要依赖于<https://github.com/flycheck/flycheck>, 用于进行代码的事实检查。
<https://github.com/manateelazycat/nox> 用于和 LSP Server 通信提供补全跳转等编码体
验，<https://github.com/lassik/emacs-format-all-the-code> 提供代码格式化。同时
<https://github.com/bbatsov/projectile> 提供了项目管理（事实上这一功能我用的比较少）。


## 琐碎 {#琐碎}

show-paren-mode 可以显示配对的括号。recentf 提供访问最近文件的方法。cua-mode 使
得 C-x, C-c, C-v 有和其他软件类似的行为。display-line-number-mode 是高效的显示行
号的方法。 winner-mode 提供对于 window 操作的撤销和重做。undo-tree 提供了非常好
的撤销， <https://github.com/Fuco1/smartparens> 提供括号和命令的补全。
<https://github.com/lewang/ws-butler> 以一种友好的方式去除行末空格。
<https://github.com/abo-abo/ace-window> 提供窗口切换的好方法。rg 提供快速的文本搜
索，和 wgrep 配合提供文本的替换。<https://github.com/raxod502/ctrlf> 增强了 Emacs
自带的搜索，使得行为更加可控。<https://github.com/redguardtoo/wucuo> 提供了快速的
拼写检查。 shackle 提供了对于弹出窗口的控制。
<https://github.com/noctuid/general.el> 提供了绑定快捷键的好方法。
<https://github.com/justbur/emacs-which-key> 提供了探索快捷键的方法。除此之外，我
还自己写了几个函数。

```emacs-lisp
;; Delete word in a more user friendly way
(defun zenith/aggressive-delete-space ()
  "Remove all the space until non-space character."
  (interactive)
  (let ((end (point))
        (begin (save-excursion
                 (re-search-backward "[^ \t\n\r]" nil t))))
    (delete-region (+ 1 begin) end)))

(defun zenith/delete-word-or-space ()
  "Remove all the space until non-space character if the char at
point and before are all space characters and delete word
otherwise."
  (interactive)
  (if (and (zenith/is-space (char-before))
           (zenith/is-space (char-before (- (point) 1))))
      (zenith/aggressive-delete-space)
    (backward-kill-word 1)))
```

zenith/aggressive-delete-space 使得删除词的行为更精细。

```emacs-lisp
;; jump in my way
(defvar zenith/jump-function-alist
  '((org-mode . org-goto)
    (latex-mode . reftex-toc)
    (org-agenda-mode . org-agenda-redo)
    (t . counsel-imenu))
  "The function to call when jump")

(defun zenith/jump ()
  "Jump as `zenith/jump-function-alist' like."
  (interactive)
  (if-let ((func (alist-get major-mode zenith/jump-function-alist)))
      (funcall func)
    (funcall (alist-get t zenith/jump-function-alist))))
```

zenith/jump 提供了浏览文件的统一方法。
