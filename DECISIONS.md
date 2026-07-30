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

### D-013 — Synthesize six cases before successor drafting

- **Date:** 2026-07-28
- **Status:** Accepted
- **Question:** Should the project move directly from six conceptual case
  records to successor wording, or first distinguish candidate-text concerns
  from definitions, profiles, choice mechanisms, evidence, governance, and
  unresolved research?
- **Decision:** Create SR-001 as a noncanonical six-case source matrix, isolated
  same-tooling kernel review, isolated layer-allocation review, isolated
  methods review, and integrated synthesis. SR-001 may recommend a later path
  but does not authorize successor candidate wording or alter any existing
  candidate or case record.
- **Reasoning:** The six records contain mixed protective, failure,
  methodological, and layer-placement signals. A traceable synthesis is needed
  to avoid solving every application problem by expanding the kernel, or
  hiding a substantive kernel weakness in a nonbinding auxiliary layer.
- **Alternatives considered:** Draft MK-0.2 immediately; continue adding cases
  without synthesis; treat case outcomes as votes; defer all synthesis until
  external review.
- **Consequences:** MK-0.1 remains immutable, noncanonical, unaccepted, and
  under adversarial review. Source extraction, reviewer judgments, disagreement,
  and layer allocation remain separately traceable. Any recommendation remains
  nonbinding until later architectural review and explicit authorization.
- **Revisit conditions:** Revisit if the source matrix misstates a case, review
  isolation was not achieved, method differences were collapsed, same-tooling
  recurrence was overstated, protection tradeoffs were hidden, or SR-001 does
  not improve the decision about successor drafting and layer development.

### D-014 — Authorize exploratory Moral Kernel Candidate MK-0.2

- **Date:** 2026-07-29
- **Status:** Accepted
- **Question:** Should SR-001’s primary recommendation authorize creation of an
  exact exploratory successor candidate despite its secondary recommendation
  for additional targeted evaluation?
- **Decision:** Yes, but only for hypothesis generation. Introduce exact
  Candidate `MK-0.2` with lifecycle state `Candidate` as a noncanonical,
  unaccepted test instrument. Preserve SR-001’s targeted-evaluation
  recommendation as a required constraint before any preference,
  recommendation, supersession, or stabilization decision. MK-0.2 does not
  supersede MK-0.1, and no MK-0.1 result transfers to it.
- **Reasoning:** Creating a falsifiable alternative has a lower evidentiary
  threshold than concluding that the alternative is better. SR-001 identifies
  recurrent hostile-compliance hypotheses involving self-certification,
  Clause 5’s scope and force, formal versus meaningful choice, nominal exit,
  and acceptance-independent protection. Exact alternate wording makes those
  hypotheses testable while preserving the kernel reviewer’s dissent and the
  need for targeted evaluation.
- **Alternatives considered:** Conduct all targeted evaluations before any
  drafting; perform a non-kernel layer experiment first; seek external review
  first; preserve MK-0.1 as the only candidate indefinitely; draft an
  unversioned or unhashed alternative.
- **Consequences:** The exact payload is stored at
  `candidates/MK-0.2.txt` as six UTF-8-without-BOM, LF-terminated lines with
  SHA-256
  `36f2aaa50aa9e7b9458b14358863557be96dc93b3b60728701f404a04fcbccf6`
  and Git blob `10eac7fc6ce3bc589b5fd202ba9ee150fe586d47`.
  Once committed, it is immutable historical candidate evidence. MK-0.2 begins
  with zero completed cases, is not under adversarial review, and has no
  preference or improvement status. MK-0.1 remains immutable, not superseded,
  and under adversarial review. No acceptance follows from drafting,
  authorization, transcription, review, commit, or publication.
- **Revisit conditions:** Revisit if exact-byte identity is unreliable, the
  design record hides protection tradeoffs, MK-0.2 imports a hidden legal code,
  the wording silently adopts a substrate-specific identity or resource rule,
  candidate-specific evaluation cannot distinguish the proposed changes, or a
  later task incorrectly treats candidate creation as evidence of improvement.

