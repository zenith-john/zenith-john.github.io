+++
title = "Questions of interest"
author = ["Zenith John"]
publishDate = 2021-12-31
draft = false
+++

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-31 Fri 14:25]</span></span>
This page serves as a list of some problems I care about with some additional remarks. For most papers referenced, I only read the reviews or abstracts.


## MNOP conjecture {#0f04a1ba-2fda-4cdd-906e-b17cd0d9ec50}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-31 Fri 14:27]</span></span>
The MNOP conjectures are proposed in [<span id="71c689e646b740e15274e4c45df483c9"><a href="#maulik2006" title="Maulik, Nekrasov, Okounkov \&amp; Pandharipande, Gromov\textendash{{Witten}} Theory and {{Donaldson}}\textendash{{Thomas}} Theory, {{I}}, {Compositio Mathematica}, v(05), 1263--1285 (2006).">maulik2006</a></span>] (primary case), [<span id="a94d6b5af3fa210c91d9309d3da103af"><a href="#maulik2006a" title="Maulik, Nekrasov, Okounkov \&amp; Pandharipande, Gromov\textendash{{Witten}} Theory and {{Donaldson}}\textendash{{Thomas}} Theory, {{II}}, {Compositio Mathematica}, v(05), 1286--1304 (2006).">maulik2006a</a></span>] (descent case). A series of conjectures states some kind of equivalence between the generating series of Gromov-Witten invariants and Donaldson-Thomas invariants. The GW/DT correspondence in primary case was proved in toric case [<span id="e25e310ddc34f4e55392b368230bb1bf"><a href="#maulik2011" title="Maulik, Oblomkov, Okounkov \&amp; Pandharipande, Gromov-{{Witten}}/{{Donaldson-Thomas}} Correspondence for Toric 3-Folds, {Inventiones mathematicae}, v(2), 435--479 (2011).">maulik2011</a></span>].

A big step in MNOP conjecture is the introduction of Pandharipande-Thomas (PT) invariants, which is introduced in [<span id="431caa59e2d75afb6b38719ad8dca5d9"><a href="#pandharipande2009" title="Pandharipande \&amp; Thomas, Curve Counting via Stable Pairs in the Derived Category, {Inventiones mathematicae}, v(2), 407--447 (2009).">pandharipande2009</a></span>]. By replacing the Hilbert scheme by moduli space of stable pairs, the generating series becomes easier to handle. The two authors conjectured the correspondence between DT and PT, which was proved in [<span id="f9133d12da33e9b2ae5ee8e0f8d3fa3a"><a href="#toda2010" title="Toda, Curve Counting Theories via Stable Objects {{I}}. {{DT}}/{{PT}} Correspondence, {Journal of the American Mathematical Society}, v(4), 1119--1157 (2010).">toda2010</a></span>] and [<span id="85e75071c648af3e4648f2c9ab2fcc28"><a href="#bridgeland2011" title="Bridgeland, Hall Algebras and Curve-Counting Invariants, {Journal of the American Mathematical Society}, v(4), 969--998 (2011).">bridgeland2011</a></span>]. It is worth noting that the DT/PT correspondence can be viewed as a special case of wall-crossing.

The establishment of GW/PT correspondence seems to be easier than GW/DT correspondence. GW/PT correspondence in toric variety case with descent insertion was given in [<span id="909250c4d905735b782534d99f6095f5"><a href="#pandharipande2014" title="Pandharipande \&amp; Pixton, Gromov\textendash{{Witten}}/Pairs Descendent Correspondence for Toric 3\textendash Folds, {Geometry \&amp; Topology}, v(5), 2747--2821 (2014).">pandharipande2014</a></span>] and the local complete intersection in product of projective space case was established latter in [<span id="88221b9c6d4636326d6b0764fc915f73"><a href="#pandharipande2017" title="Pandharipande \&amp; Pixton, Gromov-{{Witten}}/{{Pairs}} Correspondence for the Quintic 3-Fold, {Journal of the American Mathematical Society}, v(2), 389--449 (2017).">pandharipande2017</a></span>]. The explicit formula of the matrix coefficient is given in [<span id="5475808075c4e5ae5aa873cba4119875"><a href="#oblomkov2020" title="Oblomkov, Okounkov \&amp; Pandharipande, {{GW}}/{{PT Descendent Correspondence}} via {{Vertex Operators}}, {Communications in Mathematical Physics}, v(3), 1321--1359 (2020).">oblomkov2020</a></span>].

