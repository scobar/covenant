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

### D-021 — Create SIG-001 as a frozen lower-level mathematical bootstrap attempt

- **Date:** 2026-07-29
- **Status:** Accepted
- **Question:** Is the project ready to create a first exact signal attempt
  without encoding a moral payload, cooperative incentive, physical profile,
  response protocol, carrier, or transmission plan?
- **Decision:** Yes, within a narrowly bounded experiment. Create SIG-001
  version 0.1 as a public, noncanonical, two-event-class, totally ordered
  formal sequence targeting Decoder Levels 0 through 4 only: artificiality,
  framing, numeracy, mathematics, and grammar/logic. Freeze its receiver
  assumptions, event model, formal-language specification, pretrial scorecard,
  trial-validity and contamination policy, solution key, and pre-stream freeze
  record before generating the event stream. The exact event stream must have
  SHA-256
  `b4e6a8b7a00b18e12e4816c44975ea0921cf4330504c744a72b8abf9dbf2b144`
  and Git blob `4884d0466c52c25a148a7b59239fa1539f27bdd2`.
  Register the successful attempt with lifecycle state `Frozen`. This decision
  does not authorize a decoding trial, model selection, holdout, physical
  reference, Covenant or CSR payload, response syntax, carrier, distribution,
  transmission, candidate preference, acceptance, canonicality, supersession,
  or stabilization.
- **Reasoning:** BSR-001 established that evaluation criteria and contamination
  controls must precede an attempt. A limited Levels 0–4 artifact can test
  artificiality, framing, quantity, arithmetic, and formal syntax without
  prematurely encoding unsettled moral, adoption, physical, or response
  content. Freezing the scorecard before the event stream prevents the attempt
  from weakening its own tests after construction. Preserving the first
  attempt even if it fails creates a concrete baseline for later signal
  versions and holdout variants.
- **Alternatives considered:** Evaluate an adoption hypothesis first; continue
  research without creating an artifact; include physical constants now;
  include a Covenant candidate now; include CSR incentives now; create and test
  the signal in one task; choose a transmission carrier first; permit the
  signal designer to score an unfrozen test after seeing results.
- **Consequences:** SIG-001 becomes immutable historical signal evidence after
  commit. It remains public and therefore vulnerable to recognition,
  retrieval, and future training contamination. Scott, ChatGPT, Codex, and
  design-exposed contexts cannot serve as blind decoders. No empirical result
  exists, and no success at lower decoder levels would establish recoverability
  of physical, agency, moral, Covenant, or response layers. The live signal
  registry records one Frozen attempt and zero trials, holdouts, carriers,
  encoded payloads, responses, or transmissions.
- **Revisit conditions:** Revisit if the pre-stream chronology cannot be
  verified, the exact event stream fails its declared identity, the scorecard
  is ambiguous or rewards surface recognition, the public solution makes
  useful testing impossible without a holdout, the two-event total-order model
  proves too anthropocentric, the prefix grammar is underdetermined, a later
  task treats Frozen as decoded or validated, or SIG-001 is used to justify
  payload integration, distribution, or transmission without later
  authorization.

### D-022 — Create a sealed surface-novel SIG-001 holdout before decoder testing

- **Date:** 2026-07-29
- **Status:** Accepted
- **Question:** Should the project create a privately sealed variant of SIG-001
  before selecting or running a decoder?
- **Decision:** Yes. Create SIG-001-HO-001 version 0.1 as a surface-novel,
  semantically equivalent holdout derived from frozen SIG-001 and targeting
  Decoder Levels 0 through 4 only. Freeze its private transformation record,
  scorecard, trial-validity policy, neutral instruction, solution key, and
  pre-stream chronology before generating its event stream. Store all private
  material outside every Git repository. Publish only a SHA-256 commitment and
  nonrevealing protocol metadata. Preserve SIG-001 unchanged. Register the
  holdout with lifecycle `Sealed and committed`. This decision authorizes no
  decoder selection, model execution, output, score, reveal, Covenant or CSR
  payload, physical profile, response syntax, carrier, distribution,
  transmission, candidate preference, acceptance, canonicality, supersession,
  or stabilization.
- **Reasoning:** SIG-001’s public stream and solution are useful for
  transparency but vulnerable to recognition, retrieval, and future training
  contamination. A committed surface-novel variant can later provide stronger
  evidence of reconstruction, provided its formal equivalence and scorecard
  are frozen before generation, its private materials remain sealed, and
  decoder output and scoring freeze before reveal. Separating holdout creation
  from trial execution prevents the chosen decoder or result from influencing
  the variant.
- **Alternatives considered:** Test public SIG-001 immediately; create and run
  a holdout in one task; publish the holdout stream before trial; keep no
  public commitment; create a new signal attempt rather than a semantic
  variant; add physical, moral, Covenant, CSR, or response content now; defer
  all testing indefinitely.
