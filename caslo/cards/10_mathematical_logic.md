# Mathematical logic -- OpenAI result families in CASLO framing

Levels: 0 none, 1 words, 2 analogy, 3 shared object, 4 direct use. Final levels >= 2 were confirmed by an adversarial verifier; unverified claims are capped at 1.

## 240. Shelah's eventual categoricity and the prescribed-threshold obstruction

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Shelah's eventual categoricity conjecture: for each bound on the Löwenheim–Skolem number, a uniform threshold makes categoricity in one cardinal above that threshold imply categoricity throughout the same tail of cardinals.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/helmet/nodes/s00-06-11-13-15-19-23-25.md#L1` -- Mathematical Foundations
     why: Word-only match on 'Mathematical Foundations'; abstract elementary classes use model-theoretic vocabulary orthogonal to Zeckendorf decomposition, Fibonacci sequences, Z[phi] ring, cascade rules.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/WIKI.md#L169` -- 4.1 Uniqueness of the Combined Address
     why: Uniqueness of Zeckendorf representation is about guaranteed unique decomposition of positive integers into non-consecutive Fibonacci numbers; not about categorical invariants of abstract structures.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: CASLO axioms concern register state, cascade rules, and recurrence operations; no connection to Shelah's abstract elementary class theory.

## 241. Rigidity of the Turing degrees

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Rigidity of Turing degrees: every order automorphism of the partial order of Turing degrees is the identity, proving no nontrivial relabeling preserves relative computability ordering.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/zlogpi/zphi.py#L97` -- ZPhi
     why: ZPhi class represents Z[phi] = Z[x]/(x^2-x-1) ring elements; word 'automorphism' appears in context of ring endomorphisms like multiplication by phi, not order automorphisms of partial orders.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Foundational lemmas in CASLO concern register operations and cascade logic; orthogonal to computability theory and Turing degree lattice structure.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/04-hyperbolic/anosov-dynamical.md#L1` -- [V] Hyperbolic dynamics (Anosov)
     why: Anosov dynamics concerns dynamical systems and hyperbolic geometry; unrelated to rigidity of degree structures in computability theory.

## 242. Single-fold Diophantine representations and undecidability under an at-most-one-solution promise

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Single-fold Diophantine conjecture: every recursively enumerable set of natural-number tuples has a polynomial Diophantine representation with exactly one complete auxiliary tuple per member and none for nonmembers.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/EQUATIONS/00_axioms/phi_squared.md#L1` -- phi squared
     why: phi^2 = phi + 1 is a polynomial equation defining the golden ratio; Family 242 uses Diophantine polynomials to represent RE sets and prove undecidability—orthogonal objectives.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `_master_workflow_/math/eigenvalue-geometry/01-golden-constants/constants.md#L1` -- [V] Golden constants
     why: Golden constants and recurrence relations; not about Diophantine undecidability or recursively enumerable sets.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L79` -- 0.1 Axioms (verbatim from the derivation spine)
     why: Recursion in CASLO context means state machine and register advance; no connection to recursively enumerable sets or Diophantine equations in logic.

## 243. Separating choiceless counting from polynomial time and witnessed choice

- **Vetting:** 2 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Noncapture theorem: choiceless polynomial time with counting does not capture polynomial time on unordered finite structures; a linear-consistency query over F₃ in fixed binary vocabulary is decidable in P but not in counting formalism.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** NONE
  1. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XV_FED_MEMORY_GRC.md#L328` -- CITATION ON REFERENCE DURING LIVE INFERENCE
     why: Word 'decidable' appears in context of GRC (generative recurrence circuit) audit; no connection to polynomial-time expressiveness or choiceless computation.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L692` -- 6.1 Closure of the two-register basis
     why: Closure of two-register basis concerns bitstring invariants under cascade rules; no relationship to computational complexity classes or finite-structure queries.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L391` -- §17  The reframe — why we changed the audit model
     why: Reframe in audit model is about Zeckendorf encoding verification; unrelated to polynomial-time decision problems.

## 244. The Partition Principle does not imply Choice

- **Vetting:** 1 manuscript(s); Lean scope note; 1 in formalization.yaml; 0 revised.
- **Plain:** Partition Principle does not imply Choice: constructs a ZF model where every surjective image injects (Partition Principle holds) yet the Axiom of Choice fails; Choice for ordinal-indexed families persists.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `caslo_test_framework/docs/MASTER_CONTROL.md#L9` -- §0  Compaction-Survival Protocol — read this first
     why: Word 'axiom' appears in 'Compaction-Survival Protocol' title; refers to encoding axioms for CASLO (no XOR, no hash, etc.), not ZF set-theoretic axioms.
  2. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/jun_11_2026/superfunction.py#L200` -- encode
     why: Encode function in superfunction context is about token/Zeckendorf encoding; not about surjections, injections, or set-theoretic choice operators.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L417` -- XIII. Ancestry survives transformation (L13, Prop 8, P5 with P3)
     why: Ancestry survives transformation in the context of elements and propositions about cascade rules; no connection to axioms of set theory.

## 245. Weak normalization implies strong normalization in pure type systems

- **Vetting:** 1 manuscript(s); Lean scope note; 0 in formalization.yaml; 0 revised.
- **Plain:** Weak normalization implies strong normalization in pure type systems: if every legal expression in valid context has a β-normal form, then all β-reduction sequences terminate; resolves the β-Barendregt–Geuvers–Klop conjecture.
- **CASLO frame:** no shared object with the owner's framework
- **Verdict:** WORDS
  1. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L457` -- XIV. Meaning is revealed without privilege (L14, Prop 6)
     why: Word 'type system' appears in context of CASLO's logical propositions and rules; refers to the fibbinary/cascade rule semantics, not type-theoretic β-reduction.
  2. level 1 (draft 1, NOT_REVIEWED_BELOW_2) `theLab/ELEMENTS_BOOK_XI_RAIL_DAG.md#L148` -- I. Mass is preserved under R1/R3 (L1, P1)
     why: Termination appears: 'termination in general' is a limit of the Mass Preservation proof for R1/R3 cascade rules; convergence to normal form in Zeckendorf decomposition, not type-theoretic reduction strategy.
  3. level 0 (draft 0, NOT_REVIEWED_BELOW_2) `_master_workflow_/caslo_lm/docs/EMBEDDING_CLOCK_AND_CHANNELS.md#L119` -- 0.3 Foundational lemmas
     why: Foundational lemmas establish register semantics and rules; no shared object with pure type systems, dependent types, or β-reduction properties.
