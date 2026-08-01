# Beacon Signal-Attempt Registry

> **LIVE NONCANONICAL REGISTRY — ATTEMPTS ARE HISTORICAL EXPERIMENTS, NOT BEACON AUTHORITY**

## Registry Boundary

This registry records attempts created after the frozen BSR-001 research
snapshot. BSR-001's
[zero-attempt registry](BSR-001/03-SIGNAL-ATTEMPT-REGISTRY.md)
remains immutable historical evidence at its checkpoint. This live registry
records current attempt state without editing BSR-001.

An attempt is not decoded, validated, accepted, preferred, canonical, or
suitable for transmission merely because it is registered, first, current, or
Frozen. No attempt is preferred merely because it is first or current.

## Current Counts

- Signal attempts: `1`
- Frozen attempts: `1`
- Sealed holdouts: `2`
- Known provider-exposed holdouts: `2`
- Trial records: `2`
- Closed complete trials: `1`
- Closed incomplete trials: `1`
- Run attempts: `3`
- Valid outputs: `1`
- Scores: `1`
- Private reveal-stage verifications: `1`
- Public raw-output reveals: `0`
- Diagnostic plans: `1`
- Executed diagnostics: `1`
- Frozen diagnostic results: `1`
- Design-research packages: `3`
- Selected successor research targets: `1`
- Exact symbolic paired designs: `1`
- Serialized successor condition streams: `2`
- Sealed unassigned successor holdouts: `2`
- Successor provider/model selections: `1`
- Prepared successor paired trials: `2`
- Executed successor trials: `0`
- SIG-002 attempts: `0`
- Signal redesigns: `0`
- Aggregate empirical decode rates: `0`
- Carriers: `0`
- Covenant payloads: `0`
- CSR payloads: `0`
- Response protocols: `0`
- Transmissions: `0`

## Attempt Registry

| Attempt | Version | Lifecycle | Intended levels | Event stream | SHA-256 | Git blob | Trials | Holdouts | Carrier | Covenant payload | CSR payload | Supersedes | Attempt record | Manifest |
|---|---:|---|---|---|---|---|---:|---:|---|---|---|---|---|---|
| `SIG-001` | `0.1` | `Frozen` | `0–4` | [`08-EVENT-STREAM.txt`](attempts/SIG-001/08-EVENT-STREAM.txt) | `b4e6a8b7a00b18e12e4816c44975ea0921cf4330504c744a72b8abf9dbf2b144` | `4884d0466c52c25a148a7b59239fa1539f27bdd2` | `0` | `0` | None | None | None | None | [`09-ATTEMPT-RECORD.md`](attempts/SIG-001/09-ATTEMPT-RECORD.md) | [`10-ATTEMPT-MANIFEST.md`](attempts/SIG-001/10-ATTEMPT-MANIFEST.md) |

PTR-001 records one selected successor provider/model configuration and two
prepared opaque condition trials:
[public charter](paired-trials/SDR-003-PH-001-PT-001/00-PUBLIC-PAIRED-TRIAL-CHARTER.md)
and [preparation manifest](paired-trials/SDR-003-PH-001-PT-001/04-PUBLIC-PAIRED-TRIAL-PREPARATION-MANIFEST.md).
Provider selection and paired-trial preparation do not create an attempt.
Successor executions and SIG-002 attempts remain zero.

## Evidence Boundary

SIG-001 is a public lower-level formal attempt targeting Decoder Levels 0–4.
Its public solution must be withheld from an active decoder context until
output freezes. Public availability creates contamination risk, and
design-exposed people and model contexts cannot later be described as blind
decoders.

The [sealed-holdout registry](HOLDOUT-REGISTRY.md) records two later sealed
variants. SIG-001's frozen manifest and attempt row retain their historical
zero-holdout and zero-trial snapshot; this live registry records later state
without editing SIG-001. A holdout is not a new signal attempt, and a
commitment is not a decoding result.

The [decoding-trial registry](TRIAL-REGISTRY.md) records one closed incomplete
trial and one
[closed complete TR-002 result](trials/SIG-001-HO-002-TR-002/05-PUBLIC-RESULT-AND-CLOSURE-RECORD.md).
The frozen public result is bound by its
[public result manifest](trials/SIG-001-HO-002-TR-002/06-PUBLIC-RESULT-MANIFEST.md).
TR-002 contains one valid but prior-exposed, same-provider-dependent
conditional datapoint. It is not a universal probability.

The frozen SIG-001, HO-001, HO-002, TR-001, and TR-002 preparation manifests
retain their historical checkpoint counts unchanged. This live registry
records the later result without rewriting those records.

The [diagnostic registry](DIAGNOSTIC-REGISTRY.md) records DA-001 as executed
and closed. Its nonrevealing [result and closure
record](diagnostics/DA-001/04-PUBLIC-DIAGNOSTIC-RESULT-AND-CLOSURE-RECORD.md)
and frozen [result
manifest](diagnostics/DA-001/05-PUBLIC-DIAGNOSTIC-RESULT-MANIFEST.md) identify
controlled experiment classes but select no successor signal design.
Diagnostic preparation or closure is not a signal attempt, redesign, score
change, or new model run.

The [successor-design research
registry](DESIGN-RESEARCH-REGISTRY.md) preserves
[SDR-001](SDR-001/00-SUCCESSOR-DESIGN-RESEARCH-CHARTER.md) as frozen target-
selection research and records
[SDR-002](SDR-002/00-PUBLIC-EXACT-PAIR-CHARTER.md) as one privately frozen
exact symbolic pair under D-030 and
[SDR-003](SDR-003/00-PUBLIC-SERIALIZED-PAIR-CHARTER.md) as the later
surface-serialized opaque pair under D-031. `Nested local framing signatures`
was selected by a feasibility hard gate, not expected performance. The two
SDR-003 condition streams are sealed unassigned successor holdouts, not a
public attempt or valid-trial denominator. No public attempt, provider/model
selection, trial, output, score, comparison, unblinding, or SIG-002 follows
automatically.

One valid output, one frozen categorical Levels 0–4 score, and one private
reveal-stage verification exist. No aggregate empirical decode rate, public
raw-output reveal, carrier, Covenant or CSR payload, response protocol,
distribution, or transmission exists.
