# Combinatorics -- OpenAI result families in CASLO framing

Levels: 0 none, 1 words, 2 analogy, 3 shared object, 4 direct use. Final levels >= 2 were confirmed by an adversarial verifier; unverified claims are capped at 1.

## 155. A counterexample to periodic tiling in dimension three

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Constructs a finite translational tile in Z³ that tiles space but has no fully periodic tiling, disproving the periodic tiling conjecture in dimension three.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE

## 156. Borsuk's conjecture fails in dimension nine

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Shows the compact set of rank-one orthogonal projectors onto R⁴ with Frobenius metric cannot be covered by ten smaller-diameter sets, disproving Borsuk's conjecture in dimension nine.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE

## 157. Graph coloring, clique minors, and Colin de Verdière invariants

- **Vetting:** 3 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Disproves Hadwiger and Colin de Verdière conjectures by constructing large finite graphs where chromatic number exceeds the Hadwiger number, even in fractional coloring.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_lattice/level0_cascade_adjacency.md#L1` -- Level-0 cascade adjacency
     why: Both papers study constraint structures and adjacency, but owner's lattice is fibbinary recurrence-based, not graph-theoretic; lexical match only on 'lattice' and 'adjacency'.

## 158. The Euclidean plane cannot be colored with five colors

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves every five-coloring of the Euclidean plane contains a monochromatic unit-distance pair; advances the Hadwiger–Nelson chromatic number to six or seven.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE

## 159. Erdős’s reciprocal-sum conjecture and quasipolynomial Szemerédi bounds

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised; reasoning summary reasoning_traces/quasipolynomial-arithmetic-progressions.pdf.
- **Plain:** Proves Erdős's conjecture: sets of positive integers with divergent reciprocal sum contain arithmetic progressions of every length. Subsets with no k-term progression have size at most N·exp[−c_k(log N)^ε_k].
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: Both deal with constraint structures (forbidden adjacency in Zeckendorf, no k-progressions in arithmetic sets), but mechanisms differ fundamentally: algebraic recurrence vs. combinatorial density argument.

## 160. Superexponential van der Waerden numbers

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Resolves Erdős's question: van der Waerden numbers satisfy W_r(k) > k^(ck⌊log₂ r⌋) for absolute c>0, proving superexponential growth and W_r(k)^(1/k)→∞.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/06-atmosphere/barometric.md#L1` -- [V] Barometric law = eigenfunction of d/dz
     why: Both papers prove exponential/superexponential growth bounds, but owner's growth rate ln(φ) emerges from spectral Perron-Frobenius theory of transfer matrices [[1,1],[1,0]], whereas van der Waerden bound is purely combinatorial Ramsey-theoretic.

## 161. Counterexamples to Sidorenko’s conjecture and the forcing conjecture

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Disproves Sidorenko's conjecture with a 35-vertex bipartite graph: its homomorphism density is lower than conjectured, also disproving the forcing conjecture about quasirandomness.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Transfer matrix addresses Fibonacci evolution in signal processing; graph homomorphism density is a combinatorial invariant unrelated to recurrence matrices.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/01_recurrences/lucas.md#L1` -- Lucas recurrence
     why: Lucas sequence generates integer values via L(k)=L(k-1)+L(k-2); Sidorenko addresses graph homomorphism counting with no connection to recurrence structure.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: Entropy rate s=ln(phi) per A-application measures information growth; homomorphism density measures graph structure frequency—orthogonal concepts.

## 162. Counterexamples to Ryser’s covering conjecture

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Constructs intersecting (q+1)-partite (q+1)-uniform hypergraphs with covering number q+1 instead of predicted q for prime q, disproving Ryser's conjecture.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Transfer matrix iterates linear map A on state register; hypergraph covering requires set-system combinatorics with no recurrence or eigenvalue component.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/01_recurrences/lucas.md#L1` -- Lucas recurrence
     why: Fibonacci/Lucas enumerate via recurrence; Ryser addresses partition structures in hypergraph families—different mathematical domains.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: CASLO embedding designs cascade rules for signal lattice; set covering in hypergraphs requires combinatorial existence proofs, not signal routing.