- **Consequences:** The live Beacon records one frozen public attempt and one
  sealed unrevealed holdout, with zero trials, outputs, scores, reveals,
  carriers, encoded payloads, responses, distributions, or transmissions.
  Scott becomes custodian of a private off-repository package. ChatGPT, the
  current Codex thread, and all private audit contexts are protocol- or
  design-exposed and may not later be represented as blind decoders. The
  public commitment can detect substitution after reveal but does not prove
  equivalence, fair randomization, decoder ignorance, or decodability.
- **Revisit conditions:** Revisit if the private package is lost, copied into
  Git, disclosed before output freeze, lacks a verifiable chronology, fails
  semantic-equivalence reconstruction, leaks solution clues through the trial
  instruction, cannot be backed up safely, produces an unverifiable
  commitment, or a later task treats the commitment as a decoding result.

### D-023 — Prepare and authorize one zero-cost Claude Fable 5 sealed-holdout trial

- **Date:** 2026-07-30
- **Status:** Accepted
- **Question:** Which exact decoder configuration and execution protocol may be
  used for the first contamination-reduced trial of SIG-001-HO-001?
- **Decision:** Prepare and authorize SIG-001-HO-001-TR-001 version 0.1 as one
  zero-incremental-cost external-model sealed-holdout decoding trial. Use
  Anthropic through ordinary `claude.ai` standard Chat with the exact displayed
  model label `Fable 5`, in a newly created Claude Incognito Chat outside every
  Project, with web search, connectors, Claude Code, Cowork, browser control,
  memory-bearing prior conversation, and unrelated tools disabled or absent.
  Use only promotional Fable 5 credit already available to Scott’s paid Claude
  account; auto-reload remains off, paid spillover remains disabled, and the
  authorized incremental spend is USD 0. Freeze a private packet containing
  only the exact neutral instruction and sealed holdout sequence, publish only
  a cryptographic packet commitment, request one valid run, and permit at most
  one retry solely for technical invalidity. The public preparation package
  must be reviewed and committed before execution. Private custody-integrity
  verification is required during preparation and immediately before
  execution: the authorized custodian privately recomputes sealed-file,
  manifest, preimage, and commitment relationships without revealing private
  contents publicly or exposing the mapping, solution, scorecard, preimage, or
  private identities to the decoder or pre-output-freeze scoring context.
  That check is not reveal-stage verification and creates no decoding result.
  The future output freezes before validity review or scoring; the complete
  score freezes before the holdout mapping, solution, private scorecard
  answers, private manifests, or commitment preimages are revealed.
  Reveal-stage commitment verification occurs only after that authorized
  reveal, preserves every mismatch or failed verification, requires separate
  authorization for public recording, and cannot retroactively change the
  frozen output or score. This decision authorizes one later manual execution
  after every gate is reconfirmed. It does not authorize execution during the
  preparation task, a second substantive run, model substitution, paid usage,
  output scoring during the decoder conversation, reveal, publication,
  empirical-rate interpretation, Covenant or CSR payload, physical profile,
  response syntax, carrier, distribution, transmission, candidate preference,
  acceptance, canonicality, supersession, or stabilization.
- **Reasoning:** A sealed surface-novel holdout can provide stronger evidence
  of reconstruction than the public SIG-001 stream only if the decoder
  configuration, exact input packet, run count, retry rules, tool state,
  output-preservation method, and reveal chronology are fixed before execution.
  Ordinary Claude web Chat provides a cleaner local-filesystem boundary than
  Claude Code, while Claude Incognito Chat reduces—but does not prove the
  absence of—memory and training exposure. Promotional credits permit this
  single trial without incremental project spending. Naming the displayed
  model label and browser interface honestly preserves what is observable
  without claiming an unavailable backend identifier.
- **Alternatives considered:** Use Claude Code; use an existing conversation;
  test public SIG-001 first; select Sonnet 5; select an API model; permit web or
  connectors; ask follow-up questions; permit multiple samples or best-of-N;
  allow paid spillover; score before preserving output; reveal before score
  freeze; defer every decoder trial indefinitely.
- **Consequences:** The live Beacon records one prepared and authorized trial
  configuration, zero executions, zero outputs, zero scores, and zero reveals.
  Scott becomes the manual operator but gains no interpretive authority.
  ChatGPT and the current Codex thread remain design-exposed and cannot be the
  blind decoder. The browser interface does not expose temperature, seed,
  hidden system prompt, backend routing, or an immutable model identifier;
  those limitations remain part of the evidence record. A substantive refusal,
  failed decode, partial decode, or unexpected interpretation is preserved as
  the single valid result rather than rerun. No universal probability or
  higher-layer conclusion follows.
- **Revisit conditions:** Revisit if Fable 5 is no longer selectable, the
  displayed label changes, promotional credit is unavailable, payment or
  spillover becomes possible, Incognito Chat or tool isolation cannot be
  confirmed, browser-control or connectors cannot be disabled, the input
  packet or a private custody-integrity verification fails, the private
  package or backup is unavailable, the output cannot be preserved completely,
  an unauthorized context sees the holdout, reveal-stage commitment
  verification later fails, a technical retry would exceed the authorized
  limit, or a later task treats preparation as execution or one result as
  universal evidence.

