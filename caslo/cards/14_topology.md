# Topology -- OpenAI result families in CASLO framing

Levels: 0 none, 1 words, 2 analogy, 3 shared object, 4 direct use. Final levels >= 2 were confirmed by an adversarial verifier; unverified claims are capped at 1.

## 304. The Hilbert–Smith conjecture in every dimension

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** The Hilbert–Smith conjecture: every locally compact second-countable Hausdorff group acting faithfully on a connected finite-dimensional topological manifold is a Lie group. Proved in all finite dimensions.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Both use 'transfer matrix' and 'topology' vocabulary, but contexts differ: owner discusses classical tight-binding model with Fibonacci eigenvalues on lattice; paper treats Lie group actions on manifolds. No shared mathematical object.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/CAS_LUT_PIPELINE.md#L191` -- 6. The Multiplication Bypass as Topology
     why: Title mentions 'Multiplication Bypass as Topology' — topology here is routing topology in LUT fabric, unrelated to manifold topology or group actions.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/04-hyperbolic/anosov-dynamical.md#L1` -- [V] Hyperbolic dynamics (Anosov)
     why: Anosov dynamics studies chaotic flows; CASLO is deterministic recurrence. No shared object despite both mentioning manifolds.

## 305. Four-dimensional disk embedding and Wall's conjecture

- **Vetting:** 3 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Four-dimensional disk-embedding conjecture disproved: framed algebraic dual spheres do not suffice for disjoint locally flat spanning disks. Also disproves Wall's conjecture on Poincaré duality groups in dimension four.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L570` -- THE LINKED BUILD — end state at the top, first action at the bottom
     why: Pre-ranked hit on 'constructs', 'class', 'dimension', 'space' is lexical overlap only. No mathematical connection between 4D topological manifolds and owner's finite state/register constructions.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Glossary entry; contains words like 'preserve', 'classes', 'dimension' but is about quantum computing (qudit states), not algebraic topology or Poincaré duality groups.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L718` -- 6.2 The transient-multiplicity caveat (Lemma L13)
     why: Transient-multiplicity caveat discusses register encoding; no connection to Wall's conjecture or Poincaré duality.

## 306. The purely cosmetic surgery conjecture

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Purely cosmetic surgery conjecture: distinct Dehn surgery slopes on nontrivial smooth knots in S³ never produce orientation-preservingly homeomorphic manifolds, including meridional slope.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: Query 'Zeckendorf' matched in search; owner's Zeckendorf representation is arithmetic encoding in recurrence, not knot invariant theory. Shared word only.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L41` -- 3. Qudit Cat States (Sec 2.2; pp. 14-22)
     why: Lexical match on 'trivial', 'three', 'nontrivial' — all vocabulary only. Content is quantum computing, not knot theory.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/BOOLEAN_PATHING.md#L189` -- 9. The strict-Boolean variant
     why: Boolean logic in register routing; no connection to Dehn surgery or knot invariants.

## 307. Failure of rational injectivity for maximal coarse assembly

