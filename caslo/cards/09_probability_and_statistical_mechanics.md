# Probability and statistical mechanics -- OpenAI result families in CASLO framing

Levels: 0 none, 1 words, 2 analogy, 3 shared object, 4 direct use. Final levels >= 2 were confirmed by an adversarial verifier; unverified claims are capped at 1.

## 211. The geometric phase diagram, diffusion, and spectra of random planar maps

- **Vetting:** 7 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Random walks on critical Fortuin–Kasteleyn planar maps converge to Liouville Brownian motion; spectral measures converge; eigenvalues of the transfer operator limit to those of the continuum sphere.
- **CASLO frame:** Transfer matrix eigenvalue analysis of 2D walk limits. Owner uses transfer operators on fibbinary registers with phi, psi eigenvalues (EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md S2); family analyzes spectral convergence of random walks on random maps. No shared mathematical objects or shared problem domain.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L36` -- S2. The F-channel and L-channel ARE the eigenspaces
     why: Both invoke transfer matrix diagonalization; owner's A = [[1,1],[1,0]] with eigenspaces F-channel (phi) and L-channel (psi); family: transfer operator spectrum on Liouville sphere. Structure analogy only, different objects and domains.
     ruling: Family 211 never uses a transfer matrix or transfer operator, so the claimed 'transfer operator spectrum on Liouville sphere' is not in the family text. Its objects are FK and spanning-tree planar maps, their Gromov-Hausdorff-Prokhorov scaling limits (Liouville quantum gravity spheres, Brownian cont
  2. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L223` -- 2. The Cascade as Renormalization Information-Flow
     why: Owner describes cascade as 'renormalization information-flow' using transfer operators on shell lattice, preserving I-1 conserved current. Family: spectral renormalization on random maps. Both renormalize a state space; different objects and purposes.
     ruling: Owner section 2 is a confluent rewriting system: Zeckendorf carry R1/R3, the Lucas bridge and the x5 focus gate, each proven to conserve I-1 = Sum F(k)R[k]. Here 'transfer operator' and 'RG level' are labels for local rewrite rules, not a renormalization map or a scaling limit. Family 211 has no ren
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: Owner has entropy-rate law keyed to phi eigenvalue and log(phi) decay rates. Family: spectral convergence with heat traces. Both use eigenvalue decay; vocabulary only.

## 212. Planar first-passage geometry and the absence of bigeodesics

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** First-passage percolation on planar graphs has no doubly-infinite geodesic for nonatomic iid edge weights; exponential and Gamma models have strictly convex limit shapes with C1 boundaries.
- **CASLO frame:** No shared object with the owner's framework. Family studies lattice percolation geometry; owner studies fibbinary token encoding on deterministic FPGA substrate with no randomness or limit shapes.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L178` -- 1.2 Canonicality forces the Lucas bridge to read single-valuedly (Lemma L5)
     why: Owner describes strict-Boolean routing; family studies strictly convex limit shapes. Vocabulary overlap only (strict, convex); no shared mathematical structure.

## 213. Critical percolation on every quasi-transitive graph

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Bond and site percolation at criticality have no infinite cluster on quasi-transitive graphs, resolving the Benjamini–Schramm criticality conjecture for all locally finite nonamenable graphs.
- **CASLO frame:** No shared object with the owner's framework. Family analyzes phase transitions on infinite random graphs; owner analyzes deterministic cascade dynamics on finite fibbinary shells.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/03_zeckendorf/zeckendorf_theorem.md#L1` -- Zeckendorf theorem
     why: Both mention lattices: family uses vertex lattice in percolation graphs; owner uses Fibonacci shell lattice as address space. Different lattice structures; vocabulary overlap only.

## 214. The Benjamini–Schramm nonuniqueness conjecture

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Bernoulli percolation has p_c < p_u on every nonamenable quasi-transitive graph, so infinitely many infinite clusters exist in a nonempty probability interval; proves operator-threshold conjecture.
- **CASLO frame:** No shared object with the owner's framework. Family studies percolation phase diagram on random graphs; owner computes deterministic token sequences on fixed Fibonacci-indexed shells.
- **Verdict:** NONE

## 215. Canonical $O(3)$ continuum limit and exact $O(4)$ mass asymptotics