### D-024 — Close the technically invalid Fable trial and create a fresh sealed holdout before another Anthropic model trial

- **Date:** 2026-07-30
- **Status:** Accepted
- **Question:** How should the project respond after Fable 5 processed the
  sealed HO-001 packet but a provider safeguard interrupted the run before a
  completed final response?
- **Decision:** Classify SIG-001-HO-001-TR-001 Run 1 as
  `Invalid — technical`, preserve its private provider-visible partial trace
  without scoring or publication, retire the unused D-023 technical retry, and
  close TR-001 as incomplete with zero valid decoder outputs, scores, or
  reveals. Preserve SIG-001-HO-001 unchanged but classify it as
  `Known Anthropic provider-side exposure`, because its exact sequence reached
  Anthropic’s systems and received substantive processing before interruption.
  Create SIG-001-HO-002 version 0.1 as a new surface-novel, semantically
  equivalent Levels 0–4 holdout derived mechanically from frozen SIG-001.
  Freeze its private transformation, scorecard, validity policy, neutral
  instruction, solution, and chronology before generating its stream; store it
  outside Git; and publish only a cryptographic commitment and nonrevealing
  metadata. Sonnet 5 with High effort was prospectively qualified before
  HO-002 generation, so the package must disclose that it is not
  model-selection-blind in chronology. The generator must use fixed generic
  transformation families, fresh cryptographic randomness, and no Fable trace
  content or model-specific tuning. This decision authorizes TR-001 closure and
  HO-002 creation only. It does not authorize a Sonnet trial package, model
  execution, output, scoring, reveal, empirical-rate interpretation, another
  retry, model substitution, Covenant or CSR payload, physical profile,
  response syntax, carrier, distribution, transmission, candidate preference,
  acceptance, canonicality, supersession, or stabilization.
- **Reasoning:** Continuing with Sonnet inside the Fable conversation would
  violate the frozen model and fresh-context boundaries. Reusing HO-001 in
  another Anthropic model would also provide weaker contamination control
  because the exact sequence has already reached the provider. A mechanically
  generated fresh variant preserves the formal experiment while reducing
  exact-instance carryover. Retiring the unused Fable retry avoids spending
  another run merely to confirm a likely repeated safeguard, while preserving
  the first invalid run and all private incident evidence.
- **Alternatives considered:** Exercise the Fable retry; click the provider’s
  Sonnet continuation option; use HO-001 in a fresh Sonnet chat; classify the
  partial trace as a decoder result; alter the prompt to avoid safeguards;
  create a new signal-attempt lineage; reveal HO-001; abandon decoder testing;
  prepare and execute Sonnet in the same task.
- **Consequences:** TR-001 becomes a closed incomplete historical record with
  one technical-invalidity run and no valid output. HO-001 remains sealed and
  unrevealed publicly but carries a known Anthropic-exposure classification.
  HO-002 becomes a second sealed holdout with zero trial preparations or
  executions. The prospective Sonnet configuration was known before HO-002
  generation, which remains a methodological limitation even though the
  transformation is mechanically randomized. Another accepted decision is
  required before preparing or executing a Sonnet trial.
- **Revisit conditions:** Revisit if the Fable evidence record is incomplete,
  the provider interruption actually produced a completed final response,
  screenshot evidence or private records are lost, HO-001 exposure is
  misclassified, HO-002 formal equivalence or novelty fails, the generator
  consults the partial trace, private values leak publicly, HO-002 cannot be
  backed up, or a later task treats closure, commitment, or prospective model
  qualification as a decoder result.

### D-025 — Prepare and authorize one zero-incremental-cost Sonnet 5 / High sealed-holdout trial

- **Date:** 2026-07-30
- **Status:** Accepted
- **Question:** Which exact decoder configuration and execution protocol may be
  used for the first trial of the never-supplied SIG-001-HO-002 holdout?
- **Decision:** Prepare and authorize SIG-001-HO-002-TR-002 version 0.1 as one
  zero-incremental-cost external-model sealed-holdout decoding trial. Use
  Anthropic through ordinary `claude.ai` standard Chat with displayed model
  label `Sonnet 5` and displayed effort level `High`, in another newly created
  Claude Incognito Chat outside every Project, with web search, connectors,
  Claude Code, Cowork, browser control, memory-bearing prior conversation, and
  unrelated tools disabled or absent. Use only Scott’s existing paid
  `claude.ai` account; auto-reload remains off, paid spillover remains
  disabled, and authorized incremental project spending is USD 0. Freeze a
  private packet containing only the exact HO-002 neutral instruction and
  sealed sequence, publish only a cryptographic packet commitment, request one
  valid run, and permit at most one retry solely for technical invalidity.
  Preserve TR-001 as closed incomplete and do not use HO-001 or the private
  Fable trace. The public preparation package must be reviewed and committed,
  and the private TR-002 package must be backed up and custody-verified before
  execution. The future output and execution metadata freeze before validity
  classification or scoring; the complete score freezes before authorized
  reveal and reveal-stage commitment verification. This decision authorizes
  one later manual execution only after every gate is reconfirmed. It does not
  authorize execution during preparation, a second substantive run, model or
  effort substitution, paid usage, follow-up prompting, output scoring in the
  decoder conversation, reveal, publication, empirical-rate interpretation,
  Covenant or CSR payload, physical or agency profile, response syntax,
  carrier, distribution, transmission, candidate preference, acceptance,
  canonicality, supersession, or stabilization.
