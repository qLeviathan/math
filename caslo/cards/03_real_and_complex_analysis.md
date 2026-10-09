# Real and complex analysis -- OpenAI result families in CASLO framing

Levels: 0 none, 1 words, 2 analogy, 3 shared object, 4 direct use. Final levels >= 2 were confirmed by an adversarial verifier; unverified claims are capped at 1.

## 071. Koebe’s circle-domain conjecture

- **Vetting:** 2 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Every domain in the Riemann sphere is conformally equivalent to a circle domain with removable boundary; establishes that conformal equivalences between circle domains are Möbius transformations.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L144` -- 6. The twist — why this is a *Möbius* ribbon, not a cylinder
     why: Both mention Möbius, but owner's context is fibbinary ribbon topology, not conformal geometry; purely vocabulary overlap
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L1` -- Transfer Matrix as LUT Fabric — Synthesis
     why: Both use 'mapping', but transfer matrix maps Z[φ] states, not conformal domains; only the word 'mapping' is shared
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: Owner's φ/ψ are Fibonacci eigenvalues in recurrence algebra; Koebe's problem is about conformal geometry of domains

## 072. Brennan's conjecture and the integral-means spectrum

- **Vetting:** 2 manuscript(s); Lean scope note; 2 in formalization.yaml; 0 revised.
- **Plain:** For conformal bijections from plane domains onto the unit disk, the derivative satisfies area-integrability bounds; sharp integral-means spectrum disproves Kraetzer's conjecture at specific parameters.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/04_zphi_ring/z_phi_element.md#L1` -- Z[phi] element
     why: Word 'integral' appears, but owner's context is ring-theoretic ('integral elements a+bφ'), not Lebesgue integral means of derivatives
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XIII_ENERGY_ROUTING.md#L85` -- Proposition VI — The walk is the energy integral at Fibonacci strides.
     why: Energy integral at Fibonacci strides; unrelated to univalent function derivatives or conformal bijection integrals
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Discusses axioms and functions in CASLO embedding context, not univalent functions or complex analysis

## 073. The Falconer distance conjecture

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Every compact set in ℝ^d with Hausdorff dimension > d/2 determines a set of Euclidean distances with positive Lebesgue measure, resolving Falconer's conjecture in all dimensions.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L171` -- Addendum: Tensor-Hop Network Reading
     why: Both mention 'dimension', but owner's dimension is lattice shell-index k ∈ {2..46}, not Hausdorff dimension of compact sets
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L5` -- 1. Core Construction (Sec 1, 1.1, 2.1; pp. 3-6, 13)
     why: Discusses construction of transfer matrix properties; unrelated to fractal dimension or distance set theory
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_X_UNIFIED_LM.md#L14` -- NOMENCLATURE
     why: CASLO nomenclature; no connection to Hausdorff measure or Euclidean distance geometry

## 074. Kakeya in three and four dimensions

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** In 3D, tube maximal operators map L³ to L³(S²) with norm O_ε(δ^{-ε}); in 4D, every set containing unit segments in all directions has Hausdorff dimension 4, resolving Kakeya conjectures.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L57` -- S4. Spine entropy rate = throughput operator
     why: Both mention 'dimension' and 'operator', but owner's operator is A=[[1,1],[1,0]] on Z[φ] states; Kakeya operator is Fourier tube averaging in L^p spaces
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/BOOLEAN_PATHING.md#L30` -- 2. Closure — the only operations allowed on addr
     why: Boolean closure operations on fibbinary addresses; unrelated to harmonic analysis of maximal operators
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/stall_predicate.md#L1` -- stall predicate (S_PSI_RETRACT trigger)
     why: CASLO control logic predicate; unrelated to Kakeya geometry or tubular neighborhoods

