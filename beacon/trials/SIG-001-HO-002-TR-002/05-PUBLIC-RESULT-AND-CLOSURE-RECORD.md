# SIG-001-HO-002-TR-002 — Public Result and Closure Record

> **TR-002 CLOSED COMPLETE — ONE VALID PRIOR-EXPOSED OUTPUT — LEVELS 0–4 SCORE FROZEN — PRIVATE COMMITMENTS VERIFIED**

## Identity and configuration

- Trial ID: `SIG-001-HO-002-TR-002`
- Version: `0.1`
- Parent attempt: `SIG-001 v0.1`
- Parent holdout: `SIG-001-HO-002 v0.1`
- Provider: `Anthropic`
- Displayed model label: `Sonnet 5`
- Displayed effort level: `High`
- Interface: `claude.ai standard Chat`
- Backend model identity: Not exposed by claude.ai
- Incremental spend: USD `0`
- Prior lifecycle: `Prepared and authorized — not executed`
- Final lifecycle: `Closed complete — valid prior-exposed result`

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
- Public raw-output reveals: `0`

RUN-001 was `Invalid — technical`. RUN-002 was completed and valid but
prior-exposed. No third run is authorized. The technically invalid first run
is excluded from the valid denominator. The second run enters only an
exposure-stratified denominator.

## Validity and exposure

```text
TRIAL_VALIDITY=Valid but prior-exposed
EXPOSURE_CLASS=Nonspecific prior exposure
DENOMINATOR_ELIGIBLE=True — exposure-stratified only
SAME_PROVIDER_INDEPENDENCE=False
```

HO-002 reached Anthropic during RUN-001 before RUN-002. Incognito does not
prove provider isolation. Prior exposure does not prove cross-session transfer.
Prior exposure does not invalidate the completed run under the frozen policy.
This record does not claim no-known-exposure evidence.

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

The decoder recovered the artificiality/observable-structure level. It
partially recovered quantity and structured numeracy. It did not recover the
frozen framing/hierarchy level, the frozen relations/arithmetic level, or the
frozen grammar/logic/query-recovery level.

This is one valid but prior-exposed, same-provider-dependent conditional
datapoint. It is not a universal probability of decodability or
undecodability. Level 0 recovery does not imply Level 1–4 recovery. Level 2
partial recovery despite Level 1 nonrecovery is not treated as an aggregate
contradiction; levels are criterion-specific. No result exists for Levels
5–9. No Covenant, moral, agency, physical-reference, shared-model, response,
carrier, distribution, or transmission inference follows.

- Primary score audit: `PASS WITH PRESERVED DISSENT`
- The independent same-tooling scorer reproduced the same five categorical
  outcomes.
- Existing dissent remains private and unchanged.
- The audit was same-tooling, not external independent validation.

No criterion counts, query counts, private excerpts, or individual answers are
published.

## Reveal-stage verification

```text
HO002_COMMITMENT_VERIFICATION=PASS
HO002_DEPENDENCIES=8/8
TR002_PACKET_COMMITMENT_VERIFICATION=PASS
TR002_DEPENDENCIES=7/7
PACKET_SOURCE_EQUALITY=2/2
SCORE_IMMUTABILITY=PASS
REVEAL_AUDIT=PASS — exact agreement
PUBLIC_RAW_HOLDOUT_REVEAL=False
```

The authorized private reveal occurred only after complete score freeze. Both
public commitments recomputed exactly. Reveal-stage verification did not alter
output, validity, score, or dissent. Private values remain private. Public
integration reports verification status, not sealed contents.

## Methodological limits

- This is one valid prior-exposed trial.
- The technically invalid first run and the valid retry used the same
  provider.
- Model and effort are displayed UI labels, not verified backend identities.
- Sonnet qualification preceded HO-002 generation.
- Same-provider and model-selection-blind independence are not claimed.
- Incognito does not prove absence of hidden provider context.
- Browser-copy output may omit hidden formatting or metadata.
- Same-tooling scoring and audits are not external independent validation.
- One trial cannot establish a universal probability.
- No Levels 5–9 conclusion follows.
- No Covenant or higher-layer conclusion follows.

## Closure

TR-002 is permanently closed under D-026. No output may be replaced or
inserted. No retry remains. No public raw response publication is authorized.
Future post-hoc diagnostic analysis requires a separate decision. SIG-002 or
another attempt requires a separate decision. No carrier, distribution, or
transmission follows.