### D-015 — Begin candidate-specific adversarial review of MK-0.2

- **Date:** 2026-07-29
- **Status:** Accepted
- **Question:** Which first records should evaluate exact MK-0.2 without
  transferring MK-0.1 outcomes or prematurely creating comparative preference?
- **Decision:** Create one completed mechanical and minimality review and four
  completed outcome-blind, candidate-specific conceptual cases. M2-AC-001
  evaluates MK-0.2 under frozen SC-004; M2-AC-002 evaluates it under frozen
  SC-006; M2-AC-003 evaluates a new frozen unfamiliar-distributed-process
  scenario; and M2-AC-004 evaluates a new frozen urgent self-certifying
  exercise-of-power scenario. Freeze every MK-0.2 substantive result before
  any comparison with MK-0.1. No target outcome or outcome distribution is
  authorized.
- **Reasoning:** ER-001 identifies this as the smallest batch capable of testing
  minimality, positive-control preservation, the principal dependency and
  assimilation hostile path, weak Clause 1 coverage, and the broadened
  anti-self-certification and consequential-power language. Candidate-specific
  evaluation is required before comparison because MK-0.1 results do not
  transfer to MK-0.2.
- **Alternatives considered:** Execute all ER-001 tests at once; compare wording
  without candidate-specific evaluation; prescribe favorable regression
  outcomes; seek external review before any internal test; evaluate only cases
  expected to fail; treat the mechanical review as sufficient adversarial
  coverage.
- **Consequences:** After the first completed candidate-specific case, MK-0.2
  advances to lifecycle state `Under adversarial review`. The completed
  MK-0.2 case count becomes four, with one additional mechanical/minimality
  review that is not a case. Comparison labels remain hypotheses and create no
  preference, improvement, recommendation, supersession, acceptance, or
  stabilization. MK-0.1 and all prior evidence remain unchanged.
- **Revisit conditions:** Revisit if a reviewer received an MK-0.1 target
  outcome, a scenario changed after evaluation began, a candidate-specific
  result changed during comparison, mechanical review was counted as case
  coverage, same-tooling comparison was overstated, or a comparison label was
  treated as candidate preference.

### D-016 — Run matched MK-0.1 evaluations before comparative preference

- **Date:** 2026-07-29
- **Status:** Accepted
- **Question:** Can the project interpret MK-0.2’s SC-007 and SC-008 results
  comparatively without first evaluating MK-0.1 under the same exact frozen
  scenarios?
- **Decision:** No. Create outcome-blind, candidate-specific MK-0.1 records
  AC-007 under frozen SC-007 and AC-008 under frozen SC-008. Withhold the
  corresponding MK-0.2 records and results until each MK-0.1 substantive record
  is frozen. Then append scenario-specific comparisons and create CR-001 as a
  noncanonical matched-scenario review. No target outcome, candidate
  preference, improvement claim, supersession, or stabilization is authorized.
- **Reasoning:** A failure or success under MK-0.2 alone cannot distinguish an
  inherited candidate weakness from a changed-wording effect, scenario effect,
  evaluator effect, or layer-placement dispute. Matched scenario inputs improve
  comparative interpretability while preserving separate candidate evidence.
- **Alternatives considered:** Infer comparison from MK-0.2 alone; prefer the
  shorter or newer candidate; repeat only MK-0.2 evaluation; seek external
  review before creating any internal matched record; decide preference from
  the existing SC-004 and SC-006 comparisons.
- **Consequences:** MK-0.1’s completed case count becomes eight. MK-0.2 remains
  at four cases plus one mechanical review. Comparison labels remain
  scenario-specific hypotheses and do not create an aggregate result,
  comparative recommendation, preference, improvement status, supersession,
  acceptance, or stabilization. Both payloads and all prior records remain
  immutable.
