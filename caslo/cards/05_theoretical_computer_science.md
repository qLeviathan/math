# Theoretical computer science -- OpenAI result families in CASLO framing

Levels: 0 none, 1 words, 2 analogy, 3 shared object, 4 direct use. Final levels >= 2 were confirmed by an adversarial verifier; unverified claims are capped at 1.

## 102. The Unique Games Conjecture and optimal approximation thresholds

- **Vetting:** 5 manuscript(s); Lean scope note; 3 in formalization.yaml; 0 revised; reasoning summary reasoning_traces/basic-semidefinite-threshold-np-hardness.pdf.
- **Plain:** The Unique Games Conjecture proves NP-hardness of approximating maximum cut and vertex cover via polynomial-time reductions from 3SAT to constraint satisfaction problems with unique labels.
- **CASLO frame:** No shared object with the owner's framework.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L753` -- 6.3 Scalogram corollary
     why: Matched on 'optimization'; CASLO uses optimization in the sense of cost functions on the cascade lattice (shell structure). UGC uses optimization in complexity-theoretic approximation ratios. Different mathematical objects.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/WIKI.md#L48` -- 2. Hard Constraints
     why: Matched on 'threshold'; CASLO's thresholds are Fibonacci shell indices (cutoffs on register size W). UGC's thresholds are approximation ratios (inapproximability factors). Vocabulary only.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/AI_MODEL_LOGIC.md#L9` -- 1. Purpose
     why: Matched on 'decision'; CASLO makes bit decisions on which Fibonacci shells to activate. UGC proves NP-hardness of decision problems. No shared computational model.

## 103. Exact derandomization of logarithmic space: $\mathsf L=\mathsf{RL}=\mathsf{BPL}$

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Derandomization resolves L = RL = BPL by converting randomized polynomial-time logarithmic-space machines into deterministic deciders with explicit polynomial running-time bounds.
- **CASLO frame:** No shared object with the owner's framework.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Matched on 'transfer matrix', 'space', 'deterministic', 'time'. CASLO's transfer matrix is A = [[1,1],[1,0]] for Fibonacci generation. Family 103 uses transfer matrices for state-space derandomization. Same vocabulary, different objects.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L692` -- 6.1 Closure of the two-register basis
     why: Matched on 'deterministic computation'; both discuss deterministic algorithms. CASLO: deterministic Fibonacci recurrence on registers. Family 103: deterministic simulation of randomized log-space Turing machines. Different computational models.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Matched on 'space'; CASLO's 'space' is the W-bit shell register in log-space. Family 103's 'space' is logarithmic-space computation (tape length). Homonyms.

## 104. Quasipolynomial algorithms for mean-payoff, stochastic and parity games

- **Vetting:** 4 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Quasipolynomial algorithms compute exact values and optimal strategies for mean-payoff games, stochastic games, and parity games in deterministic 2^O((log L)^2) time.
- **CASLO frame:** No shared object with the owner's framework.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L203` -- 9. Open Directions (Sec 1.2; pp. 11-12)
     why: Matched on 'theory', 'computation'; both use these words. CASLO: computation via Fibonacci recurrence. Family 104: game-theoretic algorithms. Different domains.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/WIKI.md#L48` -- 2. Hard Constraints
     why: Matched on 'computation', 'parity'; CASLO's 'parity' is (-1)^n (Cassini parity, orientation bit). Family 104's 'parity' is game constraints. Different mathematical objects.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L398` -- 3.3 The centroid moment M is a third orthogonal projection
     why: Matched on 'strategy'; CASLO's strategies are cascade rewrite rules (R1, R3). Family 104's strategies are game-theoretic positional strategies. Vocabulary only.

## 105. Perfect completeness for 2-to-1 games

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** 2-to-1 Games Conjecture: it is NP-hard to distinguish satisfiable 2-to-1 games from games with value at most delta, on explicit unweighted instances with every right label having exactly two preimages.
- **CASLO frame:** No shared object with the owner's framework.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/BOOLEAN_PATHING.md#L138` -- 6. The empirical floor (2026-06-01, post-mode-implementation)
     why: Matched on 'perfect'; CASLO: perfect reconstruction of cascade state from the register. Family 105: perfect completeness in hardness proofs. Different uses.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L688` -- 6. Basis Closure, Caveat, and Scalogram Corollary
     why: Matched on 'completeness'; CASLO: computational completeness of embedding clock basis. Family 105: perfect completeness in hardness reduction. Different meanings.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Matched on 'constraint'; CASLO: constraints from the NO HASH/NO MULTIPLY rules. Family 105: constraint satisfaction problems. Different constraint classes.

## 106. Hardness of coloring three-colorable graphs

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Hardness of coloring three-colorable graphs: for every fixed delta in (0, 1/3), it is NP-hard to distinguish three-colorable graphs from those with no independent set of size delta*n.
- **CASLO frame:** No shared object with the owner's framework.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L398` -- 3.3 The centroid moment M is a third orthogonal projection
     why: Matched on 'independent set'; CASLO: linearly independent scalars (n_q_psi, M) in the coordinate system (Lemma 3.B). Family 106: graph-theoretic independent sets (vertices with no edges). False match: different fields (linear algebra vs. graph theory).
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L129` -- 4. Engineering concepts (perused, one line + provenance)
     why: Matched on 'graph', 'constraint', 'set'; CASLO's graphs are data-dependency DAGs. Family 106's graphs are vertices and edges. Different graph types.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Matched on 'constraint'; CASLO: hard constraints (NO HASH, NO MULTIPLY, etc.). Family 106: constraint satisfaction in hardness reductions. Vocabulary only.

## 107. Matrix multiplication with exponent at most 9/4

- **Vetting:** 3 manuscript(s); Lean scope note; 3 in formalization.yaml; 0 revised.
- **Plain:** Matrix multiplication exponent: proves omega <= 9/4 over complex numbers; gives O_epsilon(n^(9/4+epsilon)) arithmetic operations and n^2+o(1) for rectangular multiplication in characteristic zero.
- **CASLO frame:** No shared object with the owner's framework.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Matched on 'operations', 'bounds'; CASLO's operations are integer ADD/SUB/shift on registers (no multiply). Family 107 bounds matrix multiplication complexity. Different operation sets.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/WIKI.md#L48` -- 2. Hard Constraints
     why: Matched on 'operations', 'arithmetic'; CASLO's arithmetic is addition on Fibonacci shells, NO MULTIPLY. Family 107 optimizes matrix multiplication exponent. Opposite constraints.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L85` -- S6. The state register advance is the ONLY arithmetic the fabric ever does
     why: Matched on 'multiplication', 'arithmetic'; CASLO uses 2x2 transfer matrix A = [[1,1],[1,0]] applied iteratively (not multiplied as matrices). Family 107 optimizes matrix multiplication. No shared object.

