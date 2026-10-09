# Algebra -- OpenAI result families in CASLO framing

Levels: 0 none, 1 words, 2 analogy, 3 shared object, 4 direct use. Final levels >= 2 were confirmed by an adversarial verifier; unverified claims are capped at 1.

## 193. Serre’s intersection-multiplicity conjecture

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves strict positivity of Serre's intersection multiplicity χ^R(M,N) for nonzero finitely generated modules over regular local rings when M⊗_R N has finite length and complementary dimensions.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L718` -- 6.2 The transient-multiplicity caveat (Lemma L13)
     why: Lexical collision: both use 'multiplicity' and 'ring'. Serre's multiplicity is an intersection-theoretic invariant in algebraic geometry; owner's multiplicity is fibbinary encoding capacity (max representable ≤2 per shell).

## 194. Lech’s multiplicity conjecture

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Hilbert-Samuel multiplicity e(R) ≤ e(S) for every flat local homomorphism of nonzero Noetherian local rings, resolving Lech's conjecture in arbitrary dimension.
- **CASLO frame:** Partial frame: both invoke conservation/invariance properties. Owner's Fibonacci mass I-1=Σ F(k)M(k) exactly preserved by cascade rules R1, R3; Lech's multiplicity is monotone under ring homomorphisms.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L489` -- 4.7 The deepest cycle — `I-1` conservation as the period-1 hand
     why: ANALOGY: Both systems have fundamental invariant quantities preserved under their operations. Lech: e(S) non-decreasing under flat homomorphisms. Owner: I-1 exactly preserved every micro-tick by R1, R3. Parallel structure of conservation laws.
     ruling: Words only. Lech's theorem is an inequality, e(R) <= e(S), between the Hilbert-Samuel multiplicities of two different Noetherian local rings joined by a flat local homomorphism. Hilbert-Samuel multiplicity is the leading coefficient of length(R/m^n). The owner's L489 is an exact equality: the linear

## 195. A counterexample to the small Cohen–Macaulay module conjecture

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Constructs a three-dimensional complete Noetherian normal local domain over ℂ with no nonzero finitely generated maximal Cohen-Macaulay module, disproving the domain form of the conjecture.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L718` -- 6.2 The transient-multiplicity caveat (Lemma L13)
     why: Lexical collision: 'finitely generated', 'modules', 'complete'. Cohen-Macaulay theory concerns depth and regular sequences; owner's system is deterministic cascade composition on fibbinary lattice.

## 196. A counterexample to Kaplansky’s zero-divisor conjecture

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Constructs a finitely presented torsion-free group G whose group algebra F₂[G] has nonzero zero divisors, disproving Kaplansky's zero-divisor conjecture for group rings.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: Word collision on 'zero': family addresses zero divisors in group algebras; owner's analysis concerns golden-ratio eigenvector components in transfer-matrix spectral decomposition.

## 197. A torsion-free group algebra that is not directly finite

