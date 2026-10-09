# The OpenAI math collection, distilled into the owner's framing

Date 2026-10-08. Source: private fork `qLeviathan/math` at `fd4aeeb` (upstream `github.com/openai/math`; last commit by Dan Roberts \<dr@openai.com\>, 2026-10-07, "Update manuscripts and Lean formalizations").

Companion files:
- `TRANSFER_MAP.md`: result by result, what transfers to the owner's mathematics.
- `cards/`: one card per family.
- `catalog.jsonl`: machine-readable.

All counts below are read from the repository files named in each row.

---

## 1. What the system is

| Fact | Value | Source |
|---|---|---|
| Producer | an unreleased internal OpenAI model; about 3 hours of ChatGPT Pro thinking per result | `README.md` "How the results were produced" |
| Problems posed | about 4,000 | same |
| Output kept | 719 manuscripts in 372 result families, after an aggregation and significance filter | `README.md`, `overview.tex` |
| Family | a principal result plus companion arguments, consequences or alternative proofs | `README.md` |
| Subjects | 17 (largest: Theoretical computer science 40, Combinatorics 37, Algebraic and complex geometry 36) | `overview.tex` `\cataloguesection` |
| Human exceptions | zeta zero-free region work and Hodge for CM abelian varieties; the Re(s) > 11/12 writeup was human-edited | `README.md` |

## 2. How it checks itself (the verification contract)

| Layer | What it is | Count | Source |
|---|---|---|---|
| Lean library | one large library, namespace `OAI`, Lean `v4.34.1`, Mathlib pinned at `d13f23b` plus about 15 external packages (carleson, StrongPNT, ClassFieldTheory, sphere-eversion, Zeta3Irrational, …) | — | `lean/lakefile.lean`, `lean/lake-manifest.json` |
| Formalization catalogue | papers whose main result is formalized | 173 sources | `lean/formalization.yaml` |
| Scope notes | per family: what the Lean statement covers and what it does not | 242 notes; 70 state limits or outside-scope parts | `lean/docs/NNN.md` |
| Comparator challenges | a statement file ending in `sorry` (human-auditable), a solution module, and a whitelist of permitted axioms `propext`, `Quot.sound`, `Classical.choice`. The Comparator tool checks the solution proves exactly the statement | 416 | `lean/ComparatorChallenges/*.json` |
| Release history | withdrawals, fixes and added formalizations, kept as versions | 3 withdrawn (one sign error in a stabilization-trace cancellation invalidated two dependent papers); 14 revised; formalized 300 / 719 top-line results | `history.md` (2026-10-07) |
| Reasoning summaries | abridged chains of thought with verbatim excerpts, dead ends included | 10 families, 91,246 words | `reasoning_traces/*.pdf` |

## 3. The same contract in the owner's terms

| OpenAI layer | Owner equivalent (already in use) | Where |
|---|---|---|
| Result family | helmet hook / research-round finding; the address is the Zeckendorf register of its title | `helmet/SPEC.md` §1 |
| Manuscript | EQUATIONS entry or proof doc with provenance | `EQUATIONS/INDEX.md` |
| Comparator statement file (`sorry`) | the declared claim: cross_check `lhs` (claimed), or a prediction declared before a QPU job | `zlog/warehouse/schema.sql` `cross_checks` |
| Solution module + Comparator | golden file + byte-exact replay + verify-all gate | `caslo_monolith` golden fixtures, `verify-all` |
| Permitted axioms whitelist | the nine hard constraints (permitted operations) | `CLAUDE.md` |
| Scope note ("outside this statement") | NOT_EXECUTED / scope lines in DEVLOG and evidence | e.g. `caslo_monolith/harness/docs/DEVLOG.md` L771 |
| Withdrawal after a sign error | a falsified cross_check, plus a drift_todo; choice-graph drift propagation | `q.py failing`; `drift_todos` |
| Release history | append-only DEVLOG, CHANGELOG and ledger | `EQUATIONS/CHANGELOG.md`, `research_loop/ledger` |
| Reasoning summary with dead ends | the refused register and research letters | `math/eigenvalue-geometry/08-refused/refused.md` |
| 4,000 problems → 372 families | research rounds → helmet intake with a human approve gate | `helmet/intake.py` |

**Method lesson:** keep the statement separate from the proof, and audit the statement by eye. The owner already separates claim from measurement for hardware. The same split can carry the owner's mathematics into Lean.

## 4. The owner's core, already machine-checked in Mathlib (same pin `d13f23b`)

