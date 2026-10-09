# Convex and metric geometry -- OpenAI result families in CASLO framing

Levels: 0 none, 1 words, 2 analogy, 3 shared object, 4 direct use. Final levels >= 2 were confirmed by an adversarial verifier; unverified claims are capped at 1.

## 087. The Mahler conjectures, functional inequalities and polar-product symplectic width

- **Vetting:** 3 manuscript(s); Lean scope note; 2 in formalization.yaml; 0 revised; reasoning summary reasoning_traces/symmetric-and-general-mahler-conjectures.pdf.
- **Plain:** Mahler conjectures resolved: every origin-symmetric convex body in ℝⁿ has volume product at least 4ⁿ/n!, with equality for Hanner polytopes; non-symmetric bodies satisfy analogous bounds for simplices.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: Shared vocabulary only: both use 'duality', but owner's duality is eigenspace decomposition (phi/psi) of transfer matrix A, whereas Mahler concerns geometric polar duality of convex bodies—different mathematical objects
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L204` -- 1.4 Canonicality is upstream of mass-conservation and of parity
     why: Shared vocabulary 'conservation' only: owner's mass conservation is I-1=Σ F(k)·R[k] invariance under cascade redexes, whereas Mahler volume products conserve geometric measure under polarity—unrelated domains
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: General mathematical methodology reference; no specific connection to convex volume products or polar geometry

## 088. Sharp projection-body inequalities and a counterexample to simplex maximization

- **Vetting:** 2 manuscript(s); Lean scope note; 2 in formalization.yaml; 0 revised.
- **Plain:** Petty's projection-volume conjecture proved: ellipsoids uniquely minimize projection-body volume among convex bodies of fixed volume in all dimensions ≥4; products of simplices counterexample Brannen's simplex maximum.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_lattice/level0_cascade_adjacency.md#L1` -- Level-0 cascade adjacency
     why: Shared vocabulary 'lattice' only: owner's lattice is shell-index (k∈{2..46}) for cascade composition, not geometric lattice for convex bodies
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L435` -- 4.1 Axis 0 — master hand: `A^n` and the global period
     why: Mentions lattice in discrete arithmetic context; no relevance to projection-body inequalities
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/03_zeckendorf/zeckendorf_theorem.md#L1` -- Zeckendorf theorem
     why: Zeckendorf is unique integer representation via non-consecutive Fibonacci numbers; unrelated to convex geometry or extremal volumes

## 089. Bounded-distortion L1 embeddings of planar and bounded-treewidth graphs

- **Vetting:** 2 manuscript(s); Lean scope note; 2 in formalization.yaml; 0 revised.
- **Plain:** Graph metric-embedding conjecture resolved: shortest-path metrics of finite connected planar graphs embed into L₁ with constant universal distortion; bounded-treewidth graphs embed with distortion bounded by treewidth.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Shared vocabulary 'embedding' only: owner uses register embedding for state representation in cascade pipeline, not metric embedding of graph metrics
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: General methodology; no connection to graph metric distortion bounds
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/07_hyperbolic_jump/product_to_sum.md#L1` -- Product-to-sum (Fibonacci-Lucas), CORRECTED 2026-05-21
     why: Owner's product-to-sum is 5F(m)F(n)=L(m+n)-(-1)ⁿL(m-n), a Fibonacci identity; orthogonal to graph embeddings

## 090. Triangular-lattice optimality, long-range Riesz and Coulomb energies, and spherical logarithmic energy

