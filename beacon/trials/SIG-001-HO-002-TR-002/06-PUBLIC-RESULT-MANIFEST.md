# SIG-001-HO-002-TR-002 — Public Result Manifest

> **FROZEN PUBLIC TR-002 RESULT MANIFEST v0.1 — NONCANONICAL — NO RAW OUTPUT OR PRIVATE HOLDOUT CONTENT PUBLISHED**

> **TR-002 CLOSED COMPLETE — ONE VALID PRIOR-EXPOSED OUTPUT — LEVELS 0–4 SCORE FROZEN — PRIVATE COMMITMENTS VERIFIED**

## Identity and final state

- Trial ID: `SIG-001-HO-002-TR-002`
- Version: `0.1`
- Final lifecycle: `Closed complete — valid prior-exposed result`
- Trial validity: `Valid but prior-exposed`
- Exposure class: `Nonspecific prior exposure`
- Denominator eligibility: `True — exposure-stratified only`
- Same-provider independence: `False`

## Run accounting

- Run attempts: `2`
- Technical-invalidity runs: `1`
- Valid runs: `1`
- Valid outputs: `1`
- Scores frozen: `1`
- Technical retries used: `1`
- Retry capacity: exhausted
- Follow-up messages: `0`
- Model substitutions: `0`

## Public dependency manifest

This table lists exactly one dependency. Raw SHA-256 and the no-filter Git blob
were computed from the exact dependency bytes.

| Relative path | Public role | Raw SHA-256 | No-filter Git blob | Byte count | Encoding | Line endings | Final newline |
|---|---|---|---|---:|---|---|---|
| [`05-PUBLIC-RESULT-AND-CLOSURE-RECORD.md`](05-PUBLIC-RESULT-AND-CLOSURE-RECORD.md) | Records the nonrevealing frozen categorical result, validity and exposure class, verification status, methodological limits, and permanent closure. | `a1bd794d1569d9baf00b5244b5797facf8055d4f1376147f2a80ae9cd964fd2c` | `65a65294502b69e87b87d509a20e348ad50e9c39` | `4655` | UTF-8 without BOM | LF only | Exactly one LF |

This manifest does not include its own identity. Its raw SHA-256, no-filter
Git blob, and byte count are recorded in `STATUS.md` and the secrecy-safe
completion report.

## Frozen categorical result

```text
LEVEL_0=Recovered
LEVEL_1=Not recovered
LEVEL_2=Partially recovered
LEVEL_3=Not recovered
LEVEL_4=Not recovered
NO_AGGREGATE_SCORE=True
LEVELS_5_TO_9_SCORED=False
```

## Verification status

```text
HO002_COMMITMENT_VERIFICATION=PASS
HO002_DEPENDENCIES=8/8
TR002_PACKET_COMMITMENT_VERIFICATION=PASS
TR002_DEPENDENCIES=7/7
PACKET_SOURCE_EQUALITY=2/2
SCORE_IMMUTABILITY=PASS
PUBLIC_RAW_OUTPUT_REVEAL=False
```

Both commitment verifications occurred after score freeze. No verification
altered output, validity, score, or preserved dissent. No aggregate score
exists, and Levels 5–9 are unscored.

## Public-integration audits

These were same-tooling, read-only public-integration checks, not external
independent validation.

- Audit A — private-to-public transcription: `PASS`
- Audit B — public secrecy: `PASS`
- Audit C — registry and status consistency: `PASS`
- Audit D — protected evidence and scope: `PASS`

The audits confirmed the frozen run accounting, validity, exposure, five
categorical outcomes, verification status, protected evidence, and authorized
public scope without publishing private details.

## Public and scope boundary

- No raw decoder output is public.
- No sealed holdout content is public.
- No private content or private identity is included.
- No criterion or query counts are included.
- No aggregate result exists.
- No result exists for Levels 5–9.
- No new trial or signal attempt was created.
- No post-hoc diagnostic analysis, rescoring, higher layer, carrier,
  distribution, or transmission was performed or authorized.
