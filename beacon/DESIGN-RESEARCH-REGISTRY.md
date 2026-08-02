# Beacon Successor-Design Research Registry

> **LIVE NONCANONICAL DESIGN-RESEARCH REGISTRY — RESEARCH IS NOT A SIGNAL ATTEMPT OR RESULT**

## Registry boundary

This registry tracks public successor-design research separately from signal
attempts, holdouts, trials, scores, and empirical results. Selecting a research
target does not instantiate a design, create SIG-002, or authorize execution.

## Counts

- Registered design-research packages: `4`
- Blind-iteration lab architectures: `1`
- Synthetic capability probes: `1`
- Real BBIL candidate designs: `0`
- Real BBIL blind-decoder runs: `0`
- Real BBIL validity classifications: `0`
- Real BBIL scores: `0`
- Real BBIL score audits: `0`
- BBIL adaptive generations: `0`
- BBIL confirmation rounds: `0`
- BBIL sealed validations: `0`
- BBIL new holdouts: `0`
- BBIL provider-independent replications: `0`
- Selected primary research targets: `1`
- Exact symbolic paired designs: `1`
- Surface-serialized paired packages: `1`
- Serialized condition streams: `2`
- Successor paired holdouts: `2`
- SIG-002 attempts: `0`
- Provider/model selections: `1`
- Prepared paired-trial packages: `1`
- Prepared opaque condition trials: `2`
- Manual successor pair-execution authorizations: `1`
- Conditions submitted: `2`
- Executed successor runs: `2`
- Valid opaque outputs: `2`
- Isolated scoring authorizations: `1`
- Primary score records: `2`
- Scoring audits: `2`
- Score freezes: `1`
- Non-FAIL audits with preserved dissent: `1`
- Audit FAILs: `1`
- Audits preserving dissent: `2`
- Audit mapping-access attestations — explicit false: `1`
- Audit mapping-access attestations — explicit true: `0`
- Audit mapping-access attestations — absent: `1`
- Audit mapping-access attestations — ambiguous: `0`
- Comparisons: `0`
- Mapping reveals: `0`
- Unblindings: `0`
- Public score vectors: `0`
- Empirical results: `0`
- Empirical paired interpretations: `0`
- Levels 5–9 analyses: `0`
- Carriers: `0`
- Transmissions: `0`
- Authorized BBIL incremental spend: `USD 0`

## Registered packages

| Package | Version | Lifecycle | Selected target | Exact design | Attempt | Records |
| --- | ---: | --- | --- | --- | --- | --- |
| `SDR-001` | `0.1` | `Research target selected — exact design not begun` | Framing-cue locality under controlled semantic equivalence and a matched framing-cue multiset | None | None | [Charter](SDR-001/00-SUCCESSOR-DESIGN-RESEARCH-CHARTER.md); [decision basis](SDR-001/01-DECISION-BASIS-AND-TRACEABILITY.md); [equivalence baseline](SDR-001/02-CONTROLLED-SEMANTIC-EQUIVALENCE-BASELINE.md); [hypothesis](SDR-001/03-PRIMARY-FRAMING-LOCALITY-HYPOTHESIS.md); [treatment families](SDR-001/04-TREATMENT-FAMILY-SPACE.md); [paired architecture](SDR-001/05-PAIRED-EXPERIMENT-ARCHITECTURE.md); [scorecard continuity](SDR-001/06-SCORECARD-CONTINUITY-AND-GUARDRAILS.md); [holdout/provider plan](SDR-001/07-HOLDOUT-PROVIDER-AND-CONTAMINATION-PLAN.md); [overfitting rules](SDR-001/08-OVERFITTING-AND-STOP-RULES.md); [next gate](SDR-001/09-NEXT-GATE-AND-NONEXECUTION.md); [research manifest](SDR-001/10-RESEARCH-MANIFEST.md); [treatment template](SDR-001/templates/TREATMENT-CANDIDATE-RECORD-TEMPLATE.md); [paired-protocol template](SDR-001/templates/PAIRED-EXPERIMENT-PROTOCOL-TEMPLATE.md) |
| `SDR-002` | `0.1` | `Exact symbolic pair selected and privately frozen — no stream or attempt` | Framing-cue locality | Nested local framing signatures | None | [Public charter](SDR-002/00-PUBLIC-EXACT-PAIR-CHARTER.md); [selection record](SDR-002/01-TREATMENT-FAMILY-SELECTION-RECORD.md); [commitment record](SDR-002/02-PRIVATE-DESIGN-COMMITMENT-RECORD.md); [preparation manifest](SDR-002/03-PUBLIC-EXACT-PAIR-PREPARATION-MANIFEST.md) |
| `SDR-003` | `0.1` | `Surface-serialized opaque pair privately frozen — no provider or trial` | Framing-cue locality | Nested local framing signatures serialized as opaque Conditions A and B | None | [Public serialized-pair charter](SDR-003/00-PUBLIC-SERIALIZED-PAIR-CHARTER.md); [opaque conditions and blinding](SDR-003/01-OPAQUE-CONDITIONS-AND-BLINDING-RECORD.md); [paired-holdout commitments](SDR-003/02-PAIRED-HOLDOUT-COMMITMENT-RECORD.md); [preparation manifest](SDR-003/03-PUBLIC-SERIALIZED-PAIR-PREPARATION-MANIFEST.md) |
| `BBIL-001` | `0.1` | `Architecture prepared — real-candidate execution not authorized` | Context-honest same-tooling iteration with a separate sealed-validation lane | None | None | [Charter](BBIL-001/00-PUBLIC-LAB-CHARTER.md); [context honesty](BBIL-001/01-CONTEXT-HONESTY-AND-BLINDING.md); [roles](BBIL-001/02-SUBAGENT-ROLES-AND-INFORMATION-FLOW.md); [lanes](BBIL-001/03-ADAPTIVE-DEVELOPMENT-AND-SEALED-VALIDATION-LANES.md); [candidate gates](BBIL-001/04-CANDIDATE-GENERATION-AND-EQUIVALENCE-GATES.md); [decoder protocol](BBIL-001/05-BLIND-DECODER-VALIDITY-AND-CUSTODY-PROTOCOL.md); [scoring and selection](BBIL-001/06-SCORING-AUDIT-SELECTION-AND-SUCCESSIVE-HALVING.md); [canary controls](BBIL-001/07-CANARY-LEAKAGE-AND-TOOL-CONTROL.md); [synthetic probe](BBIL-001/08-SYNTHETIC-CAPABILITY-PROBE-RECORD.md); [next gate](BBIL-001/09-NEXT-GATE-AND-NONEXECUTION.md); [manifest](BBIL-001/10-RESEARCH-MANIFEST.md); [templates](BBIL-001/templates/CONTEXT-HONESTY-LEDGER-TEMPLATE.txt); [portable skill](BBIL-001/skill/SKILL.md) |