As an application, based on GW/PT correspondence, in toric variety case, Virasoro constraint for stable pairs and therefore for GW theory is obtained in [<span id="b79997d2a1ead8b84a185c6680e7e9db"><a href="#moreira2020" title="Moreira, Oblomkov, Okounkov \&amp; Pandharipande, Virasoro Constraints for Stable Pairs on Toric 3-Folds, {arXiv:2008.12514 [math]}, v(), (2020).">moreira2020</a></span>].

Despite these advances, as far as I know, the most general form of the conjecture is still open.


## Homological Mirror Symmetry {#d9c04b5b-0121-45f9-88bb-6f83ea9bdf9a}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-31 Fri 14:46]</span></span>
Homological mirror symmetry was proposed by Kontsevich in [<span id="44000f73d8f646d7fa90b5bc5a28bf9b"><a href="#kontsevich1994" title="Kontsevich, Homological {{Algebra}} of {{Mirror Symmetry}}, 120--139, in in: {Proceedings of the {{International Congress}} of {{Mathematicians}}}, edited by {Birkhauser} (1994)">kontsevich1994</a></span>], which is one of the most profound conjecture in geometry. Roughly speaking, it suggests some deep similarities  between symplectic geometry and complex algebraic geometry of Calabi-Yau manifolds. More specifically, it states some variant of Fukaya category on \\(X\\) is equivalent to derived category of coherent sheaves on \\(X^{\vee}\\), its mirror variety.

The physics of mirror symmetry is 2d SCFT, and homological mirror symmetry is one way to describe this duality in mathematics. Another famous conjecture is SYZ conjecture. The homological mirror symmetry is related to D-branes, where 'derived' category then arises (For example, see [<span id="098282e46a95b270bc2b59e3df1baade"><a href="#aspinwall2009" title="Aspinwall, Dirichlet Branes and Mirror Symmetry, {American Mathematical Society ; Clay Mathematics Institute} (2009).">aspinwall2009</a></span>]).

Like the case of MNOP conjecture, the homological mirror symmetry is checked in many cases. Though the case related to physics is Calabi-Yau 3-fold, the conjecture was first checked in the most simple CY variety, elliptic curve, in [<span id="70c949c120546c33ce64bbe3507f4bdd"><a href="#polishchuk1998" title="Polishchuk \&amp; Zaslow, Categorical Mirror Symmetry: {{The}} Elliptic Curve, {Advances in Theoretical and Mathematical Physics}, v(2), 443--470 (1998).">polishchuk1998</a></span>], later for quartic surfaces in [<span id="cffc8537b21f2cb01d40656dee905fb8"><a href="#seidel2015" title="Seidel, Homological Mirror Symmetry for the Quartic Surface, {Memoirs of the American Mathematical Society}, v(1116), 0--0 (2015).">seidel2015</a></span>], also for CY hypersurfaces in [<span id="0f78a6cbd09db85bb4133c0230ce77f4"><a href="#sheridan2015" title="Sheridan, Homological Mirror Symmetry for {{Calabi}}\textendash{{Yau}} Hypersurfaces in Projective Space, {Inventiones mathematicae}, v(1), 1--186 (2015).">sheridan2015</a></span>].

