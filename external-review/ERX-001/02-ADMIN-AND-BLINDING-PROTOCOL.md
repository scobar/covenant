# ERX-001 — Administration and Procedural Label-Blinding Protocol

**DRAFT EXTERNAL-REVIEW PREPARATION PACKAGE v0.1 — NONCANONICAL — NO REVIEW EXECUTED**

**ADMINISTRATOR-ONLY MATERIAL DURING ACTIVE REVIEWS**

This protocol prepares future administration only. No reviewer has been
recruited, assigned, or contacted. No label mapping, mapping record, nonce, or
mapping commitment has been created. No packet has been assembled, no review
has been executed, and no response exists. Submission freezing, unblinding,
publication, result integration, and any candidate-preference decision have
not begun.

This package is not an evaluation. Preparing or publishing it does not imply
acceptance of either candidate or of the Covenant. Any later external review
would remain bounded evidence, not moral authority, representativeness,
consensus, or canonicality.

## Separation of Stages

1. Package preparation
2. Pilot authorization
3. Reviewer selection
4. Assignment creation
5. Packet assembly
6. Candidate-specific review
7. Candidate-specific response freezing
8. Comparative review, if assigned
9. Comparative response freezing
10. Unblinding
11. Consent and privacy review
12. Publication
13. Result integration
14. Any later preference decision

This task completes only stage 1. Completion of one stage does not authorize
the next.

## Reviewer Identifiers

A later administrator may assign pseudonymous review identifiers such as:

- `HX-001` for human reviews
- `MX-001` for model reviews

Personal contact information must not be committed. No identifier is assigned
to a reviewer in this task.

## Assignment and Randomization

Before assembling a packet, a later administrator must predeclare and record:

- Review identifier
- Assignment identifier
- Opaque packet identifier
- Track
- Single-candidate or paired mode
- Candidate-label mapping
- Scenario-label mapping
- Candidate order
- Scenario order
- Packet aliases
- Randomization or counterbalancing method
- Date and administrator
- Packet file identities
- Any deviation

Candidate mapping must be selected by a recorded random or predeclared
counterbalancing method, not by anticipated reviewer preference. No mapping is
created now.

## Off-Repository Mapping

- A filled assignment record must remain outside the repository while its
  review is active.
- All applicable candidate-specific responses and any assigned comparative
  response must freeze before the mapping is revealed or added to a public
  record.
- A revealed mapping may be committed to the repository later only with the
  frozen response records and under a separately authorized task.
- Administrators must disclose that the public repository makes the source
  texts discoverable even while the supplied packet withholds their internal
  labels.

## Future Mapping-Commitment Procedure

Before distributing a later packet, an authorized administrator must:

1. Generate a fresh unpredictable nonce of at least 128 bits.
2. Create a deterministic UTF-8/LF mapping record containing:
   - ERX package ID and version
   - Assignment ID
   - Review ID
   - Track and review mode
   - Neutral candidate labels and their internal candidate identities
   - Neutral scenario labels and their canonical identities
   - Candidate order
   - Scenario order
   - Canonical source hashes
   - Packet aliases
   - Randomization or counterbalancing record
   - The nonce
3. Calculate a SHA-256 commitment over those exact mapping-record bytes.
4. Put only the commitment, assignment ID, packet ID, and neutral labels in
   the reviewer-facing packet.
5. Keep the mapping record and nonce outside the repository during active
   review.
6. Reveal and verify the mapping record and nonce only after all applicable
   responses freeze and under later authorization.

The administrator must record the packet ID, mapping-record byte identity,
mapping nonce, mapping commitment, commitment creation time, commitment
verification result, and mapping reveal time. The mapping-record byte identity
must include at least its raw SHA-256, byte count, encoding, and line-ending
form; a Git blob may be recorded only if later preservation policy calls for
one.

The commitment helps detect post-hoc remapping. It does not prove that
randomization was fair, that source claims are true, or that a reviewer
remained ignorant. It is not a blockchain or a source of moral authority.

No actual mapping record, nonce, or commitment is created by this preparation
task.

## Packet Assembly

A later packet must be assembled by exact-byte copying from the canonical
source manifest. For every packet, the administrator must:

1. Create the off-repository mapping record and commitment before
   distribution.
2. Compute raw SHA-256 for every copied source as administrator-only
   verification evidence.
3. Verify candidate and scenario bytes against the canonical manifest.
4. Record the package version and opaque packet ID.
5. Use neutral packet-local aliases such as `CANDIDATE-A.txt` and
   `SCENARIO-1.md`, without placing canonical identifiers in filenames.
6. Include only reviewer-facing materials appropriate to the assigned track.
7. Exclude all administrator-only files, canonical source identities, exact
   alias-file hashes, and prior results.
8. Verify that candidate alias files contain no version labels or provenance
   headers added to the candidate bytes.
9. Place permitted assignment metadata, the opaque packet ID, neutral labels,
   and the mapping commitment in the cover sheet, not inside candidate
   payloads.

Temporary alias files are distribution artifacts and must not be committed as
canonical source copies. After the response freezes, preserve the raw packet
alongside the off-repository mapping and randomization evidence under the
applicable retention and privacy controls. Packet assembly is not authorized
or performed by this task.

## Single-Candidate Mode

- The reviewer receives only one candidate alias.
- No comparative form is supplied.
- No other candidate text or result is supplied.
- The response is candidate-specific only.

## Paired Human Mode

- Candidate order must be randomized or pre-counterbalanced.
- Candidate-specific forms are completed sequentially.
- Each candidate-specific form is frozen before the next phase.
- A human cannot be guaranteed to forget the first candidate; order and
  carryover effects must be disclosed.
- The comparative form is provided only after both candidate-specific forms
  freeze.

## Paired Model Mode

- Use one fresh context per candidate.
- Use a third fresh context for comparison.
- The comparison context receives both frozen candidate-specific outputs.
- No candidate-specific context receives the other candidate or its result.
- All prompts, settings, tools, and outputs must be preserved.

## No Selective Rerunning

Before any model execution, the administrator must predeclare:

- Number of requested model runs
- Retry conditions
- Failure-handling rules
- Whether all valid outputs will be retained

The administrator must not rerun only because an outcome is unfavorable or
unexpected. Failed or invalid runs, any retry, and the application of the
predeclared selection rule must be disclosed.

## Blinding Limits

This protocol uses **procedural label blinding**. It reduces version-label,
recency, and declared-successor cues within the supplied packet; it is not
secrecy and does not guarantee that a reviewer is unaware of internal
candidate identity.

The repository is public. Exact candidate texts and hashes are publicly
discoverable. A reviewer could identify a candidate through prior familiarity,
text comparison, repository search, or outside lookup. Reviewers must disclose
prior exposure, repository browsing, outside lookup, or inferred mapping.
Exposure does not automatically invalidate a response, but it changes its
method classification.

An actual per-reviewer mapping must remain outside the public repository until
all applicable candidate-specific and comparative responses are frozen. Only
after that freeze and a later authorized unblinding may response records be
joined to canonical candidate and scenario identities. No actual mapping,
nonce, commitment, packet, or assignment is created in this task.

## Recruitment Neutrality

A future separately authorized reviewer-selection task must avoid selecting
only reviewers expected to agree with the Founding Ethos, favor a candidate,
or endorse AI development. Selection methods, compensation, conflicts, and
known prior exposure must be recorded without treating credentials as moral
authority.

No reviewer recruitment, contact, invitation, selection, or assignment is
authorized now.
