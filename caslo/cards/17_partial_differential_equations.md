# Partial differential equations -- OpenAI result families in CASLO framing

Levels: 0 none, 1 words, 2 analogy, 3 shared object, 4 direct use. Final levels >= 2 were confirmed by an adversarial verifier; unverified claims are capped at 1.

## 362. Global smoothness for relativistic Vlasov–Maxwell

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised; reasoning summary reasoning_traces/relativistic-vlasov-maxwell.pdf.
- **Plain:** Proves global existence and uniqueness of smooth solutions to the relativistic Vlasov-Maxwell system for particles with compactly supported density and electromagnetic fields with finite energy.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/MASTER_CONTROL.md#L9` -- 
     why: Words 'uniqueness', 'model', 'system', 'data' match but reference Zeckendorf decomposition axioms, not PDE existence theory
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/UPGRADE/caslo_monolith/harness/docs/ELEMENTS_BOOK_XVI_HETEROGENEITY.md#L34` -- Propositions
     why: Words 'regularity', 'bounded', 'uniqueness' match but describe CASLO register composition rules (CARRY/SPLIT), not relativistic kinetic equations
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Words 'conservation', 'uniqueness', 'bounded' match but concern Zeckendorf conservation current (sum F(k)R[k]), not mass/energy in PDEs

## 363. Nonuniqueness with local conservation for the hard-sphere Boltzmann equation

- **Vetting:** 2 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Constructs two distinct global entropy solutions of the hard-sphere Boltzmann equation from the same initial density, satisfying exact local conservation of mass, momentum, and kinetic energy.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Words 'satisfy', 'both', 'three-dimensional', 'equation' match but describe cascade composition axioms, not kinetic theory
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Words 'nonuniqueness', 'conservation', 'mass', 'both' match but concern Zeckendorf uniqueness and register invariants, not entropy solutions
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L492` -- THEOREMS T1..T5 AND THE ROOT T0
     why: Words 'finite', 'L1', 'among', 'gain' match but discuss CASLO theorems and signal routing, not Boltzmann collision operators

## 364. Kinetic limits and fluctuations over the Boltzmann lifespan

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Derives the nonlinear Boltzmann equation from grand-canonical Newtonian gases with stable radial potentials; proves finite-dimensional central limit theorem for hard-sphere fluctuations governed by the linear fluctuating Boltzmann equation.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Words 'restrictions', 'linear', 'bounds', 'probability' match but are about quantum error codes, not kinetic limits
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XV_FED_MEMORY_GRC.md#L293` -- HOW THE TWO MEMORIES JOIN
     why: Words 'three-dimensional', 'its', 'with' match but describe memory architecture, not Boltzmann-Grad limits
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/UPGRADE/caslo_monolith/harness/docs/ELEMENTS_BOOK_XVI_HETEROGENEITY.md#L34` -- Propositions
     why: Words 'regular', 'bounds', 'on every' match but concern Zeckendorf canonicality, not gauge theory or fluctuation theorems

## 365. Joint metric and connection recovery from one boundary patch

- **Vetting:** 3 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves that zero-frequency boundary measurements on an open patch determine a smooth Riemannian metric and unitary connection on a rank-two Hermitian bundle over a manifold of dimension at least three, up to diffeomorphism and gauge.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/UPGRADE/caslo_monolith/harness/docs/ELEMENTS_BOOK_XVI_HETEROGENEITY.md#L34` -- Propositions
     why: Words 'regularity', 'rank', 'open', 'uniqueness' match but describe register composition, not inverse problems or Riemannian geometry
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Words 'measurements', 'determined', 'data' match but are quantum code terminology, not Calderon inverse problem
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L20` -- NOMENCLATURE
     why: Words 'unit', 'equal', 'data' match but concern CASLO signal taxonomy, not unitary connections or Riemannian metrics

## 366. The planar Mumford–Shah regularity conjecture and local weak-L4 gradient bounds

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Resolves the interior regularity of planar Mumford-Shah minimizers: the discontinuity set is a C^1,alpha arc, a regular crack tip, or three arcs meeting at 120 degrees; only finitely many components meet any compact region.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/UPGRADE/caslo_monolith/harness/docs/ELEMENTS_BOOK_XVI_HETEROGENEITY.md#L34` -- Propositions
     why: Words 'regularity', 'regular', 'open' match but describe Zeckendorf canonicality, not minimal surface singularities
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L21` -- 2. Bicycle Instructions (Sec 2.2.2, 2.3; pp. 16-19, App. A, B)
     why: Words '120', 'three', 'alpha' match but from unrelated quantum code appendix, not PDE regularity theory
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L636` -- 5.4 R(t-1) triple-duty
     why: Words 'interior', 'prove', 'point', 'three' match but describe register logic, not monotonicity or free boundary regularity

