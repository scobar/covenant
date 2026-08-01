# Beacon Sealed-Holdout Registry

> **LIVE NONCANONICAL HOLDOUT REGISTRY — COMMITMENTS ARE NOT DECODING RESULTS**

> **TWO SEALED SIG-001 HOLDOUTS — TWO PROVIDER-EXPOSED — ONE VALID OUTPUT — ZERO PUBLIC RAW-CONTENT REVEALS**

> **TWO ADDITIONAL SDR-003 SUCCESSOR HOLDOUTS — VALID OUTPUTS FROZEN — PRIVATE CONDITION MAPPING**

## Registry Boundary

This live registry records sealed holdout variants separately from public
signal attempts. A holdout does not become a new signal-attempt lineage merely
because its surface representation differs. Registration and commitment do
not mean decoded, tested, scored, revealed, validated, accepted, canonical, or
independently verified.

## Current Counts

- Registered sealed holdouts: `2`
- Sealed and committed: `2`
- Known provider-exposed holdouts: `2`
- Never supplied to a decoder: `0`
- Under active trial: `0`
- Valid outputs: `1`
- Scores: `1`
- Private reveal-stage verifications: `1`
- Public raw-content reveals: `0`
- Diagnostic plans: `1`
- Executed diagnostics: `1`
- Frozen diagnostic results: `1`
- Signal redesigns: `0`
- Existing attempt-associated holdouts: `2`
- Successor paired holdouts: `2`
- Total sealed holdout artifacts: `4`
- Successor holdouts supplied to a provider: `2`
- Successor holdouts under trial: `0`
- Successor valid outputs: `2`
- Successor score-eligible outputs: `2`
- Successor denominator-eligible outputs: `2`
- Successor technical retries: `0`
- Successor scores: `0`
- Successor comparisons: `0`
- Successor mapping reveals: `0`

## Holdout Registry

| Parent attempt | Holdout ID | Version | Lifecycle | Intended levels | Exposure | Trial | Valid outputs | Score | Private commitment verification | Public raw reveal | Public commitment | Public charter | Commitment record | Public manifest |
|---|---|---:|---|---|---|---|---:|---|---|---|---|---|---|---|
| `SIG-001` | `SIG-001-HO-001` | `0.1` | `Sealed and committed` | `0–4` | `Known Anthropic provider-side exposure` | TR-001 closed incomplete | `0` | None | Not performed | `No` | `7776c5e763891725bc7c8d55a9c1f600b33e9d1c642a4d20f2cb433d94f6aed6` | [`00-PUBLIC-HOLDOUT-CHARTER.md`](holdouts/SIG-001-HO-001/00-PUBLIC-HOLDOUT-CHARTER.md) | [`01-COMMITMENT-RECORD.md`](holdouts/SIG-001-HO-001/01-COMMITMENT-RECORD.md) | [`02-PUBLIC-MANIFEST.md`](holdouts/SIG-001-HO-001/02-PUBLIC-MANIFEST.md) |
| `SIG-001` | `SIG-001-HO-002` | `0.1` | `Sealed and committed` | `0–4` | `Known Anthropic provider-side exposure` | [TR-002 closed complete](trials/SIG-001-HO-002-TR-002/05-PUBLIC-RESULT-AND-CLOSURE-RECORD.md) | `1` | `Levels 0–4 frozen` | `PASS` | `No` | `c8103cd2e80a2dc49309f1e1186817a75d97b8338950d726ffbc85e1127249b9` | [`00-PUBLIC-HOLDOUT-CHARTER.md`](holdouts/SIG-001-HO-002/00-PUBLIC-HOLDOUT-CHARTER.md) | [`01-COMMITMENT-RECORD.md`](holdouts/SIG-001-HO-002/01-COMMITMENT-RECORD.md) | [`02-PUBLIC-MANIFEST.md`](holdouts/SIG-001-HO-002/02-PUBLIC-MANIFEST.md) |

## Design-Stage Successor Pair

| Pair | Conditions | Lifecycle | Exposure | Trial | Mapping | Raw content public | Public records |
|---|---|---|---|---|---|---|---|
| `SDR-003-PH-001` | `A` and `B` | `Valid outputs frozen — isolated scoring authorized and not begun` | `Same-provider pair dependence` | PTR-001 execution complete; scoring authorized but not begun | Private | `No` | [Charter](SDR-003/00-PUBLIC-SERIALIZED-PAIR-CHARTER.md); [blinding record](SDR-003/01-OPAQUE-CONDITIONS-AND-BLINDING-RECORD.md); [commitment record](SDR-003/02-PAIRED-HOLDOUT-COMMITMENT-RECORD.md); [manifest](SDR-003/03-PUBLIC-SERIALIZED-PAIR-PREPARATION-MANIFEST.md) |

PTR-001 and D-033 add this preparation and manual-authorization state to the
successor pair without changing its sealed artifacts or commitments:

