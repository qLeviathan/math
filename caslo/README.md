# caslo/ — the OpenAI math collection read through the CASLO framework

This folder lives only in the private fork `qLeviathan/math`; upstream `openai/math` is untouched. It records what this collection means for the owner's mathematics: Zeckendorf / fibbinary registers, the Fibonacci and Lucas rails, Z[φ], the carry/split cascade and the CASLO hardware stack.

## Contents

| Path | What it is |
|---|---|
| `SYSTEM_DISTILLATION.md` | How the collection was produced and how it verifies itself (Lean, scope notes, Comparator), restated in the owner's terms. Also which of the owner's core identities Mathlib already proves |
| `TRANSFER_MAP.md` | Result-by-result transfer verdicts, the families that land on owner items, and the owner items they land on |
| `cards/NN_subject.md` | One card per result family: vetting status, plain statement, CASLO frame, and the owner's top 3 matching items with transfer level |
| `catalog.jsonl` | The same, machine-readable (one family per line) |
| `vetting/017_pi/` | Independent machine check of family 017 (irrationality exponent of π is 2) on the owner's machine, with OpenAI's own Lean and Mathlib pins |

## How it was produced
1. **Owner index:** 1,246 items from `_master_workflow_`, theLab and caslo_test_framework (EQUATIONS, WIKI, AI_MODEL_LOGIC rules, helmet hooks, Zeckendorf engine functions, ELEMENTS books, MASTER_CONTROL, eigenvalue-geometry notes). Each item is addressed the way the helmet addresses a hook: cl100k token signature plus a canonical Zeckendorf register.
2. **Top-3 matcher** (`_master_workflow_/math_transfer/top3.py`): rarity-weighted shared signature, with ties broken by Zeckendorf shell distance. Integer only.
3. **Helmet bots:** 68 Haiku agents, each wearing the helmet (`_master_workflow_/helmet/wear.py`), read 6 families each. They translated each family into the owner's vocabulary, re-queried the matcher, opened the cited lines, and graded transfer.
4. **Adversarial verifiers:** every transfer claimed at level 2 or above was re-read by a stronger model instructed to refute it. Unconfirmed claims are capped at level 1.

**Levels:** 0 none · 1 words · 2 analogy (same kind of structure) · 3 shared object (one identity or object present in both) · 4 direct use (their theorem applies to an owner item as stated).

## Reproduce
From `_master_workflow_`, in this order:
```
python3 math_transfer/owner_index.py
python3 math_transfer/openai_catalog.py /path/to/this/repo
python3 math_transfer/candidates.py 8
python3 math_transfer/top3.py "any text"
python3 math_transfer/assemble.py <workflow output>
```
