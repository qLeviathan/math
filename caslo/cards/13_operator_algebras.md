# Operator algebras -- OpenAI result families in CASLO framing

Levels: 0 none, 1 words, 2 analogy, 3 shared object, 4 direct use. Final levels >= 2 were confirmed by an adversarial verifier; unverified claims are capped at 1.

## 285. Counterexamples to Baum–Connes and Kadison–Kaplansky

- **Vetting:** 3 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Disproves two major conjectures in functional analysis on Hilbert spaces: the Baum-Connes assembly map is not injective for torsion-free groups, and the Kadison-Kaplansky projection conjecture fails. Both results use group C*-algebra counterexamples.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L718` -- 6.2 The transient-multiplicity caveat (Lemma L13)
     why: Word 'projection' appears in both, but owner's context is caching projections of cascade values onto a lattice (line 756: 'exactly the materialized cache of on-demand projections of T3'), while family 285 uses projections in C*-algebras (self-adjoint idempotent operators). Different mathematical obj
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L109` -- 3. Math concepts (perused, one line + provenance)
     why: Lexical match only on 'concepts.' Owner's math (Zeckendorf, Fibonacci recurrence, Z[φ]) addresses text compression via discrete integer arithmetic. Family 285 addresses K-theory and spectral theory on Hilbert spaces. No shared structure.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L398` -- 3.3 The centroid moment M is a third orthogonal projection
     why: Centroid moment M is described as 'a third orthogonal projection' in CASLO's register-landing context. Family 285's projections are self-adjoint elements of C*-algebras (functional-analytic objects). No mathematical transfer.

## 286. Rigidity and arithmetic of lattice von Neumann algebras

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Classifies finite-index bimodules between scalar-twisted group factors of ICC groups on characteristic-zero local fields. Proves arithmetic exhaustion: every such bimodule is a summand of finite direct sums of models from subgroup isomorphisms and projective representations.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/UPGRADE/caslo_monolith/harness/docs/ELEMENTS_BOOK_XVI_HETEROGENEITY.md#L34` -- Propositions
     why: Lexical match on 'closed,' 'factors,' 'finite.' But owner's 'factors' refers to fibbinary bit-string decomposition into Fibonacci bases, while family 286's 'factors' are von Neumann algebras over local fields. Different domains entirely.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L109` -- 3. Math concepts (perused, one line + provenance)
     why: Owner's math concepts are Zeckendorf-based integer arithmetic. Family 286 is arithmetic geometry over local fields in the context of von Neumann algebras—fundamentally different.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Foundational lemmas in CASLO concern cascade preservation and shell lattice. Family 286's foundational work is on modular forms and arithmetic properties of lattice inclusions in von Neumann algebras. No mathematical object overlap.

## 287. Isomorphism of the free group factors

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised; reasoning summary reasoning_traces/free-group-factor-isomorphism.pdf.
- **Plain:** Solves the free group factor isomorphism problem: proves L(F₂) ≅ L(F₃) and hence all free group factors, including L(F_∞), are isomorphic with fundamental group ℝ₊.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L109` -- 3. Math concepts (perused, one line + provenance)
     why: Shared word 'isomorphism,' but owner isomorphisms are between Zeckendorf encodings and their canonical forms (discrete), while family 287 proves isomorphism of tracial von Neumann algebras (infinite-dimensional). Different mathematical objects.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Glossary includes 'group,' 'free,' but owner's group context is permutations on shell lattice indices; family 287's is abstract group representations on Hilbert spaces and their group factors.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L481` -- 4.6 Non-commensurability — the joint odometer has no shared modulus
     why: Non-commensurability describes lack of shared modulus in CASLO's phase clocks. Family 287 uses commensurability in the context of lattices of groups. Different meanings, different domains.

## 288. Kadison's similarity conjecture

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Kadison's similarity conjecture: every bounded unital algebra homomorphism from a C*-algebra to operators on a Hilbert space is similar to a ∗-homomorphism after conjugation by a bounded invertible operator.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: Shared term 'De Morgan,' but owner's context: De Morgan applies to Boolean constraints on Zeckendorf fibbinary words (no adjacent 1s). Family 288's context: De Morgan is functional-analytic (if at all). Lexical coincidence, not mathematical transfer.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L109` -- 3. Math concepts (perused, one line + provenance)
     why: Shared words 'algebra,' 'bounded,' 'theorem.' Owner algebras are Z[φ] integer rings with Fibonacci operations. Family 288 algebras are C*-algebras of operators on infinite-dimensional Hilbert spaces. No shared structure.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L636` -- 5.4 R(t-1) triple-duty
     why: Owner's R(t-1) register triple-duty involves invertible state transitions in a finite state machine. Family 288's invertible operators are continuous linear operators on infinite Hilbert spaces. Different mathematical substrates.

## 289. Strong Kadison–Kastler stability and its spatial boundaries

- **Vetting:** 3 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves universal strong Kadison-Kastler stability: sufficiently close unital von Neumann algebras are conjugate by a unitary arbitrarily close to identity. Provides counterexamples showing near-identity conjugacy fails for one-sided near-inclusions and norm-close C*-algebras need not be unitarily conjugate.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: Shared vocabulary: 'identity,' 'conjugate.' Owner: conjugate directions φ and ψ on Fibonacci recurrence (algebraic directions on discrete lattice). Family 289: unitary conjugacy in C*-algebras (continuous operators on Hilbert spaces). Different objects.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/psi_retract_operator.md#L1` -- psi_retract operator
     why: Shared word 'operator,' but owner's ψ-retract is a discrete integer operation (shell lattice descent). Family 289's operators are continuous linear maps on Hilbert spaces. No transfer.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Owner's foundational lemmas concern cascade preservation on discrete shells. Family 289 concerns spectral gaps and continuity of unitary conjugacy in infinite-dimensional algebras. No overlap.

