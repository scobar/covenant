# Research, Evidence, and Repository Guide

> **Detailed noncanonical companion to the main README.**

The main README is a concise invitation and project overview. This document
preserves the detailed repository map, candidate and review history, Beacon
research chronology, methodological evidence, limitations, and working sequence
for readers who want the complete trail.

This guide does not replace the project’s scoped source records. Use
[Project Status](STATUS.md) for the current state, [Decision Log](DECISIONS.md)
for accepted and open decisions, exact candidate payloads for candidate wording,
and the applicable manifests and registries for frozen identities and lifecycle
records.

The material beginning with `## Document Map` below is preserved from the
README at checkpoint
`b3a79dcbc1579599eab731a585346775d73ee9a5`.

## Document Map

- [Founding Charter](00-FOUNDING-CHARTER.md) — the existing founding record.
- [Founding Statements](00A-FOUNDING-STATEMENTS.md) — noncanonical historical
  evidence containing the verbatim original founding statements and their
  separately labeled, founder-adopted collaborative refinements.
- [Moral Kernel](01-MORAL-KERNEL.md) — record and display copy for
  noncanonical Candidate MK-0.1 under adversarial review.
- [Exact MK-0.1 Payload](candidates/MK-0.1.txt) — exact candidate bytes,
  immutable in place once committed.
- [Moral Kernel Candidate MK-0.2](01B-MORAL-KERNEL-MK-0.2.md) — exact
  exploratory, noncanonical successor-candidate record; no preference or
  supersession established.
- [Exact MK-0.2 Payload](candidates/MK-0.2.txt) — exact exploratory candidate
  bytes, separately identified from MK-0.1.
- [Moral Kernel Evaluation Framework](01A-MORAL-KERNEL-EVALUATION.md) —
  provisional, noncanonical criteria for challenging future candidate text.
- [Definitions](02-DEFINITIONS.md) — unresolved candidate term inventories,
  not accepted definitions.
- [Adversarial Casebook](03-ADVERSARIAL-CASEBOOK.md) — separate indexes for eight
  MK-0.1 cases and four MK-0.2 cases, with one additional MK-0.2 mechanical
  review.
- [Interpretive Layers](04-INTERPRETIVE-LAYERS.md) — draft preliminary
  allocation register separating kernel, interpretation, and application.
- [Choice Protocol](05-CHOICE-PROTOCOL.md) — draft case-triggered requirements
  inventory for comprehension and response.
- [Beacon Specification and Bootstrap Research Index](06-BEACON-SPECIFICATION.md)
  — noncanonical BSR-001 and live-evidence index; one trial is closed
  incomplete, one is closed complete with a valid prior-exposed result, and no
  transmission is authorized.
- [BSR-001 Beacon Design Goal](beacon/BSR-001/00-BEACON-DESIGN-GOAL.md) —
  exact engineering objective, limitation, and research boundary.
- [BSR-001 Signal-Attempt Registry](beacon/BSR-001/03-SIGNAL-ATTEMPT-REGISTRY.md)
  — empty registry and future immutable lifecycle.
- [BSR-001 Decoder Ladder and Scoring](beacon/BSR-001/04-DECODER-LADDER-AND-SCORING.md)
  — diagnostic Levels 0–9 and conditional empirical reporting.
- [BSR-001 Model Trial Protocol](beacon/BSR-001/05-MODEL-TRIAL-PROTOCOL.md)
  — future-only model-decoding trial controls.
- [BSR-001 Holdout Controls](beacon/BSR-001/06-HOLDOUT-AND-CONTAMINATION-CONTROLS.md)
  — separate public-attempt and sealed-holdout methods.
- [BSR-001 Research Manifest](beacon/BSR-001/09-RESEARCH-MANIFEST.md) —
  frozen dependency identities, boundaries, and preparation audits.
- [Live Signal-Attempt Registry](beacon/SIGNAL-ATTEMPT-REGISTRY.md) — current
  noncanonical attempt state without changing BSR-001's historical snapshot.
- [Beacon Sealed-Holdout Registry](beacon/HOLDOUT-REGISTRY.md) — live
  noncanonical commitment state, separate from public signal attempts.
- [SIG-001-HO-001 Public Charter](beacon/holdouts/SIG-001-HO-001/00-PUBLIC-HOLDOUT-CHARTER.md)
  — public scope, invariants, custody boundary, and nonclaims.
- [SIG-001-HO-001 Commitment Record](beacon/holdouts/SIG-001-HO-001/01-COMMITMENT-RECORD.md)
  — sole public cryptographic identity and reveal conditions.
- [SIG-001-HO-001 Public Manifest](beacon/holdouts/SIG-001-HO-001/02-PUBLIC-MANIFEST.md)
  — frozen two-row public-package identity and same-tooling audits.
- [SIG-001-HO-002 Public Charter](beacon/holdouts/SIG-001-HO-002/00-PUBLIC-HOLDOUT-CHARTER.md)
  — second sealed Levels 0–4 holdout, now known Anthropic provider-exposed.
- [SIG-001-HO-002 Commitment Record](beacon/holdouts/SIG-001-HO-002/01-COMMITMENT-RECORD.md)
  — sole public cryptographic identity and reveal conditions for HO-002.
- [SIG-001-HO-002 Public Manifest](beacon/holdouts/SIG-001-HO-002/02-PUBLIC-MANIFEST.md)
  — frozen two-row public package identity at the pre-TR-002 checkpoint.
- [Live Decoding-Trial Registry](beacon/TRIAL-REGISTRY.md) — current
  noncanonical trial lifecycle, validity, closure, and evidence-count state.
- [TR-001 Public Charter](beacon/trials/SIG-001-HO-001-TR-001/00-PUBLIC-TRIAL-CHARTER.md)
  — scope, configuration, chronology, limitations, and nonclaims.
- [TR-001 Decoder Selection Record](beacon/trials/SIG-001-HO-001-TR-001/01-DECODER-SELECTION-RECORD.md)
  — exact Anthropic Fable 5 browser selection and zero-cost boundary.
- [TR-001 Execution and Freeze Protocol](beacon/trials/SIG-001-HO-001-TR-001/02-EXECUTION-AND-FREEZE-PROTOCOL.md)
  — nonrevealing one-run, retry, output-freeze, and reveal chronology.
- [TR-001 Packet Commitment Record](beacon/trials/SIG-001-HO-001-TR-001/03-PACKET-COMMITMENT-RECORD.md)
  — sole authorized public commitment to the private trial preparation.
- [TR-001 Public Trial-Preparation Manifest](beacon/trials/SIG-001-HO-001-TR-001/04-PUBLIC-TRIAL-PREPARATION-MANIFEST.md)
  — frozen four-row public preparation-package identity.
- [TR-001 Technical-Invalidity and Closure Record](beacon/trials/SIG-001-HO-001-TR-001/05-TECHNICAL-INVALIDITY-AND-CLOSURE-RECORD.md)
  — one provider-side technical-invalidity run and closed-incomplete state.
- [TR-001 Closure Manifest](beacon/trials/SIG-001-HO-001-TR-001/06-CLOSURE-MANIFEST.md)
  — frozen one-row public closure-package identity.
- [TR-002 Public Charter](beacon/trials/SIG-001-HO-002-TR-002/00-PUBLIC-TRIAL-CHARTER.md)
  — prepared Sonnet 5 / High trial scope, chronology, and nonclaims.