## 164. Hindman’s finite sums and products conjecture

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves every finite coloring of positive integers contains k-element sets whose all nonempty subset sums and products share one common color.
- **CASLO frame:** integers and enumeration appear in both, but Ramsey coloring has no connection to Zeckendorf representation or fibbinary lattice structure
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/01_recurrences/lucas.md#L1` -- Lucas recurrence
     why: Both enumerate over integers and subsets: owner's Lucas L(k)=L(k-1)+L(k-2) generates sequences; Hindman proves coloring invariants on subset products—shared enumeration vocabulary only.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/03_zeckendorf/fibbinary_max.md#L1` -- Fibbinary register maximum value
     why: Both bound integer quantities: owner uses max_N=F(W+2)-1 for register capacity; Hindman partitions integer subsets by color class size—same operator (bounding), different structures.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Both count/enumerate constrained sets: transfer matrix A^n counts reachable Zeckendorf states; Hindman counts color-monochromatic subsets—shared enumeration paradigm, different constraints.

## 165. The Harary–Hill and Zarankiewicz crossing-number formulas

- **Vetting:** 2 manuscript(s); Lean scope note; 2 in formalization.yaml; 0 revised.
- **Plain:** Resolves crossing numbers: Kn has crossing=floor(n/2)·floor((n-1)/2)·floor((n-2)/2)·floor((n-3)/2)/4; establishes optimality of classical graph drawings.
- **CASLO frame:** both employ floor functions for combinatorial bounding, but crossing-number graph drawing is unrelated to fibbinary register bounds or cascade composition
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/03_zeckendorf/fibbinary_max.md#L1` -- Fibbinary register maximum value
     why: Both formulas bound combinatorial counts via floor/ceiling: owner max_N=F(W+2)-1; crossing formula floor(n/2)·floor((n-1)/2)·...—same operator (floor arithmetic), distinct structures (register vs. graph).
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Both bound state/structure cardinalities: owner's A^n bounds canonical state count via F(n+2); crossing formula bounds edge-crossing count—shared enumeration via integer arithmetic only.
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/01_recurrences/lucas.md#L1` -- Lucas recurrence
     why: Both employ recursive integer operations: Lucas L(k)=L(k-1)+L(k-2) builds sequence recursively; floor(n/2) applied to descending integers mirrors recursive decomposition—shared arithmetic method.

## 166. The higher-dimensional Erdős distinct-distances conjecture

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves n distinct points in R^d determine at least c_d·n^(2/d) distinct distances for d≥3, matching integer-grid bounds and resolving Erdős's higher-dimensional conjecture.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L193` -- What this buys us conceptually
     why: Transfer matrix governs discrete integer Fibonacci evolution; Euclidean R^d point-distance geometry operates in continuous metric space with no discrete lattice structure.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/00-spine/entropy-rate-law.md#L1` -- [V] Entropy-rate law (spine)
     why: Entropy s=ln(phi) measures information growth in sequences; distance conjecture addresses metric geometry—measure theory vs. combinatorial geometry, unrelated.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/03_zeckendorf/fibbinary_max.md#L1` -- Fibbinary register maximum value
     why: Fibbinary is integer Zeckendorf-address encoding; point distances in R^d use Euclidean metric—combinatorial vs. metric geometry, no shared framework.

## 167. Planar distinct distances and unit-distance bounds

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves weak pinned Erdős conjecture: all but o(n) points of any n-point planar set determine n^(1−ε) distinct distances; bounds unit-distance pairs by O(n^β) for β<4/3.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: CASLO embedding cascades Fibonacci rules on discrete token lattice; unit-distance conjecture addresses Euclidean incidence geometry—no shared lattice or cascade structure.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/01_recurrences/lucas.md#L1` -- Lucas recurrence
     why: Lucas enumerates discrete integer positions; planar unit distances are metric relations in continuous Euclidean plane—orthogonal mathematical frameworks.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/03_zeckendorf/fibbinary_max.md#L1` -- Fibbinary register maximum value
     why: Fibbinary encodes integers on shell lattice via Zeckendorf; planar unit-distance is metric geometry—integer addressing vs. Euclidean metric, no transfer possible.

