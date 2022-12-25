+++
title = "几何 III：几何作为类比"
author = ["Zenith John"]
publishDate = 2022-12-25
tags = ["Essay", "Mathematics"]
draft = false
+++

## 前言 {#前言}

本章将会介绍几何学和数论之间一个类比关系。所谓类比指的是两个东西之间存在相似之处。但作者并不知道有什么更高的观点来解释这种相似性，也就是说这种相似关系是松散的。然而这种类比已经被证明是卓有成效的，并继续持续启发着数学家们，因此值得一书。在本文中，主要介绍了数论和几何之间的两个类比，事实上第二个类比应该被视为第一个类比的改进。


## Weil's Rosetta Stone {#weil-s-rosetta-stone}

第一个数论与几何的类比，一般认为应该归功于 Weil。他在 1940 年（在监狱中的）所写的一封信 [<a href="#citeproc_bib_item_1">1</a>]，在信中，它提出了常常被引用为 Weil's Rosetta Stone 的一个类比。即数域、函数域上的曲线以及黎曼曲面（即复曲面）之间的类比关系。这个类比的内容是非常丰富的，可以把很多数论中的对象和几何中的对象对应起来。具体可以看：<https://ncatlab.org/nlab/show/function+field+analogy>
值得一提的是 Weil 提出这个对应是在 Grothendieck 重写代数几何之前，而在 Grothendieck 重写代数几何之后，这一对应就有了更好的解释。

这一类比的一个重要例子是 Drinfeld 的几何朗兰兹，即函数域上的朗兰兹纲领。由于函数域的特殊性质，在其上的对应定理证明一般而言相比于数域而言要容易一些。在朗兰兹纲领中也是如此。在之后，Drinfeld 进一步地把朗兰兹纲领推广到到了复数域上，形成了另一个版本的几何朗兰兹纲领。而复数域版本的几何朗兰兹甚至能够和物理联系起来。而在这里起到作用的就是 Weil's Rosetta stone。

存在另一个看起来和 Weil's Rosetta stone 有些出入的有趣的类比的结论，在数论中，我们有素数定理，即
\\[\pi(x) = \\{\text{number of primes \\(\leq n\\)}\\} \sim x / \ln \pi\\]
而在黎曼曲面中，我们也有一个类似的结论，在一个紧双曲黎曼曲面上，我们有
\\[\pi(L) = \\{\text{number of closed geodesics with length \\(\leq L\\)}\\} \sim C L / \ln L\\]
事实上，上述定理是 Selberg Trace Formula 的一个推论，有着很深刻的数论内涵。但是注意到在 Weil's Rosetta stone 中素数应该对应于黎曼曲面上的一个点，因此，这里的类比并非是 Weil's Rosetta stone。或许它启发了下面这个更为神奇的类比。


## Knots and Number Theory {#knots-and-number-theory}

这个类比一般认为归功于 Barry Mazur，一位最初研究拓扑学，最后转向数论的伟大数学家。这个类比的核心观察是 Grothendieck 对于 Galois 群的重新解释，即将其解释成 étale covering。同时，Mazur 注意到一些上同调的计算以及上同调之间的对偶，说明数域实际上更像一个三维流形。比如，对于 \\(X = \mathop{Spec}(\mathcal{O}\_{k})\\), 我们有
\\[\hat{H}^{3}(X, \mathbb{G}\_{m,X}) \cong \mathbb{Q} / \mathbb{Z}\\]
在这里我不想过多地去解释各项的含义，只想指出这个 \\(X\\) 的 étale 上同调维数是 3 而不是 2。因此 Mazur 指出我们更应该把数域或者函数域上的曲线对应到一个三维流形，把素数对应到三维流形中的扭结。从这个角度看，上面的黎曼曲面上的素数定理似乎是介于两个类比之间的东西。如果我们采用 Mazur 的视角，我们可以从几何的角度解读很多数论的理论包括素数在域扩张后的分解，互反律，genus 理论等等。具体可以参考 [<a href="#citeproc_bib_item_2">2</a>]。

这一类比也有着非常重要的启发性作用，目前有人把物理中的 Chern-Simons 规范理论（最初在 3 维流形上严格化）迁移到数域上形成 Arithmetics Chern-Simons Theory 来研究数论。


## 参考文献 {#参考文献}

<style>.csl-left-margin{float: left; padding-right: 0em;}
 .csl-right-inline{margin: 0 0 0 1em;}</style><div class="csl-bib-body">
  <div class="csl-entry"><a id="citeproc_bib_item_1"></a>
    <div class="csl-left-margin">[1]</div><div class="csl-right-inline"> Weil, A (1940 ). Sur l’analogie entre les corps de nombres algébrique et les corps de fonctions algébrique</div>
  </div>
  <div class="csl-entry"><a id="citeproc_bib_item_2"></a>
    <div class="csl-left-margin">[2]</div><div class="csl-right-inline"> Morishita, M (2012 ). <i>Knots and Primes: An Introduction to Arithmetic Topology</i>. Springer, London ; New York</div>
  </div>
</div>