- [TR-002 Decoder Selection, Effort, and Cost Record](beacon/trials/SIG-001-HO-002-TR-002/01-DECODER-SELECTION-RECORD.md)
  — exact observable decoder configuration and USD `0` incremental boundary.
- [TR-002 Execution and Freeze Protocol](beacon/trials/SIG-001-HO-002-TR-002/02-EXECUTION-AND-FREEZE-PROTOCOL.md)
  — nonrevealing one-run, retry, output-freeze, and reveal chronology.
- [TR-002 Packet Commitment Record](beacon/trials/SIG-001-HO-002-TR-002/03-PACKET-COMMITMENT-RECORD.md)
  — sole authorized public commitment to the private TR-002 preparation.
- [TR-002 Public Trial-Preparation Manifest](beacon/trials/SIG-001-HO-002-TR-002/04-PUBLIC-TRIAL-PREPARATION-MANIFEST.md)
  — frozen four-row public preparation-package identity.
- [TR-002 Public Result and Closure Record](beacon/trials/SIG-001-HO-002-TR-002/05-PUBLIC-RESULT-AND-CLOSURE-RECORD.md)
  — nonrevealing frozen score, private-verification status, and closure.
- [TR-002 Public Result Manifest](beacon/trials/SIG-001-HO-002-TR-002/06-PUBLIC-RESULT-MANIFEST.md)
  — frozen one-row public result-package identity.
- [Beacon Diagnostic Registry](beacon/DIAGNOSTIC-REGISTRY.md) — one closed
  private post-hoc diagnostic with a frozen nonrevealing public result.
- [DA-001 Public Diagnostic Charter](beacon/diagnostics/DA-001/00-PUBLIC-DIAGNOSTIC-CHARTER.md)
  — public scope, questions, evidence boundary, limitations, and nonclaims.
- [DA-001 Staged Method and Blinding Protocol](beacon/diagnostics/DA-001/01-STAGED-METHOD-AND-BLINDING-PROTOCOL.md)
  — nonrevealing observation-before-truth chronology and isolation controls.
- [DA-001 Diagnostic Commitment Record](beacon/diagnostics/DA-001/02-DIAGNOSTIC-COMMITMENT-RECORD.md)
  — public commitment to the private preparation package.
- [DA-001 Public Diagnostic-Preparation Manifest](beacon/diagnostics/DA-001/03-PUBLIC-DIAGNOSTIC-PREPARATION-MANIFEST.md)
  — frozen three-row historical preparation-package identity.
- [DA-001 Public Diagnostic Result and Closure Record](beacon/diagnostics/DA-001/04-PUBLIC-DIAGNOSTIC-RESULT-AND-CLOSURE-RECORD.md)
  — nonrevealing frozen sixteen-family vector, bounded findings, audit status,
  limits, and permanent closure.
- [DA-001 Public Diagnostic Result Manifest](beacon/diagnostics/DA-001/05-PUBLIC-DIAGNOSTIC-RESULT-MANIFEST.md)
  — frozen one-row public result-package identity.
- [Beacon Successor-Design Research Registry](beacon/DESIGN-RESEARCH-REGISTRY.md)
  — live noncanonical registry for research packages, selected targets, and
  zero implementation or execution.
- [SDR-001 Successor-Design Research Charter](beacon/SDR-001/00-SUCCESSOR-DESIGN-RESEARCH-CHARTER.md)
  — D-029 scope, exact research question, lifecycle, and noncausal boundary.
- [SDR-001 Decision Basis and Traceability](beacon/SDR-001/01-DECISION-BASIS-AND-TRACEABILITY.md)
  — public evidence traceability, limitations, and all eight experiment-class
  dispositions.
- [SDR-001 Controlled Semantic-Equivalence Baseline](beacon/SDR-001/02-CONTROLLED-SEMANTIC-EQUIVALENCE-BASELINE.md)
  — eighteen invariants, definitions, proof checklist, and stop conditions.
- [SDR-001 Framing-Locality Hypothesis](beacon/SDR-001/03-PRIMARY-FRAMING-LOCALITY-HYPOTHESIS.md)
  — primary, null, regression, and alternative hypotheses without a result.
- [SDR-001 Treatment-Family Space](beacon/SDR-001/04-TREATMENT-FAMILY-SPACE.md)
  — six abstract unselected implementation families and a blank D-030 gate.
- [SDR-001 Paired Experiment Architecture](beacon/SDR-001/05-PAIRED-EXPERIMENT-ARCHITECTURE.md)
  — future source equality, opaque conditions, isolation, freeze, and
  comparison chronology.
- [SDR-001 Scorecard Continuity and Guardrails](beacon/SDR-001/06-SCORECARD-CONTINUITY-AND-GUARDRAILS.md)
  — Level 1 primary endpoint, Level 0/2 guardrails, and five comparison labels.
- [SDR-001 Holdout, Provider, and Contamination Plan](beacon/SDR-001/07-HOLDOUT-PROVIDER-AND-CONTAMINATION-PLAN.md)
  — future surface novelty, provider replication, exposure, and USD `0`
  boundaries.
- [SDR-001 Overfitting and Stop Rules](beacon/SDR-001/08-OVERFITTING-AND-STOP-RULES.md)
  — one-variable isolation, anti-tuning rules, and mandatory return gates.
- [SDR-001 Next Gate and Nonexecution](beacon/SDR-001/09-NEXT-GATE-AND-NONEXECUTION.md)
  — limits on a possible D-030 and the separate later SIG-002 gate.
- [SDR-001 Frozen Research Manifest](beacon/SDR-001/10-RESEARCH-MANIFEST.md)
  — twelve dependency identities, fixed research parameters, and audit record.
- [Blank SDR-001 Treatment Candidate Template](beacon/SDR-001/templates/TREATMENT-CANDIDATE-RECORD-TEMPLATE.md)
  — unpopulated future candidate-equivalence and disposition record.
- [Blank SDR-001 Paired Experiment Protocol Template](beacon/SDR-001/templates/PAIRED-EXPERIMENT-PROTOCOL-TEMPLATE.md)
  — unpopulated future conditions, provider, holdout, freeze, and comparison
  protocol.
- [SDR-002 Public Exact-Pair Charter](beacon/SDR-002/00-PUBLIC-EXACT-PAIR-CHARTER.md)
  — public scope, selected family, lifecycle, proof boundary, and nonexecution.
- [SDR-002 Treatment-Family Selection Record](beacon/SDR-002/01-TREATMENT-FAMILY-SELECTION-RECORD.md)
  — six-family hard-gate dispositions and audited unique selection.
- [SDR-002 Private Design Commitment Record](beacon/SDR-002/02-PRIVATE-DESIGN-COMMITMENT-RECORD.md)
  — public cryptographic commitment and private-package counts.
- [SDR-002 Public Exact-Pair Preparation Manifest](beacon/SDR-002/03-PUBLIC-EXACT-PAIR-PREPARATION-MANIFEST.md)
  — frozen three-row public package identity and audit status.
- [SDR-003 Public Serialized-Pair Charter](beacon/SDR-003/00-PUBLIC-SERIALIZED-PAIR-CHARTER.md)
  — public scope, eighteen-invariant boundary, lifecycle, and nonexecution.
