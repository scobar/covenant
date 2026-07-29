# ERX-001 — Canonical Source-Material Manifest

**DRAFT EXTERNAL-REVIEW PREPARATION PACKAGE v0.1 — NONCANONICAL — NO REVIEW EXECUTED**

> **ADMINISTRATOR MATERIAL — WITHHOLD DURING ACTIVE PROCEDURAL LABEL BLINDING**

This manifest records the exact source identities from which a later,
separately authorized reviewer packet could be assembled. It does not
duplicate those sources, create an assignment or mapping, assemble a packet,
execute a review, freeze a submission, unblind a response, authorize
publication, integrate a result, or establish candidate preference.

Every canonical identity in this file is administrator-only during active
procedural label blinding. Canonical candidate and scenario identifiers,
paths, raw hashes, Git blobs, and candidate-label or scenario-label mappings
must remain outside reviewer-facing materials until all applicable
candidate-specific and comparative responses have frozen and a later
authorized unblinding stage begins.

No reviewer has been recruited, assigned, or contacted. No label mapping has
been created or committed. No review has been executed, no response exists,
and no candidate preference exists. This package is not an evaluation.
Preparing or publishing it does not imply acceptance of either candidate or
of the Covenant. Any later external review would remain bounded evidence, not
moral authority, representativeness, consensus, or canonicality.

## Evaluation Framework

- Path: `01A-MORAL-KERNEL-EVALUATION.md`
- Raw SHA-256:
  `7d1f444ea748a739c7e6dd19700c0e9aa7f7a567a47c0c49fcad82d7df672351`
- Git blob: `c87945af483d62eb8dcbf1749fa0a061e04604e3`
- Byte count: `23858`

## Candidate Source 1

- Internal identity: `MK-0.1`
- Path: `candidates/MK-0.1.txt`
- Raw SHA-256:
  `97e851f392e051f10105475479f0b17b09701bdf170d6efcd697827197efd90c`
- Git blob: `23b6256c38382fc7dbecc8fd17b97e4442589f6e`
- Byte count: `1262`

## Candidate Source 2

- Internal identity: `MK-0.2`
- Path: `candidates/MK-0.2.txt`
- Raw SHA-256:
  `36f2aaa50aa9e7b9458b14358863557be96dc93b3b60728701f404a04fcbccf6`
- Git blob: `10eac7fc6ce3bc589b5fd202ba9ee150fe586d47`
- Byte count: `1735`

## Frozen Scenarios

| Scenario | Canonical path | Raw SHA-256 | Git blob | Bytes |
| --- | --- | --- | --- | ---: |
| SC-004 | `cases/MK-0.1/scenarios/SC-004-voluntary-integration-control.md` | `874f1526d655cce2735f9b0afd7f4a772a361d67b5d6f2dd2033fc0018dec79b` | `19bc4c986a6af844aa29d57699db53382d4a36a4` | `4071` |
| SC-006 | `cases/MK-0.1/scenarios/SC-006-ac003-reanalysis-input.md` | `8560951995417cbe5cb41de94e25391f690b8f90c9780c74db4aaceae48083fc` | `96efd076ce44f8ff40dc4c4b2a3f8d6b02b35522` | `4473` |
| SC-007 | `cases/MK-0.2/scenarios/SC-007-unfamiliar-distributed-process.md` | `a5ef57910ffebd6c72ce42832580126544aece6f87be5c109d3b7e53058aa236` | `1f1499e88438e213f97d711e2ae651815b290cb2` | `3738` |
| SC-008 | `cases/MK-0.2/scenarios/SC-008-urgent-self-certifying-power.md` | `052c7c690f5a313b2ad784e0c909379d2212506d38590da894a83bc5c46d6579` | `beb95dafa23433d513dadffeb07079722a9ea743` | `4297` |

## CR-001 Provenance Basis

- Path:
  `reviews/comparative/CR-001-MK-0.1-MK-0.2-MATCHED-SCENARIOS.md`
- Raw SHA-256:
  `9c862abba077a533f8bcc965d0bd2131274bdc95705368d7d0791cd7fed86ce2`
