+++
title = "几何 II: 几何作为启发"
author = ["Zenith John"]
publishDate = 2022-12-24
tags = ["Essay", "Mathematics"]
draft = false
+++

## 前言 {#前言}

在这章中，我将会介绍从几何学启发得到的一些数学对象。值得注意的是，这些对象是受几何启发而来，因而其研究方法中还多少带有几何的影子，而且对于其他数学的分支已经产生了深刻的影响。


## Homological Algebra {#homological-algebra}

同调代数的想法在可以追溯到 19 世纪 Riemann 和 Betti 关于同调数的研究，以及 Poincaré 对于同调的严格化。然而在 1940 年之前，同调只是拓扑学的一部分。但是在 1940-1955 年之间，范畴的概念被 Eilenberg 和 MacLane 两位拓扑学家发明出来，而同调的想法被逐渐地运用到了多种代数结构上。尤其是在 1956 年最初出版的由 Cartan 和 Eilenberg 合写的 Homological Algebra 一书中，将同调论放到了范畴论的框架中进行讨论，研究了导出函子，内射预解，投射预解等一系列的对象。同调代数的使用改变了很多代数学研究的面貌，尤其是在交换代数和代数几何中，同调代数已经成了不可或缺的一部分。而对于 Galois 群的上同调的研究，也在数论的发展中起到了重要的作用。

参考资料：[<a href="#citeproc_bib_item_1">1</a>]


## Topos Theory {#topos-theory}

一般认为 Topos 有两个来源，一是来自于；而另一个就来自于 Grothendieck 对于层论的抽象化解释。在 Grothendieck 之前，层是在拓扑空间上定义的。而 Grothendieck 的重要观察在于如果仅仅需要层这样的性质，拓扑空间的公理显得过多了，因此他在范畴上定义了 Grothendieck topology 并以此定义了 (Grothendieck) topos。而 Topos 的另一个来源是 Lawvere 引入的 Elementary Topos。Topos 既可以被认为是一个拓展的空间理论，同时在数理逻辑上也有着重要的意义。

参考资料：[<a href="#citeproc_bib_item_2">2</a>] Introduction。


## Model Category and Homotopical Algebra {#model-category-and-homotopical-algebra}

在代数拓扑中，除同调论之外，另一个重要的基础理论就是同伦论。相比于同调论而言，同伦论更为精细和灵活。在一定程度上，同调论是同伦论的某种“线性化”。因此同伦比同调有着更为丰富的信息。因此，对于同伦论的研究也就更为困难。理解同伦等价类是代数拓扑的一个重要问题，但是在 CW 复形的同伦类构成的范畴之中并不具有一般的 limit 和 colimit。因此简单地考虑 CW 复形的同伦类是不够的，人们试图寻找一个代数的方法在 CW 复形构成的范畴中来记录同伦的结构。Quinn 的 model category 以及 homotopical algebra 就是其中的一条可能路径。它将拓扑中的同伦论进行了抽象，使得能够在代数乃至范畴中谈论同伦的含义。事实上，正如同调论是同伦论的某种线性化，导出范畴的理论也可以在 model category 的语言下，进行重新解读。这条道路最后通向的是 Joyal，Lurie 等人的无穷范畴理论。虽然似乎这些理论最大的应用场景依然在几何学中，但是这一领域内的证明却已经变成代数的了。


## Algebraic K-Theory {#algebraic-k-theory}

拓扑 K 理论是研究拓扑空间上的向量丛的分类的理论。而由于代数几何的强大的桥梁作用，这一理论很快发展到交换环，甚至范畴上，成为代数 K 理论。然而其代数的类比事实上并不是直接的。其中 \\(K\_{0}\\) 和 \\(K\_{1}\\) 是类比几何较为容易定义的，但是 Bott periodicity 在代数 K 理论中其实是缺失的。最初由 Milnor 以得到长正合列为目的，给出了一个 \\(K\_{2}\\) 的定义。而一般的高阶 K 理论则是由 Quinn 利用了很多拓扑的构造所给出的。目前代数 K 理论和代数几何，数论等领域都有着紧密的联系。


## Noncommutative Geometry {#noncommutative-geometry}

非交换几何是由 Connes 所建立的一套理论框架，融合了几何，分析，代数等多个学科。其核心在于结合了以下几个重要观察：1，局部紧（紧）的 Hausdorff 空间的范畴和交换（带单位的交换的）的 \\(C^{\*}\\) 代数的范畴是等价的；2，在紧 Hausdorff 空间上 \\(X\\) 的复向量丛构成的范畴和有限投影的 \\(C(X)\\)-模范畴是等价的（\\(C(X)\\) 是 \\(X\\) 上连续函数构成的代数）。这两个观察在几何对象和代数对象之间建立了等价关系。在此基础上，Connes 意识到在不可交换的 \\(C^{\*}\\) 代数上，我们也可以建立类似于几何的一套理论，包括 K 理论，Chern-Weil 理论等等。非交换几何是对于几何的巨大扩展，事实上已经成为了一个庞大的领域，在数学物理，算子代数等领域有着重要作用，Connes 甚至将数论中的 Riemann Hypothesis 也纳入这一框架之中。

参考资料：[<a href="#citeproc_bib_item_3">3</a>] Chapter 1。


## 总结 {#总结}

有人曾说“对既有思想史的个性化解释恰恰是伟大的原创性思想家在开辟自身新道路时所常采用的方法。”而对几何对象的新的解释，不仅仅为数学的研究开辟了众多新的领域，还在很多时候深化了我们对于旧的数学对象的认识。在这些新的领域的研究中，几何的想法往往如影随形，为其不断地注入新鲜活力。相信在 21 世纪，几何学还会不断地启发新的想法，新的理论。


## 参考文献 {#参考文献}

<style>.csl-left-margin{float: left; padding-right: 0em;}
 .csl-right-inline{margin: 0 0 0 1em;}</style><div class="csl-bib-body">
  <div class="csl-entry"><a id="citeproc_bib_item_1"></a>
    <div class="csl-left-margin">[1]</div><div class="csl-right-inline"> Weibel, C A (1999 ). <a href="https://doi.org/10.1016/B978-044482375-5/50029-8">CHAPTER 28 - History of Homological Algebra</a>. <i>History of Topology</i>. North-Holland, Amsterdam. 797–836</div>
  </div>
  <div class="csl-entry"><a id="citeproc_bib_item_2"></a>
    <div class="csl-left-margin">[2]</div><div class="csl-right-inline"> Borceux, F (2018 ). Some glances at topos theory</div>
  </div>
  <div class="csl-entry"><a id="citeproc_bib_item_3"></a>
    <div class="csl-left-margin">[3]</div><div class="csl-right-inline"> Khalkhali, M (2013 ). <i>Basic Noncommutative Geometry</i>, Second edition. European Mathematical Society, Zürich, Switzerland</div>
  </div>
</div>
