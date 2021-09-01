+++
title = "Mathematics Notes"
author = ["Zenith John"]
date = 2021-08-31
categories = ["Mathematics"]
draft = false
showtoc = true
+++

## Functional Analysis {#functional-analysis}


### Banach-Hahn Theorem {#banach-hahn-theorem}


### Open Mapping Theorem {#open-mapping-theorem}


### Closed Graph Theorem {#closed-graph-theorem}


### Banach-Alaoglu Theorem {#banach-alaoglu-theorem}


### Arzelà–Ascoli Theorem {#arzelà-ascoli-theorem}


## Morse Theory {#morse-theory}


### Morse Theory {#morse-theory}

Let \\(f\\) be a smooth real valued function on manifold M. Let \\(a < b\\) and
suppose that the set \\(f^{-1}[a,b]\\) is **compact** and contain no critical points
of \\(f\\). Then \\(M^{a}\\) is differomorphic to \\(M^{b}\\). Furthermore, \\(M^{a}\\)
is a deformation retract of \\(M^{b}\\), inclusion map \\(M^{a} \to M^{b}\\) is a
homotopy equivalence.

The theorem supplies the condition when the retraction is possible.

{{% theorem %}}
If \\(f\\) is a differentiable function on a manifold \\(M\\), with no degenerate
critical points, and if each \\(M^{a}\\) is compact, then \\(M\\) has the homotopy
type of a CW-complex, with one cell of dimension \\(\lambda\\) for each critical
point of index \\(\lambda\\).
{{% /theorem %}}

{{% theorem %}}
Let \\(\phi\_{0}\\) and \\(\phi\_{1}\\) be homotopic maps from the sphere
\\(\dot{e^{\lambda}}\\) to \\(X\\). Then the identity map of \\(X\\) extends to a homotopy
equivalence \\(k:X \cup\_{\phi\_{0}} e^{\lambda} \to X \cap\_{\phi\_{1}}
e^{\lambda}\\).
{{% /theorem %}}

{{% proof %}}
\\[\begin{align} k(x) = x && x \in X \\\ k(tu) = 2tu && 0 \leq t \leq 1/2 \\\ k(tu) = \phi\_{2-2t}(u) && 1/2 \leq t \leq 1 \\\ \end{align}\\]
{{% /proof %}}

{{% lemma %}}
Let \\(\phi:\dot{e^{\lambda}} \to X\\) be an attaching map. Any homotopy
equivalence \\(f:X \to Y\\) extends to a homotopy equivalence \\(F:X
\cup\_{\phi}e^{\lambda} \to Y \cup\_{f\phi}e^{\lambda}\\)
{{% /lemma %}}


## Partial Differential Equation {#partial-differential-equation}

Author L. C. Evans


## Representation of finite groups {#representation-of-finite-groups}

The reference includes <sup id="19580479584332ed50a4af7bf7f3f201"><a href="#steinberg2012" title="Steinberg, Representation Theory of Finite Groups: An Introductory Approach, {Springer} (2012).">steinberg2012</a></sup> Chapter 1-6.


### Representation of finite groups {#representation-of-finite-groups}

<div class="definition">
  <div></div>

A representation of a group \\(G\\) is homomorphism \\(\phi: G \to GL(V)\\) for some (finite-dimensional) vector space \\(V\\). The dimension of \\(V\\) is called the degree of \\(\phi\\).

</div>

equivalence; G-invariant subspace; irreducible representation; completely reducible representation; indecomposable representation; unitary representation


### Completely decomposition {#completely-decomposition}

{{% proposition %}}
Every representation of a finite group is equivalent to a unitary representation.
{{% /proposition %}}

{{% theorem %}}
Every representation of a finite group is completely reducible.
{{% /theorem %}}


### Schur lemma {#schur-lemma}

{{% lemma %}}
Let \\(\phi\\), \\(\rho\\) be irreducible representation of \\(G\\), and \\(T \in Hom\_{G}(\phi, \rho)\\). Then either \\(T\\) is invertible or \\(T = 0\\).
{{% /lemma %}}

{{% corollary %}}
Let \\(G\\) be an abelian group. Then any irreducible representation of \\(G\\) has degree 1.
{{% /corollary %}}


### Orthogonal relations {#orthogonal-relations}

Group algebra

{{% theorem %}}
Suppose that \\(\phi,\rho: G \to U\_{n}( C)\\) are inequivalent irreducible unitary representations. Then
\\[\begin{equation} \langle \phi\_{ij}, \rho\_{kl} \rangle = 0 \end{equation}\\]

\\[\begin{equation} \langle \phi\_{ij}, \phi\_{kl} \rangle =  \begin{cases} 1/n & \text{if } i = k \text{ and } j = l \\\    0 & \text{else} \end{cases} \end{equation}\\]
{{% /theorem %}}


### Characters and class functions {#characters-and-class-functions}

\\(L(G)\\); character; irreducible character; class function; multiplicity; regular representation; character table

{{% proposition %}}
Equivalent representations has equal characters.
{{% /proposition %}}

{{% proposition %}}
Characters are class functions.
{{% /proposition %}}

The irreducible characters of \\(G\\) form an orthonormal set of class functions.
and \\({\rm dim} Z(L(G)) = |Cl(G)|\\).
因此有限群的不可约表示数小于等于其共轭类群的数量。之后，进一步地可以证明，有限群不可约表示的数量恰好等于其共轭类群的数量。