- **Vetting:** 4 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Triangular lattice proved universally optimal: minimizes lower energy per particle among locally finite planar configurations for every nonnegative completely monotone function of squared distance; resolves Riesz/Coulomb/spherical logarithmic energy conjectures.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_lattice/level0_cascade_adjacency.md#L1` -- Level-0 cascade adjacency
     why: Shared term 'lattice' only: owner's shell lattice k∈{2..46} is finite arithmetic structure for cascade indexing; triangular lattice is geometric lattice in ℝ²
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/WIKI.md#L1` -- Leviathan AI / (phi,psi)-Mechanics — Consolidated Reference (WIKI)
     why: Owner's lattice section discusses discrete cascade composition and shell indexing, not energy optimization over geometric configurations
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L451` -- 4.3 Axis 2 — shell-index hand: `log_phi` rapidity, density `phi^{-k}`
     why: Mentions log_phi rapidity and phi^{-k} density in arithmetic context; unrelated to Riesz energy or lattice minimization

## 091. Logarithmic and Lp Brunn–Minkowski inequalities and the B-conjecture

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Logarithmic Brunn–Minkowski conjecture proved for origin-symmetric convex bodies in every dimension; symmetric Lₚ inequality for 0<p<1; scalar-dilation B-conjecture for even log-concave Radon measures.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Foundational lemmas reference is generic; no connection to convex-body inequalities or log-concave measure theory
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: General methodology; not relevant to Brunn–Minkowski
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L1` -- Transfer Matrix as LUT Fabric — Synthesis
     why: Owner's transfer matrix A is discrete recurrence machinery; orthogonal to continuous convex geometry and measure-theoretic inequalities

## 092. The optimal order of convex-body covering density

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Convex-body covering density determined: every convex body in ℝⁿ, n≥2, admits lattice covering of density Θ(n log n); lower bounds match Rogers' upper bound in every sufficiently large dimension.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_lattice/level0_cascade_adjacency.md#L1` -- Level-0 cascade adjacency
     why: Shared term 'lattice': owner's is discrete shell index {2..46} for cascade adjacency detection, not geometric lattice for translative coverings
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L435` -- 4.1 Axis 0 — master hand: `A^n` and the global period
     why: Owner's Θ(n log n) references concern cascade period bounds, not covering density asymptotics
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/07_hyperbolic_jump/product_to_sum.md#L1` -- Product-to-sum (Fibonacci-Lucas), CORRECTED 2026-05-21
     why: Product-to-sum is arithmetic Fibonacci identity; unrelated to geometric covering bounds

