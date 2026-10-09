# Number theory -- OpenAI result families in CASLO framing

Levels: 0 none, 1 words, 2 analogy, 3 shared object, 4 direct use. Final levels >= 2 were confirmed by an adversarial verifier; unverified claims are capped at 1.

## 001. Milne’s rationality conjecture and algebraic specialization

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 1 revised.
- **Plain:** Proves specialized Hodge classes on abelian varieties pair rationally with divisor products in all cohomology theories.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Foundational lemmas on Z[phi] and Fibonacci recurrence; unrelated to abelian varieties or Hodge classes
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Cross-cutting insights on CASLO's Zeckendorf/cascade algebra; unrelated to algebraic geometry
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L398` -- 3.3 The centroid moment M is a third orthogonal projection
     why: Describes orthogonal projections in CASLO's channel system; unrelated to algebraic cycle pairing

## 002. The full BSD formula from low Selmer corank

- **Vetting:** 3 manuscript(s); no Lean scope note; 0 in formalization.yaml; 3 revised.
- **Plain:** Proves Birch-Swinnerton-Dyer formula for elliptic curves with Selmer group corank 0 or 1, settling arithmetic rank via L-function.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L20` -- NOMENCLATURE
     why: Nomenclature for CASLO's rail DAG system; unrelated to elliptic curves or L-functions
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Glossary of CASLO/Fibonacci terminology; does not address elliptic curves or Selmer groups
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L489` -- 4.7 The deepest cycle — `I-1` conservation as the period-1 hand
     why: Describes period-1 conservation in cascade composition; unrelated to Mordell-Weil ranks or BSD formula

## 003. The quasi-Riemann hypothesis

- **Vetting:** 3 manuscript(s); Lean scope note; 2 in formalization.yaml; 0 revised.
- **Plain:** Proves Dirichlet L-functions and Riemann zeta function are zero-free in half-plane Re(s) > 7/8, resolving quasi-Riemann hypothesis.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Foundational lemmas on Z[phi] and Fibonacci recurrence; does not concern L-functions or analytical zeros
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/ZECKENDORF_LOGIC.md#L14` -- PART I — The Dual Address (the atom)
     why: Describes Zeckendorf addressing scheme for fibbinary representation; unrelated to complex analytic half-planes
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L20` -- NOMENCLATURE
     why: Nomenclature for CASLO rail structures; unrelated to Dirichlet L-functions or zeta zeros

## 004. Hilbert’s tenth problem over ℚ

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 2 revised.
- **Plain:** Proves no algorithm decides whether a polynomial with integer coefficients has rational zeros, resolving Hilbert's tenth problem negatively.
- **CASLO frame:** Vocabulary overlap on 'algorithm' and 'polynomial' only; contexts entirely unrelated (Diophantine equations vs. Fibonacci state machine).
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L492` -- THEOREMS T1..T5 AND THE ROOT T0
     why: Mentions 'algorithm' and 'theorem'; describes CASLO cascade composition, not polynomial decidability
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Shares 'algorithm' vocabulary; glossary of CASLO operations, not Diophantine decision problems
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: General mathematical methodology; discusses problem-solving in Fibonacci/cascade context only

## 005. Irrationality of Catalan’s constant

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Catalan's constant G = sum_{j≥0}(-1)^j/(2j+1)^2 is irrational, settling transcendental number theory question.
- **CASLO frame:** Vocabulary overlap on 'transcendental'; CASLO represents φ^n as integer pairs (no irrational elements), unrelated to Catalan's constant series.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L443` -- 4.2 Axis 1 — Cassini hand: period 2 with no XOR, no mod
     why: Mentions Cassini identity and period-2 properties; uses 'constant' in Fibonacci context, not transcendental numbers
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: States φ^n is 'transcendental' but immediately shows exact integer-pair representation; opposite of Catalan's irrationality
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/ZECKENDORF_LOGIC.md#L14` -- PART I — The Dual Address (the atom)
     why: Discusses exact Zeckendorf integer representation; does not address irrational constants or infinite series

