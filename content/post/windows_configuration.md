+++
title = "Windows 装机指南"
author = ["Zenith John"]
publishDate = 2021-08-19
categories = ["computer"]
draft = false
showtoc = true
+++

## 常用软件 {#常用软件}

Office: 请卸载 OneNote UWP 版后，重新下载。
In powershell:

```powershell
Get-AppxPackage *OneNote* | Remove-AppxPackage
```

从这里 <https://www.onenote.com/download># 下载

Firefox （也可用 Edge）
<http://www.firefox.com.cn/>
使用全球服务同步,导入 switchOmega 配置
考虑使用 dogedoge 作为搜索引擎

Vscode: R, R lsp client, Remote WSL, Remote ssh

PotPlayer： <http://potplayer.daum.net/> （被墙） <http://www.potplayercn.com/>
Bandzip： <https://www.bandisoft.com/bandizip/>
FoxitReader： <https://www.foxitsoftware.cn/>
Sumatra PDF:  <https://www.sumatrapdfreader.org/download-free-pdf-viewer.html>
使用 <https://www.irfanview.com/> 对 org-download 提供截屏功能。需要手动加入 PATH，同时 irfanview 是非常优秀的图片浏览工具，用于替代默认的图片浏览器。


## 其他软件 {#其他软件}

Nutstore:  <https://www.jianguoyun.com/s/downloads>

Flux: 护眼 <https://justgetflux.com/>
Q-dir: <http://www.softwareok.com/?seite=Freeware/Q-Dir>
FDM: <https://www.freedownloadmanager.org/zh/>
Foobar2000:  <https://www.foobar2000.org/download>
Ditto: <https://ditto-cp.sourceforge.io/>
CopyTranslator: <https://github.com/CopyTranslator/CopyTranslator#tap-to-copyexperimental>
Goldendict: <https://sourceforge.net/projects/goldendict/files/>

Powershell 允许用户脚本

```powershell
set-executionpolicy remotesigned
```

编辑 $PROFILE 文件加入以下代码

```powershell
Import-Module PSReadLine
# zsh-like menu complete, for bash-like use `Complete`
Set-PSReadlineKeyHandler -Key Tab -Function MenuComplete
```

启动脚本，关闭 cmd，使用 vbs

```visualbasic
CreateObject("WScript.Shell").Run "wsl.exe ec", 0, False
```

TeXmacs
<http://texmacs.org/tmweb/home/welcome.en.html>

AutoHotKey
<https://www.autohotkey.com/>
disable.ahk

禁用了 Windows Hotkey.

以下代码禁止锁屏
HKEY\_CURRENT\_USER\Software\Microsoft\Windows\CurrentVersion\Policies\System DisableLockWorkstation 1


## 实用工具 {#实用工具}

Trojan: <https://github.com/trojan-gfw/trojan/releases>
指南见: <https://manateelazycat.github.io/proxy/2020/03/17/best-proxy.html>
Wox: <https://github.com/Wox-launcher/Wox/releases>

考虑使用 <https://github.com/Wox-launcher/Wox/issues/634> 的方法来保存/恢复配置文件
非常好用的启动工具，集成了 Everything，可以在一个界面中同时搜索文件和程序。但是 Clipboard 插件似乎有些一些问题，因此我是用 Ditto 进行替代。

Everything： <https://www.voidtools.com/zh-cn/>
最强大和快速的文件搜索工具，部分可被 Listary 替代，但是 Wox 提供了集成。

Listary: <https://www.listary.com/>
只需要使用免费功能，其中最重要的两个功能：一是增强Windows的搜索功能和文件选择窗口的功能，二是在文件位置选择中用Ctrl-G在定位到资源管理器的位置。付费版较贵，但是很好用。免费版有一些功能缺失。