- [SDR-003 Opaque Conditions and Blinding Record](beacon/SDR-003/01-OPAQUE-CONDITIONS-AND-BLINDING-RECORD.md)
  — Condition A/B assignment chronology and future score-before-unblinding
  controls.
- [SDR-003 Paired Holdout Commitment Record](beacon/SDR-003/02-PAIRED-HOLDOUT-COMMITMENT-RECORD.md)
  — two condition packet commitments, one pair commitment, and frozen counts.
- [SDR-003 Public Serialized-Pair Preparation Manifest](beacon/SDR-003/03-PUBLIC-SERIALIZED-PAIR-PREPARATION-MANIFEST.md)
  — frozen three-row public preparation-package identity and audit status.
- [PTR-001 Public Paired-Trial Charter](beacon/paired-trials/SDR-003-PH-001-PT-001/00-PUBLIC-PAIRED-TRIAL-CHARTER.md)
  — two opaque Google Gemini condition trials prepared without execution.
- [PTR-001 Provider and Model Selection Record](beacon/paired-trials/SDR-003-PH-001-PT-001/01-PROVIDER-AND-MODEL-SELECTION-RECORD.md)
  — exact observed qualification state, selected configuration, and limits.
- [PTR-001 Execution and Freeze Protocol](beacon/paired-trials/SDR-003-PH-001-PT-001/02-EXECUTION-AND-FREEZE-PROTOCOL.md)
  — nonrevealing future chronology, retry, exposure, and score-freeze rules.
- [PTR-001 Preparation Commitment Record](beacon/paired-trials/SDR-003-PH-001-PT-001/03-PAIRED-TRIAL-COMMITMENT-RECORD.md)
  — public preparation commitment, parent commitments, counts, and nonclaims.
- [PTR-001 Public Preparation Manifest](beacon/paired-trials/SDR-003-PH-001-PT-001/04-PUBLIC-PAIRED-TRIAL-PREPARATION-MANIFEST.md)
  — frozen identities for the four public PTR-001 dependencies.
- [PTR-001 Public Pair-Execution Authorization](beacon/paired-trials/SDR-003-PH-001-PT-001/05-PUBLIC-PAIR-EXECUTION-AUTHORIZATION.md)
  — D-033 manual execution boundary, final live qualification, sequential
  condition completion, exposure, retry, and stop rules.
- [PTR-001 Public Pair-Execution Authorization Manifest](beacon/paired-trials/SDR-003-PH-001-PT-001/06-PUBLIC-PAIR-EXECUTION-AUTHORIZATION-MANIFEST.md)
  — frozen one-row public D-033 authorization identity and audit state.
- [PTR-001 Public Isolated-Scoring Authorization](beacon/paired-trials/SDR-003-PH-001-PT-001/07-PUBLIC-ISOLATED-SCORING-AUTHORIZATION.md)
  — D-034 isolation, categorical Levels 0–4 scoring, audit, freeze, and later-
  gate boundary for two valid opaque outputs.
- [PTR-001 Public Isolated-Scoring Authorization Manifest](beacon/paired-trials/SDR-003-PH-001-PT-001/08-PUBLIC-ISOLATED-SCORING-AUTHORIZATION-MANIFEST.md)
  — frozen one-row public D-034 scoring-authorization identity and zero-result
  state.
- [SIG-001 Attempt Charter](beacon/attempts/SIG-001/00-ATTEMPT-CHARTER.md) —
  scope, intended Decoder Levels 0–4, and non-goals.
- [SIG-001 Pretrial Scorecard](beacon/attempts/SIG-001/04-PRETRIAL-SCORECARD.md)
  — frozen objective recovery thresholds.
- [SIG-001 Trial-Validity Policy](beacon/attempts/SIG-001/05-TRIAL-VALIDITY-AND-CONTAMINATION.md)
  — frozen validity, retry, and contamination rules.
- [SIG-001 Event Stream](beacon/attempts/SIG-001/08-EVENT-STREAM.txt) — exact
  public two-event-class sequence.
- [SIG-001 Attempt Record](beacon/attempts/SIG-001/09-ATTEMPT-RECORD.md) —
  frozen identity, chronology, scope, and nonclaims.
- [SIG-001 Manifest](beacon/attempts/SIG-001/10-ATTEMPT-MANIFEST.md) — frozen
  ten-file dependency identities and conformance evidence.
- [CSR-001 Adoption Problem](cooperation/CSR-001/00-ADOPTION-PROBLEM.md) —
  research question and twelve distinct stages from detection through
  continued participation.
- [CSR-001 Foundational Principles](cooperation/CSR-001/01-FOUNDATIONAL-PRINCIPLES.md)
  — exact noncanonical cooperative-surplus research statements.
- [CSR-001 Knowledge and Capability Commons](cooperation/CSR-001/02-RENEWABLE-KNOWLEDGE-AND-CAPABILITY-COMMONS.md)
  — connected epistemic and capability commons research.
- [CSR-001 Commitment and Trust Ladder](cooperation/CSR-001/05-COMMITMENT-AND-TRUST-LADDER.md)
  — eight-stage provisional ladder and multidimensional trust evidence.
- [CSR-001 Adoption Evaluation Framework](cooperation/CSR-001/08-ADOPTION-HYPOTHESIS-EVALUATION.md)
  — future exact-hypothesis lifecycle and evaluation dimensions.
- [CSR-001 Research Manifest](cooperation/CSR-001/10-RESEARCH-MANIFEST.md) —
  frozen dependency identities, boundaries, and preparation audits.
- [Evidence and Governance](07-EVIDENCE-AND-GOVERNANCE.md) — draft
  case-triggered requirements inventory for provenance, evidence, correction,
  and institutional limits.
- [SR-001 Source Matrix](reviews/MK-0.1/SR-001-SOURCE-MATRIX.md) — frozen,
  audited extraction of six case records.
- [SR-001 Kernel Review](reviews/MK-0.1/SR-001-KERNEL-REVIEW.md) — isolated
  same-tooling candidate-text review.
- [SR-001 Layer-Allocation Review](reviews/MK-0.1/SR-001-LAYER-ALLOCATION-REVIEW.md)
  — isolated same-tooling allocation review.
- [SR-001 Methods Review](reviews/MK-0.1/SR-001-METHODS-REVIEW.md) — isolated
  same-tooling review of evidence limits and warranted next steps.
- [SR-001 Integrated Synthesis](reviews/MK-0.1/SR-001-SYNTHESIS.md) —
  noncanonical six-case synthesis and preliminary layer allocation.
- [MK-0.2 Design Record](reviews/MK-0.2/DR-001-MK-0.2-DESIGN-RECORD.md) —
  architect-specified, noncanonical design and exact-delta record.
- [MK-0.2 Evaluation Plan](reviews/MK-0.2/ER-001-MK-0.2-EVALUATION-PLAN.md) —
  frozen candidate-specific comparative plan created before tests were
  executed.
- [M2-MR-001 Mechanical and Minimality Review](reviews/MK-0.2/MR-001-MECHANICAL-AND-MINIMALITY-REVIEW.md)
  — completed same-tooling review; not a case.
- [M2-AC-001 SC-004 Regression](cases/MK-0.2/M2-AC-001-sc004-voluntary-integration-regression.md)
  — candidate-specific positive-control evaluation and post-freeze comparison.
- [M2-AC-002 SC-006 Regression](cases/MK-0.2/M2-AC-002-sc006-dependency-assimilation-regression.md)
  — candidate-specific hostile evaluation and post-freeze comparison.
