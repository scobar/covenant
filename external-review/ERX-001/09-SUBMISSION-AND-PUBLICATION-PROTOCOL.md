# ERX-001 — Submission, Consent, and Publication Protocol

> **DRAFT EXTERNAL-REVIEW PREPARATION PACKAGE v0.1 — NONCANONICAL — NO REVIEW EXECUTED**

> **ADMINISTRATOR MATERIAL — NO CURRENT SUBMISSION OR CONSENT RECORD**

This protocol prepares controls for a possible later external-review pilot. Only package preparation is authorized. Reviewer assignment, review execution, submission freezing, unblinding, publication, result integration, and any candidate-preference decision are separate stages and have not begun.

No reviewer has been recruited, contacted, or assigned. No label mapping,
mapping record, nonce, or mapping commitment has been created. No packet has
been assembled, no review has been executed, no response or result exists, and
no candidate preference exists. This package is not an evaluation. Preparing
or publishing it does not imply acceptance of either candidate or of the
Covenant. Any future external review would remain bounded evidence, not moral
authority, representativeness, consensus, or canonicality.

## Response freezing

Before unblinding or integration, the administrator must:

- Preserve the original response bytes.
- Calculate the response's raw SHA-256 and Git blob identity.
- Record its byte count, encoding, and line endings.
- Record the completion and freeze times.
- Preserve prompts, the raw packet bytes, and administrator-only exact
  source-packet identities.
- Record the applicable review ID, assignment ID, packet ID, neutral candidate
  label, neutral scenarios, package version, packet mapping commitment, and
  disclosure identity.
- Preserve the exact off-repository mapping record, its byte identity, its
  nonce, the commitment creation time, and randomization or counterbalancing
  evidence.
- Prevent silent editing of substantive content.

Candidate-specific responses must freeze before any paired comparison begins. A comparative response, if assigned, must freeze before unblinding. A freeze establishes provenance; it does not establish correctness, acceptance, publication authorization, or candidate preference.

Before unblinding, the response remains joined only to the opaque packet ID,
neutral packet labels, and mapping commitment. It must not be joined in a
reviewer-facing record to canonical candidate or scenario identities.

## Normalized display copy

If formatting normalization is needed:

- Preserve the raw response separately.
- Identify every normalization.
- Do not change substantive wording.
- Link the display copy to the raw response identity.
- Record identities for both raw and display files.
- Do not describe normalization as reviewer revision.

Examples of normalization that require disclosure include line-ending conversion, encoding conversion, layout-only heading repair, or removal of transport artifacts. Any ambiguity about whether a change is substantive must be resolved by retaining the original and seeking a reviewer correction rather than silently editing.

## Corrections

- Reviewer-requested corrections must be appended or versioned.
- Preserve the original record unless publication consent requires withholding it from publication.
- Link each correction to the response version it addresses.
- Record who requested the correction, when it was received, and whether it changes substantive content.
- Do not silently replace criticism or dissent.

Where the original cannot be published, retain its private provenance subject to the agreed privacy and retention terms; do not imply that a public display copy is the untouched raw submission.

## Unblinding

- Unblinding occurs only after all applicable candidate-specific responses and any assigned comparative response are frozen.
- Reveal the exact deterministic UTF-8/LF mapping record and its nonce only
  under later authorization.
- Recalculate SHA-256 over the revealed mapping-record bytes and record the
  commitment verification result.
- Record the mapping-record byte identity, commitment creation time, mapping
  reveal time, administrator, candidate-label and scenario-label mappings,
  and which participants were informed.
- Join a frozen response to canonical candidate and scenario identities only
  after that freeze, reveal, and verification.
- Keep the filled mapping outside the public repository while active procedural label blinding is in effect.
- Commit or publish a mapping only under separate authorization and with the applicable frozen response records.
- Unblinding does not change prior outcomes.

The repository and candidate texts are public and discoverable. Procedural label blinding reduces packet cues but cannot guarantee ignorance. Prior exposure, repository browsing, outside lookup, or inferred mapping must be disclosed and reflected in method classification. No actual mapping is created in this task.

The commitment can help detect post-hoc remapping. It does not prove fair
randomization, source truth, or reviewer ignorance, and it is not a blockchain
or source of moral authority.

## Privacy

- Keep contact information outside the repository.
- Minimize personal data.
- Use pseudonymous review identifiers when requested.
- Do not publish sensitive affiliation, disability, religious, political, or personal information without explicit consent.
- Separate conflict disclosure needed for interpretation from unnecessary personal detail.
- Review prompts, outputs, attachments, metadata, and normalization logs for unintended personal information.

Privacy minimization must not be used to erase substantive criticism. When de-identification affects context needed to interpret a conflict or method limitation, document the limitation without exposing unnecessary personal detail.

## Publication consent

- Confirm consent after the response is complete.
- Explain public Git permanence, copying, mirrors, and possible archival retention.
- Permit full, pseudonymous, de-identified, metadata-only, private-only, or declined publication.
- Record the authorized form and scope of publication.
- Do not equate nonpublication with invalidity.
- Do not publish a human response without confirmed consent.
- Reconfirm consent if a proposed display copy, correction, or contextual framing differs materially from what the reviewer previously saw.

Preparing or publishing this protocol does not publish a response and does not imply reviewer or candidate endorsement.

## Model outputs

For a model review, preserve the operator's publication authorization and the exact prompt/output provenance. Record the provider, interface, reported model identity, settings, tools, web access, source packet, retries, selection method, all valid outputs, and any invalid or failed runs. Operator authorization does not convert model output into assent or independent moral authority.

## Withdrawal

- A reviewer may withdraw before public commit.
- Before publication, the administrator must apply the agreed private-retention and deletion terms to withdrawn material.
- After public Git publication, complete erasure cannot be guaranteed.
- Later removal from the visible branch does not erase all copies, clones, caches, mirrors, quotations, or history.

These limits must be explained before a human reviewer gives publication consent.

## No current submission

No response, correction, consent record, withdrawal request, mapping,
mapping-record nonce, mapping commitment, packet, assignment, unblinding
record, or publication record exists in this task. This protocol does not
authorize the collection, publication, or integration of any such record.