## 290. Relative bicentralizers and modular spectral recovery

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves Connes' bicentralizer conjecture for type III₁ factors with separable predual: every inclusion N⊂M of von Neumann algebras with faithful conditional expectation contains an expected amenable subalgebra P⊂N with P'∩c(M)=N'∩c(M). Provides spectral recovery theorem for modular spectral bands.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L492` -- THEOREMS T1..T5 AND THE ROOT T0
     why: Shared word 'inclusion,' 'expected,' 'theorem,' but owner's inclusion is of a subrange in shell lattice indexing. Family 290's inclusion is of von Neumann algebras (functional-analytic objects on Hilbert spaces). Different domains.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: Lexical match on 'algebra,' but owner's algebra is the fibbinary shell operations on Z[φ]. Family 290's algebra is von Neumann algebras (infinite-dimensional). No mathematical transfer.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XV_FED_MEMORY_GRC.md#L259` -- Proposition VII — The capture is faithful; the source is not byte-stable.
     why: Shared word 'faithful' (in different contexts). Owner: faithful capture means bit-exact state logging. Family 290: faithful refers to faithful normal states on von Neumann algebras (measure-theoretic). Different meanings.

## 291. Cuntz comparison, nuclear dimension, and equivariant Jiang–Su stability

- **Vetting:** 4 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves equivariant Jiang-Su stability: amenable group actions on nuclear C*-algebras automatically absorb the Jiang-Su algebra up to cocycle conjugacy; also proves unital Toms-Winter theorem equating strict comparison, nuclear dimension, and Jiang-Su stability.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: OpenAI: C*-algebra stability under group actions. CASLO: transfer matrix A=[[1,1],[1,0]] generates Fibonacci sequences on finite lattice. Same word 'stability' but different domains: infinite-dimensional Banach spaces vs discrete integer lattices.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L223` -- 2. The Cascade as Renormalization Information-Flow
     why: CASLO cascade conserves mass Sum F(k)*M(k); cascade is local (R1 and R3 rewrites). OpenAI studies abstract stability properties of infinite-dimensional algebras. No overlap in mathematical objects.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: IBM paper is on quantum error correction with Galois qudits; OpenAI 291 is on operator algebra classification. Both mention algebras but operate on entirely different structures.

## 292. Kirchberg's $\mathcal O_2$ norm-ultrapower embedding problem

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Answers Kirchberg's embedding problem negatively: constructs separable unital full group C*-algebra that cannot embed unitally into the norm ultrapower of any nonzero nuclear C*-algebra.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: Shared vocabulary: 'algebra', 'full', 'cannot embed'. But OpenAI studies embedding of full group C*-algebras (Banach spaces of bounded operators); CASLO phi/psi bridge is algebraic identity in Z[phi]. Word-level match only.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L89` -- 4. The graded fold — packing the whole past into one register
     why: Both use 'embedding' and 'separable'; OpenAI embeds C*-algebras into function spaces; CASLO embedding is the bit-to-channel mapping of the latent state. Vocabulary overlap, no shared structure.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: IBM quantum error correction vs OpenAI operator algebra. No shared object.