## 075. The $L\log L$ Fourier-convergence conjecture

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Symmetric Fourier partial sums of L log L functions on the circle converge almost everywhere along the full sequence, establishing the classical L log L sufficiency conjecture.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/zlogpi/zphi.py#L538` -- bounded_transfer
     why: Function bounded_transfer includes 'convergence' keyword, but is about Z[φ] state transitions, not Fourier series convergence
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/07_hyperbolic_jump/lucas_product.md#L1` -- Lucas-Lucas product-to-sum
     why: Lucas product identities; unrelated to Fourier analysis or function space theory
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/BOOLEAN_PATHING.md#L221` -- 10. How to use this doc
     why: CASLO pathing documentation; no connection to Fourier series or classical harmonic analysis

## 076. Real ultraflat Littlewood polynomials and unbounded binary merit factors

- **Vetting:** 3 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Constructs polynomials with ±1 coefficients having modulus (1+o(1))√N uniformly on the unit circle; proves real Littlewood polynomials are ultraflat with unbounded merit factors, disproving Turyn's conjecture.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/CAS_LUT_PIPELINE.md#L34` -- 2. phi and psi as Operators (not numbers)
     why: Discusses φ and ψ as operators with coefficients in Z[φ]; completely different from Littlewood polynomial ±1 coefficients on unit circle
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L352` -- 3.1 Binet lifts each lit shell to a Z[phi] coordinate
     why: Binet lifting of fibbinary shells to Z[φ]; unrelated to polynomial merit factors or binary approximation on the unit circle
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/LUT4_REALIZATION.md#L23` -- 00 — Axioms (6)
     why: LUT4 axioms for CASLO fabric; unrelated to additive combinatorics or polynomial coefficient sequences

## 077. Fourier restriction for positively curved surfaces

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Fourier extension operators are bounded from Lp(Σ) to Lp(R³) for positively curved surfaces in 3D, for all p > 3. Resolves diagonal Fourier extension conjecture.
- **CASLO frame:** No shared object with the owner's framework. Continuous harmonic analysis (Fourier operators on function spaces) differs from discrete Zeckendorf cascades on a shell lattice.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L223` -- 2. The Cascade as Renormalization Information-Flow
     why: Both mention 'transfer operator' and 'bounded', but CASLO's transfer operators re-coordinatize conserved fibbinary mass on a discrete register; Fourier extension maps function spaces.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L36` -- S2. The F-channel and L-channel ARE the eigenspaces
     why: Discusses spectral decomposition (eigenvalues phi/psi) and transfer matrix, matching vocabulary 'spectral' in Fourier analysis, but eigenvalues of A[[1,1],[1,0]] are not Fourier operators.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Lists 'bounded' operations and conservation laws as cross-cutting insights, matching terminology only.

## 078. The three-dimensional Bochner–Riesz conjecture

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Bochner-Riesz multiplier operators are bounded on Lp(R³) for all 1≤p≤∞ when order δ > max{3|1/p−1/2|−1/2, 0}. Resolves 3D conjecture in strict range.
- **CASLO frame:** No shared object with the owner's framework. Fourier multiplier theory (spectral analysis of convolution operators on function spaces) has no connection to Zeckendorf cascades.
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L435` -- 4.1 Axis 0 — master hand: `A^n` and the global period
     why: Mentions A^n (transfer matrix powers); Bochner-Riesz is about Fourier multiplier symbols m(ξ), not about iterating a 2×2 matrix.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/06-atmosphere/phase-cycle.md#L1` -- [V] Phase-change cycle = loop invariant
     why: Nominal L^p notation match but about phase cycles, not about Bochner-Riesz multipliers.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L21` -- 1. The system in plain language
     why: Contains word 'multiplier' in a different context (data multiplexing in cascades, not harmonic analysis).

## 079. Local smoothing in three dimensions

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves critical L³ local smoothing estimate for 3D wave equation with positive Sobolev loss. Resolves Sogge's Euclidean local smoothing conjecture for dimension 3.
- **CASLO frame:** No shared object with the owner's framework. Wave equation (continuous PDE) and Sobolev regularity theory differ from discrete Zeckendorf recurrences.
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/UPGRADE/caslo_monolith/harness/docs/ELEMENTS_BOOK_XVI_HETEROGENEITY.md#L34` -- Propositions
     why: Contains word 'regularity' but refers to register pattern regularity, not Sobolev regularity of distributions.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XIII_ENERGY_ROUTING.md#L11` -- NOMENCLATURE
     why: Nominal 'local' and 'loss' terminology overlap with Sobolev loss, but context is energy routing in cascades.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/ZECKENDORF_LOGIC.md#L14` -- PART I — The Dual Address (the atom)
     why: Mathematical notation overlap (dimensions 2,3) but no connection to wave equations or Sobolev spaces.

