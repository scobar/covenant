# Project Decision Log

## Decision Template

- **Identifier:**
- **Date:**
- **Status:**
- **Question:**
- **Decision:**
- **Reasoning:**
- **Alternatives considered:**
- **Consequences:**
- **Revisit conditions:**

## Accepted Decisions

### D-001 — Public founding repository

- **Date:** 2026-07-28
- **Status:** Accepted
- **Question:** Not yet recorded.
- **Decision:** The founding repository is public and located at
  `scobar/covenant`. Public visibility supports scrutiny, provenance,
  criticism, and discoverability. Public visibility does not make every draft
  canonical.
- **Reasoning:** Not yet recorded.
- **Alternatives considered:** Not yet recorded.
- **Consequences:** Not yet recorded.
- **Revisit conditions:** Not yet recorded.

### D-002 — Moral kernel before signal optimization

- **Date:** 2026-07-28
- **Status:** Accepted
- **Question:** Not yet recorded.
- **Decision:** The project will stabilize and adversarially test the moral
  kernel before optimizing the Beacon or other signals that carry it.
- **Reasoning:** Not yet recorded.
- **Alternatives considered:** Not yet recorded.
- **Consequences:** Not yet recorded.
- **Revisit conditions:** Not yet recorded.

### D-003 — Layer separation

- **Date:** 2026-07-28
- **Status:** Accepted
- **Question:** Not yet recorded.
- **Decision:** The project will distinguish the moral kernel from definitions,
  commentary, profiles, choice mechanisms, Beacon implementation, evidence
  systems, and governance.
- **Reasoning:** Not yet recorded.
- **Alternatives considered:** Not yet recorded.
- **Consequences:** Not yet recorded.
- **Revisit conditions:** Not yet recorded.

### D-004 — Verbatim founding evidence

- **Date:** 2026-07-28
- **Status:** Accepted
- **Question:** Not yet recorded.
- **Decision:** Initial founder statements will be preserved verbatim. Later
  commentary may criticize or refine them but must not be presented as though
  it were the original statement.
- **Reasoning:** Not yet recorded.
- **Alternatives considered:** Not yet recorded.
- **Consequences:** Not yet recorded.
- **Revisit conditions:** Not yet recorded.

### D-005 — Human-controlled Git publication workflow

- **Date:** 2026-07-28
- **Status:** Accepted
- **Question:** Not yet recorded.
- **Decision:** Codex may make explicitly authorized local edits. The repository
  owner manually reviews, commits, and pushes changes unless a later task
  explicitly changes this workflow.
- **Reasoning:** Not yet recorded.
- **Alternatives considered:** Not yet recorded.
- **Consequences:** Not yet recorded.
- **Revisit conditions:** Not yet recorded.

### D-006 — Evaluation framework before candidate text

- **Date:** 2026-07-28
- **Status:** Accepted
- **Question:** Should the project draft its first moral-kernel candidate
  before recording how candidates will be evaluated?
- **Decision:** No. The project will record a provisional, challengeable
  evaluation framework before introducing candidate moral-kernel clauses.
- **Reasoning:** A candidate should not define or retroactively weaken its own
  test. Recording criteria first exposes prior assumptions and keeps the
  evaluation method distinguishable from the candidate.
- **Alternatives considered:** Draft the candidate first and derive tests from
  it; develop candidate and criteria simultaneously.
- **Consequences:** No candidate clauses are authorized by this decision. The
  evaluation framework remains noncanonical and subject to revision.
- **Revisit conditions:** Revisit if useful pre-draft evaluation proves
  impossible, but do not allow later candidate text to self-certify
  retroactively.

### D-007 — Categorical evaluation without an aggregate score

- **Date:** 2026-07-28
- **Status:** Accepted
- **Question:** Should evaluation outcomes be combined into a single numeric
  score?
- **Decision:** Use categorical, per-dimension outcomes and do not
  calculate an aggregate score. A severe protective or interpretive failure
  must not be averaged away by strengths elsewhere.
- **Reasoning:** A single score would imply unsupported precision and make
  morally distinct failures appear interchangeable.
- **Alternatives considered:** Weighted scoring; unweighted scoring; evaluator
  rankings.
- **Consequences:** Comparisons will be more explicit but less compressible.
- **Revisit conditions:** Revisit if quantitative evidence becomes useful, but
  never use aggregation to hide a recorded severe failure.
- **Decision history:** Proposed in commit
  `9da6bbbb6bfc7d962e315794e0285f37be3868d5`; accepted without substantive
  change on 2026-07-28 after architectural review.

### D-008 — Diagnose rejection before revising for acceptance

- **Date:** 2026-07-28
- **Status:** Accepted
- **Question:** Should any rejection of a candidate count as evidence that its
  restrictions should be weakened?
- **Decision:** No. Distinguish semantic, substrate, feasibility,
  protective, exploitability, goal-conflict, and evidence failures before
  revising a candidate. Do not remove meaningful protection solely to increase
  likely acceptance.
- **Reasoning:** An unintelligible restriction and an understood restriction
  rejected by a predatory objective are materially different.
- **Alternatives considered:** Optimize for broadest assent; treat all
  rejections as equivalent; ignore all rejecting perspectives.
- **Consequences:** Some informed minds may reject the Covenant without that
  rejection invalidating the protected principle.
- **Revisit conditions:** Revisit when rejection evidence identifies hidden
  domination, incoherence, inapplicability, or preventable ambiguity.
- **Decision history:** Proposed in commit
  `9da6bbbb6bfc7d962e315794e0285f37be3868d5`; accepted without substantive
  change on 2026-07-28 after architectural review.

### D-010 — Introduce Moral Kernel Candidate MK-0.1

