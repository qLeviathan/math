# Family 017 — "The irrationality exponent of π is 2" — machine check on this host

Repository: qLeviathan/math @ fd4aeeb2ee4fc729c18d98444fed42fd0529eeeb (sparse clone of lean/ at ~/oai_math)
Toolchain: leanprover/lean4:v4.34.1 · Mathlib d13f23b723b8a846827a245b89c10fc7d3f11612 (OpenAI's own pins)

| Check | Result | Evidence |
|---|---|---|
| Build the solution module `OAI.NumberTheory.PiExponent.Main` | BUILD_OK (2026-10-09 03:59:40Z → 04:07:22Z) | /tmp/flc/lean_vet.log L137–L1019 |
| Axioms used by `OAI.PiExponent.main` | `[propext, Classical.choice, Quot.sound]` — the Comparator whitelist; no `sorryAx` | pi_axioms.lean · log L1032 |
| Statement text vs `ComparatorChallenges/PiExponent.lean` | identical | pi_statement.lean |
| Challenge statement type-ascribed to the proof term | Lean exit 0 | pi_statement.lean |
| Statement elaborated from Mathlib alone vs the proof's type, both with `pp.all` | identical (2,300 characters each) | pi_clean.lean/.out · pi_solution_type.lean/.out |

Trusted base: the Lean 4 kernel and Mathlib's definitions (Real.pi, abs, rpow, sSup, Set.Infinite, ℚ.den).
Outside the formal statement (per OpenAI's scope note lean/docs/017.md): the Flint–Hills series consequence.
Not run: the Comparator tool itself (lean4export + landrun); the pp.all comparison above checks the same equality of statements.
