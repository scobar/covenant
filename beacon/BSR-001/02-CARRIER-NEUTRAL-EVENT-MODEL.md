# BSR-001 — Carrier-Neutral Event-Model Research

> **DRAFT BEACON BOOTSTRAP RESEARCH v0.1 — NONCANONICAL — NO SIGNAL ATTEMPT OR DECODING TRIAL EXECUTED**

## Research-only boundary

This document records requirements and competing abstractions. It does not
select a final event model, carrier, encoding, alphabet, numeral base, grammar,
event stream, framing syntax, physical anchor, payload, or response protocol.
No signal attempt, holdout, decoder, model execution, test, transmission, or
distribution exists.

BSR-001 is an evaluation and research framework, not a signal or final Beacon
specification. It is not evidence of universal decodability or Covenant
acceptance, and it does not choose a moral-kernel candidate or authorize
`SIG-001`. It may require substantial correction. This research can advance
while PX-001 remains dormant without weakening the requirement that
moral-payload stabilization precede final Beacon payload optimization.

All strengths and weaknesses below are hypotheses for later testing. No
abstraction is preferred, accepted, or represented as carrier-independent.

## Competing abstractions

### 1. Totally ordered event stream

- **Observable primitives:** Distinguishable event occurrences considered one
  at a time.
- **Ordering or adjacency relation:** A hypothesized total before-and-after
  relation and immediate succession.
- **Grouping possibilities:** Repetition, pauses or spacing relations,
  recurring delimiters, nested blocks, and restart structures could be
  investigated without selecting any syntax.
- **Synchronization assumptions:** The observer can recover or construct a
  consistent scan direction and enough ordering to compare recurrence.
- **Noise and erasure behavior:** Insertions, deletions, substitutions,
  duplicated events, missing events, and loss of the initial prefix can shift
  every later framing hypothesis.
- **Strengths:** A single order may make recurrence, prediction, and
  serialization comparatively easy to state and test.
- **Hidden assumptions:** Global linear order, meaningful succession,
  separable events, a usable observation rate, and a privileged direction.
- **Candidate carrier mappings:** A future, separately authorized profile
  could map abstract succession to distinguishable changes in an unspecified
  medium. No medium, timing, or mapping is selected.
- **Questions requiring trials:** Can framing recover from an unknown starting
  point, reversed scan, truncated prefix, or moderate edit corruption? How many
  incompatible total orders fit the same observation?

### 2. Multiple synchronized event channels

- **Observable primitives:** Distinguishable events associated with multiple
  hypothesized channels.
- **Ordering or adjacency relation:** Order within a channel plus a candidate
  synchronization or correspondence relation across channels.
- **Grouping possibilities:** Parallel examples, redundant copies,
  cross-channel checks, contrasts, and nested groups could be investigated.
- **Synchronization assumptions:** The observer can distinguish channels and
  infer simultaneity, phase, alignment, or another cross-channel relation.
- **Noise and erasure behavior:** Channel loss, skew, drift, cross-talk,
  substitution, and unequal erasure can create false correspondences.
- **Strengths:** Redundancy and simultaneous contrasts may expose structure
  that a single sequence hides.
- **Hidden assumptions:** Channel separability, comparable clocks or states,
  meaningful cross-channel alignment, and the absence of unobserved channels.
- **Candidate carrier mappings:** A future profile could realize channels as
  distinguishable dimensions of an unspecified carrier. No number of channels,
  physical dimension, or realization is selected.
- **Questions requiring trials:** Can a decoder distinguish channels from one
  interleaved stream, recover unknown phase, and continue if one channel is
  missing or corrupted?

### 3. Spatial or topological arrangement

- **Observable primitives:** Distinguishable sites, regions, objects, marks, or
  states and relations among them.
- **Ordering or adjacency relation:** Neighborhood, incidence, containment,
  connection, distance class, orientation, or topology rather than a required
  reading order.
- **Grouping possibilities:** Connected components, repeated motifs,
  boundaries, symmetries, tilings, and nested regions could be investigated.