The conjecture has many variants. For example, the conjecture may be extended to Laudau-Ginzburg models and therefore Fano varieties, for example in [<span id="51f35accde243514c8fce69e6b548f46"><a href="#auroux2006" title="Auroux, Katzarkov \&amp; Orlov, Mirror Symmetry for Del {{Pezzo}} Surfaces: Vanishing Cycles and Coherent Sheaves, {Inventiones Mathematicae}, v(3), 537--582 (2006).">auroux2006</a></span>]. Also, the coherent sheaves may be replaced by constructible sheaves, for example in [<span id="91e0e36c6455319bb0d413b84ee12ef7"><a href="#nadler2009" title="Nadler \&amp; Zaslow, Constructible Sheaves and the {{Fukaya}} Category, {Journal of the American Mathematical Society}, v(1), 233--286 (2009).">nadler2009</a></span>], and Fukaya category may be replaced by wrapped Fukaya category as in [<span id="d6b9979569c7a1e5950882f88707ce51"><a href="#abouzaid2013" title="Abouzaid, Auroux, Efimov, Katzarkov \&amp; Orlov, Homological Mirror Symmetry for Punctured Spheres, {Journal of the American Mathematical Society}, v(4), 1051--1083 (2013).">abouzaid2013</a></span>].

Also similar to the case of MNOP, the most general case, as far as I know, is wide open.


## Extending Donaldson-Thomas Theory {#09bc15c3-210d-4180-864d-232601316a27}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-31 Fri 15:26]</span></span>
In [<span id="7660f0957f2344ea4392e8be1692ad6a"><a href="#donaldson1998" title="Donaldson \&amp; Thomas, Gauge Theory in Higher Dimensions, {The geometric universe (Oxford, 1996)}, v(), 31--47 (1998).">donaldson1998</a></span>], Donaldson and Thomas suggested some extension of 3 dimensional Chern-Simons theory and 4 dimensional Donaldson theory to higher dimensional manifolds, for example Calabi-Yau 3-fold, \\(G\_{2}\\) manifold and \\(Spin(7)\\) manifold (also higher dimesional CY varieties). For a long time, only CY3 case is established in [<span id="5594b63044942e72d0c5c1c208a8c2af"><a href="#thomas2000" title="Thomas, A Holomorphic {{Casson}} Invariant for {{Calabi-Yau}} 3-Folds, and Bundles on \${{K3}}\$ Fibrations, {Journal of Differential Geometry}, v(2), 367--438 (2000).">thomas2000</a></span>] and widely studied and other 2 cases is unknown.

By the injection \\(SU(4) \to Spin(7)\\), the CY 4-fold can be viewed as \\(Spin(7)\\) manifold. However, the problem is the obstruction theory has more than two terms and methods of [<span id="6d3562706b4b416b46b9c7a4eca8c9d0"><a href="#behrend1997" title="Behrend \&amp; Fantechi, The Intrinsic Normal Cone, {Inventiones mathematicae}, v(1), 45--88 (1997).">behrend1997</a></span>] can not be applied. Recently, in [<span id="c81f85e2d1dcb6ace57d8db11b405155"><a href="#cao2015" title="Cao \&amp; Leung, Donaldson-{{Thomas}} Theory for {{Calabi-Yau}} 4-Folds, {arXiv:1407.7659 [math]}, v(), (2015).">cao2015</a></span>] (special case) and [<span id="4c26e00026bdeabe129a01c41cc6cdc3"><a href="#borisov2017" title="Borisov \&amp; Joyce, Virtual Fundamental Classes for Moduli Spaces of Sheaves on {{Calabi}}\textendash{{Yau}} Four-Folds, {Geometry \&amp; Topology}, v(6), 3231--3311 (2017).">borisov2017</a></span>] (general case), the authors established Donaldson-Thoms theory for CY 4-fold. Many results for CY3 can be transported to CY4 case, including some cases of MNOP conjecture (also in [<span id="c81f85e2d1dcb6ace57d8db11b405155"><a href="#cao2015" title="Cao \&amp; Leung, Donaldson-{{Thomas}} Theory for {{Calabi-Yau}} 4-Folds, {arXiv:1407.7659 [math]}, v(), (2015).">cao2015</a></span>]), the DT/PT correspondence in [<span id="819973f55419ababa55f22967b8b37c9"><a href="#cao2020" title="Cao \&amp; Kool, Curve Counting and {{DT}}/{{PT}} Correspondence for {{Calabi-Yau}} 4-Folds, {Advances in Mathematics}, v(), 107371 (2020).">cao2020</a></span>], and a lot more. It is then a natural question, whether Donaldson-Thomas invariants can be generalized to higher dimensions, since we are not using special holonomy in construction. As a reminder, Gromov-Witten theory is well defined for varieties of arbitrary dimension.