## 093. Dimension-free logarithmic Sobolev inequality for subgaussian log-concave measures

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proved dimension-free logarithmic Sobolev inequality: for log-concave densities with subgaussian marginals, entropy of f² is bounded by a universal constant times parameter-squared times integral of |∇f|².
- **CASLO frame:** Gap-law normalization P(k)=φ⁻ᵏ is self-normalizing in Z[φ]; entropy rate is ln(φ) per shell step. No shared object with Sobolev PDE on ℝⁿ.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: L3 defines entropy rate per tick as ln(φ), dominant eigenvalue of transfer matrix. Same symbol for growth rate, different domain (lattice vs manifold).
     ruling: Owner L3 'entropy rate ln(phi)' is the log of the spectral radius of the 2x2 companion matrix A (growth rate of a linear recurrence). Family 093's entropy is the functional Ent_mu(f^2), bounded by Dirichlet energy C a^2 * integral |Df|^2 dmu for centered log-concave, subgaussian densities on R^n. Th
  2. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/04_zphi_ring/gap_law_normalization.md#L1` -- Gap-law exact normalization
     why: P(gap=k)=φ⁻ᵏ is self-normalizing (max-entropy measure on golden-mean subshift). Parallel structure: both prove a distribution is normalized; different objects.
     ruling: Owner proves sum_{k>=2} phi^-k = 1 by geometric-series telescoping in Z[phi] and names the gap law the Parry (max-entropy) measure of the golden-mean shift. Family 093 never proves that any distribution is normalized; it proves a log-Sobolev inequality, so the claimed parallel 'both prove a distribu
  3. level 1 (draft 2, REJECT) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L242` -- 11. The reachable-set measure (softmax, but intrinsic)
     why: Defines measure on reachable canonical states; both papers bound a measure. No transfer to PDE.
     ruling: Owner sections 11-14 cover: normalization of the phi^-k gap law, topological entropy log(phi), sech kernel ranking via Lucas/Fibonacci reciprocals, the lock bit, and the Mobius-ribbon summary theorem. The owner normalizes a discrete measure; it does not bound one. Family 093 bounds the entropy of f^

## 094. Subpolynomial dimension reduction in Lp

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proved every n-point metric space in Lp (p≠2) embeds into ℓ_p^d with bounded distortion and subpolynomial dimension d=n^o(1), answering Naor's question.
- **CASLO frame:** Shell lattice (k∈[2,46]) acts as coordinate system: transfer matrix A^n maps state via dimension-1 bond structure. No direct shared object with metric geometry.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L171` -- Addendum: Tensor-Hop Network Reading
     why: Maps tensor sites to shell indices, bond dimension 1 (minimal). Both study low-rank embeddings via dimension reduction.
     ruling: Owner L193 window covers: constraints read as tight-binding assumptions, cascade as local Hamiltonian, L-channel as trace of A^n, integrability, anyon quantum dimension phi vs integer bond dimension 1, MPS-LM framing, and operator discipline. There is no ambient/target pair, no embedding, no distort
  2. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Transfer matrix structure with dimension 1. Both involve dimension trade-offs between ambient and target.
     ruling: Owner L193 window covers: constraints read as tight-binding assumptions, cascade as local Hamiltonian, L-channel as trace of A^n, integrability, anyon quantum dimension phi vs integer bond dimension 1, MPS-LM framing, and operator discipline. There is no ambient/target pair, no embedding, no distort
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L5` -- Scope
     why: Shell lattice provides coordinate indexing. Superficial: both use coordinates, no structural homology.

## 095. Hyperbolicity cones without semidefinite lifts

- **Vetting:** 3 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Disproved the Projected Lax conjecture: some hyperbolicity cones admit no finite affine semidefinite lift, even with arbitrary coefficients and auxiliary variables.
- **CASLO frame:** Z[φ] ring composition (d'Ocagne/Vajda) relates Fibonacci indices algebraically. No shared object with hyperbolicity cones or convex geometry.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/04_zphi_ring/ring_compose.md#L1` -- Ring composition (d'Ocagne / Vajda)
     why: Expresses index addition as ring multiplication in Z[√5]. Shared vocabulary 'ring, algebra' only. No transfer to semidefinite geometry.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L271` -- §11  Median algebra — NOT Boolean
     why: Discusses algebraic constraints. Vocabulary only; hyperbolicity is convex geometry, not lattice algebra.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L9` -- §0  Compaction-Survival Protocol — read this first
     why: Mentions constraints and algebra. Vocabulary overlap only, no structural transfer.

## 096. The Gaussian propeller conjecture in every dimension

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proved the Gaussian propeller conjecture: sum of squared first moments of any finite partition of Euclidean space is at most 9/(8π); three planar sectors attain the bound when d≥2.
- **CASLO frame:** Zeckendorf theorem decomposes integers into non-consecutive Fibonacci sums; moments tracked via shell indices. No shared object with Gaussian moments on manifolds.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/03_zeckendorf/zeckendorf_theorem.md#L1` -- Zeckendorf theorem
     why: Every positive integer has unique Fibonacci decomposition. Vocabulary: sum, theorem. No connection to Gaussian moments.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L505` -- 5.1 The generating basis
     why: Tracks state as pair (a,b); propeller sums moments. Both sum quantities, vocabulary only.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/helmet/nodes/s01-08-13-18-22-26.md#L1` -- Zeckendorf theorem
     why: Reference copy of match 1.

## 097. The Euclidean Steinitz–Bergström bound

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proved the Euclidean Steinitz–Bergström conjecture: any finite sequence in unit ball ℝᵈ has signing with partial sums bounded by C√d, independent of length. Optimal S₂(d)=Θ(√d).
- **CASLO frame:** Shell-indexed sequence (k∈[2,46]); Zeckendorf addressing maps shells to bit positions. Both bound partial sums/states by dimension. Structural parallel: dimension-dependent bound.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L398` -- 3.3 The centroid moment M is a third orthogonal projection
     why: State M tracks cumulative quantity; partial sums are cumulative. Both bound cumulative sums by dimension-dependent function Θ(√d) vs Θ(φⁿ).
     ruling: Owner M = sum_k k*R[k] is a first (centroid) moment of a bit register, not a cumulative or partial sum over a sequence. The window's other objects are: linear-functional independence (Lemma 3.B, L12), master period ord(A), Cassini period 2 via k AND 1, and phi^-k density. The window's only signed su
  2. level 1 (draft 2, REJECT) `caslo_test_framework/docs/MASTER_CONTROL.md#L111` -- §4  Zeckendorf representation — the addressing scheme
     why: Maps integers to shell indices. Both index sequences and ensure bounds; dimension-dependent growth.
     ruling: Owner sections 4-5 cover: Zeckendorf uniqueness (stated), content addressing, CC1-CC4 cascade rewrite rules, Church-Rosser confluence, sum preservation, and sweep firing counts. Family 097 is about signing or reordering vectors in R^d so that prefix-sum norms stay <= C sqrt(d). The integer-to-shell 
  3. level 1 (draft 2, REJECT) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L58` -- 2. Zeckendorf addressing — the tape of the ribbon
     why: Addresses states by shell sequence with dimensional constraints.
     ruling: Owner sections 2-4 cover: fibbinary legality, Zeckendorf existence/uniqueness (greedy, with max legal sub-sum < F(k+2)), index shift sigma, graded fold with gutters, and injective packing (Theorem 4.3). The only bound on a sum is a telescoping upper bound on a positive Fibonacci sum, used for unique

## 098. Compact counterexamples to bi-Lipschitz dimension reduction

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Disproved Lang–Plaut problem: every infinite-dimensional Banach space contains compact doubling set with no bi-Lipschitz embedding into finite-dimensional space, universal doubling constant.
- **CASLO frame:** Entropy rate ln(φ) per A-step bounds information growth; reachable set F(n+2) after n steps. Both show dimensional limits on embedding via exponential growth.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L57` -- S4. Spine entropy rate = throughput operator
     why: Reachable set grows as F(n+2) ∼ Θ(φⁿ); Lang–Plaut shows doubling has exponential growth incompatible with finite embedding.
     ruling: Owner 'bond dimension 1 bit per leg' is tensor contraction rank in a physics analogy. Family 098 has no tensor structure, and its conclusion is that no finite target dimension exists at all, not 'exponential dimension' as the claim says. Owner 'Fibonacci-quotient Hilbert space' is a loose state-spac
  2. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L171` -- Addendum: Tensor-Hop Network Reading
     why: Bond dimension 1 (minimal); doubling metric requires exponential dimension. Both constrain dimension in metric/tensor structures.
     ruling: Owner 'bond dimension 1 bit per leg' is tensor contraction rank in a physics analogy. Family 098 has no tensor structure, and its conclusion is that no finite target dimension exists at all, not 'exponential dimension' as the claim says. Owner 'Fibonacci-quotient Hilbert space' is a loose state-spac
  3. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Entropy rate ln(φ) gives exponential growth; finite embedding needs bounded growth. Structural analogy: exponential growth limits embedding.
     ruling: Owner L1-L4b covers: the shared F/L recurrence, a 2-dimensional linear solution space, Binet in Z[phi], A^n closed form with ln(phi) growth, the Cassini determinant, and the canonicality predicate. 'Embedding' in this window refers to the positional embedding clock, not a bi-Lipschitz metric embeddi

## 099. The sharp exponential scale of edit-distance distortion

- **Vetting:** 3 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Edit distance on strings requires exponential ℓ1 distortion exp(Θ(√(log d·log log d))) where d bounds string length; the bound holds uniformly over all finite alphabets and is tight up to constants.
- **CASLO frame:** CASLO's transfer matrix A with eigenvalues phi, psi governs exponential growth on the shell lattice via recursive application. Family 099 embeds strings into ℓ1 using hopping operators; both exploit transfer matrices and eigenvalue-driven exponential scaling, though ℓ1 geometry differs from fibbinary-lattice structure.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Section 'What this buys us conceptually' explains that the cascade rule acts as a local Hamiltonian on a tight-binding lattice, with transfer matrix A mapping (a,b) pairs. Edit distance similarly uses transfer operators to embed strings; both exploit 2×2 matrix eigenvalues (phi, psi) to bound expone
     ruling: The claim's stated basis is false for family 099. I grepped all three manuscripts' LaTeX (math/preprints/Edit-Distance-in-l1-*, Finite-Circle-Obstructions-*, Tree-Constructions-*/build). None contains a transfer matrix or transfer operator, an eigenvalue, Perron-Frobenius, Fibonacci, the golden rati
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/04_zphi_ring/hyperbolic_distance.md#L1` -- Hyperbolic distance
     why: Defines hyperbolic distance d(m,n) = |m−n| on the shell lattice. Family 099 concerns edit distance metrics, but on continuous ℓ1 rather than discrete fibbinary domains; shared vocabulary only.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/03_zeckendorf/zeckendorf_theorem.md#L1` -- Zeckendorf theorem
     why: Zeckendorf representations use Fibonacci summands. Family 099 uses words and strings; CASLO uses fibbinary words. Shared discrete structure vocabulary, but applied to different mathematical objects.

## 100. Cylinder coverings below the half-area bound

- **Vetting:** 4 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Finite cylinder coverings of regular tetrahedra achieve total perpendicular base area less than half the minimum orthogonal projection area, disproving Bang's half-area conjecture and the directionwise normalized variant.
- **CASLO frame:** No shared object with the owner's framework. CASLO operates on discrete Fibonacci-indexed shell lattices with fibbinary (no-adjacent-1s) constraints and Z[phi] ring arithmetic. Family 100 addresses purely Euclidean convex geometry with continuous projections and volume measures—fundamentally different mathematical domains.
- **Verdict:** NONE

## 101. The sharp simplex conjecture for isotropic constants

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Simplices uniquely maximize the isotropic constant L_K among all convex bodies in every dimension. The sharp entropy bound h(f) ≥ m + ½log det Cov(f) holds for log-concave probability densities, with equality for exponential product laws.
- **CASLO frame:** CASLO derives entropy rate s = ln(phi) from the transfer matrix A's dominant eigenvalue via the topological-entropy theorem. Family 101 uses Perron-Frobenius eigenvalue analysis to bound Shannon entropy of log-concave densities. Both frameworks invoke Perron-Frobenius theory and link eigenvalues to entropy, but CASLO's domain is discrete lattice paths (topological entropy) while Family 101 works with continuous probability (differential entropy).
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: States the general formula s = lim(1/n)ln Ω(n) = ln λ_max(A). CASLO applies this to transfer matrix A with λ_max = phi. Family 101 uses eigenvalue methods for covariance analysis; both invoke the same topological-entropy formula relating growth to dominant eigenvalues.
     ruling: The claim that '101's entropy bounds derive from Perron-Frobenius analysis on covariance matrices' is false. 101 derives its bound from Gaussian-to-target Brenier transport, Caffarelli regularity, the normalization E[A]=0 of the matrix field A=q^{-1}(D^2 phi), matrix-function derivative estimates th
  2. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L67` -- S5. Perron-Frobenius vector = steady-state bit-density operator
     why: Section 'Perron-Frobenius vector' shows v_PF = (phi, 1) with steady-state density φ^{-k}. CASLO uses Perron-Frobenius eigenvector directly for bit-density analysis. Family 101 invokes Perron-Frobenius theory for isotropic constant bounds; shared eigenvalue method but different probability models.
     ruling: The claim that '101's entropy bounds derive from Perron-Frobenius analysis on covariance matrices' is false. 101 derives its bound from Gaussian-to-target Brenier transport, Caffarelli regularity, the normalization E[A]=0 of the matrix field A=q^{-1}(D^2 phi), matrix-function derivative estimates th
  3. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Explains integrability via A^n closed form with Perron-Frobenius eigenvalues phi, psi. Family 101's entropy bounds derive from Perron-Frobenius analysis on covariance matrices; both invoke the eigenvalue-entropy link, though applied to discrete vs. continuous structures.
     ruling: The claim that '101's entropy bounds derive from Perron-Frobenius analysis on covariance matrices' is false. 101 derives its bound from Gaussian-to-target Brenier transport, Caffarelli regularity, the normalization E[A]=0 of the matrix field A=q^{-1}(D^2 phi), matrix-function derivative estimates th
