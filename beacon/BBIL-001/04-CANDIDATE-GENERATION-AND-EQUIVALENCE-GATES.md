# BBIL-001 — Candidate Generation and Equivalence Gates

> **BBIL-001 v0.1 — DRAFT BLIND-ITERATION LAB ARCHITECTURE — SYNTHETIC CAPABILITY PROBE ONLY — NO REAL BEACON CANDIDATE, SCORE, HOLDOUT, OR RESULT**

> **Zero Beacon-specific context is intentionally supplied to the blind
> decoder; unavoidable system context, model-training priors, minimum interface
> instructions, hidden backend behavior, and any unproven workspace or
> provider isolation remain disclosed limitations.**

## Candidate construction contract

Every later candidate record must declare exactly one manipulated variable and
must freeze before decoder exposure:

- one abstract semantic source shared across the generation;
- fixed nonframing content and order;
- a matched framing budget where framing is manipulated;
- one unique intended parse;
- exact reconstruction from the frozen source;
- surface novelty against declared prior artifacts;
- absence of leaked labels, answer structure, mapping, or solution cues; and
- one scorecard fixed before any decoder sees the candidate.

## Hard equivalence gate

An equivalence and construction auditor records each item as `PASS`, `FAIL`,
or `INDETERMINATE`. A candidate is eligible only when every required item is
`PASS`. Parse ambiguity, source mismatch, uncontrolled content change,
budget mismatch, solution-reconstruction failure, surface reuse, label leak,
or late scorecard change rejects the candidate before any decoder context is
created.

Rejected candidates are retained as design evidence but never reach the blind
decoder swarm. Rejection is not evidence that the underlying design family
can never work.

## Feedback boundary

Candidate-design subagents may receive only high-level frozen failure families
and declared constraints from earlier adaptive work. They must not receive raw
sealed confirmation outputs, sealed truth keys, score details, other active
candidates, or favored-result instructions. One-variable isolation remains
mandatory even when multiple improvements appear plausible.

## Common status

- Lifecycle: `Architecture prepared — real-candidate execution not authorized`
- Real Beacon candidate designs: `0`
- Real blind-decoder runs: `0`
- Real validity classifications: `0`
- Real scores: `0`
- Real score audits: `0`
- Adaptive generations: `0`
- Confirmation rounds: `0`
- Sealed validations: `0`
- New holdouts: `0`
- Provider-independent replications: `0`
- SIG-002 attempts: `0`
- Levels 5–9 analyses: `0`
- Carriers: `0`
- Transmissions: `0`
- Synthetic capability probes: `1`
- Authorized incremental spend: `USD 0`
