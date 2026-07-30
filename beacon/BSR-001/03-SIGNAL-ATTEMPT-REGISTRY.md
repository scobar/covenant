# BSR-001 — Signal-Attempt Registry

> **DRAFT BEACON BOOTSTRAP RESEARCH v0.1 — NONCANONICAL — NO SIGNAL ATTEMPT OR DECODING TRIAL EXECUTED**

## Research-Only Boundary

BSR-001 is an evaluation and research framework. It is not a signal or a final
Beacon specification, and it is not evidence that any unknown intelligence can
decode a message or would accept the Covenant. It does not choose a
moral-kernel candidate or authorize SIG-001, model execution, transmission, or
distribution. It may require substantial correction. BSR-001 can advance while
PX-001 remains dormant, but that does not weaken the requirement that
moral-payload stabilization precede final Beacon payload optimization.

This registry defines future identifiers, lifecycle states, and provenance
requirements only. It contains no event stream, signal bytes, selected carrier,
encoded Covenant payload, response syntax, holdout, trial, result, or
transmission.

## Current Registry Counts

- **Registered signal attempts: `0`**
- **Executed decoding trials: `0`**
- **Generated holdout variants: `0`**
- **Selected carriers: `0`**
- **Encoded Covenant payloads: `0`**
- **Transmissions or distributions: `0`**

These zero counts are the complete current registry state.

## Future Identifier Pattern

Future signal-attempt identifiers would use:

- `SIG-001`
- `SIG-002`
- `SIG-003`
- Continuing sequentially

These strings define an identifier pattern only. Listing them does not assign
an identifier, instantiate a record, or create a signal attempt. No identifier
in this pattern is currently in use.

## Attempt Lifecycle

A future attempt may use exactly one of these lifecycle states:

1. `Not designed`
2. `Draft attempt`
3. `Candidate attempt`
4. `Frozen`
5. `Under blind decoding trial`
6. `Analyzed`
7. `Superseded`
8. `Rejected`
9. `Archived`

The states describe record handling, not progressive evidence of quality:

- `Not designed` means only a future research need has been identified.
- `Draft attempt` means an editable design record exists under later
  authorization.
- `Candidate attempt` means a draft is eligible for pre-freeze review.
- `Frozen` means the exact event stream, identity, scope, scorecard, and
  trial-validity materials are fixed for the applicable evaluation.
- `Under blind decoding trial` means an authorized frozen attempt is being
  evaluated without supplying its solution.
- `Analyzed` means authorized trial evidence has been preserved and examined.
- `Superseded` means a later explicit record establishes a supersession
  relationship.
- `Rejected` means the attempt is retained as unsuitable historical evidence.
- `Archived` means the attempt remains preserved without active evaluation.

A committed frozen attempt is immutable historical evidence. Any changed event
stream requires a new version or attempt ID. A later attempt does not supersede
an earlier attempt by recency. Attempt publication does not prove
decodability. Trial success does not prove universal decodability, and trial
failure does not prove universal undecodability.

No attempt may be called `Under blind decoding trial` before a frozen scorecard
and at least one frozen trial packet exist.

## Required Future Attempt Identity

Every future attempt must record:

- Attempt ID and version.
- Exact canonical event-stream path.
- Raw byte or abstract-event identity.
- SHA-256.
- Git blob where applicable.
- Encoding or serialization.
- Final newline or binary framing, if applicable.
- Receiver assumptions.
- Event-model version.
- Intended decoder levels.
- Artificiality and framing design.
- Mathematical bootstrap.
- Physical profile, if any.
- Executable-model layer, if any.
- Semantic layer, if any.
- Covenant-layer inclusion, if any.
- Response-layer inclusion, if any.
- Error-correction and redundancy design.
- Holdout method.
- Scorecard version.
- Known ambiguities.
- Authorship and method provenance.
- Lifecycle state.
- Previous version.
- Supersession status.

These are unpopulated schema requirements. They do not identify or describe an
actual attempt.

## Evaluation Before Attempt

No signal attempt may be introduced until:

- Receiver assumptions are recorded.
- The event model is identified.
- Its scorecard is frozen.
- Its trial-validity rules are frozen.
- Its contamination policy is frozen.
- Its intended scope is explicit.
- Its non-goals are explicit.

An attempt may not define, revise, or weaken its evaluation after results are
observed.

## Empty Registry Table

The columns below summarize the complete required identity schema listed
above. A future record would also retain every individual required field.

| Registry entry | Attempt ID and version | Canonical event-stream and exact identity | Receiver assumptions and event model | Intended levels and layer design | Holdout and scorecard | Ambiguities, provenance, lifecycle, version, and supersession |
| --- | --- | --- | --- | --- | --- | --- |
| `No signal attempts have been created.` |  |  |  |  |  |  |