## 108. A cubic permanent–determinant lower bound

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves that representing an n×n permanent using determinants of affine-linear matrices requires matrix size at least Ω(n³), even allowing limits and coefficientwise operations.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Keyword match on 'determinant', 'matrix', '^3', 'fixed'; actual content is transfer matrix A^n = [[F(n+1), F(n)], [F(n), F(n-1)]] from linear recurrence theory, not computational complexity
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Glossary entry sharing word 'determinant' but in context of transfer-matrix determinant, not algebraic complexity bounds
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: Lucas-aperture bridge relates φ/ψ operators; no connection to permanent-determinant complexity bounds

## 109. Integer multiplication below $n\log n$

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Gives a deterministic algorithm multiplying two n-bit integers in O(n log n)^(1-κ) time with κ=2^-182, disproving Schönhage–Strassen conjecture on a fixed multitape Turing machine.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `CASLO_CLAUDE_DESIGN_WIRING_PROMPT_v0.1.md#L1` -- 
     why: Keyword match on 'algorithm', 'recurrence', 'computation'; owner uses linear recurrences (F(n), L(n)) for token embedding, family uses integer multiplication algorithms
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_X_UNIFIED_LM.md#L1` -- ELEMENTS, Book X — the unified language model: one law, one build
     why: Keyword match on 'algorithm'; scholia document schematic, not fast integer multiplication
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Glossary shares word 'algorithm' only

## 110. Optimal-order randomized k-server on arbitrary metrics

- **Vetting:** 2 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Establishes O(log²(k+1)) competitive ratio for randomized k-server on every metric space, matching worst-case lower bounds; one policy serves all oblivious request sequences.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Keyword match on 'algorithm', 'online', 'state transitions'; owner's CASLO processes tokens sequentially (online), family is online competitive algorithms on metric spaces
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XV_FED_MEMORY_GRC.md#L259` -- Proposition VII — The capture is faithful; the source is not byte-stable.
     why: Match on 'algorithm', 'online'; no shared mathematical structure with k-server competitive analysis
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L481` -- 4.6 Non-commensurability — the joint odometer has no shared modulus
     why: Keyword match on 'algorithm', 'state'; no connection to metric-space competitive analysis

## 111. One-sample matroid prophet inequalities against an almighty adversary

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** For any finite matroid, proves a constant-competitive prophet inequality using one sample per element, even against an adversary seeing all samples, values, and the algorithm's random seed.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: No mathematical overlap; glossary shares no relevant entries with matroid prophet inequalities or online stochastic optimization
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L481` -- 4.6 Non-commensurability — the joint odometer has no shared modulus
     why: Keyword match on 'online' only; owner system is online in token-processing sense, not in online optimization game sense
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_X_UNIFIED_LM.md#L1` -- ELEMENTS, Book X — the unified language model: one law, one build
     why: No connection between matroid independence systems and CASLO architecture

## 112. Beyond the square-root exponent for depth-three circuits

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Constructs a polynomial-time decidable language whose n-bit membership requires 2^ω(√n) gates in unbounded-fan-in OR-AND-OR circuits, crossing the square-root threshold for explicit depth-three lower bounds.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XV_FED_MEMORY_GRC.md#L229` -- Proposition VI — The engine's three-key law reproduced every recorded winner, and the host
     why: Keyword match on 'depth', 'bound', 'circuit'; owner uses LUT4 circuits and pipeline depth, family proves circuit lower bounds for depth-3 OR-AND-OR
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Glossary entry shares 'circuit', 'depth', 'lower', 'bound'; different problem domains
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/WIKI.md#L1` -- Leviathan AI / (phi,psi)-Mechanics — Consolidated Reference (WIKI)
     why: Keyword match on 'depth', 'circuit', 'gates'; WIKI discusses LUT4 computation model, not Boolean circuit lower bounds