- Provider/configuration: selected under D-032
- Provider selected for future pair: `Google`
- Displayed model: `3.1 Pro`
- Extended Thinking: `True`
- Trial preparation: `PTR-001 prepared`
- Manual execution: complete under the frozen D-033 protocol
- Conditions supplied: `2`
- Valid outputs: `2`
- Technical retries: `0`
- Scoring: authorized but not begun
- Exposure: same-provider dependent; the first submitted condition records no
  prior-other-condition provider exposure, while the second submitted
  condition records prior-other-condition provider exposure, without
  associating submission order with an opaque label
- Trial run: `Complete; both validity freezes immutable`
- Mapping: `Private`
- Raw content public: `No`
- PTR-001 records: [charter](paired-trials/SDR-003-PH-001-PT-001/00-PUBLIC-PAIRED-TRIAL-CHARTER.md);
  [selection](paired-trials/SDR-003-PH-001-PT-001/01-PROVIDER-AND-MODEL-SELECTION-RECORD.md);
  [protocol](paired-trials/SDR-003-PH-001-PT-001/02-EXECUTION-AND-FREEZE-PROTOCOL.md);
  [commitment](paired-trials/SDR-003-PH-001-PT-001/03-PAIRED-TRIAL-COMMITMENT-RECORD.md);
  [preparation manifest](paired-trials/SDR-003-PH-001-PT-001/04-PUBLIC-PAIRED-TRIAL-PREPARATION-MANIFEST.md);
  [D-033 authorization](paired-trials/SDR-003-PH-001-PT-001/05-PUBLIC-PAIR-EXECUTION-AUTHORIZATION.md);
  [D-033 manifest](paired-trials/SDR-003-PH-001-PT-001/06-PUBLIC-PAIR-EXECUTION-AUTHORIZATION-MANIFEST.md);
  [D-034 scoring authorization](paired-trials/SDR-003-PH-001-PT-001/07-PUBLIC-ISOLATED-SCORING-AUTHORIZATION.md);
  [D-034 manifest](paired-trials/SDR-003-PH-001-PT-001/08-PUBLIC-ISOLATED-SCORING-AUTHORIZATION-MANIFEST.md).

The sealed pair content and its three public commitments remain unchanged.

The two successor conditions remain sealed artifacts and are not associated
with a public signal attempt. They now have two valid, score-eligible,
denominator-eligible outputs, but no score, comparison, mapping reveal,
unblinding, or public result. Their private mapping remains unavailable until
both condition-specific scores freeze, D-035 separately authorizes opaque
comparison, and a later decision separately authorizes mapping reveal.

## Trial and Exposure State

- [Live decoding-trial registry](TRIAL-REGISTRY.md)
- [Live diagnostic registry](DIAGNOSTIC-REGISTRY.md)
- [SIG-001-HO-001-TR-001 closure record](trials/SIG-001-HO-001-TR-001/05-TECHNICAL-INVALIDITY-AND-CLOSURE-RECORD.md)
- [SIG-001-HO-001-TR-001 closure manifest](trials/SIG-001-HO-001-TR-001/06-CLOSURE-MANIFEST.md)
- [SIG-001-HO-002-TR-002 public charter](trials/SIG-001-HO-002-TR-002/00-PUBLIC-TRIAL-CHARTER.md)

HO-001’s exact sequence reached Anthropic and received provider-side
processing before a safeguard interrupted the response. It remains immutable,
sealed, and publicly unrevealed, but it is now known provider-exposed. That
status is not proof of cross-session memory, cross-model transfer, training
ingestion, retrieval exposure, or successful decoding.

HO-002 remains immutable. It reached Anthropic during TR-002 RUN-001 and is
therefore classified as known Anthropic provider-side exposure. RUN-002
produced one valid but prior-exposed output and one frozen Levels 0–4 score.
Its public commitment was privately verified after score freeze. Public
commitment-verification status is published without revealing sealed content.
Provider exposure does not prove cross-session transfer.

Sonnet 5 / High was known prospectively before HO-002 generation, so
model-selection-blind chronology is not claimed. Because TR-001 and TR-002 use
Anthropic, same-provider independence is not established.

DA-001 was executed privately and is closed with one frozen diagnostic result.
It did not reveal either attempt-associated holdout publicly, and neither
holdout lifecycle, exposure class, score, or commitment changed. The later
SDR-003 pair contains two successor holdouts created under D-031. Their
private executions and D-034 scoring authorization create no public signal
attempt, comparison, mapping reveal, SIG-002, or signal redesign.

## Evidence and Secrecy Boundary

The registry stores no private stream, mapping, solution, scorecard answer,
nonce, commitment preimage, or private cryptographic identity. Each public
commitment is the sole authorized private-package identity for its holdout.
Commitments help detect later substitution but are not decoding results and
do not prove formal equivalence, randomness quality, decoder ignorance,
provider isolation, decodability, independence, or moral authority.