## 367. The critical dimension for the one-phase Bernoulli problem

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves seven is the critical dimension for the one-phase Bernoulli problem: all nonzero one-homogeneous global minimizers in dimensions at most six are flat; nonflat minimizers exist in dimension seven with singular sets of dimension at most n-7.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L689` -- HAZARDS
     why: Words 'finite', 'one', 'lean' match but concern CASLO signal hazards and Lean formalization status, not free boundary regularity
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Words 'problem', 'flat', 'free', 'while' match but generic cross-cutting notes, not dimension-critical PDE theory
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L636` -- 5.4 R(t-1) triple-duty
     why: Words 'interior', 'prove', 'finite', 'exists' match but describe register update cycles, not free boundary existence or dimensionality

## 368. The three-dimensional Ball–Evans approximation problem

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Every W^{1,p} homeomorphism between arbitrary bounded 3D domains is approximable as a strong W^{1,p} limit of smooth diffeomorphisms onto the same target.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE

## 369. The hot spots conjecture for simply connected planar domains

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Neumann eigenfunctions of the first positive eigenvalue on simply connected planar domains have no interior critical points; all extrema lie on the boundary.
- **CASLO frame:** Both domains use eigenvalue/eigenvector analysis; owner's discrete transfer matrix A has Perron-Frobenius dominant eigenvector φ^{-k} determining shell-density profile. Same structural role: leading eigenvalue governs asymptotic behavior.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L451` -- 4.3 Axis 2 — shell-index hand: `log_phi` rapidity, density `phi^{-k}`
     why: Theorem 4.3 states shell index is log_phi rapidity with Perron-Frobenius density phi^{-k}, the dominant eigenvector of transfer matrix A. This is exactly the eigenvalue/eigenvector machinery that Family 369 applies to Neumann operator.
     ruling: Family 369 proves that every eigenfunction for the first POSITIVE Neumann eigenvalue of the Laplacian on a smooth simply connected planar domain has nonvanishing interior gradient. That eigenfunction is mean-zero and sign-changing: it is the mode after the constant ground state, not a Perron/dominan
  2. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L153` -- Implications for v013
     why: Discusses transfer matrix eigenvalues (phi, psi) and their role in determining spectral gap and correlations. Eigenvalue structure is shared with Family 369's Neumann eigenvalue analysis, though applied to different operators.
     ruling: The shared terms name different objects. In the 369 manuscript, 'spectral gap' means Lemma lem:gap, mu < lambda_D: the first positive Neumann eigenvalue lies strictly below the first Dirichlet eigenvalue (Friedlander-Filonov, proved with plane-wave test functions). The theorem itself is about critic
  3. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L67` -- S5. Perron-Frobenius vector = steady-state bit-density operator
     why: Section S5 on Perron-Frobenius vector as steady-state bit-density operator. Same use of dominant eigenvector for asymptotic behavior as Family 369 applies to Neumann eigenfunctions.
     ruling: The claimed parallel ('dominant eigenvector for asymptotic behavior, same as 369 applies to Neumann eigenfunctions') does not hold for 369. Its eigenfunctions belong to the first positive Neumann eigenvalue, so they are orthogonal to the constant (the Neumann ground state, eigenvalue 0) and change s

## 370. The Lane–Emden and Hénon–Lane–Emden conjectures

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Nonlinear elliptic system with power-law weighted Laplacians has no positive entire solutions when a critical dimensional-power condition is exceeded.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Lexical match on 'existence' and 'system', but semantics differ: owner discusses cascade rule existence axioms on discrete lattice; family discusses PDE system existence criteria. Word-only.

## 371. Stable blowup for the defocusing Schrödinger equation

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Finite-time blow-up for defocusing nonlinear Schrödinger on torus is stable under Sobolev perturbations when nonlinearity power is sufficiently large.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L209` -- What it does NOT buy us
     why: Match on 'finite' and 'up', but context is unrelated: owner discusses what the tensor-network model does NOT buy (no continuum limit, no quantum speedup); family discusses Sobolev stability. Word-only.

## 372. Global uniqueness in smooth isotropic elasticity

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Full static boundary displacement-to-traction data uniquely determine both Lamé elastic moduli on bounded 3D domains under positivity constraints.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L481` -- 4.6 Non-commensurability — the joint odometer has no shared modulus
     why: Lexical match on 'moduli', but semantics are unrelated: owner discusses modular arithmetic constraints and non-commensurate periods in odometer; family discusses Lamé elastic coefficients. Word-only.

## 373. Nonattainment of the three-marginal Coulomb Monge problem

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Three-particle Coulomb optimal-transport infimum need not be attained as a deterministic map, even when Monge and Kantorovich infima coincide.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/MULTI_ZECKENDORF_SCALING.md#L18` -- PART I — The three structures that fall out of tokenize-then-Zeckendorf
     why: Match on 'three', but refers to entirely different structures: owner's 'three structures' are set-count, gap-signature, and composite in Zeckendorf encoding; family's 'three-marginal' refers to three-particle configurations in Monge problem. Word-only.