Directory Opus： <https://www.gpsoft.com.au/>
使用盗版（捂脸），替代 Windows 默认的垃圾管理器。
免费替代：QTTabBar： <http://qttabbar.wikidot.com/>
使用参考： <https://sspai.com/post/52521>
缺少 restore closed tab，和自动保存 tab 的功能。
Windows Terminal Preivew: Windows Store
PowerToys: <https://github.com/microsoft/PowerToys/releases/>
考虑在设置-系统-多任务处理中取消窗口对其显示能在其旁边对齐的内容的选项。使用 PowerToys 进行窗口管理，批量重命名和选取颜色。

Recoll: 官网必须付费，可以找到免费版的下载，根据内容检索文件。

字体: <https://github.com/be5invis/Iosevka> 和 <https://github.com/be5invis/Sarasa-Gothic/releases>

Windows Terminal 设置快捷键和默认打开路径

```js
"startingDirectory": "//wsl$/Ubuntu-20.04/home/zenith-john"
 { "command": { "action": "splitPane", "split": "auto", "splitMode": "duplicate" }, "keys": "alt+shift+d" },
 { "command": { "action": "switchToTab", "index": 0 }, "keys": "alt+1" },
 { "command": { "action": "switchToTab", "index": 1 }, "keys": "alt+2" },
 { "command": { "action": "switchToTab", "index": 2 }, "keys": "alt+3" },
 { "command": { "action": "switchToTab", "index": 3 }, "keys": "alt+4" },
 { "command": { "action": "switchToTab", "index": 4 }, "keys": "alt+5" },
 { "command": { "action": "switchToTab", "index": 5 }, "keys": "alt+6" },
 { "command": { "action": "switchToTab", "index": 6 }, "keys": "alt+7" },
 { "command": { "action": "switchToTab", "index": 7 }, "keys": "alt+8" },
 { "command": { "action": "switchToTab", "index": 8 }, "keys": "alt+9" }
```

Windows sshfs： <https://github.com/billziss-gh/sshfs-win/releases> 和 <https://github.com/billziss-gh/winfsp/releases> 要使用 sshfs.k 作为前缀来使用 .ssh 中的 ip 凭证，但是无法使用 .ssh/config 的配置
使用了新方案<https://www.nsoftware.com/sftp/drive/> 虽然免费版有所不足，但是也比 sshfs 稍好用一些，至少不会弹出链接中断的问题。


## WSL {#wsl}

In powershell

```powershell
dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
```

然后使用 Store 安装 Ubuntu

可以考虑使用 WSL2，首先启用虚拟机平台功能和相关的内核包 <https://docs.microsoft.com/zh-cn/windows/wsl/install-win10#step-4---download-the-linux-kernel-update-package>

```powershell
dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
```

使用

```powershell
wsl --list --verbose
wsl --set-version <distribution name> <versionNumber>
```

来进行 wsl 版本管理。
WSL2 事实上是一个轻量的虚拟机，主要的问题是 WSL2 与 Windows 文件系统的交互速度很慢（远慢于 Linux 下挂载 ntfs 的速度），其原因未知。

WSL X server 设置

```bash
export DISPLAY=$(awk '/nameserver / {print $2; exit}' /etc/resolv.conf 2>/dev/null):0 # in WSL 2
```

Mobaxterm （X410 is good but too expensive, mobaxterm is good enough）
<https://mobaxterm.mobatek.net/>
使用我购买的 X410（Windows Store）.


## VSCode {#vscode}

使得 vscode 在 terminal 中不捕捉 C+e, C+k

```javascript
    {
        "key": "ctrl+e",
        "command": "ctrl+e",
        "when": "terminalFocus"
    },
    {
        "key": "ctrl+k",
        "command": "ctrl+k",
        "when": "terminalFocus"
    }
```

在 terminal 和 editor 之间切换

```javascript
	  {
        "key": "ctrl+'",
        "command": "workbench.action.terminal.focus"
    },
    {
        "key": "ctrl+'",
        "command": "workbench.action.focusActiveEditorGroup",
        "when": "terminalFocus"
    }
```

配置文件地址
%APPDATA%\Code\User