## 168. Combinatorial invariance of Kazhdan–Lusztig polynomials

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Resolves combinatorial invariance: isomorphic Bruhat intervals in Coxeter systems preserve Kazhdan–Lusztig polynomials; abstract order determines polynomial structure.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L424` -- 4. The Multi-Dimensional No-Modulo Embedding Clock
     why: Matched on 'invariant', 'order', 'structure'—but applied to embedding-clock design, not polynomial invariants on posets
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L145` -- 5. Cross-cutting insights (the real ones, across folders)
     why: Cross-cutting insight I1: 'invariant' and 'order' appear but in context of Fibonacci recurrence, cascade, and Zeckendorf structure
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L645` -- §34  Scalographic Tensor — the unification (thesis cross-walk)
     why: Scalographic tensor discussion matches on 'cascade' but in algebraic-compaction context, not Kazhdan-Lusztig

## 169. Shareshian–Wachs elementary positivity

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves elementary-positivity: chromatic quasisymmetric functions on natural unit interval graphs have elementary-basis coefficients, resolving Shareshian–Wachs conjecture.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L129` -- 4. Engineering concepts (perused, one line + provenance)
     why: Matched on 'graph' and 'function' but in engineering concepts context, not quasisymmetric function positivity
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/CAS_LUT_PIPELINE.md#L243` -- 8. Equation-to-Routing Map (Master Table)
     why: Master table section; matched on 'function', 'symmetric' in transfer-matrix and LUT routing, not basis coefficients
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/CAS_LUT_PIPELINE.md#L349` -- 10. Design Principles (CAS-LUT laws)
     why: CAS-LUT design principles section; 'function', 'symmetric' refer to dual-rail symmetry, not quasisymmetric functions

## 170. Sharp logarithmic exponents for off-diagonal Ramsey numbers

- **Vetting:** 2 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Determines sharp logarithmic exponent: r(s,t) = t^{s-1}/(log t)^{s-2+o(1)} for off-diagonal Ramsey; determines log scale and matches classical upper bound asymptotically.
- **CASLO frame:** Exponential growth structure: both Ramsey bounds and Fibonacci F(k)~phi^k scale exponentially; owner uses log(phi) entropy, register width ~log(S_max), shell growth as phi^k—shared analogy of exponential/log duality
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/math/eigenvalue-geometry/06-atmosphere/barometric.md#L1` -- [V] Barometric law = eigenfunction of d/dz
     why: Barometric law: eigenfunction of d/dz exhibits exponential/logarithmic reciprocal structure; owner's phi eigenvalue and log(phi) entropy parallel this analogy
     ruling: The owner item (7 lines) is the first-order linear ODE dp/dz = -(g/RT)p, whose solution p0 e^{-z/H} is an eigenfunction of d/dz. Family 170 is an extremal-graph asymptotic, r(s,t) = t^{s-1}/(log t)^{s-2+o(1)}, proved by probabilistic and algebraic constructions. Neither family manuscript contains an
  2. level 1 (draft 2, REJECT) `_master_workflow_/WIKI.md#L140` -- 3.5 Base-phi / Log-space Representation
     why: Base-phi / log-space representation: converts exponential growth phi^k into linear log-phi coordinate; same structural duality as Ramsey exponent scaling
     ruling: WIKI 3.5 describes a positional representation: the register stores Fibonacci indices, values grow as phi^k, carries and gaps are read as log_phi differences, and distance is |m-n| ln(phi). The family's 'logarithmic exponent' is the power of the log t factor in an asymptotic Ramsey bound. It has no 
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/UPGRADE/caslo_monolith/harness/docs/ELEMENTS_BOOK_XVI_HETEROGENEITY.md#L34` -- Propositions
     why: Matched on 'logarithmic', 'bounds' but in fixed-diagonal context, not exponential growth analysis

## 171. The hypercube Ramsey conjecture

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Resolves hypercube Ramsey conjecture: two-color Ramsey number of n-dimensional cube is Theta(2^n); red-blue coloring of universal-constant vertices contains monochromatic copy.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/LUT_FABRIC_LM_ALGORITHM.md#L370` -- §6.6  Honest limits
     why: Honest limits section; matched on 'hypercube' and dimensional notation but applies to hyperbolic geometry, not binary cube Ramsey
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/helmet/nodes/s02-04-06-08-10-16-22-24-27.md#L1` -- K=8 visualizer run: 55 admissible states = F(10); 130 fibcube edges, 706 transitions
     why: K=8 visualizer: '130 fibcube edges'—Fibonacci-dimensional cube, not binary hypercube; different combinatorial object
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/zlogpi/zphi.py#L442` -- zeckendorf_encode
     why: zeckendorf_encode function; 'cube' used as data-structure term, not combinatorial Ramsey structure