Apart from extending Donaldson-Thomas theory to higher dimensions, there are some variants and refinement of Donaldson-Thomas theory, for example [<span id="99afc40046801f02eb8f58defc2ea74f"><a href="#szendroi2008" title="Szendr\H oi, Non-Commutative {{Donaldson}}\textendash{{Thomas}} Invariants and the Conifold, {Geometry \&amp; Topology}, v(2), 1171--1202 (2008).">szendroi2008</a></span>] and [<span id="c827a57522bdbf702e67749c50e2df36"><a href="#kontsevich2011a" title="Kontsevich \&amp; Soibelman, Cohomological {{Hall}} Algebra, Exponential {{Hodge}} Structures and Motivic {{Donaldson}}\textendash{{Thomas}} Invariants, {Communications in Number Theory and Physics}, v(2), 231--252 (2011).">kontsevich2011a</a></span>]. In conifold case [<span id="7e42b2f2ed2a5e2191272a2cb9410cf8"><a href="#nagao2010" title="Nagao \&amp; Nakajima, Counting {{Invariant}} of {{Perverse Coherent Sheaves}} and Its {{Wall-crossing}}, {International Mathematics Research Notices}, v(), rnq195 (2010).">nagao2010</a></span>], the noncommutative case is related to original one by wall-crossing. Again in confiold case [<span id="da0a139573e280c8269dbceaff593e16"><a href="#morrison2012" title="Morrison, Mozgovoy, Nagao \&amp; Szendr\H oi, Motivic {{Donaldson}}\textendash{{Thomas}} Invariants of the Conifold and the Refined Topological Vertex, {Advances in Mathematics}, v(4), 2065--2093 (2012).">morrison2012</a></span>], the motivic refinement matches refined topological vertex as original DT theory matches topological vertex.

Another aspect of extending Donaldson-Thomas theory seems more astonishing. That is we can define Donaldson-Thomas theory for categories by notation of stability from Bridgeland and definition of Calabi-Yau categories. This idea is first proposed in [<span id="3b2bace0f82473dfaf9bfe3060c2929b"><a href="#kontsevich2008" title="Kontsevich \&amp; Soibelman, Stability Structures, Motivic {{Donaldson-Thomas}} Invariants and Cluster Transformations, {arXiv:0811.2435 [hep-th]}, v(), (2008).">kontsevich2008</a></span>] with some conjectural requirement. This kind of Donalson-Thomas theory is directly related to wall crossing and interacts more with algebras, for example in [<span id="bf093cafee676d3618a854647366bdec"><a href="#davison2020" title="Davison \&amp; Meinhardt, Cohomological {{Donaldson}}\textendash{{Thomas}} Theory of a Quiver with Potential and Quantum Enveloping Algebras, {Inventiones mathematicae}, v(3), 777--871 (2020).">davison2020</a></span>].

Inspired by homological mirror symmetry and MNOP conjecture, I suppose there exists some kind of counting theory for symplectic manifold, since Gromov-Witten invariants can be defined for symplectic manifold and Donaldson-Thomas theory counts some kind of special sheaves in complex geometry. Will Donovan suggests that DT theory for symplectic manifold may correspond to counting of special Lagrangians, but nobody seems to explore it before.


## References {#1cb49c92-8747-4a1f-bd9c-04c227a3096b}

