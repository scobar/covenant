# SIG-001-HO-001-TR-001 — Public Trial-Preparation Manifest

> **FROZEN PUBLIC TRIAL-PREPARATION MANIFEST v0.1 — NONCANONICAL — NOT EXECUTED**

> **PREPARED HOLDOUT DECODING TRIAL SIG-001-HO-001-TR-001 v0.1 — NONCANONICAL — NOT EXECUTED**

## Identity and boundary

- Trial ID: `SIG-001-HO-001-TR-001`
- Version: `0.1`
- Parent attempt: `SIG-001 v0.1`
- Parent holdout: `SIG-001-HO-001 v0.1`
- Provider: `Anthropic`
- Displayed model label: `Fable 5`
- Backend model identifier: `Not exposed by claude.ai`
- Interface: `claude.ai standard Chat`
- Conversation mode: new `Claude Incognito Chat`
- Lifecycle: `Prepared and authorized — not executed`
- Requested valid runs: `1`
- Technical-retry maximum: `1`
- Substantive retries: `0`
- Incremental-spend cap: USD `0`
- Public trial-packet commitment:
  `121b8741cc00e028280216a36d83b3781216852d5a4d52d441c4ab126e8da977`
- Executed trials: `0`
- Outputs: `0`
- Scores: `0`
- Reveals: `0`
- Empirical decode rate: None

Preparation is complete because the required private and final audits passed.
The decoder configuration and public commitment are frozen. No trial or
result exists.

## Public dependency manifest

This table lists exactly the other four public TR-001 preparation files. Raw
SHA-256 and no-filter Git blobs were computed from the exact dependency bytes.

| Relative path | Public role | Raw SHA-256 | No-filter Git blob | Byte count | Encoding | Line endings | Final newline |
|---|---|---|---|---:|---|---|---|
| `00-PUBLIC-TRIAL-CHARTER.md` | Records trial scope, identity, frozen decoder configuration, commitment architecture, chronology, limitations, and nonclaims. | `833e95b124ecadb61c7d8fe6bea289558ace28a8a5ef12a7a9e83e0423078710` | `959295a351ecfadf01dee1e9aa8b8e3e606d0a86` | `5935` | UTF-8 without BOM | LF only | Exactly one LF |
| `01-DECODER-SELECTION-RECORD.md` | Records exact observable decoder selection, zero-cost qualification, unavailable settings, and execution rechecks. | `abf9a3ba7924b8645d4bb9be79d917dd1f6d6d936dbebc3059b2b4318f34c504` | `75384eb2c2a751c661b0ba731cefd6b7429c2017` | `2988` | UTF-8 without BOM | LF only | Exactly one LF |
| `02-EXECUTION-AND-FREEZE-PROTOCOL.md` | Records nonrevealing preconditions, one-message delivery, one-run and retry rules, output preservation, and reveal chronology. | `8f115e9d1c3b55d0ea123bf8ce59380767738f9561bfc4bd1cd3f0cecfefa550` | `a143e717d278790fec3a4c9d70d5f541a39ac755` | `6087` | UTF-8 without BOM | LF only | Exactly one LF |
| `03-PACKET-COMMITMENT-RECORD.md` | Records the sole authorized public private-package identity, exact public counts, and commitment nonclaims. | `b985f944fc3adbd873dc719d9f21b3d88b5e75dfb7be0bf735f815cc3d6ddceb` | `fe781daa6393a218039bcc9654d8391826ee90a5` | `3807` | UTF-8 without BOM | LF only | Exactly one LF |

This manifest does not include its own identity. Its raw SHA-256, no-filter
Git blob, and byte count are recorded in `STATUS.md` and the secrecy-safe
completion report.

## Private/public boundary

- Private preparation-package files: `9`
- Private manifest dependency rows: `7`
- Future decoder packet files: `2`
- Public manifest dependency rows: `4`
- Other public private-package identity: None

No private identity appears here except the authorized public trial-packet
commitment. The manifest contains no private path, backup location,
packet-file identity, private manifest identity, nonce, preimage, instruction,
sequence, mapping, scorecard answer, query, solution, output, or score.

## Verification and chronology

Private custody-integrity verification is the custodian's private,
nonrevealing recomputation that sealed files, manifests, preimages, and
commitments still match. It is required during preparation and immediately
before execution. It exposes no private contents publicly or to the decoder or
pre-output-freeze scoring context, is not reveal-stage verification, and
creates no decoding result.

Reveal-stage commitment verification occurs only after the complete raw output
and complete score have frozen and after the relevant private preimages,
manifests, mapping, solution, and scorecard materials are revealed under later
authorization. Every mismatch or failed verification remains preserved.
Public recording requires separate authorization, and verification cannot
retroactively change the frozen output or score.

The fixed order is: freeze private configuration and packet; perform private
custody-integrity verification; publish and commit the public package;
reconfirm private custody-integrity verification immediately before
execution; execute exactly one permitted run; freeze the complete raw output
and metadata; classify validity and score; freeze the complete score; reveal
the authorized private materials; perform reveal-stage commitment
verification; preserve every mismatch, deviation, failure, and alternative
interpretation; and consider publication only through a later explicit
decision.

## Preparation audits

All audits were separate same-tooling, read-only preparation checks. They were
not decoding trials, external review, independent validation, model
evaluation, or empirical evidence.

### Audit A — terminology and chronology

**Result:** Pass.

Every applicable record must distinguish private custody-integrity
verification from reveal-stage commitment verification and preserve the fixed
twelve-stage chronology.

### Audit B — private packet preservation

**Result:** Pass.

Private custody-integrity verification must confirm that both packet files,
the parent package, the seven-row private manifest, the new public packet
commitment, and the absence of execution artifacts remain exact without
exposing private identities.

### Audit C — public secrecy

**Result:** Pass.

No public file may contain a private path, packet-file identity, private
manifest identity, nonce, preimage, mapping, solution, scorecard answer,
private query or answer, or any private identity except the authorized public
packet commitment.

### Audit D — nonexecution and frozen decoder configuration

**Result:** Pass.

Provider, displayed model label, interface, Incognito and tool-isolation
gates, USD `0`, one valid run, and one technical-retry maximum must remain
exact. No Claude conversation, upload, execution, output, score, reveal, or
empirical result may exist.

## Evidence limitations

`Fable 5` is a displayed UI label, not an independently verified backend
model identifier. Browser settings are partly hidden. Claude Incognito Chat
does not prove absent hidden context or training exposure. Promotional credit
avoids incremental project spending but does not create independent evaluator
diversity. Browser copy may not preserve hidden formatting or metadata.

One future same-provider, same-interface model run is one bounded datapoint.
Successful lower-level decoding would not establish Levels 5–9. Failure would
not establish universal undecodability. No candidate, Covenant, CSR, physical,
agency, choice, response, carrier, distribution, or transmission conclusion
follows.
