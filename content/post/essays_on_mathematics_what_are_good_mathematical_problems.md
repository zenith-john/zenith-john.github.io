+++
title = "数学随笔：什么是好的数学问题"
author = ["Zenith John"]
publishDate = 2023-03-23
tags = ["Essay", "Mathematics"]
draft = false
lastmod = 2023-03-23
+++

## 前言 {#前言}

什么是一个好的数学问题与其说是一个客观的问题，不如说是对于数学的美学的观点的提问。在此仅仅提出我个人的一点浅薄的想法，供大家参考批判。本文中除了探讨什么是好的数学问题外，还对爱因斯坦的名言“提出一个问题往往比解决一个问题更为重要”进行了批判。


## 什么是好的数学问题 {#什么是好的数学问题}

在此我再次引用一下 Charles Fefferman 的话

> Mathematics at the highest level has several flavors. On seeing it, one might say
>
> 1.  What amazing technical power!
> 2.  What a grand synthesis!
> 3.  How could anyone not have seen this before?
> 4.  Where on earth did this come from?

虽然它是对于数学的一个总结，并非专门探讨数学问题，但是用于数学问题的好坏上也可以进行参考。个人认为这四点在数学问题上可以理解为以下四点

1.  启发了数学研究的新的技术。
2.  联系了不同的数学领域。
3.  对解决其他问题有重要价值。
4.  解释特殊的数学现象

而在这四点之外，我也想要提出新的一点：

<ol class="org-ol">
<li value="5">数学研究中自然产生的问题。</li>
<li>来自现实世界的数学问题。</li>
</ol>

当然一个好的数学问题不是说一定要同时具备以上六点，但是多多少少能够在这六点之中找到些许的痕迹。我将从第五点开始对于这些特点逐一进行一些分析。


## 数学研究中自然产生的问题 {#数学研究中自然产生的问题}

什么样的问题是数学研究中自然产生的呢？我认为以下的一些种类是比较具有代表性的

1.  存在性问题。如费马大定理。
2.  唯一性问题。如微分方程解是否唯一。
3.  分类问题。如有限单群的分类。
4.  相容性问题。如连续统问题。

这四类问题都很容易理解。相对来说可能第四类问题基本上属于数理逻辑的领域，而远离现代数学的主流。而前三类都可以举出很多很多的例子。毕竟在数学中我们可以构造出各种各样的对象，如代数对象、几何对象、方程等等。而对象的存在性就是第一个需要解决的问题。以抽象代数举例，如果不存在群，那就没有必要研究群。而如果一个对象存在，那么就会有自然的问题，这样的对象唯一么？如果不唯一，那么它能否被分类呢？

在这里我们第一次看到了 **解决问题** 的重要性，如果没有对于存在性问题的解决，那么唯一性和分类问题都无从谈起。而在解决分类的问题中，一个非常常见的情况是，我们发现我们最初的对象是无法被分类的。比如我们不可能分类所有的群。但是我们就可以继续追问，有限群能否被分类呢？事实上也是不行的，但是我们可以找到有限群的结构定理，告诉我们任意的有限群可以在一定的意义下被分解为某些单位，即有限单群。而通过几代人的努力我们终于有了有限单群的完整分类。在这个例子中，我们就会发现，有一些问题不是一下子就出现的，而是在解决问题的过程中，逐步被揭示出来的。

再举一个例子，就是代数簇的双有理分类，极小模型纲领（minimal model program）。它本质上是要在双有理等价下，给出代数簇的分类。而在每一个等价类下有一个唯一的代表元，叫做极小代数簇，因此这一领域叫做极小模型纲领。在一维时这个问题是容易的，在二维时也并不太复杂，但是到了三维以上时这个问题就超出一般人想象的复杂了。其中一个重要的化归步骤是奇点消解，在特征0的情况下，Hironaka 于1964年给出了奇点消解的一般情况的证明。这说明任意代数簇都可以双有理等价为一个光滑的代数簇。为了说明这一步是多么不平凡，只需要指出 Hironaka 凭借这一工作获得了 1970 年的菲尔兹奖或许就足够了。