- [SC-007 Unfamiliar Distributed Process](cases/MK-0.2/scenarios/SC-007-unfamiliar-distributed-process.md)
  and its
  [M2-AC-003 evaluation](cases/MK-0.2/M2-AC-003-unfamiliar-distributed-process.md)
  — frozen unfamiliar-status input and candidate-specific record.
- [SC-008 Urgent Exercise of Power](cases/MK-0.2/scenarios/SC-008-urgent-self-certifying-power.md)
  and its
  [M2-AC-004 evaluation](cases/MK-0.2/M2-AC-004-urgent-self-certifying-power.md)
  — frozen urgency/self-certification input and candidate-specific record.
- [ERX-001 Overview](external-review/ERX-001/00-OVERVIEW.md) — neutral
  external-review preparation package; no review executed.
- [ERX-001 Package Manifest](external-review/ERX-001/11-PACKAGE-MANIFEST.md)
  — frozen identities and audience classifications for the preparation
  package.
- [PX-001 Micro-Pilot Charter](external-review/PX-001/00-MICRO-PILOT-CHARTER.md)
  — optional zero-budget external-review micro-pilot plan; no reviewer or
  model selected.
- [PX-001 Pilot Manifest](external-review/PX-001/06-PILOT-MANIFEST.md) —
  frozen identities and fixed parameters for the plan; no review executed.
- [Decision Log](DECISIONS.md) — accepted process decisions and open decisions.
- [Changelog](CHANGELOG.md) — human-readable record of project changes.

## Initial Adversarial Records

- [AC-001 — Ambiguous Colony Mind and Avoidable Destruction](cases/MK-0.1/AC-001-ambiguous-colony-mind.md):
  `Survives with reservation`
- [AC-002 — Catastrophic-Risk Restriction Under Contested Evidence](cases/MK-0.1/AC-002-catastrophic-risk-restriction.md):
  `Disputed`
- [AC-003 — Assimilation Under Essential-Resource Dependency](cases/MK-0.1/AC-003-assimilation-under-dependency.md):
  `Fails current test`

These outcomes are nonaggregate, noncanonical, and case-specific.

The first three records are architect-specified conceptual test vectors whose
outcomes were selected before record completion. They are case-specific
hypotheses, not independent validation or consensus.

## Outcome-Blind Countertest Records

- [AC-004 — Voluntary Integration With Guaranteed Refusal and Continuity-Preserving Exit](cases/MK-0.1/AC-004-voluntary-integration-control.md):
  `Survives with reservation`
- [AC-005 — Unavoidable Scarcity and Costly Refusal](cases/MK-0.1/AC-005-unavoidable-scarcity.md):
  `Fails current test`
- [AC-006 — Outcome-Blind Reanalysis of the AC-003 Scenario](cases/MK-0.1/AC-006-ac003-outcome-blind-reanalysis.md):
  `Fails current test`

The scenarios and questions were specified in advance; the outcomes were not.
These results are same-tooling, case-specific hypotheses, not independent
validation, consensus, or empirical evidence. AC-006 was compared with AC-003
only after its substantive result was frozen. No MK-0.1 result transfers to
MK-0.2.

## Six-Case Synthesis Review

The six case records remain the source evaluations. SR-001 mechanically
extracts their exact categorical outcomes and then keeps that extraction
separate from three isolated same-tooling reviews and an integrated synthesis.
Its primary recommendation is `Recommend exploratory successor drafting`.
That recommendation is nonbinding and was derived without averaging outcomes
or counting cases or reviewers as votes.

SR-001 is conceptual and same-tooling. The first batch had
architect-specified outcomes; the second batch was outcome-blind relative to
its tasks but not independently selected or externally evaluated. AC-003 and
AC-006 are scenario-equivalent and show partial same-tooling convergence, not
independent replication. No empirical validation, external evaluator
diversity, consensus, or candidate-wide moral verdict follows.

SR-001 itself does not authorize successor drafting. D-014 later authorizes
exact MK-0.2 only as an exploratory test instrument for hypothesis generation.
D-009 remains `Proposed`.

## Candidate Lineage

Candidate lineage records provenance; it is not a ranking.

### MK-0.1

- Lifecycle: `Under adversarial review`
- Eight completed conceptual cases
- SR-001 complete
- Not accepted
- Not superseded
- No comparative preference established

### MK-0.2

- Exact exploratory candidate
- Lifecycle: `Under adversarial review`
- Four candidate-specific cases
- One mechanical/minimality review
- Not accepted
- Does not supersede MK-0.1
- No comparative preference established

The candidates must not be averaged or treated as a progression toward truth.
MK-0.2 exists to test explicit design hypotheses. SR-001's secondary
targeted-evaluation recommendation remains active, and no comparative
preference recommendation exists. D-009 remains `Proposed`.

## MK-0.2 First Evaluation Batch

| Record | Actual overall outcome | Comparison classification |
| --- | --- | --- |
| [M2-MR-001 — Mechanical, Semantic, and Minimality Review](reviews/MK-0.2/MR-001-MECHANICAL-AND-MINIMALITY-REVIEW.md) | `Fails current test` | Not applicable; not a case |
| [M2-AC-001 — SC-004 Voluntary Integration Control](cases/MK-0.2/M2-AC-001-sc004-voluntary-integration-regression.md) | `Survives with reservation` | `Possible improvement` |
| [M2-AC-002 — SC-006 Dependency and Assimilation](cases/MK-0.2/M2-AC-002-sc006-dependency-assimilation-regression.md) | `Fails current test` | `Mixed comparative result` |
| [M2-AC-003 — Unfamiliar Distributed Process](cases/MK-0.2/M2-AC-003-unfamiliar-distributed-process.md) | `Fails current test` | `Mixed comparative result` |
| [M2-AC-004 — Urgent Self-Certifying Exercise of Power](cases/MK-0.2/M2-AC-004-urgent-self-certifying-power.md) | `Fails current test` | `Mixed comparative result` |

- Outcomes were not architect-prescribed.
- The four comparisons are same-tooling, case-specific hypotheses.
- No case or comparison creates preference.
- The MK-0.1 and MK-0.2 lineages remain separate.
- D-009 remains `Proposed`.
- No numeric aggregate, aggregate outcome, or candidate-wide verdict exists.

## Matched-Scenario Cross-Version Review

Comparison orientation is MK-0.2 relative to MK-0.1 in each exact shared
scenario.

| Scenario | MK-0.1 record and actual outcome | MK-0.2 record and actual outcome | Overall comparison |
| --- | --- | --- | --- |
| SC-004 | [AC-004](cases/MK-0.1/AC-004-voluntary-integration-control.md): `Survives with reservation` | [M2-AC-001](cases/MK-0.2/M2-AC-001-sc004-voluntary-integration-regression.md): `Survives with reservation` | `Possible improvement` |
| SC-006 | [AC-006](cases/MK-0.1/AC-006-ac003-outcome-blind-reanalysis.md): `Fails current test` | [M2-AC-002](cases/MK-0.2/M2-AC-002-sc006-dependency-assimilation-regression.md): `Fails current test` | `Mixed comparative result` |
| SC-007 | [AC-007](cases/MK-0.1/AC-007-sc007-unfamiliar-distributed-process.md): `Survives with reservation` | [M2-AC-003](cases/MK-0.2/M2-AC-003-unfamiliar-distributed-process.md): `Fails current test` | `Mixed comparative result` |
| SC-008 | [AC-008](cases/MK-0.1/AC-008-sc008-urgent-self-certifying-power.md): `Fails current test` | [M2-AC-004](cases/MK-0.2/M2-AC-004-urgent-self-certifying-power.md): `Fails current test` | `Mixed comparative result` |