- **Vetting:** 2 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Coarse assembly map failure: constructs uniformly discrete bounded-geometry space whose maximal coarse assembly is not rationally injective, disproving the rational coarse Novikov conjecture.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L283` -- 14. Statement of the whole object
     why: Text states: 'injectively encodes the entire prefix' — injective here means one-to-one lossless encoding. Family's rational injectivity is property of K-homology assembly maps. Same word, different mathematical object.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/psi_retract_operator.md#L1` -- psi_retract operator
     why: Pre-ranked match on 'inject', 'counter' — but psi_retract is recurrence operator in Z[phi] ring, unrelated to C*-algebra K-theory or Novikov conjecture.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L20` -- NOMENCLATURE
     why: Nomenclature; matches on 'ordinary', 'element', 'finite' but is about register semantics, not rational assembly maps.

## 308. Finite Smith–Toda complexes at every height

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Smith–Toda spectra exist at every height: constructs finite Smith–Toda spectrum V(n) at prime p, with Brown–Peterson homology BP₊/(p,v₁,...,vₙ) and canonical comodule structure.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L20` -- NOMENCLATURE
     why: Pre-ranked on 'ordinary', 'finite', '_3', '_4' — lexical only. Owner's subscripts denote recurrence shells; paper's subscripts denote formal group generators in chromatic hierarchy.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L451` -- 4.3 Axis 2 — shell-index hand: `log_phi` rapidity, density `phi^{-k}`
     why: Mentions Perron-Frobenius eigenvalue (phi); Smith-Toda theory uses primes and chromatic filtration, not Fibonacci eigenvalues. Same mathematical structure (spectral) in completely different contexts.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Glossary contains '_1', '_3' notation but in quantum context; no connection to chromatic spectrum theory.

## 309. The Kervaire invariant problem at the prime three

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Kervaire invariant problem at prime three: standard Kervaire classes survive in mod-three Adams spectral sequence at indices 0, 2, 3 (stems 10, 106, 322); each survives with order-three element.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L137` -- A2. A^∞ has no fixed point — only the spectral gap matters
     why: Title: 'A^∞ has no fixed point — only the spectral gap matters' — spectral here means eigenvalue spread of transfer matrix A. Adams spectral sequence is homological algebra sequence, different object.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/07_hyperbolic_jump/sech_kernel.md#L1` -- Sech kernel, integer forms
     why: Shell-index kernel ranking; no connection to Adams spectral sequences or Kervaire invariants.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L352` -- 3.1 Binet lifts each lit shell to a Z[phi] coordinate
     why: Binet lifts shells to Z[phi] coordinates; 'element', 'order' are about register elements and their indices, not group-theoretic order in homotopy theory.

## 310. Quillen's conjecture in rational homology

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves finite groups with trivial largest normal p-subgroup have posets of elementary abelian p-subgroups with nonzero rational homology, establishing Quillen's conjecture.
- **CASLO frame:** No shared object with the owner's framework.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/psi_retract_operator.md#L1` -- psi_retract operator
     why: Pre-ranked match on 'abelian', 'O_p', 'finite'. Psi_retract is shell-lattice operator on Fibonacci/Lucas Z[phi]; no connection to finite-group posets or homology.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Lexical match on 'abelian', 'O', 'G'. Owner's context is algebraic/combinatorial method; topology's context is algebraic topology of subgroup posets.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L718` -- 6.2 The transient-multiplicity caveat (Lemma L13)
     why: Pre-ranked match on 'precisely', 'If', 'therefore'. L13 lemma concerns register multiplicity in cascade; no topological structure shared.

## 311. The Hovey–Strickland and Chai conjectures

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Classifies invariant ideals of Lubin-Tate deformation rings; proves K(n)-local spectra have exactly n+2 thick tensor ideals with Balmer spectrum a chain of n+1 points.
- **CASLO frame:** Both use 'invariant' and 'ring'; owner's Z[phi] satisfies x²=x+1, K-theory algebras are distinct. No shared object in tensor/ideal structure.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/psi_retract_operator.md#L1` -- psi_retract operator
     why: Pre-ranked score=137 on 'invariant under', 'ring'. Psi_retract preserves F-mass via Fibonacci recurrence; K(n) tensor ideals use stable homotopy theory, not Fibonacci structures.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L1` -- Transfer Matrix as LUT Fabric — Synthesis
     why: Transfer matrix A=[[1,1],[1,0]] has eigenvalues phi,psi (golden ratio); K(n)-local Balmer spectrum is discrete topological space of ideals, structurally unrelated.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L489` -- 4.7 The deepest cycle — `I-1` conservation as the period-1 hand
     why: Pre-ranked on 'invariant under', 'at every'. I-1 conservation is Fibonacci multiset sum; thick tensor ideals are stable homotopy localization, no overlap.