- **Synchronization assumptions:** Temporal synchronization may be unnecessary,
  but the observer must recover stable spatial or relational structure.
- **Noise and erasure behavior:** Missing sites, deformations, occlusion,
  rotation, reflection, scale changes, and false adjacency may alter
  interpretation.
- **Strengths:** Several scan directions and relational invariants may be
  available without privileging a linear sequence.
- **Hidden assumptions:** Access to persistent arrangement, meaningful
  adjacency or geometry, distinguishable dimensionality, and a way to separate
  representation from carrier shape. A raster image is not assumed.
- **Candidate carrier mappings:** A future profile could map abstract relations
  into a persistent arrangement in an unspecified medium. No geometry,
  dimensionality, object type, or physical carrier is selected.
- **Questions requiring trials:** Which relations survive rotation,
  reflection, deformation, rescaling, partial observation, or alternative
  traversals? Which natural structures produce false positives?

### 4. Partially ordered event graph

- **Observable primitives:** Event-like nodes and typed or untyped candidate
  relations between them.
- **Ordering or adjacency relation:** A partial precedence, dependency,
  reachability, or causal relation in which some events may remain unordered.
- **Grouping possibilities:** Subgraphs, repeated motifs, branches, joins,
  independent examples, and integrity relations could be investigated.
- **Synchronization assumptions:** No single global clock is required, but the
  observer must recover nodes, edges, and enough relation identity to compare
  graph structure.
- **Noise and erasure behavior:** Missing or spurious nodes and edges can alter
  reachability, introduce false cycles, or disconnect teaching structures.
- **Strengths:** The abstraction may avoid imposing a total order on
  distributed or concurrent relations.
- **Hidden assumptions:** Relations are observable, node identity is stable
  enough for comparison, graph boundaries can be recovered, and partial order
  is meaningful to the receiver.
- **Candidate carrier mappings:** A future profile could encode nodes and
  relations through observable correspondences in an unspecified medium. No
  graph serialization or carrier is selected.
- **Questions requiring trials:** Can the graph be recovered without a
  supplied traversal, and can equivalent graphs be recognized across
  different presentations, missing relations, or added noise?

### 5. Repeated state transitions in an interactive environment

- **Observable primitives:** Distinguishable states, candidate actions or
  interventions, and observed transitions.
- **Ordering or adjacency relation:** Pre-state, transition, and post-state
  relations, potentially with branching or repeated trials.
- **Grouping possibilities:** Episodes, reset states, demonstrations,
  counterfactual contrasts, transition families, and checkpoints could be
  investigated.
- **Synchronization assumptions:** The observer can distinguish state from
  transition, identify or infer restart conditions, and preserve comparisons
  across episodes.
- **Noise and erasure behavior:** Hidden state, nondeterminism, delayed
  effects, incomplete observations, failed resets, and intervention errors can
  mimic or obscure rules.
- **Strengths:** Prediction and intervention may test whether a reconstructed
  model generalizes beyond displayed examples.
- **Hidden assumptions:** Interaction is possible and safe; action, state,
  causation, and agency are distinguishable; repeatability exists; and the
  environment does not strategically manipulate the test.
- **Candidate carrier mappings:** A future, separately authorized interactive
  profile could expose abstract state transitions. No environment, interface,
  action alphabet, response syntax, or recipient is selected.
- **Questions requiring trials:** Can a passive observer recover the same
  relations? How are hidden state, nondeterminism, strategic behavior, and
  unsafe interaction distinguished from decoding failure?

### 6. Hybrid temporal and spatial representation

- **Observable primitives:** Distinguishable events or states together with
  persistent spatial, topological, or channel relations.
- **Ordering or adjacency relation:** A combination of temporal succession and
  non-temporal adjacency, containment, incidence, or correspondence.
- **Grouping possibilities:** Spatial frames, temporal sequences within
  regions, parallel demonstrations, animated motifs, and cross-domain
  integrity checks could be investigated.
