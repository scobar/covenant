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

- Registered trial records: `2`
- Active prepared trials: `1`
- Closed incomplete trials: `1`
- Run attempts: `1`
- Valid runs: `0`
- Technical-invalidity runs: `1`
- Valid outputs: `0`
- Scores frozen: `0`
- Reveals: `0`
- Empirical decode rates: `0`

## Trial registry

| Trial ID | Parent attempt | Parent holdout | Provider | Displayed model label | Effort level | Interface | Lifecycle | Run attempts | Valid outputs | Retry | Reveal status | Preparation | Closure record | Closure manifest |
|---|---|---|---|---|---|---|---|---:|---:|---|---|---|---|---|
| `SIG-001-HO-001-TR-001` | `SIG-001 v0.1` | `SIG-001-HO-001 v0.1` | Anthropic | `Fable 5` | Not recorded separately | claude.ai standard Chat | `Closed incomplete — technical invalidity` | `1` | `0` | `Retired unused` | `Not revealed` | [Frozen preparation manifest](trials/SIG-001-HO-001-TR-001/04-PUBLIC-TRIAL-PREPARATION-MANIFEST.md) | [Technical-invalidity and closure record](trials/SIG-001-HO-001-TR-001/05-TECHNICAL-INVALIDITY-AND-CLOSURE-RECORD.md) | [Closure manifest](trials/SIG-001-HO-001-TR-001/06-CLOSURE-MANIFEST.md) |
| `SIG-001-HO-002-TR-002` | `SIG-001 v0.1` | `SIG-001-HO-002 v0.1` | Anthropic | `Sonnet 5` | `High` | claude.ai standard Chat | `Prepared and authorized — not executed` | `0` | `0` | `Maximum one technical retry` | `Not revealed` | [Charter](trials/SIG-001-HO-002-TR-002/00-PUBLIC-TRIAL-CHARTER.md); [selection](trials/SIG-001-HO-002-TR-002/01-DECODER-SELECTION-RECORD.md); [execution](trials/SIG-001-HO-002-TR-002/02-EXECUTION-AND-FREEZE-PROTOCOL.md); [packet commitment](trials/SIG-001-HO-002-TR-002/03-PACKET-COMMITMENT-RECORD.md); [preparation manifest](trials/SIG-001-HO-002-TR-002/04-PUBLIC-TRIAL-PREPARATION-MANIFEST.md) | None | None |

## Evidence boundary

The frozen preparation files remain exact historical evidence. One run was
attempted with the exact packet. Anthropic’s safeguard interrupted
provider-side processing before a completed final response. The preserved
partial trace is private incident evidence, not a completed decoder output,
and is not scored.

The optional technical retry remains unused and is retired by D-024. No
Sonnet substitution occurred. TR-001 closes incomplete with zero valid
outputs, scores, reveals, or empirical results.

TR-002 is a distinct prepared and authorized record. It does not substitute
into or reopen TR-001, and TR-001 cannot receive a later inserted output.
Prepared does not mean executed, selected does not mean evaluated, and a
packet commitment is not a decoder result. Future trials remain distinct
records and require their own decisions, identities, and frozen packages.

HO-002 has never been supplied to a decoder. Sonnet 5 / High was known
prospectively before HO-002 generation, so model-selection-blind chronology is
not claimed. Both trial records use Anthropic, so same-provider independence
is not established.

Displayed model and effort labels are not independently verified backend
identities. Provider exposure does not prove successful decoding,
cross-session memory, cross-model transfer, retrieval, or training ingestion.
No lower-level, higher-layer, carrier, response, distribution, or transmission
conclusion follows.