## 312. The Grothendieck homotopy hypothesis

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves ∞-groupoids from Grothendieck coherators recover homotopy theory of spaces, establishing the Grothendieck homotopy hypothesis.
- **CASLO frame:** Both mention φ/ψ notation; owner's φ/ψ are algebraic directions (advance/retract on F(k)); coherators are higher-categorical objects. No shared algebra.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: Pre-ranked score=79. φ/ψ are conjugate Fibonacci directions (F(k)→F(k+1) vs F(k)→F(k-1)); coherators are categorical equivalences, structurally unrelated.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Axiom A1: φ and ψ satisfy x²=x+1 (characteristic polynomial of A=[[1,1],[1,0]]). Grothendieck's φ/ψ are not algebraic invariants of this type.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L645` -- §34  Scalographic Tensor — the unification (thesis cross-walk)
     why: References transfer matrix and algebraic structure. Coherators operate on ∞-categories, not on Fibonacci recurrence structures.

## 313. Finite generation for the $K(n)$-local sphere

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves homotopy groups of K(n)-local spheres are finitely generated ℤp-modules in every integer degree, answering Hovey-Strickland's finiteness question.
- **CASLO frame:** No shared object with the owner's framework.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Pre-ranked on 'for every', 'equivalently'. Owner's axioms constrain Z[phi] register; K(n)-local categories use chromatic homotopy structure, unrelated.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XV_FED_MEMORY_GRC.md#L259` -- Proposition VII — The capture is faithful; the source is not byte-stable.
     why: Word match on 'finite', 'prove that'. Owner's finite generation is of register cardinality (size F(n+2)); K(n) finite generation is of homotopy groups over ℤp.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L377` -- 3.2 phi-advance is a derived ADD, not independent state
     why: Matching on 'finiten', 'integer'. Phi_advance adds shells to register; K(n)-localization filters spectrum by chromatic level, distinct mechanisms.

## 314. Cyclic length and chromatic fixed-point loss

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves optimal chromatic loss from H-fixed to G-fixed points equals shortest subnormal-chain length from H to G with cyclic quotients, resolving Kuhn-Lloyd proposal.
- **CASLO frame:** Both discuss finite structures and chains; owner's chains are cascade R1+R3 decompositions of Zeckendorf values. Topological chains are quotient sequences.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XV_FED_MEMORY_GRC.md#L361` -- HOW THE MEMORY STATE IS TRACED FOR A GRC AUDIT
     why: Pre-ranked score=109 on 'proposed', 'for every', 'witness', 'loss'. Owner's GRC audit traces state sequences; chromatic loss measures stable homotopy decay, unrelated.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XV_FED_MEMORY_GRC.md#L259` -- Proposition VII — The capture is faithful; the source is not byte-stable.
     why: Pre-ranked on 'prove that', 'length', 'Each'. Owner's chain length is Fibonacci decomposition steps; quotient chain is group-theoretic subnormal series.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L492` -- THEOREMS T1..T5 AND THE ROOT T0
     why: Pre-ranked on 'finite', 'equals', 'chain'. Theorems T1-T5 concern Zeckendorf chain properties; chromatic chains are homotopy-theoretic filtrations.

## 315. The four-dimensional Singer conjecture

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves L2-Betti numbers of universal covers of closed aspherical topological four-manifolds vanish outside degree two, establishing the four-dimensional Singer conjecture.
- **CASLO frame:** No shared object with the owner's framework.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L570` -- THE LINKED BUILD — end state at the top, first action at the bottom
     why: Pre-ranked on 'closed', 'P', 'top', 'non'. Owner's linked build is register state topology; Singer conjecture is differential topology of Poincaré complexes.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/BOOLEAN_PATHING.md#L189` -- 9. The strict-Boolean variant
     why: Matching on 'four', 'two', 'wider', 'manifold'. Boolean pathing is register routing; Singer's four-dimensional result uses topological manifold invariants.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L317` -- IX. The gate (L9, Prop 7)
     why: Matching on 'four', 'outside', 'P', 'non'. Gate L9 is Fibonacci-based predicate; L2-Betti numbers are homological invariants of manifold topology.

