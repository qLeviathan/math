# Dynamical systems and ergodic theory -- OpenAI result families in CASLO framing

Levels: 0 none, 1 words, 2 analogy, 3 shared object, 4 direct use. Final levels >= 2 were confirmed by an adversarial verifier; unverified claims are capped at 1.

## 143. Hilbert's sixteenth problem: uniform bounds for limit cycles

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Hilbert's sixteenth problem: proved that planar polynomial vector fields have finitely many periodic orbits bounded by degree. Resolves boundedness for quintic Liénard systems with exactly two limit cycles.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L467` -- 4.5 Axis 4 — phase-register hand: latched `R`, period `~F(W+2)`, Markov boundary (Lemma L1
     why: Shares vocabulary (periodic, field, degree) but CASLO periodic orbits are permutation cycles on finite Fibonacci lattices (cardinality F(W+2)), not polynomial vector field limit cycles on R^2. The mathematical objects are fundamentally different.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L424` -- 4. The Multi-Dimensional No-Modulo Embedding Clock
     why: Discusses dynamical systems and invariants but in the context of LUT4 fabric operations and fibbinary constraints, not polynomial dynamics.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L178` -- 1.2 Canonicality forces the Lucas bridge to read single-valuedly (Lemma L5)
     why: Discusses algebraic constraints and recurrence but on Zeckendorf/Fibonacci structures, not polynomial fields.

## 144. Banach’s simple Lebesgue-spectrum problem

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Banach's simple Lebesgue-spectrum problem: constructed a smooth diffeomorphism of the 3-torus whose Koopman operator has simple Lebesgue spectrum on the mean-zero L² space, solving the problem for smooth probability-preserving dynamics.
- **CASLO frame:** CASLO has transfer matrix A with eigenvalues φ/ψ and spectral gap analysis; both frameworks apply spectral theory to constrained dynamical systems, but Koopman operator on tori vs discrete lattice quotient dynamics.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L171` -- Addendum: Tensor-Hop Network Reading
     why: Both use transfer matrices and eigenvalue/eigenvector spectral theory. CASLO: A has eigenvalues φ, ψ with |φ| > 1 > |ψ|; spectral gap φ − |ψ| = √5; Perron-Frobenius eigenvector φ^{-k}. Family 144 uses Koopman operator spectrum. Same mathematical structure (spectrum, eigenvalues, Perron density), dif
     ruling: IBM_PAPER_BRIEF.md L85 summarizes an external IBM quantum-error-correction paper. 'Spacetime error mixing' there means averaging the failure probability over random qudit-to-qubit bases B and random column scalings nu, to get failure-probability bounds. The item has no spectrum, no Koopman operator,
  2. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L85` -- 5. Spacetime Error Mixing (Sec 1.1, 3.3; pp. 9-10, 39-40)
     why: CASLO discusses spectral gap and mixing-like behavior from A^∞ dynamics; Family 144 concerns Koopman spectrum. Both invoke spectral analysis of measure-preserving/probability-preserving operations.
     ruling: IBM_PAPER_BRIEF.md L85 summarizes an external IBM quantum-error-correction paper. 'Spacetime error mixing' there means averaging the failure probability over random qudit-to-qubit bases B and random column scalings nu, to get failure-probability bounds. The item has no spectrum, no Koopman operator,
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/LUT_FABRIC_LM_ALGORITHM.md#L108` -- §3.3  `cascade_resolve` — addr_precanon → addr_canonical
     why: Discusses A-matrix eigenvalues in fabric context but does not address Koopman operator or mean-zero L² analysis.