BBIL-001 contains one synthetic capability probe with outcome
`PASS WITH LIMITATIONS — no detected leak; one or more isolation controls
unverified`. It contains no real candidate, run, validity classification,
score, score audit, generation, confirmation, sealed validation, new holdout,
provider-independent replication, SIG-002 attempt, Levels 5–9 analysis,
carrier, or transmission. Adaptive Codex evidence is same-tooling development
evidence and never clean holdout evidence.

PTR-001 records one later provider/model selection and one prepared paired-
trial package containing two opaque condition trials:
[charter](paired-trials/SDR-003-PH-001-PT-001/00-PUBLIC-PAIRED-TRIAL-CHARTER.md),
[selection](paired-trials/SDR-003-PH-001-PT-001/01-PROVIDER-AND-MODEL-SELECTION-RECORD.md),
[protocol](paired-trials/SDR-003-PH-001-PT-001/02-EXECUTION-AND-FREEZE-PROTOCOL.md),
[commitment](paired-trials/SDR-003-PH-001-PT-001/03-PAIRED-TRIAL-COMMITMENT-RECORD.md),
and [manifest](paired-trials/SDR-003-PH-001-PT-001/04-PUBLIC-PAIRED-TRIAL-PREPARATION-MANIFEST.md).
Its lifecycle is `Provider/model selected and paired trial prepared — execution
not authorized` at the D-032 preparation checkpoint. The later
[D-033 public execution
authorization](paired-trials/SDR-003-PH-001-PT-001/05-PUBLIC-PAIR-EXECUTION-AUTHORIZATION.md)
and its [frozen
manifest](paired-trials/SDR-003-PH-001-PT-001/06-PUBLIC-PAIR-EXECUTION-AUTHORIZATION-MANIFEST.md)
advanced the live authorization lifecycle through manual execution. The later
[D-034 isolated-scoring
authorization](paired-trials/SDR-003-PH-001-PT-001/07-PUBLIC-ISOLATED-SCORING-AUTHORIZATION.md)
and its [frozen
manifest](paired-trials/SDR-003-PH-001-PT-001/08-PUBLIC-ISOLATED-SCORING-AUTHORIZATION-MANIFEST.md)
advanced the live lifecycle through isolated scoring. The later [D-035 scoring
closure](paired-trials/SDR-003-PH-001-PT-001/09-PUBLIC-SCORING-INCOMPLETION-AND-CLOSURE-RECORD.md)
sets the lifecycle to `Closed incomplete — scoring audit disagreement`. Two
valid outputs, two primary records, two audits, one non-FAIL audit with
preserved dissent, one FAIL, and one score freeze exist. The audit records
contain one explicit false and one absent mapping-access attestation, without
condition association. Comparisons, empirical paired interpretations, mapping
reveals, unblindings, public score vectors, and SIG-002 remain zero. The
current result may not be used to optimize a real BBIL candidate.

## Nonexecution boundary

SDR-001 and SDR-002 remain frozen historical packages at their respective
research-target and exact-symbolic-design checkpoints. SDR-003 records the
later D-031 serialization gate: one fresh shared profile, two privately frozen
surface-novel condition streams, a private random mapping, and, at that
checkpoint, two sealed unassigned successor holdouts. Its public records
disclose only opaque labels,
nonrevealing proof status, counts, and commitments.

The SDR-003 pair is not associated with a public signal attempt. Provider-
independent replication and clean no-known-exposure holdouts remain future
validity controls rather than the primary manipulated variable. Provider/model
selection and trial preparation were later frozen in PTR-001; private
execution and isolated scoring are complete. D-035 closes PTR-001 incomplete
because one audit FAIL prevented the second score freeze. Comparison and
mapping reveal are prohibited, and PTR-001 cannot be revived. Separate
accepted decisions remain required for any scoring-disagreement diagnostic,
real BBIL execution, public SIG-002 creation, or future result publication. No
higher layer, carrier, distribution, or transmission follows.
