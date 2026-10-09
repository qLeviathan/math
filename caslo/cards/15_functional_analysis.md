# Functional analysis -- OpenAI result families in CASLO framing

Levels: 0 none, 1 words, 2 analogy, 3 shared object, 4 direct use. Final levels >= 2 were confirmed by an adversarial verifier; unverified claims are capped at 1.

## 322. Tingley’s sphere-isometry problem

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Tingley's problem: every isometry between unit spheres of real Banach spaces extends uniquely to a linear isometry of the whole spaces, so metric geometry of the unit sphere determines the space up to isomorphism.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Matches on word 'problem' only; methodology text discusses reviewing models, not isometry or metric geometry.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/08-refused/refused.md#L1` -- [X] Refused / false -- recorded so they are NOT rebuilt
     why: Word match on 'sphere', but this is owner's refusal log for rejected ideas, not functional analysis.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Discusses transfer matrix as tight-binding model, different from isometry theory. Word 'linear' is coincidental.

## 323. Independence of the separable quotient problem

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** The separable quotient problem is independent of ZFC: infinite-dimensional Banach spaces may or may not have separable quotients depending on set-theoretic assumptions, even holding over both real and complex fields.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Matches on 'independent' but context is axioms of deterministic computation engine, not set-theoretic independence.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Word match on 'problem' and 'space'; methodology text is about reviewing heuristics, not Banach space theory.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L467` -- 4.5 Axis 4 — phase-register hand: latched `R`, period `~F(W+2)`, Markov boundary (Lemma L1
     why: Mentions 'space' but refers to finite register state space F(W+2), not infinite-dimensional Banach spaces.

## 324. Lipschitz equivalent Banach spaces need not be linearly isomorphic

- **Vetting:** 2 manuscript(s); Lean scope note; 2 in formalization.yaml; 0 revised.
- **Plain:** Separable Banach spaces can be globally bi-Lipschitz equivalent but not linearly isomorphic, so metric structure alone does not determine the linear structure of Banach spaces.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L570` -- THE LINKED BUILD — end state at the top, first action at the bottom
     why: Word 'isomorphic' appears in different context (abstract lattice theory), not related to metric geometry or Banach spaces.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Glossary entry; 'linear' appears in quantum error correction context, not Banach space theory.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L109` -- 3. Math concepts (perused, one line + provenance)
     why: Lists math concepts reviewed; word 'isomorphism' only, not related to Lipschitz equivalence.

## 325. The complete Crouzeix conjecture

- **Vetting:** 2 manuscript(s); Lean scope note; 2 in formalization.yaml; 0 revised.
- **Plain:** Crouzeix theorem: for bounded operators A on Hilbert spaces, ||P[A]|| <= 2*sup|P(z)| on the numerical range W(A), with sharp constant 2 independent of matrix dimension.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Mentions operator A (2x2 transfer matrix) in classical tight-binding model, not Hilbert space operators or numerical range.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L20` -- NOMENCLATURE
     why: Word 'finite' in lattice nomenclature context, not in operator theory or Hilbert spaces.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: phi/psi are Zeckendorf algebra operators, not Perron-Frobenius eigenvalues in numerical range problems.

## 326. The cotype–cotype conjecture under the approximation property

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** K-convexity of Banach spaces with approximation property is equivalent to both space and dual having finite Rademacher cotype with possibly different exponents.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L689` -- HAZARDS
     why: Word matches 'finite' and 'space'; HAZARDS section documents edge cases in owner's system, not Banach space cotype.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L492` -- THEOREMS T1..T5 AND THE ROOT T0
     why: Lists owner's theorems T0-T5 about lattice properties, not Rademacher type or K-convexity.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Word 'property' and 'both' appear; axioms section specifies computation rules, not functional analysis.

## 327. Markov type characterizes superreflexivity

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Markov type p>1 forces superreflexivity: every real Banach space with nontrivial Markov type admits equivalent uniformly convex norm, characterizing superreflexive spaces.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L467` -- 4.5 Axis 4 — phase-register hand: latched `R`, period `~F(W+2)`, Markov boundary (Lemma L1
     why: Word 'Markov' but in context of Markovian boundary on finite state space F(W+2), not Markov type in Banach spaces.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L636` -- 5.4 R(t-1) triple-duty
     why: Mentions 'Markov' again as state boundary condition; completely unrelated to Banach space theory.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Word 'space' and 'real' appear; text is about methodology, not superreflexivity or renorming.