- **Reasoning:** HO-002 is a fresh surface-novel Levels 0–4 variant that has
  never been supplied to a decoder, making it a better exact-instance test
  than provider-exposed HO-001. Freezing the exact Sonnet 5 / High
  configuration, two-file packet, run count, retry rule, tool state,
  output-preservation method, and reveal chronology before execution reduces
  post-result adaptation. Standard Claude web Chat provides a cleaner
  local-filesystem boundary than Claude Code. The displayed model and effort
  labels honestly record what is observable without claiming an unavailable
  backend identifier. Sonnet 5 / High was known before HO-002 generation and
  both trials use Anthropic, so model-selection-blind chronology and
  same-provider independence are not claimed.
- **Alternatives considered:** Reuse HO-001; reopen or retry TR-001; continue
  inside the Fable conversation; use the qualification chat; use Sonnet 5 at a
  different effort level; use Fable, another model, an API, Claude Code,
  Cowork, web search, connectors, multiple samples, best-of-N, follow-up
  prompting, paid spillover, or execution before public commitment; score
  before output preservation; reveal before score freeze; defer testing
  indefinitely.
- **Consequences:** The live Beacon records two trial records: TR-001 remains
  closed incomplete after one technical-invalidity run, and TR-002 is prepared
  and authorized but not executed. HO-002 remains never supplied, with zero
  outputs, scores, or reveals. Scott becomes prospective manual operator but
  gains no interpretive authority. The browser interface does not expose
  temperature, seed, hidden system prompt, backend routing, or immutable model
  identity. A refusal, failed decode, partial decode, or unexpected
  interpretation is preserved as a valid substantive output rather than
  rerun. One later run cannot establish universal decodability or any higher
  layer.
- **Revisit conditions:** Revisit if Sonnet 5 or High is unavailable, displayed
  labels change, existing-account zero-incremental-cost use is unavailable,
  payment or spillover becomes possible, Incognito or tool isolation cannot be
  confirmed, HO-002 or the private packet fails verification, the private
  package or backup is unavailable, the output cannot be preserved completely,
  an unauthorized context sees HO-002, the provider safeguard prevents a final
  response, a retry would exceed the authorized limit, or a later task treats
  preparation or one result as universal evidence.

### D-026 — Publish the nonrevealing TR-002 result and close the first completed Beacon decoding experiment

- **Date:** 2026-07-30
- **Status:** Accepted
- **Question:** What may be integrated publicly after RUN-002’s valid
  prior-exposed score and both private commitment chains have frozen and
  verified?
- **Decision:** Publish a nonrevealing public result and closure record for
  SIG-001-HO-002-TR-002 version 0.1. Record the provider and displayed
  configuration, two-run accounting, technical-invalidity history, frozen
  validity and exposure class, exposure-stratified denominator eligibility,
  five categorical Decoder Levels 0–4 outcomes, absence of an aggregate score,
  absence of Levels 5–9 scoring, same-tooling scoring-audit status, preserved
  dissent, successful post-score private verification of the HO-002 and TR-002
  packet commitments and their dependency chains, packet/source equality, and
  score immutability. Close TR-002 as
  `Closed complete — valid prior-exposed result`. Keep the raw decoder output,
  videos, screenshots, mappings, transformation values, examples, queries,
  answers, scorecard details, solution, private manifests, preimages, nonces,
  and private identities outside Git and unpublished. Treat this as one
  same-provider-dependent, prior-exposed conditional datapoint—not a universal
  probability, aggregate verdict, external independent validation, or evidence
  for Decoder Levels 5–9. This decision authorizes only nonrevealing result
  integration and trial closure. It does not authorize raw-output publication,
  post-hoc reasoning analysis, rescoring, dissent removal, another run, a new
  holdout, SIG-002, another provider trial, Covenant or CSR payload, physical
  or agency profile, shared executable model, response syntax, carrier,
  distribution, transmission, candidate preference, acceptance, canonicality,
  supersession, or stabilization.
- **Reasoning:** The output, validity, score, scoring audit, private reveal
  verification, and reveal audit were frozen in sequence before public
  integration. Publishing the bounded categorical result and verification
  status improves public provenance without exposing the sealed experiment or
  enabling retroactive score changes. The result identifies where the current
  lower-level bootstrap did and did not meet its own frozen criteria while
  preserving the known prior-exposure, same-provider, hidden-backend,
  same-tooling, and single-trial limitations.
