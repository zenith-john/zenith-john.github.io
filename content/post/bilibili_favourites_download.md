+++
title = "半自动化下载B站收藏夹视频"
author = ["Zenith John"]
publishDate = 2021-08-19
tags = ["Computer"]
draft = false
+++

其实就是使用 js 和大佬写的 [you-get](https://github.com/soimort/you-get) 工具。由于学艺不精（对于前端还有命令行并不了解）只能使用半自动化的方法，希望能够有人提出更好的方案。

1.  首先打开收藏夹，然后打开控制台，使用以下代码获得页面中所有视频的链接。

    ```c
       list = $x("/html/body/div[2]/div[4]/div/\
       div[1]/div[2]/div[3]/ul[1]/li/a[2]")
       myhref = [];
       list.forEach(function(elm){
               myhref.push(elm.href);
           })
    ```
2.  使用你喜爱的编辑器将逗号换成空格。（大概也可以使用命令行实现，但是我不会。）
3.  然后使用 you-get 下载就大功告成了。

PS:由于我是VC爱好者很多时候我关心的并不是视频而是声音。因此需要使用 ffmpeg 工具提取声音。可以使用以下脚本。

```sh
#!/usr/bin/env zsh

for i in *.flv; do
    name=${i:t:r}
    echo $name;
    output="$HOME/Music/Bilibili/$name.mp3"
    if [ ! -f $output ]; then
        ffmpeg -i $i -b:a 128k -vn $output; # 比特率128k
    fi
done
```

注意最好使用 zsh, 因为 bash 对于字符串中的空格似乎有奇怪的处理方式会导致莫名奇妙的问题。[^fn:1]

另外 Markdown 似乎有诡异的设定。如果在一个处在列表中的代码块指定了语言，列表的排序似乎会出现一些奇怪的情况。更多的讨论可见<https://stackoverflow.com/questions/18088955/markdown-continue-numbered-list>

[^fn:1]: 2019-10-20 Update 修改了zsh 的代码，因为在处理文件名时出现了问题。