- **Vetting:** 5 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Two-dimensional O(n) models have exact continuum limits, explicit mass asymptotics (O(4): m ∼ 32 exp(π/4 − 1/2) √β exp(−πβ)), isolated particle poles, and exponential spin-correlation decay for n ≥ 3.
- **CASLO frame:** Transfer operator analysis of 2D lattice spin systems, measuring mass gaps and spectral convergence. Owner uses transfer matrix A with Perron-Frobenius eigenvector (phi, 1) and bit-density decay phi^{−k}; family analyzes O(n) model transfer operator spectrum. Both employ transfer operators for spectral analysis of 2D systems; shared structure but different problem domains (deterministic vs. statistical).
- **Verdict:** ANALOGY
  1. level 2 (draft 2, CONFIRM) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L67` -- S5. Perron-Frobenius vector = steady-state bit-density operator
     why: Both use Perron-Frobenius analysis: owner defines bit-density ∝ phi^{−k} as right Perron-Frobenius eigenvector; family: transfer operator eigenvalues govern asymptotic mass decay. Same mathematical structure (eigenvalue decay), different application (deterministic token encoding vs. physical O(n) mo
     ruling: Level 2 holds. Owner S5 takes the Perron-Frobenius eigenvector of A as the stationary state and reads an exponential rate from A's spectrum. A really is a transfer matrix: the doc names it one, uses s = ln(lambda_max) as the entropy rate, and counts F(n+2) no-adjacent-1 configurations. Family 215's 
  2. level 2 (draft 2, CONFIRM) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L36` -- S2. The F-channel and L-channel ARE the eigenspaces
     why: Both analyze transfer operator spectra: owner has A diagonalizing with D = diag(phi, psi) and P = [[phi, psi], [1,1]]; family computes continuum spectrum of O(n) transfer operator. Shared eigenspace methodology; different objects and domains.
     ruling: Level 2 holds, though it is weaker than the S5 pairing. Owner S2 is the spectral decomposition of the doc's transfer matrix A: spectrum {phi, psi} with |psi| < 1 < phi; the phi-component dominates and the psi term shrinks exponentially; and L_n = tr(A^n), the trace-of-powers form of the transfer-mat
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: Owner derives entropy ∝ log(phi) from eigenvalue; family studies exponential mass decay. Both scale with eigenvalues; vocabulary overlap in decay rate notion.

## 216. Critical and near-critical XY scaling and BKT universality

- **Vetting:** 6 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** XY model on 2D square lattice has critical correlation exponent 1/4, logarithmic corrections C_c(r) ∼ r^{−1/4}(log r)^{1/8}, BKT essential singularity, and Gaussian scaling limits for discrete Gaussian heights throughout rough phase.
- **CASLO frame:** No shared object with the owner's framework. Family analyzes critical exponents and scaling limits of 2D classical lattice field theories; owner encodes tokens in Zeckendorf fibbinary, deterministic and finite.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/02_identities/focus_multi_hot.md#L1` -- Focus identity over a multi-hot register
     why: Owner handles multi-valued field encodings on lattice-like structures; family: field convergence on lattice sites. Vocabulary overlap (field, lattice); no shared mathematical objects.

## 217. The low-temperature Sherrington–Kirkpatrick fluctuation law

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** For Gaussian Ising spin glass at inverse temperature β > 1, the log partition function variance scales as n^(1/3), standard deviation n^(1/6). Centered and standardized, it converges to a nondegenerate limiting law.
- **CASLO frame:** The zero-field log partition function behaves as a golden-mean-scaled measure with Boltzmann weight φ^(-k), but over an external temperature parameter β, not intrinsic system scaling.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L242` -- 11. The reachable-set measure (softmax, but intrinsic)
     why: Line 242 defines P(gap=k)=φ^(-k) with inverse temperature β=ln φ, paralleling SK variance scaling. Shared vocabulary (Boltzmann weight, entropy, log φ) but different systems: SK is statistical mechanics of spins; owner is measure on reachable words.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/05-entropy-test/golden-mean-shift.md#L1` -- [V]/[C] Entropy as an exponent of phi
     why: Rate s_n = ln Ω(n)/n → ln φ, exact residual. Same golden-mean scaling and entropy formula, but applied to constraint counting (Fibonacci), not partition function variance.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Discusses deterministic scaling and limit theorems, but no shared mathematical object with SK free energy.

## 218. Conformal universality for weakly interacting and random-bond Ising models