| Owner object | Mathlib anchor | File:line (Mathlib) |
|---|---|---|
| Carry R1: F(k)+F(k+1)=F(k+2) | `Nat.fib_add_two` | `Data/Nat/Fib/Basic.lean:75` |
| Zeckendorf form; no adjacent shells | `Nat.IsZeckendorfRep l := (l ++ [0]).IsChain (fun a b ↦ b + 2 ≤ a)` | `Data/Nat/Fib/Zeckendorf.lean:52` |
| Greedy descent | `Nat.greatestFib` | `Data/Nat/Fib/Zeckendorf.lean:77` |
| Bijection ℕ ↔ fibbinary words | `Nat.zeckendorfEquiv : ℕ ≃ {l // IsZeckendorfRep l}` | `Data/Nat/Fib/Zeckendorf.lean:175` |
| Cassini sign | Cassini's identity (and Catalan's) for `Int.fib` | `Data/Int/Fib/Lemmas.lean:27` |
| Z[φ] power law φ^(n+1) = φ·F(n+1)+F(n) | `goldenRatio_mul_fib_succ_add_fib` | `NumberTheory/Real/GoldenRatio.lean:224` |
| ψ rail: F(n+1) − φ·F(n) = ψ^n | `fib_succ_sub_goldenRatio_mul_fib` | `NumberTheory/Real/GoldenRatio.lean:211` |
| Binet F(n) = (φ^n − ψ^n)/√5 | `coe_fib_eq` | `NumberTheory/Real/GoldenRatio.lean:198` |
| Addition law (product channel) | `Nat.fib_add` | `Data/Nat/Fib/Basic.lean:141` |
| Doubling identities | `Nat.fib_two_mul`, `Nat.fib_two_mul_add_one` | `Data/Nat/Fib/Basic.lean:150, :157` |
| φ, ψ irrational | `goldenRatio_irrational`, `goldenConj_irrational` | `NumberTheory/Real/GoldenRatio.lean:120, :128` |
| **Lucas rail L(k)** | **not present.** Mathlib's "Lucas" files are Lucas–Lehmer, Lucas primality and Lucas' binomial theorem | gap |
| **Split R3 and the cascade as a rewrite system** (termination, confluence, mass) | **not present** | gap |
| **Golden-mean shift count F(n+2); majority vote keeps no-11** | not located | gap |

**Consequence:** the owner's foundation (Zeckendorf form, carry, Cassini, the Z[φ] power law) sits on formally verified ground. The owner-specific parts that are not yet machine-checked are:
- the Lucas rail;
- the R1/R3 cascade as a terminating, confluent, mass-preserving rewrite system;
- the golden-mean-shift counting;
- the majority-vote closure.

These are the natural Comparator-style challenges: a statement file plus a proof plus the permitted axioms.

## 5. What does and does not transfer (results, verifier-ruled)

The run:
- **Readers:** 68 Haiku helmet bots read all 372 families (6 per batch). They returned 1,116 top-3 slots and 170 claims at level ≥ 2.
- **Verifiers:** 34 adversarial verifiers ruled on every claim: **129 REJECT, 20 DOWNGRADE, 21 CONFIRM**.
- **Haiku inflates:** about three of every four ambitious claims did not survive a reader that opened the manuscripts' TeX sources.

| Final verdict | Families |
|---|---|
| Direct use (their theorem applies to an owner item as stated) | 0 |
| Shared object | 1 |
| Analogy (same kind of structure) | 19 |
| Words only | 285 |
| None | 67 |

**Where it lands:** almost entirely on one spine of the owner's mathematics, *entropy = log of the leading transfer-matrix eigenvalue*.

| Owner item | Families landing at level ≥ 2 |
|---|---|
| `math/eigenvalue-geometry/00-spine/entropy-rate-law.md` | 8 |
| `EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md` S5 (Perron–Frobenius vector) | 5 |
| `EQUATIONS/TRANSFER_MATRIX_AS_LUT_FABRIC.md` tensor-hop addendum | 5 |
| `TRANSFER_MATRIX_AS_LUT_FABRIC.md` A2 (spectral gap), S1 (pipeline = A^32) | 2 each |
| `CASLO_MOBIUS_BIT_RIBBON_APPENDIX` §11 (Parry measure, entropy log φ) | 2 |
| `caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md` axioms (mass Σ F(k)M(k)) | 2 |

**By subject:**
- **Families that transfer:** probability and statistical mechanics 7 / 29; dynamical systems 5 / 12; mathematical physics 3 / 25; number theory 2 / 31; one each in combinatorics, algebra and differential geometry.
- **Zero transfer:** algebraic and complex geometry (Hodge, BSD, K3), analysis, convex geometry, theoretical computer science, logic, group theory, operator algebras, topology, functional analysis, PDE.

