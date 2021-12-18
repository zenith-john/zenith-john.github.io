+++
title = "Mathematics Notes"
author = ["Zenith John"]
date = 2021-08-31
tags = ["Mathematics"]
draft = true
lastmod = 2021-11-14
showtoc = true
+++

## General Mathematics {#general-mathematics}




### Existence proof {#existence-proof}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-27 Mon 20:43]</span></span>
One kind of the importance theorem in mathematics is the existence theorem which states something with certain property exists. Basically, there are two kinds of proof of the existence theorem.

-   Construction. E.g. existence of smooth but not differentiable function.
-   Proof by contradiction. E.g. infiniteness of prime numbers, [Brouwer fixed point theorem](#brouwer-fixed-point-theorem).


### Flavors of mathematics {#flavors-of-mathematics}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 17:44]</span></span>
I want to quote the word of Charles Fefferman to show my flavors of mathematics.

> Mathematics at the highest level has several flavors. On seeing it, one might say
>
> 1.  What amazing technical power!
> 2.  What a grand synthesis!
> 3.  How could anyone not have seen this before?
> 4.  Where on earth did this come from?

In my opinion, the proof of Fermat's last theorem by Wiles of kind 1; Langlands conjecutre is of kind 2; the mirror symmetry conjecture or its computation on Calabi-Yau quintics is of kind 3; Tao and Green's proof of the primes contain arbitrarily long arithmetic progressions of kind 4.


## Category Theory {#category-theory}




### <span class="org-todo todo TODO">TODO</span> A\_&infin; algebra {#a-and-infin-algebra}


### <span class="org-todo todo TODO">TODO</span> A\_&infin; category {#a-and-infin-category}


### Anodyne extension {#anodyne-extension}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:09]</span></span>
**Anodyne extensions** denote the class of morphisms \\(\Lambda\_{k}^{n} \subset \Delta^{n}\\).

Referenced: [Kan fibration](#kan-fibration).


### Associativity constraint {#associativity-constraint}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 19:10]</span></span>
For \\(\mathscr{C}\\) category with functor \\(\otimes\\), an **associativity constraint** is a functorial isomorphism
\\[\phi: X \otimes (Y \otimes Z) \to (X \otimes Y) \otimes Z\\]
satisfying pentagon identity.

{{< figure src="/img/2021-09-30_13-57-58_screenshot.png" >}}

Referenced: [Monoidal category](#monoidal-category), [Tensor category](#tensor-category), [Rigid](#rigid), [Tensor functor](#tensor-functor).


### <span class="org-todo todo TODO">TODO</span> Bialgebra {#bialgebra}


### Classifying space {#classifying-space}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-12 Sun 21:54]</span></span>
For \\(\mathscr{C}\\) a small category, the **classifying space** (or **nerve**) \\(B\mathscr{C}\\) isthe [Simplicial set](#simplicial-set) with \\(B \mathscr{C} = \hom\_{\cat{Cat}}(\bm{n}, \mathscr{C})\\).

A standard example is the \\(BG\\), where \\(G\\) is a group and denoted by the same notion corresponding [Groupoid](#groupoid), and \\(\abs{BG}\\) is the [Eilenberg-Mac Lane space](#eilenberg-mac-lane-space) \\(K(G,1)\\).


### Cocomplete {#cocomplete}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:47]</span></span>
A category is called **cocomplete** if all [Colimits](#colimit) exist.

Referenced: [Category CGWH](#category-cgwh).


### <span class="org-todo todo TODO">TODO</span> Cofiber {#cofiber}


### <span class="org-todo todo TODO">TODO</span> Colimit {#colimit}



Referenced: [Cocomplete](#cocomplete), [Compact](#compact).


### Commutativity constraint {#commutativity-constraint}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 13:58]</span></span>
The **commutativity constraint** is \\(\psi\_{X,Y}: X \otimes Y \to Y \otimes X\\) for all \\(X, Y\\) such that
\\[\psi\_{Y,X} \circ \psi\_{X,Y} = \id\_{X \otimes Y}\\]
with some compatibility condition.

{{< figure src="/img/2021-09-30_14-02-04_screenshot.png" >}}

Referenced: [Tensor category](#tensor-category), [Rigid](#rigid), [Tensor functor](#tensor-functor).


### Comodule {#comodule}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 14:05]</span></span>
Let \\(A\\) be a [Hopf algebra](#hopf-algebra). Then \\(V\\) with \\(k\\)-linear map \\(\rho: V \to V \otimes A\\) satisfying \\(V \stackrel{\rho}{\to} V \otimes A \stackrel{\id \otimes \epsilon}{\to} V \otimes k \cong V\\) is identity and \\(V \stackrel{\rho}{\to} V \otimes A \overset{\rho \otimes \id}{\underset{\id \otimes \Delta}{\rightrightarrows}} V \otimes A \otimes A\\) are same.


### Compact {#compact}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-29 Mon 18:45]</span></span>
An object \\(A\\) in category \\(\mathscr{C}\\) is called compact if the functor \\(\Hom(A, -): \mathscr{C} \to \cat{Set}\\) preserves the [Colimit](#colimit).

{{% proposition %}}
An object \\(A\\) in \\(\cat{Set}\\) is compact if and only if \\(A\\) is finite.
{{% /proposition %}}


### Complete {#complete}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:47]</span></span>
A category is called **complete** if all [Limits](#limit) exist.

Referenced: [Category CGWH](#category-cgwh).


### Cylinder object {#cylinder-object}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 17:34]</span></span>
A **cylinder boject** for an object \\(A\\) in a [Closed model category](#model-category) is the commutative triangle

![](/img/2021-12-18_17-34-46_screenshot.png)
where \\(\nabla\\) is the canonical fold map identity on each component.

Referenced: [Left homotopy](#left-homotopy), [Path object](#path-object).


### <span class="org-todo todo TODO">TODO</span> Derived category {#derived-category}


### <span class="org-todo todo TODO">TODO</span> Derived functor {#derived-functor}


### Drinfeld double {#drinfeld-double}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:15]</span></span>
Let \\((H, H^{\vee}, \langle , \rangle)\\) [Dual pair](#dual-pair) of [Hopf algebra](#hopf-algebra), and let \\(H^{0}\\) be he Hopf algebra \\(H^{\vee}\\) with the opposite comultiplication. Then \\(D(H) = H \otimes H^{0}\\) has an algebra structure uniquely determined by
\\[\Delta\_{D}(a)( R) = R \Delta\_{D}^{op}(a)\\]
for any \\(a \in D(H)\\) and \\(R = \sum\_{i} (e\_{i} \otimes 1\_{H^{0}}) \otimes (1\_{H} \otimes e^{i})\\), where \\(e\_{i}\\) is basis in \\(H\\) and \\(e^{i}\\) basis in \\(H^{\vee}\\). Such construction is called **Drinfeld double**.


### Dual {#dual}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 14:46]</span></span>
We define the **dual** to be \\(X^{\vee} = \ihom(X, U)\\), where \\(U\\) is the [Identity object](#identity-object).

Cf. [Tensor category.](#tensor-category)

Referenced: [Reflexive](#reflexive).


### <span class="org-todo todo TODO">TODO</span> Fiber {#fiber}


### Fibre functor {#fibre-functor}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 19:09]</span></span>
For [Tensor category](#tensor-category) \\((\mathscr{C}, \otimes)\\), a **fibre functor** \\(F\\) is a functor \\(\mathscr{C} \to \cat{Vec}\\) satisfies that \\(F(V\_{1} \otimes V\_{2}) \cong F(V\_{1}) \otimes F(V\_{2})\\).


### Fork {#fork}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:16]</span></span>
The **fork** \\(\Lambda^{n}\_{k}\\) is defined by

![](/img/2021-12-17_20-16-49_screenshot.png)
as coequalizer in \\(\bm{S}\\).


### Function complex {#function-complex}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:13]</span></span>
The **function complex** \\(\bm{Hom}(X,Y)\\) is the simplicial set defined by
\\[\bm{Hom}(X,Y)\_{n} = \hom\_{\bm{S}}(X \times \Delta^{n}, Y)\\]


### <span class="org-todo todo TODO">TODO</span> Functor {#functor}



Referenced: [Continuous](#continuous), [Simplicial set](#simplicial-set).


#### Continuous {#continuous}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-07 Sun 10:21]</span></span>
Let \\(C\\) and \\(C'\\) be [Sites](#site) with associated [Topoi](#topos) \\(T\\) and \\(T'\\), then a [Functor](#functor) \\(C' \to C\\) is called **continuous** if for every \\(X \in C'\\) and \\(\\{X\_{i} \to X\\} \in \cat{Cov}(X)\\) the family \\(\\{f(X\_{i}) \to f(X)\\}\\) is in \\(\cat{Cov}(f(X))\\) and if \\(f\\) commutes with fiber prooducts when they exists in \\(C'\\).

{{% exam %}}
Consider \\(f: X \to Y\\) continuous map, then \\(f^{-1}: \cat{Op}(Y) \to \cat{Op}(X)\\) is a continuous morhpism of sites.
{{% /exam %}}

Given a functor \\(f: C' \to C\\), we have a functor of presheaves: \\(f\_{\* }: \hat{C} \to \hat{C}'\\). That is \\((f\_{\* }F)(T) := F(f(X))\\). When functor is continuous, then \\(f\_{\* }\\)  sends sheaves to sheaves.

Referenced: [Sheaf](#sheaf).


### Functorial factorization {#functorial-factorization}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 17:53]</span></span>
A **functorial factorization** is an ordered pair \\((\alpha, \beta)\\) of functors \\(\cat{Map}(\mathcal{C}) \to \cat{Map}(\mathcal{C})\\) such that \\(f = \beta(f) \circ \alpha(f)\\) for all \\(f \in \cat{Map}(\mathcal{C})\\).

Referenced: [Model category](#model-category), [Cofibrant replacement](#cofibrant-replacement).


### Group object {#group-object}


### Groupoid {#groupoid}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 14:59]</span></span>
A **groupoid** is a category whose morphisms are all isomorphisms.

Referenced: [Classifying space](#classifying-space), [Seifert-Van Kampen theorem](#seifert-van-kampen-theorem).


### Heart {#heart}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 18:33]</span></span>
Let \\((D^{\leq 0}, D^{\geq 0})\\) be [t-structure](#t-structure) for category \\(D\\), then \\(C = D^{\leq 0} \cap D^{\geq 0}\\) is called **heart** of t-structure.

Referenced: [Perverse sheaf](#perverse-sheaf).


### Homotopic {#homotopic}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:19]</span></span>
Maps \\(f,g\\) are a **homotopic** which is both [Left homotopic](#left-homotopy) and right homotopic, denoted by \\(f \sim g\\).


### Homotopy category {#homotopy-category}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:11]</span></span>
Suppose \\(\mathcal{C}\\) is a category with a subcategory of weak equivalence \\(\mathcal{W}\\). Define the **homotopy category** \\(\cat{Ho}(\mathcal{C})\\) as follows. Form the free category \\(F(\mathcal{C}, \mathcal{W}^{-1})\\) on the arrows of \\(\mathcal{C}\\) and reversals of the arrows of \\(W\\). \\(\cat{Ho}(\mathcalC)\\) is the quotient category of \\(F(\mathcal{C}, \mathcal{W}^{-1})\\) by the relations \\(1\_{A} = (1\_{A})\\) for all objects \\(A\\), \\((f, g) = (g \circ f)\\) for all composable arrows \\(f,g\\) and \\(1\_{\text{dom } w} = (w, w^{-1})\\) and \\(1\_{\text{codom } w} = (w^{-1}, w)\\).

Let \\(\mathcal{C}\_{cf}\\) denote the full subcategory of [Cofibrant](#cofibrant) and [Fibrant](#fibrant) objects of \\(\mathcal{C}\\). Then we have

{{% theorem %}}
The inclusion functor \\(\cat{Ho}(\mathcal{C}\_{cf}) \to \cat{Ho}(\mathcal{C})\\) is equivalence of categories.
{{% /theorem %}}

{{% proposition %}}
Suppose \\(\mathcal{C}\\) is a model category. Then a map of \\(\mathcal{C}\_{cf}\\) is a weak equivalence if and only if it is a homotopy equivalence.
{{% /proposition %}}

Cf. [Model category](#model-category), [Homotopy equivalence](#homotopy-equivalence).

{{% theorem %}}
Suppose \\(\mathcal{C}\\) is a model category. Let \\(\gamma: \mathcal{C} \to \cat{Ho}(\mathcal{C})\\) denote the canonical functor. Let \\(Q, R\\) denote the cofibrant replacement and fibrant replacement functor.

1.  The inclusion \\(\mathcal{C}\_{cf} \to \mathcal{C}\\) induces an equivalence of categories \\(\mathcal{C}\_{cf}/ \sim \cong \cat{Ho}(\mathcal{C}\_{cf}) \to \cat{Ho}(\mathcal{C})\\).
2.  There are natural isomorphisms
    \\[\mathcal{C}(QRX, QRY)/ \sim \cat{Ho}(\mathcal{C})(\gamma X, \gamma Y) \cong \mathcal{C}(RQX, RQY)/ \sim\\]
    In addition, there is a natural isomorphism \\(\cat{Ho}(\mathcal{C})(\gamma X, \gamma Y) \cong \mathcal{C}(QX, RY)/ \sim\\).
3.  The functor \\(\gamma: \mathcal{C} \to \cat{Ho}(\mathcal{C})\\) identifies left or right homotopy maps.
4.  If \\(A \to B\\) is a map in \\(\mathcal{C}\\) such that \\(\gamma f\\) is an isomorphism in \\(\cat{Ho}(\mathcal{C})\\), then \\(f\\) is a weak equivalence.
{{% /theorem %}}

Cf. [Cofibrant replacement](#cofibrant-replacement), [Fibrant replacement](#fibrant-replacement).


### Homotopy equivalence {#homotopy-equivalence}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:22]</span></span>
A map \\(f\\) is a **homotopy equivalence** if there exists a map \\(f\\) such that \\(hf \sim 1\\) and \\(fh \sim 1\\).

Referenced: [Homotopy category](#homotopy-category).


### Hopf algebra {#hopf-algebra}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 14:05]</span></span>
A bialgebra \\((A, \Delta, \epsilon)\\) equipped with an antiautomorphism \\(S: A \to A\\), that is \\(S(ab) = S(b)S(a)\\) and \\(\Delta(S(a)) = (S \otimes S)(\Delta^{op}(a))\\) is called a **Hopf algebra** if the following diagram is commutative

{{< figure src="/img/2021-11-04_17-56-31_screenshot.png" >}}

Referenced: [Comodule](#comodule), [Drinfeld double](#drinfeld-double), [Dual pair](#dual-pair), [Quasitriangular](#quasitriangular), [Ribbon](#ribbon).


#### Dual pair {#dual-pair}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 17:51]</span></span>
\\((H\_{1}, H\_{2}, \langle \rangle: H\_{1} \otimes H\_{2} \to k)\\) is a **dual pair** of [Hopf algebra](#hopf-algebra) if \\(\langle, \rangle\\) is nondegerate and \\[\langle lm, a \rangle = \langle l \otimes m , \Delta\_{H\_{2}}(a) \rangle\\] \\[\langle e, ab \rangle = \langle \Delta\_{H\_{1}}(e), a \otimes b \rangle\\] \\[\langle S\_{H\_{1}}(e), a \rangle = \langle e, S\_{H\_{2}}(a) \rangle\\] \\[\langle 1\_{H\_{1}}, a \rangle = \epsilon\_{H\_{2}}(a)\\] \\[\langle e, 1\_{H\_{2}} \rangle = \epsilon\_{H\_{1}}(e)\\]

However, the dual pair is not unique.

Referenced: [Drinfeld double](#drinfeld-double).


#### Quasitriangular {#quasitriangular}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:13]</span></span>
A [Hopf algebra](#hopf-algebra) \\((A, R \in A \hat{\otimes} A)\\) is called **quasitriangular** if
\\[\Delta^{op}(a) = R \Delta(a)R^{-1}\\]
\\[(\Delta \otimes \id)( R) = R\_{13}R\_{23} \in A^{\otimes 3}\\]
\\[(\id \otimes \Delta)( R) = R\_{13}R\_{12} \in A^{\otimes 3}\\]


#### Ribbon {#ribbon}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:21]</span></span>
A [Hopf algebra](#hopf-algebra) is called **ribbon** if \\(v \in Z(A)\\) such that
\\[\Delta\_{v} = (v \otimes v)(R\_{21}R)^{-1} = (R\_{21}R)^{-1}(v \otimes v)\\]

Cf. [Ribbon category](#ribbon-category).


### Identity object {#identity-object}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 14:06]</span></span>
See [Tensor category](#tensor-category).

Referenced: [Dual](#dual).


### <span class="org-todo todo TODO">TODO</span> &infin;-category {#and-infin-category}


### Internal adjunction {#internal-adjunction}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 14:45]</span></span>
With the notation of [Internal Hom](#internal-hom), we have **internal adjunction**  \\(\ihom(Z, \ihom(X,Y)) \ito \ihom(Z \otimes X, Y)\\).

Cf. [Tensor category](#tensor-category).


### Internal Hom {#internal-hom}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 14:07]</span></span>
If \\(\mathscr{C}^{op} \to \cat{Set}\\), \\(T \to \Hom(T \otimes X, Y)\\) is representable, then write the representing object \\(\ihom(X,Y)\\) called **internal Hom**. \\(\ihom(T \otimes X, Y) \cong \Hom(T, \ihom(X,Y))\\). So we have \\({\rm ev}\_{X,Y}: \ihom(X, Y) \otimes X \to Y\\) isomorphic to \\({\rm id}\_{\ihom(X,Y)}\\).

Cf. [Tensor category](#tensor-category).

Referenced: [Internal adjunction](#internal-adjunction).


### Invertible {#invertible}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 14:06]</span></span>
See [Tensor category](#tensor-category).


### Left homotopy {#left-homotopy}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 17:36]</span></span>
A **left homotopy** of maps \\(f,g: A \to B\\) is a commutative diagram
where \\((f, g)\\) is the map on the disjoint union. \\(\tilde{A}\\) is some choice of [Cylinder object](#cylinder-object).

{{< figure src="/img/2021-12-18_17-38-23_screenshot.png" >}}

A similar definition of **right homotopy** for [Path object](#path-object).

Referenced: [Homotopic](#homotopic).


### Left lifting property {#left-lifting-property}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:08]</span></span>
See [Right lifting property](#right-lifting-property).


### Left Quillen functor {#left-quillen-functor}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:32]</span></span>
A functor is a **left Quillen functor** if \\(F\\) is a left adjoint and preserves cofibrations and trivial cofibrations. A functor is a **right Quillen functor** if \\(U\\) is a right adjoint and preserves fibrations and trivial fibrations. We call \\((F, U, \phi)\\) **Quillen adjunction** if \\(F\\) is a left Quillen functor and \\(\phi\\) makes \\(U\\) a right adjoint of \\(F\\).

Referenced: [Quillen adjunction](#quillen-adjunction), [Right Quillen functor](#right-quillen-functor), [Total left derived functor](#total-left-derived-functor).


### <span class="org-todo todo TODO">TODO</span> Limit {#limit}



Referenced: [Complete](#complete).


### Map {#map}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 17:51]</span></span>
For a category \\(\mathcal{C}\\), we can form a category \\(\cat{Map}(\mathcal{C})\\), whose objects are morphisms of \\(\mathcal{C}\\) and whose morphisms are commutative squares.


### Model category {#model-category}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:38]</span></span>
A **model structure** on a category is three classes of morphisms called **cofibrations**, **fibrations**, and **weak equivalences**, satisfying

1.  The category is closed under all finite limits and colimits.
2.  Suppose that the following diagram commutes,

    ![](/img/2021-12-17_20-40-04_screenshot.png)
    if any two \\(f, g\\) and \\(h\\) are weak equivalence, then so is the third.
3.  If \\(f\\) is a [Retract](#retract) of \\(g\\) and \\(g\\) is a weak ewquivalence, fibration or cofibration, then so if \\(f\\).
4.  Suppose that we are given a commutative solid arrow diagram

    ![](/img/2021-12-17_20-43-02_screenshot.png)
    where \\(i\\) is a cofibration and \\(p\\) is a fibration. Then the dotted arrow exists, making the diagram commute, if either \\(i\\) or \\(p\\) is also a weak equivalence.
5.  Any map \\(f: X \to Y\\) may be factored \\(f = p \circ i\\), where \\(p\\) is fibration and \\(i\\) is trivial cofibration and \\(f = q \circ j\\) where \\(q\\) is a trivial fibration and \\(j\\) a cofibration. (We can further require [Functorial factorization](#functorial-factorization))

A **model category** is a category with all small limits and colimits together with a model structure.

{{% remark %}}
The definition of a model category here differs from definition in Quillen's original definition. It is roughly called **closed model category** there. For more differences, you can see book Model categories by Hover.
{{% /remark %}}

If \\(\mathcal{C}\\) is a model category, then it has an initial object, the colimit of the empty diagram, and a terminal object, the limit of the empty diagram.

Referenced: [Cylinder object](#cylinder-object), [Homotopy category](#homotopy-category), [Cofibrant](#cofibrant), [Path object](#path-object).


#### Cofibrant {#cofibrant}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:00]</span></span>
An object of [Model category](#model-category) is called **cofibrant** if the map from the initial object \\(0\\) to it is a cofibration.

An object is called **fibrant** if the map from it to the terminal object is a fibration.

Referenced: [Homotopy category](#homotopy-category), [Fibrant](#fibrant), [Cofibrant replacement](#cofibrant-replacement), [Quillen equivalence](#quillen-equivalence), [Total left derived functor](#total-left-derived-functor).


#### Fibrant {#fibrant}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:04]</span></span>
See [Cofibrant](#cofibrant).

Referenced: [Homotopy category](#homotopy-category), [Quillen equivalence](#quillen-equivalence).


#### Fibrant replacement {#fibrant-replacement}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:10]</span></span>
See [Cofibrant replacement](#cofibrant-replacement).

Referenced: [Homotopy category](#homotopy-category).


#### Cofibrant replacement {#cofibrant-replacement}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:08]</span></span>
By applying factorization to \\(0 \to X\\), we get a **cofibrant replacement** functor \\(X \to QX\\) ([Functorial factorization](#functorial-factorization) is required here) such that \\(QX\\) is [Cofibrant](#cofibrant) and \\(QX \to X\\) is a trivial fibration.

Similar, we have **fibrant replacement** functor \\(X \to RX\\) by applying factorization to \\(X \to 1\\).

Referenced: [Homotopy category](#homotopy-category), [Fibrant replacement](#fibrant-replacement).


### Monoid {#monoid}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 14:17]</span></span>
A **monoid** is a group without inverse. In other words, a group is a monoid with inverse.


### Monoidal category {#monoidal-category}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 18:07]</span></span>
A **monoidal category** is a category \\(C\\) with \\(\otimes\\) which has [Associativity constraint](#associativity-constraint) and there exists unit \\(1 \in \mathop{Ob}( C)\\) such that \\(1 \otimes V \cong V \otimes 1 \cong V\\).

A **monoidal functor** is a functor respect the monoid structure.

Cf. [Tensor category](#tensor-category). In fact, I don't know their differences.

Referenced: [Strict](#strict), [Pivotal](#pivotal), [Braided](#braided), [Rigid braided monoidal category](#rigid-braided-monoidal-category).


#### Strict {#strict}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 18:10]</span></span>
A [Monoidal category](#monoidal-category) is called **strict** if \\((A \otimes B) \otimes C = A \otimes (B \otimes C)\\) and the same is for morphisms.

{{% proposition %}}
Every monoidal category \\(C\\) is naturally equivalent to a strict monoidal category \\(C^{str}\\)
{{% /proposition %}}


#### Pivotal {#pivotal}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 17:51]</span></span>
A [Rigid](#rigid) [Monoidal category](#monoidal-category) is called **pivotal** if there exists a system of functorial isomorphism
\\[\mu = \\{\mu\_{X}: X \to X^{\*\*}\\}\\] such that
\\[\mu\_{X \otimes Y} = \mu\_{X} \otimes \mu\_{Y}\\]

Referenced: [Spherical](#spherical).


#### Trace {#trace}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:01]</span></span>
We introduce the **categorical trace** by
\\[\tr\_{f}^{L} = 1 \xrightarrow{i} V \otimes V^{\*} \xrightarrow{f \otimes \id} V \otimes V^{\*} \xrightarrow{\mu\_{V} \otimes \id} V^{\*\*} \otimes V^{\*} \xrightarrow{e\_{V^{\*}}} 1\\]
Similarly, we can define the right trace \\(\tr\_{f}^{R}\\).

We have following properties similar to classical trace
\\(\tr^{L,R}(fg) = \tr^{L,R}(gf)\\) and \\(\tr^{L,R}(f \otimes g) = \tr^{L,R}(f) \otimes \tr^{L,R}(g)\\).

Referenced: [Spherical](#spherical), [Dimension](#dimension).


#### Spherical {#spherical}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:07]</span></span>
A [Pivotal](#pivotal) category is **spherical** if for any \\(V\\) and \\(f: V \to V\\), we have \\(\tr^{L}(f) = \tr^{R}(f)\\).

Cf. [Trace](#trace).

Referenced: [Dimension](#dimension).


#### Dimension {#dimension}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:07]</span></span>
In [Spherical](#spherical) category we can define the **categorical dimension** by \\(\dim V = \tr(\id\_{V})\\) since the two [Traces](#trace) are the same.


#### Braided {#braided}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:09]</span></span>
A [Monoidal category](#monoidal-category) is **braided** if there exists \\(c = \\{c\_{V,W}\\}\\), \\(c\_{V,W}: V \otimes W \to W \otimes V\\) with some compatibility conditions.

Referenced: [Rigid braided monoidal category](#rigid-braided-monoidal-category).


### Ordinal number category {#ordinal-number-category}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-12 Sun 21:29]</span></span>
See [Simplicial set](#simplicial-set).


### Path object {#path-object}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:29]</span></span>
Let \\(\bm{S}\_{f}\\) be the full subcategory of [Simplicial set](#simplicial-set) category (or [Closed model category](#model-category)) whose objects are the [Kan complex](#kan-complex). A **path object** for \\(X \in \bm{S}\_{f}\\) is a commutative diagram

{{< figure src="/img/2021-12-17_20-36-10_screenshot.png" >}}

where \\(s\\) is a [Weak equivalence](#weak-equivalence) and \\(d\_{0}, d\_{1}\\) are [Kan fibrations](#kan-fibration) (in fact necessarily [Trivial fibrations](#trivial-fibration)).

Cf. [Cylinder object](#cylinder-object).

Referenced: [Left homotopy](#left-homotopy).


### Pointed {#pointed}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:05]</span></span>
An category is called **pointed** if the map from the initial object to the termninal object is an isomorphism.


### Quillen adjunction {#quillen-adjunction}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:35]</span></span>
Cf. [Left Quillen functor](#left-quillen-functor).

Referenced: [Quillen equivalence](#quillen-equivalence).


### Quillen equivalence {#quillen-equivalence}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:41]</span></span>
A [Quillen adjunction](#quillen-adjunction) \\((F, U, \phi): \mathcal{C} \to \mathcal{D}\\) is called a **Quillen equivalence** if and only if, for all [Cofibrant](#cofibrant) \\(X\\) in \\(\mathcal{C}\\) and [Fibrant](#fibrant) \\(Y\\) in \\(\mathcal{D}\\), a map \\(f: FX \to Y\\) is a weak equivalence in \\(\mathcal{D}\\) if and only if \\(\phi(f): X \to UY\\) is a weak equivalence in \\(\mathcal{C}\\).


### Reflexive {#reflexive}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 14:47]</span></span>
An object \\(X\\) is called **reflexive** if \\(i\_{X}: X \ito X^{\vee \vee}\\).

Cf. [Dual](#dual), [Tensor category](#tensor-category).

Referenced: [Rigid](#rigid).


### Retract {#retract}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 17:44]</span></span>
A map in \\(\mathcal{C}\\) is a **retract** of a map \\(g \in \mathcal{C}\\) if and only if there is a commutative diagram of the form

{{< figure src="/img/2021-12-18_17-46-06_screenshot.png" >}}

where horizontal composites are identities.

Referenced: [Model category](#model-category).


### Ribbon category {#ribbon-category}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:19]</span></span>
A **ribbon category** is a [Rigid braided monoidal category](#rigid-braided-monoidal-category) with \\(v = \\{v\_{X}\\}\\) such that
\\[v\_{X \otimes Y} = (v\_{X} \otimes v\_{Y}) c\_{XY}^{-1}c\_{YX}^{-1}\\]

Referenced: [Ribbon](#ribbon).


### Right lifting property {#right-lifting-property}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:04]</span></span>
A map \\(p: X \to Y\\) is said to have the **right lifting property** (RLP) with repsect to a class \\(M\\) is in every solid arrow diagram

![](/img/2021-12-17_20-05-45_screenshot.png)
with \\(i \in M\\) the dotted arrow exists making the diagram commute.

The **left lifting property** is defined by same diagram with \\(i\\) and \\(p\\) in definition changed.

Referenced: [Left lifting property](#left-lifting-property), [Kan fibration](#kan-fibration).


### Right Quillen functor {#right-quillen-functor}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:34]</span></span>
See [Left Quillen functor](#left-quillen-functor).


### Rigid braided monoidal category {#rigid-braided-monoidal-category}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:10]</span></span>
A **rigid braided monoidal category** is a [Rigid](#rigid) [Braided](#braided) [Monoidal category](#monoidal-category) such that
\\[c\_{A^{\*}B^{\*}} = (c\_{B,A})^{\*}\\]

Referenced: [Ribbon category](#ribbon-category).


### Saturated {#saturated}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:02]</span></span>
A class \\(M\\) of monomorphisms of \\(\cat{S}\\) is said to be **saturated** if the following conditions are satisfied:

1.  All isomorphisms are in \\(M\\).
2.  \\(M\\) is closed under pushout.
3.  Each retract of an element of \\(M\\) is in \\(M\\).
4.  \\(M\\) is closed under countable compositions and arbitrary direct sums.


### Simplicial group {#simplicial-group}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:00]</span></span>
A **simplicial group** is a simplical object in the category of groups, that is a contravariant functor from \\(\bm{\Delta}\\) to the category \\(\cat{Group}\\).


### Simplicial homotopy {#simplicial-homotopy}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:17]</span></span>
Let \\(f, g: K \to X\\) be simplicial maps. We say that there is a **simplicial homotopy** \\(f \cong g\\) from \\(f\\) to \\(g\\) if there is a commutative diagram

{{< figure src="/img/2021-12-17_20-19-04_screenshot.png" >}}

The map \\(h\\) is called **homotopy**.

This is the analog of topological [Homotopy](#homotopy).


### Simplicial homotopy group {#simplicial-homotopy-group}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:20]</span></span>
Let \\(X\\) be a [Fibrant](#fibrant) [Simplicial set](#simplicial-set) and \\(v \in X\_{0}\\) be a vertex of \\(X\\). Define the **simplicial homotopy group** \\(\pi\_{n}(X, v), n \geq 1\\) to be the set of homotopy classes of maps \\(\alpha: \Delta^{n} \to X (\text{rel } \partial \Delta^{n})\\) fit into the diagram

{{< figure src="/img/2021-12-17_20-21-55_screenshot.png" >}}

\\(\pi\_{0}(X)\\) is usually called **path components** of \\(X\\). The simplicial set \\(X\\) is said to be connected if \\(\pi\_{0}(X)\\) is trivial.

{{% proposition %}}
\\(\pi\_{n}(X, v)\\) is a group for \\(n \geq 1\\) and abelian group for \\(n \geq 2\\).
{{% /proposition %}}

The group law is given by \\([\alpha] \* [\beta]\\) to be \\(\dif\_{n}(\omega)\\) of the extension

![](/img/2021-12-17_20-25-34_screenshot.png)
where \\((v\_{0}, \cdots, v\_{n - 1}, , v\_{n+1}) = (v, v, \cdots, v, \alpha, , \beta)\\).

Cf. [Homotopy group](#homotopy-group).


### Simplicial set {#simplicial-set}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:02]</span></span>
Let \\(\bm{\Delta}\\) be the category of finite ordianl numbers with order preserving maps between them. The object of \\(\bm{\Delta}\\) is denoted by \\(\bm{n}\\) which is a category denoted by \\(0 \to 1 \to 2 \to \cdots \to n\\), where identity and composition morphism is omitted. \\(\bm{\Delta}\\) is called **ordinal number category**. A **simplicial set** is a contravariant [Functor](#functor) \\(X: \bm{\Delta^{op}} \to \cat{Sets}\\).

One of the important example is standard covarinat functor \\(\bm{\Delta} \to \cat{Top}\\) mapping \\(\bm{n}\\) to **standard n-simplex** \\(\abs{\Delta^{n}}\\) with
\\[\abs{\Delta^{n}} = \\{(t\_{0}, \cdots, t\_{n}) \in \RR^{n + 1} \mdi \sum\_{i = 0}^{n}t\_{i} = 1, t\_{i} \geq 0\\}\\]

In this language, the [Singular homology](#singular-homology) can be describe by **singular set** \\(S(T)\\)
\\[\bm{n} \to \hom(\abs{\Delta^{n}, T})\\]

We have morphism in \\(\bm{\Delta}\\) \\(d\_{i}: \bm{n - 1} \to \bm{n}\\) (**cofaces**) and \\(s^{j}: \bm{n + 1} \to \bm{n}\\) (**codegeneracies**), defined as
\\[d^{i}(0 \to 1 \to \cdots \to n - 1) = (0 \to 1 \to \cdots \to i - 1 \to i + 1 \to \cdots \to n)\\]
\\[s^{j}(0 \to 1 \to \cdots \to n + 1) = (0 \to 1 \to \cdots \to j \to j \to \cdots \to n)\\]

We have **cosimplicial identities**

\begin{align\*} \begin{cases} d^{j}d^{i} = d^{i}d^{j - 1} & \text{if } i < j \\\\\\ s^{j}d^{i} = d^{i}s^{j - 1} & \text{if } i < j \\\\\\ s^{j}d^{j} =1 = s^{j}d^{j+1} &\\\\\\ s^{j}d^{i} = d^{i - 1} s^{j} & \text{if } i > j + 1 \\\\\\ s^{j}d^{i} = s^{i}s^{j+1} & \text{if } i \leq j \\\\\\ \end{cases} \end{align\*}

We have similar simplicial identities for \\(Y\_{n}\\), where \\(Y\\) is a simplicial set.

Referenced: [Classifying space](#classifying-space), [Ordinal number category](#ordinal-number-category), [Path object](#path-object), [Simplicial homotopy group](#simplicial-homotopy-group), [Realization](#realization), [Fibrant](#fibrant), [Weak equivalence](#weak-equivalence).


#### Realization {#realization}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 19:52]</span></span>
A **realization** of a [Simplicial set](#simplicial-set) \\(X\\), \\(\abs{X}\\), is defined to be
\\[\abs{X} = \varinjlim\_{\Delta^{n} \to X} \abs{\Delta^{n}}\\]
It is a functor from simplicial set category to topology space category (in fact \\(\cat{CGWH}\\), [Category CGWH](#category-cgwh)). In fact, we have adjoint property
\\[\hom\_{\cat{Top}}(\abs{X}, Y) \cong \hom\_{\cat{S}} (X, SY)\\]


#### Kan fibration {#kan-fibration}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 19:56]</span></span>
A map \\(p: X \to Y\\) of simplicial set is called **Kan fibration** if it satisfies the extension condition that for every commutative diagram

![](/img/2021-12-17_19-57-49_screenshot.png)
there exists \\(\theta: \Delta \to X\\) making the diagram commute.

Kan fibration is the categorical analog of [Fibration](#fibration).

{{% proposition %}}
A **Kan fibration** is a map which has the right lifting property with respect to all anodyne extensions.
{{% /proposition %}}

Cf. [Anodyne extension](#anodyne-extension)， [Right lifting property](#right-lifting-property).

Referenced: [Path object](#path-object), [Fibrant](#fibrant), [Trivial fibration](#trivial-fibration).


#### Fibrant {#fibrant}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 19:58]</span></span>
A [Simplicial set](#simplicial-set) is called **fibrant** or **Kan complex** if the canonical map \\(Y \to \*\\) is a [Kan fibration](#kan-fibration).

Referenced: [Simplicial homotopy group](#simplicial-homotopy-group), [Kan complex](#kan-complex), [Weak equivalence](#weak-equivalence).


#### Kan complex {#kan-complex}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:30]</span></span>
See [Fibrant](#fibrant).

Referenced: [Path object](#path-object).


#### Weak equivalence {#weak-equivalence}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:31]</span></span>
The map \\(f: X \to Y\\) between [Fibrant](#fibrant) [Simplicial sets](#simplicial-set) is called **weak equivalence** if

1.  For each vertex \\(x\\) of \\(X\\) the induced map \\(f\_{\*}: \pi\_{i}(X, x) \to \pi\_{i}(Y, f(x))\\) is an isomorphism for \\(i \geq 1\\).
2.  The map \\(f\_{\*}: \pi\_{0}(X) \to \pi\_{0}(Y)\\) is a bijection.

Cf. [Weak homotopy equivalence](#weak-homotopy-equivalence).

Referenced: [Path object](#path-object), [Trivial fibration](#trivial-fibration).


#### Trivial fibration {#trivial-fibration}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:33]</span></span>
A map \\(p: X \to Y\\) in \\(\bm{S}\_{f}\\) is called **trivial fibration** if it is a [Kan fibration](#kan-fibration) and a [Weak equivalence](#weak-equivalence).

Referenced: [Path object](#path-object).


### <span class="org-todo todo TODO">TODO</span> Stable &infin;-category {#stable-and-infin-category}


### Tensor category {#tensor-category}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 19:04]</span></span>
A **tensor category** is data \\((\mathscr{C}, \otimes, \phi, \psi)\\) where \\(\phi\\) is the [Associativity constraint](#associativity-constraint) and \\(\psi\\) the [Commutativity constraint](#commutativity-constraint).

The **identity object** in tensor cateogry is a pair \\((U, u)\\) where \\(U \in \mathscr{C}\\) with \\(u: U \ito U \otimes U\\) such that \\(U \otimes -\\) is an equivalence.

The object \\(L\\) is called **invertible** if \\(L \otimes -\\) is an equivalence. If \\(L\\) is invertible, then \\(L\\) has inverse with \\(\delta: L \otimes L^{-1} \ito U\\).

Referenced: [Dual](#dual), [Fibre functor](#fibre-functor), [Identity object](#identity-object), [Internal adjunction](#internal-adjunction), [Internal Hom](#internal-hom), [Invertible](#invertible), [Monoidal category](#monoidal-category), [Reflexive](#reflexive), [Rigid](#rigid), [Tensor functor](#tensor-functor), [Criterion for category being representation category](#criterion-for-category-being-representation-category).


#### Rigid {#rigid}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 14:48]</span></span>
A [Tensor category](#tensor-category) is called **rigid** if we have isomorphism
\\[\ihom(X\_{1}, Y\_{1}) \otimes \ihom(X\_{2}, Y\_{2}) \to \ihom(X\_{1} \otimes X\_{2}, Y\_{1} \otimes Y\_{2})\\]
for all \\(X\_{i}, Y\_{i}\\) and all objects are [Reflexive](#reflexive).

In rigid category, we have trace \\(ihom(X, X) \to X^{\vee} \otimes X \to U\\) called **trace**. And we define the **rank** to be \\(\tr\_{X}({\rm id}\_{X})\\).

The following is a criterion for rigidity.

{{% proposition %}}
Let \\(C\\) be an abelian category and \\(\otimes: C \times C \to C\\) bilinear. Take
\\[F: C \to \cat{Vec}\_{k}\\]
faithul exact and \\(\phi, \psi\\) isomorphisms of associativity and communitivity such that

-   \\(F\\) repsects \\(\otimes\\).
-   \\(F\\) induces usual associativitiy on \\(\cat{Vec}\_{k}\\).
-   \\(F\\) induces usual communitivity on \\(\cat{Vec}\_{k}\\).
-   There exists identity \\(U\\) in \\(C\\) where \\(k \cong \End(U)\\) and \\(\dim F(U) = 1\\).
-   If \\(\dim F(L) = 1\\), then there exists \\(L^{-1}\\) such that \\(L \otimes L^{-1} \cong U\\).

Then \\((C, \otimes)\\) is abelian rigid tensor category.
{{% /proposition %}}

Cf. [Associativity constraint](#associativity-constraint), [Commutativity constraint](#commutativity-constraint), [Tensor category](#tensor-category).

Referenced: [Pivotal](#pivotal), [Rigid braided monoidal category](#rigid-braided-monoidal-category), [Criterion for category being representation category](#criterion-for-category-being-representation-category).


### Tensor functor {#tensor-functor}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 14:51]</span></span>
A **tensor functor** between [Tensor category](#tensor-category) is a functor with morphism
\\[c:FX \otimes FY \ito F(X \otimes Y)\\]
functorial in \\(X, Y\\) with compatibility with [Commutativity constraint](#commutativity-constraint) and [Associativity constraint](#associativity-constraint).


### t-exact {#t-exact}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-30 Sat 16:17]</span></span>
A functor is called **t-exact** if it is compatible with the [t-structure](#t-structure).


### Torsion pair {#torsion-pair}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 18:33]</span></span>
A torsion pair \\((\mathcal{P}, \mathcal{Q})\\) is a pair of full subcategory of \\(\mathcal{C}\\) such that

1.  \\(\hom(P, Q) = 0\\) for every \\(P \in \mathcal{P}, Q \in \mathcal{Q}\\).
2.  \\(\hom(\mathcal{P}, X) = 0\\), then \\(X \in \mathcal{Q}\\).
3.  \\(\hom(X, \mathcal{Q}) = 0\\), then \\(X \in \mathcal{P}\\).
4.  For every \\(C\\) in \\(\mathcal{C}\\), there exists \\(P \in \mathcal{P}, Q \in \mathcal{Q}\\) such that
    \\[0 \to P \to C \to Q \to 0\\]
    is exact.


### Total left derived functor {#total-left-derived-functor}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:36]</span></span>
If \\(F: \mathcal{C} \to \mathcal{D}\\) is a [Left Quillen functor](#left-quillen-functor), define the **total left derived functor** \\(LF: \cat{Ho}(\mathcal{C}) \to \cat{Ho}(\mathcal{D})\\) to be the composite
\\[\cat{Ho}(\mathcal{C}) \xrightarrow{\cat{Ho}(Q)} \cat{Ho}(\mathcal{C}\_{c}) \xrightarrow{\cat{Ho}(F)} \cat{Ho}(\mathcal{D})\\]
where \\(\mathcal{C}\_{c}\\) means the full subcategory with [Cofibrant](#cofibrant) objects. For natural transformation, we have **total derived natural transformation**.

Similarly, we have **total right derived functor**.

Referenced: [Total right derived functor](#total-right-derived-functor).


### Total right derived functor {#total-right-derived-functor}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:39]</span></span>
See [Total left derived functor](#total-left-derived-functor).


### <span class="org-todo todo TODO">TODO</span> Triangulated category {#triangulated-category}



Referenced: [t-structure](#t-structure).


### t-structure {#t-structure}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 18:33]</span></span>
Let \\(D\\) be a [Triangulated category](#triangulated-category) and \\(D^{\leq 0}, D^{\geq 0}\\) full subcategories, then \\((D^{\leq 0}, D^{\geq 0})\\) is called **t-structure** if the followings are satisfied

1.  \\(D^{\leq 1} \subset D^{\leq 0}\\), \\(D^{\geq 1} \subset D^{\geq 0}\\).
2.  \\(\Hom\_{D}(X, Y) = 0\\) for \\(X \in D^{\leq 0}, Y \in D^{\geq 1}\\).
3.  For \\(X \in D\\), there exists distinguished triangle
    \\[X\_{0} \in D^{\leq 0} \to X \to X\_{1} \in D^{\geq 1} \to X\_{0}[1]\\]

Referenced: [Heart](#heart), [t-exact](#t-exact), [Bounded](#bounded), [Perverse sheaf](#perverse-sheaf).


#### Bounded {#bounded}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-30 Sat 16:14]</span></span>
A [t-structure](#t-structure) is called **bounded** if \\(D^{\leq n} = D = D^{\geq m}\\) for \\(m \ll 0\\) and \\(n \gg 0\\).


### <span class="org-todo todo TODO">TODO</span> Zero object {#zero-object}


## Commutative Algebra {#commutative-algebra}




### <span class="org-todo todo TODO">TODO</span> Commutative Frobenius algebra {#commutative-frobenius-algebra}


### Ext group {#ext-group}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-13 Wed 21:11]</span></span>
Let \\(M, N\\) be two \\(R\\)-modules. Let \\(P\_{\bullet} \to M\\) be a free \\(R\\)-module resolution of \\(M\\)
\\[\cdots \to P\_{n} \to \cdots \to P\_{1} \to P\_{0} \to M \to 0\\]
is an exact sequence of \\(R\\)-modules and \\(P\_{i}\\)'s are free. Then we define the **Ext group** by
\\[\Ext^{k}\_{R}(M, N) = H^{k}(\Hom(P\_{\bullet}, N))\\]
and the **Tor group**
\\[\Tor^{R}\_{k}(M, N) = H\_{k}(P\_{\bullet} \otimes\_{R} N)\\]

Referenced: [Tor group](#tor-group).


### <span class="org-todo todo TODO">TODO</span> Finite length {#finite-length}


### <span class="org-todo todo TODO">TODO</span> K-theory {#k-theory}


### Module {#module}




#### <span class="org-todo todo TODO">TODO</span> Injective {#injective}


### <span class="org-todo todo TODO">TODO</span> Resolution {#resolution}


### Semisimple {#semisimple}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-30 Sat 16:19]</span></span>
An object in a category is called **semisimple** if it is the direct sum of the [Simple](#simple) object.


### <span class="org-todo todo TODO">TODO</span> Simple {#simple}



Referenced: [Semisimple](#semisimple).


### Tor group {#tor-group}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-13 Wed 21:11]</span></span>
See [Ext group](#ext-group).


## Sheaf Theory {#sheaf-theory}




### Constructible sheaf {#constructible-sheaf}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-23 Sat 14:20]</span></span>
A sheaf is called **constructible** if \\(F|\_{X\_{\alpha}}\\) is a [Local system](#local-system) for some [Stratification](#stratification) \\((X\_{\alpha})\\). And we define the category \\(D\_{c}^{b}(X) \subset D^{b}(X)\\) full subcategory with constructible cohomology.


### Dual complex {#dual-complex}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-23 Sat 14:19]</span></span>
We define **dual complex** to be \\(D\_{X} = w\_{X}[n]\\), where \\(n = \dim X\\). and \\(w\_{X}(U) = \Hom(H\_{c}^{n}(U), k)\\).

Referenced: [Verdier duality](#verdier-duality).


### <span class="org-todo todo TODO">TODO</span> Equivariant sheaf {#equivariant-sheaf}


### <span class="org-todo todo TODO">TODO</span> G-resolution {#g-resolution}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:08]</span></span>
Equivariant pullback


### <span class="org-todo todo TODO">TODO</span> Intersection cohomology {#intersection-cohomology}


### <span class="org-todo todo TODO">TODO</span> Local system {#local-system}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:00]</span></span>
The local system also has its dual.

Referenced: [Constructible sheaf](#constructible-sheaf), [Verdier duality](#verdier-duality).


### Perverse sheaf {#perverse-sheaf}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:01]</span></span>
For \\(D = D^{b}\_{c}(X)\\), we can take [t-structure](#t-structure) as
\\[D^{\leq 0} = \\{F | \dim \supp \mathscr{H}^{j}(F) \leq -j\\}\\]
\\[D^{\geq 0} = \\{F | \dim \supp \mathscr{H}^{j}(\mathbb{D}\_{X}F) \leq -j\\}\\]
And we define the **perverse sheaf** to be the [Heart](#heart) of the t-structure. That is
\\[\cat{Perv}(X) = D^{\leq 0} \cap D^{\geq 0}\\]

The operator \\(\mathbb{D}\_{X}\\) preverse the category \\(\cat{Perv}(X)\\).

For perverse sheaf category, we have functor \\(^{p}F\\).


### <span class="org-todo todo TODO">TODO</span> Six functors {#six-functors}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:01]</span></span>
\\(f^{-1}\\) is exact, and \\(f\_{\* }\\) and \\(f\_{!}\\) only left exact.

We have following important properties for operators.

-   Adjunction pairs: \\((f^{\*}, Rf\_{\* })\\), \\((Rf\_{!}, f^{!})\\), \\((- \otimes \mathcal{F}, \shom(\mathcal{F}, -)\\).
-   The morphism between functors \\(f\_{!} \to f\_{\* }\\), which is isomorphism if \\(f\\) is proper. Also, we have \\(j^{!} = j^{\* }\\) for \\(j\\) an open inclusion.
-   For \\(X = U \coprod Z\\) where \\(U\\) is open and \\(Z\\) is closed, denote the includion \\(i: U \to X\\), \\(j: Z \to X\\), then we have distinguished triangles
    \\[i\_{!}i^{!} \to \id \to j\_{\* } j^{\* }\\]
    \\[j\_{!}j^{!} \to \id \to i\_{\* } i^{\* }\\]
-   See [Verdier duality](#verdier-duality).
-   For \\(f: X \to Y\\) smooth of relative dimension \\(d\\) then one has an isomorphism
    \\[f^{!}k = k[2d]\\]
-   \\(H^{n}(X) = H^{n}(f\_{\* }k\_{X})\\), \\(H\_{n}^{!}(X) = H^{n}(f\_{\* } \omega\_{X})\\), \\(H\_{!}^{n} = H^{n}(f\_{!}k\_{X})\\), \\(H\_{n}(X) = H^{-n}(f\_{!} \omega\_{X})\\)
-   For pullback diagram

    ![](/img/2021-11-04_18-20-23_screenshot.png)
    We have isomorphism of functors
    \\[f^{\* } \circ g\_{!} \cong (g')\_{!} \circ (f')^{!}\\]


### Stratification {#stratification}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-23 Sat 14:20]</span></span>
A **stratification** of \\(X\\) is a decomposition
\\[X = \coprod\_{\alpha \in A} X\_{\alpha}\\]
which is locally finite, \\(X\_{\alpha}\\) locally closed and smooth and satisfies
\\[\bar{X}\_{\alpha} = \coprod\_{\beta \in B} X\_{\beta}\\]

Referenced: [Constructible sheaf](#constructible-sheaf).


### Verdier duality {#verdier-duality}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-23 Sat 14:29]</span></span>
Let \\(D\_{X} \in D^{b}(X)\\) be the [Dual complex](#dual-complex), we define \\(\mathbb{D}\_{X}(E) = \mathbb{R} \shom\_{X}(E, D\_{X})\\) gives functor \\(\mathbb{D}\_{X}: D^{b}(X) \to D^{b}(X)\\).

We have \\(\mathbb{D}^{2} = \id\\).

The **Verdier duality** is the eqauility
\\[\mathbb{D}\_{Y} \circ Rf\_{!} = Rf\_{\*} \circ \mathbb{D}\_{X}\\]
Also, we have
\\[f^{!} \circ \mathbb{D}\_{Y} = \mathbb{D}\_{X} \circ f^{-1}\\]

As a speical case, when \\(\mathcal{L}\\) is [Local system](#local-system) and \\(X\\) is smooth, we have
\\[\mathbb{D} \mathcal{L} \cong \mathcal{L}^{\vee}[2 d\_{X}]\\]

Referenced: [Six functors](#six-functors).


### <span class="org-todo todo TODO">TODO</span> Whitney stratification {#whitney-stratification}


## Representation of groups {#representation-of-groups}

The reference includes [<span id="19580479584332ed50a4af7bf7f3f201"><a href="#steinberg2012" title="Steinberg, Representation Theory of Finite Groups: An Introductory Approach, {Springer} (2012).">steinberg2012</a></span>] Chapter 1-6.

Referenced: [Representation category](#representation-category).


### Burnside Theorem {#burnside-theorem}

{{% theorem %}}
Let \\(G\\) be a group of order \\(p^{a}q^{b}\\) with \\(p\\), \\(q\\) primes. Then \\(G\\) is not simple unless it is cyclic of prime order.
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

\begin{equation} \sum\_{i = 1}^{s}\chi\_{i}(g) \overline{\chi\_{i}(h)} = \begin{cases} |G|/|C| & C = C' \\\\\\  0 & C \neq C' \end{cases} \end{equation}

That is the columns of the character table are orthogonal.
{{% /theorem %}}


### Completely decomposition {#completely-decomposition}

{{% proposition %}}
Every representation of a finite group is equivalent to a unitary representation.
{{% /proposition %}}

{{% theorem %}}
Every representation of a finite group is completely reducible.
{{% /theorem %}}


### Criterion for category being representation category {#criterion-for-category-being-representation-category}



{{% theorem %}}
Let \\((C, \otimes)\\) rigid abelian tensor category, \\(\End({\bold 1}) = k\\) and \\(w: C \to \cat{Vec}\_{k}\\) exact faithful \\(k\\)-linear tensor functor. Then we have

-   \\(\cat{Aut}^{\otimes}(w) \cong G\\) affine group scheme.
-   \\(C \to \cat{Rep}\_{k}(G)\\) induced by \\(w\\) is tensor equivalence.
{{% /theorem %}}

Cf. [Tensor category](#tensor-category), [Rigid](#rigid), [Group scheme](#group-scheme).


### Dimension theorem {#dimension-theorem}

{{% theorem %}}
Let \\(\phi\\) be an irreducible representation of \\(G\\) of degree \\(d\\). Then \\(d\\) divides \\(|G|\\).
{{% /theorem %}}

这里值得注意的是，证明中使用了一些代数数论的结论，主要是关于 algebraic number 和 algebraic integer。


### Fourier analysis of finite groups {#fourier-analysis-of-finite-groups}

fourier transform; fourier inversion; convolution; dual group;

{{% proposition %}}
The class functions form the center of \\(L(G)\\).
{{% /proposition %}}

{{% proposition %}}
\\(\widehat{a \* b} = \hat{a} \cdot \hat{b}\\)
{{% /proposition %}}

nonabelian Fourier transform (Wedderburn)


### Orthogonal relations {#orthogonal-relations}

Group algebra

{{% theorem %}}
Suppose that \\(\phi,\rho: G \to U\_{n}( C)\\) are inequivalent irreducible unitary representations. Then

\begin{equation} \langle \phi\_{ij}, \rho\_{kl} \rangle = 0 \end{equation}

\begin{equation} \langle \phi\_{ij}, \phi\_{kl} \rangle =  \begin{cases} 1/n & \text{if } i = k \text{ and } j = l \\\\\\ 0 & \text{else} \end{cases} \end{equation}
{{% /theorem %}}

Referenced: [Characters and class functions](#characters-and-class-functions).


### Reconstruction theorem {#reconstruction-theorem}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 14:18]</span></span>
Let \\(\cat{Rep}\_{k}(G)\\) be [Representation category](#representation-category) of affine [Group scheme](#group-scheme) \\(G\\). And let \\({\rm For}: \cat{Rep}\_{k}(G) \to \cat{Vec}\_{k}\\) be forgetful functor. Then we have \\(\cat{Aut}^{\otimes}({\rm For})( R) \ni \lambda\\) is data of \\(\lambda\_{X}: X \otimes R \to X \otimes R\\) for every \\(X \in \cat{Rep}\_{k}(G)\\) with compatibilities

-   \\(\lambda\_{X\_{1} \otimes X\_{2}} = \lambda\_{X\_{1}} \otimes \lambda\_{X\_{2}}\\)
-   \\(\lambda\_{\bold 1} = \id\_{k \otimes R = R}\\)

And for all \\(\alpha: X \to Y\\) in \\(\cat{Rep}\_{k}(G)\\), it commutes with \\(\lambda\_{X}\\). We observe that \\(g \in G( R)\\) gives an element of \\(\cat{Aut}^{\otimes}({\rm For})( R)\\). In fact, we have

{{% proposition %}}
The associated morphism of schemes \\(G \to \cat{Aut}^{\otimes}({\rm For})\\) is an isomorphism.
{{% /proposition %}}


### Representation category {#representation-category}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 19:03]</span></span>
For a group \\(G\\), we may define the category \\(\cat{Rep}(G)\\) for finite dimensional representation of \\(G\\) with morphisms of representations.

Cf. [Representation of finite groups](#representation-of-groups), [Algebraic group](#algebraic-group).

Referenced: [Reconstruction theorem](#reconstruction-theorem).


### Representation of finite groups {#representation-of-finite-groups}

{{% definition %}}
A representation of a group \\(G\\) is homomorphism \\(\phi: G \to GL(V)\\) for some (finite-dimensional) vector space \\(V\\). The dimension of \\(V\\) is called the degree of \\(\phi\\).
{{% /definition %}}

equivalence; G-invariant subspace; irreducible representation; completely reducible representation; indecomposable representation; unitary representation


### Schur lemma {#schur-lemma}

{{% lemma %}}
Let \\(\phi\\), \\(\rho\\) be irreducible representation of \\(G\\), and \\(T \in \Hom\_{G}(\phi, \rho)\\). Then either \\(T\\) is invertible or \\(T = 0\\).
{{% /lemma %}}

{{% corollary %}}
Let \\(G\\) be an abelian group. Then any irreducible representation of \\(G\\) has degree 1.
{{% /corollary %}}


### Tensor product of irreducible representations {#tensor-product-of-irreducible-representations}


### 有限群表示的总结 {#有限群表示的总结}

1.  在有限群上的很多操作可以复制到紧群和李群上，如李群表示中的不可约表示以及傅里叶分析。


### 点群 {#点群}

{{% definition %}}
A finite subgroup of O(3) is called a point group.
{{% /definition %}}


## Representation of quivers {#representation-of-quivers}

The basics of the quivers are from [<span id="df38f5636bec59103a70400bed4764c9"><a href="#kirillov2016" title="Kirillov, Quiver Representations and Quiver Varieties, {American Mathematical Society} (2016).">kirillov2016</a></span>].


### Definition of Quivers {#definition-of-quivers}

quiver; subquiver; oriented cycle; loop; morphism; direct sum; subrepresentation; irreducible representation; indecomposable representation; quivers of finite type; path; product of path; path algebra; one-way path

{{% theorem %}}
The category of representations of \\(Q\\) over a field \\(k\\) is equivalent to the category of \\(k(Q)\\)-modules.
{{% /theorem %}}

{{% lemma %}}
The Jacobson radical of the path algebra \\(k(Q)\\) is the span of all one-way paths of \\(Q\\).
{{% /lemma %}}


## Linear Algebra {#linear-algebra}




### Simultaneously diagonalizable {#simultaneously-diagonalizable}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-17 Fri 21:45]</span></span>
For two linear endomorphism \\(A, B\\), if \\([A,B] = 0\\), then \\(A, B\\) can be simultaneously diagonalized.


## Lie Algebra {#lie-algebra}




### Base {#base}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:56]</span></span>
A **base** of a [Root system](#root-system) \\(\Delta \in \phi\\) is a basis for \\(V\\) such that each \\(\alpha \in \phi\\) is a positive or negative integer linear combination from \\(\Delta\\).

For a base \\(\Delta\\) we have \\(\NN \Delta \cap \phi\\) system of [Positive roots](#positive-root). And positive roots can give a bases by [simple roots](#simple-root).

Referenced: [Fundamental weight](#fundamental-weight).


### Dominant {#dominant}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 19:00]</span></span>
For \\(\\{\lambda\_{i}\\}\\) [Fundamental weights](#fundamental-weight), \\(\lambda \in P(\phi) = \oplus\_{i} \ZZ \lambda\_{i}\\) is called **dominant** if \\(\langle \lambda, \alpha\_{j}^{\vee} \rangle \geq 0\\) for all \\(j\\).

Cf. [Root system](#root-system).


### Fundamental weight {#fundamental-weight}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:58]</span></span>
For \\(\Delta = \\{\alpha\_{1}, \cdots, \alpha\_{n}\\}\\) [Base](#base) for \\(\phi\\), we define the **fundamental weights** \\(\\{\lambda\_{1}, \cdots, \lambda\_{n}\\}\\) basis for \\(V\\) dual to \\(\Delta^{\vee}\\) so that \\(\langle \lambda\_{i}, \alpha\_{j}^{\vee}\rangle = \delta\_{ij}\\).

Cf. [Root system](#root-system).

Referenced: [Dominant](#dominant).


### <span class="org-todo todo TODO">TODO</span> Poinccaré-Birkhoff-Witt theorem {#poinccaré-birkhoff-witt-theorem}


### Positive root {#positive-root}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:53]</span></span>
Let \\((G, T)\\) split [Reductive](#reductive), there exists [Borel](#borel) \\(B \supset T\\), and therefore \\(\mathfrak{b} \supset \mathfrak{t}\\). Let \\(\phi\\) be the [Root system](#root-system) of \\(G\\), we define the **positive root** to by \\(\phi^{+ }(B) = \\{\alpha \in \phi \mid \mathfrak{g}\_{\alpha} \subset \mathfrak{b}\\}\\).

Referenced: [Base](#base).


### <span class="org-todo todo TODO">TODO</span> Root system {#root-system}



Referenced: [Base](#base), [Dominant](#dominant), [Fundamental weight](#fundamental-weight), [Positive root](#positive-root).


### <span class="org-todo todo TODO">TODO</span> simple root {#simple-root}



Referenced: [Base](#base).


## Differential Geometry {#differential-geometry}


### Cartan's magic formula {#cartan-s-magic-formula}



{{% theorem %}}
On a smooth manifold \\(M\\) for any smooth vector field \\(V\\) and any smooth differential form \\(\omega\\),
\\[\mathscr{L}\_{V} \omega = V \iprod (\dif \omega) + \dif (V \iprod \omega)\\]
{{% /theorem %}}


### Collar {#collar}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:56]</span></span>
A collar of a smooth boundary [Manifold](#manifold) \\(M\\) is a diffeomorphism \\(\kappa: \partial M \times \rinterval{0}{1} \to M\\) where the image is an open neighborhood of \\(\partial M\\) in \\(M\\) and \\(\kappa(x, 0) = x\\).

For collar, we have following proposition

{{% proposition %}}
A smooth boundary manifold \\(M\\) has a collar.
{{% /proposition %}}

The proposition is similar to the existence of the tubular neighborhood for [Normal bundle](#normal-bundle).


### Complete integral distribution {#complete-integral-distribution}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:35]</span></span>
Given a rank \\(k\\) [Distribution](#distribution) \\(D \subset TM\\), let us say that a smooth coordinate chart \\((U, \phi)\\) on \\(M\\) is **flat** for \\(D\\) if \\(\phi(U)\\) is a cube in \\(\RR^{n}\\) and at points of \\(U\\), \\(D\\) is spanned by the first \\(k\\) coordinate vector fields \\(\partial/ \partial x^{1}, \cdots, \partial/ \partial x^{k}\\).

A distribution \\(D \subset TM\\) is **completely integrable** if there exists a flat chart for \\(D\\) in a neighborhood of each point of \\(M\\).

Referenced: [Frobenius theorem](#frobenius-theorem).


### Connected sum {#connected-sum}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-31 Tue 17:46]</span></span>
Given two \\(n\\)-[manifolds](#manifold) \\(M\_{1}\\), and \\(M\_{2}\\), we define the **connected sum** of \\(M\_{1}\\) and \\(M\_{2}\\) by remove two \\(D^{n}\\) in \\(M\_{1}\\) and \\(M\_{2}\\) and glue two \\(S^{n - 1}\\) together, denoted by \\(M\_{1} \shar M\_{2}\\).


### Connection {#connection}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-06 Mon 19:32]</span></span>
A **connection** on a [Vector bundle](#vector-bundle) \\(E \to M\\) is a linear map \\(\nabla^{E} : C^{\infty}(E) \to C^{\infty}(E \otimes T^{ \*}M)\\) satisfying the condition
\\[\nabla^{E}(\alpha e) = \alpha \nabla^{E} e + e \otimes \dif \alpha\\]
whenever \\(e \in C^{\infty}\\) is a smooth section of \\(E\\) and \\(\alpha\\) is a smooth function on \\(M\\).

A **connection** on a [Principal bundle](#principal-bundle) is a linear map \\(A: TP \to \ker(\pi\_{\*})\\) that equals the identity on the kernal of \\(\pi\_{\*}\\) and is equivariant with respect to the action of \\(G\\) on \\(P\\). Here \\(\pi: P \to M\\) is the projection map, \\(\ker(\pi\_{\*})\\) is often called **vertical subbundle**. Equivariant means that if \\(g \in G\\) and \\(v \in TP\\), then \\((m\_{g})\_{\*} (Av) = A((m\_{g})\_{\*} v)\\). \\(\ker(A)\\) is often called **horizontal subbundle**.

By isomorphism of \\(\psi: P \times \mathfrak{lie}(G) \to \ker(\pi\_{\*})\\) we can view a connection as a map
\\[A: TP \to \mathfrak{lie}(G)\\]
(or in other words \\(A: \mathfrak{lie}(G) \to \mathfrak{lie}(G) \times T^{\*}M\\))
with \\(A(\psi(p,m)) = m\\) and \\(A(m\_{g\*}v) = gA(v)g^{-1}\\)

Referenced: [Flat](#flat), [Covariant derivative](#covariant-derivative), [Curvature](#curvature), [Holonomy group](#holonomy-group), [Horizontal subbundle](#horizontal-subbundle), [Vertical subbunel](#vertical-subbunel), [Chern class](#chern-class), [Chern-Simons functional](#chern-simons-functional).


#### Flat {#flat}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-12 Sun 21:20]</span></span>
A [Connection](#connection) is called **flat** if the [Curvature](#curvature) of the connection is identically zero.

Referenced: [Chern-Simons functional](#chern-simons-functional).


### Covariant derivative {#covariant-derivative}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-12 Sun 20:51]</span></span>
The **covariant derivative** for [Vector bundle](#vector-bundle) is same as [Connection](#connection). (Not sure)

Given a connection on a [Principal bundle](#principal-bundle) \\(P\\), we defines a **covariant derivative** \\(\nabla\_{A}\\) on \\(P \times\_{\rho} V\\) where \\(\rho\\) is a representation of \\(G\\) on \\(V\\). The [Horizontal subbundle](#horizontal-subbundle) \\(H\_{A} \subset TP\\) is canonically isomorphic to \\(\pi^{\*}TM\\). For section \\(s\\) of \\(E\\), we can view it as \\(G\\)-equivariant map \\(s^{P}:P \to V\\). Then the restriction to \\(H\_{A}\\) of the homomorphism \\((s^{P})\_{\*}: TP \to V\\) defines a covariant derivative of \\(s\\). In other word, let \\(x \in M\\) and \\(v \in TM|\_{x}\\). Pick \\(p \in P|\_{X}\\), then there exists a unique \\(v\_{A} \in H\_{A}|\_{p}\\) such that \\(\pi\_{\*} v\_{A} = v\\). Then \\(\nabla\_{A}s\\) defined to send \\(v\\) to the equivalence class in \\(E|\_{x} = (P|\_{x} \times\_{\rho} V)\\) of the pair \\((p, (s^{p})\_{\*}v\_{A})\\).

Referenced: [Exterior covarint derivative](#exterior-covarint-derivative).


### Curvature {#curvature}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-06 Mon 19:41]</span></span>
For a given [Connection](#connection) and therefore [Exterior covarint derivative](#exterior-covarint-derivative) \\(\nabla^{E}\\), there exists a unique smooth section \\(R(\nabla^{E}) \in C^{\infty}(\End(E) \otimes \wedge^{2} T^{\* }M)\\) called the **curvature** of \\(\nabla^{E}\\), that satisfies the equation
\\[R(\nabla^{E}) \cdot (e \otimes v \wedge w) = \nabla\_{v}^{E} \nabla\_{w}^{E} e - \nabla\_{w}^{E} \nabla\_{v}^{E} e - \nabla^{E}\_{ [v,w]}e\\]
for all \\(v,w \in C^{\infty}( TM)\\) and \\(e \in C^{\infty}(E)\\).

Or we can define curvature \\(F\_{\nabla}\\) by \\(\dif\_{\nabla}^{2}m = F\_{\nabla} \wedge m\\).

The famous **Bianchi identity** is
\\[\dif\_{\nabla} F\_{\nabla} = 0\\]

For [Principal bundle](#principal-bundle), we define the \\(F\_{A}\\) to be the section of the bundle \\((P \times\_{ad} \mathfrak{lie}(G)) \otimes \wedge^{2} T^{\*}M\\).

Referenced: [Flat](#flat), [Chern class](#chern-class), [Chern-Simons functional](#chern-simons-functional), [Yang-Mills equation](#yang-mills-equation).


### Degree {#degree}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:25]</span></span>
Suppose \\(M\\) and \\(N\\) are compact, connected, [Oriented](#orientation), smooth manifolds of dimension \\(n\\), and \\(F: M \to N\\) is a smooth map. There exists a unique integer \\(k\\) called the **degree** of \\(F\\), that satisfies

1.  For every smooth \\(n\\)-form \\(\omega\\) on \\(N\\)
    \\[\int\_{M} F^{\* } \omega  = k \int\_{N} \omega\\]
2.  If \\(q\\) is a [Regular value](#regular-point) of \\(F\\), then
    \\[k = \sum\_{x \in F^{-1}(q)} \sgn(x)\\]
    where \\(\sgn(x) = 1\\) if \\(\dif F\_{x}\\) is orientation-preserving and \\(-1\\) if orientation-reversing.


### de Rham cohomology {#de-rham-cohomology}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:15]</span></span>
We define the **de Rham cohomology group** in degree \\(p\\) to be the quotient vector space
\\[H\_{dR}^{p}(M) = \frac{Z^{p}(M)}{B^{p}(M)}\\]
where \\(Z^{p}(M)\\) is the closed \\(p\\)-forms on \\(M\\). then \\(B^{p}(M)\\) is the exact \\(p\\)-forms.

{{% proposition %}}
The de Rham cohomology is homotopy invariants. If \\(M\\) and \\(N\\) is homotopy equivalent manifolds, then \\(H\_{dR}^{n}(M) \cong H^{p}\_{dR}(N)\\) for each \\(p\\). The isomorphisms are induced by any smooth homotopy equivalence \\(F: M \to N\\).
{{% /proposition %}}

Referenced: [de Rham theorem](#de-rham-theorem), [Cohomology](#cohomology).


### de Rham theorem {#de-rham-theorem}



{{% theorem %}}
For every smooth manifold \\(M\\) and nonnegative integer \\(p\\), the de Rham homomorphism \\(J: H\_{dR}^{p}(M) \to H^{p}(M; \RR)\\) is an isomorphism.
{{% /theorem %}}

Cf. [Singular cohomology](#singular-cohomology) and [de Rham cohomology](#de-rham-cohomology).


### Differential form {#differential-form}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 19:42]</span></span>
A section of \\(\Lambda^{k}T^{\* }M\\) is called a **differential \\(k\\)-form**. The integer \\(k\\) is called the **degree** of the form.

Cf. [Tangent bundle](#tangent-bundle).

Referenced: [Exterior derivative](#exterior-derivative), [Invariant formula for the exterior derivative](#invariant-formula-for-the-exterior-derivative), [Stokes's theorem](#stokes-s-theorem).


### Distribution {#distribution}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:28]</span></span>
Cf. [Tangent bundle](#tangent-bundle).

A **distribution** on \\(M\\) of rank \\(k\\) is a rank \\(k\\) subbundle of \\(TM\\). It is called a **smooth** distribution if it is a smooth subbundle.

Referenced: [Complete integral distribution](#complete-integral-distribution), [Integral distribution](#integral-distribution), [Involutive distribution](#involutive-distribution).


### Exterior derivative {#exterior-derivative}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:02]</span></span>
We define the **exterior differential** of [Differential form](#differential-form)
\\[\dif (\sum\_{J} \omega\_{J} \dif x^{J}) = \sum\_{J} \dif \omega\_{J} \wedge \dif x^{J}\\]

Referenced: [Exterior covarint derivative](#exterior-covarint-derivative), [Invariant formula for the exterior derivative](#invariant-formula-for-the-exterior-derivative), [Stokes's theorem](#stokes-s-theorem).


### Exterior covarint derivative {#exterior-covarint-derivative}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-12 Sun 21:07]</span></span>
Cf. [Exterior derivative](#exterior-derivative).

Given a [Covariant derivative](#covariant-derivative) \\(\nabla\\), we can define the **exterior covariant derivative** to be \\(\dif\_{\nabla}\\) such that if \\(\omega\\) is a \\(p\\) form and \\(s\\) is a section of \\(E\\), then \\(\dif\_{\nabla}(s \omega) = \nabla(s) \wedge \omega + s \dif \omega\\)

Referenced: [Curvature](#curvature).


### Frobenius theorem {#frobenius-theorem}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:39]</span></span>
By definition, we have [Complete integral distribution](#complete-integral-distribution) implies [Integral distribution](#integral-distribution) and integral distribution implies [Involutive distribution](#involutive-distribution). The **Frobenius theorem** suggests the reverse.

{{% theorem %}}
Every involutive distribution is completely integrable.
{{% /theorem %}}


### Holonomy group {#holonomy-group}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-06 Mon 19:44]</span></span>
Let \\(M\\) be a [Manifold](#manifold), \\(E\\) a [Vector bundle](#vector-bundle) over \\(M\\), and \\(\nabla^{E}\\) a [Connection](#connection) on \\(E\\). Suppose \\(\gamma: [0,1] \to M\\) is smooth, with \\(\gamma(0) = x\\) and \\(\gamma(1) = y\\), where \\(x,y \in M\\). Then for each \\(e \in E\_{x}\\) there exists a unique smooth section \\(s\\) of \\(\gamma^{\* }(E)\\) satisfying \\(\nabla\_{\dot{\gamma}(t)}^{E} s(t) = 0\\) for \\(t \in [0,1]\\) with \\(s(0) = e\\). Define \\(P\_{\gamma}(e) = s(1)\\). Then \\(P\_{\gamma}: E\_{x} \to E\_{y}\\) is a well-defined linear map called the **parallel transport map**.

Fix a point \\(x \in M\\), we define the **holonomy group** \\(\hol\_{x}(\nabla^{E}) = \\{P\_{\gamma}: \gamma \text{ is a loop based at } x\\} \subset \GL(E\_{x})\\).

Referenced: [Kähler manifold with holomorphic symplectic structure](#kähler-manifold-with-holomorphic-symplectic-structure).


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


### Horizontal subbundle {#horizontal-subbundle}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-12 Sun 20:45]</span></span>
See [Connection](#connection).

Referenced: [Covariant derivative](#covariant-derivative).


### Immersion {#immersion}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:17]</span></span>
A smooth map \\(f\\) is an **immersion** if each \\(T\_{x}f\\) is injective and **submersion** if each \\(T\_{x}f\\) is surjective. Cf. [Tangent space](#tangent-space).

Referenced: [Normal bundle](#normal-bundle), [Submersion](#submersion), [Knot](#knot), [Link](#link).


### Integral distribution {#integral-distribution}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:31]</span></span>
A nonempty immersed submanifold \\(N \subset M\\) is called an **integral manifold** of \\(D\\) if \\(T\_{p}N = D\_{p}\\) at each point \\(p \in N\\). And a [Distribution](#distribution) is called **integral** if every point of \\(M\\) is contained in an integral manifold.

Referenced: [Frobenius theorem](#frobenius-theorem).


### Invariant formula for the exterior derivative {#invariant-formula-for-the-exterior-derivative}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 19:44]</span></span>
Let \\(M\\) be a smooth [Manifold](#manifold), and \\(\omega \in \Omega^{k}(M)\\). For any smooth vector fields \\(X\_{1}, \cdots, X\_{k + 1}\\) on \\(M\\).

\begin{align}\dif \omega (X\_{1}, \cdots, X\_{k + 1}) &= \\\\\\  & \sum\_{1 \leq i \leq k + 1}(-1)^{i - 1}X\_{i}(\omega(X\_{1}, \cdots, \widehat{X\_{i}}, \cdots, X\_{k + 1})) \\\\\\  & + \sum\_{1 \leq i < j \leq k + 1} (-1)^{i + j} \omega([X\_{i}, X\_{j}], X\_{1}, \cdots, \widehat{X}\_{i}, \cdots, \widehat{X\_{j}}, \cdots, X\_{k + 1}) \end{align}

Cf. [Differential form](#differential-form), [Exterior derivative](#exterior-derivative).


### Involutive distribution {#involutive-distribution}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:32]</span></span>
The [Distribution](#distribution) \\(D\\) is **involutive** if given a pair of smooth local sections of \\(D\\), their Lie bracket is also local section of \\(D\\).

Referenced: [Frobenius theorem](#frobenius-theorem).


### Lie derivative {#lie-derivative}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-02 Thu 10:53]</span></span>
Given a smooth covariant tensor field \\(A\\) on \\(M\\), we define the **Lie derivative** of \\(A\\) with respect to \\(V\\), denoted by \\(\mathscr{L}\_{V}A\\) by
\\[(\mathscr{L}\_{V}A)\_{p} = \frac{\dif}{\dif t} \mid\_{t = 0} (\theta\_{t}^{\* }A)\_{p}\\]
Here \\(V\\) is a smooth vector field on \\(M\\), and \\(\theta\\) is its flow. \\(\theta\_{t}\\) is locally an isomorphism.

Referenced: [Liouville vector field](#liouville-vector-field).


### Lie group {#lie-group}



{{% definition %}}
A **Lie group** is a smooth manifold with a group structure, where the group multiplication and inverse are smooth maps.
{{% /definition %}}

Cf. [Manifold](#manifold).

Referenced: [Principal bundle](#principal-bundle).


#### <span class="org-todo todo TODO">TODO</span> E8 {#e8}



Referenced: [Intersection forms](#intersection-forms).


### Manifold {#manifold}



{{% definition %}}
An \\(n\\)-dimensional **manifold** is an \\(n\\)-dimensional locally Euclidean Hausdorff space with countable basis for its topology.
{{% /definition %}}

The definition has three requirements, where the countable basis is hardly used.

{{% definition %}}
A **differential structure**  on the \\(n\\)-manifold \\(M\\) is a maximal smooth atlas \\(\mathscr{D}\\) for \\(M\\). The pair \\((M, \mathscr{D})\\) is called a **smooth manifold** or **differentiable manifold**.
{{% /definition %}}

We call a compact manifold without boundary a **closed manifold**.

Referenced: [Collar](#collar), [Connected sum](#connected-sum), [Holonomy group](#holonomy-group), [Invariant formula for the exterior derivative](#invariant-formula-for-the-exterior-derivative), [Lie group](#lie-group), [Orientation](#orientation), [Riemannian metric](#riemannian-metric), [Tangent space](#tangent-space), [Whitney embedding theorem](#whitney-embedding-theorem), [Fundamental class](#fundamental-class), [Local homology group](#local-homology-group), [Poincaré duality](#poincaré-duality), [Symplectic manifold](#symplectic-manifold), [Freedman's classification of topological 4-manifold](#freedman-s-classification-of-topological-4-manifold), [Rokhlin Theorem](#rokhlin-theorem), [Spin structure](#spin-structure).


### Normal bundle {#normal-bundle}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:48]</span></span>
Let \\(f: M \to N\\) be an [Immersion](#immersion). We define the quotient bundle of the bundle morphism \\(i: TM \to f^{\* }TN|\_{M}\\) to be the **normal bundle**. There exists a neighborhood of the zero section of normal bundle diffeomorphic to the neighborhood of \\(N\\) in \\(M\\). The diffeomorphic map is called **tubular map** and the target is called **tubular neighborhood**.

Cf. [Vector bundle](#vector-bundle), [Tangent bundle](#tangent-bundle).

Referenced: [Collar](#collar).


### Orientable {#orientable}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 13:36]</span></span>
See [Orientation](#orientation).

Referenced: [Heegaard diagram](#heegaard-diagram), [Trisection](#trisection).


### Orientation {#orientation}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:38]</span></span>
An atlas is called **orienting** if any two charts are positively related, that is every two charts has the same orientation as a subset of \\(\RR^{n}\\). If a [Manifold](#manifold) \\(M\\) has an orienting atlas, we call \\(M\\) **orientable**. Notice that if a manifold is orientable, it naturally has two orientation.

Given [Local homology group](#local-homology-group), a generator of the homology group \\(H\_{n}(M, M \backslash x; R) \cong R\\) is called a **local \\(R\\)-orientation**. Let \\(M\\) be a \\(n\\)-manifold and \\(A \subset M\\). An \\(R\\)-orientation of \\(M\\) along \\(A\\) is a section \\(s \subset \Gamma(A; R)\\) of \\(\omega: H\_{n}(M, M \backslash \bullet; R) \to M\\) such that \\(s(a) \in H\_{n}(M, M \backslash a; R) \cong R\\) is a generator for each \\(a \in A\\). For \\(A = M\\), we called it **\\(R\\)-orientation** and for \\(R = \ZZ\\), it is called **orientation**.

By characteristic class theory, a manifold is orientable if the first [Stiefel-Whitney class](#stiefel-whitney-class) vanishes that is \\(w\_{1}(E) = 0\\).

Referenced: [Degree](#degree), [Orientable](#orientable), [Oriented](#oriented), [Euler class](#euler-class), [Fundamental class](#fundamental-class), [Poincaré duality](#poincaré-duality), [Lickorish-Wallace theorem](#lickorish-wallace-theorem).


### Oriented {#oriented}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 13:36]</span></span>
See [Orientation](#orientation).

Referenced: [Linking number](#linking-number), [Seiberg-Witten moduli space](#seiberg-witten-moduli-space), [Seifert surface](#seifert-surface), [Trisection](#trisection).


### Poincaré lemma {#poincaré-lemma}



{{% proposition %}}
If \\(U\\) is a star-shaped open subset of \\(\RR^{n}\\) of \\(\HH^{n}\\), then every closed covector field on \\(U\\) is exact.
{{% /proposition %}}


### Principal bundle {#principal-bundle}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-12 Sun 20:34]</span></span>
A **principal bundle** is a fiber bundle with fiber [Lie group](#lie-group) \\(G\\) and free \\(G\\) actions fiberwise.

Referenced: [Connection](#connection), [Covariant derivative](#covariant-derivative), [Curvature](#curvature).


### Regular point {#regular-point}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:20]</span></span>
For a smooth map \\(f: M \to N\\), a point \\(x \in M\\) is called a **regular point** if \\(T\_{x}f\\) is surjective and a point \\(y \in N\\) is called a **regular value** if each \\(x \in f^{-1}(y)\\) is a regular point, otherwise is called a **singular value**. Cf. [Tangent space](#tangent-space).

Referenced: [Degree](#degree), [Sard theorem](#sard-theorem), [Critical point](#critical-point).


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

Referenced: [Spin^C connection](#spin-c-connection).


### Sard theorem {#sard-theorem}



{{% theorem %}}
The set of singular values of a smooth map has measure zero, and the set of regular values is dense.
{{% /theorem %}}

Cf. [Regular point](#regular-point).

{{% remark %}}
In most applications, the dense property implies the existence, as in the case of Whitney embedding theorem.
{{% /remark %}}

Referenced: [Whitney embedding theorem](#whitney-embedding-theorem), [Seiberg-Witten moduli space](#seiberg-witten-moduli-space).


### Stein manifold {#stein-manifold}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-12 Sun 10:07]</span></span>
A **stein manifold** is a complex manifold which is a holomoprhically convex and holomorphically separable subset of \\(\CC^{n}\\). This is equivalent to \\(\Sigma\\) admits a proper holomorphic immersion \\(\Sigma \hookrightarrow \CC^{n}\\). In particular, analytification of any affine variety over \\(\CC\\) is a Stein space, but the converse is not true.


### Stokes's theorem {#stokes-s-theorem}



{{% theorem %}}
Let \\(M\\) be an oriented smooth \\(n\\)-manifold with boundary, and let \\(\omega\\) be a compactly generated supported smooth \\((n - 1)\\)-form on \\(M\\). Then
\\[\int\_{M} \dif \omega = \int\_{\partial M} \omega\\]
{{% /theorem %}}

Cf. [Differential form](#differential-form), [Exterior derivative](#exterior-derivative).


### Submersion {#submersion}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 18:14]</span></span>
See [Immersion](#immersion).


### Tangent bundle {#tangent-bundle}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:45]</span></span>
The [Tangent space](#tangent-space) at each point constitutes a [Vector bundle](#vector-bundle) called the **tangent bundle**.

Referenced: [Differential form](#differential-form), [Distribution](#distribution), [Normal bundle](#normal-bundle).


### Tangent space {#tangent-space}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:17]</span></span>
We denote the **tangent space** at point \\(p\\) by \\(T\_{p}(M)\\), and to each map \\(f: M \to N\\) associated a linear map \\(T\_{p}(f): T\_{p}(M) \to T\_{f(p)}N\\) the **differential** of \\(f\\) at \\(p\\), such that
\\[T\_{p}(gf) = T\_{f(p)} g \circ T\_{p}f\\]
The elements of \\(T\_{p}(M)\\) are the **tangent vectors** of \\(M\\) at \\(p\\). Cf. [Manifold](#manifold).

Referenced: [Immersion](#immersion), [Regular point](#regular-point), [Tangent bundle](#tangent-bundle), [Predeformation functor](#predeformation-functor).


### <span class="org-todo todo TODO">TODO</span> Uhlenbeck compactification {#uhlenbeck-compactification}


### Vertical subbunel {#vertical-subbunel}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-12 Sun 20:45]</span></span>
See [Connection](#connection).


### Wedge product {#wedge-product}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 19:39]</span></span>
For \\(w \in \Lambda^{k}(V^{\* })\\) and \\(\eta \in \Lambda^{l}(V^{\* })\\), we define the **wedge product** or **exterior product** to be
\\[\omega \wedge \eta = \frac{(k+l)!}{k!l!} {\rm Alt}(\omega \otimes \eta)\\]


### Whitney embedding theorem {#whitney-embedding-theorem}



{{% theorem %}}
A smooth \\(n\\)-manifold has an embedding as a closed submanifold of \\(\RR^{2n + 1}\\).
{{% /theorem %}}

Cf. [Sard theorem](#sard-theorem), [Manifold](#manifold).


## Algebraic Topology {#algebraic-topology}


### Alexander-Whitney map {#alexander-whitney-map}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-26 Sun 21:25]</span></span>
See [Eilenberg-Zilber theorem](#eilenberg-zilber-theorem).

Referenced: [Cup product](#cup-product).


### Base {#base}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 15:12]</span></span>
See [Fibre bundle](#fibre-bundle).


### Borsuk-Ulam theorem {#borsuk-ulam-theorem}



{{% theorem %}}
Let \\(f: S^{2} \to \RR^{2}\\). Then there exists \\(x \in S^{2}\\) such that \\(f(x) = f(-x)\\).
{{% /theorem %}}

Cf. [Degree](#degree).


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


### Brouwer fixed point theorem {#brouwer-fixed-point-theorem}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-27 Mon 20:40]</span></span>
The **Brouwer fixed point theorem** is an example of non construction existence proof.

{{% theorem %}}
Let \\(f: D^{2} \to D^{2}\\). Then there exists \\(x \in D^{2}\\) such that \\(f(x) = x\\).
{{% /theorem %}}

The Brouwer fixed point theorem can give a proof of the fundamental theorem of algebra.

Referenced: [Existence proof](#existence-proof).


### Category CGWH {#category-cgwh}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 15:51]</span></span>
denote the full subcategory of [Compactly generated](#compactly-generated) [Weak Hausdorff](#weak-hausdorff) space by \\(\cat{CGWH}\\).

{{% theorem %}}
The category \\(\cat{CGWH}\\) is complete and cocomplete.
{{% /theorem %}}

Cf. [Complete](#complete), [Cocomplete](#cocomplete).

Also, we have for \\(X, Y \in \cat{CGWH}\\),
\\[{\rm Map}(X, Y) \in \cat{CGWH}\\]
and the exponential law holds.

Referenced: [Realization](#realization), [Loop space](#loop-space).


### Cellular {#cellular}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:52]</span></span>
Let \\((X, Y)\\) be [CW complexes](#cw-complex). A map \\(f: X \to Y\\) is called **cellular** if \\(f(X^{n}) \subset Y^{n}\\) for any \\(n\\). We define the category \\((cat{CW})\\) whose objects are CW complexes and morphisms are cellular maps.

Referenced: [Cellular approxiamtion theorem](#cellular-approxiamtion-theorem), [Cellular homotopy](#cellular-homotopy).


### Cellular approxiamtion theorem {#cellular-approxiamtion-theorem}



{{% theorem %}}
Any map between relative CW complexes is homotopic to a cellular map. If two cellular maps between relative CW complexes are homotopic, then they are cellular homotopic.
{{% /theorem %}}

Cf. [Cellular homotopy](#cellular-homotopy), [Cellular](#cellular) and [Relative CW complex](#relative-cw-complex).


### Cellular homotopy {#cellular-homotopy}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:54]</span></span>
A **cellular homotopy** between two [Cellular](#cellular) maps \\(X \to Y\\) is a [Homotopy](#homotopy) \\(X \times I \to Y\\) that itself a cellular map. The quotient category is called \\(\cat{hCW}\\).

Referenced: [Cellular approxiamtion theorem](#cellular-approxiamtion-theorem).


### Chern class {#chern-class}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-22 Wed 20:40]</span></span>
Consider complex [Vector bundle](#vector-bundle) \\(E \to X\\), we wan to find sections linear independent everywhere. Then we have primary obstruction **Chern class** \\(c\_{n - k + 1} \in H^{2 (n - k + 1)}(X; \ZZ)\\). Axioms of Chern class include \\(c\_{0}(E) = 1\\), naturality and product structure and normalization \\(c(T \CC \PP^{n}) = (1 + w)^{n + 1}\\) for \\(w = \pd [\CC \PP^{n - 1}]\\).

All characteristic class (classes satisfies the naturality condition) for complex vector bundles are combination of Chern classes.

For complex manifod, with [Connection](#connection) \\(\nabla\_{A}\\), we can calculate the Chern class analytically by **Chern-Weil formula**

{{% theorem %}}
\\[\sum t^{k}c\_{k}(E) = \det(I - \frac{t F\_{A}}{2 \pi i})\\]
where \\(F\_{A}\\) is the curvature with respect to connection \\(\nabla\_{A}\\).
{{% /theorem %}}

Cf. [Curvature](#curvature).

This can be generalized to principal bundles.

Referenced: [Pontryagin class](#pontryagin-class), [Chern-Weil theory](#chern-weil-theory).


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


### Cobordism hypothesis {#cobordism-hypothesis}


### Cofibered {#cofibered}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-09 Sat 15:12]</span></span>
We say a pair \\((X, A)\\) is **cofibered** if the inclusion \\(A \subset X\\) is a [Cofibration](#cofibration).


### Cofiber exact sequence {#cofiber-exact-sequence}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:14]</span></span>
Cf. [Exact Puppe sequence](#exact-puppe-sequence).
Let \\(f: X \to Y\\) in \\(\cat{CGWH\*}\\) between well-pointed spaces. The following sequence is co-exact in \\(\cat{hCGWH\*}\\)
\\[X \to Y \to C\_{\* f} \to \Sigma X \to \Sigma Y \to \Sigma C\_{\* f} \to \Sigma^{2}X \to \cdots\\]
Cf. [Cone](#cone).


### Cofibration {#cofibration}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-09 Sat 15:05]</span></span>
A map \\(i: A \to X\\) is called a **cofibration** if it has [Homotopy extension property](#homotopy-extension-property) for any spaces.

An equivalent saying is the follow one.

{{% proposition %}}
Let \\(i: A \to X\\) and \\(j: M\_{i} \to X \times I\\). Then \\(i\\) is a cofibration if and only if there exists \\(r: X \times I \to M\_{i}\\) such that \\(r \circ j = 1\_{M\_{i}}\\).
{{% /proposition %}}

{{% proposition %}}
Let \\(i: A \to X\\) be a cofibration. Then \\(i\\) is a homeomorphism to its image. If we work in \\(\cat{CGWH}\\), then \\(i\\) has closed image.
{{% /proposition %}}

{{% exam %}}
The inclusion \\(S^{n - 1} \to D^{n}\\) is a cofibration.
{{% /exam %}}

Referenced: [Cofibered](#cofibered), [Well-pointed](#well-pointed).


### Cohomology {#cohomology}



There are various **cohomology** theories. The can be defined by common axioms.

{{% definition %}}
A **cohomology theory** for pairs of spaces with values in the category of \\(R\\)-modules consists of a family \\((h^{n} \mid n \in \ZZ)\\) of contravariant functors \\(h^{n}: TOP(2) \to R-MOD\\) and natural transformations \\(\delta^{n}: h^{n - 1} \circ \kappa \to h^{n}\\) such that

-   Homotopy invariance. Homotopic maps \\(f\_{0}\\) and \\(f\_{1}\\) between pairs of space induces the same homomorphism \\(h^{n}(f\_{0}) = h^{n}(f\_{1})\\).
-   Exact sequence. For each pair \\((X, A)\\), we have exact sequence
    \\[\cdots \to h^{n - 1}(A, \emptyset) \stackrel{\delta}{\to} h^{n}(X, A) \to h^{n}(X, \emptyset) \to h^{n}(A) \to \cdots \\]
-   Excision. Let \\((X, A)\\) be a pair and \\(U \subset A\\) such that \\(\bar{U} \subset A^{\circ}\\). Then the inclusion \\((X \backslash U, A \backslash U) \to (X,A)\\) induces an isomorphism \\(h^{n}(X, A) \cong h^{n}(X \backslash U, A \backslash U)\\).
{{% /definition %}}

Cf. [Excision theorem](#excision-theorem), [Mayer-Vietoris sequence](#mayer-vietoris-sequence).

Given a cohomology theory, we called \\(h^{n}(X,A)\\) the \\(n\\)-th **cohomology group**. The \\(\delta^{n}\\) are called the coboundary operator. And we write \\(h^{n}(X) := h^{n}(X, \emptyset)\\).

As in homology theory, we called \\(h^{n}(pt)\\) the coefficient groups of the theory and a cohomology theory may have following additional axioms

-   dimension axiom. \\(h^{n}(pt) = 0\\) for \\(n \neq 0\\).
-   additive axiom. \\[h^{n}(\coprod X\_{j}, \coprod A\_{j}) \to \coprod\_{j} h^{n}(X\_{j}, A\_{j})\\]
    is always an isomorphism.

Also, we have triple exact sequence
\\[ \cdots \to h^{n - 1}(A, B) \stackrel{\delta}{\to} h^{n}(X, A) \to h^{n}(X, B) \to h^{n}(A, B) \stackrel{\delta}{\to} \cdots\\]

Cf. [de Rham cohomology](#de-rham-cohomology).

Referenced: [Cap product](#cap-product), [Eilenberg-Mac Lane space](#eilenberg-mac-lane-space), [Excision theorem](#excision-theorem), [Mayer-Vietoris sequence](#mayer-vietoris-sequence), [Reduced cohomology](#reduced-cohomology), [Category of modules](#category-of-modules).


#### Singular cohomology {#singular-cohomology}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:23]</span></span>
Cf. [Singular homology](#singular-homology).

We consider the cochain complex \\(S^{n}(X; G) = \Hom(S\_{n}(X), G)\\) and define the i-th **singular cohomology** by the i-th cohomology group of the cochain complex.

Referenced: [de Rham theorem](#de-rham-theorem).


#### Relative singular cohomology {#relative-singular-cohomology}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-13 Wed 21:00]</span></span>
We define the **relative singular cochain complex** by \\(S^{\bullet}(X, A; G) = \Hom(S\_{\bullet}(X)/S\_{\bullet}(A), G)\\). Its cohomology is called the **relative singular cohomology**.


#### Compactly supported cohomology {#compactly-supported-cohomology}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-27 Mon 20:24]</span></span>
Let \\(\mathscr{K}\\) denote the set of compact subspaces of \\(X\\). We define **compactly supported cohomology** of \\(X\\) by
\\[H\_{c}^{k}(X) :=\colim\_{K \in \mathscr{K}} H^{k}(X, X - K)\\]
In particular if \\(X\\) is compact, we have \\(H\_{c}^{k}(X) = H^{k}(X)\\).

The compactly supported cohomology also satisfies [Mayer-Vietoris sequence](#mayer-vietoris-sequence).

Referenced: [Poincaré duality](#poincaré-duality).


#### Cup product {#cup-product}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-03 Fri 20:36]</span></span>
One of the most difference between homology theory and cohomology theory is the multiplicative structure making cohomology group a cohomology rings.
\\[h^{m}(X, A) \otimes\_{R} h^{n}(X, B) \to h^{m + n}(X, A \cap B)\\]
We call \\(x \cap y\\) the **cup product** of \\(x, y\\). The cup product is defined if \\(A\\) or \\(B\\) is empty or \\(A = B\\). We have axioms of cup product

-   Naturality: For triads \\(f:(X, A, B) \to (X'; A', B')\\) we have
    \\[f^{ \*}(x \cup y) = f^{ \*}(x) \cup f^{ \*}(y)\\]
-   Stability: TODO
-   Unit element: There is a unit \\(1 \in h^{0}(pt)\\) such that \\(1\_{X} = p^{\*}(1)\\) is the unit of multiplication in cohomology ring.
-   Associativity: \\((x \cup y) \cup z = x \cup (y \cup z)\\).
-   Commutativity: \\(x \cup y = (-1)^{\abs{x} \abs{y}} y \cup x\\). Here \\(\abs{x}\\) is the grade in the cohomology ring.

For the most importanct case \\(A = B = \emptyset\\), the cup product can be given by [Alexander-Whitney map](#alexander-whitney-map), that is
\\[(\alpha \cup \beta)(\sigma) = \alpha(\_{p}\sigma) \cdot \beta(\sigma\_{q})\\]

The morphism \\(H^{\* }(-; R)\\) is natural, that is it is a functor from the category of topological spaces to the category of graded commutative rings.


#### Cap product {#cap-product}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-26 Sun 21:34]</span></span>
We have **cap product** between [Cohomology](#cohomology) and [Homology](#homology). That is we first consider the pairing
\\[\langle -, - \rangle: S^{\bullet}(X; R) \times\_{R} S\_{\bullet}(X;R) \to R\\]
for \\(\alpha \in S^{p}(X)\\), \\(\sigma \in S\_{p}(X)\\), \\(r \in R\\), defined as \\(\langle \alpha, (\sigma \otimes r) \rangle = \alpha(\sigma) \cdot r\\).

The we define the cap product by composing the above pairing by \\(1 \otimes \Delta\\), so we have
\\[S^{\bullet}(X;R) \otimes S\_{\bullet}(X;R) \to S^{\bullet}(X;R) \otimes S\_{\bullet}(X \times X; R) \to S^{\bullet}(X;R) \otimes S\_{\bullet}(X;R) \otimes S\_{\bullet}(X;R) \to S\_{\bullet}(X;R)\\]
which induced the map
\\[\cap : H^{p}(X; R) \otimes H\_{p + q}(X; R) \to H\_{q}(X; R)\\]

The cap product makes \\(H\_{\bullet}(X; R)\\) an \\(H^{\bullet}(X;R)\\)-module.

{{% remark %}}
The cap product can be generalized to relative case
\\[\cap: H^{p}(X;A) \otimes H\_{p + q}(X, A) \to H\_{q}(X)\\]
\\[\cap: H^{p}(X) \otimes H\_{p + q}(X, A) \to H\_{q}(X, A)\\]
{{% /remark %}}


#### External product {#external-product}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-07 Tue 21:42]</span></span>
For details see, section 17.3 in [<span id="5ad6139c99b6d2508f6ef6f11ce7f09d"><a href="#dieck2008" title="tom Dieck, Algebraic Topology, {European Mathematical Society} (2008).">dieck2008</a></span>].

The **external product** is a family of \\(R\\)-linear maps
\\[h^{m}(X, A) \otimes\_{R} h^{n}(Y, B) \to h^{m + n}((X, A) \times (Y, B)), x \otimes y \to x \times y\\]
The external products satisfying some properties.


### Compactly generated {#compactly-generated}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 15:43]</span></span>
A subset \\(Y \subset X\\) is called **compactly closed** or **\\(k\\)-closed** if \\(f^{-1}(Y)\\) is closed in \\(K\\) for every continuous map \\(f: K \to X\\) with \\(K\\) compact Hausdorff. We define a new topology on \\(X\\) denoted by \\(X\\), where close subsets of \\(kX\\) are compactly closed subsets of \\(X\\). The map \\(kX \to X\\) is a continuous map. \\(X\\) is called **compactly generated** if \\(kX = X\\). The full subcategory of \\(\cat{Top}\\) consisting of compactly generated space is denoted by \\(\cat{CG}\\).

{{% proposition %}}
Every locally compact Hausdorff space is compact generated.
{{% /proposition %}}

We have exponential law in \\(\cat{CG}\\).

{{% theorem %}}
Let \\(X,Y,Z \in \cat{CG}\\). Then we have homeomorphism
\\[{\rm Map}(X \times Y, Z) \to {\rm Map}(X, {\rm Map}(Y,Z))\\]
{{% /theorem %}}

Referenced: [Category CGWH](#category-cgwh).


### Complex line bundle over CP^1 {#complex-line-bundle-over-cp-1}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-24 Tue 10:18]</span></span>
We have that \\(H(k) = (\mathbb{C}^{2} \backslash 0) \times\_{\mathbb{C}^{\* }} \mathbb{C}\\) with equivalence relation \\(((z\_{0}, z\_{1}), u) \sim ((\lambda z\_{0}, \lambda z\_{1}), \lambda^{k} u) \\). Then we have that \\(H(k)\\) represent the isomorphism classes of complex line bundles.

{{% remark %}}
This is a simple but non-trivial fact, leading naturally to the problems of complex line bundles over \\(\mathbb{C}P^{n}\\). And more generally, vector bundles over \\(\mathbb{C}P^{n}\\).
{{% /remark %}}

Cf. [Vector bundle](#vector-bundle)

Referenced: [Bott periodicity](#bott-periodicity).


### Cone {#cone}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:18]</span></span>
Let \\((X, x\_{0}) \in \cat{CGWH\*}\\). We define its **cone** by
\\[C\_{\* }X = X \wedge I = X \times I / (X \times \\{0\\} \cap \\{x\_{0}\\} \times I)\\]
Cf. [Smash product](#smash-product).

Referenced: [Cofiber exact sequence](#cofiber-exact-sequence), [Homotopy cofiber](#homotopy-cofiber).


### <span class="org-todo todo TODO">TODO</span> Contractible {#contractible}



Referenced: [Integer homology 3-sphere](#integer-homology-3-sphere).


### Covering {#covering}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 15:10]</span></span>
A **covering (space)** is a [Locally trivial](#local-trivial) map \\(p: E \to B\\) with discrete [Fibre](#fibre) \\(F\\). A covering map which is a trivial [Fibre bundle](#fibre-bundle) is also called a **trivial covering**.

{{% exam %}}
\\[S^{n} \to \RR P^{n}\\] is a double covering.
{{% /exam %}}

{{% exam %}}
The map \\(\RR^{1} \to S^{1}\\), \\(t \to e^{2 \pi i t}\\) is a \\(\ZZ\\)-covering.
{{% /exam %}}

{{% theorem %}}
Assume \\(B\\) is path connected, locally path connected and semi-locally simply connected and \\(b \in B\\). Then there exists an equivalence of categories
\\[\cat{Cov}(B) \cong \pi\_{1}(B, b)-\cat{Set}\\]
{{% /theorem %}}

Cf. [Path connected](#path-connected), [Semi-locally simply connected](#semi-locally-simply-connected).

Referenced: [Deck transformation](#deck-transformation), [Fibration](#fibration), [Fundamental group](#fundamental-group), [G-principal covering](#g-principal-covering), [Lifting](#lifting), [Universal covering](#universal-covering).


### CW approximation {#cw-approximation}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:58]</span></span>
A **CW approximation** of a topological space \\(Y\\) is a [CW complex](#cw-complex) \\(X\\) with a [Weak homotopy equivalence](#weak-homotopy-equivalence) \\(f: X \to Y\\).

The following theorem making the study of topological space reduces to the study of CW complex up to weak homotopy equivalence.

{{% theorem %}}
Any space has a CW approximation.
{{% /theorem %}}


### <span class="org-todo todo TODO">TODO</span> CW complex {#cw-complex}



Referenced: [Cellular](#cellular), [CW approximation](#cw-approximation), [Eilenberg-Mac Lane space](#eilenberg-mac-lane-space), [Whitehead theorem](#whitehead-theorem).


### Deck transformation {#deck-transformation}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:29]</span></span>
Let \\(B\\) be a [Path connected](#path-connected) and \\(p: E \to B\\) be a connected [Covering](#covering). A **deck transformation** is a homeomorphism \\(f: E \to E\\) such that \\(p \circ f = p\\). We denote the group of deck transformations by \\( \aut(p)\\).


### Deformation retract {#deformation-retract}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:19]</span></span>
See [Retraction](#retraction).

Referenced: [Neighborhood deformation retract](#neighborhood-deformation-retract).


### Degree {#degree}



For degree of isogeny, see [Isogeny](#isogeny).

For degree of a map \\(f: S^{n} \to S^{n}\\), the **degree** its image in the [Homotopy group](#homotopy-group) \\(\pi\_{n}(S^{n}) \cong \ZZ\\).

Referenced: [Borsuk-Ulam theorem](#borsuk-ulam-theorem).


### Eilenberg-Mac Lane space {#eilenberg-mac-lane-space}



{{% definition %}}
The **Eilenberg-Mac Lane space** \\(K(G, n)\\) is the space with homotopy group \\(\pi\_{i}(K(G,n)) = 0\\) for \\(i \neq n\\) and \\(G\\) if \\(i = n\\).
{{% /definition %}}

{{% theorem %}}
The Eilenberg-Mac Lane spaces exist.
{{% /theorem %}}

Eilenberg-Mac Lane space is the representation space for [Cohomology](#cohomology), that is we have the following

{{% theorem %}}
\\[H^{n}(X; G) \cong [X, K(G,n)]\\]
for any CW complex \\(X\\).
{{% /theorem %}}

Cf. [CW complex](#cw-complex).

{{% exam %}}
\\[\CC P^{\infty} = K(\ZZ, 2)\\]
{{% /exam %}}

Referenced: [Classifying space](#classifying-space), [Classifying Space](#classifying-space).


### Eilenberg-Zilber theorem {#eilenberg-zilber-theorem}



{{% theorem %}}
If \\(H\_{0}(S\_{\bullet}(X \times Y)) = H\_{0}(S\_{\bullet}(X)) \otimes H\_{0}(S\_{\bullet}(Y))\\), then there exists natural transformations
\\[S\_{\bullet}(- \times -) \stackrel{F}{\underset{G} \Longleftrightarrow} S\_{\bullet}(-) \otimes S\_{\bullet}(-)\\]
And therefore isomorphisms on homology groups. Here \\(F\\), \\(G\\) is called **Eilenberg-Zilber map**.
{{% /theorem %}}

The proof of the theorem relies on [Spectral sequence](#spectral-sequence) and is rather abstract. However, for [Singular homology](#singular-homology), there exists a explicit form of the Eilenberg-Zilber map, called **Alexander-Whitney map**. First for \\(\sigma: \Delta^{n} \to X\\), we introduce the map \\( \_{p} \sigma: \Delta^{p} \to X, \_{p} \sigma(t\_{0}, \cdots, t\_{p}) = \sigma(t\_{0}, \cdots, t\_{p}, 0 ,\cdots, 0)\\) and \\(\sigma\_{q}(t\_{0}, \cdots, t\_{q}) = \sigma(0, \cdots, 0, t\_{0}, \cdots, t\_{q})\\), and then we have Alexander-Whitney map
\\[AW: S\_{\bullet}(X \times Y) \to S\_{\bullet}(X) \otimes S\_{\bullet}(Y)\\]
given by
\\[AW(\sigma) = \sum\_{p + q = n} {}\_{p}(\pi\_{X} \circ \sigma) \otimes (\pi\_{Y} \circ \Sigma)\_{q}\\]
By Eilenberg-Zilber theorem, the above map is a chain homotopy equivalence.

Cf. [Homology](#homology).

Referenced: [Alexander-Whitney map](#alexander-whitney-map).


### <span class="org-todo todo TODO">TODO</span> Equivariant cohomology {#equivariant-cohomology}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-29 Sun 15:25]</span></span>
Compared with classical cohomology theory, the equivariant cohomology is more general and simpler.

Referenced: [Geometric representation theory](#geometric-representation-theory).


### <span class="org-todo todo TODO">TODO</span> Equivariant K-theory {#equivariant-k-theory}



Referenced: [Geometric representation theory](#geometric-representation-theory).


### Euler class {#euler-class}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-22 Wed 20:34]</span></span>
Let \\(p: E \to X\\) be a real [Oriented](#orientation) [Vector bundle](#vector-bundle) of dimension \\(n\\), we want to find a nowhere vanishing section \\(s: X \to E\\), the primary obstruction is defined as the **Euler class** \\(e(E) \in H^{n}(X; \ZZ)\\). A geometric definition is taht we consider a generic section \\(s: X \to E\\) which is transverse to zero section, then \\(s^{-1}(0)\\) is a submanifold of \\(X\\) of codimension \\(n\\) and \\(e(E)\\) can be taken as Poincaré dual of \\([s^{-1}(0)]\\).

Referenced: [Poincaré-Hopf thereom](#poincaré-hopf-thereom).


### Exact Puppe sequence {#exact-puppe-sequence}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-09 Sat 14:26]</span></span>
A sequence in \\(\cat{hCGWH}\\) is **exact** if for any \\(Y\\), the sequence \\(\cdots \to [Y, X\_{n + 1}]\_{0} \to [Y, X]\_{0} \to [Y, X\_{n - 1}]\_{0} \to \cdots\\) is exact. Let [Homotopy fiber](#homotopy-fiber) \\(F\_{f}\\) be the pullback of \\(p\_{1}:P\_{y\_{0}}Y \to Y\\) and \\(f:X \to Y\\) in category \\(\cat{CGWH\*}\\). Then we have

{{% proposition %}}
The sequence \\(F\_{f} \overset{\pi}{\to} X \to \overset{f}{\to} Y\\) is exact in \\(\cat{hCGWH}\\).
{{% /proposition %}}

We also have that \\(\Omega Y = F\_{F\_{f} \to X}\\). So we have exact sequence

{{% lemma %}}
The sequence \\(\Omega X \xrightarrow{\Omega f} \Omega Y \to F\_{f} \xrightarrow{\pi} X \xrightarrow{f} Y\\) is exact in \\(\cat{hCGWH}\\).
{{% /lemma %}}

Also by considering the adjunction formula \\([\sigma Y, X]\_{0} = [Y, \Omega X]\_{0}\\), we have that

{{% lemma %}}
Let \\(X\_{1} \to X\_{2} \to X\_{3}\\) be exact in \\(\cat{hCGWH\*}\\), then so is \\(\Omega X\_{1} \to X\_{2} \to X\_{3}\\).
{{% /lemma %}}

Combining two lemmas above, we get the **exact Puppe sequence**

{{% theorem %}}
Let \\(f:X \to Y\\) in \\(\cat{CGWH\*}\\). Then the following sequence is exact in \\(\cat{hCGWH\*}\\).
\\[\cdots \to \Omega^{2}Y \to \Omega F\_{f} \to \Omega X \to \Omega Y \to F\_{f} \to X \to Y\\]
{{% /theorem %}}

{{% corollary %}}
Let \\(p: E \to B\\) be a fibration whose fiber over the base point is \\(F\\). Then we have an exact sequence of homotopy groups
\\[\cdots \to \pi\_{n}(F) \to \pi\_{n}(E) \to \pi\_{n}(B) \to \pi\_{n - 1}F \to \cdots \to \pi\_{0}(E) \to \pi\_{0}(B)\\]
{{% /corollary %}}

Cf. [Fibration](#fibration), [Homotopy group](#homotopy-group).

Referenced: [Cofiber exact sequence](#cofiber-exact-sequence).


### Excision theorem {#excision-theorem}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-12 Tue 18:07]</span></span>
The [Mayer-Vietoris sequence](#mayer-vietoris-sequence) has a equivalent description called **excision theorem**.

{{% theorem %}}
Let \\(U \subset A \subset X\\) be subspaces such that \\(\bar{U} \subset A^{\circ}\\). Then the inclusion \\(i:(X - U, A - U) \to (X, A)\\) induces isomorphisms
\\[i\_{\* }: H\_{n}(X - U, A - U) \cong H\_{n}(X, A), \; \forall n\\]
{{% /theorem %}}

Cf. [Homology](#homology) and [Cohomology](#cohomology).

Referenced: [Cohomology](#cohomology).


### Fibration {#fibration}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 15:42]</span></span>
A map \\(p: E \to B\\) is a **fibration** if \\(p\\) has [Homotopy lifting property](#homotopy-lifting-property).

{{% theorem %}}
A covering is a fibration.
{{% /theorem %}}

Cf. [Covering](#covering).

By the corollary in [Homotopy fiber](#homotopy-fiber), we see that fibration is similar to [Fibre bundle](#fibre-bundle). In the converse, we have following criterion for fibration

{{% theorem %}}
Let \\(p:E \to B\\) be a fiber bundle with \\(B\\) paracompact Hausdorff. Then \\(p\\) is a fibration.
{{% /theorem %}}

Referenced: [Kan fibration](#kan-fibration), [Exact Puppe sequence](#exact-puppe-sequence), [Homotopy fiber](#homotopy-fiber).


### Fibre {#fibre}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 15:12]</span></span>
See [Fibre bundle](#fibre-bundle).

Referenced: [Covering](#covering).


### Fibre bundle {#fibre-bundle}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 15:07]</span></span>
Let \\(p: E \to B\\) be in \\(\cat{Top}\\). A **trivialization** of \\(p\\) over an open set \\(U \subset B\\) is a homeomorphism \\(\phi:p^{-1}(U) \to U \times F\\) over \\(U\\), such that the following diagram commutes

![](/img/2021-10-07_15-09-18_screenshot.png)
\\(p\\) is called **locally trivial** if there exists an open cover \\(\mathscr{U}\\) of \\(B\\) such that \\(p\\) has trivialization over each open \\(U \in \mathscr{U}\\). Such \\(p\\) is called a **fibre bundle**, \\(F\\) is called the **fiber** and \\(B\\) is called the **base**. And we denoted by
\\[F \to E \to B\\]

Cf. [Vector bundle](#vector-bundle).

{{% exam %}}
\\[S^{1} \to S^{2n + 1} \to \CC P^{n}\\]
{{% /exam %}}

Referenced: [Base](#base), [Covering](#covering), [Fibration](#fibration), [Fibre](#fibre), [Homotopy fiber](#homotopy-fiber), [Local trivial](#local-trivial), [Trvialization](#trvialization).


### Fibre homotopy {#fibre-homotopy}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 21:32]</span></span>
For two fibrations \\(p\_{1}:E\_{1} \to B\\) and \\(p\_{2}: E\_{2} \to B\\) and two fiber maps \\(f\_{0}, f\_{1}:p\_{1} \to p\_{2}\\) are said to be **fiber homotopic** if there exists a homootpy \\(F: E\_{1} \times I \to E\_{2}\\) such that \\(F(-, t)\\) is a fiber map for each \\(t \in I\\). \\(f:p\_{1} \to p\_{2}\\) is a **fiber homotopic equivalence** if there exists an inverse.

{{% proposition %}}
Let \\(p\_{1}:E\_{1} \to B\\) and \\(p\_{2}: E\_{2} \to B\\) be two fibrations and \\(f:E\_{1} \to E\_{2}\\) be a fiber map. Assume \\(f: E\_{1} \to E\_{2}\\) is a homotopy equivalence, then \\(f\\) is a fiber homotopy equivalence. In particular, \\(f: p\_{1}^{-1}(b) \to p\_{2}^{-1}(b)\\) is a homotopy equivalence.
{{% /proposition %}}


### Fundamental class {#fundamental-class}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-31 Tue 18:12]</span></span>
Theorem 16.4.1 in [<span id="5ad6139c99b6d2508f6ef6f11ce7f09d"><a href="#dieck2008" title="tom Dieck, Algebraic Topology, {European Mathematical Society} (2008).">dieck2008</a></span>].

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

Referenced: [Poincaré duality](#poincaré-duality), [Virtual fundamental class](#virtual-fundamental-class).


### <span class="org-todo todo TODO">TODO</span> Fundamental group {#fundamental-group}



{{% proposition %}}
Let \\(p: E \to B\\) be a covering and \\(E\\) path connected. Let \\(e \in E\\) and \\(b = p(e) \in B\\). Then the action of \\(\pi\_{1}(B, b)\\) on \\(p^{-1}(b)\\) is transitive, whose stabilizer at \\(e\\) is \\(\pi\_{1}(E, e)\\). In other words, we have following exact sequence
\\[1 \to \pi\_{1}(E, e) \to \pi\_{1}(B, b) \to p^{-1}(b) \to 1\\]
{{% /proposition %}}

Cf. [Covering](#covering).

{{% theorem %}}
Let \\(p: E \to B\\) be a \\(G\\)-principal covering, \\(E\\) path connected, \\(e \in E\\), \\(b = p(e)\\). Then we have an exact sequence of groups
\\[1 \to \pi\_{1}(E, e) \to \pi\_{1}(B, b) \to G \to 1\\]
That is \\(\pi\_{1}(E, e)\\) is a normal subgroup of \\(\pi\_{1}(B, b)\\).
{{% /theorem %}}

Cf. [G-principal covering](#g-principal-covering) and above theorem.

Referenced: [Homotopy group](#homotopy-group), [Seifert-Van Kampen theorem](#seifert-van-kampen-theorem), [Semi-locally simply connected](#semi-locally-simply-connected), [Braid group](#braid-group).


### <span class="org-todo todo TODO">TODO</span> Fundamental groupoid {#fundamental-groupoid}



Referenced: [Seifert-Van Kampen theorem](#seifert-van-kampen-theorem).


### G-principal covering {#g-principal-covering}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 15:54]</span></span>
A left **\\(G\\)-principal covering** is a [Covering](#covering) \\(p: E \to B\\) with a left [Properly discontinuous](#properly-discontinuous) \\(G\\)-action on \\(E\\) over \\(B\\) commutes with the covering map.

{{% exam %}}
The map \\(\RR^{1} \to S^{1}\\) is a \\(\ZZ\\)-principal covering for action \\(n: t \to t + n\\).
{{% /exam %}}

Referenced: [Fundamental group](#fundamental-group).


### Grothendieck ring {#grothendieck-ring}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-24 Tue 10:55]</span></span>
Given a commutative monoid \\(M\\) which is a set together with an associative and commutative composition law \\(+\\) with zero element. We have a group \\(K(M) = M \times M / D(M)\\). That is elements of \\(K(M)\\) are of the form \\((a,b) \in M \times M\\), with equivalence relation \\((a, b) \sim (c, d)\\) if \\((a + n, b + n) = (c + m, d + m)\\) for some \\(m,n \in M\\). Such group is called **Grothendieck group**. If the monoid is given with a multiplicative structure, which can by inherited by Grothendieck group, the group becomes **Grothendieck ring**.

Referenced: [Bott periodicity](#bott-periodicity), [Vector bundle](#vector-bundle).


### <span class="org-todo todo TODO">TODO</span> Homology {#homology}



Referenced: [Cap product](#cap-product), [Eilenberg-Zilber theorem](#eilenberg-zilber-theorem), [Excision theorem](#excision-theorem), [Hurewicz theorem](#hurewicz-theorem), [Whitehead theorem](#whitehead-theorem).


#### Singular homology {#singular-homology}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-26 Sun 19:55]</span></span>
A **singular n-simplex** is a continuous map \\(\sigma: \Delta^{n} \to X\\), where \\(\Delta^{n}\\) is the [Standard n-simplex](#standard-n-simplex). We define \\(S\_{n}(X)\\) to be the free abelian group by all singular \\(n\\)-simplexes \\(S\_{n}(X) = \oplus\_{\sigma \in \Hom(\Delta^{n}, X)} \ZZ \sigma\\). An element of \\(S\_{n}\\) is called a **singular n-chain** in \\(X\\). Given \\(\sigma: \Delta^{n} \to X\\), we have \\(\partial^{i} \sigma: \Delta^{n - 1} \to X\\) for \\(0 \leq i \leq n\\), by restricting the \\(\sigma\\) to the \\(i\\)-th face of the \\(\Delta^{n}\\) whose vertices are given by \\(\\{v\_{0}, v\_{1}, \cdots, \hat{v}\_{i}, \cdots, v\_{n}\\}\\). And we define the **boundary map** \\(\partial: S\_{n}(X) \to S\_{n - 1}(X)\\) to be \\(\partial \sigma = \sum\_{i = 0}^{n} (-1)^{i} \partial^{(i)} \sigma\\). Then \\((S\_{\bullet}(X), \partial)\\) defines a chain complex and we define the \\(n\\)-th **singular homology** group of \\(X\\) by
\\[H\_{n}(X) = H\_{n}(S\_{\bullet}(X), \partial)\\]

The singular homology groups are homotopy invariants.

The following theorem is sometimes called **dimension axiom**.

{{% theorem %}}
If \\(X\\) is contractible, then

\begin{equation} H\_{n}(X) =   \begin{cases}     0 & n > 0 \\\\\\     \ZZ & n = 0   \end{cases} \end{equation}
{{% /theorem %}}

Referenced: [Simplicial set](#simplicial-set), [Singular cohomology](#singular-cohomology), [Eilenberg-Zilber theorem](#eilenberg-zilber-theorem), [Künneth formula](#künneth-formula), [Local homology group](#local-homology-group), [Poincaré duality](#poincaré-duality).


#### Relative singular homology {#relative-singular-homology}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-12 Tue 17:45]</span></span>
Let \\(A \subset X\\) be a subspace. It induces a natural injective chain map \\(S\_{\bullet}(A) \to S\_{\bullet}(X)\\). We define the singular chain complex of \\(X\\) relative to \\(A\\) to be
\\[S\_{n}(X, A) = S\_{n}(X)/S\_{n}(A)\\]
with the induced differential. Its homology \\(H\_{n}(X, A) = H\_{n}(S\_{\bullet}(X, A))\\) is called the \\(n\\)-th **relative homology**.


#### <span class="org-todo todo TODO">TODO</span> Reduced homology {#reduced-homology}



{{% theorem %}}
Let \\((X, x\_{0})\\) be a well-pointed space, then \\(\tilde{H}\_{n}(\Sigma X) = \tilde{H}\_{n - 1}(X)\\).
{{% /theorem %}}

Cf. [Suspension](#suspension).


#### <span class="org-todo todo TODO">TODO</span> Cellular homology {#cellular-homology}


### <span class="org-todo todo TODO">TODO</span> Homotopy {#homotopy}



Referenced: [Simplicial homotopy](#simplicial-homotopy), [Cellular homotopy](#cellular-homotopy), [Hurewicz theorem](#hurewicz-theorem).


### Homotopy cofiber {#homotopy-cofiber}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:25]</span></span>
Cf. [Homotopy fiber](#homotopy-fiber).

Given \\(f: X \to Y\\) in \\(\cat{CGWH\*}\\), we define **homotopy cofiber** \\(C\_{ \* f}\\) by the push-out of \\(X \to C\_{\*}X\\) and \\(f: X \to Y\\).
Cf. [Cone](#cone).


### Homotopy excision theorem {#homotopy-excision-theorem}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-12 Tue 08:17]</span></span>
Let \\((A, C)\\), \\((B, C)\\) be [Relative CW complex](#relative-cw-complex). Let \\(X\\) be the push-out of \\(C \to B\\) and \\(C \to A\\). If \\((A, C)\\) is [m-connected](#n-connected) and \\((B, C)\\) is [n-connected](#n-connected), then
\\[\pi\_{i}(A, C) \to \pi\_{i}(X, B)\\]
is an isomorphism for \\(i < m + n\\) and a surjection for \\(i = m + n\\).


### Homotopy extension property {#homotopy-extension-property}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-09 Sat 15:02]</span></span>
A map \\(i: A \to X\\) is said to have the **homotopy extension property** (HEP) with respect to \\(Y\\) if for any map \\(f:X \to Y\\) and any homotopy \\(F:A \times I \to Y\\), we have following commutative diagram.

{{< figure src="/img/2021-10-09_15-04-49_screenshot.png" >}}

Referenced: [Cofibration](#cofibration).


### Homotopy fiber {#homotopy-fiber}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-09 Sat 14:52]</span></span>
Let \\(f: X \to Y\\), we define its **homotopy fiber** over \\(y \in Y\\) to be the fiber of \\(P\_{f} \to Y\\) over \\(y\\). Then we have

{{% proposition %}}
If \\(Y\\) is path connected, then all homotopy fibers of \\(f:X \to Y\\) are homotopic equivalent.
{{% /proposition %}}

Cf. [Path connected](#path-connected).

{{% proposition %}}
If \\(f: X \to Y\\) is a fibration, then its homotopy fiber at \\(y\\) is homootpy equivalent to \\(f^{-1}(y)\\).
{{% /proposition %}}

{{% corollary %}}
Let \\(f:X \to Y\\) be a fibration and \\(Y\\) path connected. Then all fibers of \\(f\\) are homotpy equivalent.
{{% /corollary %}}

Therefore, [Fibration](#fibration) is similar to [Fibre bundle](#fibre-bundle).

Referenced: [Exact Puppe sequence](#exact-puppe-sequence), [Fibration](#fibration), [Homotopy cofiber](#homotopy-cofiber).


### <span class="org-todo todo TODO">TODO</span> Homotopy group {#homotopy-group}



Unlike the [Fundamental group](#fundamental-group), the higher homotopy group is abelian.

{{% proposition %}}
\\(\pi\_{n}(X)\\) is abelian if \\(n \geq 2\\).
{{% /proposition %}}

Referenced: [Simplicial homotopy group](#simplicial-homotopy-group), [Degree](#degree), [Exact Puppe sequence](#exact-puppe-sequence), [Smash product](#smash-product).


### Homotopy lifting property {#homotopy-lifting-property}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 15:43]</span></span>
A map \\(p: E \to B\\) is said to have the **homotopy lifting property** with respect to \\(X\\) if for every \\(\tilde{f}\\) and \\(F\\) we have \\(\tilde{F}\\) making the following diagram commutes.

{{< figure src="/img/2021-10-07_15-44-54_screenshot.png" >}}

Referenced: [Fibration](#fibration).


### Hurewicz theorem {#hurewicz-theorem}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-26 Sun 15:54]</span></span>
The **Hurewicz theorem** relates the [Homotopy](#homotopy) theory and [Homology](#homology) theory. We first fix generator satisfying the compatibility conditions \\(i\_{n} \in \tilde{H}\_{n}(S^{n}) = H\_{n}(D^{n}, S^{n - 1}) = \tilde{H}\_{n - 1}(S^{n - 1})\\). Then we can define **Hurewicz map**
\\[\rho: \pi\_{n}(X) \to H\_{n}(X)\\]
by sending \\([f: S^{n} \to X] \to f\_{\* }(i\_{n})\\). Then we have

{{% proposition %}}
The Hurewicz map is a group homomorphism.
{{% /proposition %}}

The Hurewicz theorem states that in certian circumstances the above homomorphism can be isomorphism.

{{% theorem %}}
Let \\(X\\) be a path-connected \\((n - 1)\\)-connected space. Then the Hurewicz map
\\[\rho\_{n}(\pi\_{n}(X)) \to H\_{n}(X)\\]
is the abelianization homomorphism.
{{% /theorem %}}

Notice that for \\(n \geq 2\\), the homotopy group \\(\pi\_{n}(X)\\) is already abelian.

The theorem can also be written in relative form.

{{% theorem %}}
Let \\((X, A)\\) be a pair of path-connected spaces and \\(A\\) non-empty simply connected. If \\((X, A)\\)is \\((n - 1)\\)-connected, then
\\[H\_{i}(X,A) = 0 \text{ for } i < n\\]
and the Hurewicz map
\\[\pi\_{n}(X,A) \to H\_{n}(X, A)\\]
is an isomorphism.
{{% /theorem %}}

Referenced: [Whitehead theorem](#whitehead-theorem).


### Künneth formula {#künneth-formula}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-26 Sun 21:14]</span></span>
The algebraic version of **Künneth formula** is

{{% theorem %}}
Let \\(C\_{\bullet}\\) and \\(D\_{\bullet}\\) be chain complex of free abelian groups. Then there is a split exact sequence
\\[0 \to (H\_{\bullet}( C) \otimes H\_{\bullet}(D))\_{n} \to H\_{n}(C\_{\bullet} \otimes D\_{\bullet}) \to \Tor(H\_{\bullet}( C), H\_{\bullet}(D))\_{n - 1} \to 0\\]
Here \\(\Tor(H\_{\bullet}, H\_{\bullet}(D))\_{k} = \oplus\_{p + q = k} \Tor(H\_{p}( C), H\_{q}(D))\\).
{{% /theorem %}}

Apply the algebraic version to the [Singular homology](#singular-homology), we have

{{% theorem %}}
For any topological spaces \\(X, Y\\) and \\(n \geq 0\\), there is a split exact sequence
\\[0 \to \oplus\_{p + q = n} H\_{p}(X) \otimes H\_{q}(X) \to H\_{n}(X \times Y) \to \oplus\_{p + q = n - 1} \Tor(H\_{p}(X), H\_{q}(Y)) \to 0\\]
{{% /theorem %}}


### Lefschetz fixed point theorem {#lefschetz-fixed-point-theorem}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-27 Mon 20:33]</span></span>
The [Poincaré duality](#poincaré-duality) gives the **intersection pairing**
\\[\langle -, - \rangle : H\_{i}(X) \times H\_{n - i}(X) \to H\_{0}(X) \cong \mathbb{Z}\\]
or equivalently
\\[\langle -, - \rangle : H^{i}(X) \times H^{n - i}(X) \to H^{n}(X) \cong \mathbb{Z}\\]

Cf. [Intersection forms](#intersection-forms).

By consider the intersection of the diagonal \\(\Delta\\) and the graph of the map \\(f\\), we get the fixed points of \\(f\\). We define the **Lefschetz number** of \\(f\\) by
\\[L(f) := \sum\_{p}(-1)^{p} \tr(f\_{\* }: H\_{p}(X; \QQ) \to H\_{p}(X; \QQ))\\]
Then we have **Lefschetz fixed point theorem**

{{% theorem %}}
When \\(\Gamma\_{f}\\) and \\(\Delta\\) intersections transversely, then we have
\\[\abs{ {\rm Fix}(f)} = L(f)\\]
{{% /theorem %}}


### <span class="org-todo todo TODO">TODO</span> Lifting {#lifting}



The following theorem states when a map can be lifted to its [Covering](#covering) space.

{{% theorem %}}
Let \\(p: E \to B\\) be a covering. Consider a continuous map \\(f: X \to B\\), where \\(X\\) is path connected and locally path connected. Let \\(e\_{0} \in E\\), \\(x\_{0} \in X\\) such that \\(f(x\_{0}) = p(e\_{0})\\). Then there exists a lift \\(F\\) of \\(f\\) with \\(F(x\_{0}) = e\_{0}\\) if and only if
\\[f\_{\* }(\pi\_{1}(X, x\_{0})) \subset \pi\_{\* }(\pi\_{1}(E, e\_{0}))\\]
{{% /theorem %}}

Cf. [Path connected](#path-connected).


### Local homology group {#local-homology-group}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-31 Tue 17:57]</span></span>
Let \\(h\_{\* }(-)\\) be a homology theory and \\(M\\) an \\(n\\)-dimensional [Manifold](#manifold). Then groups of the form \\(h\_{k}(M, M \backslash x)\\) are called **local homology group**.

By excision theorem, we have that \\(h\_{k}(M, M \backslash x)\\) is \\(h\_{k}(D^{n}, D^{n} \backslash x)\\). For [Singular homology](#singular-homology) theory, we have \\(H\_{n}(M, M \backslash x; G) \cong G\\) and other homology groups are all \\(0\\).

For \\(K \subset L \subset M\\), we have homomorphism \\(r\_{K}^{L}: h\_{k}(M, M \backslash L) \to h\_{k}(M, M \backslash K)\\).

Referenced: [Orientation](#orientation), [Fundamental class](#fundamental-class).


### Local trivial {#local-trivial}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 15:13]</span></span>
See [Fibre bundle](#fibre-bundle).

Referenced: [Covering](#covering).


### Loop space {#loop-space}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 21:17]</span></span>
Given \\((X, x\_{0}) \in \cat{CGWH\* }\\), we define the **based loop space** \\(\Omega\_{x\_{0}}X\\) or simply \\(\Omega X\\) by
\\[\Omega X = {\rm Map}\_{\* }(S^{1}, X)\\]
And we define the **free loop space**
\\[\mathscr{L}X = {\rm Map}(S^{1}, X)\\]

Cf. [Category CGWH](#category-cgwh).

Referenced: [Arc space](#arc-space).


### Mapping cylinder {#mapping-cylinder}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-09 Sat 15:06]</span></span>
For \\(f: A \to X\\), we define the **mapping cyclinder** \\(M\_{f}\\) by the pushout of \\(A \times \\{0\\} \to A \times I\\) and \\(A \times \\{0\\} \to X \times \\{0\\}\\).

For based space, let \\(f:(X, x\_{0}) \to (Y, y\_{0}) \in \cat{CGWH\*}\\). We define its **mapping cylinder** by
\\[M\_{\*f} = M\_{f}/ \\{x\_{0} \times I\\}\\]


### Mayer-Vietoris sequence {#mayer-vietoris-sequence}



There are **Mayer-Vietoris sequence** for homology and [Cohomology](#cohomology) theory. For \\((A; A\_{0}, A\_{1}) \subset (X; X\_{0}, X\_{1})\\) be excisive triads that is \\(A = A\_{0}^{\circ} \cap A\_{1}^{\circ}\\) and \\(X = X\_{0}^{\circ} \cap X\_{1}^{\circ}\\). Set \\(X\_{01} = X\_{0} \cap X\_{1}\\) and \\(A\_{01} = A\_{0} \cap A\_{1}\\). Then we have exact sequence
\\[\cdots \to h^{n - 1}(X\_{01}, A\_{01}) \to h^{n}(X, A) \to h^{n}(X\_{0}, A\_{0}) \oplus h^{n}(X\_{1}, A\_{1}) \to h^{n}(X\_{01}, A\_{01}) \to \cdots\\]

Referenced: [Cohomology](#cohomology), [Compactly supported cohomology](#compactly-supported-cohomology), [Excision theorem](#excision-theorem).


### n-connected {#n-connected}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:36]</span></span>
A pair \\((X, A)\\) is called **n-connected** if \\(\pi\_{0}(A) \to \pi\_{0}(X)\\) is surjective and
\\[\pi\_{k}(X, A; x\_{0}) = 0 \; \forall 1 \leq k \leq n, x\_{0} \in A\\]

Let \\(X\\) be obtained from \\(A\\) by attaching \\(n\\)-cells \\((n \geq 1)\\), then \\((X, A)\\) is \\((n - 1)\\)-connected.

Referenced: [Homotopy excision theorem](#homotopy-excision-theorem).


### Neighborhood deformation retract {#neighborhood-deformation-retract}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:02]</span></span>
Let \\(A\\) be a subspace of \\(X\\). \\(A\\) is called a **neighborhood deformation retract** if there exists a continuous map \\(u: X \to I\\) with \\(A = u^{-1}(0)\\) and a homotopy \\(H: X \times I \to X\\) such that

\begin{equation}   \begin{cases}     H(x, 0) = x & \forall x \in X \\\\\\     H(a, t) = a & \text{if } (a, t) \in A \times I \\\\\\     H(x, 1) \in A & \text{if } u(x) < 1   \end{cases} \end{equation}

If \\(A\\) is a NDR of \\(X\\), then \\(A\\) is a strong [Deformation retract](#deformation-retract) of the open subset \\(u^{-1}(\rinterval{0}{1})\\).


### n-equivalence {#n-equivalence}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:38]</span></span>
A map \\(f: X \to Y\\) is called an **n-equivalence** if for any \\(x\_{0} \in X\\) we have \\(f\_{\* }: \pi\_{r}(X,x\_{0}) \to \pi\_{r}(Y, f(x\_{0}))\\) bijective for \\(r < n\\) and \\(f\_{\* }: \pi\_{n}(X, x\_{0}) \to \pi\_{n}(Y, f(x\_{0}))\\) is surjective.

Referenced: [Weak homotopy equivalence](#weak-homotopy-equivalence).


### Numerable {#numerable}



{{% definition %}}
An open covering is called **numerable** if it admits a subordinate partition of unity.
{{% /definition %}}

Partition of unity is one of the important properties of the covering which deserves its own definition.

{{% definition %}}
A vector bundle (locally trivial bundle) \\(\xi: E(\xi) \to B\\) is called **numerable** if there exists a numerable covering on which the vector bundle is trivial.
{{% /definition %}}

Cf. [Vector bundle](#vector-bundle)

Referenced: [Riemannian metric](#riemannian-metric), [Classifying Space](#classifying-space), [Vector bundle](#vector-bundle).


### <span class="org-todo todo TODO">TODO</span> Path connected {#path-connected}



Referenced: [Covering](#covering), [Deck transformation](#deck-transformation), [Homotopy fiber](#homotopy-fiber), [Lifting](#lifting), [Seifert-Van Kampen theorem](#seifert-van-kampen-theorem), [Universal covering](#universal-covering).


### Path space {#path-space}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 21:25]</span></span>
Given \\(X \in \cat{CGWH}\\) and \\(x \in X\\), we define the **free path space** \\(PX = {\rm Map}(I, X)\\) and **based path space** \\(P\_{x}X = {\rm Map}((I, 0), (X, x))\\).

For \\(f: X \to Y\\), and \\(p\_{1}:PY \to Y\\), we define the **mapping path space** \\(P\_{f}\\) by the pull-back \\(PY \times\_{Y} X\\).


### Poincaré duality {#poincaré-duality}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-27 Mon 20:21]</span></span>
The Poincaré duality is the following famous theorem.

{{% theorem %}}
Given \\(X\\) an oriented \\(n\\)-manifold. Then for any \\(p\\)
\\[D: H\_{c}^{p}(X) \to H\_{n - p}(X)\\]
is an isomorphism. In particular, if \\(X\\) is compact, then \\(H^{p}(X) \cong H\_{n - p}(X)\\). The isomorphism is given by cap product with the fundamental class of \\(X\\).
{{% /theorem %}}

Cf. [Orientation](#orientation), [Manifold](#manifold), [Compactly supported cohomology](#compactly-supported-cohomology), [Singular homology](#singular-homology), [Fundamental class](#fundamental-class).

Referenced: [Lefschetz fixed point theorem](#lefschetz-fixed-point-theorem).


### Poincaré-Hopf thereom {#poincaré-hopf-thereom}



{{% theorem %}}
\\(\chi(X) = e(TX) [X] = \sum\_{i = 0}^{\dim X}(-1)^{i}b\_{i}(X)\\), here \\(b\_{i}(X)\\) is the ith betti number.
{{% /theorem %}}

Cf. [Euler class](#euler-class), [Vector bundle](#vector-bundle).


### Pontryagin class {#pontryagin-class}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-22 Wed 20:46]</span></span>
The **Pontryagin class** is defined as \\(P\_{i}(E) = (-1)^{i}c\_{2i}(E \otimes\_{\RR} \CC)\\), where \\(c\_{i}\\) is the [Chern class](#chern-class).

Referenced: [Characteristic class for 4-manifold](#characteristic-class-for-4-manifold).


### <span class="org-todo todo TODO">TODO</span> Postnikov tower {#postnikov-tower}


### <span class="org-todo todo TODO">TODO</span> Properly discontinuous {#properly-discontinuous}



Referenced: [G-principal covering](#g-principal-covering).


### Reduced cohomology {#reduced-cohomology}



The **reduced cohomology groups** are defined to be \\(\tilde{h}^{n}(X) \to \coker(h^{n}(pt) \to h^{n}(X))\\) where the map is induced by \\(p: X \to pt\\).

Cf. [Cohomology](#cohomology).


### <span class="org-todo todo TODO">TODO</span> Relative CW complex {#relative-cw-complex}



Referenced: [Cellular approxiamtion theorem](#cellular-approxiamtion-theorem), [Homotopy excision theorem](#homotopy-excision-theorem).


### <span class="org-todo todo TODO">TODO</span> Relative homotopy group {#relative-homotopy-group}


### Retraction {#retraction}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:01]</span></span>
Let \\(i: A \subset X\\) be an inclusion. A continuous map \\(r: X \to A\\) is called a **retraction** if \\(r \circ i = 1\_{A}\\). \\(r\\) is called a **deformation retraction** if furthermore we have a homotopy \\(i  \circ r \cong 1\_{X} \text{ rel } A\\).

Referenced: [Deformation retract](#deformation-retract).


### Seifert-Van Kampen theorem {#seifert-van-kampen-theorem}



{{% theorem %}}
Let \\(X = U \cap V\\) where \\(U, V \subset X\\) are open. Then the following diagram

{{< figure src="/img/2021-10-07_16-50-43_screenshot.png" >}}

is a pushout in the category \\(\cat{Groupoid}\\).
{{% /theorem %}}

Cf. [Groupoid](#groupoid), [Fundamental groupoid](#fundamental-groupoid).

{{% theorem %}}
Let \\(X = U \cap V\\) where \\(U, V \subset X\\) are open and \\(U, V, U \cap V\\) are path connected. Let \\(x\_{0} \in U \cap V\\). Then the following diagram

![](/img/2021-10-07_16-52-14_screenshot.png)
is a pushout in the category \\(\cat{Group}\\).
{{% /theorem %}}

Cf. [Path connected](#path-connected), [Fundamental group](#fundamental-group).


### Semi-locally simply connected {#semi-locally-simply-connected}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:21]</span></span>
A space is **semi-locally simply connected** if for any \\(x\_{0} \in X\\), there is a neighborhood \\(U\_{0}\\) such that the image of the map \\(i\_{\* }: \pi\_{1}(U\_{0}, x\_{0}) \to \pi\_{1}(X, x\_{0})\\) is trivial.

Cf. [Simply connected](#simply-connected), [Fundamental group](#fundamental-group).

Referenced: [Covering](#covering), [Universal covering](#universal-covering).


### <span class="org-todo todo TODO">TODO</span> Simply connected {#simply-connected}



Referenced: [Semi-locally simply connected](#semi-locally-simply-connected), [Universal covering](#universal-covering).


### Smash product {#smash-product}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:43]</span></span>
We define the **smash product** \\(\wedge\\) by \\(X \wedge Y = X \times Y / X \vee Y\\).

Cf. [Wedge product](#wedge-product).

{{% exam %}}
\\[S^{1} \wedge S^{n} \cong S^{n + 1}\\]
{{% /exam %}}

The above example will be used in the computation of [Homotopy group](#homotopy-group) of \\(S^{n}\\).

Referenced: [Cone](#cone), [Suspension](#suspension).


### Standard n-simplex {#standard-n-simplex}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-12 Tue 16:03]</span></span>
We denote the **standard n-simplex** by \\(\Delta^{n} = \\{(t\_{0}, \cdots, t\_{n}) \in \RR^{n + 1} \mid \sum\_{i = 0}^{n} t\_{i} = 1, t\_{i} \geq 0\\}\\).

Referenced: [Singular homology](#singular-homology).


### Stiefel-Whitney class {#stiefel-whitney-class}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-22 Wed 20:44]</span></span>
For \\(p: E \to X\\) real [Vector bundle](#vector-bundle), we want to find sections linear independent. And we define the **Stiefel-Whitney class** \\(w\_{\* }(E)\\) as the obstruction in \\(H^{\* }(X; \ZZ/2)\\). It is universal for characteristic class in \\(\ZZ/2\\) coeffecients.

Referenced: [Orientation](#orientation), [Characteristic class for 4-manifold](#characteristic-class-for-4-manifold), [Spin^C structure](#spin-c-structure).


### Suspension {#suspension}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 21:20]</span></span>
We define the **suspension** of the space \\(X\\) by \\(\Sigma X = X \wedge S^{1}\\).

Cf. [Smash product](#smash-product).

Referenced: [Reduced homology](#reduced-homology).


### <span class="org-todo todo TODO">TODO</span> Transport functor {#transport-functor}


### Trvialization {#trvialization}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 15:12]</span></span>
See [Fibre bundle](#fibre-bundle).


### Universal coefficient theorem {#universal-coefficient-theorem}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-13 Wed 21:45]</span></span>
The **universal coefficient theorem** for cohomology gives cohomology from homology.

{{% theorem %}}
Let \\(G\\) be an abelian group and \\(X\\) be a topological space. Then for any \\(n \geq 0\\), there exists a split exact sequence
\\[0 \to \Ext(H\_{n - 1}(X), G) \to H^{n}(X; G) \to \Hom(H\_{n}(X), G) \to 0\\]
which induces isomorphisms
\\[H^{n}(X; G) \cong \Hom(H\_{n}(X), G) \oplus \Ext(H\_{n -1}(X), G)\\]
{{% /theorem %}}

The **universal coefficient theorem** for homology gives homology with other coefficients from coefficient \\(\ZZ\\).

{{% theorem %}}
Let \\(G\\) be an abelian group and \\(X\\) be a topological space. Then for any \\(n \geq 0\\), there exists a split exact sequence
\\[0 \to H\_{n}(X) \otimes G \to H\_{n}(X; G) \to \Tor(H\_{n - 1}(X), G) \to 0\\]
which induces isomorphisms
\\[H\_{n}(X; G) \cong (H\_{n}(X) \otimes G) \oplus \Tor(H\_{n - 1}(X), G)\\]
{{% /theorem %}}

{{% remark %}}
The split exact sequence is natural for \\(G\\) but not for \\(X\\).
{{% /remark %}}


### Universal covering {#universal-covering}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:19]</span></span>
A **universal covering** is a [Covering](#covering) which is [Simply connected](#simply-connected).

{{% theorem %}}
If \\(B\\) is path connected, locally path connected, and semi-locally simply connected. Then \\(B\\) admits a universal covering.
{{% /theorem %}}

Cf. [Path connected](#path-connected), [Semi-locally simply connected](#semi-locally-simply-connected).


### Vector bundle {#vector-bundle}



{{% definition %}}
The **Whitney sum** of two vector bundle \\(\xi: E(\xi) \to B\\) and \\(\eta: E(\eta) \to B\\) is \\(d^{\* }(\xi \times \eta) = \xi \oplus \eta\\), where \\(d: B \to B \times B\\) is the diagonal map. A bundle \\(\eta\\) is called an **inverse** of \\(\xi\\), if \\(\xi \oplus \eta\\) is isomorphic to a trivial bundle.
{{% /definition %}}

{{% theorem %}}
A numerable vector bundle has a **Riemann metric**.
{{% /theorem %}}

Cf. [Numerable](#numerable)

{{% theorem %}}
A bundle has an inverse if and only if it is numerable of finite type.
{{% /theorem %}}

The real vector bundles and complex vector bundles have monoid structure and can be transformed into [Grothendieck ring](#grothendieck-ring) denoted by \\(KO(X)\\) and \\(K(X) = KU(X)\\).

Referenced: [Connection](#connection), [Covariant derivative](#covariant-derivative), [Holonomy group](#holonomy-group), [Normal bundle](#normal-bundle), [Tangent bundle](#tangent-bundle), [Bott periodicity](#bott-periodicity), [Chern class](#chern-class), [Complex line bundle over CP^1](#complex-line-bundle-over-cp-1), [Euler class](#euler-class), [Fibre bundle](#fibre-bundle), [Numerable](#numerable), [Poincaré-Hopf thereom](#poincaré-hopf-thereom), [Stiefel-Whitney class](#stiefel-whitney-class), [Elliptic fibration](#elliptic-fibration).


### Weak Hausdorff {#weak-hausdorff}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 15:48]</span></span>
A space \\(X\\) is **weak Hausdorff** if for every compact Hausdorff \\(K\\) and every continuous map \\(f:K \to X\\), the image \\(f(K)\\) is closed in \\(X\\). We denote the full subcategory of weak Hausdorff space by \\(\cat{WH}\\).

Referenced: [Category CGWH](#category-cgwh).


### Weak homotopy equivalence {#weak-homotopy-equivalence}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:41]</span></span>
\\(f\\) is called **weak homotopy equivalence** if \\(f\\) is [n-equivalence](#n-equivalence) for any \\(n \geq 0\\).

Referenced: [Weak equivalence](#weak-equivalence), [CW approximation](#cw-approximation), [Whitehead theorem](#whitehead-theorem).


### Wedge product {#wedge-product}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:42]</span></span>
We define the **wedge product** \\(\vee\\) by \\(X \vee Y = X \coprod Y / \sim\\), where \\(\sim\\) identifies \\(x\_{0} \in X\\) and \\(y\_{0} \in Y\\).

Referenced: [Smash product](#smash-product).


### Well-pointed {#well-pointed}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:15]</span></span>
A based space \\((X,x\_{0})\\) is called **well-pointed**, if the inclusion of the base point \\(x\_{0} \in X\\) is a [Cofibration](#cofibration) in the unbased sense.


### Whitehead theorem {#whitehead-theorem}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-26 Sun 16:14]</span></span>
The **Whitehead theorem** means that [Weak homotopy equivalence](#weak-homotopy-equivalence) is equivalent to homotopy equivalence for [CW complexes](#cw-complex).

{{% theorem %}}
A map between CW complexes is a weak homotopy equivalence if and only if it is a homotopy equivalence.
{{% /theorem %}}

By [Hurewicz theorem](#hurewicz-theorem), the Whitehead theorem also has an [Homology](#homology) version.

{{% theorem %}}
Let \\(f: X \to Y\\) between simply connected CW complexes. Assume
\\[f\_{\* }: H\_{n}(X) \to H\_{n}(Y)\\]
is an isomorphism for each \\(n\\). Then \\(f\\) is a homotopy equivalence.
{{% /theorem %}}


### <span class="org-todo todo TODO">TODO</span> Whitehead tower {#whitehead-tower}


## Algebraic Geometry {#algebraic-geometry}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-23 Mon 19:50]</span></span>
There are two tastes of algebraic geometry. The algebraic geometers view it as a specialized geometry, which is closed related to complex geometry (by GAGA), birational geometry (MMP for example), symplectic geometry (Gromov-Witten invariants) etc. Algebraic geometers are mainly interested in case where the base field is \\(\CC\\). Experts in other field may view algebraic geometry as useful languages, where vast properties are worked out by algebraic geometers. Therefore, Grothendieck's style of algebraic geometry provides many insights into number theory, representation theory etc. In both case, the characteristic \\(p\\) case is more interesting. Examples includes [Steinberg variety](#steinberg-variety), p-adic Hodge theory.

The following are the themes in Algebraic Geometry Salt Lake 2015 seminar <https://sites.google.com/site/2015summerinstitute/home/schedule> : analytic methods, birational geometry and classification, commutative algebra and computational algebraic geometry, Hodge theory, singularities and characteristic p methods, derived algebraic geometry, derived categories, geometric representation theory, Gromov-Witten and Donaldson-Thomas theories, mirror symmetry, tropical geometry, algebraic cycles, cohomology theories, p-adic Hodge theory, rational points and Diophantine problems, topology of algebraic varieties


### <span class="org-todo todo TODO">TODO</span> Affine derived scheme {#affine-derived-scheme}


### Affine grassmannian {#affine-grassmannian}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:31]</span></span>
Let \\(G\\) affine linear [Algebraic group](#algebraic-group). We define the functor
\\[{\rm Gr}\_{G}( R) = G(R((t)))/G(R[|t|])\\]
called **affine grassmannian**. We write \\(\mathcal{O} = k[|t|]\\) and \\(K = k((t))\\).

Cf. [Loop space](#loop-space), [Arc space](#arc-space).

We have Cartan decomposition for \\(G(K)\\).

{{% theorem %}}
\\[G(K) = \coprod\_{\mu \in X\_{\*}(T)^{+}} G(\mathcal{O})t^{\mu} G(\mathcal{O})\\]
{{% /theorem %}}

The above theorem gives a stratification of \\({\rm Gr}\_{G}\\)

{{% corollary %}}
\\[{\rm Gr}\_{G} = \coprod\_{\mu \in X\_{\*}(T)^{+}}G(\mathcal{O})t^{\mu} G(\mathcal{O})/ G(\mathcal{O}) = \coprod\_{\mu} {\rm Gr}\_{\mu}\\]
{{% /corollary %}}

And we have following inclusion properties

{{% proposition %}}
For \\(G\\) reductive, we have
\\[\overline{{\rm Gr}^{\lambda}} = \cup\_{\mu \leq \lambda} {\rm Gr}^{\mu}\\]
{{% /proposition %}}


### Affine toric variety {#affine-toric-variety}



{{% definition %}}
An **affine toric variety** is an irreducible affine variety \\(V\\) containing a [Torus](#torus) \\(T\_{N} \cong (\CC^{\* })^{n}\\) as a Zariski open subset such that the action of \\(T\_{N}\\) on itself extends to an action on \\(V\\).
{{% /definition %}}

There are several ways of constructing toric varieties. First, consider a finite subset \\(\mathscr{A} = \\{\chi^{1}, \cdots, \chi^{l}\\} \subset \ZZ^{n}\\) a lattice equivalent to the character of a torus \\((\CC^{\* })^{n}\\). Then we may consider a map \\(\Phi\_{\mathscr{A}}(t) = (\chi^{1}(t), \cdots, \chi^{l}(t)), T\_{N} \to \CC^{s}\\). The Zariski closure of the image is a toric variety denoted by \\(Y\_{\mathscr{A}}\\). The ideal of the affine toric variety is a [Toric ideal](#toric-ideal). Detailed construction can see [<span id="8a8485591c9ae40ab7e9a4d136fca3d2"><a href="#cox2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">cox2011</a></span>] p.14-15.

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

We consider the relation between sublattice variety and original variety. ([<span id="8a8485591c9ae40ab7e9a4d136fca3d2"><a href="#cox2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">cox2011</a></span>] Proposition 1.3.18) For \\(N'\\) have finite index in \\(N\\) a sublattice and quotient \\(G = N/N'\\) and \\(\sigma \subset N\_{\RR}' = N\_{\RR}\\) be a [Strongly convex](#strongly-convex) [Rational](#rational) [Polyhedral cone](#polyhedral-cone). Then we have

1.  There are natural isomorphisms
    \\[G \cong \Hom\_{\ZZ}(M'/M, \CC^{\* }) = \ker(T\_{N'} \to T\_{N})\\]
2.  \\(G\\) acts on \\(\CC[\sigma^{\vee} \cap M']\\) and
    \\[\CC[\sigma^{\vee} \cap M']^{G} = \CC[\sigma^{\vee} \cap M]\\]
3.  We have bijection
    \\[U\_{\sigma, N'}/G \cong U\_{\sigma, N}\\]

That is the original variety is [Geometric quotient](#geometric-quotient) of the sublattice varieties.

Referenced: [Toric](#toric), [Face](#face), [Pointed](#pointed), [Saturated](#saturated), [Toric variety](#toric-variety).


### Algebraic group {#algebraic-group}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-07 Tue 20:45]</span></span>
An **algebraic group** \\(G\\) over a field \\(k\\) is a [Group scheme](#group-scheme) \\(G/k\\) which is separated and smooth.

Referenced: [Representation category](#representation-category), [Affine grassmannian](#affine-grassmannian), [Radical](#radical), [Unipotent](#unipotent), [Unipotent radical](#unipotent-radical), [Semisimple](#semisimple), [Reductive](#reductive), [Parabolic](#parabolic), [Isogeny](#isogeny), [Langlands dual pair](#langlands-dual-pair).


#### Radical {#radical}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 08:52]</span></span>
[<span id="868cb56e509be613430cca58b1ead9f3"><a href="#milne2017" title="Milne, Algebraic {{Groups}}: {{The Theory}} of {{Group Schemes}} of {{Finite Type}} over a {{Field}}, {Cambridge University Press} (2017).">milne2017</a></span>] p.135

Let \\(G\\) be a connected [Algebraic group](#algebraic-group) over \\(k\\). \\(G\\) contains a largest connected solvable normal subgroup called the **radical**, \\(R(G)\\) of \\(G\\).

Referenced: [Unipotent radical](#unipotent-radical), [Semisimple](#semisimple).


#### Unipotent {#unipotent}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 09:01]</span></span>
[<span id="868cb56e509be613430cca58b1ead9f3"><a href="#milne2017" title="Milne, Algebraic {{Groups}}: {{The Theory}} of {{Group Schemes}} of {{Finite Type}} over a {{Field}}, {Cambridge University Press} (2017).">milne2017</a></span>] p.135

An [Algebraic group](#algebraic-group) \\(G\\) is said to be **unipotent** if every nonzero representation of \\(G\\) has a nonzero fixed point. Or equivalently speaking, every finite-dimensional representation \\(r: G \to \GL\_{V}\\) there is a basis such that \\(r(G) \subset \U\_{n}\\).


#### Unipotent radical {#unipotent-radical}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 09:01]</span></span>
[<span id="868cb56e509be613430cca58b1ead9f3"><a href="#milne2017" title="Milne, Algebraic {{Groups}}: {{The Theory}} of {{Group Schemes}} of {{Finite Type}} over a {{Field}}, {Cambridge University Press} (2017).">milne2017</a></span>] p.135

The **unipotent radical** of \\(G\\) is the largest connected normal unipotent sub-[Algebraic group](#algebraic-group) of \\(G\\), denoted by \\(R\_{u}(G)\\).

Cf. [Radical](#radical).

Referenced: [Reductive](#reductive).


#### Semisimple {#semisimple}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 08:50]</span></span>
[<span id="868cb56e509be613430cca58b1ead9f3"><a href="#milne2017" title="Milne, Algebraic {{Groups}}: {{The Theory}} of {{Group Schemes}} of {{Finite Type}} over a {{Field}}, {Cambridge University Press} (2017).">milne2017</a></span>] p.135

An [Algebraic group](#algebraic-group) is called **semisimple** if \\(R(G\_{k^{a}})\\) is trivial, where \\(k^{a}\\) is the algebraic closure of \\(k\\).

Cf. [Radical.](#radical)


#### Reductive {#reductive}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 08:49]</span></span>
[<span id="868cb56e509be613430cca58b1ead9f3"><a href="#milne2017" title="Milne, Algebraic {{Groups}}: {{The Theory}} of {{Group Schemes}} of {{Finite Type}} over a {{Field}}, {Cambridge University Press} (2017).">milne2017</a></span>] p.135

An [Algebraic group](#algebraic-group) is called **reductive** if \\(R\_{u}(G\_{k^{a}})\\) is trivial, where \\(k^{a}\\) is the algebraic closure of \\(k\\).

Cf. [Unipotent radical](#unipotent-radical).

Referenced: [Positive root](#positive-root).


#### Parabolic {#parabolic}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:50]</span></span>
A smooth subgroup \\(P \subset G\\) is **parabolic** if \\(G/P\\) complete as algebraic variety.

{{% proposition %}}
For \\(k\\) algebraic closed, a smooth connected algebraic group \\(B \subset G\\) is minimal among parabolics \\(P\\) is equivalent to \\(B\\) solvable parabolic.
{{% /proposition %}}

Cf. [Algebraic group](#algebraic-group).

Referenced: [Borel](#borel).


#### Borel {#borel}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:51]</span></span>
A algebraic subgroup \\(B\\) is called **Borel** if it is [Parabolic](#parabolic), smooth, connected and solvable.

Referenced: [Positive root](#positive-root).


### <span class="org-todo todo TODO">TODO</span> Anti-self-dual connection {#anti-self-dual-connection}


### Arc space {#arc-space}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:26]</span></span>
We define the **arc space** to be functor \\(Y[|t|]\\) such that \\(Y[|t|\]\( R) = Y(R[|t|])\\).

Cf. [Loop space](#loop-space).

{{% proposition %}}
Arc spaces and \\(Y[k[t]/t^{n}]\\) are schemes. Moreover, if \\(Y\\) is affine then they are also affine.
{{% /proposition %}}

Referenced: [Affine grassmannian](#affine-grassmannian), [Loop space](#loop-space).


### Auslander-Buchsbaum formula {#auslander-buchsbaum-formula}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:32]</span></span>
Let \\(A\\) be a regular ring, then we have
\\[\dimh(M) + \depth(M) = \dim (A)\\]
Cf. [Homological dimension](#homological-dimension), [Depth](#depth).


### Calabi-Yau variety {#calabi-yau-variety}



Referenced: [Donaldson-Thomas theory](#donaldson-thomas-theory), [Kähler manifold with holomorphic symplectic structure](#kähler-manifold-with-holomorphic-symplectic-structure).


### Castelnuovo theorem {#castelnuovo-theorem}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:32]</span></span>
The **Castelnuovo theorem** classified the mimimal surfaces.

{{% theorem %}}
Two birational [minimal models](#minimal-model) are isomorphic unless they are both birational to a ruled surface \\(C \times \CC P^{1}\\).
{{% /theorem %}}


### Categorical quotient {#categorical-quotient}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-07 Tue 20:59]</span></span>
Given an action \\(\sigma\\) of \\(G/S\\) on \\(X/S\\), a pair \\((Y, \phi: X \to Y)\\)  is called a **categorical quotient** if we have diagram

![](/img/2021-09-07_21-01-38_screenshot.png)
commutes and universal property that for any \\((Z, \psi)\\) satisfying the above diagram, there exists a unique morphism \\(\chi: Y \to Z\\) such that \\(\psi = \chi \circ \phi\\).

A categorical quotient is called **universal** if it is stable under base change, and is called **uniform** if it is stable under flat base change.

Referenced: [Geometric quotient](#geometric-quotient).


### Category of modules {#category-of-modules}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-07 Sun 15:21]</span></span>
Let \\(T\\) be a [Topos](#topos) and let \\(\Lambda\\) be a ring in \\(T\\). Denote by \\(\cat{Mod}\_{\Lambda}\\) the category of \\(\Lambda\\)-modules in \\(T\\).

{{% theorem %}}
The category \\(\cat{Mod}\_{\Lambda}\\) is an abelian category with enough injectives.
{{% /theorem %}}

Then we have functor
\\[\Gamma(T, -): \cat{Mod}\_{\Lambda} \to \cat{Ab}\\]
obtained by
\\[F \to \Hom\_{\cat{Mod}\_{\Lambda}}(\Lambda, F)\\]
This is a left exact functor, and we denote the resulting right derived functor by \\(H^{i}(T, -)\\), called **cohomology functor**.

Cf. [Cohomology](#cohomology).


### Character (of a torus) {#character--of-a-torus}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 19:50]</span></span>
A **character** of a [Torus](#torus) is a group homomorphism \\(\chi: T \to \CC^{\* }\\).


### <span class="org-todo todo TODO">TODO</span> Coarse moduli space {#coarse-moduli-space}


### <span class="org-todo todo TODO">TODO</span> Cohen strcuture theorem {#cohen-strcuture-theorem}



{{% corollary %}}
Let \\(X\\) be a locally Noetherian scheme over a field \\(k\\), having dimension \\(n\\) at a smooth point \\(x\\). Then \\(\hat{\OO}\_{X,x} \cong k(x)[ [x\_{1}, \cdots, x\_{n}]]\\).
{{% /corollary %}}


### Deformation functor {#deformation-functor}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-19 Sun 20:24]</span></span>
A [Predeformation functor](#predeformation-functor) is called a **deformation functor** if it satisfies (1-2) in [Schlessinger's theorem](#schlessinger-s-theorem).


### Depth {#depth}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:34]</span></span>
The maximal length of an \\(M\\)-[Regular sequence](#regular-sequence) is called the **depth** of \\(M\\).

Referenced: [Auslander-Buchsbaum formula](#auslander-buchsbaum-formula).


### <span class="org-todo todo TODO">TODO</span> Derived stack {#derived-stack}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:06]</span></span>
Examples: Betti stack, de Rham stack


### Determinant bundle {#determinant-bundle}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:50]</span></span>
If \\(E\\) is locally free of rank \\(s\\), then the **determinant bundle** \\(\det(E)\\) is by definition the line bundle \\(\wedge^{s}(E)\\). Let \\(E\\) be arbitrary coherent sheaf. Then we consider a finite locally free resolution
\\[0 \to E\_{n} \to \cdots \to E\_{0} \to E \to 0\\]
And define \\(\det(E) = \otimes \det(E\_{i})^{(-1)^{i}}\\).

If \\(\dim(E) \leq \dim(X) - 2\\), then we have that \\(\det(E) \cong \OO\_{X}\\).


### Different characters may give same toric variety {#different-characters-may-give-same-toric-variety}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:26]</span></span>
Exercise 1.1.6 in [<span id="8a8485591c9ae40ab7e9a4d136fca3d2"><a href="#cox2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">cox2011</a></span>]. We consider two map
\\[\Phi\_{1}(s,t) = (s^{2}, st, st^{3}), \quad \Phi\_{2}(s,t) = (s^{3}, st, t^{3})\\]
We can show that \\(\Phi\_{1}\\) and \\(\Phi\_{2}\\) gives same affine toric variety. However \\(\Phi\_{2}\\) is surjective and \\(\Phi\_{1}\\) is not.


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

The expected dimension is given by \\(\dim(\Ext\_{0}^{1}(E, E)) - \dim(\Ext\_{0}^{2}(E,E))\\), where \\(\Ext\_{0}\\) denote the trace free subspace. So we have that \\(\virdim I\_{\chi}(X, \beta) = \chi(E, E) - \chi(\OO) = -K\_{X} \cdot \beta\\). In [Gromov-Witten theory](#gromov-witten-theory), we also have the fundamental class of dimension equal to \\(-K\_{X} \cdot \beta\\). So if \\(X\\) is [Calabi-Yau variety](#calabi-yau-variety), we have \\(\virdim I\_{\chi}(X, \beta) = 0\\).

We don't have evaluation map in Donaldson-Thomas theory, so we consider
\\[\tilde{J} \to \hilb(X) \times X\\]
for the purpose of integration. Given \\(\alpha \in H^{\*}(X)\\), we can define an operator
\\[\sigma\_{0}(\alpha): \pi\_{\hilb \*}(- \ch\_{2}(\tilde{J}) \cup \pi\_{X}^{\*}(\alpha) \cap \pi\_{\hilb}^{\*}(-)), H\_{\*}(\hilb(X)) \to H\_{\*}(\hilb(X))\\]
Then the **Donaldson-Thomas invariants** are defined by

\begin{align}\langle \alpha\_{1}, \cdots, \alpha\_{n} \rangle^{DT}\_{\beta, m} &= \deg \prod\_{k} \sigma\_{0}(\alpha\_{k})[I\_{\chi}(X, \beta)]^{vir} \\\\\\  &= \int\_{ [I\_{\chi}(X, \beta)]^{vir}} \prod\_{k} \sigma\_{0}(\alpha\_{k}) \\\\\\  &= \int\_{ [I\_{\chi}(X, \beta)]^{vir}} \prod\_{k} \pi\_{\hilb \*}(- \ch\_{2}(\tilde{J}) \cup \pi\_{X}^{\*}(\alpha\_{k}) \cap \pi^{\*} \beta)\end{align}

Here note \\(-\ch\_{2}(I\_{Z}) = \beta\\) is represented by cycle class \\(Z \subset X\\).

There may be some mistakes in definition, because I suppose that the second line is not well-defined and the \\(\beta\\) in the last line is unnatural. However, I don't know the correct algebraic definition of Donaldson-Thomas theory yet. So I still follow the definition in [GW/DT Theory](https://www.bilibili.com/video/BV1Gi4y1T7ed) Lecture 11.


### Dual sheaf {#dual-sheaf}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:39]</span></span>
Let \\(E\\) be a coherent sheaf of codimension \\(c\\). The **dual sheaf** is defined as \\(E^{D} = \sext^{c}\_{X} (E, \omega\_{X})\\).

Referenced: [Reflexive](#reflexive).


### <span class="org-todo todo TODO">TODO</span> Dykin diagram {#dykin-diagram}


### Enumerative geometry {#enumerative-geometry}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-31 Tue 08:52]</span></span>
There are several aspects of enumerative geometry, beyond the numbers.

-   counting curves and sheaves (Gromov-Witten theory, Donaldson-Thomas and related theories)
-   gauge theory enumerative geometry (3d gauge theories and Coulomb branches, mirror symmetry, 4d gauge theories, and Vafa-Witten invariants, etc)
-   applications of enumerative geometry to categorification and low-dimensional topology
-   Hall algebras and their refined versions (cohomological, K-theoretic, derived categories)
-   Enumerative geometry of Nakajima quiver variety and the representation of quantum groups (symplectic resolution, etc)

Referenced: [Donaldson-Thomas theory](#donaldson-thomas-theory), [Gromov-Witten theory](#gromov-witten-theory).


#### MNOP conjecture {#mnop-conjecture}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-28 Tue 20:20]</span></span>
The MNOP conjecture is proposed in [<span id="71c689e646b740e15274e4c45df483c9"><a href="#maulik2006" title="Maulik, Nekrasov, Okounkov \&amp; Pandharipande, Gromov\textendash{{Witten}} Theory and {{Donaldson}}\textendash{{Thomas}} Theory, {{I}}, {Compositio Mathematica}, v(05), 1263--1285 (2006).">maulik2006</a></span>] (primary case), [<span id="a94d6b5af3fa210c91d9309d3da103af"><a href="#maulik2006a" title="Maulik, Nekrasov, Okounkov \&amp; Pandharipande, Gromov\textendash{{Witten}} Theory and {{Donaldson}}\textendash{{Thomas}} Theory, {{II}}, {Compositio Mathematica}, v(05), 1286--1304 (2006).">maulik2006a</a></span>] (descent case). The Gromov-Witten/Donaldson-Thomas correspondence is proved in toric case [<span id="e25e310ddc34f4e55392b368230bb1bf"><a href="#maulik2011" title="Maulik, Oblomkov, Okounkov \&amp; Pandharipande, Gromov-{{Witten}}/{{Donaldson-Thomas}} Correspondence for Toric 3-Folds, {Inventiones mathematicae}, v(2), 435--479 (2011).">maulik2011</a></span>].

The Pandharipande-Thomas (PT) invariants is introduced in [<span id="431caa59e2d75afb6b38719ad8dca5d9"><a href="#pandharipande2009" title="Pandharipande \&amp; Thomas, Curve Counting via Stable Pairs in the Derived Category, {Inventiones mathematicae}, v(2), 407--447 (2009).">pandharipande2009</a></span>], whose moduli space behaves better than the Donaldson-Thomas invariants. And correspondence between DT and PT is proved in [<span id="f9133d12da33e9b2ae5ee8e0f8d3fa3a"><a href="#toda2010" title="Toda, Curve Counting Theories via Stable Objects {{I}}. {{DT}}/{{PT}} Correspondence, {Journal of the American Mathematical Society}, v(4), 1119--1157 (2010).">toda2010</a></span>] and therefore the problem of GW/DT correspondence is reduced to GW/PT correspondence, where the latter is easier to handle.

The toric case of GW/PT correspondence is given in [<span id="909250c4d905735b782534d99f6095f5"><a href="#pandharipande2014" title="Pandharipande \&amp; Pixton, Gromov\textendash{{Witten}}/Pairs Descendent Correspondence for Toric 3\textendash Folds, {Geometry \&amp; Topology}, v(5), 2747--2821 (2014).">pandharipande2014</a></span>] and the local complete intersection in product of projective space case is established in [<span id="88221b9c6d4636326d6b0764fc915f73"><a href="#pandharipande2017" title="Pandharipande \&amp; Pixton, Gromov-{{Witten}}/{{Pairs}} Correspondence for the Quintic 3-Fold, {Journal of the American Mathematical Society}, v(2), 389--449 (2017).">pandharipande2017</a></span>]. The explicit formula of the matrix coefficient is given in [<span id="5475808075c4e5ae5aa873cba4119875"><a href="#oblomkov2020" title="Oblomkov, Okounkov \&amp; Pandharipande, {{GW}}/{{PT Descendent Correspondence}} via {{Vertex Operators}}, {Communications in Mathematical Physics}, v(3), 1321--1359 (2020).">oblomkov2020</a></span>].

Based on GW/PT correspondence, in toric variety, [Virasoro constraint](#virasoro-constraint) for stable pairs and therefore for GW theory is obtained in [<span id="b79997d2a1ead8b84a185c6680e7e9db"><a href="#moreira2020" title="Moreira, Oblomkov, Okounkov \&amp; Pandharipande, Virasoro Constraints for Stable Pairs on Toric 3-Folds, {arXiv:2008.12514 [math]}, v(), (2020).">moreira2020</a></span>]


### Étale site {#étale-site}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 21:30]</span></span>
See [Site](#site).

:ID:       e75a7770-d111-4f5e-9fb0-72a34c894b6e

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 21:32]</span></span>
See [Site](#site).


### <span class="org-todo todo TODO">TODO</span> Exact sequence about extensions {#exact-sequence-about-extensions}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 21:29]</span></span>
See [<span id="7cd3e01b28c2ede526fee96d60981f02"><a href="#sernesi2006" title="Sernesi, Deformations of {{Algebraic Schemes}}, {Springer Berlin Heidelberg} (2006).">sernesi2006</a></span>] Proposition 1.1.5, Proposition 1.1.7, and Corollary 1.1.8.

{{% remark %}}
The proof in my mind is straightforward but a little tricky when manipulate the objects, since sometimes we need to consider the \\(R\\)-module structure and sometimes as \\(A\\)-algebra.
{{% /remark %}}

Referenced: [Extension](#extension).


### Ex\_A(R,I) {#ex-a--r-i}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 21:15]</span></span>
See [<span id="7cd3e01b28c2ede526fee96d60981f02"><a href="#sernesi2006" title="Sernesi, Deformations of {{Algebraic Schemes}}, {Springer Berlin Heidelberg} (2006).">sernesi2006</a></span>] p.12.

We now consider all isomorphism class of \\(A\\)-[Extensions](#extension) of \\(R\\) by \\(I\\), called \\(\ex\_{A}(R,I)\\). We want to show that \\(\ex\_{A}(R, I)\\) is an \\(R\\)-module. We first construct the **pullback** and **pushout** for extensions. We define the pullback, denoted by \\(f^{\* }(R', \phi)\\) by following diagram:

![](/img/2021-09-15_21-22-39_screenshot.png)
And define the pushout by the other, denoted by \\(\lambda\_{\*}(R', \phi)\\):

![](/img/2021-09-15_21-23-05_screenshot.png)
Where
\\[R' \coprod\_{I} J = \frac{R' \tilde{\oplus} J}{\\{(- \alpha(i), \lambda(i)), i \in I\\}}\\]

Now we are ready to define the \\(R\\)-module structure on \\(\ex\_{A}(R, I)\\). If \\(r \in R\\), we define \\(r[R', \phi] = [r\_{\* }(R', \phi)]\\) where \\(r: I \to I\\) is multiplication by \\(r\\). And for some, we consider \\(R' \times\_{R} R''\\) as the extension of \\(R\\) by \\(I \oplus I\\). And consider the pushout of the function \\(\delta: I \oplus I \to I\\), such that \\(\delta(i \oplus j) = i + j\\).

By above construction, \\(\ex\_{A}(R, -)\\) is a covariant functor from \\(R\\)-modules to \\(R\\)-modules.

Referenced: [Extension](#extension), [First cotangent module](#first-cotangent-module).


### Extension {#extension}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 20:28]</span></span>
See [<span id="7cd3e01b28c2ede526fee96d60981f02"><a href="#sernesi2006" title="Sernesi, Deformations of {{Algebraic Schemes}}, {Springer Berlin Heidelberg} (2006).">sernesi2006</a></span>] p.9.

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

Examples: dual number, small extension. See [<span id="7cd3e01b28c2ede526fee96d60981f02"><a href="#sernesi2006" title="Sernesi, Deformations of {{Algebraic Schemes}}, {Springer Berlin Heidelberg} (2006).">sernesi2006</a></span>] p.11.

The extension of algebras can be extended to extension of schemes. An **extension** of \\(X/S\\) is a closed immersion \\(X \subset X'\\), where \\(X'\\) is an \\(S\\)-scheme, defined by a sheaf of ideals \\(\mathscr{I} \subset \mathscr{O}\_{X'}\\) such that \\(\mathscr{I}^{2} = 0\\). The **isomorphism**, **homomorphism**, **triviality**, and \\(\ex(X/S, \mathscr{I})\\) is similar to the algebra case. For details, see [<span id="7cd3e01b28c2ede526fee96d60981f02"><a href="#sernesi2006" title="Sernesi, Deformations of {{Algebraic Schemes}}, {Springer Berlin Heidelberg} (2006).">sernesi2006</a></span>] p.15. (Cf. [Ex\_A(R,I)](#ex-a--r-i) and [Exact sequence about extensions](#exact-sequence-about-extensions))

In particular, we have following theorem relating the deformation to the \\(\Ext\\) groups.

{{% theorem %}}
Let \\(X \to S\\) be a morphism of finite type of schemes and \\(\mathscr{I}\\) a coherent locally free sheaf on \\(X\\). Suppose that \\(X\\) reduced and \\(S\\)-smooth on a dense open subset. Then there is a cononical equivalence
\\[\ex(X/S, \mathscr{I}) = \Ext^{1}\_{\mathscr{O}\_{X}}(\Omega\_{X/S}^{1}, \mathscr{I})\\]
which maps the extension
\\[\mathscr{E}: 0 \to \mathscr{I} \to \OO\_{X'} \to \OO\_{X} \to 0\\]
to
\\[c\_{\mathscr{E}}: 0 \to \mathscr{I} \to (\Omega^{1}\_{X'/S})|\_{X} \to \Omega^{1}\_{X/S} \to 0\\]
{{% /theorem %}}

Referenced: [Ex\_A(R,I)](#ex-a--r-i), [Versal extension](#versal-extension).


### <span class="org-todo todo TODO">TODO</span> Fine moduli space {#fine-moduli-space}


### First cotangent module {#first-cotangent-module}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 21:33]</span></span>
See [<span id="7cd3e01b28c2ede526fee96d60981f02"><a href="#sernesi2006" title="Sernesi, Deformations of {{Algebraic Schemes}}, {Springer Berlin Heidelberg} (2006).">sernesi2006</a></span>] p.14.

The \\(R\\)-module \\(\ex\_{A}(R,R)\\) is called the **first cotangent module** of \\(R\\) over \\(A\\), and is denoted by \\(T\_{R/A}^{1}\\). We omit \\(A\\) if \\(A = k\\). The **first cotagent sheaf** is obtained by gluing the first cotangent modules.

Cf. [Ex\_A(R,I)](#ex-a--r-i).


### Flat {#flat}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-19 Sun 20:23]</span></span>
A \\(R\\)-module \\(M\\) is called **flat** if tensoring with \\(M\\) is an exact functor.


### Fppf site {#fppf-site}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 21:32]</span></span>
See [Site](#site).


### Framed moduli space {#framed-moduli-space}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-19 Sun 19:28]</span></span>
See [<span id="24e67c8afe5163064e4018cb5a5cbd8a"><a href="#nakajima1999" title="Nakajima, Lectures on {{Hilbert}} Schemes of Points on Surfaces, {American Mathematical Society} (1999).">nakajima1999</a></span>] p.17.

We define \\(\mathscr{M}(r,n)\\), the **framed moduli space** of torsion free [Sheaves](#sheaf) on \\(\PP^{2}\\) with rank (r) and \\(c\_{2} = n\\). That is the isomorphism class of pairs \\((E, \Phi)\\) on \\(\PP^{2}\\) with \\(\rk(E) = n\\) \\(c\_{2}(E) = n\\) which is locally free in a neighborhood of \\(l\_{\infty}\\) such that \\(\Phi: E|\_{l\_{\infty}} \ito \mathscr{O}\_{l\_{\infty}}^{\oplus r}\\). The latter isomorphism is called **framing at infinity**.

We have following simple characterization of framed moduli space.

{{% theorem %}}
There exists a bijection between \\(\mathscr{M}(r,n)\\) and pairs \\((B\_{1}, B\_{2}, i, j)\\) such that \\([B\_{1}, B\_{2}] + ij = 0\\), and stability condition there exists no proper subspace \\(S \subsetneq \CC^{n}\\) such that \\(B\_{\alpha}(S) \subset S\\) and \\(\im i \subset S\\) modulo the action of \\(\GL\_{n}(\CC)\\). Here \\(B\_{1}, B\_{2} \in \End(\CC^{n})\\), \\(i \in \Hom(\CC^{r}, \CC^{n})\\) and \\(j \in \Hom(\CC^{n}, \CC^{r})\\) with the action
\\[g \cdot (B\_{1}, B\_{2}, i, j) = (gB\_{1}g^{-1}, gB\_{2}g^{-1}, gi, jg^{-1})\\]
{{% /theorem %}}

Cf. [Hilb(A^2,n)](#hilb--a-2-n).

There is a interesting lemma with basic techniques in linear algebra.

{{% lemma %}}
When \\(r = 1\\) and \\(B\_{1}, B\_{2}, i, j\\) same as above theorem, for \\(ij + [B\_{1}, B\_{2}] = 0\\), we have that \\(ji = 0\\).
{{% /lemma %}}

See [<span id="24e67c8afe5163064e4018cb5a5cbd8a"><a href="#nakajima1999" title="Nakajima, Lectures on {{Hilbert}} Schemes of Points on Surfaces, {American Mathematical Society} (1999).">nakajima1999</a></span>] p.26. We have \\(S^{n}(\CC^{2}) \cong \\{(B\_{1}, B\_{2}, i, j) \mid [B\_{1}, B\_{2}] + i j = 0\\} // \GL\_{n}(\CC)\\), where \\(//\\) denote the algebro-geometric quotient.

Cf. [Geometric quotient](#geometric-quotient).


### Generalized Serre's condition {#generalized-serre-s-condition}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:37]</span></span>
We define the **generalized Serre's condition** \\(S\_{k,c}\\) as
\\[\depth(E\_{x} \geq \min \\{k, \dim(\OO\_{X,x}) - c\\}) \text{ for all } x \in \supp(E)\\]


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

Referenced: [Affine toric variety](#affine-toric-variety), [Framed moduli space](#framed-moduli-space).


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

Referenced: [Donaldson-Thomas theory](#donaldson-thomas-theory), [Linear axiom](#linear-axiom), [Effectivity axiom](#effectivity-axiom), [Degree axiom](#degree-axiom), [Equivariant axiom](#equivariant-axiom), [Fundamental class axiom](#fundamental-class-axiom), [Divisor axiom](#divisor-axiom), [Point mapping axiom](#point-mapping-axiom), [Splitting axiom](#splitting-axiom), [Reduction axiom](#reduction-axiom), [Deformation axiom](#deformation-axiom), [Kontsevich recursion formula](#kontsevich-recursion-formula).


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


### Grothendieck topology {#grothendieck-topology}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 21:20]</span></span>
Let \\(C\\) be a category. A **Grothendieck topology** on \\(C\\) consists of a set \\(\cat{Cov}(X)\\) of collections of moprhisms \\(\\{X\_{i} \to X\\}\_{i \in I}\\) for every object \\(X \in C\\) such that the following hold:

1.  If \\(V \to X\\) is an isomorphism, then \\(\\{V \to X\\} \in \cat{Cov}(X)\\).
2.  If \\(\\{X\_{i} \to X\\}\_{i \in I} \in \cat{Cov}(X)\\) and \\(Y \to X\\) is any arrow in \\(C\\), then the fiber products \\(X\_{i} \times\_{X} Y\\) exist in \\(C\\) and the collection
    \\[\\{X\_{i} \times\_{X} Y \to Y\\}\_{i \in I}\\]
    is in \\(\cat{Cov}(Y)\\).
3.  If \\(\\{X\_{i} \to X\\}\_{i \in I} \in \cat{Cov}(X)\\) and if for every \\(i \in I\\) we are given \\(\\{V\_{ij} \to X\_{i}\\}\_{j \in J\_{i}} \in \cat{Cov}(X)\\), then the collection of compositions
    \\[\\{V\_{ij} \to X\_{i} \to X\\}\_{i \in I, j \in J\_{i}}\\]
    is in \\(\cat{Cov}(X)\\).

The Grothendieck topology is also called a **pre-topology**.

Referenced: [Site](#site).


### Group scheme {#group-scheme}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-07 Tue 20:42]</span></span>
A **group scheme** \\(G/S\\) is a morphism \\(\pi: G \to S\\) of schemes with \\(S\\)-morphism multiplication \\(\mu: G \times\_{S} G \to G\\), inverse \\(\beta: G \to G\\) identity \\(e: S \to G\\) satisfying associativity, law of inverse and law of identity.

A group scheme \\(G\\) action on a scheme \\(X/S\\) is given by a morphism \\(\sigma: G \times\_{S} X \to X\\) with associativity property and identity.

Let \\(f: T \to X\\) be a \\(T\\)-valued point. We have morphism \\(\phi\_{f} = \sigma \circ (1\_{G} \times f): G \times\_{S} T \to X \times\_{S} T\\). The image of \\(\phi\_{f}\\) is called the **orbit** of \\(f\\) and denoted by \\(O(f)\\). The fibre product \\(S(f)\\) is called **stabilizer** of \\(f\\). The orbit and stabilizer is the algebraic version of orbit and stabilizer in action on topological spaces.

{{< figure src="/img/2021-09-07_20-58-55_screenshot.png" >}}

Referenced: [Criterion for category being representation category](#criterion-for-category-being-representation-category), [Reconstruction theorem](#reconstruction-theorem), [Algebraic group](#algebraic-group).


### Hilb(A^2,n) {#hilb--a-2-n}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-16 Thu 20:35]</span></span>
See [<span id="24e67c8afe5163064e4018cb5a5cbd8a"><a href="#nakajima1999" title="Nakajima, Lectures on {{Hilbert}} Schemes of Points on Surfaces, {American Mathematical Society} (1999).">nakajima1999</a></span>], Theorem 1.9.

We have a specific characterization of \\(\hilb(A^{2}, n)\\). Let
\\[\tilde{H} = \\{(B\_{1}, B\_{2}, i) \mid [B\_{1}, B\_{2}] = 0 \text{ and stable}\\}\\]
The triple \\((B\_{1}, B\_{2}, i)\\) is called stable if there exists no proper subspace \\(S \subsetneq k^{n}\\) such that \\(B\_{\alpha}(S) \subset S\\), \\(\alpha = 0,1\\) and \\(\im i \subset S\\). \\(B\_{\alpha} \in \End(k^{n}) \\) and \\(i \in \Hom(k, k^{n})\\). We have a natural \\(\GL\_{n}\\) action on \\(\tilde{H}\\) defined by \\((B\_{1}, B\_{2}, i) \to (gB\_{1}g^{-1}, gB\_{2}g^{-1}, gi)\\). And by quotient, we define \\(H = \tilde{H}/ \GL\_{n}\\). And we have that \\(H \cong \hilb(\mathbb{A}^{2},n)\\).

Cf. [Hilbert scheme](#hilbert-scheme).

The manifold \\(\hilb(\mathbb{A}^{2}, n)\\) admits a hyper-Kähler metric.

Referenced: [Framed moduli space](#framed-moduli-space).


### Hilbert-Chow morphism {#hilbert-chow-morphism}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-16 Thu 20:25]</span></span>
For [Hilbert scheme](#hilbert-scheme) of points, we have a well define map
\\[\pi:X^{ [n]}\_{red} \to S^{n}X\\]
by \\(\pi(Z) = \sum\_{x \in X}l(Z\_{x})[x]\\), here \\(l\\) denote the length.

Referenced: [Smoothness of Hilbert scheme](#smoothness-of-hilbert-scheme).


### Hilbert scheme {#hilbert-scheme}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-29 Sun 15:24]</span></span>
We fix a class \\(\beta \in H\_{2}(X, \ZZ)\\) and fix an integer \\(\chi \in \ZZ\\).

{{% definition %}}
The **Hilbert scheme** \\({\rm Hilb}\_{\chi}(X, \beta)\\) parametrizes \\(1\\) dimensional subscheme \\(Z \subset X\\) whose irreducible components are at most \\(1\\)-dimension with numerical invariants \\(\beta = [Z] \in H\_{2}(X, \ZZ)\\) and \\(\chi(\mathscr{O}\_{Z}) = \chi\\).
{{% /definition %}}

In [<span id="24e67c8afe5163064e4018cb5a5cbd8a"><a href="#nakajima1999" title="Nakajima, Lectures on {{Hilbert}} Schemes of Points on Surfaces, {American Mathematical Society} (1999).">nakajima1999</a></span>], there is another notation of Hilbert schemes, where in \\(\hilb(X, p)\\), the \\(p\\) denote the Hilbert polynomial. And we write \\(X^{ [n]}\\) for \\(\hilb(X, n)\\) for Hilbert scheme of points.

Referenced: [Donaldson-Thomas theory](#donaldson-thomas-theory), [Hilb(A^2,n)](#hilb--a-2-n), [Hilbert-Chow morphism](#hilbert-chow-morphism), [Simple resolution](#simple-resolution), [Smoothness of Hilbert scheme](#smoothness-of-hilbert-scheme), [Symplectic structure of Hilbert scheme](#symplectic-structure-of-hilbert-scheme).


### Homological dimension {#homological-dimension}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:29]</span></span>
Let \\(M\\) be a module of a local ring \\(A\\). The **homological dimension** denoted by \\(\dimh(M)\\) is defined as the minimal length of a projective resolution of \\(M\\). It is also the length of free resolution of \\(M\\).

Referenced: [Auslander-Buchsbaum formula](#auslander-buchsbaum-formula).


### Hull {#hull}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-19 Sun 20:23]</span></span>
Let \\(F\\) be a [Predeformation functor](#predeformation-functor) and \\(\hat{F}\\) its completeion. We say a pair \\((R, \eta)\\) with \\(R\\) a [Noetherian](#noetherian) [Complete](#complete) [Local ring](#local-ring), and \\(\eta \in \hat{F}( R)\\), is a **hull** for \\(F\\) if the induced map \\(\bar{h}\_{R} \to F\\) is smooth, and induces a bijection \\(T\_{\bar{h}\_{R}} \ito T\_{F}\\) on tangent spaces.

Referenced: [Schlessinger's theorem](#schlessinger-s-theorem).


### <span class="org-todo todo TODO">TODO</span> Hyper-Kähler quotient {#hyper-kähler-quotient}


### Ind-scheme {#ind-scheme}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:23]</span></span>
An **ind-scheme** is object in \\(\cat{Fun}(\cat{k-algebra}, \cat{Set})\\) which can be written as
\\[X = \varinjlim\_{I} X\_{i}\\]
such that \\(I\\) is a direct diagram, \\(X\_{i}\\) is a scheme, all maps \\(X\_{i} \to X\_{j}\\) are closed embedding. We call **ind-affine**, **ind-projective**, **ind-finite type** if all \\(X\_{i}\\) are affine, projective, finite type.

Referenced: [Loop space](#loop-space).


### Isogeny {#isogeny}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:46]</span></span>
An **isogeny** is a surjective homomorphism between smooth connected [Algebraic groups](#algebraic-group) \\(\phi: G \to G'\\) with finite kernel \\(K\\). The **degree** of \\(\phi\\) is given by \\(\abs{K}\\).

See also [Isogeny](#isogeny).

Referenced: [Degree](#degree).


### <span class="org-todo todo TODO">TODO</span> Jacobian criterion {#jacobian-criterion}


### <span class="org-todo todo TODO">TODO</span> K3 surfaces {#k3-surfaces}



Referenced: [Intersection forms](#intersection-forms).


### Kähler manifold with holomorphic symplectic structure {#kähler-manifold-with-holomorphic-symplectic-structure}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-16 Thu 20:50]</span></span>
See [<span id="24e67c8afe5163064e4018cb5a5cbd8a"><a href="#nakajima1999" title="Nakajima, Lectures on {{Hilbert}} Schemes of Points on Surfaces, {American Mathematical Society} (1999).">nakajima1999</a></span>], Proposition 1.19.

The following proposition may be useful.

{{% proposition %}}
Let \\(X\\) be a compact Kähler manifold which admits a holomorphic symplectic structure. Then \\(X\\) has a hyper-Kähler structure.
{{% /proposition %}}

Cf. [Calabi-Yau variety](#calabi-yau-variety), [Holonomy group](#holonomy-group).


### Lattice {#lattice}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:03]</span></span>
A **lattice** is a free abelian group of finite rank.

Referenced: [Lattice ideal](#lattice-ideal), [Rational](#rational), [Affine semigroup](#affine-semigroup).


### Lattice ideal {#lattice-ideal}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:03]</span></span>
Let \\(L \subset \ZZ^{s}\\) be a sublattice. Then we call the ideal \\(I\_{L} = \langle x^{\alpha} - x^{\beta} \mid \alpha, \beta \in \NN^{s} \text{ and } \alpha - \beta \in L \rangle\\) **lattice ideal**.

Cf. [Lattice](#lattice).

Referenced: [Toric ideal](#toric-ideal).


### <span class="org-todo todo TODO">TODO</span> Linearly reductive {#linearly-reductive}


### Loop space {#loop-space}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:27]</span></span>
We define the **loop space** to be functor \\(Y((t))( R) = Y(R((t)))\\).

Cf. [Arc space](#arc-space).

{{% proposition %}}
The loop space is ind-scheme if \\(Y\\) is affine.
{{% /proposition %}}

Cf. [Ind-scheme](#ind-scheme).

Referenced: [Affine grassmannian](#affine-grassmannian).


### <span class="org-todo todo TODO">TODO</span> Luna's slice theorem {#luna-s-slice-theorem}


### <span class="org-todo todo TODO">TODO</span> McKay correspondence {#mckay-correspondence}


### <span class="org-todo todo TODO">TODO</span> Minimal model {#minimal-model}



Referenced: [Castelnuovo theorem](#castelnuovo-theorem).


### Minuscule {#minuscule}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:41]</span></span>
A coweight \\(\mu\\) is **minuscule** if
\\[\langle \alpha, \mu \rangle \leq 1\\]
for all \\(\alpha\\) positive. For minuscule \\(\mu\\), we have \\({\rm Gr}\_{\mu} = \overline{{\rm Gr}\_{\mu}} = G/P\_{\mu}\\), where \\(P\_{\mu}\\) is a partial flag.


### <span class="org-todo todo TODO">TODO</span> Moduli space of curves {#moduli-space-of-curves}



Referenced: [Canonical line bundle](#canonical-line-bundle).


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

Referenced: [Descent integral](#descent-integral).


#### Descent integral {#descent-integral}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 21:09]</span></span>
Following the terminology in [Canonical line bundle](#canonical-line-bundle). We define
\\[\langle \tau\_{1}^{k\_{1}} \cdots \tau\_{n}^{k\_{n}} \rangle\_{g,n} = \int\_{\bar{M}\_{g,n}} \psi\_{1}^{k\_{1}} \cdots \psi\_{n}^{k\_{n}}\\]
Here, we must make sure \\(\sum k\_{i} = 3g - 3 + n\\) and \\(2g - 2 + n \leq 0\\). Or by simplify notation, we make \\(n = \sum\_{k\_{i}} - 3g + 3\\). These integrals are called **descent integral**.

Referenced: [Witten's Conjecture](#witten-s-conjecture).


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

Referenced: [Virasoro constraint](#virasoro-constraint).


#### <span class="org-todo todo TODO">TODO</span> String equation {#string-equation}


#### <span class="org-todo todo TODO">TODO</span> Diliton equation {#diliton-equation}


#### Virasoro constraint {#virasoro-constraint}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 21:34]</span></span>
Using the same generating function as in [Witten's Conjecture](#witten-s-conjecture). We define partition function \\(Z(\lambda, t) = \exp(F)\\). Now we define a sequence of operators satisfying the [Virasoro bracket](#virasoro-bracket).
\\[L\_{n} = -\frac{(2n + 3)!!}{2 ^{n + 1}} \frac{\partial}{\partial t\_{n + 1}} + \sum\_{i = 0}^{\infty} \frac{(2i + 2n + 1)!!}{(2i - 1)!! 2 ^{n + 1}} t\_{i} \frac{\partial}{\partial t\_{i + n}} + \frac{\lambda^{2}}{2} \sum\_{i = 0}^{n - 1} \frac{(2i + 1)!! (-2i +2n - 1)!!}{2 ^{n + 1}} \frac{\partial^{2}}{\partial t\_{i} \partial t\_{n - 1 - i}}\\]
Then we have that
\\[L\_{n}(Z) = 0\\]
for \\(n \geq -1\\), which is called **Virasoro constraint**.

Referenced: [MNOP conjecture](#mnop-conjecture).


### Moduli space of Stable Maps {#moduli-space-of-stable-maps}



{{% definition %}}
Let \\(X\\) be a non-singular projective variety. A morphism \\(f\\) from a pointed nodal curve to \\(X\\) is a **stable map** if every genus \\(0\\) contracted component of \\(\Sigma\\) has at least three special points, and every genus \\(1\\) contracted component has at least one special point.
{{% /definition %}}

{{% definition %}}
A stable map represents a homology class \\(\beta \in H\_{2}(X, \mathbb{Z})\\) if \\(f\_{\*}[C] = \beta\\).
{{% /definition %}}

{{% definition %}}
The moduli space of stable maps from \\(n\\)-pointed genus \\(g\\) nodal curves to \\(X\\) representing the class \\(\beta\\) is denoted \\(\bar{M}\_{g,n}(X, \beta)\\). The subscript \\(n\\) may be omitted if \\(n = 0\\).
{{% /definition %}}

The moduli space \\(\overline{M}\_{g,n}(X, \beta)\\) is a Deligne-Mumford stack. And the moduli    space admits [Virtual fundamental class](#virtual-fundamental-class).

Referenced: [Gromov-Witten theory](#gromov-witten-theory).


### <span class="org-todo todo TODO">TODO</span> Morphism {#morphism}



Referenced: [Toric](#toric).


#### Toric {#toric}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-12 Sun 20:23]</span></span>
Let \\(V\_{i} = \spec (\CC[S\_{i}])\\) be the [Affine toric variety](#affine-toric-variety) coming from the affine semigroup \\(S\_{i}\\), \\(i = 1,2\\). Then a [Morphism](#morphism) \\(\phi: V\_{1} \to V\_{2}\\) is **toric** if the corresponding map of coordinate rings \\(\phi^{\* }: \CC[S\_{2}] \to \CC[S\_{1}]\\) is induced by a [Semigroup](#semigroup) homomorphism \\(\hat{\phi}: S\_{2} \to S\_{1}\\).

A toric morphism is **equivariant**. That is
\\[\phi(t \cdot p) = \phi(t) \cdot \phi(p)\\]
for \\(t \in T\_{N}\\) and \\(p \in V\_{1}\\).


### Non-normal toric variety {#non-normal-toric-variety}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:08]</span></span>
[Toric variety](#toric-variety) is not necessarily normal. For example, \\(\spec \CC[x,y]/(x^{2} - y^{3})\\).


### Polyhedral cone {#polyhedral-cone}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 19:48]</span></span>
A **convex polyhedral cone** in a real vector space \\(N\_{\RR}\\) is a set of the form
\\[\sigma = \cone(S) = \\{\sum\_{u \in S} \lambda\_{u} u \mid \lambda\_{u} \geq 0\\}\\]
where \\(S \subset N\_{\RR}\\) is finite. And we say that \\(\sigma\\) is generated by \\(S\\). In particular, we define \\(\cone(\emptyset) = \\{0\\}\\).

The **dimension** of polyhedral cone is the dimension of the minimal linear space containing the cone.

Referenced: [Affine toric variety](#affine-toric-variety), [Polytope](#polytope), [Dual cone](#dual-cone), [Supporting hyperplane](#supporting-hyperplane), [Face](#face), [Dual face](#dual-face), [Relative interior space](#relative-interior-space), [Strongly convex](#strongly-convex), [Separation lemma](#separation-lemma), [Rational](#rational), [Smooth](#smooth), [Simplicial](#simplicial), [Saturated](#saturated).


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

Referenced: [Face](#face), [Separation lemma](#separation-lemma).


#### Face {#face}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:04]</span></span>
A **face** of a cone of the [Polyhedral cone](#polyhedral-cone) \\(\sigma\\) is \\(\tau = H\_{m} \cap \sigma\\) for some \\(m \in \sigma^{\vee}\\) and \\(H\_{m}\\) is the [Supporting hyperplane](#supporting-hyperplane). We may write as \\(\tau \preceq \sigma\\). If \\(\tau \neq \sigma\\), we called \\(\tau\\) the **proper face** and write \\(\tau \prec \sigma\\). A **facet** is a face of codimension \\(1\\) and an **edge** is a face of dimension \\(1\\).

The faces of the [Strongly convex](#strongly-convex) [Rational](#rational) [Polyhedral cone](#polyhedral-cone) gives affine open subset of the [Affine toric variety](#affine-toric-variety). ([<span id="8a8485591c9ae40ab7e9a4d136fca3d2"><a href="#cox2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">cox2011</a></span>] Proposition 1.3.16)

{{% proposition %}}
Let \\(\tau\\) be a face of strongly convex rational polyhedral cone \\(\sigma\\) and \\(\tau = H\_{m} \cap \sigma\\) for some \\(m \in \sigma^{\vee} \cap M\\). Then we have
\\[\CC[S\_{\tau}] = \CC[S\_{\sigma}]\_{\chi^{m}}\\]
{{% /proposition %}}

Referenced: [Dual face](#dual-face).


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

Referenced: [Affine toric variety](#affine-toric-variety), [Face](#face), [Smooth](#smooth), [Simplicial](#simplicial), [Saturated](#saturated).


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

Referenced: [Affine toric variety](#affine-toric-variety), [Face](#face), [Smooth](#smooth), [Simplicial](#simplicial), [Saturated](#saturated).


#### Smooth {#smooth}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:20]</span></span>
A [Strongly convex](#strongly-convex), [Rational](#rational) [Polyhedral cone](#polyhedral-cone) is called **smooth** or **regular** if its minimal generators form part of a \\(\ZZ\\)-basis of \\(N\\).

The following theorem justify the above name. ([<span id="8a8485591c9ae40ab7e9a4d136fca3d2"><a href="#cox2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">cox2011</a></span>] Theorem 1.3.12)

{{% theorem %}}
Let \\(\sigma \subset N\_{\RR}\\) be a strongly convex rational polyhedral cone. Then \\(U\_{\sigma}\\) is smooth if and only if \\(\sigma\\) is smooth. Furthermore, all smooth affine varieties are of this form.
{{% /theorem %}}


#### Simplicial {#simplicial}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:24]</span></span>
A [Strongly convex](#strongly-convex), [Rational](#rational) [Polyhedral cone](#polyhedral-cone) is called **simplicial** if its minimal generators are linearly independent over \\(\RR\\).


### Predeformation functor {#predeformation-functor}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-19 Sun 20:14]</span></span>
A **predeformation functor** is a covariant functor \\(F: \cat{Art}(\Lambda, k) \to \cat{Set}\\) such that \\(F(k)\\) is the one-element set. The **tangent space** \\(T\_{F}\\) is defined to be \\(F(k[\epsilon]/(\epsilon^{2}))\\). The objects of \\(\cat{Art}(\Lambda, k)\\) are local Artin \\(\Lambda\\)-algebra with residue field \\(k\\).

Cf. [Tangent space](#tangent-space).

Referenced: [Deformation functor](#deformation-functor), [Hull](#hull), [Schlessinger's theorem](#schlessinger-s-theorem).


### Presheaf {#presheaf}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 21:35]</span></span>
A **presheaf** on a category \\(C\\) is a functor
\\[F: C^{op} \to \cat{Set}\\]
We usually write \\(\hat{C}\\) for teh category of presheaves on \\(C\\).

Referenced: [Separated](#separated), [Sheaf](#sheaf).


#### Separated {#separated}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 21:36]</span></span>
A [Presheaf](#presheaf) \\(F\\) on \\(C\\) is called **separated** if for every \\(U \in C\\) and \\(\\{U\_{i} \to U\\}\_{i \in I} \in \cat{Cov}(U)\\) the map \\(F(U) \to \prod F(U\_{i})\\) is injective.


### <span class="org-todo todo TODO">TODO</span> Prestack {#prestack}


### Prorepresnetable {#prorepresnetable}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-19 Sun 20:23]</span></span>
Let \\(\widehat{\cat{Art}(\Lambda, k)}\\) be the category of complete Noetherian local \\(\Lambda\\)-algebra with residue field \\(k\\). Set \\(\hat{F} := \varprojlim\_{n} F(R/ \mathfrak{m}^{n})\\). We say that \\(F\\) is **propresentable** if and only if \\(\hat{F}\\) is representable.

Referenced: [Schlessinger's theorem](#schlessinger-s-theorem).


### Pure {#pure}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:29]</span></span>
\\(E\\) is **pure of dimension** \\(d\\) if \\(\dim F = d\\) for all non-trivial coherent subsheaves \\(F \subset E\\).

Referenced: [Stable](#stable).


### Rational surface {#rational-surface}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:36]</span></span>
A **rational surface** is an algebraic surface birational equivalent to \\(\CC P^{2}\\).


### Reflexive {#reflexive}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:39]</span></span>
A coherent sheaf \\(E\\) of codimension \\(c\\) is called **reflexive** if \\(\theta\_{E}: E \to E^{DD}\\) is an isomorphism. \\(E^{DD}\\) is called the **reflexive hull**  of \\(E\\).

Cf. [Dual sheaf](#dual-sheaf).


### Regular sequence {#regular-sequence}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:47]</span></span>
Let \\(M\\) be a module over a local ring \\(A\\). An element \\(a \in \mathfrak{m}\\) of \\(A\\) is called **\\(M\\)-regular** if \\(m \to am\\) is injective morphism. A sequence \\(a\_{1}, \cdots, a\_{l} \in \mathfrak{m}\\) is a **\\(M\\)-regular sequence** if \\(a\_{i}\\) is \\(M/(a\_{1}, \cdots, a\_{i - 1}) M\\) regular for all \\(i\\).

The definition can be generalized to sheaf theoretic language. Let \\(X\\) be a Noetherian scheme, let \\(E\\) be a coherent sheaf on \\(X\\) and \\(L\\) a line bundle on \\(X\\). A section \\(s \in H^{0}(X, L)\\) is called **\\(E\\)-regular** if and only if \\(E \otimes L^{\vee} \stackrel{\cdot s}{\to} E\\) is injective. A sequence \\(s\_{1}, \cdots, s\_{l} \in H^{0}(X, L)\\) is called **\\(E\\)-regular** similarly in the module theoretic language.

Referenced: [Depth](#depth).


### <span class="org-todo todo TODO">TODO</span> Riemann-Roch theorem {#riemann-roch-theorem}


### <span class="org-todo todo TODO">TODO</span> Ring {#ring}




#### <span class="org-todo todo TODO">TODO</span> Local ring {#local-ring}



Referenced: [Hull](#hull), [Complete](#complete).


#### Complete {#complete}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-19 Sun 20:14]</span></span>
A [Local ring](#local-ring) is called **complete** if it is complete with respect to the \\(\mathfrak{m}\\)-adic topology.

Referenced: [Hull](#hull).


#### <span class="org-todo todo TODO">TODO</span> Noetherian {#noetherian}



Referenced: [Hull](#hull).


### Schlessinger's theorem {#schlessinger-s-theorem}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-19 Sun 20:24]</span></span>
The **Schlessinger's theorem** is a criterion for existence of [Hull](#hull) or [Prorepresnetibility](#prorepresnetable).

{{% theorem %}}
Let \\(F\\) be a predoformation functor. Then \\(F\\) has a hull if and only if the following conditions (1-3) holds, and \\(F\\) is prorepresentable if and only if in addition (4) holds.

1.  The map
    \\[F(A' \times\_{A} A'') \to F(A') \times\_{F(A)} F(A'')\\]
    is surjective when \\(A'' \to A\\) is a small thickening.
2.  The above map is bijective when \\(A = k\\) and \\(A'' = k[\epsilon]\\).
3.  The tangent space \\(T\_{F}\\) is finite-dimensional over \\(k\\).
4.  The above map is bijective if \\(A'' = A'\\) and \\(A' \to A\\) is a small thickening.
{{% /theorem %}}

Cf. [Predeformation functor](#predeformation-functor), [Small thickening](#small-thickening).

Referenced: [Deformation functor](#deformation-functor).


### Semigroup {#semigroup}



Referenced: [Toric](#toric), [Affine semigroup](#affine-semigroup), [Irreducible](#irreducible).


#### Affine semigroup {#affine-semigroup}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:17]</span></span>
An **affine semigroup** is a [Semigroup](#semigroup) where the binary operation is commutative, finite generated, and can be embedded in a [Lattice](#lattice) \\(M\\).

Referenced: [Affine toric variety](#affine-toric-variety), [Pointed](#pointed), [Saturated](#saturated).


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

\begin{equation} m \to \begin{cases} 1 & m = 0 \\\\\\ 0 & m \neq 0 \end{cases} \end{equation}
{{% /proposition %}}


#### Saturated {#saturated}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-12 Sun 19:44]</span></span>
An [Affine semigroup](#affine-semigroup) \\(S \subset M\\) is **saturated** if for all \\(k \in \NN \backslash \\{0\\}\\) and \\(m \in M\\), \\(km \in S\\) implies \\(m \in S\\). ([<span id="8a8485591c9ae40ab7e9a4d136fca3d2"><a href="#cox2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">cox2011</a></span>] p.37)

One important source of the saturated affine semigroup is \\(S\_{\sigma} = \sigma^{\vee} \cap M\\) where \\(\sigma\\) is a [Strongly convex](#strongly-convex) [Rational](#rational) [Polyhedral cone](#polyhedral-cone).

The saturated affine semigroup is related to normal [Affine toric variety](#affine-toric-variety). ([<span id="8a8485591c9ae40ab7e9a4d136fca3d2"><a href="#cox2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">cox2011</a></span>] Theorem 1.3.5)

{{% theorem %}}
Let \\(V\\) be an affine toric variety with torus \\(T\_{N}\\). Then \\(V\\) is normal if and only if \\(V = \spec(\CC[S])\\), where \\(S \subset M\\) is a saturated affine semigroup.
{{% /theorem %}}


### <span class="org-todo todo TODO">TODO</span> Semismall map {#semismall-map}



Referenced: [Small map](#small-map).


### <span class="org-todo todo TODO">TODO</span> Serre duality {#serre-duality}


### Sheaf {#sheaf}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:46]</span></span>
A [Presheaf](#presheaf) \\(F\\) on \\(C\\) is called a **sheaf** if for every object \\(U \in C\\) and covering \\(\\{U\_{i} \to U\\}\\) the sequence
\\[F(U) \to \prod\_{i} F(U\_{i}) \rightrightarrows \prod\_{i,j} F(U\_{i} \times\_{U} U\_{j})\\]
is exact, where the two maps on the right are induced by the two projections \\(U\_{i} \times\_{U} U\_{j} \to U\_{i}\\) and \\(U\_{i} \times U\_{j} \to U\_{j}\\). Here exact means equalizer.

We write \\(C^{~}\\) for the category of sheaves on \\(C\\).

{{% theorem %}}
Let \\(C\\) be a site. The inclusion
\\[\text{(sheaves on \\(C\\))} \hookrightarrow \text{(presheaves on \\(C\\))}\\]
has a left adjoint \\(F \to F^{a}\\).
{{% /theorem %}}

Cf. [Site](#site).

The left adjoint \\(F \to F^{a}\\) is called **sheafification** and \\(F^{a}\\) is called the **sheaf associated to** \\(F\\).

For \\(f: C' \to C\\) functor between small categories, we have functor \\(f\_{\*}: \hat{C} \to \hat{C}\\) by \\((f\_{\*}F)(X) := F(f(X))\\). And we have left adjoint functor \\(\hat{f}^{\*}\\). And if \\(f\\) is [Continuous](#continuous), then the induced functor between [Topoi](#topos) \\(f\_{\*}: T \to T'\\) also has a left adjoint.

If finite limits in \\(C'\\) are representable and that \\(f\\) commutes with all finite limits in \\(C'\\). Then \\(f^{\*}\\) commutes with finite limits and hence \\(f\\) defines a morphism of topoi.

Referenced: [Framed moduli space](#framed-moduli-space), [Sheafification](#sheafification), [Topos](#topos).


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

Referenced: [Multiplicity](#multiplicity), [Rank](#rank), [Stable](#stable), [&mu;-stable](#and-mu-stable).


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

A coherent sheaf \\(E\\) of dimension \\(d\\) is **semistable** if \\(E\\) is [Pure](#pure) and for any proper subsheaf \\(F \subset E\\), one has [Hilbert polynomial](#hilbert-polynomial) \\(p(F) \leq p(E)\\). And is **stable** if \\(E\\) is semistable and \\(p(F) < p(E)\\)

{{% proposition %}}
Let \\(F\\) and \\(G\\) be semistable purely \\(d\\)-dimensional sheaves. If \\(p(F) \geq p(G)\\) then \\(\Hom(F, G) = 0\\). If \\(p(F) = p(G)\\) and \\(f: F \to G\\) non-trivial, then \\(f\\) is injective if \\(F\\) is stable and surjective if \\(G\\) is stable. If \\(p(F) = p(G)\\) and \\(\alpha\_{d}(F) = \alpha\_{d}(G)\\) then any non-trivial homomorphism \\(f: F \to G\\) is an isomorphism provided \\(F\\) or \\(G\\) is stable.
{{% /proposition %}}

{{% corollary %}}
If \\(E\\) is a stable sheaf, then \\(\End(E)\\) is a finite dimensional division algebra over \\(k\\). In particular if \\(k\\) is algebraically closed, then \\(\End(E) \cong k\\).
{{% /corollary %}}

Referenced: [Geometrically stable](#geometrically-stable).


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


### Sheafification {#sheafification}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 22:01]</span></span>
Cf. [Sheaf](#sheaf).


### Simple resolution {#simple-resolution}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:31]</span></span>
See [<span id="24e67c8afe5163064e4018cb5a5cbd8a"><a href="#nakajima1999" title="Nakajima, Lectures on {{Hilbert}} Schemes of Points on Surfaces, {American Mathematical Society} (1999).">nakajima1999</a></span>] p.47.

A **simple singularity** is a quotient space \\(\CC^{2} / \Gamma\\), where \\(\Gamma\\) is a finite subgroup of \\(\SU(2)\\). A **simple resolution** is a resolution of simple singularity.

The following theorem construct the simple resolution by [Hilbert scheme](#hilbert-scheme) of points.

{{% theorem %}}
Consider the Hilbert scheme \\((\CC^{2})^{ [N]}\\) where \\(N\\) is the order of \\(\Gamma\\). The \\(\Gamma\\) orbit of a point \\(p\\) in \\(\CC\backslash \\{0\\}\\) defines a \\(0\\) dimensional subscheme \\(Z \in (\CC^{2})^{ [N]}\\). Let \\(X\\) be the component of \\(\Gamma\\) fixed point set which contains the set of \\(\Gamma\\)-orbits \\(\Gamma \cdot (\CC \backslash \\{0\\})\\). Then we have that the restriction of the Hilbert-Chow morphism to \\(X\\) is the minimal resolution of singularities of \\(\CC^{2} \backslash \Gamma \cong (S^{N}(\CC^{2}))^{\Gamma}\\).
{{% /theorem %}}

Referenced: [Simple singularity](#simple-singularity).


### Simple singularity {#simple-singularity}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:32]</span></span>
See [Simple resolution](#simple-resolution).


### Site {#site}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 21:24]</span></span>
A category with a [Grothendieck topology](#grothendieck-topology) is called a **site**.

{{% exam %}}
Let \\(X\\) be a topological space, \\(\cat{Op}(X)\\) the category of open sets. Then let \\(\cat{Cov}(U)\\) to be the collections \\(\\{U\_{i} \to U\\}\\) for which \\(U = \cup U\_{i}\\), where \\(U\_{i}\\) is a Grothendieck topology. For Zariski topology space, it is called **small Zariski site**.
{{% /exam %}}

{{% exam %}}
Let \\(X\\) be a scheme and let \\(\cat{(Sch/X)}\\) be the category of \\(X\\)-schemes. We define \\(\cat{Cov}(X)\\) be the set of collections \\(\\{U\_{i} \to U\\}\\) of \\(X\\)-morphisms for which each morphism \\(U\_{i} \to U\\) is étale and the map
\\[\coprod U\_{i} \to U\\]
is surjective. It is called **big étale site**.
{{% /exam %}}

Similarly, we can define **fppf site** (flat and locally of finite presentation) and **smooth site**.

Referenced: [Continuous](#continuous), [Étale site](#étale-site), [Fppf site](#fppf-site), [Sheaf](#sheaf), [Smooth site](#smooth-site), [Topos](#topos).


### <span class="org-todo todo TODO">TODO</span> Small map {#small-map}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-20 Sat 21:44]</span></span>
See [Semismall map](#semismall-map).


### Small thickening {#small-thickening}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-19 Sun 20:23]</span></span>
A surjective map \\(f: A \to B\\) in \\(\cat{Art}(\Lambda, k)\\) is a **small thickening** if \\(\ker f \mathfrak{m}\_{A} = 0\\) and \\(\ker f\\) is principal.

Referenced: [Schlessinger's theorem](#schlessinger-s-theorem).


### Smooth {#smooth}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-28 Tue 19:58]</span></span>
Let \\(F, F': \cat{Art}(\Lambda, k) \to \cat{Set}\\) be covariant functors, with a morphism \\(\phi: F \to F'\\). We say that \\(\phi\\) is **smooth** if for every surjection \\(A \to B\\) in \\(\cat{Art}(\Lambda, k)\\) the map
\\[F(A) \to F(B) \times\_{F'(B)}F'(A)\\]
is surjective.


### Smoothness of Hilbert scheme {#smoothness-of-hilbert-scheme}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-16 Thu 20:44]</span></span>
See [<span id="24e67c8afe5163064e4018cb5a5cbd8a"><a href="#nakajima1999" title="Nakajima, Lectures on {{Hilbert}} Schemes of Points on Surfaces, {American Mathematical Society} (1999).">nakajima1999</a></span>], Section 1.3.

{{% theorem %}}
Suppose \\(X\\) is nonsingular of dimension \\(2\\), then \\(X^{ [n]}\\) is nonsingular of dimension \\(2n\\) and the Hilbert-Chow morphism is a resolution of singularities.
{{% /theorem %}}

Cf. [Hilbert scheme](#hilbert-scheme), [Hilbert-Chow morphism](#hilbert-chow-morphism).


### Smooth site {#smooth-site}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 21:32]</span></span>
See [Site](#site).


### <span class="org-todo todo TODO">TODO</span> Spectral sequence {#spectral-sequence}



Referenced: [Eilenberg-Zilber theorem](#eilenberg-zilber-theorem).


#### <span class="org-todo todo TODO">TODO</span> Beilison spectral sequence {#beilison-spectral-sequence}


### Splitting torus {#splitting-torus}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-16 Thu 20:02]</span></span>
A **splitting torus** is a torus of type \\(k^{\times n}\\).

Cf. [Torus](#torus).


### <span class="org-todo todo TODO">TODO</span> Stack {#stack}


### Symmetric power of P^1 {#symmetric-power-of-p-1}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-16 Thu 20:28]</span></span>
Fact, \\(S^{n}(\PP^{1}) = \PP^{n}\\).


### <span class="org-todo todo TODO">TODO</span> Symplectic resolution {#symplectic-resolution}


### Symplectic structure of Hilbert scheme {#symplectic-structure-of-hilbert-scheme}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-16 Thu 20:41]</span></span>
See [<span id="24e67c8afe5163064e4018cb5a5cbd8a"><a href="#nakajima1999" title="Nakajima, Lectures on {{Hilbert}} Schemes of Points on Surfaces, {American Mathematical Society} (1999).">nakajima1999</a></span>], Section 1.4.

{{% theorem %}}
Suppose \\(X\\) has a holomorphic symplectic form \\(\omega\\). Then \\(X^{ [n]}\\) also has a holomorphic symplectic form.
{{% /theorem %}}

Cf. [Symplectic manifold](#symplectic-manifold), [Hilbert scheme](#hilbert-scheme).


### Topos {#topos}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 22:02]</span></span>
A **topos** is a category \\(T\\) equivalent to the category of [Sheaves](#sheaf) of sets on [Site](#site).

{{% proposition %}}
Let \\(T\\) be a topos, and let \\(F: I \to T\\) be a functor with \\(I\\) small. Then the limit \\(\varprojlim F\\) is representable.
{{% /proposition %}}

{{% remark %}}
Usually topos is more important than site, as different site can give the same topos.
{{% /remark %}}

A **morphism** of topoi \\(f: T \to T'\\) is an adjoint pair
\\[f = (f^{\* }, f\_{\* }, \phi)\\]
where
\\[f\_{\* }: T \to T', \quad f^{\* }: T' \to T\\]
are functors and \\(\phi\\) is an isomorphism
\\[\phi: \Hom\_{T}(f^{\* }(-), -) \to \Hom\_{T'}(-, f\_{\* }(-))\\]
of bifunctors and \\(f^{\* }\\) commutes with finite limits.

Referenced: [Continuous](#continuous), [Category of modules](#category-of-modules), [Sheaf](#sheaf), [Ringed](#ringed), [Point](#point).


#### Ringed {#ringed}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-07 Sun 10:12]</span></span>
A **ringed** [Topos](#topos) is a pair \\((T, \Lambda)\\), where \\(\Lambda\\) is a ring object in topos \\(T\\). A **morphism** between ringed topoi is a pair \\((f, f^{\shar})\\) consisting of a morphism of topoi \\(f: T \to T'\\) and a morphism of rings in \\(T'\\) \\(f^{\shar}: \Lambda' \to f\_{\*} \Lambda\\).


#### Point {#point}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-07 Sun 15:17]</span></span>
Let \\(\text{pt}\\) denote the [Topos](#topos) of sheaves on the one-point space. A **point** of the topos \\(T\\) is a morphism of topoi
\\[x: \text{pt} \to T\\]
We say that the topos \\(T\\) has **enough points** if there exists a set of points
\\[\\{x\_{i}: \text{pt} \to T\\}\\]
such that the induced functor
\\[T \to \cat{Set}^{I}, F \to \\{x\_{i}^{\*}F\\}\\]
is faithful.


### Toric ideal {#toric-ideal}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:05]</span></span>
A prime [Lattice ideal](#lattice-ideal) is called **toric ideal**.

We have following criterion for toric ideal.

{{% proposition %}}
An ideal \\(I \subset \CC[x\_{1}, \cdots, x\_{s}]\\) is toric if and only if it is prime and generated by binomials.
{{% /proposition %}}

Referenced: [Affine toric variety](#affine-toric-variety).


### <span class="org-todo todo TODO">TODO</span> Toric variety {#toric-variety}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:08]</span></span>
The toric variety is a field connecting algebraic geometry, combinatorial and mathematical physics. Our main reference is [<span id="8a8485591c9ae40ab7e9a4d136fca3d2"><a href="#cox2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">cox2011</a></span>].

Cf. [Affine toric variety](#affine-toric-variety)

Referenced: [Non-normal toric variety](#non-normal-toric-variety).


### Torsion filtration {#torsion-filtration}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:30]</span></span>
The **torsion filtration** of a coherent sheaf \\(E\\) is the unique filtration
\\[0 \subset T\_{0}(E) \subset \cdots \subset T\_{d}(E) = E\\]
where \\(d = \dim(E)\\) and \\(T\_{i}(E)\\) is the maximal subsheaf of \\(E\\) of dimension \\(\geq i\\).


### Torsion free {#torsion-free}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:52]</span></span>
A coherent sheaf \\(E\\) is called **torsion free** if for each \\(x \in X\\) and \\(s \in \OO\_{X,x} \backslash \\{0\\}\\) the multiplication by \\(s\\) induces a injective morphism \\(E\_{x} \to E\_{x}\\).


### Torus {#torus}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 19:51]</span></span>
Over \\(\CC\\), a torus is \\(\CC^{\* n}\\). In general a scheme \\(X\\) over \\(k\\) is called a torus if \\(X\_{k^{a}}\\) is of the form \\((k^{a})^{\times n}\\) where \\(k^{a}\\) is the algbraic closure of \\(k\\).

The following proposition is useful in toric geometry over \\(\CC\\). The image of a torus in a torus is also a torus.

{{% proposition %}}
Let \\(T\_{1}\\) and \\(T\_{2}\\) be tori, and \\(\Phi: T\_{1} \to T\_{2}\\) a group homomorphism and morphism of varieties. Then the image of \\(\Phi\\) is a torus and closed in \\(T\_{2}\\).
{{% /proposition %}}

A group subvariety of a torus is a torus.

{{% proposition %}}
If \\(H \subset T\\) is an irreducible group subvariety of \\(T\\). Then \\(H\\) is a torus.
{{% /proposition %}}

Referenced: [Affine toric variety](#affine-toric-variety), [Character (of a torus)](#character--of-a-torus), [Splitting torus](#splitting-torus).


### Versal extension {#versal-extension}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 21:37]</span></span>
An \\(A\\)-[Extension](#extension) \\((P, f)\\) is called **versal** if for every other \\(A\\)-extensions \\((R', \phi)\\) of \\(R\\), there exists a homomorphism of extensions \\(r: (P, f) \to (R, \phi)\\). For example, for \\(R = P/I\\) where \\(P\\) a polynomial ring over \\(A\\),
\\[0 \to I/I^{2} \to P/I^{2} \to R \to 0\\]
is a versal \\(A\\)-extension of \\(R\\).

{{% remark %}}
The word versal is similar to universal and certainly has some similarities. However, I don't know which words come into math world first.
{{% /remark %}}


### Virasoro bracket {#virasoro-bracket}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 21:32]</span></span>
**Virasoro bracket** is a set of commutator relation for operators \\(L\_{n}\\) such that
\\[[L\_{n}, L\_{m}] = (n - m) L\_{n + m}\\]

Referenced: [Virasoro constraint](#virasoro-constraint).


### <span class="org-todo todo TODO">TODO</span> Virtual fundamental class {#virtual-fundamental-class}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-01 Wed 16:57]</span></span>
The analog of [Fundamental class](#fundamental-class) for stacks and orbifold.

Referenced: [Donaldson-Thomas theory](#donaldson-thomas-theory), [Moduli space of Stable Maps](#moduli-space-of-stable-maps).


### <span class="org-todo todo TODO">TODO</span> Yoneda product {#yoneda-product}


## Symplectic Geometry {#symplectic-geometry}




### Liouville vector field {#liouville-vector-field}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-02 Thu 10:51]</span></span>
Let \\((M, \omega)\\) is a [Symplectic manifold](#symplectic-manifold). A vector field \\(V: M \to TM\\) is **Liouville** if \\(L\_{X} \omega = \omega\\).
Cf. [Lie derivative](#lie-derivative).

The existence of a Liouville vector field implies that \\((M, \omega)\\) is exact as the one-form \\(\lambda = i\_{V} \omega\\) satisfies that \\(\dif \lambda = \omega\\).

Referenced: [Weinstein manifold](#weinstein-manifold).


### Symplectic manifold {#symplectic-manifold}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-02 Thu 10:43]</span></span>
A **symplectic manifold** is a [smooth Manifold](#manifold) \\(X\\) of even dimension \\(\dim X = 2n\\), equipped with a **symplectic form** a closed smooth \\(2\\)-form \\(\omega \in \Omega\_{cl}^{2}(X)\\) such that \\(\omega\\) is non-degenerate. That is \\(\omega^{n}\\) has the maximal rank at every point \\(p\\), or equivalently that \\((\wedge^{2} T\_{p}^{\* }X, \omega\_{p})\\) symplectic vector space for every \\(p\\).

Referenced: [Symplectic structure of Hilbert scheme](#symplectic-structure-of-hilbert-scheme), [Liouville vector field](#liouville-vector-field), [Weinstein manifold](#weinstein-manifold).


### Weinstein manifold {#weinstein-manifold}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-02 Thu 10:42]</span></span>
A [Symplectic manifold](#symplectic-manifold) \\((M, \omega)\\) is **Weinstein** if it comes with a distinguished [Liouville vector field](#liouville-vector-field) \\(Y\\), and a proper bounded below function \\(h: M \to \RR\\), such that \\(\dif h(Y)\\) is positive on a sequence of level set \\(h^{-1}(c\_{k})\\) with \\(\lim\_{k}c\_{k} = \infty\\).

A Weinstein manifold is called **of finite type** if \\(\dif h(Y) > 0\\) outside a compact subset of \\(M\\) and is called **complete** if the flow of \\(Y\\) is defined for all times.


## Geometric representation theory {#geometric-representation-theory}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-29 Sun 15:26]</span></span>
In geometric representation theory, we tries to encode the algebra operation in geometric objects. The one of the general construction is the usage of correspondence, that is the cycles or sheaves etc in \\(X\_{1} \times X\_{2}\\). It is a nonlinear analog of matrices. To retain the linear information, we consider functors such as [Equivariant cohomology](#equivariant-cohomology) and [Equivariant K-theory](#equivariant-k-theory).


### Langlands dual pair {#langlands-dual-pair}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:39]</span></span>
The **Langlands dual** is a pair of [Algebraic groups](#algebraic-group) \\((X, Y)\\) such that the root system of \\(X\\) is coroot of \\(Y\\) and vice versa. The center of \\(X\\) is the fundamental group of \\(Y\\) and vice versa.

For example \\((\Sp(n), \SO(2n + 1))\\), \\((\SO(2n), \SO(2n))\\) and \\((\SL(n), \PGL(n))\\).


### Steinberg variety {#steinberg-variety}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-29 Sun 15:41]</span></span>
For a general symplectic resolution
\\[\pi: X \to X\_{0}\\]
we have the **Steinerg variety** \\(X \times\_{X\_{0}} X\\).

Referenced: [Algebraic Geometry](#algebraic-geometry).


## Number Theory {#number-theory}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-31 Tue 13:34]</span></span>
There are two main themes in number theory.

-   prime number
-   Diophantine equations


### Langlands correspondence {#langlands-correspondence}



{{< figure src="/img/2021-08-31_14-02-53_screenshot.png" >}}


### Riemann zeta function {#riemann-zeta-function}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-31 Tue 13:37]</span></span>
\\[\zeta(s) = 1 + \frac{1}{2^{s}} + \frac{1}{3^{s}} + \cdots = \prod\_{p \text{ prime}} \frac{1}{1 - p^{-s}}\\]
The function can be extend as a meromorphic function on \\(\CC\\).


### Rosseta stone in mathematics {#rosseta-stone-in-mathematics}

The similarity over number fields, function fields, algebraic curves over \\(\CC\\).

Referenced: [Personal Thoughts]({{<relref "Notes_Mathematics.md#personal-thoughts" >}}).


## Knot Theory {#knot-theory}

Referenced: [Exotic R^4](#exotic-r-4).


### Affine braid group {#affine-braid-group}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:56]</span></span>
We define the **affine braid group** to be
\\[\tilde{B\_{n}} = \langle s\_{1}, \cdots, s\_{n -1}, t\_{1}, \cdots, t\_{n}\rangle\\]
with the same condition as [Braid group](#braid-group) with addition
\\[s\_{i}t\_{i + 1} = t\_{i} s\_{i}\\]


### Braid {#braid}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:41]</span></span>
A **braid** is the isotopy class of a [Geometric braid](#geometric-braid).

{{% theorem %}}
The braids are in bijection with Redemeister classes of diagrams.

{{< figure src="/img/2021-09-21_15-46-24_screenshot.png" >}}
{{% /theorem %}}

Referenced: [Pure](#pure), [Positive](#positive), [Braid group](#braid-group).


#### Pure {#pure}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:46]</span></span>
A [Braid](#braid) is called **pure** if it connects \\(\\{x\_{0}\\} \times \\{0\\}\\) to \\(\\{x\_{i}\\} \times \\{1\\}\\).

Referenced: [Braid group](#braid-group).


#### Positive {#positive}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:43]</span></span>
A [Braid](#braid) is called **positive** if it is a product of \\(\sigma\_{i}\\) and not \\(\sigma\_{i}^{-1}\\) in braid group. And a braid is **quasi-positive** if it has the form \\(\prod\_{k = 1}^{m} w\_{k} \sigma\_{ik} w\_{k}^{-1}\\) where \\(w\_{k}\\) is any word in the braid group. A [Knot](#knot) **positive** (resp. **quasi-positive**) if it is a completion of a positive (resp. quasi-positive) braid.

Referenced: [Quasi-positive](#quasi-positive), [Knots bounds algebraic surface](#knots-bounds-algebraic-surface).


#### Quasi-positive {#quasi-positive}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:44]</span></span>
See [Positive](#positive).

Referenced: [Knots bounds algebraic surface](#knots-bounds-algebraic-surface).


### Braid diagram {#braid-diagram}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:42]</span></span>
Consider the projection \\(\pi: \RR^{2} \times [0,1] \to \RR \times [0,1]\\). Then \\(\hat{\beta}\\) is called **generic** if \\(\pi(\hat{\beta})\\) has simple transversal singular points outside of \\(\RR \times \\{0,1\\}\\). Such \\(\pi(\hat{\beta})\\) is called a **geometric braid diagram**.

A **braid diagram** is a regular isotopy class of a geometric braid diagram.


### Braid group {#braid-group}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:44]</span></span>
The [Braids](#braid) form a group called **braid group** where the composition is given by glueing two embeddings. Obviously, the [Pure](#pure) braids form a subgroup of braid group. The braid group is denoted by \\(B\_{n}\\), and pure braid group by \\(P\_{n}\\).

{{% theorem %}}
\\(B\_{n}\\) is generated by elements

{{< figure src="/img/2021-09-21_15-49-51_screenshot.png" >}}

with defining relations
\\[s\_{i}s\_{i+1}s\_{i} = s\_{i + 1}s\_{i}s\_{i + 1},\; i = 1, \cdots, n - 1\\]
\\[s\_{i}s\_{j} = s\_{j}s\_{i}, \; \abs{i - j} > 1\\]
{{% /theorem %}}

The braid group can be realized as a [Fundamental group](#fundamental-group) of a manifold. Define \\(C\_{n} = \\{x\_{1}, \cdots, x\_{n} \in \RR^{2} \mid x\_{i} \neq x\_{j}\\}\\). Then we have \\(\pi\_{1}(C\_{n}) = P\_{n}\\). By considering the \\(S\_{n}\\) action on \\(C\_{n}\\), we have that \\(B\_{n} = \pi\_{1}(C\_{n}/ S\_{n})\\).

Referenced: [Affine braid group](#affine-braid-group), [Hecke-Iwahori algebra](#hecke-iwahori-algebra), [Representation of braids](#representation-of-braids).


### Diagram {#diagram}

The image of a generic geometric representative \\(\hat{L}\\) of [Link](#link) \\(L\\) from \\(\RR^{3}\\) to \\(\RR^{2}\\) is a **diagram** of \\(L\\).

For equivalent class of diagrams, we have the following theorem by Reidemeister.

{{% theorem %}}
Equivalence class of diagrams with respect to the local moves

{{< figure src="/img/2021-09-13_18-22-18_screenshot.png" >}}
{{% /theorem %}}

We can also consider the diagram of [Framed](#framing) links in \\(\RR^{3}\\). And we have equivalence class of regular isotopy class of framed diagrams on \\(\RR^{2}\\) is given by

{{< figure src="/img/2021-09-13_18-30-56_test.png" >}}

Referenced: [Skein relations](#skein-relations), [Unknot number](#unknot-number).


### Framed {#framed}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 16:01]</span></span>
See [Framing](#framing).

Referenced: [Jones-Markov trace](#jones-markov-trace).


### Framing {#framing}

**Framing** of a [Link](#link) in \\(\RR^{3}\\) is an isotopy class of a continuous section of a normal bundle to \\(L \subset \RR^{3}\\).

Referenced: [Diagram](#diagram), [Framed](#framed).


### Geometric braid {#geometric-braid}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:38]</span></span>
A **geometric braid** in \\(\RR^{2} \times [0,1]\\) is an embedding \\(\hat{\beta} : [0,1]^{\coprod n} \to \RR^{2} \times [0,1]\\) connecting \\(\\{x\_{0}, \cdots, x\_{n}\\} \times \\{0\\}\\) and \\(\\{x\_{0}, \cdots, x\_{n}\\} \times \\{1\\}\\) componentwise.

Referenced: [Braid](#braid).


### Hecke-Iwahori algebra {#hecke-iwahori-algebra}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:53]</span></span>
For [Braid group](#braid-group) \\(B\_{n}\\), the elements \\((s\_{i} - q)(s\_{i} + q^{-1})\\) generates an ideal in the group algebra \\(\CC[B\_{n}]\\). The **Hecke-Iwahori algebra** is the quotient algebra with respect to the ideal, i.e.,
\\[H\_{n}(q) = \langle s\_{1}, \cdots, s\_{n} \rangle\\]
such that
\\[s\_{i}s\_{i+1}s\_{i} = s\_{i + 1}s\_{i}s\_{i + 1},\; i = 1, \cdots, n - 1\\]
\\[s\_{i}s\_{j} = s\_{j}s\_{i}, \; \abs{i - j} > 1\\]
\\[(s\_{i} - q)(s\_{i} + q^{-1}) = 0\\]
The interesting case is that \\(q\\) be the root of \\(1\\).

\\(H\_{n}(q)\\) is a deformation of \\(\CC[S\_{n}]\\).


### HOMFLY invariant {#homfly-invariant}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 18:37]</span></span>
Since [Skein relations](#skein-relations) are compatible with Reidemeister moves, for every [Link](#link), we may consider its diagram \\(D\_{L}\\) and we define \\([D\_{L}] = \langle L \rangle [O]\\). Here \\(O\\) is one loop and \\(\langle L \rangle \in \ZZ[A, B^{\pm 1}, C]\\). \\(\langle L \rangle\\) depends only on \\(L\\) but not on representative diagram \\(D\_{L}\\). \\(\langle L \rangle\\) is the **HOMFLY** invariant of framed links.

For unframed links, we also have **HOMFLY invariants** by consider \\(L = L\_{1} \coprod \cdots \coprod L\_{n}\\) as framed links and consider \\(\langle \langle L \rangle \rangle = B^{- \sum\_{i} w(L\_{i})} \langle L \rangle\\) where \\(w(L\_{i})\\) is the winding number.


### Jones-Markov trace {#jones-markov-trace}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:58]</span></span>
There exists a **Jones-Markov** trace \\(\tr: \tilde{B}\_{n} \to k = \ZZ[q, q^{-1}][\frac{1}{(q - q^{-1})}]\\) such that
\\[\tr(\beta \gamma \beta^{-1}) = \tr(\gamma)\\]
\\[\tr(\beta s\_{n}) = \tr(\beta t\_{n}) = z \tr(\beta)\\]

It defines invariants of [Framed](#framed) [Links](#link). To get a invariant of links, we consider [Writhe number](#writhe-number), \\(\omega(\beta)\\). We have \\(\tr(\beta)z^{w(\beta)}\\) is an invarinat of links.

{{% remark %}}
For \\(z = q^{2}\\) the polynomial is the [Jones polynomial](#jones-polynomial).
{{% /remark %}}


### <span class="org-todo todo TODO">TODO</span> Jones polynomial {#jones-polynomial}



Referenced: [Jones-Markov trace](#jones-markov-trace).


### Jones twist {#jones-twist}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 16:15]</span></span>
A map \\(\mu: V \to V\\) is called **Jones twist** if
\\[(\mu \otimes \mu) R = R(\mu \otimes \mu)\\]
\\[(\id \otimes \tr)(\id \otimes \mu) PR = z \id\_{V}\\]


### Knot {#knot}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 18:13]</span></span>
A **knot** (in \\(S^{3}\\)) is an isotopy class of an [Immersion](#immersion) \\(\hat{K}: S^{1} \to S^{3}\\), \\(K = [\hat{K}]\\).

Referenced: [Positive](#positive), [Link](#link), [Homotopic slice](#homotopic-slice), [Knots bounds algebraic surface](#knots-bounds-algebraic-surface), [Linking number](#linking-number), [Poincarè conjecutre](#poincarè-conjecutre), [Unknot number](#unknot-number).


### Link {#link}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 18:13]</span></span>
A **link** is an isotopy class of an [Immersion](#immersion) \\(\hat{L}: (S^{1})^{\times K} \to S^{3}\\), \\(L = \hat{L}\\).

Cf. [Knot](#knot).

Referenced: [Diagram](#diagram), [Framing](#framing), [HOMFLY invariant](#homfly-invariant), [Jones-Markov trace](#jones-markov-trace), [Skein relations](#skein-relations), [Lickorish-Wallace theorem](#lickorish-wallace-theorem), [Seifert surface](#seifert-surface).


### Representation of braids {#representation-of-braids}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 16:10]</span></span>
The following proposition relates the representation of [Braid group](#braid-group) to [Yang-Baxter equation](#yang-baxter-equation).

{{% proposition %}}
If \\(R\\) satisfies the Yang-Baxter equation, the mapping
\\[\rho: B\_{n} \to \aut(V^{\otimes n})\\]
\\[\rho(s\_{i}) = 1 \otimes \cdots \otimes PR \otimes \cdots \otimes 1\\]
where \\(P(x \otimes y) = y \otimes 1\\) extends uniquely to a representation of \\(B\_{n}\\) in \\(V^{\otimes n}\\).
{{% /proposition %}}


### Skein relations {#skein-relations}

We now consider a vector space \\(V\\) of formal \\(\ZZ\\) linear combinations of [Diagrams](#diagram) of [Links](#link) modulo Reidemeister moves. The **Skein relations** are defined by

![](/img/2021-09-13_18-34-45_2021-09-13_18-33.png)
where \\(A, B, C\\) are formal variables and \\(B\\) is invertible. We have
\\[C = \frac{B - B^{-1}}{A}\\]

Also, we Skein is related to Reidemeister moves.

{{% theorem %}}
Skein relations are compatible with Reidemeister moves.
{{% /theorem %}}

Referenced: [HOMFLY invariant](#homfly-invariant).


### Writhe number {#writhe-number}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 16:02]</span></span>
We define the **Writhe number** of \\(\beta\\) to be

{{< figure src="/img/2021-09-21_16-02-43_screenshot.png" >}}

Referenced: [Jones-Markov trace](#jones-markov-trace).


### Yang-Baxter equation {#yang-baxter-equation}



{{% definition %}}
A morphism \\(R: V \otimes V \to V \otimes V\\) satisfies the **Yang-Baxter equation** if
\\[R\_{12}R\_{13}R\_{23} = R\_{23}R\_{13}R\_{12} \in \End(V^{\otimes 3})\\]
where \\(R\_{12} = R \otimes 1\\) and so on.
{{% /definition %}}

An solution is given by
\\[R(e\_{i} \otimes e\_{j}) =  \begin{cases}     q e\_{i} \otimes e\_{i} & i = j \\\\\\     e\_{i} \otimes e\_{j} & i < j \\\\\\     e\_{i} \otimes e\_{j} + (q - q^{-1})e\_{j} \otimes e\_{i} & i > j   \end{cases} \\]

Referenced: [Representation of braids](#representation-of-braids).


## Geometric Topology {#geometric-topology}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 18:20]</span></span>
Named geometric topology, this section includes some result in \\(4\\)-manifold and knot theory and higher dimensional topology.


### 11/8 conjecture {#11-8-conjecture}

By [Freedman's classification of topological 4-manifold](#freedman-s-classification-of-topological-4-manifold), [Rokhlin Theorem](#rokhlin-theorem) and [Donaldson diagonalizable theorem](#donaldson-diagonalizable-theorem), the only remaining case to determine the existence of smooth structure on topological \\(4\\)-manifold are those with \\(Q\_{X}\\) even and indefinite. That is \\(Q\_{X} = mE\_{8} \oplus n \begin{pmatrix} 0 & 1 \\\\\\ 1 & 0 \end{pmatrix}\\). Since we have K3 surface with \\(Q\_{X} = 2E\_{8} \oplus 3 \begin{pmatrix}0 & 1\\\\\\ 1 & 0 \end{pmatrix}\\) and \\(S^{2} \times S^{2}\\) with \\(Q\_{X} = \begin{pmatrix} 0 & 1\\\\\\ 1 & 0 \end{pmatrix}\\), we can show that the for \\(Q\_{X}\\) with \\(m = 2k\\) and \\(n \geq 3k\\) the smooth structure on the manifold exists. The conjecture is that that is the only possibility for the existence of smooth structure.

{{% conjecture %}}
If \\(X\\) is spin, smooth and \\(Q\_{X} = 2k E\_{8} \oplus n \begin{pmatrix} 0 & 1\\\\\\ 1 & 0 \end{pmatrix}\\), then \\(n \geq 3k\\). Or equivalently speaking \\(b\_{2}(X) \geq \frac{11}{8} \abs{\sigma(X)}\\).
{{% /conjecture %}}

A theorem by Furuta says

{{% theorem %}}
Let \\(X\\) be a spin \\(4\\)-manifold, such that \\(b\_{2}(X) \neq 0\\). Then
\\[b\_{2}(X) \geq \frac{10}{8} \abs{\sigma(X)} + 2\\]
{{% /theorem %}}

The [Seiberg-Witten invariant](#seiberg-witten-invariant) together with spin Dirac operator can give one proof. The proof suggests [Bauer-Furuta invariant](#bauer-furuta-invariant).

{{% remark %}}
The current status (2021 Sep.) of the conjecture is that \\(k \leq 1\\) case is proved. For \\(k > 1\\), we have
\\[n \geq 2k + \begin{cases} 2 & k = 1,2,5,6 \\\\\\ 3 & k = 3,4,7 \\\\\\ 4 & 0 \end{cases} \mod 8 \\]
{{% /remark %}}


### <span class="org-todo todo TODO">TODO</span> Alexander duality {#alexander-duality}


### <span class="org-todo todo TODO">TODO</span> Alexander polynomial {#alexander-polynomial}



Referenced: [Fintushel-Stern knot surgery](#fintushel-stern-knot-surgery).


### Anti-self-dual {#anti-self-dual}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 20:21]</span></span>
A \\(n\\)-form \\(w\\) on \\(2n\\) manifold is called **self-dual** if \\(\* w = -w\\).
Cf. [Self-dual](#self-dual).

Referenced: [Self-dual](#self-dual).


### <span class="org-todo todo TODO">TODO</span> Bauer-Furuta invariant {#bauer-furuta-invariant}



Referenced: [Geometric Topology](#geometric-topology).


### Botany problem of 4-manifold {#botany-problem-of-4-manifold}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:52]</span></span>
For \\(b^{+} > 1\\), \\(\pi\_{1} = 1\\) irrducible case, by theorem of Fintushel-Stern, any such \\(X\\) admits \\(\infty\\) smooth structure.

For \\(b^{+} = 1\\), then \\(\CC P^{2} \shar n \overline{\CC P}^{2}\\) for \\(n \geq 2\\) has \\(\infty\\) smooth structure. \\(S^{2} \times S^{2}\\) and \\(n < 2\\) case is unknown.

\\(b^{+} = 0\\) case is completely unknown.

{{% remark %}}
In each case, we have no method to determine whether all the smooth structures have been found. That is if a manifold is known to have some smooth structure, we don't know whether they are all of the possible smooth structures.
{{% /remark %}}

{{% remark %}}
It is well known that \\(S^{7}\\) has 28 different differential structures. And those structures are only smooth structures possible. The proof requires [h-Cobordism](#h-cobordism) theorem, so the similar methods can not be applied to \\(4\\)-manifold.
{{% /remark %}}


### Characteristic class for 4-manifold {#characteristic-class-for-4-manifold}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-22 Wed 20:49]</span></span>
We may assume that \\(X\\) is a connected, closed, oriented, smooth \\(4\\)-manifold.
We have a [Signature](#signature) theorem by Hirzebruch.

{{% theorem %}}
\\[P\_{1}(TX)[X] = 3 \sigma(X)\\]
{{% /theorem %}}

Cf. [Pontryagin class](#pontryagin-class).

And theorem by Wenjun Wu on [Stiefel-Whitney class](#stiefel-whitney-class).

{{% theorem %}}
1.  For all \\(\alpha \in H^{2}(X; \ZZ/2)\\), we have \\(w\_{2}(TX) \cup \alpha = \alpha \cup \alpha\\)
2.  \\(w\_{3}(TX) = \sq^{1}(w\_{2}(TX))\\), here \\(\sq^{1}\\) is the square operator.
{{% /theorem %}}

By above theorem, [Freedman's classification of topological 4-manifold](#freedman-s-classification-of-topological-4-manifold), [Donaldson diagonalizable theorem](#donaldson-diagonalizable-theorem) and algebraic classification of bilinear forms, we have

{{% proposition %}}
Let \\(X\\) be a smooth, closed \\(4\\)-manifold. Then homeomorphism type of \\(X\\) is determined by \\(e(TX), P\_{1}(TX)\\)and \\(w\_{2}(TX)\\).
{{% /proposition %}}

{{% remark %}}
However, characteristic class in dimension \\(4\\) cannot detect exotic phenomenon.
{{% /remark %}}


### Clasp number {#clasp-number}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:39]</span></span>
We define the **clasp number** of \\(K\\) to be minimal number of double points of the immersed disk in \\(D^{4}\\) with boundary \\(K\\) with only transverse double point.

We have \\(c\_{4}(k) \leq U(K)\\) ([Unknot number](#unknot-number)), for we can trade knot for double points. Also, we have \\(g\_{S}(K) \leq c\_{4}(K)\\) ([Slice genus](#slice-genus)) since we can trade double points for genus.


### Clifford algebra {#clifford-algebra}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:56]</span></span>
Let \\(H\\) be a real vector space. The tensor algebra \\(T(H)\\) modulo ideal generated by \\(\\{v \otimes v + \norm{v}^{2}\\}\\) is called the **Clifford algebra**.

Referenced: [Clifford module](#clifford-module).


### Clifford module {#clifford-module}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 20:00]</span></span>
A **Clifford module** of [Clifford algebra](#clifford-algebra) over \\(H\\) is a Hermitian complex vector space \\(V\\) equipped with a **Clifford multiplication** \\(\gamma: H \to \End(V)\\) such that

-   If \\(\norm{e} = 1\\), then \\(\gamma(e)^{2} = -1\\).
-   If \\(e\_{1} \perp v\_{2}\\), then \\(\gamma(e\_{1}) \cdot \gamma(e\_{2}) + \gamma(e\_{2}) \cdot \gamma(e\_{1}) = 0\\).
-   \\(\gamma(e)^{\* } = - \gamma(e)\\).

That is a Clifford module is a representation of Clifford algebra.

The irreducible Clifford module is competely identified.

{{% theorem %}}
If \\(n = 2k\\), then there exists a unique finite dimensional irreducible Clifford module \\((S, \gamma)\\) up to isomoprhism and \\(\dim\_{\CC} S = 2^{k}\\).

If \\(n = 2k + 1\\), there are exactly two clifford modules \\((S, \gamma), (S, - \gamma)\\) up to isomoprhism and \\(\dim\_{\CC} S = 2^{k}\\).
{{% /theorem %}}

Referenced: [Dirac operator](#dirac-operator), [Spin^C structure](#spin-c-structure).


### Corbordism {#corbordism}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-20 Sat 21:38]</span></span>
Let \\(\mathscr{C}\\) denote one of the following categories: smooth / topological / piecewise linear category. Let \\(M\_{0}, M\_{1}\\) be oriented \\(\mathscr{C}\\)-manifold. A **cobordism** \\(W\\) form \\(M\_{0}\\) to \\(M\_{1}\\) is a \\(n + 1\\) dimensional \\(\mathscr{C}\\)-manifold such that \\(\partial W = \bar{M\_{0}} \coprod M\_{1}\\).

We can define the **cobordism category** \\(\cat{Cob}\_{n}\\), where the objects are closed \\(n\\) dimensional manifolds and the morphisms are isotopic classes of cobordisms.

Referenced: [h-Cobordism](#h-cobordism).


### <span class="org-todo todo TODO">TODO</span> Cork {#cork}


### Critical point {#critical-point}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 15:16]</span></span>
The **critical point** of \\(f: X \to \RR\\) is the map \\(\dif f\_{p}: T\_{p}X \to T\_{f(p)} \RR\\) is trivial. And \\(r = f(p)\\) is the **critical value**, otherwise \\(r\\) is called the **regular value**.

Cf. [Regular point](#regular-point).

Referenced: [Non-degenerate](#non-degenerate), [Critical value](#critical-value), [Morse inequality](#morse-inequality).


#### Non-degenerate {#non-degenerate}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 15:19]</span></span>
We say \\(p\\) [Critical point](#critical-point) **non-degenerate** if \\(\det({\rm Hess} f\_{p}) \neq q\\). The **index** of the \\(p\\) is the number of negative eigenvalues of [Hessian](#hessian) of \\(f\\) at \\(p\\).

Referenced: [Index](#index).


### Critical value {#critical-value}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 15:18]</span></span>
See [Critical point](#critical-point).

Referenced: [Regular value](#regular-value).


### Dirac operator {#dirac-operator}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 20:05]</span></span>
Given a [Clifford module](#clifford-module) \\(S\\) over \\(H\\), we define the **Dirac operator** \\(\dirac: C^{\infty}(H, S) \to C^{\infty}(H, S)\\) by
\\[\dirac \phi = \sum\_{i = 1}^{n} \gamma(e\_{i}) \cdot \frac{\partial \phi}{\partial e\_{i}}\\]

\\(\dirac\\) is a self-adjoint operator with \\(\dirac^{2} = \Delta\\).

On manifold, given a [Spin^C connection](#spin-c-connection) \\(A\\), we can also define the **Dirac operator**
\\[\dirac\_{A} = \rho \circ \nabla\_{A}: \Gamma(s) \to \Gamma(s)\\]
For decomposition \\(S = S^{+} \oplus S^{-}\\), we have \\(\dirac\_{A} = \dirac\_{A}^{ +} + \dirac\_{A}^{-} \\)\\(\dirac\_{A}^{ +}: \Gamma(S^{ +}) \to \Gamma(S^{-})\\) and \\(\dirac\_{A}^{-}: \Gamma(S^{-}) \to \Gamma(S^{ + })\\).

On manifolds, the Dirac operator is also self-adjoint. And we call \\(\dirac\_{A}^{2}\\) the **Dirac Laplacian**. We have
\\[\dirac\_{A}^{2} \phi = \Delta \phi + \rho(F\_{A^{\tau}}^{+ }) \phi + \frac{s}{4} \phi\\]
where \\(\Delta\\) is the usual Laplacian and \\(F\_{A^{\tau}}^{+}\\) is the [Self-dual](#self-dual) part of curvature of the connection induced by \\(A\\) on \\(\det(S^{ +})\\)


### Donaldson diagonalizable theorem {#donaldson-diagonalizable-theorem}



{{% theorem %}}
Let \\(X\\) be a smooth \\(4\\)-manifold. Suppose \\(Q\_{X}\\) is definite that is the matrix \\(Q\_{X}\\) is postive or negative definite, we have \\(Q\_{X} \cong \pm \begin{pmatrix} 1 & \cdots & 0 \\\\\\ \vdots & \ddots & \vdots \\\\\\ 0 & \cdots & 1 \end{pmatrix} \\).
{{% /theorem %}}

Cf. [Intersection forms](#intersection-forms).

One of the proofs is given by [Seiberg-Witten invariant](#seiberg-witten-invariant) and following algebra result.

{{% theorem %}}
Let \\(Q: \ZZ^{m} \otimes \ZZ^{m} \to \ZZ\\) be a negative definite, unimodular form and let \\(\Char(Q) = \\{v \in \ZZ^{m} \mid Q(v, w) \equiv Q(w,w) \pmod 2\\}\\). Suppose that \\(Q(v, v) + m \leq 0, \quad \forall v \in \Char(Q)\\). Then \\(Q \cong -I\\).
{{% /theorem %}}

Referenced: [Geometric Topology](#geometric-topology), [Characteristic class for 4-manifold](#characteristic-class-for-4-manifold).


### <span class="org-todo todo TODO">TODO</span> Dot notation {#dot-notation}


### Elliptic fibration {#elliptic-fibration}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:31]</span></span>
A map \\(q: X \to \Sigma\\) is an **elliptic fibration** if there exists a finite set \\(S \subset \Sigma\\) such that \\(X \backslash q^{-1}(S) \to \Sigma \backslash S\\) is a fiber bundle whose fiber is a smooth curve of genus \\(1\\), that is the elliptic curve. We call \\(q^{-1}(t)\\) a **regular fiber** if \\(t \not \in S\\) and a **singular fiber** if \\(t \in S\\).

Cf. [Vector bundle](#vector-bundle).


### Exotic R^4 {#exotic-r-4}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 18:51]</span></span>
\\(\RR^{4}\\) has infinitely many smooth structures. While other Eucliean space has unique smooth structure by Stallings.

{{% theorem %}}
\\(\RR^{4}\\) has uncountably many smooth structures.
{{% /theorem %}}

The construction follows from the oberservation for \\(X = \CC P^{2} \shar 9 \overline{\CC P}^{2}\\), we have \\(Q\_{X} \cong (-E\_{8}) \oplus (-1) \oplus (1)\\). Then if all \\(\RR^{4}\\) has same smooth structure, some kind of surgery gives impossible \\(4\\)-manifolds. By examing the construction carefully, one shows that there exists a parameter such that every two construction gives different smooth structures.

Exotic \\(R^{4}\\) can also be constructed using [Knot Theory](#knot-theory).


### <span class="org-todo todo TODO">TODO</span> Exotic surfaces {#exotic-surfaces}


### <span class="org-todo todo TODO">TODO</span> Fintushel-Stern knot surgery {#fintushel-stern-knot-surgery}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 15:02]</span></span>
The following theorem by Fintushel-Stern gives many exotic smooth structures.

{{% theorem %}}
Suppose \\([T^{2}] \neq 0 \in H\_{2}(X ; \RR)\\), let \\(X\_{K}\\) be the knot surgery along \\(T^{2}\\). Then
\\[SW\_{X\_{K}} = SW\_{X} \cdot \Delta\_{K}(e^{2[T]^{2}})\\]
where \\(SW\_{X} = \sum\_{v \in \Char(X)} SW\_{X}(v) e^{v}\\) and \\(\Delta\\) is the [Alexander polynomial](#alexander-polynomial)
{{% /theorem %}}

{{% corollary %}}
Given any smooth \\(4\\)-manifold \\(X\\) with

-   \\(b^{+}(X) \neq 0\\), \\(\pi\_{1}(X) = 1\\).
-   \\(SW\_{X} \neq 0\\).
-   There exists \\(T^{2} \to X\\) embedding such that \\([T^{2}] \neq 0\\) and \\(T^{2} \cdot T^{2} = 0\\), \\(\pi\_{1}(X \backslash T^{2}) = 1\\).

Then \\(X\\) has infinitely many smooth structure. In particular, all knonw symplectic \\(4\\)-manifold with \\(b^{+} > 1\\) satisfies this conditions.
{{% /corollary %}}

{{% conjecture %}}
Suppose \\([T^{2}] \neq 0\\) then \\(X\_{K} \cong X\_{L}\\) if and only if \\(\pi\_{1}(S^{3} \backslash K) \cong \pi\_{1}(S^{3} \backslash L)\\).
{{% /conjecture %}}

{{% remark %}}
The conjecture is related to the open question, given \\(K, L\\) with \\(\Delta\_{K} = \Delta\_{L}\\) can \\(X\_{K} \not \cong\_{diff} X\_{L}\\). Since there exists many knots with same Alexander polynomial, the question is important. However, we don't have any tool to detect smooth structure other than [Seiberg-Witten invariant](#seiberg-witten-invariant).
{{% /remark %}}


### Freedman's classification of topological 4-manifold {#freedman-s-classification-of-topological-4-manifold}



{{% theorem %}}
1.  Let \\(X\_{0}, X\_{1}\\) be two simply connected topological \\(4\\)-manifolds. Then \\(X\_{0} \cong\_{top} X\_{1} \Leftrightarrow Q\_{X\_{0}} \cong Q\_{X\_{1}}, \ks(X\_{0}) = \ks(X\_{1})\\).
2.  Given any unimodular, symmetric bilinear form \\(Q\\). Then
    1.  Suppose \\(Q\\) is odd, i.e. there exists \\(v\\) such that \\(Q(v,v)\\) is odd, then any combination of \\((Q, i)\\) where \\(i \in \\{0,1\\}\\) can be realized as the intersection form and KS invariant of some simply connected topological \\(4\\)-manifold \\(X\\).
    2.  Suppose \\(Q\\) is even, i.e. for every \\(v\\), \\(Q(v,v)\\) is even. Then \\((Q, i)\\) can be realized if and only if \\(i \equiv \frac{\sigma(Q)}{8} \mod 2\\).
{{% /theorem %}}

Cf. [Manifold](#manifold), [Kirby-Sieberman invariant](#kirby-sieberman-invariant), [Whitehead theorem](#whitehead-theorem), [Intersection forms](#intersection-forms), [Signature](#signature).

By Freedman's result, the Chern number \\(c(X) = 2 \chi(X) + 3 \sigma(X)\\), and [Holomorphic Euler number](#holomorphic-euler-number) \\(\chi\_{h}\\) and \\(t(X) = \begin{cases} 0 & Q\_{X} \text{ is even.} \\ 1 & Q\_{X} \text{ is odd.} \end{cases}\\).

Referenced: [Geometric Topology](#geometric-topology), [Characteristic class for 4-manifold](#characteristic-class-for-4-manifold), [Geography of 4-manifold](#geography-of-4-manifold).


### Gabai's lightbulb theorem {#gabai-s-lightbulb-theorem}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 15:13]</span></span>
Given \\(F \hookrightarrow X\\), we say an embedded sphere \\(\Sigma \hookrightarrow X\\) is a **geometric dual** of \\(F\\) if \\(\Sigma \cdot \Sigma = 0\\) and \\(F \pitchfork \Sigma = \\{pt\\}\\). And \\(F\\) is **\\(\Sigma\\)-essential** if \\(\pi\_{1}(F \backslash \Sigma) \to \pi\_{1}(X \backslash \Sigma)\\) is trivial. The **Gabai's lightbulb theorem** states

{{% theorem %}}
1.  Given any \\(S^{2} \hookrightarrow S^{2} \times S^{2}\\) with \\(S^{2} \pitchfork (\* \times S^{2}) = \\{pt\\}\\). Then \\(S^{2} \cong\_{diff} S^{2} \times \\{\*\\}\\).
2.  Given any \\(F\_{1}, F\_{2} \hookrightarrow X\\) with \\(\pi\_{1}(X)\\) no \\(2\\)-torsion. Suppose there exists a common geometric dual for \\(F\_{i}\\) and \\(F\_{1}, F\_{2}\\) both \\(\Sigma\\)-essential. Then \\(F\_{1} \cong\_{diff} F\_{2}\\).
{{% /theorem %}}


### Geography of 4-manifold {#geography-of-4-manifold}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:33]</span></span>
By [Freedman's classification of topological 4-manifold](#freedman-s-classification-of-topological-4-manifold), the **geography of \\(4\\)-manifold** is the question which triple \\((c, \chi\_{h}, t)\\) can be realized as smooth, [Irreducible](#irreducible), simply connected \\(X\\).

The following conjecture relates the irreduciblity of \\(4\\)-manifold and [Holomorphic Euler number](#holomorphic-euler-number).

{{% conjecture %}}
For irreducible \\(X\\), \\(\chi\_{h}(X)\\) or \\(\chi\_{h}(\bar{X})\\) must be integer.
{{% /conjecture %}}

Also, we have following theorem.

{{% theorem %}}
\\(\chi\_{h}(X) \in \ZZ\\) if and only if \\(X\\) has an almost complex structure.
{{% /theorem %}}

For complex geography problem, we have inequalities for surface of general type, Bogomolov-Miyaoka-Yau inequality\\(c \leq 9 \chi\_{h}\\) and Noether inequality \\(c \geq 2 \chi\_{h} - 6\\). If \\(X\\) is minimal, simply conected then \\(X \cong\_{diff} \CC P^{2}\\) or \\(X \cong\_{diff} S^{2} \times S^{2}\\). If \\(X\\) is elliptic, then \\(c = 0\\). The currenst status of complex geography problem is in following diagram.

{{< figure src="/img/2021-10-15_19-44-48_screenshot.png" >}}

The current status of smooth geography problem is deduced from complex case by rational blow down.

{{< figure src="/img/2021-10-15_19-46-40_screenshot.png" >}}

{{% remark %}}
However, the smooth simply connected case with \\(c \geq 9 X\_{h}\\) or \\(c < 0\\) is completely unknown.
{{% /remark %}}

The current status of symplectic geography problem is in following picture.

{{< figure src="/img/2021-10-15_19-49-46_screenshot.png" >}}

The \\(c < 0\\) case is deleted by the theorem of Taubes.

{{% theorem %}}
If \\(X\\) is minimal symplectic with \\(\pi\_{1}(X) = 1\\), then \\(c \geq 0\\).
{{% /theorem %}}

There exists symplectic BMY conjecture.

{{% conjecture %}}
Let \\(X\\) be a simply connected, symplectic \\(4\\)-manifold, then \\(c(X) \leq 9 \chi\_{h}(X)\\).
{{% /conjecture %}}


### Geometric tangle {#geometric-tangle}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 18:02]</span></span>
A **geometric tangle** is an embedding of \\([0, 1]^{\coprod k} \coprod (S^{1})^{\coprod m}\\) into \\(\RR^{2} \times [0,1]\\) such that images of endpoints of intervals are on \\(\RR^{2} \times \\{0\\}\\) and \\(\RR^{2} \times \\{1\\}\\), intersection of intervals is transversal to the planes and images of cirvles are strictly inside of \\(\RR^{2} \times [0,1]\\).

A **based tangle** is the regular isotopy class, preserving boundary points of a geometric tangle. And a **standardized tangle** is a based tangle with endpoints being in a line \\(\RR \subset \RR^{2}\\).


### <span class="org-todo todo TODO">TODO</span> Handle decomposition {#handle-decomposition}



Referenced: [Monotone](#monotone), [Handle move](#handle-move), [Morse complex](#morse-complex), [Morse theory](#morse-theory).


#### Monotone {#monotone}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 15:49]</span></span>
A [Handle decomposition](#handle-decomposition) \\(X\_{0}| \cdots | X\_{k}\\) is called **monotone** if \\(X\_{i}\\) only consists of \\(i\\)-handles for all \\(i\\).

{{% proposition %}}
Any manifold has a monotone handle decomposition.
{{% /proposition %}}

{{% corollary %}}
Every manifold has a self-indexed Morse function.
{{% /corollary %}}

Cf. [Self-indexed](#self-indexed) [Morse function](#morse-function).

Referenced: [Handle move](#handle-move), [Morse complex](#morse-complex).


### <span class="org-todo todo TODO">TODO</span> Handle move {#handle-move}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 16:44]</span></span>
Any two [Monotone](#monotone) [Handle decomposition](#handle-decomposition) of \\(X\\) are related by the following handle moves

-   handle slide
-   creation / cancellation


### h-Cobordism {#h-cobordism}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 18:42]</span></span>
With the same notation as in [Corbordism](#corbordism), we say that \\(W\\) is **h-cobordism** if \\(M\_{0} \hookrightarrow W\\) and \\(M\_{1} \hookrightarrow M\\) are all homotopy equivalences.

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

Referenced: [Botany problem of 4-manifold](#botany-problem-of-4-manifold), [Poincarè conjecutre](#poincarè-conjecutre), [Wall Theorem](#wall-theorem).


### Heegaard diagram {#heegaard-diagram}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:03]</span></span>
A genus \\(g\\) **Heegaard diagram** is \\((\Sigma\_{g}, \alpha\_{1}, \cdots, \alpha\_{g}, \beta\_{1}, \cdots, \beta\_{g})\\) consists of a genus \\(g\\) [Orientable](#orientable) surface \\(\Sigma\_{g}\\), two families of simple closed curves \\(\alpha\_{\* }\\), \\(\beta\_{\* }\\) such that \\(\alpha\_{i} \cap \alpha\_{j} = \beta\_{i} \cap \beta\_{j} = 0 \\) for \\(i \neq j\\) and \\(\Sigma\_{g} - \coprod \alpha\_{i}, \Sigma\_{g} - \coprod \beta\_{i}\\) are both connected.

Cf. [Heegaard splitting](#heegaard-splitting).

Referenced: [Trisection diagram](#trisection-diagram).


### Heegaard splitting {#heegaard-splitting}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:03]</span></span>
A genus \\(g\\) **Heegaard splitting** of \\(3\\)-manifold is a decomposition of \\(Y\\) into two genus \\(g\\) handle bodies.

Referenced: [Heegaard diagram](#heegaard-diagram).


### Hessian {#hessian}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 15:21]</span></span>
The **Hessian** is the well-defined map \\({\rm Hess} f\_{p}: T\_{p}X \otimes T\_{p}X \to \RR\\) defined by \\(\left(\frac{\partial^{2}f}{\partial x\_{i} \partial x\_{j}}\right)\\).

Referenced: [Non-degenerate](#non-degenerate).


### Holomorphic Euler number {#holomorphic-euler-number}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:26]</span></span>
We define the **holomorphic Euler number** by \\(\chi\_{h}(X) = \frac{\chi(X) + \sigma(X)}{4}\\).

Referenced: [Freedman's classification of topological 4-manifold](#freedman-s-classification-of-topological-4-manifold), [Geography of 4-manifold](#geography-of-4-manifold).


### Homotopic slice {#homotopic-slice}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-05 Sun 17:34]</span></span>
A [Knot](#knot) \\(K \subset S^{3}\\) is called **homotopy slice** if \\(K\\) bounds a smooth \\(i:D^{2} \hookrightarrow X\\) with \\(\partial X = S^{3}\\) such that \\(i\\) is homotopic to \\(i': D^{2} \to \partial X\\) relative to \\(\partial D^{2} = K\\).

Kronheimer and Mrowka has the following conjecture.

{{% conjecture %}}
\\(K\\) is homotopy slice then the Rasmuusen invariant \\(s(K) = 0\\).
{{% /conjecture %}}

Cf. [Rasmussen invariant](#rasmussen-invariant).

The above conjecture is proved for \\(X = \CC P^{2}\\).


### Index {#index}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 15:54]</span></span>
See [Non-degenerate](#non-degenerate).

Referenced: [Morse inequality](#morse-inequality).


### Integer homology 3-sphere {#integer-homology-3-sphere}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:05]</span></span>
The **integer homology 3-sphere** is a \\(3\\)-manifold \\(Y\\) with \\(H\_{1}(Y; \ZZ) = 0\\).

Freedman proved following result.

{{% theorem %}}
Any integer homology \\(3\\)-sphere bounds a contractible topological \\(4\\)-manifold.
{{% /theorem %}}

Cf. [Contractible](#contractible).


### Intersection forms {#intersection-forms}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-17 Fri 21:48]</span></span>
For \\(4\\)-manifold, we have nondegenerated bilinear form
\\[Q\_{X}: H^{2}(X; \ZZ)/(tors) \times H^{2}(X; \ZZ)/(tors) \to \ZZ\\]
defined by \\((\alpha \cup \beta)[X]\\) called **intersection form**. It is a symmetric, unimodular form.

As an example of the intersection form, we have the intersection form of K3 surfaces \\(Q\_{X} = 2E\_{8} \oplus 3 \begin{pmatrix} 0 & 1 \\\\\\ 1 & 0 \end{pmatrix}\\)

Cf. [K3 surfaces](#k3-surfaces), [E8](#e8).

We can generalized above intersection form to manifold with boundary. The interesection form is defined on \\(V = \im(H\_{2}(X) \to H\_{2}(X, \partial X))/(torsion)\\). \\(Q\_{X}(i\_{\* }(\alpha), i\_{\* }(\beta)) = (\pd(\alpha) \cap \pd(\beta)) \cdot [X]\\).

For a manifold with boundary, the intersection form is still nondegenerate but not necessarily unimodular. In fact, we have the following proposition

{{% proposition %}}
Given any symmetric \\(Q\\) with \\(\det(Q) \neq 0\\), there exists a simply connected \\(4\\)-manifold \\(X\\) such that \\(Q\_{X} = Q\\) and \\(\abs{\det(Q)} = \abs{H\_{1}(\partial X)}\\).
{{% /proposition %}}

Referenced: [Lefschetz fixed point theorem](#lefschetz-fixed-point-theorem), [Donaldson diagonalizable theorem](#donaldson-diagonalizable-theorem), [Freedman's classification of topological 4-manifold](#freedman-s-classification-of-topological-4-manifold), [Signature](#signature).


### Irreducible {#irreducible}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:22]</span></span>
A simply connected, closed, oriented \\(4\\)-manifold \\(X\\) is **irreducible** if \\(X \not \cong\_{diff} X\_{0} \shar X\_{1}\\) with \\(X\_{0}, X\_{1} \not \cong S^{4}\\).

Referenced: [Geography of 4-manifold](#geography-of-4-manifold), [Seiberg-Witten invariant](#seiberg-witten-invariant).


### <span class="org-todo todo TODO">TODO</span> Jones polynomial {#jones-polynomial}


### <span class="org-todo todo TODO">TODO</span> Khovanov homology {#khovanov-homology}



Referenced: [Lee homology](#lee-homology).


### <span class="org-todo todo TODO">TODO</span> Kirby calculus {#kirby-calculus}


### <span class="org-todo todo TODO">TODO</span> Kirby move {#kirby-move}


### Kirby-Sieberman invariant {#kirby-sieberman-invariant}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-17 Fri 22:00]</span></span>
We define the set \\({\rm Top}\_{m} = \\{\text{ homomorphism } f: \RR^{m} \to \RR^{m} \text{ such that } f(0) = 0\\}\\). And \\({\rm PL}\_{m} = \\{\text{ piecewise linear homeomorphism} f: \RR^{m} \to \RR^{m} \text{ such that } f(0) = 0\\}\\).

The Kirby and Sieberman has following deep and mysterious theorem.

{{% theorem %}}
For \\(m \geq 5\\), \\(k < m\\). Then \\(\pi\_{k}({\rm Top}\_{m}/ {\rm PL}\_{m}) = \begin{cases} 0 & k \neq 3 \\\\\\ \ZZ/2 & k = 3 \end{cases}\\).
{{% /theorem %}}

So to have PL structure on \\(X\\), \\(\dim X \geq 5\\) we need to overcome the obstruction called **Kirby-Sieberman** invariant \\(KS(X) \in H^{4}(X; \ZZ/2)\\). So \\(X\\) has a PL-structure then \\(\ks(X) = 0\\). And for \\(\dim X = 4\\), \\(\ks(X) = 0\\) if and only \\(X \times \RR\\) has a PL-structure.

{{% remark %}}
For \\(\dim X \leq 7\\), we have existence of piecewise linear structure equivalent to existence of smooth structure.
{{% /remark %}}

Referenced: [Freedman's classification of topological 4-manifold](#freedman-s-classification-of-topological-4-manifold).


### <span class="org-todo todo TODO">TODO</span> Knizhnik–Zamolodchikov equation {#knizhnik-zamolodchikov-equation}


### Knots bounds algebraic surface {#knots-bounds-algebraic-surface}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:45]</span></span>
By [Seiberg-Witten invariant](#seiberg-witten-invariant), it is natural to ask when a [Knot](#knot) bounds an algebraic surface. The answer is the following theorem.

{{% theorem %}}
A knot \\(K\\) arises as \\(K = S \pitchfork \partial D^{4}\\) for some affine algebraic curve \\(S \subset \CC^{2}\\) if and only if \\(K\\) is quasi-positive. Moreover, suppose \\(K = \bar{b}\\), where
\\[b = \prod\_{k = 1}^{m} w\_{k} \sigma\_{i\_{k}} w^{-1}\_{k}\\]
Then we can find \\(S\\) with \\(g(S \cap D^{4}) = \frac{m - n + 1}{2}\\), and therefore \\(g\_{S}(K) = \frac{m - n + 1}{2}\\).
{{% /theorem %}}

Cf. [Quasi-positive](#quasi-positive), [Slice genus](#slice-genus).

For [Positive](#positive) knot, we have \\(U\_{K} = g\_{S}(K)\\) which is not true for quasi-positive knot.


### <span class="org-todo todo TODO">TODO</span> Lee homology {#lee-homology}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:33]</span></span>
Cf. [Khovanov homology](#khovanov-homology).

Referenced: [Rasmussen invariant](#rasmussen-invariant).


### Lefschetz hyperplane theorem {#lefschetz-hyperplane-theorem}



{{% theorem %}}
Let \\(X\\) be a hypersurface in \\(\CC \PP^{n}\\) defined by a single polynomial, then \\(X \to \CC P^{n}\\) induces isomorphism on \\(\pi\_{k}(-)\\) if \\(k < n - 1\\).
{{% /theorem %}}

{{% corollary %}}
The hypersurface in \\(\CC P^{3}\\) is simply connected.
{{% /corollary %}}


### Lickorish-Wallace theorem {#lickorish-wallace-theorem}



{{% theorem %}}
Every closed orientable connected \\(3\\)-manifold can be obtained from a surgery on a link with coefficient \\(\pm 1\\).
{{% /theorem %}}

Cf. [Link](#link), [Orientation](#orientation), [Surgery](#surgery).


### Linking number {#linking-number}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 13:41]</span></span>
Let \\(K\_{1}, K\_{2}\\) be [Oriented](#oriented) [Knots](#knot) in \\(S^{3}\\). We define the **linking number** \\(lK(K\_{1}, K\_{2}) \in \ZZ\\) by
\\[[K\_{2}] = lK(K\_{1}, K\_{2})[m\_{1}] \in H\_{1}(S^{3} \backslash K\_{1}) \cong \ZZ\\]
where \\(m\_{1}\\) is the meridian of \\(K\_{1}\\). The following is a sketch graph of meridian.

{{< figure src="/img/2021-10-08_13-43-37_screenshot.png" >}}

An alternative definition is consider \\(\Sigma\_{1}\\) [Seifert surface](#seifert-surface) of \\(K\_{1}\\) and then define \\(lK(K\_{1}, K\_{2}) = \Sigma\_{2} \cdot K\_{1}\\). Or we consider embeddings \\(\Sigma\_{1} \to D^{4}\\), \\(\Sigma\_{2} \to D^{4}\\) such that \\(\partial \Sigma\_{1} = K\_{1}\\), \\(\partial \Sigma\_{2} = K\_{2}\\) and define \\(lK(K\_{1}, K\_{2}) = K\_{1} \cdot K\_{2}\\).


### <span class="org-todo todo TODO">TODO</span> Mazur manifold {#mazur-manifold}


### Milnor conjecture (theorem) {#milnor-conjecture--theorem}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:24]</span></span>
The **Milnor conjecture** is the following. (now a theorem)

{{% theorem %}}
For \\(T\_{p,q}\\) the \\((p,q)\\)-torus knot, we have
\\[g\_{S}(T\_{p,q}) = \frac{(p - 1)(q - 1)}{2}\\]
{{% /theorem %}}

One can use [local Thom conjecture (theorem)](#thom-conjecture--theorem) to prove.


### Morse complex {#morse-complex}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 16:38]</span></span>
Now we consider the complex constructed from Morse theory. We have \\(X = X\_{0} | X\_{1} | \cdots | X\_{n}\\) [Monotone](#monotone). And for \\(H\_{k} \subset X\_{k}\\) and \\(H\_{k + 1} \subset X\_{k + 1}\\), we define the pairing \\(\langle H\_{k}, H\_{k + 1}\rangle\\) the intersection number of the belt sphere of \\(H\_{k}\\) and attaching sphere of \\(H\_{k + 1}\\). Then we have **Morse complex** \\(C\_{k}^{n}(X) = \ZZ \langle H\_{k}^{1}, \cdots, H\_{k}^{a\_{k}}\rangle\\) and define the differential to be
\\[\dif H\_{k}^{i} = \sum\_{j} \langle H\_{k - 1}^{j}, H\_{k}^{i}\rangle H\_{k - 1}^{j}\\]
We have that \\(\dif^{2} = 0\\).

Cf. [Handle decomposition](#handle-decomposition).

Referenced: [Morse inequality](#morse-inequality).


### Morse function {#morse-function}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 15:39]</span></span>
A **Morse function** is a funciton if all critical points are non-degenerate. If the origin manifold \\(X\\) has boundary, then \\(f^{-1}(\max f) = \partial X\\).

Referenced: [Monotone](#monotone), [Self-indexed](#self-indexed).


#### Self-indexed {#self-indexed}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 15:54]</span></span>
A [Morse function](#morse-function) is called **self-indexed** if for all \\(x \in {\rm crit}(f)\\), we have \\(f(x) = {\rm index}(x)\\).

Referenced: [Monotone](#monotone).


### Morse inequality {#morse-inequality}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 16:41]</span></span>
From [Morse complex](#morse-complex), we have that

{{% theorem %}}
For any \\(0 \leq k \leq  \dim(X)\\), we have that
\\[\sum\_{0 \leq i \leq k}(-1)^{k - i}b\_{i}(X) \leq \sum\_{0 \leq i \leq k} (-1)^{k - i} \abs{{\rm crit}\_{i}(f)}\\]
{{% /theorem %}}

{{% corollary %}}
Suppose all critical points of \\(f\\) have even indices, then \\(b\_{2k}(X) = \abs{{\rm crit}\_{2k}(f)}\\).
{{% /corollary %}}

Cf. [Critical point](#critical-point), [Index](#index).


### Morse theory {#morse-theory}

Let \\(f\\) be a smooth real valued function on manifold M. Let \\(a < b\\) and
suppose that the set \\(f^{-1}[a,b]\\) is **compact** and contain no critical points
of \\(f\\). Then \\(M^{a}\\) is diffeomorphic to \\(M^{b}\\). Furthermore, \\(M^{a}\\)
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
equivalence \\(k:X \cup\_{\phi\_{0}} e^{\lambda} \to X \cap\_{\phi\_{1}} e^{\lambda}\\).
{{% /theorem %}}

{{% proof %}}
\begin{align} k(x) = x && x \in X \\\\\\ k(tu) = 2tu && 0 \leq t \leq 1/2 \\\\\\ k(tu) = \phi\_{2-2t}(u) && 1/2 \leq t \leq 1 \end{align}
{{% /proof %}}

{{% lemma %}}
Let \\(\phi:\dot{e^{\lambda}} \to X\\) be an attaching map. Any homotopy
equivalence \\(f:X \to Y\\) extends to a homotopy equivalence \\(F:X \cup\_{\phi}e^{\lambda} \to Y \cup\_{f\phi}e^{\lambda}\\)
{{% /lemma %}}

Given a Morse function, we have a [Handle decomposition](#handle-decomposition).

{{% theorem %}}
Suppose \\(f^{-1}( r) \cap {\rm crit}(f) = \\{x\_{1}, \cdots, x\_{l}\\}\\). Let \\(a\_{i} = {\rm index}(x\_{i})\\). Then for \\(\epsilon > 0\\) small enough, we have
\\[X\_{\leq r + \epsilon} = X\_{\leq r - \epsilon} \cup (H\_{a\_{1}} \coprod H\_{a\_{2}}) \cdots \coprod H\_{a\_{l}}\\]
where \\(H\_{i}\\) is the \\(i\\)-handle.
{{% /theorem %}}


### Poincarè conjecutre {#poincarè-conjecutre}



We have following **generalized Poincarè conjecture** which is proved by various people in various dimensions.

{{% theorem %}}
Let \\(M\\) be a \\(n\\)-dimensional topological manifold homootpy equivalent to \\(S^{n}\\). Then \\(M \cong\_{top} S^{n}\\).
{{% /theorem %}}

For \\(n \geq 6\\), we can give a proof by [h-Cobordism](#h-cobordism).

However, the smooth structure on \\(S^{n}\\) may not be unique. \\(S^{2k + 1}\\) has unique smooth structure if and only if \\(2k + 1 = 1,3,5,61\\).

The dimension \\(4\\) smooth Poincaré conjecture is still open. A possible approach is suggested by Freedman-Gompf-Morrison-Walker using [Knot](#knot) on \\(S^{4}\\) to do some surgery and making contradiction.


### <span class="org-todo todo TODO">TODO</span> Rasmussen invariant {#rasmussen-invariant}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:33]</span></span>
Cf. [Lee homology](#lee-homology).

Referenced: [Homotopic slice](#homotopic-slice), [Slice genus](#slice-genus).


### <span class="org-todo todo TODO">TODO</span> Rational blow down {#rational-blow-down}


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


### Regular value {#regular-value}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 15:18]</span></span>
See [Critical value](#critical-value).


### Rokhlin Theorem {#rokhlin-theorem}



{{% theorem %}}
Let \\(X\\) be a smooth spin \\(4\\)-[Manifold](#manifold). Then \\(16 | \sigma(X)\\).
{{% /theorem %}}

Cf. [Signature](#signature).

Referenced: [Geometric Topology](#geometric-topology).


### Seiberg-Witten equation {#seiberg-witten-equation}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-23 Sat 15:28]</span></span>
The **Seiberg-Witten equation** is the following equations for \\((A, \phi \in \Gamma^{S^{+}})\\)
\\[ \begin{cases}      F\_{A^{\tau}}^{+} - \rho^{-1}(\phi^{\*} \phi)\_{0} = 0 & \\\\\\      \dirac\_{A}^{+} \phi = 0 &    \end{cases} \\]
Here \\((\phi^{\* } \phi)\_{0}: \psi \to \langle \psi, \phi> \cdot \phi - \frac{\abs{\phi}^{2}}{2} \psi\\). We have \\(((\phi^{\* } \phi)\_{0})^{\* } = (\phi^{\* } \phi)\_{0}\\) and \\(\tr (\phi^{\* } \phi)\_{0} = 0\\).

Referenced: [Seiberg-Witten moduli space](#seiberg-witten-moduli-space).


### Seiberg-Witten invariant {#seiberg-witten-invariant}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-23 Sat 15:51]</span></span>
For simply connected \\(4\\)-manifold \\(X\\), we have a natural \\(S^{1}\\) bundle \\(P\\) on [Seiberg-Witten moduli space](#seiberg-witten-moduli-space) \\(\mathscr{M}\_{SW}\\) coming from the Coulomb guage description. So we define the **Seiberg-Witten invariant** by
\\[SW(X, S) = c\_{1}(P)^{d(S)/2} \cdot [\mathscr{M}\_{SW}] \in \ZZ\\]
where \\(d(S)\\) is the dimension of the Seiberg-Witten moduli space. When \\(d(S)\\) is odd, we simply define the Seiberg-Witten invariant to be \\(0\\).

We have following conjecture for Seiberg-Witten invariants called **simple type conjecture**

{{% conjecture %}}
If \\(d(S) > 0\\), \\(b^{+ } > 1\\), then \\(SW(X, S) = 0\\).
{{% /conjecture %}}

The symplectic case is proved by Taubes.

{{% theorem %}}
The simple type conjecture holds for symplectic manifolds.
{{% /theorem %}}

Let \\(\Char(X)\\) denote the set \\(\\{K \in H^{2}(X; \ZZ) \mid K \cdot [\Sigma] = \Sigma \cdot \Sigma \pmod 2\\}\\), and we define the \\(SW\\) as a map
\\[SW(\alpha) = \sum\_{S \in \Spin^{\CC}(X), c\_{1}(S) = K} SW(X, S)\\]
The Seilberg-Witten invariants have following properties:

1.  \\(SW\_{X}(K) = 0\\)  for all but finitely many \\(K \in \text{char}(X)\\). Those \\(K\\) are called **basic classes**.
2.  If \\(X\\) has postive scalar curvature, then \\(SW\_{X}(K) = 0\\) for every \\(K\\).
3.  \\(SW\_{X}(-K) = (-1)^{b\_{2}^{+}(X) - b\_{1}(X) + 1} SW\_{X}(K)\\).
4.  If \\(X \cong\_{diff} X\_{1} \shar X\_{2}\\) with \\(b\_{2}^{+}(X\_{1}), b\_{2}^{+}(X\_{2}) > 0\\), then \\(SW\_{X}(K) = 0\\) for every \\(K\\).
5.  Blow-up formula: If \\(X \cong\_{diff} X' \shar \overline{\CC P}^{2}\\), then basic classes of \\(X\\) are \\(\\{K \pm \pd E \mid K \text{ is a basic class of } X'\\}\\). Moreover, \\(SW\_{X}(K \pm \pd E) = SW\_{X'}(K)\\).
6.  If \\(X\\) is an algebraic surface, then \\(SW\_{X}(c\_{1}(TX)) = \pm 1\\). (Witten)
7.  If \\(X\\) is symplectic, and \\(J\\) compatible almost complex structure, then \\(SW\_{X}(c\_{1}(TX, J)) = \pm 1\\). (Taubes)
8.  Adjunction inequality. (See below)

As an application of Taubes result on symplectic \\(4\\)-manifold, we consider the following corollary.

{{% corollary %}}
If \\(X\\) is symplectic, and \\(X \cong\_{diff} X\_{1} \shar X\_{2}\\). Then \\(b\_{2}^{+}(X\_{1})\\) or \\(b\_{2}^{+}(X\_{2})\\) must be \\(0\\).
{{% /corollary %}}

Some more works show the following theorem by Kotschick, Taubes.

{{% theorem %}}
Let \\(X\\) be a simply connected, symplectic \\(4\\)-manifold. Then \\(X\\) is minimal if and only if \\(X\\) is irreducible.
{{% /theorem %}}

Cf. [Irreducible](#irreducible).

We state the adjunction inequality by Kronheimer-Mrowka, Ozsrath-Szabo, Fintushel-Stern.

{{% theorem %}}
Let \\(\Sigma \to X\\) be a smoothly embedded essential surface (\\([\Sigma] \neq 0\\)), where \\(b^{+}\_{2}(X) > 1\\) and \\(S \in \Spin^{\CC}(X)\\) such that \\(SW\_{X}(S) \neq 0\\). Then we have

1.  If \\(\Sigma \cdot \Sigma \geq 0\\), then
    \\[2g(\Sigma) - 2 \geq \Sigma \cdot \Sigma + \abs{c\_{1}(S) \cdot [\Sigma]}\\]
2.  Assume \\(X\\) is simple type, then same results holds even if \\(\Sigma \cdot \Sigma < 0\\).
{{% /theorem %}}

Since the symplectic \\(4\\)-manifold is simple type, so we can deduce the following symplectic Thom conjecture.

{{% theorem %}}
Let \\((X, \omega)\\) be a symplectic \\(4\\)-manifold. Let \\(\Sigma \stackrel{i}{\hookrightarrow} X\\) be a symplectic surface, that is \\(i^{\*}(\omega)\\) is nowhere vanishing on \\(\Sigma\\). Then \\(\Sigma\\) is genus minimizing in its homology class.
{{% /theorem %}}

{{% remark %}}
To apply the above theorem, we have a priori known a symplectic surface. Because not all homology class can be represented by a simplectic surface. There are two major obstructions: first, the symplectic area; second, the adjunction formula in Seiberg-Witten theory. However, you can always find immersed symplectic surface representing a homology class if the symplectic area is positive; and if \\(\dim X \geq 6\\), then you can make the surface embedded. Again, \\(4\\) is the critical dimension.
{{% /remark %}}

Referenced: [Geometric Topology](#geometric-topology), [Donaldson diagonalizable theorem](#donaldson-diagonalizable-theorem), [Fintushel-Stern knot surgery](#fintushel-stern-knot-surgery), [Knots bounds algebraic surface](#knots-bounds-algebraic-surface), [Thom conjecture (theorem)](#thom-conjecture--theorem).


### Seiberg-Witten moduli space {#seiberg-witten-moduli-space}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-23 Sat 15:35]</span></span>
By [Seiberg-Witten equation](#seiberg-witten-equation), the solution forms **Seiberg-Witten moduli space**,
\\[\mathscr{M}\_{SW} = \\{\text{Seiberg-Witten solutions}\\}/ \mathscr{G}\\]
where \\(\mathscr{G} = \Gamma(X, \End(S^{+}, \rho)) = C^{\infty}(X, U(1))\\) acts on \\(\\{(A, \phi)\\}\\) by \\(u \cdot (A, \phi) = (A - u^{-1} \dif u, u \cdot \phi)\\).

Or we can formulate in another way by fixed the **Coulomb gauge** with respect ot a base [Spin^C connection](#spin-c-connection) \\(A\_{0}\\) by setting \\(\dif^{\* }(A - A\_{0}) = 0\\).
\\[\mathscr{M}\_{SW} = \\{\text{Coulomb gauge Seiberg-Witten solutions}\\}/ \mathscr{G}\_{h}\\]
where \\(\mathscr{G}\_{h} = \\{\text{harmonic map }X \to S^{1}\\} \cong H^{1}(X; \ZZ) \times S^{1}\\).

The following result is important and <span class="underline">magic</span> by Clifford Taubes.

{{% theorem %}}
\\(\mathscr{M}\_{SW}\\) is compact.
{{% /theorem %}}

The proof relies on the estimate of the \\(\abs{\phi}\\) and elliptic boosting technique for elliptic partial differential equations.

However, in general the moduli space is not a manifold, but in \\(b^{+ }\_{2} > 0\\) case, by perturbing the equation a little, we can get an [Oriented](#oriented) manifold of dimension \\(\frac{c\_{1}(S)^{2} - \sigma(X)}{4} + b^{1}(X) - b\_{2}^{+}(X)\\). The result depend on Sard-Smale theorem which is an analog of [Sard theorem](#sard-theorem) in infinite dimensional case. For \\(b^{ +} > 1\\), all such moduli space is equivalent, but in \\(b\_{2}^{ +} = 1\\) case, we have \\(2\\) choices.

Referenced: [Seiberg-Witten invariant](#seiberg-witten-invariant).


### Seifert genus {#seifert-genus}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 13:37]</span></span>
See [Seifert surface](#seifert-surface).

Referenced: [Thom conjecture (theorem)](#thom-conjecture--theorem).


### Seifert surface {#seifert-surface}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 13:35]</span></span>
For any [Oriented](#oriented) [Link](#link) \\(L \to S^{3}\\), there exists an embedded orientable surface \\(\Sigma \to S^{3}\\) with \\(\partial \Sigma = L\\). Such surface is called **Seifert surface**.

The **Seifert genus** \\(g(K)\\) is the minimal genus of Seifert surface. The **slice genus** \\(g\_{S}(K)\\) is the minimal genus of orientable \\(\Sigma \to D^{4}\\) with \\(\partial \Sigma = K\\).

Obviously, we have \\(g\_{S}(K) \leq g(K)\\).

Referenced: [Linking number](#linking-number), [Seifert genus](#seifert-genus), [Slice genus](#slice-genus).


### Self-dual {#self-dual}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 20:21]</span></span>
A \\(n\\)-form \\(w\\) on \\(2n\\) manifold is called **self-dual** if \\(\* w = w\\).

Any \\(n\\)-form can be decomposed to a sum of self-dual part and [Anti-self-dual](#anti-self-dual) part.

Referenced: [Anti-self-dual](#anti-self-dual), [Dirac operator](#dirac-operator).


### Signature {#signature}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-17 Fri 21:50]</span></span>
For [Intersection forms](#intersection-forms) \\(Q\_{X}\\), we have \\(b^{+ }(X)/b^{- }(X)\\) denote the number of the positive and negative eigenvalues of \\(Q\_{X}\\). And we define the **signature** to be \\(\sigma(X) = b^{+ }(X) - b\_{2}^{-}(X)\\).

Referenced: [Characteristic class for 4-manifold](#characteristic-class-for-4-manifold), [Freedman's classification of topological 4-manifold](#freedman-s-classification-of-topological-4-manifold), [Rokhlin Theorem](#rokhlin-theorem).


### Slice genus {#slice-genus}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 13:40]</span></span>
See [Seifert surface](#seifert-surface).

The slice genus is bounded below by [Rasmussen invariant](#rasmussen-invariant).

Referenced: [Clasp number](#clasp-number), [Knots bounds algebraic surface](#knots-bounds-algebraic-surface), [Slice ribbon conjecture](#slice-ribbon-conjecture).


### Slice ribbon conjecture {#slice-ribbon-conjecture}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:33]</span></span>
We say a knot \\(K\\) is **slice** if \\(g\_{S}(K) = 0\\) ([Slice genus](#slice-genus)). And say \\(K\\) is **ribbon** if \\(K\\) bounds immersed \\(D^{2} \subset S^{3}\\) such that self intersection of \\(D^{2} = \coprod \text{arcs}\\). We know that ribbon is a slice, the conjecture is the converse also holds.

{{% conjecture %}}
Any slice knot is ribbon.
{{% /conjecture %}}


### Smale conjecture {#smale-conjecture}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-05 Sun 17:34]</span></span>
The **Smale conjecture** for dimension \\(n\\) means

{{% conjecture %}}
The map \\(O(n + 1) \to {\rm Diff}(S^{n})\\) is homotopy equivalence.
{{% /conjecture %}}

The conjecture is true for \\(n \leq 3\\) and false for \\(n \geq 4\\). The last case \\(n = 4\\) was proved in around 2018.


### Spin^C connection {#spin-c-connection}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-23 Sat 15:15]</span></span>
A **unitary** connection \\(A\\) on \\(S\\) is **spin\\(^{\CC}\\) connection** if
\\[\nabla\_{A}(\rho(v) \cdot s) = \rho(v) \cdot \nabla\_{A} s + \rho(\nabla\_{LC} v) \cdot s\\]
for every \\(v \in \Gamma(T\_{\* }X), s \in \Gamma(s)\\). Here \\(\nabla\_{LC}\\) is the Levi-Civita connection which relies on [Riemannian metric](#riemannian-metric).

Referenced: [Dirac operator](#dirac-operator), [Seiberg-Witten moduli space](#seiberg-witten-moduli-space).


### Spin^C structure {#spin-c-structure}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 20:16]</span></span>
A **Spin\\(^{\CC}\\) structure** on \\(X\\) is a Hermitian bundle \\(S \to X\\) with bundle map \\(\rho: T\_{\* }X \to \End(S)\\) such that for all \\(x\\), \\(\rho\_{x}: T\_{x}X \to \End(S\_{x})\\) is an irreducible [Clifford module](#clifford-module). Consider \\(\pi = \rho(e\_{1} \cdots e\_{n})\\), we have \\(\pi^{2} = -1\\). So \\(S = S^{+} \oplus S^{-}\\) by \\(\pi\\) action.

Spin\\(^{\CC}\\) structure is useful in \\(4\\)-manifold by following theorem.

{{% theorem %}}
Any \\(4\\)-manifold has a spin\\(^{\CC}\\) structure.
{{% /theorem %}}

which result from the following proposition

{{% proposition %}}
A \\(n\\)-dimensional manifold \\(X\\) has a spin\\(^{\CC}\\) structure if and only if \\(w\_{2}(TX) \in \im(H^{2}(X; \ZZ) \to H^{2}(X; \ZZ/2))\\).
{{% /proposition %}}

Cf. [Stiefel-Whitney class](#stiefel-whitney-class).


### Spin structure {#spin-structure}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-17 Fri 22:16]</span></span>
Let \\(\SO(n) \to {\rm Fr} \to X\\) be the frame bundle of a smooth [Manifold](#manifold). A **spin structure** is a lift of \\({\rm Fr}\\) to a \\(\Spin(n)\\) bundle.

We have following lemma on the existence of spin structure.

{{% lemma %}}
\\(X\\) has a spin strucutre if and only if the second Stiefel-Whitney class \\(\omega\_{2}(X) = 0\\). Furthermore, when \\(\dim X = 4\\) and \\(\pi\_{1} = 1\\), \\(X\\) has a spin structure if and only if \\(Q\_{X}\\) is even.
{{% /lemma %}}


### <span class="org-todo todo TODO">TODO</span> Surgery {#surgery}



Referenced: [Lickorish-Wallace theorem](#lickorish-wallace-theorem).


### Tangle {#tangle}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 18:02]</span></span>
A **tangle** is the regular isotopy class of a standardized [Tangle](#tangle) with respect to deformation of endpoints.

Referenced: [Tangle](#tangle).


### Thom conjecture (theorem) {#thom-conjecture--theorem}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:24]</span></span>
The **Thom conjecture** is the following, now a theorem.

{{% theorem %}}
For \\(X = \CC P^{2}\\) and \\(d > 0\\), we have
\\[\min \\{g(\Sigma) \mid \Sigma \hookrightarrow X, [\Sigma] = d \pd (\CC P^{1})\\} = \frac{(d - 1)(d - 2)}{2}\\]
{{% /theorem %}}

Cf. [Seiberg-Witten invariant](#seiberg-witten-invariant), [Seifert genus](#seifert-genus).

The following corolloary called **local Thom conjecture** is useful.

{{% corollary %}}
Let \\(\Sigma \hookrightarrow \CC^{2}\\) be an affine, smooth algebraic curve. Then \\(\Sigma\\) is locally genus miminizing, that is, for all \\(D^{4} \in \CC^{2}, S \hookrightarrow D^{4}\\) such that \\(\partial D^{4} \pitchfork \Sigma = K\\) and \\(\partial S = K\\), we have \\(g(S) \geq g(\Sigma \cap D^{4})\\).
{{% /corollary %}}

Referenced: [Milnor conjecture (theorem)](#milnor-conjecture--theorem).


### Trisection {#trisection}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:03]</span></span>
Let \\(X\\) be a closed smooth [Oriented](#oriented) connected \\(4\\)-manifold. For \\(0 \leq k \leq g\\), a \\((g, K)\\)- **trisection** of \\(X\\) is a decomposition \\(X = X\_{1} \cap X\_{2} \cap X\_{3}\\) such that

1.  \\(X\_{i} \cong\_{diff} \shar^{k}(S^{1} \times B^{3})\\)
2.  \\((X\_{i} \cap X\_{j}) = H\_{ij} \cong\_{diff} \shar^{g}(S^{1} \times B^{2})\\)
3.  \\(X\_{1} \cap X\_{2} \cap X\_{3} = \Sigma\_{g}\\)

The following theorem of Gay and Kirby shows that trisection exists for any [Orientable](#orientable) \\(4\\)-manifold and unique in some sense.

{{% theorem %}}
1.  Every closed smooth connected oriented \\(4\\)-manifold admits a trisection.
2.  Any two trisection diagrams of \\(X^{4}\\) are related by a sequence of particular moves.
{{% /theorem %}}


### Trisection diagram {#trisection-diagram}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:03]</span></span>
A **trisection diagram** is a set of three curves \\(\\{\alpha\_{i}\\}, \\{\beta\_{i}\\}, \\{\gamma\_{i}\\}\\) on \\(\Sigma\_{g}\\) with \\(1 \leq i \leq g\\) such that any two collection is a [Heegaard diagram](#heegaard-diagram) for \\(\shar^{k}(S^{1} \times S^{2})\\).


### Unknot number {#unknot-number}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:38]</span></span>
Given a [Knot](#knot) \\(K\\), we define the **unknotting number** \\(U(K)\\) the minimal number that a knot [Diagram](#diagram) of \\(K\\) can be made into an unknot.

Referenced: [Clasp number](#clasp-number).


### Wall Theorem {#wall-theorem}



{{% theorem %}}
Let \\(M\_{0}, M\_{1}\\) be simply-connected smooth \\(4\\)-manifold. Suppose \\(M\_{0} \cong\_{homotopy} M\_{1}\\). Then

1.  \\(M\_{0}\\) is smoothly h-cobordant to \\(M\_{1}\\).
2.  For \\(m \geq 0\\), \\(M\_{0} \shar^{m} (S^{2} \times S^{2}) \cong\_{diff} M\_{1} \shar^{m} (S^{2} \times S^{2})\\).
{{% /theorem %}}

{{% remark %}}
All known example show that \\(m = 1\\) is already enough but the proves requires large enough \\(m\\). Is the theorem not strong enough, or our understanding of 4-manifold too shallow?
{{% /remark %}}

{{% remark %}}
The theorem also shows that [h-Cobordism](#h-cobordism) theorem fails for \\(n = 4\\).
{{% /remark %}}


### Whitehead theorem {#whitehead-theorem}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-17 Fri 21:55]</span></span>
The **Whitehead theorem** is of the following form:

{{% theorem %}}
Suppose \\(\pi\_{1}(X\_{1}) = \pi\_{1}(X\_{2}) = 1\\). Then
\\[Q\_{X\_{0}} \cong Q\_{X\_{1}} \Rightarrow X\_{0} \cong\_{homotopy} X\_{1}\\]
{{% /theorem %}}

The proof relies on the following lemma of Hopf.

{{% lemma %}}
\\[\pi\_{3}(S^{2} \vee \cdots \vee S^{2}) \cong \\{n \times n \text{ symmetric matrices with integer coefficient}\\}\\]
The left hand side has \\(n\\) copies of \\(S^{2}\\) and the isomorphism is group homomorphism.
{{% /lemma %}}

Referenced: [Freedman's classification of topological 4-manifold](#freedman-s-classification-of-topological-4-manifold).


## Quantum Fields and Strings {#quantum-fields-and-strings}




### <span class="org-todo todo TODO">TODO</span> Cobordism conjecture {#cobordism-conjecture}


### <span class="org-todo todo TODO">TODO</span> Extended topological quantum field theory {#extended-topological-quantum-field-theory}


### Super algebra {#super-algebra}



A **super algebra** over \\(k\\) is a [Super vector space](#super-vector-space) \\(A\\), with a given morphism \\(A \otimes A \to A\\). \\(A\\) is **associative** if \\((xy)z = x(yz)\\). A **unit** is an even element \\(1\\) such that \\(1 x = x 1 = x\\). \\(A\\) is **commutative** if
\\[xy = (-1)^{p(x)p(y)}yx\\]
for homogeneous elements.

We can define the **module** for algebra \\(A\\). And we make left module right module by
\\[m \cdot a := (-1)^{p(m)p(a)} a \cdot m\\]

We also have **opposite algebra** \\(A^{o}\\) of \\(A\\) by product
\\[x \cdot\_{opp} y = (-1)^{p(x)p(y)}y \cdot x\\]

We can define the tensor product of modules and algebras naturely.


### Super vector space {#super-vector-space}



{{% definition %}}
A **super vector space** is a \\(\ZZ/2 \ZZ\\) graded vector space
\\[V = V\_{0} \oplus V\_{1}\\]
An element \\(v\\) of \\(V\_{0}\\) (resp. \\(V\_{1}\\)) is said to be **even** (resp. **odd**). Its parity in \\(\ZZ / 2 \ZZ\\) is denoted \\(p(a)\\). And **morphism** between super vector spaces is degree presevering linear map.
{{% /definition %}}

We have **parity reversing functor** \\(\Pi\\) such that \\((\Pi V)\_{0} = V\_{1}\\) and \\((\Pi V)\_{1} = V\_{0}\\). Also we use the notation \\(m\_{0} \mid m\_{1}\\) to denote the dimension of \\(V\\) with \\(\dim V\_{0} = m\_{0}\\) and \\(\dim V\_{1} = m\_{1}\\).

The **tensor product** is defined by \\((V \otimes W)\_{k} = \oplus\_{i + j = k} V\_{i} \otimes W\_{j}\\). We define the **commutativity isomorphism**
\\[c\_{V,W}: V \otimes W \to W \otimes V, v \otimes w \to (-1)^{p(v)p(w)} w \otimes v\\]
By above definition, we have the following diagram commutes.

{{< figure src="/img/2021-09-15_19-00-07_screenshot.png" >}}

Referenced: [Super algebra](#super-algebra).


### <span class="org-todo todo TODO">TODO</span> Topological quantum field theory {#topological-quantum-field-theory}


### Chern-Weil theory {#chern-weil-theory}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-13 Mon 19:06]</span></span>
See [Chern class](#chern-class).


### Chern-Simons functional {#chern-simons-functional}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-13 Mon 19:50]</span></span>
For \\(A\\) a connection on \\(SU(2)\\) principal bundle on manifold \\(M\\). We usually denote
\\[CS(A) = \frac{1}{8 \pi^{2}}\int\_{M} \tr(F\_{A} \wedge F\_{A}) \in \RR/\ZZ\\]
called **Chern-Simons functional**, where \\(F\_{A}\\) is the [Curvature](#curvature).

Or on 3-manifold, we define for [Connection](#connection) \\(A\\) (matrix valued 1 form),
\\[CS(A) = \frac{1}{8 \pi^{2}} \int\_{Y} \tr(A \wedge \dif A + \frac{2}{3}A \wedge A \wedge A) \in \RR/\ZZ\\]

Critical poiont of Chern-Simons functional are [Flat](#flat) connections and corresponds to group homomorphism \\(\rho: \pi\_{1}(M) \to SU(2)\\).


### Yang-Mills equation {#yang-mills-equation}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-13 Mon 20:05]</span></span>
Let \\(P\\) be a \\(SU(2)\\) bundle over \\(4\\)-manifold \\(M\\), then we call
\\[F\_{A}^{+} = 0\\]
**Anti-self-dual equation**. The connection satisfying the equation minimizing energy equaiton **Yang-Mills functional**
\\[YM(A) = \int\_{M} \abs{F\_{A}}^{2}\\]
Critical point of Yang-Mills functional is given by **Yang-Mills equation**

\begin{equation\*} \begin{cases} d^{\*}\_{A}F\_{A} = 0 & \\\\\\ d\_{A} F\_{A} = 0 & \end{cases} \end{equation\*}

The second equation is Bianchi identity (Cf. [Curvature](#curvature)) and is automatically satisfied. In fact, solutions of anti-self-dual equation is a special solutions of the Yang-Mills equation, because it takes globally minimal value.


## Arithmetic Geometry {#arithmetic-geometry}




### Absolute height {#absolute-height}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 16:42]</span></span>
See [Height](#height).


### Absolute value {#absolute-value}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 16:26]</span></span>
An **absolute value** on a field \\(k\\) is a real-valued function
\\[\abs{\cdot}: k \to \linterval{0}{\infty}\\]
with the following properties

1.  \\(\abs{x} = 0\\) if and only if \\(x = 0\\).
2.  \\(\abs{xy} = \abs{x} \abs{y}\\).
3.  \\(\abs{x + y} \leq \abs{x} + \abs{y}\\).

The absolute value is said to be **nonarchimedean** if it satisfies
\\[\abs{x + y} \leq \max \\{ \abs{x}, \abs{y}\\}\\]

Referenced: [Degree formula](#degree-formula), [Local degree](#local-degree), [Nonarchimedean](#nonarchimedean), [Normalized absolute value](#normalized-absolute-value).


### Degree formula {#degree-formula}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 16:29]</span></span>
Let \\(k' / k\\) be an extension of number fields, and let \\(v \in M\_{k}\\) be an [Absolute value](#absolute-value) on \\(k\\). Then
\\[\sum\_{w \in M\_{k'}, w | v} [k'\_{w} : k\_{v}] = [k' : k]\\]
where \\(k\_{v}\\) is the \\(v\\) completion of \\(k\\).


### Dirichlet theorem {#dirichlet-theorem}



{{% theorem %}}
Let \\(\alpha \in \RR\\) with \\(\alpha \not \in \QQ\\). Then there are infinitely many rational number \\(p/q \in \QQ\\) such that
\\[\abs{\alpha - \frac{p}{q}} < \frac{1}{q^{2}}\\]
{{% /theorem %}}

The constant on the right hand side can be refined to \\(\frac{1}{\sqrt{5}q^{2}}\\), which can not be further required for \\(\alpha = \frac{-1 + \sqrt{5}}{2}\\).

Referenced: [Roth's theorem](#roth-s-theorem).


### Elliptic curve {#elliptic-curve}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-22 Fri 20:50]</span></span>
An **elliptic curve** \\(E\\) over \\(K\\) is a nonsingular projective curve of genus \\(1\\), which comes equipped with a rational point \\(\OO \in E(K)\\) the **origin**. A **morphism** \\(E \to E'\\) between elliptic curves over \\(K\\) is a morphism of \\(K\\)-schemes which preserves the origin. It is an **isomorphism** if it is an isomorphism of \\(K\\)-schemes.

The following theorem shows the elliptic curve can always be realized as a plane cubic curve.

{{% theorem %}}
Let \\(E/K\\) be an elliptic curve. Then \\(E\\) is isomorphic to a plane cubic curve with affine equation
\\[y^{2} + a\_{1} xy + a\_{3}y = x^{3} + a\_{2}x^{2} + a\_{4}x + a\_{6}\\]
for some \\(a\_{1}, \cdots, a\_{4}, a\_{6} \in K\\) such that the above equation has no singularities.
{{% /theorem %}}

Referenced: [Origin](#origin), [Group law](#group-law), [Isogeny](#isogeny).


#### Origin {#origin}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-22 Fri 21:02]</span></span>
See [Elliptic curve](#elliptic-curve).


#### Group law {#group-law}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-22 Fri 20:50]</span></span>
We write \\(\pic^{\circ} X\\) for the subgroup of divisor classes of degree \\(0\\).

{{% remark %}}
This is a special case of the [Jacobian variety](#jacobian-variety).
{{% /remark %}}

{{% theorem %}}
Let \\(E\\) be an elliptic curve over \\(K\\). There is a bijection \\(E(K) \cong \pic^{\circ}E\\) sending \\(P\\) ot the class \\((P) - (O)\\).
{{% /theorem %}}

Cf. [Elliptic curve](#elliptic-curve).

The group is defined by \\(P + Q = R\\), where \\((P) + (Q) = ( R) + (O)\\).


#### <span class="org-todo todo TODO">TODO</span> Dual {#dual}


#### Isogeny {#isogeny}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-22 Fri 21:16]</span></span>
An **isogeny** is a morphism between [Elliptic curves](#elliptic-curve) which is finite.

Referenced: [Isogeny](#isogeny).


#### Riemann hypothesis {#riemann-hypothesis}



{{% theorem %}}
Let \\(E/ \mathbb{F}\_{q}\\) be an elliptic curve, and define \\(a(E) = q + 1 - \shar(\mathbb{F}\_{q})\\). Then \\(\abs{a} \leq 2 \sqrt{q}\\).
{{% /theorem %}}


#### Tate module {#tate-module}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-22 Fri 21:19]</span></span>
Let \\(l\\) be a prime number unequal to the characteristic of \\(K\\). The **Tate module** of \\(E\\) is the inverse limit
\\[T\_{l}E = \varprojlim E(\bar{K})[l^{n}]\\]
A free \\(\ZZ\_{l}\\)-module of rank \\(2\\). The **rational Tate module** is \\(V\_{l}E = T\_{l}E \otimes\_{\ZZ\_{l}} \QQ\_{l}\\). Here \\(E(\bar{K})[m]\\) denote the number of \\(m\\) torsion points of \\(E(\bar{K})\\).

Referenced: [Tate's isogeny theorem](#tate-s-isogeny-theorem).


#### Tate's isogeny theorem {#tate-s-isogeny-theorem}



{{% theorem %}}
Let \\(E\\) and \\(E'\\) be elliptic curves over a finite field \\(K\\). The map
\\[\Hom(E, E') \otimes\_{Z} \QQ\_{l} \to \Hom\_{G\_{K}}(V\_{l}E, V\_{l}E')\\]
is an isomorphism. Here \\(G\_{K}\\) is the absolute Galois group of \\(K\\).
{{% /theorem %}}

Cf. [Tate module](#tate-module).


#### Mordell-Weil theorem {#mordell-weil-theorem}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-22 Fri 21:43]</span></span>
The first version is **weak Mordell-Weil theorem**.

{{% theorem %}}
Let \\(K\\) be a number field, let \\(E/K\\) be an elliptic curve, and let \\(m \geq 2\\). The group \\(E(K)/mE(K)\\) is finite.
{{% /theorem %}}

Then we lead to (full) **Mordell-Weil theorem**.

{{% theorem %}}
\\(E(K)\\) is finitely generated.
{{% /theorem %}}

{{% remark %}}
The weak Mordell-Weil theorem do not implies Mordell-Weil theorem, for it doesn't exclude case for example \\(E(K) = \QQ / \ZZ\\).
{{% /remark %}}


### Finiteness of class group {#finiteness-of-class-group}



{{% proposition %}}
There are finitely many ideal classes in \\(K\\).
{{% /proposition %}}

Cf. [Ideal class](#ideal-class).


### Finiteness of point under height {#finiteness-of-point-under-height}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 16:42]</span></span>
The following theorem shows some finiteness of points less than a given height.

{{% theorem %}}
For any number \\(B, D \geq 0\\), the set
\\[\\{P \in \PP^{n}(\bar{\QQ}) \mid H(P) \leq B \text{ and } [\QQ(P) : \QQ] \leq D\\}\\]
is finite. In particular, when \\(k\\) is fixed, the set \\(\\{P \in \PP^{n}(k) \mid H\_{k}(P) \leq B\\}\\) is finite.
{{% /theorem %}}

This implies the Kronecker's theorem.

{{% corollary %}}
Let \\(k\\) be a number field, and \\(P = (x\_{0}, \cdots, x\_{n})\\). Fix any \\(i\\) with \\(x\_{i} \neq 0\\). Then \\(H(P) = 1\\) if and only if the ratio \\(x\_{j}/ x\_{i}\\) is a root of unity or zero for every \\(0 \leq j \leq n\\).
{{% /corollary %}}


### Finiteness of unit group {#finiteness-of-unit-group}



{{% proposition %}}
The abelian group \\(\OO\_{K,S}\\) is finitely generated.
{{% /proposition %}}

Cf. [S-integer](#s-integer).


### Height {#height}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 16:36]</span></span>
Let \\(k\\) be a number field and let \\(P = (x\_{0}, x\_{1}, \cdots, x\_{n}) \in \PP^{n}(k)\\) be a point whose homogeneous coordinates are chosen in \\(k\\). The **height** is the quantity
\\[H\_{k}(P) = \prod\_{v \in M\_{k}} \max \\{\norm{x\_{0}}\_{v}, \norm{x\_{1}}\_{v}, \cdots, \norm{x\_{n}}\_{v}\\}\\]
And define the **logarithmic height** by
\\[h\_{k} = \log H\_{k}(P)\\]
Cf. [Normalized absolute value](#normalized-absolute-value).

We have preceding formula for height in extension field

{{% lemma %}}
If \\(k\\) be a number field and \\(k'/k\\) a finite field extension. Then
\\[H\_{k'}(P) = H\_{k}(P)^[k':k]\\]
{{% /lemma %}}

By above lemma, we can define the **absolute height** on \\(\PP^{n}\\) by
\\[H: \PP^{n}(\bar{Q}) \to \linterval{0}{\infty}\\]
\\[H(P) = H\_{k}(P)^{1/[k: \QQ]}\\]
where \\(P \in \PP^{n}(k)\\). The **absolute logarithmic height** is defined similarly.

We can extend the definition of height to varieties. Let \\(\phi: V \to \PP^{n}\\) is a morphism, then we can define
\\[h\_{\phi}(P) = h(\phi(P))\\]
The definition of this height is dependent on the choice of the morphism \\(\phi\\).

Referenced: [Absolute height](#absolute-height).


### <span class="org-todo todo TODO">TODO</span> Ideal class {#ideal-class}



Referenced: [Finiteness of class group](#finiteness-of-class-group).


### <span class="org-todo todo TODO">TODO</span> Jacobian variety {#jacobian-variety}



Referenced: [Group law](#group-law).


### Local degree {#local-degree}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 16:31]</span></span>
Let \\(v \in M\_{k}\\) be an [Absolute value](#absolute-value) on number field \\(k\\). The **local degree** of \\(v\\) is the number
\\[n\_{v} = [k\_{v} : \QQ\_{v}]\\]


### Nonarchimedean {#nonarchimedean}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 16:29]</span></span>
See [Absolute value](#absolute-value).


### Normalized absolute value {#normalized-absolute-value}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 16:32]</span></span>
Let \\(v \in M\_{k}\\) be an [Absolute value](#absolute-value) on number field \\(k\\). The **normalized absolute value** of \\(v\\) associated to \\(v\\) is
\\[\norm{x}\_{v} = \abs{x}\_{v}^{n\_{v}}\\]

For normalized absolute value, we have the **product formula**, for \\(x \in k^{\* }\\), we have
\\[\prod\_{v \in M\_{k}} \norm{x}\_{v} = 1\\]

Referenced: [Height](#height).


### Roth's theorem {#roth-s-theorem}



{{% theorem %}}
Let \\(\alpha \in \bar{K}\\), and let \\(v \in S\_{K}\\). Extend \\(\abs{\cdot}\_{v}\\) to an absolute value \\(\abs{\cdot}\_{v}\\) on \\(K(\alpha)\\). For all \\(\epsilon > 0\\) and every \\(C > 0\\), the inequality
\\[\abs{\alpha - x}\_{v} < \frac{C}{H\_{K}(x)^{2 + \epsilon}}\\]
has only finitely many solutions in \\(x \in K\\).
{{% /theorem %}}

Cf. [Dirichlet theorem](#dirichlet-theorem).


### S-integer {#s-integer}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 16:34]</span></span>
The ring of **S-integers** of \\(k\\) is defined to be
\\[R\_{S} = \\{x \in k \mid \abs{x}\_{v} \leq 1 \text{ for all } v \in M\_{k}, v \not \in S\\}\\]

We can also characterize the rings of integers of \\(k\\) by \\(M\_{k}^{\infty}\\)-integers of \\(k\\).

Referenced: [S-unit]({{<relref "Notes_Mathematics.md#algebraic-number-theory" >}}), [Finiteness of unit group](#finiteness-of-unit-group).


## Bibliography {#bibliography}

<a id="steinberg2012"></a>[steinberg2012] Steinberg, Representation Theory of Finite Groups: An Introductory Approach, Springer (2012). [↩](#19580479584332ed50a4af7bf7f3f201)

<a id="kirillov2016"></a>[kirillov2016] Kirillov, Quiver Representations and Quiver Varieties, American Mathematical Society (2016). [↩](#df38f5636bec59103a70400bed4764c9)

<a id="dieck2008"></a>[dieck2008] tom Dieck, Algebraic Topology, European Mathematical Society (2008). [↩](#5ad6139c99b6d2508f6ef6f11ce7f09d)

<a id="cox2011"></a>[cox2011] Cox, Little & Schenck, Toric Varieties, American Mathematical Society (2011). [↩](#8a8485591c9ae40ab7e9a4d136fca3d2)

<a id="milne2017"></a>[milne2017] Milne, Algebraic Groups: The Theory of Group Schemes of Finite Type over a Field, Cambridge University Press (2017). [↩](#868cb56e509be613430cca58b1ead9f3)

<a id="maulik2006"></a>[maulik2006] Maulik, Nekrasov, Okounkov & Pandharipande, Gromov\textendashWitten Theory and Donaldson\textendashThomas Theory, I, <i>Compositio Mathematica</i>, <b>142(05)</b>, 1263-1285 (2006). <a href="http://dx.doi.org/10.1112/S0010437X06002302">doi</a>. [↩](#71c689e646b740e15274e4c45df483c9)

<a id="maulik2006a"></a>[maulik2006a] Maulik, Nekrasov, Okounkov & Pandharipande, Gromov\textendashWitten Theory and Donaldson\textendashThomas Theory, II, <i>Compositio Mathematica</i>, <b>142(05)</b>, 1286-1304 (2006). <a href="http://dx.doi.org/10.1112/S0010437X06002314">doi</a>. [↩](#a94d6b5af3fa210c91d9309d3da103af)

<a id="maulik2011"></a>[maulik2011] Maulik, Oblomkov, Okounkov & Pandharipande, Gromov-Witten/Donaldson-Thomas Correspondence for Toric 3-Folds, <i>Inventiones mathematicae</i>, <b>186(2)</b>, 435-479 (2011). <a href="http://dx.doi.org/10.1007/s00222-011-0322-y">doi</a>. [↩](#e25e310ddc34f4e55392b368230bb1bf)

<a id="pandharipande2009"></a>[pandharipande2009] Pandharipande & Thomas, Curve Counting via Stable Pairs in the Derived Category, <i>Inventiones mathematicae</i>, <b>178(2)</b>, 407-447 (2009). <a href="http://dx.doi.org/10.1007/s00222-009-0203-9">doi</a>. [↩](#431caa59e2d75afb6b38719ad8dca5d9)

<a id="toda2010"></a>[toda2010] Toda, Curve Counting Theories via Stable Objects I. DT/PT Correspondence, <i>Journal of the American Mathematical Society</i>, <b>23(4)</b>, 1119-1157 (2010). <a href="http://dx.doi.org/10.1090/S0894-0347-10-00670-3">doi</a>. [↩](#f9133d12da33e9b2ae5ee8e0f8d3fa3a)

<a id="pandharipande2014"></a>[pandharipande2014] Pandharipande & Pixton, Gromov\textendashWitten/Pairs Descendent Correspondence for Toric 3\textendash Folds, <i>Geometry & Topology</i>, <b>18(5)</b>, 2747-2821 (2014). <a href="http://dx.doi.org/10.2140/gt.2014.18.2747">doi</a>. [↩](#909250c4d905735b782534d99f6095f5)

<a id="pandharipande2017"></a>[pandharipande2017] Pandharipande & Pixton, Gromov-Witten/Pairs Correspondence for the Quintic 3-Fold, <i>Journal of the American Mathematical Society</i>, <b>30(2)</b>, 389-449 (2017). <a href="http://dx.doi.org/10.1090/jams/858">doi</a>. [↩](#88221b9c6d4636326d6b0764fc915f73)

<a id="oblomkov2020"></a>[oblomkov2020] Oblomkov, Okounkov & Pandharipande, GW/PT Descendent Correspondence via Vertex Operators, <i>Communications in Mathematical Physics</i>, <b>374(3)</b>, 1321-1359 (2020). <a href="http://dx.doi.org/10.1007/s00220-020-03686-4">doi</a>. [↩](#5475808075c4e5ae5aa873cba4119875)

<a id="moreira2020"></a>[moreira2020] Moreira, Oblomkov, Okounkov & Pandharipande, Virasoro Constraints for Stable Pairs on Toric 3-Folds, <i>arXiv:2008.12514 [math]</i>,  (2020). [↩](#b79997d2a1ead8b84a185c6680e7e9db)

<a id="sernesi2006"></a>[sernesi2006] Sernesi, Deformations of Algebraic Schemes, Springer Berlin Heidelberg (2006). [↩](#7cd3e01b28c2ede526fee96d60981f02)

<a id="nakajima1999"></a>[nakajima1999] Nakajima, Lectures on Hilbert Schemes of Points on Surfaces, American Mathematical Society (1999). [↩](#24e67c8afe5163064e4018cb5a5cbd8a)