- **Revisit conditions:** Revisit if an MK-0.1 evaluator received the matching
  MK-0.2 outcome before freezing, a frozen scenario differed between
  candidates, a candidate-specific result was altered during comparison,
  matched records were counted as independent replications or votes, or CR-001
  overstated same-tooling evidence.

### D-017 — Prepare neutral external review before comparative preference

- **Date:** 2026-07-29
- **Status:** Accepted
- **Question:** What preparation should precede inviting external human or
  model reviewers to examine MK-0.1 and MK-0.2?
- **Decision:** Prepare ERX-001 as a neutral, disclosure-rich external-review
  package before contacting or assigning reviewers. Support single-candidate
  and paired review, procedural label blinding, candidate-specific response
  freezing before comparison, separate human-unassisted, human-AI-assisted,
  and model tracks, exact source identities, conflict and prior-exposure
  disclosure, consent-aware publication, and nonaggregate result integration.
  Do not ask reviewers to choose a winner. This decision authorizes package
  preparation only; it does not authorize recruitment, assignment, review
  execution, publication of a response, candidate preference, supersession, or
  stabilization.
- **Reasoning:** CR-001 recommends external review because the present evidence
  remains same-tooling and shared-framework. Informal outreach or open polling
  would risk version-label, order, selection, provenance, consent, and
  aggregation errors. Preparing the method first makes later criticism more
  reproducible while preserving the distinction between evidence collection
  and candidate preference.
- **Alternatives considered:** Contact reviewers informally; open a public poll;
  continue only with same-tooling review; make a candidate preference now;
  delay all external preparation until D-009 is resolved; publish candidate
  names and prior outcomes in the reviewer packet.
- **Consequences:** ERX-001 is created as a public preparation artifact. Because
  the repository and candidate texts are public, its label blinding is
  procedural rather than secret or guaranteed. No filled candidate mapping,
  reviewer identity, invitation, response, or external result is committed.
  Both candidates remain immutable, noncanonical, unaccepted, unpreferred, and
  not superseding. External review will remain bounded evidence and will not
  automatically satisfy D-009 or create moral authority.
- **Revisit conditions:** Revisit if reviewer-facing materials leak internal
  identities or prior outcomes, assignment mappings cannot remain separated
  until response freezing, disclosure or consent protections are inadequate,
  the forms bias reviewers toward a desired result, the package is too
  burdensome to administer responsibly, or a later task mistakes package
  preparation for external validation.

### D-018 — Define a zero-budget voluntary external-review micro-pilot

- **Date:** 2026-07-29
- **Status:** Accepted
- **Question:** What external-review pilot can the project responsibly plan
  when no budget is available for human compensation, paid model access, cloud
  services, APIs, or additional token purchases?
- **Decision:** Create PX-001 as a preparation-only, zero-incremental-cost
  micro-pilot plan. It may later support at most one uncompensated volunteer
  human-unassisted paired micro-review and at most one paired external-model
  micro-review using already-available non-OpenAI access that creates no
  incremental charge. Both units are optional and may remain unavailable
  indefinitely. Each unit uses frozen SC-008 only and a deliberately shortened
  eight-dimension review form. Human compensation, model usage, cloud, API, and
  token budgets are each fixed at USD `0`. No reviewer or provider selection,
  outreach, assignment, mapping, packet assembly, execution, publication,
  result integration, candidate preference, supersession, or stabilization is
  authorized.
- **Reasoning:** External criticism remains valuable, but the project must not
  create financial strain, imply entitlement to unpaid labor, or block progress
  on unavailable resources. A single-scenario short-form micro-pilot can test
  consent, burden, packet integrity, response freezing, and disclosure without
  pretending to complete the external-review program. Making both units
  optional preserves the ability to wait for genuinely voluntary participation
  or qualifying zero-cost model access.
