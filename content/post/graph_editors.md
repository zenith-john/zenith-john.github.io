+++
title = "Compare Scapple, CmapTools and yEd Graph Editor"
author = ["Zenith John"]
publishDate = 2021-08-19
categories = ["Essay"]
draft = false
+++

<span class="timestamp-wrapper"><span class="timestamp">[2021-07-05 Mon 17:19]</span></span>
最近在寻找绘制概念图的工具。概念图与思维导图不同，它是无中心的，也就是说它不是从中心发散的网络结构而是一个自然的网络结构。

首先发现的是 [Scapple](https://www.literatureandlatte.com/scapple/overview)。这个软件的优点在于绘图非常自然，比如双击创建图案等，较为人性化。但是由于它箭头的类型较少，同时对于箭头进行标注不是很自然，除此之外，它还缺少其他二者所有的分析的工具。因此首先放弃。（PS:Scapple 付费且只支持 Windows 和 Mac OS）

[CmapTools](https://cmap.ihmc.us/cmaptools/) 是一个专门用于绘制概念图的软件。它有分析关系的功能是最好的，有连接词的概念，同时具有能在不同的概念图中建立关系的能力。但是它在自己指向自己的箭头方面不是很自然（可能设计者不认为会有这种情况出现）。同时它将一个已有的节点变为 Nested Node 并在其中添加内容也不是很方便。CmapTools 的另一个问题是他的搜索功能较弱，不能够查找添加的 information，而只能查找所展示的概念。同时，CmapTools 的大纲也不是非常好用。

[yEd Graph Editor](https://www.yworks.com/products/yed) 是另一个绘制示意图的软件。它对于 CmapTools 的两个问题都有所改进，代价是牺牲了不同概念图之间建立关系的能力和对于谓词的分析能力。它的分析主要是以节点为中心的。它的问题在于不能很好地使用连接多个概念的谓词，需要手动添加节点，而手动添加的节点又往往会使图示不那么清楚。另外由于 yEd Graph Editor 不仅仅是一个概念图软件，因此它可以选择的元素很多，可以用于绘制包括流程图在内的各种图片。

我个人最后选择的是 CmapTools，因为我个人的需求比较单一，而 CmapTools 能最好地满足我的需求。在 CmapTools 之外我偶尔会使用 [Graphviz](https://graphviz.org) 通过编程进行绘图。但 Graphviz 也无法解决多个概念的结合问题同时 Graphviz 绘制的过程中并不直观。