## 080. The exact Sobolev endpoint for Schrödinger convergence

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves endpoint pointwise convergence for free Schrödinger evolution: for initial data in H^{n/(2(n+1))}(Rⁿ), convergence e^{itΔ}f→f as t↓0 holds almost everywhere. Resolves Carleson's problem at sharp endpoint.
- **CASLO frame:** No shared object with the owner's framework. Schrödinger quantum mechanics and Carleson-style convergence theory differ fundamentally from Zeckendorf cascades on shell lattices.
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Dimension and Sobolev notation match; Schrödinger evolution operator e^{itΔ} is fundamentally different from CASLO's cascade operators.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Mentions 'free' and 'convergence' in different context (reversibility and compression saturation, not wave convergence).
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XIII_ENERGY_ROUTING.md#L11` -- NOMENCLATURE
     why: Nominal vocabulary overlap (dimension n, convergence) but no mathematical connection.

## 081. Riesz transforms and rectifiability in higher codimension

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves n-Ahlfors-David regular Radon measures are uniformly rectifiable when n-Riesz transform is L²-bounded (d≥4, 2≤n≤d-2). Resolves David-Semmes question in remaining higher-codimension range.
- **CASLO frame:** No shared object with the owner's framework. Riesz transforms and geometric measure theory (rectifiability, singular integrals on measures) have no connection to Zeckendorf lattice cascades.
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/UPGRADE/caslo_monolith/harness/docs/ELEMENTS_BOOK_XVI_HETEROGENEITY.md#L34` -- Propositions
     why: Matches 'regularity' and 'bounds' but Ahlfors-David regularity on measures differs from register regularity.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Contains glossary entries with generic 'dimension' and 'bounds' terminology.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Generic 'bounded' and 'problem' terminology only.

## 082. Annular variation and dyadic absolute bounds for the triangular Hilbert transform

- **Vetting:** 3 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves annular r-variation and maximal bounds for triangular Hilbert transform from complex L³×L³ to L^{3/2} for r>2. Settles symmetric 3-input point and dyadic bounds with coefficient freedom.
- **CASLO frame:** No shared object with the owner's framework. Multilinear harmonic analysis (bilinear/trilinear Hilbert operators, r-variation, L^p bounds) differs from Zeckendorf cascades.
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: L³ notation and 'symmetric' vocabulary match but refer to register symmetries, not to symmetric point in multilinear operators.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/UPGRADE/caslo_monolith/harness/docs/ELEMENTS_BOOK_XVI_HETEROGENEITY.md#L34` -- Propositions
     why: Mentions 'bounds' and generic 'values' but in context of cascade composition, not trilinear Hilbert operators.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/stall_predicate.md#L1` -- stall predicate (S_PSI_RETRACT trigger)
     why: Generic 'estimate' and 'range' terminology, no connection to Hilbert transforms.

