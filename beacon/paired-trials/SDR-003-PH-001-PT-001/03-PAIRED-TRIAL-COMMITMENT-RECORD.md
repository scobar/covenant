# PTR-001 — Paired-Trial Preparation Commitment Record

> **PTR-001 v0.1 — GOOGLE GEMINI OPAQUE PAIRED TRIAL PREPARED — EXECUTION NOT AUTHORIZED**

## Identity

- Paired-trial package: PTR-001
- Version: 0.1
- Full trial ID: SDR-003-PH-001-PT-001
- Parent pair: SDR-003-PH-001
- Provider/configuration: Google Gemini web app; displayed model 3.1 Pro; Extended Thinking True; browser-incognito Temporary Chat
- Backend model identifier: Not exposed
- Authorized incremental spend: USD 0

## Public parent commitments

- Parent pair commitment: f140a6ac403a1183c56cedb4e2eeada4a4cd7d53be8979f5e2e21a88e3d2bd71
- Opaque Condition A packet commitment: e171c1d208e333b3c12025c8289c39d539d5126bcfffbfae859e442a946a5737
- Opaque Condition B packet commitment: dfd5480bb9d87e8f9f612c627048258cfdbac0135273e0ec32078e626bbd8870

These are the already-public SDR-003 commitments. They do not disclose the condition mapping or sealed packet contents.

## PTR-001 preparation commitment

- Algorithm: SHA-256 of the exact private nonce-bearing PTR-001 preparation preimage bytes
- Public PTR-001 preparation commitment: 1de6dcbed650450b046a950d87e989370601249ac2bd7a98f6dffeddf9a5184a
- Commitment created UTC: 2026-08-01T06:04:29Z

## Frozen counts

- Private files: 25
- Private dependencies: 23
- Prepared opaque condition trials: 2
- Valid outputs requested: 2
- Technical retries maximum: 1 per condition
- Substantive retries: 0
- Executions: 0
- Outputs: 0
- Validity classifications: 0
- Scores: 0
- Comparisons: 0
- Unblindings: 0
- SIG-002 attempts: 0

The commitment binds the prepared private package state, selected configuration, parent public commitments, frozen execution-order existence, retry limits, nonexecution state, creation time, and a private nonce. It helps detect later substitution when checked against the retained private material.

It does not reveal or prove the execution order, condition mapping, packet content, backend identity, provider isolation, retention behavior, randomness quality, future availability, successful execution, output validity, decoding performance, comparative effect, or moral authority. The commitment is not execution, empirical evidence, external validation, a public result, or SIG-002.