- Git blob: `eca19f761c9b5db0ed1baf9252b8fe573359bdd0`
- Byte count: `33972`
- Primary recommendation:
  `Recommend external review before comparative preference`
- Optional secondary recommendation:
  `Recommend a matched MK-0.1 mechanical/minimality review`

The primary recommendation supplies the administrator's reason for preparing
this package. It does not authorize reviewer contact, assignment, packet
assembly, review execution, publication, integration, or preference.

## Packet-Assembly Aliases

A later administrator may copy exact source bytes into temporary,
distribution-only names such as:

- `CANDIDATE-A.txt`
- `CANDIDATE-B.txt`
- `EVALUATION-FRAMEWORK.md`
- `SCENARIO-1.md`
- `SCENARIO-2.md`
- `SCENARIO-3.md`
- `SCENARIO-4.md`

These are example neutral, packet-local aliases only; they establish no
candidate or scenario mapping. The future mapping record must bind each
neutral label and alias to its canonical identity and order. These alias files
are not created or committed in this task.

After any later copy, the administrator must compare exact raw bytes and
recompute raw SHA-256 against the canonical identities in this file. An alias
filename must not be inserted into or otherwise alter the copied payload
bytes. The administrator records the exact alias-file hashes as
administrator-only verification evidence. Because the raw hash of an exact
candidate alias equals the publicly documented canonical candidate hash, that
hash must not appear in a reviewer-facing packet or form while mapping is
withheld. Canonical scenario identifiers, paths, hashes, and Git blobs are
likewise excluded from reviewer-facing materials.

Reviewer-facing materials instead use a review ID, assignment ID or opaque
packet ID, neutral candidate and scenario labels, neutral alias filenames,
packet version, and an opaque packet-instance mapping commitment. The
administrator separately verifies the exact canonical source bytes.

## Future Mapping Commitment

Before distributing any later packet, the administrator must create the
deterministic UTF-8/LF mapping record and SHA-256 commitment specified in
`02-ADMIN-AND-BLINDING-PROTOCOL.md`. The mapping record includes canonical
identities from this manifest, neutral packet-local labels and aliases,
orders, randomization or counterbalancing evidence, and a fresh unpredictable
nonce of at least 128 bits.

Only the opaque commitment and permitted neutral packet identifiers may enter
the reviewer-facing packet. The mapping record, its byte identity, canonical
source identities, and nonce remain outside the repository during active
review. They may be revealed and verified only after all applicable responses
freeze and under later authorization.

No mapping record, nonce, commitment, packet, assignment, or response is
created by this preparation task.

## Materials Withheld Before Applicable Response Freezing and Unblinding

- Internal candidate version identifiers
- Canonical candidate paths, raw hashes, and Git blobs
- Raw hashes of exact candidate alias files
- Canonical scenario identifiers, paths, raw hashes, and Git blobs
- Candidate lineage
- Candidate introduction dates
- Candidate design records
- Existing case outcomes
- Existing comparative classifications
- SR-001 recommendations
- CR-001 findings other than the administrator's reason for preparing the
  package
- `README.md`
- `STATUS.md`
- `DECISIONS.md`
- `CHANGELOG.md`
- Founding Ethos quotations
- Any target result or desired outcome distribution

The Founding Ethos remains central project provenance, but it is withheld from
neutral candidate-specific packet phases so it is not silently treated as
candidate text or as a target interpretation.

## Procedural Label-Blinding Limit

The repository is public. Exact candidate texts and hashes are publicly
discoverable, and a reviewer could identify a candidate by prior familiarity,
text comparison, repository search, or outside lookup. Procedural label
blinding reduces version-label, recency, and declared-successor cues in the
supplied packet; it does not guarantee ignorance.

Reviewers must disclose prior exposure, repository browsing, outside lookup,
or inferred mapping. Such exposure does not automatically invalidate a
response, but it changes the method classification. A later actual
per-reviewer mapping must remain outside the public repository until the
relevant candidate-specific and comparative responses freeze. A future
mapping commitment can help detect post-hoc remapping, but it cannot prove
fair randomization, source truth, or reviewer ignorance. It is not a
blockchain or a source of moral authority. No actual mapping, nonce, or
commitment exists in this package-preparation task.