- **Synchronization assumptions:** The observer can distinguish temporal
  change from persistent structure and infer how the two relation families
  align.
- **Noise and erasure behavior:** Temporal corruption, spatial loss, drift,
  deformation, desynchronization, and inconsistent scan choices can interact.
- **Strengths:** Independent relation families may provide redundant teaching
  and cross-checks.
- **Hidden assumptions:** The receiver can observe both relation families,
  separate them, and avoid treating one as incidental carrier behavior.
- **Candidate carrier mappings:** A future profile could map abstract temporal
  and non-temporal relations into an unspecified realization. No hybrid
  medium, direction, timing, geometry, or serialization is selected.
- **Questions requiring trials:** Does redundancy reduce ambiguity or multiply
  plausible framings? Can one relation family repair loss in the other without
  supplying the intended interpretation?

## Minimal abstract primitives

The following are topics for comparison, not a selected syntax or ontology:

- **Event:** What observation would count as an occurrence rather than carrier
  background?
- **Distinguishable event class:** What equivalence or contrast could support
  classification without a supplied symbol mapping?
- **Relation:** How could a receiver infer a repeatable connection among
  observations?
- **Order:** Is order total, partial, local, derived, reversible, or absent?
- **Adjacency:** Which neighborhood or succession relation is observable, and
  which is imposed by a scan?
- **Duration or spacing ratio:** Can relative duration or separation be
  recovered without selecting a clock, unit, or numerical value?
- **Channel:** What evidence distinguishes parallel channels from an
  interleaved sequence or unrelated background?
- **Group:** Which recurrence or integrity relation supports grouping?
- **Frame:** What marks a recoverable scope without assuming a familiar
  delimiter?
- **Repetition:** Which observations are equivalent enough to count as
  recurrence?
- **Escape or quoting behavior:** How could literal data be distinguished from
  structural use without circularly assuming grammar?
- **Unknown or erasure state:** How can missing, unreadable, or ambiguous
  observations remain distinct from an ordinary event class?
- **Restart point:** What local evidence supports resynchronization without the
  original prefix?
- **Integrity relation:** Which predictable relation can expose corruption or
  an incorrect framing without supplying the answer?

No primitive is adopted as a final definition, and no concrete value, symbol,
sequence, or rule is assigned.

## Carrier-neutral versus carrier-independent

- A logical message may be carrier-neutral.
- Every physical realization still introduces carrier-specific assumptions.
- Carrier-neutral does not mean carrier-independent.
- A future attempt must identify which properties belong to the abstract
  message and which belong to its carrier profile.

BSR-001 does not select or create a carrier profile.

## Artificiality-marker research

Candidate marker families for later comparison include:

- prime and composite recurrence patterns;
- nested repetition at multiple scales;
- predictable continuations;
- symmetry and deliberate asymmetry;
- forward and reverse correspondences;
- cross-channel redundancy;
- error-detecting relationships; and
- multiple independent mathematical regularities.

No marker alone proves artificial construction. Natural, accidental,
adversarial, and observer-dependent explanations must remain visible, and a
later scorecard must identify the evidence required to prefer one hypothesis
for a particular attempt.

## Framing and synchronization research

A future event-model candidate must state how it proposes to support:

- clock or unit recovery;
- symbol boundaries;
- group boundaries;
- statement boundaries;
- start and end;
- restart after corruption;
- competing frame hypotheses;
- self-checking alternate framings; and
- insertions, deletions, substitutions, and erasures.

These are research requirements, not an encoding choice. No clock, unit,
symbol, group, statement, boundary marker, checksum, or corruption pattern is
selected here.

## Future test requirements

A future event-model candidate must be tested for:

- recovery from an unknown starting position;
- recovery from a truncated prefix;
- recovery from moderate corruption;
- multiple possible scan directions;
- multiple plausible group sizes;
- false-positive natural patterns; and
- distinguishability of data from framing.

The test must record alternative interpretations and disclose every receiver
assumption it relies on. No candidate event model, signal, holdout, decoder,
scorecard, test packet, or decoding trial is created or executed now.
