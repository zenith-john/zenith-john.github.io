+++
title = "Ubuntu 安装后"
author = ["Zenith John"]
publishDate = 2021-08-19
tags = ["Computer"]
draft = false
showtoc = true
+++

## 使用的代理软件 {#使用的代理软件}

v2raya 以及 v2ray-core。具体可以参考 [这篇文章](https://v2xtls.org/v2ray-linux%e5%ae%a2%e6%88%b7%e7%ab%afv2raya%e4%b8%8b%e8%bd%bd%e5%ae%89%e8%a3%85%e5%8f%8a%e4%bd%bf%e7%94%a8%e6%95%99%e7%a8%8b-%e6%94%af%e6%8c%81vmess-vless-ss-ssr-trojan-pingtunnel/)。

同时，为让命令行工具使用代理，我使用的是 privoxy

```bash
apt install privoxy
vim /etc/privoxy/config
```

修改为

```conf
forward-socks5t   /   127.0.0.1:1080 .
listen-address  127.0.0.1:8118
```

注意 . 不可省略。

在 zsh 配置文件中加入

```sh
# proxy setting
alias proxyon="export http_proxy='http://127.0.0.1:8118'; export https_proxy=$http_proxy"
alias proxyoff="unset http_proxy; unset https_proxy"
```

然后就可以使用这两个命令来临时开启、关闭代理。


## 软件包安装 {#软件包安装}

安装 git, zsh, rust, find-fd, ripgrep, cmake, make, autoconf 等软件, 编译 emacs-28 --with-modules --with-native-comp, 在此过程中需要添加大量的包,包括 jansson, jpeg, png, tiff, xpm, gnutls, gtk3,libvterm, libtool 等, 还需要安装 rcm

```bash
apt install git rcm zsh lua5.3 fd-find ripgrep cmake autoconf libjansson4 libjansson-dev libjpeg-dev libpng-dev libtiff5 libtiff5-dev libgtk-3-0 libgtk-3-dev libvterm0 libvterm-dev libtool libxpm4 libxpm-dev libgnutls28-dev libgif7 libgif-dev  libncurses-dev texinfo clang libclang-dev  librime librime-dev libgccjit0 libgccgit-10-dev

apt install zathura

# git clone 最好在代理配置后进行
git clone https://github.com/zplug/zplug .zplug

git clone git@github.com:zenith-john/dotfiles.git .dotfiles
rcup
git clone git@github.com:zenith-john/Notes.git
git clone git@github.com:zenith-john/zenith-emacs.git
ln -s zenith-emacs .emacs.d

git clone https://github.com/emacs-mirror/emacs --depth=1
```

在安装完 zsh 后，使用 chsh 命令将 login shell 转化为 zshell。

在 .emacs.d 的 README.md 中可以看到具体的 emacs 配置的安装方法。

Trojan 需要版本 1.14 否则可能有一些问题。（Trojan 已经无法使用了。）

安装 rust

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

然后可以使用 rust 安装 sd。

```bash
cargo install sd
```


## 安装一些应用软件 {#安装一些应用软件}

-   [Zotero](https://www.zotero.org/)
-   [Joplin](https://joplinapp.org)
-   [坚果云](https://www.jianguoyun.com/)

安装 jumpapp

```bash
git clone https://github.com/mkropat/jumpapp.git
cd jumpapp
make && sudo make install
```

```bash
apt install flameshot juk goldendict latte-dock fsearch xbindkeys fcitx5 fcitx5-rime rofi
```

将 rime 配置文件，放入 ~/.local/share/fcitx5/rime/

为了使用 mu4e 必须编译安装 [mu](https://www.djcbsoftware.nl/code/mu/)，这一过程也比较复杂，请按照需求安装软件包，并完成编译。


## 杂项 {#杂项}

1.  KDE 的快捷键设置和虚拟桌面。将 .local/bin/zstart 加入启动项。将 CapsLock 换为 Ctrl。
2.  修改 /etc/fstab 来进行自动挂载 windows 的几个磁盘，以下是案例。

    ```conf
       /dev/nvme0n1p3	/media/C	ntfs	defaults	0	1
    ```
3.  加入 okular-unique 这一 script 来弥补 okular open in tab 的不足，然后使用 mimeopen -d 来切换默认的打开程序为 okular-unique

    ```bash
       #!/bin/sh
       jumpapp okular
       okular $1
    ```


## clang 找不到标准库头文件错误 {#clang-找不到标准库头文件错误}

由于 clang 会找 gcc，g++ 版本最高的 headers，因此有时 clang 会找不到头文件，因此需要安装新版本的 gcc。


## Sshfs {#sshfs}

Example: bash

```nil
sshfs -o follow_symlinks,idmap=user zhangnt20@101.6.120.15:/home/zhangnt20 -p 5003 ~/remote_home
```


## Webcal {#webcal}

将 webcal:// 换为 <http://> 直接使用 wget 下载为 ics， 然后使用 ics2org.awk 脚本处理。


## 使用 Gnome {#使用-gnome}

```sh
apt install vanilla-gnome-desktop gnome-tweak-tools
```

由于我使用的部分软件需要 X，因此，我还是在 Xorg 中使用 Gnome。可以使用 firefox 的 app 来安装 appindicator， dash-to-dock， clipboard 三个 extensions。也需要和 KDE 一样对虚拟桌面和快捷键进行设置。

切换到 Gnome 的主要原因是 KDE 的 notfiy-send 的 notification 无法存留在 nofication center 中，而 gnome 可以。不知道是特性还是功能的问题。由于我使用 org-mode 管理日程，因此这个提醒对我来说还是比较重要的，因此我切换到了 gnome 中。

我们可以使用 kvantum 来对 QT 的应用进行 appearance 的修饰使得和 gtk 的应用更相似。

```sh
sudo apt install qt5-style-kvantum qt5-style-kvantum-themes
echo "export QT_STYLE_OVERRIDE=kvantum" >> ~/.profile
```

可以使用以下的命令，禁用 Win 的 activity 效果

```sh
gsettings set org.gnome.mutter overlay-key ""
```

在 Gnome 使用过程中，发现 xbindkeys 的部分快捷键不能正确作用。我们使用

```sh
(for schema in $(gsettings list-schemas); do gsettings list-recursively $schema; done) | grep '<Super>'
```

来找到有问题的快捷键被哪个东西占了，然后使用

```sh
gsettings set org.gnome.settings-daemon.plugins.media-keys rotate-video-lock-static \[\'XF86DRotationLockToggle\'\]
```

来取消绑定，这个快捷键就能够正常使用了。

使用 ibus-rime 来进行中文输入

```sh
apt install ibus-rime
```

为使 ibus-rime 横排显示需要在 ibus-rime.yaml 中加入

```yaml
style:
   horizontal: true
```

同时需要修改 .profile

```sh
export GTK_IM_MODULE=ibus
export QT_IM_MODULE=ibus
export XMODIFIERS=@im=ibus
```


## KDE connect and GSconnect {#kde-connect-and-gsconnect}

GSConnect 是 Gnome 的一个 Extension 与 KDE connect 一样，其安卓 app 利用的就是 KDE connect 的 app。使用他就可以非常方便的进行手机和电脑的互操作。Enjoy!


## 无法 hibernate {#无法-hibernate}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-14 Sat]</span></span>
在 Linux 中，进行 Hibernate 较为复杂，主要参考的是 <https://blog.ivansmirnov.name/how-to-set-up-hibernate-on-ubuntu-20-04/> 。我使用的是 swapfile 首先需要将 \\/swapfile 扩大。可以参考的命令是

```sh
swapoff
dd if=/dev/zero of=/swapfile bs=1M count=$((SIZE*1024))
mkswap /swapfile
swapon /swapfile
```

之后可能需要更改一下 /etc/fstab， 通过以下命令来获得 swapfile 的 UUID 和 offset。

```sh
RESUME_PARAMS="resume=UUID=$(findmnt / -o UUID -n) resume_offset=$(sudo filefrag -v /swapfile|awk 'NR==4{gsub(/\./,"");print $4;}') "
```

更新 grub 以及 Linux-kernel 镜像就完成了，将上述的变量的字符串加入 /etc/default/grub 文件，中的 GRUB\\\_CMDLINE\\\_LINUX\\\_DEFAULT ，例如

```conf
GRUB_CMDLINE_LINUX_DEFAULT="quiet splash resume=UUID=18ec5634-548e-40ef-8629-aca25a6eeb00 resume_offset=18003967"
```

然后将 RESUME\_PARAMS 写入 /etc/initramfs-tools/conf.d/resume。之后运行

```sh
update-initramfs -c -k all
```

这样 hibernate 应该能正常进行了。

如果还有问题，可以使用以下的命令来对 hibernate 的问题进行调试了

```sh
journalctl -xe
dmesg | less
vim /var/log/pm-suspend.log
systemctl status hibernate
```

同时由于 Lenovo 的问题，因此，我们 ELAN touchpad 被错误地认为了 touchscreen。我们要解决这个问题，可以使用 systemctl 的 service。参考 <https://bugzilla.kernel.org/show%5Fbug.cgi?id=207759#c17>

```sh
#!/bin/bash
modprobe i2c_hid
echo "i2c-ELAN0001:00" > /sys/bus/i2c/drivers/elants_i2c/unbind
echo "i2c-ELAN0001:00" > /sys/bus/i2c/drivers/i2c_hid/bind
```

以及

```conf
[Unit]
Description=Move touchscreen to correct driver

[Service]
ExecStart=/etc/tsmove
Type=oneshot
RemainAfterExit=yes

[Install]
WantedBy=multi-user.target
```

然后使用了

```sh
systemctl enable touchscreen
systemctl start touchscreen
```

来解决这个问题，但是即使这样，但是由于在开机的过程中，这个错误的程序是无法加载的，因此也就会导致存储的文件无法正常使用，因此也就无法使用 hibernate 了。


## Ubuntu 安装 deepin-wine {#ubuntu-安装-deepin-wine}

来自：<https://zhuanlan.zhihu.com/p/341481469>
系统：Ubuntu 20.10

今天使用Ubuntu，想安装一下deepin的qq，在网上找到以下方法：

```sh
wget -O- https://deepin-wine.i-m.dev/setup.sh | sh
```

正常执行

```sh
sudo apt-get install com.qq.im.deepin
```

报错：

下列软件包有未满足的依赖关系：
 libgirepository-1.0-1 : 破坏: python-gi (< 3.34.0-4~) 但是 3.30.4-1 正要被安装
E: 无法修正错误，因为您要求某些软件包保持现状，就是它们破坏了软件包间的依赖关系。

我试着安装python-gi，同样报错，我又试着删了libgirepository-1.0-1，但是他是很多包的依赖，不敢删。

百度搜索无果，bing搜索外国也没找到解决办法，倒是有人遇到了同样的问题。

在ubuntu搜集信息后，发现libgirepository-1.0-1依赖于libffi7，但是apt下载不到他，只能去<https://packages.ubuntu.com/zh-cn/focal/libffi7> 手动下载。安装完后又去<https://packages.ubuntu.com/zh-cn/focal/python-gi> 手动下载python-gi，先后安装成功。

再次安装qq，重启，安装成功。

但是发现字体显示不全。找了个网站下载了simsun.ttc，放到 ~/.deepinwine/Deepin-QQ/drive\_c/windows/Fonts/

问题解决。

PS:注意 deepin-wine 是无法使用摄像头的。