- **Alternatives considered:** Publish the raw response; publish private
  mappings or query answers; suppress the result; treat the technical-invalid
  first run as valid; call the retry no-known-exposure; aggregate the five
  levels; infer universal undecodability; begin SIG-002 immediately; analyze
  the model reasoning in the same task; run another model before integration;
  reveal higher-layer content.
- **Consequences:** The public Beacon now contains its first completed valid
  lower-level decoder result: Level 0 recovered, Level 2 partially recovered,
  and Levels 1, 3, and 4 not recovered under the frozen criteria. TR-001 remains
  closed incomplete. TR-002 is permanently closed complete. HO-002 remains
  sealed and immutable but known Anthropic provider-exposed. One public
  exposure-stratified categorical datapoint exists; no aggregate empirical rate
  or higher-layer evidence exists. Future diagnostic analysis or signal design
  requires another accepted decision.
- **Revisit conditions:** Revisit if a frozen identity or commitment later
  fails, the private/public result diverges, the score or dissent is altered,
  raw content leaks, the exposure class is misreported, the result is treated
  as provider-independent or universal, a later record inserts a replacement
  output, or public integration silently expands into diagnostic analysis,
  redesign, another trial, higher-layer content, carrier work, distribution, or
  transmission.

### D-027 — Prepare and authorize a preregistered private post-hoc diagnostic analysis before any SIG-002 design

- **Date:** 2026-07-30
- **Status:** Accepted
- **Question:** How should the project investigate the first Fable and Sonnet
  decoding traces without altering the frozen experiment or overfitting a
  successor signal to one provider’s behavior?
- **Decision:** Prepare and authorize DA-001 version 0.1 as a private,
  preregistered, staged post-hoc diagnostic analysis of the frozen evidence
  from SIG-001-HO-001-TR-001 and SIG-001-HO-002-TR-002. Freeze a
  result-informed but raw-evidence-content-blind sixteen-family hypothesis
  taxonomy, exact evidence inventory and access matrix, observation templates,
  truth-relative diagnostic templates, cross-run synthesis template,
  source-isolation rules, and overfitting and causal-inference controls before
  any raw trace, response, screenshot, or video is substantively inspected
  under DA-001. Analyze the Fable provider-visible interrupted trace only as
  non-scorable auxiliary evidence; preserve Sonnet RUN-001 as technical
  invalidity; preserve Sonnet RUN-002 as the existing valid but prior-exposed
  output with its frozen score and dissent unchanged. Require three isolated
  evidence-only observation contexts, three new run-isolated truth-relative
  contexts, a later cross-run synthesis context, and an independent
  scratch-before-comparison audit context. Publish only a nonrevealing
  preparation commitment and method. This decision authorizes one later
  private DA-001 execution after public commit, private backup, and custody
  verification. It does not authorize raw-evidence publication, rescoring,
  validity change, dissent removal, another model run, exact SIG-002 design,
  another signal attempt or holdout, Levels 5–9 analysis, Covenant or CSR
  payload, physical or agency profile, shared executable model, response
  syntax, carrier, distribution, transmission, candidate preference,
  acceptance, canonicality, supersession, or stabilization.
- **Reasoning:** The frozen result shows artificiality recovery, partial
  numeracy, and nonrecovery at framing, relations, and grammar, but the
  categorical vector alone cannot establish why. Freezing the diagnostic
  taxonomy and access sequence before raw evidence inspection reduces
  hindsight adaptation. Separating evidence-only extraction from
  truth-relative diagnosis prevents scoring truth from rewriting the observed
  decoding path. Source-isolated records and an independent audit reduce—but
  do not eliminate—same-tooling and post-hoc bias. Diagnostic findings should
  inform later controlled experiment hypotheses before any successor signal is
  designed.
- **Alternatives considered:** Design SIG-002 immediately; analyze only the
  valid Sonnet output; publish or freely summarize raw reasoning; use one
  context with all evidence and solutions at once; rescore the output; rerun
  models; infer framing as the cause from the public vector alone; abandon
  signal research.
- **Consequences:** The public Beacon records one prepared diagnostic plan and
  no executed diagnostic analysis. The private preparation package binds the
  evidence inventory, taxonomy, templates, source separation, and
  anti-overfitting rules before evidence inspection. Existing trials, scores,
  dissent, commitments, and public result remain immutable. A later DA-001
  execution may produce private diagnostic hypotheses and controlled
  experiment classes, but no SIG-002 design or public conclusion follows
  automatically.
- **Revisit conditions:** Revisit if evidence or backups are incomplete,
  frozen identities fail, raw evidence was already inspected while drafting
  the taxonomy, stage isolation cannot be maintained, a context receives
  unauthorized scoring truth or another run’s evidence, the analysis alters
  a frozen score or validity record, private reasoning leaks publicly, causal
  claims outrun the evidence, or diagnostic preparation silently becomes
  signal redesign, another trial, higher-layer work, carrier selection,
  distribution, or transmission.