## 113. Approximate counting and entropy of perfect matchings

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Gives an FPRAS for counting perfect matchings in arbitrary graphs with exact zero detection; proves the perfect-matching entropy conjecture bounding maximum entropy of matching distributions.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: High lexical score on 'entropy', 'matching', 'counting'; owner uses entropy rate = ln(phi) as algorithmic growth metric, family uses Shannon entropy of matching probability distributions
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/stall_predicate.md#L1` -- stall predicate (S_PSI_RETRACT trigger)
     why: Keyword match on 'entropy'; stall predicate uses entropy-like concepts but for control flow, not combinatorial enumeration
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_X_UNIFIED_LM.md#L14` -- NOMENCLATURE
     why: Match on 'matching'; nomenclature entries use term 'matching' in CASLO context (pattern matching), not graph-theoretic matching

## 114. Approximate counting of common integer polymatroid bases

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Gives a fully polynomial randomized approximation scheme for counting common integer bases of two integral polymatroids supplied by rank-value oracles, with binary-encoded capacities.
- **CASLO frame:** No shared object with the owner's framework. Family 114 addresses matroid-basis enumeration via abstract oracle interfaces; CASLO addresses deterministic state reduction via Zeckendorf integer decomposition.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L505` -- 5.1 The generating basis
     why: Match on 'basis' and 'integer': CASLO T3 defines 'generating basis' as coordinate set {R(t), R(t-1), operators}, not matroid bases. Semantic difference: coordinate compression vs. combinatorial independence.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Match on 'constraint' and 'integer': describes tight-binding model integer-only arithmetic. Not polymatroid-specific.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Glossary: matches on 'basis' and 'bound'. No substantive overlap with FPRAS approximation schemes.

## 115. Sampling and counting contingency tables with arbitrary margins

- **Vetting:** 2 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Exact uniform sampling and approximate counting of nonnegative integer contingency tables with prescribed row and column sums; no positivity or dimension assumptions.
- **CASLO frame:** No shared object. Family 115 counts contingency tables (nonnegative integer matrices constrained by margins); CASLO uses transfer matrix A as deterministic dynamical operator on Fibonacci lattices. Both mention matrices and integer constraints, but solve entirely different problems.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Match on 'matrix' and 'integer constraint': describes A as 2×2 integer matrix. But A is a deterministic operator, not a constraint-satisfaction object for table enumeration.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L144` -- 6. The twist — why this is a *Möbius* ribbon, not a cylinder
     why: Discusses matrix structure (Möbius ribbon). Lexical match on 'matrix', 'row', 'column' but semantically unrelated to contingency tables.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Match on 'constraint', 'sum', 'column'. No algorithmic overlap with FPRAS sampling.

## 116. Uniform black-box noncommutative identity testing across characteristics

- **Vetting:** 3 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Constructs polynomial-dimensional matrix tuples deterministically that detect every nonzero division-free noncommutative formula over any field of given characteristic.
- **CASLO frame:** No shared object. Family 116 tests algebraic identities via matrix substitution; CASLO bans division and multiplication, operates on Zeckendorf integers. The phrase 'division-free' appears in CASLO (parity via popcount & 1) but addresses bit-manipulation, not formula testing.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/jun_11_2026/zeck_kernel.py#L537` -- readout
     why: Lexical match: 'division-free' in comment. But context is Cassini parity readout (popcount & 1), not noncommutative formula testing.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/WIKI.md#L48` -- 2. Hard Constraints
     why: NO DIVIDE constraint header. Both prohibit division, but for orthogonal reasons (CASLO: hardware efficiency on FPGA; Family 116: algebraic formula structure).
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/jun_11_2026/superfunction.py#L1194` -- pairFold
     why: Match on 'tuple' only. No relevance to division-free formula testing.

## 117. Uniform sparsest cut: hardness and semidefinite gaps

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves NP-hardness of uniform sparsest cut within any fixed constant factor and constructs Goemans–Linial SDP integrality gaps of order ≥ √(log n)/(log log n)³.
- **CASLO frame:** No shared object. Family 117 addresses graph-cut optimization hardness and SDP relaxation gaps; CASLO addresses integer-state dynamics on a Fibonacci lattice. Both mention 'gap', but context is entirely different (SDP integrality vs. φ⁻¹ approximation).
- **Verdict:** WORDS
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/jun_11_2026/superfunction.py#L1313` -- hypergraphExport
     why: Lexical match on 'graph' and 'gap'; function hypergraphExport. Not relevant to sparsest-cut hardness.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L459` -- 4.4 Axis 3 — annealing hand: `13C/32`, period 5, integer-subtraction reload
     why: Match on 'approximation' and 'gap': 13C/32 ≈ φ⁻¹·C as additive register approximation. Context (clock budget) distinct from SDP gaps.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/jun_11_2026/superfunction.py#L1328` -- memoryGraphExport
     why: Lexical match on 'graph' and 'gap'; memoryGraphExport. No relevance to NP-hardness or SDP.

