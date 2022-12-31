+++
title = "几何 IV：几何作为桥梁"
author = ["Zenith John"]
publishDate = 2022-12-31
tags = ["Essay", "Mathematics"]
draft = false
+++

## 前言 {#前言}
本章将会介绍几何学是如何作为桥梁广泛地影响其他数学分支的。本章的标题也可以改为“几何作为工具”，但是我认为工具一词矮化了几何学在这些领域中的重要作用，也无法体现出几何的直观如何能够帮助我们认识一些抽象的对象。作为和类比之间的区别，这里几何和其他领域的关系是紧密而严格的。

## Weil Conjecture {#weil-conjecture}
Weil 猜想是黎曼猜想在函数域上的类比。但是相比于数域而言，其更为简单。整个猜想可以完全被描述为一个数论的猜想，即考虑模 p 的同余类中的解所生成的函数，考虑这个单变量函数的解析性质。而 Weil 猜想最终的解决所依靠的是 Grothendieck 所发展的代数几何，和 Deligne 的技术上的突破。Grothendieck 的想法是从 Weil 自己的一些想法继承而来的。事实上，在 Weil 本人提出猜想之后，便很快发现了其几何本质，并提出了 Weil cohomology 的存在性的猜想，和通过 Lefschetz trace formula 解决这一猜想的可能。然而，系统的代数几何在当时并未建立，因此 Weil 的想法还是粗糙的。而 Grothendieck 的重要贡献在于，他成功地将代数几何推广到了一般的环上，并得到了 Weil 所猜想的上同调理论，即 \\(\mathbb{Q}_{l}\\)-adic 上同调。通过这一上同调理论，他能够证明 Weil Conjecture 的一部分，只剩下最困难的黎曼假设的类比。而这一类比最后被 Deligne 解决，被认为是 Deligne 最重要的工作之一。

## Geometric Representation Theory {#geometric-representation-theory}
几何表示论也是近年来越来越受关注的研究方向（有同学和我说这是因为纯代数的表示论已经没有什么可以研究的东西了，对此我持保留态度）。几何表示论可以被认为开始于对于 Kazhdan-Lustzig 猜想的研究。Kazhdn 和 Lustzig 通过对于 Weyl group 的 Springer representation 的研究得到了 Hecke algebra 的两组基。他们猜想两者之间的转移函数是多项式函数，并具有一系列的性质。为解决这一猜想，他们二人首先使用 intersection cohomology 重新解释了这一猜想。而 intersection cohomology 又可以由 perserve sheaf 的上同调表示。通过 Riemann-Hilbert correspondence 这一猜想和 D-module 联系起来并由 Beilinson-Bernstein 以及 Brylinsk-Kashiwara 两组人独立得到了解决。从这一发展过程中可以看到几何在这一问题中发挥的重要作用。（之后也出现了更代数的证明方法。）从 Springer 理论到 Nakajima 的 quiver variety 到几何朗兰兹，几何表示论已经形成了一个庞大的研究领域。

## Fundamental Lemma {#fundamental-lemma}
Ngo 对于基本引理的证明是近年来朗兰兹纲领的重大突破之一。基本引理联系了不同群之间的轨道积分，对于 Langlands 函子性猜想提供了重要的工具。然而虽然叫做基本引理，但是在自 1970 年代提出后一直少有进展。Ngo 的突出贡献在于他发现了几何中的 Hitchin fibration（最初在可积系统中被引入）和这一猜想之间的深刻联系。在他之前 Goresky， Kottwitz 和 MacPherson 做了大量的工作去分析 affine Springer fiber，因为轨道积分可以被视为 affine Springer fiber 上的某种点的计数。而 Ngo 和 Laumon 也通过更细致的分析证明了酉群上的基本引理。而 Ngo 认识到 Hitchin fibration 是 affine Springer fiber 的全局类比，从而绕过了一些无法克服的技术细节，得到了完整了基本引理的证明。在此之前恐怕少有人能够想到在几何和数学物理中被大量研究的 Hitchin fibration 在自守表示中有着如此重要的应用。

## Geometric Group Theory {#geometric-group-theory}
几何群论是在近年来获得了越来越多的关注。其本质上是通过几何的方法来研究群论的问题。这个想法本身是很自然的：首先，在几何中会自然地产生很多的有限生成群，事实上任意的有限表示群都可以作为某个流形的基本群；其次，群在几何对象上的作用是几何学中常见的研究对象；最后，有限生成群在选定生成元后的 Cayley 图有着自然的度量。所以几何群论的历史可以说是非常悠久的。而其再度兴起和 Gromov 在其中的工作有很大的关系。Gromov 参考几何中的双曲性，定义了双曲群，并对其性质进行了研究。很多几何上的定理如等周不等式等都可以成为研究群论的工具。比如 Gromov 证明了一个有限生成群如果是多项式生长的，那么它有一个有限指标的幂零子群等等一系列结论。几何群论的工作也反过来反哺了几何本身。比如 Agol 对于 virtual Haken conjecture 以及 virtual fibration conjecture 这两个三维流形的领域的重要猜想的证明就是建立在 Wise 等人对于 CAT(0) cube complex 的研究之上的。