{{% proposition %}}
\\(|G| = d\_{1}^{2} + d\_{2}^{2} + \cdots + d\_{s}^{2}\\) holds, where \\(d\_{i}\\) is the degree of the irreducible representation.
{{% /proposition %}}

正交关系 2(cf. [有限群表示的正交关系](#orthogonal-relations))

{{% theorem %}}
Let \\(C\\), \\(C'\\) be conjugacy classes of \\(G\\), and let \\(g \in C\\) and \\(h \in C'\\). Then

\begin{equation} \sum\_{i = 1}^{s}\chi\_{i}(g) \overline{\chi\_{i}(h)} = \begin{cases} |G|/|C| & C = C' \\\ 0 & C \neq C' \end{cases} \end{equation}

That is the columns of the character table are orthogonal.
{{% /theorem %}}


### Fourier analysis of finite groups {#fourier-analysis-of-finite-groups}

fourier transform; fourier inversion; convolution; dual group;

{{% proposition %}}
The class functions form the center of \\(L(G)\\).
{{% /proposition %}}

{{% proposition %}}
\\(\widehat{a \* b} = \hat{a} \cdot \hat{b}\\)
{{% /proposition %}}

nonabelian Fourier transform (Wedderburn)


### Dimension theorem {#dimension-theorem}

{{% theorem %}}
Let \\(\phi\\) be an irreducible representation of \\(G\\) of degree \\(d\\). Then \\(d\\) divides \\(|G|\\).
{{% /theorem %}}

这里值得注意的是，证明中使用了一些代数数论的结论，主要是关于 algebraic number 和 algebraic integer。


### Burnside Theorem {#burnside-theorem}

{{% theorem %}}
Let \\(G\\) be a group of order \\(p^{a}q^{b}\\) with \\(p\\), \\(q\\) primes. Then \\(G\\) is not simple unless it is cyclic of prime order.
{{% /theorem %}}


### Tensor product of irreducible representations {#tensor-product-of-irreducible-representations}


### 点群 {#点群}

<div class="definition">
  <div></div>

A finite subgroup of O(3) is called a point group.

</div>


### 有限群表示的总结 {#有限群表示的总结}

1.  在有限群上的很多操作可以复制到紧群和李群上，如李群表示中的不可约表示以及傅里叶分析。


## Representation of quivers {#representation-of-quivers}

The basics of the quivers are from <sup id="df38f5636bec59103a70400bed4764c9"><a href="#kirillov2016" title="Kirillov, Quiver Representations and Quiver Varieties, {American Mathematical Society} (2016).">kirillov2016</a></sup>.


### Definition of Quivers {#definition-of-quivers}

quiver; subquiver; oriented cycle; loop; morphism; direct sum; subrepresentation; irreducible representation; indecomposable representation; quivers of finite type; path; product of path; path algebra; one-way path

{{% theorem %}}
The category of representations of \\(Q\\) over a field \\(k\\) is equivalent to the category of \\(k(Q)\\)-modules.
{{% /theorem %}}

{{% lemma %}}
The Jacobson radical of the path algebra \\(k(Q)\\) is the span of all one-way paths of \\(Q\\).
{{% /lemma %}}


## Differential Geometry {#differential-geometry}


### Manifold {#manifold}



<div class="definition">
  <div></div>

An \\(n\\)-dimensional **manifold** is an \\(n\\)-dimensional locally Euclidean Hausdorff space with countable basis for its topology.

</div>

The definition has three requirements, where the countable basis is hardly used.

<div class="definition">
  <div></div>

A **differential structure**  on the \\(n\\)-manifold \\(M\\) is a maximal smooth atlas \\(\mathscr{D}\\) for \\(M\\). The pair \\((M, \mathscr{D})\\) is called a **smooth manifold** or **differentiable manifold**.

</div>

We call a compact manifold without boundary a **closed manifold**.


### Lie group {#lie-group}



<div class="definition">
  <div></div>

A **Lie group** is a smooth manifold with a group structure, where the group multiplication and inverse are smooth maps.

</div>

Cf. [Manifold](#manifold).


### Tangent space {#tangent-space}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:17]</span></span>
We denote the **tangent space** at point \\(p\\) by \\(T\_{p}(M)\\), and to each map \\(f: M \to N\\) associated a linear map \\(T\_{p}(f): T\_{p}(M) \to T\_{f(p)}N\\) the **differential** of \\(f\\) at \\(p\\), such that
\\[T\_{p}(gf) = T\_{f(p)} g \circ T\_{p}f\\]
The elements of \\(T\_{p}(M)\\) are the **tangent vectors** of \\(M\\) at \\(p\\). Cf. [Manifold](#manifold).


### Immersion, submersion {#immersion-submersion}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:17]</span></span>
A smooth map \\(f\\) is an **immersion** if each \\(T\_{x}f\\) is injective and **submersion** if each \\(T\_{x}f\\) is surjective. Cf. [Tangent space](#tangent-space).


### Regular point {#regular-point}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:20]</span></span>
For a smooth map \\(f: M \to N\\), a point \\(x \in M\\) is called a **regular point** if \\(T\_{x}f\\) is surjective and a point \\(y \in N\\) is called a **regular value** if each \\(x \in f^{-1}(y)\\) is a regular point, otherwise is called a **singular value**. Cf. [Tangent space](#tangent-space).


### Sard theorem {#sard-theorem}



{{% theorem %}}
The set of singular values of a smooth map has measure zero, and the set of regular values is dense.
{{% /theorem %}}

Cf. [Regular point](#regular-point).

Remark: in most applications, the dense property implies the existence, as in the case of Whitney embedding theorem.


### Orientation {#orientation}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:38]</span></span>
An atlas is called **orienting** if any two charts are positively related, that is every two charts has the same orientation as a subset of \\(\RR^{n}\\). If a [Manifold](#manifold) \\(M\\) has an orienting atlas, we call \\(M\\) **orientable**. Notice that if a manifold is orientable, it naturally has two orientation.

Given [Local homology group](#local-homology-group), a generator of the homology group \\(H\_{n}(M, M \backslash x; R) \cong R\\) is called a **local \\(R\\)-orientation**. Let \\(M\\) be a \\(n\\)-manifold and \\(A \subset M\\). An \\(R\\)-orientation of \\(M\\) along \\(A\\) is a section \\(s \subset \Gamma(A; R)\\) of \\(\omega: H\_{n}(M, M \backslash \bullet; R) \to M\\) such that \\(s(a) \in H\_{n}(M, M \backslash a; R) \cong R\\) is a generator for each \\(a \in A\\). For \\(A = M\\), we called it **\\(R\\)-orientation** and for \\(R = \ZZ\\), it is called **orientation**.


### Tangent bundle {#tangent-bundle}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:45]</span></span>
The [Tangent space](#tangent-space) at each point constitutes a [Vector bundle](#vector-bundle) called the **tangent bundle**.


### Normal bundle {#normal-bundle}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:48]</span></span>
Let \\(f: M \to N\\) be an [Immersion](#immersion-submersion). We define the quotient bundle of the bundle morphism \\(i: TM \to f^{\* }TN|\_{M}\\) to be the **normal bundle**. There exists a neighborhood of the zero section of normal bundle diffeomorphic to the neighborhood of \\(N\\) in \\(M\\). The diffeomorphic map is called **tubular map** and the target is called **tubular neighborhood**.

Cf. [Vector bundle](#vector-bundle), [Tangent bundle](#tangent-bundle).


### Whitney embedding theorem {#whitney-embedding-theorem}



{{% theorem %}}
A smooth \\(n\\)-manifold has an embedding as a closed submanifold of \\(\RR^{2n + 1}\\).
{{% /theorem %}}

Cf. [Sard theorem](#sard-theorem), [Manifold](#manifold).


### Collar {#collar}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:56]</span></span>
A collar of a smooth boundary [Manifold](#manifold) \\(M\\) is a diffeomorphism \\(\kappa: \partial M \times \rinterval{0}{1} \to M\\) where the image is an open neighborhood of \\(\partial M\\) in \\(M\\) and \\(\kappa(x, 0) = x\\).

For collar, we have following proposition

{{% proposition %}}
A smooth boundary manifold \\(M\\) has a collar.
{{% /proposition %}}

The proposition is similar to the existence of the tubular neighborhood for [Normal bundle](#normal-bundle).


### Connected sum {#connected-sum}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-31 Tue 17:46]</span></span>
Given two \\(n\\)-[manifolds](#manifold) \\(M\_{1}\\), and \\(M\_{2}\\), we define the **connected sum** of \\(M\_{1}\\) and \\(M\_{2}\\) by remove two \\(D^{n}\\) in \\(M\_{1}\\) and \\(M\_{2}\\) and glue two \\(S^{n - 1}\\) together, denoted by \\(M\_{1} \sharp M\_{2}\\).


## Algebraic Topology {#algebraic-topology}


### Vector bundle {#vector-bundle}



<div class="definition">
  <div></div>

The **Whitney sum** of two vector bundle \\(\xi: E(\xi) \to B\\) and \\(\eta: E(\eta) \to B\\) is \\(d^{\* }(\xi \times \eta) = \xi \oplus \eta\\), where \\(d: B \to B \times B\\) is the diagonal map. A bundle \\(\eta\\) is called an **inverse** of \\(\xi\\), if \\(\xi \oplus \eta\\) is isomorphic to a trivial bundle.

</div>

{{% theorem %}}
A numerable vector bundle has a **Riemann metric**.
{{% /theorem %}}

Cf. [Numerable](#numerable)

{{% theorem %}}
A bundle has an inverse if and only if it is numerable of finite type.
{{% /theorem %}}

The real vector bundles and complex vector bundles have monoid structure and can be transformed into [Grothendieck ring](#grothendieck-ring) denoted by \\(KO(X)\\) and \\(K(X) = KU(X)\\).


### Bott periodicity {#bott-periodicity}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-24 Tue 10:55]</span></span>
We consider the [Grothendieck ring](#grothendieck-ring) of [vector bundles](#vector-bundle). We have that

{{% proposition %}}
\\(K(S^{2})\\) is free abelian group with basis \\(1\\) and \\(\eta = H(1)\\). The multiplicative structure is determined by \\(\eta^{2} = 2 \eta - 1\\).
{{% /proposition %}}

Cf. [Complex line bundle over CP^1](#complex-line-bundle-over-cp-1).

The Bott periodicity is the following deep result

{{% theorem %}}
\\[K(X) \otimes K(S^{2}) \cong K(X \times S^{2})\\]
\\[KO(X) \otimes KO(S^{8}) \cong KO(X \times S^{8})\\]
{{% /theorem %}}


### Complex line bundle over CP^1 {#complex-line-bundle-over-cp-1}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-24 Tue 10:18]</span></span>
We have that \\(H(k) = (\mathbb{C}^{2} \backslash 0) \times\_{\mathbb{C}^{\* }} \mathbb{C}\\) with equivalence relation \\(((z\_{0}, z\_{1}), u) \sim ((\lambda z\_{0}, \lambda z\_{1}), \lambda^{k} u) \\). Then we have that \\(H(k)\\) represent the isomorphism classes of complex line bundles.

Remark: This is a simple but non-trivial fact, leading naturally to the problems of complex line bundles over \\(\mathbb{C}P^{n}\\). And more generally, vector bundles over \\(\mathbb{C}P^{n}\\).

Cf. [Vector bundle](#vector-bundle)


### Grothendieck ring {#grothendieck-ring}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-24 Tue 10:55]</span></span>
Given a commutative monoid \\(M\\) which is a set together with an associative and commutative composition law \\(+\\) with zero element. We have a group \\(K(M) = M \times M / D(M)\\). That is elements of \\(K(M)\\) are of the form \\((a,b) \in M \times M\\), with equivalence relation \\((a, b) \sim (c, d)\\) if \\((a + n, b + n) = (c + m, d + m)\\) for some \\(m,n \in M\\). Such group is called **Grothendieck group**. If the monoid is given with a multiplicative structure, which can by inherited by Grothendieck group, the group becomes **Grothendieck ring**.


### Numerable {#numerable}



<div class="definition">
  <div></div>

An open covering is called **numerable** if it admits a subordinate partition of unity.

</div>

Partition of unity is one of the important properties of the covering which deserves its own definition.

<div class="definition">
  <div></div>

A vector bundle (locally trivial bundle) \\(\xi: E(\xi) \to B\\) is called **numerable** if there exists a numerable covering on which the vector bundle is trivial.

</div>

Cf. [Vector bundle](#vector-bundle)


### Eilenberg-Mac Lane space {#eilenberg-mac-lane-space}



<div class="definition">
  <div></div>

The **Eilenberg-Mac Lane space** \\(K(G, n)\\) is the space with homotopy group \\(\pi\_{i}(K(G,n)) = 0\\) for \\(i \neq n\\) and \\(G\\) if \\(i = n\\).

</div>

{{% theorem %}}
The Eilenberg-Mac Lane spaces exist.
{{% /theorem %}}


### Classifying Space {#classifying-space}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-23 Mon 19:50]</span></span>
We consider the functor \\(B(-, G)\\) from the category of topological space to sets, where \\(B(B,G)\\) denote the set of isomorphism classes of [Numerable](#numerable) \\(G\\) principal bundles over \\(B\\). We have that functor representable by **classifying space** \\(BG\\), with a numerable \\(EG \to BG\\). The total space \\(EG\\) is called **universal** if each numerable free \\(G\\) space \\(E\\) has up to \\(G\\)-map \\(E \to EG\\).

We can construct \\(EG, BG\\) by **join**. We consider a family of topological space \\(X\_{j} \in J\\). Then we have
\\[X = \star\_{j \in J} X\_{j} = \\{(t\_{i}X\_{i})\_{i \in J}| \sum\_{i \in J}t\_{i} = 1\\}/ \sim\\]
where the summation has finite nonzero summand \\((t\_{i}X\_{i}) \sim (s\_{i}Y\_{i})\\) if \\(t\_{i} = s\_{i}\\) and \\(X\_{i} = Y\_{i}\\) when \\(t\_{i} = s\_{i} \neq 0\\). The topology of the space \\(X\\) is the coarsest topology where the function \\(t\_{i}: X \to \mathbb{R}, (t\_{i}X\_{i}) \to t\_{i}\\) and function \\(t\_{i}:t\_{i}^{-1}(\linterval{0}{1}) \to X\_{i}, (t\_{i}X\_{i}) \to X\_{i}\\) is continuous.

Then we construct the **Milnor space**
\\[EG = G \star G \star G \star \cdots\\]
and \\(BG = EG/G\\). The action of \\(G\\) is obvious.

{{% theorem %}}
\\(EG\\) is contractible.
{{% /theorem %}}

For a discrete group, \\(BG\\) is an [Eilenberg-Mac Lane space](#eilenberg-mac-lane-space) of type \\(K(G,1)\\).


### <span class="org-todo todo TODO">TODO</span> Equivariant cohomology {#equivariant-cohomology}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-29 Sun 15:25]</span></span>
Compared with classical cohomology theory, the equivariant cohomology is more general and simpler.


### <span class="org-todo todo TODO">TODO</span> Equivariant K-theory {#equivariant-k-theory}


### Local homology group {#local-homology-group}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-31 Tue 17:57]</span></span>
Let \\(h\_{\* }(-)\\) be a homology theory and \\(M\\) an \\(n\\)-dimensional [Manifold](#manifold). Then groups of the form \\(h\_{k}(M, M \backslash x)\\) are called **local homology group**.

By excision theorem, we have that \\(h\_{k}(M, M \backslash x)\\) is \\(h\_{k}(D^{n}, D^{n} \backslash x)\\). For singular homology theory, we have \\(H\_{n}(M, M \backslash x; G) \cong G\\) and other homology groups are all \\(0\\).

For \\(K \subset L \subset M\\), we have homomorphism \\(r\_{K}^{L}: h\_{k}(M, M \backslash L) \to h\_{k}(M, M \backslash K)\\).


### Fundamental class {#fundamental-class}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-31 Tue 18:12]</span></span>
Theorem 16.4.1 in <sup id="5ad6139c99b6d2508f6ef6f11ce7f09d"><a href="#dieck2008" title="tom Dieck, Algebraic Topology, {European Mathematical Society} (2008).">dieck2008</a></sup>.

{{% theorem %}}
Let \\(M\\) be a compact connected \\(n\\)-[Manifold](#manifold). Then one of the following holds:

-   \\(M\\) is orientable, then we have that \\(H\_{n}(M) \cong \ZZ\\) and for each \\(x \in M\\), \\(r^{M}\_{x}\\) is isomorphism.
-   \\(M\\) is non-orientable, then \\(H\_{n}(M) = 0\\).
{{% /theorem %}}

Cf. [Orientation](#orientation), [Local homology group](#local-homology-group).

If \\(M\\) is orientable, then a generator will be called **fundamental class**. If \\(M\\) is a manifold with boundary, then we call \\(z \in H\_{n}(M, \partial M)\\) a **fundamental class** if for each \\(x \in M \backslash \partial M\\) the restriction of \\(z\\) is a generator in \\(H\_{n}(M, M \backslash x)\\), cf. [Local homology group](#local-homology-group).

Theorem 16.5.1 (ibid.)

{{% theorem %}}
Let \\(M\\) be a compact connected \\(n\\)-manifold with non-empty boundary. Then one of the following holds:

-   \\(H\_{n}(M, \partial M) \cong \ZZ\\) and a generator of this group is a fundamental class. The image of the map \\(\partial: H\_{n}(M, \partial M) \to H\_{n - 1}(\partial M)\\) is a fundamental class. The interior \\(M \backslash \partial M\\) is orientable.
-   \\(H\_{n}(M, \partial M) = 0\\), and \\(M \backslash \partial M\\) is not orientable.
{{% /theorem %}}


### <span class="org-todo todo TODO">TODO</span> Cohomology {#cohomology}


## Mirror Symmetry {#mirror-symmetry}


## Algebraic Geometry {#algebraic-geometry}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-23 Mon 19:50]</span></span>
There are two tastes of algebraic geometry. The algebraic geometers view it as a specialized geometry, which is closed related to complex geometry (by GAGA), birational geometry (MMP for example), symplectic geometry (Gromov-Witten invariants) etc. Algebraic geometers are mainly interested in case where the base field is \\(\CC\\). Experts in other field may view algebraic geometry as useful languages, where vast properties are worked out by algebraic geometers. Therefore, Grothendieck's style of algebraic geometry provides many insights into number theory, representation theory etc. In both case, the characteristic \\(p\\) case is more interesting. Examples includes [Steinberg variety](#steinberg-variety), p-adic Hodge theory.

The following are the themes in Algebraic Geometry Salt Lake 2015 seminar <https://sites.google.com/site/2015summerinstitute/home/schedule> : analytic methods, birational geometry and classification, commutative algebra and computational algebraic geometry, Hodge theory, singularities and characteristic p methods, derived algebraic geometry, derived categories, geometric representation theory, Gromov-Witten and Donaldson-Thomas theories, mirror symmetry, tropical geometry, algebraic cycles, cohomology theories, p-adic Hodge theory, rational points and Diophantine problems, topology of algebraic varieties


### Enumerative geometry {#enumerative-geometry}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-31 Tue 08:52]</span></span>
There are several aspects of enumerative geometry, beyond the numbers.

-   counting curves and sheaves (Gromov-Witten theory, Donaldson-Thomas and related theories)
-   gauge theory enumerative geometry (3d gauge theories and Coulomb branches, mirror symmetry, 4d gauge theories, and Vafa-Witten invariants, etc)
-   applications of enumerative geometry to categorification and low-dimensional topology
-   Hall algebras and their refined versions (cohomological, K-theoretic, derived categories)
-   Enumerative geometry of Nakajima quiver variety and the representation of quantum groups (symplectic resolution, etc)


### Moduli space of Stable Maps {#moduli-space-of-stable-maps}



<div class="definition">
  <div></div>

Let \\(X\\) be a non-singular projective variety. A morphism \\(f\\) from a pointed nodal curve to \\(X\\) is a **stable map** if every genus \\(0\\) contracted component of \\(\Sigma\\) has at least three special points, and every genus \\(1\\) contracted component has at least one special point.

</div>

<div class="definition">
  <div></div>

A stable map represents a homology class \\(\beta \in H\_{2}(X, \mathbb{Z})\\) if \\(f\_{\*}[C] = \beta\\).

</div>

<div class="definition">
  <div></div>

The moduli space of stable maps from \\(n\\)-pointed genus \\(g\\) nodal curves to \\(X\\) representing the class \\(\beta\\) is denoted \\(\bar{M}\_{g,n}(X, \beta)\\). The subscript \\(n\\) may be omitted if \\(n = 0\\).

</div>

The moduli space \\(\overline{M}\_{g,n}(X, \beta)\\) is a Deligne-Mumford stack. And the moduli    space admits [Virtual fundamental class](#virtual-fundamental-class).


### Gromov-Witten theory {#gromov-witten-theory}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 19:53]</span></span>
Cf. [Enumerative geometry](#enumerative-geometry).

We have natural maps for [Moduli space of Stable Maps](#moduli-space-of-stable-maps)

{{< figure src="/img/2021-08-25_20-25-36_screenshot.png" >}}

And we have **Gromov-Witten class**
\\[I\_{g,n,\beta}(\alpha\_{1}, \alpha\_{2}, \cdots, \alpha\_{n}) = \pi\_{2!} (\pi\_{1}^{\* }(\alpha\_{1} \otimes \cdots \otimes \alpha\_{n}))\\]
Also we have **Gromov-Witten invariant**
\\[\langle I\_{g,n,\beta}(\alpha\_{1}, \alpha\_{2}, \cdots, \alpha\_{n}) \rangle = \int\_{\overline{M}\_{g,n}} I\_{g,n,\beta}(\alpha\_{1}, \alpha\_{2}, \cdots, \alpha\_{n}) \\]

The Gromov-Witten invariants has natural enumerative geometric interpretation. \\(\langle I\_{g,n,\beta}(\alpha\_{1}, \cdots, \alpha\_{n}) \rangle\\) equals the number of stable curves in \\((C, p\_{1}, \cdots, p\_{n}) \in \overline{M}\_{g,n}\\) for which we can find \\(f\\) such that \\(f(p\_{i}) \in Z\_{i} = \alpha\_{i}^{\vee}\\) and \\(f\_{\*}( C) = \beta\\).

By above interpretation we have natural axioms about Gromov-Witten invariants.


#### Linear axiom {#linear-axiom}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:35]</span></span>
Cf. [Gromov-Witten theory](#gromov-witten-theory).
\\(I\_{g,n,\beta}\\) is linear in each variable.


#### Effectivity axiom {#effectivity-axiom}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:35]</span></span>
Cf. [Gromov-Witten theory](#gromov-witten-theory).
For \\(X\\) projective, \\(I\_{g,n,\beta} = 0\\) if \\(\beta\\) is not an effective curve class.


#### Degree axiom {#degree-axiom}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:36]</span></span>
Cf. [Gromov-Witten theory](#gromov-witten-theory).
For \\(\alpha\_{1}, \cdots, \alpha\_{n} \in H^{\* }(X, \mathbb{Q})^{\otimes n}\\), \\(I\_{g,n, \beta}(\alpha\_{1}, \cdots, \alpha\_{n}) \in H^{\* }(\bar{M}\_{g,n}, \mathbb{Q})\\) has degree \\(2 (g - 1) {\rm dim} X + 2 \int\_{\beta} \omega\_{X} + \sum\_{i} {\rm deg} \alpha\_{i}\\)


#### Equivariant axiom {#equivariant-axiom}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:39]</span></span>
Cf. [Gromov-Witten theory](#gromov-witten-theory).
The map \\(I\_{g,n, \beta}\\) is \\(S\_{n}\\) equivariant where \\(S^{n}\\) acts on \\(H^{\*}(X, \mathbb{Q})^{\otimes n}\\) naturally and acts on \\(H^{ \*}(\overline{M}\_{g,n}), \mathbb{Q}\\) by permuting \\(p\_{i}\\)'s  of the pointed curves.


#### Fundamental class axiom {#fundamental-class-axiom}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:41]</span></span>
Cf. [Gromov-Witten theory](#gromov-witten-theory).
If \\(n + 2g \geq 4\\) then there exists a natural forgetting map
\\[\pi\_{n}: \bar{M}\_{g,n} \to \bar{M}\_{g,n - 1}\\]
if \\([X] \in H^{0}(X, \mathbb{Q})\\) fundamental cycle, then we have that
\\[I\_{g,n, \beta}(\alpha\_{1}, \cdots, \alpha\_{n - 1}, [X]) = \pi\_{n}^{\* }I\_{g,n-1, \beta}(\alpha\_{1}, \cdots, \alpha\_{n - 1})\\]


#### Divisor axiom {#divisor-axiom}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:43]</span></span>
Cf. [Gromov-Witten theory](#gromov-witten-theory).
If \\(n + 2g \geq 4\\), then \\(\pi\_{n}: \bar{M}\_{g,n} \to \bar{M}\_{g,n - 1}\\) as above, if \\(\alpha\_{n} \in H^{2}(X, \mathbb{Q})\\) then we have
\\[\pi\_{n \* } I\_{g,n, \beta}(\alpha\_{1}, \cdots, \alpha\_{n}) = (\int\_{\beta} \alpha\_{n}) \times I\_{g,n -1, \beta}(\alpha\_{1}, \cdots, \alpha\_{n-1})\\]


#### Point mapping axiom {#point-mapping-axiom}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:45]</span></span>
Cf. [Gromov-Witten theory](#gromov-witten-theory).
When \\(\beta = 0\\), if \\(\alpha\_{i}\\) are homogeneous cohomology classes, then
\\[I\_{0,n,0}(\alpha\_{1}, \cdots, \alpha\_{n}) = \int\_{X}(\alpha\_{1} \cup \cdots \cup \alpha\_{n})[\bar{M}\_{g,n}]\\]
if \\(\sum\_{i} {\rm deg} \alpha\_{i} = 2 {\rm dim} X\\) and is zero otherwise.


#### Splitting axiom {#splitting-axiom}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:48]</span></span>
Cf. [Gromov-Witten theory](#gromov-witten-theory).
By gluing \\(2\\) points, we have natural map
\\[C: \bar{M}\_{g\_{1}, n\_{1} + 1} \times \bar{M}\_{g\_{2}, n\_{2} +1} \to \bar{M}\_{g,n}\\]
where \\(g = g\_{1} + g\_{2}\\) and \\(n = n\_{1} + n\_{2}\\). Then we have
\\[\phi^{\* }I\_{g,n, \beta} (\alpha\_{1}, \cdots, \alpha\_{n}) = \sum\_{\beta = \beta\_{1} + \beta\_{2}} \sum\_{i,j} g^{ij}I\_{g\_{1}, n\_{1} + 1, \beta}(\alpha\_{1}, \cdots, \alpha\_{n\_{1}}, T\_{i}) \otimes I\_{g\_{2}, n\_{2} +1, \beta\_{2}}(T\_{j}, \alpha\_{n\_{1}+ 1}, \cdots, \alpha\_{n})\\]
where \\(\phi\\) is the diagonal map and \\(g^{ij}\\) is the inverse matrix of \\(g\_{ij} = \int\_{X} T\_{i} \cup T\_{j}\\).


#### Reduction axiom {#reduction-axiom}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:52]</span></span>
Cf. [Gromov-Witten theory](#gromov-witten-theory).
Gluing two point together, we have natural map \\(\psi: \bar{M}\_{g - 1, n + 2} \to \bar{M}\_{g, n}\\). Then we have
\\[\psi^{\* } I\_{g,n, \beta}(\alpha\_{1}, \cdots, \alpha\_{n}) = \sum\_{i,j}g^{ij}I\_{g - 1, n +2, \beta}(\alpha\_{1}, \cdots, \alpha\_{n}, T\_{i}, T\_{j})\\]


#### Deformation axiom {#deformation-axiom}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:54]</span></span>
Cf. [Gromov-Witten theory](#gromov-witten-theory).
Let \\(X \to T\\) be a smooth proper amp with connected base \\(T\\). And set \\(X\_{t}\\)  is the fiber. Then for each \\(t \in T\\) and \\(\beta\_{t} \in H\_{2}(X\_{t}, \mathbb{Z})\\), we obtain a map \\(I\_{g,n, \beta\_{t}}: H^{\* }(X\_{t}, \mathbb{Q}) \to H^{\* }(M\_{g,n}, \mathbb{Q})\\). Then if \\(\beta\_{t}\\) is locally constant section of \\(H\_{2}(X\_{t}, \mathbb{Q})\\) and \\(\alpha\_{1}, \cdots, \alpha\_{n}\\) are locally constant, then we have \\(I\_{g,n, \beta\_{t}}(\alpha\_{1}, \cdots, \alpha\_{n})\\) is constant.


#### Kontsevich recursion formula {#kontsevich-recursion-formula}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 15:23]</span></span>
Cf. [Gromov-Witten theory](#gromov-witten-theory).
For \\(X = \mathbb{P}^{2}\\), we denote that \\(N\_{d} = \langle I\_{0, 3d - 1, d}([pt], \cdots, [pt]) \rangle \\) where \\([pt]\\) occur \\(3d - 1\\) times for \\(d \geq 1\\). Then we have following **Kontsevich recursion formula**
\\[N\_{d} = \sum\_{d = d\_{1} + d\_{2}, d\_{1}, d\_{2} > 0} N\_{d\_{1}}N\_{d\_{2}} (d\_{1}^{2}d\_{2}^{2} \binom{3d - 4}{3d\_{1} - 2} - d\_{1}^{3}d\_{2} \binom{3d - 4}{3d\_{1} - 1})\\]


### Hilbert scheme {#hilbert-scheme}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-29 Sun 15:24]</span></span>
We fix a class \\(\beta \in H\_{2}(X, \ZZ)\\) and fix an integer \\(\chi \in \ZZ\\).

<div class="definition">
  <div></div>

The **Hilbert scheme** \\({\rm Hilb}\_{\chi}(X, \beta)\\) parametrizes \\(1\\) dimensional subscheme \\(Z \subset X\\) whose irreducible components are at most \\(1\\)-dimension with numerical invariants \\(\beta = [Z] \in H\_{2}(X, \ZZ)\\) and \\(\chi(\mathscr{O}\_{Z}) = \chi\\).

</div>


### <span class="org-todo todo TODO">TODO</span> Symplectic resolution {#symplectic-resolution}


### <span class="org-todo todo TODO">TODO</span> Virtual fundamental class {#virtual-fundamental-class}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-01 Wed 16:57]</span></span>
The analog of [Virtual fundamental class](#virtual-fundamental-class) for stacks and orbifold.


### Calabi-Yau variety {#calabi-yau-variety}


### Donaldson-Thomas theory {#donaldson-thomas-theory}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-29 Sun 16:00]</span></span>
Cf. [Enumerative geometry](#enumerative-geometry).

We consider the case when \\({\rm dim}\_{\CC}(X) = 3\\). We fix a class \\(\beta \in H\_{2}(X, \ZZ)\\) and fix an integer \\(\chi \in \ZZ\\). The **Donaldson-Thomas theory** describes the intersection theory on [Hilbert scheme](#hilbert-scheme) of \\(X\\). Due to existence of nonvanishing higher \\({\rm Ext}\\) group, the deformation-obstruction theory and [Virtual fundamental class](#virtual-fundamental-class) of virtual fundamental class is not well-defined. To remedy the issue, we consider \\(I\_{\chi}(X, \beta)\\) parametrizing pairs \\((E, \phi)\\) such that

-   \\(E\\) is a torsion free sheaf on \\(X\\) of rank \\(1\\).
-   \\(E\\) is equipped with a trivialization \\(\phi: \det E \cong \mathbb{O}\_{X}\\).
-   The numerical invariants of \\(E\\) is given by \\(c\_{2}(E) = - \beta\\), \\(\xi(E) = \xi(\mathbb{O}\_{X}) - \chi\\).

The natural map
\\[{\rm Hilb}\_{\chi}(X, \beta) \to I\_{\chi}(X, \beta)\\]
\\[Z \to J\_{Z}\\]
is an isomorphism on the level of closed points.

The expected dimension is given by \\(\dim(\ext\_{0}^{1}(E, E)) - \dim(\ext\_{0}^{2}(E,E))\\), where \\(\ext\_{0}\\) denote the trace free subspace. So we have that \\(\virdim I\_{\chi}(X, \beta) = \chi(E, E) - \chi(\OO) = -K\_{X} \cdot \beta\\). In [Gromov-Witten theory](#gromov-witten-theory), we also have the fundamental class of dimension equal to \\(-K\_{X} \cdot \beta\\). So if \\(X\\) is [Calabi-Yau variety](#calabi-yau-variety), we have \\(\virdim I\_{\chi}(X, \beta) = 0\\).

We don't have evaluation map in Donaldson-Thomas theory, so we consider
\\[\tilde{J} \to \hilb(X) \times X\\]
for the purpose of integration. Given \\(\alpha \in H^{\*}(X)\\), we can define an operator
\\[\sigma\_{0}(\alpha): \pi\_{\hilb \*}(- \ch\_{2}(\tilde{J}) \cup \pi\_{X}^{\*}(\alpha) \cap \pi\_{\hilb}^{\*}(-)), H\_{\*}(\hilb(X)) \to H\_{\*}(\hilb(X))\\]
Then the **Donaldson-Thomas invariants** are defined by

\begin{align}\langle \alpha\_{1}, \cdots, \alpha\_{n} \rangle^{DT}\_{\beta, m} &= \deg \prod\_{k} \sigma\_{0}(\alpha\_{k})[I\_{\chi}(X, \beta)]^{vir}\\\
&= \int\_{ [I\_{\chi}(X, \beta)]^{vir}} \prod\_{k} \sigma\_{0}(\alpha\_{k}) \\\ &=
\int\_{ [I\_{\chi}(X, \beta)]^{vir}} \prod\_{k} \pi\_{\hilb \*}(- \ch\_{2}(\tilde{J}) \cup \pi\_{X}^{\*}(\alpha\_{k}) \cap \pi^{\*} \beta)\end{align}

Here note \\(-\ch\_{2}(I\_{Z}) = \beta\\) is represented by cycle class \\(Z \subset X\\).

There may be some mistakes in definition, because I suppose that the second line is not well-defined and the \\(\beta\\) in the last line is unnatural. However, I don't know the correct algebraic definition of Donaldson-Thomas theory yet. So I still follow the definition in [GW/DT Theory](https://www.bilibili.com/video/BV1Gi4y1T7ed) Lecture 11.


## Geometric representation theory {#geometric-representation-theory}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-29 Sun 15:26]</span></span>
In geometric representation theory, we tries to encode the algebra operation in geometric objects. The one of the general construction is the usage of correspondence, that is the cycles or sheaves etc in \\(X\_{1} \times X\_{2}\\). It is a nonlinear analog of matrices. To retain the linear information, we consider functors such as [Equivariant cohomology](#equivariant-cohomology) and [Equivariant K-theory](#equivariant-k-theory).


### Steinberg variety {#steinberg-variety}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-29 Sun 15:41]</span></span>
For a general symplectic resolution
\\[\pi: X \to X\_{0}\\]
we have the **Steinverg variety** \\(X \times\_{X\_{0}} X\\).


## Number Theory {#number-theory}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-31 Tue 13:34]</span></span>
There are two main themes in number theory.

-   prime number
-   Diophantine equations


### Riemann zeta function {#riemann-zeta-function}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-31 Tue 13:37]</span></span>
\\[\zeta(s) = 1 + \frac{1}{2^{s}} + \frac{1}{3^{s}} + \cdots = \prod\_{p \text{ prime}} \frac{1}{1 - p^{-s}}\\]
The function can be extend as a meromorphic function on \\(\CC\\).


### Langlands correspondence {#langlands-correspondence}



{{< figure src="/img/2021-08-31_14-02-53_screenshot.png" >}}


## Rosseta stone in mathematics {#rosseta-stone-in-mathematics}

The similarity over number fields, function fields, algebraic curves over \\(\CC\\).

## Bibliography
<a id="steinberg2012"></a>[steinberg2012] Steinberg, Representation Theory of Finite Groups: An Introductory Approach, Springer (2012). [↩](#19580479584332ed50a4af7bf7f3f201)

<a id="kirillov2016"></a>[kirillov2016] Kirillov, Quiver Representations and Quiver Varieties, American Mathematical Society (2016). [↩](#df38f5636bec59103a70400bed4764c9)

<a id="dieck2008"></a>[dieck2008] tom Dieck, Algebraic Topology, European Mathematical Society (2008). [↩](#5ad6139c99b6d2508f6ef6f11ce7f09d)