## 083. Hilbert transforms along Lipschitz directions

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves uniform L2 bound for Hilbert transform along Lipschitz vector fields, resolving Stein's weak-(2,2) conjecture at short scales with integration length bounded by reciprocal Lipschitz constant.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L36` -- S2. The F-channel and L-channel ARE the eigenspaces
     why: Both invoke transfer matrices and spectral decomposition (eigenvalues phi/psi); Hilbert transform is bounded operator, owner's transfer matrix has spectral bounds—but applications diverge: singular integral vs tight-binding model.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L67` -- S5. Perron-Frobenius vector = steady-state bit-density operator
     why: Perron-Frobenius eigenvalue phi governs bit-density scaling; shared vocabulary (eigenvalue, spectral theory, growth rate) but owner uses for state cardinality, not operator bounds.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/psi_retract_operator.md#L1` -- psi_retract operator
     why: Both study operators (psi_retract is conjugate channel operator); shared word 'operator' and 'bounded', but different domains and purposes.

## 084. The geometric case of the Erdős similarity conjecture

- **Vetting:** 2 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Constructs compact subsets of [0,1] with measure arbitrarily close to one, containing no affine copy of geometric progressions {q^n : n≥1} for any fixed q∈(0,1), resolving geometric-progression case of Erdős similarity conjecture.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/01_recurrences/fibonacci.md#L1` -- Fibonacci recurrence
     why: Both study sequences; Erdős paper avoids exponential sequences q^n, owner studies Fibonacci F(n)=F(n-1)+F(n-2)—different growth mechanisms, no shared structure.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/03_zeckendorf/zeckendorf_theorem.md#L1` -- Zeckendorf theorem
     why: Both address decomposition/representation problems; Erdős avoids patterns in sets, Zeckendorf provides unique decomposition—shared vocabulary but unrelated domains.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L36` -- S2. The F-channel and L-channel ARE the eigenspaces
     why: Owner's phi eigenvalue governs Fibonacci growth ~phi^n; Erdős uses exponential q^n—both exponential, but Fibonacci vs arbitrary ratio, no interaction.

## 085. Endpoint Sobolev regularity of centered disk averages

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves endpoint gradient bound ‖∇Mf‖₁ ≤ C‖∇f‖₁ for centered disk maximal function, showing it belongs locally to W^{1,1}(ℝ²), resolving Hajłasz–Onninen regularity question.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/05_cascade/cascade_cost.md#L1` -- Cascade cost (hardware)
     why: Both study cost/bounds; cascade cost is architectural LUT overhead, maximal function gradient bound is harmonic analysis—shared word 'bound', unrelated mathematics.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L178` -- 1.2 Canonicality forces the Lucas bridge to read single-valuedly (Lemma L5)
     why: Lemma L5 canonicality constraint enforces fibbinary regularity; maximal function regularity is Sobolev-space property—both 'regularity' but in entirely different contexts.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/CLAUDE.md#L1` -- 
     why: Owner's conservation law I-1 preserves multiset mass exactly; harmonic analysis gradient bounds are functional-analytic—both invoke conservation/invariant ideas, no shared mechanism.

## 086. An L3 bound for the trilinear Hilbert transform

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves trilinear Hilbert transform with fixed slopes 1,2,3 maps L³(ℝ)×L³(ℝ)×L³(ℝ) boundedly to L¹(ℝ), resolving the L³ exponent case of trilinear Hilbert conjecture.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L36` -- S2. The F-channel and L-channel ARE the eigenspaces
     why: Both use transfer-matrix language and spectral decomposition; Hilbert transform is singular integral operator, owner's transfer matrix is Fibonacci tight-binding—shared terminology, divergent applications.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/04_zphi_ring/index_subtraction.md#L1` -- Index subtraction (backward hop composition)
     why: phi/psi are eigenvalues of owner's companion matrix; trilinear Hilbert has no direct eigenvalue-based analysis—shared word 'eigenvalue', no mathematical transfer.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/03_zeckendorf/zeckendorf_theorem.md#L1` -- Zeckendorf theorem
     why: Zeckendorf fibbinary bounds state cardinality; trilinear Hilbert bounds operator norms in Lebesgue spaces—both measure-theoretic in abstract sense, no shared object.