## 172. Classification of finite Euclidean Ramsey configurations

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Classifies finite Euclidean Ramsey configurations: point sets appearing monochromatically in every coloring of high-dimensional space satisfy tensor condition over coordinate field.
- **CASLO frame:** Shared object: Euclidean geometry. Owner explicitly: 'Euclidean navigation of hyperbolic space' (Hyperbolic Jump Rule, WIKI L223)—navigates Euclidean-metric unit steps on hyperbolic-distance shell lattice
- **Verdict:** WORDS
  1. level 1 (draft 3, REJECT) `_master_workflow_/WIKI.md#L217` -- 4.5 The Hyperbolic Jump Rule
     why: Hyperbolic Jump Rule L223: 'crawling one shell at a time is Euclidean navigation of a hyperbolic space'—Euclidean geometry appears directly
     ruling: 'Euclidean navigation of a hyperbolic space' in WIKI 4.5 is a metaphor for unit-step shell crawling versus index jumps. It is not Euclidean space R^n. Family 172 concerns finite colorings of R^n, monochromatic congruent copies of finite point sets, and a tensor criterion over coordinate fields. The 
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L689` -- HAZARDS
     why: HAZARDS section; matched lexically on 'Eu' and 'configuration' but in execution-graph context
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L178` -- 1.2 Canonicality forces the Lucas bridge to read single-valuedly (Lemma L5)
     why: Lemma L5; matched on 'configuration' but refers to bridge read configuration, not point configuration

## 173. Seymour’s second-neighborhood conjecture

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves Seymour's second-neighborhood: every nonempty finite directed graph has vertex with ≥ vertices at directed distance-2 as at distance-1, resolving conjecture affirmatively.
- **CASLO frame:** Graph structure with distance metrics and vertex ordering. Owner uses rail DAG (directed execution graph) with vertices, edges, shell-distance metrics, and lattice-based vertex ordering
- **Verdict:** ANALOGY
  1. level 1 (draft 2, REJECT) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L232` -- 10. Time is recursion depth is rapidity
     why: Time = recursion depth structure; execution graph with directed edges parallels Seymour's directed neighborhood distance structure
     ruling: Sections 10-14 starting at L232 cover: the eta = ln(phi) identification of index, tick and rapidity; the Parry gap measure; the sech kernel ranking; the lock bit; and the Mobius-ribbon theorem. There is no oriented graph, no vertex neighborhoods and no comparison of distance-1 and distance-2 counts.
  2. level 2 (draft 2, CONFIRM) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L1` -- ELEMENTS, Book XI — the rail DAG: state composes, meaning emerges, authority descends
     why: Execution graph with 19-20 vertices and directed edges; shell-distance metrics in state composition; lattice distance ordering analog to directed-graph distances
     ruling: The owner text defines a finite execution DAG: 19-20 vertices, Def8 nodes, Def9 directed edges u->v of kinds DATA/EVIDENCE/CONTROL, authority propagated along CONTROL edges, and Pred(v) readiness. Its checks run over random DAGs of 10-60 nodes, and cyclic graphs are rejected. A finite DAG has no loo
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L20` -- NOMENCLATURE
     why: NOMENCLATURE: defines register, mass, shell-indexed structure; vertices in graph formalism

## 174. Deterministic construction of strong thin spanning trees

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Resolves the strong thin-tree conjecture: every k-edge-connected multigraph has a spanning tree that crosses each cut at most C/k times the cut size, constructible in polynomial time.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L773` -- 6.4 Harmonized two-register build prescription
     why: Lexical match on 'tree', 'edge', 'deterministic' only. Content discusses Fibonacci cascade registers and fibbinary lattice, unrelated to graph spanning trees.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L295` -- 9. What this reviewing model actually thinks
     why: Lexical match on 'conservation law' and 'recursion'. Content discusses CASLO conservation of Fibonacci mass under R1/R3 cascade rules, not graph-theoretic conservation.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/03_zeckendorf/lattice_cardinality.md#L1` -- Lattice cardinality
     why: No overlap. Family studies combinatorial structure of graphs; owner studies fibbinary cardinality of shell lattices under golden-ratio encoding.

## 175. Talagrand’s expectation thresholds, discrete convexity, and graph decompositions