> Heisuke Hironaka 的菲尔兹奖颁奖辞：
> Generalized work of Zariski who had proved for dimension ≤ 3 the theorem concerning the resolution of singularities on an algebraic variety. Hironaka proved the results in any dimension.

但是仅仅化归到光滑代数簇还是远远不够的，而其中最重要的突破由另一位日本数学家 Mori 给出，因此有的人会把现代的极小模型纲领，叫做 Mori's program。

> Shigefumi Mori 菲尔兹奖颁奖辞：
> The most profound and exciting development in algebraic geometry during the last decade or so was [...] Mori's Program in connection with the classification problems of algebraic varieties of dimension three. Early in 1979, Mori brought to algebraic geometry a completely new excitement, that was his proof of Hartshorne's conjecture.

通过对于 3 维的情形的精细研究， Mori 发现原有的对于曲面而言可行的极小代数簇的定义变得不够用了。他发现如果采用原来的定义，那么一个代数簇所对应的极小代数簇并不是唯一的。为了使得在每一个双有理等价类有着唯一的代表元，需要在代表元上引入奇点，并得到典范模型。他证明了关于 flip 和 flop 的一系列定理并由此得到了对于 3 维代数簇的完整分类，并为更高维的情形勾画了蓝图。他的发现也使得奇点理论自然地进入了双有理几何之中，从而产生了很多新的问题，并引导了双有理几何的发展。我们再一次看到，如果没有 Hironaka 和 Mori 的工作，我们就不会发现我们最初的问题其实是存在一定问题，也不能正确地提出更高维数下的类比。这再一次说明了解决问题的重要性——在解决问题的过程中，我们才能够提出更多更好的问题。


## 来自现实世界的问题 {#来自现实世界的问题}

数学来自现实世界，整数来自于人计数的需要，实数是为了描述一些连续的事物的需要，虚数来自于方程的解，几何来自于对于土地的面积的计算，代数来自于对于方程可解性的研究。即使现在数学似乎已经离现实越来越远了，但是现实的问题始终在数学中有所回响。在我看来三个现实的领域是数学问题的重要来源：

1.  物理学。如 Navier-Stokes 方程。
2.  计算机。如密码学，数值分析，人工智能。
3.  统计学。
4.  博弈论。
5.  运筹学。

必须要注意到牛顿对于微积分的发明主要是为了解决他的物理学问题。而微分方程这一领域自诞生开始就和物理学息息相关。数学家可以随手写出无数个微分方程，可以比 Navier-Stokes 方程更复杂，但是却并不是每一个方程都如此的重要，因为不是每一个方程都有着现实的意义。比如 Einstein 方程，这些来自于物理的方程就是很好的数学问题。当然，如同牛顿并没有将微积分严格化一样，现在我们似乎面临着一个相似的境地，即不严格的路径积分，已经成为了物理学研究的重要工具，但是数学上我们却无法严格的定义它。我相信路径积分的严格化，虽然现在还没有什么进展，是一个重要的数学问题。而通过路径积分，物理学家已经提出了很多数学上的预言，对于这些预言的验证或许也是一些非常好的问题。一个重要的代表人物自然是 Witten。

> Edward Witten 的菲尔兹奖颁奖辞：
> Time and again he has surprised the mathematical community by a brilliant application of physical insight leading to new and deep mathematical theorems.

当然还有 Smirnov，Duminil-Copin 等人对于统计物理的研究。这些研究的模型都来自于一些物理学的问题，但是在这些物理问题的解决的背后依然是深刻的数学。

> Stanislav Smirnov 菲尔兹奖颁奖辞：
> For the proof of conformal invariance of percolation and the planar Ising model in statistical physics.
>
> Hugo Duminil-Copin 的菲尔兹奖颁奖辞：
> For solving longstanding problems in the probabilistic theory of phase transitions in statistical physics, especially in dimensions three and four.