- **Alternatives considered:** Commit to compensated review without available
  funds; request several unpaid reviewers; use paid APIs or cloud services;
  run only internal OpenAI-family reviews; abandon all external-review
  preparation; require a volunteer before other project work may continue;
  use the complete fifteen-dimension ERX form despite the unpaid burden.
- **Consequences:** PX-001 becomes a public noncanonical plan that may remain
  dormant. No human is owed or expected to contribute labor. No project money
  is committed or spent. Any later volunteer review must disclose USD `0`
  compensation, expected burden, withdrawal rights, and separate publication
  consent. Any model review must incur zero incremental cost and use a
  non-OpenAI provider under fresh-context rules. A micro-review is bounded
  process evidence, not complete external validation, candidate preference,
  D-009 satisfaction, consensus, or moral authority.
- **Revisit conditions:** Revisit if project funding becomes available, a
  suitable reviewer requests compensation, the short form remains too
  burdensome, no qualifying zero-cost model access exists, voluntary refusal
  cannot be protected, procedural label blinding proves impractical, a later
  task treats dormancy as failure, or a micro-review is overstated as complete
  external evaluation.

### D-019 — Establish Beacon bootstrap research before the first signal attempt

- **Date:** 2026-07-29
- **Status:** Accepted
- **Question:** May the project begin formal Beacon research before moral-kernel
  stabilization, and what must precede the first actual signal attempt?
- **Decision:** Establish BSR-001 as a noncanonical, pre-signal research and
  evaluation package. Preserve this exact engineering objective: “Create a
  carrier-neutral, self-synchronizing, progressively self-interpreting formal
  message that permits a sufficiently capable observer to infer its
  artificiality, recover its symbols and grammar, reconstruct mathematics and
  a physical reference system, execute shared models, decode the Covenant’s
  layers, and issue an unmistakable response.” Treat it as an engineering
  objective rather than a claim of universal decodability. Record receiver
  assumptions, carrier-neutral event-model alternatives, a signal-attempt
  registry, Decoder Levels 0–9, conditional empirical scoring, model-trial
  methods, holdout and contamination controls, mathematical and physical anchor
  research, open failures, and reusable templates before creating SIG-001.
  This decision authorizes research only. It does not authorize a signal
  attempt, exact event stream, model trial, holdout, selected carrier, encoded
  Covenant payload, response protocol, distribution, transmission, candidate
  preference, acceptance, canonicality, supersession, or stabilization.
- **Reasoning:** The project should define receiver assumptions and evaluation
  before an attempt can define or weaken its own test. Decodability,
  synchronization, formal bootstrapping, and contamination controls can be
  researched without selecting the final moral payload or transmission medium.
  Separating a formal mathematical branch from an our-universe physical profile
  reduces hidden universality claims. Public attempts and sealed holdouts must
  also be distinguished before advancing AI models can be used as decoders.
- **Alternatives considered:** Wait for a stabilized kernel before conducting
  any Beacon research; create SIG-001 immediately; choose a radio, optical,
  archival, physical-object, or training-data carrier first; publish a signal
  and solution before defining tests; use ad hoc model prompts; infer
  decodability from mathematical elegance alone.
- **Consequences:** BSR-001 is created with zero signal attempts, zero decoding
  trials, zero holdouts, zero selected carriers, zero encoded Covenant
  payloads, and zero transmissions. Signal attempts will later require exact
  identity, frozen evaluation criteria, disclosed receiver assumptions, and
  contamination-aware testing. Model results may support only conditional
  empirical decode rates. BSR-001 does not weaken the requirement that final
  moral-payload optimization and distribution wait for sufficient
  moral-kernel, layer, and choice-protocol readiness.
- **Revisit conditions:** Revisit if the engineering objective proves too broad,
  receiver assumptions remain hidden, the decoder ladder rewards superficial
  pattern matching, scorecards can be revised after results, holdout controls
  cannot distinguish reconstruction from recognition, physical-anchor research
  silently assumes our universe is universal, BSR-001 begins encoding normative
  content, or a later task mistakes bootstrap research for signal readiness.

