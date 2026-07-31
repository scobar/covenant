# DA-001 — Public Diagnostic Result and Closure Record

> **DA-001 CLOSED COMPLETE — PRIVATE POST-HOC DIAGNOSTIC RESULT FROZEN — NO RAW EVIDENCE OR SIG-002 DESIGN PUBLISHED**

## Identity and provenance

- Diagnostic ID: `DA-001`
- Version: `0.1`
- Parent attempt: `SIG-001 v0.1`
- Related trials:
  - `SIG-001-HO-001-TR-001`
  - `SIG-001-HO-002-TR-002`
- Public preparation checkpoint:
  `a7451b330b0613adc395e7b207449fea2cf06c6e`
- Public preparation commitment:
  `29171f6664858dcc5649905797db89bfb5e1a94d104b851973b80caadb17bebf`
- Previous lifecycle: `Prepared and authorized — not executed`
- Final lifecycle: `Closed complete — private diagnostic result frozen`

## Execution accounting

- Observation records: `3`
- Truth-relative diagnostic records: `3`
- Cross-run syntheses: `1`
- Diagnostic audits: `1`
- Result dependencies: `8`
- Raw evidence publicly revealed: `0`
- Validity changes: `0`
- Score changes: `0`
- Dissent changes: `0`
- Levels 5–9 analyses: `0`
- SIG-002 designs: `0`
- New signal attempts: `0`
- Model runs: `0`

## Evidence boundaries

- Nineteen Fable screenshots were inspected natively without OCR.
- Fable remained non-scorable.
- Sonnet RUN-001 and RUN-002 visual evidence was not needed.
- Sonnet raw outputs remain private.
- No raw evidence is published.
- Existing validity, score, audit, and dissent remain unchanged.

## Diagnostic status semantics

- `Supported` means the frozen evidence supports that family as a material
  diagnostic concern or explanatory site under DA-001. It does not mean the
  decoder successfully recovered that capability, and it does not by itself
  prove causation.
- `Weakly supported` means some evidence is compatible with the concern, but
  alternatives, incomplete records, or limited evidence prevent a stronger
  conclusion.
- `Contradicted` means the proposed diagnostic concern, as framed in the
  preregistered family, is contradicted by the evidence. For example,
  `Artificiality detection — Contradicted` means failure to detect
  artificiality is contradicted as the explanation; the evidence instead
  includes artificiality recognition.
- `Unresolved` means the frozen evidence cannot discriminate the concern from
  plausible alternatives.

The family vector is a set of diagnostic classifications. It is not a score,
ranking, vote, aggregate, or success/failure verdict.

## Sixteen-family vector

```text
FAMILY_01=Artificiality detection|Contradicted
FAMILY_02=Event-class discrimination|Weakly supported
FAMILY_03=Unary or run-length quantity inference|Weakly supported
FAMILY_04=Delimiter-versus-data separation|Supported
FAMILY_05=Boundary-hierarchy ordering|Supported
FAMILY_06=Duplicate-body recognition|Contradicted
FAMILY_07=Section segmentation and ordering|Weakly supported
FAMILY_08=Header or sentinel interpretation|Supported
FAMILY_09=Local-to-global integration|Supported
FAMILY_10=Relation and arithmetic mapping|Supported
FAMILY_11=Boolean orientation and logic|Supported
FAMILY_12=Fixed-arity prefix grammar|Supported
FAMILY_13=Example-versus-query distinction|Supported
FAMILY_14=Hypothesis management and uncertainty|Weakly supported
FAMILY_15=Instruction interpretation and response completeness|Supported
FAMILY_16=Provider safeguard or interface interruption effects|Supported
```

## Shared and divergent paths

Shared decoding paths:

- Artificiality recognition.
- Event/run decomposition.
- Local quantity recovery.
- Recognition of large repeated structure.
- Section-like cue detection.
- Explicit uncertainty.

The paths diverged most strongly in:

- framing;
- functional orientation;
- boundary hierarchy;
- integration into relations and arithmetic;
- Boolean logic;
- grammar;
- query interpretation.

## Causal-strength register

- `Supported`: provider/interface events caused observable noncompletion in the
  two technically invalid runs.
- `Weakly supported`: incomplete hierarchy, delimiter/data-role confusion, and
  duplication being insufficient by itself for later semantic recovery.
- `Contradicted`: a strict requirement that complete hierarchy must be
  recovered before any quantity recovery can occur.
- `Unresolved`: exposure effects, hidden-backend differences, early hypothesis
  lock-in, and instruction/report-strategy effects.

The family vector and causal-strength register are different artifacts. A
family may be `Supported` as a diagnostic site without a single-cause claim
being established.

## Future controlled experiment classes

1. Boundary-redundancy strength.
2. Local versus global framing.
3. Explicit versus emergent section differentiation.
4. Duplicate-body cue presence versus ablation.
5. Fixed framing with varied arithmetic teaching.
6. Fixed grammar with varied query marking.
7. Provider-independent replication.
8. Clean no-known-exposure holdout testing.

These are experiment classes, not a SIG-002 design. No exact symbols, token
maps, delimiters, values, examples, queries, stream, packet, provider, or
execution plan is selected. A later decision must choose one controlled
variable and preregister the successor experiment.

## Audit and dissent

- Primary method: frozen six-record comparison under the preregistered
  sixteen-family taxonomy.
- Independent audit: scratch result frozen before synthesis access.
- Audit result: `PASS WITH PRESERVED DISSENT`.
- Five family-status disagreements were preserved.
- Additional abstract experiment-class scope dissent was preserved.
- No synthesis correction was made.
- The dissent remains private.
- Same-tooling agreement or disagreement is not external independent
  validation.

## Methodological limitations

- Same provider across Fable and Sonnet.
- Prior exposure.
- Unverified backend identity.
- Incognito cannot prove provider isolation.
- Browser-copy output limitations.
- Two technically interrupted runs and one valid run.
- Fable trace is incomplete and provider-visible, not full hidden cognition.
- Same-tooling post-hoc analysis.
- No external independent validation.
- Five preserved family-status disagreements.
- One completed diagnostic package cannot establish a universal receiver
  model.
- Diagnostic findings may inform controlled experiments but do not select a
  signal design.

## Roles and authority

- Scott Barbian remains repository owner, private custodian, and project
  director.
- ChatGPT remains project architect under Scott’s direction.
- Codex remains implementation and same-tooling analysis assistance.
- Anthropic, Fable, and Sonnet remain provider/model labels, not final
  authorities.
- No observer, diagnostician, synthesizer, auditor, model, or founder gains
  sovereign or final interpretive authority.

## Closure

- DA-001 is permanently closed under D-028.
- Its private source and result files remain immutable.
- No result may be replaced or inserted.
- No raw evidence publication is authorized.
- No score or trial result changes.
- No SIG-002 design is authorized by this record.
- A later decision may choose one controlled experiment class and prepare a
  separate successor-design research package.
- No Levels 5–9, Covenant, carrier, distribution, or transmission work
  follows.
