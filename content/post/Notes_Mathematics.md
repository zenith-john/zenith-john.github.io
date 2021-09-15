+++
title = "Mathematics Notes"
author = ["Zenith John"]
date = 2021-08-31
categories = ["Mathematics"]
draft = false
lastmod = 2021-09-15
showtoc = true
+++

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
Let \\(\phi\\), \\(\rho\\) be irreducible representation of \\(G\\), and \\(T \in \Hom\_{G}(\phi, \rho)\\). Then either \\(T\\) is invertible or \\(T = 0\\).
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
\\(test formu\\)


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


### Immersion {#immersion}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:17]</span></span>
A smooth map \\(f\\) is an **immersion** if each \\(T\_{x}f\\) is injective and **submersion** if each \\(T\_{x}f\\) is surjective. Cf. [Tangent space](#tangent-space).


### Submersion {#submersion}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 18:14]</span></span>
See [Immersion](#immersion).


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
Let \\(f: M \to N\\) be an [Immersion](#immersion). We define the quotient bundle of the bundle morphism \\(i: TM \to f^{\* }TN|\_{M}\\) to be the **normal bundle**. There exists a neighborhood of the zero section of normal bundle diffeomorphic to the neighborhood of \\(N\\) in \\(M\\). The diffeomorphic map is called **tubular map** and the target is called **tubular neighborhood**.

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


### Lie derivative {#lie-derivative}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-02 Thu 10:53]</span></span>
Given a smooth covariant tensor field \\(A\\) on \\(M\\), we define the **Lie derivative** of \\(A\\) with respect to \\(V\\), denoted by \\(\mathscr{L}\_{V}A\\) by
\\[(\mathscr{L}\_{V}A)\_{p} = \frac{\dif}{\dif t} \mid\_{t = 0} (\theta\_{t}^{\* }A)\_{p}\\]
Here \\(V\\) is a smooth vector field on \\(M\\), and \\(\theta\\) is its flow. \\(\theta\_{t}\\) is locally an isomorphism.


### Connection {#connection}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-06 Mon 19:32]</span></span>
A **connection** on a [Vector bundle](#vector-bundle) \\(E \to M\\) is a linear map \\(\nabla^{E} : C^{\infty}(E) \to C^{\infty}(E \otimes T^{ \*}M)\\) satisfying the condition
\\[\nabla^{E}(\alpha e) = \alpha \nabla^{E} e + e \otimes \dif \alpha\\]
whenever \\(e \in C^{\infty}\\) is a smooth section of \\(E\\) and \\(\alpha\\) is a smooth function on \\(M\\).


### Curvature {#curvature}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-06 Mon 19:41]</span></span>
For a given [Connection](#connection) \\(\nabla^{E}\\), there exists a unique smooth section \\(R(\nabla^{E}) \in C^{\infty}(\End(E) \otimes \wedge^{2} T^{\* }M)\\) called the **curvature** of \\(\nabla^{E}\\), that satisfies the equation
\\[R(\nabla^{E}) \cdot (e \otimes v \wedge w) = \nabla\_{v}^{E} \nabla\_{w}^{E} e - \nabla\_{w}^{E} \nabla\_{v}^{E} e - \nabla^{E}\_{ [v,w]}e\\]
for all \\(v,w \in C^{\infty}( TM)\\) and \\(e \in C^{\infty}(E)\\).


### Holonomy group {#holonomy-group}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-06 Mon 19:44]</span></span>
Let \\(M\\) be a [Manifold](#manifold), \\(E\\) a [Vector bundle](#vector-bundle) over \\(M\\), and \\(\nabla^{E}\\) a [Connection](#connection) on \\(E\\). Suppose \\(\gamma: [0,1] \to M\\) is smooth, with \\(\gamma(0) = x\\) and \\(\gamma(1) = y\\), where \\(x,y \in M\\). Then for each \\(e \in E\_{x}\\) there exists a unique smooth section \\(s\\) of \\(\gamma^{\* }(E)\\) satisfying \\(\nabla\_{\dot{\gamma}(t)}^{E} s(t) = 0\\) for \\(t \in [0,1]\\) with \\(s(0) = e\\). Define \\(P\_{\gamma}(e) = s(1)\\). Then \\(P\_{\gamma}: E\_{x} \to E\_{y}\\) is a well-defined linear map called the **parallel transport map**.

Fix a point \\(x \in M\\), we define the **holonomy group** \\(\hol\_{x}(\nabla^{E}) = \\{P\_{\gamma}: \gamma \text{ is a loop based at } x\\} \subset \GL(E\_{x})\\).


#### Berger classification theorem {#berger-classification-theorem}



{{% theorem %}}
Suppose \\(M\\) is a simply connected manifold of dimension \\(n\\) and \\(g\\) is irreducible, nonsymmetric Riemannian metric on \\(M\\). Then exactly one of the following seven cases holds:

1.  \\(\hol(g) = \SO(n)\\).
2.  \\(n = 2m\\) with \\(m \geq 2\\), and \\(\hol(g) = \U(m) \subset \SO(2m)\\).
3.  \\(n = 2m\\) with \\(m \geq 2\\), and \\(\hol(g) = \SU(m) \subset \SO(2m)\\).
4.  \\(n = 4m\\) with \\(m \geq 2\\), and \\(\hol(g) = \Sp(m) \subset \SO(4m)\\).
5.  \\(n = 4m\\) with \\(m \geq 2\\), and \\(\hol(g) = \Sp(m) \Sp(1) \subset \SO(4m)\\).
6.  \\(n = 7\\) and \\(\hol(g) = G\_{2} \subset \SO(7)\\).
7.  \\(n = 8\\) and \\(\hol(g) = \Spin(7) \subset \SO(8)\\).
{{% /theorem %}}


### Poincaré lemma {#poincaré-lemma}



{{% proposition %}}
If \\(U\\) is a star-shaped open subset of \\(\RR^{n}\\) of \\(\HH^{n}\\), then every closed covector field on \\(U\\) is exact.
{{% /proposition %}}


### Riemannian metric {#riemannian-metric}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 19:29]</span></span>
A **Riemannian metric** on \\(M\\) is a smooth symmetric covariant \\(2\\)-tensor field on \\(M\\) that is positive definite at each point. A **Riemannian manifold** is a pair \\((M, g)\\), where \\(M\\) is a smooth manifold and \\(g\\) is a Riemannian metric on \\(M\\).

Cf. [Manifold](#manifold).

{{% proposition %}}
Every smooth manifold admits a Riemannian metric.
{{% /proposition %}}

{{% proof %}}
By [Numerable](#numerable) property of the smooth manifold.
{{% /proof %}}


### Wedge product {#wedge-product}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 19:39]</span></span>
For \\(w \in \Lambda^{k}(V^{\* })\\) and \\(\eta \in \Lambda^{l}(V^{\* })\\), we define the **wedge product** or **exterior product** to be
\\[\omega \wedge \eta = \frac{(k+l)!}{k!l!} {\rm Alt}(\omega \otimes \eta)\\]


### Differential form {#differential-form}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 19:42]</span></span>
A section of \\(\Lambda^{k}T^{\* }M\\) is called a **differential \\(k\\)-form**. The integer \\(k\\) is called the **degree** of the form.

Cf. [Tangent bundle](#tangent-bundle).


### Invariant formula for the exterior derivative {#invariant-formula-for-the-exterior-derivative}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 19:44]</span></span>
Let \\(M\\) be a smooth [Manifold](#manifold), and \\(\omega \in \Omega^{k}(M)\\). For any smooth vector fields \\(X\_{1}, \cdots, X\_{k + 1}\\) on \\(M\\).

\begin{align}\dif \omega (X\_{1}, \cdots, X\_{k + 1}) &= \\\ & \sum\_{1 \leq i \leq k + 1}(-1)^{i - 1}X\_{i}(\omega(X\_{1}, \cdots, \widehat{X\_{i}}, \cdots, X\_{k + 1})) \\\ & + \sum\_{1 \leq i < j \leq k + 1} (-1)^{i + j} \omega([X\_{i}, X\_{j}], X\_{1}, \cdots, \widehat{X}\_{i}, \cdots, \widehat{X\_{j}}, \cdots, X\_{k + 1})\end{align}

Cf. [Differential form](#differential-form), [Exterior derivative](#exterior-derivative).


### Exterior derivative {#exterior-derivative}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:02]</span></span>
We define the **exterior differential** of [Differential form](#differential-form)
\\[\dif (\sum\_{J} \omega\_{J} \dif x^{J}) = \sum\_{J} \dif \omega\_{J} \wedge \dif x^{J}\\]


### Cartan's magic formula {#cartan-s-magic-formula}



{{% theorem %}}
On a smooth manifold \\(M\\) for any smooth vector field \\(V\\) and any smooth differential form \\(\omega\\),
\\[\mathscr{L}\_{V} \omega = V \iprod (\dif \omega) + \dif (V \iprod \omega)\\]
{{% /theorem %}}


### Stokes's theorem {#stokes-s-theorem}



{{% theorem %}}
Let \\(M\\) be an oriented smooth \\(n\\)-manifold with boundary, and let \\(\omega\\) be a compactly generated supported smooth \\((n - 1)\\)-form on \\(M\\). Then
\\[\int\_{M} \dif \omega = \int\_{\partial M} \omega\\]
{{% /theorem %}}

Cf. [Differential form](#differential-form), [Exterior derivative](#exterior-derivative).


### de Rham cohomology {#de-rham-cohomology}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:15]</span></span>
We define the **de Rham cohomology group** in degree \\(p\\) to be the quotient vector space
\\[H\_{dR}^{p}(M) = \frac{Z^{p}(M)}{B^{p}(M)}\\]
where \\(Z^{p}(M)\\) is the closed \\(p\\)-forms on \\(M\\). then \\(B^{p}(M)\\) is the exact \\(p\\)-forms.

{{% proposition %}}
The de Rham cohomology is homotopy invariants. If \\(M\\) and \\(N\\) is homotopy equivalent manifolds, then \\(H\_{dR}^{n}(M) \cong H^{p}\_{dR}(N)\\) for each \\(p\\). The isomorphisms are induced by any smooth homotopy equivalence \\(F: M \to N\\).
{{% /proposition %}}


### de Rham theorem {#de-rham-theorem}



{{% theorem %}}
For every smooth manifold \\(M\\) and nonnegative integer \\(p\\), the de Rham homomorphism \\(J: H\_{dR}^{p}(M) \ot H^{p}(M; \RR)\\) is an isomorphism.
{{% /theorem %}}

Cf. [Singular cohomology](#singular-cohomology) and [de Rham cohomology](#de-rham-cohomology).


### Degree {#degree}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:25]</span></span>
Suppose \\(M\\) and \\(N\\) are compact, connected, [Oriented](#orientation), smooth manifolds of dimension \\(n\\), and \\(F: M \to N\\) is a smooth map. There exists a unique integer \\(k\\) called the **degree** of \\(F\\), that satisfies

1.  For every smooth \\(n\\)-form \\(\omega\\) on \\(N\\)
    \\[\int\_{M} F^{\* } \omega  = k \int\_{N} \omega\\]
2.  If \\(q\\) is a [Regular value](#regular-point) of \\(F\\), then
    \\[k = \sum\_{x \in F^{-1}(q)} \sgn(x)\\]
    where \\(\sgn(x) = 1\\) if \\(\dif F\_{x}\\) is orientation-preserving and \\(-1\\) if orientation-reversing.


### Distribution {#distribution}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:28]</span></span>
Cf. [Tangent bundle](#tangent-bundle).

A **distribution** on \\(M\\) of rank \\(k\\) is a rank \\(k\\) subbundle of \\(TM\\). It is called a **smooth** distribution if it is a smooth subbundle.


### Integral distribution {#integral-distribution}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:31]</span></span>
A nonempty immersed submanifold \\(N \subset M\\) is called an **integral manifold** of \\(D\\) if \\(T\_{p}N = D\_{p}\\) at each point \\(p \in N\\). And a [Distribution](#distribution) is called **integral** if every point of \\(M\\) is contained in an integral manifold.


### Involutive distribution {#involutive-distribution}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:32]</span></span>
The [Distribution](#distribution) \\(D\\) is **involutive** if given a pair of smooth local sections of \\(D\\), their Lie bracket is also local section of \\(D\\).


### Complete integral distribution {#complete-integral-distribution}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:35]</span></span>
Given a rank \\(k\\) [Distribution](#distribution) \\(D \subset TM\\), let us say that a smooth coordinate chart \\((U, \phi)\\) on \\(M\\) is **flat** for \\(D\\) if \\(\phi(U)\\) is a cube in \\(\RR^{n}\\) and at points of \\(U\\), \\(D\\) is spanned by the first \\(k\\) coordinate vector fields \\(\partial/ \partial x^{1}, \cdots, \partial/ \partial x^{k}\\).

A distribution \\(D \subset TM\\) is **completely integrable** if there exists a flat chart for \\(D\\) in a neighborhood of each point of \\(M\\).


### Frobenius theorem {#frobenius-theorem}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:39]</span></span>
By definition, we have [Complete integral distribution](#complete-integral-distribution) implies [Integral distribution](#integral-distribution) and integral distribution implies [Involutive distribution](#involutive-distribution). The **Frobenius theorem** suggests the reverse.

{{% theorem %}}
Every involutive distribution is completely integrable.
{{% /theorem %}}


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


### Cohomology {#cohomology}



There are various **cohomology** theories. The can be defined by common axioms.

<div class="definition">
  <div></div>

A **cohomology theory** for pairs of spaces with values in the category of \\(R\\)-modules consists of a family \\((h^{n} \mid n \in \ZZ)\\) of contravariant functors \\(h^{n}: TOP(2) \to R-MOD\\) and natural transformations \\(\delta^{n}: h^{n - 1} \circ \kappa \to h^{n}\\) such that

-   Homotopy invariance. Homotopic maps \\(f\_{0}\\) and \\(f\_{1}\\) between pairs of space induces the same homomorphism \\(h^{n}(f\_{0}) = h^{n}(f\_{1})\\).
-   Exact sequence. For each pair \\((X, A)\\), we have exact sequence
    \\[\cdots \to h^{n - 1}(A, \emptyset) \stackrel{\delta}{\to} h^{n}(X, A) \to h^{n}(X, \emptyset) \to h^{n}(A) \to \cdots \\]
-   Excision. Let \\((X, A)\\) be a pair and \\(U \subset A\\) such that \\(\bar{U} \subset A^{\circ}\\). Then the inclusion \\((X \backslash U, A \backslash U) \to (X,A)\\) induces an isomorphism \\(h^{n}(X, A) \cong h^{n}(X \backslash U, A \backslash U)\\).

</div>

Given a cohomology theory, we called \\(h^{n}(X,A)\\) the \\(n\\)-th **cohomology group**. The \\(\delta^{n}\\) are called the coboundary operator. And we write \\(h^{n}(X) := h^{n}(X, \emptyset)\\).

As in homology theory, we called \\(h^{n}(pt)\\) the coefficient groups of the theory and a cohomology theory may have following additional axioms

-   dimension axiom. \\(h^{n}(pt) = 0\\) for \\(n \neq 0\\).
-   additive axiom. \\[h^{n}(\coprod X\_{j}, \coprod A\_{j}) \to \coprod\_{j} h^{n}(X\_{j}, A\_{j})\\]
    is always an isomorphism.

Also, we have triple exact sequence
\\[ \cdots \to h^{n - 1}(A, B) \stackrel{\delta}{\to} h^{n}(X, A) \to h^{n}(X, B) \to h^{n}(A, B) \stackrel{\delta}{\to} \cdots\\]


#### <span class="org-todo todo TODO">TODO</span> Singular cohomology {#singular-cohomology}


#### Cup product {#cup-product}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-03 Fri 20:36]</span></span>
One of the most difference between homology theory and cohomology theory is the multiplicative structure on cohomology rings.
\\[h^{m}(X, A) \otimes\_{R} h^{n}(X, B) \to h^{m + n}(X, A \cap B)\\]
We call \\(x \cap y\\) the **cup product** of \\(x, y\\). The cup product is defined if \\(A\\) or \\(B\\) is empty or \\(A = B\\). We have axioms of cup product

-   Naturality: For triads \\(f:(X, A, B) \to (X'; A', B')\\) we have
    \\[f^{ \*}(x \cup y) = f^{ \*}(x) \cup f^{ \*}(y)\\]
-   Stability: TODO
-   Unit element: There is a unit \\(1 \in h^{0}(pt)\\) such that \\(1\_{X} = p^{\*}(1)\\) is the unit of multiplication in cohomology ring.
-   Associativity: \\((x \cup y) \cup z = x \cup (y \cup z)\\).
-   Commutativity: \\(x \cup y = (-1)^{\abs{x} \abs{y}} y \cup x\\). Here \\(\abs{x}\\) is the grade in the cohomology ring.


#### External product {#external-product}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-07 Tue 21:42]</span></span>
For details see, section 17.3 in <sup id="5ad6139c99b6d2508f6ef6f11ce7f09d"><a href="#dieck2008" title="tom Dieck, Algebraic Topology, {European Mathematical Society} (2008).">dieck2008</a></sup>.

The **external product** is a family of \\(R\\)-linear maps
\\[h^{m}(X, A) \otimes\_{R} h^{n}(Y, B) \to h^{m + n}((X, A) \times (Y, B)), x \otimes y \to x \times y\\]
The external products satisfying some properties.


### Reduced cohomology {#reduced-cohomology}



The **reduced cohomology groups** are defined to be \\(\tilde{h}^{n}(X) \to \coker(h^{n}(pt) \to h^{n}(X))\\) where the map is induced by \\(p: X \to pt\\).


### Mayer-Vietoris sequence {#mayer-vietoris-sequence}



There are **Mayer-Vietoris sequence** for homology and cohomology theory. For \\((A; A\_{0}, A\_{1}) \subset (X; X\_{0}, X\_{1})\\) be excisive triads that is \\(A = A\_{0}^{\circ} \cap A\_{1}^{\circ}\\) and \\(X = X\_{0}^{\circ} \cap X\_{1}^{\circ}\\). Set \\(X\_{01} = X\_{0} \cap X\_{1}\\) and \\(A\_{01} = A\_{0} \cap A\_{1}\\). Then we have exact sequence
\\[\cdots \to h^{n - 1}(X\_{01}, A\_{01}) \to h^{n}(X, A) \to h^{n}(X\_{0}, A\_{0}) \oplus h^{n}(X\_{1}, A\_{1}) \to h^{n}(X\_{01}, A\_{01}) \to \cdots\\]


## Mirror Symmetry {#mirror-symmetry}


## Algebraic Geometry {#algebraic-geometry}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-23 Mon 19:50]</span></span>
There are two tastes of algebraic geometry. The algebraic geometers view it as a specialized geometry, which is closed related to complex geometry (by GAGA), birational geometry (MMP for example), symplectic geometry (Gromov-Witten invariants) etc. Algebraic geometers are mainly interested in case where the base field is \\(\CC\\). Experts in other field may view algebraic geometry as useful languages, where vast properties are worked out by algebraic geometers. Therefore, Grothendieck's style of algebraic geometry provides many insights into number theory, representation theory etc. In both case, the characteristic \\(p\\) case is more interesting. Examples includes [Steinberg variety](#steinberg-variety), p-adic Hodge theory.

The following are the themes in Algebraic Geometry Salt Lake 2015 seminar <https://sites.google.com/site/2015summerinstitute/home/schedule> : analytic methods, birational geometry and classification, commutative algebra and computational algebraic geometry, Hodge theory, singularities and characteristic p methods, derived algebraic geometry, derived categories, geometric representation theory, Gromov-Witten and Donaldson-Thomas theories, mirror symmetry, tropical geometry, algebraic cycles, cohomology theories, p-adic Hodge theory, rational points and Diophantine problems, topology of algebraic varieties


### <span class="org-todo todo TODO">TODO</span> Morphism {#morphism}




#### Toric {#toric}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-12 Sun 20:23]</span></span>
Let \\(V\_{i} = \spec (\CC[S\_{i}])\\) be the [Affine toric variety](#affine-toric-variety) coming from the affine semigroup \\(S\_{i}\\), \\(i = 1,2\\). Then a [Morphism](#morphism) \\(\phi: V\_{1} \to V\_{2}\\) is **toric** if the corresponding map of coordinate rings \\(\phi^{\* }: \CC[S\_{2}] \to \CC[S\_{1}]\\) is induced by a [Semigroup](#semigroup) homomorphism \\(\hat{\phi}: S\_{2} \to S\_{1}\\).

A toric morphism is **equivariant**. That is
\\[\phi(t \cdot p) = \phi(t) \cdot \phi(p)\\]
for \\(t \in T\_{N}\\) and \\(p \in V\_{1}\\).


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


### <span class="org-todo todo TODO">TODO</span> Moduli space of curves {#moduli-space-of-curves}




#### Canonical line bundle {#canonical-line-bundle}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 19:47]</span></span>
Cf. [Moduli space of curves](#moduli-space-of-curves).

We now consider the **canonical line bundles** on \\(M\_{g,n}\\). We consider \\(T\_{i}^{\* } \to \bar{M}\_{g,n}\\) the line bundle determined by the cotangent space at the \\(i\\)th point and denoted by \\(\mathbb{L}\_{i}\\). We have geometric result on the canonical line bundles

{{% proposition %}}
\\(\mathbb{L}\_{i}\\) is nef on \\(\bar{M}\_{g,n}\\).
{{% /proposition %}}

We will use the standard notation \\(\psi\_{i} = c\_{1}(\mathbb{L}\_{i}) \in H^{2}(\bar{M}\_{g,n})\\).

For the forgetful map
\\[\pi: \bar{M}\_{g,n + 1} \to \bar{M}\_{g,n}\\]
we define \\(k\_{r} = \pi\_{\* } \psi\_{n + 1}^{r + 1} \in H^{2r}(\bar{M}\_{g,n})\\). Under these assumptions, we have

{{% proposition %}}
\\(H^{2}(M\_{g,n}, \mathbb{Q}) \cong \pic(M\_{g,n}, \mathbb{Q})\\) is generated by \\(k\_{1}, \psi\_{1}, \cdots, \psi\_{n}\\).
{{% /proposition %}}


#### Descent integral {#descent-integral}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 21:09]</span></span>
Following the terminology in [Canonical line bundle](#canonical-line-bundle). We define
\\[\langle \tau\_{1}^{k\_{1}} \cdots \tau\_{n}^{k\_{n}} \rangle\_{g,n} = \int\_{\bar{M}\_{g,n}} \psi\_{1}^{k\_{1}} \cdots \psi\_{n}^{k\_{n}}\\]
Here, we must make sure \\(\sum k\_{i} = 3g - 3 + n\\) and \\(2g - 2 + n \leq 0\\). Or by simplify notation, we make \\(n = \sum\_{k\_{i}} - 3g + 3\\). These integrals are called **descent integral**.


#### Witten's Conjecture {#witten-s-conjecture}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 20:43]</span></span>
Considering the [Descent integrals](#descent-integral), we have generating function
\\[F\_{g}(t\_{0}, t\_{1}, t\_{2}, \cdots) = \sum\_{\\{n\_{i}\\}} \prod\_{i = 1}^{n} \frac{t\_{i}^{n\_{i}}}{n\_{i}!} \langle \tau\_{0}^{n\_{0}}\tau\_{1}^{n\_{1}} \cdots \rangle\_{g}\\]
where the sum on right hand side is by sum over sequences with only finitely many nonzero terms. It can also be written as \\(F\_{g} = \sum\_{n = 0}^{\infty} \frac{\langle \phi^{n} \rangle\_{g}}{n!}\\), where \\(\phi = \sum\_{i = 0}^{\infty} t\_{i} \tau\_{i}\\). \\(F\_{g}\\) is the generating function that contains all integrals of \\(\psi\\) classes over all moduli spaces \\(\bar{M}\_{g,n}\\).

We can put all data for all genera together by defining
\\[F(\lambda, t) = \sum\_{g = 0}^{\infty} \lambda^{2g - 2} F\_{g}\\]
We introduce another notation
\\[\langle \langle  \tau\_{k\_{1}} \cdots \tau\_{k\_{n}} \rangle \rangle = \frac{\partial}{\partial t\_{k\_{1}}} \cdots \frac{\partial}{\partial t\_{k\_{n}}} F\\]

We have following **Witten's conjecture** and **Kontsevich's theorem**

{{% theorem %}}
For \\(n \geq 1\\), we have
\\[(2n + 1) \lambda^{-2} \langle \langle \tau\_{n} \tau\_{0}^{2} \rangle \rangle = \langle \langle \tau\_{n - 1} \tau\_{0} \rangle \rangle \langle \langle \tau\_{0}^{3} \rangle \rangle + 2 \langle \langle \tau\_{n - 1} \tau\_{0}^{2} \rangle \rangle \langle \langle \tau\_{0}^{2} \rangle \rangle + \frac{1}{4} \langle \langle \tau\_{n - 1} \tau\_{0}^{4} \rangle \rangle\\]
{{% /theorem %}}

By taking \\(U = \frac{\partial^{2} F}{\partial t\_{0}^{2}}\\) and setting \\(n = 1\\), we have KdV equation
\\[\frac{\partial U}{\partial t\_{1}} = U \frac{\partial U}{\partial t\_{0}} + \frac{1}{12} \frac{\partial^{3} U}{\partial t\_{0}^{3}}\\]


#### <span class="org-todo todo TODO">TODO</span> String equation {#string-equation}


#### <span class="org-todo todo TODO">TODO</span> Diliton equation {#diliton-equation}


#### Virasoro constraint {#virasoro-constraint}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 21:34]</span></span>
Using the same generating function as in [Witten's Conjecture](#witten-s-conjecture). We define partition function \\(Z(\lambda, t) = \exp(F)\\). Now we define a sequence of operators satisfying the [Virasoro bracket](#virasoro-bracket).
\\[L\_{n} = -\frac{(2n + 3)!!}{2 ^{n + 1}} \frac{\partial}{\partial t\_{n + 1}} + \sum\_{i = 0}^{\infty} \frac{(2i + 2n + 1)!!}{(2i - 1)!! 2 ^{n + 1}} t\_{i} \frac{\partial}{\partial t\_{i + n}} + \frac{\lambda^{2}}{2} \sum\_{i = 0}^{n - 1} \frac{(2i + 1)!! (-2i +2n - 1)!!}{2 ^{n + 1}} \frac{\partial^{2}}{\partial t\_{i} \partial t\_{n - 1 - i}}\\]
Then we have that
\\[L\_{n}(Z) = 0\\]
for \\(n \geq -1\\), which is called **Virasoro constraint**.


### Virasoro bracket {#virasoro-bracket}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 21:32]</span></span>
**Virasoro bracket** is a set of commutator relation for operators \\(L\_{n}\\) such that
\\[[L\_{n}, L\_{m}] = (n - m) L\_{n + m}\\]


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
The map \\(I\_{g,n, \beta}\\) is \\(S\_{n}\\) equivariant where \\(S^{n}\\) acts on \\(H^{\* }(X, \mathbb{Q})^{\otimes n}\\) naturally and acts on \\(H^{ \* }(\overline{M}\_{g,n}), \mathbb{Q}\\) by permuting \\(p\_{i}\\)'s  of the pointed curves.


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

\begin{align}\langle \alpha\_{1}, \cdots, \alpha\_{n} \rangle^{DT}\_{\beta, m} &= \deg \prod\_{k} \sigma\_{0}(\alpha\_{k})[I\_{\chi}(X, \beta)]^{vir} \\\ &= \int\_{ [I\_{\chi}(X, \beta)]^{vir}} \prod\_{k} \sigma\_{0}(\alpha\_{k}) \\\ &= \int\_{ [I\_{\chi}(X, \beta)]^{vir}} \prod\_{k} \pi\_{\hilb \*}(- \ch\_{2}(\tilde{J}) \cup \pi\_{X}^{\*}(\alpha\_{k}) \cap \pi^{\*} \beta)\end{align}

Here note \\(-\ch\_{2}(I\_{Z}) = \beta\\) is represented by cycle class \\(Z \subset X\\).

There may be some mistakes in definition, because I suppose that the second line is not well-defined and the \\(\beta\\) in the last line is unnatural. However, I don't know the correct algebraic definition of Donaldson-Thomas theory yet. So I still follow the definition in [GW/DT Theory](https://www.bilibili.com/video/BV1Gi4y1T7ed) Lecture 11.


### Group scheme {#group-scheme}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-07 Tue 20:42]</span></span>
A **group scheme** \\(G/S\\) is a morphism \\(\pi: G \to S\\) of schemes with \\(S\\)-morphism multiplication \\(\mu: G \times\_{S} G \to G\\), inverse \\(\beta: G \to G\\) identity \\(e: S \to G\\) satisfying associativity, law of inverse and law of identity.

A group scheme \\(G\\) action on a scheme \\(X/S\\) is given by a morphism \\(\sigma: G \times\_{S} X \to X\\) with associativity property and identity.

Let \\(f: T \to X\\) be a \\(T\\)-valued point. We have morphism \\(\phi\_{f} = \sigma \circ (1\_{G} \times f): G \times\_{S} T \to X \times\_{S} T\\). The image of \\(\phi\_{f}\\) is called the **orbit** of \\(f\\) and denoted by \\(O(f)\\). The fibre product \\(S(f)\\) is called **stabilizer** of \\(f\\). The orbit and stabilizer is the algebraic version of orbit and stabilizer in action on topological spaces.

{{< figure src="/img/2021-09-07_20-58-55_screenshot.png" >}}


### Algebraic group {#algebraic-group}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-07 Tue 20:45]</span></span>
An **algebraic group** \\(G\\) over a field \\(k\\) is a [Group scheme](#group-scheme) \\(G/k\\) which is separated and smooth.


#### Radical {#radical}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 08:52]</span></span>
<sup id="868cb56e509be613430cca58b1ead9f3"><a href="#milne2017" title="Milne, Algebraic {{Groups}}: {{The Theory}} of {{Group Schemes}} of {{Finite Type}} over a {{Field}}, {Cambridge University Press} (2017).">milne2017</a></sup> p.135

Let \\(G\\) be a connected [Algebraic group](#algebraic-group) over \\(k\\). \\(G\\) contains a largest connected solvable normal subgroup called the **radical**, \\(R(G)\\) of \\(G\\).


#### Unipotent {#unipotent}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 09:01]</span></span>
<sup id="868cb56e509be613430cca58b1ead9f3"><a href="#milne2017" title="Milne, Algebraic {{Groups}}: {{The Theory}} of {{Group Schemes}} of {{Finite Type}} over a {{Field}}, {Cambridge University Press} (2017).">milne2017</a></sup> p.135

An [Algebraic group](#algebraic-group) \\(G\\) is said to be **unipotent** if every nonzero representation of \\(G\\) has a nonzero fixed point. Or equivalently speaking, every finite-dimensional representation \\(r: G \to \GL\_{V}\\) there is a basis such that \\(r(G) \subset \U\_{n}\\).


#### Unipotent radical {#unipotent-radical}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 09:01]</span></span>
<sup id="868cb56e509be613430cca58b1ead9f3"><a href="#milne2017" title="Milne, Algebraic {{Groups}}: {{The Theory}} of {{Group Schemes}} of {{Finite Type}} over a {{Field}}, {Cambridge University Press} (2017).">milne2017</a></sup> p.135

The **unipotent radical** of \\(G\\) is the largest connected normal unipotent sub-[Algebraic group](#algebraic-group) of \\(G\\), denoted by \\(R\_{u}(G)\\).

Cf. [Radical](#radical).


#### Semisimple {#semisimple}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 08:50]</span></span>
<sup id="868cb56e509be613430cca58b1ead9f3"><a href="#milne2017" title="Milne, Algebraic {{Groups}}: {{The Theory}} of {{Group Schemes}} of {{Finite Type}} over a {{Field}}, {Cambridge University Press} (2017).">milne2017</a></sup> p.135

An [Algebraic group](#algebraic-group) is called **semisimple** if \\(R(G\_{k^{a}})\\) is trivial, where \\(k^{a}\\) is the algebraic closure of \\(k\\).

Cf. [Radical.](#radical)


#### Reductive {#reductive}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 08:49]</span></span>
<sup id="868cb56e509be613430cca58b1ead9f3"><a href="#milne2017" title="Milne, Algebraic {{Groups}}: {{The Theory}} of {{Group Schemes}} of {{Finite Type}} over a {{Field}}, {Cambridge University Press} (2017).">milne2017</a></sup> p.135

An [Algebraic group](#algebraic-group) is called **reductive** if \\(R\_{u}(G\_{k^{a}})\\) is trivial, where \\(k^{a}\\) is the algebraic closure of \\(k\\).

Cf. [Unipotent radical](#unipotent-radical).


### Categorical quotient {#categorical-quotient}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-07 Tue 20:59]</span></span>
Given an action \\(\sigma\\) of \\(G/S\\) on \\(X/S\\), a pair \\((Y, \phi: X \to Y)\\)  is called a **categorical quotient** if we have diagram

![](/img/2021-09-07_21-01-38_screenshot.png)
commutes and universal property that for any \\((Z, \psi)\\) satisfying the above diagram, there exists a unique morphism \\(\chi: Y \to Z\\) such that \\(\psi = \chi \circ \phi\\).

A categorical quotient is called **universal** if it is stable under base change, and is called **uniform** if it is stable under flat base change.


### Geometric quotient {#geometric-quotient}



Given an action \\(\sigma\\) of \\(G/S\\) on \\(X/S\\), a pair \\((Y, \phi: X \to Y)\\)  is called a **categorical quotient** if we have

-   diagram

    ![](/img/2021-09-07_21-01-38_screenshot.png)
    commutes.
-   \\(\phi\\) is surjective and image of \\(\Psi = \phi\_{\id\_{X}}\\) is \\(X \times\_{S} X\\) (equivalently the geometric fiber of \\(\phi\\) are precisely the orbits of the geometric points of \\(X\\) for geometric points over an algebraic closed field of sufficiently high transcendence degree).
-   \\(\phi\\) is submersion that is \\(U \subset Y\\) is open if and only if \\(\phi^{-1}(U)\\) is open in \\(X\\).
-   The fundamental sheaf \\(\OO\_{Y}\\) is the subsheaf of \\(\phi\_{\* }(\OO\_{X})\\) consisting of invariant functions, i.e., if \\(f \in \Gamma(U, \phi\_{\* }(\OO\_{X})) = \Gamma(\phi^{-1}(U), \OO\_{X})\\), then \\(f \in \Gamma(U, \OO\_{Y})\\) if and only if

    {{< figure src="/img/2021-09-07_21-12-48_screenshot.png" >}}

commutes, where \\(F\\) is the function induced by \\(f\\).

A geometric quotient is called **universal** if it is stable under base change, and is called **uniform** if it is stable under flat base change.

The geometric quotient is related to [Categorical quotient](#categorical-quotient) by the following proposition.

{{% proposition %}}
Given an action \\(\sigma\\) of \\(G/S\\) over \\(X/S\\), and \\((Y, \phi)\\) is a geometric quotient. Then \\((Y, \phi)\\) is also a categorical quotient and hence unique. If \\((Y, \phi)\\) is the universal geometric quotient, then it is also a universal categorical quotient.
{{% /proposition %}}


### Character (of a torus) {#character--of-a-torus}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 19:50]</span></span>
A **character** of a [Torus](#torus) is a group homomorphism \\(\chi: T \to \CC^{\* }\\).


### Torus {#torus}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 19:51]</span></span>
A torus is \\(\CC^{\* n}\\).

The following proposition is useful in toric geometry. The image of a torus in a torus is also a torus.

{{% proposition %}}
Let \\(T\_{1}\\) and \\(T\_{2}\\) be tori, and \\(\Phi: T\_{1} \to T\_{2}\\) a group homomorphism and morphism of varieties. Then the image of \\(\Phi\\) is a torus and closed in \\(T\_{2}\\).
{{% /proposition %}}

A group subvariety of a torus is a torus.

{{% proposition %}}
If \\(H \subset T\\) is an irreducible group subvariety of \\(T\\). Then \\(H\\) is a torus.
{{% /proposition %}}


### <span class="org-todo todo TODO">TODO</span> Toric variety {#toric-variety}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:08]</span></span>
The toric variety is a field connecting algebraic geometry, combinatorial and mathematical physics. Our main reference is <sup id="8a8485591c9ae40ab7e9a4d136fca3d2"><a href="#cox2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">cox2011</a></sup>.

Cf. [Affine toric variety](#affine-toric-variety)


### Affine toric variety {#affine-toric-variety}



<div class="definition">
  <div></div>

An **affine toric variety** is an irreducible affine variety \\(V\\) containing a [Torus](#torus) \\(T\_{N} \cong (\CC^{\* })^{n}\\) as a Zariski open subset such that the action of \\(T\_{N}\\) on itself extends to an action on \\(V\\).

</div>

There are several ways of constructing toric varieties. First, consider a finite subset \\(\mathscr{A} = \\{\chi^{1}, \cdots, \chi^{l}\\} \subset \ZZ^{n}\\) a lattice equivalent to the character of a torus \\((\CC^{\* })^{n}\\). Then we may consider a map \\(\Phi\_{\mathscr{A}}(t) = (\chi^{1}(t), \cdots, \chi^{l}(t)), T\_{N} \to \CC^{s}\\). The Zariski closure of the image is a toric variety denoted by \\(Y\_{\mathscr{A}}\\). The ideal of the affine toric variety is a [Toric ideal](#toric-ideal). Detailed construction can see <sup id="8a8485591c9ae40ab7e9a4d136fca3d2"><a href="#cox2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">cox2011</a></sup> p.14-15.

Another construction concerns [Affine semigroup](#affine-semigroup). given a affine semigroup \\(S\\), we have \\(\CC[S] = \\{\sum\_{m \in S} c\_{m} \chi^{m} \mid c\_{m} \in \CC \text{ and } c\_{m} = 0 \text{ for all but finitely many } m\\}\\), where \\(\chi^{m}\\) is dependent on the embedding into the lattice \\(M\\). The multiplication is induced by \\(\chi^{m} \cdot \chi^{m'} = \chi^{m + m'}\\). We have

{{% proposition %}}
Let \\(S \subset M\\) be an affine semigroup. Then:

1.  \\(\CC[S]\\) is an integral domain and finitely generated as \\(\CC\\)-algebra.
2.  \\(\spec \CC[S]\\) is an affine toric variety. If \\(S = \NN \mathscr{A}\\) for a finite set \\(\mathscr{A} \subset M\\), then we have \\(\spec \CC[S] = Y\_{\mathscr{A}}\\).
{{% /proposition %}}

The above construction are equivalent in the sense

{{% proposition %}}
Let \\(V\\) be an affine variety. The followings are equivalent:

1.  \\(V\\) is an affine toric variety.
2.  \\(V = Y\_{\mathscr{A}}\\) for some finite set \\(\mathscr{A}\\) in a lattice.
3.  \\(V\\) is an affine variety defined by a toric ideal.
4.  \\(V = \spec \CC[S]\\) for an affine semigroup \\(S\\).
{{% /proposition %}}

We consider the relation between sublattice variety and original variety. (<sup id="8a8485591c9ae40ab7e9a4d136fca3d2"><a href="#cox2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">cox2011</a></sup> Proposition 1.3.18) For \\(N'\\) have finite index in \\(N\\) a sublattice and quotient \\(G = N/N'\\) and \\(\sigma \subset N\_{\RR}' = N\_{\RR}\\) be a [Strongly convex](#strongly-convex) [Rational](#rational) [Polyhedral cone](#polyhedral-cone). Then we have

1.  There are natural isomorphisms
    \\[G \cong \Hom\_{\ZZ}(M'/M, \CC^{\* }) = \ker(T\_{N'} \to T\_{N})\\]
2.  \\(G\\) acts on \\(\CC[\sigma^{\vee} \cap M']\\) and
    \\[\CC[\sigma^{\vee} \cap M']^{G} = \CC[\sigma^{\vee} \cap M]\\]
3.  We have bijection
    \\[U\_{\sigma, N'}/G \cong U\_{\sigma, N}\\]

That is the original variety is [Geometric quotient](#geometric-quotient) of the sublattice varieties.


### Different characters may give same toric variety {#different-characters-may-give-same-toric-variety}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:26]</span></span>
Exercise 1.1.6 in <sup id="8a8485591c9ae40ab7e9a4d136fca3d2"><a href="#cox2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">cox2011</a></sup>. We consider two map
\\[\Phi\_{1}(s,t) = (s^{2}, st, st^{3}), \quad \Phi\_{2}(s,t) = (s^{3}, st, t^{3})\\]
We can show that \\(\Phi\_{1}\\) and \\(\Phi\_{2}\\) gives same affine toric variety. However \\(\Phi\_{2}\\) is surjective and \\(\Phi\_{1}\\) is not.


### Non-normal toric variety {#non-normal-toric-variety}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:08]</span></span>
[Toric variety](#toric-variety) is not necessarily normal. For example, \\(\spec \CC[x,y]/(x^{2} - y^{3})\\).


### Lattice {#lattice}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:03]</span></span>
A **lattice** is a free abelian group of finite rank.


### Lattice ideal {#lattice-ideal}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:03]</span></span>
Let \\(L \subset \ZZ^{s}\\) be a sublattice. Then we call the ideal \\(I\_{L} = \langle x^{\alpha} - x^{\beta} \mid \alpha, \beta \in \NN^{s} \text{ and } \alpha - \beta \in L \rangle\\) **lattice ideal**.

Cf. [Lattice](#lattice).


### Toric ideal {#toric-ideal}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:05]</span></span>
A prime [Lattice ideal](#lattice-ideal) is called **toric ideal**.

We have following criterion for toric ideal.

{{% proposition %}}
An ideal \\(I \subset \CC[x\_{1}, \cdots, x\_{s}]\\) is toric if and only if it is prime and generated by binomials.
{{% /proposition %}}


### Semigroup {#semigroup}




#### Affine semigroup {#affine-semigroup}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:17]</span></span>
An **affine semigroup** is a [Semigroup](#semigroup) where the binary operation is commutative, finite generated, and can be embedded in a [Lattice](#lattice) \\(M\\).


#### Irreducible {#irreducible}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:26]</span></span>
An element in a [Semigroup](#semigroup) is called **irreducible** if \\(m = m' + m''\\) in the semigroup, then we have \\(m' = 0\\) or \\(m'' = 0\\).


#### Pointed {#pointed}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-12 Sun 19:24]</span></span>
A **pointed** affine semigroup \\(S\\) is the [Affine semigroup](#affine-semigroup) such that \\(S \cap (-S) = \\{0\\}\\).

The pointed affine semigroup is related to [Affine toric variety](#affine-toric-variety) by the following proposition.

{{% proposition %}}
If we write \\(V = \spec(\CC[S])\\), then the torus action has a fixed point if and only if \\(S\\) is pointed. What's more, the fixed point is unique and given by semigroup homomorphism
\\(\phi:S \to \CC\\) defined by
\\[m \to \begin{cases} 1 & m = 0 \\\ 0 & m \neq 0 \end{cases} \\]
{{% /proposition %}}


#### Saturated {#saturated}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-12 Sun 19:44]</span></span>
An [Affine semigroup](#affine-semigroup) \\(S \subset M\\) is **saturated** if for all \\(k \in \NN \backslash \\{0\\}\\) and \\(m \in M\\), \\(km \in S\\) implies \\(m \in S\\). (<sup id="8a8485591c9ae40ab7e9a4d136fca3d2"><a href="#cox2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">cox2011</a></sup> p.37)

One important source of the saturated affine semigroup is \\(S\_{\sigma} = \sigma^{\vee} \cap M\\) where \\(\sigma\\) is a [Strongly convex](#strongly-convex) [Rational](#rational) [Polyhedral cone](#polyhedral-cone).

The saturated affine semigroup is related to normal [Affine toric variety](#affine-toric-variety). (<sup id="8a8485591c9ae40ab7e9a4d136fca3d2"><a href="#cox2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">cox2011</a></sup> Theorem 1.3.5)

{{% theorem %}}
Let \\(V\\) be an affine toric variety with torus \\(T\_{N}\\). Then \\(V\\) is normal if and only if \\(V = \spec(\CC[S])\\), where \\(S \subset M\\) is a saturated affine semigroup.
{{% /theorem %}}


### Pure {#pure}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:29]</span></span>
\\(E\\) is **pure of dimension** \\(d\\) if \\(\dim F = d\\) for all non-trivial coherent subsheaves \\(F \subset E\\).


### Torsion filtration {#torsion-filtration}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:30]</span></span>
The **torsion filtration** of a coherent sheaf \\(E\\) is the unique filtration
\\[0 \subset T\_{0}(E) \subset \cdots \subset T\_{d}(E) = E\\]
where \\(d = \dim(E)\\) and \\(T\_{i}(E)\\) is the maximal subsheaf of \\(E\\) of dimension \\(\geq i\\).


### Homological dimension {#homological-dimension}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:29]</span></span>
Let \\(M\\) be a module of a local ring \\(A\\). The **homological dimension** denoted by \\(\dh(M)\\) is defined as the minimal length of a projective resolution of \\(M\\). It is also the length of free resolution of \\(M\\).


### Regular sequence {#regular-sequence}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:47]</span></span>
Let \\(M\\) be a module over a local ring \\(A\\). An element \\(a \in \mathfrak{m}\\) of \\(A\\) is called **\\(M\\)-regular** if \\(m \to am\\) is injective morphism. A sequence \\(a\_{1}, \cdots, a\_{l} \in \mathfrak{m}\\) is a **\\(M\\)-regular sequence** if \\(a\_{i}\\) is \\(M/(a\_{1}, \cdots, a\_{i - 1}) M\\) regular for all \\(i\\).

The definition can be generalized to sheaf theoretic language. Let \\(X\\) be a Noetherian scheme, let \\(E\\) be a coherent sheaf on \\(X\\) and \\(L\\) a line bundle on \\(X\\). A section \\(s \in H^{0}(X, L)\\) is called **\\(E\\)-regular** if and only if \\(E \otimes L^{\vee} \stackrel{\cdot s}{\to} E\\) is injective. A sequence \\(s\_{1}, \cdots, s\_{l} \in H^{0}(X, L)\\) is called **\\(E\\)-regular** similarly in the module theoretic language.


### Depth {#depth}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:34]</span></span>
The maximal length of an \\(M\\)-[Regular sequence](#regular-sequence) is called the **depth** of \\(M\\).


### Auslander-Buchsbaum formula {#auslander-buchsbaum-formula}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:32]</span></span>
Let \\(A\\) be a regular ring, then we have
\\[\dh(M) + \depth(M) = \dim (A)\\]
Cf. [Homological dimension](#homological-dimension), [Depth](#depth).


### Generalized Serre's condition {#generalized-serre-s-condition}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:37]</span></span>
We define the **generalized Serre's condition** \\(S\_{k,c}\\) as
\\[\depth(E\_{x} \geq \min \\{k, \dim(\OO\_{X,x}) - c\\}) \text{ for all } x \in \supp(E)\\]


### <span class="org-todo todo TODO">TODO</span> Spectral sequence {#spectral-sequence}


### Dual sheaf {#dual-sheaf}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:39]</span></span>
Let \\(E\\) be a coherent sheaf of codimension \\(c\\). The **dual sheaf** is defined as \\(E^{D} = \Ext^{c}\_{X} (E, \omega\_{X})\\).


### Reflexive {#reflexive}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:39]</span></span>
A coherent sheaf \\(E\\) of codimension \\(c\\) is called **reflexive** if \\(\theta\_{E}: E \to E^{DD}\\) is an isomorphism. \\(E^{DD}\\) is called the **reflexive hull**  of \\(E\\).

Cf. [Dual sheaf](#dual-sheaf).


### Torsion free {#torsion-free}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:52]</span></span>
A coherent sheaf \\(E\\) is called **torsion free** if for each \\(x \in X\\) and \\(s \in \OO\_{X,x} \backslash \\{0\\}\\) the multiplication by \\(s\\) induces a injective morphism \\(E\_{x} \to E\_{x}\\).


### Determinant bundle {#determinant-bundle}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:50]</span></span>
If \\(E\\) is locally free of rank \\(s\\), then the **determinant bundle** \\(\det(E)\\) is by definition the line bundle \\(\wedge^{s}(E)\\). Let \\(E\\) be arbitrary coherent sheaf. Then we consider a finite locally free resolution
\\[0 \to E\_{n} \to \cdots \to E\_{0} \to E \to 0\\]
And define \\(\det(E) = \otimes \det(E\_{i})^{(-1)^{i}}\\).

If \\(\dim(E) \leq \dim(X) - 2\\), then we have that \\(\det(E) \cong \OO\_{X}\\).


### Polyhedral cone {#polyhedral-cone}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 19:48]</span></span>
A **convex polyhedral cone** in a real vector space \\(N\_{\RR}\\) is a set of the form
\\[\sigma = \cone(S) = \\{\sum\_{u \in S} \lambda\_{u} u \mid \lambda\_{u} \geq 0\\}\\]
where \\(S \subset N\_{\RR}\\) is finite. And we say that \\(\sigma\\) is generated by \\(S\\). In particular, we define \\(\cone(\emptyset) = \\{0\\}\\).

The **dimension** of polyhedral cone is the dimension of the minimal linear space containing the cone.


#### Polytope {#polytope}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 19:57]</span></span>
A **polytope** in \\(N\_{\RR}\\) is a set of the form
\\[P = \conv(S) = \\{\sum\_{u \in S} \lambda\_{u}u \mid \lambda\_{u} \geq 0, \sum\_{u \in S} \lambda\_{u} = 1\\}\\]
where \\(S \subset N\_{\RR}\\) is finite. We say that \\(P\\) is the **convex hull** of \\(S\\).

Cf. [Polyhedral cone](#polyhedral-cone).


#### Dual cone {#dual-cone}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 19:59]</span></span>
Given a [Polyhedral cone](#polyhedral-cone) \\(\sigma \in N\_{\RR}\\), we have a **dual cone** in dual space \\(M\_{\RR}\\) of \\(N\_{RR}\\),
\\[\sigma^{\vee} = \\{m \in M\_{\RR} \mid \langle m, n \rangle \geq 0 \text{ for all } u \in \sigma\\}\\]

Obviously, we have \\((\sigma^{\vee})^{\vee} = \sigma\\).


#### Supporting hyperplane {#supporting-hyperplane}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:01]</span></span>
For \\(m \in M\_{\RR}\\), the dual space of \\(N\_{\RR}\\), We define \\(H\_{m} = \\{u \in N\_{\RR} \mid \langle m,n \rangle = 0\\}\\), and \\(H\_{m}^{+ } = \\{u \in N\_{\RR} \mid \langle m, n \rangle \geq 0\\}\\). We call \\(H\_{m}\\) a **supporting hyperplane** of a [Polyhedral cone](#polyhedral-cone) \\(\sigma\\) if we have \\(\sigma \subset H\_{m}^{+}\\) and \\(H\_{m}^{ +}\\) is then called supporting half-space.


#### Face {#face}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:04]</span></span>
A **face** of a cone of the [Polyhedral cone](#polyhedral-cone) \\(\sigma\\) is \\(\tau = H\_{m} \cap \sigma\\) for some \\(m \in \sigma^{\vee}\\) and \\(H\_{m}\\) is the [Supporting hyperplane](#supporting-hyperplane). We may write as \\(\tau \preceq \sigma\\). If \\(\tau \neq \sigma\\), we called \\(\tau\\) the **proper face** and write \\(\tau \prec \sigma\\). A **facet** is a face of codimension \\(1\\) and an **edge** is a face of dimension \\(1\\).

The faces of the [Strongly convex](#strongly-convex) [Rational](#rational) [Polyhedral cone](#polyhedral-cone) gives affine open subset of the [Affine toric variety](#affine-toric-variety). (<sup id="8a8485591c9ae40ab7e9a4d136fca3d2"><a href="#cox2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">cox2011</a></sup> Proposition 1.3.16)

{{% proposition %}}
Let \\(\tau\\) be a face of strongly convex rational polyhedral cone \\(\sigma\\) and \\(\tau = H\_{m} \cap \sigma\\) for some \\(m \in \sigma^{\vee} \cap M\\). Then we have
\\[\CC[S\_{\tau}] = \CC[S\_{\sigma}]\_{\chi^{m}}\\]
{{% /proposition %}}


#### Dual face {#dual-face}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:09]</span></span>
Given a [Face](#face) \\(\tau \preceq \sigma\\), we have
\\[\tau^{\perp} = \\{m \in M\_{\RR} \mid \langle m,n \rangle = 0 \text{ for all } u \in \tau\\}\\]
and the **dual face** is defined as
\\[\tau^{\* } = \sigma^{\vee} \cap \tau^{\perp}\\]

Cf. [Polyhedral cone](#polyhedral-cone).


#### Relative interior space {#relative-interior-space}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:11]</span></span>
The **relative interior space** of a [Polyhedral cone](#polyhedral-cone) \\(\sigma\\) is the interior of the cone with respect to the minimal linear space containing it. The terminology is useful, since we may consider the cone with less dimension than the ambient linear space.


#### Strongly convex {#strongly-convex}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:13]</span></span>
A [Polyhedral cone](#polyhedral-cone) is called **strongly convex** if the origin is a face of the cone. Or equivalently speaking we have \\(\sigma \cap (- \sigma) = \\{0\\}\\).


#### Separation lemma {#separation-lemma}



{{% lemma %}}
Let \\(\sigma\_{1}, \sigma\_{2}\\) be polyhedral cones in \\(N\_{\RR}\\), and they meet along a common face \\(\tau = \sigma\_{1} \cap \sigma\_{2}\\). Then we have
\\[\tau = H\_{m} \cap \sigma\_{1} = H\_{m} \cap \sigma\_{2}\\]
for some \\(m\\) in the dual space of \\(N\_{\RR}\\).
{{% /lemma %}}

Cf. [Supporting hyperplane](#supporting-hyperplane), [Polyhedral cone](#polyhedral-cone).


#### Rational {#rational}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:16]</span></span>
A [Polyhedral cone](#polyhedral-cone) is called **rational** if by equating \\(N\_{\RR} = N \otimes\_{\ZZ} \RR\\), where \\(N\\) is a [Lattice](#lattice), we have \\(\sigma = \cone(S)\\) for \\(S \in N\\).

For rational cone, \\(\rho \subset \sigma\\) an edge, the generator of \\(\rho \cap N\\) is called **ray generator** of \\(\rho\\).


#### Smooth {#smooth}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:20]</span></span>
A [Strongly convex](#strongly-convex), [Rational](#rational) [Polyhedral cone](#polyhedral-cone) is called **smooth** or **regular** if its minimal generators form part of a \\(\ZZ\\)-basis of \\(N\\).

The following theorem justify the above name. (<sup id="8a8485591c9ae40ab7e9a4d136fca3d2"><a href="#cox2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">cox2011</a></sup> Theorem 1.3.12)

{{% theorem %}}
Let \\(\sigma \subset N\_{\RR}\\) be a strongly convex rational polyhedral cone. Then \\(U\_{\sigma}\\) is smooth if and only if \\(\sigma\\) is smooth. Furthermore, all smooth affine varieties are of this form.
{{% /theorem %}}


#### Simplicial {#simplicial}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:24]</span></span>
A [Strongly convex](#strongly-convex), [Rational](#rational) [Polyhedral cone](#polyhedral-cone) is called **simplicial** if its minimal generators are linearly independent over \\(\RR\\).


### <span class="org-todo todo TODO">TODO</span> Sheaf {#sheaf}




#### Euler characteristic {#euler-characteristic}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:33]</span></span>
The **Euler characteristic** of a sheaf \\(E\\) is
\\[\chi(E) = \sum (-1)^{i} h^{i}(X, E)\\]


#### Hilbert polynomial {#hilbert-polynomial}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:34]</span></span>
The **Hilbert polynomial** is the function
\\[P(E,m): m \to \chi(E \otimes \OO(m))\\]

For Hilbert polynomial \\(P(E, m) = \sum\_{i = 0}^{\dim(E)} \alpha\_{i}(E) \frac{m^{i}}{i!}\\), we
define **reduced Hilbert polynomial** as
\\[p(E)= P(E)/ \alpha\_{d}(E) \\]


#### Multiplicity {#multiplicity}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:37]</span></span>
For [Hilbert polynomial](#hilbert-polynomial) \\(P(E, m) = \sum\_{i = 0}^{\dim(E)} \alpha\_{i}(E) \frac{m^{i}}{i!}\\), and \\(E \neq 0\\), the leading coefficient \\(\alpha\_{\dim(E)}(E)\\) is called **multiplicity**.


#### Rank {#rank}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:38]</span></span>
For [Hilbert polynomial](#hilbert-polynomial) \\(P(E, m) = \sum\_{i = 0}^{\dim(E)} \alpha\_{i}(E) \frac{m^{i}}{i!}\\), and \\(\dim(E) = \dim(X) = d\\),
\\[\rk(E) := \frac{\alpha\_{d}(E)}{\alpha\_{d}(\OO\_{X})}\\]


#### Stable {#stable}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:40]</span></span>
We write \\(p\_{1} \leq p\_{2}\\) for two polynomials if \\(p\_{1}(x) \leq p\_{2}(x)\\) when \\(x \gg 0\\).

A coherent sheaf \\(E\\) of dimension \\(d\\) is **semistable** if \\(E\\) is [Pure](#pure) and for any proper subsheaf \\(F \subset E\\), one has \\(p(F) \leq p(E)\\). And is **stable** if \\(E\\) is semistable and \\(p(F) < p(E)\\)

{{% proposition %}}
Let \\(F\\) and \\(G\\) be semistable purely \\(d\\)-dimensional sheaves. If \\(p(F) \geq p(G)\\) then \\(\Hom(F, G) = 0\\). If \\(p(F) = p(G)\\) and \\(f: F \to G\\) non-trivial, then \\(f\\) is injective if \\(F\\) is stable and surjective if \\(G\\) is stable. If \\(p(F) = p(G)\\) and \\(\alpha\_{d}(F) = \alpha\_{d}(G)\\) then any non-trivial homomorphism \\(f: F \to G\\) is an isomorphism provided \\(F\\) or \\(G\\) is stable.
{{% /proposition %}}

{{% corollary %}}
If \\(E\\) is a stable sheaf, then \\(\End(E)\\) is a finite dimensional division algebra over \\(k\\). In particular if \\(k\\) is algebraically closed, then \\(\End(E) \cong k\\).
{{% /corollary %}}


#### Geometrically stable {#geometrically-stable}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:40]</span></span>
A coherent sheaf \\(E\\) is **geometrically stable** if for any base field extension \\(X\_{K} = X \times\_{k} \spec(K) \to K\\) the pull-back \\(E \otimes\_{k} K\\) is [Stable](#stable).


#### &mu;-stable {#and-mu-stable}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:41]</span></span>
Let \\(E\\) a coherent sheaf of dimension \\(d = \dim X\\) with [Hilbert polynomial](#hilbert-polynomial) \\(P(E, m) = \sum\_{i = 0}^{\dim(E)} \alpha\_{i}(E) \frac{m^{i}}{i!}\\). We define the **degree** of \\(E\\) by
\\[\deg(E) := \alpha\_{d - 1}(E) - \rk(E) \cdot \alpha\_{d - 1}(\OO\_{X})\\]
and its **slope** by
\\[\mu(E) := \frac{\deg(E)}{\rk(E)}\\]

A coherent sheaf \\(E\\) of dimension \\(d\\) is **\\(\mu\\)-(semi)stable** if \\(T\_{d - 2}(E) = T\_{d - 1}E\\) and \\(\mu(F)(\leq)\mu(E)\\) for all subsheaves \\(F \subset E\\) with \\(0 < \rk(F) < \rk(E)\\).

{{% lemma %}}
\\(E\\) is \\(\mu\\)-stable \\(\Rightarrow\\) \\(E\\) is stable \\(\Rightarrow\\) \\(E\\) is semistable \\(\Rightarrow\\) \\(E\\) is \\(\mu\\)-semistable.
{{% /lemma %}}


### Extension {#extension}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 20:28]</span></span>
See <sup id="7cd3e01b28c2ede526fee96d60981f02"><a href="#sernesi2006" title="Sernesi, Deformations of {{Algebraic Schemes}}, {Springer Berlin Heidelberg} (2006).">sernesi2006</a></sup> p.9.

Let \\(A \to R\\) be a ring homomorphism. An \\(A\\)-\*extension\* of \\(R\\) by \\(I\\) is an exact sequence
\\[(R', \phi) : 0 \to I \to R' \stackrel{\phi}{\to} R \to 0\\]
where \\(R'\\) is an \\(A\\)-algebra and \\(\phi\\) is a homomorphism of \\(A\\)-algebras whose kernel \\(I\\) is an ideal of \\(R'\\) satisfying \\(I^{2} = (0)\\) which makes \\(I\\) a \\(R\\)-module.

Two extensions are **isomorphic** if the following diagram commutes:

![](/img/2021-09-15_21-06-15_screenshot.png)
Here \\(\chi\\) is an isomorphism of \\(A\\)-algebras. Similarly, we can define the **homomorphism** of extensions.

{{% remark %}}
Here \\(R'\\) has to be an \\(A\\)-algebras, and therefore rings. And \\(\chi\\) has to be algebra homomorphism. Instead \\(I\\) only has \\(R\\)-module structure and may not be rings in general.
{{% /remark %}}

The \\(A\\)-extension \\((R', \phi)\\) is called **trivial** if it has a section, that is we have ring homomorphism \\(\psi :R \to R'\\) such that \\(\phi \circ \phi = 1\_{R}\\). In that case, we say \\((R', \phi)\\) **splits** and \\(\psi\\) is called a **splitting**.

Examples: dual number, small extension. See <sup id="7cd3e01b28c2ede526fee96d60981f02"><a href="#sernesi2006" title="Sernesi, Deformations of {{Algebraic Schemes}}, {Springer Berlin Heidelberg} (2006).">sernesi2006</a></sup> p.11.

The extension of algebras can be extended to extension of schemes. An **extension** of \\(X/S\\) is a closed immersion \\(X \subset X'\\), where \\(X'\\) is an \\(S\\)-scheme, defined by a sheaf of ideals \\(\mathscr{I} \subset \mathscr{O}\_{X'}\\) such that \\(\mathscr{I}^{2} = 0\\). The **isomorphism**, **homomorphism**, **triviality**, and \\(\ex(X/S, \mathscr{I})\\) is similar to the algebra case. For details, see <sup id="7cd3e01b28c2ede526fee96d60981f02"><a href="#sernesi2006" title="Sernesi, Deformations of {{Algebraic Schemes}}, {Springer Berlin Heidelberg} (2006).">sernesi2006</a></sup> p.15. (Cf. [Ex\_A(R,I)](#ex-a--r-i) and [Exact sequence about extensions](#exact-sequence-about-extensions))

In particular, we have following theorem relating the deformation to the \\(\ext\\) groups.

{{% theorem %}}
Let \\(X \to S\\) be a morphism of finite type of schemes and \\(\mathscr{I}\\) a coherent locally free sheaf on \\(X\\). Suppose that \\(X\\) reduced and \\(S\\)-smooth on a dense open subset. Then there is a cononical equivalence
\\[\ex(X/S, \mathscr{I}) = \ext^{1}\_{\mathscr{O}\_{X}}(\Omega\_{X/S}^{1}, \mathscr{I})\\]
which maps the extension
\\[\mathscr{E}: 0 \to \mathscr{I} \to \OO\_{X'} \to \OO\_{X} \to 0\\]
to
\\[c\_{\mathscr{E}}: 0 \to \mathscr{I} \to (\Omega^{1}\_{X'/S})|\_{X} \to \Omega^{1}\_{X/S} \to 0\\]
{{% /theorem %}}


### Ex\_A(R,I) {#ex-a--r-i}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 21:15]</span></span>
See <sup id="7cd3e01b28c2ede526fee96d60981f02"><a href="#sernesi2006" title="Sernesi, Deformations of {{Algebraic Schemes}}, {Springer Berlin Heidelberg} (2006).">sernesi2006</a></sup> p.12.

We now consider all isomorphism class of \\(A\\)-[Extensions](#extension) of \\(R\\) by \\(I\\), called \\(\ex\_{A}(R,I)\\). We want to show that \\(\ex\_{A}(R, I)\\) is an \\(R\\)-module. We first construct the **pullback** and **pushout** for extensions. We define the pullback, denoted by \\(f^{\* }(R', \phi)\\) by following diagram:

![](/img/2021-09-15_21-22-39_screenshot.png)
And define the pushout by the other, denoted by \\(\lambda\_{\*}(R', \phi)\\):

![](/img/2021-09-15_21-23-05_screenshot.png)
Where
\\[R' \coprod\_{I} J = \frac{R' \tilde{\oplus} J}{\\{(- \alpha(i), \lambda(i)), i \in I\\}}\\]

Now we are ready to define the \\(R\\)-module structure on \\(\ex\_{A}(R, I)\\). If \\(r \in R\\), we define \\(r[R', \phi] = [r\_{\* }(R', \phi)]\\) where \\(r: I \to I\\) is multiplication by \\(r\\). And for some, we consider \\(R' \times\_{R} R''\\) as the extension of \\(R\\) by \\(I \oplus I\\). And consider the pushout of the function \\(\delta: I \oplus I \to I\\), such that \\(\delta(i \oplus j) = i + j\\).

By above construction, \\(\ex\_{A}(R, -)\\) is a covariant functor from \\(R\\)-modules to \\(R\\)-modules.


### <span class="org-todo todo TODO">TODO</span> Exact sequence about extensions {#exact-sequence-about-extensions}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 21:29]</span></span>
See <sup id="7cd3e01b28c2ede526fee96d60981f02"><a href="#sernesi2006" title="Sernesi, Deformations of {{Algebraic Schemes}}, {Springer Berlin Heidelberg} (2006).">sernesi2006</a></sup> Proposition 1.1.5, Proposition 1.1.7, and Corollary 1.1.8.

{{% remark %}}
The proof in my mind is straightforward but a little tricky when manipulate the objects, since sometimes we need to consider the \\(R\\)-module structure and sometimes as \\(A\\)-algebra.
{{% /remark %}}


### First cotangent module {#first-cotangent-module}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 21:33]</span></span>
See <sup id="7cd3e01b28c2ede526fee96d60981f02"><a href="#sernesi2006" title="Sernesi, Deformations of {{Algebraic Schemes}}, {Springer Berlin Heidelberg} (2006).">sernesi2006</a></sup> p.14.

The \\(R\\)-module \\(\ex\_{A}(R,R)\\) is called the **first cotangent module** of \\(R\\) over \\(A\\), and is denoted by \\(T\_{R/A}^{1}\\). We omit \\(A\\) if \\(A = k\\). The **first cotagent sheaf** is obtained by gluing the first cotangent modules.

Cf. [Ex\_A(R,I)](#ex-a--r-i).


### Versal extension {#versal-extension}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 21:37]</span></span>
An \\(A\\)-[Extension](#extension) \\((P, f)\\) is called **versal** if for every other \\(A\\)-extensions \\((R', \phi)\\) of \\(R\\), there exists a homomorphism of extensions \\(r: (P, f) \to (R, \phi)\\). For example, for \\(R = P/I\\) where \\(P\\) a polynomial ring over \\(A\\),
\\[0 \to I/I^{2} \to P/I^{2} \to R \to 0\\]
is a versal \\(A\\)-extension of \\(R\\).

{{% remark %}}
The word versal is similar to universal and certainly has some similarities. However, I don't know which words come into math world first.
{{% /remark %}}


## Symplectic Geometry {#symplectic-geometry}




### Symplectic manifold {#symplectic-manifold}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-02 Thu 10:43]</span></span>
A **symplectic manifold** is a [smooth Manifold](#manifold) \\(X\\) of even dimension \\(\dim X = 2n\\), equipped with a **symplectic form** a closed smooth \\(2\\)-form \\(\omega \in \Omega\_{cl}^{2}(X)\\) such that \\(\omega\\) is non-degenerate. That is \\(\omega^{n}\\) has the maximal rank at every point \\(p\\), or equivalently that \\((\wedge^{2} T\_{p}^{\* }X, \omega\_{p})\\) symplectic vector space for every \\(p\\).


### Liouville vector field {#liouville-vector-field}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-02 Thu 10:51]</span></span>
Let \\((M, \omega)\\) is a [Symplectic manifold](#symplectic-manifold). A vector field \\(V: M \to TM\\) is **Liouville** if \\(L\_{X} \omega = \omega\\).
Cf. [Lie derivative](#lie-derivative).

The existence of a Liouville vector field implies that \\((M, \omega)\\) is exact as the one-form \\(\lambda = i\_{V} \omega\\) satisfies that \\(\dif \lambda = \omega\\).


### Weinstein manifold {#weinstein-manifold}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-02 Thu 10:42]</span></span>
A [Symplectic manifold](#symplectic-manifold) \\((M, \omega)\\) is **Weinstein** if it comes with a distinguished [Liouville vector field](#liouville-vector-field) \\(Y\\), and a proper bounded below function \\(h: M \to \RR\\), such that \\(\dif h(Y)\\) is positive on a sequence of level set \\(h^{-1}(c\_{k})\\) with \\(\lim\_{k}c\_{k} = \infty\\).

A Weinstein manifold is called **of finite type** if \\(\dif h(Y) > 0\\) outside a compact subset of \\(M\\) and is called **complete** if the flow of \\(Y\\) is defined for all times.


## Geometric representation theory {#geometric-representation-theory}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-29 Sun 15:26]</span></span>
In geometric representation theory, we tries to encode the algebra operation in geometric objects. The one of the general construction is the usage of correspondence, that is the cycles or sheaves etc in \\(X\_{1} \times X\_{2}\\). It is a nonlinear analog of matrices. To retain the linear information, we consider functors such as [Equivariant cohomology](#equivariant-cohomology) and [Equivariant K-theory](#equivariant-k-theory).


### Steinberg variety {#steinberg-variety}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-29 Sun 15:41]</span></span>
For a general symplectic resolution
\\[\pi: X \to X\_{0}\\]
we have the **Steinerg variety** \\(X \times\_{X\_{0}} X\\).


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


### Rosseta stone in mathematics {#rosseta-stone-in-mathematics}

The similarity over number fields, function fields, algebraic curves over \\(\CC\\).


## Knot Theory {#knot-theory}


### Knot {#knot}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 18:13]</span></span>
A **knot** (in \\(S^{3}\\)) is an isotopy class of an [Immersion](#immersion) \\(\hat{K}: S^{1} \to S^{3}\\), \\(K = [\hat{K}]\\).


### Link {#link}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 18:13]</span></span>
A **link** is an isotopy class of an [Immersion](#immersion) \\(\hat{L}: (S^{1})^{\times K} \to S^{3}\\), \\(L = \hat{L}\\).

Cf. [Knot](#knot).


### Framing {#framing}

**Framing** of a [Link](#link) in \\(\RR^{3}\\) is an isotopy class of a continuous section of a normal bundle to \\(L \subset \RR^{3}\\).


### Diagram {#diagram}

The image of a generic geometric representative \\(\hat{L}\\) of [Link](#link) \\(L\\) from \\(\RR^{3}\\) to \\(\RR^{2}\\) is a **diagram** of \\(L\\).

For equivalent class of diagrams, we have the following theorem by Reidemeister.

{{% theorem %}}
Equivalence class of diagrams with respect to the local moves

{{< figure src="/img/2021-09-13_18-22-18_screenshot.png" >}}
{{% /theorem %}}

We can also consider the diagram of [Framed](#framing) links in \\(\RR^{3}\\). And we have equivalence class of regular isotopy class of framed diagrams on \\(\RR^{2}\\) is given by

{{< figure src="/img/2021-09-13_18-30-56_test.png" >}}


### Skein relations {#skein-relations}

We now consider a vector space \\(V\\) of formal \\(\ZZ\\) linear combinations of [Diagrams](#diagram) of [Links](#link) modulo Reidemeister moves. The **Skein relations** are defined by

![](/img/2021-09-13_18-34-45_2021-09-13_18-33.png)
where \\(A, B, C\\) are formal variables and \\(B\\) is invertible. We have
\\[C = \frac{B - B^{-1}}{A}\\]

Also, we Skein is related to Reidemeister moves.

{{% theorem %}}
Skein relations are compatible with Reidemeister moves.
{{% /theorem %}}


### HOMFLY invariant {#homfly-invariant}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 18:37]</span></span>
Since [Skein relations](#skein-relations) are compatible with Reidemeister moves, for every [Link](#link), we may consider its diagram \\(D\_{L}\\) and we define \\([D\_{L}] = \langle L \rangle [O]\\). Here \\(O\\) is one loop and \\(\langle L \rangle \in \ZZ[A, B^{\pm 1}, C]\\). \\(\langle L \rangle\\) depends only on \\(L\\) but not on representative diagram \\(D\_{L}\\). \\(\langle L \rangle\\) is the **HOMFLY** invariant of framed links.

For unframed links, we also have **HOMFLY invariants** by consider \\(L = L\_{1} \coprod \cdots \coprod L\_{n}\\) as framed links and consider \\(\langle \langle L \rangle \rangle = B^{- \sum\_{i} w(L\_{i})} \langle L \rangle\\) where \\(w(L\_{i})\\) is the winding number.


## Geometric Topology {#geometric-topology}




### Realization of Finite Presnetation Group as Fundamental Group of Manifolds {#realization-of-finite-presnetation-group-as-fundamental-group-of-manifolds}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 18:20]</span></span>
We have following theorem by Markov, showing that any finite presentation group can be realized as a fundamental group of a manifold.

{{% theorem %}}
Given any presentation of a group \\(G = \langle g\_{1}, \cdots, g\_{m} \mid r\_{1}, \cdots, r\_{m}\rangle\\), one can construct a \\(n\\)-dim \\(n \geq 4\\) manifold \\(M\\) with \\(\pi\_{1}(M) = G\\).
{{% /theorem %}}

Together with the following theorem of Adyan-Rubin, we show that a complete classification of high dimensional manifold is impossible.

{{% theorem %}}
There does not exist an algorithm that tells whether a given presentation yields the trivial group.
{{% /theorem %}}


### h-Cobordism {#h-cobordism}



Let \\(\mathscr{C}\\) denote one of the following categories: smooth / topological / piecewise linear category. Let \\(M\_{0}, M\_{1}\\) be oriented \\(\mathscr{C}\\)-manifold. A **cobordism** \\(W\\) form \\(M\_{0}\\) to \\(M\_{1}\\) is a \\(n + 1\\) dimensional \\(\mathscr{C}\\)-manifold such that \\(\partial W = \bar{M\_{0}} \coprod M\_{1}\\). We say that \\(W\\) is **h-cobordism** if \\(M\_{0} \hookrightarrow W\\) and \\(M\_{1} \hookrightarrow M\\) are all homotopy equivalences.

The following theorem by Smale, Kirby-Siebenmann show that h-cobordism is powerful classification tool in high dimensional topology.

{{% theorem %}}
Let \\(W\\) be an h-cobordism (in \\(\mathscr{C}\\)) from \\(M\_{0}\\) to \\(M\_{1}\\). Suppose \\(\pi\_{1}(W) = 1\\) and \\(\dim(M\_{0}) \geq 5\\). Then \\(W \cong\_{\mathscr{C}} M\_{0} \times [0,1]\\).
{{% /theorem %}}

The key lemma in the proof of the last theorem is by Whitney, which gives the mysterious dimension bound in the theorem.

{{% lemma %}}
Let \\(F\_{0}, F\_{1}\\) be connected, orientable manifolds smoothly embedded in \\(M\\). suppose

1.  \\(\dim F\_{0} + \dim F\_{1} = \dim M \geq 5\\).
2.  \\(\pi\_{1}(M) = \pi\_{1}(M \backslash F\_{0}) = \pi\_{1}(M \backslash F\_{1}) = 1\\).

Then we can isotope \\(F\_{0}, F\_{1}\\) such that they intersect transversely at \\(\abs{F\_{0} \cdot F\_{1}}\\) points.
{{% /lemma %}}

{{% remark %}}
The key of the previous lemma is that all the intersection number gives positive or negative intersection sign. The transversity can be done in any dimension.
{{% /remark %}}


### Poincarè conjecutre {#poincarè-conjecutre}



We have following **generalized Poincarè conjecture** which is proved by various people in various dimensions.

{{% theorem %}}
Let \\(M\\) be a \\(n\\)-dimensional topological manifold homootpy equivalent to \\(S^{n}\\). Then \\(M \cong\_{top} S^{n}\\).
{{% /theorem %}}

For \\(n \geq 6\\), we can give a proof by [h-Cobordism](#h-cobordism).

However, the smooth structure on \\(S^{n}\\) may not be unique. \\(S^{2k + 1}\\) has unique smooth structure if and only if \\(2k + 1 = 1,3,5,61\\).

The dimension \\(4\\) smooth Poincaré conjecture is still open.


### Wall Theorem {#wall-theorem}



{{% theorem %}}
Let \\(M\_{0}, M\_{1}\\) be simply-connected smooth \\(4\\)-manifold. Suppose \\(M\_{0} \cong\_{homotopy} M\_{1}\\). Then

1.  \\(M\_{0}\\) is smoothly h-cobordant to \\(M\_{1}\\).
2.  For \\(m \geq 0\\), \\(M\_{0} \sharp^{m} (S^{2} \times S^{2}) \cong\_{diff} M\_{1} \sharp^{m} (S^{2} \times S^{2})\\).
{{% /theorem %}}

{{% remark %}}
All known example show that \\(m = 1\\) is already enough but the proves requires large enough \\(m\\). Is the theorem not strong enough, or our understanding of 4-manifold too shallow?
{{% /remark %}}

{{% remark %}}
The theorem also shows that [h-Cobordism](#h-cobordism) theorem fails for \\(n = 4\\).
{{% /remark %}}


### Exotic R^4 {#exotic-r-4}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 18:51]</span></span>
\\(\RR^{4}\\) has infinitely many smooth structures. While other Eucliean space has unique smooth structure by Stallings.


## Quantum Fields and Strings {#quantum-fields-and-strings}




### Super vector space {#super-vector-space}



<div class="definition">
  <div></div>

A **super vector space** is a \\(\ZZ/2 \ZZ\\) graded vector space
\\[V = V\_{0} \oplus V\_{1}\\]
An element \\(v\\) of \\(V\_{0}\\) (resp. \\(V\_{1}\\)) is said to be **even** (resp. **odd**). Its parity in \\(\ZZ / 2 \ZZ\\) is denoted \\(p(a)\\). And **morphism** between super vector spaces is degree presevering linear map.

</div>

We have **parity reversing functor** \\(\Pi\\) such that \\((\Pi V)\_{0} = V\_{1}\\) and \\((\Pi V)\_{1} = V\_{0}\\). Also we use the notation \\(m\_{0} \mid m\_{1}\\) to denote the dimension of \\(V\\) with \\(\dim V\_{0} = m\_{0}\\) and \\(\dim V\_{1} = m\_{1}\\).

The **tensor product** is defined by \\((V \otimes W)\_{k} = \oplus\_{i + j = k} V\_{i} \otimes W\_{j}\\). We define the **commutativity isomorphism**
\\[c\_{V,W}: V \otimes W \to W \otimes V, v \otimes w \to (-1)^{p(v)p(w)} w \otimes v\\]
By above definition, we have the following diagram commutes.

{{< figure src="/img/2021-09-15_19-00-07_screenshot.png" >}}


### Super algebra {#super-algebra}



A **super algebra** over \\(k\\) is a [Super vector space](#super-vector-space) \\(A\\), with a given morphism \\(A \otimes A \to A\\). \\(A\\) is **associative** if \\((xy)z = x(yz)\\). A **unit** is an even element \\(1\\) such that \\(1 x = x 1 = x\\). \\(A\\) is **commutative** if
\\[xy = (-1)^{p(x)p(y)}yx\\]
for homogeneous elements.

We can define the **module** for algebra \\(A\\). And we make left module right module by
\\[m \cdot a := (-1)^{p(m)p(a)} a \cdot m\\]

We also have **opposite algebra** \\(A^{o}\\) of \\(A\\) by product
\\[x \cdot\_{opp} y = (-1)^{p(x)p(y)}y \cdot x\\]

We can define the tensor product of modules and algebras naturely.


### <span class="org-todo todo TODO">TODO</span> Tensor category {#tensor-category}


## Bibliography {#bibliography}

<a id="steinberg2012"></a>[steinberg2012] Steinberg, Representation Theory of Finite Groups: An Introductory Approach, Springer (2012). [↩](#19580479584332ed50a4af7bf7f3f201)

<a id="kirillov2016"></a>[kirillov2016] Kirillov, Quiver Representations and Quiver Varieties, American Mathematical Society (2016). [↩](#df38f5636bec59103a70400bed4764c9)

<a id="dieck2008"></a>[dieck2008] tom Dieck, Algebraic Topology, European Mathematical Society (2008). [↩](#5ad6139c99b6d2508f6ef6f11ce7f09d)

<a id="milne2017"></a>[milne2017] Milne, Algebraic Groups: The Theory of Group Schemes of Finite Type over a Field, Cambridge University Press (2017). [↩](#868cb56e509be613430cca58b1ead9f3)

<a id="cox2011"></a>[cox2011] Cox, Little & Schenck, Toric Varieties, American Mathematical Society (2011). [↩](#8a8485591c9ae40ab7e9a4d136fca3d2)

<a id="sernesi2006"></a>[sernesi2006] Sernesi, Deformations of Algebraic Schemes, Springer Berlin Heidelberg (2006). [↩](#7cd3e01b28c2ede526fee96d60981f02)
