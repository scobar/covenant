# SDR-003 — Opaque Conditions and Blinding Record

> **SDR-003 v0.1 — SURFACE-NOVEL OPAQUE PAIRED HOLDOUTS PRIVATELY FROZEN — NO PROVIDER, TRIAL, OUTPUT, SCORE, UNBLINDING, OR SIG-002 ATTEMPT**

## Identity and lifecycle

- Package: `SDR-003 v0.1`.
- Pair ID: `SDR-003-PH-001`.
- Parent: `SDR-002 v0.1`.
- Selected family: `Nested local framing signatures`.
- Lifecycle:
  `Surface-serialized opaque pair privately frozen — no provider or trial`.

## Opaque conditions

The sealed pair uses only `Condition A` and `Condition B` publicly. The
baseline/treatment mapping remains private. Both canonical streams and both
independent exact reconstructions froze before a fresh cryptographically
random assignment to the opaque labels. Assignment did not rename,
regenerate, select, or alter either canonical stream.

Both conditions use the same neutral instruction, the same shared surface
profile, the same Levels 0–4 scorecard, the same validity and contamination
rules, and condition-specific private solution keys. Exact-copy checks bind
each opaque condition to its privately mapped canonical stream.

## Required later chronology

Any later separately authorized paired trial must:

- use the same provider, displayed model, interface, effort, tool state, and
  configuration for both conditions;
- use a fresh isolated context per condition;
- randomize or counterbalance order under a frozen rule;
- allow one substantive output per condition and no substantive retry;
- freeze each output before condition-specific scoring;
- freeze both validity classifications and both condition-specific scores
  before unblinding; and
- prohibit favorable selection.

The future operator, decoder, and condition-specific scorer must not receive
the mapping before those freezes. No provider, model, trial, output, score,
comparison, or unblinding exists now.

## What blinding does and does not prove

Opaque labels reduce direct construction-role and scoring cues when the
private mapping remains controlled. They do not establish decoder ignorance,
provider independence, absence of recognition or retrieval, clean exposure,
representativeness, causal identification, decodability, success, moral
authority, acceptance, or canonicality.
