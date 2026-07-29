# ERX-001 — Assignment Record Template

**DRAFT EXTERNAL-REVIEW PREPARATION PACKAGE v0.1 — NONCANONICAL — NO REVIEW EXECUTED**

> **BLANK ADMINISTRATOR TEMPLATE — DO NOT COMMIT A FILLED ACTIVE MAPPING**

No field is populated in this task. This template creates no reviewer,
assignment, candidate-label mapping, scenario-label mapping, mapping nonce,
mapping commitment, packet, response, consent record, review result, or
candidate preference.

Package preparation is the only authorized stage. Assignment creation, packet
assembly, review execution, response freezing, unblinding, publication, result
integration, and any later preference decision require separate
authorization.

## Assignment Identity

- Assignment ID:
- Review ID:
- Packet ID:
- Track:
- Reviewer pseudonym:
- Mode — single or paired:
- Administrator:
- Date:
- ERX package ID and version:

## Mapping and Order

- Candidate A internal mapping:
- Candidate B internal mapping:
- Neutral scenario labels and canonical identities:
- Candidate order:
- Scenario order:
- Candidate and scenario packet aliases:
- Randomization or counterbalancing method:
- Randomization or counterbalancing record:

The mapping must be chosen by a recorded random or predeclared
counterbalancing method rather than an anticipated reviewer preference. A
filled active record must remain outside the repository until all applicable
candidate-specific and comparative responses freeze.

## Mapping Commitment

- Mapping-record byte identity:
- Mapping-record raw SHA-256:
- Mapping-record byte count:
- Mapping-record encoding: UTF-8
- Mapping-record line endings: LF
- Mapping-record Git blob, if later preservation policy requires one:
- Mapping nonce — fresh, unpredictable, at least 128 bits:
- Mapping commitment — SHA-256 over the exact mapping-record bytes:
- Commitment creation time:
- Commitment verification result:
- Mapping reveal time:

Before packet distribution, the administrator must create a deterministic
UTF-8/LF mapping record containing the ERX package ID and version, assignment
ID, review ID, track and mode, neutral candidate labels and internal
identities, neutral scenario labels and canonical identities, candidate and
scenario order, canonical source hashes, packet aliases, randomization or
counterbalancing record, and nonce. Only the commitment, assignment ID,
packet ID, and neutral labels may be placed in the reviewer-facing packet.
The mapping record and nonce remain outside the repository during active
review and may be revealed and verified only after all applicable responses
freeze and under later authorization.

The commitment helps detect post-hoc remapping. It does not prove fair
randomization, source truth, or reviewer ignorance. It is not a blockchain or
a source of moral authority.

## Packet Identities

- Candidate canonical paths, raw SHA-256 values, and Git blobs —
  administrator-only:
- Candidate neutral alias filenames:
- Candidate alias raw SHA-256 values — administrator-only exact-byte
  verification; exclude from reviewer-facing materials:
- Framework canonical path and hash — administrator-only:
- Scenario canonical IDs, paths, raw SHA-256 values, and Git blobs —
  administrator-only:
- Neutral scenario alias filenames:
- Raw packet identity to preserve after response freezing:
- Packet mapping commitment shown to reviewer:
- Reviewer-facing files included:
- Administrator-only files excluded:

The administrator must verify alias bytes exactly against canonical sources.
Canonical identities and exact alias hashes do not enter reviewer-facing
materials while the mapping is withheld.

## Method Conditions

- Prior exposure known before assignment:
- Public-repository discoverability disclosed:
- Procedural label-blinding limitations disclosed:
- Deviations:

## Response and Unblinding Identities

- Candidate A response freeze identity:
- Candidate B response freeze identity:
- Comparative response freeze identity:
- Unblinding time:
- Post-freeze canonical join record:
- Mapping-commitment verification result:

## Consent and Mapping Publication

- Publication-consent status:
- Mapping-publication authorization:

Do not place personal contact information in this record. No field is
populated, no active mapping or nonce is created, no commitment is calculated,
and no later stage is executed by this preparation task.
