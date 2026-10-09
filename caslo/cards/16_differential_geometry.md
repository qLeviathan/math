# Differential geometry -- OpenAI result families in CASLO framing

Levels: 0 none, 1 words, 2 analogy, 3 shared object, 4 direct use. Final levels >= 2 were confirmed by an adversarial verifier; unverified claims are capped at 1.

## 333. Smooth isometric immersions of surfaces into ℝ4

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Every smooth closed Riemannian surface, including non-orientable ones, can be smoothly embedded with isometry preserved in four-dimensional Euclidean space. This resolves whether all 2D metrics admit such 4D immersions.
- **CASLO frame:** Möbius ribbon structure: orientation bit flips by sign(-1)^n via transfer matrix determinant (Cassini); the owner realizes non-orientable topology through eigenvalue sign alternation in [[1,1],[1,0]] and L/F channel swap.
- **Verdict:** WORDS
  1. level 1 (draft 3, REJECT) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L144` -- 6. The twist — why this is a *Möbius* ribbon, not a cylinder
     why: Shares the Möbius ribbon object and non-orientability: family 333 includes non-orientable surfaces as valid immersion domains; owner derives orientation reversal from det(Q^n)=(-1)^n with ψ^n sign-flip, making the ribbon structure non-orientable. Both invoke Möbius as central topological object.
     ruling: The claimed shared object is missing from family 333. Its full TeX source (math/preprints/Smooth-isometric-immersions-.../build/*.tex, 11 files) has 0 hits for Mobius, double cover, determinant-sign holonomy, Cassini, Binet or cosh/sinh. The theorem covers only CLOSED surfaces ('compact smooth two-d
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L283` -- 14. Statement of the whole object
     why: Reiterates the Möbius structure and orientation doubling; vocabulary overlap on orientability and surface, but applied to bit-ribbon encoding rather than geometric immersion.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Transfer matrix eigenvalues φ/ψ underpin both the owner's spectral architecture and the geometric structure family 333 analyzes, but owner applies them to hardware LUT routing, not immersion.

## 334. A smooth surface metric with no local isometric immersion in ℝ3

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** A smooth metric on a 2D disk agrees with the flat metric to all orders at the origin, yet no neighborhood of the origin can be isometrically embedded in 3D Euclidean space. This answers a classical question negatively.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Uses word 'embedding' and 'constraint' but in context of hardware clock phase constraints, not differential geometric immersion restrictions.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L5` -- Scope
     why: Mentions 'embedding' and 'structure' but applies to register state encoding in CASLO hardware, not metric geometry.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Discusses structure and constraints but on transfer matrices and LUT fabric, not smooth Riemannian metrics or isometric immersion obstructions.

## 335. Gromov’s integral scalar-curvature bound for simplicial volume

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Gromov's conjecture proves: the integral of (negative scalar curvature)^(n/2) over an n-dimensional closed manifold bounds below by a constant times the manifold's simplicial volume. Also proves positive scalar curvature forces a manifold to be rationally inessential.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L5` -- 1. Core Construction (Sec 1, 1.1, 2.1; pp. 3-6, 13)
     why: Vocabulary: 'dimension', 'bound'. Owner applies these to Zeckendorf cardinality F(W+2) and register width; family applies to differential-geometric scalar curvature.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XIII_ENERGY_ROUTING.md#L85` -- Proposition VI — The walk is the energy integral at Fibonacci strides.
     why: Uses word 'integral' in context of Fibonacci walk energy, not in Riemannian integral sense of family 335.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/06-atmosphere/phase-cycle.md#L1` -- [V] Phase-change cycle = loop invariant
     why: Discusses integral and loop properties but in eigenvalue-geometry context, not scalar curvature bounds.

## 336. Spectral scalar curvature, Urysohn width, and macroscopic dimension

