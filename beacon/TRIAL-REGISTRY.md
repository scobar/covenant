# Beacon Decoding-Trial Registry

> **LIVE NONCANONICAL TRIAL REGISTRY — TECHNICAL INVALIDITY IS NOT A VALID DECODER RESULT**

> **TR-002 CLOSED COMPLETE — ONE VALID PRIOR-EXPOSED OUTPUT — LEVELS 0–4 SCORE FROZEN — PRIVATE COMMITMENTS VERIFIED**

## Registry boundary

This live registry records preparation, run attempts, validity, closure, and
reveal separately from public signal attempts and sealed holdouts. A packet
commitment is not a decoder result. Provider-side processing can create
exposure and technical invalidity without producing a completed, scorable
output. Future models require distinct trial IDs and decisions.

## Current counts

- Registered trial records: `2`
- Active prepared trials: `0`
- Closed complete trials: `1`
- Closed incomplete trials: `1`
- Run attempts: `3`
- Valid runs: `1`
- Technical-invalidity runs: `2`
- Valid outputs: `1`
- Scores frozen: `1`
- Private reveal-stage verifications: `1`
- Public raw-output reveals: `0`
- Aggregate empirical decode rates: `0`

## Trial registry

| Trial ID | Parent attempt | Parent holdout | Provider | Displayed model label | Effort level | Interface | Lifecycle | Run attempts | Valid outputs | Score | Retry | Public raw-output reveal | Preparation or closure | Public result | Result manifest |
|---|---|---|---|---|---|---|---|---:|---:|---|---|---|---|---|---|
| `SIG-001-HO-001-TR-001` | `SIG-001 v0.1` | `SIG-001-HO-001 v0.1` | Anthropic | `Fable 5` | Not recorded separately | claude.ai standard Chat | `Closed incomplete — technical invalidity` | `1` | `0` | None | `Retired unused` | `No` | [Technical-invalidity and closure record](trials/SIG-001-HO-001-TR-001/05-TECHNICAL-INVALIDITY-AND-CLOSURE-RECORD.md) | None | [Closure manifest](trials/SIG-001-HO-001-TR-001/06-CLOSURE-MANIFEST.md) |
| `SIG-001-HO-002-TR-002` | `SIG-001 v0.1` | `SIG-001-HO-002 v0.1` | Anthropic | `Sonnet 5` | `High` | claude.ai standard Chat | `Closed complete — valid prior-exposed result` | `2` | `1` | `Levels 0–4 frozen` | `Used and exhausted` | `No` | [Frozen preparation manifest](trials/SIG-001-HO-002-TR-002/04-PUBLIC-TRIAL-PREPARATION-MANIFEST.md) | [Public result and closure record](trials/SIG-001-HO-002-TR-002/05-PUBLIC-RESULT-AND-CLOSURE-RECORD.md) | [Public result manifest](trials/SIG-001-HO-002-TR-002/06-PUBLIC-RESULT-MANIFEST.md) |

## Prepared Diagnostic Links

- TR-001 non-outcome diagnostic link:
  [DA-001 public charter](diagnostics/DA-001/00-PUBLIC-DIAGNOSTIC-CHARTER.md).
- TR-002 non-outcome diagnostic link:
  [DA-001 public charter](diagnostics/DA-001/00-PUBLIC-DIAGNOSTIC-CHARTER.md).
- [DA-001](DIAGNOSTIC-REGISTRY.md) is prepared and authorized, not executed.
  It reopens neither trial, changes no validity, score, or dissent, and
  authorizes no new run.

## Evidence boundary

The frozen preparation and closure files remain exact historical evidence.
TR-001 remains `Closed incomplete — technical invalidity`; its preserved
provider-visible partial trace remains private, non-scorable incident evidence.
It cannot receive a later inserted output.

TR-002 used one technically invalid run and its sole technical retry. RUN-002
is one valid but prior-exposed output. Technical-invalidity runs do not enter
valid denominators. TR-002 may enter only an exposure-stratified denominator.
The five categorical outcomes are not an aggregate rate. Public result
publication reveals neither raw output nor sealed contents.

Both trial records use Anthropic, so same-provider independence is not
established. Displayed model and effort labels are not independently verified
backend identities. One conditional datapoint is not a universal probability,
and no Levels 5–9, higher-layer, carrier, response, distribution, or
transmission conclusion follows.