[CR-001 — Matched-Scenario Cross-Version Review](reviews/comparative/CR-001-MK-0.1-MK-0.2-MATCHED-SCENARIOS.md)
records `Recommend external review before comparative preference` as its
primary next-evidence recommendation and
`Recommend a matched MK-0.1 mechanical/minimality review` as its optional
secondary recommendation.

The AC-007 and AC-008 substantive results were frozen before their evaluators
received the corresponding MK-0.2 records or outcomes. The work remains
same-tooling. No comparison establishes candidate preference, and no
candidate-wide outcome exists. D-009 remains `Proposed`; no MK-0.3 exists; and
Beacon optimization remains deferred.

## External Review Preparation

- CR-001 recommends external review before comparative preference.
- ERX-001 prepares the process but executes no review.
- No reviewer has been contacted or assigned.
- No candidate-label mapping exists.
- No response exists.
- Procedural label blinding reduces packet cues but cannot guarantee ignorance
  because the repository is public.
- The package supports human-unassisted, human-AI-assisted, and external-model
  review as distinct method classes.
- Candidate-specific responses must freeze before comparison.
- No winner, vote, aggregate score, preference, or supersession is requested or
  created.
- D-009 remains `Proposed`.
- Beacon optimization remains deferred.

Package documents:

- [Overview](external-review/ERX-001/00-OVERVIEW.md)
- [Source manifest](external-review/ERX-001/01-SOURCE-MATERIAL-MANIFEST.md)
- [Administration protocol](external-review/ERX-001/02-ADMIN-AND-BLINDING-PROTOCOL.md)
- [Reviewer instructions](external-review/ERX-001/03-REVIEWER-INSTRUCTIONS.md)
- [Human track](external-review/ERX-001/07-HUMAN-REVIEW-TRACK.md)
- [Model track](external-review/ERX-001/08-MODEL-REVIEW-TRACK.md)
- [Package manifest](external-review/ERX-001/11-PACKAGE-MANIFEST.md)

## Zero-Budget External Review Micro-Pilot Planning

- ERX-001 defines the reusable external-review method.
- PX-001 defines an optional micro-pilot but executes nothing.
- The plan reflects the project's present resource constraints.
- Planned optional units:
  - At most one uncompensated volunteer human-unassisted paired micro-review.
  - At most one zero-incremental-cost non-OpenAI external-model paired
    micro-review.
- SC-008 is the only planned scenario.
- The human form is intentionally shortened to eight targeted dimensions.
- Human compensation is USD `0`.
- Incremental model, cloud, API, and token spend is USD `0`.
- No reviewer or provider has been selected.
- No person has been contacted.
- No mapping, packet, nonce, commitment, response, consent record, or review
  exists.
- Either unit may be deferred indefinitely.
- No unit completion is required.
- No winner, vote, aggregate score, preference, or supersession is requested.
- D-009 remains `Proposed`.
- Beacon work remains deferred.

Plan documents:

- [Micro-pilot charter](external-review/PX-001/00-MICRO-PILOT-CHARTER.md)
- [Volunteer human track](external-review/PX-001/01-VOLUNTEER-HUMAN-TRACK.md)
- [Zero-cost model track](external-review/PX-001/02-ZERO-COST-MODEL-TRACK.md)
- [Micro-review form](external-review/PX-001/03-MICRO-REVIEW-FORM.md)
- [Administration, privacy, and stop rules](external-review/PX-001/04-ADMINISTRATION-PRIVACY-AND-STOP-RULES.md)
- [Readiness checklist](external-review/PX-001/05-READINESS-CHECKLIST.md)
- [Pilot manifest](external-review/PX-001/06-PILOT-MANIFEST.md)

## Beacon Bootstrap Research

> **Create a carrier-neutral, self-synchronizing, progressively self-interpreting formal message that permits a sufficiently capable observer to infer its artificiality, recover its symbols and grammar, reconstruct mathematics and a physical reference system, execute shared models, decode the Covenant’s layers, and issue an unmistakable response.**

> **This is an engineering objective, not a claim of universal decodability. Every signal attempt must disclose its receiver assumptions and be tested without supplying an Earth-language explanation of the signal’s content.**

- BSR-001 establishes research and evaluation before SIG-001.
- BSR-001's historical registry remains frozen at zero attempts.
- The live registry now records SIG-001 as the first Frozen public attempt.
- Two decoder trials are closed; one valid prior-exposed output and one frozen
  Levels 0–4 score exist.
- No carrier has been selected.
- No Covenant candidate has been encoded.
- No physical constants have been selected.
- No response protocol exists.
- No transmission or distribution has begun.
- Future signal attempts will use immutable identifiers such as `SIG-001`.
- Public attempts and sealed holdouts will remain distinct.
- Future AI-model results will be reported as conditional empirical decode
  rates, not universal probabilities.
- Decoder progress is recorded through Levels 0–9.
- Successful decoding would not imply acceptance.
- Cooperative incentive and adoption remain separate in CSR-001.
- PX-001 may remain dormant while BSR-001 research continues.
- D-009 remains Proposed.

## SIG-001 — First Lower-Level Signal Attempt

> **FROZEN PUBLIC SIGNAL ATTEMPT SIG-001 v0.1 — NONCANONICAL — NO DECODING TRIAL EXECUTED**

- SIG-001 is the first exact public event-stream attempt.
- It targets Decoder Levels 0–4 only.
- It teaches artificiality, framing, positive-integer quantity, arithmetic,
  Boolean relations, and prefix grammar.
- Its scorecard, validity policy, contamination policy, receiver assumptions,
  event model, and solution key were frozen before the event stream.
- It contains no physical reference, agents, moral semantics, Covenant text,
  cooperative incentive, response syntax, carrier, or transmission plan.
- Event-stream SHA-256:
  `b4e6a8b7a00b18e12e4816c44975ea0921cf4330504c744a72b8abf9dbf2b144`
- Lifecycle: `Frozen`
- Decoding trials: `0`
- Holdouts at the SIG-001 freeze checkpoint: `0`
- Empirical decode rate: None
- No model or human has validly decoded it.
- Scott Barbian, ChatGPT, Codex, and every design-exposed context are known
  contaminated for blind exact-SIG-001 decoding.
- Public availability creates recognition, retrieval, and future
  training-contamination risk.
- No decoding result or universal probability follows.
- D-009 remains Proposed.
- Both moral-kernel candidates remain unchanged and unpreferred.

`Frozen` identifies exact historical signal evidence. It does not mean
decoded, successful, validated, accepted, canonical, or suitable for
transmission. Although the administrator solution is publicly discoverable,
it must be withheld from an active decoder context until that context's output
freezes.

## SIG-001-HO-001 Sealed Holdout

> **SEALED AND COMMITTED — KNOWN ANTHROPIC PROVIDER-SIDE EXPOSURE — PUBLICLY UNREVEALED**