- **Vetting:** 3 manuscript(s); Lean scope note; 2 in formalization.yaml; 0 revised.
- **Plain:** Proves Talagrand's conjectures on expectation thresholds and discrete convexity; every graph's edges decompose into universally bounded pieces with threshold at most a constant factor of the original.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L204` -- 1.4 Canonicality is upstream of mass-conservation and of parity
     why: Lexical match on 'conservation' and 'recursion'. Content: Fibonacci cascade mass conservation via R1/R3, deterministic not probabilistic.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XV_FED_MEMORY_GRC.md#L361` -- HOW THE MEMORY STATE IS TRACED FOR A GRC AUDIT
     why: No substantive connection. Family is probabilistic threshold theory; owner system is deterministic fibbinary algebra.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/WIKI.md#L440` -- 9.2 8D Algebraic Address
     why: No overlap between graph-decomposition conjectures and Zeckendorf/base-phi representation.

## 176. The second Kahn–Kalai conjecture with an edge-count bound

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves the second Kahn–Kalai conjecture: the appearance threshold of a graph H in random G(n,p) is at most a constant times H's integral density threshold, up to a logarithmic factor in edge count.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L171` -- Addendum: Tensor-Hop Network Reading
     why: Lexical match on 'binary', 'matrix', 'relation'. Content: tensor-network view of fibbinary cascade LUT fabric with Perron-Frobenius eigenvalue phi. No overlap with random graph thresholds.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/ZECKENDORF_LOGIC.md#L90` -- PART IV — Computational memory IN ACTION
     why: No connection between threshold theory on random graphs and Zeckendorf decomposition algorithms.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/WIKI.md#L440` -- 9.2 8D Algebraic Address
     why: No shared mathematical object between probabilistic thresholds and fibbinary lattice operations.

## 177. Bounded-degree coboundary expanders

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Constructs arbitrarily large d-dimensional simplicial complexes (d≥3) with bounded vertex degrees and uniform F₂ coboundary expansion in all degrees below d, resolving the existence question for high-dimensional expanders.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: No connection. Family is topological (simplicial cohomology); owner is algebraic (fibbinary recursion).
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/04_zphi_ring/ring_compose.md#L1` -- Ring composition (d'Ocagne / Vajda)
     why: No overlap between simplicial-complex cohomology and Z[phi] ring composition under Zeckendorf cascade.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L626` -- PORISMS
     why: No shared mathematical structure.

## 178. Deterministic nonbipartite Ramanujan graphs in every fixed degree

- **Vetting:** 1 manuscript(s); no Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** For every fixed d≥3, deterministically constructs d-regular nonbipartite Ramanujan graphs on all sufficiently large even vertex counts, with spectral gap and eigenvalues strictly within [-2√(d-1), 2√(d-1)], in polynomial bit time.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L171` -- Addendum: Tensor-Hop Network Reading
     why: WORDS only. Both mention transfer matrices and eigenvalues (phi, psi spectrum). Family: spectral properties of random regular graphs via adjacency matrix. Owner: fibbinary cascade transfer matrix [[1,1],[1,0]] with Perron-Frobenius eigenvalue phi. No shared theorem or application; different mathemat
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L295` -- 9. What this reviewing model actually thinks
     why: No connection between Ramanujan spectral theory and fibbinary conservation laws.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L645` -- §34  Scalographic Tensor — the unification (thesis cross-walk)
     why: No overlap between spectral graph theory and algebraic Zeckendorf recursion.

