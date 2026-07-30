# Beacon Decoding-Trial Registry

> **LIVE NONCANONICAL TRIAL REGISTRY — TECHNICAL INVALIDITY IS NOT A VALID DECODER RESULT**

> **TR-001 CLOSED INCOMPLETE — ONE TECHNICAL-INVALIDITY RUN — NO VALID DECODER OUTPUT**

## Registry boundary

This live registry records preparation, run attempts, validity, closure, and
reveal separately from public signal attempts and sealed holdouts. A packet
commitment is not a decoder result. Provider-side processing can create
exposure and technical invalidity without producing a completed, scorable
output. Future models require distinct trial IDs and decisions.

## Current counts

- Registered trial records: `1`
- Active prepared trials: `0`
- Closed incomplete trials: `1`
- Run attempts: `1`
- Valid runs: `0`
- Technical-invalidity runs: `1`
- Valid outputs: `0`
- Scores frozen: `0`
- Reveals: `0`
- Empirical decode rates: `0`

## Trial registry

| Trial ID | Parent attempt | Parent holdout | Provider | Displayed model label | Interface | Lifecycle | Run attempts | Valid outputs | Retry | Reveal status | Preparation | Closure record | Closure manifest |
|---|---|---|---|---|---|---|---:|---:|---|---|---|---|---|
| `SIG-001-HO-001-TR-001` | `SIG-001 v0.1` | `SIG-001-HO-001 v0.1` | Anthropic | `Fable 5` | claude.ai standard Chat | `Closed incomplete — technical invalidity` | `1` | `0` | `Retired unused` | `Not revealed` | [Frozen preparation manifest](trials/SIG-001-HO-001-TR-001/04-PUBLIC-TRIAL-PREPARATION-MANIFEST.md) | [Technical-invalidity and closure record](trials/SIG-001-HO-001-TR-001/05-TECHNICAL-INVALIDITY-AND-CLOSURE-RECORD.md) | [Closure manifest](trials/SIG-001-HO-001-TR-001/06-CLOSURE-MANIFEST.md) |

## Evidence boundary

The frozen preparation files remain exact historical evidence. One run was
attempted with the exact packet. Anthropic’s safeguard interrupted
provider-side processing before a completed final response. The preserved
partial trace is private incident evidence, not a completed decoder output,
and is not scored.

The optional technical retry remains unused and is retired by D-024. No
Sonnet substitution occurred. TR-001 closes incomplete with zero valid
outputs, scores, reveals, or empirical results.

The displayed model label is not an independently verified backend model ID.
Provider exposure does not prove successful decoding, cross-session memory,
cross-model transfer, retrieval, or training ingestion. No lower-level,
higher-layer, carrier, response, distribution, or transmission conclusion
follows.