## 118. Bin packing and unbounded configuration-LP gaps

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Disproves the modified integer round-up conjecture by constructing bin-packing instances with arbitrarily large additive gaps between configuration-LP and integral optimum.
- **CASLO frame:** No shared object. Family 118 addresses bin-packing approximation gaps (optimization hardness); CASLO addresses state register evolution under recurrence constraints. The word 'additive gap' appears in both but domains are disjoint.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L459` -- 4.4 Axis 3 — annealing hand: `13C/32`, period 5, integer-subtraction reload
     why: Match on 'approximation' and 'additive gap': theorem 4.4 describes 13C/32 as additive approximation. But this is clock budgeting, not packing.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L180` -- 7. Why one rail is not enough — the two coordinates of a ribbon
     why: Lexical match on 'additive' and 'gap'. Context is geometric (Möbius ribbon structure), not optimization hardness.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L109` -- 3. Math concepts (perused, one line + provenance)
     why: Match on 'additive gap' in concepts section. No substantive connection to bin packing.

## 119. The Courtade–Kumar and Hellinger conjectures

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves Courtade–Kumar and Hellinger conjectures: among Boolean functions of independent bits, a single coordinate maximizes mutual information after noise; entropy-contraction bounds follow.
- **CASLO frame:** Transfer matrix A with Perron-Frobenius eigenvalue φ provides information-theoretic framework paralleling Family 119. Both use eigenvalue φ to define entropy-rate (CASLO: s = ln(φ) per A-step), both employ PF eigenvector for steady-state structure (CASLO: bit-density φ⁻ᵏ at shell k), both dimension-reduce to dominant eigenspace.
- **Verdict:** WORDS
  1. level 1 (draft 3, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L67` -- S5. Perron-Frobenius vector = steady-state bit-density operator
     why: Perron-Frobenius vector v_PF = (φ, 1) defines bit-density φ⁻ᵏ. Both use PF eigenvector for information-theoretic structure: Courtade-Kumar via coordinate selection; CASLO via shell-activity ordering.
     ruling: The owner window (L193 on) reads A as a tight-binding / integrability model: L_n = tr(A^n), the Binet closed form, recurrence periods mod F(W+2), and a transfer-matrix MPS. It says explicitly 'no thermalization' and 'deterministic, no probabilistic contraction', and the same doc says A is hyperbolic
  2. level 1 (draft 3, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Transfer matrix A as central operator; L-channel = tr(A^n) non-local order parameter. Both use eigenvalue decomposition (A = P·D·P⁻¹, D=diag(φ,ψ)) to reduce information dynamics. Shared object: Perron-Frobenius eigenvalue φ in information bounds.
     ruling: The owner window (L193 on) reads A as a tight-binding / integrability model: L_n = tr(A^n), the Binet closed form, recurrence periods mod F(W+2), and a transfer-matrix MPS. It says explicitly 'no thermalization' and 'deterministic, no probabilistic contraction', and the same doc says A is hyperbolic
  3. level 1 (draft 3, REJECT) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: Spine equation s = ln(φ) entropy-rate. Both 119 (mutual information contraction) and CASLO (ln(φ) per A-step) treat entropy-rate via dominant eigenvalue. Shared identity: logarithm of Perron-Frobenius eigenvalue as information metric.
     ruling: The owner note states the topological-entropy theorem: s = lim (1/n) ln Omega(n) = ln lambda_max(A) for a constrained system. In words, the log growth rate of the number of allowed words equals the log of the spectral radius. 119 has none of these objects: no constrained system, no adjacency matrix,

## 120. Almost-linear-time exact matching and prescribed-degree factors in general graphs

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Gives randomized polynomial-time algorithm for maximum-cardinality graph matching in (n+m)^{1+o(1)} time with 2/3 success probability, extending to prescribed-degree spanning subgraphs.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Matching algorithms operate on graph adjacency structures via randomized walks; CASLO operates on Zeckendorf shell lattice via transfer matrix A=[[1,1],[1,0]]. No shared mathematical object. Generic 'complexity' + 'algorithm' vocabulary match only.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L144` -- 6. The twist — why this is a *Möbius* ribbon, not a cylinder
     why: Matching polytope structure unrelated to fibbinary bit-ribbon topology or Fibonacci lattice.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: Entropy-rate law uses ln(phi) as spectral gap of transfer matrix A. Matching algorithms do not explicitly use this eigenvalue structure in their analysis.

## 121. Almost-linear approximation of edit distance

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Gives uniform randomized (1+ε)-approximation to unit-cost edit distance between strings of total length N in N^{1+o(1)} expected time with 2/3 success probability.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Both involve algorithmic complexity analysis and time bounds, but edit distance operates on string metrics with dynamic programming; CASLO operates on Fibonacci lattice with transfer matrix iteration. Shared vocabulary (polynomial time, approximation) but distinct mathematical objects.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/01_recurrences/fibonacci.md#L1` -- Fibonacci recurrence
     why: Edit distance uses string-length dependent recurrence (Wagner-Fischer DP table), but not Fibonacci recurrence F(k)=F(k-1)+F(k-2). Generic 'recurrence relation' structure only; no shared identity.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L36` -- S2. The F-channel and L-channel ARE the eigenspaces
     why: Edit distance approximation does not use eigenspace projection or spectral decomposition of any specific transfer matrix.

## 122. Quantitative trace-reconstruction bounds with a uniform decoder

- **Vetting:** 3 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Worst-case binary string reconstruction from independent deletion traces requires n^{Ω(log log n)} samples at fixed deletion probability; quasipolynomial reconstruction algorithm with uniform decoder for known rational retention probabilities.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Trace reconstruction uses information-theoretic entropy bounds; CASLO uses ln(phi) as spectral entropy rate of transfer matrix A. Both involve logarithmic complexity, but on different channels: deletion channel vs. eigenvalue spectral gap. Not shared object.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L562` -- 5.2 Channel inventory
     why: CASLO's 'channels' refer to F-channel and L-channel (Fibonacci/Lucas eigenspace projections), not information-theoretic deletion channels. Shared word 'channel' but distinct mathematical meanings.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/stall_predicate.md#L1` -- stall predicate (S_PSI_RETRACT trigger)
     why: Stall predicate involves psi (conjugate eigenvalue) of transfer matrix; trace reconstruction involves deletion-probability distributions. No overlap in mathematical objects.

## 124. Polynomial-time scheduling on three identical machines

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Deterministic polynomial-time algorithm for minimum-makespan scheduling of unit-length jobs with precedence constraints on three identical parallel machines; decides deadline feasibility exactly.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Scheduling uses dynamic programming on state space of 3-machine configurations. CASLO pipeline has Fibonacci-timed stages (LOAD(1)·DECOMPOSE(2)·COMPOSE(3)=F_2+F_3+...=32 cycles), but paper does not use Fibonacci numbers or golden-ratio eigenvalues. Generic 'algorithm', 'time', 'deterministic' vocabu
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/01_recurrences/fibonacci.md#L1` -- Fibonacci recurrence
     why: Scheduling problem solved via DP recurrence on makespan/deadline state, not Fibonacci recurrence F(k)=F(k-1)+F(k-2). Different recurrence structure.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L467` -- 4.5 Axis 4 — phase-register hand: latched `R`, period `~F(W+2)`, Markov boundary (Lemma L1
     why: CASLO's phase-register period ~F(W+2) uses Fibonacci timing as hardware constraint; scheduling period is artifact of 3-machine system, not Fibonacci sequence. No shared mathematical identity.

## 125. The metric k-median approximation threshold and recovery

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Deterministic polynomial-time (1+2/e+ε)-approximation for finite rational metric k-median with candidate facility set; proves optimal approximation threshold is 1+2/e assuming P≠NP.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: k-median clustering uses metric geometry and local-search approximation algorithms. CASLO uses metric distance in shell lattice [2,46] via Zeckendorf decomposition, not on continuous metric spaces. Approximation factor (1+2/e) is distinct from CASLO's deterministic 1.0-factor encoding (no approximat
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L481` -- 4.6 Non-commensurability — the joint odometer has no shared modulus
     why: CASLO's lattice cardinality F(W+2) and shell metric are on discrete Zeckendorf lattice; k-median operates on continuous metric spaces with facility-location structure. No shared mathematical object.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/03_zeckendorf/lattice_cardinality.md#L1` -- Lattice cardinality
     why: CASLO lattice cardinality relates to Fibonacci shell structure, not k-median facility placement.

## 126. Exponential semidefinite complexity of perfect matching

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves exponential positive semidefinite rank lower bounds 2^{Ω(n)} for odd-cut slack matrix of perfect matching polytope with any fixed positive shift; answers polynomial-size lift question negatively.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Both analyze structural properties via matrix-theoretic methods (PSD rank vs. transfer matrix eigendecomposition), but on different matrices: matching slack matrices vs. A=[[1,1],[1,0]]. Both prove bounds on matrix properties, but no shared specific identity or object. Shared category (matrix analys
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L144` -- 6. The twist — why this is a *Möbius* ribbon, not a cylinder
     why: Matching polytope structure and perfect-matching rank bounds unrelated to Möbius ribbon bit-encoding or Fibonacci polytope structure in CASLO.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/02_identities/cassini.md#L1` -- Cassini identity
     why: Cassini identity F(n-1)·F(n+1)−F(n)²=(-1)^n appears in determinant analysis of Fibonacci objects, not in matching polytope PSD rank analysis.

## 127. Average sensitivity of polynomial threshold functions

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves that degree-d polynomial threshold functions on the uniform Boolean cube have average sensitivity at most 8d√n, resolving the Gotsman–Linial conjecture for polynomial zeros with sgn(0)=1.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/BOOLEAN_PATHING.md#L189` -- 9. The strict-Boolean variant
     why: Mentions Boolean addressing and R1/R3 canonicalization, but refers to fibbinary register encoding, not polynomial threshold functions or average sensitivity on Boolean cubes.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/00_axioms/phi_squared.md#L1` -- phi squared
     why: Fundamental equation of golden ratio; no connection to polynomial degrees or Boolean cube sensitivity.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/stall_predicate.md#L1` -- stall predicate (S_PSI_RETRACT trigger)
     why: Boolean scheduling predicate in CASLO; unrelated to polynomial threshold analysis.

## 128. A factor-two approximation for shortest common superstring

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Gives a deterministic polynomial-time algorithm that for every finite family of strings produces a common superstring of length at most twice the optimum, with time polynomial in total encoded input size including symbol labels.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/LUT_FABRIC_LM_ALGORITHM.md#L1` -- LUT-Fabric Language Modeling Algorithm — Articulation
     why: Describes CASLO's LUT-fabric algorithm for language modeling; matches on 'algorithm' and 'deterministic' but addresses token sequence generation, not string superstring overlap.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XIII_ENERGY_ROUTING.md#L11` -- NOMENCLATURE
     why: Mentions greedy routing strategy; vocabulary overlap with greedy approximation but applied to energy routing, not string algorithms.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L1` -- Transfer Matrix as LUT Fabric — Synthesis
     why: Core CASLO transfer matrix; no connection to shortest common superstring problem.

## 129. Exponential state costs for two-way automata

- **Vetting:** 2 manuscript(s); Lean scope note; 2 in formalization.yaml; 0 revised.
- **Plain:** Proves exponential lower bounds on state complexity for complementing two-way nondeterministic finite automata and for simulating one-way nondeterministic automata by two-way deterministic ones, resolving the Sakoda–Sipser conjecture.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/CAS_LUT_PIPELINE.md#L62` -- 3. The LUT4 Cell
     why: Describes LUT4 cell complexity in CASLO pipeline; mentions 'complexity' and 'automata' but refers to logic fabric, not finite automata state bounds.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/zlogpi/zphi.py#L97` -- ZPhi
     why: State machine for Zeckendorf operations; matches on 'state' and 'automata' but implements Fibonacci representation, not automata complementation.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Cross-cutting insights on methodology; no connection to two-way automata or nondeterminism.

## 130. Exact Fourier transforms below $n\log n$

- **Vetting:** 2 manuscript(s); Lean scope note; 2 in formalization.yaml; 0 revised.
- **Plain:** Constructs a deterministic discrete Fourier transform algorithm achieving O(n(log n)^(1-δ)) operations for explicit δ=10⁻¹³ using exact complex arithmetic, unrestricted coefficients, and unit-cost logarithmic-word indexing.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/WIKI.md#L48` -- 2. Hard Constraints
     why: Lists hard constraints including NO FLOAT, NO MULTIPLY; family uses exact complex arithmetic but CASLO uses integer-only Zeckendorf, not Fourier circuits.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Glossary of operations; vocabulary overlap on 'operations' and 'circuit' but glossary covers CASLO operations, not FFT.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L467` -- 4.5 Axis 4 — phase-register hand: latched `R`, period `~F(W+2)`, Markov boundary (Lemma L1
     why: Describes phase-register timing; unrelated to Fourier transform arithmetic.

## 131. Rapid mixing of graph switches for every degree sequence

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Resolves Kannan–Tetali–Vempala conjecture: the lazy edge-switch Markov chain mixes in O(n⁸) time for every graphical degree sequence by analyzing spectral gap and second eigenvalue of the chain.
- **CASLO frame:** Both analyze mixing/dynamics via spectral gap. Owner: transfer matrix A=[[1,1],[1,0]] has eigenvalues φ,ψ with spectral gap √5. Family: degree sequence Markov chain mixing time governed by spectral gap λ₁−λ₂.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L137` -- A2. A^∞ has no fixed point — only the spectral gap matters
     why: Section A2 states 'A is hyperbolic (|φ|>1>|ψ|)' and 'only the spectral gap matters' for dynamics. Both family 131 and owner use spectral gap to bound mixing/dynamics behavior—same structure, different objects.
     ruling: The two texts share the words 'spectral gap' and 'mixing' but not the mathematical structure. In family 131 (build/sections/mixing.tex), the gap and the mixing belong to the same reversible stochastic kernel P_d. A Poincare inequality Var(f) <= 2n^2<f,Lf> gives gap >= 1/(24n^2 C(n,4)), and that give
  2. level 1 (draft 2, REJECT) `_master_workflow_/math/eigenvalue-geometry/04-hyperbolic/anosov-dynamical.md#L1` -- [V] Hyperbolic dynamics (Anosov)
     why: Analyzes A as hyperbolic automorphism with topological entropy = ln(φ); both works use eigenvalue properties for understanding mixing but in different dynamical systems.
     ruling: The owner note is the whole 8-line file. It says only that A on the 2-torus is a hyperbolic automorphism with stable/unstable manifolds and h_top = ln(phi). Grep finds no mixing, gap, convergence, correlation or measure anywhere in it, so the claim's 'both use eigenvalue properties for understanding
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L97` -- 0.2 Notation
     why: Defines φ, ψ as eigenvalues of A; mentions second-order Markov context R(t-1) but in state memory context, not Markov chain mixing time analysis.

## 132. A superquadratic separation of sensitivity and block sensitivity

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Constructs total Boolean functions f where block sensitivity bs(f)≥s(f)^α for fixed α>2, disproving the quadratic strengthening of the Sensitivity Conjecture. Sensitivity counts output-changing single-bit flips.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/WIKI.md#L595` -- 13.4 Lucas Zero Detection Rate
     why: Discusses Lucas Zero Detection Rate and error detection via bit flips; matches 'bit flip' vocabulary but analyzes error correction, not Boolean function sensitivity properties.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/AI_MODEL_LOGIC.md#L126` -- R50 R50 (Lucas Zero, 100%): Compute N_L(zeros) = Σ L(k) at every zero position. Any bit fl
     why: Rule R50 on Lucas Zero detects when bit flips create zeros; vocabulary overlap on 'bit flip' but applied to hardware error detection, not Boolean sensitivity analysis.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/BOOLEAN_PATHING.md#L189` -- 9. The strict-Boolean variant
     why: Boolean variant of address encoding using fibbinary; no connection to sensitivity gaps between s(f) and bs(f).

## 133. The computational complexity of Weisfeiler–Leman refinement

- **Vetting:** 4 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves that determining whether two graphs are equivalent under k-dimensional Weisfeiler-Leman refinement requires exponential time n^Ω(k), establishing tight computational lower bounds.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Both discuss matrices and lower bounds, but owner's transfer matrix [[1,1],[1,0]] and eigenvalue phi analyze linear recurrences, not graph equivalence refinement.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Both mention dimension and complexity, but in different frameworks: family 133 uses refinement dimension for graph coloring; owner uses shell lattice dimension for Zeckendorf encoding.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Both discuss lower bounds and complexity, but owner's work bounds register width and cascade depth in LUT fabric, not refinement time.

## 134. Generalized star height at most three

- **Vetting:** 3 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves every regular language over a finite alphabet can be expressed with generalized regular expressions containing at most three nested Kleene stars, solving the uniform star-height boundedness problem.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L467` -- 4.5 Axis 4 — phase-register hand: latched `R`, period `~F(W+2)`, Markov boundary (Lemma L1
     why: Both discuss finite structures and clocks, but family 134 addresses finite monoid computations and star-height bounds via affine updates; owner's clock is a phase register operating on Fibonacci lattice.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L20` -- NOMENCLATURE
     why: Both mention finite structures and words, but owner's fibbinary words (no adjacent 1s) are Zeckendorf encodings, not regular-language word construction.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: Both use complement operations, but family 134 complements over free monoids; owner's phi/psi bridge is a De Morgan duality in the Z[phi] ring algebra.

## 135. Homogeneous depth-five lower bounds for iterated matrix multiplication

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Establishes n^Θ(√n) gate-complexity lower bounds for homogeneous depth-five circuits computing the (1,1) entry of products of n independent n×n variable matrices.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L36` -- S2. The F-channel and L-channel ARE the eigenspaces
     why: Both discuss transfer matrices and eigenvalues, but family 135 analyzes arithmetic-circuit depth complexity for matrix multiplication; owner's transfer matrix A=[[1,1],[1,0]] and eigenspaces phi/psi encode Fibonacci/Lucas recurrence structure, not circuit arithmetic.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Both mention lower bounds and matrix structure, but owner's foundational lemmas bound the state space via Fibonacci cardinality F(W+2), not arithmetic-circuit gate count.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/AI_MODEL_LOGIC.md#L148` -- 11. Operational Checklist
     why: Both discuss gates and products, but owner's operational checklist is a decision tree for per-tick channel coupling, not circuit complexity bounds.

## 136. A quasilinear PCP theorem for PPAD

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves the quasilinear PCP-for-PPAD conjecture: an End-of-Line instance of length N reduces to circuit constraints of length N(log N)^O(1) such that any nearly-satisfying rational assignment yields a solution.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L718` -- 6.2 The transient-multiplicity caveat (Lemma L13)
     why: Both discuss constraint satisfaction and verification, but family 136 is computational-complexity PCP theory; owner's transient-multiplicity caveat is a hardware scheduling constraint for cascade operations.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/BOOLEAN_PATHING.md#L189` -- 9. The strict-Boolean variant
     why: Both mention verification, but family 136 verifies constraint satisfaction for PPAD completeness; owner's Boolean pathing is a strict-Boolean variant for routing cascade decisions.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L21` -- 1. The system in plain language
     why: Both discuss deterministic reductions and gates, but family 136 reduces PPAD instances to circuit verification; owner describes CASLO as a deterministic natural-language transducer, not an NP/PPAD solver.

## 137. One-tape time simulation in two-fifths-power space

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Shows that deterministic one-tape Turing machines can be simulated in O(T^{2/5} polylog(T)) space, improving the square-root exponent for space-time tradeoffs.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Both discuss space and simulation, but family 137 optimizes Turing-machine tape-access complexity; owner's foundational lemmas bound CASLO state-space via Fibonacci lattice, not tape simulation.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XV_FED_MEMORY_GRC.md#L293` -- HOW THE TWO MEMORIES JOIN
     why: Both discuss memory and machine simulation, but family 137 trades time for Turing-machine space; owner's memory-join is about two-register architecture in CASLO.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Both mention space and machines, but family 137 analyzes Turing-machine complexity; owner's cross-cutting insights document CASLO's deterministic inference engine, not universal computation.

## 138. Subset Sum in $O(2^{0.49n})$ time

- **Vetting:** 2 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Gives a randomized worst-case algorithm for Subset Sum in O(2^{0.49n}) time on polynomial-bit words, improving the brute-force exponential baseline.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Both mention combinatorial algorithms and exponential bounds, but family 138 optimizes NP-complete Subset Sum via meet-in-the-middle; owner's glossary entry D_k is a counting function for quantum error-correction TLF bounds, unrelated to combinatorial search.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L232` -- 10. Time is recursion depth is rapidity
     why: Both discuss exponential growth, but family 138 uses exponential time for worst-case search; owner's rapidity discussion frames exponential growth via phi^n Fibonacci eigenvalue scaling in the Z[phi] ring.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/LUT_FABRIC_LM_ALGORITHM.md#L172` -- §3.6  `commit_gate` — (addr_canonical, candidates) → commit | reject
     why: Both mention algorithms, but family 138 is a combinatorial search algorithm; owner's commit_gate decides cascade routing deterministically, not probabilistic subset selection.

## 139. Subpolynomial query complexity for log-concave sampling

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** For C2 potentials with known minimizer and Hessian between I and 2I, sampling to total-variation distance 1/10 requires only C_ε d^ε first-order queries for every ε > 0, achieving subpolynomial oracle complexity.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L1` -- Transfer Matrix as LUT Fabric — Synthesis
     why: Both invoke eigenvalue-driven iteration: transfer matrix A=[1,1;1,0] with eigenvalues φ,ψ iterates like gradient descent with dimension-dependent complexity, but the specific objects (Fibonacci sequences vs Hessian-driven sampling) diverge.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Both enforce conservation laws (Axiom A4: I-1 conservation; Family 139: convexity + Hessian bounds); both scale complexity by dimension d, but the conserved quantities differ (Fibonacci sum vs potential function gradient).
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L489` -- 4.7 The deepest cycle — `I-1` conservation as the period-1 hand
     why: Theorem 4.7 states I-1 invariant under every operator: Sum F(k)R[k]=const. Family 139 uses analogous invariants (Hessian positive-definite, minimizer fixed) to bound iterations, but apply to fundamentally different domains.

## 140. Memory–sample lower bounds for noiseless Gaussian regression

- **Vetting:** 6 manuscript(s); Lean scope note; 5 in formalization.yaml; 0 revised.
- **Plain:** Learners with Ad² persistent bits across distinct measurement blocks need Ω(d log(1/ε)) noiseless Gaussian samples to achieve angular error ε≤1/10 at probability 2/3, proving memory-sample lower bound.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L562` -- 5.2 Channel inventory
     why: Section 5.2 Channel inventory enumerates information-bearing projections of state. Family 140 bounds information in finite messages from measurements. Shared vocabulary (projections, information, message bounds) but distinct substrates: register projections vs Gaussian measurement messages.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L435` -- 4.1 Axis 0 — master hand: `A^n` and the global period
     why: Section 4.1 Master hand invokes period F(W+2) and entropy rate ln(φ) per clock. Family 140 uses entropy H(W) to bound information growth. Both scale by dimension, but CASLO's entropy is symbolic (ln φ per register bit) vs information H in nats.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L212` -- 10. Glossary
     why: Glossary section cites bounds and lower-bound arguments. Family 140 is a memory-sample lower-bound proof. Shared terminology (lower bounds, sample complexity, dimension scaling d) but operate on distinct mathematical models (Gaussian vs fibbinary).

## 141. Existential–universal real sentences in the counting hierarchy

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Existential theory of the reals (and more generally, existential–universal real sentences) can be decided at a fixed level of the counting hierarchy, even when polynomials are given by arithmetic circuits.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/psi_retract_operator.md#L1` -- psi_retract operator
     why: Psi_retract operates on Z[φ] ring with shell register R over lattice [2,46]. Family 141 studies decidability over real numbers using polynomial rings Z[x]. Shared vocabulary (ring, real/algebra, decidability) but objects are disjoint: Z[φ] Fibonacci lattice vs R and arithmetic circuits.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L352` -- 3.1 Binet lifts each lit shell to a Z[phi] coordinate
     why: Section 3.1 Binet lifts each shell to Z[φ] coordinate (a+bφ). Family 141 studies existential/universal quantification over reals and polynomial rings. Both invoke algebraic rings and coordinates, but Binet's lift is deterministic projection (no quantifiers) vs decidability under quantifiers.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Foundational lemmas state all cascades preserve I-1 (sum conservation axiom A4). Family 141 proves decidability via hierarchy levels. Both involve algebraic structure and hierarchy, but CASLO's hierarchy is shell index [2,46] (finite, deterministic) vs counting hierarchy (infinite, oracle-based).

## 142. Deterministic polynomial factorization over prime fields

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Deterministic polynomial-time algorithm factors every nonzero polynomial f∈F_p[x] completely (with multiplicities) using bit operations polynomial in (deg f+1) log p, without randomness or GRH.
- **CASLO frame:** Zeckendorf decomposition (n = Σ F(k)·R[k], fibbinary normal form) parallels irreducible factorization of polynomials over F_p: both canonicalize complex objects into unique indecomposable constituents. Both achieve normal form in polynomial time.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/jun_11_2026/zeck_kernel.py#L234` -- cascade
     why: cascade() function applies rewrite rules R1 (F(k)+F(k+1)=F(k+2)) and R3 (2F(k)=F(k+1)+F(k-2)) to reach canonical Zeckendorf form uniquely. Family 142 factors polynomials to unique irreducibles. Both are unique normal forms, both decidable in polynomial time, both decompose complex objects into indec
     ruling: The only thing the two texts share is a meta-property: a deterministic procedure that returns a unique canonical form. That is as generic as 'algebra' or 'a proof', so it does not reach level 2. The mathematical structures differ. Owner (zeck_kernel.py L234-373): an additive multiset rewriting syste
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/02_identities/lucas_from_zphi.md#L1` -- Lucas from Z[phi] coordinates
     why: Lucas from Z[φ] coordinates recovers unique representation. Family 142 recovers irreducibles uniquely from F_p[x]. Shared structure: ring arithmetic supports unique factorization (Zeckendorf over Z[F_k]; irreducibles over F_p[x]), but rings are distinct.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L348` -- 3. The State is a Z[phi] Pair
     why: Section 3: State is a Z[φ] pair (a+bφ) at each shell. Family 142 uses polynomial ring F_p[x] and its factorization structure. Both employ ring coordinates to decompose state (Z[φ]-pairs for Fibonacci; F_p[x]-polynomials for fields), but the rings and decomposition strategies diverge.