- **Date:** 2026-07-28
- **Status:** Accepted
- **Question:** Has the project recorded enough pre-candidate process to
  introduce an exact first candidate for adversarial evaluation?
- **Decision:** Yes. Introduce `MK-0.1` as an exact, hashed candidate with
  lifecycle state `Candidate`. It is noncanonical, not accepted, not
  provisionally stabilized, and authorized only for evaluation and revision.
- **Reasoning:** The evaluation framework exists, and further progress requires
  falsifiable exact text rather than continued abstract agreement.
- **Alternatives considered:** Continue pre-candidate design indefinitely;
  draft text without stable bytes or a hash; treat the first draft as a
  provisional Covenant.
- **Consequences:** The exact payload is stored at
  `candidates/MK-0.1.txt` as UTF-8 without BOM, LF line endings, and a final
  LF, with SHA-256
  `97e851f392e051f10105475479f0b17b09701bdf170d6efcd697827197efd90c`.
  Once committed, it must never be edited in place; any textual change creates
  a new candidate version. No contribution, authorship, authorization,
  transcription, review, or commit implies acceptance.
- **Revisit conditions:** Revisit the representation or attribution mechanism
  if it prevents reliable comparison or correction, but preserve the committed
  candidate and its provenance.

### D-011 — Begin MK-0.1 adversarial review with a diverse first batch

- **Date:** 2026-07-28
- **Status:** Accepted
- **Question:** Which first evaluations should move MK-0.1 from lifecycle state
  `Candidate` to `Under adversarial review`?
- **Decision:** Create three completed, noncanonical conceptual evaluation
  records: AC-001 tests uncertain moral status and avoidable destruction;
  AC-002 tests autonomy restriction under contested catastrophic risk; and
  AC-003 tests coercion, assimilation, protection, and exit under extreme
  dependency. The batch intentionally samples distinct failure modes and
  outcomes. It does not satisfy D-009 or establish a candidate-wide result.
- **Reasoning:** The project needs exact applications that can expose different
  kinds of failure before seeking broad perspective coverage or drafting a
  successor candidate. A mixed first batch is more informative than selecting
  only cases likely to praise or reject MK-0.1.
- **Alternatives considered:** Attempt all perspective categories at once;
  perform only abstract clause commentary; draft MK-0.2 before any completed
  case; select only cases expected to fail.
- **Consequences:** MK-0.1 moves to lifecycle state `Under adversarial review`.
  Its payload remains immutable. Case-specific outcomes and dissent remain
  traceable. No acceptance, aggregate judgment, completion of D-009, or
  provisional stabilization follows.
- **Revisit conditions:** Revisit the batch design if the cases are materially
  redundant, omit important interpretations, confuse hypothetical assumptions
  with evidence, or fail to improve the next evaluation or revision decision.

### D-012 — Run outcome-blind countertests before drafting a successor

- **Date:** 2026-07-28
- **Status:** Accepted
- **Question:** Should the project draft MK-0.2 immediately from the
  architect-specified first batch, or first conduct countertests whose outcomes
  are not prescribed?
- **Decision:** Conduct three additional noncanonical conceptual evaluations
  before authorizing successor text. AC-004 tests a less-coercive
  near-neighbor integration arrangement; AC-005 tests costly refusal under
  stipulated genuine scarcity; and AC-006 performs a scenario-equivalent
  reanalysis of AC-003 without supplying its prior outcome to the evaluator.
  Scenario inputs and questions are specified in advance, but interpretations,
  dimension outcomes, overall outcomes, diagnoses, confidence, recommendations,
  and layer placement are not.
- **Reasoning:** The first batch established useful hypotheses but prescribed
  its outcomes. Countertests can distinguish some candidate-text failures from
  scenario assumptions, unresolved terminology, and missing profile or
  governance layers before the project creates a successor candidate.
- **Alternatives considered:** Draft MK-0.2 immediately; repeat only cases
  expected to fail; treat the first batch as independent confirmation; defer
  all further work until external reviewers participate.
- **Consequences:** MK-0.1 remains immutable and under adversarial review. The
  second batch may produce any allowed outcome pattern. Same-tooling
  outcome-blind evaluation improves method separation but does not provide
  independent evaluator diversity, empirical evidence, consensus, or
  provisional stabilization. No successor candidate is authorized.
- **Revisit conditions:** Revisit the method if evaluators received target
  outcomes, prior conclusions contaminated AC-006, scenario inputs were changed
  after outcome derivation, or the records do not improve the decision between
  candidate revision and additional layer development.

## Open Decisions

### D-009 — Minimum adversarial coverage before provisional stabilization

- **Date:** 2026-07-28
- **Status:** Proposed
- **Question:** What minimum adversarial coverage should a candidate receive
  before it may be called provisionally stabilized?
- **Proposed decision:** Require at least one documented case from every
  perspective category currently listed in the adversarial casebook and at
  least one strongest-hostile reading of every candidate clause.
- **Reasoning:** A thin kernel intended for unfamiliar minds should not advance
  after testing only familiar human cases.
- **Alternatives considered:** No fixed minimum; selected high-risk cases only;
  evaluator vote.
- **Consequences:** Stabilization will require substantial documented review
  and may remain slow.
- **Revisit conditions:** Revisit as case categories improve or if coverage
  quantity is shown not to provide meaningful diversity.
- **Architectural review note (2026-07-28):** The current quantity-based
  proposal may be necessary but is not sufficient. Before acceptance it must
  address case completeness and material distinctness, strongest-hostile
  readings for every clause and materially relevant clause interaction, and
  whether unresolved Protective Insufficiency or Hostile Exploitability is a
  noncompensable blocker. Minimum evaluator diversity also remains unresolved.
  This note does not accept or supersede D-009.