## 145. Rokhlin’s multiple-mixing problem

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Rokhlin's multiple-mixing problem: proved that every invertible mixing probability-preserving transformation is mixing of all finite orders, resolving the problem for single transformations. Correlations among finite measurable set collections converge to products of measures.
- **CASLO frame:** CASLO describes cascade rules as 'algebraic substitute for thermalization' with 'mixing property' via spectral gap; both invoke mixing, spectral gaps, and convergence of correlations in measure-preserving dynamics.
- **Verdict:** ANALOGY
  1. level 2 (draft 2, CONFIRM) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L137` -- A2. A^∞ has no fixed point — only the spectral gap matters
     why: CASLO explicitly states: 'This is the engine's mixing property — the algebraic substitute for thermalization.' A is hyperbolic with spectral gap; no fixed point, only spectral gap matters. Family 145 is about mixing probability-preserving transformations. Both invoke mixing, spectral gaps, and decay
     ruling: TRANSFER_MATRIX_AS_LUT_FABRIC.md L171 does contain the same kind of structure as mixing. It gives a stationary Perron-Frobenius occupation and says 'correlations decay under repeated A-application ... decorrelated the bit-occupations'. That is a stationary system losing correlation under iteration, 
  2. level 2 (draft 2, CONFIRM) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L171` -- Addendum: Tensor-Hop Network Reading
     why: Spectral gap controls mixing/convergence rate; both frameworks use spectral gaps to bound correlation decay, though on different probability spaces (discrete lattice quotient vs measure-preserving transformation).
     ruling: TRANSFER_MATRIX_AS_LUT_FABRIC.md L171 does contain the same kind of structure as mixing. It gives a stationary Perron-Frobenius occupation and says 'correlations decay under repeated A-application ... decorrelated the bit-occupations'. That is a stationary system losing correlation under iteration, 
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L467` -- 4.5 Axis 4 — phase-register hand: latched `R`, period `~F(W+2)`, Markov boundary (Lemma L1
     why: CASLO invokes Markovian structure and recurrence times; Family 145 invokes ergodic-theoretic mixing. Both concern long-term statistical behavior but on different spaces.

## 146. Positive metric entropy for the standard map

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Positive metric entropy for the standard map: proved the standard sine map on the 2-torus has positive metric entropy for sufficiently large parameter, confirming Sinai's conjecture with a full parameter tail.
- **CASLO frame:** CASLO has explicit entropy-rate law: s = ln(λ_max(A)) = ln(φ) for transfer matrix on Fibonacci lattice; topological entropy of golden-mean subshift is log φ. Both frameworks compute entropy from Perron-Frobenius eigenvalues.
- **Verdict:** ANALOGY
  1. level 2 (draft 2, CONFIRM) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: CASLO: 'For any constrained system with transfer/adjacency matrix A, the entropy rate equals ln of the dominant (Perron-Frobenius) eigenvalue.' Family 146 computes metric entropy of standard map. Both use Perron-Frobenius eigenvalues to compute or bound entropy, though on different systems (discrete
     ruling: CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md L242 (section 11) states the Parry measure of the golden-mean subshift, P(gap=k) = phi^-k, which is its maximal-entropy measure, and gives topological entropy log phi. That is an invariant measure with positive metric entropy on a symbolic system. Famil
  2. level 2 (draft 2, CONFIRM) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L242` -- 11. The reachable-set measure (softmax, but intrinsic)
     why: CASLO: 'The subshift (no two adjacent 1s) has topological entropy log φ' and 'Boltzmann weight at β = ln φ'. Family 146 concerns positive entropy. Both invoke log of golden ratio as the fundamental entropy scale, Perron-Frobenius eigenvector as equilibrium measure.
     ruling: CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md L242 (section 11) states the Parry measure of the golden-mean subshift, P(gap=k) = phi^-k, which is its maximal-entropy measure, and gives topological entropy log phi. That is an invariant measure with positive metric entropy on a symbolic system. Famil
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/ZECKENDORF_LOGIC.md#L90` -- PART IV — Computational memory IN ACTION
     why: Discusses Lyapunov-type dynamics (strict decrease to fixed point) but in discrete Zeckendorf context, not continuous 2-torus dynamics.

## 147. The near-boundary Birkhoff conjecture

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Birkhoff's near-boundary conjecture: proved that smooth strictly convex planar billiards with positive curvature are ellipses if a full grazing annulus is continuously foliated by invariant curves, resolving the conjecture for caustic-collared billiards.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L451` -- 4.3 Axis 2 — shell-index hand: `log_phi` rapidity, density `phi^{-k}`
     why: Shares vocabulary (foliation, Markov boundary, rigidity) but CASLO's foliations are partitions of state-space by shell index on Fibonacci lattices; Birkhoff's are geometric foliations of billiard phase space by caustics. Different geometric objects.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L144` -- 6. The twist — why this is a *Möbius* ribbon, not a cylinder
     why: CASLO discusses ribbons and annuli in the context of bit-encoding topology; Family 147 discusses annuli and leaves in billiard caustics geometry. Shared terminology, different mathematical objects.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XIII_ENERGY_ROUTING.md#L91` -- Proposition VII — An artifact has an address without a digest.
     why: File not available for verification; references exist in index but substantive comparison cannot be made with read-only access.