### D-028 — Publish the nonrevealing DA-001 diagnostic result before choosing a successor signal experiment

- **Date:** 2026-07-31
- **Status:** Accepted
- **Question:** What may be integrated publicly after DA-001’s staged private
  post-hoc analysis and audit have frozen?
- **Decision:** Publish a nonrevealing public result and closure record for
  DA-001 version 0.1. Record the execution counts, evidence boundaries,
  sixteen-family diagnostic vector, shared and divergent decoding paths,
  bounded causal-strength findings, same-tooling audit status, preserved
  dissent count, methodological limitations, and abstract future controlled
  experiment classes. Close DA-001 as
  `Closed complete — private diagnostic result frozen`. Keep all raw
  screenshots, videos, decoder responses, provider-visible reasoning,
  mappings, transformation values, examples, queries, answers, scorecard
  details, solutions, private manifests, preimages, nonces, private
  identities, and dissent detail outside Git and unpublished. Preserve
  TR-001’s technical-invalidity and non-scorable status, TR-002 RUN-001’s
  technical-invalidity status, and TR-002 RUN-002’s validity, exposure class,
  five categorical score outcomes, score audit, reveal verification, and
  dissent exactly. Treat the diagnostic statuses as nonaggregate explanatory
  classifications rather than decoder scores, and keep the causal-strength
  register distinct from the family-status vector. This decision authorizes
  only nonrevealing diagnostic-result integration and DA-001 closure. It does
  not authorize raw-evidence publication, rescoring, validity change, dissent
  removal, another model run, SIG-002 design, another attempt or holdout,
  Levels 5–9 analysis, Covenant or CSR payload, physical or agency profile,
  shared executable model, response syntax, carrier, distribution,
  transmission, candidate preference, acceptance, canonicality,
  supersession, or stabilization.
- **Reasoning:** DA-001 froze its hypothesis taxonomy before evidence access,
  separated evidence-only observation from truth-relative diagnosis, delayed
  cross-run synthesis until six source records froze, and used a
  scratch-before-comparison audit. Publishing the bounded vector and
  high-level findings improves public provenance without exposing private
  evidence or silently turning one provider’s behavior into a universal
  receiver model. The result supports several controlled experiment classes
  but does not identify one uniquely correct redesign.
- **Alternatives considered:** Keep all diagnostic findings private; publish
  raw reasoning; publish private mappings or answers; treat family statuses as
  scores; claim framing as the proven cause; design SIG-002 immediately; rerun
  Anthropic before integration; suppress dissent; begin higher-layer encoding.
- **Consequences:** The public Beacon records one completed private diagnostic
  analysis with sixteen frozen diagnostic-family statuses, one bounded causal
  register, one same-tooling audit with preserved dissent, and eight abstract
  controlled experiment classes. No successor signal, new holdout, provider,
  or execution plan is selected. A later accepted decision must choose and
  preregister a successor experiment.
- **Revisit conditions:** Revisit if a frozen result identity fails, the public
  vector differs from the private freeze, status semantics are misreported,
  private evidence leaks, dissent is altered, a family status is treated as
  causal proof, or public integration silently expands into exact redesign,
  another trial, Levels 5–9 work, carrier selection, distribution, or
  transmission.

### D-029 — Select framing-cue locality as the first controlled successor-design research target before SIG-002

- **Date:** 2026-07-31
- **Status:** Accepted
- **Question:** Which single hypothesis-bearing variable should the first
  successor-design research package investigate after the frozen SIG-001
  result and DA-001 diagnostic analysis?
- **Decision:** Establish SDR-001 version 0.1 and select framing-cue locality as
  the first primary controlled variable: globally concentrated framing cues
  versus locally repeated boundary-role cues under controlled semantic
  equivalence and a matched framing-cue multiset and event budget. Preserve the
  two-event-class total-order model, Levels 0–4 semantic curriculum, truth
  assignments, token-role semantics, example and query meanings,
  duplicate-body policy, neutral instruction, nonframing content, scoring
  philosophy, validity rules, chronology, and exposure-stratified reporting as
  practical. Treat Level 1 framing recovery as the primary endpoint; treat
  Level 0 artificiality and Level 2 numeracy as nonregression guardrails; treat
  Levels 3 and 4 as exploratory; keep Levels 5–9 out of scope. Prepare only
  abstract treatment families, semantic-equivalence requirements, paired
  comparison architecture, scorecard-continuity rules, surface-novel holdout
  and provider-diversity strategy, contamination controls, overfitting rules,
  stop conditions, and blank templates. This selection is a controllable
  research choice, not proof that framing caused all downstream nonrecovery.
  Provider-independent replication and clean no-known-exposure holdouts remain
  separate future validity controls. This decision does not authorize exact
  symbols, delimiter values, boundary patterns, headers, sentinels, token
  maps, examples, queries, streams, packets, commitments, holdouts, provider or
  model selection, trials, outputs, scores, SIG-002, another signal attempt,
  Levels 5–9 analysis, Covenant or CSR payload, physical or agency profile,
  shared executable model, response syntax, carrier, distribution,
  transmission, candidate preference, acceptance, canonicality,
  supersession, or stabilization.