## 179. The circulant Hadamard and Barker-sequence conjectures

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves circulant Hadamard matrices exist only in orders 1 and 4, and Barker sequences (binary with bounded aperiodic autocorrelations ≤1) exist only at lengths 2,3,4,5,7,11,13, resolving both conjectures.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L171` -- Addendum: Tensor-Hop Network Reading
     why: WORDS only. Both concern binary/matrix structures. Family: circulant matrices with autocorrelation constraints on real entries. Owner: fibbinary tensor network with bits 0/1 on shells, no autocorrelation theory. Different domains despite lexical overlap.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/ZECKENDORF_LOGIC.md#L90` -- PART IV — Computational memory IN ACTION
     why: Family studies binary sequence periodicity; owner studies Zeckendorf decomposition with no-adjacent-ones constraint. Constraint names differ (periodicity vs. fibbinary) and apply to different structures.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L5` -- Scope
     why: No substantive overlap between Hadamard/Barker sequence theory and CASLO register-fabric binary encoding.

## 180. Barnette’s Hamiltonian-cycle conjecture

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves every finite simple cubic bipartite planar 3-vertex-connected graph contains a Hamiltonian cycle, resolving Barnette's conjecture from 1969.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L20` -- NOMENCLATURE
     why: Mentions 'vertex' and 'cycle' but in context of Zeckendorf canonical register representation, not graph Hamiltonicity.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L636` -- 5.4 R(t-1) triple-duty
     why: Discusses 'triple-duty' register compression in cascade composition; no connection to graph cycle traversal.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/04_zphi_ring/phi_step.md#L1` -- phi_step (forward shell, Z[sqrt(5)])
     why: Forward shell navigation on Z[phi] lattice; no application to Hamiltonian cycles or planar graph structure.

## 181. The Erdős–Gallai cycle-decomposition conjecture

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves every finite undirected graph on n vertices has edge partitions into at most Cn simple cycles and single edges, resolving Erdős–Gallai cycle-decomposition conjecture.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L1` -- ELEMENTS, Book XI — the rail DAG: state composes, meaning emerges, authority descends
     why: Discusses execution DAG and register composition (19-20 vertices in state graph), not graph cycle decomposition bounds.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/jun_11_2026/superfunction.py#L1116` -- navigationGraph
     why: navigationGraph function for CASLO state navigation; not about edge partitioning or cycle decomposition.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L223` -- 2. The Cascade as Renormalization Information-Flow
     why: Discusses cascade as renormalization on shell lattice; no connection to edge partitions or cycle decomposition.

## 182. Power savings for intersective polynomial differences and prime arguments

- **Vetting:** 3 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves power-saving bounds O(N^(1-c_k)) for sets avoiding nonzero values of intersective polynomials, using Dirichlet L-functions; proves analogous bounds for polynomial arguments at primes.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Foundational lemmas about cascade closure; mentions 'modulo' in context of register arithmetic constraints, not Diophantine equations.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/00_axioms/psi_definition.md#L1` -- psi definition
     why: Psi backward shift operator; no connection to polynomial differences or Dirichlet analysis.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XIII_ENERGY_ROUTING.md#L11` -- NOMENCLATURE
     why: Register nomenclature and constraints; not about modular roots or polynomial difference sets.

## 183. Power savings for planar halving lines and k-sets

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves power savings for planar halving lines: O(n^(4/3-ε)) halving pairs in n-point sets with no three collinear, improving classical O(n^(4/3)) bound.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L180` -- 7. Why one rail is not enough — the two coordinates of a ribbon
     why: Discusses two-rail separation in Möbius ribbon encoding; not about planar geometry or halving-line combinatorics.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/METHODOLOGY.md#L109` -- 3. Math concepts (perused, one line + provenance)
     why: Math concepts for CASLO framework including 'geometry'; no connection to planar k-sets or collinearity constraints.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L492` -- THEOREMS T1..T5 AND THE ROOT T0
     why: State composition and separation in execution DAG; not about geometric halving or point configurations.

## 184. Correspondence coloring with a fixed forbidden subgraph

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Proves Alon–Krivelevich–Sudakov coloring conjecture: Kr-free graphs need O_r(Δ/log Δ) colors; proves independence conjecture: Kr-free graphs have independent sets of size Ω_r(n log d/d).
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/BOOLEAN_PATHING.md#L189` -- 9. The strict-Boolean variant
     why: Boolean independence in cascade pathing; refers to independent redex choices, not graph-theoretic independent sets.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L20` -- NOMENCLATURE
     why: Register nomenclature including 'vertex'; not about chromatic number, cliques, or graph coloring.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: De Morgan duality on Z[phi] lattice; no connection to graph correspondence coloring or clique-free bounds.

## 185. Counterexamples to infinite matroid intersection and packing/covering

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Disproves infinite matroid intersection and packing/covering conjectures in ZFC by constructing two self-dual partitional matroids on countably infinite ground set avoiding both properties.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/06_psi_retract/psi_retract_operator.md#L1` -- psi_retract operator
     why: Psi-retract operator for cascade unwinding; not about matroid packing, covering, or self-duality in set systems.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/CASLO_MOBIUS_BIT_RIBBON_APPENDIX_2026-07-03.md#L89` -- 4. The graded fold — packing the whole past into one register
     why: Discusses packing bit history into register (register compression), not matroid packing or intersection theory.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XV_FED_MEMORY_GRC.md#L328` -- CITATION ON REFERENCE DURING LIVE INFERENCE
     why: Memory citation and reference protocol; not about matroid structure or infinite set systems.