- **Vetting:** 4 manuscript(s); Lean scope note; 3 in formalization.yaml; 0 revised; reasoning summary reasoning_traces/kaplansky-direct-finiteness-characteristic-two.pdf.
- **Plain:** Constructs counterexamples to Kaplansky's direct-finiteness conjecture: group algebra over F₂ with elements a,b where ab=1 but ba≠1; matrix over ℤ[G] invertible over ℚ[G] with Fuglede-Kadison determinant strictly between 0 and 1.
- **CASLO frame:** Partial frame: family and owner both invoke matrix determinants. Owner's transfer matrix A=[[1,1],[1,0]] has det(A)=-1; det(A^n)=(-1)^n (Cassini identity) foundational to cascade parity. Family's Fuglede-Kadison determinant is ring-theoretic invariant on group-algebra matrices.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L36` -- S2. The F-channel and L-channel ARE the eigenspaces
     why: ANALOGY: Both invoke determinants and eigenvalues of matrices as fundamental invariants. Owner: det(A^n)=(-1)^n and eigenvalues φ,ψ structure cascade system. Family: Fuglede-Kadison determinant of group-ring matrices. Parallel use of determinant as central invariant.
     ruling: Words only: the shared item is the word 'determinant'. The family's object is the Fuglede-Kadison determinant. It is the exponential of a log-integral taken against the spectral measure in the group von Neumann algebra of an infinite non-sofic group G. It is always nonnegative, so it carries no sign

## 198. A counterexample to finitistic-dimension finiteness

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Constructs a finite-dimensional complex algebra whose finite-dimensional modules have unbounded finite projective dimensions, disproving the little finitistic-dimension conjecture.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L467` -- 4.5 Axis 4 — phase-register hand: latched `R`, period `~F(W+2)`, Markov boundary (Lemma L1
     why: Lexical collision: both mention 'finite' and 'dimension'. Family: finitistic projective dimension in homological algebra. Owner: shell-index dimension k∈[2,46] in fibbinary representation. Unrelated contexts.

## 199. Counterexamples to Auslander–Reiten, Tachikawa and related homological conjectures

- **Vetting:** 2 manuscript(s); Lean scope note; 2 in formalization.yaml; 0 revised.
- **Plain:** Constructs finite-dimensional algebras over characteristic-2 fields whose extension groups vanish, disproving Auslander-Reiten, Gorenstein-projective, Nakayama, and Wakamatsu conjectures.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L204` -- 1.4 Canonicality is upstream of mass-conservation and of parity
     why: Mentions conservation laws, but in context of Fibonacci recurrence invariants (I-1), not homological extension groups.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Axioms of the algebra system; shared word 'algebra' but owner's algebra is Z[phi] recurrence, not module extensions.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Cross-cutting insights mention 'algebraic'; vocabulary overlap only, no structural connection to homological algebra.

## 200. Eisenbud–Green–Harris and lex-plus-powers

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Eisenbud-Green-Harris and lex-plus-powers conjectures for characteristic-zero: homogeneous ideals with regular sequences have lex-plus-powers ideals preserving Hilbert function and Betti numbers.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Glossary entry mentions 'regular' and 'function'; shared words but applied to Perron-Frobenius spectral theory, not graded Betti numbers.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Foundational lemmas on recurrence algebra; 'sequence' and 'characteristic' words match but context is Z[phi] lattice, not commutative ideal theory.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Mentions homological concepts; word overlap only, no transfer to Zeckendorf / fibbinary framework.

## 201. A counterexample to Kurosh’s division-ring problem

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Constructs countable characteristic-zero division ring algebraic and 2-generated over its center, with infinite dimension—answering Kurosh's problem negatively.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L352` -- 3.1 Binet lifts each lit shell to a Z[phi] coordinate
     why: Binet lifts shells to Z[phi] coordinates; shared ring structure Z[phi], but owner's is commutative integral domain, not division ring (skew field).
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/04_zphi_ring/z_phi_element.md#L1` -- Z[phi] element
     why: Z[phi] ring definition: {a + b*phi : a,b in Z}; shared vocabulary 'ring', 'element', 'algebra' but fundamentally different algebraic structures and problems.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Foundational lemmas; 'characteristic', 'algebra', 'element' words match; actual mathematics orthogonal (infinite-dimensional division ring vs. finite recurrence register).

## 202. The blockwise Alperin weight conjecture

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves blockwise Alperin weight conjecture for all primes and finite groups: in each p-block, the count of irreducible Brauer characters equals the count of conjugacy classes of weights.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L9` -- §0  Compaction-Survival Protocol — read this first
     why: Compaction-Survival Protocol; mentions 'irreducible'; shared vocabulary only (representation-theoretic 'irreducible' vs. algorithmic cascade irreducibility).
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L692` -- 6.1 Closure of the two-register basis
     why: Closure of two-register basis; mentions 'weight'; different context (fibbinary shell weight vs. Lie-theoretic weight in characters).
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L67` -- S5. Perron-Frobenius vector = steady-state bit-density operator
     why: Perron-Frobenius operator; word overlap on 'conjugate' (conjugate matrix vs. conjugacy class); completely distinct mathematical domains.

## 203. Donovan's conjecture over fields and complete mixed-characteristic DVRs

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Donovan finiteness conjecture: for fixed algebraically closed field of characteristic p, blocks of finite groups with bounded defect-group order have finitely many Morita-equivalence classes.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Foundational lemmas; 'characteristic', 'finite', 'order' words match; no connection to block theory or modular representation theory.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Cross-cutting insights; matches on 'abelian', 'represent', 'bounded'; vocabulary overlap in completely different mathematical domain (group blocks vs. recurrence register).
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/stall_predicate.md#L1` -- stall predicate (S_PSI_RETRACT trigger)
     why: Psi-retract operator; mentions equivalence and order constraints, but in context of register state transitions, not block-theoretic equivalence classes.

## 204. Tensor saturation for even spin groups

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves tensor saturation for Spin(2n), n≥2: three dominant integral weights summing to root lattice have invariant iff some positive dilation does—resolves type-D saturation conjecture.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L692` -- 6.1 Closure of the two-register basis
     why: Two-register basis closure; both mention 'lattice' and 'weight', but shell lattice (fibbinary Zeckendorf) and root lattice (Lie theory) are structurally distinct.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L171` -- Addendum: Tensor-Hop Network Reading
     why: Tensor-Hop Network Reading; word overlap on 'tensor', 'lattice', 'invariant'; different mathematical structures (tensor weight representation vs. fibbinary state invariance).
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L435` -- 4.1 Axis 0 — master hand: `A^n` and the global period
     why: Global period and 'dominant' characteristics; both invoke dominant/extremal objects and lattice structures, but in orthogonal domains (spin group representations vs. Fibonacci register dynamics).

## 205. Saxl’s conjecture and universal tensor squares

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves tensor square of every staircase partition's irreducible representation contains all irreducibles of its symmetric group, resolving Saxl's conjecture.
- **CASLO frame:** CASLO implements transfer matrix A=[[1,1],[1,0]] with eigenvalue decomposition (phi,psi) as tensor-network hopping operator; F and L channels are spectral projections onto eigenspaces; cascade rules are irreducible rewrite units.
- **Verdict:** ANALOGY
  1. level 1 (draft 3, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L10` -- Core claim
     why: Core claim: LUT4 fabric IS transfer matrix A applied n times; A = P·diag(phi,psi)·P^-1 with diagonalization and eigenspace projections.
     ruling: Fails level 3, and level 2 as well. The owner item is the spectral theory of one fixed matrix A=[[1,1],[1,0]]: A^n=[[F(n+1),F(n)],[F(n),F(n-1)]], A=P*diag(phi,psi)*P^-1, F/L as eigen-projections, L(n)=tr(A^n), Cassini det(A^n)=(-1)^n, and the Perron-Frobenius vector (phi,1). Family 205 proves positi
  2. level 2 (draft 3, DOWNGRADE) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L171` -- Addendum: Tensor-Hop Network Reading
     why: Tensor-Hop Network Reading: fabric is tensor network with hopping operator; transfer-matrix eigenvalues phi,psi define spectral gap and correlation length.
     ruling: Fails level 3. The family's 'tensor square' is the representation V(x)V of S_n (Kronecker coefficients), not a tensor network. None of the owner's specific objects appears in either manuscript: not A=[[1,1],[1,0]], not the eigenvalues phi/psi, not the spectral gap, the correlation length, the Perron
  3. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Lemma L4b: F and L are eigen-projections of characteristic equation x^2=x+1; both satisfy shared recurrence X(k)=X(k-1)+X(k-2).
     ruling: Lemma L4b is about the 2-dimensional solution space of x^2=x+1: F and L are the antisymmetric and symmetric combinations of phi^k and psi^k fixed by the seeds (0,1) and (2,1), with Binet's formula and the bridge L(k)=F(k-1)+F(k+1). Family 205 has no constant-coefficient linear recurrence, characteri

## 206. Finite lattice representation and undecidability

- **Vetting:** 2 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Shows some finite lattices are not congruence lattices of any finite algebra; proves decidability of full subgroup intervals in finite groups is undecidable.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/BOOLEAN_PATHING.md#L9` -- 1. The type
     why: Word match on representation, lattice; but refers to fibbinary shell-lattice routing, not group-theoretic lattices.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L492` -- THEOREMS T1..T5 AND THE ROOT T0
     why: Word match on algebra; discusses cascade operational algebra, not abstract algebra congruences.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L424` -- 4. The Multi-Dimensional No-Modulo Embedding Clock
     why: Lattice refers to shell index {2..46}, algebra to axioms (x^2=x+1), not finite lattice representation.

## 207. The ℓ¹-Bass conjecture for all discrete groups

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves ℓ1-Bass conjecture: Hattori–Stallings traces of idempotent matrices over ℓ1 group algebras are supported on finitely many finite-order conjugacy classes.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L618` -- §32  Changelog
     why: Word match on idempotent; refers to idempotent cascade operations, not group-ring idempotents or Bass trace.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L271` -- §11  Median algebra — NOT Boolean
     why: Word match on idempotent; discusses median algebra operations, not idempotent matrices in group rings.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L109` -- 3. Math concepts (perused, one line + provenance)
     why: Word matches ring, trace; but refers to Z[phi] ring and shell-trace ops, not Bass trace conjecture.

## 208. Finite symmetric tensor categories and the Verlinde tower

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves every finite symmetric tensor category over algebraically closed field admits faithful strong symmetric monoidal fiber functor to higher Verlinde category.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Word match on symmetric; refers to symmetric eigen-projections F,L, not symmetric monoidal categories.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L171` -- Addendum: Tensor-Hop Network Reading
     why: Word match on tensor; fabric is tensor network but structure fundamentally differs from symmetric tensor categories.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Word match on characteristic; refers to characteristic equation x^2=x+1, not field characteristic.

## 209. Integral counterexamples to Gersten’s conjecture

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Constructs two-dimensional ramified regular local rings of mixed characteristic (0,5) whose integral K-theory classes vanish over fraction fields, disproving Gersten conjecture.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Word match on characteristic; refers to recurrence equation characteristic, not commutative ring characteristic.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L19` -- Derivation DAG
     why: Word match on local; refers to local LUT4 cascade ops, not localization or local rings in algebra.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L109` -- 3. Math concepts (perused, one line + provenance)
     why: Word match on ring; refers to Z[phi] integer ring, not K-theory of mixed-characteristic rings.

## 210. Foulkes' conjecture for sixth powers and quadratic stabilization

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves sixth case of Foulkes' conjecture: Sym^6(Sym^b V) embeds in Sym^b(Sym^6 V) for b≥6; proves quadratic stabilization of canonical Foulkes–Howe map.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Word match on symmetric, power; symmetric = eigen-projection, power = exponent, not symmetric power representations.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L178` -- 1.2 Canonicality forces the Lucas bridge to read single-valuedly (Lemma L5)
     why: Word match on stabilization; refers to cascade convergence to normal form, not symmetric power stabilization.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L492` -- THEOREMS T1..T5 AND THE ROOT T0
     why: Word matches dimension, space; refer to shell index space, not vector space or representation dimension.