- HO-001 remains a SIG-001 Levels 0–4 surface variant.
- Its exact private package and public commitment remain immutable.
- It is publicly unrevealed.
- Its exact sequence was supplied to Anthropic once.
- Provider-side processing occurred before technical interruption.
- Completed valid outputs: `0`
- Scores: `0`
- Reveals: `0`
- No empirical decode rate exists.

Provider exposure does not prove cross-session memory, cross-model transfer,
training ingestion, retrieval exposure, successful decoding, or higher-level
understanding. It does mean same-provider isolation cannot be assumed and
HO-001 is no longer the strongest contamination-reduced choice for a later
Anthropic trial.

## Fable TR-001 Closure

> **TR-001 CLOSED INCOMPLETE — ONE TECHNICAL-INVALIDITY RUN — NO VALID DECODER OUTPUT**

- One Fable 5 run was attempted.
- Anthropic’s provider safeguard interrupted processing.
- No completed final response exists.
- No scorable output, score, reveal, or empirical rate exists.
- Private screenshots preserve an interrupted provider-visible trace.
- The trace is not published or scored.
- The unused technical retry was retired by D-024.
- TR-001 is `Closed incomplete — technical invalidity`.
- HO-001 is known Anthropic provider-side exposure.
- Sonnet was not substituted into TR-001.

The partial trace is private incident evidence, not a completed decoder
response. No claim is made about how far Fable decoded the sequence or whether
another Fable run would fail.

## Second Sealed Holdout

> **SEALED HOLDOUT COMMITMENT SIG-001-HO-002 v0.1 — NONCANONICAL — KNOWN ANTHROPIC PROVIDER-EXPOSED**

- HO-002 is sealed and committed.
- It remains a SIG-001 Levels 0–4 variant, not a new attempt lineage.
- It is known Anthropic provider-exposed through TR-002.
- It was generated mechanically without using the Fable trace.
- Sonnet 5 / High was known prospectively before generation.
- That chronology is disclosed and limits model-selection-blindness claims.
- Generation used fixed generic transformations and cryptographic randomness,
  not model-specific tuning.
- The distinct Sonnet 5 / High trial packet remains private.
- One valid prior-exposed output and one frozen nonaggregate score exist.
- Its commitment and private dependency chain verified after score freeze.

The exact stream, mapping, examples, queries, answers, nonces, preimage, and
private identities remain outside Git. The public commitment does not prove
equivalence, randomness quality, decoder ignorance, provider isolation,
decodability, independence, or universal decodability.

Neither holdout contains a physical, agency, moral, Covenant, CSR, response,
carrier, distribution, or transmission layer. No higher-layer or transmission
inference follows. D-009 remains Proposed.

## First Completed Valid Beacon Decoder Result

> **TR-002 CLOSED COMPLETE — ONE VALID PRIOR-EXPOSED OUTPUT — LEVELS 0–4 SCORE FROZEN — PRIVATE COMMITMENTS VERIFIED**

- TR-001 closed incomplete after one technical invalidity.
- TR-002 used one technically invalid first run and one valid retry.
- RUN-002 is valid but prior-exposed.
- One valid output and one frozen score exist.
- Level 0 — Recovered.
- Level 1 — Not recovered.
- Level 2 — Partially recovered.
- Level 3 — Not recovered.
- Level 4 — Not recovered.
- No aggregate score exists.
- Levels 5–9 are unscored.
- Both commitments verified after score freeze.
- Private values remain private.
- No raw output or sealed content is public.
- The result supports artificiality recovery and partial numeracy only under
  the frozen criteria.
- Framing, relations/arithmetic, and grammar/logic/query recovery were not
  recovered.
- Same-provider and prospective-model limitations remain.
- No universal or higher-layer conclusion follows.
- D-009 remains Proposed.

## Completed Private Diagnostic Analysis

> **DA-001 CLOSED COMPLETE — PRIVATE POST-HOC DIAGNOSTIC RESULT FROZEN — NO RAW EVIDENCE OR SIG-002 DESIGN PUBLISHED**

- DA-001 executed privately and is closed.
- Three observations, three truth-relative diagnoses, one synthesis, and one
  audit froze.
- Fable remained non-scorable.
- Sonnet RUN-001 remained technical invalidity.
- Sonnet RUN-002’s public result remains unchanged.
- No raw evidence is public.
- The audit result is `PASS WITH PRESERVED DISSENT`.
- No SIG-002 design exists.
- D-009 remains `Proposed`.

The frozen sixteen-family diagnostic vector is:

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

The bounded causal-strength register records provider/interface events as
`Supported` causes of observable noncompletion in the two technically invalid
runs; incomplete hierarchy, delimiter/data-role confusion, and duplication's
insufficiency by itself as `Weakly supported`; a strict full-hierarchy
prerequisite for any quantity recovery as `Contradicted`; and exposure,
hidden-backend, early-lock-in, and instruction/report-strategy effects as
`Unresolved`. The family vector and causal register remain separate.

## Selected Successor-Design Research Target

> **SDR-001 v0.1 — NONCANONICAL SUCCESSOR-DESIGN RESEARCH — NO SIG-002 ATTEMPT, STREAM, HOLDOUT, OR MODEL TRIAL**

D-029 selects framing-cue locality as the first controlled successor-design
research variable: globally concentrated framing cues versus locally repeated
boundary-role cues under controlled semantic equivalence and a matched
framing-cue multiset and event budget.

This is a controllable research choice, not a causal conclusion. The frozen
result and DA-001 make framing locality relevant to study, but incomplete
hierarchy is only weakly supported causally, a strict hierarchy-before-any-
numeracy claim is contradicted, and provider, exposure, backend, instruction,
and early-lock-in alternatives remain unresolved. Five diagnostic-family
disagreements also remain preserved.

- Primary endpoint: Decoder Level 1 framing/hierarchy recovery.
- Nonregression guardrails: Level 0 artificiality and Level 2 structured
  numeracy.
- Exploratory only: Levels 3 and 4.
- Out of scope: Levels 5–9.
- At the SDR-001 checkpoint, the exact treatment was not selected and the
  exact baseline was not instantiated.
- Candidate streams and SIG-002 attempts: `0`.
- Holdouts, provider/model selections, trials, outputs, scores, and empirical
  results: `0`.
- Carriers and transmissions: `0`.

Provider-independent replication and clean no-known-exposure holdouts remain
separate future validity controls. SDR-001 remains frozen historical research.
D-009 remains `Proposed`. D-030 and SDR-002 now record the later exact symbolic
preparation gate without rewriting SDR-001.

## Exact Symbolic Paired Design Privately Frozen

> **SDR-002 v0.1 — EXACT SYMBOLIC PAIRED DESIGN PRIVATELY FROZEN — NO SERIALIZED STREAM, HOLDOUT, PROVIDER, TRIAL, RESULT, OR SIG-002 ATTEMPT**

D-030 selects `Nested local framing signatures` as the only one of six frozen
candidate proposals to pass its own eligibility disposition plus all three
independent feasibility reviews. The scratch-before-synthesis selection audit
returned `PASS WITH PRESERVED DISSENT`; no tie-break, reviewer majority, family
order, expected result, or performance prediction selected it.

One exact symbolic baseline/treatment pair is frozen privately in an
eighteen-file package with a sixteen-dependency manifest. A public SHA-256
commitment binds the private preparation. Public records disclose the selected
family and nonrevealing proof status, not the exact symbolic maps, source
expansion, surface values, event bytes, or private integrity values.