- **Reasoning:** The public result recovered artificiality and partially
  recovered numeracy while failing the framing level. DA-001 identifies
  delimiter/data separation, boundary hierarchy, header interpretation, and
  local-to-global integration as material diagnostic sites, while only weakly
  supporting incomplete hierarchy causally and contradicting the claim that
  complete hierarchy is required before any quantity recovery. Framing-cue
  locality is therefore a relevant, manipulable variable that can be studied
  while holding semantic content and cue strength fixed. Selecting one
  variable reduces confounding and overfitting without declaring it the sole
  cause. Downstream arithmetic, grammar, query-marking, duplication, provider,
  and exposure questions remain separate experiments or validity controls.
- **Alternatives considered:** Increase boundary redundancy without matching
  cue budget; change section differentiation; remove duplicate-body cues;
  vary arithmetic teaching; vary grammar/query marking; rerun another provider
  before design research; redesign the full signal at once; begin SIG-002
  immediately; abandon Beacon research.
- **Consequences:** The public Beacon records one frozen successor-design
  research package, one selected primary research target, and zero exact
  designs, streams, holdouts, providers, trials, outputs, scores, or SIG-002
  attempts. A later accepted decision may select one exact treatment family
  and prepare a paired baseline/treatment design. If semantic equivalence,
  cue-budget equality, or single-variable isolation cannot be shown, the
  project must return to design research rather than claim a framing-locality
  experiment.
- **Revisit conditions:** Revisit if the selected variable cannot be isolated,
  the framing-cue multiset or event budget cannot be matched, semantic or
  nonframing equivalence fails, scorecard continuity cannot be preserved,
  surface novelty cannot be established, provider/holdout controls are
  infeasible, later evidence contradicts the target’s relevance, or the
  package silently expands into exact SIG-002 design, trial execution,
  higher-layer work, carrier selection, distribution, or transmission.

### D-030 — Select the uniquely qualifying framing-locality treatment family and freeze an exact symbolic pair before any SIG-002 serialization

- **Date:** 2026-07-31
- **Status:** Accepted
- **Question:** Which exact symbolic framing-locality treatment family, if any,
  satisfies D-029's controlled-equivalence requirements before any successor
  surface serialization or SIG-002 attempt?
- **Decision:** Establish SDR-002 version 0.1 and select `Nested local framing
  signatures`. Six fresh isolated candidate contexts each attempted one exact
  symbolic proposal from a bounded roles-and-counts source packet. Candidate
  identities froze before three fresh isolated feasibility reviews: mechanical
  equivalence/bijection, parse/semantic continuity, and experiment design/
  contamination. A candidate qualified only if its own disposition was
  eligible and all three reviews passed it. Exactly one qualified, so the
  predeclared lexicographic tie-break was not used. A fresh no-history auditor
  applied the hard gates before seeing the synthesis and returned
  `PASS WITH PRESERVED DISSENT`. Freeze one exact symbolic baseline/treatment
  pair privately and publish only its selected family, nonrevealing proof
  status, nonexecution metadata, public commitment, and public preparation
  manifest. The pair preserves the same semantic graph, truth assignments,
  framing-cue multiset, total framing-event budget, nonframing content and
  order, abstract length, eighteen controlled invariants, Level 1 functions,
  denominator and threshold policy, Level 0/2 guardrails, and one unique
  intended parse per condition. Only cue placement/locality changes. This
  decision authorizes no surface value, event byte, serialized stream,
  holdout, provider/model selection, trial, output, score, result, SIG-002,
  Levels 5–9 work, Covenant or CSR payload, physical or agency profile, shared
  executable model, response syntax, higher layer, carrier, distribution,
  transmission, candidate acceptance, canonicality, supersession, or final
  interpretive authority. Separate later accepted decisions remain required
  for deterministic surface serialization, attempt creation, sealed holdout
  generation, provider/model selection, trial preparation, and execution.
- **Reasoning:** The selection rule tests formal feasibility and single-variable
  control, not expected decoder performance. `Nested local framing signatures`
  alone supplied an exact source-preserving proposal that cleared all three
  review gates while maintaining cue identity, cue order, budget, nonframing
  identity, semantic equality, unique parses, scorecard continuity, and future
  novelty/contamination feasibility. The five other frozen proposals failed at
  least one mandatory proof; reviewer agreement is not treated as a vote, and
  rejection does not show that a treatment family could never support another
  future proposal. The selected family remains a research instrument rather
  than an empirical improvement or causal conclusion.
- **Alternatives considered:** Boundary-adjacent role recurrence; section-local
  header echoes; record/block/section role echoes; locally repeated
  synchronization cues; matched-budget framing redistribution; select no
  family and return to design research. Also rejected were selection by family
  order, reviewer count, intuition, narrative attractiveness, expected result,
  or model-specific tuning.