<span class="timestamp-wrapper"><span class="timestamp">[2021-12-31 Fri 15:03]</span></span>
<a id="maulik2006"></a>[maulik2006] Maulik, Nekrasov, Okounkov & Pandharipande, Gromov\textendashWitten Theory and Donaldson\textendashThomas Theory, I, <i>Compositio Mathematica</i>, <b>142(05)</b>, 1263-1285 (2006). <a href="http://dx.doi.org/10.1112/S0010437X06002302">doi</a>. [↩](#71c689e646b740e15274e4c45df483c9)

<a id="maulik2006a"></a>[maulik2006a] Maulik, Nekrasov, Okounkov & Pandharipande, Gromov\textendashWitten Theory and Donaldson\textendashThomas Theory, II, <i>Compositio Mathematica</i>, <b>142(05)</b>, 1286-1304 (2006). <a href="http://dx.doi.org/10.1112/S0010437X06002314">doi</a>. [↩](#a94d6b5af3fa210c91d9309d3da103af)

<a id="maulik2011"></a>[maulik2011] Maulik, Oblomkov, Okounkov & Pandharipande, Gromov-Witten/Donaldson-Thomas Correspondence for Toric 3-Folds, <i>Inventiones mathematicae</i>, <b>186(2)</b>, 435-479 (2011). <a href="http://dx.doi.org/10.1007/s00222-011-0322-y">doi</a>. [↩](#e25e310ddc34f4e55392b368230bb1bf)

<a id="pandharipande2009"></a>[pandharipande2009] Pandharipande & Thomas, Curve Counting via Stable Pairs in the Derived Category, <i>Inventiones mathematicae</i>, <b>178(2)</b>, 407-447 (2009). <a href="http://dx.doi.org/10.1007/s00222-009-0203-9">doi</a>. [↩](#431caa59e2d75afb6b38719ad8dca5d9)

<a id="toda2010"></a>[toda2010] Toda, Curve Counting Theories via Stable Objects I. DT/PT Correspondence, <i>Journal of the American Mathematical Society</i>, <b>23(4)</b>, 1119-1157 (2010). <a href="http://dx.doi.org/10.1090/S0894-0347-10-00670-3">doi</a>. [↩](#f9133d12da33e9b2ae5ee8e0f8d3fa3a)

<a id="bridgeland2011"></a>[bridgeland2011] Bridgeland, Hall Algebras and Curve-Counting Invariants, <i>Journal of the American Mathematical Society</i>, <b>24(4)</b>, 969-998 (2011). <a href="http://dx.doi.org/10.1090/S0894-0347-2011-00701-7">doi</a>. [↩](#85e75071c648af3e4648f2c9ab2fcc28)

<a id="pandharipande2014"></a>[pandharipande2014] Pandharipande & Pixton, Gromov\textendashWitten/Pairs Descendent Correspondence for Toric 3\textendash Folds, <i>Geometry & Topology</i>, <b>18(5)</b>, 2747-2821 (2014). <a href="http://dx.doi.org/10.2140/gt.2014.18.2747">doi</a>. [↩](#909250c4d905735b782534d99f6095f5)

<a id="pandharipande2017"></a>[pandharipande2017] Pandharipande & Pixton, Gromov-Witten/Pairs Correspondence for the Quintic 3-Fold, <i>Journal of the American Mathematical Society</i>, <b>30(2)</b>, 389-449 (2017). <a href="http://dx.doi.org/10.1090/jams/858">doi</a>. [↩](#88221b9c6d4636326d6b0764fc915f73)

<a id="oblomkov2020"></a>[oblomkov2020] Oblomkov, Okounkov & Pandharipande, GW/PT Descendent Correspondence via Vertex Operators, <i>Communications in Mathematical Physics</i>, <b>374(3)</b>, 1321-1359 (2020). <a href="http://dx.doi.org/10.1007/s00220-020-03686-4">doi</a>. [↩](#5475808075c4e5ae5aa873cba4119875)

<a id="moreira2020"></a>[moreira2020] Moreira, Oblomkov, Okounkov & Pandharipande, Virasoro Constraints for Stable Pairs on Toric 3-Folds, <i>arXiv:2008.12514 [math]</i>,  (2020). [↩](#b79997d2a1ead8b84a185c6680e7e9db)

<a id="kontsevich1994"></a>[kontsevich1994] Kontsevich, Homological Algebra of Mirror Symmetry, 120-139, in in: Proceedings of the International Congress of Mathematicians, edited by Birkhauser (1994) [↩](#44000f73d8f646d7fa90b5bc5a28bf9b)

<a id="aspinwall2009"></a>[aspinwall2009] Aspinwall, Dirichlet Branes and Mirror Symmetry, American Mathematical Society ; Clay Mathematics Institute (2009). [↩](#098282e46a95b270bc2b59e3df1baade)

<a id="polishchuk1998"></a>[polishchuk1998] Polishchuk & Zaslow, Categorical Mirror Symmetry: The Elliptic Curve, <i>Advances in Theoretical and Mathematical Physics</i>, <b>2(2)</b>, 443-470 (1998). <a href="http://dx.doi.org/10.4310/ATMP.1998.v2.n2.a9">doi</a>. [↩](#70c949c120546c33ce64bbe3507f4bdd)

<a id="seidel2015"></a>[seidel2015] Seidel, Homological Mirror Symmetry for the Quartic Surface, <i>Memoirs of the American Mathematical Society</i>, <b>236(1116)</b>, 0-0 (2015). <a href="http://dx.doi.org/10.1090/memo/1116">doi</a>. [↩](#cffc8537b21f2cb01d40656dee905fb8)

<a id="sheridan2015"></a>[sheridan2015] Sheridan, Homological Mirror Symmetry for Calabi\textendashYau Hypersurfaces in Projective Space, <i>Inventiones mathematicae</i>, <b>199(1)</b>, 1-186 (2015). <a href="http://dx.doi.org/10.1007/s00222-014-0507-2">doi</a>. [↩](#0f78a6cbd09db85bb4133c0230ce77f4)

<a id="auroux2006"></a>[auroux2006] Auroux, Katzarkov & Orlov, Mirror Symmetry for Del Pezzo Surfaces: Vanishing Cycles and Coherent Sheaves, <i>Inventiones Mathematicae</i>, <b>166(3)</b>, 537-582 (2006). <a href="http://dx.doi.org/10.1007/s00222-006-0003-4">doi</a>. [↩](#51f35accde243514c8fce69e6b548f46)

<a id="nadler2009"></a>[nadler2009] Nadler & Zaslow, Constructible Sheaves and the Fukaya Category, <i>Journal of the American Mathematical Society</i>, <b>22(1)</b>, 233-286 (2009). <a href="http://dx.doi.org/10.1090/S0894-0347-08-00612-7">doi</a>. [↩](#91e0e36c6455319bb0d413b84ee12ef7)

<a id="abouzaid2013"></a>[abouzaid2013] Abouzaid, Auroux, Efimov, Katzarkov & Orlov, Homological Mirror Symmetry for Punctured Spheres, <i>Journal of the American Mathematical Society</i>, <b>26(4)</b>, 1051-1083 (2013). <a href="http://dx.doi.org/10.1090/S0894-0347-2013-00770-5">doi</a>. [↩](#d6b9979569c7a1e5950882f88707ce51)

<a id="donaldson1998"></a>[donaldson1998] Donaldson & Thomas, Gauge Theory in Higher Dimensions, <i>The geometric universe (Oxford, 1996)</i>,  31-47 (1998). [↩](#7660f0957f2344ea4392e8be1692ad6a)

<a id="thomas2000"></a>[thomas2000] Thomas, A Holomorphic Casson Invariant for Calabi-Yau 3-Folds, and Bundles on \$K3\$ Fibrations, <i>Journal of Differential Geometry</i>, <b>54(2)</b>, 367-438 (2000). <a href="http://dx.doi.org/10.4310/jdg/1214341649">doi</a>. [↩](#5594b63044942e72d0c5c1c208a8c2af)

<a id="behrend1997"></a>[behrend1997] Behrend & Fantechi, The Intrinsic Normal Cone, <i>Inventiones mathematicae</i>, <b>128(1)</b>, 45-88 (1997). <a href="http://dx.doi.org/10.1007/s002220050136">doi</a>. [↩](#6d3562706b4b416b46b9c7a4eca8c9d0)

<a id="cao2015"></a>[cao2015] Cao & Leung, Donaldson-Thomas Theory for Calabi-Yau 4-Folds, <i>arXiv:1407.7659 [math]</i>,  (2015). [↩](#c81f85e2d1dcb6ace57d8db11b405155)

<a id="borisov2017"></a>[borisov2017] Borisov & Joyce, Virtual Fundamental Classes for Moduli Spaces of Sheaves on Calabi\textendashYau Four-Folds, <i>Geometry & Topology</i>, <b>21(6)</b>, 3231-3311 (2017). <a href="http://dx.doi.org/10.2140/gt.2017.21.3231">doi</a>. [↩](#4c26e00026bdeabe129a01c41cc6cdc3)

<a id="cao2020"></a>[cao2020] Cao & Kool, Curve Counting and DT/PT Correspondence for Calabi-Yau 4-Folds, <i>Advances in Mathematics</i>, <b>375</b>, 107371 (2020). <a href="http://dx.doi.org/10.1016/j.aim.2020.107371">doi</a>. [↩](#819973f55419ababa55f22967b8b37c9)

<a id="szendroi2008"></a>[szendroi2008] Szendr\H oi, Non-Commutative Donaldson\textendashThomas Invariants and the Conifold, <i>Geometry & Topology</i>, <b>12(2)</b>, 1171-1202 (2008). <a href="http://dx.doi.org/10.2140/gt.2008.12.1171">doi</a>. [↩](#99afc40046801f02eb8f58defc2ea74f)

<a id="kontsevich2011a"></a>[kontsevich2011a] Kontsevich & Soibelman, Cohomological Hall Algebra, Exponential Hodge Structures and Motivic Donaldson\textendashThomas Invariants, <i>Communications in Number Theory and Physics</i>, <b>5(2)</b>, 231-252 (2011). <a href="http://dx.doi.org/10.4310/CNTP.2011.v5.n2.a1">doi</a>. [↩](#c827a57522bdbf702e67749c50e2df36)

<a id="nagao2010"></a>[nagao2010] Nagao & Nakajima, Counting Invariant of Perverse Coherent Sheaves and Its Wall-crossing, <i>International Mathematics Research Notices</i>,  rnq195 (2010). <a href="http://dx.doi.org/10.1093/imrn/rnq195">doi</a>. [↩](#7e42b2f2ed2a5e2191272a2cb9410cf8)

<a id="morrison2012"></a>[morrison2012] Morrison, Mozgovoy, Nagao & Szendr\H oi, Motivic Donaldson\textendashThomas Invariants of the Conifold and the Refined Topological Vertex, <i>Advances in Mathematics</i>, <b>230(4)</b>, 2065-2093 (2012). <a href="http://dx.doi.org/10.1016/j.aim.2012.03.030">doi</a>. [↩](#da0a139573e280c8269dbceaff593e16)

<a id="kontsevich2008"></a>[kontsevich2008] Kontsevich & Soibelman, Stability Structures, Motivic Donaldson-Thomas Invariants and Cluster Transformations, <i>arXiv:0811.2435 [hep-th]</i>,  (2008). [↩](#3b2bace0f82473dfaf9bfe3060c2929b)

<a id="davison2020"></a>[davison2020] Davison & Meinhardt, Cohomological Donaldson\textendashThomas Theory of a Quiver with Potential and Quantum Enveloping Algebras, <i>Inventiones mathematicae</i>, <b>221(3)</b>, 777-871 (2020). <a href="http://dx.doi.org/10.1007/s00222-020-00961-y">doi</a>. [↩](#bf093cafee676d3618a854647366bdec)