## 186. Uniform influence and sharp thresholds for graph and hypergraph properties

- **Vetting:** 2 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Boolean function variance bounds on hypergraphs: Var_p(f) ≤ C_r I_p(f)/(log n)^{r/(r-1)}. Relabeling-invariant increasing properties transition from probability ε to 1-ε within threshold width O(log n)^{-2} for graphs.
- **CASLO frame:** Studies variance bounds for Boolean functions over hypergraph properties under relabeling symmetry. CASLO operates on Zeckendorf domains with conservation of I-1 = Σ_k F(k)·R[k] and fibbinary constraints. Both involve invariant quantities and bounds, but on different mathematical objects: probabilistic variance vs algebraic conservation.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L223` -- 2. The Cascade as Renormalization Information-Flow
     why: Both use 'conservation' and 'invariant' but different domains: probabilistic variance vs algebraic I-1 conservation
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L10` -- Core claim
     why: Transfer operators appear in both but study different structures: Boolean functions vs Fibonacci transfer matrix
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L489` -- 4.7 The deepest cycle — `I-1` conservation as the period-1 hand
     why: Conservation laws in both but applied to different domains: hypergraph properties vs Fibonacci lattice

## 187. Snaky in 21 Maker moves

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Settles Snaky game: Maker can force the 6-cell hexomino shape within 21 of its own moves on infinite square board against arbitrary Breaker play. Translations, rotations, and reflections count as distinct wins.
- **CASLO frame:** Game theory result about optimal play in combinatorial Maker/Breaker game on spatial board. CASLO is a Fibonacci lattice transducer for deterministic natural language processing with no game-theoretic or spatial reasoning. No shared object with the owner's framework.
- **Verdict:** NONE

## 188. The sharp terminal leave in random triangle removal

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Starting from complete graph K_n, repeatedly delete uniformly random triangle. Terminal edge count asymptotic to n^{3/2}/(2√2) with L2 convergence. Proves triangle case of Joos–Kühn sharp-constant conjecture.
- **CASLO frame:** Studies random processes on graphs: stochastic removal with probability analysis, L2 convergence, asymptotic limits. CASLO operates deterministically on Zeckendorf lattices with algebraic recurrence and no stochastic reasoning. Asymptotic terminology appears in both but applied to different domains: probability theory vs Fibonacci algebra.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Word 'asymptotic' appears in both but contexts differ: φ^k lattice density vs random triangle limit
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/jun_11_2026/superfunction.py#L1116` -- navigationGraph
     why: Data structure 'graph' overlaps but no mathematical substance: address graph vs random removal process
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L10` -- Core claim
     why: Exponential growth in both but context differs: Fibonacci algebra vs stochastic probability

## 189. Cycle–clique Ramsey numbers

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Proves Erdős–Faudree–Rousseau–Schelp conjecture: R(C_m, K_n) = (m-1)(n-1)+1 for m≥n≥3. In any red-blue coloring of complete graph, must contain red m-cycle or blue n-clique. Exact combinatorial threshold.
- **CASLO frame:** Graph coloring conjecture: exact threshold guaranteeing monochromatic structure under combinatorial constraints. CASLO studies Fibonacci/Lucas lattices under cascade operators with exact conservation laws. Both involve exact bounds and thresholds on incompatible mathematical objects: graph colorings vs fibbinary addresses.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Both study exact theorems but on different objects: graph colorings vs Fibonacci/Lucas axioms
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/03_zeckendorf/fibbinary_encoding.md#L1` -- Fibbinary encoding
     why: Exact bounds and constraints in both but different domains: Ramsey colorings vs no-adjacency fibbinary
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L238` -- Operator R1 — adjacency carry (fine -> coarse)
     why: Both study constraint structures (no-adjacency, colorings) but on incompatible objects

## 190. Polynomial removal fails for ordered binary matrices

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Constructs 66×66 binary matrix where ordered pattern removal has no polynomial bound. Ordered copies preserve row and column orders and match both zeros and ones. Refutes polynomial ordered matrix-removal conjecture.
- **CASLO frame:** Binary matrix combinatorics: patterns in 0-1 matrices with order-preserving structure. CASLO uses binary fibbinary representation (no adjacent 1s in shell lattice) to preserve algebraic structure. Both involve binary encodings with order/structure preservation, but matrix removal is combinatorial while fibbinary is Fibonacci-algebraic.
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/03_zeckendorf/fibbinary_encoding.md#L1` -- Fibbinary encoding
     why: BOTH use binary representation with order-preserving constraints: family 190 preserves row/column order; fibbinary preserves Fibonacci weight via no-adjacency
     ruling: Family 190 is about ordered induced-submatrix containment: copies are picked by independent strictly increasing row and column maps (StrictMono in MatrixRemoval.lean). Its theorems relate Hamming edit distance from H-freeness to copy density, and it disproves a polynomial removal bound. The owner it
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md#L10` -- Core claim
     why: Both work with binary/integer representations but contexts differ: matrix removal vs algebraic transfer operators
  3. level 1 (draft 2, REJECT) `_master_workflow_/EQUATIONS/09_lucas_zero/phi_psi_demorgan_bridge.md#L1` -- φ/ψ ↔ De Morgan ↔ Lucas-aperture bridge
     why: BOTH use Boolean structure and binary patterns with constraints, but applied to different objects: matrix removal vs fibbinary admissibility
     ruling: The claim itself concedes that the two items concern different objects. The owner item covers: the no-11 admissibility predicate rewritten by De Morgan (AND_k NOT(R[k] AND R[k+1]) = AND_k (NOT R[k] OR NOT R[k+1])), the contiguous 101 bridge readout, the focus identity F(k-1)+F(k+1)=L(k), and the phi