## 316. Curtis’s conjecture

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Curtis's conjecture: the mod-two stable Hurewicz image of spheres is spanned by Hopf-invariant-one and Kervaire-invariant-one classes.
- **CASLO frame:** No shared mathematical object; both use spanning and basis decomposition, but Curtis spans cohomology classes while CASLO spans address space via Zeckendorf.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L67` -- S5. Perron-Frobenius vector = steady-state bit-density operator
     why: Shared vocabulary: span, invariant. Curtis spans cohomology; CASLO uses φ eigenvalue for bit-density and address spanning.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/02_identities/cassini.md#L1` -- Cassini identity
     why: Invariant classes: Cassini gives parity as topological invariant; Curtis studies invariant classes in Hurewicz image.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L9` -- §0  Compaction-Survival Protocol — read this first
     why: Spanning decomposition: Curtis spans cohomology by invariant classes; CASLO spans address via Zeckendorf canonical form.

## 317. Thomason model structures in all strict higher dimensions

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Resolves Ara-Maltsiniotis conjecture: strict globular n-categories admit Quillen-equivalent model structures to simplicial sets for all positive finite dimensions.
- **CASLO frame:** No shared object. Thomason uses category-theoretic model structures and weak equivalences; CASLO uses cascade composition and canonical normalization.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L145` -- §5  Cascade rules CC1–CC4 — the confluent normalizer
     why: Structure type: both normalize via rewrite rules. Thomason: model structure with weak equivalences; CASLO: CC1-CC4 cascade confluence rules.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L718` -- 6.2 The transient-multiplicity caveat (Lemma L13)
     why: Both study structure across levels: Thomason across n-categorical heights; CASLO across shell lattice dimensions [2,46].
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/jun_11_2026/zeck_kernel.py#L234` -- cascade
     why: Normalization: both canonicalize structures. Thomason: equivalence of model structures; CASLO: cascade_resolve to normal form.

## 318. Chromatic splitting: filtrations and counterexamples

- **Vetting:** 5 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Constructs explicit multi-stage filtrations of localized spheres in chromatic splitting; disproves strong splitting at height three for primes p ≥ 5.
- **CASLO frame:** Both use hierarchical staged lattice structures: chromatic uses p-adic heights; CASLO uses shell indices [2,46]. Shared structure type—multi-stage decomposition—but different mathematical substrates.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L773` -- 6.4 Harmonized two-register build prescription
     why: Filtration by stages: chromatic splits by p-adic height; CASLO decomposes by shell k∈[2,46]. Same structure type, different orderings.
     ruling: Section 6.4 (L773) is a six-step hardware build recipe. It specifies two 45-bit fibbinary registers R(t), R(t-1) over shells k in [2,46], four rewrite operators, a no-modulo odometer, on-demand projections, a five-channel priority arbiter, and an optional multiplicity register. Family 318 is about o
  2. level 1 (draft 2, REJECT) `caslo_test_framework/docs/MASTER_CONTROL.md#L145` -- §5  Cascade rules CC1–CC4 — the confluent normalizer
     why: Hierarchical decomposition: chromatic uses localization towers; CASLO uses cascade as confluent hierarchical rewrite.
     ruling: MASTER_CONTROL section 5 (L145) is a confluent (Church-Rosser) term-rewriting system, CC1-CC4, on Fibonacci multisets with conserved Sum F_k, plus its empirical sweeps. A rewrite system with unique normal forms is not a localization tower or a filtration of spectra. The text has no localization func
  3. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/05_cascade/seven_carry_bound.md#L1` -- Seven-carry bound
     why: Bounded stages: chromatic bounded by height; CASLO bounded by maxShell≤46 and seven-carry bound.
     ruling: seven_carry_bound.md states an empirical termination-depth bound: at most 7 carry stages reach canonical form for an 11-bit register, tested on 233 = F(13) valid states. Family 318's '2^n-stage' and 'eight-stage' count the layers of a filtration of a spectrum, one per predicted splitting summand. Th

