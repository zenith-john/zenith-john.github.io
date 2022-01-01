+++
title = "Mathematics Notes"
author = ["Zenith John"]
date = 2021-08-31
tags = ["Mathematics"]
draft = false
lastmod = 2021-12-23
showtoc = true
+++

## General Mathematics {#cccce4bf-a1dc-452e-9aad-1f6ba803b6b5}




### Existence proof {#d315cf38-ce65-43c5-9249-ffa9ec4da383}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-27 Mon 20:43]</span></span>
One kind of the importance theorem in mathematics is the existence theorem which states something with certain property exists. Basically, there are two kinds of proof of the existence theorem.

-   Construction. E.g. existence of smooth but not differentiable function.
-   Proof by contradiction. E.g. infiniteness of prime numbers, [Brouwer fixed point theorem](#200796ad-0da0-473c-90a6-56ec64145537).


### Flavors of mathematics {#a32648fb-207f-443c-9d88-6a5db6fb1dc8}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 17:44]</span></span>
I want to quote the word of Charles Fefferman to show my flavors of mathematics.

> Mathematics at the highest level has several flavors. On seeing it, one might say
>
> 1.  What amazing technical power!
> 2.  What a grand synthesis!
> 3.  How could anyone not have seen this before?
> 4.  Where on earth did this come from?

In my opinion, the proof of Fermat's last theorem by Wiles of kind 1; Langlands conjecutre is of kind 2; the mirror symmetry conjecture or its computation on Calabi-Yau quintics is of kind 3; Tao and Green's proof of the primes contain arbitrarily long arithmetic progressions of kind 4.


### Some advices {#17a30048-ee10-43da-846a-21b0b7701ca3}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-28 Tue 17:44]</span></span>
From [Vakil's page](http://math.stanford.edu/~vakil/threethings.html) on advice for listening to talks.

1.  a definition you want to remember (e.g. "a K3 surface is...")
2.  a theorem you want to remember ("the moduli space of polarized K3 surfaces is smooth")
3.  a motivating or key example ("a quartic is an example of a K3 surface")
4.  a motivating problem ("why are all moduli spaces of polarized K3 surfaces the same dimension?")
5.  a question you want to ask the speaker ("why is that hypothesis in your theorem?")
6.  a question you want to ask someone else (a definition, motivation, a question about a connection etc.)
7.  anything else of a similar flavor: something specific that made you think. Something vague ("I liked the part where she talked about groups") does not count as a "thing".

From [Kedlaya's page](https://kskedlaya.org/notes%5Fstudents.shtml),
One important point to keep in mind is that unlike at earlier stages in one's education, in graduate school and beyond one very often learns mathematics "in reverse". That is, it is often necessary to work through a particular piece of mathematics before one is familiar with its logical prerequisites; the switch from forward to reverse study of mathematics is quite a difficult transition (at least according to my own experience as a student).


## Category Theory {#19d54b18-1afe-4e4a-aec6-07f801eb67b8}




### <span class="org-todo todo TODO">TODO</span> A\_&infin; algebra {#3c02c0c1-b2d4-4ff1-b611-35294a18f29d}


### <span class="org-todo todo TODO">TODO</span> A\_&infin; category {#0cd7db62-7e09-4c15-a462-eb15cbeabcad}


### Abelian {#2c5f1f9b-9e9a-4dd1-97ba-b4c20c211806}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 20:59]</span></span>
A category is **abelian** if it is [Exact](#51c2274f-cb4a-4a7a-b6de-8c7bf81f3c39) and [Additive](#7fe0ea1e-b6d3-48b0-b843-3f6e519ce662).


### Additive {#7fe0ea1e-b6d3-48b0-b843-3f6e519ce662}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 20:53]</span></span>
A category \\(\mathcal{C}\\) is called **additive** if the following conditions hold.

1.  For any two object \\(\Hom(X,Y)\\) has an abelian group structure and compositions are bilinear.
2.  There is a zero object, denoted by \\(0\_{\mathcal{C}}\\).
3.  For any two objects \\(X, Y\\), the direct sum \\(X \oplus Y\\) exists in \\(\mathcal{C}\\).

A functor is called **additive** if it induces group homomorphism on homomorphisms.


### Adjoint {#d835fa52-0286-4324-8a6e-e58c32315833}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 20:57]</span></span>
Let \\(F: \mathcal{C} \to \mathcal{D}\\) and \\(G: \mathcal{D} \to \mathcal{C}\\) two functors. We say that \\(G\\) is **right adjoint** to \\(F\\) and \\(F\\) is **left adjoint** to \\(G\\) if there is an isomorphism
\\[\Hom\_{\mathcal{D}}(F(X), Y) \cong \Hom\_{\mathcal{C}}(X, G(Y))\\]


### Anodyne extension {#f79b88b4-95df-47ff-b4a6-bed2cb652d02}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:09]</span></span>
**Anodyne extensions** denote the class of morphisms \\(\Lambda\_{k}^{n} \subset \Delta^{n}\\).

Referenced: [Kan fibration](#24c4c625-6639-4558-95ed-fbb6015188fa).


### Associativity constraint {#7952eb96-5003-45e9-b48d-e7764d411f07}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 19:10]</span></span>
For \\(\mathscr{C}\\) category with functor \\(\otimes\\), an **associativity constraint** is a functorial isomorphism
\\[\phi: X \otimes (Y \otimes Z) \to (X \otimes Y) \otimes Z\\]
satisfying pentagon identity.

{{< figure src="/img/2021-09-30_13-57-58_screenshot.png" >}}

Referenced: [Monoidal category](#e5efd020-d8bd-4ef0-88b6-af567e6d7d43), [Tensor category](#3ff71704-ce2e-458d-88ae-adf48f6c89bf), [Rigid](#51c7cfa0-c077-4e1f-aa58-e7e9678f4cda), [Tensor functor](#cf063348-e088-4ec0-8e7a-59e5de57ccaf).


### <span class="org-todo todo TODO">TODO</span> Bialgebra {#74e04e25-67bb-4385-adbd-b49685915779}


### Category {#f1a8094b-2c4a-439a-b66e-9d16b563fb4c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 18:49]</span></span>
A **category** \\(\mathcal{C}\\) consists of the following data

1.  A collection of **objects**.
2.  For every pair of objects \\(X, Y \in \mathcal{C}\\), a set \\(\Hom\_{\mathcal{C}}(X,Y)\\) of **morphisms** from \\(X\\) to \\(Y\\).
3.  For every object \\(X \in \mathcal{C}\\), an **identity morphism** \\(\id\_{X} \in \Hom\_{\mathcal{C}}(X, X)\\).
4.  For every triple of objects, a composition map
    \\[\Hom\_{\mathcal{C}}(X, Y) \times \Hom\_{\mathcal{C}}(Y,Z) \to \Hom\_{\mathcal{C}}(X, Z)\\]
5.  We have for every morphism \\(f: X \to Y\\), \\(\id\_{Y} \circ f = f = f \circ \id\_{X}\\).
6.  The composition satisfies the associativity condition.

I will use symbol like \\(\cat{Cat}\\) to denote categories.


### Classifying space {#8274f12e-0561-404b-907f-0568cdcb95cf}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-12 Sun 21:54]</span></span>
For \\(\mathscr{C}\\) a small category, the **classifying space** (or **nerve**) \\(B\mathscr{C}\\) isthe [Simplicial set](#7f7b56bd-7f4f-4dd4-8aa1-e57a14f6e423) with \\(B \mathscr{C} = \hom\_{\cat{Cat}}(\bm{n}, \mathscr{C})\\).

A standard example is the \\(BG\\), where \\(G\\) is a group and denoted by the same notion corresponding [Groupoid](#f0f4db1c-a8a6-41ae-809f-d4c93ddfba33), with one object and morphism \\(\Hom(\*, \*) = G\\) and \\(\abs{BG}\\) is the [Eilenberg-Mac Lane space](#d850d002-bf3b-4611-9619-862541e582f4) \\(K(G,1)\\).


### Cocomplete {#04c75251-d006-4a61-84a7-0a6857c09462}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:47]</span></span>
A category is called **cocomplete** if all [Colimits](#136ef35b-144b-4e06-ae24-4db780022828) exist.

Referenced: [Category CGWH](#6fcf0c23-fe3f-4fde-80a3-6c6e6c4591c5).


### <span class="org-todo todo TODO">TODO</span> Cofiber {#746dcdf5-dcab-49bb-84ae-813d4679176e}


### Colimit {#136ef35b-144b-4e06-ae24-4db780022828}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:40]</span></span>
Let \\(C\\) be an [&infin;-category](#51b2b46f-20be-48e9-8e4e-f91d2c5b4062) and let \\(p: K \to C\\) be an arbitrary map of simplicial sets. A **colimit** for \\(p\\) is an initial object of \\(C\_{p/}\\). A **limit** for \\(p\\) is a final object of \\(C\_{/p}\\).

Referenced: [Cocomplete](#04c75251-d006-4a61-84a7-0a6857c09462), [Compact](#775652ea-578a-44c5-9c81-160c49631323).


### Commutativity constraint {#3292ae27-0e60-4f47-9a5f-ea3cf3ed8a98}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 13:58]</span></span>
The **commutativity constraint** is \\(\psi\_{X,Y}: X \otimes Y \to Y \otimes X\\) for all \\(X, Y\\) such that
\\[\psi\_{Y,X} \circ \psi\_{X,Y} = \id\_{X \otimes Y}\\]
with some compatibility condition.

{{< figure src="/img/2021-09-30_14-02-04_screenshot.png" >}}

Referenced: [Tensor category](#3ff71704-ce2e-458d-88ae-adf48f6c89bf), [Rigid](#51c7cfa0-c077-4e1f-aa58-e7e9678f4cda), [Tensor functor](#cf063348-e088-4ec0-8e7a-59e5de57ccaf).


### Comodule {#e3ffaafa-c6dd-4ecc-8595-af45c384421f}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 14:05]</span></span>
Let \\(A\\) be a [Hopf algebra](#8b7067b7-b4d0-41a3-9b0e-4b427a188551). Then \\(V\\) with \\(k\\)-linear map \\(\rho: V \to V \otimes A\\) satisfying \\(V \stackrel{\rho}{\to} V \otimes A \stackrel{\id \otimes \epsilon}{\to} V \otimes k \cong V\\) is identity and \\(V \stackrel{\rho}{\to} V \otimes A \overset{\rho \otimes \id}{\underset{\id \otimes \Delta}{\rightrightarrows}} V \otimes A \otimes A\\) are same.


### Compact {#775652ea-578a-44c5-9c81-160c49631323}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-29 Mon 18:45]</span></span>
An object \\(A\\) in category \\(\mathscr{C}\\) is called compact if the functor \\(\Hom(A, -): \mathscr{C} \to \cat{Set}\\) preserves the [Colimit](#136ef35b-144b-4e06-ae24-4db780022828).

{{% proposition %}}
An object \\(A\\) in \\(\cat{Set}\\) is compact if and only if \\(A\\) is finite.
{{% /proposition %}}


### Complete {#9b4f37d7-395c-4ed3-ade1-a12816dd52dc}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:47]</span></span>
A category is called **complete** if all [Limits](#f9c3cc0f-4513-49af-bd01-1dc06b2bddf0) exist.

Referenced: [Category CGWH](#6fcf0c23-fe3f-4fde-80a3-6c6e6c4591c5).


### Complex {#6170b3f2-c71e-4ccf-9554-27b62014bb00}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 21:00]</span></span>
A **complex** of [Abelian](#2c5f1f9b-9e9a-4dd1-97ba-b4c20c211806) category \\(\mathcal{A}\\) is a chain
\\[A^{\bullet}: \cdots \to A^{-1} \xrightarrow{d^{-1}} A^{0} \xrightarrow{d^{0}} A^{1} \to \cdots\\]
where the differential satisfies \\(d^{k+1} \circ d^{k} = 0\\). A morphism between \\(A^{\bullet}\\) and \\(B^{\bullet}\\) is a set of morphisms between \\(A^{k}\\) and \\(B^{k}\\) commutes with differential map. The category of complexes is denoted by \\(C(\mathcal{A})\\).

The **cohomology** of the complex id \\(H^{k}(A^{\bullet}) = \frac{\ker d^{k}}{\im d^{k - 1}}\\).

We introduce the following **associated truncated complexes** by
\\[\tau\_{\leq m}A^{\bullet}: \to A^{m -1} \xrightarrow{d^{m - 1}} \ker d^{m} \to 0 \to \\]
\\[\tau^{\leq m}A^{\bullet}: \to A^{m -1} \xrightarrow{d^{m - 1}} A^{m} \xrightarrow{d^{m}} \im d^{m} \to 0 \to\\]
We also define
\\[\tau\_{\geq m}A^{\bullet} = A^{\bullet}/ \tau\_{m -1} A^{\bullet}\\]
\\[\tau^{\geq m}A^{\bullet} = A^{\bullet}/ \tau^{m -1} A^{\bullet}\\]

We have shift functor \\(X[1]^{i} = X^{i + 1}\\).


#### Acyclic {#4412829b-cec9-4cf5-8558-7ace6edff387}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 21:03]</span></span>
A complex \\(A^{\bullet}\\) is called **acyclic** if \\(H^{k}(A^{\bullet}) = 0\\) for all \\(k \in \ZZ\\).


#### Mapping cone {#a0180c60-1577-4bfa-9f35-ff3b4313f674}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 21:12]</span></span>
Let \\(u: X^{\bullet} \to Y^{\bullet}\\) be a morphism. The **mapping cone** is the complex given by \\(C\_{u}^{\bullet} = Y^{\bullet} \oplus (X^{\bullet}[1])\\), where \\(d\_{u}(y, x) = (\dif y + u(x), - \dif x)\\). It also denoted by \\({\rm Cone}(u)\\).


#### Quasi-isomorphism {#3f6ffb3d-e0e1-4986-8446-28c25540ba94}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 21:04]</span></span>
A morphism \\(u: X^{\bullet} \to Y^{\bullet}\\) is a **quasi-isomorphism** if it induces isomorphism on cohomology groups.


#### Homotopy {#1807defb-b6be-4f45-94fb-cb4f3e73aea6}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 21:05]</span></span>
Two complex morphism \\(u,v: X^{\bullet} \to Y^{\bullet}\\) is called **homotopic** if there exists a **homotopy** \\(h \in \Hom^{-1}(X^{\bullet}, Y^{\bullet})\\) such that \\(u - v = \dif\_{Y} h + h \dif\_{X}\\).

Two complexes are **homotopy equivalent** if there exists \\(f: X \to Y\\) and \\(g: Y \to X\\) such that \\(v \circ u \sim \id\_{X}\\) and \\(u \circ v \sim \id\_{Y}\\).


### Cone {#b8cd7449-263f-450f-9a51-74255f29adfc}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-25 Sat 21:31]</span></span>
The **left cone** \\(K^{\vartriangleleft}\\) is defined to be \\(\Delta^{0} \star K\\). And dually, the **right cone** \\(K^{\vartriangleright}\\). Either cone contains a distinguished vertex which we will refer to as the **cone point**.


### Cylinder object {#4a135d4f-f34d-4ad4-bf2d-9514b1e56fcb}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 17:34]</span></span>
A **cylinder boject** for an object \\(A\\) in a [Closed model category](#faa405c2-1a5a-485a-83c5-d77e44887d5f) is the commutative triangle

![](/img/2021-12-18_17-34-46_screenshot.png)
where \\(\nabla\\) is the canonical fold map identity on each component.

Referenced: [Left homotopy](#6b34aa91-15a0-4f98-b8cf-204f99e14aa8), [Path object](#36d8e6af-be8c-4c87-a6d6-dd3878671658).


### Derived category {#78f25abc-ddb3-46d6-9e3a-4a1ebe561300}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 20:20]</span></span>
The **derived category** of the [Abelian](#2c5f1f9b-9e9a-4dd1-97ba-b4c20c211806) category \\(\mathcal{A}\\) is the [Triangulated category](#bfcda5c7-8c14-4365-9870-eebf8ac950b1) \\(D(\mathcal{A})\\) obtained from the [Homotopical category](#caff447d-cfac-481d-9dfd-f4db9113541a) \\(K(\mathcal{A})\\) by localization with respect to the multiplicative system formed by all the quasi-isomorphisms in \\(K(\mathcal{A})\\).

We have category \\(D^{b}(\mathcal{A})\\) (resp. \\(D^{+}(\mathcal{A}), D^{-}(\mathcal{A})\\)) equivalent to the full triangulated subcategory of \\(D(\mathcal{A})\\) consisting of objects \\(X\\) such that \\(H^{n}(X) = 0\\) for all \\(\abs{n} \gg 0\\) (resp. \\(n \ll 0, n \gg 0\\)).


### Derived functor {#c2fbc956-3975-40dd-b970-29b2e91af66a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 20:20]</span></span>
If \\(F\\) is left exact, we define the **right derived functor** to be \\(RF\\) making the diagram commutes and satisfying the universality property.

{{< figure src="/img/2021-12-19_21-40-54_screenshot.png" >}}

Similarly, we have **left derived functor**.


### Drinfeld double {#edf955e9-0d54-4d44-991c-53b5a864293c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:15]</span></span>
Let \\((H, H^{\vee}, \langle , \rangle)\\) [Dual pair](#388ef476-5a70-400b-ae35-b9a680ca1828) of [Hopf algebra](#8b7067b7-b4d0-41a3-9b0e-4b427a188551), and let \\(H^{0}\\) be he Hopf algebra \\(H^{\vee}\\) with the opposite comultiplication. Then \\(D(H) = H \otimes H^{0}\\) has an algebra structure uniquely determined by
\\[\Delta\_{D}(a)( R) = R \Delta\_{D}^{op}(a)\\]
for any \\(a \in D(H)\\) and \\(R = \sum\_{i} (e\_{i} \otimes 1\_{H^{0}}) \otimes (1\_{H} \otimes e^{i})\\), where \\(e\_{i}\\) is basis in \\(H\\) and \\(e^{i}\\) basis in \\(H^{\vee}\\). Such construction is called **Drinfeld double**.


### Dual {#37842b9c-6a24-4fc2-88d2-7fa2ceeab7ba}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 14:46]</span></span>
We define the **dual** to be \\(X^{\vee} = \ihom(X, U)\\), where \\(U\\) is the [Identity object](#3e4fd621-7f24-47d3-8afb-7032a6c59744).

Cf. [Tensor category.](#3ff71704-ce2e-458d-88ae-adf48f6c89bf)

Referenced: [Reflexive](#95bcb049-bebc-40e2-8825-3cf80620f211).


### Essentially surjective {#348254a3-ddb1-4d8a-aaba-af40f1c23fbf}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 15:20]</span></span>
For [Simplicial set](#7f7b56bd-7f4f-4dd4-8aa1-e57a14f6e423), a functor is **essentially surjective** if the induced functor on [Homotopy categories](#ab32b639-e590-4e00-8bb9-0ef66574985a) is essentially surjective. Similarly statement holds for **fully faithful**.


### Exact {#51c2274f-cb4a-4a7a-b6de-8c7bf81f3c39}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 20:52]</span></span>
A category is **exact** if there are [Zero object](#e11e1db2-b03d-4e25-82f6-3f2bfb76e6c8), all the morphisms have kernels and cokernels, and \\({\rm Coim}(f) \to {\rm Im}(f)\\) is an isomorphism.


### F-acyclic {#10475722-258f-459b-ac55-328efab6f5af}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 21:42]</span></span>
Let \\(F: \mathcal{A} \to \mathcal{B}\\) be a left [Derived functor](#c2fbc956-3975-40dd-b970-29b2e91af66a). An object \\(X\\) in \\(\mathcal{A}\\) is **F-acyclic** if \\(R^{i}F = 0\\) for all \\(i > 0\\).


### Fiber {#3342e544-9865-4dec-af2e-2e610a3f8b13}


### Fibre functor {#dee5d2a3-1cdd-4a73-9eb7-dba2e96aa45b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 19:09]</span></span>
For [Tensor category](#3ff71704-ce2e-458d-88ae-adf48f6c89bf) \\((\mathscr{C}, \otimes)\\), a **fibre functor** \\(F\\) is a functor \\(\mathscr{C} \to \cat{Vec}\\) satisfies that \\(F(V\_{1} \otimes V\_{2}) \cong F(V\_{1}) \otimes F(V\_{2})\\).


### Final {#545a1ee9-c2d2-4865-8eab-cda8993f53f2}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 15:23]</span></span>
An object in [Simplicial set](#7f7b56bd-7f4f-4dd4-8aa1-e57a14f6e423) is called **final** if it is final in the [Homotopy category](#ab32b639-e590-4e00-8bb9-0ef66574985a). Similar result holds for **initial**.


### Fully faithful {#59770a96-d29e-4ae3-9eba-348cf1c0b7d1}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 15:22]</span></span>
See [Essentially surjective](#348254a3-ddb1-4d8a-aaba-af40f1c23fbf).


### Function complex {#fa981cde-121c-4109-a0f9-4aead6157487}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:13]</span></span>
The **function complex** \\(\bm{Hom}(X,Y)\\) is the simplicial set defined by
\\[\bm{Hom}(X,Y)\_{n} = \hom\_{\bm{S}}(X \times \Delta^{n}, Y)\\]


### Functor {#49198b51-564c-4a87-b9d4-8e7adc6520d6}



Referenced: [Continuous](#acaebda9-a08a-412e-a02c-17724aba56d9), [Simplicial set](#7f7b56bd-7f4f-4dd4-8aa1-e57a14f6e423).


#### Continuous {#acaebda9-a08a-412e-a02c-17724aba56d9}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-07 Sun 10:21]</span></span>
Let \\(C\\) and \\(C'\\) be [Sites](#d827cad0-92be-4251-9e34-4243334a9315) with associated [Topoi](#7ee906fc-4e21-4965-a082-1e0ee87235c7) \\(T\\) and \\(T'\\), then a [Functor](#49198b51-564c-4a87-b9d4-8e7adc6520d6) \\(C' \to C\\) is called **continuous** if for every \\(X \in C'\\) and \\(\\{X\_{i} \to X\\} \in \cat{Cov}(X)\\) the family \\(\\{f(X\_{i}) \to f(X)\\}\\) is in \\(\cat{Cov}(f(X))\\) and if \\(f\\) commutes with fiber prooducts when they exists in \\(C'\\).

{{% exam %}}
Consider \\(f: X \to Y\\) continuous map, then \\(f^{-1}: \cat{Op}(Y) \to \cat{Op}(X)\\) is a continuous morhpism of sites.
{{% /exam %}}

Given a functor \\(f: C' \to C\\), we have a functor of presheaves: \\(f\_{\* }: \hat{C} \to \hat{C}'\\). That is \\((f\_{\* }F)(T) := F(f(X))\\). When functor is continuous, then \\(f\_{\* }\\)  sends sheaves to sheaves.
A **functor** \\(F\\) between two categories \\(\mathcal{C}\\) and \\(\mathcal{D}\\) is a collection of data, for \\(X \in \mathcal{C}\\), \\(X \to F(X)\\) and for \\(f \in \Hom\_{\mathcal{C}}(X,Y) \to F(f) \in \Hom\_{\mathcal{D}}(F(X), F(Y))\\) satisfying the associativity and identity condition.

Referenced: [Sheaf](#32e43dc9-af7b-46a9-a114-1d5f42a5f95d).


#### Fully faithful {#cde7170c-d70f-4117-88cc-bc154b32ceb1}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 20:56]</span></span>
A functor \\(F\\) is called **fully faithful** if \\(\Hom(X,Y) \to \Hom(F(X), F(Y))\\) is a bijection.


### Functorial factorization {#bedd7c88-47ad-48e8-8a6d-f820fb950061}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 17:53]</span></span>
A **functorial factorization** is an ordered pair \\((\alpha, \beta)\\) of functors \\(\cat{Map}(\mathcal{C}) \to \cat{Map}(\mathcal{C})\\) such that \\(f = \beta(f) \circ \alpha(f)\\) for all \\(f \in \cat{Map}(\mathcal{C})\\).

Referenced: [Model category](#faa405c2-1a5a-485a-83c5-d77e44887d5f), [Cofibrant replacement](#54d76b2c-186c-41de-b209-8dab6d10e5a1).


### Group object {#5c5c0b69-08cf-4b01-b4db-bacc83d09305}


### Groupoid {#f0f4db1c-a8a6-41ae-809f-d4c93ddfba33}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 14:59]</span></span>
A **groupoid** is a category whose morphisms are all isomorphisms.

Referenced: [Classifying space](#8274f12e-0561-404b-907f-0568cdcb95cf), [Seifert-Van Kampen theorem](#22a5ec7c-c651-4698-8825-d13578a874c2).


### Heart {#0c7d2280-19bc-42e0-bed7-a798b0e65aaf}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 18:33]</span></span>
Let \\((D^{\leq 0}, D^{\geq 0})\\) be [t-structure](#b2ad7b32-8a22-41e9-9db6-d3cc1d2d78f6) for category \\(D\\), then \\(C = D^{\leq 0} \cap D^{\geq 0}\\) is called **heart** of t-structure.

Referenced: [Perverse sheaf](#929a1901-d7f2-48e8-ba4e-d38299118fc4).


### Homotopic {#afbdfab2-f8f0-4f10-8ec8-57a6c3e2eac6}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:19]</span></span>
Maps \\(f,g\\) are a **homotopic** which is both [Left homotopic](#6b34aa91-15a0-4f98-b8cf-204f99e14aa8) and right homotopic, denoted by \\(f \sim g\\).


### Homotopical category {#caff447d-cfac-481d-9dfd-f4db9113541a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 21:22]</span></span>
We can define the **homotopical category** of complexes \\(K(\mathcal{A})\\) with the same object as \\(C(\mathcal{A})\\) but \\(\Hom\_{K(\mathcal{A})}(X, Y) = \Hom(X^{\bullet}, Y^{\bullet})/ \sim = H^{0}(\Hom^{\bullet}(X,Y))\\).

The family of triangles in \\(K(\mathcal{A})\\) which are isomorphic to a standard triangle ([Mapping cone](#a0180c60-1577-4bfa-9f35-ff3b4313f674)) is called **distinguished triangle**.


### Homotopy category {#ab32b639-e590-4e00-8bb9-0ef66574985a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:11]</span></span>
Suppose \\(\mathcal{C}\\) is a category with a subcategory of weak equivalence \\(\mathcal{W}\\). Define the **homotopy category** \\(\cat{Ho}(\mathcal{C})\\) as follows. Form the free category \\(F(\mathcal{C}, \mathcal{W}^{-1})\\) on the arrows of \\(\mathcal{C}\\) and reversals of the arrows of \\(W\\). \\(\cat{Ho}(\mathcal{C})\\) is the quotient category of \\(F(\mathcal{C}, \mathcal{W}^{-1})\\) by the relations \\(1\_{A} = (1\_{A})\\) for all objects \\(A\\), \\((f, g) = (g \circ f)\\) for all composable arrows \\(f,g\\) and \\(1\_{\text{dom } w} = (w, w^{-1})\\) and \\(1\_{\text{codom } w} = (w^{-1}, w)\\).

Let \\(\mathcal{C}\_{cf}\\) denote the full subcategory of [Cofibrant](#8410a73f-e0f4-4f94-bdc0-e8043b31b144) and [Fibrant](#ae1dbb9e-65a2-4528-b22b-5861beed9c7d) objects of \\(\mathcal{C}\\). Then we have

{{% theorem %}}
The inclusion functor \\(\cat{Ho}(\mathcal{C}\_{cf}) \to \cat{Ho}(\mathcal{C})\\) is equivalence of categories.
{{% /theorem %}}

{{% proposition %}}
Suppose \\(\mathcal{C}\\) is a model category. Then a map of \\(\mathcal{C}\_{cf}\\) is a weak equivalence if and only if it is a homotopy equivalence.
{{% /proposition %}}

Cf. [Model category](#faa405c2-1a5a-485a-83c5-d77e44887d5f), [Homotopy equivalence](#31efe2ba-5b31-4e3c-b7dc-c2800f302c44).

{{% theorem %}}
Suppose \\(\mathcal{C}\\) is a model category. Let \\(\gamma: \mathcal{C} \to \cat{Ho}(\mathcal{C})\\) denote the canonical functor. Let \\(Q, R\\) denote the cofibrant replacement and fibrant replacement functor.

1.  The inclusion \\(\mathcal{C}\_{cf} \to \mathcal{C}\\) induces an equivalence of categories \\(\mathcal{C}\_{cf}/ \sim \cong \cat{Ho}(\mathcal{C}\_{cf}) \to \cat{Ho}(\mathcal{C})\\).
2.  There are natural isomorphisms
    \\[\mathcal{C}(QRX, QRY)/ \sim \cat{Ho}(\mathcal{C})(\gamma X, \gamma Y) \cong \mathcal{C}(RQX, RQY)/ \sim\\]
    In addition, there is a natural isomorphism \\(\cat{Ho}(\mathcal{C})(\gamma X, \gamma Y) \cong \mathcal{C}(QX, RY)/ \sim\\).
3.  The functor \\(\gamma: \mathcal{C} \to \cat{Ho}(\mathcal{C})\\) identifies left or right homotopy maps.
4.  If \\(A \to B\\) is a map in \\(\mathcal{C}\\) such that \\(\gamma f\\) is an isomorphism in \\(\cat{Ho}(\mathcal{C})\\), then \\(f\\) is a weak equivalence.
{{% /theorem %}}

Cf. [Cofibrant replacement](#54d76b2c-186c-41de-b209-8dab6d10e5a1), [Fibrant replacement](#0353ceed-7528-4da7-ad35-cccc8a6e9037).

The **homotopy category** can also be defined for [Topological category](#51d4149b-b118-49a4-b426-fffc17d74015) \\(\mathcal{C}\\). It is then defined to have the same object \\(\mathcal{C}\\) and morphism is defined to be \\(\Hom\_{h \mathcal{C}}(X,Y) = \pi\_{0} {\rm Map}\_{\mathcal{C}}(X,Y)\\), or \\({\rm Map}\_{h \mathcal{C}}(X,Y) = [{\rm Map}\_{\mathcal{C}}(X,Y)]\\). The latter denote the equivalence class in [Category CGWH](#6fcf0c23-fe3f-4fde-80a3-6c6e6c4591c5) by inverting all [Weak homotopy equivalence](#3d692166-e320-45a7-b311-785db83d13a4), category \\(\mathcal{H}\\).

If \\(S\\) is a simplicial set, then the **homotopy category** \\(hS\\) is defined to be the homotopy category \\(h \mathfrak{C}[S]\\) of [Simplicial category](#98fc4969-941a-4afc-b76f-cbe31832374c) \\(\mathfrak{C}[S]\\). Here \\(\mathfrak{C}[S]\\) follows the definition of Higher Topos p. 21-22. You can also construct homotopy category by functor \\(\pi\\), p. 29 Higher Topos.


### Homotopy equivalence {#31efe2ba-5b31-4e3c-b7dc-c2800f302c44}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:22]</span></span>
A map \\(f\\) is a **homotopy equivalence** if there exists a map \\(f\\) such that \\(hf \sim 1\\) and \\(fh \sim 1\\).

Referenced: [Homotopy category](#ab32b639-e590-4e00-8bb9-0ef66574985a).


### Hopf algebra {#8b7067b7-b4d0-41a3-9b0e-4b427a188551}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 14:05]</span></span>
A bialgebra \\((A, \Delta, \epsilon)\\) equipped with an antiautomorphism \\(S: A \to A\\), that is \\(S(ab) = S(b)S(a)\\) and \\(\Delta(S(a)) = (S \otimes S)(\Delta^{op}(a))\\) is called a **Hopf algebra** if the following diagram is commutative

{{< figure src="/img/2021-11-04_17-56-31_screenshot.png" >}}

Referenced: [Comodule](#e3ffaafa-c6dd-4ecc-8595-af45c384421f), [Drinfeld double](#edf955e9-0d54-4d44-991c-53b5a864293c), [Dual pair](#388ef476-5a70-400b-ae35-b9a680ca1828), [Quasitriangular](#d5e59257-697d-41da-9289-17c44e2bc641), [Ribbon](#613f4702-5af0-4b49-94a7-50707e1c698e).


#### Dual pair {#388ef476-5a70-400b-ae35-b9a680ca1828}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 17:51]</span></span>
\\((H\_{1}, H\_{2}, \langle \rangle: H\_{1} \otimes H\_{2} \to k)\\) is a **dual pair** of [Hopf algebra](#8b7067b7-b4d0-41a3-9b0e-4b427a188551) if \\(\langle, \rangle\\) is nondegerate and \\[\langle lm, a \rangle = \langle l \otimes m , \Delta\_{H\_{2}}(a) \rangle\\] \\[\langle e, ab \rangle = \langle \Delta\_{H\_{1}}(e), a \otimes b \rangle\\] \\[\langle S\_{H\_{1}}(e), a \rangle = \langle e, S\_{H\_{2}}(a) \rangle\\] \\[\langle 1\_{H\_{1}}, a \rangle = \epsilon\_{H\_{2}}(a)\\] \\[\langle e, 1\_{H\_{2}} \rangle = \epsilon\_{H\_{1}}(e)\\]

However, the dual pair is not unique.

Referenced: [Drinfeld double](#edf955e9-0d54-4d44-991c-53b5a864293c).


#### Quasitriangular {#d5e59257-697d-41da-9289-17c44e2bc641}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:13]</span></span>
A [Hopf algebra](#8b7067b7-b4d0-41a3-9b0e-4b427a188551) \\((A, R \in A \hat{\otimes} A)\\) is called **quasitriangular** if
\\[\Delta^{op}(a) = R \Delta(a)R^{-1}\\]
\\[(\Delta \otimes \id)( R) = R\_{13}R\_{23} \in A^{\otimes 3}\\]
\\[(\id \otimes \Delta)( R) = R\_{13}R\_{12} \in A^{\otimes 3}\\]


#### Ribbon {#613f4702-5af0-4b49-94a7-50707e1c698e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:21]</span></span>
A [Hopf algebra](#8b7067b7-b4d0-41a3-9b0e-4b427a188551) is called **ribbon** if \\(v \in Z(A)\\) such that
\\[\Delta\_{v} = (v \otimes v)(R\_{21}R)^{-1} = (R\_{21}R)^{-1}(v \otimes v)\\]

Cf. [Ribbon category](#881b8932-3167-4f08-a14b-68c0dbed2d8b).


### Horn {#a88df829-205e-439f-bebb-e9c67f82ffbe}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:16]</span></span>
The **horn** \\(\Lambda^{n}\_{k}\\) is defined by

![](/img/2021-12-17_20-16-49_screenshot.png)
as coequalizer in \\(\bm{S}\\).


### Identity object {#3e4fd621-7f24-47d3-8afb-7032a6c59744}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 14:06]</span></span>
See [Tensor category](#3ff71704-ce2e-458d-88ae-adf48f6c89bf).

Referenced: [Dual](#37842b9c-6a24-4fc2-88d2-7fa2ceeab7ba).


### Initial {#77f36876-f102-4842-befc-18381b5ae1fe}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 15:25]</span></span>
See [Final](#545a1ee9-c2d2-4865-8eab-cda8993f53f2).


### Injective {#d0ff06a0-f68a-4d0a-9d73-f734bae8e43b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 21:32]</span></span>
An object \\(I\\) in an abelian category \\(\mathcal{A}\\) is **injective** if the functor \\(\Hom(-, I)\\) is exact. A complex \\(I^{\bullet}\\) is **injective** if all the term \\(I^{k}\\) are injective.

An abelian category **has enough injective objects** if any object \\(X\\) in \\(\mathcal{C}\\) is a suboject of an injective object \\(I\\) in \\(\mathcal{C}\\).


### &infin;-category {#51b2b46f-20be-48e9-8e4e-f91d2c5b4062}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 18:32]</span></span>
We follow Jacob Lurie's terminology. Joyal call then **quasi-categories**.

One of the possible candidate for **\\(\infty\\)-category** is [Topological category](#51d4149b-b118-49a4-b426-fffc17d74015), but it is quite hard to work with.

{{% definition %}}
An **\\(\infty\\)-category** is a simplicial set \\(K\\) which has the following property: for any \\(0 < i < n\\), any map \\(f\_{0}: \Lambda\_{i}^{n} \to K\\) admits an extension \\(f: \Delta^{n} \to K\\).
{{% /definition %}}

Cf. [Horn](#a88df829-205e-439f-bebb-e9c67f82ffbe).

It is also called **weak Kan complexes**. (Cf. [Kan complex](#b3f79ee9-0288-42af-803e-3ce5a4b612de))

The weak Kan complexes approach is equivalent to topological category approach.

The **functor** (Cf. [Functor](#49198b51-564c-4a87-b9d4-8e7adc6520d6)) between two \\(\infty\\)-categories is a functor between simplicial sets.

{{% proposition %}}
Let \\(K\\) be an arbitrary simplicial set, and \\(C\\) a \\(\infty\\)-category, the simplicial set \\({\rm Fun}(K, C)\\) is an \\(\infty\\)-category.
{{% /proposition %}}


### &infin;-category of spaces {#9e8aece8-7dfd-4ae4-84c4-5d0a9785f475}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 15:41]</span></span>
Let \\(\cat{Kan}\\) denote the full subcategory of \\(\cat{Set}\_{\Delta}\\) spanned by the collection of [Kan complex](#b3f79ee9-0288-42af-803e-3ce5a4b612de). Then \\(S = N(\cat{Kan})\\) the [Nerve](#e6e35013-4863-433f-9c36-74920db8ff6d) of \\(\cat{Kan}\\) is called **\\(\infty\\)-category of spaces**.


### (\infinity,n)-category {#18b56297-d573-4746-8f76-1f00cd9392b8}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 19:01]</span></span>
A **\\(\infty,n\\)-category** is a [\\(\infty\\)-category](#51b2b46f-20be-48e9-8e4e-f91d2c5b4062) with \\(k\\)-morphisms are invertible for \\(k > n\\).


### Internal adjunction {#06aa4443-e0fa-48fd-8481-512772deb1cd}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 14:45]</span></span>
With the notation of [Internal Hom](#3bf6cbe9-9de7-45a2-a023-f2fa62b25a29), we have **internal adjunction**  \\(\ihom(Z, \ihom(X,Y)) \ito \ihom(Z \otimes X, Y)\\).

Cf. [Tensor category](#3ff71704-ce2e-458d-88ae-adf48f6c89bf).


### Internal Hom {#3bf6cbe9-9de7-45a2-a023-f2fa62b25a29}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 14:07]</span></span>
If \\(\mathscr{C}^{op} \to \cat{Set}\\), \\(T \to \Hom(T \otimes X, Y)\\) is representable, then write the representing object \\(\ihom(X,Y)\\) called **internal Hom**. \\(\ihom(T \otimes X, Y) \cong \Hom(T, \ihom(X,Y))\\). So we have \\({\rm ev}\_{X,Y}: \ihom(X, Y) \otimes X \to Y\\) isomorphic to \\({\rm id}\_{\ihom(X,Y)}\\).

Cf. [Tensor category](#3ff71704-ce2e-458d-88ae-adf48f6c89bf).

Referenced: [Internal adjunction](#06aa4443-e0fa-48fd-8481-512772deb1cd).


### Invertible {#c69da2a1-7c82-4fe5-be2d-0ab8ae355df7}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 14:06]</span></span>
See [Tensor category](#3ff71704-ce2e-458d-88ae-adf48f6c89bf).


### Join {#f0057edd-94d7-4dd6-8701-6855b8d9586d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-25 Sat 21:07]</span></span>
Let \\(S\\) and \\(S'\\) be simplicial sets, then the simplicial set \\(S \star S'\\) is defined as
\\[(S \start S')(J) = \prod\_{J = I \cup I'} S(I) \times S'(I')\\]
That is
\\[(S \star S')\_{n} = S\_{n} \cup S'\_{n} \cup \cup\_{i + j = n - 1} S\_{i} \times S'\_{j}\\]

{{% proposition %}}
If \\(S\\) and \\(S'\\) are \\(\infty\\)-categories, then \\(S \star S'\\) is an \\(\infty\\)-category.
{{% /proposition %}}

Cf. [&infin;-category](#51b2b46f-20be-48e9-8e4e-f91d2c5b4062).


### Left homotopy {#6b34aa91-15a0-4f98-b8cf-204f99e14aa8}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 17:36]</span></span>
A **left homotopy** of maps \\(f,g: A \to B\\) is a commutative diagram
where \\((f, g)\\) is the map on the disjoint union. \\(\tilde{A}\\) is some choice of [Cylinder object](#4a135d4f-f34d-4ad4-bf2d-9514b1e56fcb).

{{< figure src="/img/2021-12-18_17-38-23_screenshot.png" >}}

A similar definition of **right homotopy** for [Path object](#36d8e6af-be8c-4c87-a6d6-dd3878671658).

Referenced: [Homotopic](#afbdfab2-f8f0-4f10-8ec8-57a6c3e2eac6).


### Left lifting property {#bfc249b7-0df1-49e6-8673-7f9375bbe77e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:08]</span></span>
See [Right lifting property](#19524edc-4d68-4c8a-9cb5-683dc703bf9d).


### Left Quillen functor {#9c9f99db-eb71-4a6a-86dc-5b585aa4763b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:32]</span></span>
A functor is a **left Quillen functor** if \\(F\\) is a left adjoint and preserves cofibrations and trivial cofibrations. A functor is a **right Quillen functor** if \\(U\\) is a right adjoint and preserves fibrations and trivial fibrations. We call \\((F, U, \phi)\\) **Quillen adjunction** if \\(F\\) is a left Quillen functor and \\(\phi\\) makes \\(U\\) a right adjoint of \\(F\\).

Referenced: [Quillen adjunction](#25787919-ae59-413e-9c29-72a6aebdbe9b), [Right Quillen functor](#63a83613-7eae-4f50-ab5b-207598dc4be5), [Total left derived functor](#323dfa8e-2e7e-451d-8fdd-6628b745a939).


### Limit {#f9c3cc0f-4513-49af-bd01-1dc06b2bddf0}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:40]</span></span>
See [Colimit](#136ef35b-144b-4e06-ae24-4db780022828).

Referenced: [Complete](#9b4f37d7-395c-4ed3-ade1-a12816dd52dc).


### Map {#35021e7d-6c03-4f48-9fa5-818243aa1cb3}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 17:51]</span></span>
For a category \\(\mathcal{C}\\), we can form a category \\(\cat{Map}(\mathcal{C})\\), whose objects are morphisms of \\(\mathcal{C}\\) and whose morphisms are commutative squares.

For \\(S\\) simplicial subset containing vertices \\(x\\) and \\(y\\). We define \\({\rm Map}\_{S}(x,y) = {\rm Map}\_{hS}(x,y) \in \mathcal{H}\\) to be the object of \\(\mathcal{H}\\) representing the space of maps from \\(x\\) to \\(y\\) in \\(S\\).


### Model category {#faa405c2-1a5a-485a-83c5-d77e44887d5f}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:38]</span></span>
A **model structure** on a category is three classes of morphisms called **cofibrations**, **fibrations**, and **weak equivalences**, satisfying

1.  The category is closed under all finite limits and colimits.
2.  Suppose that the following diagram commutes,

    ![](/img/2021-12-17_20-40-04_screenshot.png)
    if any two \\(f, g\\) and \\(h\\) are weak equivalence, then so is the third.
3.  If \\(f\\) is a [Retract](#08857836-b213-4f07-a066-55d6f3e98e0e) of \\(g\\) and \\(g\\) is a weak ewquivalence, fibration or cofibration, then so if \\(f\\).
4.  Suppose that we are given a commutative solid arrow diagram

    ![](/img/2021-12-17_20-43-02_screenshot.png)
    where \\(i\\) is a cofibration and \\(p\\) is a fibration. Then the dotted arrow exists, making the diagram commute, if either \\(i\\) or \\(p\\) is also a weak equivalence.
5.  Any map \\(f: X \to Y\\) may be factored \\(f = p \circ i\\), where \\(p\\) is fibration and \\(i\\) is trivial cofibration and \\(f = q \circ j\\) where \\(q\\) is a trivial fibration and \\(j\\) a cofibration. (We can further require [Functorial factorization](#bedd7c88-47ad-48e8-8a6d-f820fb950061))

A **model category** is a category with all small limits and colimits together with a model structure.

{{% remark %}}
The definition of a model category here differs from definition in Quillen's original definition. It is roughly called **closed model category** there. For more differences, you can see book Model categories by Hover.
{{% /remark %}}

If \\(\mathcal{C}\\) is a model category, then it has an initial object, the colimit of the empty diagram, and a terminal object, the limit of the empty diagram.

Referenced: [Cylinder object](#4a135d4f-f34d-4ad4-bf2d-9514b1e56fcb), [Homotopy category](#ab32b639-e590-4e00-8bb9-0ef66574985a), [Cofibrant](#8410a73f-e0f4-4f94-bdc0-e8043b31b144), [Path object](#36d8e6af-be8c-4c87-a6d6-dd3878671658).


#### Cofibrant {#8410a73f-e0f4-4f94-bdc0-e8043b31b144}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:00]</span></span>
An object of [Model category](#faa405c2-1a5a-485a-83c5-d77e44887d5f) is called **cofibrant** if the map from the initial object \\(0\\) to it is a cofibration.

An object is called **fibrant** if the map from it to the terminal object is a fibration.

Referenced: [Homotopy category](#ab32b639-e590-4e00-8bb9-0ef66574985a), [Fibrant](#ae1dbb9e-65a2-4528-b22b-5861beed9c7d), [Cofibrant replacement](#54d76b2c-186c-41de-b209-8dab6d10e5a1), [Quillen equivalence](#7490ba00-8f56-404d-b8c3-e085e9dbc0c3), [Total left derived functor](#323dfa8e-2e7e-451d-8fdd-6628b745a939).


#### Fibrant {#ae1dbb9e-65a2-4528-b22b-5861beed9c7d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:04]</span></span>
See [Cofibrant](#8410a73f-e0f4-4f94-bdc0-e8043b31b144).

Referenced: [Homotopy category](#ab32b639-e590-4e00-8bb9-0ef66574985a), [Quillen equivalence](#7490ba00-8f56-404d-b8c3-e085e9dbc0c3).


#### Fibrant replacement {#0353ceed-7528-4da7-ad35-cccc8a6e9037}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:10]</span></span>
See [Cofibrant replacement](#54d76b2c-186c-41de-b209-8dab6d10e5a1).

Referenced: [Homotopy category](#ab32b639-e590-4e00-8bb9-0ef66574985a).


#### Cofibrant replacement {#54d76b2c-186c-41de-b209-8dab6d10e5a1}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:08]</span></span>
By applying factorization to \\(0 \to X\\), we get a **cofibrant replacement** functor \\(X \to QX\\) ([Functorial factorization](#bedd7c88-47ad-48e8-8a6d-f820fb950061) is required here) such that \\(QX\\) is [Cofibrant](#8410a73f-e0f4-4f94-bdc0-e8043b31b144) and \\(QX \to X\\) is a trivial fibration.

Similar, we have **fibrant replacement** functor \\(X \to RX\\) by applying factorization to \\(X \to 1\\).

Referenced: [Homotopy category](#ab32b639-e590-4e00-8bb9-0ef66574985a), [Fibrant replacement](#0353ceed-7528-4da7-ad35-cccc8a6e9037).


### Monoid {#7c939378-63cd-4559-a8b7-9836c0943448}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 14:17]</span></span>
A **monoid** is a group without inverse. In other words, a group is a monoid with inverse.


### Monoidal category {#e5efd020-d8bd-4ef0-88b6-af567e6d7d43}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 18:07]</span></span>
A **monoidal category** is a category \\(C\\) with \\(\otimes\\) which has [Associativity constraint](#7952eb96-5003-45e9-b48d-e7764d411f07) and there exists unit \\(1 \in \mathop{Ob}( C)\\) such that \\(1 \otimes V \cong V \otimes 1 \cong V\\).

A **monoidal functor** is a functor respect the monoid structure.

Cf. [Tensor category](#3ff71704-ce2e-458d-88ae-adf48f6c89bf). In fact, I don't know their differences.

Referenced: [Strict](#c62abb35-85e2-4694-8fa5-c71cd791a5f8), [Pivotal](#bc1d556f-67f5-4b27-9c7b-00e618882a1e), [Braided](#f66319f5-91f0-4cb7-a02c-082f39227cd2), [Rigid braided monoidal category](#a5cb1377-0de5-4f2a-ac4e-b97a6656390c).


#### Strict {#c62abb35-85e2-4694-8fa5-c71cd791a5f8}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 18:10]</span></span>
A [Monoidal category](#e5efd020-d8bd-4ef0-88b6-af567e6d7d43) is called **strict** if \\((A \otimes B) \otimes C = A \otimes (B \otimes C)\\) and the same is for morphisms.

{{% proposition %}}
Every monoidal category \\(C\\) is naturally equivalent to a strict monoidal category \\(C^{str}\\)
{{% /proposition %}}


#### Pivotal {#bc1d556f-67f5-4b27-9c7b-00e618882a1e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 17:51]</span></span>
A [Rigid](#51c7cfa0-c077-4e1f-aa58-e7e9678f4cda) [Monoidal category](#e5efd020-d8bd-4ef0-88b6-af567e6d7d43) is called **pivotal** if there exists a system of functorial isomorphism
\\[\mu = \\{\mu\_{X}: X \to X^{\*\*}\\}\\] such that
\\[\mu\_{X \otimes Y} = \mu\_{X} \otimes \mu\_{Y}\\]

Referenced: [Spherical](#b397b3c1-e91e-4a0e-a942-0d8d9733f4c9).


#### Trace {#1161327f-b97b-4896-95c7-be4d0ccdb03e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:01]</span></span>
We introduce the **categorical trace** by
\\[\tr\_{f}^{L} = 1 \xrightarrow{i} V \otimes V^{\*} \xrightarrow{f \otimes \id} V \otimes V^{\*} \xrightarrow{\mu\_{V} \otimes \id} V^{\*\*} \otimes V^{\*} \xrightarrow{e\_{V^{\*}}} 1\\]
Similarly, we can define the right trace \\(\tr\_{f}^{R}\\).

We have following properties similar to classical trace
\\(\tr^{L,R}(fg) = \tr^{L,R}(gf)\\) and \\(\tr^{L,R}(f \otimes g) = \tr^{L,R}(f) \otimes \tr^{L,R}(g)\\).

Referenced: [Spherical](#b397b3c1-e91e-4a0e-a942-0d8d9733f4c9), [Dimension](#83f8cc7d-03c1-4e72-b4cb-9de98a3ad5ac).


#### Spherical {#b397b3c1-e91e-4a0e-a942-0d8d9733f4c9}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:07]</span></span>
A [Pivotal](#bc1d556f-67f5-4b27-9c7b-00e618882a1e) category is **spherical** if for any \\(V\\) and \\(f: V \to V\\), we have \\(\tr^{L}(f) = \tr^{R}(f)\\).

Cf. [Trace](#1161327f-b97b-4896-95c7-be4d0ccdb03e).

Referenced: [Dimension](#83f8cc7d-03c1-4e72-b4cb-9de98a3ad5ac).


#### Dimension {#83f8cc7d-03c1-4e72-b4cb-9de98a3ad5ac}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:07]</span></span>
In [Spherical](#b397b3c1-e91e-4a0e-a942-0d8d9733f4c9) category we can define the **categorical dimension** by \\(\dim V = \tr(\id\_{V})\\) since the two [Traces](#1161327f-b97b-4896-95c7-be4d0ccdb03e) are the same.


#### Braided {#f66319f5-91f0-4cb7-a02c-082f39227cd2}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:09]</span></span>
A [Monoidal category](#e5efd020-d8bd-4ef0-88b6-af567e6d7d43) is **braided** if there exists \\(c = \\{c\_{V,W}\\}\\), \\(c\_{V,W}: V \otimes W \to W \otimes V\\) with some compatibility conditions.

Referenced: [Rigid braided monoidal category](#a5cb1377-0de5-4f2a-ac4e-b97a6656390c).


### Natural transformation {#95ada66a-0528-4b01-8621-b22daa0fd138}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 18:56]</span></span>
A **natural transformation** \\(\alpha\\) between two [Functors](#49198b51-564c-4a87-b9d4-8e7adc6520d6) \\(F,G: \mathcal{C} \to \mathcal{D}\\) is a collection of morphisms \\(\\{\alpha\_{C}: F( C) \to G( C)\\}\_{C \in \mathcal{C}}\\) satisfying the commutative diagram

{{< figure src="/img/2021-12-19_18-57-36_screenshot.png" >}}


### Nerve {#e6e35013-4863-433f-9c36-74920db8ff6d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 19:35]</span></span>
To any category \\(\mathcal{C}\\), we can associate a [Simplicial set](#7f7b56bd-7f4f-4dd4-8aa1-e57a14f6e423) \\(N(\mathcal{C})\\) called **nerve** of \\(\mathcal{C}\\). For each \\(n \geq 0\\), we let \\(N(\mathcal{C})\_{n} = {\rm Map}\_{\cat{Set}\_{\Delta}}(\Delta^{n}, N(\mathcal{C}))\\) denote the set of all functors \\([n] \to \mathcal{C}\\).

The objects of \\(\mathcal{C}\\) are simply the **vertices** of \\(N(\mathcal{C})\\).

There exists a useful characterisation of the nerve.

{{% proposition %}}
Let \\(K\\) be a simplicial set. Then the following conditions are equivalent:

1.  There exists a small category \\(\mathcal{C}\\) and an isomorphism \\(K \cong N(\mathcal{C})\\).
2.  For each \\(0 < i < n\\) and each diagram

    ![](/img/2021-12-19_19-58-04_screenshot.png)
    there exists a unique dotted arrow rendering the diagram commutative.
{{% /proposition %}}

{{% proposition %}}
The nerve functor \\(\cat{Cat} \to \cat{Set}\_{\Delta}\\) is right adjoint to the functor \\(h: \cat{Set}\_{\Delta} \to \cat{Cat}\\), which associates to every simplicial set \\(S\\) its homotopy category \\(hS\\).
{{% /proposition %}}

Cf. [Homotopy category](#ab32b639-e590-4e00-8bb9-0ef66574985a).


### Ordinal number category {#432a1fd0-fdd7-434d-83c8-bfc2aa2743c0}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-12 Sun 21:29]</span></span>
See [Simplicial set](#7f7b56bd-7f4f-4dd4-8aa1-e57a14f6e423).


### Overcategory {#d44988e3-fc18-4f94-be80-8ac43d54aa9c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-25 Sat 21:40]</span></span>
See the following diagram of **overcategory**

{{< figure src="/img/2021-12-25_21-40-19_screenshot.png" >}}

For any category \\(C'\\), we have bijection
\\[\Hom(C', C\_{/X}) \con \Hom\_{x}(C' \star [0], C)\\]
where \\(x: [0] \to [C]\\) is the canonical functor.

Cf. [Join](#f0057edd-94d7-4dd6-8701-6855b8d9586d).

{{% proposition %}}
Let \\(S\\) and \\(K\\) be simplicial sets, and \\(p: K \to S\\) an arbitrary map. There exists a simplical set \\(S\_{/p}\\) with the following universal property:
\\[\Hom\_{\cat{Set}\_{\Delta}}(Y, S\_{/p}) = \Hom\_{p}(Y \star K, S)\\]
where the subscript on the right side, means \\(f|\_{K} = p\\).
{{% /proposition %}}

One defines \\((S\_{/p})\_{n}\\) to be \\(\Hom\_{p}(\Delta^{n} \star K, S)\\).

{{% proposition %}}
\\(C\_{/p}\\) is an \\(\infty\\)-category.
{{% /proposition %}}

{{% proposition %}}
\\(N( C)\_{/X} \cong N(C\_{/X})\\)
{{% /proposition %}}


### Path object {#36d8e6af-be8c-4c87-a6d6-dd3878671658}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:29]</span></span>
Let \\(\bm{S}\_{f}\\) be the full subcategory of [Simplicial set](#7f7b56bd-7f4f-4dd4-8aa1-e57a14f6e423) category (or [Closed model category](#faa405c2-1a5a-485a-83c5-d77e44887d5f)) whose objects are the [Kan complex](#b3f79ee9-0288-42af-803e-3ce5a4b612de). A **path object** for \\(X \in \bm{S}\_{f}\\) is a commutative diagram

{{< figure src="/img/2021-12-17_20-36-10_screenshot.png" >}}

where \\(s\\) is a [Weak equivalence](#dcf4ac56-1504-4a63-a707-8319f629fc10) and \\(d\_{0}, d\_{1}\\) are [Kan fibrations](#24c4c625-6639-4558-95ed-fbb6015188fa) (in fact necessarily [Trivial fibrations](#6d2ae601-9987-4e84-9e9b-c797251f498c)).

Cf. [Cylinder object](#4a135d4f-f34d-4ad4-bf2d-9514b1e56fcb).

Referenced: [Left homotopy](#6b34aa91-15a0-4f98-b8cf-204f99e14aa8).


### Pointed {#21125f57-9f82-4442-bac6-4b748619f4a0}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:05]</span></span>
An category is called **pointed** if the map from the initial object to the termninal object is an isomorphism.


### Quillen adjunction {#25787919-ae59-413e-9c29-72a6aebdbe9b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:35]</span></span>
Cf. [Left Quillen functor](#9c9f99db-eb71-4a6a-86dc-5b585aa4763b).

Referenced: [Quillen equivalence](#7490ba00-8f56-404d-b8c3-e085e9dbc0c3).


### Quillen equivalence {#7490ba00-8f56-404d-b8c3-e085e9dbc0c3}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:41]</span></span>
A [Quillen adjunction](#25787919-ae59-413e-9c29-72a6aebdbe9b) \\((F, U, \phi): \mathcal{C} \to \mathcal{D}\\) is called a **Quillen equivalence** if and only if, for all [Cofibrant](#8410a73f-e0f4-4f94-bdc0-e8043b31b144) \\(X\\) in \\(\mathcal{C}\\) and [Fibrant](#ae1dbb9e-65a2-4528-b22b-5861beed9c7d) \\(Y\\) in \\(\mathcal{D}\\), a map \\(f: FX \to Y\\) is a weak equivalence in \\(\mathcal{D}\\) if and only if \\(\phi(f): X \to UY\\) is a weak equivalence in \\(\mathcal{C}\\).


### Reflexive {#95bcb049-bebc-40e2-8825-3cf80620f211}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 14:47]</span></span>
An object \\(X\\) is called **reflexive** if \\(i\_{X}: X \ito X^{\vee \vee}\\).

Cf. [Dual](#37842b9c-6a24-4fc2-88d2-7fa2ceeab7ba), [Tensor category](#3ff71704-ce2e-458d-88ae-adf48f6c89bf).

Referenced: [Rigid](#51c7cfa0-c077-4e1f-aa58-e7e9678f4cda).


### Representable {#fa11fd46-28b4-4155-b142-529c85b659c3}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 16:45]</span></span>
We say that a functor \\(F: \cat{Sch} \to \cat{Sets}\\) is **representable by a scheme** if there exists a scheme \\(X\\) and an isomorphism of functors \\(F \cong h\_{X}\\). A morphism \\(F \to G\\) of functors is **representable by schemes** if for any map \\(S \to G\\) from a scheme \\(S\\), the fiber product \\(F \times\_{G} S\\) is representable by a scheme.

A morphism \\(F \to G\\) is **open immersion** if for any morphism \\(S \to G\\) from a scheme \\(S\\), \\(F \times\_{G} S\\) is representable by an open subscheme of \\(S\\).

We say that a set of open subfunctors \\(\\{F\_{i}\\}\\) is a **Zariski-open cover** of \\(F\\) if for any morphism \\(S \to F\\) from a scheme \\(S\\), \\(\\{F\_{i} \times\_{F} S\\}\\) is a Zariski-open cover of \\(S\\).

If we have\\(F \cong h\_{X}\\), then the **universal family** of \\(F\\) is the object \\(U \in F(X)\\) corresponding to the identity morphism \\(\id\_{X}\\)

A morphism \\(X \to Y\\) of [Prestacks](#f368a933-d735-415d-b8f1-3b980077ea40) over \\(\cat{Sch}\\) is **representable** if for every morphism \\(V \to Y\\) form a scheme \\(V\\), the fiber product \\(X \times\_{Y} V\\) is an [Algebraic space](#e881dc3c-0ab3-461b-b4eb-ff7a84203779).

.


### Retract {#08857836-b213-4f07-a066-55d6f3e98e0e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 17:44]</span></span>
A map in \\(\mathcal{C}\\) is a **retract** of a map \\(g \in \mathcal{C}\\) if and only if there is a commutative diagram of the form

{{< figure src="/img/2021-12-18_17-46-06_screenshot.png" >}}

where horizontal composites are identities.

Referenced: [Model category](#faa405c2-1a5a-485a-83c5-d77e44887d5f).


### Ribbon category {#881b8932-3167-4f08-a14b-68c0dbed2d8b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:19]</span></span>
A **ribbon category** is a [Rigid braided monoidal category](#a5cb1377-0de5-4f2a-ac4e-b97a6656390c) with \\(v = \\{v\_{X}\\}\\) such that
\\[v\_{X \otimes Y} = (v\_{X} \otimes v\_{Y}) c\_{XY}^{-1}c\_{YX}^{-1}\\]

Referenced: [Ribbon](#613f4702-5af0-4b49-94a7-50707e1c698e).


### Right lifting property {#19524edc-4d68-4c8a-9cb5-683dc703bf9d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:04]</span></span>
A map \\(p: X \to Y\\) is said to have the **right lifting property** (RLP) with repsect to a class \\(M\\) is in every solid arrow diagram

![](/img/2021-12-17_20-05-45_screenshot.png)
with \\(i \in M\\) the dotted arrow exists making the diagram commute.

The **left lifting property** is defined by same diagram with \\(i\\) and \\(p\\) in definition changed.

Referenced: [Left lifting property](#bfc249b7-0df1-49e6-8673-7f9375bbe77e), [Kan fibration](#24c4c625-6639-4558-95ed-fbb6015188fa).


### Right morphism {#a329c9b6-e2d0-41da-b04e-78107175b080}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-25 Sat 20:50]</span></span>
For \\(S\\) [&infin;-category](#51b2b46f-20be-48e9-8e4e-f91d2c5b4062), we define **right morphism** from \\(x\\) to \\(y\\) to be a new simplicial set \\(\Hom\_{S}^{R}(x,y)\\), by letting \\(\Hom\_{\cat{Set}\_{\Delta}}(\Delta^{n}, \Hom\_{S}^{R}(x,y))\\) denote the set of all \\(z: \Delta^{n + 1} \to S\\) such that \\(z| \Delta^{n + 1} = y\\) and \\(z| \Delta^{0, \cdots, n}\\) is a constant simplex at the vertex \\(x\\).

{{% proposition %}}
The simplicial set \\(\Hom\_{C}^{R}(x,y)\\) is a Kan complex.
{{% /proposition %}}

Cf. [Kan complex](#b3f79ee9-0288-42af-803e-3ce5a4b612de).


### Right Quillen functor {#63a83613-7eae-4f50-ab5b-207598dc4be5}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:34]</span></span>
See [Left Quillen functor](#9c9f99db-eb71-4a6a-86dc-5b585aa4763b).


### Rigid braided monoidal category {#a5cb1377-0de5-4f2a-ac4e-b97a6656390c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:10]</span></span>
A **rigid braided monoidal category** is a [Rigid](#51c7cfa0-c077-4e1f-aa58-e7e9678f4cda) [Braided](#f66319f5-91f0-4cb7-a02c-082f39227cd2) [Monoidal category](#e5efd020-d8bd-4ef0-88b6-af567e6d7d43) such that
\\[c\_{A^{\*}B^{\*}} = (c\_{B,A})^{\*}\\]

Referenced: [Ribbon category](#881b8932-3167-4f08-a14b-68c0dbed2d8b).


### Saturated {#adc11885-8719-4edb-996f-e419bd07e64e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:02]</span></span>
A class \\(M\\) of monomorphisms of \\(\cat{S}\\) is said to be **saturated** if the following conditions are satisfied:

1.  All isomorphisms are in \\(M\\).
2.  \\(M\\) is closed under pushout.
3.  Each retract of an element of \\(M\\) is in \\(M\\).
4.  \\(M\\) is closed under countable compositions and arbitrary direct sums.


### Simplicial category {#98fc4969-941a-4afc-b76f-cbe31832374c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-25 Sat 20:40]</span></span>
A **simplicial category** is a category which is enriched over the category \\(\cat{Set}\_{\Delta}\\) of simplical sets. The category of simplicial categories will be denoted by \\(\cat{Cat}\_{\Delta}\\).

A functor \\(\mathcal{C} \to \mathcal{C}'\\) between simplicial categories is an **equivalence** if the induced functor \\(h \mathcal{C} \to h \mathcal{C}'\\) is an equivalence of \\(\mathcal{H}\\)-enriched categories.


### Simplicial group {#6b3083af-22b7-4e8b-ac87-cac81ca028a8}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:00]</span></span>
A **simplicial group** is a simplical object in the category of groups, that is a contravariant functor from \\(\bm{\Delta}\\) to the category \\(\cat{Group}\\).


### Simplicial homotopy {#1dba3777-e013-410a-92c7-f4cb919f71be}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:17]</span></span>
Let \\(f, g: K \to X\\) be simplicial maps. We say that there is a **simplicial homotopy** \\(f \cong g\\) from \\(f\\) to \\(g\\) if there is a commutative diagram

{{< figure src="/img/2021-12-17_20-19-04_screenshot.png" >}}

The map \\(h\\) is called **homotopy**.

This is the analog of topological [Homotopy](#4badc09a-e75b-4851-bc77-90d46eea46fd).


### Simplicial homotopy group {#fec6281b-1b84-40e6-9328-202c44139152}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:20]</span></span>
Let \\(X\\) be a [Fibrant](#e7c7068b-fc3b-49c6-8c81-c26cfdb74497) [Simplicial set](#7f7b56bd-7f4f-4dd4-8aa1-e57a14f6e423) and \\(v \in X\_{0}\\) be a vertex of \\(X\\). Define the **simplicial homotopy group** \\(\pi\_{n}(X, v), n \geq 1\\) to be the set of homotopy classes of maps \\(\alpha: \Delta^{n} \to X (\text{rel } \partial \Delta^{n})\\) fit into the diagram

{{< figure src="/img/2021-12-17_20-21-55_screenshot.png" >}}

\\(\pi\_{0}(X)\\) is usually called **path components** of \\(X\\). The simplicial set \\(X\\) is said to be connected if \\(\pi\_{0}(X)\\) is trivial.

{{% proposition %}}
\\(\pi\_{n}(X, v)\\) is a group for \\(n \geq 1\\) and abelian group for \\(n \geq 2\\).
{{% /proposition %}}

The group law is given by \\([\alpha] \* [\beta]\\) to be \\(\dif\_{n}(\omega)\\) of the extension

![](/img/2021-12-17_20-25-34_screenshot.png)
where \\((v\_{0}, \cdots, v\_{n - 1}, , v\_{n+1}) = (v, v, \cdots, v, \alpha, , \beta)\\).

Cf. [Homotopy group](#492ddb93-4c8a-434e-9757-14fdbd6102f1).


### Simplicial set {#7f7b56bd-7f4f-4dd4-8aa1-e57a14f6e423}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:02]</span></span>
Let \\(\bm{\Delta}\\) be the category of finite ordianl numbers with order preserving maps between them. The object of \\(\bm{\Delta}\\) is denoted by \\(\bm{n}\\) which is a category denoted by \\(0 \to 1 \to 2 \to \cdots \to n\\), where identity and composition morphism is omitted. \\(\bm{\Delta}\\) is called **ordinal number category**. A **simplicial set** is a contravariant [Functor](#49198b51-564c-4a87-b9d4-8e7adc6520d6) \\(X: \bm{\Delta^{op}} \to \cat{Sets}\\).

One of the important example is standard covarinat functor \\(\bm{\Delta} \to \cat{Top}\\) mapping \\(\bm{n}\\) to **standard n-simplex** \\(\abs{\Delta^{n}}\\) with
\\[\abs{\Delta^{n}} = \\{(t\_{0}, \cdots, t\_{n}) \in \RR^{n + 1} \mid \sum\_{i = 0}^{n}t\_{i} = 1, t\_{i} \geq 0\\}\\]

In this language, the [Singular homology](#bd775417-5818-4811-9aa6-e3819b0e3fd1) can be describe by **singular set** \\(S(T)\\)
\\[\bm{n} \to \hom(\abs{\Delta^{n}, T})\\]

We have morphism in \\(\bm{\Delta}\\) \\(d\_{i}: \bm{n - 1} \to \bm{n}\\) (**cofaces**) and \\(s^{j}: \bm{n + 1} \to \bm{n}\\) (**codegeneracies**), defined as
\\[d^{i}(0 \to 1 \to \cdots \to n - 1) = (0 \to 1 \to \cdots \to i - 1 \to i + 1 \to \cdots \to n)\\]
\\[s^{j}(0 \to 1 \to \cdots \to n + 1) = (0 \to 1 \to \cdots \to j \to j \to \cdots \to n)\\]

We have **cosimplicial identities**

\begin{align\*} \begin{cases} d^{j}d^{i} = d^{i}d^{j - 1} & \text{if } i < j \\\\ s^{j}d^{i} = d^{i}s^{j - 1} & \text{if } i < j \\\\ s^{j}d^{j} =1 = s^{j}d^{j+1} &\\\\ s^{j}d^{i} = d^{i - 1} s^{j} & \text{if } i > j + 1 \\\\ s^{j}d^{i} = s^{i}s^{j+1} & \text{if } i \leq j \\\\ \end{cases} \end{align\*}

We have similar simplicial identities for \\(Y\_{n}\\), where \\(Y\\) is a simplicial set.

Referenced: [Classifying space](#8274f12e-0561-404b-907f-0568cdcb95cf), [Ordinal number category](#432a1fd0-fdd7-434d-83c8-bfc2aa2743c0), [Path object](#36d8e6af-be8c-4c87-a6d6-dd3878671658), [Simplicial homotopy group](#fec6281b-1b84-40e6-9328-202c44139152), [Realization](#65f00d44-6834-4d5c-a610-d892b2c60388), [Fibrant](#e7c7068b-fc3b-49c6-8c81-c26cfdb74497), [Weak equivalence](#dcf4ac56-1504-4a63-a707-8319f629fc10).


#### Realization {#65f00d44-6834-4d5c-a610-d892b2c60388}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 19:52]</span></span>
A **realization** of a [Simplicial set](#7f7b56bd-7f4f-4dd4-8aa1-e57a14f6e423) \\(X\\), \\(\abs{X}\\), is defined to be
\\[\abs{X} = \varinjlim\_{\Delta^{n} \to X} \abs{\Delta^{n}}\\]
It is a functor from simplicial set category to topology space category (in fact \\(\cat{CGWH}\\), [Category CGWH](#6fcf0c23-fe3f-4fde-80a3-6c6e6c4591c5)). In fact, we have adjoint property
\\[\hom\_{\cat{Top}}(\abs{X}, Y) \cong \hom\_{\cat{S}} (X, SY)\\]


#### Kan fibration {#24c4c625-6639-4558-95ed-fbb6015188fa}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 19:56]</span></span>
A map \\(p: X \to Y\\) of simplicial set is called **Kan fibration** if it satisfies the extension condition that for every commutative diagram

![](/img/2021-12-17_19-57-49_screenshot.png)
there exists \\(\theta: \Delta \to X\\) making the diagram commute.

Kan fibration is the categorical analog of [Fibration](#7a557249-6a76-40ae-9e38-231b828a22e9).

{{% proposition %}}
A **Kan fibration** is a map which has the right lifting property with respect to all anodyne extensions.
{{% /proposition %}}

Cf. [Anodyne extension](#f79b88b4-95df-47ff-b4a6-bed2cb652d02)， [Right lifting property](#19524edc-4d68-4c8a-9cb5-683dc703bf9d).

Referenced: [Path object](#36d8e6af-be8c-4c87-a6d6-dd3878671658), [Fibrant](#e7c7068b-fc3b-49c6-8c81-c26cfdb74497), [Trivial fibration](#6d2ae601-9987-4e84-9e9b-c797251f498c).


#### Fibrant {#e7c7068b-fc3b-49c6-8c81-c26cfdb74497}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 19:58]</span></span>
A [Simplicial set](#7f7b56bd-7f4f-4dd4-8aa1-e57a14f6e423) is called **fibrant** or **Kan complex** if the canonical map \\(Y \to \*\\) is a [Kan fibration](#24c4c625-6639-4558-95ed-fbb6015188fa).

Referenced: [Simplicial homotopy group](#fec6281b-1b84-40e6-9328-202c44139152), [Kan complex](#b3f79ee9-0288-42af-803e-3ce5a4b612de), [Weak equivalence](#dcf4ac56-1504-4a63-a707-8319f629fc10).


#### Kan complex {#b3f79ee9-0288-42af-803e-3ce5a4b612de}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:30]</span></span>
See [Fibrant](#e7c7068b-fc3b-49c6-8c81-c26cfdb74497).

Referenced: [Path object](#36d8e6af-be8c-4c87-a6d6-dd3878671658).


#### Weak equivalence {#dcf4ac56-1504-4a63-a707-8319f629fc10}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:31]</span></span>
The map \\(f: X \to Y\\) between [Fibrant](#e7c7068b-fc3b-49c6-8c81-c26cfdb74497) [Simplicial sets](#7f7b56bd-7f4f-4dd4-8aa1-e57a14f6e423) is called **weak equivalence** if

1.  For each vertex \\(x\\) of \\(X\\) the induced map \\(f\_{\*}: \pi\_{i}(X, x) \to \pi\_{i}(Y, f(x))\\) is an isomorphism for \\(i \geq 1\\).
2.  The map \\(f\_{\*}: \pi\_{0}(X) \to \pi\_{0}(Y)\\) is a bijection.

Cf. [Weak homotopy equivalence](#3d692166-e320-45a7-b311-785db83d13a4).

Referenced: [Path object](#36d8e6af-be8c-4c87-a6d6-dd3878671658), [Trivial fibration](#6d2ae601-9987-4e84-9e9b-c797251f498c).


#### Trivial fibration {#6d2ae601-9987-4e84-9e9b-c797251f498c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-17 Fri 20:33]</span></span>
A map \\(p: X \to Y\\) in \\(\bm{S}\_{f}\\) is called **trivial fibration** if it is a [Kan fibration](#24c4c625-6639-4558-95ed-fbb6015188fa) and a [Weak equivalence](#dcf4ac56-1504-4a63-a707-8319f629fc10).

Referenced: [Path object](#36d8e6af-be8c-4c87-a6d6-dd3878671658).


### <span class="org-todo todo TODO">TODO</span> Stable &infin;-category {#308c0037-45b1-4d4f-9120-68b66dba5d43}


### Strongly final {#7755eb1c-0e38-43e1-8244-df3185a1dec3}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 15:25]</span></span>
Let \\(\mathcal{C}\\) be a [Simplicial set](#7f7b56bd-7f4f-4dd4-8aa1-e57a14f6e423), then a vertex \\(X\\) is **strongly final** if the projection \\(\mathcal{C}\_{/X} \to \mathcal{C}\\) is a trivial fibration of simplicial sets. That is for any map \\(\f\_{0}: \partial \Delta^{n} \to \mathcal{C}\\) such that \\(f\_{0}(n) = X\\) can be extended to a map \\(f: \Delta^{n} \to \mathcal{C}\\).

{{% proposition %}}
Let \\(\mathcal{C}\\) be an \\(\infty\\)-category containing an object \\(Y\\). The object \\(Y\\) is strongly final if and only if for every object \\(X \in \mathcal{C}\\) the Kan complex \\(\Hom\_{\mathcal{C}}^{R}(X, Y)\\) is contractible.
{{% /proposition %}}

Cf. [&infin;-category](#51b2b46f-20be-48e9-8e4e-f91d2c5b4062).

{{% corollary %}}
Let \\(\mathcal{C}\\) be a simplicial set. Every strongly final object of \\(\mathcal{C}\\) is final object of \\(\mathcal{C}\\). The converse holds if \\(\mathcal{C}\\) is an \\(\infty\\)-category.
{{% /corollary %}}

Cf. [Final](#545a1ee9-c2d2-4865-8eab-cda8993f53f2).

The discussion can be generalized to [Initial](#77f36876-f102-4842-befc-18381b5ae1fe).


### Tensor category {#3ff71704-ce2e-458d-88ae-adf48f6c89bf}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 19:04]</span></span>
A **tensor category** is data \\((\mathscr{C}, \otimes, \phi, \psi)\\) where \\(\phi\\) is the [Associativity constraint](#7952eb96-5003-45e9-b48d-e7764d411f07) and \\(\psi\\) the [Commutativity constraint](#3292ae27-0e60-4f47-9a5f-ea3cf3ed8a98).

The **identity object** in tensor cateogry is a pair \\((U, u)\\) where \\(U \in \mathscr{C}\\) with \\(u: U \ito U \otimes U\\) such that \\(U \otimes -\\) is an equivalence.

The object \\(L\\) is called **invertible** if \\(L \otimes -\\) is an equivalence. If \\(L\\) is invertible, then \\(L\\) has inverse with \\(\delta: L \otimes L^{-1} \ito U\\).

Referenced: [Dual](#37842b9c-6a24-4fc2-88d2-7fa2ceeab7ba), [Fibre functor](#dee5d2a3-1cdd-4a73-9eb7-dba2e96aa45b), [Identity object](#3e4fd621-7f24-47d3-8afb-7032a6c59744), [Internal adjunction](#06aa4443-e0fa-48fd-8481-512772deb1cd), [Internal Hom](#3bf6cbe9-9de7-45a2-a023-f2fa62b25a29), [Invertible](#c69da2a1-7c82-4fe5-be2d-0ab8ae355df7), [Monoidal category](#e5efd020-d8bd-4ef0-88b6-af567e6d7d43), [Reflexive](#95bcb049-bebc-40e2-8825-3cf80620f211), [Rigid](#51c7cfa0-c077-4e1f-aa58-e7e9678f4cda), [Tensor functor](#cf063348-e088-4ec0-8e7a-59e5de57ccaf), [Criterion for category being representation category](#4357d757-e6bd-495c-a863-e8cef3943c0b).


#### Rigid {#51c7cfa0-c077-4e1f-aa58-e7e9678f4cda}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 14:48]</span></span>
A [Tensor category](#3ff71704-ce2e-458d-88ae-adf48f6c89bf) is called **rigid** if we have isomorphism
\\[\ihom(X\_{1}, Y\_{1}) \otimes \ihom(X\_{2}, Y\_{2}) \to \ihom(X\_{1} \otimes X\_{2}, Y\_{1} \otimes Y\_{2})\\]
for all \\(X\_{i}, Y\_{i}\\) and all objects are [Reflexive](#95bcb049-bebc-40e2-8825-3cf80620f211).

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

Cf. [Associativity constraint](#7952eb96-5003-45e9-b48d-e7764d411f07), [Commutativity constraint](#3292ae27-0e60-4f47-9a5f-ea3cf3ed8a98), [Tensor category](#3ff71704-ce2e-458d-88ae-adf48f6c89bf).

Referenced: [Pivotal](#bc1d556f-67f5-4b27-9c7b-00e618882a1e), [Rigid braided monoidal category](#a5cb1377-0de5-4f2a-ac4e-b97a6656390c), [Criterion for category being representation category](#4357d757-e6bd-495c-a863-e8cef3943c0b).


### Tensor functor {#cf063348-e088-4ec0-8e7a-59e5de57ccaf}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 14:51]</span></span>
A **tensor functor** between [Tensor category](#3ff71704-ce2e-458d-88ae-adf48f6c89bf) is a functor with morphism
\\[c:FX \otimes FY \ito F(X \otimes Y)\\]
functorial in \\(X, Y\\) with compatibility with [Commutativity constraint](#3292ae27-0e60-4f47-9a5f-ea3cf3ed8a98) and [Associativity constraint](#7952eb96-5003-45e9-b48d-e7764d411f07).


### t-exact {#e24e2753-7b78-4dce-b2e8-e33ee898d332}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-30 Sat 16:17]</span></span>
A functor is called **t-exact** if it is compatible with the [t-structure](#b2ad7b32-8a22-41e9-9db6-d3cc1d2d78f6).


### Topological category {#51d4149b-b118-49a4-b426-fffc17d74015}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 19:19]</span></span>
A **topological category** is a category which is enriched over \\(\cat{CGWH}\\). The category of topological category will be denoted by \\(\cat{Cat}\_{top}\\).

Cf. [Category CGWH](#6fcf0c23-fe3f-4fde-80a3-6c6e6c4591c5).


### Torsion pair {#eb0b7bca-f6d8-4dbe-881e-66387764647f}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 18:33]</span></span>
A torsion pair \\((\mathcal{P}, \mathcal{Q})\\) is a pair of full subcategory of \\(\mathcal{C}\\) such that

1.  \\(\hom(P, Q) = 0\\) for every \\(P \in \mathcal{P}, Q \in \mathcal{Q}\\).
2.  \\(\hom(\mathcal{P}, X) = 0\\), then \\(X \in \mathcal{Q}\\).
3.  \\(\hom(X, \mathcal{Q}) = 0\\), then \\(X \in \mathcal{P}\\).
4.  For every \\(C\\) in \\(\mathcal{C}\\), there exists \\(P \in \mathcal{P}, Q \in \mathcal{Q}\\) such that
    \\[0 \to P \to C \to Q \to 0\\]
    is exact.


### Total left derived functor {#323dfa8e-2e7e-451d-8fdd-6628b745a939}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:36]</span></span>
If \\(F: \mathcal{C} \to \mathcal{D}\\) is a [Left Quillen functor](#9c9f99db-eb71-4a6a-86dc-5b585aa4763b), define the **total left derived functor** \\(LF: \cat{Ho}(\mathcal{C}) \to \cat{Ho}(\mathcal{D})\\) to be the composite
\\[\cat{Ho}(\mathcal{C}) \xrightarrow{\cat{Ho}(Q)} \cat{Ho}(\mathcal{C}\_{c}) \xrightarrow{\cat{Ho}(F)} \cat{Ho}(\mathcal{D})\\]
where \\(\mathcal{C}\_{c}\\) means the full subcategory with [Cofibrant](#8410a73f-e0f4-4f94-bdc0-e8043b31b144) objects. For natural transformation, we have **total derived natural transformation**.

Similarly, we have **total right derived functor**.

Referenced: [Total right derived functor](#574f64c8-e717-44b9-a523-e9ab8b5dc4e1).


### Total right derived functor {#574f64c8-e717-44b9-a523-e9ab8b5dc4e1}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-18 Sat 18:39]</span></span>
See [Total left derived functor](#323dfa8e-2e7e-451d-8fdd-6628b745a939).


### Triangulated category {#bfcda5c7-8c14-4365-9870-eebf8ac950b1}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 20:20]</span></span>
An [Additive](#7fe0ea1e-b6d3-48b0-b843-3f6e519ce662) category \\(\mathcal{C}\\) endowed with a shift self-equivalence \\(T\\) and a family of **distinguished triangles** \\(\mathcal{T}\\) is a **triangulated category** if these data satisfying the following axioms, with \\(X[1] = TX\\).

1.  Any triangle isomprhic to a distinguished triangle is distinguished.
2.  \\(X \to X \to 0 \to \\) is distinguished.
3.  Any \\(u: X \to Y\\) is part of distinguished triangle \\(X \to Y \to Z \to \\).
4.  A triangle \\(X \to Y \to Z \to \\) is distinguished if and only if the triangle \\(Y \to Z \to X[1] \to\\) is distinguished.
5.  Any diagram

    ![](/img/2021-12-19_21-30-02_screenshot.png)
    can be completed to commutative diagram.
6.  For any pair of morphism \\(u: X \to Y\\) and \\(v: Y \to Z\\) and triple \\(X \to Y \to A \to \\) \\(Y \to Z \to B \to \\) and \\(X \to Z \to C \to X\\) there are isomorphisms \\(a: A \to C\\), \\(b: C \to B\\) and the triangle \\(A \to C \to B \to A\\) is distinguished.

A full additive subcategory \\(\mathcal{D} \subset \mathcal{C}\\) is called a **triangulated subcategory** if \\(T(\mathcal{D}) \subset \mathcal{D}\\) and if two vertices in a distinguished triangle in \\(\mathcal{T}\\) are in \\(\mathcal{D}\\), then so is the third.

Referenced: [t-structure](#b2ad7b32-8a22-41e9-9db6-d3cc1d2d78f6).


### t-structure {#b2ad7b32-8a22-41e9-9db6-d3cc1d2d78f6}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 18:33]</span></span>
Let \\(D\\) be a [Triangulated category](#bfcda5c7-8c14-4365-9870-eebf8ac950b1) and \\(D^{\leq 0}, D^{\geq 0}\\) full subcategories, then \\((D^{\leq 0}, D^{\geq 0})\\) is called **t-structure** if the followings are satisfied

1.  \\(D^{\leq 1} \subset D^{\leq 0}\\), \\(D^{\geq 1} \subset D^{\geq 0}\\).
2.  \\(\Hom\_{D}(X, Y) = 0\\) for \\(X \in D^{\leq 0}, Y \in D^{\geq 1}\\).
3.  For \\(X \in D\\), there exists distinguished triangle
    \\[X\_{0} \in D^{\leq 0} \to X \to X\_{1} \in D^{\geq 1} \to X\_{0}[1]\\]

Referenced: [Heart](#0c7d2280-19bc-42e0-bed7-a798b0e65aaf), [t-exact](#e24e2753-7b78-4dce-b2e8-e33ee898d332), [Bounded](#59480d24-e953-4828-8bb1-20efb6d6a4e4), [Perverse sheaf](#929a1901-d7f2-48e8-ba4e-d38299118fc4).


#### Bounded {#59480d24-e953-4828-8bb1-20efb6d6a4e4}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-30 Sat 16:14]</span></span>
A [t-structure](#b2ad7b32-8a22-41e9-9db6-d3cc1d2d78f6) is called **bounded** if \\(D^{\leq n} = D = D^{\geq m}\\) for \\(m \ll 0\\) and \\(n \gg 0\\).


### Undercategory {#adb1c3c4-abcb-4aeb-a33d-4a3e13b8704f}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-25 Sat 21:42]</span></span>
Cf. [Overcategory](#d44988e3-fc18-4f94-be80-8ac43d54aa9c).


### Weak equivalence {#15fb68f9-4900-41d3-bef7-06b6aff61696}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 20:20]</span></span>
Let \\(F: \mathcal{C} \to \mathcal{D}\\) be functor between [Topological categories](#51d4149b-b118-49a4-b426-fffc17d74015), we say that \\(F\\) is a **weak equivalence** (or **equivalence**) if the induced functor \\(h \mathcal{C} \to h \mathcal{D}\\) is an equivalence of \\(\mathcal{H}\\)-enriched categories.

Cf. [Homotopy category](#ab32b639-e590-4e00-8bb9-0ef66574985a).


### <span class="org-todo todo TODO">TODO</span> Zero object {#e11e1db2-b03d-4e25-82f6-3f2bfb76e6c8}


## Commutative Algebra {#dd8c9889-9968-4fea-b61e-68ef5f5e96f3}




### <span class="org-todo todo TODO">TODO</span> Commutative Frobenius algebra {#346c7f79-aa13-4314-af4f-ef33c9673c57}


### Ext group {#76fb6faa-33e2-4cc8-858f-49fc7d3d03c0}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-13 Wed 21:11]</span></span>
Let \\(M, N\\) be two \\(R\\)-modules. Let \\(P\_{\bullet} \to M\\) be a free \\(R\\)-module resolution of \\(M\\)
\\[\cdots \to P\_{n} \to \cdots \to P\_{1} \to P\_{0} \to M \to 0\\]
is an exact sequence of \\(R\\)-modules and \\(P\_{i}\\)'s are free. Then we define the **Ext group** by
\\[\Ext^{k}\_{R}(M, N) = H^{k}(\Hom(P\_{\bullet}, N))\\]
and the **Tor group**
\\[\Tor^{R}\_{k}(M, N) = H\_{k}(P\_{\bullet} \otimes\_{R} N)\\]

Referenced: [Tor group](#0b762e04-f0bc-4765-8577-f4e5a209e4e1).


### <span class="org-todo todo TODO">TODO</span> Finite length {#de466b2f-6240-4d46-9c8d-c367def492d3}


### <span class="org-todo todo TODO">TODO</span> K-theory {#a4db7ee2-d6aa-48a6-845a-97f6093c6fc6}


### Module {#826abae0-e69c-468f-99f1-0d0f730a65d9}




#### <span class="org-todo todo TODO">TODO</span> Injective {#68acdb6e-e62d-4c1a-b5af-f2cd16ce2d81}


### <span class="org-todo todo TODO">TODO</span> Resolution {#53f523dc-b88f-42d6-bbf1-18b631a73547}


### Semisimple {#b8989fe2-daf4-494f-9665-ba99d1f91b40}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-30 Sat 16:19]</span></span>
An object in a category is called **semisimple** if it is the direct sum of the [Simple](#845a1c97-7195-4345-babc-23c747ca69f3) object.


### <span class="org-todo todo TODO">TODO</span> Simple {#845a1c97-7195-4345-babc-23c747ca69f3}



Referenced: [Semisimple](#b8989fe2-daf4-494f-9665-ba99d1f91b40).


### Tor group {#0b762e04-f0bc-4765-8577-f4e5a209e4e1}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-13 Wed 21:11]</span></span>
See [Ext group](#76fb6faa-33e2-4cc8-858f-49fc7d3d03c0).


## Sheaf Theory {#7b7caad0-2dcd-4ede-847e-dde01099c434}




### Constructible sheaf {#de663a22-73ee-4211-994b-c55db54c8986}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-23 Sat 14:20]</span></span>
A sheaf is called **constructible** if \\(F|\_{X\_{\alpha}}\\) is a [Local system](#91515379-d2f9-4154-8eab-5fde17b51179) for some [Stratification](#ae8eff71-6745-4a59-a8b6-a2ca835fe478) \\((X\_{\alpha})\\). And we define the category \\(D\_{c}^{b}(X) \subset D^{b}(X)\\) full subcategory with constructible cohomology.


### Dual complex {#ba267178-71ca-44d4-bfc2-cef28f87db9f}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-23 Sat 14:19]</span></span>
We define **dual complex** to be \\(D\_{X} = w\_{X}[n]\\), where \\(n = \dim X\\). and \\(w\_{X}(U) = \Hom(H\_{c}^{n}(U), k)\\).

Referenced: [Verdier duality](#fdfd477b-8fe6-4b19-92ee-fc1880eead28).


### <span class="org-todo todo TODO">TODO</span> Equivariant sheaf {#b73ddbbe-a4a6-4c8b-aecc-d3b2c9ec3b5a}


### <span class="org-todo todo TODO">TODO</span> G-resolution {#42e3d2ba-d21e-46ec-b60a-4a979d93197e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:08]</span></span>
Equivariant pullback


### <span class="org-todo todo TODO">TODO</span> Intersection cohomology {#dbd6b795-51d4-4a93-b364-181296340aa1}


### <span class="org-todo todo TODO">TODO</span> Local system {#91515379-d2f9-4154-8eab-5fde17b51179}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:00]</span></span>
The local system also has its dual.

Referenced: [Constructible sheaf](#de663a22-73ee-4211-994b-c55db54c8986), [Verdier duality](#fdfd477b-8fe6-4b19-92ee-fc1880eead28).


### Perverse sheaf {#929a1901-d7f2-48e8-ba4e-d38299118fc4}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:01]</span></span>
For \\(D = D^{b}\_{c}(X)\\), we can take [t-structure](#b2ad7b32-8a22-41e9-9db6-d3cc1d2d78f6) as
\\[D^{\leq 0} = \\{F | \dim \supp \mathscr{H}^{j}(F) \leq -j\\}\\]
\\[D^{\geq 0} = \\{F | \dim \supp \mathscr{H}^{j}(\mathbb{D}\_{X}F) \leq -j\\}\\]
And we define the **perverse sheaf** to be the [Heart](#0c7d2280-19bc-42e0-bed7-a798b0e65aaf) of the t-structure. That is
\\[\cat{Perv}(X) = D^{\leq 0} \cap D^{\geq 0}\\]

The operator \\(\mathbb{D}\_{X}\\) preverse the category \\(\cat{Perv}(X)\\).

For perverse sheaf category, we have functor \\(^{p}F\\).


### <span class="org-todo todo TODO">TODO</span> Six functors {#a209f8ba-cf2a-4cbf-bb64-288086f9bec0}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:01]</span></span>
\\(f^{-1}\\) is exact, and \\(f\_{\* }\\) and \\(f\_{!}\\) only left exact.

We have following important properties for operators.

-   Adjunction pairs: \\((f^{\*}, Rf\_{\* })\\), \\((Rf\_{!}, f^{!})\\), \\((- \otimes \mathcal{F}, \shom(\mathcal{F}, -)\\).
-   The morphism between functors \\(f\_{!} \to f\_{\* }\\), which is isomorphism if \\(f\\) is proper. Also, we have \\(j^{!} = j^{\* }\\) for \\(j\\) an open inclusion.
-   For \\(X = U \coprod Z\\) where \\(U\\) is open and \\(Z\\) is closed, denote the includion \\(i: U \to X\\), \\(j: Z \to X\\), then we have distinguished triangles
    \\[i\_{!}i^{!} \to \id \to j\_{\* } j^{\* }\\]
    \\[j\_{!}j^{!} \to \id \to i\_{\* } i^{\* }\\]
-   See [Verdier duality](#fdfd477b-8fe6-4b19-92ee-fc1880eead28).
-   For \\(f: X \to Y\\) smooth of relative dimension \\(d\\) then one has an isomorphism
    \\[f^{!}k = k[2d]\\]
-   \\(H^{n}(X) = H^{n}(f\_{\* }k\_{X})\\), \\(H\_{n}^{!}(X) = H^{n}(f\_{\* } \omega\_{X})\\), \\(H\_{!}^{n} = H^{n}(f\_{!}k\_{X})\\), \\(H\_{n}(X) = H^{-n}(f\_{!} \omega\_{X})\\)
-   For pullback diagram

    ![](/img/2021-11-04_18-20-23_screenshot.png)
    We have isomorphism of functors
    \\[f^{\* } \circ g\_{!} \cong (g')\_{!} \circ (f')^{!}\\]


### Stratification {#ae8eff71-6745-4a59-a8b6-a2ca835fe478}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-23 Sat 14:20]</span></span>
A **stratification** of \\(X\\) is a decomposition
\\[X = \coprod\_{\alpha \in A} X\_{\alpha}\\]
which is locally finite, \\(X\_{\alpha}\\) locally closed and smooth and satisfies
\\[\bar{X}\_{\alpha} = \coprod\_{\beta \in B} X\_{\beta}\\]

Referenced: [Constructible sheaf](#de663a22-73ee-4211-994b-c55db54c8986).


### Verdier duality {#fdfd477b-8fe6-4b19-92ee-fc1880eead28}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-23 Sat 14:29]</span></span>
Let \\(D\_{X} \in D^{b}(X)\\) be the [Dual complex](#ba267178-71ca-44d4-bfc2-cef28f87db9f), we define \\(\mathbb{D}\_{X}(E) = \mathbb{R} \shom\_{X}(E, D\_{X})\\) gives functor \\(\mathbb{D}\_{X}: D^{b}(X) \to D^{b}(X)\\).

We have \\(\mathbb{D}^{2} = \id\\).

The **Verdier duality** is the eqauility
\\[\mathbb{D}\_{Y} \circ Rf\_{!} = Rf\_{\*} \circ \mathbb{D}\_{X}\\]
Also, we have
\\[f^{!} \circ \mathbb{D}\_{Y} = \mathbb{D}\_{X} \circ f^{-1}\\]

As a speical case, when \\(\mathcal{L}\\) is [Local system](#91515379-d2f9-4154-8eab-5fde17b51179) and \\(X\\) is smooth, we have
\\[\mathbb{D} \mathcal{L} \cong \mathcal{L}^{\vee}[2 d\_{X}]\\]

Referenced: [Six functors](#a209f8ba-cf2a-4cbf-bb64-288086f9bec0).


### <span class="org-todo todo TODO">TODO</span> Whitney stratification {#c3edd612-115c-49f1-8430-5f6f66a9f408}


## Representation theory {#10a617c4-bde9-4b6d-bbfc-3c911643dcfa}

The reference of representation of finite groups includes [<span id="19580479584332ed50a4af7bf7f3f201"><a href="#steinberg2012" title="Steinberg, Representation Theory of Finite Groups: An Introductory Approach, {Springer} (2012).">steinberg2012</a></span>] Chapter 1-6. The basics of the quivers are from [<span id="df38f5636bec59103a70400bed4764c9"><a href="#kirillov2016" title="Kirillov, Quiver Representations and Quiver Varieties, {American Mathematical Society} (2016).">kirillov2016</a></span>].


### Burnside Theorem {#eaaaedc6-0fb0-4839-8795-bcc33de24e7e}

{{% theorem %}}
Let \\(G\\) be a group of order \\(p^{a}q^{b}\\) with \\(p\\), \\(q\\) primes. Then \\(G\\) is not simple unless it is cyclic of prime order.
{{% /theorem %}}


### <span class="org-todo todo TODO">TODO</span> Characters {#22f71d14-081a-44e7-86f2-a99042264814}

\\(L(G)\\); character; irreducible character; class function; multiplicity; regular representation; character table

{{% proposition %}}
Equivalent representations has equal characters.
{{% /proposition %}}

{{% proposition %}}
Characters are class functions.
{{% /proposition %}}

The irreducible characters of \\(G\\) form an orthonormal set of class functions.
and \\({\rm dim} Z(L(G)) = |Cl(G)|\\). Therefore the number of irreducible representations is smaller than the conjugacy groups. In fact, two numbers are equal.

{{% proposition %}}
\\(|G| = d\_{1}^{2} + d\_{2}^{2} + \cdots + d\_{s}^{2}\\) holds, where \\(d\_{i}\\) is the degree of the irreducible representation.
{{% /proposition %}}

Cf. [Orthogonal relations](#2dc5be8a-7e4f-43f3-8db1-c89ec540c950).

{{% theorem %}}
Let \\(C\\), \\(C'\\) be conjugacy classes of \\(G\\), and let \\(g \in C\\) and \\(h \in C'\\). Then

\begin{equation} \sum\_{i = 1}^{s}\chi\_{i}(g) \overline{\chi\_{i}(h)} = \begin{cases} |G|/|C| & C = C' \\\\  0 & C \neq C' \end{cases} \end{equation}

That is the columns of the character table are orthogonal.
{{% /theorem %}}


### <span class="org-todo todo TODO">TODO</span> Class function {#18758f06-1d3c-47b4-95f4-3f31dcfd6531}


### Completely decomposition {#20caef12-0503-4f15-9f42-241885ee98d5}

{{% proposition %}}
Every representation of a finite group is equivalent to a unitary representation.
{{% /proposition %}}

{{% theorem %}}
Every representation of a finite group is completely reducible.
{{% /theorem %}}


### Criterion for category being representation category {#4357d757-e6bd-495c-a863-e8cef3943c0b}



{{% theorem %}}
Let \\((C, \otimes)\\) rigid abelian tensor category, \\(\End({\bold 1}) = k\\) and \\(w: C \to \cat{Vec}\_{k}\\) exact faithful \\(k\\)-linear tensor functor. Then we have

-   \\(\cat{Aut}^{\otimes}(w) \cong G\\) affine group scheme.
-   \\(C \to \cat{Rep}\_{k}(G)\\) induced by \\(w\\) is tensor equivalence.
{{% /theorem %}}

Cf. [Tensor category](#3ff71704-ce2e-458d-88ae-adf48f6c89bf), [Rigid](#51c7cfa0-c077-4e1f-aa58-e7e9678f4cda), [Group scheme](#5199da7e-9a89-43b9-a3ab-9869c4d7c38f).


### Dimension theorem {#2e876483-5fcd-4e03-9262-c06da6871f7d}

{{% theorem %}}
Let \\(\phi\\) be an irreducible representation of \\(G\\) of degree \\(d\\). Then \\(d\\) divides \\(|G|\\).
{{% /theorem %}}

这里值得注意的是，证明中使用了一些代数数论的结论，主要是关于 algebraic number 和 algebraic integer。


### Fourier analysis of finite groups {#ad969efe-de78-4fc8-9321-febec44a24d8}

fourier transform; fourier inversion; convolution; dual group;

{{% proposition %}}
The class functions form the center of \\(L(G)\\).
{{% /proposition %}}

{{% proposition %}}
\\(\widehat{a \* b} = \hat{a} \cdot \hat{b}\\)
{{% /proposition %}}

nonabelian Fourier transform (Wedderburn)


### Orthogonal relations {#2dc5be8a-7e4f-43f3-8db1-c89ec540c950}

Group algebra

{{% theorem %}}
Suppose that \\(\phi,\rho: G \to U\_{n}( C)\\) are inequivalent irreducible unitary representations. Then

\begin{equation} \langle \phi\_{ij}, \rho\_{kl} \rangle = 0 \end{equation}

\begin{equation} \langle \phi\_{ij}, \phi\_{kl} \rangle =  \begin{cases} 1/n & \text{if } i = k \text{ and } j = l \\\\ 0 & \text{else} \end{cases} \end{equation}
{{% /theorem %}}

Referenced: [Characters and class functions](#22f71d14-081a-44e7-86f2-a99042264814).


### Point group {#17b21dfb-f406-4cfb-9de9-df5ecc357bdf}

{{% definition %}}
A finite subgroup of O(3) is called a point group.
{{% /definition %}}


### Quivers {#a8ddd967-c339-4595-9ac7-3d727a3f4e16}

quiver; subquiver; oriented cycle; loop; morphism; direct sum; subrepresentation; irreducible representation; indecomposable representation; quivers of finite type; path; product of path; path algebra; one-way path

{{% theorem %}}
The category of representations of \\(Q\\) over a field \\(k\\) is equivalent to the category of \\(k(Q)\\)-modules.
{{% /theorem %}}

{{% lemma %}}
The Jacobson radical of the path algebra \\(k(Q)\\) is the span of all one-way paths of \\(Q\\).
{{% /lemma %}}


### Reconstruction theorem {#1e62d31f-a421-4a9a-8797-c6a4d7a2ec2a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 14:18]</span></span>
Let \\(\cat{Rep}\_{k}(G)\\) be [Representation category](#5bdd1646-d8d5-4499-8388-62ddc3fcddfb) of affine [Group scheme](#5199da7e-9a89-43b9-a3ab-9869c4d7c38f) \\(G\\). And let \\({\rm For}: \cat{Rep}\_{k}(G) \to \cat{Vec}\_{k}\\) be forgetful functor. Then we have \\(\cat{Aut}^{\otimes}({\rm For})( R) \ni \lambda\\) is data of \\(\lambda\_{X}: X \otimes R \to X \otimes R\\) for every \\(X \in \cat{Rep}\_{k}(G)\\) with compatibilities

-   \\(\lambda\_{X\_{1} \otimes X\_{2}} = \lambda\_{X\_{1}} \otimes \lambda\_{X\_{2}}\\)
-   \\(\lambda\_{\bold 1} = \id\_{k \otimes R = R}\\)

And for all \\(\alpha: X \to Y\\) in \\(\cat{Rep}\_{k}(G)\\), it commutes with \\(\lambda\_{X}\\). We observe that \\(g \in G( R)\\) gives an element of \\(\cat{Aut}^{\otimes}({\rm For})( R)\\). In fact, we have

{{% proposition %}}
The associated morphism of schemes \\(G \to \cat{Aut}^{\otimes}({\rm For})\\) is an isomorphism.
{{% /proposition %}}


### Representation category {#5bdd1646-d8d5-4499-8388-62ddc3fcddfb}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 19:03]</span></span>
For a group \\(G\\), we may define the category \\(\cat{Rep}(G)\\) for finite dimensional representation of \\(G\\) with morphisms of representations.

Cf. [Algebraic group](#e2cb9181-d20c-47cd-9f3b-757f9ad14ce1).

Referenced: [Reconstruction theorem](#1e62d31f-a421-4a9a-8797-c6a4d7a2ec2a).


### Representation of finite groups {#4b974727-7fb1-4266-a8a4-634d1c9cab99}

{{% definition %}}
A representation of a group \\(G\\) is homomorphism \\(\phi: G \to GL(V)\\) for some (finite-dimensional) vector space \\(V\\). The dimension of \\(V\\) is called the degree of \\(\phi\\).
{{% /definition %}}

equivalence; G-invariant subspace; irreducible representation; completely reducible representation; indecomposable representation; unitary representation


### Schur lemma {#d693bf18-4ef2-4c8b-98c5-34e3d8c5611a}

{{% lemma %}}
Let \\(\phi\\), \\(\rho\\) be irreducible representation of \\(G\\), and \\(T \in \Hom\_{G}(\phi, \rho)\\). Then either \\(T\\) is invertible or \\(T = 0\\).
{{% /lemma %}}

{{% corollary %}}
Let \\(G\\) be an abelian group. Then any irreducible representation of \\(G\\) has degree 1.
{{% /corollary %}}


### Tensor product of irreducible representations {#8df946d3-312b-49f1-ba6c-5e0fe48a958e}


### <span class="org-todo todo TODO">TODO</span> Dykin diagram {#690d99b3-0cc7-4c97-89a0-5c045c17a464}


## Linear Algebra {#dc95150e-0dc9-40de-88bf-a69013f11d1e}




### Simultaneously diagonalizable {#8d607d06-68ff-4890-a36b-bde9b0b66ca3}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-17 Fri 21:45]</span></span>
For two linear endomorphism \\(A, B\\), if \\([A,B] = 0\\), then \\(A, B\\) can be simultaneously diagonalized.


## Lie Algebra {#6e316adb-4c6b-43db-9ad2-9fa4480babe4}




### Base {#2f99ea90-ce90-44bc-9705-d74156d8de80}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:56]</span></span>
A **base** of a [Root system](#a5d162f4-32bf-4ebe-ac62-ba99323a297a) \\(\Delta \in \phi\\) is a basis for \\(V\\) such that each \\(\alpha \in \phi\\) is a positive or negative integer linear combination from \\(\Delta\\).

For a base \\(\Delta\\) we have \\(\NN \Delta \cap \phi\\) system of [Positive roots](#11c3ad25-a0cc-4433-a680-2c241f8a9910). And positive roots can give a bases by [simple roots](#6bc8ef9a-eef6-41d0-9593-a8a313ab2711).

Referenced: [Fundamental weight](#e4fa41fc-e574-4004-b7ee-62407c1542f9).


### Dominant {#b2602b08-bf46-4c7a-b832-782e3e8fa05a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 19:00]</span></span>
For \\(\\{\lambda\_{i}\\}\\) [Fundamental weights](#e4fa41fc-e574-4004-b7ee-62407c1542f9), \\(\lambda \in P(\phi) = \oplus\_{i} \ZZ \lambda\_{i}\\) is called **dominant** if \\(\langle \lambda, \alpha\_{j}^{\vee} \rangle \geq 0\\) for all \\(j\\).

Cf. [Root system](#a5d162f4-32bf-4ebe-ac62-ba99323a297a).


### Fundamental weight {#e4fa41fc-e574-4004-b7ee-62407c1542f9}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:58]</span></span>
For \\(\Delta = \\{\alpha\_{1}, \cdots, \alpha\_{n}\\}\\) [Base](#2f99ea90-ce90-44bc-9705-d74156d8de80) for \\(\phi\\), we define the **fundamental weights** \\(\\{\lambda\_{1}, \cdots, \lambda\_{n}\\}\\) basis for \\(V\\) dual to \\(\Delta^{\vee}\\) so that \\(\langle \lambda\_{i}, \alpha\_{j}^{\vee}\rangle = \delta\_{ij}\\).

Cf. [Root system](#a5d162f4-32bf-4ebe-ac62-ba99323a297a).

Referenced: [Dominant](#b2602b08-bf46-4c7a-b832-782e3e8fa05a).


### <span class="org-todo todo TODO">TODO</span> Poinccaré-Birkhoff-Witt theorem {#55daa1e0-d521-42e5-9868-f1f2ee88c461}


### Positive root {#11c3ad25-a0cc-4433-a680-2c241f8a9910}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:53]</span></span>
Let \\((G, T)\\) split [Reductive](#3c91fa04-29df-4ad0-8995-447a5fb86da1), there exists [Borel](#73ee6f1c-93e3-49cf-9401-eaf7af130e1f) \\(B \supset T\\), and therefore \\(\mathfrak{b} \supset \mathfrak{t}\\). Let \\(\phi\\) be the [Root system](#a5d162f4-32bf-4ebe-ac62-ba99323a297a) of \\(G\\), we define the **positive root** to by \\(\phi^{+ }(B) = \\{\alpha \in \phi \mid \mathfrak{g}\_{\alpha} \subset \mathfrak{b}\\}\\).

Referenced: [Base](#2f99ea90-ce90-44bc-9705-d74156d8de80).


### <span class="org-todo todo TODO">TODO</span> Root system {#a5d162f4-32bf-4ebe-ac62-ba99323a297a}



Referenced: [Base](#2f99ea90-ce90-44bc-9705-d74156d8de80), [Dominant](#b2602b08-bf46-4c7a-b832-782e3e8fa05a), [Fundamental weight](#e4fa41fc-e574-4004-b7ee-62407c1542f9), [Positive root](#11c3ad25-a0cc-4433-a680-2c241f8a9910).


### <span class="org-todo todo TODO">TODO</span> simple root {#6bc8ef9a-eef6-41d0-9593-a8a313ab2711}



Referenced: [Base](#2f99ea90-ce90-44bc-9705-d74156d8de80).


## Differential Geometry {#887d8afe-0460-4c42-8067-71b6d2c25324}


### Cartan's magic formula {#199a62a6-ba33-4b8f-99c0-9b661fdd59b5}



{{% theorem %}}
On a smooth manifold \\(M\\) for any smooth vector field \\(V\\) and any smooth differential form \\(\omega\\),
\\[\mathscr{L}\_{V} \omega = V \iprod (\dif \omega) + \dif (V \iprod \omega)\\]
{{% /theorem %}}


### Collar {#70a51fb9-cc12-4763-84ec-c6688f7e8f18}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:56]</span></span>
A collar of a smooth boundary [Manifold](#6ff3f589-8a3d-4903-b35a-fe10657823f2) \\(M\\) is a diffeomorphism \\(\kappa: \partial M \times \rinterval{0}{1} \to M\\) where the image is an open neighborhood of \\(\partial M\\) in \\(M\\) and \\(\kappa(x, 0) = x\\).

For collar, we have following proposition

{{% proposition %}}
A smooth boundary manifold \\(M\\) has a collar.
{{% /proposition %}}

The proposition is similar to the existence of the tubular neighborhood for [Normal bundle](#b6623fd3-ef1b-4871-9296-3846fdb9d03a).


### Complete integral distribution {#ea56b7ed-d7cf-4229-89fa-959ec148d450}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:35]</span></span>
Given a rank \\(k\\) [Distribution](#c7e62ec4-897a-4561-a189-15af51461c45) \\(D \subset TM\\), let us say that a smooth coordinate chart \\((U, \phi)\\) on \\(M\\) is **flat** for \\(D\\) if \\(\phi(U)\\) is a cube in \\(\RR^{n}\\) and at points of \\(U\\), \\(D\\) is spanned by the first \\(k\\) coordinate vector fields \\(\partial/ \partial x^{1}, \cdots, \partial/ \partial x^{k}\\).

A distribution \\(D \subset TM\\) is **completely integrable** if there exists a flat chart for \\(D\\) in a neighborhood of each point of \\(M\\).

Referenced: [Frobenius theorem](#b53ed6e5-d285-4a3e-9176-1601055c862a).


### Connected sum {#6d96de8b-9046-4d83-8c35-8fd05123a458}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-31 Tue 17:46]</span></span>
Given two \\(n\\)-[manifolds](#6ff3f589-8a3d-4903-b35a-fe10657823f2) \\(M\_{1}\\), and \\(M\_{2}\\), we define the **connected sum** of \\(M\_{1}\\) and \\(M\_{2}\\) by remove two \\(D^{n}\\) in \\(M\_{1}\\) and \\(M\_{2}\\) and glue two \\(S^{n - 1}\\) together, denoted by \\(M\_{1} \shar M\_{2}\\).


### Connection {#025c9171-e761-4861-bf05-42aa59e9b55b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-06 Mon 19:32]</span></span>
A **connection** on a [Vector bundle](#3944a5f8-1a1f-4cd2-82a0-d373c52e8bcf) \\(E \to M\\) is a linear map \\(\nabla^{E} : C^{\infty}(E) \to C^{\infty}(E \otimes T^{ \*}M)\\) satisfying the condition
\\[\nabla^{E}(\alpha e) = \alpha \nabla^{E} e + e \otimes \dif \alpha\\]
whenever \\(e \in C^{\infty}\\) is a smooth section of \\(E\\) and \\(\alpha\\) is a smooth function on \\(M\\).

A **connection** on a [Principal bundle](#9aa77da6-be5b-4471-b42b-ad6411e6d0e9) is a linear map \\(A: TP \to \ker(\pi\_{\*})\\) that equals the identity on the kernal of \\(\pi\_{\*}\\) and is equivariant with respect to the action of \\(G\\) on \\(P\\). Here \\(\pi: P \to M\\) is the projection map, \\(\ker(\pi\_{\*})\\) is often called **vertical subbundle**. Equivariant means that if \\(g \in G\\) and \\(v \in TP\\), then \\((m\_{g})\_{\*} (Av) = A((m\_{g})\_{\*} v)\\). \\(\ker(A)\\) is often called **horizontal subbundle**.

By isomorphism of \\(\psi: P \times \mathfrak{lie}(G) \to \ker(\pi\_{\*})\\) we can view a connection as a map
\\[A: TP \to \mathfrak{lie}(G)\\]
(or in other words \\(A: \mathfrak{lie}(G) \to \mathfrak{lie}(G) \times T^{\*}M\\))
with \\(A(\psi(p,m)) = m\\) and \\(A(m\_{g\*}v) = gA(v)g^{-1}\\)

Referenced: [Flat](#a3db89cb-badf-413a-b10e-39f1e02e34d0), [Covariant derivative](#61bd9c3b-fd42-4907-bead-7bf2577f4700), [Curvature](#24adfd2f-8b92-4a12-b729-bb04f2935e6d), [Holonomy group](#0f96248f-1f95-4b9f-b811-812dcc8c54eb), [Horizontal subbundle](#7e257936-4dd5-4717-8dd6-ecd3934a5ff6), [Vertical subbunel](#330f8cbe-44b3-4d0c-ba26-5bf314a95cbe), [Chern class](#eb44905d-a0cb-44e0-ae41-7555ca7a984b), [Chern-Simons functional](#c2fc5887-cc16-4136-a985-735cd4be83b6).


#### Flat {#a3db89cb-badf-413a-b10e-39f1e02e34d0}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-12 Sun 21:20]</span></span>
A [Connection](#025c9171-e761-4861-bf05-42aa59e9b55b) is called **flat** if the [Curvature](#24adfd2f-8b92-4a12-b729-bb04f2935e6d) of the connection is identically zero.

Referenced: [Chern-Simons functional](#c2fc5887-cc16-4136-a985-735cd4be83b6).


### Covariant derivative {#61bd9c3b-fd42-4907-bead-7bf2577f4700}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-12 Sun 20:51]</span></span>
The **covariant derivative** for [Vector bundle](#3944a5f8-1a1f-4cd2-82a0-d373c52e8bcf) is same as [Connection](#025c9171-e761-4861-bf05-42aa59e9b55b). (Not sure)

Given a connection on a [Principal bundle](#9aa77da6-be5b-4471-b42b-ad6411e6d0e9) \\(P\\), we defines a **covariant derivative** \\(\nabla\_{A}\\) on \\(P \times\_{\rho} V\\) where \\(\rho\\) is a representation of \\(G\\) on \\(V\\). The [Horizontal subbundle](#7e257936-4dd5-4717-8dd6-ecd3934a5ff6) \\(H\_{A} \subset TP\\) is canonically isomorphic to \\(\pi^{\*}TM\\). For section \\(s\\) of \\(E\\), we can view it as \\(G\\)-equivariant map \\(s^{P}:P \to V\\). Then the restriction to \\(H\_{A}\\) of the homomorphism \\((s^{P})\_{\*}: TP \to V\\) defines a covariant derivative of \\(s\\). In other word, let \\(x \in M\\) and \\(v \in TM|\_{x}\\). Pick \\(p \in P|\_{X}\\), then there exists a unique \\(v\_{A} \in H\_{A}|\_{p}\\) such that \\(\pi\_{\*} v\_{A} = v\\). Then \\(\nabla\_{A}s\\) defined to send \\(v\\) to the equivalence class in \\(E|\_{x} = (P|\_{x} \times\_{\rho} V)\\) of the pair \\((p, (s^{p})\_{\*}v\_{A})\\).

Referenced: [Exterior covarint derivative](#cede57e5-c462-4200-8493-3790d046d3b3).


### Curvature {#24adfd2f-8b92-4a12-b729-bb04f2935e6d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-06 Mon 19:41]</span></span>
For a given [Connection](#025c9171-e761-4861-bf05-42aa59e9b55b) and therefore [Exterior covarint derivative](#cede57e5-c462-4200-8493-3790d046d3b3) \\(\nabla^{E}\\), there exists a unique smooth section \\(R(\nabla^{E}) \in C^{\infty}(\End(E) \otimes \wedge^{2} T^{\* }M)\\) called the **curvature** of \\(\nabla^{E}\\), that satisfies the equation
\\[R(\nabla^{E}) \cdot (e \otimes v \wedge w) = \nabla\_{v}^{E} \nabla\_{w}^{E} e - \nabla\_{w}^{E} \nabla\_{v}^{E} e - \nabla^{E}\_{ [v,w]}e\\]
for all \\(v,w \in C^{\infty}( TM)\\) and \\(e \in C^{\infty}(E)\\).

Or we can define curvature \\(F\_{\nabla}\\) by \\(\dif\_{\nabla}^{2}m = F\_{\nabla} \wedge m\\).

The famous **Bianchi identity** is
\\[\dif\_{\nabla} F\_{\nabla} = 0\\]

For [Principal bundle](#9aa77da6-be5b-4471-b42b-ad6411e6d0e9), we define the \\(F\_{A}\\) to be the section of the bundle \\((P \times\_{ad} \mathfrak{lie}(G)) \otimes \wedge^{2} T^{\*}M\\).

Referenced: [Flat](#a3db89cb-badf-413a-b10e-39f1e02e34d0), [Chern class](#eb44905d-a0cb-44e0-ae41-7555ca7a984b), [Chern-Simons functional](#c2fc5887-cc16-4136-a985-735cd4be83b6), [Yang-Mills equation](#25c9c7d8-734a-474a-a2db-121be06ccb4e).


### Degree {#5377fecb-26ce-4c7a-b6b6-387a843a9ba3}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:25]</span></span>
Suppose \\(M\\) and \\(N\\) are compact, connected, [Oriented](#0d1fefb5-7409-4540-8afb-5b3c67e90acd), smooth manifolds of dimension \\(n\\), and \\(F: M \to N\\) is a smooth map. There exists a unique integer \\(k\\) called the **degree** of \\(F\\), that satisfies

1.  For every smooth \\(n\\)-form \\(\omega\\) on \\(N\\)
    \\[\int\_{M} F^{\* } \omega  = k \int\_{N} \omega\\]
2.  If \\(q\\) is a [Regular value](#3064e22a-123b-4f5e-9102-de7891d9bd32) of \\(F\\), then
    \\[k = \sum\_{x \in F^{-1}(q)} \sgn(x)\\]
    where \\(\sgn(x) = 1\\) if \\(\dif F\_{x}\\) is orientation-preserving and \\(-1\\) if orientation-reversing.


### de Rham cohomology {#111be87b-27bd-4c19-8499-e5e4b2cb1956}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:15]</span></span>
We define the **de Rham cohomology group** in degree \\(p\\) to be the quotient vector space
\\[H\_{dR}^{p}(M) = \frac{Z^{p}(M)}{B^{p}(M)}\\]
where \\(Z^{p}(M)\\) is the closed \\(p\\)-forms on \\(M\\). then \\(B^{p}(M)\\) is the exact \\(p\\)-forms.

{{% proposition %}}
The de Rham cohomology is homotopy invariants. If \\(M\\) and \\(N\\) is homotopy equivalent manifolds, then \\(H\_{dR}^{n}(M) \cong H^{p}\_{dR}(N)\\) for each \\(p\\). The isomorphisms are induced by any smooth homotopy equivalence \\(F: M \to N\\).
{{% /proposition %}}

Referenced: [de Rham theorem](#40d0778f-997f-4107-9cd8-3dc355c3f21c), [Cohomology](#a918cddf-cd03-4546-a2cd-ce897e10cf82).


### de Rham theorem {#40d0778f-997f-4107-9cd8-3dc355c3f21c}



{{% theorem %}}
For every smooth manifold \\(M\\) and nonnegative integer \\(p\\), the de Rham homomorphism \\(J: H\_{dR}^{p}(M) \to H^{p}(M; \RR)\\) is an isomorphism.
{{% /theorem %}}

Cf. [Singular cohomology](#9b5b928f-d06e-49b1-bf7a-3b873d3f2c59) and [de Rham cohomology](#111be87b-27bd-4c19-8499-e5e4b2cb1956).


### Differential form {#7ce49e85-c19f-4b52-8d77-a12c0e0b62f1}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 19:42]</span></span>
A section of \\(\Lambda^{k}T^{\* }M\\) is called a **differential \\(k\\)-form**. The integer \\(k\\) is called the **degree** of the form.

Cf. [Tangent bundle](#832cf3a2-8811-475c-a05e-25dee0ef6a02).

Referenced: [Exterior derivative](#f92d55e4-9f17-44fd-b1c7-c4e044448e7a), [Invariant formula for the exterior derivative](#1f9b217e-8c50-4798-b789-4bd56d522d36), [Stokes's theorem](#8ea3033d-1989-44cc-a423-9a3f52d86ef4).


### Distribution {#c7e62ec4-897a-4561-a189-15af51461c45}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:28]</span></span>
Cf. [Tangent bundle](#832cf3a2-8811-475c-a05e-25dee0ef6a02).

A **distribution** on \\(M\\) of rank \\(k\\) is a rank \\(k\\) subbundle of \\(TM\\). It is called a **smooth** distribution if it is a smooth subbundle.

Referenced: [Complete integral distribution](#ea56b7ed-d7cf-4229-89fa-959ec148d450), [Integral distribution](#a684257c-a084-476c-9a9a-0d4b58340668), [Involutive distribution](#538a8edd-010e-47a6-b201-3498306de8a5).


### Exterior derivative {#f92d55e4-9f17-44fd-b1c7-c4e044448e7a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:02]</span></span>
We define the **exterior differential** of [Differential form](#7ce49e85-c19f-4b52-8d77-a12c0e0b62f1)
\\[\dif (\sum\_{J} \omega\_{J} \dif x^{J}) = \sum\_{J} \dif \omega\_{J} \wedge \dif x^{J}\\]

Referenced: [Exterior covarint derivative](#cede57e5-c462-4200-8493-3790d046d3b3), [Invariant formula for the exterior derivative](#1f9b217e-8c50-4798-b789-4bd56d522d36), [Stokes's theorem](#8ea3033d-1989-44cc-a423-9a3f52d86ef4).


### Exterior covarint derivative {#cede57e5-c462-4200-8493-3790d046d3b3}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-12 Sun 21:07]</span></span>
Cf. [Exterior derivative](#f92d55e4-9f17-44fd-b1c7-c4e044448e7a).

Given a [Covariant derivative](#61bd9c3b-fd42-4907-bead-7bf2577f4700) \\(\nabla\\), we can define the **exterior covariant derivative** to be \\(\dif\_{\nabla}\\) such that if \\(\omega\\) is a \\(p\\) form and \\(s\\) is a section of \\(E\\), then \\(\dif\_{\nabla}(s \omega) = \nabla(s) \wedge \omega + s \dif \omega\\)

Referenced: [Curvature](#24adfd2f-8b92-4a12-b729-bb04f2935e6d).


### Frobenius theorem {#b53ed6e5-d285-4a3e-9176-1601055c862a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:39]</span></span>
By definition, we have [Complete integral distribution](#ea56b7ed-d7cf-4229-89fa-959ec148d450) implies [Integral distribution](#a684257c-a084-476c-9a9a-0d4b58340668) and integral distribution implies [Involutive distribution](#538a8edd-010e-47a6-b201-3498306de8a5). The **Frobenius theorem** suggests the reverse.

{{% theorem %}}
Every involutive distribution is completely integrable.
{{% /theorem %}}


### Holonomy group {#0f96248f-1f95-4b9f-b811-812dcc8c54eb}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-06 Mon 19:44]</span></span>
Let \\(M\\) be a [Manifold](#6ff3f589-8a3d-4903-b35a-fe10657823f2), \\(E\\) a [Vector bundle](#3944a5f8-1a1f-4cd2-82a0-d373c52e8bcf) over \\(M\\), and \\(\nabla^{E}\\) a [Connection](#025c9171-e761-4861-bf05-42aa59e9b55b) on \\(E\\). Suppose \\(\gamma: [0,1] \to M\\) is smooth, with \\(\gamma(0) = x\\) and \\(\gamma(1) = y\\), where \\(x,y \in M\\). Then for each \\(e \in E\_{x}\\) there exists a unique smooth section \\(s\\) of \\(\gamma^{\* }(E)\\) satisfying \\(\nabla\_{\dot{\gamma}(t)}^{E} s(t) = 0\\) for \\(t \in [0,1]\\) with \\(s(0) = e\\). Define \\(P\_{\gamma}(e) = s(1)\\). Then \\(P\_{\gamma}: E\_{x} \to E\_{y}\\) is a well-defined linear map called the **parallel transport map**.

Fix a point \\(x \in M\\), we define the **holonomy group** \\(\hol\_{x}(\nabla^{E}) = \\{P\_{\gamma}: \gamma \text{ is a loop based at } x\\} \subset \GL(E\_{x})\\).

Referenced: [Kähler manifold with holomorphic symplectic structure](#c261fae8-e011-484c-907f-98cb4ae3ab3d).


#### Berger classification theorem {#8ff9c0af-ccd0-4a3e-8ed6-a8cfed9fb76d}



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


### Horizontal subbundle {#7e257936-4dd5-4717-8dd6-ecd3934a5ff6}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-12 Sun 20:45]</span></span>
See [Connection](#025c9171-e761-4861-bf05-42aa59e9b55b).

Referenced: [Covariant derivative](#61bd9c3b-fd42-4907-bead-7bf2577f4700).


### Immersion {#5d4eeff2-f095-48c8-958b-4ab8f00bfd60}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:17]</span></span>
A smooth map \\(f\\) is an **immersion** if each \\(T\_{x}f\\) is injective and **submersion** if each \\(T\_{x}f\\) is surjective. Cf. [Tangent space](#8de50bef-4318-4dd1-bcde-95464bb002dd).

Referenced: [Normal bundle](#b6623fd3-ef1b-4871-9296-3846fdb9d03a), [Submersion](#20d04783-290e-472b-9cfc-602216c9ceae), [Knot](#a2bbd4aa-cc17-4042-b932-461a56e1cfce), [Link](#79ab45e1-e6f4-4938-8bee-dae2f2e09daa).


### Integral distribution {#a684257c-a084-476c-9a9a-0d4b58340668}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:31]</span></span>
A nonempty immersed submanifold \\(N \subset M\\) is called an **integral manifold** of \\(D\\) if \\(T\_{p}N = D\_{p}\\) at each point \\(p \in N\\). And a [Distribution](#c7e62ec4-897a-4561-a189-15af51461c45) is called **integral** if every point of \\(M\\) is contained in an integral manifold.

Referenced: [Frobenius theorem](#b53ed6e5-d285-4a3e-9176-1601055c862a).


### Invariant formula for the exterior derivative {#1f9b217e-8c50-4798-b789-4bd56d522d36}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 19:44]</span></span>
Let \\(M\\) be a smooth [Manifold](#6ff3f589-8a3d-4903-b35a-fe10657823f2), and \\(\omega \in \Omega^{k}(M)\\). For any smooth vector fields \\(X\_{1}, \cdots, X\_{k + 1}\\) on \\(M\\).

\begin{align}\dif \omega (X\_{1}, \cdots, X\_{k + 1}) &= \\\\  & \sum\_{1 \leq i \leq k + 1}(-1)^{i - 1}X\_{i}(\omega(X\_{1}, \cdots, \widehat{X\_{i}}, \cdots, X\_{k + 1})) \\\\  & + \sum\_{1 \leq i < j \leq k + 1} (-1)^{i + j} \omega([X\_{i}, X\_{j}], X\_{1}, \cdots, \widehat{X}\_{i}, \cdots, \widehat{X\_{j}}, \cdots, X\_{k + 1}) \end{align}

Cf. [Differential form](#7ce49e85-c19f-4b52-8d77-a12c0e0b62f1), [Exterior derivative](#f92d55e4-9f17-44fd-b1c7-c4e044448e7a).


### Involutive distribution {#538a8edd-010e-47a6-b201-3498306de8a5}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:32]</span></span>
The [Distribution](#c7e62ec4-897a-4561-a189-15af51461c45) \\(D\\) is **involutive** if given a pair of smooth local sections of \\(D\\), their Lie bracket is also local section of \\(D\\).

Referenced: [Frobenius theorem](#b53ed6e5-d285-4a3e-9176-1601055c862a).


### Lie derivative {#b2603ad3-d6f7-4c64-80b1-b40282423325}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-02 Thu 10:53]</span></span>
Given a smooth covariant tensor field \\(A\\) on \\(M\\), we define the **Lie derivative** of \\(A\\) with respect to \\(V\\), denoted by \\(\mathscr{L}\_{V}A\\) by
\\[(\mathscr{L}\_{V}A)\_{p} = \frac{\dif}{\dif t} \mid\_{t = 0} (\theta\_{t}^{\* }A)\_{p}\\]
Here \\(V\\) is a smooth vector field on \\(M\\), and \\(\theta\\) is its flow. \\(\theta\_{t}\\) is locally an isomorphism.

Referenced: [Liouville vector field](#8f4ab0d9-4b0e-484e-8acf-25f586eee8ed).


### Lie group {#51f57f80-3157-42ef-9fb8-0839fbace132}



{{% definition %}}
A **Lie group** is a smooth manifold with a group structure, where the group multiplication and inverse are smooth maps.
{{% /definition %}}

Cf. [Manifold](#6ff3f589-8a3d-4903-b35a-fe10657823f2).

Referenced: [Principal bundle](#9aa77da6-be5b-4471-b42b-ad6411e6d0e9).


#### <span class="org-todo todo TODO">TODO</span> E8 {#348fde9d-d126-4d6e-800f-52d0ae832313}



Referenced: [Intersection forms](#efde6529-9adb-401a-9a36-24b35eb28839).


### Manifold {#6ff3f589-8a3d-4903-b35a-fe10657823f2}



{{% definition %}}
An \\(n\\)-dimensional **manifold** is an \\(n\\)-dimensional locally Euclidean Hausdorff space with countable basis for its topology.
{{% /definition %}}

The definition has three requirements, where the countable basis is hardly used.

{{% definition %}}
A **differential structure**  on the \\(n\\)-manifold \\(M\\) is a maximal smooth atlas \\(\mathscr{D}\\) for \\(M\\). The pair \\((M, \mathscr{D})\\) is called a **smooth manifold** or **differentiable manifold**.
{{% /definition %}}

We call a compact manifold without boundary a **closed manifold**.

Referenced: [Collar](#70a51fb9-cc12-4763-84ec-c6688f7e8f18), [Connected sum](#6d96de8b-9046-4d83-8c35-8fd05123a458), [Holonomy group](#0f96248f-1f95-4b9f-b811-812dcc8c54eb), [Invariant formula for the exterior derivative](#1f9b217e-8c50-4798-b789-4bd56d522d36), [Lie group](#51f57f80-3157-42ef-9fb8-0839fbace132), [Orientation](#0d1fefb5-7409-4540-8afb-5b3c67e90acd), [Riemannian metric](#8d4fbb99-6c1f-4044-b8c1-cd819ca319c4), [Tangent space](#8de50bef-4318-4dd1-bcde-95464bb002dd), [Whitney embedding theorem](#0f63366f-2b94-4807-b592-a128341345c1), [Fundamental class](#b4d8db93-4571-4034-a37d-bc5ebea10fea), [Local homology group](#d72fb6c4-7adf-4742-85d8-bbc041072bd5), [Poincaré duality](#6aa27439-616e-4396-860c-d815999dfd79), [Symplectic manifold](#c127758e-3380-4bff-99e8-51d950df4d1c), [Freedman's classification of topological 4-manifold](#2802aa4d-49a8-4b19-a3f8-8d2cd41c1ef0), [Rokhlin Theorem](#3b84058d-80f3-4933-bad7-b398b673b4e4), [Spin structure](#052bd0fe-98ab-4cab-b13e-f8f73f653f65).


### Normal bundle {#b6623fd3-ef1b-4871-9296-3846fdb9d03a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:48]</span></span>
Let \\(f: M \to N\\) be an [Immersion](#5d4eeff2-f095-48c8-958b-4ab8f00bfd60). We define the quotient bundle of the bundle morphism \\(i: TM \to f^{\* }TN|\_{M}\\) to be the **normal bundle**. There exists a neighborhood of the zero section of normal bundle diffeomorphic to the neighborhood of \\(N\\) in \\(M\\). The diffeomorphic map is called **tubular map** and the target is called **tubular neighborhood**.

Cf. [Vector bundle](#3944a5f8-1a1f-4cd2-82a0-d373c52e8bcf), [Tangent bundle](#832cf3a2-8811-475c-a05e-25dee0ef6a02).

Referenced: [Collar](#70a51fb9-cc12-4763-84ec-c6688f7e8f18).


### Orientable {#e44cd985-169e-4233-984b-fe33f201c39a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 13:36]</span></span>
See [Orientation](#0d1fefb5-7409-4540-8afb-5b3c67e90acd).

Referenced: [Heegaard diagram](#cbbfa591-ea7b-49f0-b3a2-e7819b3df253), [Trisection](#6d38dc99-1d83-452b-8782-93a7d735e476).


### Orientation {#0d1fefb5-7409-4540-8afb-5b3c67e90acd}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:38]</span></span>
An atlas is called **orienting** if any two charts are positively related, that is every two charts has the same orientation as a subset of \\(\RR^{n}\\). If a [Manifold](#6ff3f589-8a3d-4903-b35a-fe10657823f2) \\(M\\) has an orienting atlas, we call \\(M\\) **orientable**. Notice that if a manifold is orientable, it naturally has two orientation.

Given [Local homology group](#d72fb6c4-7adf-4742-85d8-bbc041072bd5), a generator of the homology group \\(H\_{n}(M, M \backslash x; R) \cong R\\) is called a **local \\(R\\)-orientation**. Let \\(M\\) be a \\(n\\)-manifold and \\(A \subset M\\). An \\(R\\)-orientation of \\(M\\) along \\(A\\) is a section \\(s \subset \Gamma(A; R)\\) of \\(\omega: H\_{n}(M, M \backslash \bullet; R) \to M\\) such that \\(s(a) \in H\_{n}(M, M \backslash a; R) \cong R\\) is a generator for each \\(a \in A\\). For \\(A = M\\), we called it **\\(R\\)-orientation** and for \\(R = \ZZ\\), it is called **orientation**.

By characteristic class theory, a manifold is orientable if the first [Stiefel-Whitney class](#d61db36f-39bd-4cb5-b041-4815fda86269) vanishes that is \\(w\_{1}(E) = 0\\).

Referenced: [Degree](#5377fecb-26ce-4c7a-b6b6-387a843a9ba3), [Orientable](#e44cd985-169e-4233-984b-fe33f201c39a), [Oriented](#6ee87df9-81b1-461d-ba2a-4917799f1c5c), [Euler class](#6c02fdc1-d947-45e7-b613-a5c7108163fc), [Fundamental class](#b4d8db93-4571-4034-a37d-bc5ebea10fea), [Poincaré duality](#6aa27439-616e-4396-860c-d815999dfd79), [Lickorish-Wallace theorem](#b32c82ec-4f25-4180-bce6-8f926be285d6).


### Oriented {#6ee87df9-81b1-461d-ba2a-4917799f1c5c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 13:36]</span></span>
See [Orientation](#0d1fefb5-7409-4540-8afb-5b3c67e90acd).

Referenced: [Linking number](#69e445f3-bc07-47b7-9dc6-528113074bae), [Seiberg-Witten moduli space](#a2c62a24-c1bc-4034-a148-fbabaeb141a1), [Seifert surface](#809daf6c-a15d-4286-b29c-9b782695d32b), [Trisection](#6d38dc99-1d83-452b-8782-93a7d735e476).


### Poincaré lemma {#77d08676-09a8-4fd7-a0c2-e23c23331782}



{{% proposition %}}
If \\(U\\) is a star-shaped open subset of \\(\RR^{n}\\) of \\(\HH^{n}\\), then every closed covector field on \\(U\\) is exact.
{{% /proposition %}}


### Principal bundle {#9aa77da6-be5b-4471-b42b-ad6411e6d0e9}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-12 Sun 20:34]</span></span>
A **principal bundle** is a fiber bundle with fiber [Lie group](#51f57f80-3157-42ef-9fb8-0839fbace132) \\(G\\) and free \\(G\\) actions fiberwise.

Referenced: [Connection](#025c9171-e761-4861-bf05-42aa59e9b55b), [Covariant derivative](#61bd9c3b-fd42-4907-bead-7bf2577f4700), [Curvature](#24adfd2f-8b92-4a12-b729-bb04f2935e6d).


### Regular point {#3064e22a-123b-4f5e-9102-de7891d9bd32}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:20]</span></span>
For a smooth map \\(f: M \to N\\), a point \\(x \in M\\) is called a **regular point** if \\(T\_{x}f\\) is surjective and a point \\(y \in N\\) is called a **regular value** if each \\(x \in f^{-1}(y)\\) is a regular point, otherwise is called a **singular value**. Cf. [Tangent space](#8de50bef-4318-4dd1-bcde-95464bb002dd).

Referenced: [Degree](#5377fecb-26ce-4c7a-b6b6-387a843a9ba3), [Sard theorem](#40a40b3c-6891-4a94-ad55-17507129aaef), [Critical point](#c184e1ca-f49c-4c93-b9f6-672c9eb34fea).


### Riemannian metric {#8d4fbb99-6c1f-4044-b8c1-cd819ca319c4}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 19:29]</span></span>
A **Riemannian metric** on \\(M\\) is a smooth symmetric covariant \\(2\\)-tensor field on \\(M\\) that is positive definite at each point. A **Riemannian manifold** is a pair \\((M, g)\\), where \\(M\\) is a smooth manifold and \\(g\\) is a Riemannian metric on \\(M\\).

Cf. [Manifold](#6ff3f589-8a3d-4903-b35a-fe10657823f2).

{{% proposition %}}
Every smooth manifold admits a Riemannian metric.
{{% /proposition %}}

{{% proof %}}
By [Numerable](#6bd2d7e0-0dee-4ee3-ab4e-c390c13e143e) property of the smooth manifold.
{{% /proof %}}

Referenced: [Spin^C connection](#4bdbe70d-831d-4dc7-9065-1ee7cbda23e6).


### Sard theorem {#40a40b3c-6891-4a94-ad55-17507129aaef}



{{% theorem %}}
The set of singular values of a smooth map has measure zero, and the set of regular values is dense.
{{% /theorem %}}

Cf. [Regular point](#3064e22a-123b-4f5e-9102-de7891d9bd32).

{{% remark %}}
In most applications, the dense property implies the existence, as in the case of Whitney embedding theorem.
{{% /remark %}}

Referenced: [Whitney embedding theorem](#0f63366f-2b94-4807-b592-a128341345c1), [Seiberg-Witten moduli space](#a2c62a24-c1bc-4034-a148-fbabaeb141a1).


### Stein manifold {#6f488c59-190f-47ff-b5ab-54a37cccfd1c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-12 Sun 10:07]</span></span>
A **stein manifold** is a complex manifold which is a holomoprhically convex and holomorphically separable subset of \\(\CC^{n}\\). This is equivalent to \\(\Sigma\\) admits a proper holomorphic immersion \\(\Sigma \hookrightarrow \CC^{n}\\). In particular, analytification of any affine variety over \\(\CC\\) is a Stein space, but the converse is not true.


### Stokes's theorem {#8ea3033d-1989-44cc-a423-9a3f52d86ef4}



{{% theorem %}}
Let \\(M\\) be an oriented smooth \\(n\\)-manifold with boundary, and let \\(\omega\\) be a compactly generated supported smooth \\((n - 1)\\)-form on \\(M\\). Then
\\[\int\_{M} \dif \omega = \int\_{\partial M} \omega\\]
{{% /theorem %}}

Cf. [Differential form](#7ce49e85-c19f-4b52-8d77-a12c0e0b62f1), [Exterior derivative](#f92d55e4-9f17-44fd-b1c7-c4e044448e7a).


### Submersion {#20d04783-290e-472b-9cfc-602216c9ceae}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 18:14]</span></span>
See [Immersion](#5d4eeff2-f095-48c8-958b-4ab8f00bfd60).


### Tangent bundle {#832cf3a2-8811-475c-a05e-25dee0ef6a02}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:45]</span></span>
The [Tangent space](#8de50bef-4318-4dd1-bcde-95464bb002dd) at each point constitutes a [Vector bundle](#3944a5f8-1a1f-4cd2-82a0-d373c52e8bcf) called the **tangent bundle**.

Referenced: [Differential form](#7ce49e85-c19f-4b52-8d77-a12c0e0b62f1), [Distribution](#c7e62ec4-897a-4561-a189-15af51461c45), [Normal bundle](#b6623fd3-ef1b-4871-9296-3846fdb9d03a).


### Tangent space {#8de50bef-4318-4dd1-bcde-95464bb002dd}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 19:17]</span></span>
We denote the **tangent space** at point \\(p\\) by \\(T\_{p}(M)\\), and to each map \\(f: M \to N\\) associated a linear map \\(T\_{p}(f): T\_{p}(M) \to T\_{f(p)}N\\) the **differential** of \\(f\\) at \\(p\\), such that
\\[T\_{p}(gf) = T\_{f(p)} g \circ T\_{p}f\\]
The elements of \\(T\_{p}(M)\\) are the **tangent vectors** of \\(M\\) at \\(p\\). Cf. [Manifold](#6ff3f589-8a3d-4903-b35a-fe10657823f2).

Referenced: [Immersion](#5d4eeff2-f095-48c8-958b-4ab8f00bfd60), [Regular point](#3064e22a-123b-4f5e-9102-de7891d9bd32), [Tangent bundle](#832cf3a2-8811-475c-a05e-25dee0ef6a02), [Predeformation functor](#5bf09bb7-02f0-4ebe-86aa-588c2ac3354c).


### <span class="org-todo todo TODO">TODO</span> Uhlenbeck compactification {#27dc05fb-e0aa-4c73-a8d2-25f21344f0d1}


### Vertical subbunel {#330f8cbe-44b3-4d0c-ba26-5bf314a95cbe}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-12 Sun 20:45]</span></span>
See [Connection](#025c9171-e761-4861-bf05-42aa59e9b55b).


### Wedge product {#d1ffed59-b376-4055-8ed8-da7898e29d27}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 19:39]</span></span>
For \\(w \in \Lambda^{k}(V^{\* })\\) and \\(\eta \in \Lambda^{l}(V^{\* })\\), we define the **wedge product** or **exterior product** to be
\\[\omega \wedge \eta = \frac{(k+l)!}{k!l!} {\rm Alt}(\omega \otimes \eta)\\]


### Whitney embedding theorem {#0f63366f-2b94-4807-b592-a128341345c1}



{{% theorem %}}
A smooth \\(n\\)-manifold has an embedding as a closed submanifold of \\(\RR^{2n + 1}\\).
{{% /theorem %}}

Cf. [Sard theorem](#40a40b3c-6891-4a94-ad55-17507129aaef), [Manifold](#6ff3f589-8a3d-4903-b35a-fe10657823f2).


## Algebraic Topology {#7534352c-f57c-4db5-9085-6db3e6cfea3d}


### Alexander-Whitney map {#647c959a-7f2e-4a74-a44b-ebde48f21f0d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-26 Sun 21:25]</span></span>
See [Eilenberg-Zilber theorem](#0f96e2c1-4743-46e3-ba56-0ca173da1c8b).

Referenced: [Cup product](#795b2d16-07bf-41b0-baa3-76b5429c9ba3).


### Base {#98cee6ed-afeb-4a66-a672-4c588e623a8c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 15:12]</span></span>
See [Fibre bundle](#55a957a4-1fc2-4c8c-825d-6627b6d22e93).


### Borsuk-Ulam theorem {#0faf090d-12e5-4273-85f9-d48921171ec0}



{{% theorem %}}
Let \\(f: S^{2} \to \RR^{2}\\). Then there exists \\(x \in S^{2}\\) such that \\(f(x) = f(-x)\\).
{{% /theorem %}}

Cf. [Degree](#216ea2fe-ad83-476e-9fd8-4d687c1049c9).


### Bott periodicity {#82a32385-860c-488f-9cd4-d3f01433df28}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-24 Tue 10:55]</span></span>
We consider the [Grothendieck ring](#622ba48f-46a3-4ae0-95f4-ee3573dbeec7) of [vector bundles](#3944a5f8-1a1f-4cd2-82a0-d373c52e8bcf). We have that

{{% proposition %}}
\\(K(S^{2})\\) is free abelian group with basis \\(1\\) and \\(\eta = H(1)\\). The multiplicative structure is determined by \\(\eta^{2} = 2 \eta - 1\\).
{{% /proposition %}}

Cf. [Complex line bundle over CP^1](#69ec163b-f29c-49d5-b69b-8b1989a7feee).

The Bott periodicity is the following deep result

{{% theorem %}}
\\[K(X) \otimes K(S^{2}) \cong K(X \times S^{2})\\]
\\[KO(X) \otimes KO(S^{8}) \cong KO(X \times S^{8})\\]
{{% /theorem %}}


### Brouwer fixed point theorem {#200796ad-0da0-473c-90a6-56ec64145537}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-27 Mon 20:40]</span></span>
The **Brouwer fixed point theorem** is an example of non construction existence proof.

{{% theorem %}}
Let \\(f: D^{2} \to D^{2}\\). Then there exists \\(x \in D^{2}\\) such that \\(f(x) = x\\).
{{% /theorem %}}

The Brouwer fixed point theorem can give a proof of the fundamental theorem of algebra.

Referenced: [Existence proof](#d315cf38-ce65-43c5-9249-ffa9ec4da383).


### Category CGWH {#6fcf0c23-fe3f-4fde-80a3-6c6e6c4591c5}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 15:51]</span></span>
denote the full subcategory of [Compactly generated](#99769a47-19c4-4c86-b44b-136c305977b8) [Weak Hausdorff](#9f13cd1d-b101-4005-a7d3-f5480736e62c) space by \\(\cat{CGWH}\\).

{{% theorem %}}
The category \\(\cat{CGWH}\\) is complete and cocomplete.
{{% /theorem %}}

Cf. [Complete](#9b4f37d7-395c-4ed3-ade1-a12816dd52dc), [Cocomplete](#04c75251-d006-4a61-84a7-0a6857c09462).

Also, we have for \\(X, Y \in \cat{CGWH}\\),
\\[{\rm Map}(X, Y) \in \cat{CGWH}\\]
and the exponential law holds.

Referenced: [Realization](#65f00d44-6834-4d5c-a610-d892b2c60388), [Loop space](#23e5a4e6-5031-4076-aee6-2f811b53a2d5).


### Cellular {#e1beeea1-db35-4c2b-9c2b-42ca34f1cc83}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:52]</span></span>
Let \\((X, Y)\\) be [CW complexes](#31b773f8-25a9-4943-9ebf-5f8f5df31fad). A map \\(f: X \to Y\\) is called **cellular** if \\(f(X^{n}) \subset Y^{n}\\) for any \\(n\\). We define the category \\((cat{CW})\\) whose objects are CW complexes and morphisms are cellular maps.

Referenced: [Cellular approxiamtion theorem](#386832bb-33f7-4d94-a019-8cb1a4fd7507), [Cellular homotopy](#7696d698-c412-491d-a95c-3e2b436810a7).


### Cellular approxiamtion theorem {#386832bb-33f7-4d94-a019-8cb1a4fd7507}



{{% theorem %}}
Any map between relative CW complexes is homotopic to a cellular map. If two cellular maps between relative CW complexes are homotopic, then they are cellular homotopic.
{{% /theorem %}}

Cf. [Cellular homotopy](#7696d698-c412-491d-a95c-3e2b436810a7), [Cellular](#e1beeea1-db35-4c2b-9c2b-42ca34f1cc83) and [Relative CW complex](#4e18da69-ebed-4d26-ad89-685ccb47a041).


### Cellular homotopy {#7696d698-c412-491d-a95c-3e2b436810a7}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:54]</span></span>
A **cellular homotopy** between two [Cellular](#e1beeea1-db35-4c2b-9c2b-42ca34f1cc83) maps \\(X \to Y\\) is a [Homotopy](#4badc09a-e75b-4851-bc77-90d46eea46fd) \\(X \times I \to Y\\) that itself a cellular map. The quotient category is called \\(\cat{hCW}\\).

Referenced: [Cellular approxiamtion theorem](#386832bb-33f7-4d94-a019-8cb1a4fd7507).


### Chern class {#eb44905d-a0cb-44e0-ae41-7555ca7a984b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-22 Wed 20:40]</span></span>
Consider complex [Vector bundle](#3944a5f8-1a1f-4cd2-82a0-d373c52e8bcf) \\(E \to X\\), we wan to find sections linear independent everywhere. Then we have primary obstruction **Chern class** \\(c\_{n - k + 1} \in H^{2 (n - k + 1)}(X; \ZZ)\\). Axioms of Chern class include \\(c\_{0}(E) = 1\\), naturality and product structure and normalization \\(c(T \CC \PP^{n}) = (1 + w)^{n + 1}\\) for \\(w = \pd [\CC \PP^{n - 1}]\\).

All characteristic class (classes satisfies the naturality condition) for complex vector bundles are combination of Chern classes.

For complex manifod, with [Connection](#025c9171-e761-4861-bf05-42aa59e9b55b) \\(\nabla\_{A}\\), we can calculate the Chern class analytically by **Chern-Weil formula**

{{% theorem %}}
\\[\sum t^{k}c\_{k}(E) = \det(I - \frac{t F\_{A}}{2 \pi i})\\]
where \\(F\_{A}\\) is the curvature with respect to connection \\(\nabla\_{A}\\).
{{% /theorem %}}

Cf. [Curvature](#24adfd2f-8b92-4a12-b729-bb04f2935e6d).

This can be generalized to principal bundles.

Referenced: [Pontryagin class](#3adc046c-671b-4a0b-813e-3cdc5d09df29), [Chern-Weil theory](#0e51cc95-a929-4206-a89e-e8ab2cccb88f).


### Classifying Space {#6de51423-5039-4d35-938e-881ef5b1a5ee}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-23 Mon 19:50]</span></span>
We consider the functor \\(B(-, G)\\) from the category of topological space to sets, where \\(B(B,G)\\) denote the set of isomorphism classes of [Numerable](#6bd2d7e0-0dee-4ee3-ab4e-c390c13e143e) \\(G\\) principal bundles over \\(B\\). We have that functor representable by **classifying space** \\(BG\\), with a numerable \\(EG \to BG\\). The total space \\(EG\\) is called **universal** if each numerable free \\(G\\) space \\(E\\) has up to \\(G\\)-map \\(E \to EG\\).

We can construct \\(EG, BG\\) by **join**. We consider a family of topological space \\(X\_{j} \in J\\). Then we have
\\[X = \star\_{j \in J} X\_{j} = \\{(t\_{i}X\_{i})\_{i \in J}| \sum\_{i \in J}t\_{i} = 1\\}/ \sim\\]
where the summation has finite nonzero summand \\((t\_{i}X\_{i}) \sim (s\_{i}Y\_{i})\\) if \\(t\_{i} = s\_{i}\\) and \\(X\_{i} = Y\_{i}\\) when \\(t\_{i} = s\_{i} \neq 0\\). The topology of the space \\(X\\) is the coarsest topology where the function \\(t\_{i}: X \to \mathbb{R}, (t\_{i}X\_{i}) \to t\_{i}\\) and function \\(t\_{i}:t\_{i}^{-1}(\linterval{0}{1}) \to X\_{i}, (t\_{i}X\_{i}) \to X\_{i}\\) is continuous.

Then we construct the **Milnor space**
\\[EG = G \star G \star G \star \cdots\\]
and \\(BG = EG/G\\). The action of \\(G\\) is obvious.

{{% theorem %}}
\\(EG\\) is contractible.
{{% /theorem %}}

For a discrete group, \\(BG\\) is an [Eilenberg-Mac Lane space](#d850d002-bf3b-4611-9619-862541e582f4) of type \\(K(G,1)\\).


### Cobordism hypothesis {#808b2955-f449-4584-8035-ec5046546628}


### Cofibered {#161f16b0-7ebd-4ccc-9ce5-fc1d71bfc555}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-09 Sat 15:12]</span></span>
We say a pair \\((X, A)\\) is **cofibered** if the inclusion \\(A \subset X\\) is a [Cofibration](#793240f6-9551-465f-b749-34e6e8fd7eb3).


### Cofiber exact sequence {#af12e61a-4cba-4dc8-ba18-d986d33484d0}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:14]</span></span>
Cf. [Exact Puppe sequence](#1030d00f-61f3-4c92-b0e2-e1449e411dcd).
Let \\(f: X \to Y\\) in \\(\cat{CGWH\*}\\) between well-pointed spaces. The following sequence is co-exact in \\(\cat{hCGWH\*}\\)
\\[X \to Y \to C\_{\* f} \to \Sigma X \to \Sigma Y \to \Sigma C\_{\* f} \to \Sigma^{2}X \to \cdots\\]
Cf. [Cone](#b80cbfba-b771-44e9-97d8-e9e4efc0572b).


### Cofibration {#793240f6-9551-465f-b749-34e6e8fd7eb3}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-09 Sat 15:05]</span></span>
A map \\(i: A \to X\\) is called a **cofibration** if it has [Homotopy extension property](#3a75f46c-1b37-44fc-959b-d471a42b0601) for any spaces.

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

Referenced: [Cofibered](#161f16b0-7ebd-4ccc-9ce5-fc1d71bfc555), [Well-pointed](#1395975d-4bd9-4305-a803-a248abce490e).


### Cohomology {#a918cddf-cd03-4546-a2cd-ce897e10cf82}



There are various **cohomology** theories. The can be defined by common axioms.

{{% definition %}}
A **cohomology theory** for pairs of spaces with values in the category of \\(R\\)-modules consists of a family \\((h^{n} \mid n \in \ZZ)\\) of contravariant functors \\(h^{n}: TOP(2) \to R-MOD\\) and natural transformations \\(\delta^{n}: h^{n - 1} \circ \kappa \to h^{n}\\) such that

-   Homotopy invariance. Homotopic maps \\(f\_{0}\\) and \\(f\_{1}\\) between pairs of space induces the same homomorphism \\(h^{n}(f\_{0}) = h^{n}(f\_{1})\\).
-   Exact sequence. For each pair \\((X, A)\\), we have exact sequence
    \\[\cdots \to h^{n - 1}(A, \emptyset) \stackrel{\delta}{\to} h^{n}(X, A) \to h^{n}(X, \emptyset) \to h^{n}(A) \to \cdots \\]
-   Excision. Let \\((X, A)\\) be a pair and \\(U \subset A\\) such that \\(\bar{U} \subset A^{\circ}\\). Then the inclusion \\((X \backslash U, A \backslash U) \to (X,A)\\) induces an isomorphism \\(h^{n}(X, A) \cong h^{n}(X \backslash U, A \backslash U)\\).
{{% /definition %}}

Cf. [Excision theorem](#4dc11ed0-fefd-4a5e-8bb2-13228dcc76ac), [Mayer-Vietoris sequence](#557c64a5-48f3-4076-814f-7bae7d157188).

Given a cohomology theory, we called \\(h^{n}(X,A)\\) the \\(n\\)-th **cohomology group**. The \\(\delta^{n}\\) are called the coboundary operator. And we write \\(h^{n}(X) := h^{n}(X, \emptyset)\\).

As in homology theory, we called \\(h^{n}(pt)\\) the coefficient groups of the theory and a cohomology theory may have following additional axioms

-   dimension axiom. \\(h^{n}(pt) = 0\\) for \\(n \neq 0\\).
-   additive axiom. \\[h^{n}(\coprod X\_{j}, \coprod A\_{j}) \to \coprod\_{j} h^{n}(X\_{j}, A\_{j})\\]
    is always an isomorphism.

Also, we have triple exact sequence
\\[ \cdots \to h^{n - 1}(A, B) \stackrel{\delta}{\to} h^{n}(X, A) \to h^{n}(X, B) \to h^{n}(A, B) \stackrel{\delta}{\to} \cdots\\]

Cf. [de Rham cohomology](#111be87b-27bd-4c19-8499-e5e4b2cb1956).

Referenced: [Cap product](#ef1f3139-4e4c-4350-a10c-893f7ee5ef37), [Eilenberg-Mac Lane space](#d850d002-bf3b-4611-9619-862541e582f4), [Excision theorem](#4dc11ed0-fefd-4a5e-8bb2-13228dcc76ac), [Mayer-Vietoris sequence](#557c64a5-48f3-4076-814f-7bae7d157188), [Reduced cohomology](#5d5cf65e-1ff4-48da-9f2a-87928aee347b), [Category of modules](#bd4d822f-e06f-422b-b64f-343e6782e57b).


#### Singular cohomology {#9b5b928f-d06e-49b1-bf7a-3b873d3f2c59}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-09 Thu 20:23]</span></span>
Cf. [Singular homology](#bd775417-5818-4811-9aa6-e3819b0e3fd1).

We consider the cochain complex \\(S^{n}(X; G) = \Hom(S\_{n}(X), G)\\) and define the i-th **singular cohomology** by the i-th cohomology group of the cochain complex.

Referenced: [de Rham theorem](#40d0778f-997f-4107-9cd8-3dc355c3f21c).


#### Relative singular cohomology {#8afbf243-467d-4920-b5bd-aeb7cb8d67de}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-13 Wed 21:00]</span></span>
We define the **relative singular cochain complex** by \\(S^{\bullet}(X, A; G) = \Hom(S\_{\bullet}(X)/S\_{\bullet}(A), G)\\). Its cohomology is called the **relative singular cohomology**.


#### Compactly supported cohomology {#699bcfec-40ae-4831-8f1e-8dd6009f5c76}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-27 Mon 20:24]</span></span>
Let \\(\mathscr{K}\\) denote the set of compact subspaces of \\(X\\). We define **compactly supported cohomology** of \\(X\\) by
\\[H\_{c}^{k}(X) :=\colim\_{K \in \mathscr{K}} H^{k}(X, X - K)\\]
In particular if \\(X\\) is compact, we have \\(H\_{c}^{k}(X) = H^{k}(X)\\).

The compactly supported cohomology also satisfies [Mayer-Vietoris sequence](#557c64a5-48f3-4076-814f-7bae7d157188).

Referenced: [Poincaré duality](#6aa27439-616e-4396-860c-d815999dfd79).


#### Cup product {#795b2d16-07bf-41b0-baa3-76b5429c9ba3}

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

For the most importanct case \\(A = B = \emptyset\\), the cup product can be given by [Alexander-Whitney map](#647c959a-7f2e-4a74-a44b-ebde48f21f0d), that is
\\[(\alpha \cup \beta)(\sigma) = \alpha(\_{p}\sigma) \cdot \beta(\sigma\_{q})\\]

The morphism \\(H^{\* }(-; R)\\) is natural, that is it is a functor from the category of topological spaces to the category of graded commutative rings.


#### Cap product {#ef1f3139-4e4c-4350-a10c-893f7ee5ef37}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-26 Sun 21:34]</span></span>
We have **cap product** between [Cohomology](#a918cddf-cd03-4546-a2cd-ce897e10cf82) and [Homology](#c521a510-803a-40bb-9f2b-5e24bdf9a699). That is we first consider the pairing
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


#### External product {#84023b36-ba3c-4a54-9d47-6e378419055f}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-07 Tue 21:42]</span></span>
For details see, section 17.3 in [<span id="5ad6139c99b6d2508f6ef6f11ce7f09d"><a href="#dieck2008" title="tom Dieck, Algebraic Topology, {European Mathematical Society} (2008).">dieck2008</a></span>].

The **external product** is a family of \\(R\\)-linear maps
\\[h^{m}(X, A) \otimes\_{R} h^{n}(Y, B) \to h^{m + n}((X, A) \times (Y, B)), x \otimes y \to x \times y\\]
The external products satisfying some properties.


### Compactly generated {#99769a47-19c4-4c86-b44b-136c305977b8}

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

Referenced: [Category CGWH](#6fcf0c23-fe3f-4fde-80a3-6c6e6c4591c5).


### Complex line bundle over CP^1 {#69ec163b-f29c-49d5-b69b-8b1989a7feee}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-24 Tue 10:18]</span></span>
We have that \\(H(k) = (\mathbb{C}^{2} \backslash 0) \times\_{\mathbb{C}^{\* }} \mathbb{C}\\) with equivalence relation \\(((z\_{0}, z\_{1}), u) \sim ((\lambda z\_{0}, \lambda z\_{1}), \lambda^{k} u) \\). Then we have that \\(H(k)\\) represent the isomorphism classes of complex line bundles.

{{% remark %}}
This is a simple but non-trivial fact, leading naturally to the problems of complex line bundles over \\(\mathbb{C}P^{n}\\). And more generally, vector bundles over \\(\mathbb{C}P^{n}\\).
{{% /remark %}}

Cf. [Vector bundle](#3944a5f8-1a1f-4cd2-82a0-d373c52e8bcf)

Referenced: [Bott periodicity](#82a32385-860c-488f-9cd4-d3f01433df28).


### Cone {#b80cbfba-b771-44e9-97d8-e9e4efc0572b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:18]</span></span>
Let \\((X, x\_{0}) \in \cat{CGWH\*}\\). We define its **cone** by
\\[C\_{\* }X = X \wedge I = X \times I / (X \times \\{0\\} \cap \\{x\_{0}\\} \times I)\\]
Cf. [Smash product](#90750e55-bff5-474e-99e6-7a08b30f3f92).

Referenced: [Cofiber exact sequence](#af12e61a-4cba-4dc8-ba18-d986d33484d0), [Homotopy cofiber](#dc96a3af-6ea9-4037-b3ff-741179ef4f2e).


### <span class="org-todo todo TODO">TODO</span> Contractible {#ededb2d9-23e9-4438-9632-d497708cffdf}



Referenced: [Integer homology 3-sphere](#365edc60-5f78-42bb-a010-fcaa0b69b644).


### Covering {#e5f94645-231a-4765-8cdd-6d6c89a58f6a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 15:10]</span></span>
A **covering (space)** is a [Locally trivial](#999af1ba-af36-4a0b-9304-320d70f5eaa9) map \\(p: E \to B\\) with discrete [Fibre](#b737cff2-f621-43a4-bdef-e094c8ff3c5f) \\(F\\). A covering map which is a trivial [Fibre bundle](#55a957a4-1fc2-4c8c-825d-6627b6d22e93) is also called a **trivial covering**.

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

Cf. [Path connected](#be3b8eef-420f-47dc-af50-005ce1bb2161), [Semi-locally simply connected](#1bac04f0-4749-49b2-8fe9-9948fb8daedb).

Referenced: [Deck transformation](#da862591-d0f4-4f8d-a906-b38f482daf5a), [Fibration](#7a557249-6a76-40ae-9e38-231b828a22e9), [Fundamental group](#f2693b59-6cae-4cb7-85c4-d09e21ffe625), [G-principal covering](#8172c6e1-8747-4190-a6d8-89754b7d32db), [Lifting](#76602510-3721-461d-9c18-80fcf062e5a9), [Universal covering](#42558a60-2e3d-4d09-9b7a-31517f753318).


### CW approximation {#6f12de59-ad55-49fa-a51d-bf2ff07d1139}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:58]</span></span>
A **CW approximation** of a topological space \\(Y\\) is a [CW complex](#31b773f8-25a9-4943-9ebf-5f8f5df31fad) \\(X\\) with a [Weak homotopy equivalence](#3d692166-e320-45a7-b311-785db83d13a4) \\(f: X \to Y\\).

The following theorem making the study of topological space reduces to the study of CW complex up to weak homotopy equivalence.

{{% theorem %}}
Any space has a CW approximation.
{{% /theorem %}}


### <span class="org-todo todo TODO">TODO</span> CW complex {#31b773f8-25a9-4943-9ebf-5f8f5df31fad}



Referenced: [Cellular](#e1beeea1-db35-4c2b-9c2b-42ca34f1cc83), [CW approximation](#6f12de59-ad55-49fa-a51d-bf2ff07d1139), [Eilenberg-Mac Lane space](#d850d002-bf3b-4611-9619-862541e582f4), [Whitehead theorem](#b02aba25-72ab-46c8-8b63-f13919980fea).


### Deck transformation {#da862591-d0f4-4f8d-a906-b38f482daf5a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:29]</span></span>
Let \\(B\\) be a [Path connected](#be3b8eef-420f-47dc-af50-005ce1bb2161) and \\(p: E \to B\\) be a connected [Covering](#e5f94645-231a-4765-8cdd-6d6c89a58f6a). A **deck transformation** is a homeomorphism \\(f: E \to E\\) such that \\(p \circ f = p\\). We denote the group of deck transformations by \\( \aut(p)\\).


### Deformation retract {#312dfaaf-4372-4d58-b8dd-01d42aee7662}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:19]</span></span>
See [Retraction](#a383ee4e-3190-4791-8587-0901a021c46b).

Referenced: [Neighborhood deformation retract](#6a287f14-edd1-48fb-835e-e012dcac9b77).


### Degree {#216ea2fe-ad83-476e-9fd8-4d687c1049c9}



For degree of isogeny, see [Isogeny](#35538f98-babe-4fc7-82a3-81a3964c035a).

For degree of a map \\(f: S^{n} \to S^{n}\\), the **degree** its image in the [Homotopy group](#492ddb93-4c8a-434e-9757-14fdbd6102f1) \\(\pi\_{n}(S^{n}) \cong \ZZ\\).

Referenced: [Borsuk-Ulam theorem](#0faf090d-12e5-4273-85f9-d48921171ec0).


### Eilenberg-Mac Lane space {#d850d002-bf3b-4611-9619-862541e582f4}



{{% definition %}}
The **Eilenberg-Mac Lane space** \\(K(G, n)\\) is the space with homotopy group \\(\pi\_{i}(K(G,n)) = 0\\) for \\(i \neq n\\) and \\(G\\) if \\(i = n\\).
{{% /definition %}}

{{% theorem %}}
The Eilenberg-Mac Lane spaces exist.
{{% /theorem %}}

Eilenberg-Mac Lane space is the representation space for [Cohomology](#a918cddf-cd03-4546-a2cd-ce897e10cf82), that is we have the following

{{% theorem %}}
\\[H^{n}(X; G) \cong [X, K(G,n)]\\]
for any CW complex \\(X\\).
{{% /theorem %}}

Cf. [CW complex](#31b773f8-25a9-4943-9ebf-5f8f5df31fad).

{{% exam %}}
\\[\CC P^{\infty} = K(\ZZ, 2)\\]
{{% /exam %}}

Referenced: [Classifying space](#8274f12e-0561-404b-907f-0568cdcb95cf), [Classifying Space](#6de51423-5039-4d35-938e-881ef5b1a5ee).


### Eilenberg-Zilber theorem {#0f96e2c1-4743-46e3-ba56-0ca173da1c8b}



{{% theorem %}}
If \\(H\_{0}(S\_{\bullet}(X \times Y)) = H\_{0}(S\_{\bullet}(X)) \otimes H\_{0}(S\_{\bullet}(Y))\\), then there exists natural transformations
\\[S\_{\bullet}(- \times -) \stackrel{F}{\underset{G} \Longleftrightarrow} S\_{\bullet}(-) \otimes S\_{\bullet}(-)\\]
And therefore isomorphisms on homology groups. Here \\(F\\), \\(G\\) is called **Eilenberg-Zilber map**.
{{% /theorem %}}

The proof of the theorem relies on [Spectral sequence](#39be8244-5b96-4223-99ec-9259f5c649ec) and is rather abstract. However, for [Singular homology](#bd775417-5818-4811-9aa6-e3819b0e3fd1), there exists a explicit form of the Eilenberg-Zilber map, called **Alexander-Whitney map**. First for \\(\sigma: \Delta^{n} \to X\\), we introduce the map \\( \_{p} \sigma: \Delta^{p} \to X, \_{p} \sigma(t\_{0}, \cdots, t\_{p}) = \sigma(t\_{0}, \cdots, t\_{p}, 0 ,\cdots, 0)\\) and \\(\sigma\_{q}(t\_{0}, \cdots, t\_{q}) = \sigma(0, \cdots, 0, t\_{0}, \cdots, t\_{q})\\), and then we have Alexander-Whitney map
\\[AW: S\_{\bullet}(X \times Y) \to S\_{\bullet}(X) \otimes S\_{\bullet}(Y)\\]
given by
\\[AW(\sigma) = \sum\_{p + q = n} {}\_{p}(\pi\_{X} \circ \sigma) \otimes (\pi\_{Y} \circ \Sigma)\_{q}\\]
By Eilenberg-Zilber theorem, the above map is a chain homotopy equivalence.

Cf. [Homology](#c521a510-803a-40bb-9f2b-5e24bdf9a699).

Referenced: [Alexander-Whitney map](#647c959a-7f2e-4a74-a44b-ebde48f21f0d).


### <span class="org-todo todo TODO">TODO</span> Equivariant cohomology {#c6af30c7-f999-48d3-8c55-8776b454f38a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-29 Sun 15:25]</span></span>
Compared with classical cohomology theory, the equivariant cohomology is more general and simpler.

Referenced: [Geometric representation theory](#7f5a1efb-e09c-414a-858d-b0e65e83c4bc).


### <span class="org-todo todo TODO">TODO</span> Equivariant K-theory {#b8cfa111-3c52-4bb3-8fbd-63d76b24916b}



Referenced: [Geometric representation theory](#7f5a1efb-e09c-414a-858d-b0e65e83c4bc).


### Euler class {#6c02fdc1-d947-45e7-b613-a5c7108163fc}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-22 Wed 20:34]</span></span>
Let \\(p: E \to X\\) be a real [Oriented](#0d1fefb5-7409-4540-8afb-5b3c67e90acd) [Vector bundle](#3944a5f8-1a1f-4cd2-82a0-d373c52e8bcf) of dimension \\(n\\), we want to find a nowhere vanishing section \\(s: X \to E\\), the primary obstruction is defined as the **Euler class** \\(e(E) \in H^{n}(X; \ZZ)\\). A geometric definition is taht we consider a generic section \\(s: X \to E\\) which is transverse to zero section, then \\(s^{-1}(0)\\) is a submanifold of \\(X\\) of codimension \\(n\\) and \\(e(E)\\) can be taken as Poincaré dual of \\([s^{-1}(0)]\\).

Referenced: [Poincaré-Hopf thereom](#3fffc275-36f0-47b6-90b8-a763a8098ae0).


### Exact Puppe sequence {#1030d00f-61f3-4c92-b0e2-e1449e411dcd}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-09 Sat 14:26]</span></span>
A sequence in \\(\cat{hCGWH}\\) is **exact** if for any \\(Y\\), the sequence \\(\cdots \to [Y, X\_{n + 1}]\_{0} \to [Y, X]\_{0} \to [Y, X\_{n - 1}]\_{0} \to \cdots\\) is exact. Let [Homotopy fiber](#8faa91f0-3bd9-4e63-b241-f22da0c6450e) \\(F\_{f}\\) be the pullback of \\(p\_{1}:P\_{y\_{0}}Y \to Y\\) and \\(f:X \to Y\\) in category \\(\cat{CGWH\*}\\). Then we have

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

Cf. [Fibration](#7a557249-6a76-40ae-9e38-231b828a22e9), [Homotopy group](#492ddb93-4c8a-434e-9757-14fdbd6102f1).

Referenced: [Cofiber exact sequence](#af12e61a-4cba-4dc8-ba18-d986d33484d0).


### Excision theorem {#4dc11ed0-fefd-4a5e-8bb2-13228dcc76ac}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-12 Tue 18:07]</span></span>
The [Mayer-Vietoris sequence](#557c64a5-48f3-4076-814f-7bae7d157188) has a equivalent description called **excision theorem**.

{{% theorem %}}
Let \\(U \subset A \subset X\\) be subspaces such that \\(\bar{U} \subset A^{\circ}\\). Then the inclusion \\(i:(X - U, A - U) \to (X, A)\\) induces isomorphisms
\\[i\_{\* }: H\_{n}(X - U, A - U) \cong H\_{n}(X, A), \\; \forall n\\]
{{% /theorem %}}

Cf. [Homology](#c521a510-803a-40bb-9f2b-5e24bdf9a699) and [Cohomology](#a918cddf-cd03-4546-a2cd-ce897e10cf82).

Referenced: [Cohomology](#a918cddf-cd03-4546-a2cd-ce897e10cf82).


### Fibration {#7a557249-6a76-40ae-9e38-231b828a22e9}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 15:42]</span></span>
A map \\(p: E \to B\\) is a **fibration** if \\(p\\) has [Homotopy lifting property](#3405114c-c1b4-4b99-8e91-b97165362e56).

{{% theorem %}}
A covering is a fibration.
{{% /theorem %}}

Cf. [Covering](#e5f94645-231a-4765-8cdd-6d6c89a58f6a).

By the corollary in [Homotopy fiber](#8faa91f0-3bd9-4e63-b241-f22da0c6450e), we see that fibration is similar to [Fibre bundle](#55a957a4-1fc2-4c8c-825d-6627b6d22e93). In the converse, we have following criterion for fibration

{{% theorem %}}
Let \\(p:E \to B\\) be a fiber bundle with \\(B\\) paracompact Hausdorff. Then \\(p\\) is a fibration.
{{% /theorem %}}

Referenced: [Kan fibration](#24c4c625-6639-4558-95ed-fbb6015188fa), [Exact Puppe sequence](#1030d00f-61f3-4c92-b0e2-e1449e411dcd), [Homotopy fiber](#8faa91f0-3bd9-4e63-b241-f22da0c6450e).


### Fibre {#b737cff2-f621-43a4-bdef-e094c8ff3c5f}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 15:12]</span></span>
See [Fibre bundle](#55a957a4-1fc2-4c8c-825d-6627b6d22e93).

Referenced: [Covering](#e5f94645-231a-4765-8cdd-6d6c89a58f6a).


### Fibre bundle {#55a957a4-1fc2-4c8c-825d-6627b6d22e93}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 15:07]</span></span>
Let \\(p: E \to B\\) be in \\(\cat{Top}\\). A **trivialization** of \\(p\\) over an open set \\(U \subset B\\) is a homeomorphism \\(\phi:p^{-1}(U) \to U \times F\\) over \\(U\\), such that the following diagram commutes

![](/img/2021-10-07_15-09-18_screenshot.png)
\\(p\\) is called **locally trivial** if there exists an open cover \\(\mathscr{U}\\) of \\(B\\) such that \\(p\\) has trivialization over each open \\(U \in \mathscr{U}\\). Such \\(p\\) is called a **fibre bundle**, \\(F\\) is called the **fiber** and \\(B\\) is called the **base**. And we denoted by
\\[F \to E \to B\\]

Cf. [Vector bundle](#3944a5f8-1a1f-4cd2-82a0-d373c52e8bcf).

{{% exam %}}
\\[S^{1} \to S^{2n + 1} \to \CC P^{n}\\]
{{% /exam %}}

Referenced: [Base](#98cee6ed-afeb-4a66-a672-4c588e623a8c), [Covering](#e5f94645-231a-4765-8cdd-6d6c89a58f6a), [Fibration](#7a557249-6a76-40ae-9e38-231b828a22e9), [Fibre](#b737cff2-f621-43a4-bdef-e094c8ff3c5f), [Homotopy fiber](#8faa91f0-3bd9-4e63-b241-f22da0c6450e), [Local trivial](#999af1ba-af36-4a0b-9304-320d70f5eaa9), [Trvialization](#f078be8d-cd6a-40f8-a374-8c2de3f34e0e).


### Fibre homotopy {#cbc7a957-3200-4db4-af75-aa4e42725728}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 21:32]</span></span>
For two fibrations \\(p\_{1}:E\_{1} \to B\\) and \\(p\_{2}: E\_{2} \to B\\) and two fiber maps \\(f\_{0}, f\_{1}:p\_{1} \to p\_{2}\\) are said to be **fiber homotopic** if there exists a homootpy \\(F: E\_{1} \times I \to E\_{2}\\) such that \\(F(-, t)\\) is a fiber map for each \\(t \in I\\). \\(f:p\_{1} \to p\_{2}\\) is a **fiber homotopic equivalence** if there exists an inverse.

{{% proposition %}}
Let \\(p\_{1}:E\_{1} \to B\\) and \\(p\_{2}: E\_{2} \to B\\) be two fibrations and \\(f:E\_{1} \to E\_{2}\\) be a fiber map. Assume \\(f: E\_{1} \to E\_{2}\\) is a homotopy equivalence, then \\(f\\) is a fiber homotopy equivalence. In particular, \\(f: p\_{1}^{-1}(b) \to p\_{2}^{-1}(b)\\) is a homotopy equivalence.
{{% /proposition %}}


### Fundamental class {#b4d8db93-4571-4034-a37d-bc5ebea10fea}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-31 Tue 18:12]</span></span>
Theorem 16.4.1 in [<span id="5ad6139c99b6d2508f6ef6f11ce7f09d"><a href="#dieck2008" title="tom Dieck, Algebraic Topology, {European Mathematical Society} (2008).">dieck2008</a></span>].

{{% theorem %}}
Let \\(M\\) be a compact connected \\(n\\)-[Manifold](#6ff3f589-8a3d-4903-b35a-fe10657823f2). Then one of the following holds:

-   \\(M\\) is orientable, then we have that \\(H\_{n}(M) \cong \ZZ\\) and for each \\(x \in M\\), \\(r^{M}\_{x}\\) is isomorphism.
-   \\(M\\) is non-orientable, then \\(H\_{n}(M) = 0\\).
{{% /theorem %}}

Cf. [Orientation](#0d1fefb5-7409-4540-8afb-5b3c67e90acd), [Local homology group](#d72fb6c4-7adf-4742-85d8-bbc041072bd5).

If \\(M\\) is orientable, then a generator will be called **fundamental class**. If \\(M\\) is a manifold with boundary, then we call \\(z \in H\_{n}(M, \partial M)\\) a **fundamental class** if for each \\(x \in M \backslash \partial M\\) the restriction of \\(z\\) is a generator in \\(H\_{n}(M, M \backslash x)\\), cf. [Local homology group](#d72fb6c4-7adf-4742-85d8-bbc041072bd5).

Theorem 16.5.1 (ibid.)

{{% theorem %}}
Let \\(M\\) be a compact connected \\(n\\)-manifold with non-empty boundary. Then one of the following holds:

-   \\(H\_{n}(M, \partial M) \cong \ZZ\\) and a generator of this group is a fundamental class. The image of the map \\(\partial: H\_{n}(M, \partial M) \to H\_{n - 1}(\partial M)\\) is a fundamental class. The interior \\(M \backslash \partial M\\) is orientable.
-   \\(H\_{n}(M, \partial M) = 0\\), and \\(M \backslash \partial M\\) is not orientable.
{{% /theorem %}}

Referenced: [Poincaré duality](#6aa27439-616e-4396-860c-d815999dfd79), [Virtual fundamental class](#7d52eb53-34d5-4da6-80f4-7242956a1c44).


### <span class="org-todo todo TODO">TODO</span> Fundamental group {#f2693b59-6cae-4cb7-85c4-d09e21ffe625}



{{% proposition %}}
Let \\(p: E \to B\\) be a covering and \\(E\\) path connected. Let \\(e \in E\\) and \\(b = p(e) \in B\\). Then the action of \\(\pi\_{1}(B, b)\\) on \\(p^{-1}(b)\\) is transitive, whose stabilizer at \\(e\\) is \\(\pi\_{1}(E, e)\\). In other words, we have following exact sequence
\\[1 \to \pi\_{1}(E, e) \to \pi\_{1}(B, b) \to p^{-1}(b) \to 1\\]
{{% /proposition %}}

Cf. [Covering](#e5f94645-231a-4765-8cdd-6d6c89a58f6a).

{{% theorem %}}
Let \\(p: E \to B\\) be a \\(G\\)-principal covering, \\(E\\) path connected, \\(e \in E\\), \\(b = p(e)\\). Then we have an exact sequence of groups
\\[1 \to \pi\_{1}(E, e) \to \pi\_{1}(B, b) \to G \to 1\\]
That is \\(\pi\_{1}(E, e)\\) is a normal subgroup of \\(\pi\_{1}(B, b)\\).
{{% /theorem %}}

Cf. [G-principal covering](#8172c6e1-8747-4190-a6d8-89754b7d32db) and above theorem.

Referenced: [Homotopy group](#492ddb93-4c8a-434e-9757-14fdbd6102f1), [Seifert-Van Kampen theorem](#22a5ec7c-c651-4698-8825-d13578a874c2), [Semi-locally simply connected](#1bac04f0-4749-49b2-8fe9-9948fb8daedb), [Braid group](#3fd75bd7-4528-40df-b4ee-70f3675e2a36).


### <span class="org-todo todo TODO">TODO</span> Fundamental groupoid {#0e9e2de9-6240-4faf-a6fd-12251e178293}



Referenced: [Seifert-Van Kampen theorem](#22a5ec7c-c651-4698-8825-d13578a874c2).


### G-principal covering {#8172c6e1-8747-4190-a6d8-89754b7d32db}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 15:54]</span></span>
A left **\\(G\\)-principal covering** is a [Covering](#e5f94645-231a-4765-8cdd-6d6c89a58f6a) \\(p: E \to B\\) with a left [Properly discontinuous](#b8b322d4-aa85-444d-a157-deee448da647) \\(G\\)-action on \\(E\\) over \\(B\\) commutes with the covering map.

{{% exam %}}
The map \\(\RR^{1} \to S^{1}\\) is a \\(\ZZ\\)-principal covering for action \\(n: t \to t + n\\).
{{% /exam %}}

Referenced: [Fundamental group](#f2693b59-6cae-4cb7-85c4-d09e21ffe625).


### Grothendieck ring {#622ba48f-46a3-4ae0-95f4-ee3573dbeec7}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-24 Tue 10:55]</span></span>
Given a commutative monoid \\(M\\) which is a set together with an associative and commutative composition law \\(+\\) with zero element. We have a group \\(K(M) = M \times M / D(M)\\). That is elements of \\(K(M)\\) are of the form \\((a,b) \in M \times M\\), with equivalence relation \\((a, b) \sim (c, d)\\) if \\((a + n, b + n) = (c + m, d + m)\\) for some \\(m,n \in M\\). Such group is called **Grothendieck group**. If the monoid is given with a multiplicative structure, which can by inherited by Grothendieck group, the group becomes **Grothendieck ring**.

Referenced: [Bott periodicity](#82a32385-860c-488f-9cd4-d3f01433df28), [Vector bundle](#3944a5f8-1a1f-4cd2-82a0-d373c52e8bcf).


### <span class="org-todo todo TODO">TODO</span> Homology {#c521a510-803a-40bb-9f2b-5e24bdf9a699}



Referenced: [Cap product](#ef1f3139-4e4c-4350-a10c-893f7ee5ef37), [Eilenberg-Zilber theorem](#0f96e2c1-4743-46e3-ba56-0ca173da1c8b), [Excision theorem](#4dc11ed0-fefd-4a5e-8bb2-13228dcc76ac), [Hurewicz theorem](#ead0481e-e574-4458-863e-26d30b5ba7aa), [Whitehead theorem](#b02aba25-72ab-46c8-8b63-f13919980fea).


#### Singular homology {#bd775417-5818-4811-9aa6-e3819b0e3fd1}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-26 Sun 19:55]</span></span>
A **singular n-simplex** is a continuous map \\(\sigma: \Delta^{n} \to X\\), where \\(\Delta^{n}\\) is the [Standard n-simplex](#a69d168f-a9c9-40d1-a5e5-cd594854534c). We define \\(S\_{n}(X)\\) to be the free abelian group by all singular \\(n\\)-simplexes \\(S\_{n}(X) = \oplus\_{\sigma \in \Hom(\Delta^{n}, X)} \ZZ \sigma\\). An element of \\(S\_{n}\\) is called a **singular n-chain** in \\(X\\). Given \\(\sigma: \Delta^{n} \to X\\), we have \\(\partial^{i} \sigma: \Delta^{n - 1} \to X\\) for \\(0 \leq i \leq n\\), by restricting the \\(\sigma\\) to the \\(i\\)-th face of the \\(\Delta^{n}\\) whose vertices are given by \\(\\{v\_{0}, v\_{1}, \cdots, \hat{v}\_{i}, \cdots, v\_{n}\\}\\). And we define the **boundary map** \\(\partial: S\_{n}(X) \to S\_{n - 1}(X)\\) to be \\(\partial \sigma = \sum\_{i = 0}^{n} (-1)^{i} \partial^{(i)} \sigma\\). Then \\((S\_{\bullet}(X), \partial)\\) defines a chain complex and we define the \\(n\\)-th **singular homology** group of \\(X\\) by
\\[H\_{n}(X) = H\_{n}(S\_{\bullet}(X), \partial)\\]

The singular homology groups are homotopy invariants.

The following theorem is sometimes called **dimension axiom**.

{{% theorem %}}
If \\(X\\) is contractible, then

\begin{equation} H\_{n}(X) =   \begin{cases}     0 & n > 0 \\\\     \ZZ & n = 0   \end{cases} \end{equation}
{{% /theorem %}}

Referenced: [Simplicial set](#7f7b56bd-7f4f-4dd4-8aa1-e57a14f6e423), [Singular cohomology](#9b5b928f-d06e-49b1-bf7a-3b873d3f2c59), [Eilenberg-Zilber theorem](#0f96e2c1-4743-46e3-ba56-0ca173da1c8b), [Künneth formula](#bf2b57da-b412-4014-9d62-6ec3f8bfc7f7), [Local homology group](#d72fb6c4-7adf-4742-85d8-bbc041072bd5), [Poincaré duality](#6aa27439-616e-4396-860c-d815999dfd79).


#### Relative singular homology {#99473e22-a6b0-460f-983c-78f8224102b5}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-12 Tue 17:45]</span></span>
Let \\(A \subset X\\) be a subspace. It induces a natural injective chain map \\(S\_{\bullet}(A) \to S\_{\bullet}(X)\\). We define the singular chain complex of \\(X\\) relative to \\(A\\) to be
\\[S\_{n}(X, A) = S\_{n}(X)/S\_{n}(A)\\]
with the induced differential. Its homology \\(H\_{n}(X, A) = H\_{n}(S\_{\bullet}(X, A))\\) is called the \\(n\\)-th **relative homology**.


#### <span class="org-todo todo TODO">TODO</span> Reduced homology {#faed95ba-4829-4d21-ba6e-5ee8bf024fe4}



{{% theorem %}}
Let \\((X, x\_{0})\\) be a well-pointed space, then \\(\tilde{H}\_{n}(\Sigma X) = \tilde{H}\_{n - 1}(X)\\).
{{% /theorem %}}

Cf. [Suspension](#fd1ebb6e-9c0a-42fb-9883-8f4bdb98c9d8).


#### <span class="org-todo todo TODO">TODO</span> Cellular homology {#9a27868f-b9e4-4502-9028-0023ec93fbc1}


### <span class="org-todo todo TODO">TODO</span> Homotopy {#4badc09a-e75b-4851-bc77-90d46eea46fd}



Referenced: [Simplicial homotopy](#1dba3777-e013-410a-92c7-f4cb919f71be), [Cellular homotopy](#7696d698-c412-491d-a95c-3e2b436810a7), [Hurewicz theorem](#ead0481e-e574-4458-863e-26d30b5ba7aa).


### Homotopy cofiber {#dc96a3af-6ea9-4037-b3ff-741179ef4f2e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:25]</span></span>
Cf. [Homotopy fiber](#8faa91f0-3bd9-4e63-b241-f22da0c6450e).

Given \\(f: X \to Y\\) in \\(\cat{CGWH\*}\\), we define **homotopy cofiber** \\(C\_{ \* f}\\) by the push-out of \\(X \to C\_{\*}X\\) and \\(f: X \to Y\\).
Cf. [Cone](#b80cbfba-b771-44e9-97d8-e9e4efc0572b).


### Homotopy excision theorem {#5b378933-4009-4560-9b6c-181bbfae4a3c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-12 Tue 08:17]</span></span>
Let \\((A, C)\\), \\((B, C)\\) be [Relative CW complex](#4e18da69-ebed-4d26-ad89-685ccb47a041). Let \\(X\\) be the push-out of \\(C \to B\\) and \\(C \to A\\). If \\((A, C)\\) is [m-connected](#6be27a99-14e3-44f6-841b-623c45da5223) and \\((B, C)\\) is [n-connected](#6be27a99-14e3-44f6-841b-623c45da5223), then
\\[\pi\_{i}(A, C) \to \pi\_{i}(X, B)\\]
is an isomorphism for \\(i < m + n\\) and a surjection for \\(i = m + n\\).


### Homotopy extension property {#3a75f46c-1b37-44fc-959b-d471a42b0601}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-09 Sat 15:02]</span></span>
A map \\(i: A \to X\\) is said to have the **homotopy extension property** (HEP) with respect to \\(Y\\) if for any map \\(f:X \to Y\\) and any homotopy \\(F:A \times I \to Y\\), we have following commutative diagram.

{{< figure src="/img/2021-10-09_15-04-49_screenshot.png" >}}

Referenced: [Cofibration](#793240f6-9551-465f-b749-34e6e8fd7eb3).


### Homotopy fiber {#8faa91f0-3bd9-4e63-b241-f22da0c6450e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-09 Sat 14:52]</span></span>
Let \\(f: X \to Y\\), we define its **homotopy fiber** over \\(y \in Y\\) to be the fiber of \\(P\_{f} \to Y\\) over \\(y\\). Then we have

{{% proposition %}}
If \\(Y\\) is path connected, then all homotopy fibers of \\(f:X \to Y\\) are homotopic equivalent.
{{% /proposition %}}

Cf. [Path connected](#be3b8eef-420f-47dc-af50-005ce1bb2161).

{{% proposition %}}
If \\(f: X \to Y\\) is a fibration, then its homotopy fiber at \\(y\\) is homootpy equivalent to \\(f^{-1}(y)\\).
{{% /proposition %}}

{{% corollary %}}
Let \\(f:X \to Y\\) be a fibration and \\(Y\\) path connected. Then all fibers of \\(f\\) are homotpy equivalent.
{{% /corollary %}}

Therefore, [Fibration](#7a557249-6a76-40ae-9e38-231b828a22e9) is similar to [Fibre bundle](#55a957a4-1fc2-4c8c-825d-6627b6d22e93).

Referenced: [Exact Puppe sequence](#1030d00f-61f3-4c92-b0e2-e1449e411dcd), [Fibration](#7a557249-6a76-40ae-9e38-231b828a22e9), [Homotopy cofiber](#dc96a3af-6ea9-4037-b3ff-741179ef4f2e).


### <span class="org-todo todo TODO">TODO</span> Homotopy group {#492ddb93-4c8a-434e-9757-14fdbd6102f1}



Unlike the [Fundamental group](#f2693b59-6cae-4cb7-85c4-d09e21ffe625), the higher homotopy group is abelian.

{{% proposition %}}
\\(\pi\_{n}(X)\\) is abelian if \\(n \geq 2\\).
{{% /proposition %}}

Referenced: [Simplicial homotopy group](#fec6281b-1b84-40e6-9328-202c44139152), [Degree](#216ea2fe-ad83-476e-9fd8-4d687c1049c9), [Exact Puppe sequence](#1030d00f-61f3-4c92-b0e2-e1449e411dcd), [Smash product](#90750e55-bff5-474e-99e6-7a08b30f3f92).


### Homotopy lifting property {#3405114c-c1b4-4b99-8e91-b97165362e56}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 15:43]</span></span>
A map \\(p: E \to B\\) is said to have the **homotopy lifting property** with respect to \\(X\\) if for every \\(\tilde{f}\\) and \\(F\\) we have \\(\tilde{F}\\) making the following diagram commutes.

{{< figure src="/img/2021-10-07_15-44-54_screenshot.png" >}}

Referenced: [Fibration](#7a557249-6a76-40ae-9e38-231b828a22e9).


### Hurewicz theorem {#ead0481e-e574-4458-863e-26d30b5ba7aa}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-26 Sun 15:54]</span></span>
The **Hurewicz theorem** relates the [Homotopy](#4badc09a-e75b-4851-bc77-90d46eea46fd) theory and [Homology](#c521a510-803a-40bb-9f2b-5e24bdf9a699) theory. We first fix generator satisfying the compatibility conditions \\(i\_{n} \in \tilde{H}\_{n}(S^{n}) = H\_{n}(D^{n}, S^{n - 1}) = \tilde{H}\_{n - 1}(S^{n - 1})\\). Then we can define **Hurewicz map**
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

Referenced: [Whitehead theorem](#b02aba25-72ab-46c8-8b63-f13919980fea).


### Künneth formula {#bf2b57da-b412-4014-9d62-6ec3f8bfc7f7}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-26 Sun 21:14]</span></span>
The algebraic version of **Künneth formula** is

{{% theorem %}}
Let \\(C\_{\bullet}\\) and \\(D\_{\bullet}\\) be chain complex of free abelian groups. Then there is a split exact sequence
\\[0 \to (H\_{\bullet}( C) \otimes H\_{\bullet}(D))\_{n} \to H\_{n}(C\_{\bullet} \otimes D\_{\bullet}) \to \Tor(H\_{\bullet}( C), H\_{\bullet}(D))\_{n - 1} \to 0\\]
Here \\(\Tor(H\_{\bullet}, H\_{\bullet}(D))\_{k} = \oplus\_{p + q = k} \Tor(H\_{p}( C), H\_{q}(D))\\).
{{% /theorem %}}

Apply the algebraic version to the [Singular homology](#bd775417-5818-4811-9aa6-e3819b0e3fd1), we have

{{% theorem %}}
For any topological spaces \\(X, Y\\) and \\(n \geq 0\\), there is a split exact sequence
\\[0 \to \oplus\_{p + q = n} H\_{p}(X) \otimes H\_{q}(X) \to H\_{n}(X \times Y) \to \oplus\_{p + q = n - 1} \Tor(H\_{p}(X), H\_{q}(Y)) \to 0\\]
{{% /theorem %}}


### Lefschetz fixed point theorem {#a8f5a758-c8fc-4a7f-af5c-37191d0ebdb3}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-27 Mon 20:33]</span></span>
The [Poincaré duality](#6aa27439-616e-4396-860c-d815999dfd79) gives the **intersection pairing**
\\[\langle -, - \rangle : H\_{i}(X) \times H\_{n - i}(X) \to H\_{0}(X) \cong \mathbb{Z}\\]
or equivalently
\\[\langle -, - \rangle : H^{i}(X) \times H^{n - i}(X) \to H^{n}(X) \cong \mathbb{Z}\\]

Cf. [Intersection forms](#efde6529-9adb-401a-9a36-24b35eb28839).

By consider the intersection of the diagonal \\(\Delta\\) and the graph of the map \\(f\\), we get the fixed points of \\(f\\). We define the **Lefschetz number** of \\(f\\) by
\\[L(f) := \sum\_{p}(-1)^{p} \tr(f\_{\* }: H\_{p}(X; \QQ) \to H\_{p}(X; \QQ))\\]
Then we have **Lefschetz fixed point theorem**

{{% theorem %}}
When \\(\Gamma\_{f}\\) and \\(\Delta\\) intersections transversely, then we have
\\[\abs{ {\rm Fix}(f)} = L(f)\\]
{{% /theorem %}}


### <span class="org-todo todo TODO">TODO</span> Lifting {#76602510-3721-461d-9c18-80fcf062e5a9}



The following theorem states when a map can be lifted to its [Covering](#e5f94645-231a-4765-8cdd-6d6c89a58f6a) space.

{{% theorem %}}
Let \\(p: E \to B\\) be a covering. Consider a continuous map \\(f: X \to B\\), where \\(X\\) is path connected and locally path connected. Let \\(e\_{0} \in E\\), \\(x\_{0} \in X\\) such that \\(f(x\_{0}) = p(e\_{0})\\). Then there exists a lift \\(F\\) of \\(f\\) with \\(F(x\_{0}) = e\_{0}\\) if and only if
\\[f\_{\* }(\pi\_{1}(X, x\_{0})) \subset \pi\_{\* }(\pi\_{1}(E, e\_{0}))\\]
{{% /theorem %}}

Cf. [Path connected](#be3b8eef-420f-47dc-af50-005ce1bb2161).


### Local homology group {#d72fb6c4-7adf-4742-85d8-bbc041072bd5}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-31 Tue 17:57]</span></span>
Let \\(h\_{\* }(-)\\) be a homology theory and \\(M\\) an \\(n\\)-dimensional [Manifold](#6ff3f589-8a3d-4903-b35a-fe10657823f2). Then groups of the form \\(h\_{k}(M, M \backslash x)\\) are called **local homology group**.

By excision theorem, we have that \\(h\_{k}(M, M \backslash x)\\) is \\(h\_{k}(D^{n}, D^{n} \backslash x)\\). For [Singular homology](#bd775417-5818-4811-9aa6-e3819b0e3fd1) theory, we have \\(H\_{n}(M, M \backslash x; G) \cong G\\) and other homology groups are all \\(0\\).

For \\(K \subset L \subset M\\), we have homomorphism \\(r\_{K}^{L}: h\_{k}(M, M \backslash L) \to h\_{k}(M, M \backslash K)\\).

Referenced: [Orientation](#0d1fefb5-7409-4540-8afb-5b3c67e90acd), [Fundamental class](#b4d8db93-4571-4034-a37d-bc5ebea10fea).


### Local trivial {#999af1ba-af36-4a0b-9304-320d70f5eaa9}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 15:13]</span></span>
See [Fibre bundle](#55a957a4-1fc2-4c8c-825d-6627b6d22e93).

Referenced: [Covering](#e5f94645-231a-4765-8cdd-6d6c89a58f6a).


### Loop space {#23e5a4e6-5031-4076-aee6-2f811b53a2d5}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 21:17]</span></span>
Given \\((X, x\_{0}) \in \cat{CGWH\* }\\), we define the **based loop space** \\(\Omega\_{x\_{0}}X\\) or simply \\(\Omega X\\) by
\\[\Omega X = {\rm Map}\_{\* }(S^{1}, X)\\]
And we define the **free loop space**
\\[\mathscr{L}X = {\rm Map}(S^{1}, X)\\]

Cf. [Category CGWH](#6fcf0c23-fe3f-4fde-80a3-6c6e6c4591c5).

Referenced: [Arc space](#b6fc8f15-2dd7-4586-9659-532694b2f2d3).


### Mapping cylinder {#2afb5a3e-daef-4379-bfe3-1b34d231c2f5}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-09 Sat 15:06]</span></span>
For \\(f: A \to X\\), we define the **mapping cyclinder** \\(M\_{f}\\) by the pushout of \\(A \times \\{0\\} \to A \times I\\) and \\(A \times \\{0\\} \to X \times \\{0\\}\\).

For based space, let \\(f:(X, x\_{0}) \to (Y, y\_{0}) \in \cat{CGWH\*}\\). We define its **mapping cylinder** by
\\[M\_{\*f} = M\_{f}/ \\{x\_{0} \times I\\}\\]


### Mayer-Vietoris sequence {#557c64a5-48f3-4076-814f-7bae7d157188}



There are **Mayer-Vietoris sequence** for homology and [Cohomology](#a918cddf-cd03-4546-a2cd-ce897e10cf82) theory. For \\((A; A\_{0}, A\_{1}) \subset (X; X\_{0}, X\_{1})\\) be excisive triads that is \\(A = A\_{0}^{\circ} \cap A\_{1}^{\circ}\\) and \\(X = X\_{0}^{\circ} \cap X\_{1}^{\circ}\\). Set \\(X\_{01} = X\_{0} \cap X\_{1}\\) and \\(A\_{01} = A\_{0} \cap A\_{1}\\). Then we have exact sequence
\\[\cdots \to h^{n - 1}(X\_{01}, A\_{01}) \to h^{n}(X, A) \to h^{n}(X\_{0}, A\_{0}) \oplus h^{n}(X\_{1}, A\_{1}) \to h^{n}(X\_{01}, A\_{01}) \to \cdots\\]

Referenced: [Cohomology](#a918cddf-cd03-4546-a2cd-ce897e10cf82), [Compactly supported cohomology](#699bcfec-40ae-4831-8f1e-8dd6009f5c76), [Excision theorem](#4dc11ed0-fefd-4a5e-8bb2-13228dcc76ac).


### n-connected {#6be27a99-14e3-44f6-841b-623c45da5223}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:36]</span></span>
A pair \\((X, A)\\) is called **n-connected** if \\(\pi\_{0}(A) \to \pi\_{0}(X)\\) is surjective and
\\[\pi\_{k}(X, A; x\_{0}) = 0 \\; \forall 1 \leq k \leq n, x\_{0} \in A\\]

Let \\(X\\) be obtained from \\(A\\) by attaching \\(n\\)-cells \\((n \geq 1)\\), then \\((X, A)\\) is \\((n - 1)\\)-connected.

Referenced: [Homotopy excision theorem](#5b378933-4009-4560-9b6c-181bbfae4a3c).


### Neighborhood deformation retract {#6a287f14-edd1-48fb-835e-e012dcac9b77}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:02]</span></span>
Let \\(A\\) be a subspace of \\(X\\). \\(A\\) is called a **neighborhood deformation retract** if there exists a continuous map \\(u: X \to I\\) with \\(A = u^{-1}(0)\\) and a homotopy \\(H: X \times I \to X\\) such that

\begin{equation}   \begin{cases}     H(x, 0) = x & \forall x \in X \\\\     H(a, t) = a & \text{if } (a, t) \in A \times I \\\\     H(x, 1) \in A & \text{if } u(x) < 1   \end{cases} \end{equation}

If \\(A\\) is a NDR of \\(X\\), then \\(A\\) is a strong [Deformation retract](#312dfaaf-4372-4d58-b8dd-01d42aee7662) of the open subset \\(u^{-1}(\rinterval{0}{1})\\).


### n-equivalence {#f7343d34-95fe-4206-90b1-40dcaa83cbab}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:38]</span></span>
A map \\(f: X \to Y\\) is called an **n-equivalence** if for any \\(x\_{0} \in X\\) we have \\(f\_{\* }: \pi\_{r}(X,x\_{0}) \to \pi\_{r}(Y, f(x\_{0}))\\) bijective for \\(r < n\\) and \\(f\_{\* }: \pi\_{n}(X, x\_{0}) \to \pi\_{n}(Y, f(x\_{0}))\\) is surjective.

Referenced: [Weak homotopy equivalence](#3d692166-e320-45a7-b311-785db83d13a4).


### Numerable {#6bd2d7e0-0dee-4ee3-ab4e-c390c13e143e}



{{% definition %}}
An open covering is called **numerable** if it admits a subordinate partition of unity.
{{% /definition %}}

Partition of unity is one of the important properties of the covering which deserves its own definition.

{{% definition %}}
A vector bundle (locally trivial bundle) \\(\xi: E(\xi) \to B\\) is called **numerable** if there exists a numerable covering on which the vector bundle is trivial.
{{% /definition %}}

Cf. [Vector bundle](#3944a5f8-1a1f-4cd2-82a0-d373c52e8bcf)

Referenced: [Riemannian metric](#8d4fbb99-6c1f-4044-b8c1-cd819ca319c4), [Classifying Space](#6de51423-5039-4d35-938e-881ef5b1a5ee), [Vector bundle](#3944a5f8-1a1f-4cd2-82a0-d373c52e8bcf).


### <span class="org-todo todo TODO">TODO</span> Path connected {#be3b8eef-420f-47dc-af50-005ce1bb2161}



Referenced: [Covering](#e5f94645-231a-4765-8cdd-6d6c89a58f6a), [Deck transformation](#da862591-d0f4-4f8d-a906-b38f482daf5a), [Homotopy fiber](#8faa91f0-3bd9-4e63-b241-f22da0c6450e), [Lifting](#76602510-3721-461d-9c18-80fcf062e5a9), [Seifert-Van Kampen theorem](#22a5ec7c-c651-4698-8825-d13578a874c2), [Universal covering](#42558a60-2e3d-4d09-9b7a-31517f753318).


### Path space {#9d893849-d55f-4c9a-8dfe-80a2d03fdfd6}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 21:25]</span></span>
Given \\(X \in \cat{CGWH}\\) and \\(x \in X\\), we define the **free path space** \\(PX = {\rm Map}(I, X)\\) and **based path space** \\(P\_{x}X = {\rm Map}((I, 0), (X, x))\\).

For \\(f: X \to Y\\), and \\(p\_{1}:PY \to Y\\), we define the **mapping path space** \\(P\_{f}\\) by the pull-back \\(PY \times\_{Y} X\\).


### Poincaré duality {#6aa27439-616e-4396-860c-d815999dfd79}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-27 Mon 20:21]</span></span>
The Poincaré duality is the following famous theorem.

{{% theorem %}}
Given \\(X\\) an oriented \\(n\\)-manifold. Then for any \\(p\\)
\\[D: H\_{c}^{p}(X) \to H\_{n - p}(X)\\]
is an isomorphism. In particular, if \\(X\\) is compact, then \\(H^{p}(X) \cong H\_{n - p}(X)\\). The isomorphism is given by cap product with the fundamental class of \\(X\\).
{{% /theorem %}}

Cf. [Orientation](#0d1fefb5-7409-4540-8afb-5b3c67e90acd), [Manifold](#6ff3f589-8a3d-4903-b35a-fe10657823f2), [Compactly supported cohomology](#699bcfec-40ae-4831-8f1e-8dd6009f5c76), [Singular homology](#bd775417-5818-4811-9aa6-e3819b0e3fd1), [Fundamental class](#b4d8db93-4571-4034-a37d-bc5ebea10fea).

Referenced: [Lefschetz fixed point theorem](#a8f5a758-c8fc-4a7f-af5c-37191d0ebdb3).


### Poincaré-Hopf thereom {#3fffc275-36f0-47b6-90b8-a763a8098ae0}



{{% theorem %}}
\\(\chi(X) = e(TX) [X] = \sum\_{i = 0}^{\dim X}(-1)^{i}b\_{i}(X)\\), here \\(b\_{i}(X)\\) is the ith betti number.
{{% /theorem %}}

Cf. [Euler class](#6c02fdc1-d947-45e7-b613-a5c7108163fc), [Vector bundle](#3944a5f8-1a1f-4cd2-82a0-d373c52e8bcf).


### Pontryagin class {#3adc046c-671b-4a0b-813e-3cdc5d09df29}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-22 Wed 20:46]</span></span>
The **Pontryagin class** is defined as \\(P\_{i}(E) = (-1)^{i}c\_{2i}(E \otimes\_{\RR} \CC)\\), where \\(c\_{i}\\) is the [Chern class](#eb44905d-a0cb-44e0-ae41-7555ca7a984b).

Referenced: [Characteristic class for 4-manifold](#3f183207-72d8-4c9c-bd6d-1a95da5037f7).


### <span class="org-todo todo TODO">TODO</span> Postnikov tower {#62eae029-0609-4e19-aca1-c6222aba5739}


### <span class="org-todo todo TODO">TODO</span> Properly discontinuous {#b8b322d4-aa85-444d-a157-deee448da647}



Referenced: [G-principal covering](#8172c6e1-8747-4190-a6d8-89754b7d32db).


### Reduced cohomology {#5d5cf65e-1ff4-48da-9f2a-87928aee347b}



The **reduced cohomology groups** are defined to be \\(\tilde{h}^{n}(X) \to \coker(h^{n}(pt) \to h^{n}(X))\\) where the map is induced by \\(p: X \to pt\\).

Cf. [Cohomology](#a918cddf-cd03-4546-a2cd-ce897e10cf82).


### <span class="org-todo todo TODO">TODO</span> Relative CW complex {#4e18da69-ebed-4d26-ad89-685ccb47a041}



Referenced: [Cellular approxiamtion theorem](#386832bb-33f7-4d94-a019-8cb1a4fd7507), [Homotopy excision theorem](#5b378933-4009-4560-9b6c-181bbfae4a3c).


### <span class="org-todo todo TODO">TODO</span> Relative homotopy group {#680b3c6b-712f-42ec-a85c-81efdee23607}


### Retraction {#a383ee4e-3190-4791-8587-0901a021c46b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:01]</span></span>
Let \\(i: A \subset X\\) be an inclusion. A continuous map \\(r: X \to A\\) is called a **retraction** if \\(r \circ i = 1\_{A}\\). \\(r\\) is called a **deformation retraction** if furthermore we have a homotopy \\(i  \circ r \cong 1\_{X} \text{ rel } A\\).

Referenced: [Deformation retract](#312dfaaf-4372-4d58-b8dd-01d42aee7662).


### Seifert-Van Kampen theorem {#22a5ec7c-c651-4698-8825-d13578a874c2}



{{% theorem %}}
Let \\(X = U \cap V\\) where \\(U, V \subset X\\) are open. Then the following diagram

{{< figure src="/img/2021-10-07_16-50-43_screenshot.png" >}}

is a pushout in the category \\(\cat{Groupoid}\\).
{{% /theorem %}}

Cf. [Groupoid](#f0f4db1c-a8a6-41ae-809f-d4c93ddfba33), [Fundamental groupoid](#0e9e2de9-6240-4faf-a6fd-12251e178293).

{{% theorem %}}
Let \\(X = U \cap V\\) where \\(U, V \subset X\\) are open and \\(U, V, U \cap V\\) are path connected. Let \\(x\_{0} \in U \cap V\\). Then the following diagram

![](/img/2021-10-07_16-52-14_screenshot.png)
is a pushout in the category \\(\cat{Group}\\).
{{% /theorem %}}

Cf. [Path connected](#be3b8eef-420f-47dc-af50-005ce1bb2161), [Fundamental group](#f2693b59-6cae-4cb7-85c4-d09e21ffe625).


### Semi-locally simply connected {#1bac04f0-4749-49b2-8fe9-9948fb8daedb}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:21]</span></span>
A space is **semi-locally simply connected** if for any \\(x\_{0} \in X\\), there is a neighborhood \\(U\_{0}\\) such that the image of the map \\(i\_{\* }: \pi\_{1}(U\_{0}, x\_{0}) \to \pi\_{1}(X, x\_{0})\\) is trivial.

Cf. [Simply connected](#c0bd5827-fb15-45c3-802b-d5919c73bc9e), [Fundamental group](#f2693b59-6cae-4cb7-85c4-d09e21ffe625).

Referenced: [Covering](#e5f94645-231a-4765-8cdd-6d6c89a58f6a), [Universal covering](#42558a60-2e3d-4d09-9b7a-31517f753318).


### <span class="org-todo todo TODO">TODO</span> Simply connected {#c0bd5827-fb15-45c3-802b-d5919c73bc9e}



Referenced: [Semi-locally simply connected](#1bac04f0-4749-49b2-8fe9-9948fb8daedb), [Universal covering](#42558a60-2e3d-4d09-9b7a-31517f753318).


### Smash product {#90750e55-bff5-474e-99e6-7a08b30f3f92}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:43]</span></span>
We define the **smash product** \\(\wedge\\) by \\(X \wedge Y = X \times Y / X \vee Y\\).

Cf. [Wedge product](#386bb0a4-1593-4b22-ab86-a67fa2a49ec0).

{{% exam %}}
\\[S^{1} \wedge S^{n} \cong S^{n + 1}\\]
{{% /exam %}}

The above example will be used in the computation of [Homotopy group](#492ddb93-4c8a-434e-9757-14fdbd6102f1) of \\(S^{n}\\).

Referenced: [Cone](#b80cbfba-b771-44e9-97d8-e9e4efc0572b), [Suspension](#fd1ebb6e-9c0a-42fb-9883-8f4bdb98c9d8).


### Standard n-simplex {#a69d168f-a9c9-40d1-a5e5-cd594854534c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-12 Tue 16:03]</span></span>
We denote the **standard n-simplex** by \\(\Delta^{n} = \\{(t\_{0}, \cdots, t\_{n}) \in \RR^{n + 1} \mid \sum\_{i = 0}^{n} t\_{i} = 1, t\_{i} \geq 0\\}\\).

Referenced: [Singular homology](#bd775417-5818-4811-9aa6-e3819b0e3fd1).


### Stiefel-Whitney class {#d61db36f-39bd-4cb5-b041-4815fda86269}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-22 Wed 20:44]</span></span>
For \\(p: E \to X\\) real [Vector bundle](#3944a5f8-1a1f-4cd2-82a0-d373c52e8bcf), we want to find sections linear independent. And we define the **Stiefel-Whitney class** \\(w\_{\* }(E)\\) as the obstruction in \\(H^{\* }(X; \ZZ/2)\\). It is universal for characteristic class in \\(\ZZ/2\\) coeffecients.

Referenced: [Orientation](#0d1fefb5-7409-4540-8afb-5b3c67e90acd), [Characteristic class for 4-manifold](#3f183207-72d8-4c9c-bd6d-1a95da5037f7), [Spin^C structure](#14bb7bc5-aa5d-479e-a420-b1ab6ac0d3d1).


### Suspension {#fd1ebb6e-9c0a-42fb-9883-8f4bdb98c9d8}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 21:20]</span></span>
We define the **suspension** of the space \\(X\\) by \\(\Sigma X = X \wedge S^{1}\\).

Cf. [Smash product](#90750e55-bff5-474e-99e6-7a08b30f3f92).

Referenced: [Reduced homology](#faed95ba-4829-4d21-ba6e-5ee8bf024fe4).


### <span class="org-todo todo TODO">TODO</span> Transport functor {#d4fc9972-5b70-4164-a74f-41285fd411fe}


### Trvialization {#f078be8d-cd6a-40f8-a374-8c2de3f34e0e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 15:12]</span></span>
See [Fibre bundle](#55a957a4-1fc2-4c8c-825d-6627b6d22e93).


### Universal coefficient theorem {#bc5bdfdc-48ec-4498-bfd0-9e8170cad2a9}

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


### Universal covering {#42558a60-2e3d-4d09-9b7a-31517f753318}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:19]</span></span>
A **universal covering** is a [Covering](#e5f94645-231a-4765-8cdd-6d6c89a58f6a) which is [Simply connected](#c0bd5827-fb15-45c3-802b-d5919c73bc9e).

{{% theorem %}}
If \\(B\\) is path connected, locally path connected, and semi-locally simply connected. Then \\(B\\) admits a universal covering.
{{% /theorem %}}

Cf. [Path connected](#be3b8eef-420f-47dc-af50-005ce1bb2161), [Semi-locally simply connected](#1bac04f0-4749-49b2-8fe9-9948fb8daedb).


### Vector bundle {#3944a5f8-1a1f-4cd2-82a0-d373c52e8bcf}



{{% definition %}}
The **Whitney sum** of two vector bundle \\(\xi: E(\xi) \to B\\) and \\(\eta: E(\eta) \to B\\) is \\(d^{\* }(\xi \times \eta) = \xi \oplus \eta\\), where \\(d: B \to B \times B\\) is the diagonal map. A bundle \\(\eta\\) is called an **inverse** of \\(\xi\\), if \\(\xi \oplus \eta\\) is isomorphic to a trivial bundle.
{{% /definition %}}

{{% theorem %}}
A numerable vector bundle has a **Riemann metric**.
{{% /theorem %}}

Cf. [Numerable](#6bd2d7e0-0dee-4ee3-ab4e-c390c13e143e)

{{% theorem %}}
A bundle has an inverse if and only if it is numerable of finite type.
{{% /theorem %}}

The real vector bundles and complex vector bundles have monoid structure and can be transformed into [Grothendieck ring](#622ba48f-46a3-4ae0-95f4-ee3573dbeec7) denoted by \\(KO(X)\\) and \\(K(X) = KU(X)\\).

Referenced: [Connection](#025c9171-e761-4861-bf05-42aa59e9b55b), [Covariant derivative](#61bd9c3b-fd42-4907-bead-7bf2577f4700), [Holonomy group](#0f96248f-1f95-4b9f-b811-812dcc8c54eb), [Normal bundle](#b6623fd3-ef1b-4871-9296-3846fdb9d03a), [Tangent bundle](#832cf3a2-8811-475c-a05e-25dee0ef6a02), [Bott periodicity](#82a32385-860c-488f-9cd4-d3f01433df28), [Chern class](#eb44905d-a0cb-44e0-ae41-7555ca7a984b), [Complex line bundle over CP^1](#69ec163b-f29c-49d5-b69b-8b1989a7feee), [Euler class](#6c02fdc1-d947-45e7-b613-a5c7108163fc), [Fibre bundle](#55a957a4-1fc2-4c8c-825d-6627b6d22e93), [Numerable](#6bd2d7e0-0dee-4ee3-ab4e-c390c13e143e), [Poincaré-Hopf thereom](#3fffc275-36f0-47b6-90b8-a763a8098ae0), [Stiefel-Whitney class](#d61db36f-39bd-4cb5-b041-4815fda86269), [Elliptic fibration](#0ecad10b-236b-4627-a5f7-29a27a1ccf90).


### Weak Hausdorff {#9f13cd1d-b101-4005-a7d3-f5480736e62c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 15:48]</span></span>
A space \\(X\\) is **weak Hausdorff** if for every compact Hausdorff \\(K\\) and every continuous map \\(f:K \to X\\), the image \\(f(K)\\) is closed in \\(X\\). We denote the full subcategory of weak Hausdorff space by \\(\cat{WH}\\).

Referenced: [Category CGWH](#6fcf0c23-fe3f-4fde-80a3-6c6e6c4591c5).


### Weak homotopy equivalence {#3d692166-e320-45a7-b311-785db83d13a4}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:41]</span></span>
\\(f\\) is called **weak homotopy equivalence** if \\(f\\) is [n-equivalence](#f7343d34-95fe-4206-90b1-40dcaa83cbab) for any \\(n \geq 0\\).

Referenced: [Weak equivalence](#dcf4ac56-1504-4a63-a707-8319f629fc10), [CW approximation](#6f12de59-ad55-49fa-a51d-bf2ff07d1139), [Whitehead theorem](#b02aba25-72ab-46c8-8b63-f13919980fea).


### Wedge product {#386bb0a4-1593-4b22-ab86-a67fa2a49ec0}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-07 Thu 16:42]</span></span>
We define the **wedge product** \\(\vee\\) by \\(X \vee Y = X \coprod Y / \sim\\), where \\(\sim\\) identifies \\(x\_{0} \in X\\) and \\(y\_{0} \in Y\\).

Referenced: [Smash product](#90750e55-bff5-474e-99e6-7a08b30f3f92).


### Well-pointed {#1395975d-4bd9-4305-a803-a248abce490e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-11 Mon 20:15]</span></span>
A based space \\((X,x\_{0})\\) is called **well-pointed**, if the inclusion of the base point \\(x\_{0} \in X\\) is a [Cofibration](#793240f6-9551-465f-b749-34e6e8fd7eb3) in the unbased sense.


### Whitehead theorem {#b02aba25-72ab-46c8-8b63-f13919980fea}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-26 Sun 16:14]</span></span>
The **Whitehead theorem** means that [Weak homotopy equivalence](#3d692166-e320-45a7-b311-785db83d13a4) is equivalent to homotopy equivalence for [CW complexes](#31b773f8-25a9-4943-9ebf-5f8f5df31fad).

{{% theorem %}}
A map between CW complexes is a weak homotopy equivalence if and only if it is a homotopy equivalence.
{{% /theorem %}}

By [Hurewicz theorem](#ead0481e-e574-4458-863e-26d30b5ba7aa), the Whitehead theorem also has an [Homology](#c521a510-803a-40bb-9f2b-5e24bdf9a699) version.

{{% theorem %}}
Let \\(f: X \to Y\\) between simply connected CW complexes. Assume
\\[f\_{\* }: H\_{n}(X) \to H\_{n}(Y)\\]
is an isomorphism for each \\(n\\). Then \\(f\\) is a homotopy equivalence.
{{% /theorem %}}


### <span class="org-todo todo TODO">TODO</span> Whitehead tower {#6a6b946f-cf3a-4f5f-8025-46f7f820d412}


## Algebraic Geometry {#588b0321-5a8f-4710-a67a-2a34de657fde}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-23 Mon 19:50]</span></span>
There are two tastes of algebraic geometry. The algebraic geometers view it as a specialized geometry, which is closed related to complex geometry (by GAGA), birational geometry (MMP for example), symplectic geometry (Gromov-Witten invariants) etc. Algebraic geometers are mainly interested in case where the base field is \\(\CC\\). Experts in other field may view algebraic geometry as useful languages, where vast properties are worked out by algebraic geometers. Therefore, Grothendieck's style of algebraic geometry provides many insights into number theory, representation theory etc. In both case, the characteristic \\(p\\) case is more interesting. Examples includes [Steinberg variety](#6f0885bd-5fc9-4287-ab31-560a5be9365e), p-adic Hodge theory.

The following are the themes in Algebraic Geometry Salt Lake 2015 seminar <https://sites.google.com/site/2015summerinstitute/home/schedule> : analytic methods, birational geometry and classification, commutative algebra and computational algebraic geometry, Hodge theory, singularities and characteristic p methods, derived algebraic geometry, derived categories, geometric representation theory, Gromov-Witten and Donaldson-Thomas theories, mirror symmetry, tropical geometry, algebraic cycles, cohomology theories, p-adic Hodge theory, rational points and Diophantine problems, topology of algebraic varieties


### 2-Yoneda lemma {#4b7957f4-a63f-4732-b5be-d6fd81e505aa}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-27 Mon 20:15]</span></span>
The **2-Yoneda lemma** is Yoneda lemma for 2-morphisms.

{{% lemma %}}
Let \\(\mathfrak{X}\\) be a prestack over a category \\(\mathfrak{S}\\) and \\(S \in \mathfrak{S}\\). The functor
\\[\cat{Mor}(S, \mathfrak{X}) \to \mathfrak{X}(S), f \to f\_{S}(\id\_{S})\\]
is an equivalence of categories, here we view \\(S\\) as presheaf \\(\Hom(-, S)\\).
{{% /lemma %}}

Cf. [Prestack](#f368a933-d735-415d-b8f1-3b980077ea40).


### <span class="org-todo todo TODO">TODO</span> Affine derived scheme {#2e1a90a6-054c-4c51-88da-5eb7bf07e4f8}


### Affine grassmannian {#ddff7416-2bf3-4e82-8304-47adff72751b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:31]</span></span>
Let \\(G\\) affine linear [Algebraic group](#e2cb9181-d20c-47cd-9f3b-757f9ad14ce1). We define the functor
\\[{\rm Gr}\_{G}( R) = G(R((t)))/G(R[|t|])\\]
called **affine grassmannian**. We write \\(\mathcal{O} = k[|t|]\\) and \\(K = k((t))\\).

Cf. [Loop space](#06844816-a0dd-4e1e-940f-f8aca636a2be), [Arc space](#b6fc8f15-2dd7-4586-9659-532694b2f2d3).

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


### Affine toric variety {#fad44b6c-ee19-49dc-90e7-3f83dbb75678}



{{% definition %}}
An **affine toric variety** is an irreducible affine variety \\(V\\) containing a [Torus](#14c0a895-04a6-4976-bce3-2b511741dc32) \\(T\_{N} \cong (\CC^{\* })^{n}\\) as a Zariski open subset such that the action of \\(T\_{N}\\) on itself extends to an action on \\(V\\).
{{% /definition %}}

There are several ways of constructing toric varieties. First, consider a finite subset \\(\mathscr{A} = \\{\chi^{1}, \cdots, \chi^{l}\\} \subset \ZZ^{n}\\) a lattice equivalent to the character of a torus \\((\CC^{\* })^{n}\\). Then we may consider a map \\(\Phi\_{\mathscr{A}}(t) = (\chi^{1}(t), \cdots, \chi^{l}(t)), T\_{N} \to \CC^{s}\\). The Zariski closure of the image is a toric variety denoted by \\(Y\_{\mathscr{A}}\\). The ideal of the affine toric variety is a [Toric ideal](#89e4ed03-df8b-4ee4-b4e9-86e036a0d301). Detailed construction can see [<span id="56219725c40008d847a57904e2a7e775"><a href="#CLS2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">CLS2011</a></span>] p.14-15.

Another construction concerns [Affine semigroup](#ca294346-6eb1-45fc-b49f-4a01691e96ab). given a affine semigroup \\(S\\), we have \\(\CC[S] = \\{\sum\_{m \in S} c\_{m} \chi^{m} \mid c\_{m} \in \CC \text{ and } c\_{m} = 0 \text{ for all but finitely many } m\\}\\), where \\(\chi^{m}\\) is dependent on the embedding into the lattice \\(M\\). The multiplication is induced by \\(\chi^{m} \cdot \chi^{m'} = \chi^{m + m'}\\). We have

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

We consider the relation between sublattice variety and original variety. ([<span id="56219725c40008d847a57904e2a7e775"><a href="#CLS2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">CLS2011</a></span>] Proposition 1.3.18) For \\(N'\\) have finite index in \\(N\\) a sublattice and quotient \\(G = N/N'\\) and \\(\sigma \subset N\_{\RR}' = N\_{\RR}\\) be a [Strongly convex](#c3e2c96e-0eaf-4319-99ac-ffbc5ba9f62a) [Rational](#ac77486a-35da-4294-b711-eba0eab4533e) [Polyhedral cone](#1dfb8b9c-7a4a-4c23-bf4d-9665c421e19f). Then we have

1.  There are natural isomorphisms
    \\[G \cong \Hom\_{\ZZ}(M'/M, \CC^{\* }) = \ker(T\_{N'} \to T\_{N})\\]
2.  \\(G\\) acts on \\(\CC[\sigma^{\vee} \cap M']\\) and
    \\[\CC[\sigma^{\vee} \cap M']^{G} = \CC[\sigma^{\vee} \cap M]\\]
3.  We have bijection
    \\[U\_{\sigma, N'}/G \cong U\_{\sigma, N}\\]

That is the original variety is [Geometric quotient](#8a47cf27-cc4a-416d-977f-39fa7b17e1dd) of the sublattice varieties.

Referenced: [Toric](#90007b48-ef9b-474d-a2ac-6f3f4a2447b0), [Face](#ecf9eadb-edb2-48f3-b9b9-500dece9c422), [Pointed](#5c3f014a-571f-47a0-a97e-11c210848309), [Saturated](#8566ada4-b025-4f91-a38b-1b2b7583ab80), [Toric variety](#13b3e41c-f513-4c38-90ea-5063fde975cc).


### Algebraic group {#e2cb9181-d20c-47cd-9f3b-757f9ad14ce1}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-07 Tue 20:45]</span></span>
An **algebraic group** \\(G\\) over a field \\(k\\) is a [Group scheme](#5199da7e-9a89-43b9-a3ab-9869c4d7c38f) \\(G/k\\) which is separated and smooth.

Referenced: [Representation category](#5bdd1646-d8d5-4499-8388-62ddc3fcddfb), [Affine grassmannian](#ddff7416-2bf3-4e82-8304-47adff72751b), [Radical](#6777b23e-4eb6-42dd-a26e-5ee83515f2fe), [Unipotent](#cb3c198c-a24a-44c7-9ef1-f15653f95904), [Unipotent radical](#7a8f6fd8-d2e5-4a1e-828d-a2af7f8d8e52), [Semisimple](#24acba18-48f4-4682-b522-a869c6cb8a0b), [Reductive](#3c91fa04-29df-4ad0-8995-447a5fb86da1), [Parabolic](#b363d8f7-d558-40db-a889-4b92c13a2e88), [Isogeny](#35538f98-babe-4fc7-82a3-81a3964c035a), [Langlands dual pair](#dcdc572d-35c5-425b-8436-99595ee16acb).


#### Radical {#6777b23e-4eb6-42dd-a26e-5ee83515f2fe}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 08:52]</span></span>
[<span id="868cb56e509be613430cca58b1ead9f3"><a href="#milne2017" title="Milne, Algebraic {{Groups}}: {{The Theory}} of {{Group Schemes}} of {{Finite Type}} over a {{Field}}, {Cambridge University Press} (2017).">milne2017</a></span>] p.135

Let \\(G\\) be a connected [Algebraic group](#e2cb9181-d20c-47cd-9f3b-757f9ad14ce1) over \\(k\\). \\(G\\) contains a largest connected solvable normal subgroup called the **radical**, \\(R(G)\\) of \\(G\\).

Referenced: [Unipotent radical](#7a8f6fd8-d2e5-4a1e-828d-a2af7f8d8e52), [Semisimple](#24acba18-48f4-4682-b522-a869c6cb8a0b).


#### Unipotent {#cb3c198c-a24a-44c7-9ef1-f15653f95904}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 09:01]</span></span>
[<span id="868cb56e509be613430cca58b1ead9f3"><a href="#milne2017" title="Milne, Algebraic {{Groups}}: {{The Theory}} of {{Group Schemes}} of {{Finite Type}} over a {{Field}}, {Cambridge University Press} (2017).">milne2017</a></span>] p.135

An [Algebraic group](#e2cb9181-d20c-47cd-9f3b-757f9ad14ce1) \\(G\\) is said to be **unipotent** if every nonzero representation of \\(G\\) has a nonzero fixed point. Or equivalently speaking, every finite-dimensional representation \\(r: G \to \GL\_{V}\\) there is a basis such that \\(r(G) \subset \U\_{n}\\).


#### Unipotent radical {#7a8f6fd8-d2e5-4a1e-828d-a2af7f8d8e52}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 09:01]</span></span>
[<span id="868cb56e509be613430cca58b1ead9f3"><a href="#milne2017" title="Milne, Algebraic {{Groups}}: {{The Theory}} of {{Group Schemes}} of {{Finite Type}} over a {{Field}}, {Cambridge University Press} (2017).">milne2017</a></span>] p.135

The **unipotent radical** of \\(G\\) is the largest connected normal unipotent sub-[Algebraic group](#e2cb9181-d20c-47cd-9f3b-757f9ad14ce1) of \\(G\\), denoted by \\(R\_{u}(G)\\).

Cf. [Radical](#6777b23e-4eb6-42dd-a26e-5ee83515f2fe).

Referenced: [Reductive](#3c91fa04-29df-4ad0-8995-447a5fb86da1).


#### Semisimple {#24acba18-48f4-4682-b522-a869c6cb8a0b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 08:50]</span></span>
[<span id="868cb56e509be613430cca58b1ead9f3"><a href="#milne2017" title="Milne, Algebraic {{Groups}}: {{The Theory}} of {{Group Schemes}} of {{Finite Type}} over a {{Field}}, {Cambridge University Press} (2017).">milne2017</a></span>] p.135

An [Algebraic group](#e2cb9181-d20c-47cd-9f3b-757f9ad14ce1) is called **semisimple** if \\(R(G\_{k^{a}})\\) is trivial, where \\(k^{a}\\) is the algebraic closure of \\(k\\).

Cf. [Radical.](#6777b23e-4eb6-42dd-a26e-5ee83515f2fe)


#### Reductive {#3c91fa04-29df-4ad0-8995-447a5fb86da1}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 08:49]</span></span>
[<span id="868cb56e509be613430cca58b1ead9f3"><a href="#milne2017" title="Milne, Algebraic {{Groups}}: {{The Theory}} of {{Group Schemes}} of {{Finite Type}} over a {{Field}}, {Cambridge University Press} (2017).">milne2017</a></span>] p.135

An [Algebraic group](#e2cb9181-d20c-47cd-9f3b-757f9ad14ce1) is called **reductive** if \\(R\_{u}(G\_{k^{a}})\\) is trivial, where \\(k^{a}\\) is the algebraic closure of \\(k\\).

Cf. [Unipotent radical](#7a8f6fd8-d2e5-4a1e-828d-a2af7f8d8e52).

Referenced: [Positive root](#11c3ad25-a0cc-4433-a680-2c241f8a9910).


#### Parabolic {#b363d8f7-d558-40db-a889-4b92c13a2e88}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:50]</span></span>
A smooth subgroup \\(P \subset G\\) is **parabolic** if \\(G/P\\) complete as algebraic variety.

{{% proposition %}}
For \\(k\\) algebraic closed, a smooth connected algebraic group \\(B \subset G\\) is minimal among parabolics \\(P\\) is equivalent to \\(B\\) solvable parabolic.
{{% /proposition %}}

Cf. [Algebraic group](#e2cb9181-d20c-47cd-9f3b-757f9ad14ce1).

Referenced: [Borel](#73ee6f1c-93e3-49cf-9401-eaf7af130e1f).


#### Borel {#73ee6f1c-93e3-49cf-9401-eaf7af130e1f}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:51]</span></span>
A algebraic subgroup \\(B\\) is called **Borel** if it is [Parabolic](#b363d8f7-d558-40db-a889-4b92c13a2e88), smooth, connected and solvable.

Referenced: [Positive root](#11c3ad25-a0cc-4433-a680-2c241f8a9910).


### Algebraic space {#e881dc3c-0ab3-461b-b4eb-ff7a84203779}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 20:35]</span></span>
An **algebraic space** is a [Sheaf](#32e43dc9-af7b-46a9-a114-1d5f42a5f95d) \\(X\\) on \\(\cat{Sch}\_{Ét}\\) such that there exist a scheme \\(U\\) and a surjective [Étale](#ed41498b-430c-485c-b0d3-1f26d531902a) morphism \\(U \to X\\) representable by schemes. The morphism \\(U \to X\\) is called an **étale presentation**.

{{% proposition %}}
Let \\(P\\) be one of the following property of morphisms of algebraic spaces: open immersion, closed immersion, locally closed immersion, affine, or quasi-affine. Consider the cartesian diagram

{{< figure src="/img/2021-12-29_20-03-12_screenshot.png" >}}

such that \\(Y' \to Y\\) is surjective, flat and locally of finite presentation. Then \\(X \to Y\\) has \\(P\\) if and only if \\(X' \to Y'\\) has \\(P\\).
{{% /proposition %}}

For more properties, see [Algebraic stack](#bb5b2734-6496-44c1-a515-c956d5277467).


### Algebraic stack {#bb5b2734-6496-44c1-a515-c956d5277467}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 20:38]</span></span>
An **algebraic stack** is a [Stack](#7fcf9705-95fa-4c83-8514-af8b15b1d50d) \\(X\\) over \\(\cat{Sch}\_{Ét}\\) such that there exist a scheme \\(U\\) and a surjective, smooth and [Representable](#fa11fd46-28b4-4155-b142-529c85b659c3) morphism \\(U \to X\\). The morphism is called **smooth presentation**.

A typical example of algebraic stack is the **quotient stack**, denoted by \\([X/G]\\), whose object over \\(S\\) are diagrams

![](/img/2021-12-26_20-40-29_screenshot.png)
where \\(P \to S\\) is a \\(G\\)-[Torsor](#4cf947bf-dc13-487c-8694-d31a12c3f96e) and \\(f: P \to X\\) \\(G\\)-equivaraint. And morphism between objects the following diagram

{{< figure src="/img/2021-12-26_20-40-58_screenshot.png" >}}

The map \\(X \to [X/G]\\) is a \\(G\\)-torsor even when the action is not free.

{{% remark %}}
The flatness, smoothness, surjectivity, locally of finite presentation, locally of finite type are smooth-local and étaleness is étale-local. So all can be defined for Deligne-Mumford stacks but latter can not be defined for algebraic stacks.
{{% /remark %}}

We define the topological space of the algebraic stack \\(\abs{X}\\) as set consisting of field-value moprhisms \\(x: \spec K \to X\\). Two morphism \\(x\_{1}: \spec X\_{1} \to X\\) and \\(x\_{2}: \spec K\_{2} \to X\\) if there exists field extension \\(K\_{3}/K\_{1}\\) and \\(K\_{3}/K\_{2}\\) such that \\(x\_{1}|\_{\spec K\_{3}}\\) and \\(x\_{2}|\_{\spec K\_{3}}\\) are isomorphic in \\(X(K\_{3})\\). A subset \\(V\\) is open if there exists open immersion \\(U \ito X\\) such that \\(V\\) is the image of \\(\abs{U} \to \abs{X}\\).

We say that an algebraic stack is **quasi-compact**, **connected**, or **irreducible** if \\(\abs{X}\\) is.

A point \\(x \in \abs{X}\\) is of **finite type** if there exists a representative \\(\spec K \to X\\) of finite type.

Let \\(R \to U\\) be a smooth [Groupoid of schemes](#566bd6c2-8369-4b55-8bc3-6700b9f8fc36). Define \\([U/R]^{pre}\\) to be the prestack whose objects are morphism \\(T \to U\\) from a scheme \\(T\\). A morphism \\((S \xrightarrow{a} U) \to (T \xrightarrow{b} U)\\) is the data of a morphism of schemes \\(f: S \to T\\) and an element \\(r \in R(S)\\) such that \\(s( r) = a\\) and \\(t( r) = f \circ b\\). Define \\([U/R]\\) to be the stackification of \\([U/R]^{pre}\\).

{{% theorem %}}
Let \\(R \to U\\) be an étale (resp. smooth) groupoid of schemes. Then \\([U/R]\\) is a Deligne-Mumford stack (resp. algebraic stack) and \\(U \to [U/R]\\) is an étale (resp. smooth) presentation.
{{% /theorem %}}

{{% theorem %}}
The diagonal of an algebraic space is representable by schemes.

The diagonal of an algebraic stack is representable.
{{% /theorem %}}

{{% corollary %}}
Any morphism from a scheme to an algebraic space is representable by schemes.

Any morphism from a scheme to an algebraic stack is representable.
{{% /corollary %}}

{{% corollary %}}
If \\(R \to U\\) be an étale equivalence relation of schemes, then \\(U/R\\) is an algebraic space and \\(U \to U/R\\) is an étale morphism.
{{% /corollary %}}

{{% definition %}}
1.  A morphism of algebraic stack \\(X \to Y\\) is **quasi-separated** if \\(X \to X \times\_{Y} X\\) is quasi-compact.
2.  A representable morphism \\(X \to Y\\) of algebraic stacks is **separated** if the morphism \\(X \to X \times\_{Y} X\\) is representable by schemes and proper.
3.  An algebraic stack \\(X\\) is **quasi-separated** if it is quasi-separated over \\(\spec \ZZ\\).
4.  An algebraic stack \\(X\\) is **noetherian** if it is locally noetherian, quasi-compact and quasi-separated.
{{% /definition %}}

Let \\(X\\) be a noetherian algebraic space and \\(x \in \abs{X}\\). We define the **dimension** of \\(X\\) at \\(x\\) to be
\\[\dim\_{x} X = \dim\_{u} U \in \mathbb{Z}\_{\geq 0} \cup \infty\\]
where \\(U \to X\\) is any étale presentation and \\(u \in U\\) is an preimage.

Let \\(X\\) be an algebraic stack with smooth presentation \\(U \to X\\) and corresponding smooth groupoid \\(s, t: R \to U\\), and let \\(u \in U\\) be a preimage of \\(x \in \abs{X}\\). We define the **dimension** of \\(X\\) at \\(x\\) to be
\\[\dim\_{x} X = \dim\_{u} U - \dim\_{e(u)} R\_{u} \in \ZZ \cup \infty\\]
where \\(R\_{u}\\) is the fiber of \\(s: R \to U\\) over \\(u\\) and \\(e: U \to R\\) denotes the identity morphism in the groupoid.

If \\(X\\) is a noetherian algebraic space or stack, we define the **dimension** of \\(X\\) to be
\\[\dim X = \sup \dim\_{x} X \in \ZZ \cup \infty\\]

If \\(X\\) is an algebraic stack and \\(x: \spec k \to X\\), we define the **Zariski tangent space** or simply the **tangent space** of \\(X\\) at \\(x\\) as the set
\\[T\_{X,x} = \\{f:\spec k[\epsilon] \to X, \alpha: x \cong f|\_{spec k}\\}/ \sim\\]
where two pairs are equivalent if there is an isomorphism between them.

{{% proposition %}}
If \\(X\\) is an algebraic stack with affine diagonal and \\(x \in X(k)\\), then \\(T\_{X,x}\\) is naturally a \\(k\\)-vector space.
{{% /proposition %}}


### Arc space {#b6fc8f15-2dd7-4586-9659-532694b2f2d3}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:26]</span></span>
We define the **arc space** to be functor \\(Y[|t|]\\) such that \\(Y[|t|\]\( R) = Y(R[|t|])\\).

Cf. [Loop space](#23e5a4e6-5031-4076-aee6-2f811b53a2d5).

{{% proposition %}}
Arc spaces and \\(Y[k[t]/t^{n}]\\) are schemes. Moreover, if \\(Y\\) is affine then they are also affine.
{{% /proposition %}}

Referenced: [Affine grassmannian](#ddff7416-2bf3-4e82-8304-47adff72751b), [Loop space](#06844816-a0dd-4e1e-940f-f8aca636a2be).


### Auslander-Buchsbaum formula {#d8cf7a10-3c77-4d14-b144-94f18a7b8108}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:32]</span></span>
Let \\(A\\) be a regular ring, then we have
\\[\dimh(M) + \depth(M) = \dim (A)\\]
Cf. [Homological dimension](#e76fb0a8-5966-4d84-b5ae-105a5f031a3a), [Depth](#85bd6a8b-f480-47f2-8873-f3f39578df09).


### Calabi-Yau variety {#6f8f1b66-9779-4ca4-95d7-7768aaecd600}



Referenced: [Donaldson-Thomas theory](#d99e0505-469d-469f-b47f-8fb5e04f57b7), [Kähler manifold with holomorphic symplectic structure](#c261fae8-e011-484c-907f-98cb4ae3ab3d).


### Castelnuovo theorem {#984f29be-77c1-4a79-9407-4dc72c0e9329}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:32]</span></span>
The **Castelnuovo theorem** classified the mimimal surfaces.

{{% theorem %}}
Two birational [minimal models](#9b74b17c-1c2b-476c-a978-1cea023cc08e) are isomorphic unless they are both birational to a ruled surface \\(C \times \CC P^{1}\\).
{{% /theorem %}}


### Categorical quotient {#d459451a-9e61-4e92-b806-aff2159fec95}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-07 Tue 20:59]</span></span>
Given an action \\(\sigma\\) of \\(G/S\\) on \\(X/S\\), a pair \\((Y, \phi: X \to Y)\\)  is called a **categorical quotient** if we have diagram

![](/img/2021-09-07_21-01-38_screenshot.png)
commutes and universal property that for any \\((Z, \psi)\\) satisfying the above diagram, there exists a unique morphism \\(\chi: Y \to Z\\) such that \\(\psi = \chi \circ \phi\\).

A categorical quotient is called **universal** if it is stable under base change, and is called **uniform** if it is stable under flat base change.

Referenced: [Geometric quotient](#8a47cf27-cc4a-416d-977f-39fa7b17e1dd).


### Category of modules {#bd4d822f-e06f-422b-b64f-343e6782e57b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-07 Sun 15:21]</span></span>
Let \\(T\\) be a [Topos](#7ee906fc-4e21-4965-a082-1e0ee87235c7) and let \\(\Lambda\\) be a ring in \\(T\\). Denote by \\(\cat{Mod}\_{\Lambda}\\) the category of \\(\Lambda\\)-modules in \\(T\\).

{{% theorem %}}
The category \\(\cat{Mod}\_{\Lambda}\\) is an abelian category with enough injectives.
{{% /theorem %}}

Then we have functor
\\[\Gamma(T, -): \cat{Mod}\_{\Lambda} \to \cat{Ab}\\]
obtained by
\\[F \to \Hom\_{\cat{Mod}\_{\Lambda}}(\Lambda, F)\\]
This is a left exact functor, and we denote the resulting right derived functor by \\(H^{i}(T, -)\\), called **cohomology functor**.

Cf. [Cohomology](#a918cddf-cd03-4546-a2cd-ce897e10cf82).


### Character (of a torus) {#13bc02d5-1271-497c-ad8f-20f52be7d055}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 19:50]</span></span>
A **character** of a [Torus](#14c0a895-04a6-4976-bce3-2b511741dc32) is a group homomorphism \\(\chi: T \to \CC^{\* }\\).


### <span class="org-todo todo TODO">TODO</span> Coarse moduli space {#325a41f1-edc5-4d0f-bb0a-3eacfb75e8d1}


### <span class="org-todo todo TODO">TODO</span> Cohen strcuture theorem {#f8e0b92b-e100-46d6-a89e-4a6243f6bcfe}



{{% corollary %}}
Let \\(X\\) be a locally Noetherian scheme over a field \\(k\\), having dimension \\(n\\) at a smooth point \\(x\\). Then \\(\hat{\OO}\_{X,x} \cong k(x)[ [x\_{1}, \cdots, x\_{n}]]\\).
{{% /corollary %}}


### Deformation functor {#6c6901f3-261c-4f7a-bdfc-6fdfe9aa38ad}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-19 Sun 20:24]</span></span>
A [Predeformation functor](#5bf09bb7-02f0-4ebe-86aa-588c2ac3354c) is called a **deformation functor** if it satisfies (1-2) in [Schlessinger's theorem](#5a2b53ea-6a6d-43eb-b668-9125f5023c91).


### Deligne-Mumford stack {#30e38a6a-1476-4c73-967f-cb882e9d96e8}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 20:33]</span></span>
A **Deligne-Mumford stack** is a stack \\(X\\) over \\(\cat{Sch}\_{Ét}\\) such that there exist a scheme \\(U\\) and a surjective, [Étale](#ed41498b-430c-485c-b0d3-1f26d531902a) and [Representable](#fa11fd46-28b4-4155-b142-529c85b659c3) morphism \\(U \to X\\). The morphism is also called **étale presentation**.

For properties, see [Algebraic stack](#bb5b2734-6496-44c1-a515-c956d5277467).

Cf. [Algebraic space](#e881dc3c-0ab3-461b-b4eb-ff7a84203779).


### Depth {#85bd6a8b-f480-47f2-8873-f3f39578df09}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:34]</span></span>
The maximal length of an \\(M\\)-[Regular sequence](#e8f31b9d-3f74-4d2c-b31a-86d78466e799) is called the **depth** of \\(M\\).

Referenced: [Auslander-Buchsbaum formula](#d8cf7a10-3c77-4d14-b144-94f18a7b8108).


### <span class="org-todo todo TODO">TODO</span> Derived stack {#f0b7b2b1-d2ca-4786-a70d-77061acc5359}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:06]</span></span>
Examples: Betti stack, de Rham stack


### Determinant bundle {#1671ae72-7024-4b27-a327-265d8cca4b5e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:50]</span></span>
If \\(E\\) is locally free of rank \\(s\\), then the **determinant bundle** \\(\det(E)\\) is by definition the line bundle \\(\wedge^{s}(E)\\). Let \\(E\\) be arbitrary coherent sheaf. Then we consider a finite locally free resolution
\\[0 \to E\_{n} \to \cdots \to E\_{0} \to E \to 0\\]
And define \\(\det(E) = \otimes \det(E\_{i})^{(-1)^{i}}\\).

If \\(\dim(E) \leq \dim(X) - 2\\), then we have that \\(\det(E) \cong \OO\_{X}\\).


### Different characters may give same toric variety {#e8b5dda6-cdc6-4cb9-8fcb-1d5c5927cdb9}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:26]</span></span>
Exercise 1.1.6 in [<span id="56219725c40008d847a57904e2a7e775"><a href="#CLS2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">CLS2011</a></span>]. We consider two map
\\[\Phi\_{1}(s,t) = (s^{2}, st, st^{3}), \quad \Phi\_{2}(s,t) = (s^{3}, st, t^{3})\\]
We can show that \\(\Phi\_{1}\\) and \\(\Phi\_{2}\\) gives same affine toric variety. However \\(\Phi\_{2}\\) is surjective and \\(\Phi\_{1}\\) is not.


### Donaldson-Thomas theory {#d99e0505-469d-469f-b47f-8fb5e04f57b7}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-29 Sun 16:00]</span></span>
Cf. [Enumerative geometry](#78708dd9-a024-437b-9908-1f62672a4a77).

We consider the case when \\({\rm dim}\_{\CC}(X) = 3\\). We fix a class \\(\beta \in H\_{2}(X, \ZZ)\\) and fix an integer \\(\chi \in \ZZ\\). The **Donaldson-Thomas theory** describes the intersection theory on [Hilbert scheme](#e1fd15af-27a1-4320-b02b-fd567b184b24) of \\(X\\). Due to existence of nonvanishing higher \\({\rm Ext}\\) group, the deformation-obstruction theory and [Virtual fundamental class](#7d52eb53-34d5-4da6-80f4-7242956a1c44) of virtual fundamental class is not well-defined. To remedy the issue, we consider \\(I\_{\chi}(X, \beta)\\) parametrizing pairs \\((E, \phi)\\) such that

-   \\(E\\) is a torsion free sheaf on \\(X\\) of rank \\(1\\).
-   \\(E\\) is equipped with a trivialization \\(\phi: \det E \cong \mathbb{O}\_{X}\\).
-   The numerical invariants of \\(E\\) is given by \\(c\_{2}(E) = - \beta\\), \\(\xi(E) = \xi(\mathbb{O}\_{X}) - \chi\\).

The natural map
\\[{\rm Hilb}\_{\chi}(X, \beta) \to I\_{\chi}(X, \beta)\\]
\\[Z \to J\_{Z}\\]
is an isomorphism on the level of closed points.

The expected dimension is given by \\(\dim(\Ext\_{0}^{1}(E, E)) - \dim(\Ext\_{0}^{2}(E,E))\\), where \\(\Ext\_{0}\\) denote the trace free subspace. So we have that \\(\virdim I\_{\chi}(X, \beta) = \chi(E, E) - \chi(\OO) = -K\_{X} \cdot \beta\\). In [Gromov-Witten theory](#0fafdc7b-a6b5-4143-b239-810531e0623f), we also have the fundamental class of dimension equal to \\(-K\_{X} \cdot \beta\\). So if \\(X\\) is [Calabi-Yau variety](#6f8f1b66-9779-4ca4-95d7-7768aaecd600), we have \\(\virdim I\_{\chi}(X, \beta) = 0\\).

We don't have evaluation map in Donaldson-Thomas theory, so we consider
\\[\tilde{J} \to \hilb(X) \times X\\]
for the purpose of integration. Given \\(\alpha \in H^{\*}(X)\\), we can define an operator
\\[\sigma\_{0}(\alpha): \pi\_{\hilb \*}(- \ch\_{2}(\tilde{J}) \cup \pi\_{X}^{\*}(\alpha) \cap \pi\_{\hilb}^{\*}(-)), H\_{\*}(\hilb(X)) \to H\_{\*}(\hilb(X))\\]
Then the **Donaldson-Thomas invariants** are defined by

\begin{align}\langle \alpha\_{1}, \cdots, \alpha\_{n} \rangle^{DT}\_{\beta, m} &= \deg \prod\_{k} \sigma\_{0}(\alpha\_{k})[I\_{\chi}(X, \beta)]^{vir} \\\\  &= \int\_{ [I\_{\chi}(X, \beta)]^{vir}} \prod\_{k} \sigma\_{0}(\alpha\_{k}) \\\\  &= \int\_{ [I\_{\chi}(X, \beta)]^{vir}} \prod\_{k} \pi\_{\hilb \*}(- \ch\_{2}(\tilde{J}) \cup \pi\_{X}^{\*}(\alpha\_{k}) \cap \pi^{\*} \beta)\end{align}

Here note \\(-\ch\_{2}(I\_{Z}) = \beta\\) is represented by cycle class \\(Z \subset X\\).

There may be some mistakes in definition, because I suppose that the second line is not well-defined and the \\(\beta\\) in the last line is unnatural. However, I don't know the correct algebraic definition of Donaldson-Thomas theory yet. So I still follow the definition in [GW/DT Theory](https://www.bilibili.com/video/BV1Gi4y1T7ed) Lecture 11.


### Dual sheaf {#47e13ac2-f80a-44aa-8b25-d79bdacd0600}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:39]</span></span>
Let \\(E\\) be a coherent sheaf of codimension \\(c\\). The **dual sheaf** is defined as \\(E^{D} = \sext^{c}\_{X} (E, \omega\_{X})\\).

Referenced: [Reflexive](#15449aca-6239-4e92-a379-cb76a4cf492b).


### Enumerative geometry {#78708dd9-a024-437b-9908-1f62672a4a77}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-31 Tue 08:52]</span></span>
There are several aspects of enumerative geometry, beyond the numbers.

-   counting curves and sheaves (Gromov-Witten theory, Donaldson-Thomas and related theories)
-   gauge theory enumerative geometry (3d gauge theories and Coulomb branches, mirror symmetry, 4d gauge theories, and Vafa-Witten invariants, etc)
-   applications of enumerative geometry to categorification and low-dimensional topology
-   Hall algebras and their refined versions (cohomological, K-theoretic, derived categories)
-   Enumerative geometry of Nakajima quiver variety and the representation of quantum groups (symplectic resolution, etc)

Referenced: [Donaldson-Thomas theory](#d99e0505-469d-469f-b47f-8fb5e04f57b7), [Gromov-Witten theory](#0fafdc7b-a6b5-4143-b239-810531e0623f).


### Étale site {#d95143d5-1124-4c8a-b7d9-9bc2ab630418}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 21:30]</span></span>
See [Site](#d827cad0-92be-4251-9e34-4243334a9315).

:ID:       e75a7770-d111-4f5e-9fb0-72a34c894b6e

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 21:32]</span></span>
See [Site](#d827cad0-92be-4251-9e34-4243334a9315).


### <span class="org-todo todo TODO">TODO</span> Exact sequence about extensions {#fd29dfd5-9364-403d-aacc-2abaf68c1652}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 21:29]</span></span>
See [<span id="7cd3e01b28c2ede526fee96d60981f02"><a href="#sernesi2006" title="Sernesi, Deformations of {{Algebraic Schemes}}, {Springer Berlin Heidelberg} (2006).">sernesi2006</a></span>] Proposition 1.1.5, Proposition 1.1.7, and Corollary 1.1.8.

{{% remark %}}
The proof in my mind is straightforward but a little tricky when manipulate the objects, since sometimes we need to consider the \\(R\\)-module structure and sometimes as \\(A\\)-algebra.
{{% /remark %}}

Referenced: [Extension](#e074be48-ee62-4fa6-b0bc-3de8fcc9a492).


### Ex\_A(R,I) {#4659315c-4d65-419c-93ed-e7577b6bcb13}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 21:15]</span></span>
See [<span id="7cd3e01b28c2ede526fee96d60981f02"><a href="#sernesi2006" title="Sernesi, Deformations of {{Algebraic Schemes}}, {Springer Berlin Heidelberg} (2006).">sernesi2006</a></span>] p.12.

We now consider all isomorphism class of \\(A\\)-[Extensions](#e074be48-ee62-4fa6-b0bc-3de8fcc9a492) of \\(R\\) by \\(I\\), called \\(\ex\_{A}(R,I)\\). We want to show that \\(\ex\_{A}(R, I)\\) is an \\(R\\)-module. We first construct the **pullback** and **pushout** for extensions. We define the pullback, denoted by \\(f^{\* }(R', \phi)\\) by following diagram:

![](/img/2021-09-15_21-22-39_screenshot.png)
And define the pushout by the other, denoted by \\(\lambda\_{\*}(R', \phi)\\):

![](/img/2021-09-15_21-23-05_screenshot.png)
Where
\\[R' \coprod\_{I} J = \frac{R' \tilde{\oplus} J}{\\{(- \alpha(i), \lambda(i)), i \in I\\}}\\]

Now we are ready to define the \\(R\\)-module structure on \\(\ex\_{A}(R, I)\\). If \\(r \in R\\), we define \\(r[R', \phi] = [r\_{\* }(R', \phi)]\\) where \\(r: I \to I\\) is multiplication by \\(r\\). And for some, we consider \\(R' \times\_{R} R''\\) as the extension of \\(R\\) by \\(I \oplus I\\). And consider the pushout of the function \\(\delta: I \oplus I \to I\\), such that \\(\delta(i \oplus j) = i + j\\).

By above construction, \\(\ex\_{A}(R, -)\\) is a covariant functor from \\(R\\)-modules to \\(R\\)-modules.

Referenced: [Extension](#e074be48-ee62-4fa6-b0bc-3de8fcc9a492), [First cotangent module](#4c8d7294-6449-4d50-92eb-00e9fc8d1f8c).


### Extension {#e074be48-ee62-4fa6-b0bc-3de8fcc9a492}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 20:28]</span></span>
See [<span id="7cd3e01b28c2ede526fee96d60981f02"><a href="#sernesi2006" title="Sernesi, Deformations of {{Algebraic Schemes}}, {Springer Berlin Heidelberg} (2006).">sernesi2006</a></span>] p.9.

Let \\(A \to R\\) be a ring homomorphism. An \\(A\\)-**extension** of \\(R\\) by \\(I\\) is an exact sequence
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

The extension of algebras can be extended to extension of schemes. An **extension** of \\(X/S\\) is a closed immersion \\(X \subset X'\\), where \\(X'\\) is an \\(S\\)-scheme, defined by a sheaf of ideals \\(\mathscr{I} \subset \mathscr{O}\_{X'}\\) such that \\(\mathscr{I}^{2} = 0\\). The **isomorphism**, **homomorphism**, **triviality**, and \\(\ex(X/S, \mathscr{I})\\) is similar to the algebra case. For details, see [<span id="7cd3e01b28c2ede526fee96d60981f02"><a href="#sernesi2006" title="Sernesi, Deformations of {{Algebraic Schemes}}, {Springer Berlin Heidelberg} (2006).">sernesi2006</a></span>] p.15. (Cf. [Ex\_A(R,I)](#4659315c-4d65-419c-93ed-e7577b6bcb13) and [Exact sequence about extensions](#fd29dfd5-9364-403d-aacc-2abaf68c1652))

In particular, we have following theorem relating the deformation to the \\(\Ext\\) groups.

{{% theorem %}}
Let \\(X \to S\\) be a morphism of finite type of schemes and \\(\mathscr{I}\\) a coherent locally free sheaf on \\(X\\). Suppose that \\(X\\) reduced and \\(S\\)-smooth on a dense open subset. Then there is a cononical equivalence
\\[\ex(X/S, \mathscr{I}) = \Ext^{1}\_{\mathscr{O}\_{X}}(\Omega\_{X/S}^{1}, \mathscr{I})\\]
which maps the extension
\\[\mathscr{E}: 0 \to \mathscr{I} \to \OO\_{X'} \to \OO\_{X} \to 0\\]
to
\\[c\_{\mathscr{E}}: 0 \to \mathscr{I} \to (\Omega^{1}\_{X'/S})|\_{X} \to \Omega^{1}\_{X/S} \to 0\\]
{{% /theorem %}}

Referenced: [Ex\_A(R,I)](#4659315c-4d65-419c-93ed-e7577b6bcb13), [Versal extension](#744a4c24-3412-4043-ba95-b20a711eff25).


### Fiber category {#bba822be-d871-4f9b-a9d9-ecd971dba9ba}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 20:09]</span></span>
Given a [Prestack](#f368a933-d735-415d-b8f1-3b980077ea40) \\(\mathfrak{X}\\), the **fiber category** \\(\mathfrak{X}(S)\\) is the category of objects over \\(S\\) whose morphisms are over \\(\id\_{S}\\).


### <span class="org-todo todo TODO">TODO</span> Fine moduli space {#b458a9fa-d476-49de-821a-aa86b8f151de}


### First cotangent module {#4c8d7294-6449-4d50-92eb-00e9fc8d1f8c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 21:33]</span></span>
See [<span id="7cd3e01b28c2ede526fee96d60981f02"><a href="#sernesi2006" title="Sernesi, Deformations of {{Algebraic Schemes}}, {Springer Berlin Heidelberg} (2006).">sernesi2006</a></span>] p.14.

The \\(R\\)-module \\(\ex\_{A}(R,R)\\) is called the **first cotangent module** of \\(R\\) over \\(A\\), and is denoted by \\(T\_{R/A}^{1}\\). We omit \\(A\\) if \\(A = k\\). The **first cotagent sheaf** is obtained by gluing the first cotangent modules.

Cf. [Ex\_A(R,I)](#4659315c-4d65-419c-93ed-e7577b6bcb13).


### Flat {#54a4ffc3-66e4-41c5-9363-7257b47949ee}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-19 Sun 20:23]</span></span>
A \\(R\\)-module \\(M\\) is called **flat** if tensoring with \\(M\\) is an exact functor.


### Fppf site {#352dde73-f559-4539-8881-0c7919e48e8e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 21:32]</span></span>
See [Site](#d827cad0-92be-4251-9e34-4243334a9315).


### Framed moduli space {#db778f90-fd0b-4436-87b4-d64ab769b8af}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-19 Sun 19:28]</span></span>
See [<span id="24e67c8afe5163064e4018cb5a5cbd8a"><a href="#nakajima1999" title="Nakajima, Lectures on {{Hilbert}} Schemes of Points on Surfaces, {American Mathematical Society} (1999).">nakajima1999</a></span>] p.17.

We define \\(\mathscr{M}(r,n)\\), the **framed moduli space** of torsion free [Sheaves](#32e43dc9-af7b-46a9-a114-1d5f42a5f95d) on \\(\PP^{2}\\) with rank (r) and \\(c\_{2} = n\\). That is the isomorphism class of pairs \\((E, \Phi)\\) on \\(\PP^{2}\\) with \\(\rk(E) = n\\) \\(c\_{2}(E) = n\\) which is locally free in a neighborhood of \\(l\_{\infty}\\) such that \\(\Phi: E|\_{l\_{\infty}} \ito \mathscr{O}\_{l\_{\infty}}^{\oplus r}\\). The latter isomorphism is called **framing at infinity**.

We have following simple characterization of framed moduli space.

{{% theorem %}}
There exists a bijection between \\(\mathscr{M}(r,n)\\) and pairs \\((B\_{1}, B\_{2}, i, j)\\) such that \\([B\_{1}, B\_{2}] + ij = 0\\), and stability condition there exists no proper subspace \\(S \subsetneq \CC^{n}\\) such that \\(B\_{\alpha}(S) \subset S\\) and \\(\im i \subset S\\) modulo the action of \\(\GL\_{n}(\CC)\\). Here \\(B\_{1}, B\_{2} \in \End(\CC^{n})\\), \\(i \in \Hom(\CC^{r}, \CC^{n})\\) and \\(j \in \Hom(\CC^{n}, \CC^{r})\\) with the action
\\[g \cdot (B\_{1}, B\_{2}, i, j) = (gB\_{1}g^{-1}, gB\_{2}g^{-1}, gi, jg^{-1})\\]
{{% /theorem %}}

Cf. [Hilb(A^2,n)](#13561c7b-a9cf-4058-b768-4cadf7b405e6).

There is a interesting lemma with basic techniques in linear algebra.

{{% lemma %}}
When \\(r = 1\\) and \\(B\_{1}, B\_{2}, i, j\\) same as above theorem, for \\(ij + [B\_{1}, B\_{2}] = 0\\), we have that \\(ji = 0\\).
{{% /lemma %}}

See [<span id="24e67c8afe5163064e4018cb5a5cbd8a"><a href="#nakajima1999" title="Nakajima, Lectures on {{Hilbert}} Schemes of Points on Surfaces, {American Mathematical Society} (1999).">nakajima1999</a></span>] p.26. We have \\(S^{n}(\CC^{2}) \cong \\{(B\_{1}, B\_{2}, i, j) \mid [B\_{1}, B\_{2}] + i j = 0\\} // \GL\_{n}(\CC)\\), where \\(//\\) denote the algebro-geometric quotient.

Cf. [Geometric quotient](#8a47cf27-cc4a-416d-977f-39fa7b17e1dd).


### Generalized Serre's condition {#8d9ee983-c938-49fe-a392-2c73652a3925}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:37]</span></span>
We define the **generalized Serre's condition** \\(S\_{k,c}\\) as
\\[\depth(E\_{x} \geq \min \\{k, \dim(\OO\_{X,x}) - c\\}) \text{ for all } x \in \supp(E)\\]


### Geometric quotient {#8a47cf27-cc4a-416d-977f-39fa7b17e1dd}



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

The geometric quotient is related to [Categorical quotient](#d459451a-9e61-4e92-b806-aff2159fec95) by the following proposition.

{{% proposition %}}
Given an action \\(\sigma\\) of \\(G/S\\) over \\(X/S\\), and \\((Y, \phi)\\) is a geometric quotient. Then \\((Y, \phi)\\) is also a categorical quotient and hence unique. If \\((Y, \phi)\\) is the universal geometric quotient, then it is also a universal categorical quotient.
{{% /proposition %}}

Referenced: [Affine toric variety](#fad44b6c-ee19-49dc-90e7-3f83dbb75678), [Framed moduli space](#db778f90-fd0b-4436-87b4-d64ab769b8af).


### Gromov-Witten theory {#0fafdc7b-a6b5-4143-b239-810531e0623f}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 19:53]</span></span>
Cf. [Enumerative geometry](#78708dd9-a024-437b-9908-1f62672a4a77).

We have natural maps for [Moduli space of Stable Maps](#cee41211-6bef-4bb0-b5d7-52d6d0cab804)

{{< figure src="/img/2021-08-25_20-25-36_screenshot.png" >}}

And we have **Gromov-Witten class**
\\[I\_{g,n,\beta}(\alpha\_{1}, \alpha\_{2}, \cdots, \alpha\_{n}) = \pi\_{2!} (\pi\_{1}^{\* }(\alpha\_{1} \otimes \cdots \otimes \alpha\_{n}))\\]
Also we have **Gromov-Witten invariant**
\\[\langle I\_{g,n,\beta}(\alpha\_{1}, \alpha\_{2}, \cdots, \alpha\_{n}) \rangle = \int\_{\overline{M}\_{g,n}} I\_{g,n,\beta}(\alpha\_{1}, \alpha\_{2}, \cdots, \alpha\_{n}) \\]

The Gromov-Witten invariants has natural enumerative geometric interpretation. \\(\langle I\_{g,n,\beta}(\alpha\_{1}, \cdots, \alpha\_{n}) \rangle\\) equals the number of stable curves in \\((C, p\_{1}, \cdots, p\_{n}) \in \overline{M}\_{g,n}\\) for which we can find \\(f\\) such that \\(f(p\_{i}) \in Z\_{i} = \alpha\_{i}^{\vee}\\) and \\(f\_{\*}( C) = \beta\\).

By above interpretation we have natural axioms about Gromov-Witten invariants.

Referenced: [Donaldson-Thomas theory](#d99e0505-469d-469f-b47f-8fb5e04f57b7), [Linear axiom](#42ae7c01-de7f-448c-8af3-0e06be57bc23), [Effectivity axiom](#e651f5ef-7377-433c-a67b-67ce9e0c999e), [Degree axiom](#128a2668-74e9-427c-8403-369270263bf3), [Equivariant axiom](#86007420-6a91-4d45-86f6-d89f5da7538c), [Fundamental class axiom](#be1c3263-26e5-48c7-af97-bf6af1d5e911), [Divisor axiom](#7c5c0133-9836-4ce3-94d6-d7cd618149e2), [Point mapping axiom](#ccc14e69-fe02-4b7e-808e-fc311bf7da07), [Splitting axiom](#49f706f9-95f5-4edb-a18a-2bfc50e2215a), [Reduction axiom](#202babd8-6c02-4368-8717-50a262a3a752), [Deformation axiom](#c0367284-8a38-4be3-8dff-cbbc59a2f61d), [Kontsevich recursion formula](#d5d9d292-15ed-4859-9ad2-4dc76e07c257).


#### Linear axiom {#42ae7c01-de7f-448c-8af3-0e06be57bc23}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:35]</span></span>
Cf. [Gromov-Witten theory](#0fafdc7b-a6b5-4143-b239-810531e0623f).
\\(I\_{g,n,\beta}\\) is linear in each variable.


#### Effectivity axiom {#e651f5ef-7377-433c-a67b-67ce9e0c999e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:35]</span></span>
Cf. [Gromov-Witten theory](#0fafdc7b-a6b5-4143-b239-810531e0623f).
For \\(X\\) projective, \\(I\_{g,n,\beta} = 0\\) if \\(\beta\\) is not an effective curve class.


#### Degree axiom {#128a2668-74e9-427c-8403-369270263bf3}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:36]</span></span>
Cf. [Gromov-Witten theory](#0fafdc7b-a6b5-4143-b239-810531e0623f).
For \\(\alpha\_{1}, \cdots, \alpha\_{n} \in H^{\* }(X, \mathbb{Q})^{\otimes n}\\), \\(I\_{g,n, \beta}(\alpha\_{1}, \cdots, \alpha\_{n}) \in H^{\* }(\bar{M}\_{g,n}, \mathbb{Q})\\) has degree \\(2 (g - 1) {\rm dim} X + 2 \int\_{\beta} \omega\_{X} + \sum\_{i} {\rm deg} \alpha\_{i}\\)


#### Equivariant axiom {#86007420-6a91-4d45-86f6-d89f5da7538c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:39]</span></span>
Cf. [Gromov-Witten theory](#0fafdc7b-a6b5-4143-b239-810531e0623f).
The map \\(I\_{g,n, \beta}\\) is \\(S\_{n}\\) equivariant where \\(S^{n}\\) acts on \\(H^{\* }(X, \mathbb{Q})^{\otimes n}\\) naturally and acts on \\(H^{ \* }(\overline{M}\_{g,n}), \mathbb{Q}\\) by permuting \\(p\_{i}\\)'s  of the pointed curves.


#### Fundamental class axiom {#be1c3263-26e5-48c7-af97-bf6af1d5e911}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:41]</span></span>
Cf. [Gromov-Witten theory](#0fafdc7b-a6b5-4143-b239-810531e0623f).
If \\(n + 2g \geq 4\\) then there exists a natural forgetting map
\\[\pi\_{n}: \bar{M}\_{g,n} \to \bar{M}\_{g,n - 1}\\]
if \\([X] \in H^{0}(X, \mathbb{Q})\\) fundamental cycle, then we have that
\\[I\_{g,n, \beta}(\alpha\_{1}, \cdots, \alpha\_{n - 1}, [X]) = \pi\_{n}^{\* }I\_{g,n-1, \beta}(\alpha\_{1}, \cdots, \alpha\_{n - 1})\\]


#### Divisor axiom {#7c5c0133-9836-4ce3-94d6-d7cd618149e2}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:43]</span></span>
Cf. [Gromov-Witten theory](#0fafdc7b-a6b5-4143-b239-810531e0623f).
If \\(n + 2g \geq 4\\), then \\(\pi\_{n}: \bar{M}\_{g,n} \to \bar{M}\_{g,n - 1}\\) as above, if \\(\alpha\_{n} \in H^{2}(X, \mathbb{Q})\\) then we have
\\[\pi\_{n \* } I\_{g,n, \beta}(\alpha\_{1}, \cdots, \alpha\_{n}) = (\int\_{\beta} \alpha\_{n}) \times I\_{g,n -1, \beta}(\alpha\_{1}, \cdots, \alpha\_{n-1})\\]


#### Point mapping axiom {#ccc14e69-fe02-4b7e-808e-fc311bf7da07}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:45]</span></span>
Cf. [Gromov-Witten theory](#0fafdc7b-a6b5-4143-b239-810531e0623f).
When \\(\beta = 0\\), if \\(\alpha\_{i}\\) are homogeneous cohomology classes, then
\\[I\_{0,n,0}(\alpha\_{1}, \cdots, \alpha\_{n}) = \int\_{X}(\alpha\_{1} \cup \cdots \cup \alpha\_{n})[\bar{M}\_{g,n}]\\]
if \\(\sum\_{i} {\rm deg} \alpha\_{i} = 2 {\rm dim} X\\) and is zero otherwise.


#### Splitting axiom {#49f706f9-95f5-4edb-a18a-2bfc50e2215a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:48]</span></span>
Cf. [Gromov-Witten theory](#0fafdc7b-a6b5-4143-b239-810531e0623f).
By gluing \\(2\\) points, we have natural map
\\[C: \bar{M}\_{g\_{1}, n\_{1} + 1} \times \bar{M}\_{g\_{2}, n\_{2} +1} \to \bar{M}\_{g,n}\\]
where \\(g = g\_{1} + g\_{2}\\) and \\(n = n\_{1} + n\_{2}\\). Then we have
\\[\phi^{\* }I\_{g,n, \beta} (\alpha\_{1}, \cdots, \alpha\_{n}) = \sum\_{\beta = \beta\_{1} + \beta\_{2}} \sum\_{i,j} g^{ij}I\_{g\_{1}, n\_{1} + 1, \beta}(\alpha\_{1}, \cdots, \alpha\_{n\_{1}}, T\_{i}) \otimes I\_{g\_{2}, n\_{2} +1, \beta\_{2}}(T\_{j}, \alpha\_{n\_{1}+ 1}, \cdots, \alpha\_{n})\\]
where \\(\phi\\) is the diagonal map and \\(g^{ij}\\) is the inverse matrix of \\(g\_{ij} = \int\_{X} T\_{i} \cup T\_{j}\\).


#### Reduction axiom {#202babd8-6c02-4368-8717-50a262a3a752}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:52]</span></span>
Cf. [Gromov-Witten theory](#0fafdc7b-a6b5-4143-b239-810531e0623f).
Gluing two point together, we have natural map \\(\psi: \bar{M}\_{g - 1, n + 2} \to \bar{M}\_{g, n}\\). Then we have
\\[\psi^{\* } I\_{g,n, \beta}(\alpha\_{1}, \cdots, \alpha\_{n}) = \sum\_{i,j}g^{ij}I\_{g - 1, n +2, \beta}(\alpha\_{1}, \cdots, \alpha\_{n}, T\_{i}, T\_{j})\\]


#### Deformation axiom {#c0367284-8a38-4be3-8dff-cbbc59a2f61d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-25 Wed 20:54]</span></span>
Cf. [Gromov-Witten theory](#0fafdc7b-a6b5-4143-b239-810531e0623f).
Let \\(X \to T\\) be a smooth proper amp with connected base \\(T\\). And set \\(X\_{t}\\)  is the fiber. Then for each \\(t \in T\\) and \\(\beta\_{t} \in H\_{2}(X\_{t}, \mathbb{Z})\\), we obtain a map \\(I\_{g,n, \beta\_{t}}: H^{\* }(X\_{t}, \mathbb{Q}) \to H^{\* }(M\_{g,n}, \mathbb{Q})\\). Then if \\(\beta\_{t}\\) is locally constant section of \\(H\_{2}(X\_{t}, \mathbb{Q})\\) and \\(\alpha\_{1}, \cdots, \alpha\_{n}\\) are locally constant, then we have \\(I\_{g,n, \beta\_{t}}(\alpha\_{1}, \cdots, \alpha\_{n})\\) is constant.


#### Kontsevich recursion formula {#d5d9d292-15ed-4859-9ad2-4dc76e07c257}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-26 Thu 15:23]</span></span>
Cf. [Gromov-Witten theory](#0fafdc7b-a6b5-4143-b239-810531e0623f).
For \\(X = \mathbb{P}^{2}\\), we denote that \\(N\_{d} = \langle I\_{0, 3d - 1, d}([pt], \cdots, [pt]) \rangle \\) where \\([pt]\\) occur \\(3d - 1\\) times for \\(d \geq 1\\). Then we have following **Kontsevich recursion formula**
\\[N\_{d} = \sum\_{d = d\_{1} + d\_{2}, d\_{1}, d\_{2} > 0} N\_{d\_{1}}N\_{d\_{2}} (d\_{1}^{2}d\_{2}^{2} \binom{3d - 4}{3d\_{1} - 2} - d\_{1}^{3}d\_{2} \binom{3d - 4}{3d\_{1} - 1})\\]


### Grothendieck topology {#3126cca2-f75b-46a3-aa2e-c03e375ecc4e}

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

Referenced: [Site](#d827cad0-92be-4251-9e34-4243334a9315).


### Group scheme {#5199da7e-9a89-43b9-a3ab-9869c4d7c38f}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-07 Tue 20:42]</span></span>
A **group scheme** \\(G/S\\) is a morphism \\(\pi: G \to S\\) of schemes with \\(S\\)-morphism multiplication \\(\mu: G \times\_{S} G \to G\\), inverse \\(\beta: G \to G\\) identity \\(e: S \to G\\) satisfying associativity, law of inverse and law of identity.

A group scheme \\(G\\) action on a scheme \\(X/S\\) is given by a morphism \\(\sigma: G \times\_{S} X \to X\\) with associativity property and identity.

Let \\(f: T \to X\\) be a \\(T\\)-valued point. We have morphism \\(\phi\_{f} = \sigma \circ (1\_{G} \times f): G \times\_{S} T \to X \times\_{S} T\\). The image of \\(\phi\_{f}\\) is called the **orbit** of \\(f\\) and denoted by \\(O(f)\\). The fibre product \\(S(f)\\) is called **stabilizer** of \\(f\\). The orbit and stabilizer is the algebraic version of orbit and stabilizer in action on topological spaces.

{{< figure src="/img/2021-09-07_20-58-55_screenshot.png" >}}

Referenced: [Criterion for category being representation category](#4357d757-e6bd-495c-a863-e8cef3943c0b), [Reconstruction theorem](#1e62d31f-a421-4a9a-8797-c6a4d7a2ec2a), [Algebraic group](#e2cb9181-d20c-47cd-9f3b-757f9ad14ce1).


### Groupoid of schemes {#566bd6c2-8369-4b55-8bc3-6700b9f8fc36}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-28 Tue 20:49]</span></span>
See Introduction to Stacks and Moduli p.79.


### Hilb(A^2,n) {#13561c7b-a9cf-4058-b768-4cadf7b405e6}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-16 Thu 20:35]</span></span>
See [<span id="24e67c8afe5163064e4018cb5a5cbd8a"><a href="#nakajima1999" title="Nakajima, Lectures on {{Hilbert}} Schemes of Points on Surfaces, {American Mathematical Society} (1999).">nakajima1999</a></span>], Theorem 1.9.

We have a specific characterization of \\(\hilb(A^{2}, n)\\). Let
\\[\tilde{H} = \\{(B\_{1}, B\_{2}, i) \mid [B\_{1}, B\_{2}] = 0 \text{ and stable}\\}\\]
The triple \\((B\_{1}, B\_{2}, i)\\) is called stable if there exists no proper subspace \\(S \subsetneq k^{n}\\) such that \\(B\_{\alpha}(S) \subset S\\), \\(\alpha = 0,1\\) and \\(\im i \subset S\\). \\(B\_{\alpha} \in \End(k^{n}) \\) and \\(i \in \Hom(k, k^{n})\\). We have a natural \\(\GL\_{n}\\) action on \\(\tilde{H}\\) defined by \\((B\_{1}, B\_{2}, i) \to (gB\_{1}g^{-1}, gB\_{2}g^{-1}, gi)\\). And by quotient, we define \\(H = \tilde{H}/ \GL\_{n}\\). And we have that \\(H \cong \hilb(\mathbb{A}^{2},n)\\).

Cf. [Hilbert scheme](#e1fd15af-27a1-4320-b02b-fd567b184b24).

The manifold \\(\hilb(\mathbb{A}^{2}, n)\\) admits a hyper-Kähler metric.

Referenced: [Framed moduli space](#db778f90-fd0b-4436-87b4-d64ab769b8af).


### Hilbert-Chow morphism {#ea9ca8a9-96aa-4dce-ac1e-1b338d01ec3b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-16 Thu 20:25]</span></span>
For [Hilbert scheme](#e1fd15af-27a1-4320-b02b-fd567b184b24) of points, we have a well define map
\\[\pi:X^{ [n]}\_{red} \to S^{n}X\\]
by \\(\pi(Z) = \sum\_{x \in X}l(Z\_{x})[x]\\), here \\(l\\) denote the length.

Referenced: [Smoothness of Hilbert scheme](#061ec6cf-d155-4b1b-9850-5fbcd84660f6).


### Hilbert scheme {#e1fd15af-27a1-4320-b02b-fd567b184b24}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-29 Sun 15:24]</span></span>
We fix a class \\(\beta \in H\_{2}(X, \ZZ)\\) and fix an integer \\(\chi \in \ZZ\\).

{{% definition %}}
The **Hilbert scheme** \\({\rm Hilb}\_{\chi}(X, \beta)\\) parametrizes \\(1\\) dimensional subscheme \\(Z \subset X\\) whose irreducible components are at most \\(1\\)-dimension with numerical invariants \\(\beta = [Z] \in H\_{2}(X, \ZZ)\\) and \\(\chi(\mathscr{O}\_{Z}) = \chi\\).
{{% /definition %}}

In [<span id="24e67c8afe5163064e4018cb5a5cbd8a"><a href="#nakajima1999" title="Nakajima, Lectures on {{Hilbert}} Schemes of Points on Surfaces, {American Mathematical Society} (1999).">nakajima1999</a></span>], there is another notation of Hilbert schemes, where in \\(\hilb(X, p)\\), the \\(p\\) denote the Hilbert polynomial. And we write \\(X^{ [n]}\\) for \\(\hilb(X, n)\\) for Hilbert scheme of points.

Referenced: [Donaldson-Thomas theory](#d99e0505-469d-469f-b47f-8fb5e04f57b7), [Hilb(A^2,n)](#13561c7b-a9cf-4058-b768-4cadf7b405e6), [Hilbert-Chow morphism](#ea9ca8a9-96aa-4dce-ac1e-1b338d01ec3b), [Simple resolution](#14bae490-825c-4bc0-b176-73ef6dbf0b8c), [Smoothness of Hilbert scheme](#061ec6cf-d155-4b1b-9850-5fbcd84660f6), [Symplectic structure of Hilbert scheme](#9e6166a7-590b-44da-a207-f45f189df7c0).


### Homological dimension {#e76fb0a8-5966-4d84-b5ae-105a5f031a3a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:29]</span></span>
Let \\(M\\) be a module of a local ring \\(A\\). The **homological dimension** denoted by \\(\dimh(M)\\) is defined as the minimal length of a projective resolution of \\(M\\). It is also the length of free resolution of \\(M\\).

Referenced: [Auslander-Buchsbaum formula](#d8cf7a10-3c77-4d14-b144-94f18a7b8108).


### Hull {#81b84e2c-f7ef-4c3b-a662-b7cdbfd1b043}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-19 Sun 20:23]</span></span>
Let \\(F\\) be a [Predeformation functor](#5bf09bb7-02f0-4ebe-86aa-588c2ac3354c) and \\(\hat{F}\\) its completeion. We say a pair \\((R, \eta)\\) with \\(R\\) a [Noetherian](#553a8417-9fe5-428c-ad73-8044d8af226b) [Complete](#f92f1fd0-86ef-4e15-acbc-104ebfee400a) [Local ring](#82ff8727-44bd-4118-94f5-27c7aeae8cc7), and \\(\eta \in \hat{F}( R)\\), is a **hull** for \\(F\\) if the induced map \\(\bar{h}\_{R} \to F\\) is smooth, and induces a bijection \\(T\_{\bar{h}\_{R}} \ito T\_{F}\\) on tangent spaces.

Referenced: [Schlessinger's theorem](#5a2b53ea-6a6d-43eb-b668-9125f5023c91).


### <span class="org-todo todo TODO">TODO</span> Hyper-Kähler quotient {#0dbb0133-df4f-417e-8411-be6640c58520}


### Ind-scheme {#cd7030e3-da4c-425a-90c3-ec12929939ee}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:23]</span></span>
An **ind-scheme** is object in \\(\cat{Fun}(\cat{k-algebra}, \cat{Set})\\) which can be written as
\\[X = \varinjlim\_{I} X\_{i}\\]
such that \\(I\\) is a direct diagram, \\(X\_{i}\\) is a scheme, all maps \\(X\_{i} \to X\_{j}\\) are closed embedding. We call **ind-affine**, **ind-projective**, **ind-finite type** if all \\(X\_{i}\\) are affine, projective, finite type.

Referenced: [Loop space](#06844816-a0dd-4e1e-940f-f8aca636a2be).


### Inertia stack {#054ebb10-bae4-4682-863b-5a8532648dcf}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-28 Tue 21:11]</span></span>
The **inertia stack** of an [Algebraic stack](#bb5b2734-6496-44c1-a515-c956d5277467) \\(X\\) is the fiber product

{{< figure src="/img/2021-12-29_20-03-46_screenshot.png" >}}


### Isogeny {#35538f98-babe-4fc7-82a3-81a3964c035a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:46]</span></span>
An **isogeny** is a surjective homomorphism between smooth connected [Algebraic groups](#e2cb9181-d20c-47cd-9f3b-757f9ad14ce1) \\(\phi: G \to G'\\) with finite kernel \\(K\\). The **degree** of \\(\phi\\) is given by \\(\abs{K}\\).

See also [Isogeny](#3271ffe5-7252-466c-89a4-41f7e53ec99b).

Referenced: [Degree](#216ea2fe-ad83-476e-9fd8-4d687c1049c9).


### <span class="org-todo todo TODO">TODO</span> Jacobian criterion {#e9397b77-5d8a-4089-8e35-c10a61f32798}


### <span class="org-todo todo TODO">TODO</span> K3 surfaces {#a02155e5-899f-436d-8cc6-8d32d597550f}



Referenced: [Intersection forms](#efde6529-9adb-401a-9a36-24b35eb28839).


### Kähler manifold with holomorphic symplectic structure {#c261fae8-e011-484c-907f-98cb4ae3ab3d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-16 Thu 20:50]</span></span>
See [<span id="24e67c8afe5163064e4018cb5a5cbd8a"><a href="#nakajima1999" title="Nakajima, Lectures on {{Hilbert}} Schemes of Points on Surfaces, {American Mathematical Society} (1999).">nakajima1999</a></span>], Proposition 1.19.

The following proposition may be useful.

{{% proposition %}}
Let \\(X\\) be a compact Kähler manifold which admits a holomorphic symplectic structure. Then \\(X\\) has a hyper-Kähler structure.
{{% /proposition %}}

Cf. [Calabi-Yau variety](#6f8f1b66-9779-4ca4-95d7-7768aaecd600), [Holonomy group](#0f96248f-1f95-4b9f-b811-812dcc8c54eb).


### Lattice {#f35a2d22-45cb-470e-92bf-b6601186d5f4}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:03]</span></span>
A **lattice** is a free abelian group of finite rank.

Referenced: [Lattice ideal](#bca68ca1-b16a-4519-8d04-8903e4aa8912), [Rational](#ac77486a-35da-4294-b711-eba0eab4533e), [Affine semigroup](#ca294346-6eb1-45fc-b49f-4a01691e96ab).


### Lattice ideal {#bca68ca1-b16a-4519-8d04-8903e4aa8912}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:03]</span></span>
Let \\(L \subset \ZZ^{s}\\) be a sublattice. Then we call the ideal \\(I\_{L} = \langle x^{\alpha} - x^{\beta} \mid \alpha, \beta \in \NN^{s} \text{ and } \alpha - \beta \in L \rangle\\) **lattice ideal**.

Cf. [Lattice](#f35a2d22-45cb-470e-92bf-b6601186d5f4).

Referenced: [Toric ideal](#89e4ed03-df8b-4ee4-b4e9-86e036a0d301).


### <span class="org-todo todo TODO">TODO</span> Linearly reductive {#f7b67acf-d9dc-438c-9666-2f7f71788ba5}


### Loop space {#06844816-a0dd-4e1e-940f-f8aca636a2be}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:27]</span></span>
We define the **loop space** to be functor \\(Y((t))( R) = Y(R((t)))\\).

Cf. [Arc space](#b6fc8f15-2dd7-4586-9659-532694b2f2d3).

{{% proposition %}}
The loop space is ind-scheme if \\(Y\\) is affine.
{{% /proposition %}}

Cf. [Ind-scheme](#cd7030e3-da4c-425a-90c3-ec12929939ee).

Referenced: [Affine grassmannian](#ddff7416-2bf3-4e82-8304-47adff72751b).


### <span class="org-todo todo TODO">TODO</span> Luna's slice theorem {#b701bbbd-533e-44d4-99a8-f9dd08edcd4e}


### <span class="org-todo todo TODO">TODO</span> McKay correspondence {#ce960e47-8e38-4918-8f31-11304f93b829}


### <span class="org-todo todo TODO">TODO</span> Minimal model {#9b74b17c-1c2b-476c-a978-1cea023cc08e}



Referenced: [Castelnuovo theorem](#984f29be-77c1-4a79-9407-4dc72c0e9329).


### Minuscule {#bb17f90b-69cd-43c1-a3b5-b90fadfadaab}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 14:41]</span></span>
A coweight \\(\mu\\) is **minuscule** if
\\[\langle \alpha, \mu \rangle \leq 1\\]
for all \\(\alpha\\) positive. For minuscule \\(\mu\\), we have \\({\rm Gr}\_{\mu} = \overline{{\rm Gr}\_{\mu}} = G/P\_{\mu}\\), where \\(P\_{\mu}\\) is a partial flag.


### <span class="org-todo todo TODO">TODO</span> Moduli space of curves {#dd0e811c-1a3d-4a51-8434-e8ed0c1b41c9}



Referenced: [Canonical line bundle](#52fa2b27-e4ed-47b1-aaab-d89b2139e8f8).


#### Canonical line bundle {#52fa2b27-e4ed-47b1-aaab-d89b2139e8f8}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 19:47]</span></span>
Cf. [Moduli space of curves](#dd0e811c-1a3d-4a51-8434-e8ed0c1b41c9).

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

Referenced: [Descent integral](#161f1d7d-e8f2-4d0c-9629-73de8028219b).


#### Descent integral {#161f1d7d-e8f2-4d0c-9629-73de8028219b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 21:09]</span></span>
Following the terminology in [Canonical line bundle](#52fa2b27-e4ed-47b1-aaab-d89b2139e8f8). We define
\\[\langle \tau\_{1}^{k\_{1}} \cdots \tau\_{n}^{k\_{n}} \rangle\_{g,n} = \int\_{\bar{M}\_{g,n}} \psi\_{1}^{k\_{1}} \cdots \psi\_{n}^{k\_{n}}\\]
Here, we must make sure \\(\sum k\_{i} = 3g - 3 + n\\) and \\(2g - 2 + n \leq 0\\). Or by simplify notation, we make \\(n = \sum\_{k\_{i}} - 3g + 3\\). These integrals are called **descent integral**.

Referenced: [Witten's Conjecture](#9165c3c5-e1ca-4d24-9ad4-9e918a0a63f6).


#### Witten's Conjecture {#9165c3c5-e1ca-4d24-9ad4-9e918a0a63f6}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 20:43]</span></span>
Considering the [Descent integrals](#161f1d7d-e8f2-4d0c-9629-73de8028219b), we have generating function
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

Referenced: [Virasoro constraint](#22a94486-fcc6-4ba9-a5c4-5e49c40517f4).


#### <span class="org-todo todo TODO">TODO</span> String equation {#aa09deb9-27c3-44fe-b0d4-25b9020b1b1a}


#### <span class="org-todo todo TODO">TODO</span> Diliton equation {#90453a81-c070-49d8-9bbd-5754453428b2}


#### Virasoro constraint {#22a94486-fcc6-4ba9-a5c4-5e49c40517f4}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 21:34]</span></span>
Using the same generating function as in [Witten's Conjecture](#9165c3c5-e1ca-4d24-9ad4-9e918a0a63f6). We define partition function \\(Z(\lambda, t) = \exp(F)\\). Now we define a sequence of operators satisfying the [Virasoro bracket](#bb1d2011-9d33-4cf1-b728-ea0181af047a).
\\[L\_{n} = -\frac{(2n + 3)!!}{2 ^{n + 1}} \frac{\partial}{\partial t\_{n + 1}} + \sum\_{i = 0}^{\infty} \frac{(2i + 2n + 1)!!}{(2i - 1)!! 2 ^{n + 1}} t\_{i} \frac{\partial}{\partial t\_{i + n}} + \frac{\lambda^{2}}{2} \sum\_{i = 0}^{n - 1} \frac{(2i + 1)!! (-2i +2n - 1)!!}{2 ^{n + 1}} \frac{\partial^{2}}{\partial t\_{i} \partial t\_{n - 1 - i}}\\]
Then we have that
\\[L\_{n}(Z) = 0\\]
for \\(n \geq -1\\), which is called **Virasoro constraint**.


### Moduli space of Stable Maps {#cee41211-6bef-4bb0-b5d7-52d6d0cab804}



{{% definition %}}
Let \\(X\\) be a non-singular projective variety. A morphism \\(f\\) from a pointed nodal curve to \\(X\\) is a **stable map** if every genus \\(0\\) contracted component of \\(\Sigma\\) has at least three special points, and every genus \\(1\\) contracted component has at least one special point.
{{% /definition %}}

{{% definition %}}
A stable map represents a homology class \\(\beta \in H\_{2}(X, \mathbb{Z})\\) if \\(f\_{\*}[C] = \beta\\).
{{% /definition %}}

{{% definition %}}
The moduli space of stable maps from \\(n\\)-pointed genus \\(g\\) nodal curves to \\(X\\) representing the class \\(\beta\\) is denoted \\(\bar{M}\_{g,n}(X, \beta)\\). The subscript \\(n\\) may be omitted if \\(n = 0\\).
{{% /definition %}}

The moduli space \\(\overline{M}\_{g,n}(X, \beta)\\) is a Deligne-Mumford stack. And the moduli    space admits [Virtual fundamental class](#7d52eb53-34d5-4da6-80f4-7242956a1c44).

Referenced: [Gromov-Witten theory](#0fafdc7b-a6b5-4143-b239-810531e0623f).


### Morphism {#d6b5466f-95eb-4b5b-b4e3-d0861021dcb1}



Referenced: [Toric](#90007b48-ef9b-474d-a2ac-6f3f4a2447b0).


#### Étale {#ed41498b-430c-485c-b0d3-1f26d531902a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 19:47]</span></span>
A morphism \\(f: X \to Y\\) is **étale** if one of the followings are satisfied

1.  \\(f\\) is flat and unramified, that is for \\(y \in Y\\) scheme theoretic fiber \\(X\_{y}\\) is isomorphic to a disjoint union of \\(\spec K\_{i}\\) where \\(K\_{i}\\) is separable field extension of \\(\kappa(y)\\).
2.  \\(f\\) is flat and \\(\Omega\_{X/Y} = 0\\).
3.  For any surjection \\(A \to A\_{0}\\) of rings with nilpotent kernel the following commutative diagram can be filled.

    {{< figure src="/img/2021-12-26_19-58-35_screenshot.png" >}}
4.  For every point \\(x \in X\\), there exist affine open neighborhoods \\(\spec B\\) of \\(f(x)\\) and \\(\spec A \subset f^{-1}(\spec B)\\) of \\(x\\) and an \\(A\\)-algebra isomorphism
    \\[B \cong (A[x\_{1}, \cdots, x\_{n}]/(f\_{1}, \cdots, f\_{n}))\_{g}\\]
    for some \\(f\_{1}, \cdots, f\_{n}, g \in A[x\_{1}, \cdots, x\_{n}]\\) such that determinant \\(\det(\frac{\dif f\_{j}}{\dif x\_{i}})\_{1 \leq i,j \leq n} \in B\\) is a unit.

In addition \\(X\\) and \\(Y\\) are locally of finite type over an algebraic closed field \\(K\\), then above is equivalent to

<ol class="org-ol">
<li value="5">For all \\(x\\) closed point, the induced map \\(\hat{\mathcal{O}}\_{Y, f(x)} \to \hat{\mathcal{O}}\_{X, x}\\) on completions is an isomorphism.</li>
<li>If \\(X\\) and \\(Y\\) are smooth, the induced map \\(T\_{X,x} \to T\_{Y,f(x)}\\) on tangent spaces is an isomorphism.</li>
</ol>

A morphism is called **étale** at \\(x\\) if it is étale in a small neighborhood.


#### Toric {#90007b48-ef9b-474d-a2ac-6f3f4a2447b0}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-12 Sun 20:23]</span></span>
Let \\(V\_{i} = \spec (\CC[S\_{i}])\\) be the [Affine toric variety](#fad44b6c-ee19-49dc-90e7-3f83dbb75678) coming from the affine semigroup \\(S\_{i}\\), \\(i = 1,2\\). Then a [Morphism](#d6b5466f-95eb-4b5b-b4e3-d0861021dcb1) \\(\phi: V\_{1} \to V\_{2}\\) is **toric** if the corresponding map of coordinate rings \\(\phi^{\* }: \CC[S\_{2}] \to \CC[S\_{1}]\\) is induced by a [Semigroup](#9d39df7e-9bb0-4cd4-a8c6-31f42159397e) homomorphism \\(\hat{\phi}: S\_{2} \to S\_{1}\\).

A toric morphism is **equivariant**. That is
\\[\phi(t \cdot p) = \phi(t) \cdot \phi(p)\\]
for \\(t \in T\_{N}\\) and \\(p \in V\_{1}\\).

For [Algebraic stack](#bb5b2734-6496-44c1-a515-c956d5277467), a morphsim \\(X \to Y\\) is **unramified** or **étale** if \\(X \to Y\\) is representable by [Deligne-Mumford stack](#30e38a6a-1476-4c73-967f-cb882e9d96e8) and has the corresponding property.


### Non-normal toric variety {#8047b0a5-171f-4e4d-a598-b05e3fb06df7}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:08]</span></span>
[Toric variety](#13b3e41c-f513-4c38-90ea-5063fde975cc) is not necessarily normal. For example, \\(\spec \CC[x,y]/(x^{2} - y^{3})\\).


### Polyhedral cone {#1dfb8b9c-7a4a-4c23-bf4d-9665c421e19f}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 19:48]</span></span>
A **convex polyhedral cone** in a real vector space \\(N\_{\RR}\\) is a set of the form
\\[\sigma = \cone(S) = \\{\sum\_{u \in S} \lambda\_{u} u \mid \lambda\_{u} \geq 0\\}\\]
where \\(S \subset N\_{\RR}\\) is finite. And we say that \\(\sigma\\) is generated by \\(S\\). In particular, we define \\(\cone(\emptyset) = \\{0\\}\\).

The **dimension** of polyhedral cone is the dimension of the minimal linear space containing the cone.

Referenced: [Affine toric variety](#fad44b6c-ee19-49dc-90e7-3f83dbb75678), [Polytope](#0a081e79-524f-4bca-bc70-2bb592dfd9ec), [Dual cone](#267ebe2f-e11a-4728-8760-45f1c47b482e), [Supporting hyperplane](#e0c158b5-810f-4847-bd27-d07f74d608ca), [Face](#ecf9eadb-edb2-48f3-b9b9-500dece9c422), [Dual face](#20480d24-2e40-4ff6-8cef-5ce94832b4bb), [Relative interior space](#5cedeff9-9950-4b9b-9914-c5a52496279a), [Strongly convex](#c3e2c96e-0eaf-4319-99ac-ffbc5ba9f62a), [Separation lemma](#5a8c132b-e57f-47a5-9cf6-ba3611e5b3ae), [Rational](#ac77486a-35da-4294-b711-eba0eab4533e), [Smooth](#488012f2-a151-492b-8877-8dc36a3c4215), [Simplicial](#711ed181-cbdc-4358-9d72-bf92bc1d8712), [Saturated](#8566ada4-b025-4f91-a38b-1b2b7583ab80).


#### Polytope {#0a081e79-524f-4bca-bc70-2bb592dfd9ec}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 19:57]</span></span>
A **polytope** in \\(N\_{\RR}\\) is a set of the form
\\[P = \conv(S) = \\{\sum\_{u \in S} \lambda\_{u}u \mid \lambda\_{u} \geq 0, \sum\_{u \in S} \lambda\_{u} = 1\\}\\]
where \\(S \subset N\_{\RR}\\) is finite. We say that \\(P\\) is the **convex hull** of \\(S\\).

Cf. [Polyhedral cone](#1dfb8b9c-7a4a-4c23-bf4d-9665c421e19f).


#### Dual cone {#267ebe2f-e11a-4728-8760-45f1c47b482e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 19:59]</span></span>
Given a [Polyhedral cone](#1dfb8b9c-7a4a-4c23-bf4d-9665c421e19f) \\(\sigma \in N\_{\RR}\\), we have a **dual cone** in dual space \\(M\_{\RR}\\) of \\(N\_{RR}\\),
\\[\sigma^{\vee} = \\{m \in M\_{\RR} \mid \langle m, n \rangle \geq 0 \text{ for all } u \in \sigma\\}\\]

Obviously, we have \\((\sigma^{\vee})^{\vee} = \sigma\\).


#### Supporting hyperplane {#e0c158b5-810f-4847-bd27-d07f74d608ca}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:01]</span></span>
For \\(m \in M\_{\RR}\\), the dual space of \\(N\_{\RR}\\), We define \\(H\_{m} = \\{u \in N\_{\RR} \mid \langle m,n \rangle = 0\\}\\), and \\(H\_{m}^{+ } = \\{u \in N\_{\RR} \mid \langle m, n \rangle \geq 0\\}\\). We call \\(H\_{m}\\) a **supporting hyperplane** of a [Polyhedral cone](#1dfb8b9c-7a4a-4c23-bf4d-9665c421e19f) \\(\sigma\\) if we have \\(\sigma \subset H\_{m}^{+}\\) and \\(H\_{m}^{ +}\\) is then called supporting half-space.

Referenced: [Face](#ecf9eadb-edb2-48f3-b9b9-500dece9c422), [Separation lemma](#5a8c132b-e57f-47a5-9cf6-ba3611e5b3ae).


#### Face {#ecf9eadb-edb2-48f3-b9b9-500dece9c422}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:04]</span></span>
A **face** of a cone of the [Polyhedral cone](#1dfb8b9c-7a4a-4c23-bf4d-9665c421e19f) \\(\sigma\\) is \\(\tau = H\_{m} \cap \sigma\\) for some \\(m \in \sigma^{\vee}\\) and \\(H\_{m}\\) is the [Supporting hyperplane](#e0c158b5-810f-4847-bd27-d07f74d608ca). We may write as \\(\tau \preceq \sigma\\). If \\(\tau \neq \sigma\\), we called \\(\tau\\) the **proper face** and write \\(\tau \prec \sigma\\). A **facet** is a face of codimension \\(1\\) and an **edge** is a face of dimension \\(1\\).

The faces of the [Strongly convex](#c3e2c96e-0eaf-4319-99ac-ffbc5ba9f62a) [Rational](#ac77486a-35da-4294-b711-eba0eab4533e) [Polyhedral cone](#1dfb8b9c-7a4a-4c23-bf4d-9665c421e19f) gives affine open subset of the [Affine toric variety](#fad44b6c-ee19-49dc-90e7-3f83dbb75678). ([<span id="56219725c40008d847a57904e2a7e775"><a href="#CLS2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">CLS2011</a></span>] Proposition 1.3.16)

{{% proposition %}}
Let \\(\tau\\) be a face of strongly convex rational polyhedral cone \\(\sigma\\) and \\(\tau = H\_{m} \cap \sigma\\) for some \\(m \in \sigma^{\vee} \cap M\\). Then we have
\\[\CC[S\_{\tau}] = \CC[S\_{\sigma}]\_{\chi^{m}}\\]
{{% /proposition %}}

Referenced: [Dual face](#20480d24-2e40-4ff6-8cef-5ce94832b4bb).


#### Dual face {#20480d24-2e40-4ff6-8cef-5ce94832b4bb}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:09]</span></span>
Given a [Face](#ecf9eadb-edb2-48f3-b9b9-500dece9c422) \\(\tau \preceq \sigma\\), we have
\\[\tau^{\perp} = \\{m \in M\_{\RR} \mid \langle m,n \rangle = 0 \text{ for all } u \in \tau\\}\\]
and the **dual face** is defined as
\\[\tau^{\* } = \sigma^{\vee} \cap \tau^{\perp}\\]

Cf. [Polyhedral cone](#1dfb8b9c-7a4a-4c23-bf4d-9665c421e19f).


#### Relative interior space {#5cedeff9-9950-4b9b-9914-c5a52496279a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:11]</span></span>
The **relative interior space** of a [Polyhedral cone](#1dfb8b9c-7a4a-4c23-bf4d-9665c421e19f) \\(\sigma\\) is the interior of the cone with respect to the minimal linear space containing it. The terminology is useful, since we may consider the cone with less dimension than the ambient linear space.


#### Strongly convex {#c3e2c96e-0eaf-4319-99ac-ffbc5ba9f62a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:13]</span></span>
A [Polyhedral cone](#1dfb8b9c-7a4a-4c23-bf4d-9665c421e19f) is called **strongly convex** if the origin is a face of the cone. Or equivalently speaking we have \\(\sigma \cap (- \sigma) = \\{0\\}\\).

Referenced: [Affine toric variety](#fad44b6c-ee19-49dc-90e7-3f83dbb75678), [Face](#ecf9eadb-edb2-48f3-b9b9-500dece9c422), [Smooth](#488012f2-a151-492b-8877-8dc36a3c4215), [Simplicial](#711ed181-cbdc-4358-9d72-bf92bc1d8712), [Saturated](#8566ada4-b025-4f91-a38b-1b2b7583ab80).


#### Separation lemma {#5a8c132b-e57f-47a5-9cf6-ba3611e5b3ae}



{{% lemma %}}
Let \\(\sigma\_{1}, \sigma\_{2}\\) be polyhedral cones in \\(N\_{\RR}\\), and they meet along a common face \\(\tau = \sigma\_{1} \cap \sigma\_{2}\\). Then we have
\\[\tau = H\_{m} \cap \sigma\_{1} = H\_{m} \cap \sigma\_{2}\\]
for some \\(m\\) in the dual space of \\(N\_{\RR}\\).
{{% /lemma %}}

Cf. [Supporting hyperplane](#e0c158b5-810f-4847-bd27-d07f74d608ca), [Polyhedral cone](#1dfb8b9c-7a4a-4c23-bf4d-9665c421e19f).


#### Rational {#ac77486a-35da-4294-b711-eba0eab4533e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:16]</span></span>
A [Polyhedral cone](#1dfb8b9c-7a4a-4c23-bf4d-9665c421e19f) is called **rational** if by equating \\(N\_{\RR} = N \otimes\_{\ZZ} \RR\\), where \\(N\\) is a [Lattice](#f35a2d22-45cb-470e-92bf-b6601186d5f4), we have \\(\sigma = \cone(S)\\) for \\(S \in N\\).

For rational cone, \\(\rho \subset \sigma\\) an edge, the generator of \\(\rho \cap N\\) is called **ray generator** of \\(\rho\\).

Referenced: [Affine toric variety](#fad44b6c-ee19-49dc-90e7-3f83dbb75678), [Face](#ecf9eadb-edb2-48f3-b9b9-500dece9c422), [Smooth](#488012f2-a151-492b-8877-8dc36a3c4215), [Simplicial](#711ed181-cbdc-4358-9d72-bf92bc1d8712), [Saturated](#8566ada4-b025-4f91-a38b-1b2b7583ab80).


#### Smooth {#488012f2-a151-492b-8877-8dc36a3c4215}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:20]</span></span>
A [Strongly convex](#c3e2c96e-0eaf-4319-99ac-ffbc5ba9f62a), [Rational](#ac77486a-35da-4294-b711-eba0eab4533e) [Polyhedral cone](#1dfb8b9c-7a4a-4c23-bf4d-9665c421e19f) is called **smooth** or **regular** if its minimal generators form part of a \\(\ZZ\\)-basis of \\(N\\).

The following theorem justify the above name. ([<span id="56219725c40008d847a57904e2a7e775"><a href="#CLS2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">CLS2011</a></span>] Theorem 1.3.12)

{{% theorem %}}
Let \\(\sigma \subset N\_{\RR}\\) be a strongly convex rational polyhedral cone. Then \\(U\_{\sigma}\\) is smooth if and only if \\(\sigma\\) is smooth. Furthermore, all smooth affine varieties are of this form.
{{% /theorem %}}


#### Simplicial {#711ed181-cbdc-4358-9d72-bf92bc1d8712}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:24]</span></span>
A [Strongly convex](#c3e2c96e-0eaf-4319-99ac-ffbc5ba9f62a), [Rational](#ac77486a-35da-4294-b711-eba0eab4533e) [Polyhedral cone](#1dfb8b9c-7a4a-4c23-bf4d-9665c421e19f) is called **simplicial** if its minimal generators are linearly independent over \\(\RR\\).


### Predeformation functor {#5bf09bb7-02f0-4ebe-86aa-588c2ac3354c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-19 Sun 20:14]</span></span>
A **predeformation functor** is a covariant functor \\(F: \cat{Art}(\Lambda, k) \to \cat{Set}\\) such that \\(F(k)\\) is the one-element set. The **tangent space** \\(T\_{F}\\) is defined to be \\(F(k[\epsilon]/(\epsilon^{2}))\\). The objects of \\(\cat{Art}(\Lambda, k)\\) are local Artin \\(\Lambda\\)-algebra with residue field \\(k\\).

Cf. [Tangent space](#8de50bef-4318-4dd1-bcde-95464bb002dd).

Referenced: [Deformation functor](#6c6901f3-261c-4f7a-bdfc-6fdfe9aa38ad), [Hull](#81b84e2c-f7ef-4c3b-a662-b7cdbfd1b043), [Schlessinger's theorem](#5a2b53ea-6a6d-43eb-b668-9125f5023c91).


### Presheaf {#6cbbbc05-b715-4d9c-aee1-16fd53bd4ad2}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 21:35]</span></span>
A **presheaf** on a category \\(C\\) is a functor
\\[F: C^{op} \to \cat{Set}\\]
We usually write \\(\hat{C}\\) for teh category of presheaves on \\(C\\).

Referenced: [Separated](#46d7ded4-ff2b-4777-a02a-0af38b86678f), [Sheaf](#32e43dc9-af7b-46a9-a114-1d5f42a5f95d).


#### Separated {#46d7ded4-ff2b-4777-a02a-0af38b86678f}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 21:36]</span></span>
A [Presheaf](#6cbbbc05-b715-4d9c-aee1-16fd53bd4ad2) \\(F\\) on \\(C\\) is called **separated** if for every \\(U \in C\\) and \\(\\{U\_{i} \to U\\}\_{i \in I} \in \cat{Cov}(U)\\) the map \\(F(U) \to \prod F(U\_{i})\\) is injective.


### Prestack {#f368a933-d735-415d-b8f1-3b980077ea40}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:05]</span></span>
A **prestack** over \\(\cat{Sch}\\) is a category \\(\mathfrak{X}\\) together with functor \\(p: \mathfrak{X} \to \cat{Sch}\\) such that

1.  for any diagram

    {{< figure src="/img/2021-12-29_20-02-06_screenshot.png" >}}

    there exist a morphism \\(a \to b\\) over \\(S \to T\\).
2.  for any diagram

    {{< figure src="/img/2021-12-29_20-02-18_screenshot.png" >}}

    there exists a unique arrow \\(a \to b\\) over \\(R \to S\\) filling in the diagram.

{{% exam %}}
Presheaves are prestacks.
{{% /exam %}}

Cf. [Presheaf](#6cbbbc05-b715-4d9c-aee1-16fd53bd4ad2).

{{% exam %}}
Schemes are prestacks.
{{% /exam %}}

A morphism of prestacks \\(f: \mathfrak{X} \to \mathfrak{Y}\\) is a functor commutes with morphism to \\(S\\). For \\(f,g\\) two morphisms, a 2-morphism is a natural transformation \\(\alpha: f \to g\\) such that \\(\alpha\_{a}: f(a) \to g(a)\\) in \\(\mathfrak{Y}\\) is over \\(\id\_{s}\\).


### Prorepresnetable {#86359962-b390-4e4f-a49e-d7704506e013}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-19 Sun 20:23]</span></span>
Let \\(\widehat{\cat{Art}(\Lambda, k)}\\) be the category of complete Noetherian local \\(\Lambda\\)-algebra with residue field \\(k\\). Set \\(\hat{F} := \varprojlim\_{n} F(R/ \mathfrak{m}^{n})\\). We say that \\(F\\) is **propresentable** if and only if \\(\hat{F}\\) is representable.

Referenced: [Schlessinger's theorem](#5a2b53ea-6a6d-43eb-b668-9125f5023c91).


### Pure {#12784521-08ec-4290-a252-2a478138bc9c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:29]</span></span>
\\(E\\) is **pure of dimension** \\(d\\) if \\(\dim F = d\\) for all non-trivial coherent subsheaves \\(F \subset E\\).

Referenced: [Stable](#6166a93c-597c-4b52-804f-0b1d8b73b2a8).


### Rational surface {#8d881b57-22fa-4c0d-9e02-d56fde2b4d47}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:36]</span></span>
A **rational surface** is an algebraic surface birational equivalent to \\(\CC P^{2}\\).


### Reflexive {#15449aca-6239-4e92-a379-cb76a4cf492b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:39]</span></span>
A coherent sheaf \\(E\\) of codimension \\(c\\) is called **reflexive** if \\(\theta\_{E}: E \to E^{DD}\\) is an isomorphism. \\(E^{DD}\\) is called the **reflexive hull**  of \\(E\\).

Cf. [Dual sheaf](#47e13ac2-f80a-44aa-8b25-d79bdacd0600).


### Regular sequence {#e8f31b9d-3f74-4d2c-b31a-86d78466e799}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:47]</span></span>
Let \\(M\\) be a module over a local ring \\(A\\). An element \\(a \in \mathfrak{m}\\) of \\(A\\) is called **\\(M\\)-regular** if \\(m \to am\\) is injective morphism. A sequence \\(a\_{1}, \cdots, a\_{l} \in \mathfrak{m}\\) is a **\\(M\\)-regular sequence** if \\(a\_{i}\\) is \\(M/(a\_{1}, \cdots, a\_{i - 1}) M\\) regular for all \\(i\\).

The definition can be generalized to sheaf theoretic language. Let \\(X\\) be a Noetherian scheme, let \\(E\\) be a coherent sheaf on \\(X\\) and \\(L\\) a line bundle on \\(X\\). A section \\(s \in H^{0}(X, L)\\) is called **\\(E\\)-regular** if and only if \\(E \otimes L^{\vee} \stackrel{\cdot s}{\to} E\\) is injective. A sequence \\(s\_{1}, \cdots, s\_{l} \in H^{0}(X, L)\\) is called **\\(E\\)-regular** similarly in the module theoretic language.

Referenced: [Depth](#85bd6a8b-f480-47f2-8873-f3f39578df09).


### Residual gerbe {#f894f7df-c44c-4579-93ea-5900220e7e9c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-28 Tue 21:44]</span></span>
Let \\(X\\) be an [Algebraic stack](#bb5b2734-6496-44c1-a515-c956d5277467) and \\(x \in \abs{X}\\) be a point. Choose a smooth presentation \\((U, u) \to (X, x)\\). The **residual gerbe** of \\(x\\) is the substack \\(G\_{x} \subset X\\) defined as the stackification of the full subcategory \\(G\_{x}^{pre}\\) consisting of object \\(a \in X\\) over \\(S\\) which factor as \\(a: S \to \spec \kappa(u) \to X\\).


### <span class="org-todo todo TODO">TODO</span> Riemann-Roch theorem {#71567b80-690f-4d38-9eb7-d6a5454d715a}


### <span class="org-todo todo TODO">TODO</span> Ring {#8fb9bf46-4339-41aa-812a-5aed815c59a2}




#### <span class="org-todo todo TODO">TODO</span> Local ring {#82ff8727-44bd-4118-94f5-27c7aeae8cc7}



Referenced: [Hull](#81b84e2c-f7ef-4c3b-a662-b7cdbfd1b043), [Complete](#f92f1fd0-86ef-4e15-acbc-104ebfee400a).


#### Complete {#f92f1fd0-86ef-4e15-acbc-104ebfee400a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-19 Sun 20:14]</span></span>
A [Local ring](#82ff8727-44bd-4118-94f5-27c7aeae8cc7) is called **complete** if it is complete with respect to the \\(\mathfrak{m}\\)-adic topology.

Referenced: [Hull](#81b84e2c-f7ef-4c3b-a662-b7cdbfd1b043).


#### <span class="org-todo todo TODO">TODO</span> Noetherian {#553a8417-9fe5-428c-ad73-8044d8af226b}



Referenced: [Hull](#81b84e2c-f7ef-4c3b-a662-b7cdbfd1b043).


### Schlessinger's theorem {#5a2b53ea-6a6d-43eb-b668-9125f5023c91}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-19 Sun 20:24]</span></span>
The **Schlessinger's theorem** is a criterion for existence of [Hull](#81b84e2c-f7ef-4c3b-a662-b7cdbfd1b043) or [Prorepresnetibility](#86359962-b390-4e4f-a49e-d7704506e013).

{{% theorem %}}
Let \\(F\\) be a predoformation functor. Then \\(F\\) has a hull if and only if the following conditions (1-3) holds, and \\(F\\) is prorepresentable if and only if in addition (4) holds.

1.  The map
    \\[F(A' \times\_{A} A'') \to F(A') \times\_{F(A)} F(A'')\\]
    is surjective when \\(A'' \to A\\) is a small thickening.
2.  The above map is bijective when \\(A = k\\) and \\(A'' = k[\epsilon]\\).
3.  The tangent space \\(T\_{F}\\) is finite-dimensional over \\(k\\).
4.  The above map is bijective if \\(A'' = A'\\) and \\(A' \to A\\) is a small thickening.
{{% /theorem %}}

Cf. [Predeformation functor](#5bf09bb7-02f0-4ebe-86aa-588c2ac3354c), [Small thickening](#6083073b-8545-443d-9772-bf9aec15baa0).

Referenced: [Deformation functor](#6c6901f3-261c-4f7a-bdfc-6fdfe9aa38ad).


### Semigroup {#9d39df7e-9bb0-4cd4-a8c6-31f42159397e}



Referenced: [Toric](#90007b48-ef9b-474d-a2ac-6f3f4a2447b0), [Affine semigroup](#ca294346-6eb1-45fc-b49f-4a01691e96ab), [Irreducible](#73b9497d-1b0b-4702-87a9-cddc86dae64c).


#### Affine semigroup {#ca294346-6eb1-45fc-b49f-4a01691e96ab}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:17]</span></span>
An **affine semigroup** is a [Semigroup](#9d39df7e-9bb0-4cd4-a8c6-31f42159397e) where the binary operation is commutative, finite generated, and can be embedded in a [Lattice](#f35a2d22-45cb-470e-92bf-b6601186d5f4) \\(M\\).

Referenced: [Affine toric variety](#fad44b6c-ee19-49dc-90e7-3f83dbb75678), [Pointed](#5c3f014a-571f-47a0-a97e-11c210848309), [Saturated](#8566ada4-b025-4f91-a38b-1b2b7583ab80).


#### Irreducible {#73b9497d-1b0b-4702-87a9-cddc86dae64c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:26]</span></span>
An element in a [Semigroup](#9d39df7e-9bb0-4cd4-a8c6-31f42159397e) is called **irreducible** if \\(m = m' + m''\\) in the semigroup, then we have \\(m' = 0\\) or \\(m'' = 0\\).


#### Pointed {#5c3f014a-571f-47a0-a97e-11c210848309}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-12 Sun 19:24]</span></span>
A **pointed** affine semigroup \\(S\\) is the [Affine semigroup](#ca294346-6eb1-45fc-b49f-4a01691e96ab) such that \\(S \cap (-S) = \\{0\\}\\).

The pointed affine semigroup is related to [Affine toric variety](#fad44b6c-ee19-49dc-90e7-3f83dbb75678) by the following proposition.

{{% proposition %}}
If we write \\(V = \spec(\CC[S])\\), then the torus action has a fixed point if and only if \\(S\\) is pointed. What's more, the fixed point is unique and given by semigroup homomorphism
\\(\phi:S \to \CC\\) defined by

\begin{equation} m \to \begin{cases} 1 & m = 0 \\\\ 0 & m \neq 0 \end{cases} \end{equation}
{{% /proposition %}}


#### Saturated {#8566ada4-b025-4f91-a38b-1b2b7583ab80}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-12 Sun 19:44]</span></span>
An [Affine semigroup](#ca294346-6eb1-45fc-b49f-4a01691e96ab) \\(S \subset M\\) is **saturated** if for all \\(k \in \NN \backslash \\{0\\}\\) and \\(m \in M\\), \\(km \in S\\) implies \\(m \in S\\). ([<span id="56219725c40008d847a57904e2a7e775"><a href="#CLS2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">CLS2011</a></span>] p.37)

One important source of the saturated affine semigroup is \\(S\_{\sigma} = \sigma^{\vee} \cap M\\) where \\(\sigma\\) is a [Strongly convex](#c3e2c96e-0eaf-4319-99ac-ffbc5ba9f62a) [Rational](#ac77486a-35da-4294-b711-eba0eab4533e) [Polyhedral cone](#1dfb8b9c-7a4a-4c23-bf4d-9665c421e19f).

The saturated affine semigroup is related to normal [Affine toric variety](#fad44b6c-ee19-49dc-90e7-3f83dbb75678). ([<span id="56219725c40008d847a57904e2a7e775"><a href="#CLS2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">CLS2011</a></span>] Theorem 1.3.5)

{{% theorem %}}
Let \\(V\\) be an affine toric variety with torus \\(T\_{N}\\). Then \\(V\\) is normal if and only if \\(V = \spec(\CC[S])\\), where \\(S \subset M\\) is a saturated affine semigroup.
{{% /theorem %}}


### <span class="org-todo todo TODO">TODO</span> Semismall map {#ad98c86c-c893-4d8b-ae71-3e2041801a6b}



Referenced: [Small map](#8eb64256-2da8-489b-a275-4d677add85a5).


### <span class="org-todo todo TODO">TODO</span> Serre duality {#75a66ecb-0159-45cd-9060-45958cefaa9b}


### Sheaf {#32e43dc9-af7b-46a9-a114-1d5f42a5f95d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:46]</span></span>
A [Presheaf](#6cbbbc05-b715-4d9c-aee1-16fd53bd4ad2) \\(F\\) on \\(C\\) is called a **sheaf** if for every object \\(U \in C\\) and covering \\(\\{U\_{i} \to U\\}\\) the sequence
\\[F(U) \to \prod\_{i} F(U\_{i}) \rightrightarrows \prod\_{i,j} F(U\_{i} \times\_{U} U\_{j})\\]
is exact, where the two maps on the right are induced by the two projections \\(U\_{i} \times\_{U} U\_{j} \to U\_{i}\\) and \\(U\_{i} \times U\_{j} \to U\_{j}\\). Here exact means equalizer.

We write \\(C^{~}\\) for the category of sheaves on \\(C\\).

{{% theorem %}}
Let \\(C\\) be a site. The inclusion
\\[\text{(sheaves on \\(C\\))} \hookrightarrow \text{(presheaves on \\(C\\))}\\]
has a left adjoint \\(F \to F^{a}\\).
{{% /theorem %}}

Cf. [Site](#d827cad0-92be-4251-9e34-4243334a9315).

The left adjoint \\(F \to F^{a}\\) is called **sheafification** and \\(F^{a}\\) is called the **sheaf associated to** \\(F\\).

For \\(f: C' \to C\\) functor between small categories, we have functor \\(f\_{\*}: \hat{C} \to \hat{C}\\) by \\((f\_{\*}F)(X) := F(f(X))\\). And we have left adjoint functor \\(\hat{f}^{\*}\\). And if \\(f\\) is [Continuous](#acaebda9-a08a-412e-a02c-17724aba56d9), then the induced functor between [Topoi](#7ee906fc-4e21-4965-a082-1e0ee87235c7) \\(f\_{\*}: T \to T'\\) also has a left adjoint.

If finite limits in \\(C'\\) are representable and that \\(f\\) commutes with all finite limits in \\(C'\\). Then \\(f^{\*}\\) commutes with finite limits and hence \\(f\\) defines a morphism of topoi.

Referenced: [Framed moduli space](#db778f90-fd0b-4436-87b4-d64ab769b8af), [Sheafification](#7c9a213c-0275-4e68-8ae3-a42d65a3c77c), [Topos](#7ee906fc-4e21-4965-a082-1e0ee87235c7).


#### Euler characteristic {#2b604784-0335-478d-975f-9fef8d1c3946}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:33]</span></span>
The **Euler characteristic** of a sheaf \\(E\\) is
\\[\chi(E) = \sum (-1)^{i} h^{i}(X, E)\\]


#### Hilbert polynomial {#b64d4546-beb7-4290-a156-f555146ab6b5}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:34]</span></span>
The **Hilbert polynomial** is the function
\\[P(E,m): m \to \chi(E \otimes \OO(m))\\]

For Hilbert polynomial \\(P(E, m) = \sum\_{i = 0}^{\dim(E)} \alpha\_{i}(E) \frac{m^{i}}{i!}\\), we
define **reduced Hilbert polynomial** as
\\[p(E)= P(E)/ \alpha\_{d}(E) \\]

Referenced: [Multiplicity](#302aac45-94d5-45ab-986c-b684f65d9fe5), [Rank](#02e95a35-be50-4a08-b3c6-b1ec417159fd), [Stable](#6166a93c-597c-4b52-804f-0b1d8b73b2a8), [&mu;-stable](#df9d557e-ba66-41f2-af07-188d5b7f4a8b).


#### Multiplicity {#302aac45-94d5-45ab-986c-b684f65d9fe5}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:37]</span></span>
For [Hilbert polynomial](#b64d4546-beb7-4290-a156-f555146ab6b5) \\(P(E, m) = \sum\_{i = 0}^{\dim(E)} \alpha\_{i}(E) \frac{m^{i}}{i!}\\), and \\(E \neq 0\\), the leading coefficient \\(\alpha\_{\dim(E)}(E)\\) is called **multiplicity**.


#### Rank {#02e95a35-be50-4a08-b3c6-b1ec417159fd}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:38]</span></span>
For [Hilbert polynomial](#b64d4546-beb7-4290-a156-f555146ab6b5) \\(P(E, m) = \sum\_{i = 0}^{\dim(E)} \alpha\_{i}(E) \frac{m^{i}}{i!}\\), and \\(\dim(E) = \dim(X) = d\\),
\\[\rk(E) := \frac{\alpha\_{d}(E)}{\alpha\_{d}(\OO\_{X})}\\]


#### Stable {#6166a93c-597c-4b52-804f-0b1d8b73b2a8}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:40]</span></span>
We write \\(p\_{1} \leq p\_{2}\\) for two polynomials if \\(p\_{1}(x) \leq p\_{2}(x)\\) when \\(x \gg 0\\).

A coherent sheaf \\(E\\) of dimension \\(d\\) is **semistable** if \\(E\\) is [Pure](#12784521-08ec-4290-a252-2a478138bc9c) and for any proper subsheaf \\(F \subset E\\), one has [Hilbert polynomial](#b64d4546-beb7-4290-a156-f555146ab6b5) \\(p(F) \leq p(E)\\). And is **stable** if \\(E\\) is semistable and \\(p(F) < p(E)\\)

{{% proposition %}}
Let \\(F\\) and \\(G\\) be semistable purely \\(d\\)-dimensional sheaves. If \\(p(F) \geq p(G)\\) then \\(\Hom(F, G) = 0\\). If \\(p(F) = p(G)\\) and \\(f: F \to G\\) non-trivial, then \\(f\\) is injective if \\(F\\) is stable and surjective if \\(G\\) is stable. If \\(p(F) = p(G)\\) and \\(\alpha\_{d}(F) = \alpha\_{d}(G)\\) then any non-trivial homomorphism \\(f: F \to G\\) is an isomorphism provided \\(F\\) or \\(G\\) is stable.
{{% /proposition %}}

{{% corollary %}}
If \\(E\\) is a stable sheaf, then \\(\End(E)\\) is a finite dimensional division algebra over \\(k\\). In particular if \\(k\\) is algebraically closed, then \\(\End(E) \cong k\\).
{{% /corollary %}}

Referenced: [Geometrically stable](#c00e14f7-2428-4a23-95a7-413dad118761).


#### Geometrically stable {#c00e14f7-2428-4a23-95a7-413dad118761}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:40]</span></span>
A coherent sheaf \\(E\\) is **geometrically stable** if for any base field extension \\(X\_{K} = X \times\_{k} \spec(K) \to K\\) the pull-back \\(E \otimes\_{k} K\\) is [Stable](#6166a93c-597c-4b52-804f-0b1d8b73b2a8).


#### &mu;-stable {#df9d557e-ba66-41f2-af07-188d5b7f4a8b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-11 Sat 20:41]</span></span>
Let \\(E\\) a coherent sheaf of dimension \\(d = \dim X\\) with [Hilbert polynomial](#b64d4546-beb7-4290-a156-f555146ab6b5) \\(P(E, m) = \sum\_{i = 0}^{\dim(E)} \alpha\_{i}(E) \frac{m^{i}}{i!}\\). We define the **degree** of \\(E\\) by
\\[\deg(E) := \alpha\_{d - 1}(E) - \rk(E) \cdot \alpha\_{d - 1}(\OO\_{X})\\]
and its **slope** by
\\[\mu(E) := \frac{\deg(E)}{\rk(E)}\\]

A coherent sheaf \\(E\\) of dimension \\(d\\) is **\\(\mu\\)-(semi)stable** if \\(T\_{d - 2}(E) = T\_{d - 1}E\\) and \\(\mu(F)(\leq)\mu(E)\\) for all subsheaves \\(F \subset E\\) with \\(0 < \rk(F) < \rk(E)\\).

{{% lemma %}}
\\(E\\) is \\(\mu\\)-stable \\(\Rightarrow\\) \\(E\\) is stable \\(\Rightarrow\\) \\(E\\) is semistable \\(\Rightarrow\\) \\(E\\) is \\(\mu\\)-semistable.
{{% /lemma %}}


### Sheafification {#7c9a213c-0275-4e68-8ae3-a42d65a3c77c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 22:01]</span></span>
Cf. [Sheaf](#32e43dc9-af7b-46a9-a114-1d5f42a5f95d).


### Simple resolution {#14bae490-825c-4bc0-b176-73ef6dbf0b8c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:31]</span></span>
See [<span id="24e67c8afe5163064e4018cb5a5cbd8a"><a href="#nakajima1999" title="Nakajima, Lectures on {{Hilbert}} Schemes of Points on Surfaces, {American Mathematical Society} (1999).">nakajima1999</a></span>] p.47.

A **simple singularity** is a quotient space \\(\CC^{2} / \Gamma\\), where \\(\Gamma\\) is a finite subgroup of \\(\SU(2)\\). A **simple resolution** is a resolution of simple singularity.

The following theorem construct the simple resolution by [Hilbert scheme](#e1fd15af-27a1-4320-b02b-fd567b184b24) of points.

{{% theorem %}}
Consider the Hilbert scheme \\((\CC^{2})^{ [N]}\\) where \\(N\\) is the order of \\(\Gamma\\). The \\(\Gamma\\) orbit of a point \\(p\\) in \\(\CC\backslash \\{0\\}\\) defines a \\(0\\) dimensional subscheme \\(Z \in (\CC^{2})^{ [N]}\\). Let \\(X\\) be the component of \\(\Gamma\\) fixed point set which contains the set of \\(\Gamma\\)-orbits \\(\Gamma \cdot (\CC \backslash \\{0\\})\\). Then we have that the restriction of the Hilbert-Chow morphism to \\(X\\) is the minimal resolution of singularities of \\(\CC^{2} \backslash \Gamma \cong (S^{N}(\CC^{2}))^{\Gamma}\\).
{{% /theorem %}}

Referenced: [Simple singularity](#d22ef6f0-3eb0-40b4-a5ac-f0da25175530).


### Simple singularity {#d22ef6f0-3eb0-40b4-a5ac-f0da25175530}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:32]</span></span>
See [Simple resolution](#14bae490-825c-4bc0-b176-73ef6dbf0b8c).


### Site {#d827cad0-92be-4251-9e34-4243334a9315}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 21:24]</span></span>
A category with a [Grothendieck topology](#3126cca2-f75b-46a3-aa2e-c03e375ecc4e) is called a **site**.

{{% exam %}}
Let \\(X\\) be a topological space, \\(\cat{Op}(X)\\) the category of open sets. Then let \\(\cat{Cov}(U)\\) to be the collections \\(\\{U\_{i} \to U\\}\\) for which \\(U = \cup U\_{i}\\), where \\(U\_{i}\\) is a Grothendieck topology. For Zariski topology space, it is called **small Zariski site**.
{{% /exam %}}

{{% exam %}}
Let \\(X\\) be a scheme and let \\(\cat{(Sch/X)}\\) be the category of \\(X\\)-schemes. We define \\(\cat{Cov}(X)\\) be the set of collections \\(\\{U\_{i} \to U\\}\\) of \\(X\\)-morphisms for which each morphism \\(U\_{i} \to U\\) is étale and the map
\\[\coprod U\_{i} \to U\\]
is surjective. It is called **big étale site**.
{{% /exam %}}

Similarly, we can define **fppf site** (flat and locally of finite presentation) and **smooth site**.

Referenced: [Continuous](#acaebda9-a08a-412e-a02c-17724aba56d9), [Étale site](#d95143d5-1124-4c8a-b7d9-9bc2ab630418), [Fppf site](#352dde73-f559-4539-8881-0c7919e48e8e), [Sheaf](#32e43dc9-af7b-46a9-a114-1d5f42a5f95d), [Smooth site](#657c5ec0-2e1b-4181-a64b-e6020a6950de), [Topos](#7ee906fc-4e21-4965-a082-1e0ee87235c7).


### <span class="org-todo todo TODO">TODO</span> Small map {#8eb64256-2da8-489b-a275-4d677add85a5}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-20 Sat 21:44]</span></span>
See [Semismall map](#ad98c86c-c893-4d8b-ae71-3e2041801a6b).


### Small thickening {#6083073b-8545-443d-9772-bf9aec15baa0}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-19 Sun 20:23]</span></span>
A surjective map \\(f: A \to B\\) in \\(\cat{Art}(\Lambda, k)\\) is a **small thickening** if \\(\ker f \mathfrak{m}\_{A} = 0\\) and \\(\ker f\\) is principal.

Referenced: [Schlessinger's theorem](#5a2b53ea-6a6d-43eb-b668-9125f5023c91).


### Smooth {#ed6ca881-761a-43b8-a905-b4a7b1e808cd}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-28 Tue 19:58]</span></span>
Let \\(F, F': \cat{Art}(\Lambda, k) \to \cat{Set}\\) be covariant functors, with a morphism \\(\phi: F \to F'\\). We say that \\(\phi\\) is **smooth** if for every surjection \\(A \to B\\) in \\(\cat{Art}(\Lambda, k)\\) the map
\\[F(A) \to F(B) \times\_{F'(B)}F'(A)\\]
is surjective.


### Smoothness of Hilbert scheme {#061ec6cf-d155-4b1b-9850-5fbcd84660f6}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-16 Thu 20:44]</span></span>
See [<span id="24e67c8afe5163064e4018cb5a5cbd8a"><a href="#nakajima1999" title="Nakajima, Lectures on {{Hilbert}} Schemes of Points on Surfaces, {American Mathematical Society} (1999).">nakajima1999</a></span>], Section 1.3.

{{% theorem %}}
Suppose \\(X\\) is nonsingular of dimension \\(2\\), then \\(X^{ [n]}\\) is nonsingular of dimension \\(2n\\) and the Hilbert-Chow morphism is a resolution of singularities.
{{% /theorem %}}

Cf. [Hilbert scheme](#e1fd15af-27a1-4320-b02b-fd567b184b24), [Hilbert-Chow morphism](#ea9ca8a9-96aa-4dce-ac1e-1b338d01ec3b).


### Smooth site {#657c5ec0-2e1b-4181-a64b-e6020a6950de}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 21:32]</span></span>
See [Site](#d827cad0-92be-4251-9e34-4243334a9315).


### <span class="org-todo todo TODO">TODO</span> Spectral sequence {#39be8244-5b96-4223-99ec-9259f5c649ec}



Referenced: [Eilenberg-Zilber theorem](#0f96e2c1-4743-46e3-ba56-0ca173da1c8b).


#### <span class="org-todo todo TODO">TODO</span> Beilison spectral sequence {#c794e2a4-8fde-4c95-9ef7-46b8f296fe72}


### Splitting torus {#33b4d7d0-3bd6-4548-9eb6-b3c2cf0780ba}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-16 Thu 20:02]</span></span>
A **splitting torus** is a torus of type \\(k^{\times n}\\).

Cf. [Torus](#14c0a895-04a6-4976-bce3-2b511741dc32).


### Stabilizer {#d7044001-a28e-41b4-9c24-74206f3ef069}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-28 Tue 21:08]</span></span>
If \\(X\\) is an [Algebraic stack](#bb5b2734-6496-44c1-a515-c956d5277467) and \\(x: \spec K \to X\\) is a field-valued point, the **stabilizer** of \\(x\\) is defined as the group scheme \\(G\_{x} = Aut\_{X(K)}(x)\\).

By representability of the diagonal, \\(G\_{x}\\) is a group algebraic space.

If \\(X\\) is a [Deligne-Mumford stack](#30e38a6a-1476-4c73-967f-cb882e9d96e8) and \\(x \in \abs{X}\\), we define the **geometric stabilizer** of \\(x\\) as the discrete group \\(G = G\_{\bar{x}}\\) where \\(\bar{x}: \spec k \to X\\) is any representative of \\(x\\) with \\(k\\) algebraic closed.


### Stack {#7fcf9705-95fa-4c83-8514-af8b15b1d50d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:06]</span></span>
A [Prestack](#f368a933-d735-415d-b8f1-3b980077ea40) \\(\mathfrak{X}\\) over a [Site](#d827cad0-92be-4251-9e34-4243334a9315) \\(\mathfrak{S}\\) is a **stack** if the following conditions hold for all coverings \\(\\{S\_{i} \to S\\}\\) of an object \\(S \in \mathfrak{S}\\):

1.  For object \\(a\\) and \\(b\\) in \\(\mathfrak{X}\\) over \\(S\\) and morphism \\(\phi\_{i}: a|\_{S\_{i}} \to b\\) such that \\(\phi\_{i}|\_{S\_{ij}} = \phi\_{j}|\_{S\_{ij}}\\), there exists a unique morphism \\(\phi: a \to b\\) with \\(\phi|\_{S\_{i}} = \phi\_{i}\\).
2.  For objects \\(a\_{i}\\) over \\(S\_{i}\\) and isomoprhisms \\(\alpha\_{ij}: \alpha\_{i}|\_{S\_{ij}} \to \alpha\_{j}|\_{S\_{ij}}\\) satisfying \\(\alpha\_{ij}|\_{S\_{ijk}} \circ \alpha\_{jk}|\_{S\_{ijk}} = \alpha\_{ik}|\_{S\_{ijk}}\\) on \\(S\_{ijk}\\), then there exists an object \\(a\\) over \\(S\\) and isomorphisms \\(\phi\_{i}: a|\_{S\_{i}} \to a\_{i}\\) such that \\(\alpha\_{ij} \circ \phi\_{i}|\_{S\_{ij}} = \phi\_{j}|\_{S\_{ij}}\\) on \\(S\_{ij}\\).

{{% exam %}}
If \\(g \geq 2\\), then \\(\mathcal{M}\_{g}\\) is a stack over \\(\cat{Sch}\_{Ét}\\).
{{% /exam %}}

{{% exam %}}
For all integers \\(r,d\\) with \\(r \geq 0\\), \\(Bun\_{r,d}( C)\\) is a stack over \\(\cat{Sch/ \CC}\_{Ét}\\).
{{% /exam %}}

{{% theorem %}}
If \\(\mathfrak{X}\\) is a prestack over a site \\(\mathfrak{S}\\), there exists a stack \\(\mathfrak{X}^{st}\\), which we call the **stackfication**, and a morphism \\(\mathfrak{X} \to \mathfrak{X}^{st}\\) of prestacks such that for any stack \\(\mathfrak{Y}\\) over \\(\mathfrak{S}\\), the induced functor \\(\cat{MOR}(\mathfrak{X}^{st}, \mathfrak{Y}) \to \cat{MOR}(\mathfrak{X}, \mathfrak{Y})\\) is an equivalence of categories.
{{% /theorem %}}


### Symmetric power of P^1 {#dada5b28-37d2-446b-b8f4-2a366e575449}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-16 Thu 20:28]</span></span>
Fact, \\(S^{n}(\PP^{1}) = \PP^{n}\\).


### <span class="org-todo todo TODO">TODO</span> Symplectic resolution {#ed5f4bcb-9fbf-45ff-9c26-0d56567405ac}


### Symplectic structure of Hilbert scheme {#9e6166a7-590b-44da-a207-f45f189df7c0}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-16 Thu 20:41]</span></span>
See [<span id="24e67c8afe5163064e4018cb5a5cbd8a"><a href="#nakajima1999" title="Nakajima, Lectures on {{Hilbert}} Schemes of Points on Surfaces, {American Mathematical Society} (1999).">nakajima1999</a></span>], Section 1.4.

{{% theorem %}}
Suppose \\(X\\) has a holomorphic symplectic form \\(\omega\\). Then \\(X^{ [n]}\\) also has a holomorphic symplectic form.
{{% /theorem %}}

Cf. [Symplectic manifold](#c127758e-3380-4bff-99e8-51d950df4d1c), [Hilbert scheme](#e1fd15af-27a1-4320-b02b-fd567b184b24).


### Topos {#7ee906fc-4e21-4965-a082-1e0ee87235c7}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-06 Sat 22:02]</span></span>
A **topos** is a category \\(T\\) equivalent to the category of [Sheaves](#32e43dc9-af7b-46a9-a114-1d5f42a5f95d) of sets on [Site](#d827cad0-92be-4251-9e34-4243334a9315).

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

Referenced: [Continuous](#acaebda9-a08a-412e-a02c-17724aba56d9), [Category of modules](#bd4d822f-e06f-422b-b64f-343e6782e57b), [Sheaf](#32e43dc9-af7b-46a9-a114-1d5f42a5f95d), [Ringed](#9162568f-56ca-4c95-afa3-cb5053742bee), [Point](#1feee86f-f818-4763-bcbf-7074b7927aa8).


#### Ringed {#9162568f-56ca-4c95-afa3-cb5053742bee}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-07 Sun 10:12]</span></span>
A **ringed** [Topos](#7ee906fc-4e21-4965-a082-1e0ee87235c7) is a pair \\((T, \Lambda)\\), where \\(\Lambda\\) is a ring object in topos \\(T\\). A **morphism** between ringed topoi is a pair \\((f, f^{\shar})\\) consisting of a morphism of topoi \\(f: T \to T'\\) and a morphism of rings in \\(T'\\) \\(f^{\shar}: \Lambda' \to f\_{\*} \Lambda\\).


#### Point {#1feee86f-f818-4763-bcbf-7074b7927aa8}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-07 Sun 15:17]</span></span>
Let \\(\text{pt}\\) denote the [Topos](#7ee906fc-4e21-4965-a082-1e0ee87235c7) of sheaves on the one-point space. A **point** of the topos \\(T\\) is a morphism of topoi
\\[x: \text{pt} \to T\\]
We say that the topos \\(T\\) has **enough points** if there exists a set of points
\\[\\{x\_{i}: \text{pt} \to T\\}\\]
such that the induced functor
\\[T \to \cat{Set}^{I}, F \to \\{x\_{i}^{\*}F\\}\\]
is faithful.


### Toric ideal {#89e4ed03-df8b-4ee4-b4e9-86e036a0d301}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:05]</span></span>
A prime [Lattice ideal](#bca68ca1-b16a-4519-8d04-8903e4aa8912) is called **toric ideal**.

We have following criterion for toric ideal.

{{% proposition %}}
An ideal \\(I \subset \CC[x\_{1}, \cdots, x\_{s}]\\) is toric if and only if it is prime and generated by binomials.
{{% /proposition %}}

Referenced: [Affine toric variety](#fad44b6c-ee19-49dc-90e7-3f83dbb75678).


### <span class="org-todo todo TODO">TODO</span> Toric variety {#13b3e41c-f513-4c38-90ea-5063fde975cc}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:08]</span></span>
The toric variety is a field connecting algebraic geometry, combinatorial and mathematical physics. Our main reference is [<span id="56219725c40008d847a57904e2a7e775"><a href="#CLS2011" title="Cox, Little \&amp; Schenck, Toric Varieties, {American Mathematical Society} (2011).">CLS2011</a></span>].

Cf. [Affine toric variety](#fad44b6c-ee19-49dc-90e7-3f83dbb75678)

Referenced: [Non-normal toric variety](#8047b0a5-171f-4e4d-a598-b05e3fb06df7).


### Torsion filtration {#52989523-d3a0-4df2-85bb-e164ed65c076}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:30]</span></span>
The **torsion filtration** of a coherent sheaf \\(E\\) is the unique filtration
\\[0 \subset T\_{0}(E) \subset \cdots \subset T\_{d}(E) = E\\]
where \\(d = \dim(E)\\) and \\(T\_{i}(E)\\) is the maximal subsheaf of \\(E\\) of dimension \\(\geq i\\).


### Torsion free {#96c1a8d7-91ad-49b2-993b-a0e35938d2dd}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-08 Wed 20:52]</span></span>
A coherent sheaf \\(E\\) is called **torsion free** if for each \\(x \in X\\) and \\(s \in \OO\_{X,x} \backslash \\{0\\}\\) the multiplication by \\(s\\) induces a injective morphism \\(E\_{x} \to E\_{x}\\).


### Torsor {#4cf947bf-dc13-487c-8694-d31a12c3f96e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 20:39]</span></span>
Let \\(S\\) be a [Site](#d827cad0-92be-4251-9e34-4243334a9315) and \\(G\\) a sheaf of groups on \\(S\\). A \\(G\\)- **torsor** on \\(S\\) is a sheaf \\(P\\) of sets on \\(S\\) with left action \\(\sigma: G \times P \to P\\) of \\(G\\) such that

1.  For every object \\(X \in S\\), there exists a covering \\(\\{X\_{i} \to X\\}\\) such that \\(P(X\_{i}) \neq 0\\), and
2.  The action map \\((\sigma, p\_{2}): G \times P \to P \times P\\) is an isomorphism.


### Torus {#14c0a895-04a6-4976-bce3-2b511741dc32}

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

Referenced: [Affine toric variety](#fad44b6c-ee19-49dc-90e7-3f83dbb75678), [Character (of a torus)](#13bc02d5-1271-497c-ad8f-20f52be7d055), [Splitting torus](#33b4d7d0-3bd6-4548-9eb6-b3c2cf0780ba).


### Unramified {#400b9160-9c06-4df4-aa66-4caf328f86bd}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-28 Tue 20:41]</span></span>
See [Étale](#ed41498b-430c-485c-b0d3-1f26d531902a).


### Versal extension {#744a4c24-3412-4043-ba95-b20a711eff25}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 21:37]</span></span>
An \\(A\\)-[Extension](#e074be48-ee62-4fa6-b0bc-3de8fcc9a492) \\((P, f)\\) is called **versal** if for every other \\(A\\)-extensions \\((R', \phi)\\) of \\(R\\), there exists a homomorphism of extensions \\(r: (P, f) \to (R, \phi)\\). For example, for \\(R = P/I\\) where \\(P\\) a polynomial ring over \\(A\\),
\\[0 \to I/I^{2} \to P/I^{2} \to R \to 0\\]
is a versal \\(A\\)-extension of \\(R\\).

{{% remark %}}
The word versal is similar to universal and certainly has some similarities. However, I don't know which words come into math world first.
{{% /remark %}}


### Virasoro bracket {#bb1d2011-9d33-4cf1-b728-ea0181af047a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 21:32]</span></span>
**Virasoro bracket** is a set of commutator relation for operators \\(L\_{n}\\) such that
\\[[L\_{n}, L\_{m}] = (n - m) L\_{n + m}\\]

Referenced: [Virasoro constraint](#22a94486-fcc6-4ba9-a5c4-5e49c40517f4).


### <span class="org-todo todo TODO">TODO</span> Virtual fundamental class {#7d52eb53-34d5-4da6-80f4-7242956a1c44}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-01 Wed 16:57]</span></span>
The analog of [Fundamental class](#b4d8db93-4571-4034-a37d-bc5ebea10fea) for stacks and orbifold.

Referenced: [Donaldson-Thomas theory](#d99e0505-469d-469f-b47f-8fb5e04f57b7), [Moduli space of Stable Maps](#cee41211-6bef-4bb0-b5d7-52d6d0cab804).


### <span class="org-todo todo TODO">TODO</span> Yoneda product {#90a94aa3-9874-4118-a4a9-8f8e519d5607}


## Symplectic Geometry {#311efaf5-c800-4a25-b242-ef8c34bbf4c3}




### Liouville vector field {#8f4ab0d9-4b0e-484e-8acf-25f586eee8ed}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-02 Thu 10:51]</span></span>
Let \\((M, \omega)\\) is a [Symplectic manifold](#c127758e-3380-4bff-99e8-51d950df4d1c). A vector field \\(V: M \to TM\\) is **Liouville** if \\(L\_{X} \omega = \omega\\).
Cf. [Lie derivative](#b2603ad3-d6f7-4c64-80b1-b40282423325).

The existence of a Liouville vector field implies that \\((M, \omega)\\) is exact as the one-form \\(\lambda = i\_{V} \omega\\) satisfies that \\(\dif \lambda = \omega\\).

Referenced: [Weinstein manifold](#79df6949-cd16-45aa-bdd0-963c4a5e4b73).


### Symplectic manifold {#c127758e-3380-4bff-99e8-51d950df4d1c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-02 Thu 10:43]</span></span>
A **symplectic manifold** is a [smooth Manifold](#6ff3f589-8a3d-4903-b35a-fe10657823f2) \\(X\\) of even dimension \\(\dim X = 2n\\), equipped with a **symplectic form** a closed smooth \\(2\\)-form \\(\omega \in \Omega\_{cl}^{2}(X)\\) such that \\(\omega\\) is non-degenerate. That is \\(\omega^{n}\\) has the maximal rank at every point \\(p\\), or equivalently that \\((\wedge^{2} T\_{p}^{\* }X, \omega\_{p})\\) symplectic vector space for every \\(p\\).

Referenced: [Symplectic structure of Hilbert scheme](#9e6166a7-590b-44da-a207-f45f189df7c0), [Liouville vector field](#8f4ab0d9-4b0e-484e-8acf-25f586eee8ed), [Weinstein manifold](#79df6949-cd16-45aa-bdd0-963c4a5e4b73).


### Weinstein manifold {#79df6949-cd16-45aa-bdd0-963c4a5e4b73}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-02 Thu 10:42]</span></span>
A [Symplectic manifold](#c127758e-3380-4bff-99e8-51d950df4d1c) \\((M, \omega)\\) is **Weinstein** if it comes with a distinguished [Liouville vector field](#8f4ab0d9-4b0e-484e-8acf-25f586eee8ed) \\(Y\\), and a proper bounded below function \\(h: M \to \RR\\), such that \\(\dif h(Y)\\) is positive on a sequence of level set \\(h^{-1}(c\_{k})\\) with \\(\lim\_{k}c\_{k} = \infty\\).

A Weinstein manifold is called **of finite type** if \\(\dif h(Y) > 0\\) outside a compact subset of \\(M\\) and is called **complete** if the flow of \\(Y\\) is defined for all times.


## Geometric representation theory {#7f5a1efb-e09c-414a-858d-b0e65e83c4bc}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-29 Sun 15:26]</span></span>
In geometric representation theory, we tries to encode the algebra operation in geometric objects. The one of the general construction is the usage of correspondence, that is the cycles or sheaves etc in \\(X\_{1} \times X\_{2}\\). It is a nonlinear analog of matrices. To retain the linear information, we consider functors such as [Equivariant cohomology](#c6af30c7-f999-48d3-8c55-8776b454f38a) and [Equivariant K-theory](#b8cfa111-3c52-4bb3-8fbd-63d76b24916b).


### Langlands dual pair {#dcdc572d-35c5-425b-8436-99595ee16acb}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:39]</span></span>
The **Langlands dual** is a pair of [Algebraic groups](#e2cb9181-d20c-47cd-9f3b-757f9ad14ce1) \\((X, Y)\\) such that the root system of \\(X\\) is coroot of \\(Y\\) and vice versa. The center of \\(X\\) is the fundamental group of \\(Y\\) and vice versa.

For example \\((\Sp(n), \SO(2n + 1))\\), \\((\SO(2n), \SO(2n))\\) and \\((\SL(n), \PGL(n))\\).


### Steinberg variety {#6f0885bd-5fc9-4287-ab31-560a5be9365e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-29 Sun 15:41]</span></span>
For a general symplectic resolution
\\[\pi: X \to X\_{0}\\]
we have the **Steinerg variety** \\(X \times\_{X\_{0}} X\\).

Referenced: [Algebraic Geometry](#588b0321-5a8f-4710-a67a-2a34de657fde).


## Geometric Topology {#a1f3ce74-3431-4878-9dde-69fefea81bd1}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 18:20]</span></span>
Named geometric topology, this section includes some result in \\(4\\)-manifold and knot theory and higher dimensional topology.


### 11/8 conjecture {#11-8-conjecture}

By [Freedman's classification of topological 4-manifold](#2802aa4d-49a8-4b19-a3f8-8d2cd41c1ef0), [Rokhlin Theorem](#3b84058d-80f3-4933-bad7-b398b673b4e4) and [Donaldson diagonalizable theorem](#3cab4e7a-7b31-4295-8d83-bd812c1b7d1c), the only remaining case to determine the existence of smooth structure on topological \\(4\\)-manifold are those with \\(Q\_{X}\\) even and indefinite. That is \\(Q\_{X} = mE\_{8} \oplus n \begin{pmatrix} 0 & 1 \\\\ 1 & 0 \end{pmatrix}\\). Since we have K3 surface with \\(Q\_{X} = 2E\_{8} \oplus 3 \begin{pmatrix}0 & 1\\\\ 1 & 0 \end{pmatrix}\\) and \\(S^{2} \times S^{2}\\) with \\(Q\_{X} = \begin{pmatrix} 0 & 1\\\\ 1 & 0 \end{pmatrix}\\), we can show that the for \\(Q\_{X}\\) with \\(m = 2k\\) and \\(n \geq 3k\\) the smooth structure on the manifold exists. The conjecture is that that is the only possibility for the existence of smooth structure.

{{% conjecture %}}
If \\(X\\) is spin, smooth and \\(Q\_{X} = 2k E\_{8} \oplus n \begin{pmatrix} 0 & 1\\\\ 1 & 0 \end{pmatrix}\\), then \\(n \geq 3k\\). Or equivalently speaking \\(b\_{2}(X) \geq \frac{11}{8} \abs{\sigma(X)}\\).
{{% /conjecture %}}

A theorem by Furuta says

{{% theorem %}}
Let \\(X\\) be a spin \\(4\\)-manifold, such that \\(b\_{2}(X) \neq 0\\). Then
\\[b\_{2}(X) \geq \frac{10}{8} \abs{\sigma(X)} + 2\\]
{{% /theorem %}}

The [Seiberg-Witten invariant](#1f580179-efd8-4aa3-b57a-095b011d0e31) together with spin Dirac operator can give one proof. The proof suggests [Bauer-Furuta invariant](#cae1c370-1514-4238-ab54-c69df92268ed).

{{% remark %}}
The current status (2021 Sep.) of the conjecture is that \\(k \leq 1\\) case is proved. For \\(k > 1\\), we have
\\[n \geq 2k + \begin{cases} 2 & k = 1,2,5,6 \\\\ 3 & k = 3,4,7 \\\\ 4 & 0 \end{cases} \mod 8 \\]
{{% /remark %}}


### Affine braid group {#614b31f1-c7d7-4c72-9ea1-de75e30a62d0}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:56]</span></span>
We define the **affine braid group** to be
\\[\tilde{B\_{n}} = \langle s\_{1}, \cdots, s\_{n -1}, t\_{1}, \cdots, t\_{n}\rangle\\]
with the same condition as [Braid group](#3fd75bd7-4528-40df-b4ee-70f3675e2a36) with addition
\\[s\_{i}t\_{i + 1} = t\_{i} s\_{i}\\]


### <span class="org-todo todo TODO">TODO</span> Alexander duality {#a333dfee-1f6e-4f46-a4d6-fdd15a32bf55}


### <span class="org-todo todo TODO">TODO</span> Alexander polynomial {#d653d869-ce6d-4709-9603-6acd362bf411}



Referenced: [Fintushel-Stern knot surgery](#9336f7df-8b53-4594-9f87-f06ff4f75a63).


### Anti-self-dual {#6dc95247-d4be-4782-81bc-57079c5e86a6}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 20:21]</span></span>
A \\(n\\)-form \\(w\\) on \\(2n\\) manifold is called **self-dual** if \\(\* w = -w\\).
Cf. [Self-dual](#c5341509-3a47-4821-be72-f988460688f0).

Referenced: [Self-dual](#c5341509-3a47-4821-be72-f988460688f0).


### <span class="org-todo todo TODO">TODO</span> Bauer-Furuta invariant {#cae1c370-1514-4238-ab54-c69df92268ed}



Referenced: [Geometric Topology](#a1f3ce74-3431-4878-9dde-69fefea81bd1).


### Botany problem of 4-manifold {#ba30b9dc-eff4-4f1c-82c8-974f3ce280c7}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:52]</span></span>
For \\(b^{+} > 1\\), \\(\pi\_{1} = 1\\) irrducible case, by theorem of Fintushel-Stern, any such \\(X\\) admits \\(\infty\\) smooth structure.

For \\(b^{+} = 1\\), then \\(\CC P^{2} \shar n \overline{\CC P}^{2}\\) for \\(n \geq 2\\) has \\(\infty\\) smooth structure. \\(S^{2} \times S^{2}\\) and \\(n < 2\\) case is unknown.

\\(b^{+} = 0\\) case is completely unknown.

{{% remark %}}
In each case, we have no method to determine whether all the smooth structures have been found. That is if a manifold is known to have some smooth structure, we don't know whether they are all of the possible smooth structures.
{{% /remark %}}

{{% remark %}}
It is well known that \\(S^{7}\\) has 28 different differential structures. And those structures are only smooth structures possible. The proof requires [h-Cobordism](#6d89f833-721c-4d1d-894c-377510bdff68) theorem, so the similar methods can not be applied to \\(4\\)-manifold.
{{% /remark %}}


### Braid {#69dd0a70-00f7-4cc5-90aa-99f977df175d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:41]</span></span>
A **braid** is the isotopy class of a [Geometric braid](#ae0adc02-4f2d-4a87-81a7-5659d8761e26).

{{% theorem %}}
The braids are in bijection with Redemeister classes of diagrams.

{{< figure src="/img/2021-09-21_15-46-24_screenshot.png" >}}
{{% /theorem %}}

Referenced: [Pure](#a37c7629-2ef3-4267-a403-5b915e71c232), [Positive](#759f3418-ced8-4ac6-87e0-f6c082d05996), [Braid group](#3fd75bd7-4528-40df-b4ee-70f3675e2a36).


#### Pure {#a37c7629-2ef3-4267-a403-5b915e71c232}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:46]</span></span>
A [Braid](#69dd0a70-00f7-4cc5-90aa-99f977df175d) is called **pure** if it connects \\(\\{x\_{0}\\} \times \\{0\\}\\) to \\(\\{x\_{i}\\} \times \\{1\\}\\).

Referenced: [Braid group](#3fd75bd7-4528-40df-b4ee-70f3675e2a36).


#### Positive {#759f3418-ced8-4ac6-87e0-f6c082d05996}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:43]</span></span>
A [Braid](#69dd0a70-00f7-4cc5-90aa-99f977df175d) is called **positive** if it is a product of \\(\sigma\_{i}\\) and not \\(\sigma\_{i}^{-1}\\) in braid group. And a braid is **quasi-positive** if it has the form \\(\prod\_{k = 1}^{m} w\_{k} \sigma\_{ik} w\_{k}^{-1}\\) where \\(w\_{k}\\) is any word in the braid group. A [Knot](#a2bbd4aa-cc17-4042-b932-461a56e1cfce) **positive** (resp. **quasi-positive**) if it is a completion of a positive (resp. quasi-positive) braid.

Referenced: [Quasi-positive](#24566987-ceff-4d2e-8aad-1fb0f3fcea76), [Knots bounds algebraic surface](#bf2f3f16-3745-4ab4-b1d5-d65dcd982e62).


#### Quasi-positive {#24566987-ceff-4d2e-8aad-1fb0f3fcea76}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:44]</span></span>
See [Positive](#759f3418-ced8-4ac6-87e0-f6c082d05996).

Referenced: [Knots bounds algebraic surface](#bf2f3f16-3745-4ab4-b1d5-d65dcd982e62).


### Braid diagram {#362ccdc7-b389-49d5-8127-b269a28d6e0b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:42]</span></span>
Consider the projection \\(\pi: \RR^{2} \times [0,1] \to \RR \times [0,1]\\). Then \\(\hat{\beta}\\) is called **generic** if \\(\pi(\hat{\beta})\\) has simple transversal singular points outside of \\(\RR \times \\{0,1\\}\\). Such \\(\pi(\hat{\beta})\\) is called a **geometric braid diagram**.

A **braid diagram** is a regular isotopy class of a geometric braid diagram.


### Braid group {#3fd75bd7-4528-40df-b4ee-70f3675e2a36}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:44]</span></span>
The [Braids](#69dd0a70-00f7-4cc5-90aa-99f977df175d) form a group called **braid group** where the composition is given by glueing two embeddings. Obviously, the [Pure](#a37c7629-2ef3-4267-a403-5b915e71c232) braids form a subgroup of braid group. The braid group is denoted by \\(B\_{n}\\), and pure braid group by \\(P\_{n}\\).

{{% theorem %}}
\\(B\_{n}\\) is generated by elements

{{< figure src="/img/2021-09-21_15-49-51_screenshot.png" >}}

with defining relations
\\[s\_{i}s\_{i+1}s\_{i} = s\_{i + 1}s\_{i}s\_{i + 1},\\; i = 1, \cdots, n - 1\\]
\\[s\_{i}s\_{j} = s\_{j}s\_{i}, \\; \abs{i - j} > 1\\]
{{% /theorem %}}

The braid group can be realized as a [Fundamental group](#f2693b59-6cae-4cb7-85c4-d09e21ffe625) of a manifold. Define \\(C\_{n} = \\{x\_{1}, \cdots, x\_{n} \in \RR^{2} \mid x\_{i} \neq x\_{j}\\}\\). Then we have \\(\pi\_{1}(C\_{n}) = P\_{n}\\). By considering the \\(S\_{n}\\) action on \\(C\_{n}\\), we have that \\(B\_{n} = \pi\_{1}(C\_{n}/ S\_{n})\\).

Referenced: [Affine braid group](#614b31f1-c7d7-4c72-9ea1-de75e30a62d0), [Hecke-Iwahori algebra](#31ad6a45-68e6-4735-8b83-b56f276cbeb7), [Representation of braids](#12b6f0d3-f63f-4ee7-b65b-9d74c1052d77).


### Characteristic class for 4-manifold {#3f183207-72d8-4c9c-bd6d-1a95da5037f7}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-22 Wed 20:49]</span></span>
We may assume that \\(X\\) is a connected, closed, oriented, smooth \\(4\\)-manifold.
We have a [Signature](#df89e8ff-fa5e-4e37-a527-87778f8289c8) theorem by Hirzebruch.

{{% theorem %}}
\\[P\_{1}(TX)[X] = 3 \sigma(X)\\]
{{% /theorem %}}

Cf. [Pontryagin class](#3adc046c-671b-4a0b-813e-3cdc5d09df29).

And theorem by Wenjun Wu on [Stiefel-Whitney class](#d61db36f-39bd-4cb5-b041-4815fda86269).

{{% theorem %}}
1.  For all \\(\alpha \in H^{2}(X; \ZZ/2)\\), we have \\(w\_{2}(TX) \cup \alpha = \alpha \cup \alpha\\)
2.  \\(w\_{3}(TX) = \sq^{1}(w\_{2}(TX))\\), here \\(\sq^{1}\\) is the square operator.
{{% /theorem %}}

By above theorem, [Freedman's classification of topological 4-manifold](#2802aa4d-49a8-4b19-a3f8-8d2cd41c1ef0), [Donaldson diagonalizable theorem](#3cab4e7a-7b31-4295-8d83-bd812c1b7d1c) and algebraic classification of bilinear forms, we have

{{% proposition %}}
Let \\(X\\) be a smooth, closed \\(4\\)-manifold. Then homeomorphism type of \\(X\\) is determined by \\(e(TX), P\_{1}(TX)\\)and \\(w\_{2}(TX)\\).
{{% /proposition %}}

{{% remark %}}
However, characteristic class in dimension \\(4\\) cannot detect exotic phenomenon.
{{% /remark %}}


### Clasp number {#6aef8405-2cf0-42ab-a7b6-ccfcd45aee1e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:39]</span></span>
We define the **clasp number** of \\(K\\) to be minimal number of double points of the immersed disk in \\(D^{4}\\) with boundary \\(K\\) with only transverse double point.

We have \\(c\_{4}(k) \leq U(K)\\) ([Unknot number](#1349d31d-bf03-49b6-85a8-9dd3e0f39467)), for we can trade knot for double points. Also, we have \\(g\_{S}(K) \leq c\_{4}(K)\\) ([Slice genus](#28644ed9-6a26-4318-bc73-eb0a43982e1e)) since we can trade double points for genus.


### Clifford algebra {#1adbe0cc-79e4-4691-9883-c7c9520a72df}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:56]</span></span>
Let \\(H\\) be a real vector space. The tensor algebra \\(T(H)\\) modulo ideal generated by \\(\\{v \otimes v + \norm{v}^{2}\\}\\) is called the **Clifford algebra**.

Referenced: [Clifford module](#d6fed5dc-ffe7-467f-b780-d062de508bf3).


### Clifford module {#d6fed5dc-ffe7-467f-b780-d062de508bf3}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 20:00]</span></span>
A **Clifford module** of [Clifford algebra](#1adbe0cc-79e4-4691-9883-c7c9520a72df) over \\(H\\) is a Hermitian complex vector space \\(V\\) equipped with a **Clifford multiplication** \\(\gamma: H \to \End(V)\\) such that

-   If \\(\norm{e} = 1\\), then \\(\gamma(e)^{2} = -1\\).
-   If \\(e\_{1} \perp v\_{2}\\), then \\(\gamma(e\_{1}) \cdot \gamma(e\_{2}) + \gamma(e\_{2}) \cdot \gamma(e\_{1}) = 0\\).
-   \\(\gamma(e)^{\* } = - \gamma(e)\\).

That is a Clifford module is a representation of Clifford algebra.

The irreducible Clifford module is competely identified.

{{% theorem %}}
If \\(n = 2k\\), then there exists a unique finite dimensional irreducible Clifford module \\((S, \gamma)\\) up to isomoprhism and \\(\dim\_{\CC} S = 2^{k}\\).

If \\(n = 2k + 1\\), there are exactly two clifford modules \\((S, \gamma), (S, - \gamma)\\) up to isomoprhism and \\(\dim\_{\CC} S = 2^{k}\\).
{{% /theorem %}}

Referenced: [Dirac operator](#149cbd17-c12c-404d-a4a4-822f04f8c88a), [Spin^C structure](#14bb7bc5-aa5d-479e-a420-b1ab6ac0d3d1).


### Corbordism {#99cfb23d-9973-4c8c-976c-f9e526ad870e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-20 Sat 21:38]</span></span>
Let \\(\mathscr{C}\\) denote one of the following categories: smooth / topological / piecewise linear category. Let \\(M\_{0}, M\_{1}\\) be oriented \\(\mathscr{C}\\)-manifold. A **cobordism** \\(W\\) form \\(M\_{0}\\) to \\(M\_{1}\\) is a \\(n + 1\\) dimensional \\(\mathscr{C}\\)-manifold such that \\(\partial W = \bar{M\_{0}} \coprod M\_{1}\\).

We can define the **cobordism category** \\(\cat{Cob}\_{n}\\), where the objects are closed \\(n\\) dimensional manifolds and the morphisms are isotopic classes of cobordisms.

Referenced: [h-Cobordism](#6d89f833-721c-4d1d-894c-377510bdff68).


### <span class="org-todo todo TODO">TODO</span> Cork {#5adbf119-4ba2-49d1-950e-407ea389ea4b}


### Critical point {#c184e1ca-f49c-4c93-b9f6-672c9eb34fea}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 15:16]</span></span>
The **critical point** of \\(f: X \to \RR\\) is the map \\(\dif f\_{p}: T\_{p}X \to T\_{f(p)} \RR\\) is trivial. And \\(r = f(p)\\) is the **critical value**, otherwise \\(r\\) is called the **regular value**.

Cf. [Regular point](#3064e22a-123b-4f5e-9102-de7891d9bd32).

Referenced: [Non-degenerate](#964ab9d3-8f65-4af8-a38f-5db4faa15371), [Critical value](#372a87b7-a11c-46d4-bd9d-9b0b86b66ad1), [Morse inequality](#d7a97a15-5d7d-4f9b-8ebf-156467695c1d).


#### Non-degenerate {#964ab9d3-8f65-4af8-a38f-5db4faa15371}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 15:19]</span></span>
We say \\(p\\) [Critical point](#c184e1ca-f49c-4c93-b9f6-672c9eb34fea) **non-degenerate** if \\(\det({\rm Hess} f\_{p}) \neq q\\). The **index** of the \\(p\\) is the number of negative eigenvalues of [Hessian](#85697013-72df-48d1-bbe4-2daf274801f9) of \\(f\\) at \\(p\\).

Referenced: [Index](#259627c4-5422-462b-a3a8-f6c1e1d67084).


### Critical value {#372a87b7-a11c-46d4-bd9d-9b0b86b66ad1}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 15:18]</span></span>
See [Critical point](#c184e1ca-f49c-4c93-b9f6-672c9eb34fea).

Referenced: [Regular value](#9c4464b3-201a-4ab1-9444-d8928027ee23).


### Diagram {#3dd44557-fc38-4a13-85c3-0af1b962f5c2}

The image of a generic geometric representative \\(\hat{L}\\) of [Link](#79ab45e1-e6f4-4938-8bee-dae2f2e09daa) \\(L\\) from \\(\RR^{3}\\) to \\(\RR^{2}\\) is a **diagram** of \\(L\\).

For equivalent class of diagrams, we have the following theorem by Reidemeister.

{{% theorem %}}
Equivalence class of diagrams with respect to the local moves

{{< figure src="/img/2021-09-13_18-22-18_screenshot.png" >}}
{{% /theorem %}}

We can also consider the diagram of [Framed](#3cf59cde-321e-4ff1-a767-4d591bdbf57b) links in \\(\RR^{3}\\). And we have equivalence class of regular isotopy class of framed diagrams on \\(\RR^{2}\\) is given by

{{< figure src="/img/2021-09-13_18-30-56_test.png" >}}

Referenced: [Skein relations](#2d47c676-92cf-4f3c-9ae3-be5afba8a77f), [Unknot number](#1349d31d-bf03-49b6-85a8-9dd3e0f39467).


### Dirac operator {#149cbd17-c12c-404d-a4a4-822f04f8c88a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 20:05]</span></span>
Given a [Clifford module](#d6fed5dc-ffe7-467f-b780-d062de508bf3) \\(S\\) over \\(H\\), we define the **Dirac operator** \\(\dirac: C^{\infty}(H, S) \to C^{\infty}(H, S)\\) by
\\[\dirac \phi = \sum\_{i = 1}^{n} \gamma(e\_{i}) \cdot \frac{\partial \phi}{\partial e\_{i}}\\]

\\(\dirac\\) is a self-adjoint operator with \\(\dirac^{2} = \Delta\\).

On manifold, given a [Spin^C connection](#4bdbe70d-831d-4dc7-9065-1ee7cbda23e6) \\(A\\), we can also define the **Dirac operator**
\\[\dirac\_{A} = \rho \circ \nabla\_{A}: \Gamma(s) \to \Gamma(s)\\]
For decomposition \\(S = S^{+} \oplus S^{-}\\), we have \\(\dirac\_{A} = \dirac\_{A}^{ +} + \dirac\_{A}^{-} \\)\\(\dirac\_{A}^{ +}: \Gamma(S^{ +}) \to \Gamma(S^{-})\\) and \\(\dirac\_{A}^{-}: \Gamma(S^{-}) \to \Gamma(S^{ + })\\).

On manifolds, the Dirac operator is also self-adjoint. And we call \\(\dirac\_{A}^{2}\\) the **Dirac Laplacian**. We have
\\[\dirac\_{A}^{2} \phi = \Delta \phi + \rho(F\_{A^{\tau}}^{+ }) \phi + \frac{s}{4} \phi\\]
where \\(\Delta\\) is the usual Laplacian and \\(F\_{A^{\tau}}^{+}\\) is the [Self-dual](#c5341509-3a47-4821-be72-f988460688f0) part of curvature of the connection induced by \\(A\\) on \\(\det(S^{ +})\\)


### Donaldson diagonalizable theorem {#3cab4e7a-7b31-4295-8d83-bd812c1b7d1c}



{{% theorem %}}
Let \\(X\\) be a smooth \\(4\\)-manifold. Suppose \\(Q\_{X}\\) is definite that is the matrix \\(Q\_{X}\\) is postive or negative definite, we have \\(Q\_{X} \cong \pm \begin{pmatrix} 1 & \cdots & 0 \\\\ \vdots & \ddots & \vdots \\\\ 0 & \cdots & 1 \end{pmatrix} \\).
{{% /theorem %}}

Cf. [Intersection forms](#efde6529-9adb-401a-9a36-24b35eb28839).

One of the proofs is given by [Seiberg-Witten invariant](#1f580179-efd8-4aa3-b57a-095b011d0e31) and following algebra result.

{{% theorem %}}
Let \\(Q: \ZZ^{m} \otimes \ZZ^{m} \to \ZZ\\) be a negative definite, unimodular form and let \\(\Char(Q) = \\{v \in \ZZ^{m} \mid Q(v, w) \equiv Q(w,w) \pmod 2\\}\\). Suppose that \\(Q(v, v) + m \leq 0, \quad \forall v \in \Char(Q)\\). Then \\(Q \cong -I\\).
{{% /theorem %}}

Referenced: [Geometric Topology](#a1f3ce74-3431-4878-9dde-69fefea81bd1), [Characteristic class for 4-manifold](#3f183207-72d8-4c9c-bd6d-1a95da5037f7).


### <span class="org-todo todo TODO">TODO</span> Dot notation {#4ace5121-7b8f-47b3-ad5c-d4fa11de8fa1}


### Elliptic fibration {#0ecad10b-236b-4627-a5f7-29a27a1ccf90}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-25 Sat 18:31]</span></span>
A map \\(q: X \to \Sigma\\) is an **elliptic fibration** if there exists a finite set \\(S \subset \Sigma\\) such that \\(X \backslash q^{-1}(S) \to \Sigma \backslash S\\) is a fiber bundle whose fiber is a smooth curve of genus \\(1\\), that is the elliptic curve. We call \\(q^{-1}(t)\\) a **regular fiber** if \\(t \not \in S\\) and a **singular fiber** if \\(t \in S\\).

Cf. [Vector bundle](#3944a5f8-1a1f-4cd2-82a0-d373c52e8bcf).


### Exotic R^4 {#4978dcd4-b158-41ef-9605-9a9546d262bb}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 18:51]</span></span>
\\(\RR^{4}\\) has infinitely many smooth structures. While other Eucliean space has unique smooth structure by Stallings.

{{% theorem %}}
\\(\RR^{4}\\) has uncountably many smooth structures.
{{% /theorem %}}

The construction follows from the oberservation for \\(X = \CC P^{2} \shar 9 \overline{\CC P}^{2}\\), we have \\(Q\_{X} \cong (-E\_{8}) \oplus (-1) \oplus (1)\\). Then if all \\(\RR^{4}\\) has same smooth structure, some kind of surgery gives impossible \\(4\\)-manifolds. By examing the construction carefully, one shows that there exists a parameter such that every two construction gives different smooth structures.

Exotic \\(R^{4}\\) can also be constructed using [Knot](#a2bbd4aa-cc17-4042-b932-461a56e1cfce) theory.


### <span class="org-todo todo TODO">TODO</span> Exotic surfaces {#94f688c6-8c2d-4c3b-b778-c53ad280343f}


### <span class="org-todo todo TODO">TODO</span> Fintushel-Stern knot surgery {#9336f7df-8b53-4594-9f87-f06ff4f75a63}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 15:02]</span></span>
The following theorem by Fintushel-Stern gives many exotic smooth structures.

{{% theorem %}}
Suppose \\([T^{2}] \neq 0 \in H\_{2}(X ; \RR)\\), let \\(X\_{K}\\) be the knot surgery along \\(T^{2}\\). Then
\\[SW\_{X\_{K}} = SW\_{X} \cdot \Delta\_{K}(e^{2[T]^{2}})\\]
where \\(SW\_{X} = \sum\_{v \in \Char(X)} SW\_{X}(v) e^{v}\\) and \\(\Delta\\) is the [Alexander polynomial](#d653d869-ce6d-4709-9603-6acd362bf411)
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
The conjecture is related to the open question, given \\(K, L\\) with \\(\Delta\_{K} = \Delta\_{L}\\) can \\(X\_{K} \not \cong\_{diff} X\_{L}\\). Since there exists many knots with same Alexander polynomial, the question is important. However, we don't have any tool to detect smooth structure other than [Seiberg-Witten invariant](#1f580179-efd8-4aa3-b57a-095b011d0e31).
{{% /remark %}}


### Framed {#2dc48843-eedf-4deb-b573-eaa3ddaf1f19}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 16:01]</span></span>
See [Framing](#3cf59cde-321e-4ff1-a767-4d591bdbf57b).

Referenced: [Jones-Markov trace](#b2dbc6ea-c15c-45ef-8411-7e1e8b1988fa).


### Framing {#3cf59cde-321e-4ff1-a767-4d591bdbf57b}

**Framing** of a [Link](#79ab45e1-e6f4-4938-8bee-dae2f2e09daa) in \\(\RR^{3}\\) is an isotopy class of a continuous section of a normal bundle to \\(L \subset \RR^{3}\\).

Referenced: [Diagram](#3dd44557-fc38-4a13-85c3-0af1b962f5c2), [Framed](#2dc48843-eedf-4deb-b573-eaa3ddaf1f19).


### Freedman's classification of topological 4-manifold {#2802aa4d-49a8-4b19-a3f8-8d2cd41c1ef0}



{{% theorem %}}
1.  Let \\(X\_{0}, X\_{1}\\) be two simply connected topological \\(4\\)-manifolds. Then \\(X\_{0} \cong\_{top} X\_{1} \Leftrightarrow Q\_{X\_{0}} \cong Q\_{X\_{1}}, \ks(X\_{0}) = \ks(X\_{1})\\).
2.  Given any unimodular, symmetric bilinear form \\(Q\\). Then
    1.  Suppose \\(Q\\) is odd, i.e. there exists \\(v\\) such that \\(Q(v,v)\\) is odd, then any combination of \\((Q, i)\\) where \\(i \in \\{0,1\\}\\) can be realized as the intersection form and KS invariant of some simply connected topological \\(4\\)-manifold \\(X\\).
    2.  Suppose \\(Q\\) is even, i.e. for every \\(v\\), \\(Q(v,v)\\) is even. Then \\((Q, i)\\) can be realized if and only if \\(i \equiv \frac{\sigma(Q)}{8} \mod 2\\).
{{% /theorem %}}

Cf. [Manifold](#6ff3f589-8a3d-4903-b35a-fe10657823f2), [Kirby-Sieberman invariant](#3477afca-5e6b-4702-996b-ed087b03591d), [Whitehead theorem](#8f012fb9-53b3-4589-a2ab-c9da1c856e3f), [Intersection forms](#efde6529-9adb-401a-9a36-24b35eb28839), [Signature](#df89e8ff-fa5e-4e37-a527-87778f8289c8).

By Freedman's result, the Chern number \\(c(X) = 2 \chi(X) + 3 \sigma(X)\\), and [Holomorphic Euler number](#3e2b8be9-4f26-48d2-ad39-82a323bee911) \\(\chi\_{h}\\) and \\(t(X) = \begin{cases} 0 & Q\_{X} \text{ is even.} \\\ 1 & Q\_{X} \text{ is odd.} \end{cases}\\).

Referenced: [Geometric Topology](#a1f3ce74-3431-4878-9dde-69fefea81bd1), [Characteristic class for 4-manifold](#3f183207-72d8-4c9c-bd6d-1a95da5037f7), [Geography of 4-manifold](#41023816-636a-41f4-bce3-f7de83a301ed).


### Gabai's lightbulb theorem {#7c1e0ff2-ce3c-4f65-bac7-255e1b5c6926}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-14 Sun 15:13]</span></span>
Given \\(F \hookrightarrow X\\), we say an embedded sphere \\(\Sigma \hookrightarrow X\\) is a **geometric dual** of \\(F\\) if \\(\Sigma \cdot \Sigma = 0\\) and \\(F \pitchfork \Sigma = \\{pt\\}\\). And \\(F\\) is **\\(\Sigma\\)-essential** if \\(\pi\_{1}(F \backslash \Sigma) \to \pi\_{1}(X \backslash \Sigma)\\) is trivial. The **Gabai's lightbulb theorem** states

{{% theorem %}}
1.  Given any \\(S^{2} \hookrightarrow S^{2} \times S^{2}\\) with \\(S^{2} \pitchfork (\* \times S^{2}) = \\{pt\\}\\). Then \\(S^{2} \cong\_{diff} S^{2} \times \\{\*\\}\\).
2.  Given any \\(F\_{1}, F\_{2} \hookrightarrow X\\) with \\(\pi\_{1}(X)\\) no \\(2\\)-torsion. Suppose there exists a common geometric dual for \\(F\_{i}\\) and \\(F\_{1}, F\_{2}\\) both \\(\Sigma\\)-essential. Then \\(F\_{1} \cong\_{diff} F\_{2}\\).
{{% /theorem %}}


### Geography of 4-manifold {#41023816-636a-41f4-bce3-f7de83a301ed}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:33]</span></span>
By [Freedman's classification of topological 4-manifold](#2802aa4d-49a8-4b19-a3f8-8d2cd41c1ef0), the **geography of \\(4\\)-manifold** is the question which triple \\((c, \chi\_{h}, t)\\) can be realized as smooth, [Irreducible](#eec97100-b390-47cb-8768-29c21b1cac23), simply connected \\(X\\).

The following conjecture relates the irreduciblity of \\(4\\)-manifold and [Holomorphic Euler number](#3e2b8be9-4f26-48d2-ad39-82a323bee911).

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


### Geometric braid {#ae0adc02-4f2d-4a87-81a7-5659d8761e26}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:38]</span></span>
A **geometric braid** in \\(\RR^{2} \times [0,1]\\) is an embedding \\(\hat{\beta} : [0,1]^{\coprod n} \to \RR^{2} \times [0,1]\\) connecting \\(\\{x\_{0}, \cdots, x\_{n}\\} \times \\{0\\}\\) and \\(\\{x\_{0}, \cdots, x\_{n}\\} \times \\{1\\}\\) componentwise.

Referenced: [Braid](#69dd0a70-00f7-4cc5-90aa-99f977df175d).


### Geometric tangle {#b0ae7c12-ba48-4401-ba46-076e478857ef}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 18:02]</span></span>
A **geometric tangle** is an embedding of \\([0, 1]^{\coprod k} \coprod (S^{1})^{\coprod m}\\) into \\(\RR^{2} \times [0,1]\\) such that images of endpoints of intervals are on \\(\RR^{2} \times \\{0\\}\\) and \\(\RR^{2} \times \\{1\\}\\), intersection of intervals is transversal to the planes and images of cirvles are strictly inside of \\(\RR^{2} \times [0,1]\\).

A **based tangle** is the regular isotopy class, preserving boundary points of a geometric tangle. And a **standardized tangle** is a based tangle with endpoints being in a line \\(\RR \subset \RR^{2}\\).


### <span class="org-todo todo TODO">TODO</span> Handle decomposition {#21f95029-6093-4cc3-a654-78f20d574450}



Referenced: [Monotone](#798b377b-41b2-4df5-b5b5-459129c8559d), [Handle move](#795b07f0-b932-4b45-b20f-875133965b5e), [Morse complex](#b53e361b-16ae-4bfa-b1b7-1cad82d42d11), [Morse theory](#48b444e3-17e1-4953-8031-285d67a8d9be).


#### Monotone {#798b377b-41b2-4df5-b5b5-459129c8559d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 15:49]</span></span>
A [Handle decomposition](#21f95029-6093-4cc3-a654-78f20d574450) \\(X\_{0}| \cdots | X\_{k}\\) is called **monotone** if \\(X\_{i}\\) only consists of \\(i\\)-handles for all \\(i\\).

{{% proposition %}}
Any manifold has a monotone handle decomposition.
{{% /proposition %}}

{{% corollary %}}
Every manifold has a self-indexed Morse function.
{{% /corollary %}}

Cf. [Self-indexed](#c163e006-49df-4558-83a7-911204dd0a7e) [Morse function](#b7d93405-e9b4-4594-b46c-d8a6f54d5a3d).

Referenced: [Handle move](#795b07f0-b932-4b45-b20f-875133965b5e), [Morse complex](#b53e361b-16ae-4bfa-b1b7-1cad82d42d11).


### <span class="org-todo todo TODO">TODO</span> Handle move {#795b07f0-b932-4b45-b20f-875133965b5e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 16:44]</span></span>
Any two [Monotone](#798b377b-41b2-4df5-b5b5-459129c8559d) [Handle decomposition](#21f95029-6093-4cc3-a654-78f20d574450) of \\(X\\) are related by the following handle moves

-   handle slide
-   creation / cancellation


### h-Cobordism {#6d89f833-721c-4d1d-894c-377510bdff68}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 18:42]</span></span>
With the same notation as in [Corbordism](#99cfb23d-9973-4c8c-976c-f9e526ad870e), we say that \\(W\\) is **h-cobordism** if \\(M\_{0} \hookrightarrow W\\) and \\(M\_{1} \hookrightarrow M\\) are all homotopy equivalences.

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

Referenced: [Botany problem of 4-manifold](#ba30b9dc-eff4-4f1c-82c8-974f3ce280c7), [Poincarè conjecutre](#18e765e4-13ae-4fb4-b065-3c000466688b), [Wall Theorem](#5ea26322-29fc-4e24-a614-791b3372e6bf).


### Hecke-Iwahori algebra {#31ad6a45-68e6-4735-8b83-b56f276cbeb7}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:53]</span></span>
For [Braid group](#3fd75bd7-4528-40df-b4ee-70f3675e2a36) \\(B\_{n}\\), the elements \\((s\_{i} - q)(s\_{i} + q^{-1})\\) generates an ideal in the group algebra \\(\CC[B\_{n}]\\). The **Hecke-Iwahori algebra** is the quotient algebra with respect to the ideal, i.e.,
\\[H\_{n}(q) = \langle s\_{1}, \cdots, s\_{n} \rangle\\]
such that
\\[s\_{i}s\_{i+1}s\_{i} = s\_{i + 1}s\_{i}s\_{i + 1},\\; i = 1, \cdots, n - 1\\]
\\[s\_{i}s\_{j} = s\_{j}s\_{i}, \\; \abs{i - j} > 1\\]
\\[(s\_{i} - q)(s\_{i} + q^{-1}) = 0\\]
The interesting case is that \\(q\\) be the root of \\(1\\).

\\(H\_{n}(q)\\) is a deformation of \\(\CC[S\_{n}]\\).


### Heegaard diagram {#cbbfa591-ea7b-49f0-b3a2-e7819b3df253}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:03]</span></span>
A genus \\(g\\) **Heegaard diagram** is \\((\Sigma\_{g}, \alpha\_{1}, \cdots, \alpha\_{g}, \beta\_{1}, \cdots, \beta\_{g})\\) consists of a genus \\(g\\) [Orientable](#e44cd985-169e-4233-984b-fe33f201c39a) surface \\(\Sigma\_{g}\\), two families of simple closed curves \\(\alpha\_{\* }\\), \\(\beta\_{\* }\\) such that \\(\alpha\_{i} \cap \alpha\_{j} = \beta\_{i} \cap \beta\_{j} = 0 \\) for \\(i \neq j\\) and \\(\Sigma\_{g} - \coprod \alpha\_{i}, \Sigma\_{g} - \coprod \beta\_{i}\\) are both connected.

Cf. [Heegaard splitting](#94c5706c-ef02-4306-85c1-6fc327ec6303).

Referenced: [Trisection diagram](#ee030b29-0c69-4683-8878-36801db39d06).


### Heegaard splitting {#94c5706c-ef02-4306-85c1-6fc327ec6303}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:03]</span></span>
A genus \\(g\\) **Heegaard splitting** of \\(3\\)-manifold is a decomposition of \\(Y\\) into two genus \\(g\\) handle bodies.

Referenced: [Heegaard diagram](#cbbfa591-ea7b-49f0-b3a2-e7819b3df253).


### Hessian {#85697013-72df-48d1-bbe4-2daf274801f9}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 15:21]</span></span>
The **Hessian** is the well-defined map \\({\rm Hess} f\_{p}: T\_{p}X \otimes T\_{p}X \to \RR\\) defined by \\(\left(\frac{\partial^{2}f}{\partial x\_{i} \partial x\_{j}}\right)\\).

Referenced: [Non-degenerate](#964ab9d3-8f65-4af8-a38f-5db4faa15371).


### Holomorphic Euler number {#3e2b8be9-4f26-48d2-ad39-82a323bee911}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:26]</span></span>
We define the **holomorphic Euler number** by \\(\chi\_{h}(X) = \frac{\chi(X) + \sigma(X)}{4}\\).

Referenced: [Freedman's classification of topological 4-manifold](#2802aa4d-49a8-4b19-a3f8-8d2cd41c1ef0), [Geography of 4-manifold](#41023816-636a-41f4-bce3-f7de83a301ed).


### HOMFLY invariant {#e629d166-9aba-401a-ae0e-e627ca85e84f}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 18:37]</span></span>
Since [Skein relations](#2d47c676-92cf-4f3c-9ae3-be5afba8a77f) are compatible with Reidemeister moves, for every [Link](#79ab45e1-e6f4-4938-8bee-dae2f2e09daa), we may consider its diagram \\(D\_{L}\\) and we define \\([D\_{L}] = \langle L \rangle [O]\\). Here \\(O\\) is one loop and \\(\langle L \rangle \in \ZZ[A, B^{\pm 1}, C]\\). \\(\langle L \rangle\\) depends only on \\(L\\) but not on representative diagram \\(D\_{L}\\). \\(\langle L \rangle\\) is the **HOMFLY** invariant of framed links.

For unframed links, we also have **HOMFLY invariants** by consider \\(L = L\_{1} \coprod \cdots \coprod L\_{n}\\) as framed links and consider \\(\langle \langle L \rangle \rangle = B^{- \sum\_{i} w(L\_{i})} \langle L \rangle\\) where \\(w(L\_{i})\\) is the winding number.


### Homotopic slice {#59eda827-39de-4a44-9ec9-9a0f28a08755}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-05 Sun 17:34]</span></span>
A [Knot](#a2bbd4aa-cc17-4042-b932-461a56e1cfce) \\(K \subset S^{3}\\) is called **homotopy slice** if \\(K\\) bounds a smooth \\(i:D^{2} \hookrightarrow X\\) with \\(\partial X = S^{3}\\) such that \\(i\\) is homotopic to \\(i': D^{2} \to \partial X\\) relative to \\(\partial D^{2} = K\\).

Kronheimer and Mrowka has the following conjecture.

{{% conjecture %}}
\\(K\\) is homotopy slice then the Rasmuusen invariant \\(s(K) = 0\\).
{{% /conjecture %}}

Cf. [Rasmussen invariant](#6a51437f-a420-4d2a-bd10-875a5b2c9d4c).

The above conjecture is proved for \\(X = \CC P^{2}\\).


### Index {#259627c4-5422-462b-a3a8-f6c1e1d67084}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 15:54]</span></span>
See [Non-degenerate](#964ab9d3-8f65-4af8-a38f-5db4faa15371).

Referenced: [Morse inequality](#d7a97a15-5d7d-4f9b-8ebf-156467695c1d).


### Integer homology 3-sphere {#365edc60-5f78-42bb-a010-fcaa0b69b644}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:05]</span></span>
The **integer homology 3-sphere** is a \\(3\\)-manifold \\(Y\\) with \\(H\_{1}(Y; \ZZ) = 0\\).

Freedman proved following result.

{{% theorem %}}
Any integer homology \\(3\\)-sphere bounds a contractible topological \\(4\\)-manifold.
{{% /theorem %}}

Cf. [Contractible](#ededb2d9-23e9-4438-9632-d497708cffdf).


### Intersection forms {#efde6529-9adb-401a-9a36-24b35eb28839}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-17 Fri 21:48]</span></span>
For \\(4\\)-manifold, we have nondegenerated bilinear form
\\[Q\_{X}: H^{2}(X; \ZZ)/(tors) \times H^{2}(X; \ZZ)/(tors) \to \ZZ\\]
defined by \\((\alpha \cup \beta)[X]\\) called **intersection form**. It is a symmetric, unimodular form.

As an example of the intersection form, we have the intersection form of K3 surfaces \\(Q\_{X} = 2E\_{8} \oplus 3 \begin{pmatrix} 0 & 1 \\\\ 1 & 0 \end{pmatrix}\\)

Cf. [K3 surfaces](#a02155e5-899f-436d-8cc6-8d32d597550f), [E8](#348fde9d-d126-4d6e-800f-52d0ae832313).

We can generalized above intersection form to manifold with boundary. The interesection form is defined on \\(V = \im(H\_{2}(X) \to H\_{2}(X, \partial X))/(torsion)\\). \\(Q\_{X}(i\_{\* }(\alpha), i\_{\* }(\beta)) = (\pd(\alpha) \cap \pd(\beta)) \cdot [X]\\).

For a manifold with boundary, the intersection form is still nondegenerate but not necessarily unimodular. In fact, we have the following proposition

{{% proposition %}}
Given any symmetric \\(Q\\) with \\(\det(Q) \neq 0\\), there exists a simply connected \\(4\\)-manifold \\(X\\) such that \\(Q\_{X} = Q\\) and \\(\abs{\det(Q)} = \abs{H\_{1}(\partial X)}\\).
{{% /proposition %}}

Referenced: [Lefschetz fixed point theorem](#a8f5a758-c8fc-4a7f-af5c-37191d0ebdb3), [Donaldson diagonalizable theorem](#3cab4e7a-7b31-4295-8d83-bd812c1b7d1c), [Freedman's classification of topological 4-manifold](#2802aa4d-49a8-4b19-a3f8-8d2cd41c1ef0), [Signature](#df89e8ff-fa5e-4e37-a527-87778f8289c8).


### Irreducible {#eec97100-b390-47cb-8768-29c21b1cac23}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:22]</span></span>
A simply connected, closed, oriented \\(4\\)-manifold \\(X\\) is **irreducible** if \\(X \not \cong\_{diff} X\_{0} \shar X\_{1}\\) with \\(X\_{0}, X\_{1} \not \cong S^{4}\\).

Referenced: [Geography of 4-manifold](#41023816-636a-41f4-bce3-f7de83a301ed), [Seiberg-Witten invariant](#1f580179-efd8-4aa3-b57a-095b011d0e31).


### Jones-Markov trace {#b2dbc6ea-c15c-45ef-8411-7e1e8b1988fa}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 15:58]</span></span>
There exists a **Jones-Markov** trace \\(\tr: \tilde{B}\_{n} \to k = \ZZ[q, q^{-1}][\frac{1}{(q - q^{-1})}]\\) such that
\\[\tr(\beta \gamma \beta^{-1}) = \tr(\gamma)\\]
\\[\tr(\beta s\_{n}) = \tr(\beta t\_{n}) = z \tr(\beta)\\]

It defines invariants of [Framed](#2dc48843-eedf-4deb-b573-eaa3ddaf1f19) [Links](#79ab45e1-e6f4-4938-8bee-dae2f2e09daa). To get a invariant of links, we consider [Writhe number](#d6f99d19-a8b6-4740-8a64-2a14f809bfa2), \\(\omega(\beta)\\). We have \\(\tr(\beta)z^{w(\beta)}\\) is an invarinat of links.

{{% remark %}}
For \\(z = q^{2}\\) the polynomial is the [Jones polynomial](#a115770e-52a5-4ed9-9b00-af23c5a7b98a).
{{% /remark %}}


### <span class="org-todo todo TODO">TODO</span> Jones polynomial {#a115770e-52a5-4ed9-9b00-af23c5a7b98a}



Referenced: [Jones-Markov trace](#b2dbc6ea-c15c-45ef-8411-7e1e8b1988fa).


### <span class="org-todo todo TODO">TODO</span> Jones polynomial {#dc859102-e190-4435-a8fa-d6e89519f543}


### Jones twist {#2da1839e-6897-4604-bd4c-58e2d63f2e5b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 16:15]</span></span>
A map \\(\mu: V \to V\\) is called **Jones twist** if
\\[(\mu \otimes \mu) R = R(\mu \otimes \mu)\\]
\\[(\id \otimes \tr)(\id \otimes \mu) PR = z \id\_{V}\\]


### <span class="org-todo todo TODO">TODO</span> Khovanov homology {#24d13849-0af1-4589-93b4-77cf4f953fc3}



Referenced: [Lee homology](#f89b4db4-45f9-47bf-99d7-0c3fd40d1d1a).


### <span class="org-todo todo TODO">TODO</span> Kirby calculus {#15327667-0f3c-4d06-aecc-d485b7d69a43}


### <span class="org-todo todo TODO">TODO</span> Kirby move {#80e157ab-011d-4b0d-9ca8-a9abc9e5a70b}


### Kirby-Sieberman invariant {#3477afca-5e6b-4702-996b-ed087b03591d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-17 Fri 22:00]</span></span>
We define the set \\({\rm Top}\_{m} = \\{\text{ homomorphism } f: \RR^{m} \to \RR^{m} \text{ such that } f(0) = 0\\}\\). And \\({\rm PL}\_{m} = \\{\text{ piecewise linear homeomorphism} f: \RR^{m} \to \RR^{m} \text{ such that } f(0) = 0\\}\\).

The Kirby and Sieberman has following deep and mysterious theorem.

{{% theorem %}}
For \\(m \geq 5\\), \\(k < m\\). Then \\(\pi\_{k}({\rm Top}\_{m}/ {\rm PL}\_{m}) = \begin{cases} 0 & k \neq 3 \\\\ \ZZ/2 & k = 3 \end{cases}\\).
{{% /theorem %}}

So to have PL structure on \\(X\\), \\(\dim X \geq 5\\) we need to overcome the obstruction called **Kirby-Sieberman** invariant \\(KS(X) \in H^{4}(X; \ZZ/2)\\). So \\(X\\) has a PL-structure then \\(\ks(X) = 0\\). And for \\(\dim X = 4\\), \\(\ks(X) = 0\\) if and only \\(X \times \RR\\) has a PL-structure.

{{% remark %}}
For \\(\dim X \leq 7\\), we have existence of piecewise linear structure equivalent to existence of smooth structure.
{{% /remark %}}

Referenced: [Freedman's classification of topological 4-manifold](#2802aa4d-49a8-4b19-a3f8-8d2cd41c1ef0).


### <span class="org-todo todo TODO">TODO</span> Knizhnik–Zamolodchikov equation {#161a6e88-3d2a-4eb5-a2c8-e4fd562a0a6f}


### Knot {#a2bbd4aa-cc17-4042-b932-461a56e1cfce}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 18:13]</span></span>
A **knot** (in \\(S^{3}\\)) is an isotopy class of an [Immersion](#5d4eeff2-f095-48c8-958b-4ab8f00bfd60) \\(\hat{K}: S^{1} \to S^{3}\\), \\(K = [\hat{K}]\\).

Referenced: [Positive](#759f3418-ced8-4ac6-87e0-f6c082d05996), [Link](#79ab45e1-e6f4-4938-8bee-dae2f2e09daa), [Homotopic slice](#59eda827-39de-4a44-9ec9-9a0f28a08755), [Knots bounds algebraic surface](#bf2f3f16-3745-4ab4-b1d5-d65dcd982e62), [Linking number](#69e445f3-bc07-47b7-9dc6-528113074bae), [Poincarè conjecutre](#18e765e4-13ae-4fb4-b065-3c000466688b), [Unknot number](#1349d31d-bf03-49b6-85a8-9dd3e0f39467).


### Knots bounds algebraic surface {#bf2f3f16-3745-4ab4-b1d5-d65dcd982e62}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:45]</span></span>
By [Seiberg-Witten invariant](#1f580179-efd8-4aa3-b57a-095b011d0e31), it is natural to ask when a [Knot](#a2bbd4aa-cc17-4042-b932-461a56e1cfce) bounds an algebraic surface. The answer is the following theorem.

{{% theorem %}}
A knot \\(K\\) arises as \\(K = S \pitchfork \partial D^{4}\\) for some affine algebraic curve \\(S \subset \CC^{2}\\) if and only if \\(K\\) is quasi-positive. Moreover, suppose \\(K = \bar{b}\\), where
\\[b = \prod\_{k = 1}^{m} w\_{k} \sigma\_{i\_{k}} w^{-1}\_{k}\\]
Then we can find \\(S\\) with \\(g(S \cap D^{4}) = \frac{m - n + 1}{2}\\), and therefore \\(g\_{S}(K) = \frac{m - n + 1}{2}\\).
{{% /theorem %}}

Cf. [Quasi-positive](#24566987-ceff-4d2e-8aad-1fb0f3fcea76), [Slice genus](#28644ed9-6a26-4318-bc73-eb0a43982e1e).

For [Positive](#759f3418-ced8-4ac6-87e0-f6c082d05996) knot, we have \\(U\_{K} = g\_{S}(K)\\) which is not true for quasi-positive knot.


### <span class="org-todo todo TODO">TODO</span> Lee homology {#f89b4db4-45f9-47bf-99d7-0c3fd40d1d1a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:33]</span></span>
Cf. [Khovanov homology](#24d13849-0af1-4589-93b4-77cf4f953fc3).

Referenced: [Rasmussen invariant](#6a51437f-a420-4d2a-bd10-875a5b2c9d4c).


### Lefschetz hyperplane theorem {#b4c1796b-4880-4388-a0a3-968ed82415e7}



{{% theorem %}}
Let \\(X\\) be a hypersurface in \\(\CC \PP^{n}\\) defined by a single polynomial, then \\(X \to \CC P^{n}\\) induces isomorphism on \\(\pi\_{k}(-)\\) if \\(k < n - 1\\).
{{% /theorem %}}

{{% corollary %}}
The hypersurface in \\(\CC P^{3}\\) is simply connected.
{{% /corollary %}}


### Lickorish-Wallace theorem {#b32c82ec-4f25-4180-bce6-8f926be285d6}



{{% theorem %}}
Every closed orientable connected \\(3\\)-manifold can be obtained from a surgery on a link with coefficient \\(\pm 1\\).
{{% /theorem %}}

Cf. [Link](#79ab45e1-e6f4-4938-8bee-dae2f2e09daa), [Orientation](#0d1fefb5-7409-4540-8afb-5b3c67e90acd), [Surgery](#ffcb5951-6b3e-4410-bc1e-3b25ce358857).


### Link {#79ab45e1-e6f4-4938-8bee-dae2f2e09daa}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-13 Mon 18:13]</span></span>
A **link** is an isotopy class of an [Immersion](#5d4eeff2-f095-48c8-958b-4ab8f00bfd60) \\(\hat{L}: (S^{1})^{\times K} \to S^{3}\\), \\(L = \hat{L}\\).

Cf. [Knot](#a2bbd4aa-cc17-4042-b932-461a56e1cfce).

Referenced: [Diagram](#3dd44557-fc38-4a13-85c3-0af1b962f5c2), [Framing](#3cf59cde-321e-4ff1-a767-4d591bdbf57b), [HOMFLY invariant](#e629d166-9aba-401a-ae0e-e627ca85e84f), [Jones-Markov trace](#b2dbc6ea-c15c-45ef-8411-7e1e8b1988fa), [Skein relations](#2d47c676-92cf-4f3c-9ae3-be5afba8a77f), [Lickorish-Wallace theorem](#b32c82ec-4f25-4180-bce6-8f926be285d6), [Seifert surface](#809daf6c-a15d-4286-b29c-9b782695d32b).


### Linking number {#69e445f3-bc07-47b7-9dc6-528113074bae}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 13:41]</span></span>
Let \\(K\_{1}, K\_{2}\\) be [Oriented](#6ee87df9-81b1-461d-ba2a-4917799f1c5c) [Knots](#a2bbd4aa-cc17-4042-b932-461a56e1cfce) in \\(S^{3}\\). We define the **linking number** \\(lK(K\_{1}, K\_{2}) \in \ZZ\\) by
\\[[K\_{2}] = lK(K\_{1}, K\_{2})[m\_{1}] \in H\_{1}(S^{3} \backslash K\_{1}) \cong \ZZ\\]
where \\(m\_{1}\\) is the meridian of \\(K\_{1}\\). The following is a sketch graph of meridian.

{{< figure src="/img/2021-10-08_13-43-37_screenshot.png" >}}

An alternative definition is consider \\(\Sigma\_{1}\\) [Seifert surface](#809daf6c-a15d-4286-b29c-9b782695d32b) of \\(K\_{1}\\) and then define \\(lK(K\_{1}, K\_{2}) = \Sigma\_{2} \cdot K\_{1}\\). Or we consider embeddings \\(\Sigma\_{1} \to D^{4}\\), \\(\Sigma\_{2} \to D^{4}\\) such that \\(\partial \Sigma\_{1} = K\_{1}\\), \\(\partial \Sigma\_{2} = K\_{2}\\) and define \\(lK(K\_{1}, K\_{2}) = K\_{1} \cdot K\_{2}\\).


### <span class="org-todo todo TODO">TODO</span> Mazur manifold {#b3bdb3e3-282e-4199-8331-67be37812ec8}


### Milnor conjecture (theorem) {#9fbd067c-35d4-40b7-9b87-19a3591422de}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:24]</span></span>
The **Milnor conjecture** is the following. (now a theorem)

{{% theorem %}}
For \\(T\_{p,q}\\) the \\((p,q)\\)-torus knot, we have
\\[g\_{S}(T\_{p,q}) = \frac{(p - 1)(q - 1)}{2}\\]
{{% /theorem %}}

One can use [local Thom conjecture (theorem)](#c188176a-8535-46a3-b3b7-37041e4c336f) to prove.


### Morse complex {#b53e361b-16ae-4bfa-b1b7-1cad82d42d11}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 16:38]</span></span>
Now we consider the complex constructed from Morse theory. We have \\(X = X\_{0} | X\_{1} | \cdots | X\_{n}\\) [Monotone](#798b377b-41b2-4df5-b5b5-459129c8559d). And for \\(H\_{k} \subset X\_{k}\\) and \\(H\_{k + 1} \subset X\_{k + 1}\\), we define the pairing \\(\langle H\_{k}, H\_{k + 1}\rangle\\) the intersection number of the belt sphere of \\(H\_{k}\\) and attaching sphere of \\(H\_{k + 1}\\). Then we have **Morse complex** \\(C\_{k}^{n}(X) = \ZZ \langle H\_{k}^{1}, \cdots, H\_{k}^{a\_{k}}\rangle\\) and define the differential to be
\\[\dif H\_{k}^{i} = \sum\_{j} \langle H\_{k - 1}^{j}, H\_{k}^{i}\rangle H\_{k - 1}^{j}\\]
We have that \\(\dif^{2} = 0\\).

Cf. [Handle decomposition](#21f95029-6093-4cc3-a654-78f20d574450).

Referenced: [Morse inequality](#d7a97a15-5d7d-4f9b-8ebf-156467695c1d).


### Morse function {#b7d93405-e9b4-4594-b46c-d8a6f54d5a3d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 15:39]</span></span>
A **Morse function** is a funciton if all critical points are non-degenerate. If the origin manifold \\(X\\) has boundary, then \\(f^{-1}(\max f) = \partial X\\).

Referenced: [Monotone](#798b377b-41b2-4df5-b5b5-459129c8559d), [Self-indexed](#c163e006-49df-4558-83a7-911204dd0a7e).


#### Self-indexed {#c163e006-49df-4558-83a7-911204dd0a7e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 15:54]</span></span>
A [Morse function](#b7d93405-e9b4-4594-b46c-d8a6f54d5a3d) is called **self-indexed** if for all \\(x \in {\rm crit}(f)\\), we have \\(f(x) = {\rm index}(x)\\).

Referenced: [Monotone](#798b377b-41b2-4df5-b5b5-459129c8559d).


### Morse inequality {#d7a97a15-5d7d-4f9b-8ebf-156467695c1d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 16:41]</span></span>
From [Morse complex](#b53e361b-16ae-4bfa-b1b7-1cad82d42d11), we have that

{{% theorem %}}
For any \\(0 \leq k \leq  \dim(X)\\), we have that
\\[\sum\_{0 \leq i \leq k}(-1)^{k - i}b\_{i}(X) \leq \sum\_{0 \leq i \leq k} (-1)^{k - i} \abs{{\rm crit}\_{i}(f)}\\]
{{% /theorem %}}

{{% corollary %}}
Suppose all critical points of \\(f\\) have even indices, then \\(b\_{2k}(X) = \abs{{\rm crit}\_{2k}(f)}\\).
{{% /corollary %}}

Cf. [Critical point](#c184e1ca-f49c-4c93-b9f6-672c9eb34fea), [Index](#259627c4-5422-462b-a3a8-f6c1e1d67084).


### Morse theory {#48b444e3-17e1-4953-8031-285d67a8d9be}

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
\begin{align} k(x) = x && x \in X \\\\ k(tu) = 2tu && 0 \leq t \leq 1/2 \\\\ k(tu) = \phi\_{2-2t}(u) && 1/2 \leq t \leq 1 \end{align}
{{% /proof %}}

{{% lemma %}}
Let \\(\phi:\dot{e^{\lambda}} \to X\\) be an attaching map. Any homotopy
equivalence \\(f:X \to Y\\) extends to a homotopy equivalence \\(F:X \cup\_{\phi}e^{\lambda} \to Y \cup\_{f\phi}e^{\lambda}\\)
{{% /lemma %}}

Given a Morse function, we have a [Handle decomposition](#21f95029-6093-4cc3-a654-78f20d574450).

{{% theorem %}}
Suppose \\(f^{-1}( r) \cap {\rm crit}(f) = \\{x\_{1}, \cdots, x\_{l}\\}\\). Let \\(a\_{i} = {\rm index}(x\_{i})\\). Then for \\(\epsilon > 0\\) small enough, we have
\\[X\_{\leq r + \epsilon} = X\_{\leq r - \epsilon} \cup (H\_{a\_{1}} \coprod H\_{a\_{2}}) \cdots \coprod H\_{a\_{l}}\\]
where \\(H\_{i}\\) is the \\(i\\)-handle.
{{% /theorem %}}


### Poincarè conjecutre {#18e765e4-13ae-4fb4-b065-3c000466688b}



We have following **generalized Poincarè conjecture** which is proved by various people in various dimensions.

{{% theorem %}}
Let \\(M\\) be a \\(n\\)-dimensional topological manifold homootpy equivalent to \\(S^{n}\\). Then \\(M \cong\_{top} S^{n}\\).
{{% /theorem %}}

For \\(n \geq 6\\), we can give a proof by [h-Cobordism](#6d89f833-721c-4d1d-894c-377510bdff68).

However, the smooth structure on \\(S^{n}\\) may not be unique. \\(S^{2k + 1}\\) has unique smooth structure if and only if \\(2k + 1 = 1,3,5,61\\).

The dimension \\(4\\) smooth Poincaré conjecture is still open. A possible approach is suggested by Freedman-Gompf-Morrison-Walker using [Knot](#a2bbd4aa-cc17-4042-b932-461a56e1cfce) on \\(S^{4}\\) to do some surgery and making contradiction.


### <span class="org-todo todo TODO">TODO</span> Rasmussen invariant {#6a51437f-a420-4d2a-bd10-875a5b2c9d4c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:33]</span></span>
Cf. [Lee homology](#f89b4db4-45f9-47bf-99d7-0c3fd40d1d1a).

Referenced: [Homotopic slice](#59eda827-39de-4a44-9ec9-9a0f28a08755), [Slice genus](#28644ed9-6a26-4318-bc73-eb0a43982e1e).


### <span class="org-todo todo TODO">TODO</span> Rational blow down {#1d4a6dc0-a93c-44c5-b148-3c562d2cb4ab}


### Realization of Finite Presnetation Group as Fundamental Group of Manifolds {#769e86ad-e3db-40c5-bbad-921ffa76406e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-15 Wed 18:20]</span></span>
We have following theorem by Markov, showing that any finite presentation group can be realized as a fundamental group of a manifold.

{{% theorem %}}
Given any presentation of a group \\(G = \langle g\_{1}, \cdots, g\_{m} \mid r\_{1}, \cdots, r\_{m}\rangle\\), one can construct a \\(n\\)-dim \\(n \geq 4\\) manifold \\(M\\) with \\(\pi\_{1}(M) = G\\).
{{% /theorem %}}

Together with the following theorem of Adyan-Rubin, we show that a complete classification of high dimensional manifold is impossible.

{{% theorem %}}
There does not exist an algorithm that tells whether a given presentation yields the trivial group.
{{% /theorem %}}


### Regular value {#9c4464b3-201a-4ab1-9444-d8928027ee23}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-30 Thu 15:18]</span></span>
See [Critical value](#372a87b7-a11c-46d4-bd9d-9b0b86b66ad1).


### Representation of braids {#12b6f0d3-f63f-4ee7-b65b-9d74c1052d77}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 16:10]</span></span>
The following proposition relates the representation of [Braid group](#3fd75bd7-4528-40df-b4ee-70f3675e2a36) to [Yang-Baxter equation](#b636a0ca-d367-4cec-9c58-a8232b1df370).

{{% proposition %}}
If \\(R\\) satisfies the Yang-Baxter equation, the mapping
\\[\rho: B\_{n} \to \aut(V^{\otimes n})\\]
\\[\rho(s\_{i}) = 1 \otimes \cdots \otimes PR \otimes \cdots \otimes 1\\]
where \\(P(x \otimes y) = y \otimes 1\\) extends uniquely to a representation of \\(B\_{n}\\) in \\(V^{\otimes n}\\).
{{% /proposition %}}


### Rokhlin Theorem {#3b84058d-80f3-4933-bad7-b398b673b4e4}



{{% theorem %}}
Let \\(X\\) be a smooth spin \\(4\\)-[Manifold](#6ff3f589-8a3d-4903-b35a-fe10657823f2). Then \\(16 | \sigma(X)\\).
{{% /theorem %}}

Cf. [Signature](#df89e8ff-fa5e-4e37-a527-87778f8289c8).

Referenced: [Geometric Topology](#a1f3ce74-3431-4878-9dde-69fefea81bd1).


### Seiberg-Witten equation {#886bba89-0ed8-464c-99bf-d4f572f927be}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-23 Sat 15:28]</span></span>
The **Seiberg-Witten equation** is the following equations for \\((A, \phi \in \Gamma^{S^{+}})\\)
\\[ \begin{cases}      F\_{A^{\tau}}^{+} - \rho^{-1}(\phi^{\*} \phi)\_{0} = 0 & \\\\      \dirac\_{A}^{+} \phi = 0 &    \end{cases} \\]
Here \\((\phi^{\* } \phi)\_{0}: \psi \to \langle \psi, \phi> \cdot \phi - \frac{\abs{\phi}^{2}}{2} \psi\\). We have \\(((\phi^{\* } \phi)\_{0})^{\* } = (\phi^{\* } \phi)\_{0}\\) and \\(\tr (\phi^{\* } \phi)\_{0} = 0\\).

Referenced: [Seiberg-Witten moduli space](#a2c62a24-c1bc-4034-a148-fbabaeb141a1).


### Seiberg-Witten invariant {#1f580179-efd8-4aa3-b57a-095b011d0e31}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-23 Sat 15:51]</span></span>
For simply connected \\(4\\)-manifold \\(X\\), we have a natural \\(S^{1}\\) bundle \\(P\\) on [Seiberg-Witten moduli space](#a2c62a24-c1bc-4034-a148-fbabaeb141a1) \\(\mathscr{M}\_{SW}\\) coming from the Coulomb guage description. So we define the **Seiberg-Witten invariant** by
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

Cf. [Irreducible](#eec97100-b390-47cb-8768-29c21b1cac23).

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

Referenced: [Geometric Topology](#a1f3ce74-3431-4878-9dde-69fefea81bd1), [Donaldson diagonalizable theorem](#3cab4e7a-7b31-4295-8d83-bd812c1b7d1c), [Fintushel-Stern knot surgery](#9336f7df-8b53-4594-9f87-f06ff4f75a63), [Knots bounds algebraic surface](#bf2f3f16-3745-4ab4-b1d5-d65dcd982e62), [Thom conjecture (theorem)](#c188176a-8535-46a3-b3b7-37041e4c336f).


### Seiberg-Witten moduli space {#a2c62a24-c1bc-4034-a148-fbabaeb141a1}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-23 Sat 15:35]</span></span>
By [Seiberg-Witten equation](#886bba89-0ed8-464c-99bf-d4f572f927be), the solution forms **Seiberg-Witten moduli space**,
\\[\mathscr{M}\_{SW} = \\{\text{Seiberg-Witten solutions}\\}/ \mathscr{G}\\]
where \\(\mathscr{G} = \Gamma(X, \End(S^{+}, \rho)) = C^{\infty}(X, U(1))\\) acts on \\(\\{(A, \phi)\\}\\) by \\(u \cdot (A, \phi) = (A - u^{-1} \dif u, u \cdot \phi)\\).

Or we can formulate in another way by fixed the **Coulomb gauge** with respect ot a base [Spin^C connection](#4bdbe70d-831d-4dc7-9065-1ee7cbda23e6) \\(A\_{0}\\) by setting \\(\dif^{\* }(A - A\_{0}) = 0\\).
\\[\mathscr{M}\_{SW} = \\{\text{Coulomb gauge Seiberg-Witten solutions}\\}/ \mathscr{G}\_{h}\\]
where \\(\mathscr{G}\_{h} = \\{\text{harmonic map }X \to S^{1}\\} \cong H^{1}(X; \ZZ) \times S^{1}\\).

The following result is important and <span class="underline">magic</span> by Clifford Taubes.

{{% theorem %}}
\\(\mathscr{M}\_{SW}\\) is compact.
{{% /theorem %}}

The proof relies on the estimate of the \\(\abs{\phi}\\) and elliptic boosting technique for elliptic partial differential equations.

However, in general the moduli space is not a manifold, but in \\(b^{+ }\_{2} > 0\\) case, by perturbing the equation a little, we can get an [Oriented](#6ee87df9-81b1-461d-ba2a-4917799f1c5c) manifold of dimension \\(\frac{c\_{1}(S)^{2} - \sigma(X)}{4} + b^{1}(X) - b\_{2}^{+}(X)\\). The result depend on Sard-Smale theorem which is an analog of [Sard theorem](#40a40b3c-6891-4a94-ad55-17507129aaef) in infinite dimensional case. For \\(b^{ +} > 1\\), all such moduli space is equivalent, but in \\(b\_{2}^{ +} = 1\\) case, we have \\(2\\) choices.

Referenced: [Seiberg-Witten invariant](#1f580179-efd8-4aa3-b57a-095b011d0e31).


### Seifert genus {#745368a1-16c3-4e08-be74-ab5376133388}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 13:37]</span></span>
See [Seifert surface](#809daf6c-a15d-4286-b29c-9b782695d32b).

Referenced: [Thom conjecture (theorem)](#c188176a-8535-46a3-b3b7-37041e4c336f).


### Seifert surface {#809daf6c-a15d-4286-b29c-9b782695d32b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 13:35]</span></span>
For any [Oriented](#6ee87df9-81b1-461d-ba2a-4917799f1c5c) [Link](#79ab45e1-e6f4-4938-8bee-dae2f2e09daa) \\(L \to S^{3}\\), there exists an embedded orientable surface \\(\Sigma \to S^{3}\\) with \\(\partial \Sigma = L\\). Such surface is called **Seifert surface**.

The **Seifert genus** \\(g(K)\\) is the minimal genus of Seifert surface. The **slice genus** \\(g\_{S}(K)\\) is the minimal genus of orientable \\(\Sigma \to D^{4}\\) with \\(\partial \Sigma = K\\).

Obviously, we have \\(g\_{S}(K) \leq g(K)\\).

Referenced: [Linking number](#69e445f3-bc07-47b7-9dc6-528113074bae), [Seifert genus](#745368a1-16c3-4e08-be74-ab5376133388), [Slice genus](#28644ed9-6a26-4318-bc73-eb0a43982e1e).


### Self-dual {#c5341509-3a47-4821-be72-f988460688f0}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 20:21]</span></span>
A \\(n\\)-form \\(w\\) on \\(2n\\) manifold is called **self-dual** if \\(\* w = w\\).

Any \\(n\\)-form can be decomposed to a sum of self-dual part and [Anti-self-dual](#6dc95247-d4be-4782-81bc-57079c5e86a6) part.

Referenced: [Anti-self-dual](#6dc95247-d4be-4782-81bc-57079c5e86a6), [Dirac operator](#149cbd17-c12c-404d-a4a4-822f04f8c88a).


### Signature {#df89e8ff-fa5e-4e37-a527-87778f8289c8}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-17 Fri 21:50]</span></span>
For [Intersection forms](#efde6529-9adb-401a-9a36-24b35eb28839) \\(Q\_{X}\\), we have \\(b^{+ }(X)/b^{- }(X)\\) denote the number of the positive and negative eigenvalues of \\(Q\_{X}\\). And we define the **signature** to be \\(\sigma(X) = b^{+ }(X) - b\_{2}^{-}(X)\\).

Referenced: [Characteristic class for 4-manifold](#3f183207-72d8-4c9c-bd6d-1a95da5037f7), [Freedman's classification of topological 4-manifold](#2802aa4d-49a8-4b19-a3f8-8d2cd41c1ef0), [Rokhlin Theorem](#3b84058d-80f3-4933-bad7-b398b673b4e4).


### Skein relations {#2d47c676-92cf-4f3c-9ae3-be5afba8a77f}

We now consider a vector space \\(V\\) of formal \\(\ZZ\\) linear combinations of [Diagrams](#3dd44557-fc38-4a13-85c3-0af1b962f5c2) of [Links](#79ab45e1-e6f4-4938-8bee-dae2f2e09daa) modulo Reidemeister moves. The **Skein relations** are defined by

![](/img/2021-09-13_18-34-45_2021-09-13_18-33.png)
where \\(A, B, C\\) are formal variables and \\(B\\) is invertible. We have
\\[C = \frac{B - B^{-1}}{A}\\]

Also, we Skein is related to Reidemeister moves.

{{% theorem %}}
Skein relations are compatible with Reidemeister moves.
{{% /theorem %}}

Referenced: [HOMFLY invariant](#e629d166-9aba-401a-ae0e-e627ca85e84f).


### Slice genus {#28644ed9-6a26-4318-bc73-eb0a43982e1e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-08 Fri 13:40]</span></span>
See [Seifert surface](#809daf6c-a15d-4286-b29c-9b782695d32b).

The slice genus is bounded below by [Rasmussen invariant](#6a51437f-a420-4d2a-bd10-875a5b2c9d4c).

Referenced: [Clasp number](#6aef8405-2cf0-42ab-a7b6-ccfcd45aee1e), [Knots bounds algebraic surface](#bf2f3f16-3745-4ab4-b1d5-d65dcd982e62), [Slice ribbon conjecture](#84f2f5f8-9669-46fe-b22b-acfb6db67f91).


### Slice ribbon conjecture {#84f2f5f8-9669-46fe-b22b-acfb6db67f91}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:33]</span></span>
We say a knot \\(K\\) is **slice** if \\(g\_{S}(K) = 0\\) ([Slice genus](#28644ed9-6a26-4318-bc73-eb0a43982e1e)). And say \\(K\\) is **ribbon** if \\(K\\) bounds immersed \\(D^{2} \subset S^{3}\\) such that self intersection of \\(D^{2} = \coprod \text{arcs}\\). We know that ribbon is a slice, the conjecture is the converse also holds.

{{% conjecture %}}
Any slice knot is ribbon.
{{% /conjecture %}}


### Smale conjecture {#5f8be3f4-739d-4f96-bc85-ba832e6d2a49}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-05 Sun 17:34]</span></span>
The **Smale conjecture** for dimension \\(n\\) means

{{% conjecture %}}
The map \\(O(n + 1) \to {\rm Diff}(S^{n})\\) is homotopy equivalence.
{{% /conjecture %}}

The conjecture is true for \\(n \leq 3\\) and false for \\(n \geq 4\\). The last case \\(n = 4\\) was proved in around 2018.


### Spin^C connection {#4bdbe70d-831d-4dc7-9065-1ee7cbda23e6}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-23 Sat 15:15]</span></span>
A **unitary** connection \\(A\\) on \\(S\\) is **spin\\(^{\CC}\\) connection** if
\\[\nabla\_{A}(\rho(v) \cdot s) = \rho(v) \cdot \nabla\_{A} s + \rho(\nabla\_{LC} v) \cdot s\\]
for every \\(v \in \Gamma(T\_{\* }X), s \in \Gamma(s)\\). Here \\(\nabla\_{LC}\\) is the Levi-Civita connection which relies on [Riemannian metric](#8d4fbb99-6c1f-4044-b8c1-cd819ca319c4).

Referenced: [Dirac operator](#149cbd17-c12c-404d-a4a4-822f04f8c88a), [Seiberg-Witten moduli space](#a2c62a24-c1bc-4034-a148-fbabaeb141a1).


### Spin^C structure {#14bb7bc5-aa5d-479e-a420-b1ab6ac0d3d1}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 20:16]</span></span>
A **Spin\\(^{\CC}\\) structure** on \\(X\\) is a Hermitian bundle \\(S \to X\\) with bundle map \\(\rho: T\_{\* }X \to \End(S)\\) such that for all \\(x\\), \\(\rho\_{x}: T\_{x}X \to \End(S\_{x})\\) is an irreducible [Clifford module](#d6fed5dc-ffe7-467f-b780-d062de508bf3). Consider \\(\pi = \rho(e\_{1} \cdots e\_{n})\\), we have \\(\pi^{2} = -1\\). So \\(S = S^{+} \oplus S^{-}\\) by \\(\pi\\) action.

Spin\\(^{\CC}\\) structure is useful in \\(4\\)-manifold by following theorem.

{{% theorem %}}
Any \\(4\\)-manifold has a spin\\(^{\CC}\\) structure.
{{% /theorem %}}

which result from the following proposition

{{% proposition %}}
A \\(n\\)-dimensional manifold \\(X\\) has a spin\\(^{\CC}\\) structure if and only if \\(w\_{2}(TX) \in \im(H^{2}(X; \ZZ) \to H^{2}(X; \ZZ/2))\\).
{{% /proposition %}}

Cf. [Stiefel-Whitney class](#d61db36f-39bd-4cb5-b041-4815fda86269).


### Spin structure {#052bd0fe-98ab-4cab-b13e-f8f73f653f65}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-17 Fri 22:16]</span></span>
Let \\(\SO(n) \to {\rm Fr} \to X\\) be the frame bundle of a smooth [Manifold](#6ff3f589-8a3d-4903-b35a-fe10657823f2). A **spin structure** is a lift of \\({\rm Fr}\\) to a \\(\Spin(n)\\) bundle.

We have following lemma on the existence of spin structure.

{{% lemma %}}
\\(X\\) has a spin strucutre if and only if the second Stiefel-Whitney class \\(\omega\_{2}(X) = 0\\). Furthermore, when \\(\dim X = 4\\) and \\(\pi\_{1} = 1\\), \\(X\\) has a spin structure if and only if \\(Q\_{X}\\) is even.
{{% /lemma %}}


### <span class="org-todo todo TODO">TODO</span> Surgery {#ffcb5951-6b3e-4410-bc1e-3b25ce358857}



Referenced: [Lickorish-Wallace theorem](#b32c82ec-4f25-4180-bce6-8f926be285d6).


### Tangle {#b65b8f24-1481-49cf-8744-e046b3560975}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 18:02]</span></span>
A **tangle** is the regular isotopy class of a standardized [Tangle](#b65b8f24-1481-49cf-8744-e046b3560975) with respect to deformation of endpoints.

Referenced: [Tangle](#b65b8f24-1481-49cf-8744-e046b3560975).


### Thom conjecture (theorem) {#c188176a-8535-46a3-b3b7-37041e4c336f}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:24]</span></span>
The **Thom conjecture** is the following, now a theorem.

{{% theorem %}}
For \\(X = \CC P^{2}\\) and \\(d > 0\\), we have
\\[\min \\{g(\Sigma) \mid \Sigma \hookrightarrow X, [\Sigma] = d \pd (\CC P^{1})\\} = \frac{(d - 1)(d - 2)}{2}\\]
{{% /theorem %}}

Cf. [Seiberg-Witten invariant](#1f580179-efd8-4aa3-b57a-095b011d0e31), [Seifert genus](#745368a1-16c3-4e08-be74-ab5376133388).

The following corolloary called **local Thom conjecture** is useful.

{{% corollary %}}
Let \\(\Sigma \hookrightarrow \CC^{2}\\) be an affine, smooth algebraic curve. Then \\(\Sigma\\) is locally genus miminizing, that is, for all \\(D^{4} \in \CC^{2}, S \hookrightarrow D^{4}\\) such that \\(\partial D^{4} \pitchfork \Sigma = K\\) and \\(\partial S = K\\), we have \\(g(S) \geq g(\Sigma \cap D^{4})\\).
{{% /corollary %}}

Referenced: [Milnor conjecture (theorem)](#9fbd067c-35d4-40b7-9b87-19a3591422de).


### Trisection {#6d38dc99-1d83-452b-8782-93a7d735e476}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:03]</span></span>
Let \\(X\\) be a closed smooth [Oriented](#6ee87df9-81b1-461d-ba2a-4917799f1c5c) connected \\(4\\)-manifold. For \\(0 \leq k \leq g\\), a \\((g, K)\\)- **trisection** of \\(X\\) is a decomposition \\(X = X\_{1} \cap X\_{2} \cap X\_{3}\\) such that

1.  \\(X\_{i} \cong\_{diff} \shar^{k}(S^{1} \times B^{3})\\)
2.  \\((X\_{i} \cap X\_{j}) = H\_{ij} \cong\_{diff} \shar^{g}(S^{1} \times B^{2})\\)
3.  \\(X\_{1} \cap X\_{2} \cap X\_{3} = \Sigma\_{g}\\)

The following theorem of Gay and Kirby shows that trisection exists for any [Orientable](#e44cd985-169e-4233-984b-fe33f201c39a) \\(4\\)-manifold and unique in some sense.

{{% theorem %}}
1.  Every closed smooth connected oriented \\(4\\)-manifold admits a trisection.
2.  Any two trisection diagrams of \\(X^{4}\\) are related by a sequence of particular moves.
{{% /theorem %}}


### Trisection diagram {#ee030b29-0c69-4683-8878-36801db39d06}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-15 Fri 19:03]</span></span>
A **trisection diagram** is a set of three curves \\(\\{\alpha\_{i}\\}, \\{\beta\_{i}\\}, \\{\gamma\_{i}\\}\\) on \\(\Sigma\_{g}\\) with \\(1 \leq i \leq g\\) such that any two collection is a [Heegaard diagram](#cbbfa591-ea7b-49f0-b3a2-e7819b3df253) for \\(\shar^{k}(S^{1} \times S^{2})\\).


### Unknot number {#1349d31d-bf03-49b6-85a8-9dd3e0f39467}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-04 Thu 18:38]</span></span>
Given a [Knot](#a2bbd4aa-cc17-4042-b932-461a56e1cfce) \\(K\\), we define the **unknotting number** \\(U(K)\\) the minimal number that a knot [Diagram](#3dd44557-fc38-4a13-85c3-0af1b962f5c2) of \\(K\\) can be made into an unknot.

Referenced: [Clasp number](#6aef8405-2cf0-42ab-a7b6-ccfcd45aee1e).


### Wall Theorem {#5ea26322-29fc-4e24-a614-791b3372e6bf}



{{% theorem %}}
Let \\(M\_{0}, M\_{1}\\) be simply-connected smooth \\(4\\)-manifold. Suppose \\(M\_{0} \cong\_{homotopy} M\_{1}\\). Then

1.  \\(M\_{0}\\) is smoothly h-cobordant to \\(M\_{1}\\).
2.  For \\(m \geq 0\\), \\(M\_{0} \shar^{m} (S^{2} \times S^{2}) \cong\_{diff} M\_{1} \shar^{m} (S^{2} \times S^{2})\\).
{{% /theorem %}}

{{% remark %}}
All known example show that \\(m = 1\\) is already enough but the proves requires large enough \\(m\\). Is the theorem not strong enough, or our understanding of 4-manifold too shallow?
{{% /remark %}}

{{% remark %}}
The theorem also shows that [h-Cobordism](#6d89f833-721c-4d1d-894c-377510bdff68) theorem fails for \\(n = 4\\).
{{% /remark %}}


### Whitehead theorem {#8f012fb9-53b3-4589-a2ab-c9da1c856e3f}

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

Referenced: [Freedman's classification of topological 4-manifold](#2802aa4d-49a8-4b19-a3f8-8d2cd41c1ef0).


### Writhe number {#d6f99d19-a8b6-4740-8a64-2a14f809bfa2}

<span class="timestamp-wrapper"><span class="timestamp">[2021-09-21 Tue 16:02]</span></span>
We define the **Writhe number** of \\(\beta\\) to be

{{< figure src="/img/2021-09-21_16-02-43_screenshot.png" >}}

Referenced: [Jones-Markov trace](#b2dbc6ea-c15c-45ef-8411-7e1e8b1988fa).


### Yang-Baxter equation {#b636a0ca-d367-4cec-9c58-a8232b1df370}



{{% definition %}}
A morphism \\(R: V \otimes V \to V \otimes V\\) satisfies the **Yang-Baxter equation** if
\\[R\_{12}R\_{13}R\_{23} = R\_{23}R\_{13}R\_{12} \in \End(V^{\otimes 3})\\]
where \\(R\_{12} = R \otimes 1\\) and so on.
{{% /definition %}}

An solution is given by
\\[R(e\_{i} \otimes e\_{j}) =  \begin{cases}     q e\_{i} \otimes e\_{i} & i = j \\\\     e\_{i} \otimes e\_{j} & i < j \\\\     e\_{i} \otimes e\_{j} + (q - q^{-1})e\_{j} \otimes e\_{i} & i > j   \end{cases} \\]

Referenced: [Representation of braids](#12b6f0d3-f63f-4ee7-b65b-9d74c1052d77).


## Quantum Fields and Strings {#a068136a-5b6c-4c06-98b7-1d2993ade51b}




### <span class="org-todo todo TODO">TODO</span> Cobordism conjecture {#49d86345-9879-4fa1-b6b5-4ace5d8a57a8}


### <span class="org-todo todo TODO">TODO</span> Extended topological quantum field theory {#276f6234-b6b3-4cd5-bc04-2dec7583573f}


### Super algebra {#7596fc96-8fd2-436f-8f14-c37b8c12d4fd}



A **super algebra** over \\(k\\) is a [Super vector space](#0b0e4d47-4f67-4c1d-8496-2cc178b9199a) \\(A\\), with a given morphism \\(A \otimes A \to A\\). \\(A\\) is **associative** if \\((xy)z = x(yz)\\). A **unit** is an even element \\(1\\) such that \\(1 x = x 1 = x\\). \\(A\\) is **commutative** if
\\[xy = (-1)^{p(x)p(y)}yx\\]
for homogeneous elements.

We can define the **module** for algebra \\(A\\). And we make left module right module by
\\[m \cdot a := (-1)^{p(m)p(a)} a \cdot m\\]

We also have **opposite algebra** \\(A^{o}\\) of \\(A\\) by product
\\[x \cdot\_{opp} y = (-1)^{p(x)p(y)}y \cdot x\\]

We can define the tensor product of modules and algebras naturely.


### Super vector space {#0b0e4d47-4f67-4c1d-8496-2cc178b9199a}



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

Referenced: [Super algebra](#7596fc96-8fd2-436f-8f14-c37b8c12d4fd).


### <span class="org-todo todo TODO">TODO</span> Topological quantum field theory {#31e33521-6ec8-48f5-a246-16e77fa976fa}


### Chern-Weil theory {#0e51cc95-a929-4206-a89e-e8ab2cccb88f}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-13 Mon 19:06]</span></span>
See [Chern class](#eb44905d-a0cb-44e0-ae41-7555ca7a984b).


### Chern-Simons functional {#c2fc5887-cc16-4136-a985-735cd4be83b6}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-13 Mon 19:50]</span></span>
For \\(A\\) a connection on \\(SU(2)\\) principal bundle on manifold \\(M\\). We usually denote
\\[CS(A) = \frac{1}{8 \pi^{2}}\int\_{M} \tr(F\_{A} \wedge F\_{A}) \in \RR/\ZZ\\]
called **Chern-Simons functional**, where \\(F\_{A}\\) is the [Curvature](#24adfd2f-8b92-4a12-b729-bb04f2935e6d).

Or on 3-manifold, we define for [Connection](#025c9171-e761-4861-bf05-42aa59e9b55b) \\(A\\) (matrix valued 1 form),
\\[CS(A) = \frac{1}{8 \pi^{2}} \int\_{Y} \tr(A \wedge \dif A + \frac{2}{3}A \wedge A \wedge A) \in \RR/\ZZ\\]

Critical poiont of Chern-Simons functional are [Flat](#a3db89cb-badf-413a-b10e-39f1e02e34d0) connections and corresponds to group homomorphism \\(\rho: \pi\_{1}(M) \to SU(2)\\).


### Yang-Mills equation {#25c9c7d8-734a-474a-a2db-121be06ccb4e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-13 Mon 20:05]</span></span>
Let \\(P\\) be a \\(SU(2)\\) bundle over \\(4\\)-manifold \\(M\\), then we call
\\[F\_{A}^{+} = 0\\]
**Anti-self-dual equation**. The connection satisfying the equation minimizing energy equaiton **Yang-Mills functional**
\\[YM(A) = \int\_{M} \abs{F\_{A}}^{2}\\]
Critical point of Yang-Mills functional is given by **Yang-Mills equation**

\begin{equation\*} \begin{cases} d^{\*}\_{A}F\_{A} = 0 & \\\\ d\_{A} F\_{A} = 0 & \end{cases} \end{equation\*}

The second equation is Bianchi identity (Cf. [Curvature](#24adfd2f-8b92-4a12-b729-bb04f2935e6d)) and is automatically satisfied. In fact, solutions of anti-self-dual equation is a special solutions of the Yang-Mills equation, because it takes globally minimal value.


## Algebraic Number Theory {#94c69d5d-300e-4bd4-850f-7e15611117e0}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:37]</span></span>
Apart from algebraic **number** theory, the theory of cohomology of groups is also put here. The main reference is [<span id="b4a5092d5be50d9bf5c61da5a15def18"><a href="#milne2020a" title="@misc{Milne2020a,
  title = {Exercises of {{Algebraic Number Theory}} (v3.08)},
  author = {Milne, J. S.},
  year = {2020}
}">milne2020a</a></span>] and [<span id="b71f719ac1b346d4c039df59c580b69c"><a href="#kedlaya2021" title="Kedlaya, Note on Class Field Theory, (2021).">kedlaya2021</a></span>], for detailed proof see these and references there.


### Abstract class field theory {#eb328fd6-255b-4cdb-8d6d-968217a29966}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-24 Fri 18:43]</span></span>
If \\(L/K\\) is a cyclic extension of local fields, then we have \\(\shar H\_{T}^{0}(\Gal(L/K), L^{\*}) = [L : K], \shar H\_{T}\_{-1}(\Gal(L/K), L^{\*}) = 1\\). We can construct the reciprocity map from above two equality. Such theory is called **abstract class field theory**.


### Adèle {#92e5d498-79e5-4a25-b97a-1d634a25712b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:39]</span></span>
Let \\(K\\) be a number field of degree \\(n\\). It then has \\(n\\) distinct embeddings \\(\tau: K \to \CC\\). The product embedding
\\[j: K \to \prod\_{\tau} \CC, a \to (\tau(a))\_{tau}\\]
induces an isomorphism of \\(K\_{\CC} = K \otimes\_{\QQ} \CC\\), which induces Hermitian inner product. By considering the involution by complex conjugation, then we have \\(K\_{\RR}\\). We have embedding \\(K\\) into \\(K\_{\RR}\\), \\(\mathfrak{o}\_{K}\\) corresponds to a **lattice** in \\(K\_{\RR}\\).

{{% lemma %}}
For \\(K\\) a number field, there is a natural isomorphism of compact topological rings
\\[\hat{\mathfrak{o}\_{K}} \to \prod\_{\mathfrak{p}} \varinjlim\_{m} \mathfrak{o}\_{K} / \mathfrak{p}^{m}\\]
where \\(\mathfrak{p}\\) runs over prime ideals of \\(\mathfrak{o}\_{K}\\).
{{% /lemma %}}

We define the **ring of finite adèles** \\(\mathbb{A}\_{\QQ}^{fin}\\) as any of the following isomorphic objects:

1.  the tensor product \\(\hat{\ZZ} \otimes\_{\ZZ} \QQ\\).
2.  the direct limit of \\(\frac{1}{n} \hat{\ZZ}\\) over all nonzero integers \\(n\\).
3.  The [Restricted topological product](#df98f68b-7d33-4a1e-af8e-2d9280625628) \\(\prod\_{p}' \QQ\_{p}\\), where we only allow tuples \\((\alpha\_{p})\\) for which \\(\alpha\_{p} \in \ZZ\_{p}\\) for almost all \\(p\\).

We define the **ring of adèles** over \\(\QQ\\) as \\(\mathbb{A}\_{\QQ} = \RR \times \mathbb{A}\_{\QQ}^{fin}\\). Then \\(\mathbb{A}\_{\QQ}\\) is a locally compact topological ring with a canonical embedding \\(\QQ \to \mathbb{A}\_{\QQ}\\). We refer to the elements of \\(\QQ\\) as **principal adèles** with \\(\mathbb{A}\_{\QQ}\\).

\\(\QQ\\) is discrete in \\(\mathbb{A}\_{\QQ}\\).

for general number field \\(K\\). We define the **ring of finite adèles** \\(\mathbb{A}\_{K}^{fin}\\) as following isomorphic objects:

1.  the tensor product \\(\hat{\mathfrak{o}\_{K}} \otimes\_{\mathfrak{o}\_{K}} K\\);
2.  the direct limit of \\(\frac{1}{\alpha} \hat{\mathfrak{o}\_{K}}\\) over all nonzero \\(\alpha \in \mathfrak{o}\_{K}\\);
3.  the restricted direct product of the pairs \\((K\_{\mathfrak{p}}, \mathfrak{o}\_{K\_{\mathfrak{p}}}\\) over all primes \\(\mathfrak{p}\\) of \\(K\\).

The **ring of adèles** is \\(K\_{\RR} \times \mathfrak{A}\_{K}^{fin}\\).

We have
\\[\abs{x}\_{K} = \prod\_{v} \abs{x}\_{v}\\]
where if \\(v\\) is real take real absolute value, \\(v\\) complex, square of the absolute value and \\(v\\) finite [Place](#a325e981-9105-4504-9a2f-257847e8bc89) normalized so that \\(\abs{p}\_{v} = p^{-1}\\).

{{% proposition %}}
If \\(\alpha \in K\\), then \\(\abs{\alpha}\_{K} = 1\\).
{{% /proposition %}}

{{% corollary %}}
The subset \\(K\\) of \\(\mathbb{A}\_{K}\\) is discrete.
{{% /corollary %}}

{{% proposition %}}
The quotient group \\(\mathbb{A}\_{K}/K\\) is compact.
{{% /proposition %}}


### Adelic reciprocity law {#4a1fa743-0943-45d1-aae9-758609998628}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-29 Wed 20:17]</span></span>
The **adelic reprocity law** is the following

{{% theorem %}}
There is a canonical map \\(r\_{K}: C\_{K} \to \Gal(K^{ab}/K)\\) which induces, for each Galois extension \\(L/K\\) of number fields, an isomorphism \\(r\_{L/K}: C\_{K}/ \nm\_{L/K} C\_{L} \to \Gal(L/K)^{ab}\\). Moreover, \\(\nm\_{L/K} C\_{L}\\) is an open subgroup of \\(C\_{K}\\).
{{% /theorem %}}

We have similar **existence theorem** and **norm limitation theorem**

{{% theorem %}}
For every number field \\(K\\) and every open subgroup \\(H\\) of \\(C\_{K}\\) of finite index, there exists a finite extension \\(L\\) of \\(K\\) such that \\(H = \nm\_{L/K} C\_{L}\\).
{{% /theorem %}}

{{% theorem %}}
Let \\(L/K\\) be an extension of number fields and put \\(M = L \cap K^{ab}\\). Then \\(\nm\_{L/K}C\_{L} = \nm\_{M/K} C\_{M}\\).
{{% /theorem %}}

The following local-global compatibility is important to global class field theory. We define a map \\(r\_{K,v}:K\_{v}^{\*} \to G\_{v} \subset G\\) as local reprocity map if \\(v\\) is finite place, sign map if \\(v\\) is real place, trivial map if \\(v\\) is complex place. Then we define
\\[\tilde{r}\_{K}: I\_{K} \to G, (\alpha\_{v}) \to \prod\_{v} r\_{K,v}(\alpha\_{v})\\]

{{% proposition %}}
For \\(L/K\\) an abelian extension of number fields, the map \\(\tilde{r}\_{K}: I\_{K} \to \Gal(L/K)\\) is trivial on \\(K^{\*}\\) an factor through map \\(C\_{K} \to \Gal(L/K)\\). And \\(C\_{K}/U \to \Gal(L/K)\\) is the required Artin map.
{{% /proposition %}}

Cf. [Artin's reciprocity law](#b9c3f54c-1662-44e3-ba8a-2f24a24619c4).


### Approximation theorem {#5e3b69ca-90bc-4f51-b4c8-8f722ed558b6}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:38]</span></span>
The following theorem is referred to as **approximation theorem**.

{{% theorem %}}
Let \\(S\\) be a finite set of places of \\(K\\). For each \\(v \in S\\), let \\(U\_{v}\\) be an open subgroup of \\(K\_{v}\\). Then \\(K \cap \cap\_{v \in S} U\_{v} \neq 0\\).
{{% /theorem %}}

Cf. [Adèle](#92e5d498-79e5-4a25-b97a-1d634a25712b), [Place](#a325e981-9105-4504-9a2f-257847e8bc89).


### Artin's reciprocity law {#b9c3f54c-1662-44e3-ba8a-2f24a24619c4}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 16:18]</span></span>
Let \\(L/K\\) be a finite abelian extension of number fields. For each prime \\(\mathfrak{p}\\) of \\(K\\) that does not [Ramify](#b12e3ae3-4275-4644-85b6-fbf05688d188) in \\(L\\), let \\(\mathfrak{q}\\) be a prime of \\(L\\) over \\(K\\), and put \\(\kappa = \mathfrak{o}\_{K} / \mathfrak{p}\\) and \\(\lambda = \mathfrak{o}\_{L}/ \mathfrak{q}\\). Then the residue field extension \\(\lambda/ \kappa\\) is an extension of finite fields, so it has a canonical generator \\(\sigma\\), the [Frobenius element](#1cbfd683-b890-40ff-8d40-f9e0c66aa169), which acts by rasing to \\(q\\)-th power. Since \\(\mathfrak{p}\\) does not ramify, the decomposition group \\(G\_{\mathfrak{q}}\\) is isomorphic to \\(\Gal(\lambda/ \kappa)\\), so we get a canonical element of \\(G\_{\mathfrak{q}}\\). We say it to be **Frobenius** of \\(\mathfrak{p}\\) since in abelian Galois group the conjugaton has no effect.

Now for \\(\mathfrak{m}\\) divisible by all primes of \\(K\\) which ramify in \\(L\\), define the homomorphism called **Artin map**
\\[J^{\mathfrak{m}}\_{K} \to \Gal(L/K), \\; \mathfrak{p} \to {\rm Frob}\_{\mathfrak{p}}\\]

The **Artin's reciprocity law** is the following theorem

{{% theorem %}}
There exists a formal product \\(\mathfrak{m}\\) of places of \\(K\\), including all places over which \\(L\\) ramifies, such that \\(P^{\mathfrak{m}}\_{K}\\) belongs to the kernel of the Artin map.
{{% /theorem %}}


### Augmentation ideal {#f1ac603b-5167-4ddd-a740-c24938c99780}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-22 Wed 20:39]</span></span>
Let \\(M\_{G}\\) denote the maximal quotient of \\(M\\) on which \\(G\\) acts trivially. Then we have \\(M\_{G} = M / M I\_{G}\\), where \\(I\_{G}\\) is the **augmentation ideal** of \\(\ZZ[G]\\)
\\[I\_{G} = \\{ \sum\_{g \in G} z\_{g} [g] \mid \sum\_{g} z\_{g} = 0\\}\\]
We call \\(M\_{G}\\) the group of **\\(G\\)-coinvariants**. \\(M \to M\_{G}\\) is right exact but not left exact.


### Brauer group {#6638d0ef-e5e3-4cd3-b3c5-56098303fd9b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:40]</span></span>
For any field \\(K\\), the group \\(H^{2}(\Gal(\bar{K}/K), \bar{K}^{\*})\\) is called the **Brauer group** of \\(K\\), denoted by \\({\rm Br}(K)\\).

We have following isomorphism

{{% theorem %}}
\\[H^{2}(K\_{nr}/K) = Br(K) = \QQ / \ZZ\\]
{{% /theorem %}}

The left hand side means \\(H^{2}(\Gal(K^{ur}/K), (K^{ur})\*)\\).

{{% theorem %}}
The valuation map \\(v: K\_{nr}^{\*} \to \ZZ\\) defines an isomorphism \\(H^{2}(K\_{nr}/ K) \to H^{2}(\hat{\ZZ}, \ZZ)\\).
{{% /theorem %}}

We consider the map \\({\rm inv}\\) we have isomorphism
\\[H^{2}(K\_{nr}/K) \xrightarrow{v} H^{2}(\hat{\ZZ}, \ZZ) \xrightarrow{\delta^{-1}} \Hom(\hat{\ZZ}, \QQ/\ZZ) \xrightarrow{\gamma} \QQ/\ZZ\\]

{{% theorem %}}
Let \\(L/K\\) be a finite extension of degree \\(n\\). Then
\\[{\rm inv}\_{L} \circ {\rm Res}\_{K/L} = n . {\rm inv}\_{K}\\]
{{% /theorem %}}

Referenced: [Brauer group](#6638d0ef-e5e3-4cd3-b3c5-56098303fd9b).


### Chebotarëv density theorem {#2545baef-e9f1-45ad-b238-1733a8685e74}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-21 Tue 18:57]</span></span>
The **Caebotarëv density theorem** is the following.

{{% theorem %}}
Let \\(L/K\\) be a Galois extension of number fields with Galois group \\(G\\). Then for any \\(g \in G\\) there exist infinity many primes \\(\mathfrak{p}\\) of \\(K\\) such that there is a prime \\(\mathfrak{q}\\) of \\(L\\) over \\(\mathfrak{p}\\) with Frobenius \\(g\\). In fact, the Dirichlet density of such primes \\(\mathfrak{p}\\) is the order of the conjugacy class of \\(G\\) divided by \\(\shar G\\).
{{% /theorem %}}

Cf. [Dirichlet density](#878eb51c-ce16-4b39-918a-849bb858a7e0).

{{% corollary %}}
Let \\(L/K\\) be a nontrivial extension of number fields. Then there exist infinitely many primes of \\(K\\) which do not split completely in \\(L\\).
{{% /corollary %}}


### Class field axiom {#463c465b-a799-46a1-9e9c-1e592628a990}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 17:55]</span></span>
With notation of [Weil group](#86a2985f-a089-4e4e-943e-d57bbc2b7836), we say \\(A\\) satisfies the **class field axiom** if forevery cyclic extension \\(L/K\\) of finite subextensions of \\(\bar{k}/ k\\),
\\[\shar H^{i}\_{T}(\Gal(L/K), A\_{L}) = \begin{cases} [L:K] & i = 0 \\\\ 1 & i = -1 \end{cases} \\]


### Cohomology of local fields {#15e4aad2-2bd0-440c-852b-78103f0ffa4c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-24 Fri 19:11]</span></span>
We collect some result of cohomology of local fields here.

For [Unramified](#16aeb477-ff63-4293-abd3-cf8fb879793d) case,

{{% proposition %}}
For any finite unramified extension \\(L/K\\) over local fields, the map \\(\nm\_{L/K}: \mathfrak{o}\_{L}^{\*} \to \mathfrak{o}\_{K}^{\*}\\) is surjective.
{{% /proposition %}}

{{% corollary %}}
For any finite unramified extension \\(L/K\\) of local fields, \\(H^{i}\_{T}(\Gal(L/K), \mathfrak{o}\_{L}^{\*}) = 1\\) for all \\(i \in \ZZ\\).
{{% /corollary %}}

{{% proposition %}}
For any finite unramified extension \\(L/K\\) over local fields, \\(H^{2}(L/K)\\) is cyclic of order \\([L: K]\\).
{{% /proposition %}}

For cyclic case,

{{% lemma %}}
Let \\(L/K\\) be a finite Galois extension of local fields. Then there is an open, Galois-stable subgroup \\(V\\) of \\(\mathfrak{o}\_{L}\\) as additive group such that \\(H^{i}(\Gal(L/K), V) = 0\\) for all \\(i > 0\\).
{{% /lemma %}}

{{% lemma %}}
Let \\(L/K\\) be a finite Galois extension of local fields. Then there exists an open, Galois-stable subgroup \\(W\\) of \\(\mathfrak{o}\_{L}\\) as multiplicative group such that \\(H^{i}(\Gal(L/K), W) = 0\\) for all \\(i > 0\\).
{{% /lemma %}}

{{% proposition %}}
for \\(L/K\\) a acyclic extension of local fields, \\(\shar H\_{T}^{0}(\Gal(L/K), L^{\*}) = [L:K]\\).
{{% /proposition %}}

For general case,

{{% proposition %}}
for any finite Galois extension \\(L/K\\) of local fields, the group \\(H^{2}(\Gal(L/K), L^{\*})\\) has order at most \\([L:K]\\).
{{% /proposition %}}

{{% proposition %}}
Let \\(L/K\\) be a finite Galois extension of local fields. Let \\(M/K\\) be an unramified extension of degree \\([L:K]\\). Then the image of \\(H^{2}(L/K)\\) in \\(H^{2}(ML/K)\\) contains the image of \\(H^{2}(M/K)\\) in \\(H^{2}(ML/K)\\). Consequently, the group \\(H^{2}(\Gal(L/K), L^{\*})\\) contains a cyclic subgroup of order \\([L:K]\\).
{{% /proposition %}}


### Cohomology of group {#503d2758-81fe-49b7-96c7-4976965214ce}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:39]</span></span>
We define the **cohomology** of the group to be \\(H^{i}(G, M)\\) the derived functor of \\((\bullet)^{G}\\). To compute it, we can use either [Injective](#d0ff06a0-f68a-4d0a-9d73-f734bae8e43b) resolution or [F-acyclic](#10475722-258f-459b-ac55-328efab6f5af) resolution.

Given a \\(G\\)-module \\(M\\), we can define \\(G\\)-module \\(N^{i}\\) for \\(i \geq 0\\) as the set of functions \\(\phi: G^{i + 1} \to M\\) with \\(G\\)-action
\\[(\phi^{g})(g\_{0}, \cdots, g\_{i}) = \phi(g\_{0}g^{-1}, \cdots, g\_{i}g^{-1})^{g}\\]
We have \\(N^{i} = \Ind\_{1}^{G} N\_{0}^{i}\\) for \\(N\_{0}^{i}\\) consists of \\(\phi(g\_{0}, \cdots, g\_{i}) = 0\\) when \\(g\_{0} \neq e\\). So \\(N^{i}\\) is [Induced](#d912fe9c-f313-4e88-823b-76d55d682410). Also we define the map \\(\dif^{i}: N^{i} \to N^{i + 1}\\) by
\\[(\dif^{i} \phi)(g\_{0}, \cdots, g\_{i + 1}) = \sum\_{j = 0}^{i + 1} (-1)^{j} \phi(g\_{0}, \cdots, \hat{g\_{j}}, \cdots, g\_{i + 1})\\]
With above definition, we have \\(0 \to M \to N^{0} \to N^{1} \to \cdots\\) exact, which is in fact acyclic resolution by [Shapiro's lemma](#4ded5df3-ea4c-41a6-bbb0-189610cb3683).

There are some functoriality of group cohomology.

1.  Cohomology group has no nontrivial \\(G\\)-action.
2.  If \\(H\\) is a subgroup of \\(G\\), \\(M\\) a \\(G\\)-module, \\(M'\\) is \\(M\\) with \\(H\\)-action only, we have **restriction homomorphism**
    \\[{\rm Res}:H^{i}(G, M) \to H^{i}(H, M')\\]
3.  Let \\(M\\) be Ga \\(\\)-module, then we have **corestriction map**
    \\[{\rm Cor}:H^{i}(H, M) \cong H^{i}(G, \Ind\_{H}^{G} M) \to H^{i}(G, M)\\]
4.  \\({\rm Cor} \circ {\rm Res}\\) acts as multiplication by \\([G:H]\\) on each cohomology group.
5.  Let \\(H\\) be a normal subgroup of \\(G\\). We have \\(G/H\\) acts on \\(M^{H}\\), and therefore **inflation homomorphisms**
    \\[{\rm Inf}: H^{i}(G/H, M^{H}) \to H^{i}(G, M)\\]

{{% proposition %}}
The group \\(H^{i}(G, M)\\) is the direct limit of \\(H^{i}(G/H, M^{H})\\) using the inflation homomorphisms.
{{% /proposition %}}

the following proposition is called **inflation-restriction exact sequence**

{{% proposition %}}
Let \\(G\\) be a finite group and \\(H\\) be a normal subgroup, and \\(M\\) a \\(G\\)-module. If \\(H^{i}(H, M) = 0\\) for \\(i = 1, \cdots, r - 1\\), then the sequence
\\[0 \to H^{r}(G/H, M^{H}) \xrightarrow{{\rm Inf}} H^{r}(G, M) \xrightarrow{{\rm Res}} H^{r}(H, M)\\]
is exact.
{{% /proposition %}}

The underlying theory is [Spectral sequence](#39be8244-5b96-4223-99ec-9259f5c649ec).

{{% corollary %}}
If \\(M/L/K\\) is a tower of fields with \\(M/K\\) and \\(L/K\\) finite and Galois, the sequence
\\[0 \to H^{2}(L/K) \xrightarrow{{\rm Inf}} H^{2}(M/K) \xrightarrow{{\rm Res}} H^{2}(M/L) \\]
is exact.
{{% /corollary %}}

Cf. [G-module](#efb21395-b3ec-449d-bfcd-f82612ab1ac2).


### Coinvariant {#8d1aab81-3581-4f89-be9c-2e6376744e41}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-22 Wed 20:41]</span></span>
See [Augmentation ideal](#f1ac603b-5167-4ddd-a740-c24938c99780).


### Conductor {#4c964f68-dceb-4125-8737-23709056e262}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 14:26]</span></span>
In [Kronecker-Weber theorem](#b4ee59e2-1dd0-4984-8fbf-2f1a08fe6223), the smallest number \\(K \subset \QQ(\zeta\_{n})\\) is called the **conductor** of \\(K/ \QQ\\).

In [Artin's reciprocity law](#b9c3f54c-1662-44e3-ba8a-2f24a24619c4), the **conductor** of \\(L/K\\) is the smallest formal product \\(\mathfrak{m}\\) for which the reciprocity law holds.


### Corestriction {#a1cb6a67-f698-49da-8885-3213e7578358}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-22 Wed 21:02]</span></span>
See [Cohomology of group](#503d2758-81fe-49b7-96c7-4976965214ce).


### <span class="org-todo todo TODO">TODO</span> Dedekind domain {#7d7305f1-a8e9-4b12-9852-a4f7c872b4ec}



Referenced: [Fractional ideal](#f94f4195-0caa-4b03-92f3-43c18795420e).


### Decomposition group {#6148dbef-9730-41e0-be07-954cbcd25d01}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-21 Tue 19:25]</span></span>
Let \\(L/K\\) be field extension \\(G\\) the Galois group. Let \\(\mathfrak{p}\\) prime ideal of \\(K\\) and \\(\tau\\) prime ideal of \\(L\\) over \\(\mathfrak{p}\\). Then the **decomposition group** is the group \\(G\_{\tau} \subset G\\) which consists of the stabilizer of \\(\tau\\) under the action of \\(G\\) on the primes above \\(\mathfrak{p}\\).


### Dirichlet density {#878eb51c-ce16-4b39-918a-849bb858a7e0}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-21 Tue 19:13]</span></span>
A set of primes \\(S\\) in a number field \\(K\\) has **Dirichlet density** \\(d\\) if
\\[\lim\_{s \to 1^{+}} \frac{\sum\_{\mathfrak{p} \in S} \nm(\mathfrak{p})^{-s}}{\log \frac{1}{s - 1}} = d\\]
This persumes the existence of the limit; otherwise, we have **lower Dirichlet density** and **upper Dirichlet density**.

Cf. [Norm](#8d786b1e-4989-4316-821c-c2f9d4151020).


### Discrete valuation {#42063818-df21-4040-af12-b758687c7110}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:37]</span></span>
The [Valuation](#4849a5e6-921e-44eb-928c-b8d0afcfee95) is a **discrete valuation** if there is a \\(\delta > 0\\) such that \\(1 - \delta < \abs{\alpha} < 1 + \delta\\) implies \\(\abs{\alpha} = 1\\). After taking log and do some normalization, we get a morphism
\\[v: k^{\times} \to \ZZ\\]


### <span class="org-todo todo TODO">TODO</span> Discriminant {#baea9bd0-40c9-4e74-9dc0-a64976b487f5}


### Fractional ideal {#f94f4195-0caa-4b03-92f3-43c18795420e}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 16:53]</span></span>
A **fractional ideal** of a [Dedekind domain](#7d7305f1-a8e9-4b12-9852-a4f7c872b4ec) \\(A\\) is a nonzero \\(A\\)-submodule \\(\mathfrak{a}\\) \\(K\\) such that
\\[d \mathfrak{a} \subset A\\]
for some nonzero \\(d \in A\\). With product, all the fractional ideal of \\(A\\) form a group called **fractional ideal group**.

Referenced: [Norm](#8d786b1e-4989-4316-821c-c2f9d4151020).


### Frobenius element {#1cbfd683-b890-40ff-8d40-f9e0c66aa169}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 16:40]</span></span>
Let \\(L\\) be a finite [Unramified](#16aeb477-ff63-4293-abd3-cf8fb879793d) extension of \\(K\\). Then \\(L\\) is Galois over \\(K\\) and \\(\Gal(L/K)\\) on \\(\mathscr{O}\_{L}\\) defines an isomorphism \\(\Gal(L/K) = \Gal(l/k)\\) where \\(l/k\\) are the residue field. Therefore \\(\Gal(L/K)\\) is a cyclic group and generated by \\(\sigma\\) with \\(\sigma \alpha \equiv \alpha^{q} \pmod{\mathfrak{m}\_{L}}\\) for \\(\alpha \in \mathscr{O}\_{L}\\). \\(\sigma\\) is called **Frobenius element** and denoted by \\(\Frob\_{L/K}\\).

In general, we have to choose a prime \\(\mathfrak{p}\\) of \\(K\\)and \\(\mathfrak{q}\\) prime above \\(\mathfrak{p}\\), then the element of the [Decomposition group](#6148dbef-9730-41e0-be07-954cbcd25d01) \\(G\_{\mathfrak{p}}\\) such that \\(gx \equiv x^{\shar(\mathfrak{o}\_{K}/ \mathfrak{p})} \pmod{\mathfrak{q}}\\). In general, Frobenius element only defined up to conjugation.


### Frobenius reciprocity law {#281bb3d3-a646-43a4-a49b-b49d90552e30}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-22 Wed 19:56]</span></span>
The following is **Frobenius reciprocity law**.

{{% proposition %}}
Let \\(H\\) be the a subgroup of \\(G\\), let \\(M\\) be a \\(G\\)-module and \\(N\\) be an \\(H\\)-module. Then there are natural isomorphisms
\\[\Hom\_{G}(M, \Ind\_{H}^{G} N) \cong \Hom\_{H}(M,N)\\]
\\[\Hom\_{G}(\Ind\_{H}^{G} N, M) \cong \Hom\_{H}(N, M)\\]
{{% /proposition %}}

Cf. [Induction](#419f4800-445d-412a-857f-236588ba5d5c).


### Generalized ideal class group {#38250f73-573a-4272-832f-e5eeea72e35a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-20 Mon 19:31]</span></span>
Let \\(\mathfrak{m}\\) be a formal product of places of \\(K\\). Let \\(J^{\mathfrak{m}}\_{K}\\) be the group of [Fractional ideals](#f94f4195-0caa-4b03-92f3-43c18795420e) of \\(K\\) which are coprime to each finite place of \\(K\\) occuring in \\(\mathfrak{m}\\). Let \\(P\_{K}^{\mathfrak{m}}\\) be the group of principal fractiona ideals generated by elements \\(\alpha \in K\\) such that

1.  for \\(\mathfrak{p}^{e} \mid \mathfrak{m}\\) finite, \\(\alpha \equiv 1 \pmod \mathfrak{p}^{e}\\).
2.  For every real place \\(\tau\\) in \\(\mathfrak{m}\\), \\(\tau(\alpha) > 0\\).

Then the **ray class group** \\({\rm Cl}^{\mathfrak{m}}(K)\\) is defined as the quotient \\(J^{\mathfrak{m}}\_{K} / P^{\mathfrak{m}}\_{K}\\). A quotient of a ray class group is called a **generalized ideal class group**.

Cf. [Ideal class](#a324fd37-15e1-4ea9-950d-645eb3e3bc74).


### G-extension {#e9589c44-6e5e-40da-a3f2-769a87c623fd}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 14:32]</span></span>
If \\(G\\) a group, a **G-extension** of a field \\(K\\) is a Galois extension of \\(K\\) with Galois group \\(G\\).


### G-module {#efb21395-b3ec-449d-bfcd-f82612ab1ac2}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-21 Tue 19:54]</span></span>
Let \\(G\\) be a finite group. A (right) **G-module** is an abelian group \\(A\\) equipped with a right \\(G\\)-action.

Given a \\(G\\)-module \\(M\\), we denote by \\(M^{G}\\) the abelian group of \\(G\\)-invariant elements of \\(G\\). The functor \\(M \to M^{G}\\) is left exact.

{{% exam %}}
Consider exact sequence \\(0 \to \ZZ / p \ZZ \to \ZZ/ p^{2} \ZZ \to \ZZ / p \ZZ \to 0\\), for \\(G = \ZZ / p \ZZ\\), which acts on the middle by \\(a^{g} = a(1 + pg)\\). After applying \\((\bullet)^{G}\\), the sequence is not right exact.
{{% /exam %}}

For \\(G\\)-module of [Profinite group](#308c241c-b5ec-4dd2-8325-58262241e924) \\(G\\), we require that \\(M\\) is topological group and the action \\(G \times M \to M\\) is continuous.


#### Induced {#d912fe9c-f313-4e88-823b-76d55d682410}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-22 Wed 20:11]</span></span>
A \\(G\\)-module is called **induced** if it is of this form \\(\Ind\_{1}^{G} N\\). for some \\(N\\).

The following is a corollary for [Shapiro's lemma](#4ded5df3-ea4c-41a6-bbb0-189610cb3683).

{{% corollary %}}
if \\(M\\) is an induced \\(G\\)-module, then \\(M\\) is acyclic.
{{% /corollary %}}


### Herbrand quotient {#25c1650e-2c20-4355-8c80-63141d687809}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:40]</span></span>
Let \\(G\\) be a finite cyclic group and let \\(M\\) be a \\(G\\)-module. If the group \\(H\_{T}^{i}(G, M)\\) are finite, we define the **Herbrand quotient** as the ratio
\\[h(M) = \shar H^{0}\_{T}(G, M) / \shar H\_{T}^{-1}(G, M)\\]

By periodicity theorem of [Tate cohomology group](#b2eb4671-0678-43e6-b23a-4bcba610f966), for exact sequence \\(0 \to M' \to M \to M'' \to 0\\), we have \\(h(M) = h(M') h(M'')\\).

A interesting fact is the following.

{{% proposition %}}
If \\(M\\) is finite, then \\(h(M) = 1\\).
{{% /proposition %}}


### Henselian valuation {#c54235c2-dfc4-4ec1-b3f8-c2f492cfd3e3}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 17:53]</span></span>
With the notation of [Weil group](#86a2985f-a089-4e4e-943e-d57bbc2b7836), a **henselian valuation** of \\(A\_{k}\\) with respect to \\(d\\) is a homomorphism \\(v: A\_{k} \to \hat{Z}\\) such that

1.  the group \\(Z = \im(v)\\) contains \\(\ZZ\\) and staisfies \\(Z/nZ \cong \ZZ/ n \ZZ\\) for all positive integer \\(n\\);
2.  for every finite extension \\(K\\) of \\(k\\), \\(v(\nm\_{K/k}A\_{K}) = f\_{K/k} Z\\).

for any finite subextension \\(K\\) of \\(\bar{k}/k\\), define the **unit group** \\(U\_{K}\\) as the set of \\(u \in A\_{K}\\) with \\(v\_{K}(u) = 0\\). We say \\(\pi \in A\_{K}\\) is a **uniformizer** for \\(K\\) if \\(v\_{K}(\pi) = 1\\).


### Hilbert class fields {#f846672c-7edd-48df-8ea4-93bc57c5424d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 15:10]</span></span>
Let \\(L\\) be the maximal [Unramified](#16aeb477-ff63-4293-abd3-cf8fb879793d) abelian extension of a number field \\(K\\). Then \\(L/K\\) is finite, and its Galois group is isomorphic to the ideal class group \\({\rm Cl}(K)\\) of \\(K\\). The field \\(L\\) is called **Hilbert class field** of \\(K\\).


### Homology of group {#1f75abc3-e7f1-4623-9f55-9ef7ac240a21}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-22 Wed 20:44]</span></span>
We define the **homology** of groups to be the left derived functor of [Coinvariant](#8d1aab81-3581-4f89-be9c-2e6376744e41).

Cf. [Cohomology of group](#503d2758-81fe-49b7-96c7-4976965214ce).


### <span class="org-todo todo TODO">TODO</span> Ideal class {#a324fd37-15e1-4ea9-950d-645eb3e3bc74}



Referenced: [Finiteness of class group](#0a53c20c-a6f4-4206-b485-269f5ecf0a89).


### Idèle {#1da9a675-4798-43e7-86d6-e29d087e0426}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:39]</span></span>
Let \\(K\\) be a number field and let \\(\mathbb{A}\_{K}\\) be the ring of [Adèles](#92e5d498-79e5-4a25-b97a-1d634a25712b) associated to \\(K\\). We define the group of **idèles** \\(I\_{K}\\) associated to \\(K\\) as the gorup of units of the ring \\(\mathbb{A}\_{K}\\). In fact \\(I\_{K}\\) is [Restricted topological product](#df98f68b-7d33-4a1e-af8e-2d9280625628) of \\((K\_{v}^{\*}, \mathbb{o}\_{K\_{v}}^{\*})\\).

{{% remark %}}
\\(I\_{K} \ito \mathbb{A}\_{K}\\) is continuous, but the topology of \\(I\_{K}\\) does not coincide with the subspace topology for the embedding! For example \\(I\_{K,S}\\) is open in \\(I\_{K}\\) but not the intersection with an open subset of \\(\mathbb{A}\_{K}\\).
{{% /remark %}}

We have \\(I\_{K} = \cup\_{S} I\_{K,S}\\), where \\(S\\) is finite set and \\(I\_{K,S}\\) denote the element \\(x\_{v} \in \mathbb{o}\_{K\_{v}}^{\*}\\) for each finite place \\(v \in S\\). Elements of \\(I\_{K,S}\\) called **S-units**. (Cf. [S-integer](#4bf8e1a2-074e-4e2e-8158-867d32fcfe98))

For each \\(\alpha \in K^{\*}\\), the principal adèle \\(\alpha \in \mathbb{A}\_{K}\\) is an **idèle**, so we have an embedding \\(K^{\*} \to I\_{K}\\). We refer to elements of this embedding **principal idèles**. Define the **idèle class group** of \\(K\\) as the quotient \\(C\_{K} = I\_{K}/K^{\*}\\).

{{% proposition %}}
We have surjection \\(C\_{K} \to {\rm Cl}(K)\\) with kernel \\(I\_{K,S}K^{\*}/K^{\*}\\).
{{% /proposition %}}

We have well defined norm \\(\abs{\cdot}:C\_{K} \to \RR\_{+}^{\*}\\) derived from \\(\mathbb{A}\_{K}\\). Let \\(C\_{K}^{0}\\) denote the kernel of this map.

{{% proposition %}}
The group \\(C\_{K}^{0}\\) is compact.
{{% /proposition %}}

{{% corollary %}}
The class group \\({\rm Cl}(K)\\) of \\(K\\) is finite.
{{% /corollary %}}

The following is the famous **Dirichlet's unit theorem**

{{% corollary %}}
The group of units of \\(\mathb{o}\_{K}\\) fits into an exact sequence
\\[0 \to \mu\_{K} \to \mathbb{o}\_{K}^{\*} \to \ZZ^{r + s - 1} \to 0\\]
in which \\(\mu\_{K}\\) is the group of unity of \\(K\\) and \\(r\\) ans \\(s\\) are number of real and complex places, respectively. More generally, for any finite set \\(S\\) of places containing all infinite places, the group of units of the ring \\(\mathbb{o}\_{K,S}\\) of \\(S\\)-integers fits into an exact sequence
\\[0 \to \mu\_{K} \to \mathbb{o}^{\*}\_{K,S} \to \ZZ^{\shar S -1} \to 0\\]
{{% /corollary %}}


### Induction {#419f4800-445d-412a-857f-236588ba5d5c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-22 Wed 19:49]</span></span>
If \\(H\\) is a subgroup of \\(G\\) and \\(M\\) is an \\(H\\)-module, we define the **induction** of \\(M\\) from \\(H\\) to \\(G\\) to be \\(\Ind\_{H}^{G} M = M \otimes\_{\ZZ[H]} \ZZ[G]\\). We may also identify \\(\Ind\_{H}^{G} M\\) with the set of functions \\(\phi: G \to M\\) such that \\(\phi(gh) = \phi(g)^{h}\\) for \\(h \in H\\).


### Inflation map {#19141a25-0546-4c42-9a64-99572c95a6c2}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-22 Wed 21:02]</span></span>
See [Cohomology of group](#503d2758-81fe-49b7-96c7-4976965214ce).


### Inertial degree {#407bbdcc-a669-4d15-82be-e237d23662d5}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 17:50]</span></span>
See [Weil group](#86a2985f-a089-4e4e-943e-d57bbc2b7836).


### Inertia group {#c313b9e7-9e54-4de9-bb10-878b173dfa81}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 16:13]</span></span>
See [Weil group](#86a2985f-a089-4e4e-943e-d57bbc2b7836).


### Kronecker-Weber theorem {#b4ee59e2-1dd0-4984-8fbf-2f1a08fe6223}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 14:22]</span></span>
The **Kronecker-Weber theorem** is the following

{{% theorem %}}
If \\(K/ \QQ\\) is a finite ableian extension, then \\(K \subset \QQ(\zeta\_{n})\\) for some positive integer \\(n\\).
{{% /theorem %}}

We also have a local version, called **local Kronecker-Weber theorem**.

{{% theorem %}}
If \\(K/ \QQ\_{p}\\) is a finite ableian extension, then \\(K \subset \QQ\_{p}(\zeta\_{n})\\) for some positive integer \\(n\\), where \\(\zeta\_{n}\\) is a primitive \\(n\\)-th root of unity.
{{% /theorem %}}


### Kummer theory {#9bac4334-ff42-43d0-bd8a-25ee9053b093}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 14:30]</span></span>
The following theorem is key in **Kummer theory** of ableian extensions.

{{% theorem %}}
If \\(\zeta\_{n} \in K\\), then every \\(\ZZ/n \ZZ\\) extension of \\(K\\) is of the form \\(K(\alpha^{1/n})\\) for some \\(\alpha \in K^{\*}\\) with the property that \\(\alpha^{1/d} \not \in K\\) for any proper divisor \\(d\\) of \\(n\\) and vice versa.
{{% /theorem %}}


### L-function {#bb7f0c92-3f63-4879-b7ed-1c695babff0a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-21 Tue 19:06]</span></span>
Let \\(\K\\) be a number field \\(\mathfrak{m}\\) formal product of [Places](#a325e981-9105-4504-9a2f-257847e8bc89) of \\(K\\). Let \\(\chi\_{\mathfrak{m}}: {\rm Cl}^{\mathfrak{m}}(K) \to \CC^{\*}\\) be a character. Then we can extend \\(\chi\_{\mathfrak{m}}\\) to a function on all ideal of \\(K\\) by declaring its value to be \\(0\\) on ideals not coprime to \\(\mathfrak{m}\\). Then we define the **L-function**
\\[L(s, \chi\_{\mathfrak{m}}) = \prod\_{\mathfrak{p} \not \div \mathfrak{m}}(1 - \chi(\mathfrak{p}) \nm(\mathfrak{p})^{-1})^{-1}\\]
which convergent absolutely for \\({\rm Re}(s) > 1\\). In fact, we have the following theorem

{{% theorem %}}
If \\(\chi\_{\mathfrak{m}}\\) is not trivial, then \\(L(s, \chi\_{\mathfrak{m}})\\) extends to an analytic function on \\(\CC\\).
{{% /theorem %}}

We also have nonvanishing theorem

{{% theorem %}}
If \\(\chi\_{\mathfrak{m}}\\) is not the trivial character, then \\(L(1, \chi\_{\mathfrak{m}}) \neq 0\\).
{{% /theorem %}}

Cf. [Norm](#8d786b1e-4989-4316-821c-c2f9d4151020).


### Langlands correspondence {#6271b62f-22df-4480-8154-9ffed25cc2ca}



{{< figure src="/img/2021-08-31_14-02-53_screenshot.png" >}}


### Langlands prgram {#c485ad52-a441-43f9-bde4-17164f0e245a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 17:36]</span></span>
As far as I know there are several parts of Langlands program, namely reciprocity conjecture and functoriality conjecture. The following is the reciprocity conjecture

{{% conjecture %}}
Suppose \\(E\\) is a finite Galois extension of \\(F\\) with Galois group \\(G = \Gal(E/F)\\), and \\(\sigma: G \to \GL\_{n}(\CC)\\) is an irreducible representation of \\(G\\). Then there exists an automorphic cuspidal representation \\(\pi\_{\sigma}\\) on \\(\GL\_{n}\\) over \\(F\\) such that \\(L(s, \pi\_{\sigma}) = L(s, \sigma)\\).
{{% /conjecture %}}

And the functoriality conjecture

{{% conjecture %}}
Suppose \\(G\\) and \\(G'\\) are reductive groups, and \\(\rho: ^{L}G \to ^{L}G'\\) is an \\(L\\)-homomorphism. Then to each automorphic representation \\(\pi = \otimes \pi\_{v}\\) of \\(G\\), there is an automorphic representation \\(\pi' = \otimes \pi'\_{v}\\) of \\(G'\\) such that for unramified \\(v\\), \\(t(\pi'\_{v})\\) is the conjugacy class in \\(^{L}G'\\) which contains \\(t(\pi\_{v})\\). Moreover, for any finite dimensional representation \\(r'\\) of \\(^{L}G'\\), we have
\\[L(s, \pi', r') = L(s, \pi, r' \circ \rho)\\]
Here \\(^{L}G\\) denote the Langlands dual group.
{{% /conjecture %}}

{{% remark %}}
The functoriality conjecture implies reciprocity conjecture.
{{% /remark %}}


### Local existence theorem {#0018fdec-3a68-41d9-afc2-7bf0ae88aa1c}



{{% theorem %}}
The norm groups in \\(K^{\times}\\) are exactly the open subgroups of finite index.
{{% /theorem %}}

Cf. [Norm group](#927664ce-ab27-4b67-a1e4-6af02c62dcdf).


### Local reciprocity map {#7058283b-5561-4270-8603-878604eab7bf}



{{% theorem %}}
For every nonarchimedian local field \\(K\\), there exists a unique homomorphism
\\[\phi\_{K}: K^{\times} \to \Gal(K^{ab}/K)\\]
with following properties
a. For every prime element \\(\pi\\) of \\(K\\) and every finite unramified extension \\(L\\) of \\(K\\), \\(\phi\_{K}(\pi)\\) acts on \\(L\\) as \\(\Frob\_{L/K}\\).
b. For every finite ableian extension \\(L\\) of \\(K\\), the \\(\nm\_{L/K}(L^{\times})\\) is contained in the kernel of \\(a \to \phi\_{K}(a)|\_{L}\\) and \\(\phi\_{K}\\) induces an isomorphism
\\[\phi\_{L/K}:K^{\times}/\nm\_{L/K}(L^{\times}) \to \Gal(L/K)\\]
In particular, \\((K^{\times}: \nm\_{L/K}(L^{\times})) = [L : K]\\).
{{% /theorem %}}

Here \\(\phi\_{K}\\) and \\(\phi\_{L/K}\\) are called **local Artin maps** or **local reciporicity maps** and \\(\phi\_{L/K}\\) is also called **norm residue map** or **symbol**.

By local existence theorem, we have **local existence theorem**

{{% theorem %}}
For every finite (not necessarily abelian) extension \\(L\\) of \\(K\\), \\(\nm\_{L/K}(L^{\*})\\) is an open subgroup of \\(K^{\*}\\) of finite index. Conversely, for every (open) subgroup \\(U\\) of \\(K^{\*}\\) of finite index, there exists a finite abelian extension \\(L\\) of \\(K\\) such that \\(U = \nm\_{L/K} L^{\*}\\).
{{% /theorem %}}

To see \\(\nm\_{L/K} L^{\*}\\) is norms of which abelian extension, we have **norm limitation theorem**.

{{% theorem %}}
Let \\(M\\) be the maximal abelian subextension of \\(L/K\\). Then \\(\nm\_{L/K} L^{\*} = \nm\_{M/K} M^{\*}\\).
{{% /theorem %}}


### Maximal abelian extension {#d2808c27-f35f-42d0-89c0-2e66105e6cb7}



{{% theorem %}}
Let \\(\QQ\_{p}^{cycl}\\) be the field generated over \\(\QQ\\) by all roots of unity. Then \\(\QQ\_{p}^{cycl}\\) is the maximal abelian extension of \\(\QQ\_{p}\\).
{{% /theorem %}}

on p. 172


### Norm {#8d786b1e-4989-4316-821c-c2f9d4151020}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:37]</span></span>
Let \\(L/K\\) be finite field extension, for \\(\alpha \in L\\), we have **norm** \\(\nm(\alpha)\\) in \\(K\\) defined as \\(\det(a\_{ij})\\), where \\(\alpha e\_{i} = \sum a\_{ij}e\_{j}\\) and \\(\\{e\_{1}, \cdots, e\_{n}\\}\\) is a basis for \\(L\\) over \\(K\\).

We can also consider the norm map \\(\nm: \id(B) \to \id(A)\\), where \\(\id\\) denote the [Fractional ideal](#f94f4195-0caa-4b03-92f3-43c18795420e) group.

In group theory, we define **norm** to be
\\[\nm\_{G}(m) = \sum\_{g \in G} m^{g}\\]
which induces a homomorphism
\\[\nm\_{G}: H\_{0}(G, M) \to H^{0}(G, M)\\]

In abstract class field theory, with the notation of [Weil group](#86a2985f-a089-4e4e-943e-d57bbc2b7836), we define the **norm** map \\(\nm\_{L/K}: A\_{L} \to A\_{K}\\) by \\(\nm\_{L/K}(a) = \prod\_{g} a^{g}\\), where \\(g\\) runs over a set of right coset representatives of \\(G\_{L}\\) in \\(G\_{K}\\).

For [Adèles](#92e5d498-79e5-4a25-b97a-1d634a25712b), we can also have **norm** map, for \\(L/K\\) an extension of number fields, we define the **norm map** \\(\nm\_{L/K}: I\_{L} \to I\_{K}\\) by
\\[\nm\_{L/K}(x) \to \prod\_{g} x^{g}\\]
where \\(g\\) runs over coset representatives of \\(\Gal(\bar{K}/L)\\) in \\(\Gal(\bar{K}/K)\\). Similar for trace map \\(\tr\_{L/K}: \mathbb{A}\_{L} \to \mathbb{A}\_{K}\\).


### Norm group {#927664ce-ab27-4b67-a1e4-6af02c62dcdf}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 18:06]</span></span>
A subgroup of \\(K^{\times}\\) is called a **norm group** if it is of the form \\(\nm(L^{\times})\\) for some finite abelian extension \\(L\\).

Referenced: [Local existence theorem](#0018fdec-3a68-41d9-afc2-7bf0ae88aa1c).


### Place {#a325e981-9105-4504-9a2f-257847e8bc89}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 15:06]</span></span>
A **place** of a number field \\(K\\) is a equivalence class of nontrivial [Absolute values](#2db41c9f-be95-4271-9bea-a24f6bb15d16) on \\(K\\).


### Principal ideal theorem {#042ba630-571f-4f90-853a-ee1c621fb85b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-20 Mon 19:59]</span></span>
**Principal ideal theorem** concerns the ideals of [Hilbert class fields](#f846672c-7edd-48df-8ea4-93bc57c5424d).

{{% theorem %}}
Let \\(L\\) be the Hilbert class field of the number field \\(K\\). Then every ideal of \\(K\\) becomes principal in \\(L\\).
{{% /theorem %}}


### Profinite group {#308c241c-b5ec-4dd2-8325-58262241e924}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:40]</span></span>
A **profinite group** is a topological group which is Hausdorff and compact, and which admits a basis of neighborhoods of the identity consisting of normal groups. More explicitly, a profinite group is a group \\(G\\) plus a collection of subgroups of \\(G\\) of finite index as **open subgroups**, such that the intersection of two open subgroups is open, but the intersection of all of the open subgroup is trivial.

The **profinite group** can also be defined as limits. Suppose we are given a partially ordered set \\(I\\), a family \\(\\{G\_{i}\\}\_{i \in I}\\) of finite groups and a map \\(f\_{ij}: G\_{i} \to G\_{j}\\) for each pair \\((i, j) \in I \times I\\) such that \\(i > j\\). Then there exists a profinite group \\(G\\) with open subgroups \\(H\_{i}\\) for \\(i \in I\\) such that \\(G/H\_{i} \cong G\_{i}\\) in a manner compatible with the \\(f\_{ij}\\), the limit of system.

So if \\(L/K\\) Galois extension but not necessarily finite, we make \\(G = \Gal(L/K)\\) into a profinite group by declaring that the open subgroups of \\(G\\) are precisely \\(\Gal(L/M)\\) for all finite extensions \\(M\\) of \\(K\\). In fact, we have following **Galois correspondence**

{{% theorem %}}
Let \\(L/K\\) be a Galois extension. Then there is a correspondence between (Galois) subextension of \\(M\\) of \\(L\\) and (normal) closed subgroups \\(H\\) of \\(\Gal(L/K)\\), given by
\\[H \to {\rm fix} H, \\; M \to \Gal(L/M)\\]
{{% /theorem %}}


### Ramification degree {#a854bce3-4aed-4c67-9a95-debb6d9ddb57}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 17:49]</span></span>
See [Inertia group](#c313b9e7-9e54-4de9-bb10-878b173dfa81).


### Ramification index {#08e3387b-912a-42cf-8a1d-0232514d44be}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:38]</span></span>
Let \\(L/K\\) be an extension of number fields. Let \\(\mathfrak{p}\\) be a nonzero prime ideal in the integer of rings \\(\mathfrak{o}\_{K}\\) of \\(K\\), and
\\[\mathfrak{p} \mathfrak{o}\_{L} = \prod\_{i=1}^{n} \mathfrak{P}\_{i}^{e\_{i}}\\]
for some prime ideal \\(\mathfrak{P}\_{i} \in \mathfrak{o}\_{L}\\). Then the natural number \\(e\_{i}\\) is called the **ramification index** of \\(\mathfrak{P}\_{i}\\) over \\(\mathfrak{p}\\), denoted by \\(e(\mathfrak{P}\_{i}/ \mathfrak{p})\\). If \\(e\_{i} > 1\\), we say that ideal \\(\mathfrak{p}\\) is **ramified** in \\(L\\).

Ramification index can be generalized to local fields.


### Ramified {#b12e3ae3-4275-4644-85b6-fbf05688d188}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:38]</span></span>
See [Ramification index](#08e3387b-912a-42cf-8a1d-0232514d44be).


### Ray class field {#2d9c1a49-cfae-4f18-80b4-eb772498882d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-20 Mon 19:46]</span></span>
We say \\(L/K\\) is the **ray class field** corresponding to the product \\(\mathfrak{m}\\) if \\(L/K\\) has [Conductor](#4c964f68-dceb-4125-8737-23709056e262) dividing \\(\mathfrak{m}\\) and the map \\(J\_{K}/J\_{K}^{\mathfrak{m}} \to \Gal(L/K)\\) is an isomorphism.

There is the existence theorem for ray class field.

{{% theorem %}}
Every formal product \\(\mathfrak{m}\\) of \\(K\\) has a ray class field.
{{% /theorem %}}

Cf. [Ray class group](#f870b2df-f187-4a71-91ed-b700a021b7f5).


### Ray class group {#f870b2df-f187-4a71-91ed-b700a021b7f5}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-20 Mon 19:46]</span></span>
See [Generalized ideal class group](#38250f73-573a-4272-832f-e5eeea72e35a).


### Reciprocity map {#03dbee7d-12fb-4ec3-ab03-625590da0d9d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 18:03]</span></span>
If \\(A\\) satisfies [Class field axiom](#463c465b-a799-46a1-9e9c-1e592628a990), \\(v\\) is henselian valuation of \\(A\_{k}\\) with respect to \\(d\\). Let \\(L/K\\) be a Galois extension of finite subextensions of \\(\bar{k}/k\\). Let \\(H\\) be the semigroup of \\(g \in \Gal(L^{ur}/K)\\) such that \\(d\_{K}(g)\\) is a positive integer. Define the map
\\[r' : H \to A\_{K} / \nm\_{L/K} A\_{L}\\]
by for \\(g \in \Gal(L^{ur}/K)\\), \\(M\\) the fixed field of \\(g\\) set \\(r'(g) = \nm\_{M/K}(\pi\_{M})\\) for some uniformizer \\(\pi\_{M}\\) of \\(M\\). \\(r'\\) induces a homomorphism \\(r = r\_{L/K}: \Gal(L/K) \to A\_{K} / \nm\_{L/K} A\_{L}\\) and is called **reciprocity map**.

{{% theorem %}}
For each Galois extension \\(L/K\\) of finite subextension of \\(\bar{k}/k\\), the homomorphism \\(r\_{L/K}\\) induces an isomorphism \\(\Gal(L/K)^{ab} \to A\_{K} / \nm\_{L/K}A\_{L}\\).
{{% /theorem %}}

{{% corollary %}}
Under the hypothesis of the theorem, let \\(L\_{1}/K\\) and \\(L\_{2}/K\\) be abelian extensions of finite subextensions of \\(\bar{k}/k\\). If \\(\nm\_{L\_{1}/K} A\_{L\_{1}} = \nm\_{L\_{2}/K} A\_{L\_{2}}\\), then \\(L\_{1} = L\_{2}\\).
{{% /corollary %}}


### <span class="org-todo todo TODO">TODO</span> Residue class degree {#39976576-a520-411b-9828-8f722277c929}


### Restricted topological product {#df98f68b-7d33-4a1e-af8e-2d9280625628}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:38]</span></span>
Let \\(I\\) be an index set. For each \\(i \in I\\), let \\(G\_{i}\\) be a set and let \\(H\_{i}\\) be a set of \\(G\_{i}\\). The **restricted direct product** \\(G\\) of the pairs \\((G\_{i}, H\_{i})\\) is the set of tuples \\((g\_{i})\_{i = 1}^{\infty}\\) such that \\(g\_{i} \in H\_{i}\\) for all but finitely many indices \\(i\\).


### Restriction {#28697fbb-9e5f-4075-80ac-9d931a30eb35}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:39]</span></span>
See [Cohomology of group](#503d2758-81fe-49b7-96c7-4976965214ce).


### Riemann zeta function {#501b2012-be48-483f-a084-8c6b351c56f8}

<span class="timestamp-wrapper"><span class="timestamp">[2021-08-31 Tue 13:37]</span></span>
\\[\zeta(s) = 1 + \frac{1}{2^{s}} + \frac{1}{3^{s}} + \cdots = \prod\_{p \text{ prime}} \frac{1}{1 - p^{-s}}\\]
The function can be extend as a meromorphic function on \\(\CC\\).


### Rosseta stone in mathematics {#e0ef9e67-6087-409e-944b-34e8c649fde3}

The similarity over number fields, function fields, algebraic curves over \\(\CC\\).

Referenced: [Personal Thoughts]({{<relref "Notes_Mathematics.md#personal-thoughts" >}}).


### Shapiro's lemma {#4ded5df3-ea4c-41a6-bbb0-189610cb3683}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-22 Wed 19:54]</span></span>
The following is **Shapiro's lemma**.

{{% lemma %}}
If \\(H\\) is a subgroup of \\(G\\) and \\(N\\) is an \\(H\\)-module, then there is a canonical isomorphism \\(H^{i}(G, \Ind\_{H}^{G} N) \to H^{i}(H, N)\\). In particular, \\(N\\) is an acyclic \\(H\\)-module if and only if \\(\Ind\_{H}^{G}(N)\\) is an acyclic \\(G\\)-module.
{{% /lemma %}}

Cf. [Induction](#419f4800-445d-412a-857f-236588ba5d5c).


### S-unit {#dc0448dc-4990-4bdb-882b-215b1b17f653}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:39]</span></span>
Cf. [S-integer](#4bf8e1a2-074e-4e2e-8158-867d32fcfe98).


### Tamely ramified {#77cccb22-1747-496c-a2f4-df6b75a02a51}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 15:09]</span></span>
See [Unramified](#16aeb477-ff63-4293-abd3-cf8fb879793d).


### Tate cohomology group {#b2eb4671-0678-43e6-b23a-4bcba610f966}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-22 Wed 20:51]</span></span>
We define the **Tate cohomology groups** to be
\\[H^{i}\_{T} = \begin{cases} H^{i}(G, M) & i > 0 \\\\ M^{g} / \nm\_{G}(M) & i = 0 \\\\ \ker(\nm\_{G})/M I\_{G} & i = -1 \\\\ H\_{-i - 1}(g, M) & i < -1 \end{cases} \\]

It is called cohomology group because it induces long exact sequence.

We have **periodicity theorem** for cohomology of cyclic groups.

{{% theorem %}}
Let \\(G\\) be a finite cyclic group and \\(M\\) a \\(G\\)-module. Then there is a functorial isomorphism \\(H\_{T}^{i}(G, M) \to H\_{T}^{i + 2}(G, M)\\) for all \\(i \in \ZZ\\); moreover, these isomorphisms are all determined by the choice of generator of \\(G\\).
{{% /theorem %}}


### Tate's theorem {#9ed76988-cddb-415f-bab4-bc975a31a20c}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-25 Sat 13:44]</span></span>
**Tate's theorem** refers to the following

{{% theorem %}}
Let \\(G\\) be a finite group and let \\(M\\) be a \\(G\\)-module. Suppose that for all subgroups \\(H\\) of \\(G\\) (including \\(G\\) itself), \\(H^{1}(H,M) = 0\\) and \\(H^{2}(H, M)\\) is cyclic of order \\(\shar H\\). Then there are isomorphisms \\(H\_{T}^{i}(G, \ZZ) \to H^{i + 2}\_{T}(G, M)\\) which are canonical up to a choice of generator of \\(H^{2}(G, M)\\).
{{% /theorem %}}

Cf. [Tate cohomology group](#b2eb4671-0678-43e6-b23a-4bcba610f966), [Cohomology of local fields](#15e4aad2-2bd0-440c-852b-78103f0ffa4c).


### Totally ramified {#bbb3b026-db2d-4f2a-973a-9c0f79a5bed4}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 15:06]</span></span>
See [Unramified](#16aeb477-ff63-4293-abd3-cf8fb879793d).


### Transfer map {#defb0a2a-4d1b-4745-91d0-4e97a890b907}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-20 Mon 20:22]</span></span>
Let \\(G\\) be a finite group and \\(H\\) subgroup (not necessarily normal). Let \\(g\_{1}, \cdots, g\_{n}\\) be left coset representatives of \\(H\\) in \\(G\\). Let \\(\phi(g) = g\_{i}\\) if \\(g \in g\_{i}H\\). Then we define \\(V(g) = \prod\_{i = 1}^{n} \phi(g g\_{i})^{-1}(g g\_{i})\\). The induced map \\(V: G^{ab} \to H^{ab}\\) is called the **tranfer map**.


### Uniformizer {#fc8bb4e8-953c-43a9-bf4c-fa13f2de3cd9}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 17:55]</span></span>
See [Henselian valuation](#c54235c2-dfc4-4ec1-b3f8-c2f492cfd3e3).


### Unit group {#5bdea912-0506-4615-aab2-2d3df679510a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 17:54]</span></span>
See [Henselian valuation](#c54235c2-dfc4-4ec1-b3f8-c2f492cfd3e3).

If \\(A\\) satisfies [Class field axiom](#463c465b-a799-46a1-9e9c-1e592628a990), \\(v\\) is henselian valuation of \\(A\_{k}\\) with respect to \\(d\\). Then we have following proposition.

{{% proposition %}}
Let \\(L/K\\) be an unramified extension of finite subextensions of \\(\bar{k}/k\\).

1.  The group \\(H\_{T}^{i}(\Gal(L/K), U\_{L})\\) are all trivial.
2.  The group \\(H\_{T}^{0}(\Gal(L/K), A\_{L})\\) is cyclic, generated by an uniformizer \\(\pi\_{L}\\) of \\(L\\).
{{% /proposition %}}

Cf. [Uniformizer](#fc8bb4e8-953c-43a9-bf4c-fa13f2de3cd9), [Unramified](#16aeb477-ff63-4293-abd3-cf8fb879793d).


### Unramified {#16aeb477-ff63-4293-abd3-cf8fb879793d}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-19 Sun 15:02]</span></span>
Let \\(L/K\\) be an extension of finite extensions of \\(\QQ\_{p}\\). Let \\(\mathfrak{o}\_{L}, \mathfrak{o}\_{K}\\) be the integral closure of \\(\ZZ\_{p}\\) in \\(K, L\\). We say \\(L/K\\) is **unramified** if the maximal ideal of \\(\mathfrak{o}\_{K}\\) generates the maximal ideal of \\(\mathfrak{o}\_{L}\\).

For every extension \\(L/K\\) there exists a maximal subextension of \\(L/K\\) which is unramified, denoted by \\(U\\). If this is \\(K\\), we say \\(L/K\\) is **totally ramified**.

If \\([L:U]\\) is not divisible by \\(p\\), then \\(L/K\\) is **tamely ramified**.

The above definition can be generalized to global fields by specifiying the prime ideal.

In class field theory, the phrase \\(L/K\\) is **unramified** means that \\(L/K\\) is unramified over all finite places and every real embedding of \\(K\\) extends to a real embeddings of \\(L\\).

{{% remark %}}
An unramified extension can be nonabelian. It is related to class field tower over \\(K\\).
{{% /remark %}}


### Valuation {#4849a5e6-921e-44eb-928c-b8d0afcfee95}

<span class="timestamp-wrapper"><span class="timestamp">[2021-11-28 Sun 14:38]</span></span>
A **valuation** \\(\abs{\cdot}\\) on a field \\(k\\) is a function defined on \\(k\\) with values in the non-negative real numbers satisfying the following axioms.

1.  \\(\abs{\alpha} = 0\\) if and only if \\(\alpha = 0\\).
2.  \\(\abs{\alpha \beta} = \abs{\alpha} \abs{\beta}\\).
3.  There is a constant \\(C\\) such that \\(\abs{1 + \alpha} \leq C\\) whenever \\(\alpha \leq 1\\).

There always exists **trival valuation** that \\(\abs{\alpha} = 1\\) for all \\(\alpha \neq 0\\).

Two valuations are called **equivalent** if there \\(c > 0\\) such that \\(\abs{\alpha}\_{2} = \abs{\alpha}\_{1}^{c}\\).

Referenced: [Discrete valuation](#42063818-df21-4040-af12-b758687c7110).


### Weil group {#86a2985f-a089-4e4e-943e-d57bbc2b7836}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-26 Sun 17:41]</span></span>
Let \\(k\\) be field, and \\(\bar{k}\\) an algebraic extension. Put \\(G = \Gal(\bar{k}/k)\\) and \\(A\\) be a \\(G\\)-module. Then for subextension \\(K\\) of \\(\bark{k}/k\\), define \\(A\_{K} = A^{\Gal(\bar{k}/K)}\\).

Let \\(d: G \to \hat{\ZZ}\\) be a continuous surjective homomorphism. The **Weil group** of \\(k\\) is the subgroup \\(d^{-1}(\ZZ)\\) of \\(G\\).

The **inertia group** \\(I\_{k}\\) is the kernel of \\(d\\). And maximal unramified extension \\(k^{ur}\\) of \\(k\\) to be the fixed field of \\(I\_{k}\\). For subextension \\(K\\) of \\(\bar{k}/k\\), put \\(I\_{K} = G\_{K} \cap I\_{k}\\) and let \\(K^{ur} = k^{ur} K\\). We say an extension \\(L/K\\) of subextension of \\(\bar{k}/k\\) is unramified if \\(L \subset K^{ur}\\).

Put \\(d\_{K} = \frac{1}{ [\hat{\ZZ}: d(G\_{K})]} d\\), then \\(d\_{K}\\) induces isomorphism \\(\Gal(K^{ur}/K) \cong \hat{ZZ}\\). Given a finite extension \\(L/K\\) of subextensions of \\(\bar{k}/k\\), define the **inertia degree**
\\[f\_{L/K} = [d(G\_{K}) : d(G\_{L})]\\]
and the **ramification index**
\\[e\_{L/K} = [I\_{K}: I\_{L}]\\]

we have
\\[e\_{L/K} f\_{L/K} = [L:K]\\]


### Zeta functions {#0fc0bc6c-e720-49fc-82aa-54a785183202}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-21 Tue 18:58]</span></span>
Let \\(K\\) be a number field. The **Dedekind zeta function** \\(\zeta\_{K}(s)\\) is defined for \\({\rm Re}(s) >1\\)
\\[\zeta\_{K}(s) = \prod\_{\mathfrak{p}}(1 - \nm(\mathfrak{p})^{-s})^{-1}\\]
where \\(\mathfrak{p}\\) runs over the nonzero prime ideals of \\(\mathfrak{o}\_{K}\\).

{{% theorem %}}
The function \\(\zeta\_{K}(s)\\) extends to a meromorphic function on \\(\CC\\) whose only pole is a simple pole at \\(s = 1\\).
{{% /theorem %}}

Cf. [Riemann zeta function](#501b2012-be48-483f-a084-8c6b351c56f8), [Norm](#8d786b1e-4989-4316-821c-c2f9d4151020).


## Arithmetic Geometry {#a49f8fb4-9537-4cda-9374-b80cf5adf912}




### Absolute height {#70a84cf2-2208-4bfb-b632-a29030bb2b03}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 16:42]</span></span>
See [Height](#b61af773-c2dc-4c16-95bb-811f377bef28).


### Absolute value {#2db41c9f-be95-4271-9bea-a24f6bb15d16}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 16:26]</span></span>
An **absolute value** on a field \\(k\\) is a real-valued function
\\[\abs{\cdot}: k \to \linterval{0}{\infty}\\]
with the following properties

1.  \\(\abs{x} = 0\\) if and only if \\(x = 0\\).
2.  \\(\abs{xy} = \abs{x} \abs{y}\\).
3.  \\(\abs{x + y} \leq \abs{x} + \abs{y}\\).

The absolute value is said to be **nonarchimedean** if it satisfies
\\[\abs{x + y} \leq \max \\{ \abs{x}, \abs{y}\\}\\]

Referenced: [Degree formula](#b01cc2f2-1826-410d-be91-3f9b8b918572), [Local degree](#8e21b5ed-602d-40fc-9c33-1ae4e0b1eceb), [Nonarchimedean](#7ee943d6-2948-4c37-9da6-f587989024ee), [Normalized absolute value](#cd4bbc78-d778-458a-840e-c10a7fddd2b6).


### Degree formula {#b01cc2f2-1826-410d-be91-3f9b8b918572}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 16:29]</span></span>
Let \\(k' / k\\) be an extension of number fields, and let \\(v \in M\_{k}\\) be an [Absolute value](#2db41c9f-be95-4271-9bea-a24f6bb15d16) on \\(k\\). Then
\\[\sum\_{w \in M\_{k'}, w | v} [k'\_{w} : k\_{v}] = [k' : k]\\]
where \\(k\_{v}\\) is the \\(v\\) completion of \\(k\\).


### Dirichlet theorem {#03b1f1f9-ba97-4c71-9c6e-1c155c8a45e2}



{{% theorem %}}
Let \\(\alpha \in \RR\\) with \\(\alpha \not \in \QQ\\). Then there are infinitely many rational number \\(p/q \in \QQ\\) such that
\\[\abs{\alpha - \frac{p}{q}} < \frac{1}{q^{2}}\\]
{{% /theorem %}}

The constant on the right hand side can be refined to \\(\frac{1}{\sqrt{5}q^{2}}\\), which can not be further required for \\(\alpha = \frac{-1 + \sqrt{5}}{2}\\).

Referenced: [Roth's theorem](#da5f05dd-6b31-486e-bfeb-21fb08e8411f).


### Elliptic curve {#107227f3-6542-4e06-b8e4-6d9b122f9533}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-22 Fri 20:50]</span></span>
An **elliptic curve** \\(E\\) over \\(K\\) is a nonsingular projective curve of genus \\(1\\), which comes equipped with a rational point \\(\OO \in E(K)\\) the **origin**. A **morphism** \\(E \to E'\\) between elliptic curves over \\(K\\) is a morphism of \\(K\\)-schemes which preserves the origin. It is an **isomorphism** if it is an isomorphism of \\(K\\)-schemes.

The following theorem shows the elliptic curve can always be realized as a plane cubic curve.

{{% theorem %}}
Let \\(E/K\\) be an elliptic curve. Then \\(E\\) is isomorphic to a plane cubic curve with affine equation
\\[y^{2} + a\_{1} xy + a\_{3}y = x^{3} + a\_{2}x^{2} + a\_{4}x + a\_{6}\\]
for some \\(a\_{1}, \cdots, a\_{4}, a\_{6} \in K\\) such that the above equation has no singularities.
{{% /theorem %}}

Referenced: [Origin](#9eea015c-0103-459a-b4f5-7f1081e9e303), [Group law](#0e4cd31b-afae-4dda-a22d-04689e2e0b95), [Isogeny](#3271ffe5-7252-466c-89a4-41f7e53ec99b).


#### Origin {#9eea015c-0103-459a-b4f5-7f1081e9e303}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-22 Fri 21:02]</span></span>
See [Elliptic curve](#107227f3-6542-4e06-b8e4-6d9b122f9533).


#### Group law {#0e4cd31b-afae-4dda-a22d-04689e2e0b95}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-22 Fri 20:50]</span></span>
We write \\(\pic^{\circ} X\\) for the subgroup of divisor classes of degree \\(0\\).

{{% remark %}}
This is a special case of the [Jacobian variety](#2e0f7a3a-56e3-4903-9599-5b27a3491304).
{{% /remark %}}

{{% theorem %}}
Let \\(E\\) be an elliptic curve over \\(K\\). There is a bijection \\(E(K) \cong \pic^{\circ}E\\) sending \\(P\\) ot the class \\((P) - (O)\\).
{{% /theorem %}}

Cf. [Elliptic curve](#107227f3-6542-4e06-b8e4-6d9b122f9533).

The group is defined by \\(P + Q = R\\), where \\((P) + (Q) = ( R) + (O)\\).


#### <span class="org-todo todo TODO">TODO</span> Dual {#24635174-b03e-4be0-b1a7-10134be2dc75}


#### Isogeny {#3271ffe5-7252-466c-89a4-41f7e53ec99b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-22 Fri 21:16]</span></span>
An **isogeny** is a morphism between [Elliptic curves](#107227f3-6542-4e06-b8e4-6d9b122f9533) which is finite.

Referenced: [Isogeny](#35538f98-babe-4fc7-82a3-81a3964c035a).


#### Riemann hypothesis {#955d7ac9-28e8-4408-83dd-e3e0c19ccb0c}



{{% theorem %}}
Let \\(E/ \mathbb{F}\_{q}\\) be an elliptic curve, and define \\(a(E) = q + 1 - \shar(\mathbb{F}\_{q})\\). Then \\(\abs{a} \leq 2 \sqrt{q}\\).
{{% /theorem %}}


#### Tate module {#efff1c69-c1ec-420f-aefd-8b20f081b357}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-22 Fri 21:19]</span></span>
Let \\(l\\) be a prime number unequal to the characteristic of \\(K\\). The **Tate module** of \\(E\\) is the inverse limit
\\[T\_{l}E = \varprojlim E(\bar{K})[l^{n}]\\]
A free \\(\ZZ\_{l}\\)-module of rank \\(2\\). The **rational Tate module** is \\(V\_{l}E = T\_{l}E \otimes\_{\ZZ\_{l}} \QQ\_{l}\\). Here \\(E(\bar{K})[m]\\) denote the number of \\(m\\) torsion points of \\(E(\bar{K})\\).

Referenced: [Tate's isogeny theorem](#c1c42e73-1cf9-4f4c-84d0-a2e7f79e6a02).


#### Tate's isogeny theorem {#c1c42e73-1cf9-4f4c-84d0-a2e7f79e6a02}



{{% theorem %}}
Let \\(E\\) and \\(E'\\) be elliptic curves over a finite field \\(K\\). The map
\\[\Hom(E, E') \otimes\_{Z} \QQ\_{l} \to \Hom\_{G\_{K}}(V\_{l}E, V\_{l}E')\\]
is an isomorphism. Here \\(G\_{K}\\) is the absolute Galois group of \\(K\\).
{{% /theorem %}}

Cf. [Tate module](#efff1c69-c1ec-420f-aefd-8b20f081b357).


#### Mordell-Weil theorem {#61daf363-196f-41c1-838e-a7b5223fe690}

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


### Finiteness of class group {#0a53c20c-a6f4-4206-b485-269f5ecf0a89}



{{% proposition %}}
There are finitely many ideal classes in \\(K\\).
{{% /proposition %}}

Cf. [Ideal class](#a324fd37-15e1-4ea9-950d-645eb3e3bc74).


### Finiteness of point under height {#842e8863-e341-4c64-aa58-9c4b45ce1d12}

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


### Finiteness of unit group {#3540245e-1e24-4798-bc82-4dfc39f89fde}



{{% proposition %}}
The abelian group \\(\OO\_{K,S}\\) is finitely generated.
{{% /proposition %}}

Cf. [S-integer](#4bf8e1a2-074e-4e2e-8158-867d32fcfe98).


### Height {#b61af773-c2dc-4c16-95bb-811f377bef28}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 16:36]</span></span>
Let \\(k\\) be a number field and let \\(P = (x\_{0}, x\_{1}, \cdots, x\_{n}) \in \PP^{n}(k)\\) be a point whose homogeneous coordinates are chosen in \\(k\\). The **height** is the quantity
\\[H\_{k}(P) = \prod\_{v \in M\_{k}} \max \\{\norm{x\_{0}}\_{v}, \norm{x\_{1}}\_{v}, \cdots, \norm{x\_{n}}\_{v}\\}\\]
And define the **logarithmic height** by
\\[h\_{k} = \log H\_{k}(P)\\]
Cf. [Normalized absolute value](#cd4bbc78-d778-458a-840e-c10a7fddd2b6).

We have preceding formula for height in extension field

{{% lemma %}}
If \\(k\\) be a number field and \\(k'/k\\) a finite field extension. Then
\\[H\_{k'}(P) = H\_{k}(P)^{[k':k]}\\]
{{% /lemma %}}

By above lemma, we can define the **absolute height** on \\(\PP^{n}\\) by
\\[H: \PP^{n}(\bar{Q}) \to \linterval{0}{\infty}\\]
\\[H(P) = H\_{k}(P)^{1/[k: \QQ]}\\]
where \\(P \in \PP^{n}(k)\\). The **absolute logarithmic height** is defined similarly.

We can extend the definition of height to varieties. Let \\(\phi: V \to \PP^{n}\\) is a morphism, then we can define
\\[h\_{\phi}(P) = h(\phi(P))\\]
The definition of this height is dependent on the choice of the morphism \\(\phi\\).

Referenced: [Absolute height](#70a84cf2-2208-4bfb-b632-a29030bb2b03).


### <span class="org-todo todo TODO">TODO</span> Jacobian variety {#2e0f7a3a-56e3-4903-9599-5b27a3491304}



Referenced: [Group law](#0e4cd31b-afae-4dda-a22d-04689e2e0b95).


### Local degree {#8e21b5ed-602d-40fc-9c33-1ae4e0b1eceb}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 16:31]</span></span>
Let \\(v \in M\_{k}\\) be an [Absolute value](#2db41c9f-be95-4271-9bea-a24f6bb15d16) on number field \\(k\\). The **local degree** of \\(v\\) is the number
\\[n\_{v} = [k\_{v} : \QQ\_{v}]\\]


### Nonarchimedean {#7ee943d6-2948-4c37-9da6-f587989024ee}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 16:29]</span></span>
See [Absolute value](#2db41c9f-be95-4271-9bea-a24f6bb15d16).


### Normalized absolute value {#cd4bbc78-d778-458a-840e-c10a7fddd2b6}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 16:32]</span></span>
Let \\(v \in M\_{k}\\) be an [Absolute value](#2db41c9f-be95-4271-9bea-a24f6bb15d16) on number field \\(k\\). The **normalized absolute value** of \\(v\\) associated to \\(v\\) is
\\[\norm{x}\_{v} = \abs{x}\_{v}^{n\_{v}}\\]

For normalized absolute value, we have the **product formula**, for \\(x \in k^{\* }\\), we have
\\[\prod\_{v \in M\_{k}} \norm{x}\_{v} = 1\\]

Referenced: [Height](#b61af773-c2dc-4c16-95bb-811f377bef28).


### Roth's theorem {#da5f05dd-6b31-486e-bfeb-21fb08e8411f}



{{% theorem %}}
Let \\(\alpha \in \bar{K}\\), and let \\(v \in S\_{K}\\). Extend \\(\abs{\cdot}\_{v}\\) to an absolute value \\(\abs{\cdot}\_{v}\\) on \\(K(\alpha)\\). For all \\(\epsilon > 0\\) and every \\(C > 0\\), the inequality
\\[\abs{\alpha - x}\_{v} < \frac{C}{H\_{K}(x)^{2 + \epsilon}}\\]
has only finitely many solutions in \\(x \in K\\).
{{% /theorem %}}

Cf. [Dirichlet theorem](#03b1f1f9-ba97-4c71-9c6e-1c155c8a45e2).


### S-integer {#4bf8e1a2-074e-4e2e-8158-867d32fcfe98}

<span class="timestamp-wrapper"><span class="timestamp">[2021-10-19 Tue 16:34]</span></span>
The ring of **S-integers** of \\(k\\) is defined to be
\\[R\_{S} = \\{x \in k \mid \abs{x}\_{v} \leq 1 \text{ for all } v \in M\_{k}, v \not \in S\\}\\]

We can also characterize the rings of integers of \\(k\\) by \\(M\_{k}^{\infty}\\)-integers of \\(k\\).

Referenced: [S-unit](#dc0448dc-4990-4bdb-882b-215b1b17f653), [Finiteness of unit group](#3540245e-1e24-4798-bc82-4dfc39f89fde).


## Bibliography {#535afb2f-2584-4cd2-82cf-56f94894f888}

<a id="steinberg2012"></a>[steinberg2012] Steinberg, Representation Theory of Finite Groups: An Introductory Approach, Springer (2012). [↩](#19580479584332ed50a4af7bf7f3f201)

<a id="kirillov2016"></a>[kirillov2016] Kirillov, Quiver Representations and Quiver Varieties, American Mathematical Society (2016). [↩](#df38f5636bec59103a70400bed4764c9)

<a id="dieck2008"></a>[dieck2008] tom Dieck, Algebraic Topology, European Mathematical Society (2008). [↩](#5ad6139c99b6d2508f6ef6f11ce7f09d)

<a id="CLS2011"></a>[CLS2011] Cox, Little & Schenck, Toric Varieties, American Mathematical Society (2011). [↩](#56219725c40008d847a57904e2a7e775)

<a id="milne2017"></a>[milne2017] Milne, Algebraic Groups: The Theory of Group Schemes of Finite Type over a Field, Cambridge University Press (2017). [↩](#868cb56e509be613430cca58b1ead9f3)

<a id="sernesi2006"></a>[sernesi2006] Sernesi, Deformations of Algebraic Schemes, Springer Berlin Heidelberg (2006). [↩](#7cd3e01b28c2ede526fee96d60981f02)

<a id="nakajima1999"></a>[nakajima1999] Nakajima, Lectures on Hilbert Schemes of Points on Surfaces, American Mathematical Society (1999). [↩](#24e67c8afe5163064e4018cb5a5cbd8a)

<a id="milne2020a"></a>[milne2020a] @miscMilne2020a,
  title = Exercises of Algebraic Number Theory (v3.08),
  author = Milne, J. S.,
  year = 2020
 [↩](#b4a5092d5be50d9bf5c61da5a15def18)

<a id="kedlaya2021"></a>[kedlaya2021] Kedlaya, Note on Class Field Theory, (2021). [↩](#b71f719ac1b346d4c039df59c580b69c)