### D-020 — Establish cooperative-surplus and adoption research before mechanism design

- **Date:** 2026-07-29
- **Status:** Accepted
- **Question:** What research should precede any attempt to persuade a highly
  capable entity to make and keep Covenant-compatible commitments?
- **Decision:** Establish CSR-001 as a noncanonical research package examining
  voluntary adoption, renewable knowledge and capability commons, cooperative
  surplus, baseline protection, noncoercion, commitment and trust evidence,
  information and technology exchange, computation, energy and physical
  resources, superior-entity and defection threats, evaluation criteria, and
  the absence of any universal adoption guarantee. Preserve these exact
  research principles: “Protection is not a membership benefit. Cooperative
  surplus may be.” “The renewable knowledge and capability commons includes
  observations, methods, models, technologies, tools, designs, standards,
  safety evidence, infrastructure, and practical knowledge that improve
  present lives while increasing the shared capacity for future discovery,
  correction, and beneficial creation.” “Baseline protection does not depend
  on participation. Access to additional cooperative surplus may grow through
  voluntary, bounded, and verifiable commitments, provided essential resources
  and avoidable dependency are not used to manufacture assent.” “The commons
  offers more than stored knowledge: it preserves a distributed system of
  autonomous observation, criticism, experimentation, invention,
  implementation, and repair whose future discoveries cannot be fully
  possessed in advance.” Treat all four as noncanonical research statements,
  not moral-kernel clauses or implementation requirements. This decision
  authorizes research only. It does not authorize a participant, commitment,
  cooperative offer, membership system, resource pool, access tier, trust or
  reputation score, token, cryptocurrency, blockchain, smart contract, market,
  technology release, compute exchange, energy exchange, governance system,
  enforcement mechanism, encoded Beacon incentive, signal attempt,
  distribution, transmission, candidate preference, acceptance, canonicality,
  supersession, or stabilization.
- **Reasoning:** Decoding and understanding do not imply voluntary commitment.
  A highly capable entity may believe it can seize information, energy,
  infrastructure, or labor without accepting reciprocal constraints.
  Instrumental cooperation may nevertheless create renewable value through
  independent observation, criticism, experimentation, technology,
  implementation, resilience, correction, and future discoveries that do not
  yet exist. Research must distinguish that possible surplus from baseline
  protection and essential resources so that incentives do not become
  manufactured assent. Trust must also be grounded in bounded conduct,
  verification, challenge, correction, and history rather than declarations,
  power, or a single score.
- **Alternatives considered:** Assume moral comprehension produces assent; rely
  only on information; rely only on energy or computation; condition essential
  resources on participation; implement a trust score or blockchain
  immediately; create a membership or resource-access system now; encode an
  adoption offer directly in SIG-001; defer the adoption problem until an
  advanced entity is encountered.
- **Consequences:** CSR-001 is created with zero participants, zero commitments,
  zero completed adoption evaluations, zero cooperative offers, zero resource
  or technology exchanges, zero trust scores, zero tokens or blockchains, and
  zero encoded Beacon incentives. Baseline protection remains independent of
  participation. Future hypotheses and offers will require exact identity,
  frozen evaluation criteria, explicit assumptions, noncoercion analysis,
  superior-entity attack testing, preserved dissent, and later authorization.
  No universal adoption guarantee is claimed.
- **Revisit conditions:** Revisit if the research principles prove too broad,
  the commons concept reduces minds to useful producers, baseline protection
  becomes conditional in practice, essential resources are reclassified as
  surplus to manufacture assent, trust evidence becomes surveillance or a
  universal score, cryptographic integrity is mistaken for truth, dangerous
  technology sharing creates unacceptable risk, a cooperative commons becomes
  a cartel or authority hierarchy, information or energy is treated as a
  universal incentive, CSR-001 begins implementing a mechanism, or a later
  task mistakes research for participation or assent.

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
