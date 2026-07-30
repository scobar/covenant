# Beacon Sealed-Holdout Registry

> **LIVE NONCANONICAL HOLDOUT REGISTRY — COMMITMENTS ARE NOT DECODING RESULTS**

> **SEALED HOLDOUT COMMITMENT SIG-001-HO-001 v0.1 — NONCANONICAL — NO DECODING TRIAL EXECUTED**

## Registry Boundary

This live registry records sealed holdout variants separately from public
signal attempts. A holdout does not become a new signal-attempt lineage merely
because its surface representation differs. Registration and commitment do
not mean decoded, tested, scored, revealed, validated, accepted, canonical, or
independently verified.

## Current Counts

- Registered sealed holdout variants: `1`
- Sealed and committed: `1`
- Under trial: `0`
- Prepared trial records: `1`
- Executed trials: `0`
- Outputs: `0`
- Scores: `0`
- Reveals: `0`
- Outputs frozen: `0`
- Scored: `0`
- Revealed: `0`
- Archived: `0`

## Holdout Registry

| Parent attempt | Holdout ID | Version | Lifecycle | Intended levels | Public commitment | Trial count | Reveal status | Public charter | Commitment record | Public manifest |
|---|---|---:|---|---|---|---:|---|---|---|---|
| `SIG-001` | `SIG-001-HO-001` | `0.1` | `Sealed and committed` | `0–4` | `7776c5e763891725bc7c8d55a9c1f600b33e9d1c642a4d20f2cb433d94f6aed6` | `0` | `Unrevealed` | [`00-PUBLIC-HOLDOUT-CHARTER.md`](holdouts/SIG-001-HO-001/00-PUBLIC-HOLDOUT-CHARTER.md) | [`01-COMMITMENT-RECORD.md`](holdouts/SIG-001-HO-001/01-COMMITMENT-RECORD.md) | [`02-PUBLIC-MANIFEST.md`](holdouts/SIG-001-HO-001/02-PUBLIC-MANIFEST.md) |

## Prepared trial

- [Live decoding-trial registry](TRIAL-REGISTRY.md)
- [SIG-001-HO-001-TR-001 public charter](trials/SIG-001-HO-001-TR-001/00-PUBLIC-TRIAL-CHARTER.md)

One exact decoder configuration and private packet are prepared and
authorized, but no execution has occurred. Decoder selection and packet
preparation do not reveal the holdout. The lifecycle remains
`Sealed and committed`.

## Evidence and Secrecy Boundary

The registry stores no private stream, mapping, solution, scorecard answer,
nonce, commitment preimage, or private cryptographic identity. The public
commitment is the only private-package cryptographic identity recorded here.
It helps detect later substitution but is not a decoding result and does not
prove formal equivalence, fair randomization, decoder ignorance, no prior
training exposure, decodability, independence, or moral authority.
