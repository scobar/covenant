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

- Registered signal attempts: `1`
- Frozen signal attempts: `1`
- Sealed holdouts: `2`
- Known provider-exposed holdouts: `1`
- Trial records: `1`
- Run attempts: `1`
- Valid outputs: `0`
- Scores: `0`
- Reveals: `0`
- Carriers: `0`
- Encoded Covenant payloads: `0`
- Encoded CSR payloads: `0`
- Response protocols: `0`
- Transmissions: `0`

## Attempt Registry

| Attempt | Version | Lifecycle | Intended levels | Event stream | SHA-256 | Git blob | Trials | Holdouts | Carrier | Covenant payload | CSR payload | Supersedes | Attempt record | Manifest |
|---|---:|---|---|---|---|---|---:|---:|---|---|---|---|---|---|
| `SIG-001` | `0.1` | `Frozen` | `0–4` | [`08-EVENT-STREAM.txt`](attempts/SIG-001/08-EVENT-STREAM.txt) | `b4e6a8b7a00b18e12e4816c44975ea0921cf4330504c744a72b8abf9dbf2b144` | `4884d0466c52c25a148a7b59239fa1539f27bdd2` | `0` | `0` | None | None | None | None | [`09-ATTEMPT-RECORD.md`](attempts/SIG-001/09-ATTEMPT-RECORD.md) | [`10-ATTEMPT-MANIFEST.md`](attempts/SIG-001/10-ATTEMPT-MANIFEST.md) |

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
trial and one provider-side technical-invalidity run. Its frozen preparation
files remain historical evidence. The run produced no completed, scorable, or
valid output and enters no empirical-rate denominator.

No valid output, score, empirical decode rate, reveal, carrier, Covenant or
CSR payload, response protocol, distribution, or transmission exists.