## 328. Nonexpansive fixed points in reflexive Banach spaces

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Kirk's reflexive fixed-point theorem: every distance-preserving selfmap of a nonempty closed bounded convex subset of a real reflexive Banach space has a fixed point where the map equals identity.
- **CASLO frame:** The cascade function (zeck_kernel.py:234) reaches Zeckendorf normal form via confluent rewrite rules R1 (F(k)+F(k+1)=F(k+2)) and R3 (2F(k)=F(k+1)+F(k-2)). Confluence (Frougny local confluence + Newman) guarantees unique fixed form regardless of firing order.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/jun_11_2026/zeck_kernel.py#L234` -- cascade
     why: Both reach unique fixed form via confluent rewriting; cascade uses F(k) recurrence rules analogous to Banach fixed-point iteration reaching convergence.
     ruling: The cascade() code and docstring at L234-254 describe a set of rewrite rules acting on multisets of Fibonacci indices. They stop because of a digit-sum Lyapunov function, and Frougny local confluence plus Newman's lemma make the Zeckendorf normal form unique. There is no metric: the file header itse
  2. level 1 (draft 2, REJECT) `caslo_test_framework/docs/MASTER_CONTROL.md#L145` -- §5  Cascade rules CC1–CC4 — the confluent normalizer
     why: Explicit statement of confluence property: local confluence (Frougny) + Newman confluence lemma ensure unique normal form, structurally homologous to fixed-point uniqueness.
     ruling: Section 5 (L145+) says rules CC1-CC4 are Church-Rosser, so any order of application reaches the same canonical fibbinary form, with the sum Sigma F_k preserved. That is a uniqueness result about normal forms of a rewrite system, which is order-based combinatorics. There is no norm, convex set, nonex
  3. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L718` -- 6.2 The transient-multiplicity caveat (Lemma L13)
     why: Documents convergence during cascade transients, bounding the path to normal form; analogous to fixed-point iteration convergence bounds.
     ruling: L718-778 contain Lemma L13 and Theorem T4: when R1 and R3 fire together under a multiplicity-capped (work, coll) encoding, mass leaks by -F(2). Closure holds only under one-redex-per-step ordering. The window then gives the scalogram corollary and a two-register build prescription. Nothing in it con

## 329. A counterexample to metric-entropy duality

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Disproves Pietsch's dimension-free duality conjecture: origin-symmetric convex bodies violate the conjectured comparison between covering numbers and entropy of polar bodies for every proposed universal constant.
- **CASLO frame:** The owner's shell lattice has topological entropy exactly log(phi), realized as the Perron-Frobenius dominant eigenvalue of the transfer matrix A. The golden-mean subshift (no adjacent 1s) has Parry measure P(gap=k)=phi^{-k}, a Gibbs weight at inverse temperature ln(phi)—duality between covering (gaps) and spectral measure.
- **Verdict:** WORDS
  1. level 1 (draft 3, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L451` -- 4.3 Axis 2 — shell-index hand: `log_phi` rapidity, density `phi^{-k}`
     why: Explicit statement: 'topological entropy log(phi)' and Perron-Frobenius eigenvector component decay as phi^{-k}; directly matches the covering/entropy duality the family studies.
     ruling: The phrase quoted as 'topological entropy log(phi)' does not occur anywhere in this document. A grep finds only 'entropy rate ln(phi)' at L139, L143 and L438, all outside the cited window. Theorem 4.3 at L451 is a Perron-Frobenius density claim (phi^{-k}) for the 2x2 matrix A. Family 329 is about co
  2. level 1 (draft 3, REJECT) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L242` -- 11. The reachable-set measure (softmax, but intrinsic)
     why: Proposition 11.1 states P(gap=k)=phi^{-k} normalizes exactly, entropy is log(phi), Gibbs weight at beta=ln(phi); this is the Parry measure for the golden-mean subshift—exact duality.
     ruling: Prop 11.1 (P(gap=k)=phi^{-k}) is correct: it is the gap law of the Parry measure. Together with Cor 11.2 (topological entropy log phi), it concerns the entropy of a dynamical system, the golden-mean subshift, with a Gibbs weight at beta=ln phi. The family's 'metric entropy' is log N(K,L) for convex 
  3. level 1 (draft 3, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: States 'A is 2x2 and constant; A^n has closed-form Binet expression; the model is fully integrable.' Transfer matrix structure + phi eigenvalue is the spectral side of the covering/entropy duality.
     ruling: The cited text covers a constant 2x2 matrix A, Binet closed forms, integrability, a tight-binding/MPS reading, and ln(phi) used as an 'entropy-rate symbol'. The family has no spectral side. Its duality is the polarity K <-> K° of convex bodies, and the proof goes through a matrix-to-body conversion,

## 330. A uniformly discrete counterexample to bounded approximation in Lipschitz-free spaces

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Answers Kalton's question negatively: a uniformly discrete metric space exists with the approximation property (finite-rank operators approximate identity on compacts) but not bounded approximation (no uniform norm bound).
- **CASLO frame:** The owner uses finite-rank operations (LUT4 logic on W=45 shell lattice) on a discrete Zeckendorf space. Fibbinary decomposition provides approximation, but transient multiplicity during cascade means no global bound on operator norms exists.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L467` -- 4.5 Axis 4 — phase-register hand: latched `R`, period `~F(W+2)`, Markov boundary (Lemma L1
     why: Mentions 'bounded', 'space', 'finite' but no shared mathematical structure—vocabulary only.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Contains 'identity' and 'bounded' terms but in context of system description, not mathematical approximation theory.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/psi_retract_operator.md#L1` -- psi_retract operator
     why: Discusses operators but in Zeckendorf algebra context, not Lipschitz-free spaces or approximation property.

## 331. Reflexive midpoint convexity and diamond distortion

- **Vetting:** 7 manuscript(s); Lean scope note; 7 in formalization.yaml; 0 revised.
- **Plain:** Constructs a reflexive Banach space with asymptotically midpoint uniform convexity but no equivalent asymptotically uniformly convex norm; depth-k diamond graphs require distortion at least sqrt(1+k/12)—separating these geometric properties.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/MULTI_ZECKENDORF_SCALING.md#L93` -- PART IV — The RECURSIVE COMPOSITE: fold a window into one address, two orders up
     why: Discusses recursion and tree-like structures, but in context of shell folding, not distortion bounds on diamond graphs.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L89` -- 4. The graded fold — packing the whole past into one register
     why: Describes recursion depth k in context of fibbinary folding, not midpoint convexity or Banach geometry.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L5` -- Scope
     why: Mentions 'embedding' and 'structure' but refers to clock and channel embedding, not geometric embedding or distortion in metric spaces.

## 332. Metric Markov cotype of ℓ1 and Hilbert-space Lipschitz extension

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves real ℓ1 has metric Markov cotype two. Consequently, every Lipschitz map from a Hilbert-space subset to ℓ1 extends to the whole space with universal multiplicative loss in Lipschitz constant.
- **CASLO frame:** The owner's 2×2 transfer matrix A has eigenvalue phi (Perron-Frobenius). The latched chunk phase register R at chunk boundaries is the Markovian boundary condition for the next chunk (EMBEDDING_CLOCK:467). The annealing schedule 13C/32 ≈ phi^{-1}·C is a multiplicative approximation, structurally parallel to Lipschitz extension loss.
- **Verdict:** WORDS
  1. level 1 (draft 3, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L467` -- 4.5 Axis 4 — phase-register hand: latched `R`, period `~F(W+2)`, Markov boundary (Lemma L1
     why: Explicit statement: 'The chunk phase register (latched R at chunk boundary) is the Markovian boundary condition for the next chunk'; directly shares Markov structure with metric Markov cotype.
     ruling: The family's 'multiplicative loss' is a uniform constant C on the Lipschitz constant of the extension. It has nothing to do with phi^{-k} eigenvector decay. The manuscript uses no Perron-Frobenius theory and no eigenvalues: 'Spectral' appears only in a reference title. Stationarity (piA=pi) is just 
  2. level 1 (draft 3, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: States 'A is 2×2 constant matrix; the hop is the elementary scattering event; fully integrable deterministic recurrence.' The transfer matrix + phi eigenvalue structure parallels the extension problem with multiplicative constant.
     ruling: 'Hilbert space' appears in the owner text only as a physics label: once in the contrast with anyon quantum dimension, and once in 'Fibonacci-quotient Hilbert space', which describes a classical model with bond dimension 1. There is no inner product, Lipschitz map, l1 target or extension. The rationa
  3. level 1 (draft 3, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L451` -- 4.3 Axis 2 — shell-index hand: `log_phi` rapidity, density `phi^{-k}`
     why: The multiplicative eigenvalue structure (phi^{-n} decay) and Perron-Frobenius theory are shared between the owner's spectral analysis and the metric Markov cotype's multiplicative loss.
     ruling: The family's 'multiplicative loss' is a uniform constant C on the Lipschitz constant of the extension. It has nothing to do with phi^{-k} eigenvector decay. The manuscript uses no Perron-Frobenius theory and no eigenvalues: 'Spectral' appears only in a reference title. Stationarity (piA=pi) is just 
