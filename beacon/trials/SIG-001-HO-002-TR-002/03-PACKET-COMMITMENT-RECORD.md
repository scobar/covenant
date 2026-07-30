# SIG-001-HO-002-TR-002 — Public Trial-Packet Commitment Record

> **PREPARED HOLDOUT DECODING TRIAL SIG-001-HO-002-TR-002 v0.1 — NONCANONICAL — NOT EXECUTED**

## Public commitment

- Trial ID: `SIG-001-HO-002-TR-002`
- Version: `0.1`
- Parent attempt: `SIG-001 v0.1`
- Parent holdout: `SIG-001-HO-002 v0.1`
- Provider: `Anthropic`
- Displayed model label: `Sonnet 5`
- Displayed effort level: `High`
- Backend model identifier: `Not exposed by claude.ai`
- Interface: `claude.ai standard Chat`
- Requested valid runs: `1`
- Maximum technical retries: `1`
- Substantive retries: `0`
- Authorized incremental spend: USD `0`
- Commitment algorithm:
  `SHA-256 over the exact private trial-packet commitment-preimage bytes`
- Public trial-packet commitment:
  `ba28060aa4672ec2eba477062ef6815134c0ebdb081f2d562cf55630905026c7`
- Commitment creation time: `2026-07-30T16:39:15.411Z`
- Private preparation-package files: `9`
- Private manifest dependency rows: `7`
- Future decoder packet files: `2`
- Executed runs: `0`
- Outputs: `0`
- Scores: `0`
- Reveals: `0`

The commitment is the sole authorized public private-package identity. No
other private identity, packet-file identity, private-manifest identity,
nonce, preimage, input, path, mapping, scorecard answer, example, query,
answer, solution, or stream identity is recorded here.

## What the commitment establishes

The commitment binds the exact private preparation manifest, frozen decoder
configuration, run and retry limits, cost boundary, and a fresh private nonce
through the exact private preimage. It helps detect later substitution.

Private custody-integrity verification is the custodian’s private,
nonrevealing recomputation that sealed files, manifests, preimages, and
commitments still match. It is required during preparation and immediately
before execution. It reveals no private content publicly, supplies no mapping,
solution, scorecard, preimage, private identity, or holdout content to the
decoder or pre-output-freeze scoring context, is not reveal-stage
verification, and creates no decoding result.

Reveal-stage commitment verification occurs only after the complete raw output
and complete score have frozen and authorized private materials are revealed.
Every mismatch or failed verification remains preserved. Verification cannot
retroactively alter the frozen output or score, and public recording requires
a later explicit decision.

The commitment does not prove:

- Correct private construction.
- Model identity.
- Effort implementation.
- Absence of hidden context.
- Provider isolation.
- Contamination freedom.
- Decodability.
- Independence.
- Moral authority.

## Current state and limitations

The private packet and decoder configuration are frozen. The public package is
prepared and authorized but not executed. HO-002 has never been supplied to a
decoder. No output, validity classification, score, reveal, or empirical
result exists.

Sonnet 5 / High was known prospectively before HO-002 generation, so
model-selection-blind chronology is not claimed. TR-001 used the same
provider, so same-provider independence is not established. The displayed
model and effort settings are not independently verified backend identities.
Incognito is a platform mode, not proof of absent hidden context. This trial
is contamination-reduced, not proven contamination-free.

Existing-subscription access and disabled paid spillover support the USD `0`
incremental-spend boundary but do not create evaluator independence. One model
run is one bounded datapoint. Success at Decoder Levels 0–4 would not
establish Levels 5–9. Failure would not establish universal undecodability.
No candidate, Covenant, CSR, physical, agency, response, carrier,
distribution, or transmission conclusion follows.