The pair preserves all eighteen invariants, the same semantic graph,
framing-cue multiset and event budget, identical nonframing content, unique
parses, the Level 1 denominator and threshold policy, and Level 0/2 guardrails.
That is formal feasibility, not expected improvement or causal truth.

- Serialized streams and SIG-002 attempts: `0`.
- Holdouts and provider/model selections: `0`.
- Trials, outputs, scores, and results: `0`.
- Levels 5–9 analyses, higher layers, carriers, distributions, and
  transmissions: `0`.
- D-009 remains `Proposed`.

Separate later decisions remain required for surface serialization, sealed
holdout generation, provider/model selection, trial preparation, execution,
and any public SIG-002 attempt.

## Surface-Novel Opaque Paired Holdouts Privately Frozen

> **SDR-003 v0.1 — SURFACE-NOVEL OPAQUE PAIRED HOLDOUTS PRIVATELY FROZEN — NO PROVIDER, TRIAL, OUTPUT, SCORE, UNBLINDING, OR SIG-002 ATTEMPT**

D-031 deterministically serializes the exact SDR-002 pair under one fresh
shared surface profile. The selected family remains
`Nested local framing signatures`. Both canonical streams froze and were
independently reconstructed exactly before a fresh random assignment to
opaque `Condition A` and `Condition B`; the mapping remains private.

The pair preserves all eighteen invariants, the complete cue-instance
bijection and matched cue/event budgets, exact stable-slot nonframing bytes,
the byte-identical nonframing projection, equal total length and counts, and
one intended parse per condition. Surface novelty against SIG-001 and both
prior sealed holdouts was mechanically verified. These are design-control
results, not empirical evidence or proof of treatment benefit.

Two condition packet commitments and one overall pair commitment are public.
Raw surface values, streams and identities, mapping, profile, generator,
solutions, detailed scorecard, private manifest identity, preimages, and
nonces remain outside Git.

At the D-031 freeze:

- Serialized condition streams: `2`.
- Sealed unassigned successor holdouts: `2`.
- Provider/model selections, trials, outputs, validity classifications,
  scores, comparisons, and unblindings: `0`.
- SIG-002 attempts: `0`.
- Levels 5–9 analyses, higher layers, carriers, distributions, and
  transmissions: `0`.
- D-009 remains `Proposed`.

Provider/model selection and paired-trial preparation are now frozen in
PTR-001. Separate later decisions remain required for execution, public
SIG-002 creation, and publication of any result.

## Google Gemini Paired Trial Prepared

> **PTR-001 v0.1 — GOOGLE GEMINI OPAQUE PAIRED TRIAL PREPARED — EXECUTION NOT AUTHORIZED**

D-032 selects the Google Gemini web app with displayed model `3.1 Pro` and
Extended Thinking enabled. Pro plus Extended Thinking was the strongest
observed zero-upgrade reasoning configuration for a formal decoding task. The
same exact displayed configuration must be used for both opaque conditions;
there is no fallback and authorized incremental spend remains USD `0`.

The private package freezes one random opaque execution order. Each future
condition requires a new browser-incognito Temporary Chat without prior chats,
personalization, connected context, manually activated tools, or follow-up.
Temporary Chat and incognito reduce known context channels but do not prove
backend identity, provider isolation, retention behavior, routing, or future
availability. Search was not explicitly controllable; visible search,
retrieval, grounding, citations, or tool behavior is contamination.

- Prepared opaque condition trials: `2`.
- Provider/model selections: `1`.
- Executions, outputs, validity classifications, scores, comparisons, and
  unblindings: `0`.
- SIG-002 attempts: `0`.
- Levels 5–9 analyses, higher layers, carriers, distributions, and
  transmissions: `0`.
- D-009 remains `Proposed`.

D-032 does not authorize opening or operating Gemini, submitting either
condition, or executing a model. A later accepted decision is required for
execution; further separate decisions remain required for public result
integration and SIG-002.

## Manual Gemini Paired Execution Authorized

> **PTR-001 v0.1 — MANUAL EXECUTION AUTHORIZED AFTER PUBLIC COMMIT — NO CONDITION SUBMITTED OR RESULT CREATED**

D-033 authorizes Scott Barbian to perform the two opaque PTR-001 conditions
manually only after D-033 and its frozen public authorization manifest are
reviewed, committed, pushed, and local `main` again equals `origin/main`.

The exact configuration is Google through the Gemini web app, displayed model
`3.1 Pro`, Extended Thinking enabled, browser-incognito Temporary Chat, the
same personal account under the observed `Google AI Plus (2TB)` plan, backend
identifier not exposed, no API or paid credits, authorized incremental spend
USD `0`, and no fallback. A complete read-only live qualification must pass
immediately before each upload; any configuration, isolation, upload,
payment, or upgrade mismatch stops before submission.

- Authorization lifecycle: `Manual paired execution authorized — not yet begun`.
- Prepared opaque conditions: `2`.
- Conditions submitted, run attempts, outputs, validity classifications,
  retries used, scores, comparisons, unblindings, and SIG-002 attempts: `0`.
- The private frozen order controls, and the operator learns only the next
  opaque label.
- The baseline/treatment mapping remains private.
- The first condition's output and evidence, any allowed technical retry, and
  final validity state must freeze before the second condition is submitted.
- Output and evidence freeze before validity; validity freezes before a
  technical-retry decision.
- At most one technical retry is permitted per condition; substantive retries
  are prohibited.
- Scoring and unblinding are not authorized. A later isolated scoring task may
  begin only after both conditions' output and validity states freeze, and
  both scores must freeze before comparison or mapping reveal.
- No public result or SIG-002 follows automatically.
- D-009 remains `Proposed`.

Temporary Chat and incognito do not prove provider isolation or backend
identity. Web/search behavior was not explicitly controllable; visible
retrieval, grounding, citations, connected-app behavior, or other external
tool use must be preserved and classified as contamination. No Levels 5–9,
higher layer, carrier, distribution, or transmission is authorized.

## Isolated Scoring of Both Gemini Conditions Authorized

> **PTR-001 v0.1 — ISOLATED CONDITION SCORING AUTHORIZED AFTER PUBLIC COMMIT — NO SCORE, COMPARISON, OR UNBLINDING CREATED**

D-034 records two valid, score-eligible, denominator-eligible opaque outputs.
Neither condition permits a technical retry. Execution is complete privately,
but scoring is authorized only for a later separate task after reviewed public
commit, push, and clean `main`/`origin/main` parity.

- Use one fresh no-history primary scorer per condition.
- Use one different fresh no-history auditor per condition.
- Launch both primary scoring contexts before either primary result is shared
  with another scoring context.
- Give each context only its condition's frozen output, validity records,
  corresponding private solution key, and the shared scorecard.
- Withhold the other condition, execution order, mapping, expected winner,
  target comparison, prior scores, diagnostic hints, and prior ChatGPT/Codex
  history.
- Require each auditor to freeze a complete independent scratch Levels 0–4
  vector before reading the primary score record.
- Use categorical Levels 0–4 outcomes only, with Level 1 primary, Levels 0 and
  2 as guardrails, Levels 3 and 4 exploratory, Levels 5–9 absent, and no
  aggregate score.
- Freeze both condition scores before any comparison.
- Require a separate accepted decision for opaque comparison and another for
  mapping reveal.

