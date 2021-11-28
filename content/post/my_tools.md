+++
title = "我的工具"
author = ["Zenith John"]
publishDate = 2021-08-19
tags = ["Computer"]
draft = false
+++

## Manjaro Linux {#manjaro-linux}

目前我使用的发行版是Manjaro Linux，这个发行版基于 Arch 但是有图形化的安装界面对于新手更加的友好。使用这个发行版的好处是有大量的软件可以使用，其数量甚至超过 Ubuntu PPA，而且软件的更新速度非常快。当然也有很多不好的地方，不如很多软件包是个人维护的，最后可能就没人维护了。这种事情也常常发生。更新速度太快也可能会导致一些软件的 bug 被推送，比如我个人遇到过 ripgrep 的 bug。不过我个人的体验还是非常满意的，它的优点大大超过了它的缺点（做为桌面系统）。当然，我有了清华的源 <https://mirror.tuna.tsinghua.edu.cn/> 来加快速度。


## KDE {#kde}

目前我使用的桌面环境是KDE，最开始转到KDE的原因是为了使用大佬的[Emacs Application
Framework](https://github.com/manateelazycat/emacs-application-framework)，但是经过一段时间的使用后发现还是不太适合我个人的工作流，因此就放弃了。
但是在使用的过程中也发现了KDE环境有很多的优点，因此就一直使用了下来。使用平铺式
桌面环境的一个痛点在于很多软件的设计对于平铺桌面非常不友好。在KDE中可以避免这一
个烦恼。

对于我个人而言比较重要的配置有以下几点：

1.  选择一个你比较喜欢的主题和图标，我个人的选择是 Breeze Dark，和它配套的图标。
2.  选择字体，我使用的是 Source Han Sans CN
3.  关闭一些不必要的桌面动画，比如切换虚拟桌面的动画，因为我经常切换虚拟桌面因此
    动画会让我感到厌烦。
4.  将虚拟桌面数量固定为4。选择4这个数字是因为我的键盘只有左Windows，因此同时按
    Windows 和 4 就已经比较极限了。同时4个虚拟桌面的数量已经足够满足我的个人需求。
5.  开机自启动。我有一个 zstart 程序来进行我需要的开机自启动。
6.  键盘设置。使得 Caps Lock 变为 LControl。使用 Emacs 的都懂。通过 xcape 进行更
    多的设置，在 zstart 中更多地进行介绍。
7.  关闭 File Search。这点非常重要，由于KDE的文件搜索缓存引擎 Baloo 对于非拉丁语
    系的支持非常不好，如果不关闭在搜索中文时就会一无所获，因此必须进行关闭。
8.  设置快捷键。这点对我而言非常重要。我会选择直接覆盖默认的快捷键。Win + num，切
    换虚拟桌面。 Win + Shift + num，移动窗口到虚拟桌面。 Win + m，最小化。 Win +
    0，最大化。 Win + i,o,k,l,u,y，分别打开 Firefox, Okular, Konsole, Dolphin,
    Emacs, Zathura。这一点在 wmctrl 中会进一步介绍。 Win + p，运行命令 rofi -modi
    combi -combi-modi window,drun -show combi。而 Windows 键可以运行我自己的脚本
    [ZSelectWindow](https://github.com/zenith-john/ZSelectWindow)。Win + Left, Right，将窗口分配到左右半屏。Win + Up, Down，将桌面
    分配到右上角，右下角。 Win + Shift + q 关闭窗口。
9.  KDE widget, global menu 类似 Mac 的效果使得软件有更好的体验，遗憾的是并不是所
    有的软件都支持，如 Firefox(但是可以通过 firefox-ubuntu-bin 获得)。


## KDE系软件 {#kde系软件}

相比于 Gnome 而言确实 KDE 系的软件要好看不少。我个人比较常用的有以下几个：

1.  Konsole. 终端，使用内置的 Breath2 theme，同时使用字体 Source Code Pro 并开启
    无限滚动，用了这个之后我就不再用 Tmux，通过 Control-Shift-C/V 进行复制粘贴非
    常方便。当然也要对于快捷键进行一定的设置。
2.  Okular. Pdf, dvi 等文件的查看器。同时备注功能较为强大，但是选择文本的交互总是
    让我感觉很难受，而且 Open in Tabs 在不同虚拟桌面中有问题。需要将以下文件放入
    desktop 文件夹中，然后用 mimeopen 将默认程序设为这个。（依赖于 wmctrl）
3.  Dolphin. 文件管理器，可以选择单模式。
4.  Juk. 音乐播放器，和 KDE 整合较好。
5.  KOrganizer. 和 Org Agenda 配合使用，通过读取 iCalendar 文件提供日程提示。
6.  Latte Dock. Mac-like Dock. 可以自动隐藏，放于桌面左侧。

<!--listend-->

```c
[Desktop Entry]
MimeType=image/vnd.djvu;image/vnd.djvu+multipage;application/epub+zip;application/x-mobipocket-ebook;application/pdf;application/x-gzpdf;application/x-bzpdf;application/x-wwf;
Terminal=false
Name=Okular_Unique
GenericName=Document Viewer
Comment=Universal document viewer
Exec=okular-unique %U
Icon=okular
Type=Application
InitialPreference=8
Categories=Qt;KDE;Graphics;Viewer;
X-KDE-Keywords=PDF, Portable Document Format
NoDisplay=true
```


## 其他软件 {#其他软件}

1.  Firefox / Chrome. 网页浏览，必须要有的插件是广告拦截 （我用的是 uBlock origin，
    注意要开启 Filter Lists/Regions,Languages/CHN) 和 Auto Switch。
2.  Goldendict. 英语词典，可以自己添加词典，我使用的是网上下载的，常用的包括 New
    Oxford English-Chinese Dictionary，牛津高阶学习词典（OALD）,牛津英语搭配词典，
    USE THE RIGHT WORD, WordNet 3.0 等。
3.  Zeal. 文档查询，与 Mac 的 Dash 相似。（实际上使用的就是相同的词典）
4.  Mega / Nutstore. 云盘用于同步，我用 Mega 同步较大量的文档，通过 Nutstore 同步
    一些较小的配置。
5.  ZClock. 我个人编写的一个闹钟，每隔一段时间放音乐，提示你应该休息了。[ZClock](https://github.com/zenith-john/ZClock)
6.  Thunderbird. 邮件管理。尝试过使用 Emacs 进行管理，但是弄不好多邮箱配置最后放
    弃了。
7.  Emacs. 之后细讲。
8.  QT Creator. 用于开发 QT Application。虽然实际上我只写了一个 ZClock。
9.  fcitx, rime. rime 输入法，你值得拥有。
10. Zathura. 另一个 pdf 查看器，小巧，快速，用于与 latex 相配合。
11. Zotero 联合 Firefox 插件进行文献管理。
12. flameshot。一个有用的截屏软件。
13. psensor 一个监控 cpu 的软件。
14. fsearch Linux 下的 Everything。


## 命令行程序 {#命令行程序}

1.  wmctrl. 非常重要的命令行程序，通过它可以实现 RaiseOrRun 的效果，即 wmctrl
    -x -R 'class\_name' || appname，其中 class name 可以通过 xprop 获得。
2.  git. 版本控制不用多说了。
3.  vim. 快。
4.  trojan. 详见<https://manateelazycat.github.io/proxy/2020/02/10/trojan.html>
5.  rcm. 用于管理小的配置文件，比如 .zshrc 等。可以通过 mkrc 将文件搜集到
    ~/.dotfiles，并通过 rcup 进行恢复，而收集后的文件就可以通过 git 进行管理。
6.  texlive. 对于学术工作者而言非常重要。注意使用网上的脚本
    latexindent-module-installer 进行必要的安装使得 latexindent perl 脚本可用。
7.  ripgrep. 快速的 grep，同时与 Emacs 等软件配合。
8.  zsh. 更加好用的 shell。可以参考我的 zshell 配置，并不是非常复杂。 其中 z.lua
    使你可以快速地在文件夹间穿梭。
9.  fd. 快速的 find.
10. fzf. 命令行结果选择工具，可以用于搜索历史等，非常方便。
11. ZSelectWindow. 严格来说，它并不是命令行工具，它可以实现类似 Emacs 中 Avy 的
    效果来切换窗口。不足之处是由于使用 python 编写速度不是很快。
12. xcape. 另一个非常重要的程序，通过处理 X Windows 的指令使得键盘更加好用。我添
    加的设置有将单击 Caps Lock 设置为 Escape，将单击 Alt\_R 设置为 Ctrl + X，将单
    击 Shift\_R 设置为 Ctrl + C，将单击 Windows 设置为快捷键然后连接到
13. pyenv. python 版本控制，非常不友好，几乎废弃。
14. nvm. node.js 版本控制。
15. you-get 用于下载视频。参考[半自动化下载B站收藏夹视频]({{< relref "bilibili_favourites_download" >}})
16. atool 通用解压工具。
17. sd <https://github.com/chmln/sd> sd 是 sed 的 Rust 替代品，提供了更为简单和符合直观的参数。


## Python 相关 {#python-相关}

1.  black. 文件格式化程序，确保你的代码规范。
2.  magic-import. 智能 import.
3.  python-language-server. <https://github.com/microsoft/python-language-server>,
    编译指令，当然因此我也需要 dotnet

<!--listend-->

```bash
cd python-language-server/src/LanguageServer/Impl
dotnet publish -c Release -r linux
```


## C/C++ 相关 {#c-c-plus-plus-相关}

1.  cmake. C++ 构建工具。
2.  ccls. C++/C language server。
3.  clang. 其中 clang-tidy 用于查错，同时 clang-format 用于格式化代码。个人偏向于
    使用 microsoft 格式，但是将缩进改为 4。
