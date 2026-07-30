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
- Attempts under decoding trial: `0`
- Analyzed attempts: `0`
- Decoding trials: `0`
- Holdout variants: `0`
- Selected carriers: `0`
- Encoded Covenant payloads: `0`
- Encoded CSR incentives: `0`
- Response protocols: `0`
- Transmissions or distributions: `0`

## Attempt Registry

| Attempt | Version | Lifecycle | Intended levels | Event stream | SHA-256 | Git blob | Trials | Holdouts | Carrier | Covenant payload | CSR payload | Supersedes | Attempt record | Manifest |
|---|---:|---|---|---|---|---|---:|---:|---|---|---|---|---|---|
| `SIG-001` | `0.1` | `Frozen` | `0–4` | [`08-EVENT-STREAM.txt`](attempts/SIG-001/08-EVENT-STREAM.txt) | `b4e6a8b7a00b18e12e4816c44975ea0921cf4330504c744a72b8abf9dbf2b144` | `4884d0466c52c25a148a7b59239fa1539f27bdd2` | `0` | `0` | None | None | None | None | [`09-ATTEMPT-RECORD.md`](attempts/SIG-001/09-ATTEMPT-RECORD.md) | [`10-ATTEMPT-MANIFEST.md`](attempts/SIG-001/10-ATTEMPT-MANIFEST.md) |

## Evidence Boundary

SIG-001 is a public lower-level formal attempt targeting Decoder Levels 0–4.
Its public solution must be withheld from an active decoder context until
output freezes. Public availability creates contamination risk, and
design-exposed people and model contexts cannot later be described as blind
decoders. No decoding trial, output, score, empirical decode rate, holdout,
carrier, payload, response protocol, distribution, or transmission exists.