- **Vetting:** 3 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Complete manifolds with a spectral scalar-curvature lower bound (quadratic-form inequality -4Δ+Scal≥1) admit continuous maps to low-dimensional simplicial complexes with controlled fiber diameter. Extends Gromov's width theorem to spectral rather than pointwise curvature bounds.
- **CASLO frame:** Spectral transfer-matrix analysis: family uses Laplacian eigenvalue bounds on manifolds; owner uses Perron-Frobenius eigenvalue φ on [[1,1],[1,0]] to bound bit-density scaling as φ^(-k). Both employ eigenvalue spectral decomposition as structural tool, but on disjoint mathematical objects.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L67` -- S5. Perron-Frobenius vector = steady-state bit-density operator
     why: Both use spectral eigenvalue analysis as structural tool. Owner: eigenvalue φ controls bit-density decay φ^(-k) per shell. Family: eigenvalue bounds control manifold geometry. Shared analogy: eigenspectrum → structural constraint.
     ruling: Claim anchored at L36 (S2, eigenspaces). The 'why' misstates 336: no Laplacian eigenspaces or spectral decomposition appear in any of its 3 manuscripts. 336 uses only the hypothesis -4Delta+Scal>=1 'in the quadratic-form sense... not require a lowest eigenvalue to be attained' (main.pdf, pdftotext L
  2. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L36` -- S2. The F-channel and L-channel ARE the eigenspaces
     why: Owner's eigenspace decomposition A=P·D·P^(-1) with D=diag(φ,ψ) realizes spectral structure as hardware. Family uses Laplacian eigenspaces similarly to control geometry. Same pattern, different domains.
     ruling: Claim anchored at L36 (S2, eigenspaces). The 'why' misstates 336: no Laplacian eigenspaces or spectral decomposition appear in any of its 3 manuscripts. 336 uses only the hypothesis -4Delta+Scal>=1 'in the quadratic-form sense... not require a lowest eigenvalue to be attained' (main.pdf, pdftotext L
  3. level 1 (draft 2, REJECT) `_master_workflow_/math/eigenvalue-geometry/04-hyperbolic/anosov-dynamical.md#L1` -- [V] Hyperbolic dynamics (Anosov)
     why: Owner explores eigenvalue-driven dynamics in hyperbolic regime; family 336 studies manifolds with curvature bounds as hyperbolic geometry. Structural parallelism: eigenvalue governs dynamics/geometry.
     ruling: The 'why' misstates 336. It assumes POSITIVE spectral scalar curvature (-4Delta+Scal>=1); it does not study hyperbolic geometry. 'Hyperbolic' appears in 336 only in a bibliography title (Kemper, 'Gromov Hyperbolic Manifolds...'), and 'entropy' only in Perelman's paper title. The owner's 8-line note 

## 337. Sharp Cartan–Hadamard isoperimetry and rigidity

- **Vetting:** 2 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Cartan–Hadamard isoperimetry is resolved in all dimensions: in a simply-connected manifold with non-positive sectional curvature, any finite-volume set has perimeter at least that of an equal-volume ball in the model space. Equality holds precisely for Euclidean balls.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/helmet/nodes/s01-07-10-13-15-20-22-24-27.md#L1` -- v013 L-readout is perimeter-Lucas (any neighbour), not strict bridge F(k)+F(k+2)=L(k+1)
     why: Word 'perimeter' appears in context of Lucas channel routing (hardware readout), not isoperimetric geometry on manifolds.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Vocabulary: 'bounded', 'mass', 'space'; applied to CASLO register bounds and state mass conservation, not perimeter inequalities.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Defines terms in owner's framework; no intersection with isoperimetric or CAT(0) geometry concepts.

## 338. Yau's uniformization conjecture

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Yau's uniformization conjecture is proved: every complete connected non-compact Kähler manifold with strictly positive holomorphic bisectional curvature is biholomorphic to complex Euclidean space C^n.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Vocabulary: 'dimension', 'space'; applied to LUT fabric and canonical-form dimensionality, not complex manifold biholomorphisms.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Word 'omorphic' matches 'biholomorphic' lexically but means nothing in owner's framework (no complex structures, no holomorphic maps).
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/WIKI.md#L217` -- 4.5 The Hyperbolic Jump Rule
     why: Discusses Euclidean embedding and hyperbolic geometry but in algebraic Fibonacci context, not Kähler geometry or uniformization.

## 339. Katok's entropy rigidity conjecture

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Katok's entropy rigidity conjecture: normalized Liouville measure has maximal entropy for geodesic flow on closed Riemannian manifolds of dimension ≥3 with strictly negative sectional curvature iff the metric is locally symmetric.
- **CASLO frame:** Transfer matrices with Perron-Frobenius eigenvalue phi have entropy rate = ln(phi). Bit-density distribution phi^{-k} decreases by factor phi per shell level. Information entropy controls topology of the cascade lattice and canonical fixpoint structure.
- **Verdict:** ANALOGY
  1. level 2 (draft 3, DOWNGRADE) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: States s = lim_{n→∞} (1/n) ln Ω(n) = ln λ_max(A); entropy equals log of dominant eigenvalue. For owner's transfer matrix, λ_max = φ, so s = ln(φ).
     ruling: Level 2 holds; level 3 does not. Both texts are about topological entropy as an exponential growth rate in natural log. Paper: Theorem 1.1 is h_mL(phi^1) = h_top(phi^1) <=> nabla R = 0. It introduces h_top as 'the exponential growth of its orbit complexity' and volume entropy as the growth rate of b
  2. level 2 (draft 3, DOWNGRADE) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L67` -- S5. Perron-Frobenius vector = steady-state bit-density operator
     why: S5 defines Perron-Frobenius vector v_PF = (φ, 1) giving steady-state bit-density ∝ φ^{−k}. Directly parallels entropy-rate law: eigenvalue eigenspace projects information density across shell lattice.
     ruling: No specific object crosses. The paper has no transfer matrix, Perron-Frobenius eigenvector, phi or phi^{-k} profile. Section S5 (L67-84) has no entropy: the s = ln(phi) row is a separate owner item at L98. S5 also has no probability measure invariant under a flow and no curvature. The claim's 'why' 
  3. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L451` -- 4.3 Axis 2 — shell-index hand: `log_phi` rapidity, density `phi^{-k}`
     why: Axis 2: 'log_φ rapidity, density φ^{−k}'. Shared structure: both use log of golden ratio to characterize decay rates / information density; analogy: entropy rate decays like logarithm of eigenvalue.
     ruling: The stated basis is false. The paper never uses the golden ratio or log(phi); its logarithms are natural logs of entropies. Section 4.3 (L451-457) is about a coordinate: log_phi 'rapidity', read as the top Zeckendorf shell index, plus lacunarity R[k]*R[k+1] = 0. 'Hyperbolic coordinate' and 'integer 

## 340. A counterexample to the nearby Lagrangian conjecture

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Disproves the nearby Lagrangian conjecture by constructing a closed exact Lagrangian in T*(S^9 × S^{N-1}) that is diffeomorphic to the base but not Hamiltonian isotopic to the zero section.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Word overlap on 'Hamiltonian' and 'closed', but owner's Hamiltonian context is about phase-register dynamics in state machines, not symplectic geometry.

## 341. Donaldson's hypersymplectic deformation conjecture

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Donaldson's hypersymplectic deformation conjecture: every positive triple of closed two-forms on a closed oriented four-manifold deforms, preserving cohomology, to a hyperkähler triple.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L773` -- 6.4 Harmonized two-register build prescription
     why: Lexical match on 'closed', 'preserving', 'form' but referring to state-machine register configurations and RTL closure preservation, not differential forms or deformations.

## 342. Donaldson's tamed-to-compatible conjecture

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Donaldson's tamed-to-compatible conjecture: every smooth almost complex structure on a closed four-manifold tamed by a symplectic form admits a compatible symplectic form.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L636` -- 5.4 R(t-1) triple-duty
     why: Match on 'We prove that', 'closed', 'structure' but owner discusses register handoff and phase-domain dualities, not almost-complex or symplectic structures.

## 343. Symplectic ball packing in higher dimensions

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Resolves Siegel–Yao conjecture: finitely many closed symplectic balls of capacities R_i embed disjointly into an open ball of capacity R iff ∑R_i^n < R^n and R_i + R_j < R for every pair i ≠ j.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L89` -- 4. The graded fold — packing the whole past into one register
     why: Owner's 'packing' means embedding multiple tokens into disjoint integer register bands via shifts; symplectic packing means embedding disjoint balls via symplectic embeddings. Different mathematical contexts despite word overlap.

## 344. The metric Blaschke conjecture

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves metric Blaschke conjecture: every closed connected Riemannian manifold whose injectivity radius equals its diameter is, up to scaling, a standard compact rank-one symmetric space.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: Both invoke 'symmetric' and relate to metric geometry, but Blaschke theorem concerns injectivity radius and manifold symmetry classes; owner's 'symmetric' refers to Cassini-identity symmetries in fibbinary lattice.

## 345. Infinitely many closed geodesics on Riemannian spheres and closed three-manifolds

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves every smooth Riemannian metric on the n-sphere (n≥2) has infinitely many distinct closed prime geodesics; extends to closed three-manifolds.
- **CASLO frame:** Closed geodesics proliferate with growth rate controlled by the Perron-Frobenius eigenvalue phi, where topological entropy h_top = ln(phi) = entropy-rate law, the same mechanism controlling shell capacity decay as phi^{-k} in the owner's transfer-matrix lattice.
- **Verdict:** WORDS
  1. level 1 (draft 3, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L67` -- S5. Perron-Frobenius vector = steady-state bit-density operator
     why: Both papers use Perron-Frobenius eigenvalue phi to control growth rates: geodesics via entropy h_top=ln(lambda), owner's lattice via density phi^{-k}. The eigenvalue is the same universal constant in both contexts.
     ruling: Owner item: TRANSFER_MATRIX_AS_LUT_FABRIC.md L67 (S5: Perron-Frobenius vector (phi,1), bit-density phi^{-k}). I searched all of family 345's LaTeX sections and references.bib. There are zero hits for entropy, Perron, hyperbolic, Anosov, Katok, Manning, or exponential growth, and phi never appears. T
  2. level 1 (draft 4, REJECT) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: Direct citation of topological-entropy theorem: s = ln(lambda_max(A)). Family 345 counts closed geodesics via Perelman and Rademacher-Taimanov; the growth rate is h_top = ln of the linearization's dominant eigenvalue. This is the same operator-level statement.
     ruling: Owner item: entropy-rate-law.md. It is located at _master_workflow_/math/eigenvalue-geometry/00-spine/; /mnt/c/Users/casma/math is the OpenAI clone and has no such file. It states s = lim (1/n) ln Omega(n) = ln lambda_max(A) for constrained systems. Family 345's theorem (infinitely many prime closed
  3. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L451` -- 4.3 Axis 2 — shell-index hand: `log_phi` rapidity, density `phi^{-k}`
     why: Theorem 4.3 states 'rapidity is log_phi of the magnitude' and 'occupancy proportional to phi^{-k}'. Same exponential decay structure as geodesic distribution under hyperbolic flow.
     ruling: Owner item: EMBEDDING_CLOCK_AND_CHANNELS.md L451-511 (Thm 4.3: log_phi rapidity and phi^{-k} Perron-Frobenius occupancy; then L14 and Thms 4.5-4.7 on ord(A), coprime clock periods, and the conserved current). Family 345 contains no geodesic distribution, no hyperbolic or geodesic-flow statistics, an

## 346. Sharp singular-set bounds for stationary integral varifolds

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves singular sets of stationary integral varifolds have Hausdorff dimension at most m-1 in every codimension; sharp and proved without nondegeneracy restrictions.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L718` -- 6.2 The transient-multiplicity caveat (Lemma L13)
     why: Lexical match only: 'regularity', 'bounds', 'set'. Lemma L13 is about state multiplicity in cascade steps; Family 346 is about Hausdorff dimension of singular sets in varifold theory. No shared mathematical object.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/UPGRADE/caslo_monolith/harness/docs/ELEMENTS_BOOK_XVI_HETEROGENEITY.md#L34` -- Propositions
     why: Lexical match only: 'regularity', 'bounds'. No connection to varifold measure theory.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Lexical match only: 'dimension', 'closed'. No varifold-theory connection.

## 347. Counterexamples to stable-Morse and strong Arnold fixed-point bounds

- **Vetting:** 5 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Disproves stable-Morse lower bounds for Hamiltonian fixed points: constructs simply connected Kähler manifolds where fixed-point count falls short of the stable Morse number.
- **CASLO frame:** The 2-torus admits hyperbolic automorphism via matrix A with eigenvalues phi and psi; however, Arnold conjecture and stable-Morse bounds belong to symplectic topology, not dynamical systems. Weak bridge: both involve Hamiltonian structure and Anosov-like hyperbolic geometry.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/04-hyperbolic/anosov-dynamical.md#L1` -- [V] Hyperbolic dynamics (Anosov)
     why: Anosov automorphism on 2-torus via A=[[1,1],[1,0]] with eigenvalues phi, psi; topological entropy h_top = ln(phi). Family 347 studies Hamiltonian diffeomorphisms which are also symplectic transformations; both involve hyperbolic fixed-point theory, but applied to different structures (symplectic vs.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L435` -- 4.1 Axis 0 — master hand: `A^n` and the global period
     why: A^n iteration governs the dynamical period. Arnold conjecture bounds relate to iteration count and fixed-point multiplicity, but the owner's usage is for fibbinary state counting, not symplectic geometry.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/helmet/nodes/s02-10-18-22-28.md#L1` -- LOCK/RESO/DIST/NONE predicate = detect tier: gained bits, stride-2, sym-diff, else NONE
     why: Mentions hyperbolic structure, but in the context of shell-lattice adjacency, not symplectic topology.

## 348. Nonnegative-curvature Einstein classification and an L2 topological gap

- **Vetting:** 3 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Classifies Einstein four-manifolds with positive Einstein constant and nonnegative sectional curvature: universal covers are S^4, CP^2, or S^2×S^2. Proves L^2 gap for trace-free Ricci curvature.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/04_zphi_ring/hyperbolic_distance.md#L1` -- Hyperbolic distance
     why: Lexical match on 'metric'. Owner uses hyperbolic distance metric on the Z[phi] ring to measure shell separation. Family 348 uses Riemannian metric on Einstein manifolds to measure curvature. Different mathematical objects and contexts.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L451` -- 4.3 Axis 2 — shell-index hand: `log_phi` rapidity, density `phi^{-k}`
     why: Lexical match on 'metric', 'R', 'ic'. No connection to Einstein geometry or sectional curvature.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L271` -- 13. The lock — the twist that couples the two rails
     why: Lexical match on 'metric'. No Einstein-geometry connection.

## 349. The Solomon–Yau least-volume conjecture

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Solomon-Yau least-volume conjecture for minimal hypersurfaces in spheres: minimal immersions with non-totally-geodesic image have volume at least the smallest Clifford product.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L489` -- 4.7 The deepest cycle — `I-1` conservation as the period-1 hand
     why: Lexical match on 'multiplicity', 'measured', 'Pro'. Lemma about state mass I-1 conservation in cascade steps. No minimal-surface-theory connection.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Lexical match on 'dimensional', 'closed', 'multiplicity'. No minimal-hypersurface connection.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/UPGRADE/caslo_monolith/harness/docs/ELEMENTS_BOOK_XVI_HETEROGENEITY.md#L102` -- Scholia (where the mathematics touches silicon)
     why: Lexical match on 'measured', 'multiplicity'. No volume-bound or minimal-surface connection.

## 350. Yau’s nodal bounds: surfaces and higher dimensions

- **Vetting:** 3 manuscript(s); Lean scope note; 2 in formalization.yaml; 0 revised.
- **Plain:** Proves sharp C√λ upper bound for nodal length of Laplace eigenfunctions on smooth surfaces; disproves the bound in three and higher dimensions via explicit counterexamples.
- **CASLO frame:** Both use eigenspace decomposition under spectral theory. Owner's F-channel and L-channel project state onto phi-eigenspace and trace(A^n)=psi-eigenspace; Yau's nodal bound involves Laplace eigenfunctions as eigenspaces of the Laplacian operator. Same framework (spectral decomposition and eigenvalue control of geometry), different operators.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L36` -- S2. The F-channel and L-channel ARE the eigenspaces
     why: Theorem: F-channel projects onto phi-eigenspace (F_n = (phi^n - psi^n)/√5), L-channel projects onto psi-eigenspace sum (L_n = phi^n + psi^n). Both families decompose geometry via eigenfunctions: Family 350 uses Laplace eigenfunctions ψ_λ on the surface; owner uses Fibonacci/Lucas eigenfunctions of A
     ruling: Owner item: TRANSFER_MATRIX_AS_LUT_FABRIC.md L67-127 (S5: right Perron-Frobenius vector (phi,1), activity ratio phi per shell step; then LUT-cost tables). Family 350 does not get sqrt(lambda) 'via spectral density'. The surface bound comes from averaging doubling-index log-growth over a grid of side
  2. level 1 (draft 2, DOWNGRADE) `_master_workflow_/math/eigenvalue-geometry/06-atmosphere/barometric.md#L1` -- [V] Barometric law = eigenfunction of d/dz
     why: Exponential eigenfunction p(z) = p₀ e^{-z/H} of d/dz is the canonical ansatz for spectral decomposition. Same eigenvalue method: both use eigenfunctions to decompose spatial/frequency structure, though with different rate constants (H vs. phi).
     ruling: Owner item: barometric.md (located at _master_workflow_/math/eigenvalue-geometry/06-atmosphere/). It gives p0 e^{-z/H} as the exact solution of a first-order constant-coefficient ODE and reads it as an eigenfunction of d/dz with eigenvalue -1/H. Family 350's exponentials are WKB factors e^{k Phi}A_k
  3. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L67` -- S5. Perron-Frobenius vector = steady-state bit-density operator
     why: Perron-Frobenius vector v_PF = (phi, 1) gives steady-state bit-density; density at site k scales as phi^{-k}. Family 350 relates nodal measure growth to sqrt(λ) via spectral density. Both use spectral eigenvector to control spatial structure.
     ruling: Owner item: TRANSFER_MATRIX_AS_LUT_FABRIC.md L67-127 (S5: right Perron-Frobenius vector (phi,1), activity ratio phi per shell step; then LUT-cost tables). Family 350 does not get sqrt(lambda) 'via spectral density'. The surface bound comes from averaging doubling-index log-growth over a grid of side

## 351. Scalar curvature and finite-time Ricci-flow singularities

- **Vetting:** 3 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves that smooth Ricci flow on a closed four-manifold extends past finite times with uniformly bounded scalar curvature. Constructs higher-dimensional counterexamples with bounded scalar curvature but unbounded full curvature at finite maximal time.
- **CASLO frame:** no shared object with the owner's framework — differential geometry on Riemannian manifolds (Ricci flow) versus fibbinary lattice recursion and Fibonacci transfer matrices are distinct mathematical domains
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Lexical match on 'bounded' and 'evolution,' but owner's transfer matrix A describes classical tight-binding recursion, not geometric PDEs. No shared mathematical object.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L467` -- 4.5 Axis 4 — phase-register hand: latched `R`, period `~F(W+2)`, Markov boundary (Lemma L1
     why: Match on 'finite' but context is Fibonacci lattice period F(W+2), not curvature evolution on manifolds.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/05_cascade/doubling_rule.md#L1` -- Doubling rule
     why: Conservation law 2·F(k) = F(k+1) + F(k-2) is fibbinary recursion, not curvature flow invariants.

## 352. A finite-time singularity of Calabi flow

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Constructs a smooth Kähler metric in the Fubini–Study class of CP¹⁰ whose Calabi flow develops unbounded scalar curvature at finite time, disproving Chen's smooth long-time existence conjecture.
- **CASLO frame:** no shared object with the owner's framework — Calabi flow is a geometric PDE on Kähler manifolds; owner's framework is classical Fibonacci recursion and transfer matrices on finite lattices
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/CAS_LUT_PIPELINE.md#L142` -- Stage 4 — TRANSFER (5 clocks)
     why: Lexical match on 'metric' and 'evolution' but pipeline stage is hardware datapath, not geometric flow.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/WIKI.md#L48` -- 2. Hard Constraints
     why: Mentions 'bounded' in context of NO BRAM, NO MULTIPLY, etc., not curvature bounds.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Lemmas on cascade and recursion, not on geometric singularities.

## 353. Affine Bernstein rigidity through dimension nine and a smooth dimension-ten counterexample

- **Vetting:** 2 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves affine Bernstein conjecture in dimensions 3-9: every smooth locally uniformly convex affine-maximal graph with Euclidean-complete induced metric is an elliptic paraboloid. Constructs a smooth nonquadratic counterexample in dimension ten.
- **CASLO frame:** Zeckendorf representation and shell-lattice dimension appear in owner's work, but applied to fibbinary token routing, not affine-differential geometry. The 'dimension' and 'canonical form' shared vocabulary serve fundamentally different mathematical purposes.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/zlogpi/zphi.py#L371` -- verify_zeckendorf
     why: Owner's verify_zeckendorf checks fibbinary canonical form (no adjacent 1s), superficially similar to 'canonical form' language in affine geometry, but applied to bit representations, not geometric objects.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L9` -- §0  Compaction-Survival Protocol — read this first
     why: Discusses 'dimension' (shell lattice SHELL_LO=2 to SHELL_HI=46) but as array indexing on Fibonacci lattice, not geometric dimension.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/03_zeckendorf/fibbinary_encoding.md#L1` -- Fibbinary encoding
     why: Zeckendorf representation is fibbinary bit-string encoding, not affine-geometric structure.

## 354. The isoperimetric profile of the cubic three-torus

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Determines the isoperimetric profile of the unit cubic flat three-torus and classifies all finite-perimeter minimizers: balls, circular tubes about shortest closed geodesics, coordinate slabs, and their complements, with transition volumes 4π/81 and 1/π.
- **CASLO frame:** Owner's eigenvalue geometry includes geodesic analysis on hyperbolic surfaces and modular spaces (via A ∈ SL(2,Z) with closed-geodesic length 4 ln(phi)); family studies isoperimetric minimizers on flat 3-torus. Both use 'geodesic' but in distinct geometries: owner's is topological entropy / hyperbolic dynamics, family's is Euclidean isoperimetric geometry.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/04-hyperbolic/modular-geodesic.md#L1` -- [V] Modular-surface geodesic (geometric hyperbolic)
     why: Mentions geodesics on H²/SL(2,Z) and A² = [[2,1],[1,1]] with closed-geodesic length 4 ln(phi). Shared vocabulary 'geodesic' but owner's is on hyperbolic surfaces via SL(2,Z), not flat torus isoperimetry.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/05_cascade/cascade_composition.md#L1` -- Cascade composition
     why: Fibbinary rewrite rules (minimal paths in Zeckendorf lattice); superficially analogous to 'shortest paths' in isoperimetric problems but applied to bit-string reductions, not geometric lengths.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/04-hyperbolic/anosov-dynamical.md#L1` -- [V] Hyperbolic dynamics (Anosov)
     why: Topological entropy h_top = ln(phi) from expanding eigenvalue; distinct from flat torus isoperimetric geometry.

## 355. Unique tangent flows at the first surface singularity

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves that at each singular point of the first singular time of mean-curvature flow on a smooth compact embedded surface in R³, all fixed-center backward tangent flows converge smoothly to one multiplicity-one self-shrinker flow, unique in original ambient coordinates.
- **CASLO frame:** no shared object with the owner's framework — mean-curvature flow is a parabolic PDE on surfaces; owner's uniqueness theorems apply to fixed points of recursive cascade operators and Zeckendorf decomposition. Both mention 'uniqueness' but in fundamentally different mathematical contexts.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L489` -- 4.7 The deepest cycle — `I-1` conservation as the period-1 hand
     why: Discusses fixed point and convergence of I-1 (one-cycle) in cascade algebra, not geometric mean-curvature-flow tangent cones.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L137` -- A2. A^∞ has no fixed point — only the spectral gap matters
     why: States A^∞ lacks fixed point but spectral gap |phi| − |psi| = √5 governs dynamics; geometric paper's 'tangent flow' uniqueness is about limits of geometric PDE solutions, not spectral limits of matrices.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L9` -- §0  Compaction-Survival Protocol — read this first
     why: Defines uniqueness and determinism in cascade operations; no connection to geometric mean-curvature-flow singularities.

## 356. Gigli’s characterization of Alexandrov curvature

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves Gigli's conjecture: an integer-dimensional complete separable metric space is an n-dimensional Alexandrov space of curvature at least κ if and only if it is a full-support RCD((n-1)κ, n) space with distributional sectional curvature at least κ.
- **CASLO frame:** Both employ Perron-Frobenius eigenvalue analysis: owner applies it to transfer matrix A = [[1,1],[1,0]] (eigenvalues phi, psi = (1±√5)/2) for Fibonacci routing and token density phi^{−k}; paper applies RCD characterization and Perron-Frobenius spectral theory to curvature bounds in metric spaces. Shared mathematical tool applied to distinct objects: classical transfer matrix vs metric geometry.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L67` -- S5. Perron-Frobenius vector = steady-state bit-density operator
     why: Owner explicitly states: 'A's right Perron-Frobenius eigenvector is v_PF = (phi, 1)... bit k activity ∝ phi^{−k}.' This is the same Perron-Frobenius spectral method the family employs for RCD condition characterization, but applied to Fibonacci matrices for token routing, not curvature bounds. Share
     ruling: Owner S2 (L36) is the eigendecomposition A = P diag(phi,psi) P^{-1} of the 2x2 Fibonacci matrix, with Binet F_n and L_n = tr(A^n). The family never decomposes a matrix into eigenvectors and never computes an eigenvalue, a matrix power or a matrix trace. In the family, 'trace' means Sobolev endpoint 
  2. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L36` -- S2. The F-channel and L-channel ARE the eigenspaces
     why: Spectral decomposition A = P·D·P⁻¹ with D = diag(phi, psi). F-channel and L-channel are eigenvector projections: F_n = (phi^n − psi^n)/√5 (phi-eigenspace), L_n = phi^n + psi^n = tr(A^n) (trace). Paper uses eigenvalue/eigenvector methods for RCD spectral characterization. Both rely on spectral decomp
     ruling: Owner S2 (L36) is the eigendecomposition A = P diag(phi,psi) P^{-1} of the 2x2 Fibonacci matrix, with Binet F_n and L_n = tr(A^n). The family never decomposes a matrix into eigenvectors and never computes an eigenvalue, a matrix power or a matrix trace. In the family, 'trace' means Sobolev endpoint 
  3. level 1 (draft 2, REJECT) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: Owner's eigenvalue geometry directly connects Perron-Frobenius spectrum (expanding eigenvalue phi) to topological entropy ln(phi). Paper uses spectral methods for metric geometry. Both employ Perron-Frobenius theory: analogy of method, not of object.
     ruling: The owner note (9 lines) is the topological entropy rate of a constrained system: s = lim (1/n) ln Omega(n) = ln lambda_max(A), the growth rate of an admissible-word count equal to the log of the Perron-Frobenius eigenvalue. The family's 'entropy' is a different object: the relative Boltzmann entrop

## 357. Bi-Lipschitz coordinates at every regular RCD point

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves that every regular point of a metric space has an open neighborhood with coordinate maps bounded by a Lipschitz constant dependent only on dimension to Euclidean space.
- **CASLO frame:** No shared object with owner's framework. RCD metric geometry uses bounded coordinate homeomorphisms; CASLO uses Zeckendorf representations and fibbinary lattice paths.
- **Verdict:** NONE

## 358. A three-manifold without conjugate points or nonpositive curvature

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Constructs a smooth 3-manifold with a Riemannian metric containing no conjugate points but admitting no metric with nonpositive sectional curvature everywhere.
- **CASLO frame:** No shared object with owner's framework. Conjugate points and sectional curvature are Riemannian concepts; CASLO phi/psi operators are shift operations on indices.
- **Verdict:** NONE

## 359. Negative Kähler curvature without bounded holomorphic coordinates

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Constructs a contractible domain in C^3 with a complete negatively pinched Kahler metric that admits no bounded holomorphic coordinate maps to a bounded domain.
- **CASLO frame:** No shared object with owner's framework. Kahler geometry and holomorphic functions are complex-analytic; CASLO uses integer-valued Fibonacci and Lucas sequences with algebraic structure.
- **Verdict:** NONE

## 360. Weak MTW curvature gives convexity and regular optimal transport

- **Vetting:** 2 manuscript(s); Lean scope note; 2 in formalization.yaml; 0 revised.
- **Plain:** Proves weak Ma-Trudinger-Wang curvature on a Riemannian manifold implies convexity of injectivity domains and Holder continuity of optimal transport maps and inverses.
- **CASLO frame:** No shared object with owner's framework. Optimal transport theory uses Monge maps and geodesic convexity; CASLO uses cascade reductions and shell-lattice conservation laws.
- **Verdict:** NONE

## 361. Failure of integer-degree harmonic dimension comparison

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Shows that harmonic functions of bounded polynomial growth on nonnegative Ricci manifolds can exceed Euclidean dimension counts, disproving Yau's integer-degree bound.
- **CASLO frame:** No shared object with owner's framework. Harmonic dimension on Ricci manifolds is Riemannian PDE theory; CASLO uses deterministic recurrence on finite shell indices and mass conservation.
- **Verdict:** NONE
