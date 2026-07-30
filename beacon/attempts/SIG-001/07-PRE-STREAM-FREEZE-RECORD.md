# SIG-001 — Pre-Stream Design Freeze Record

> **FROZEN PRE-STREAM DESIGN RECORD — CREATED BEFORE THE SIG-001 EVENT STREAM**

## Identity

- Date: `2026-07-29`
- Intended attempt ID: `SIG-001`
- Intended version: `0.1`
- Decision reference: D-021
- Event stream at freeze time: None
- Live-registry entry at freeze time: None
- Model or human decoding trials at freeze time: `0`

## Frozen Pre-Stream Files

These identities were computed from raw working-file bytes before
`08-EVENT-STREAM.txt` existed. Git blobs were computed without filters.

| Path | Raw SHA-256 | No-filter Git blob | Byte count | Encoding | Line endings | Final newline |
|---|---|---|---:|---|---|---|
| [`00-ATTEMPT-CHARTER.md`](00-ATTEMPT-CHARTER.md) | `ceb68cb24e37f3f737b718f7d9e50666ed4d2f781b8dd08a3922916476b63461` | `d72feb7ffab8d70ec92520ff51d23222cc41990b` | `4070` | UTF-8 without BOM | LF only | Exactly one LF |
| [`01-RECEIVER-ASSUMPTIONS.md`](01-RECEIVER-ASSUMPTIONS.md) | `3b37eb9dce2f7c2de0780822650dd95016ac1367b438b111f06b414007d75096` | `d115fcb65f3d2af6e93e4a4413ac866b71d5f979` | `9156` | UTF-8 without BOM | LF only | Exactly one LF |
| [`02-EVENT-MODEL-AND-FRAMING.md`](02-EVENT-MODEL-AND-FRAMING.md) | `6ce14c98412448d0f589c73a00c4cbb0f96295639feb5c073a83d3bcdf6cae14` | `39cac04a9f2e0b28a0d3bf09e60d87ba1fedf0be` | `4258` | UTF-8 without BOM | LF only | Exactly one LF |
| [`03-FORMAL-LANGUAGE-SPECIFICATION.md`](03-FORMAL-LANGUAGE-SPECIFICATION.md) | `e63caa0d93a979519ef259c815fbeb4778a3224008e44572d59f68deb94a442c` | `bf7795418d1542fa1d6e43506b9d0724f59a0f9c` | `7331` | UTF-8 without BOM | LF only | Exactly one LF |
| [`04-PRETRIAL-SCORECARD.md`](04-PRETRIAL-SCORECARD.md) | `1bd0bfedb2c84645a195b04db2628873f0b78abb0b934461748e38cc44ec416a` | `8a1c3e03ec83251ba3470d8c73ab1d3861aef12e` | `11060` | UTF-8 without BOM | LF only | Exactly one LF |
| [`05-TRIAL-VALIDITY-AND-CONTAMINATION.md`](05-TRIAL-VALIDITY-AND-CONTAMINATION.md) | `54138947ac89b724fd48820f8d2ac763ab85dadd69d4a870689c28560043d81b` | `08cdad6a0fa6a6d70aca56e70a80b64a88ff0b7a` | `8292` | UTF-8 without BOM | LF only | Exactly one LF |
| [`06-SOLUTION-AND-QUERY-KEY.md`](06-SOLUTION-AND-QUERY-KEY.md) | `d2b809f9a1e8582c920a4f3956b5cc31ae11ddd58735c04b6ca83c38400b291d` | `4f0f42a04ee97fecf0ffee07e6aed01b7e28215b` | `9086` | UTF-8 without BOM | LF only | Exactly one LF |

## Pre-Stream Audits

### Audit A — Scorecard and Validity

**Result:** Pass after pre-freeze correction and complete fresh rerun.

A fresh, separate, read-only Codex context checked scorecard completeness,
objective threshold boundaries, exact query answers, trial-validity and
contamination precedence, retry rules, output freezing, solution withholding,
and the prohibition on retroactive weakening. The final rerun found no
confirmed defect. Exactly Decoder Levels 0–4 are scored; Levels 5–9 are not.
No private chain-of-thought is requested.

### Audit B — Signal Architecture and Layer Boundary

**Result:** Pass after pre-freeze correction and complete fresh rerun.

A different fresh, read-only Codex context checked deterministic construction,
event-class arbitrariness, noncolliding boundaries, unique fixed-arity parses,
the fourteen supplied records, Q1–Q7, receiver assumptions, Earth-language
exclusion from the future stream, higher-layer exclusions, and contamination
visibility. The final rerun found no confirmed defect.

Both audits were same-tooling design audits without a target conclusion. They
were not decoding trials, external review, or independent validation. Neither
context edited a file or executed a prompt against an event stream.

## Chronology Proof

Immediately before this record was created:

- Files 00 through 06 existed with the exact identities above.
- `08-EVENT-STREAM.txt` did not exist.
- `beacon/SIGNAL-ATTEMPT-REGISTRY.md` did not exist.
- No signal attempt had been added to a live registry.
- No model or human decoder had been selected.
- No decoding prompt, packet, run, output, score, or empirical result existed.

The receiver assumptions, event model, formal-language specification,
scorecard, trial-validity and contamination policy, and solution key therefore
froze before the event stream.

## Immutability Rule

Files 00 through 07 are frozen as the pre-stream design record. Their bytes
must not be revised, weakened, reweighted, or reinterpreted to fit the later
generated stream or any decoder output. A post-stream defect requires stopping
and preserving the defect; it may not be silently repaired in this attempt.

`Frozen` identifies exact historical signal evidence. It does not mean
decoded, successful, validated, accepted, canonical, or suitable for
transmission. The eventual repository serialization and solution are public,
so future contamination is possible. The solution must still be withheld from
an actual decoder context until its output freezes. Scott Barbian, ChatGPT,
Codex, and every design-exposed context are known contaminated for blind
exact-SIG-001 decoding. No one has decoded SIG-001 in a valid trial, and no
empirical decode rate exists.