- **Vetting:** 6 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Weak perturbations of square-lattice Ising model preserve critical bulk limits and conformal structure. Weak quenched disorder of mean-zero law preserves chordal SLE3 interface convergence.
- **CASLO frame:** The system exhibits phase-register transitions with boundary gating, but the shared object (phase, boundary condition) operates in a lattice statistical model, not an embedding FSM.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L636` -- 5.4 R(t-1) triple-duty
     why: Line 636 discusses phase-register boundary conditions and Markov latching. But owner's phase register is a 5-state clock cycle (period ~F(W+2)), not Ising criticality.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L467` -- 4.5 Axis 4 — phase-register hand: latched `R`, period `~F(W+2)`, Markov boundary (Lemma L1
     why: Defines phase register period as ~F(W+2), matching boundary condition language. But structure is token embedding lifecycle, not ferromagnetic spin lattice.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: No phase transition or conformal structure; concerns φ/ψ algebra and Boolean logic.

## 219. GOE bulk universality for regular graphs with weak Anderson disorder

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Bulk adjacency-eigenvalue point process of uniform d-regular graph converges to Gaussian orthogonal ensemble law, with fixed-energy GOE universality persisting under weak iid diagonal disorder.
- **CASLO frame:** The system exhibits matrix eigenvalue point process universality with density of states scaling, matching owner's transfer matrix [[1,1],[1,0]] with Perron-Frobenius eigenvalue φ, but GOE is statistical universality, not deterministic recurrence.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L451` -- 4.3 Axis 2 — shell-index hand: `log_phi` rapidity, density `phi^{-k}`
     why: Line 451 defines density scaling φ^(-k) with eigenvalue φ from transfer matrix [[1,1],[1,0]]. Shared object: transfer matrix eigenvalue λ_max(A)=φ, but GOE is random matrix universality; owner's matrix is deterministic Fibonacci recurrence.
     ruling: Family 219 (show.py 219) is about random-matrix bulk universality. The unfolded microscopic eigenvalue point process of an N x N random d-regular adjacency matrix, with weak iid diagonal Anderson disorder, converges to the GOE as N -> infinity. The rescaling uses the Kesten-McKay / infinite-tree den
  2. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L1` -- Transfer Matrix as LUT Fabric — Synthesis
     why: States 'The LUT4 fabric IS the transfer matrix A applied n times' where A=[[1,1],[1,0]] with eigenvalue φ. Same structured object (matrix eigenvalue as system parameter), different context: owner uses deterministic Fibonacci matrix; GOE studies random adjacency matrices.
     ruling: Owner L1-61 diagonalizes one fixed 2x2 integer matrix A=[[1,1],[1,0]]: eigenvalues phi and psi, tr(A^n)=L_n, det(A^n)=(-1)^n (Cassini), and the F/L channels as its eigendirections. Family 219 proves GOE local statistics for the bulk spectrum of large random d-regular adjacency matrices under weak ra
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L481` -- 4.6 Non-commensurability — the joint odometer has no shared modulus
     why: Discusses lattice structure and eigenvalue in context of modular arithmetic constraints, not spectral universality.

## 220. Directional zero–one laws beyond iid environments and iid ballisticity

- **Vetting:** 3 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Random walk on Z^d in random environment: directional escape has probability zero or one; almost-sure transience in a direction implies deterministic limiting velocity (ballistic behavior) with positive projection.
- **CASLO frame:** The system exhibits deterministic velocity emergence from randomness (random environment), but operates via probabilistic transitions, not cascade conservation laws.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L251` -- VI. Meaning is not authority (L6, Prop 4)
     why: Mentions random walk but in context of nonauthority semantics, not random environment or ballistic behavior.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L424` -- 4. The Multi-Dimensional No-Modulo Embedding Clock
     why: Discusses deterministic evolution and embeddings, but no random environment or transience.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/LUT_FABRIC_LM_ALGORITHM.md#L320` -- §6.3  Why "deterministic"
     why: No random walk or ballistic velocity concepts.

## 221. The Mézard–Parisi formula for diluted spin glasses

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised; reasoning summary reasoning_traces/mezard-parisi-formula.pdf.
- **Plain:** Proves hierarchical cavity formula for Poisson-diluted Ising models: limiting free energy equals infimum over finite-depth hierarchical trial laws, requiring only first-moment integrability.
- **CASLO frame:** The system exhibits hierarchical variational structure optimizing over trial distributions, matching owner's cascade composition and proj-derive/proj-shed layering, but in different algebraic context.
- **Verdict:** WORDS
  1. level 0 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Defines 'foundational lemma' structure for hierarchical system properties. Both systems have variational hierarchy (Mézard-Parisi infimum; owner's proj-derive hierarchy), but applied to disordered spin glass vs. token embedding dynamics.
     ruling: Owner L119-179 contains Foundational Lemmas L1-L4b: the shared Fibonacci/Lucas recurrence, Binet phi^n = F(n)phi + F(n-1) in Z[phi], the closed form of A^n, Cassini det(A^n)=(-1)^n, and F/L as antisymmetric/symmetric eigen-projections. Family 221 (show.py 221) concerns Gibbs measures of Poisson-dilu
  2. level 1 (draft 2, REJECT) `caslo_test_framework/docs/MASTER_CONTROL.md#L360` -- §15  Three colours — bij / proj-derive / proj-shed / recording
     why: Introduces variational colour taxonomy (bij/proj-derive/proj-shed), creating hierarchy analogous to Mézard-Parisi trial laws. Same kind of structure (variational decomposition), different algebraic objects.
     ruling: Owner §15 (L360) sorts engine operations into four labels: bij = bijective, proj-derive = irreversible aggregation, proj-shed = discard, recording = side-channel write. It adds a rule that proj-shed needs a recording. The rest of the window covers three failure 'cliffs' and a three-layer persistence
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/zlogpi/zphi.py#L97` -- ZPhi
     why: Algebraic computation; no cavity formula or spin glass concepts.

## 222. Perceptron free energies and microscopic jamming exponents

- **Vetting:** 4 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Determines free energy of Ising and spherical perceptrons at every positive pattern density; at margin −1, sharp jamming threshold and limiting gap/force laws with critical exponents γ=(2+θ)^(−1).
- **CASLO frame:** The system exhibits feasibility thresholds and critical exponents, matching owner's proj-shed margin gates and threshold-dependent behavior, but in learning dynamics context, not statistical jamming.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XV_FED_MEMORY_GRC.md#L169` -- Proposition III — A single token cannot approach the headroom.
     why: Line 169 defines margin constraint on token evolution, using 'margin' vocabulary paralleling perceptron margin −1. But owner's margin is deterministic gate constraint, not statistical jamming threshold.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_X_UNIFIED_LM.md#L295` -- XII. The free-run gate
     why: Discusses threshold behavior in token-embedding context, not statistical feasibility or critical exponents.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L360` -- §15  Three colours — bij / proj-derive / proj-shed / recording
     why: Defines proj-shed (threshold operations), but no critical exponents or jamming dynamics.

## 223. Random-cluster interfaces: critical, disordered, thermal, and natural-time scaling

- **Vetting:** 6 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves that critical random-cluster Dobrushin interfaces on square lattices converge to Schramm-Loewner Evolution (SLE) curves. Under marked boundary conditions, the complete nested loop collections converge to Conformal Loop Ensembles (CLE). Both conformal invariance and loop multiplicities are preserved in the scaling limit.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** ANALOGY
  1. level 2 (draft 2, CONFIRM) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L28` -- S1. The pipeline IS A^32 in canonical-form quotient
     why: Both SLE and Zeckendorf cascade are scaling limits of lattice-indexed systems. OpenAI uses transfer-matrix conformal theory; owner uses A = [[1,1],[1,0]] for Fibonacci recurrence scaling. Shared structure: lattice → continuous limit via transfer matrix eigenvalue analysis.
     ruling: The stated rationale is wrong. The Zeckendorf cascade is a finite rewrite quotient, not a scaling limit, and the show.py abstracts never mention transfer matrices. Level 2 stands on the manuscripts: the FK proofs run Perron-Frobenius analysis of six-vertex transfer matrices. In /mnt/c/Users/casma/ma
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L489` -- 4.7 The deepest cycle — `I-1` conservation as the period-1 hand
     why: Discusses conservation laws and fixed points in cascade dynamics. SLE also relies on conserved crossing probabilities and fixed-point structure, but in continuous conformal setting.
  3. level 2 (draft 2, CONFIRM) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: Both SLE scaling and Zeckendorf cascade growth are controlled by Perron-Frobenius eigenvalues. Owner's s = ln(phi) directly parallels SLE's dimension formula (6 + phi for some kappa values in scaling theory).
     ruling: The claimed '6 + phi' SLE dimension link does not exist. SLE_kappa dimension is 1 + kappa/8 with kappa = 4pi/arccos(-sqrt(q)/2), and SLE scaling is not set by a PF eigenvalue. Level 2 stands on manuscript evidence instead. /mnt/c/Users/casma/math/preprints/Self-dual-random-cluster-interfaces-below-o

## 224. Critical and quenched near-critical universality for Poisson–Voronoi percolation

- **Vetting:** 3 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Cardy's conformal-crossing formula for annealed Poisson-Voronoi percolation in every Jordan quadrilateral. Establishes that near-critical thresholds for rational polygonal domains converge to the triangular-lattice universality class under the monotone coupling.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Glossary section contains probability, parameter, and formula terminology. Cardy's formula is a crossing-probability result; owner's framework mentions formulas and thresholds but not in probabilistic/percolative sense.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/UPGRADE/caslo_monolith/harness/docs/ELEMENTS_BOOK_XVI_HETEROGENEITY.md#L34` -- Propositions
     why: Discusses universality and thresholds. OpenAI's result is about universality classes in percolation; owner mentions universality in encoding/routing context, not percolation.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Foundational lemmas on convergence and thresholds. Voronoi percolation examines threshold behavior under coupling; owner's platform examines convergence of signal thresholds in coding.

## 225. Gaussian free field limits throughout the balanced six-vertex regime

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** The height function of the square-lattice six-vertex model with unit weights and free boundary converges to a Gaussian free field (GFF). The variance multiplier is 1/arcsin(c/2), where c scales the vertex weight. This establishes the scaling-limit relationship between six-vertex height and continuous GFF.
- **CASLO frame:** both six-vertex and Zeckendorf cascade involve scaling limits of lattice systems with eigenvalue-controlled growth. The variance in GFF scaling parallels phi-eigenvalue dominance in cascade quotient growth, but applied to different mathematical objects (height functions vs. shell occupancy).
- **Verdict:** ANALOGY
  1. level 2 (draft 2, CONFIRM) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L67` -- S5. Perron-Frobenius vector = steady-state bit-density operator
     why: Perron-Frobenius vector = steady-state bit-density operator, expressed as phi^{-k} scaling. Six-vertex height variance arcsin(c/2) is analogous eigenvalue-driven scaling in conformal structure, though with different operator.
     ruling: The claim's pairing of S5 with the variance multiplier 1/arcsin(c/2) is not a shared structure, but level 2 stands on the manuscript. /mnt/c/Users/casma/math/preprints/The-Gaussian-free-field-limit-of-the-balanced-six-vertex-model-with-variance-multiplier-1-over-arcsin-c-over-2-September-23-2026/bui
  2. level 2 (draft 2, CONFIRM) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L451` -- 4.3 Axis 2 — shell-index hand: `log_phi` rapidity, density `phi^{-k}`
     why: Shell-index hand uses log_phi rapidity with density phi^{-k}. GFF variance scaling is logarithmic in lattice spacing; owner's shell density decays as phi^{-k}, both are logarithmic/exponential scaling limits.
     ruling: The claimed link (log GFF covariance vs. log_phi rapidity) is not a shared structure: one is a correlation kernel of a random field, the other a coordinate change. Level 2 still stands within the window. Theorem 4.3's proof ('A is a non-negative primitive matrix, so by Perron-Frobenius it has a uniq
  3. level 2 (draft 2, CONFIRM) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: Entropy-rate law: s = ln(lambda_max). Both six-vertex GFF variance and Zeckendorf cascade cardinality growth are controlled by Perron-Frobenius eigenvalues in their respective transfer-matrix formulations.
     ruling: Level 2 holds, arguably 3. The six-vertex manuscript chooses tori long enough 'to realize the Perron asymptotic', so 'constrained log partition functions per vertex tend to p_*', and it uses 'entropy plus mean log weight equals log partition function' (/mnt/c/Users/casma/math/preprints/The-Gaussian-

## 226. The double-dimer loop ensemble converges to CLE4

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves that the complete loop ensemble formed by two independent dimer coverings of the Temperleyan square lattice converges to nested Conformal Loop Ensemble (CLE4). The convergence holds along the full mesh limit, matching each macroscopic loop as an unparametrized curve.
- **CASLO frame:** both double-dimer CLE4 and Zeckendorf cascade are lattice-to-continuum scaling limits. Owner uses transfer matrix A with conservation laws for discrete recurrence; double-dimer uses transfer-matrix dimer coupling. Both converge to measure-preserving limits, but objects are distinct (loop ensembles vs. shell-pattern normal forms).
- **Verdict:** ANALOGY
  1. level 2 (draft 2, CONFIRM) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L28` -- S1. The pipeline IS A^32 in canonical-form quotient
     why: Pipeline IS A^32 in quotient; cascade is the quotient projection. Double-dimer ensemble converges via transfer-matrix scaling; owner's cascade also uses transfer-matrix quotient to canonicalize. Shared structure: lattice-indexed transfer matrix scaling.
     ruling: The claim's mechanism is wrong: the cascade quotient is not a transfer matrix, and nothing in S1 is a scaling limit. Level 2 stands on the manuscript. The double-dimer estimates 'come from a transfer matrix counting dimer configurations column by column'. A boundary state records which dimers cross 
  2. level 1 (draft 2, REJECT) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L148` -- I. Mass is preserved under R1/R3 (L1, P1)
     why: Mass is preserved under R1/R3 (conservation law). Double-dimer loop-mass and multiplicity are conserved in the CLE4 limit; owner's conservation I-1 = Sum F(k)*R[k] is invariant under cascade.
     ruling: Family 226 has no conservation law. 'Mass' there is probability-measure mass: 'limiting mass' at 10-introduction.tex:222 and the reparametrization measure eq:partition-mass at 40-localization.tex:434. Nothing about loop mass or multiplicity is conserved, and convergence is in law. Owner Prop. I (L14
  3. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L223` -- 2. The Cascade as Renormalization Information-Flow
     why: Cascade as renormalization information-flow. CLE4 is a renormalized scaling limit of the double-dimer system; owner's cascade is discrete RG flow that preserves information in shell-pattern equivalence classes.
     ruling: No renormalization or RG appears in the 226 manuscript sources. CLE4 is reached through tightness estimates from a column transfer matrix plus identification of loop observables, not an RG flow. The owner's 'RG' (L223) is a label on Zeckendorf carry/split rewrites (R1/R3, Lucas bridge, focus) that p

## 227. Critical SK autocorrelation processes and dynamics across the temperature transition

- **Vetting:** 8 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** For Sherrington-Kirkpatrick (SK) spin-glass heat-bath dynamics at critical inverse temperature beta = 1, proves universal joint convergence of stationary and quench autocorrelations with Gaussian and Rademacher disorder. Establishes spectral gaps and mixing-time exponents (n^{2/3+o(1)}) throughout high-temperature phase.
- **CASLO frame:** SK spectral gap and mixing behavior are properties of the transfer matrix governing heat-bath dynamics. Owner's TRANSFER_MATRIX_AS_LUT_FABRIC.md explicitly discusses spectral gap (L137: 'only the spectral gap matters') and mixing property (L144) in context of A = [[1,1],[1,0]] eigenvalues phi/psi. Both use transfer-matrix spectral analysis to understand dynamics and timescales.
- **Verdict:** ANALOGY
  1. level 2 (draft 3, DOWNGRADE) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L137` -- A2. A^∞ has no fixed point — only the spectral gap matters
     why: A^∞ spectral gap section directly addresses spectral-gap control of mixing behavior. SK model spectral gap determines heat-bath mixing time; owner writes 'This is the engine's mixing property — the algebraic substitute for thermalization' at L144, exactly paralleling SK's mixing-to-equilibrium conce
     ruling: Level 3 fails: 'spectral gap' names different objects. Family 227 defines it as the infimum of Dirichlet form over variance for the SK heat-bath generator, giving relaxation to the Gibbs measure (/mnt/c/Users/casma/math/preprints/A-spectral-gap-throughout-the-high-temperature-Sherrington-Kirkpatrick
  2. level 1 (draft 3, REJECT) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: Perron-Frobenius eigenvalue lambda_max controls entropy rate s = ln(lambda_max). SK critical exponents and autocorrelation scaling are controlled by spectral gap (Perron-Frobenius eigenvalue separation). Shared object: Perron-Frobenius eigenvalue as mixing-rate governor.
     ruling: The claimed shared object (PF eigenvalue as mixing-rate governor) is in neither text. In the owner note lambda_max sets a growth rate (topological entropy of a constrained count), not a mixing rate. Family 227 has no Perron-Frobenius eigenvalue or transfer matrix: 0 hits for 'Perron' or 'transfer ma
  3. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L489` -- 4.7 The deepest cycle — `I-1` conservation as the period-1 hand
     why: I-1 conservation at period-1 fixed point under all operators. SK autocorrelation convergence and fixed point of dynamics are both stabilized by conserved quantities; owner's period-1 invariance parallels the equilibrium fixed point of SK Gibbs measure.
     ruling: SK heat-bath dynamics conserves nothing: single-site updates make it irreducible. Its fixed point is the Gibbs measure, which every initial law approaches, and the family's theorems are about the rate of that approach. In the 227 sources 'conserv' occurs only as 'conservative bound' and 'conservativ

## 228. Continuum phase transitions for radial pair potentials

- **Vetting:** 2 manuscript(s); Lean scope note; 2 in formalization.yaml; 0 revised.
- **Plain:** Constructs stable radial pair potentials in 3D with continuous or divergent cores, whose canonical free energy has a strict first-order phase transition (downward derivative jump at finite inverse temperature) throughout an open density interval. Realizes the continuum phase-transition problem raised by Simon.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L451` -- 4.3 Axis 2 — shell-index hand: `log_phi` rapidity, density `phi^{-k}`
     why: Mentions phase in context of shell-index (log_phi rapidity), not thermodynamic phase. Owner's 'phase' is a coordinate in odometer; OpenAI's 'phase transition' is a discontinuity in thermodynamic free energy. Different meanings of 'phase' prevent transfer.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L481` -- 4.6 Non-commensurability — the joint odometer has no shared modulus
     why: Non-commensurability of joint odometer. Pair-potential free energy is a function of (temperature, density) space; owner's framework has no thermodynamic potential or coupling-dependent transitions.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L464` -- §21  The 9 hard constraints
     why: Hard constraints section. Mentions free energy in passing (no-hash, no-float constraint context). Owner never develops thermodynamic free energy as a central object.

## 229. Exact three- and four-state reconstruction thresholds and four-state tree capacity

- **Vetting:** 3 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Exact thresholds for information recovery from ferromagnetic Potts broadcasting on trees: reconstruction occurs when signal-to-noise d·λ² exceeds 1.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Transfer matrix as deterministic tight-binding Hamiltonian with eigenvalue phi; reconstruction means state recovery, not probabilistic inference.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L692` -- 6.1 Closure of the two-register basis
     why: Theorem T4 reconstructs state variables from registers via recurrence; 'reconstruction' ≠ Kesten-Stigum threshold on trees.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L67` -- S5. Perron-Frobenius vector = steady-state bit-density operator
     why: Perron-Frobenius (phi,1) governs activity scaling phi^{-k}; applies to steady states, not dynamic recovery thresholds.

## 230. Exact Hausdorff gauges for SLE

- **Vetting:** 2 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Exact Hausdorff-measure formula for Schramm-Loewner evolution (random conformal curves) at all parameter values 0 < κ < 8, resolving a classical open problem.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/helmet/nodes/s01-04-12-24-27.md#L1` -- owner 10-02: carry split should mimic original logic; 128 qubits PLENTY at 1 or 0 per gate
     why: Lexical match only; no connection to conformal geometry, Hausdorff dimension, or random scaling limits.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L457` -- XIV. Meaning is revealed without privilege (L14, Prop 6)
     why: Lexical match only; no shared objects with SLE or fractal geometry.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L220` -- 9. Generation is recall, inverse, or gap-vote — never argmax over counts
     why: Generation mechanism differs fundamentally from Hausdorff gauge construction.

## 231. The free uniform spanning forest is a factor of IID

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Free uniform spanning forest is a computable function (factor) of iid random vertex labels on all infinite graphs; extends to translation-invariant strongly Rayleigh processes.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L689` -- HAZARDS
     why: Lexical match on 'tree', 'lattice'; shell lattice is geometric, not a random graph ensemble or determinantal process.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L129` -- 4. Engineering concepts (perused, one line + provenance)
     why: Lexical match on 'graph'; no shared structure between spanning forests and Fibonacci recurrence.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L773` -- 6.4 Harmonized two-register build prescription
     why: Shell lattice is deterministic recurrence-driven, not probabilistic factor-of-IID.

## 232. Gaussian fields and interfaces for triangular-lattice Lipschitz heights

- **Vetting:** 3 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Triangular-lattice height models converge to Gaussian free field in bounded domains; at critical parameters, interface converges to SLE₄ curve.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XV_FED_MEMORY_GRC.md#L259` -- Proposition VII — The capture is faithful; the source is not byte-stable.
     why: Lexical match on 'field'; here field means ROM address space, not Gaussian field.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L417` -- XIII. Ancestry survives transformation (L13, Prop 8, P5 with P3)
     why: Lexical match on 'limit'; CASLO has no scaling limits or continuum representations.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/MULTI_ZECKENDORF_SCALING.md#L93` -- PART IV — The RECURSIVE COMPOSITE: fold a window into one address, two orders up
     why: Lexical match on 'scaling'; here means Zeckendorf address composition, not continuum scaling.

## 233. The joint critical Ashkin–Teller current limit

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Ashkin-Teller model at critical point: height field and current-cluster ensembles jointly scale to Gaussian free field and its recursive decomposition.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L489` -- 4.7 The deepest cycle — `I-1` conservation as the period-1 hand
     why: Lexical match on 'joint', 'current'; conservation law concerns charge density, not critical-point scaling.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/UPGRADE/caslo_monolith/harness/docs/ELEMENTS_BOOK_XVI_HETEROGENEITY.md#L34` -- Propositions
     why: Lexical matches do not establish connection to Ashkin-Teller phase transitions.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XV_FED_MEMORY_GRC.md#L293` -- HOW THE TWO MEMORIES JOIN
     why: Memory join mechanism unrelated to critical Ashkin-Teller scaling limits.

## 234. All-temperature pressure of orthogonally invariant Ising spin glasses

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Ising spin glass with Haar-random orthogonal matrix: exact pressure formula at all temperatures from variational principle; ground-state energy from zero-temperature limit.
- **CASLO frame:** Both use transfer matrix spectral theory and Perron-Frobenius eigenvalues to extract thermodynamic/information-theoretic properties from dominant eigenvalue. CASLO applies this to deterministic [[1,1],[1,0]] with λ_max=phi, family 234 to random Haar matrices with compact spectral laws.
- **Verdict:** ANALOGY
  1. level 2 (draft 2, CONFIRM) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L144` -- 6. The twist — why this is a *Möbius* ribbon, not a cylinder
     why: Q=[[1,1],[1,0]] with eigenvalues phi, psi=-1/phi; family 234 also derives system properties from eigenvalue spectra and limiting distributions.
     ruling: Both texts define the same kind of object: a thermodynamic-limit free-entropy density, lim (1/N) log of a sum over configurations, tied to the spectral data of a matrix. The owner's is s=lim(1/n) ln Omega(n) for a constrained (hard-core, Ising-type) configuration count, i.e. the pressure at zero pot
  2. level 2 (draft 2, CONFIRM) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L67` -- S5. Perron-Frobenius vector = steady-state bit-density operator
     why: Perron-Frobenius (phi,1) and phi^{-k} scaling control activity distribution; family 234 uses similar spectral decomposition for thermodynamic properties.
     ruling: Both texts define the same kind of object: a thermodynamic-limit free-entropy density, lim (1/N) log of a sum over configurations, tied to the spectral data of a matrix. The owner's is s=lim(1/n) ln Omega(n) for a constrained (hard-core, Ising-type) configuration count, i.e. the pressure at zero pot
  3. level 2 (draft 2, CONFIRM) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: s = ln(lambda_max(A)) for any transfer matrix; both extract system properties (entropy rate vs pressure) from dominant eigenvalue.
     ruling: Both texts define the same kind of object: a thermodynamic-limit free-entropy density, lim (1/N) log of a sum over configurations, tied to the spectral data of a matrix. The owner's is s=lim(1/n) ln Omega(n) for a constrained (hard-core, Ising-type) configuration count, i.e. the pressure at zero pot

## 235. Limiting random SAT thresholds, sharp variance and computability

- **Vetting:** 4 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** For every fixed k≥3, random k-SAT with independent clauses has a finite positive limiting satisfiability threshold; hitting-time variance is Θ_k(n).
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L489` -- 4.7 The deepest cycle — `I-1` conservation as the period-1 hand
     why: Both mention 'finite' and 'conserved' quantities but SAT thresholds are Boolean formula satisfiability, not Zeckendorf recurrence conservation.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/02_identities/cassini.md#L1` -- Cassini identity
     why: Cassini identity concerns determinant and Fibonacci parity, not SAT clause satisfaction.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L467` -- 4.5 Axis 4 — phase-register hand: latched `R`, period `~F(W+2)`, Markov boundary (Lemma L1
     why: CASLO's finite lattice periods F(W+2) versus SAT's Boolean thresholds—distinct mathematical domains.

## 236. The exact factor-of-IID threshold for free Ising spins on trees

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Free zero-field ferromagnetic Ising state on infinite d-regular trees is factor-of-IID exactly when tanh(β)≤(d-1)^{−1/2}, resolving Lyons's conjecture.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L467` -- 4.5 Axis 4 — phase-register hand: latched `R`, period `~F(W+2)`, Markov boundary (Lemma L1
     why: CASLO uses shell-lattice structure; Ising uses regular trees. Shared vocabulary 'tree' and 'lattice' but mathematical objects differ fundamentally.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L137` -- A2. A^∞ has no fixed point — only the spectral gap matters
     why: Both mention spectral gap (Ising factor-of-IID involves spectral gap; CASLO: 'A^∞ has no fixed point—only spectral gap matters'). Different applications.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/WIKI.md#L195` -- 4.3 Cascade Resolution Rules
     why: CASLO cascade is deterministic algebraic recurrence; Ising is statistical mechanics—no shared mathematical objects.

## 237. The three-quarter exponent for honeycomb self-avoiding walk

- **Vetting:** 13 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Honeycomb self-avoiding walks of length n have diameter n^{3/4+o(1)}, with local mass and covering exponent 4/3, proving Nienhuis's critical exponent.
- **CASLO frame:** Self-avoiding walks use lattice recurrences and scaling exponents; CASLO shell-lattice uses Fibonacci/Lucas recurrence with phi scaling. Both lattice-structured but SAW exponents 3/4, 4/3 are domain-specific to honeycomb criticality.
- **Verdict:** ANALOGY
  1. level 2 (draft 2, CONFIRM) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L171` -- Addendum: Tensor-Hop Network Reading
     why: Both use lattice structure with transfer-operator scaling (phi in CASLO, critical exponent in SAW). Shared analogical structure of lattice eigenvalue dynamics.
     ruling: Level 2 holds, although the claim's own reasons are loose. The owner text at TRANSFER_MATRIX_AS_LUT_FABRIC.md L171 casts A as a lattice transfer matrix: sites, translation invariance, open boundary conditions, eigenvalues phi and psi, a spectral gap, a correlation length, and a Perron-Frobenius occu
  2. level 1 (draft 2, DOWNGRADE) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L435` -- 4.1 Axis 0 — master hand: `A^n` and the global period
     why: CASLO's shell-index has Fibonacci scaling phi^n; SAW exponents scale as n^{3/4}. Both scale lattice geometry differently, same framework class.
     ruling: The claimed link compares the owner's exponential shell scaling phi^n with the family's power-law diameter n^{3/4}. Those are different objects, and the claim itself says they 'scale lattice geometry differently'. The cited section (EMBEDDING_CLOCK_AND_CHANNELS.md 4.1-4.6) is about clock periods: or
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/01_recurrences/state_register_advance.md#L1` -- State register advance
     why: Recurrence relations central to both (Fibonacci in CASLO, honeycomb recursion in SAW), but specific recurrences are domain-dependent.

## 238. Optimal logarithmic mixing of the Thorp shuffle

- **Vetting:** 12 manuscript(s); Lean scope note; 3 in formalization.yaml; 0 revised.
- **Plain:** Thorp shuffle on N=2^d cards achieves full-permutation mixing in Θ(log N)=Θ(d) physical shuffles, optimal order, via spectral and coordinate sweep analysis.
- **CASLO frame:** Thorp shuffle applies repeated coordinate permutations to mix in log time via spectral gap; CASLO applies transfer matrix A repeatedly to permute F(W+2)-quotient states, mixing controlled by spectral gap ln(phi). Both permutation operators with spectral mixing control.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L137` -- A2. A^∞ has no fixed point — only the spectral gap matters
     why: CASLO: 'A^∞ has no fixed point—only spectral gap matters' controls quotient-state mixing. Thorp also controlled by spectral gap of coordinate permutation. Shared object: spectral-gap-driven mixing.
     ruling: The two texts use 'mixing' and 'spectral gap' in different senses. Owner section A2 defines its 'mixing property' as deterministic recurrence of A on the finite F(W+2)-state quotient and says 'There is no equilibrium. The engine does not converge.' On that finite set A is a permutation, so all its e
  2. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L489` -- 4.7 The deepest cycle — `I-1` conservation as the period-1 hand
     why: CASLO's 'mixing property' via canonicalization replaces equilibration; both shuffle and CASLO use repeated linear permutations with spectral control.
     ruling: The cited lines are Theorem 4.7 (the sum F(k)*R[k] is conserved under R1 and R3, a period-1 fixed point), the section-4 odometer summary, and Theorem T3 on channel compression. They contain no randomness, no mixing and no spectral control. The phrase 'mixing property via canonicalization' quoted in 
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: Both entropy rate (ln(phi) in CASLO) and log-mixing in Thorp involve spectral eigenvalues, but frameworks differ (algebraic vs probabilistic).

## 239. Sharp singularity rates for symmetric random sign matrices

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Symmetric random n×n sign matrices have singularity probability Pr(det A_n=0)=(1/2+o(1))^n for uniform signs, with rate determined by row-agreement events.
- **CASLO frame:** Both analyze matrix determinants and spectral properties. CASLO's transfer matrix A=[[1,1],[1,0]] has det(A)=-1 (Cassini identity); family studies singularity rates of random matrices. Matrix determinants shared object but contexts differ (fixed deterministic vs random ensemble).
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L47` -- S3. Cassini's identity is a free orientation bit
     why: Both study matrix determinants: CASLO derives det(A^n)=(-1)^n; family analyzes singularity via determinants of random matrices. Shared object: determinant analysis of matrix powers.
     ruling: In family 239, A_n is a random n x n symmetric matrix of +1/-1 entries; n is the dimension, not a matrix power. The theorem is that the probability det A_n = 0 is (1/2+o(1))^n, proved with Littlewood-Offord anti-concentration, and the rate comes from two rows agreeing. Owner section S3 is the exact 
  2. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/02_identities/cassini_lucas.md#L1` -- Cassini-Lucas / det Q^n equivalence
     why: Cassini identity encodes det(A^n)=(-1)^n as F(n-1)·F(n+1)-F(n)²=(-1)^n; family analyzes determinant behavior. Both focus on determinant periodicity.
     ruling: The family has no 'determinant periodicity'. Its result is the exponential decay rate of the singularity probability for random symmetric sign matrices of growing size. The owner identity L(n)^2 - 5F(n)^2 = 4(-1)^n = 4*det(Q^n) is a deterministic statement about powers of one fixed 2x2 matrix with d
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: CASLO treats determinant as foundational parity invariant; family shows determinant rate controls singularity. Both regard determinant as essential but apply differently.