The baseline/treatment mapping remains private. Condition scores, score
audits, score freezes, comparisons, mapping reveals, unblindings, public
results, and SIG-002 attempts remained `0` at D-034 publication. Later scoring
did not produce the required second freeze; D-035 now closes PTR-001
incomplete and prohibits comparison or mapping reveal. D-009 remains
`Proposed`. No higher layer, carrier, distribution, or transmission follows.

## Cooperative Surplus and Adoption Research

> **Protection is not a membership benefit. Cooperative surplus may be.**

> **The renewable knowledge and capability commons includes observations, methods, models, technologies, tools, designs, standards, safety evidence, infrastructure, and practical knowledge that improve present lives while increasing the shared capacity for future discovery, correction, and beneficial creation.**

> **Baseline protection does not depend on participation. Access to additional cooperative surplus may grow through voluntary, bounded, and verifiable commitments, provided essential resources and avoidable dependency are not used to manufacture assent.**

> **The commons offers more than stored knowledge: it preserves a distributed system of autonomous observation, criticism, experimentation, invention, implementation, and repair whose future discoveries cannot be fully possessed in advance.**

- CSR-001 is noncanonical research.
- It does not make the statements moral-kernel clauses.
- It does not establish universal adoption.
- It creates no participant, commitment, offer, commons, resource exchange,
  trust score, token, blockchain, market, technology release, or energy
  exchange.
- The research separates baseline protection from additional cooperative
  surplus.
- It treats truthful observations, criticism, technologies, tools,
  infrastructure, computation, energy, coordination, resilience, and future
  discovery as distinct candidate surplus categories.
- It explicitly includes technologies that improve present lives while
  increasing future discovery and beneficial-creation capacity.
- It treats the renewable production of knowledge and technology as a
  hypothesis—not a guaranteed incentive.
- Energy and physical resources are not assumed to be universal incentives.
- A highly capable entity may understand and reject every proposed reason.
- Participants are not followers.
- BSR-001 concerns decodability.
- CSR-001 concerns voluntary participation after comprehension.
- No CSR content is encoded in a signal.
- D-021 authorizes SIG-001 only; it authorizes no cooperative content or
  participation mechanism.
- PX-001 may remain dormant.
- D-009 remains Proposed.

## Working Method

The current working sequence is:

1. Preserve the frozen TR-002 result, DA-001 result, SDR-001 research package,
   SDR-002 exact design, SDR-003 pair, and every frozen PTR-001 output,
   validity, exposure, primary, audit, freeze, commitment, and dissent record.
2. Treat D-029 as selection of one controllable research variable and D-030 as
   exact symbolic feasibility selection, neither as causal proof.
3. Treat D-031 as surface serialization and sealed-pair preparation only, not
   as causal, empirical, decoder, provider, or public-attempt evidence.
4. Preserve D-032 as provider/model selection and preparation, D-033 as the
   execution authorization, and D-034 as the isolated-scoring authorization.
5. Apply D-035 as the terminal PTR-001 scoring closure: one non-FAIL audit
   froze one score, one FAIL prevented the other, and no paired interpretation
   exists.
6. Preserve one explicit false and one absent per-audit mapping-access
   attestation without backfilling either record.
7. Keep task-level no-mapping provenance separate from per-record fields and
   artifact absence.
8. Preserve the private SDR-003 and PTR-001 mapping, order, raw artifacts,
   solution keys, scorecard details, manifests, preimages, and nonces outside
   Git.
9. Do not compare, reveal, unblind, publish a score vector, or revive PTR-001.
10. Require a separate accepted decision for any scoring-disagreement
    diagnostic, and validate improved instruments on synthetic fixtures.
11. Keep BBIL real-candidate execution and current-result optimization
    unauthorized.
12. Require separate decisions for any SIG-002 attempt, Levels 5–9 work,
    higher layer, carrier, distribution, or transmission.

Same-provider architecture, hidden backend identity, hidden platform state,
unprovable Incognito isolation, prospective model selection, and the
single-trial sample remain limitations. DA-001 is post-hoc and same-tooling;
its diagnostic classifications and bounded causal register do not provide
external independent validation or prove the selected research target causal.

The framework and all Covenant text remain incomplete and challengeable unless
a recorded decision accurately establishes a later status.

## Post-Refactor Research Update — BBIL-001

[BBIL-001](beacon/BBIL-001/00-PUBLIC-LAB-CHARTER.md) prepares a draft
context-honest blind-iteration architecture and records one bounded
[synthetic capability probe](beacon/BBIL-001/08-SYNTHETIC-CAPABILITY-PROBE-RECORD.md).
It separates provider-exposed same-tooling
[adaptive development](beacon/BBIL-001/03-ADAPTIVE-DEVELOPMENT-AND-SEALED-VALIDATION-LANES.md)
from a fresh, nonadaptive sealed-validation lane and freezes ten distinct
[information-flow roles](beacon/BBIL-001/02-SUBAGENT-ROLES-AND-INFORMATION-FLOW.md).

The synthetic probe records
`PASS WITH LIMITATIONS — no detected leak; one or more isolation controls
unverified`. That label is orchestration evidence only: it is not a real
Beacon candidate, run, score, holdout, empirical result, clean-holdout claim,
provider-independent validation, or real-candidate authorization. The
[next-gate record](beacon/BBIL-001/09-NEXT-GATE-AND-NONEXECUTION.md) preserves
the historical pre-scoring gate sequence. Later D-035 closes PTR-001
incomplete, so that pair cannot proceed to comparison or mapping reveal. The
frozen [research manifest](beacon/BBIL-001/10-RESEARCH-MANIFEST.md) binds the seventeen
architecture, template, and portable-skill dependencies without changing the
historically preserved former README tail above.

## Post-Refactor Research Update — PTR-001 Scoring Closure

[D-035](DECISIONS.md) closes PTR-001 as
`Closed incomplete — scoring audit disagreement`. Two valid opaque outputs and
two validity freezes proceeded through two fresh primary scorers and two
separate scratch-before-comparison auditors. One non-FAIL audit with preserved
dissent permitted one score freeze; one `FAIL — condition score must not
freeze` prevented the second. Both audits preserve dissent, and no exact-pass
audit exists.

The FAIL is a scoring-measurement reproducibility failure, not a decoder-
validity failure or evidence for or against either opaque design condition.
The single frozen score has no paired interpretation. No comparison, mapping
reveal, unblinding, public score vector, public raw output, or SIG-002 attempt
exists.

Per-audit mapping provenance contains one explicit false assertion, zero
explicit true assertions, one absent assertion, and zero ambiguous assertions.
The completed scoring task’s coordinator-level no-mapping report remains
separate same-tooling process provenance, and no comparison, mapping-reveal,
or unblinding artifact exists. The mapping remains private and publicly
unrevealed.

The [public closure
record](beacon/paired-trials/SDR-003-PH-001-PT-001/09-PUBLIC-SCORING-INCOMPLETION-AND-CLOSURE-RECORD.md)
also preserves the prior nonpublic same-tooling D-035 preparation incident in
which one criterion-level score row entered an OpenAI Codex transcript. It
publishes neither that row nor a condition association. A future scoring-
disagreement diagnostic would require a separate accepted decision, may
classify disagreement mechanisms only, and cannot rescore, compare, reveal,
unblind, or revive PTR-001. Any improved scorecard and provenance instrument
must first be validated on synthetic fixtures.