## 293. Invariant projections, hyperinvariant subspaces, and transitive algebras

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Constructs norm-quasinilpotent operators on infinite-dimensional separable Hilbert spaces with no hyperinvariant subspaces, answering the hyperinvariant-subspace problem negatively.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Shared vocabulary: 'Hilbert space', 'operator', 'construction'. OpenAI: operators on infinite-dimensional Hilbert spaces; CASLO: transfer matrix A is a classical 2×2 matrix on finite Z[phi]-valued lattice. Different objects despite shared terminology.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L489` -- 4.7 The deepest cycle — `I-1` conservation as the period-1 hand
     why: Shared vocabulary: 'under every', 'operator', 'invariant'. OpenAI: invariance under operator conjugation on Hilbert spaces; CASLO: I-1 conservation invariant under cascade rewrites. Different invariants, different domains.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/psi_retract_operator.md#L1` -- psi_retract operator
     why: Both use 'operator'; OpenAI studies properties of linear operators on Hilbert spaces; CASLO psi_retract is a state transition (evict top shell, cascade down). Same word, different meaning.

## 294. Kaplansky's quasitrace conjecture and failure of tensor-product stable finiteness

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Disproves Kaplansky's quasitrace conjecture: constructs separable unital C*-algebra with normalized 2-quasitraces that are nonadditive; shows tensor product of stably finite algebras can be properly infinite.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L718` -- 6.2 The transient-multiplicity caveat (Lemma L13)
     why: OpenAI: quasitraces on infinite-dimensional C*-algebras; CASLO: transient multiplicity in cascade (state transitions). No shared mathematical object, despite both discussing 'counterexample' and 'free' algebras.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: OpenAI: Kaplansky conjecture on operator algebras; CASLO/IBM: quantum error correction and Fibonacci lattices. No overlap in mathematical objects.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: Both mention 'algebra' and operations on algebraic structures. OpenAI: C*-algebras (non-commutative Banach spaces); CASLO: Z[phi] (commutative ring of algebraic integers). Different algebraic contexts.

## 295. The Kadison–Ringrose cohomology conjecture

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Kadison-Ringrose conjecture: every bounded Hochschild cocycle of degree ≥2 on von Neumann algebras with coefficients in the algebra itself has a bounded primitive; all higher cohomology groups vanish.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Shared vocabulary: 'axioms', 'equivalently', 'two', 'bounded', 'primitive'. OpenAI: Hochschild cohomology (algebraic topology of operator algebras); CASLO: axioms for Z[phi] ring via eigenvalues phi/psi of A. Different algebraic theories.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L467` -- 4.5 Axis 4 — phase-register hand: latched `R`, period `~F(W+2)`, Markov boundary (Lemma L1
     why: OpenAI: bounded cohomology derivations; CASLO: bounded shell register (psi_retract ensures k_top ≤ 46). Different meanings of 'bounded'.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/stall_predicate.md#L1` -- stall predicate (S_PSI_RETRACT trigger)
     why: OpenAI: at least two degrees of cohomology; CASLO: stall predicate (condition for psi_retract). Both mention degree/level concepts but in different mathematical contexts.

## 296. The generator problem for finite factors

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves generator problem for von Neumann algebras: every type II₁ factor with separable predual is generated by a single operator, equivalently by two self-adjoint operators.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L331` -- RG ordering and the confluence serializer
     why: Shared vocabulary: 'a single operator', 'generators', 'form'. OpenAI: generator of von Neumann algebra (generates the algebra as a weak closure); CASLO: A^n generates state sequence via iteration of transfer matrix. Different generative models.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/psi_retract_operator.md#L1` -- psi_retract operator
     why: Both discuss 'operators' and 'generated' objects. OpenAI: operator generates algebra as abstract structure; CASLO: psi_retract operator evicts top shell (state transition). Word overlap without shared object.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Both mention 'two' and 'operators'. OpenAI: two self-adjoint operators generate type II₁ factor; CASLO: two eigenvalues phi/psi of A determine Z[phi] ring. Similar-sounding but different mathematical objects.

## 297. A ZFC counterexample to Naimark's problem

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** A simple unital infinite-dimensional C*-algebra with faithful tracial state is constructed where all nonzero irreducible representations are unitarily equivalent, answering Naimark's problem negatively.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L9` -- §0  Compaction-Survival Protocol — read this first
     why: Shared vocabulary only: 'state', 'algebra', 'representation' have different meanings. MASTER_CONTROL describes Zeckendorf/Fibonacci systems, not C*-algebras.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L10` -- Core claim
     why: 'Irreducible' refers to minimal LUT4 compute unit, not irreducible representations in operator algebras.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: 'State' and 'representation' are Zeckendorf tokens, not operator-algebra concepts. Pure lexical match.

## 298. Two notions of free entropy differ even when both are finite

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Self-adjoint tuple in von Neumann algebra separates microstates and nonmicrostates free entropies even when both are finite, answering Voiculescu's equality question negatively.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L331` -- RG ordering and the confluence serializer
     why: 'Entropy' in CASLO is log(phi) from Perron-Frobenius; free-entropy is measure-theoretic on operator systems. Different mathematical domains.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L5` -- Scope
     why: 'Self-adjoint' and 'algebra' lexically match von Neumann algebra, not Zeckendorf/cascade algebra.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/04_zphi_ring/index_subtraction.md#L1` -- Index subtraction (backward hop composition)
     why: Z[phi] ring (a+b*phi) is a number ring unrelated to operator algebras or free entropy.