## 148. The entropy-rate dimension formula for self-similar measures

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Entropy-rate dimension formula for self-similar measures: proved that Hausdorff dimension of finite self-similar measures equals min(1, h_RW / χ), where h_RW is entropy rate of random walk and χ the average logarithmic contraction, resolving the entropy-rate dimension conjecture.
- **CASLO frame:** CASLO has entropy-rate law s = ln(λ_max(A)) = ln(φ) and Lyapunov descent φ^{-k} eigenvalue; both frameworks compute dimension-like quantities from entropy rates and Lyapunov exponents (logarithmic contraction rates) on self-similar or recursively-defined structures.
- **Verdict:** ANALOGY
  1. level 2 (draft 3, DOWNGRADE) `_master_workflow_/ZECKENDORF_LOGIC.md#L90` -- PART IV — Computational memory IN ACTION
     why: CASLO: 'Running backward with psi-step drops the top shell each tick — a Lyapunov descent that strictly decreases N_q to the fixed point 0'. Family 148 uses Lyapunov exponent χ as the contraction rate controlling dimension. Both invoke Lyapunov-type descent in self-similar/recursive structures; eige
     ruling: CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md L242 has the entropy of a symbolic measure (Parry measure, topological entropy log phi). Its section also gives a log-rate eta = ln phi = -ln|psi|, with the signed ratio psi = -1/phi. Family 148 relates an entropy rate to a log-contraction rate for self
  2. level 2 (draft 3, DOWNGRADE) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: CASLO: 's = lim_{n→∞} (1/n) ln Ω(n) = ln λ_max(A)'; Family 148: 'dim_H(μ) = min{1, h_RW / χ}' where h_RW is entropy rate. Both frameworks use entropy rates (ln of eigenvalues / growth rates) divided by contraction exponents to compute intrinsic dimension. The entropy-rate dimension formula structure
     ruling: CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md L242 has the entropy of a symbolic measure (Parry measure, topological entropy log phi). Its section also gives a log-rate eta = ln phi = -ln|psi|, with the signed ratio psi = -1/phi. Family 148 relates an entropy rate to a log-contraction rate for self
  3. level 2 (draft 3, DOWNGRADE) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L242` -- 11. The reachable-set measure (softmax, but intrinsic)
     why: CASLO: 'Perron-Frobenius eigenvector φ^{-k}' and 'topological entropy log φ' on golden-mean subshift (fibbinary constraint). Family 148 concerns self-similar measures with controlled contraction ratios; CASLO's fibbinary structure (no adjacent 1s) is self-similar. Both compute measures via eigenvalu
     ruling: CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md L242 has the entropy of a symbolic measure (Parry measure, topological entropy log phi). Its section also gives a log-rate eta = ln phi = -ln|psi|, with the signed ratio psi = -1/phi. Family 148 relates an entropy rate to a log-contraction rate for self

## 149. Classwise permanence for weakly reversible mass-action systems

- **Vetting:** 2 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves all positive trajectories in weakly reversible mass-action systems eventually remain bounded, with positive lower and finite upper bounds on concentrations.
- **CASLO frame:** CASLO cascade redexes (R1, R3) preserve the conserved integer Σ_k F(k)·R[k] exactly. Conservation laws guarantee bounded evolution.
- **Verdict:** ANALOGY
  1. level 2 (draft 3, DOWNGRADE) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L204` -- 1.4 Canonicality is upstream of mass-conservation and of parity
     why: L8 (L210-242): 'R1 and R3 each leave Σ_k F(k)·R[k] invariant.' Both systems use conservation laws that guarantee bounded behavior through invariant preservation.
     ruling: The analogy is real. L8 uses R1 (X_k+X_{k+1}->X_{k+2}) and R3 (2X_k->X_{k+1}+X_{k-2}) as reactions on shell counts and proves F is orthogonal to each reaction vector, so Sum F(k)M(k) is a linear (stoichiometric) conservation law. The family's class P=(x0+S)∩R^d is the level set of such laws: the man
  2. level 2 (draft 2, CONFIRM) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Axiom A4 (L79-105): 'I-1 = Σ_k F(k)·R[k] as the conserved mass.' Shared structure: both rely on conservation as fundamental constraint.
     ruling: A4 states a positive linear conserved quantity, I-1 = Sum F(k)R[k] (provenance: multiset mass Sum F(k)M(k)). Every operator and cascade redex must preserve it, which means the admissible reaction vectors lie in its kernel. That is the structure of the linear conservation laws that define the family'
  3. level 2 (draft 2, CONFIRM) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Describes conservation laws as hard constraints. Both (mass-action networks and CASLO) use conservation to guarantee stability.
     ruling: The stated rationale ('conservation guarantees stability') fails on both sides. The owner's boundedness comes from psiRetract (I6, L187-189); the family's comes from weak reversibility, and its classes may be unbounded. 'Bounded' and 'reversible' are false friends: L153/L174 mean x-phi/x-psi inverti

