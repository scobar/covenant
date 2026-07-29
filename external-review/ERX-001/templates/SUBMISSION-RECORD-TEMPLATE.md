# ERX-001 — Submission Record Template

**DRAFT EXTERNAL-REVIEW PREPARATION PACKAGE v0.1 — NONCANONICAL — NO REVIEW EXECUTED**

**BLANK ADMINISTRATOR TEMPLATE**

No field is populated in this task. This template creates no reviewer,
assignment, mapping, mapping nonce, mapping commitment, packet, response,
consent record, review result, publication, integration record, or candidate
preference.

Package preparation is the only authorized stage. Response freezing,
unblinding, consent and privacy review, publication, result integration, and
any preference decision remain separate future stages.

## Record Identity

- Review ID:
- Assignment ID:
- Packet ID:
- Method class:
- Reviewer disclosure hash:
- Packet version:
- Packet mapping commitment:

## Opaque Assigned Identities at Response Freeze

- Candidate label:
- Candidate alias filename:
- Neutral scenario labels:
- Neutral scenario alias filenames:

Before unblinding, this record binds the response only to the opaque packet
ID, neutral labels and aliases, packet version, and mapping commitment. It
must not require canonical candidate or scenario identities or raw hashes of
exact alias files in reviewer-facing fields.

## Response Identities

- Raw candidate-specific response path and hash:
- Display-copy path and hash:
- Comparative response path and hash:
- Prompt files and hashes:
- Model settings, if applicable:
- Raw packet path and byte identity preserved after response freezing:

## Administrator-Only Mapping Evidence

- Mapping-record byte identity:
- Mapping-record raw SHA-256:
- Mapping-record byte count:
- Mapping-record encoding: UTF-8
- Mapping-record line endings: LF
- Mapping-record Git blob, if later preservation policy requires one:
- Mapping nonce — fresh, unpredictable, at least 128 bits:
- Mapping commitment — SHA-256 over the exact mapping-record bytes:
- Commitment creation time:
- Mapping reveal time:
- Commitment verification result:
- Randomization or counterbalancing record identity:

The exact mapping record, nonce, canonical source identities, and
randomization evidence remain outside the repository during active review.
Preserve the raw mapping and packet evidence after all applicable responses
freeze, subject to authorized privacy and retention controls.

## Stage Times

- Candidate-specific freeze time:
- Comparative freeze time:
- Unblinding time:

## Post-Freeze Canonical Join

- Internal candidate identity:
- Canonical candidate path, raw SHA-256, and Git blob:
- Canonical scenario IDs, paths, raw SHA-256 values, and Git blobs:
- Canonical source-byte verification result:
- Canonical join time:
- Join administrator or verifier:

A filled internal mapping must remain outside the repository while the review
is active. Canonical candidate and scenario identities may be joined to the
frozen response only after all applicable candidate-specific and comparative
responses freeze, the mapping is revealed under later authorization, and its
commitment verifies.

## Consent and Publication

- Consent status:
- Publication status:
- De-identification performed:

Contact information must remain outside repository files. Human publication
requires confirmed consent, privacy review, and prior disclosure that public
Git history may be difficult or impossible to erase completely.

## Processing and Validation

- Normalizations performed:
- Reviewer corrections:
- Administrator validation:
- Deviations and incidents:
- Later integration record:

Raw response bytes and substantive dissent must be preserved before any
normalization or synthesis. The commitment can help detect post-hoc remapping,
but it does not prove fair randomization, source truth, reviewer ignorance, or
moral authority and is not a blockchain. No field is populated and no
submission, mapping, nonce, or commitment exists in this preparation task.
