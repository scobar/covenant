# SDR-003 — Paired Holdout Commitment Record

> **SDR-003 v0.1 — SURFACE-NOVEL OPAQUE PAIRED HOLDOUTS PRIVATELY FROZEN — NO PROVIDER, TRIAL, OUTPUT, SCORE, UNBLINDING, OR SIG-002 ATTEMPT**

## Identity

- Package: `SDR-003 v0.1`.
- Pair ID: `SDR-003-PH-001`.
- Parent: `SDR-002 v0.1`.
- Parent SDR-002 design commitment:
  `0adc1c91c3de6ed23b1161b9a01d7a7caedb21f7536bdc84cd2654430fb41dba`.
- Selected family: `Nested local framing signatures`.
- Lifecycle:
  `Surface-serialized opaque pair privately frozen — no provider or trial`.
- Commitment algorithm: SHA-256 over exact UTF-8/LF private preimage bytes.

## Public commitments

- Condition A packet commitment:
  `e171c1d208e333b3c12025c8289c39d539d5126bcfffbfae859e442a946a5737`.
- Condition A commitment created UTC: `2026-08-01T00:15:57Z`.
- Condition B packet commitment:
  `dfd5480bb9d87e8f9f612c627048258cfdbac0135273e0ec32078e626bbd8870`.
- Condition B commitment created UTC: `2026-08-01T00:15:57Z`.
- Overall pair commitment:
  `f140a6ac403a1183c56cedb4e2eeada4a4cd7d53be8979f5e2e21a88e3d2bd71`.
- Overall pair commitment created UTC: `2026-08-01T00:15:57Z`.

## Frozen counts

- Private files: `22`.
- Private manifest dependencies: `18`.
- Serialized streams: `2`.
- Sealed unassigned holdouts: `2`.
- Providers: `0`.
- Trials: `0`.
- Outputs: `0`.
- Scores: `0`.
- Comparisons: `0`.
- Unblindings: `0`.
- SIG-002 attempts: `0`.

## Commitment limits

The condition commitments bind each private sequence and the shared
instruction without publishing either identity. The pair commitment binds the
private preparation state, both condition commitments, the frozen private
mapping state, and the zero-execution boundary.

These one-way commitments help detect later substitution. They do not prove
randomness quality, semantic equivalence, unique parsing, novelty, decoder
ignorance, provider isolation, clean exposure, decodability, treatment
benefit, empirical success, independent validation, acceptance, canonicality,
or moral authority. The private mapping, stream values and identities,
profile, generator, solutions, scorecard details, manifest identity,
preimages, and nonces remain unpublished.