## 150. Weak mixing of triangular billiards with an irrational angle

- **Vetting:** 2 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Shows that billiard flows in triangles with irrational angle are weakly mixing, with no Diophantine restrictions needed.
- **CASLO frame:** CASLO uses golden ratio φ=(1+√5)/2 (irrational) as core eigenvalue in Z[φ] ring and base-φ arithmetic. Both systems center on irrationality and eigenvalues.
- **Verdict:** WORDS
  1. level 1 (draft 3, REJECT) `_master_workflow_/zlogpi/zphi.py#L97` -- ZPhi
     why: ZPhi (L97+): 'Represents a + b·φ where φ = (1+√5)/2.' Shared object: golden-mean shift as core eigenvalue. Both use φ's irrationality in their dynamics.
     ruling: Family 150 contains no phi, golden-mean shift, eigenvalue or Z[phi]. Its irrationality is an angle irrational relative to pi in a triangular billiard, and its result is weak mixing (the product flow is ergodic) for Liouville measure. Golden-ratio triangles (angles pi/5, 2pi/5) are rational relative 
  2. level 1 (draft 2, REJECT) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: Entropy = ln(λ_max); CASLO's λ_max = φ. Both use eigenvalues to characterize dynamical mixing.
     ruling: The family text has no eigenvalue, transfer matrix or entropy. Weak mixing of a triangular billiard flow is stated as ergodicity of the product flow, and polygonal billiards have zero entropy and no finite transfer matrix. The owner's law (s = ln lambda_max(A) for a constrained system) says nothing 
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/ZECKENDORF_LOGIC.md#L14` -- PART I — The Dual Address (the atom)
     why: Uses base-φ arithmetic. Family 150: irrational angles; CASLO: base-φ. Shared vocabulary: phi, irrational.

## 151. A C1 counterexample to the entropy conjecture

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Disproves entropy conjecture: constructs C1 map with zero topological entropy but eigenvalue 2 on second homology.
- **CASLO frame:** CASLO uses transfer matrices [[1,1],[1,0]] with Perron-Frobenius eigenvalue φ and entropy-rate law s=ln(λ_max). Both study entropy-eigenvalue relationships.
- **Verdict:** SHARED_OBJECT
  1. level 3 (draft 3, CONFIRM) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: Directly states 's = ln(λ_max)' and 'topological-entropy theorem.' Exact shared object: entropy equals ln(Perron-Frobenius eigenvalue).
     ruling: A specific object is shared. The owner defines s = lim (1/n) ln Omega(n) = ln lambda_max(A), which is the topological entropy of a constrained system, and cites the topological-entropy theorem. The family's subject is exactly topological entropy against the log of a spectral radius: Shub's h_top(f) 
  2. level 2 (draft 3, DOWNGRADE) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L171` -- Addendum: Tensor-Hop Network Reading
     why: Discusses transfer matrices, eigenvalues, dynamics. Family 151: constructs maps with specific eigenvalues. Shared: transfer matrix eigenvalues determine behavior.
     ruling: The claimed shared object ('transfer-matrix eigenvalues determine behavior') is absent from the family. The family has no transfer matrix; its eigenvalue 2 is on H_2(M;R), and the theorem shows such an eigenvalue need NOT determine entropy. The window (L171-231) does carry an analogous structure: th
  3. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L451` -- 4.3 Axis 2 — shell-index hand: `log_phi` rapidity, density `phi^{-k}`
     why: Uses φ and log(φ) to parametrize dynamics. Both use φ as fundamental eigenvalue.
     ruling: The rationale is false: family 151 never uses phi; its eigenvalue is 2 on second real homology. The window (Thm 4.3-4.7, L451-511) has no notion of entropy or orbit complexity, which is the family's defining object. There, log_phi is a rapidity coordinate, phi^{-k} is a Perron density profile, and L