而在物理学之外，另一个重要的现实问题就是计算机相关的数学问题。无论是通信加密，还是对于方程数值解的分析，还是如何对于人工智能进行优化都是非常重要而且现实的数学问题。如何设计出更快更好的算法，如何在数学上去理解深度学习为何如此高效，当然还有 P=NP 之类的理论计算机问题，都是非常有趣而且有意义的数学问题。而这一方向上的研究也越来越受到数学家们的重视，比如 2021 年的阿贝尔奖就颁给了两位计算机科学家，László Lovász 和 Avi Wigderson。

> 2021 年阿贝尔奖颁奖辞：
> For their foundational contributions to theoretical computer science and discrete mathematics, and their leading role in shaping them into central fields of modern mathematics

统计学、博弈论和运筹学我并不算了解，在此就不展开了。

这些来自现实的问题的重要性在于它们能够很直接地帮助我们更好地理解现实世界，并帮助我们改造世界。事实上有不少的重要的数学家在这方面有着杰出的工作。


## 启发了数学研究的新的技术 {#启发了数学研究的新的技术}

有很多的数学问题启发了新的数学研究的技术，比如 Calabi 猜想，比如费马大定理。但是必须要指出的是，这一特点很难被看作是问题的内蕴的特点。换句话说，你不能通过对于问题的观察就发现这一问题的研究需要使用什么样的技术来解决。当然，如果一个问题足够老，还没有被解决，那么对于它的解决很可能是需要新的技术的。

不过在这里也可以举一个有意思的例子，即 Witten 猜想。Witten 根据 2 维量子引力猜测，曲线模空间上的相交数的生成函数满足一个可积系统。而这一猜想最初由 Kontsevich 通过矩阵模型和模空间的 ribbon graph 分层来证明。

> Maxim Kontsevich 的菲尔兹奖颁奖辞：
> For his contributions to algebraic geometry, topology, and mathematical physics, including the proof of Witten's conjecture of intersection numbers in moduli spaces of stable curves, construction of the universal Vassiliev invariant of knots, and formal quantization of Poisson manifolds

但是，之后 Mirzakhani 又通过双曲几何的方法给出了一个新的证明。这个故事有趣的地方在于，Mirzakhani 最初的目标并不是为了解决 Witten 猜想，而是为了研究曲线上长度又上界的简单测地线数量的渐进行为，并通过对于后一问题的研究积累了一系列的技巧方法，并在过程中给出了 Witten 猜想的新的证明。而她的技巧方法之后被用到了很多其他问题的研究之中。这也是对于问题的研究给出了新的技术的例子。

> Maryam Mirzakhani 的菲尔兹奖颁奖辞：
> For her outstanding contributions to the dynamics and geometry of Riemann surfaces and their moduli spaces.


## 联系了不同的数学领域 {#联系了不同的数学领域}

对于联系不同的数学领域的最重要的例子或许就是 Langlands 纲领。它将 Galois 表示和自守表示联系起来，将调和分析，自守形式，L-函数，数论等领域联系起来。但是必须要指出的是 Langlands 对于 Langlands 纲领的发现同样是基于他对于自守形式的研究的，而不是仅仅出于对于 Artin 互反律的类比。事实上，Artin 互反律是一个相对老的结果，一定是有无数人看过这个结果的，但是他们并没有想 Langlands 一样找到合适的推广，这是为什么呢？因为 **提出问题必然是要在解决问题的基础上的** ，如果没有 Langlands 自己对于一些自守形式的计算，他也无法观察到这些领域之间的微妙的联系，从而提出他的宏大猜想。

> Robert Langlands 的阿贝尔奖颁奖辞：
> For his visionary program connecting representation theory to number theory.

而在几何上，这样的例子也有很多，比如包括 Yau-Tian-Donaldson 猜想（定理），Simpson 对应在内的一系列微分-代数几何对应，说明了代数对象和分析对象之间的深刻联系。而通过两者之间的对应，我们能够更好地构造模空间，为理清它们的性质提供基础。


## 对解决其他问题有重要价值 {#对解决其他问题有重要价值}