## 006. Goldfeld’s conjecture: densities and mean analytic rank

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 2 revised.
- **Plain:** Proves analytic ranks 0 and 1 each have density 1/2 among quadratic twists of every elliptic curve, confirming Goldfeld's conjecture.
- **CASLO frame:** Vocabulary overlap on 'twist' (Möbius topological property) and 'rank' (kernel lattice order), structures unrelated: elliptic curves vs. ribbon topology.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L492` -- THEOREMS T1..T5 AND THE ROOT T0
     why: Contains 'rank' (kernel rank in lattice structure); does not address elliptic curves or analytic rank distribution
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Shares 'rank' and 'distribution' vocabulary; glossary of CASLO terms, not arithmetic statistics on twists
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L20` -- NOMENCLATURE
     why: Contains 'rank' in CASLO context; describes rail structure naming, not quadratic twist density on elliptic curves

## 007. Ordinary two-point correlations and the corrected Elliott conjecture

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised; reasoning summary reasoning_traces/ordinary-two-point-correlations.pdf.
- **Plain:** Proves the ordinary two-point Chowla conjecture on Liouville correlations of multiplicative functions, achieving O(X/(log X)^c) power-of-logarithm savings.
- **CASLO frame:** Transfer matrix eigenvalue analysis for linear recurrence systems; entropy rate characterized by dominant Perron-Frobenius eigenvalue.
- **Verdict:** ANALOGY
  1. level 2 (draft 3, DOWNGRADE) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L67` -- S5. Perron-Frobenius vector = steady-state bit-density operator
     why: Perron-Frobenius eigenvector (phi, 1) of transfer matrix A; eigenvalue phi governs bit-density scaling via phi^{-k}. Both OpenAI and owner apply matrix eigenvalues to characterize recurrent system behavior.
     ruling: Not level 3. None of the owner's specific objects appear in family 007 (ordinary two-point Chowla and binary corrected Elliott): no Perron-Frobenius eigenvector (phi,1), no eigenvalue phi, no matrix [[1,1],[1,0]], no stationary density. A grep of every TeX source finds no 'eigen', 'Perron' or 'Fibon
  2. level 2 (draft 3, DOWNGRADE) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: s = ln(lambda_max(A)) for any constrained system. Shared object: both use dominant eigenvalue to characterize entropy and growth rate of linear recurrences.
     ruling: The owner's identity s = lim (1/n) ln Omega(n) = ln lambda_max(A) (the topological-entropy / Perron-Frobenius equality for constrained systems) does not appear in family 007. Nor does any 'dominant eigenvalue characterizing growth of linear recurrences'; the family has no linear recurrences. The kin
  3. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/01_recurrences/fibonacci.md#L1` -- Fibonacci recurrence
     why: Fibonacci F(k)=F(k-1)+F(k-2) is canonical linear recurrence with transfer matrix [[1,1],[1,0]]. Both analyze recurrence eigenvalues, though in different application domains.
     ruling: The owner text (EQUATIONS/01_recurrences/fibonacci.md) only states F(k)=F(k-1)+F(k-2) with initial values, provenance, check values and parent/child links. It contains no transfer matrix and no eigenvalues; the claim brings in [[1,1],[1,0]] and 'recurrence eigenvalues' from elsewhere. Family 007 has

## 008. The Deligne–Drinfeld conjecture

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves Deligne-Drinfeld conjecture: rational Grothendieck-Teichmüller Lie algebra is freely generated by one element in each odd weight 3, 5, 7, …
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L352` -- 3.1 Binet lifts each lit shell to a Z[phi] coordinate
     why: Z[phi] as free Z-module with basis {1, phi}. Shared vocabulary: 'free', 'basis', 'algebra'. Owner's discrete number ring is unrelated to Grothendieck-Teichmüller Lie algebras.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/AI_MODEL_LOGIC.md#L15` -- 2. Invariants
     why: Vocabulary overlap: 'generators', 'algebra'. No real connection to Lie algebra generation theorems.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Generic glossary entry. Both mention 'algebra' but in unrelated contexts.

## 009. Function-field reconstruction from Milnor K-theory and Galois data