## 152. Zero entropy does not guarantee a smooth positive-volume model

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Constructs zero-entropy invertible ergodic transformation not conjugate to any smooth diffeomorphism on any manifold.
- **CASLO frame:** CASLO is invertible (forward via φ-step, backward via ψ-step) deterministic system preserving integer mass. Both fully invertible with Lyapunov descent.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/ZECKENDORF_LOGIC.md#L90` -- PART IV — Computational memory IN ACTION
     why: Describes invertible register: 'backward with ψ-step drops top shell—Lyapunov descent.' Shared: both fully invertible with backward dynamics.
     ruling: 'Invertible' is a false friend. The family's object is an ergodic invertible measure-preserving transformation of a nonatomic probability space with zero KS entropy and no smooth positive-volume model up to measurable conjugacy. In ZECKENDORF_LOGIC L90-150, 'invertible' means the absorb/cascade trac
  2. level 1 (draft 2, REJECT) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Discusses conservation and invertibility. Both construct invertible ergodic systems. Shared: conservation constrains invertible transformation structure.
     ruling: METHODOLOGY L145-205 constructs no ergodic system. In I4 (L174-179), 'reversible/invertible' means the generator can be run backward as a lossless codec, and the 'reversible mixer' is a combiner, not mixing in the ergodic sense. The window has no probability measure, Kolmogorov-Sinai entropy, measur
  3. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L467` -- 4.5 Axis 4 — phase-register hand: latched `R`, period `~F(W+2)`, Markov boundary (Lemma L1
     why: Register evolution and dynamics. Both characterize transformations via register structure and invariants.
     ruling: In L14 and Thms 4.5-4.7 (L467-527), A permutes a finite, atomic set of F(W+2) canonical words, alongside a Markov boundary latch, a no-modulo 'odometer' and conservation of I-1. That 'odometer' is a finite counter whose hands advance independently, not the ergodic adding machine, and the family text

## 153. Arithmetic classification and non-Pisot singularity for Bernoulli convolutions

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Gives arithmetic criterion (one-sided approximation by algebraic units) for singular vs. continuous Bernoulli convolutions.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/MULTI_ZECKENDORF_SCALING.md#L68` -- PART III — GAP CHANNELS: each gap is a LUT, read with no comparator
     why: Gap algebra and routing. Family: algebraic classification of measures. Shared vocabulary: 'algebraic' in different contexts.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L420` -- §19  Provenance triple — (value, verify, mirror)
     why: Algebraic provenance. Shared vocabulary: 'algebraic' but different objects.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: Uses φ/ψ pair. Family: Salem/Pisot algebraic integers. No direct shared object.

## 154. Pointwise multiple ergodic averages for mixing transformations

- **Vetting:** 4 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves pointwise convergence of n-fold ergodic averages for mixing measure-preserving transformations without rate assumptions.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/LUT_FABRIC_LM_ALGORITHM.md#L223` -- §4  The five-channel priority FSM — how §3.3 chooses its rewrite path
     why: Geometric decay convergence schedule. Both discuss convergence but in different contexts.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L85` -- 5. Spacetime Error Mixing (Sec 1.1, 3.3; pp. 9-10, 39-40)
     why: Mentions 'mixing.' Family: mixing transformations. Shared vocabulary only.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/AI_MODEL_LOGIC.md#L78` -- 5. Cascade Resolution Logic
     why: Cascade termination/convergence. Different mathematical contexts.