在这里最著名的例子莫过于黎曼猜想了。黎曼猜想对于解析数论中的众多问题的解决具有重要的意义和价值。据称，已经有 1000 条以上的数学命题是建立在黎曼猜想的基础之上。而另一个著名的猜想就是 ABC 猜想。这些猜想都已经悬而未决很久了，毫无疑问，它们是数论中的核心问题，有助于我们理解素数分布和丢番图方程，但是目前来看我们距离这些猜想还有些遥远。望月新一提出了一系列的理论来试图解决 ABC 猜想，但是他的证明被认为是有错误的。不过这也能够看出，这些老而弥坚的问题的解决是促进数学的新技术发展的重要动力。

另一个系列重要的问题就是猜想的类比，比如黎曼猜想在有限域上的类比，Langlands program 在有限域上的类比。虽然现在看来，这些类比还不足以对于数域上的情况的证明提供帮助，但是确实为数域上的情形成立的可能提供了佐证。而这些问题的解决也被认为是数学的重要进步，比如 Deligne 因为解决有限域的黎曼假设，Drinfeld，Lafforgue 证明了特征 p 下部分 Langlands 对应而获得了菲尔兹奖。

> Pierre Deligne 菲尔兹奖颁奖辞：
> Gave solution of the three Weil conjectures concerning generalizations of the Riemann hypothesis to finite fields. His work did much to unify algebraic geometry and algebraic number theory.
>
> Vladimir Drinfeld 菲尔兹奖颁奖辞：
> Drinfeld's main preoccupation in the last decade [are] Langlands' program and quantum groups. In both domains, Drinfeld's work constituted a decisive breakthrough and prompted a wealth of research.
>
> Laurent Lafforgue 菲尔兹奖颁奖辞：
> Laurent Lafforgue has been awarded the Fields Medal for his proof of the Langlands correspondence for the full linear groups GLr (r≥1) over function fields of positive characteristic.


## 解释特殊的数学现象 {#解释特殊的数学现象}

在数学中我们经常发现一些相同的数字、函数、关系全然不同的数学对象中出现。如何说明这种吻合，就是一个极好的数学问题。比如 Monstrous Moonshine 就是 Conway-Nortan 提出的联系模形式 j-invariant 的系数和 最大的有限单群的 Monster 群的不可约表示的维数的关系。再次强调如果没有对于之前对于有限单群的重要的分类工作，那么即使是提出这一猜想也是不可能的任务。而 Borcherds 最后通过对于物理中 2 维共形场论的公理化构造提出了顶点算子代数，并通过顶点算子代数的表示将模形式和有限单群的表示联系了起来，并以此证明了 Monstrous Moonshine 猜想。如何将看似巧合的相同或相近联系起来，是一个深刻而优美的数学问题。

> Richard Borcherds 的菲尔兹奖颁奖辞：
> For his contributions to algebra, the theory of automorphic forms, and mathematical physics, including the introduction of vertex algebras and Borcherds' Lie algebras, the proof of the Conway–Norton moonshine conjecture and the discovery of a new class of automorphic infinite products.


## 尾声 {#尾声}

在本文中，我探讨了一些好的数学问题的特点。同时，正如我不断强调的那样，提出问题和解决问题是一个相互促进的过程，数学的发展是在两者之间来回摇摆，螺旋上升的。如果忽视了解决问题的技巧，那么提出好的问题也将是非常困难，甚至不可能的。尤其是在现在的大环境下，各种好的问题层出不穷，强有力的技巧便显得更为重要了。事实上，并不是所有的重要数学发现都是在“好”的问题的指引下发现的，Gromov 提出伪全纯曲线的工作无疑是非常重要而杰出的工作，但是背后指引它的问题却未必是一个特别有名的“好”的问题。数学的进展并不是按部就班的，而是充满意外的，即使是在冷僻的小径上，又是也能发现意想不到的风景。

> Mikhail Gromov 阿贝尔奖颁奖辞：
> For his revolutionary contributions to geometry.