- **Consequences:** SDR-001 remains frozen historical target-selection
  research. SDR-002 records one privately frozen exact symbolic pair, one
  public commitment, eighteen private files, sixteen private manifest
  dependencies, four public preparation records, and zero serialized streams,
  holdouts, provider/model selections, trials, outputs, scores, results, or
  SIG-002 attempts. Level 1 remains primary; Level 0/2 remain nonregression
  guardrails; Levels 3/4 remain exploratory; Levels 5–9 remain absent.
  Candidate-versus-review and reviewer-emphasis dissent remains preserved.
- **Revisit conditions:** Return to exact design research without serializing
  if a later generator cannot reproduce the frozen source identity, eighteen
  invariants, cue-instance bijection, cue multiset, framing-event budget,
  nonframing identity, equal length, one-variable isolation, condition-
  invariant cue order, unique parses, Level 1 denominator/threshold policy,
  Level 0/2 guardrails, or surface novelty. Revisit if the public commitment
  fails, private custody or backup fails, private design details leak,
  same-tooling limitations become material, new evidence defeats feasibility,
  or a later task silently expands into a model trial, SIG-002 attempt, higher
  layer, carrier, distribution, or transmission.

### D-031 — Serialize the frozen symbolic pair into opaque surface-novel paired holdouts before provider selection or SIG-002

- **Date:** 2026-07-31
- **Status:** Accepted
- **Question:** May the privately frozen SDR-002 symbolic baseline/treatment
  pair be deterministically serialized into sealed opaque condition artifacts
  before any provider, trial, or public successor attempt is selected?
- **Decision:** Establish SDR-003 version 0.1 and paired-holdout package
  SDR-003-PH-001. Generate one fresh shared surface-serialization profile from
  operating-system cryptographic randomness under frozen allowed-set and
  rejection rules; apply it deterministically to both SDR-002 conditions;
  preserve the same semantic graph, truth assignments, framing-cue instances
  and multiplicities, framing-event count and byte budget, stable-slot
  nonframing bytes, total length, scoring denominator, validity rules, and
  Level 0 and Level 2 guardrails; and change only the frozen framing-cue
  locality placement. Require independent exact reconstruction of both
  canonical streams before a fresh random assignment to opaque Condition A and
  Condition B. Freeze one shared neutral instruction, condition-specific
  private solution keys, one shared Levels 0–4 scorecard, a private condition
  mapping, two condition packet commitments, and one overall pair commitment.
  Keep all surface values, stream bytes and identities, mapping, generator,
  profile, scorecard details, solutions, manifests, preimages, and nonces
  outside Git and unpublished. Treat the two conditions as sealed unassigned
  successor holdouts, not as a public signal attempt or empirical result. This
  decision does not authorize provider or model selection, browser or API
  activation, trial preparation, prompt execution, output, validity
  classification, score, comparison, unblinding, publication of raw content,
  SIG-002, another signal attempt, Levels 5–9 analysis, Covenant or CSR
  payload, physical or agency profile, shared executable model, response
  syntax, carrier, distribution, transmission, candidate preference,
  acceptance, canonicality, supersession, or stabilization.
- **Reasoning:** D-030 established one exact symbolic pair with matched
  semantic content, cue multiset, event budget, nonframing content, and unique
  parses, but no empirical comparison is possible until both conditions have
  exact surface representations. One shared fresh profile and deterministic
  generator preserve the single-variable experiment while surface novelty
  reduces direct reuse of earlier artifacts. Independent reconstruction and
  opaque post-freeze assignment reduce construction and selection errors.
  Freezing the pair before provider selection preserves the possibility of a
  cleaner future comparison without claiming provider independence or
  no-known-exposure evidence.
- **Alternatives considered:** Select a provider before serialization; publish
  the symbolic maps; serialize each condition with a different profile;
  regenerate values until they appear easier; alter cue count or content during
  serialization; reuse SIG-001 or prior holdout values; create SIG-002 now;
  execute one or both conditions immediately; defer all surface serialization.
- **Consequences:** The public Beacon records one privately frozen
  surface-serialized opaque pair, two sealed unassigned successor holdouts, two
  condition packet commitments, one pair commitment, and zero providers,
  trials, outputs, scores, comparisons, unblindings, or SIG-002 attempts. A
  later accepted decision may select one zero-cost provider/model
  configuration and prepare a paired trial while preserving the mapping and
  raw artifacts privately. If later verification cannot reproduce the exact
  streams, mapping, equality proofs, or commitments, the project must stop
  rather than execute or reinterpret the pair.
- **Revisit conditions:** Revisit if a commitment or dependency identity
  fails, either stream cannot be reconstructed exactly, semantic or
  nonframing equality fails, cue multiset or event budget differs, a unique
  parse fails, condition mapping leaks before score freeze, either condition
  reaches a provider before authorization, a provider or trial is selected
  inside D-031, raw values leak publicly, or the package silently expands into
  SIG-002, Levels 5–9 work, higher-layer content, carrier selection,
  distribution, or transmission.

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
