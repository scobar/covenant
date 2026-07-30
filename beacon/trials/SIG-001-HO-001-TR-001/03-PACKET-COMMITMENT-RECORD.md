# SIG-001-HO-001-TR-001 — Public Trial-Packet Commitment Record

> **PREPARED HOLDOUT DECODING TRIAL SIG-001-HO-001-TR-001 v0.1 — NONCANONICAL — NOT EXECUTED**

## Public commitment

- Trial ID: `SIG-001-HO-001-TR-001`
- Version: `0.1`
- Parent holdout: `SIG-001-HO-001 v0.1`
- Provider: `Anthropic`
- Displayed model label: `Fable 5`
- Interface: `claude.ai standard Chat`
- Requested valid runs: `1`
- Maximum technical retries: `1`
- Substantive retries: `0`
- Authorized incremental spend: USD `0`
- Commitment algorithm:
  `SHA-256 over the exact private trial-packet commitment-preimage bytes`
- Public trial-packet commitment:
  `121b8741cc00e028280216a36d83b3781216852d5a4d52d441c4ab126e8da977`
- Commitment creation time: `2026-07-30T09:01:43.609Z`
- Private preparation-package files: `9`
- Private manifest dependency rows: `7`
- Future decoder packet files: `2`
- Executed trials: `0`
- Outputs: `0`
- Scores: `0`
- Reveals: `0`

The commitment is the sole authorized public private-package identity. No
other private identity, packet hash, private manifest identity, nonce,
preimage, instruction, sequence, path, mapping, scorecard answer, query,
answer, or solution is recorded here.

## What the commitment establishes

The commitment binds the exact private preparation manifest, frozen decoder
configuration, run and retry limits, cost boundary, and a fresh private nonce
through the exact private preimage.

Private custody-integrity verification is the custodian's private,
nonrevealing recomputation that sealed files, manifests, preimages, and
commitments still match. It is required during preparation and immediately
before execution. It reveals nothing publicly, supplies no mapping, solution,
scorecard, preimage, private identity, or holdout content to the decoder or
pre-output-freeze scoring context, is not reveal-stage verification, and
creates no decoding result.

Reveal-stage commitment verification is the formal comparison performed only
after the complete raw output and complete score have frozen. Under later
authorization, the relevant private preimages, manifests, mapping, solution,
and scorecard materials are revealed and compared with their public
commitments. Every mismatch or failed verification is preserved. Public
recording requires separate authorization, and verification cannot
retroactively change the frozen output or score.

The fixed order is: freeze the private configuration and packet; perform
private custody-integrity verification; publish and commit the public package;
reconfirm private custody-integrity verification immediately before
execution; execute exactly one permitted run; freeze the complete raw output
and metadata; classify validity and score; freeze the complete score; reveal
the authorized private materials; perform reveal-stage commitment
verification; preserve every mismatch, deviation, failure, and alternative
interpretation; and consider publication only through a later explicit
decision.

The commitment does not prove:

- Correct private construction.
- Model identity.
- Absence of hidden context.
- Contamination freedom.
- Decodability.
- Independence.
- Moral authority.

Preparation is complete only after all package audits pass. The decoder
configuration is frozen, but no decoder has received input. No execution,
output, score, reveal, or empirical result exists.

`Fable 5` is a displayed label rather than an independently verified backend
identifier. Claude Incognito Chat does not prove absent hidden context, and
promotional credit does not create independent evaluator diversity. One
future model run is one bounded datapoint. Success would not establish Levels
5–9; failure would not establish universal undecodability. No candidate,
Covenant, CSR, carrier, response, or transmission follows.