## 299. The Kirchberg–Rørdam character criterion and infinite tensor-power Jiang–Su stability

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** C*-algebra is Jiang–Su stable iff its central-sequence algebra lacks characters for every free ultrafilter, answering Kirchberg–Rørdam character question.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L9` -- §0  Compaction-Survival Protocol — read this first
     why: 'Tensor', 'C*-algebra', 'unitary' match lexically; Jiang–Su stability is abstract C*-algebra classification, unrelated to Zeckendorf determinism.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L209` -- 6. What is NOT proven (read this before believing anything above)
     why: 'Separable' in C*-algebras is topological property; in CASLO it means shell-set disjointness. Different contexts.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L109` -- 3. Math concepts (perused, one line + provenance)
     why: 'Tensor product' in CASLO is scalographic stacking; in algebra it's fundamental C*-algebra construction.

## 300. Approximation and quadratic strong-operator paving

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Every self-adjoint operator in von Neumann algebra admits strong-operator paving over maximal abelian subalgebra with O(ε^-2) projections, resolving Popa–Vaes conjecture.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L28` -- S1. The pipeline IS A^32 in canonical-form quotient
     why: 'Projection' in CASLO is spectral projection onto phi/psi eigenspaces; in paving it means orthogonal projections in functional analysis.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/BOOLEAN_PATHING.md#L189` -- 9. The strict-Boolean variant
     why: 'Operator' refers to LUT4 logic operators; paving theorem is in functional-analysis category. No transfer.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XV_FED_MEMORY_GRC.md#L259` -- Proposition VII — The capture is faithful; the source is not byte-stable.
     why: 'Block' and 'limit' are CASLO architectural/lattice terms, not von Neumann algebra concepts.

## 301. Trace cones and Razak–Jacelon stabilization

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Cone of tracial weights on C*-algebra determines isomorphism class after tensoring with Razak–Jacelon algebra and compact operators, answering Robert's classification question.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L9` -- §0  Compaction-Survival Protocol — read this first
     why: 'Trace', 'tensor', 'compact' in CASLO are discrete/lattice concepts; in theorem they are functional-analysis structures.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L193` -- III. ⊞ is commutative and associative (L3, Prop 1, Prop 2)
     why: 'Algebra' in CASLO is Zeckendorf encoding; in theorem it is C*-algebra operator structure. Different categories.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: 'Trace' in Lucas-channel projection differs from operator-algebra tracial weight. Word overlap only.

## 302. Radius of comparison equals half the mean dimension

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** For minimal homeomorphism on compact metrizable space, radius of comparison of crossed product equals half the mean dimension, with zero mean dimension equivalent to Jiang–Su stability.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L109` -- 3. Math concepts (perused, one line + provenance)
     why: 'Product' in CASLO is Knuth circle product (index addition); crossed product is dynamical systems/C*-algebra tensor construction.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XV_FED_MEMORY_GRC.md#L194` -- Proposition V — Bit pathology: the highest cell grows logarithmically, and the runway is n
     why: 'Radius' in CASLO is lattice neighborhood (4 cells); radius of comparison is C*-algebra invariant. Word match only.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: 'Comparison' in CASLO is path-ordering; in theorem it is order-theoretic C*-algebra invariant. No mathematical transfer.

## 303. Weak pure infiniteness and Cuntz-algebra absorption

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Resolves ordinary-to-strong pure-infiniteness for C*-algebras. For exact algebras, proper infiniteness of one fixed amplification suffices. Cuntz-algebra absorption follows.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L171` -- Addendum: Tensor-Hop Network Reading
     why: Cuntz algebras use infinite-dimensional C*-structure.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L424` -- 4. The Multi-Dimensional No-Modulo Embedding Clock
     why: Owner's finite lattice has no absorption into Cuntz algebras.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/INDEX.md#L1` -- Eigenvalue Geometry — Index
     why: Pure infiniteness in operator algebra classification.
