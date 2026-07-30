# Beacon Sealed-Holdout Registry

> **LIVE NONCANONICAL HOLDOUT REGISTRY — COMMITMENTS ARE NOT DECODING RESULTS**

> **TWO SEALED SIG-001 HOLDOUTS — ONE PROVIDER-EXPOSED — ZERO VALID OUTPUTS OR REVEALS**

## Registry Boundary

This live registry records sealed holdout variants separately from public
signal attempts. A holdout does not become a new signal-attempt lineage merely
because its surface representation differs. Registration and commitment do
not mean decoded, tested, scored, revealed, validated, accepted, canonical, or
independently verified.

## Current Counts

- Registered sealed holdouts: `2`
- Sealed and committed: `2`
- Known provider-exposed holdouts: `1`
- Never supplied to a decoder: `1`
- Under active trial: `0`
- Valid outputs: `0`
- Scores: `0`
- Reveals: `0`

## Holdout Registry

| Parent attempt | Holdout ID | Version | Lifecycle | Intended levels | Exposure | Trial preparation | Completed valid outputs | Public reveal | Public commitment | Public charter | Commitment record | Public manifest |
|---|---|---:|---|---|---|---|---:|---|---|---|---|---|
| `SIG-001` | `SIG-001-HO-001` | `0.1` | `Sealed and committed` | `0–4` | `Known Anthropic provider-side exposure` | TR-001 closed incomplete | `0` | `No` | `7776c5e763891725bc7c8d55a9c1f600b33e9d1c642a4d20f2cb433d94f6aed6` | [`00-PUBLIC-HOLDOUT-CHARTER.md`](holdouts/SIG-001-HO-001/00-PUBLIC-HOLDOUT-CHARTER.md) | [`01-COMMITMENT-RECORD.md`](holdouts/SIG-001-HO-001/01-COMMITMENT-RECORD.md) | [`02-PUBLIC-MANIFEST.md`](holdouts/SIG-001-HO-001/02-PUBLIC-MANIFEST.md) |
| `SIG-001` | `SIG-001-HO-002` | `0.1` | `Sealed and committed` | `0–4` | `Never supplied to a decoder` | None | `0` | `No` | `c8103cd2e80a2dc49309f1e1186817a75d97b8338950d726ffbc85e1127249b9` | [`00-PUBLIC-HOLDOUT-CHARTER.md`](holdouts/SIG-001-HO-002/00-PUBLIC-HOLDOUT-CHARTER.md) | [`01-COMMITMENT-RECORD.md`](holdouts/SIG-001-HO-002/01-COMMITMENT-RECORD.md) | [`02-PUBLIC-MANIFEST.md`](holdouts/SIG-001-HO-002/02-PUBLIC-MANIFEST.md) |

## Trial and Exposure State

- [Live decoding-trial registry](TRIAL-REGISTRY.md)
- [SIG-001-HO-001-TR-001 closure record](trials/SIG-001-HO-001-TR-001/05-TECHNICAL-INVALIDITY-AND-CLOSURE-RECORD.md)
- [SIG-001-HO-001-TR-001 closure manifest](trials/SIG-001-HO-001-TR-001/06-CLOSURE-MANIFEST.md)

HO-001’s exact sequence reached Anthropic and received provider-side
processing before a safeguard interrupted the response. It remains immutable,
sealed, and publicly unrevealed, but it is now known provider-exposed. That
status is not proof of cross-session memory, cross-model transfer, training
ingestion, retrieval exposure, or successful decoding.

HO-002 was generated mechanically without the Fable partial trace and has
never been supplied to a decoder. Sonnet 5 / High was known prospectively
before its generation, so model-selection-blind chronology is not claimed.
No Sonnet trial is selected or prepared.

## Evidence and Secrecy Boundary

The registry stores no private stream, mapping, solution, scorecard answer,
nonce, commitment preimage, or private cryptographic identity. Each public
commitment is the sole authorized private-package identity for its holdout.
Commitments help detect later substitution but are not decoding results and
do not prove formal equivalence, randomness quality, decoder ignorance,
provider isolation, decodability, independence, or moral authority.