- **Vetting:** 3 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Reconstructs function fields of transcendence degree ≥2 over algebraically closed constants from mod-ℓ Milnor K-theory and Galois data.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Incidental word match on 'Galois' (appears in owner's acronym context, not as abstract algebra concept). No connection to K-theory or function field reconstruction.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L489` -- 4.7 The deepest cycle — `I-1` conservation as the period-1 hand
     why: Vocabulary: 'data', 'reconstruction'. No shared mathematical object.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/WIKI.md#L195` -- 4.3 Cascade Resolution Rules
     why: Generic term overlap only.

## 010. Unrestricted pro-modularity at the prime two

- **Vetting:** 3 manuscript(s); no Lean scope note; 0 in formalization.yaml; 2 revised.
- **Plain:** Every continuous odd absolutely irreducible 2-adic Galois representation unramified outside finitely many primes occurs in Hecke algebra at odd tame level.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L489` -- 4.7 The deepest cycle — `I-1` conservation as the period-1 hand
     why: Weak word match on '-mod', 'at the'. No connection to p-adic representation theory.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/CAS_LUT_PIPELINE.md#L243` -- 8. Equation-to-Routing Map (Master Table)
     why: No shared mathematical object. Unrelated to Galois representations or modularity.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/WIKI.md#L398` -- 8.3 ECP5 UART Pins
     why: No connection.

## 011. Prime-factor statistics of $p-1$

- **Vetting:** 3 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Prime factors of p-1, normalized and ordered by logarithm with multiplicity, converge jointly to Poisson-Dirichlet law PD(1) as p→∞ over primes.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L67` -- S5. Perron-Frobenius vector = steady-state bit-density operator
     why: Weak word match on 'statistics', 'factor'. Owner's bit-density analysis is unrelated to prime-factor statistical limits.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/jun_11_2026/fineweb_experiment.py#L290` -- run_compression
     why: Vocabulary overlap on 'statistics'. No connection to Poisson-Dirichlet convergence.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Glossary word match on 'statistics', 'p'. No shared statistical structure.

## 012. Independent largest prime factors of consecutive integers

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Largest prime factors of n and n+1 are asymptotically independent in natural density, with Dickman marginals; resolves Erdős-Pomerance Dickman conjecture.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_IX_THELAB.md#L5` -- NOMENCLATURE
     why: Vocabulary only: 'largest', 'integers', 'of'. No connection to prime-factor independence or Dickman distributions.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/WIKI.md#L290` -- 6.1 Cascade Composition (replaces integer addition)
     why: No mathematical connection.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/INDEX.md#L1` -- 
     why: No connection.

## 013. Ostmann’s inverse Goldbach conjecture

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Ostmann's inverse Goldbach conjecture: no finite modification of the primes can be written as A+B where A, B are sets of nonnegative integers with at least two elements each.
- **CASLO frame:** fibbinary decomposition into non-adjacent Fibonacci F-shells exhibits analogous uniqueness constraint; Zeckendorf theorem guarantees unique representation as sum of non-consecutive numbers.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/WIKI.md#L356` -- 7.2 The Shell Register
     why: Both prove uniqueness of decomposition into constrained sums (non-adjacent Fibonacci vs additive indecomposability); shared structural principle of uniqueness under constraints.
     ruling: WIKI.md L356-361 is a glossary entry for the shell register, Zeckendorf's theorem (each positive integer has one representation as a sum of non-adjacent Fibonacci numbers), and the cascade carry. Family 013 proves a non-existence result: no finite modification of the primes is a sumset A+B with |A|,
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L308` -- §13  ZeckBitNode — the unifying type
     why: Mentions decomposition structure and set representation in owner's framework, but no direct mathematical transfer beyond terminology.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L109` -- 3. Math concepts (perused, one line + provenance)
     why: General mathematical context; no specific connection to additive indecomposability or Goldbach-type problems.

## 014. Restricted geometric Langlands, global Arthur enhancements, and generic Ramanujan

- **Vetting:** 8 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves restricted geometric Langlands equivalence, Ramanujan at unramified places for cuspidal representations, and constructs global Arthur enhancements using spectral decomposition of automorphic functions.
- **CASLO frame:** spectral decomposition appears in owner's transfer matrix A with eigenvalues phi/psi; F-channel and L-channel are projections onto the two eigenspaces, analogous to spectral decomposition of automorphic forms.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L36` -- S2. The F-channel and L-channel ARE the eigenspaces
     why: Both employ spectral decomposition: family decomposes automorphic forms via spectral methods; owner decomposes state via F/L eigenspace projections of transfer matrix A, sharing the decomposition principle.
     ruling: TRANSFER_MATRIX_AS_LUT_FABRIC.md S2-S6 diagonalizes the 2x2 Fibonacci matrix A = P diag(phi,psi) P^-1 and uses trace(A^n) = L_n, det(A^n) = (-1)^n (Cassini) and the Perron-Frobenius vector. Family 014 covers the restricted geometric Langlands equivalence, Ramanujan temperedness, Arthur SL2 enhanceme
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L9` -- §0  Compaction-Survival Protocol — read this first
     why: Frame protocol document; spectral language appears but no direct connection to automorphic representations.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/04-hyperbolic/anosov-dynamical.md#L1` -- [V] Hyperbolic dynamics (Anosov)
     why: Discusses spectral properties and Anosov theory, but lacks connection to automorphic forms or Langlands theory.

## 015. Torus-packet equidistribution in prime, quartic, and sextic degrees

- **Vetting:** 3 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Haar equidistribution without escape of mass for torus packets from totally real fields: arbitrary lattices in prime degree, quartic and sextic fields with controlled discriminant growth.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L171` -- Addendum: Tensor-Hop Network Reading
     why: Uses lattice and discriminant terminology but in context of LUT tensor networks, not number field torus packets; vocabulary overlap only.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/00_axioms/sqrt5.md#L1` -- sqrt(5) as phi - psi
     why: Discusses discriminant √5 of the golden ratio ring Z[phi], not number field discriminants in torus packets; distinct mathematical objects.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L435` -- 4.1 Axis 0 — master hand: `A^n` and the global period
     why: Discusses lattice ordering of shell indices, not number field lattices or torus equidistribution.

## 016. Zilber–Pink in abelian varieties and the Siegel threefold

- **Vetting:** 4 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves abelian Zilber-Pink conjecture over the rationals: every irreducible subvariety has finitely many maximal atypical subvarieties relative to smallest containing torsion coset.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L348` -- 3. The State is a Z[phi] Pair
     why: Discusses Z[phi] pairs as state representation, distinct from abelian varieties and torsion cosets; algebraic context only.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/AI_MODEL_LOGIC.md#L15` -- 2. Invariants
     why: Describes invariants of the inference engine, not algebraic varieties or finiteness theorems on atypical subvarieties.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L443` -- 4.2 Axis 1 — Cassini hand: period 2 with no XOR, no mod
     why: Invokes algebraic structure in gating logic, but no connection to finiteness proofs on abelian varieties.

## 017. The irrationality exponent of π is 2

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised; reasoning summary reasoning_traces/irrationality-exponent-of-pi.pdf.
- **Plain:** Proves irrationality exponent of π is exactly 2 using Diophantine approximation: every ε > 0 and sufficiently large q satisfy |π−p/q| ≥ q^{−2−ε}.
- **CASLO frame:** golden ratio phi appears in owner's base-phi register representation and phi^{−k} bit-density operator; continued fractions implicit in phi approximation theory and log-phi scaling.
- **Verdict:** ANALOGY
  1. level 1 (draft 3, REJECT) `_master_workflow_/WIKI.md#L140` -- 3.5 Base-phi / Log-space Representation
     why: Both center on phi: family uses continued fractions of pi via Diophantine theory; owner uses base-phi representation and log_phi (=log(phi)) as core operator for bit-density scaling and rapidity.
     ruling: The premise 'both center on phi' is false. Family 017 is about pi, and its paper has zero hits for golden, Fibonacci or the Greek phi; the 'phi' strings in it are the name Philippon. The proof is a multivariable interpolation-determinant and zero-estimate argument (Laurent, Roth, Philippon) on logar
  2. level 2 (draft 3, DOWNGRADE) `_master_workflow_/EQUATIONS/08_annealing/phi_inverse_approximation.md#L1` -- phi^{-1} integer approximation (5C/8)
     why: Directly addresses Diophantine approximation of phi^{−1}; family proves irrationality exponent via continued-fraction approximation, sharing the Diophantine approximation framework.
     ruling: The analogy holds. The family bounds how well rationals p/q approximate pi (|pi - p/q| >= q^-nu for every nu > 2 and large q). The owner item is a rational approximant to an irrational: 5/8 for phi^-1, with its error. 5/8 = F5/F6 is in fact a continued-fraction convergent of phi^-1 with |phi^-1 - 5/
  3. level 1 (draft 3, REJECT) `caslo_test_framework/docs/MASTER_CONTROL.md#L45` -- §1  Single axiom
     why: Establishes phi as the golden ratio satisfying x² = x + 1; family uses continued-fraction properties of pi; both share golden ratio phi as a fundamental constant.
     ruling: The claim contradicts itself: it says the family 'uses continued-fraction properties of pi' and then says 'both share phi'. Family 017 never uses phi (zero golden or Fibonacci hits), and its method is interpolation determinants, not continued fractions. MASTER_CONTROL.md sections 1-3 (L45-105) conta

## 018. The Margulis–Platonov conjecture over global fields

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Margulis-Platonov conjecture over global fields: every noncentral abstract normal subgroup of rational points of simple groups is inverse image of open normal subgroup in finite product of anisotropic local groups.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/BOOLEAN_PATHING.md#L30` -- 2. Closure — the only operations allowed on addr
     why: Discusses routing involutions and closure on addresses; algebraic-group normal-subgroup structure is distinct from routing involution algebra.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/ZECKENDORF_LOGIC.md#L2` -- Dual-rail Zeckendorf as a computational substrate: filter · group by · sort · arrange · mu
     why: Mentions groupoid structure in Zeckendorf computation, but not equivalent to abstract normal subgroup structure of simple algebraic groups.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/LUT_FABRIC_LM_ALGORITHM.md#L23` -- §1  Type contract  (`BOOLEAN_PATHING.md §1-2`)
     why: References group structure in type contracts for routing, not conjugacy classes or normal subgroups of algebraic groups.

## 019. The local p-adic section conjecture and global consequences

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 1 revised.
- **Plain:** Proves rational points on geometrically connected curves (genus ≥2) over p-adic extensions correspond to sections of the arithmetic étale fundamental group; proves Grothendieck's section conjecture for X_0(N) and X_1(N).
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Lexical match on group/classes but no overlap: étale fundamental groups are algebraic-geometric objects, CASLO uses Zeckendorf/Fibonacci.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L283` -- 14. Statement of the whole object
     why: Match on 'cover' is lexical: étale cover (algebraic geometry) ≠ CASLO cascade reduction.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: No substantive connection; p-adic fields and fibbinary words are mathematically disjoint.

## 020. Squarefree quartics and power-free polynomial values

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves squarefree-values conjecture for irreducible integer quartics: squarefree values have predicted Euler-product density. Extends to (d-2)-power-free densities for polynomials of degree 4–8 under local conditions.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/02_identities/cassini_lucas.md#L1` -- Cassini-Lucas / det Q^n equivalence
     why: Matches on 'determinant', 'power', 'product' are lexical only. Cassini identity (Fibonacci/Lucas) ≠ polynomial determinant estimates.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L109` -- 3. Math concepts (perused, one line + provenance)
     why: Vocabulary overlap (integer, product) but polynomial values ≠ Zeckendorf decomposition.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Generic lexical match; polynomial theory ≠ fibbinary algebra.

## 021. A quadratic bound for Jacobsthal’s function

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves Jacobsthal's conjecture: every interval of Ck² consecutive integers contains an integer coprime to any number with ≤k distinct prime divisors. Bound is quadratic, removing classical logarithmic loss.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L481` -- 4.6 Non-commensurability — the joint odometer has no shared modulus
     why: Matches on 'prime', 'coprime' are lexical. CASLO's non-commensurate clock periods (2, 5, ord(A), F(W+2)) ≠ Jacobsthal coprimality.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/stall_predicate.md#L1` -- stall predicate (S_PSI_RETRACT trigger)
     why: No shared mathematical object; divisibility theory ≠ CASLO's recurrence rules.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L689` -- HAZARDS
     why: Lexical match on integer/divisor only; Jacobsthal function is prime-divisor combinatorics, not Fibonacci.

## 022. The weak inhomogeneous Duffin–Schaeffer conjecture

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves weak inhomogeneous Duffin–Schaeffer: for real shift γ and ψ: Σ φ(q)ψ(q)/q diverges implies ‖qx−γ‖ < ψ(q) infinitely often, almost every x, where φ is Euler's totient.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/08_annealing/phi_inverse_approximation.md#L1` -- phi^{-1} integer approximation (5C/8)
     why: CASLO's φ^{-1} ≈ 5/8 (hardware trick) ≠ Duffin-Schaeffer metric Diophantine approximation theorem.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L459` -- 4.4 Axis 3 — annealing hand: `13C/32`, period 5, integer-subtraction reload
     why: Match on 'approximation' is superficial: hardware φ^{-1} approximation ≠ Diophantine approximation theory.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/ZECKENDORF_LOGIC.md#L14` -- PART I — The Dual Address (the atom)
     why: Generic notation match (q, sum); Zeckendorf logic ≠ continued-fraction Diophantine approximation.

## 023. Patterson's first moment for cubic Gauss sums

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Patterson's first-moment conjecture for cubic Gauss sums: normalized sums over primary Eisenstein primes have main term (6/5)c₊X^{5/6}/log X, with all nonzero Fourier modes at smaller order.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Match on 'asymptotic' is lexical; CASLO's φ^{-k} Perron density ≠ Gauss sum analytic asymptotics.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L451` -- 4.3 Axis 2 — shell-index hand: `log_phi` rapidity, density `phi^{-k}`
     why: Match on 'density', 'asymptotic'; analytic number theory (Gauss sums) ≠ Fibonacci/Zeckendorf algebra.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/psi_retract_operator.md#L1` -- psi_retract operator
     why: Generic match; Gauss sum theory ≠ CASLO's cascade operators.

## 024. An asymptotic formula for the number of totients

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Gives asymptotic equivalent for V(x), count of distinct values of Euler's totient up to x, with coefficient as uniform limit of finite arithmetic data. Proves V(cx)/V(x)→c as x→∞ for all c>0.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L451` -- 4.3 Axis 2 — shell-index hand: `log_phi` rapidity, density `phi^{-k}`
     why: Match on 'asymptotic', 'density'; Perron eigenvalue φ^{-k} ≠ totient-value enumeration asymptotics.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Lexical match on 'formula', 'asymptotic'; totient enumeration ≠ Fibonacci/Zeckendorf framework.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Generic match on 'function'; totient-counting number theory ≠ CASLO's LUT4 integer algebra.

## 025. Short Egyptian fractions

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Every rational a/b with 1≤a<b is a sum of O(log log b) distinct positive unit fractions. Resolves Erdős conjecture on minimum term count.
- **CASLO frame:** No shared object with the owner's framework. Egyptian fractions decompose rationals as sums of unit 1/n; CASLO decomposes by Fibonacci shells in Z[phi].
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/02-identities/addition.md#L1` -- [V] Addition formulas
     why: Matched on 'rational' (rational vs sqrt5 parts in Z[phi]), not Egyptian fractions; shared vocabulary only.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/02-identities/coordinates.md#L1` -- [V] phi^n in the {1, sqrt5} basis
     why: Matched on 'rational'; refers to Z[phi] basis representation, not unit fraction sums.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L109` -- 3. Math concepts (perused, one line + provenance)
     why: Matched on 'sum' and 'distinct'; generic mathematical vocabulary, no connection to decomposition.

## 026. Positive lower density of large prime gaps

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** For fixed C>0, positive proportion of consecutive prime gaps exceed C log p. Answers Erdős-Prachar on lower density of indices where p_n/n increases.
- **CASLO frame:** No shared object with the owner's framework. Prime-gap growth is number-theoretic; CASLO's 'asymptotic density phi^{-k}' is the Perron-Frobenius eigenvector of the Fibonacci transfer matrix.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/AI_MODEL_LOGIC.md#L98` -- 7. Coupling Priority Rules
     why: Matched on 'lower'; no connection to prime gaps or asymptotic density.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L223` -- Operator discipline (recorded)
     why: Matched on 'logarithm'; refers to log_phi rapidity coordinate, not prime-gap growth.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XV_FED_MEMORY_GRC.md#L194` -- Proposition V — Bit pathology: the highest cell grows logarithmically, and the runway is n
     why: Matched on 'logarithm'; register bit-width growth in CASLO, not number-theoretic density.

## 027. Potential integral density on curve character varieties

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** For smooth curves and rank r, integral points on SL_r character varieties become Zariski dense, allowing quasi-unipotent boundary monodromy over number fields.
- **CASLO frame:** No shared object with the owner's framework. Character varieties are representation spaces of curve fundamental groups; CASLO uses Z[phi] fibbinary lattices without representation theory.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L9` -- §0  Compaction-Survival Protocol — read this first
     why: Matched on 'algebraic' (algebraic recurrence/order), not character varieties or monodromy.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L163` -- 8. Performance (Sec 1, 4; pp. 4, 62-64)
     why: Matched on 'curve' (error graph) and 'dense' (surface code layout); quantum-computing, not algebraic geometry.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L645` -- §34  Scalographic Tensor — the unification (thesis cross-walk)
     why: Matched on 'algebraic'; algebraic recurrence order, unrelated to varieties or monodromy.

## 028. Uniformly bounded components of Gaussian-prime graphs

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Gaussian moat conjecture: no infinite walk through distinct Gaussian primes has uniformly bounded steps. Components of Gaussian-prime graph are uniformly bounded in size.
- **CASLO frame:** No shared object with the owner's framework. Gaussian primes are complex integers Z[i] studied via graph theory. CASLO uses Z[phi] fibbinary lattices, not prime graphs.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L451` -- 4.3 Axis 2 — shell-index hand: `log_phi` rapidity, density `phi^{-k}`
     why: Matched on 'components' (state space connectivity) and 'bounded'; unrelated to Gaussian primes.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L645` -- §34  Scalographic Tensor — the unification (thesis cross-walk)
     why: Matched on 'components'; unrelated to Gaussian primes or graph theory.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L89` -- C. Process gates — how to work
     why: Matched on 'graph' and 'bounded'; generic vocabulary, no mathematical connection.

## 029. Primitive roots for every admissible integer base

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Artin primitive-root conjecture: for every integer a (not -1 or square), infinitely many primes have a as primitive root, density ≥ c_a x/(log x)^2 in (x,2x).
- **CASLO frame:** No shared object with the owner's framework. Primitive roots are multiplicative orders in finite fields. CASLO concerns Fibonacci recurrence, Zeckendorf decomposition, Z[phi] lattice structure.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Matched on 'integer bases' (positional notation) and 'roots' (equation roots); not number-theoretic roots.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L570` -- THE LINKED BUILD — end state at the top, first action at the bottom
     why: Matched on 'integer' (integer arithmetic); unrelated to Artin's conjecture.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L352` -- 3.1 Binet lifts each lit shell to a Z[phi] coordinate
     why: Matched on 'roots' (eigenvalues) and 'integer'; no connection to finite-field orders.

## 030. Modularity of elliptic curves over imaginary quadratic fields

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Modularity conjecture: every elliptic curve over imaginary quadratic fields is modular, with matching local parameters at every place (residue characteristic).
- **CASLO frame:** No shared object with the owner's framework. Elliptic curves/modularity conjecture are algebraic-geometry results on automorphic forms and Galois representations. CASLO is deterministic Z[phi] algebra on FPGA.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/CAS_LUT_PIPELINE.md#L243` -- 8. Equation-to-Routing Map (Master Table)
     why: Matched on word fragments 'ell' and 'mod'; no mathematical connection to elliptic curves or modularity.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Matched on 'ell' and 'ic' fragments; extremely weak, no connection.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L435` -- 4.1 Axis 0 — master hand: `A^n` and the global period
     why: Matched on 'mod' and 'ic' fragments; no connection to modularity conjecture.

## 031. Uchida’s conjecture for open homomorphisms of Galois groups

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Every continuous open homomorphism between Galois groups of solvably closed Galois extensions of number fields comes from a unique equivariant field embedding. No kernel restriction or compatibility assumption needed.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `/mnt/c/Users/casma/_master_workflow_/docs/boolean-zeckendorf-notes.md#L315` -- 
     why: Mentions Galois σ: φ↔ψ as one involution in parallel structure (Boolean/lattice/arithmetic/hyperbolic/hardware layers). Used as ONE automorphism of Q(φ) ring, not Galois group theory or field extension homomorphisms.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L1` -- Transfer Matrix as LUT Fabric — Synthesis
     why: Transfer matrix [[1,1],[1,0]] used in tight-binding classical model context. Not Galois-theoretic; confounds two meanings of 'transfer matrix' across different mathematical domains.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `/mnt/c/Users/casma/_master_workflow_/phi_generator.py#L109` -- 
     why: Galois conjugate map a+bφ → (a+b) - bφ implemented as Z[φ] ring operation. Named correctly but used only for coordinate arithmetic, not group homomorphisms or field embeddings.