## 191. A power improvement in the Heilbronn triangle lower bound

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** For large n, constructs n points in unit square such that every triangle has area ≥ c₁n^{-2+η} for fixed η>0. Disproves conjectured n^{-2} upper bound in Heilbronn problem: how large can smallest triangle determined by n points be?
- **CASLO frame:** Geometric extremal problem: point distribution in R² with area lower bounds and power-law exponents. CASLO operates on Fibonacci lattice addresses in Z[φ] algebra with shell-index encoding. No geometric or Euclidean reasoning in CASLO. No shared object with the owner's framework.
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L451` -- 4.3 Axis 2 — shell-index hand: `log_phi` rapidity, density `phi^{-k}`
     why: φ appears in both (power law exponent φ^{-k}) but context differs: algebraic lattice density vs geometric area bounds
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Word 'power' appears in both but contexts differ: power-law exponent vs Fibonacci growth exponent
  3. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/03-complex/ipi-identity.md#L1` -- [V] ln(phi*psi) = i*pi
     why: φ appears in complex geometric context but unrelated to Heilbronn triangle problem structure

## 192. Boolean functions violate the square-root degree bound by arbitrary factors

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Disproves the proposed square-root bound relating a Boolean function's linear Fourier coefficients to its polynomial degree. For every C > 0, there is a sign-valued Boolean function f with $\sum_i\widehat f(\{i\})\gt C\sqrt{\deg(f)}$....
- **CASLO frame:** Discrete lattice or conservation structure analogous to CASLO shell lattice and composition rules
- **Verdict:** WORDS
  1. level 1 (draft 2, REJECT) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L20` -- NOMENCLATURE
     why: elements: NOMENCLATURE (score 165) shell
     ruling: Registers in {0,1}^W with digit-wise AND/OR/NOT/XOR and OR-of-ANDs predicates are Boolean functions only in the generic sense; no Fourier coefficients, polynomial degree or sqrt(deg f) bound.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/IBM_PAPER_BRIEF.md#L85` -- 5. Spacetime Error Mixing (Sec 1.1, 3.3; pp. 9-10, 39-40)
     why: equation_doc: 5. Spacetime Error Mixing (Sec 1.1, (score 146)
  3. level 1 (draft 2, REJECT) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: design_note: 0.3 Foundational lemmas (score 146) recurrence
     ruling: L4's Cassini sum sigma = Sum (-1)^k R[k] is a fixed signed linear form on register bits, not a sum of degree-1 Fourier coefficients of a Boolean function; no degree or square-root bound.