**The one shared object: family 151, a C¹ counterexample to Shub's entropy conjecture.** Shub conjectured h_top(f) ≥ log ρ(f_*). The family refutes it with h_top = 0 < log 2 ≤ log ρ(f_*). The owner's spine states s = ln λ_max(A) for constrained symbolic systems, which is the classical equality for subshifts of finite type such as the golden-mean shift. Two consequences:
- *the owner's equality stands where it is stated (symbolic dynamics);*
- *family 151 is a proved boundary: "entropy = log eigenvalue" does not extend to smooth maps acting on homology.* Do not generalize the spine beyond the symbolic setting without a proof.

**Analogies worth acting on:**
- **149, mass-action permanence.**
  - The verifier confirmed that R1 (X_k + X_{k+1} → X_{k+2}) and R3 (2X_k → X_{k+1} + X_{k−2}) are reactions on shell counts, and that Σ F(k)·M(k) is a linear stoichiometric conservation law.
  - So the cascade is a chemical reaction network, and that theory's tools apply: stoichiometric classes, deficiency, reachability.
  - Caution: "reversible" in the owner's notes means φ/ψ invertibility, not weak reversibility.
- **017, irrationality exponent of π (machine-checked here, §6).** Diophantine approximation; the owner's 5/8 = F(5)/F(6) is a continued-fraction convergent of φ⁻¹. φ is the extremal case of exponent 2.
- **279, exact quantum factoring.** Recovering the order label from continued fractions. This bears on the owner's QPU work.
- **215, 223, 225, 226, 234, 237.** Six-vertex, dimer, random-cluster, spin-glass and self-avoiding-walk results driven by Perron–Frobenius analysis of transfer matrices: the same mechanism as the owner's A = [[1,1],[1,0]] fabric.
- **145, 146, 148, 339.** Mixing, metric entropy and entropy rates of invariant measures: the same genre as the Parry measure P(gap = k) = φ^(−k).
- **265, area laws.** The owner's note on Fibonacci-anyon topological entanglement entropy ln d_τ = ln φ is the same genre. The claimed shared object was ruled down to analogy.

## 5a. False friends: the same word, different objects (found by the verifiers)

| Word | In the owner's corpus | In the OpenAI corpus |
|---|---|---|
| golden | the golden ratio φ | the Golden–Thompson trace inequality (a person's name) |
| hyperbolic | log-scale step, "linear in index" (`EQUATIONS/04_zphi_ring/hyperbolic_distance.md`) | Gromov-hyperbolic groups and CAT(0) / CAT(−1) geometry |
| reversible | the x·φ / x·ψ map is invertible | weak reversibility of a reaction graph |
| spectral gap | eigenvalue separation φ vs ψ of A | infimum of a Dirichlet form over variance (Markov generators) |
| tensor | tensor-network / MPS reading of the shell register | the tensor square V ⊗ V of a symmetric-group representation (Kronecker coefficients) |
| transfer | transfer matrix | usually the verb ("transfer of local budgets") |
| entropy | topological entropy of a subshift, ln φ | metric, entanglement or Shannon entropy, depending on the paper |

## 5b. Drift in the owner's notes surfaced during verification

- Helmet node "Sech kernel, integer forms" (`helmet/nodes/s00-02-06-08-14-16-19-23.md`) cites "62 checks, 2.3E-72 error". In `EQUATIONS/07_hyperbolic_jump/sech_kernel.md` these are labelled "silicon-adjacent … at 60-digit host precision", which is a host-side check, not a silicon verification.
- The (work, coll) single-bit encoding caps per-shell multiplicity at 2 and drops F(2) when R1 and R3 fire on one shell in one tick. This is already a known issue in `CLAUDE.md`; a verifier re-derived it independently.

## 6. Re-checking OpenAI's claims on this machine: family 017 verified

Family 017 ("The irrationality exponent of π is 2") was machine-checked on the owner's host with OpenAI's own pins (Lean `v4.34.1`, Mathlib `d13f23b`, fork HEAD `fd4aeeb`). Evidence: `vetting/017_pi/RESULT.md`.

| Check | Result |
|---|---|
| `lake build OAI.NumberTheory.PiExponent.Main` | BUILD_OK (about 8 minutes, Mathlib from cache) |
| `#print axioms OAI.PiExponent.main` | `[propext, Classical.choice, Quot.sound]`: the Comparator whitelist; no `sorryAx` |
| Statement text vs `ComparatorChallenges/PiExponent.lean` | identical |
| Statement elaborated from Mathlib alone vs the proof's type (`pp.all`) | identical, 2,300 characters each |

**Trusted base:** the Lean kernel and Mathlib's definitions.

**Outside the formal statement** (OpenAI's own scope note): the Flint–Hills series consequence.

**Not run:** the Comparator tool itself. The `pp.all` comparison checks the same statement equality.
