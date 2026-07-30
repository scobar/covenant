# SIG-001-HO-001 — Public Holdout Manifest

> **FROZEN PUBLIC HOLDOUT MANIFEST v0.1 — NONCANONICAL — NO DECODING TRIAL EXECUTED**

> **SEALED HOLDOUT COMMITMENT SIG-001-HO-001 v0.1 — NONCANONICAL — NO DECODING TRIAL EXECUTED**

## Identity and Evidence Boundary

This frozen manifest identifies exactly the two public dependency files of the
SIG-001-HO-001 commitment package. It does not include its own identity or any
private-package identity. Raw SHA-256 and no-filter Git-style blob values were
computed from the exact dependency bytes.

## Public File Manifest

| Path | Role | Raw SHA-256 | No-filter Git blob | Byte count | Encoding | Line endings | Final newline |
|---|---|---|---|---:|---|---|---|
| `00-PUBLIC-HOLDOUT-CHARTER.md` | Public sealed-holdout scope, invariants, custody boundary, reveal order, and nonclaims. | `a28237527e0fbaf5ffbf81791c075391b85a4159a0a5096716b2e0b9b4e3f8ee` | `5e7a484caf93ab91af2eb18a8081aa72a91966e0` | `5106` | UTF-8 without BOM | LF only | Exactly one LF |
| `01-COMMITMENT-RECORD.md` | Public commitment identity, custody metadata, reveal conditions, counts, and omissions. | `b7c3d6f9481855d39a35faa1e3d8dcad287ddc226933a6bd8ef1a8b12c1d763e` | `092f53a6e32d5abc539e44050c4f0a1fb1213e2f` | `2747` | UTF-8 without BOM | LF only | Exactly one LF |

## Commitment and Counts

- Public commitment:
  `7776c5e763891725bc7c8d55a9c1f600b33e9d1c642a4d20f2cb433d94f6aed6`
- Parent attempt: `SIG-001`
- Holdout lifecycle: `Sealed and committed`
- Intended Decoder Levels: `0–4`
- Trials: `0`
- Outputs: `0`
- Scores: `0`
- Reveals: `0`
- Private package files: `10`
- Private manifest dependency rows: `8`

No secret private value appears in the public package. The public commitment
is the sole authorized private-package cryptographic identity.

## Same-Tooling Audits

These audits are same-tooling preparation and conformance checks. They are not
decoding trials, external review, or independent validation.

### Public Audit A — private semantic equivalence

- Result: `Pass`
- Reported publicly without private details.

### Public Audit B — trial neutrality and leakage

- Result: `Pass`
- Reported publicly without private details.

### Public Audit C — private stream reconstruction

- Result: `Pass`
- Reported publicly without private details.

### Public Audit D — commitment and public-secrecy integrity

- Result: `Pass`
- The public commitment matches the private preimage.
- The private package remains outside Git.
- Public files contain no secret.
- No decoder was selected and no trial occurred.

## Scope Boundary

This manifest records no private stream, mapping, solution, scorecard answer,
manifest identity, individual private-file identity, nonce, preimage, example,
query, or answer. It authorizes no decoder selection, model or provider
selection, execution, score, reveal, payload, response, carrier, distribution,
or transmission.