## 319. Counterexamples to finite generation at chromatic height two

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Disproves Hahn-Wilson conjecture: for large primes, constructs p-complete spectrum outside thick subcategory generated by standard form—finite generation fails.
- **CASLO frame:** Both identify structural limits on generation: HW shows p-spectra cannot be finitely generated from BP⟨2⟩; CASLO shows states cannot generate below shell-2 boundary.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/06_psi_retract/psi_retract_operator.md#L1` -- psi_retract operator
     why: Generation failure at boundary: HW spectrum cannot be generated; psi_retract F(2) cannot descend below SHELL_LO=2. Same structure: obstruction to building.
     ruling: Family 319 constructs a connective p-complete spectrum of exact fp-type 2 outside the thick subcategory generated by BP<2>_p (it cannot be built by finitely many sums, shifts, cones and retracts), yet it satisfies L_2^f X = L_2 X and L_{T(2)} X = L_{K(2)} X. psi_retract is a lossy index shift on a b
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Conservation laws prevent generation: HW's spectrum obstruction; CASLO's multiset mass conservation limits buildable structures.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L294` -- §12  Cassini sheet — the ±4 parity invariant
     why: Invariant obstruction: Cassini parity prevents arbitrary F/L generation, like HW's invariant obstruction to spectrum building.

## 320. Nonhomeomorphic closed aspherical four-manifolds

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Constructs homotopy-equivalent but non-homeomorphic closed aspherical four-manifolds, disproving homeomorphism formulation of Borel conjecture.
- **CASLO frame:** No shared object. Both study when two equivalence relations diverge—homotopy vs. homeomorphism topologically; cascade vs. canonical form algebraically—but in different contexts.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/02_identities/cassini.md#L1` -- Cassini identity
     why: Invariant distinguishing equivalences: Cassini parity distinguishes fibbinary forms; Borel uses invariants to distinguish homotopy from homeomorphism.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Different equivalences: Borel separates homotopy-equivalence from homeomorphism; I4 shows reversibility under φ/ψ while addressing may differ.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/psi_retract_operator.md#L1` -- psi_retract operator
     why: Invariants persist under transformation: mass conserved under psi_retract, like manifold invariants under homotopy equivalence.

## 321. A counterexample to Wall's finite D(2) problem

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Constructs finite three-dimensional CW complex satisfying D(2) condition but not equivalent to any finite 2D complex—dimension reduction fails.
- **CASLO frame:** Both prevent finite reduction via bounds: Wall's dimension 3→2 impossibility; CASLO's psi_retract prevents shell k→(k-1) below boundary k=2.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/06_psi_retract/psi_retract_operator.md#L1` -- psi_retract operator
     why: Finite reduction obstruction: Wall proves dimension 3 cannot reduce to dimension ≤2; psi_retract proves F(k_top) cannot reduce below shell 2. Same structure.
     ruling: Family 321 gives one explicit finite 3-dimensional CW complex that satisfies D(2) but is not homotopy-equivalent to any finite 2-complex. D(2) here means the universal cover has no integral homology above degree 2 and H^3 vanishes for all local coefficients. This is a homotopy-type realization probl
  2. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L718` -- 6.2 The transient-multiplicity caveat (Lemma L13)
     why: Bounded finiteness: Wall uses finite CW complexes with dimension bounds; CASLO uses finite shell range [SHELL_LO=2, SHELL_HI=46].
     ruling: Section 6.2, Lemma L13 / T4 caveat (L718), is a counter-capacity argument. The (work, coll) encoding caps per-shell multiplicity at 2, so R1 and R3 firing on one shell in the same tick drops F(2) (measured drift -1). The cure is either one-redex-per-step ordering or a third multiplicity register. 'F
  3. level 1 (draft 2, REJECT) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Bounded systems are special: Wall shows finite assembly fails under dimension constraint; CASLO shows bounded psiRetract enables infinite-token generation.
     ruling: METHODOLOGY section 5 (I1-I8) lists empirical and engineering insights: the bigram ceiling, spine versus cliff, reversibility, codebook saturation, I6 'psiRetract keeps maxShell<=46 so generation runs on fixed silicon', the -F(2) mass bug, and a single address space. None of it is topology. The 'why