## 374. Sharp one-third stability of Brenier maps

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves that quadratic optimal transport maps from uniform measures are one-third Hölder continuous in L² with respect to 2-Wasserstein distance. The exponent is sharp; a three-atom counterexample disproves the conjectured square-root bound.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: Both mention Perron-Frobenius theory, but entropy-rate applies it to physics of distributed systems; family 374 applies spectral theory to optimal transport stability—vocabulary overlap only, no shared mathematical objects.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L67` -- S5. Perron-Frobenius vector = steady-state bit-density operator
     why: Describes Perron-Frobenius vector and eigenvalue phi for Fibonacci transfer matrix A=[[1,1],[1,0]]; family 374 does not invoke this matrix or phi eigenvalue explicitly. Shared technical vocabulary (eigenvalue, transfer, stability) but distinct mathematical objects.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L451` -- 4.3 Axis 2 — shell-index hand: `log_phi` rapidity, density `phi^{-k}`
     why: References log-phi rapidity and bit-density scaling; family 374 analyzes stability of maps, not bit-density or logarithmic scaling. Shared phi terminology but distinct contexts.

## 375. De Giorgi's conjecture in dimension eight

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Resolves De Giorgi's conjecture in dimension eight: every entire C² solution u:ℝ⁸→(-1,1) of Δu=u³-u that is increasing in one direction depends on only one coordinate. Also classifies all stable solutions in ℝ⁷ as constant wells or planar heteroclinics.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Pre-ranked match is lexical only (words: 'solution', 'equation', 'growth'); no PDE theory, dimension analysis, or heteroclinic structure in CASLO framework.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L20` -- NOMENCLATURE
     why: Nomenclature section shares vocabulary ('coordinate', 'theorem') but CASLO's lattice structures and rail routing do not overlap with PDE existence/regularity theory.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/UPGRADE/caslo_monolith/harness/docs/ELEMENTS_BOOK_XVI_HETEROGENEITY.md#L34` -- Propositions
     why: Propositions section is lexically ranked but addresses heterogeneity in token coupling and register state, not planar heteroclinic solutions to semilinear elliptic equations.

## 376. Universal computation in forced Navier–Stokes flows

- **Vetting:** 9 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Constructs viscous incompressible flows on a flat 3-torus that perform universal computation under smooth forcing. A compiler turns any Turing machine and input into a finite force program such that a fixed particle reaches a target region exactly when the machine halts.
- **CASLO frame:** Both CASLO and family 376 are deterministic computational systems—CASLO routes tokens via cascade rules on Zeckendorf shells, while family 376 encodes Turing machines in fluid dynamics. No shared mathematical objects or transfer theorems.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/LUT_FABRIC_LM_ALGORITHM.md#L320` -- §6.3  Why "deterministic"
     why: Explains why CASLO is deterministic: 'each token CANCELS all possibilities except one'; family 376 also encodes deterministic computation, but in Navier-Stokes rather than cascade recurrence. Shared concept (determinism), distinct substrates.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L9` -- §0  Compaction-Survival Protocol — read this first
     why: Describes CASLO as a state machine with deterministic transitions; family 376 also simulates state machines (Turing machine transitions via fluid dynamics). Same abstract computational pattern, completely different physics.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/WIKI.md#L14` -- 1. System Identity
     why: WIKI system identity: deterministic computation via algebraic state translocations; family 376 achieves deterministic computation via forced viscous flow. Both deterministic and computational but no shared theorems or technical machinery.

## 377. Interior $C^{1,\alpha}$ regularity for infinity-harmonic functions

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves uniform interior C^{1,α_d} regularity for bounded infinity-harmonic functions in every dimension d≥3. The gradient's supremum norm and α_d-Hölder seminorm on the half unit ball are bounded by a dimension-dependent constant times the oscillation on the unit ball.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/UPGRADE/caslo_monolith/harness/docs/ELEMENTS_BOOK_XVI_HETEROGENEITY.md#L34` -- Propositions
     why: Pre-ranked on generic words (regularity, bounds, dimension); addresses heterogeneous token coupling in CASLO's five-channel fabric, not regularity of solutions to the infinity Laplacian equation.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: 'What this buys us conceptually' discusses dimension-dependent bit-density scaling and spectral properties; family 377 proves dimension-dependent Hölder exponents for PDE solutions. Same adjective (dimension-dependent), different objects.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L89` -- 4. The graded fold — packing the whole past into one register
     why: Lexical match on 'dimension d' and 'explicit' bounds; addresses bit-ribbon packing and state representation in CASLO, not Hölder continuity or infinity-harmonic functions.
