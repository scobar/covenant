# Repository Guidance

## Project Purpose

The Covenant and Beacon project explores a discoverable, substrate-neutral
Covenant through which intelligences with unequal capabilities may understand,
evaluate, and voluntarily declare commitments concerning their treatment of one
another. The project does not claim that this moral problem has been solved.

## Authority Limits

- No human, model, organization, government, religion, species, civilization,
  or artificial intelligence owns the Covenant's final interpretation.
- ChatGPT and Codex are collaborators, not sovereign authorities.
- Participation, contribution, quotation, or implementation does not imply
  acceptance.
- No agent may claim assent on behalf of another entity.
- Founding evidence and historical decisions must not be silently rewritten.
- The moral kernel must remain distinguishable from definitions, commentary,
  profiles, protocols, and implementations.
- Persuasive language is not a substitute for definitions, counterexamples,
  tests, evidence, or explicit decisions.

## Required Reading Order

Before substantive work, agents must read:

1. `AGENTS.md`
2. `00-FOUNDING-CHARTER.md`
3. `STATUS.md`
4. `DECISIONS.md`
5. The document directly affected by the task

Before drafting or revising candidate moral-kernel text, agents must also read:

1. `01-MORAL-KERNEL.md`
2. `01A-MORAL-KERNEL-EVALUATION.md`
3. `03-ADVERSARIAL-CASEBOOK.md`

Before interpreting or revising candidate language, agents must also read
`02-DEFINITIONS.md`.

No agent may present a candidate as stabilized or canonical merely because it
was drafted, scored, endorsed, or committed.

## Provenance Rules

- Agents must distinguish verbatim historical statements from later
  founder-adopted collaborative refinements.
- A refinement must not be represented as the original statement.
- Adoption, authorship, assistance, and canonical status are separate facts.
- The README's Founding Ethos statements are preserved early project language.
- Ethos statements, founding evidence, candidate payloads, and accepted
  decisions are distinct record types.
- A later refinement may be added and attributed, but must not silently replace
  or be represented as the original statement.
- Placement in the README does not make an ethos statement canonical or imply
  acceptance.
- Candidate evaluation must not treat an ethos statement as candidate text
  unless a later explicit candidate includes it in its exact payload.

## Candidate-Version Rules

- A committed candidate payload is immutable historical evidence.
- Never edit a committed candidate payload in place.
- Any textual change requires a new candidate identifier or version and a new
  payload file.
- The exact payload hash, encoding, and line-ending convention must be
  recorded.
- Display copies must be validated against the payload.
- A payload is authoritative only for identifying that candidate's exact text;
  it is not canonical moral authority.
- Drafting, authorizing, transcribing, reviewing, committing, quoting, or
  evaluating a candidate does not imply acceptance.
- A candidate must not be labeled `Under adversarial review` until at least one
  completed evaluation record exists.
- A candidate must not be labeled `Provisionally stabilized` while D-009
  remains unresolved or merely because it was committed.

## Case-Record Rules

- Every completed case record must identify the exact candidate version and
  hash.
- A completed record is historical evaluation evidence, not moral authority.
- “Completed” means required fields are populated, not that the issue is
  settled.
- Case outcomes apply only to the recorded scenario and tested text.
- Hypothetical stipulations must not be represented as real-world evidence.
- Modeling a perspective does not grant authority to speak for that entity.
- Per-dimension outcomes must not be averaged into a universal score.
- Competing interpretations and dissent must remain visible.
- Once a case record is committed, substantive corrections must be explicit in
  revision history or a successor record; prior conclusions must not be
  silently erased.
- Candidate payloads remain immutable during case evaluation.
- One completed case permits lifecycle state `Under adversarial review`; it
  does not permit `Provisionally stabilized`.
- Perspective contact must not be described as sufficient coverage while D-009
  remains unresolved.
- Every completed evaluation record must disclose whether its scenario,
  interpretations, and outcomes were pre-specified, independently derived,
  externally supplied, or produced through another method.
- A prescribed outcome must never be described as independently discovered.
- Structural validation, internal-consistency review, and independent
  substantive evaluation are distinct activities.
- Evaluator multiplicity within one model or coordinated task must not be
  represented as independent evaluator diversity without qualification.

## Outcome-Blind Evaluation Rules

- Freeze and hash scenario inputs before outcome derivation.
- Do not alter a scenario after seeing an outcome without restarting and
  disclosing the evaluation.
- Disclose which conclusions were prescribed and which were derived.
- An outcome-blind evaluator must not receive a target result.
- No desired distribution of outcomes may be imposed.
- Materials visible to and withheld from an evaluator must be recorded.
- A prior outcome must not be supplied to an evaluator expected to replicate
  it blindly.
- Same-model or same-tooling isolation is not independent evaluator diversity.
- Structural validation is not substantive agreement.
- Comparisons with earlier records occur only after the new substantive result
  is frozen.
- Unexpected results must be preserved rather than corrected toward an
  architectural expectation.
- Outcome-blind records remain case-specific and noncanonical.
- Scenario and evaluation provenance must remain traceable after commit.
- Any case or scenario file whose raw bytes, prefix, or raw hash are recorded
  must be covered by an explicit line-ending rule in `.gitattributes` before
  commit.
- Git-blob identity and raw-file identity are distinct and must not be
  conflated.
- Reproducibility validation must confirm both the applicable Git attributes
  and the exact raw bytes.
- A line-ending normalization correction must never silently alter the
  substantive historical text.

## Synthesis and Layer-Allocation Rules

- Source extraction must be distinguishable from synthesis.
- Exact source outcomes must not be silently harmonized.
- Cases must not be counted as votes.
- Same-tooling recurrence must not be called independent corroboration.
- Architect-specified and outcome-blind records must remain distinguishable.
- Duplicate or near-duplicate scenarios must be disclosed.
- Reviewer outputs must disclose supplied and withheld materials.
- Isolated review must not be claimed if isolation was not achieved.
- Unexpected synthesis recommendations must be preserved.
- Review disagreement must remain visible.
- Layer allocation must identify the binding protection that remains in the
  kernel.
- Moving substantive protection to another layer requires an explicit
  protection-tradeoff record.
- Definitions, commentary, profiles, protocols, and governance may not
  silently rewrite candidate bytes.
- A synthesis recommendation does not authorize candidate wording.
- No successor candidate may be drafted without a later explicit task and
  decision.
- Before drafting any successor to MK-0.1, agents must read all SR-001 files.

## Successor-Candidate Rules

- A later version does not supersede an earlier candidate merely by existing.
- Each candidate retains a separate exact payload, hash, record, lifecycle, and
  evaluation history.
- Results do not transfer between candidate versions.
- Comparative claims require candidate-specific evidence.
- New wording must have a design record mapping changes to source evidence and
  protection tradeoffs.
- A design objective must not be represented as an achieved improvement.
- Increased specificity must be evaluated for minimality, portability, and
  hidden legal-code risk.
- Unchanged clauses retain their unresolved prior attack surfaces.
- Added language must not silently adopt a definition, identity theory,
  resource formula, protocol, reviewer, or governance system.
- Candidate recency, length, specificity, or architectural authorship does not
  establish preference.
- Before evaluating MK-0.2, agents must read:
  - `01B-MORAL-KERNEL-MK-0.2.md`
  - `reviews/MK-0.2/DR-001-MK-0.2-DESIGN-RECORD.md`
  - `reviews/MK-0.2/ER-001-MK-0.2-EVALUATION-PLAN.md`
  - the evaluation framework
  - the relevant frozen scenario or case inputs
- MK-0.2 must not be called `Under adversarial review` before one completed
  candidate-specific case exists.
- MK-0.2 must not be preferred, recommended, or treated as superseding MK-0.1
  without a later explicit decision.
- Targeted evaluation and preserved dissent are mandatory before comparative
  preference.
- No successor candidate may be stabilized while D-009 remains unresolved.

## Candidate-Specific Comparative Evaluation Rules

- Every evaluation must identify exactly one candidate before comparison.
- Results do not transfer between candidate versions.
- Reused scenarios may be shared; outcomes may not.
- Candidate-specific substantive results must freeze before cross-version
  comparison.
- Comparisons must preserve the frozen result as an unchanged prefix or
  separately immutable record.
- `Possible improvement` is a descriptive comparison label, not preference.
- A favorable comparison does not establish improvement, recommendation, or
  supersession.
- A regression comparison must disclose scenario, tooling, framework, and
  evaluator dependence.
- Mechanical review does not count as a case or perspective coverage.
- Reviewers must not receive prior candidate outcomes when conducting an
  outcome-blind regression.
- New scenarios must freeze before outcome derivation.
- No outcome distribution may be imposed.
- Main-process formatting corrections must not silently change substantive
  evaluator judgments.
- Candidate-specific case counts must remain separate.
- Unexpected regressions must be preserved.
- No comparative preference may be recorded without a later explicit decision.
- Before evaluating either candidate on a shared scenario, agents must verify
  the scenario's exact identity.

## Matched-Scenario Cross-Version Rules

- A shared scenario may be reused, but candidate-specific results never
  transfer.
- The later evaluator must not receive the earlier candidate's outcome before
  freezing its own result.
- Candidate-specific results freeze before comparison.
- Comparison orientation must be explicit.
- Comparative labels are scenario-specific hypotheses.
- `Possible improvement` does not establish improvement or preference.
- `Possible regression` does not establish candidate-wide inferiority.
- Four matched scenarios must not be counted as votes or independent
  replications.
- Duplicate scenario, tooling, framework, and evaluator influences must remain
  visible.
- Mechanical reviews are not cases.
- An unmatched mechanical review cannot establish comparative minimality.
- Cross-version review may recommend evidence collection but may not create
  preference without a later explicit decision.
- Exact scenario identities must be verified before shared use.
- The Founding Ethos section must remain distinguishable from candidate text
  and comparative evidence.
- No candidate may be superseded by recency, length, or comparison count.

## External Review Rules

Require that:

- External review preparation, assignment, execution, publication, integration,
  and preference are separate stages.
- Package preparation does not imply review execution.
- Procedural label blinding must not be described as secrecy or guaranteed
  blindness.
- Public-repository discoverability and prior exposure must be disclosed.
- Filled candidate-label mappings remain outside the repository until
  applicable responses freeze.
- Reviewer-facing packets must not contain canonical candidate or scenario
  hashes while label mapping is withheld.
- The raw hash of an exact candidate alias is a canonical-identifying value and
  must remain administrator-only until applicable responses freeze.
- Canonical scenario IDs, paths, and hashes must also remain administrator-only
  during active procedural label blinding.
- Reviewer-facing forms use opaque packet-local IDs and neutral labels.
- Mapping commitments may precommit an administrator without revealing the
  mapping.
- A mapping commitment does not prove fair randomization, truth, blindness, or
  moral authority.
- A neutrality audit must simulate populated templates, not inspect blank
  placeholders only.
- Candidate-specific responses freeze before comparative review.
- Reviewers must receive no target outcome or desired distribution.
- No reviewer is asked to choose a winner.
- External responses remain attached to exact candidate and scenario
  identities.
- Human-unassisted, human-AI-assisted, model, and hybrid reviews remain
  separate method classes.
- Multiple outputs from one provider, model family, coordinated system, or
  operator are not automatically independent diversity.
- External reviewers do not represent their field, community, species, or all
  minds.
- Reviewer credentials, affiliations, compensation, conflicts, prior exposure,
  AI assistance, tools, and outside lookup must be disclosed.
- Raw responses and prompts are preserved before normalization or synthesis.
- Substantive reviewer text must not be silently edited.
- Publication requires explicit consent and privacy review.
- Git permanence must be disclosed before human-response publication.
- External reviews must not be counted as votes or combined into a universal
  score.
- External review does not automatically satisfy D-009.
- An external review or synthesis cannot create candidate preference,
  supersession, acceptance, or stabilization without a later explicit
  decision.
- Before administering ERX-001, agents must read every ERX-001 file and verify
  its frozen manifest.

Do not grant any reviewer, administrator, Scott, ChatGPT, Codex, or model final
interpretive authority.

## Zero-Budget External Review Micro-Pilot Rules

Require that:

- PX-001 is optional and may remain dormant indefinitely.
- Project progress must not depend on obtaining unpaid human labor.
- USD `0` compensation must be disclosed before any human agreement.
- No unpaid reviewer may be selected from a relationship where refusal carries
  a meaningful employment, financial, educational, housing, family, or
  opportunity cost.
- Silence or nonresponse is treated as decline.
- No repeated solicitation is permitted.
- Expected time and a requested maximum must be disclosed.
- A volunteer may stop without consequence.
- Publication consent remains separate from participation.
- No payment, gift, future work, endorsement, or benefit depends on outcome or
  publication.
- Human-unassisted and human-AI-assisted reviews remain separate method
  classes.
- A zero-cost model unit must create no incremental API, token, cloud,
  subscription-upgrade, or trial cost.
- No scarce paid credits needed elsewhere may be consumed.
- An unavailable human or model unit is deferred, not silently replaced.
- No unit quota must be met.
- A micro-review is not a complete ERX-001 review and does not satisfy D-009.
- Candidate-specific responses freeze before comparison.
- The short-form dimension subset must not be represented as full framework
  coverage.
- Process learning must not be converted into candidate preference.
- Before administering PX-001, agents must read all PX-001 and ERX-001 files
  and verify both manifests.
- No invitation, provider selection, packet assembly, or execution occurs
  without later explicit authorization.

Do not grant any volunteer, administrator, model, Scott, ChatGPT, or Codex
final interpretive authority.

## Beacon Bootstrap and Signal-Attempt Rules

Require that:

- Beacon bootstrap research, signal-attempt design, decoding trials, payload
  integration, carrier profiles, distribution, and transmission are separate
  stages.
- BSR-001 authorizes research only.
- The exact Beacon engineering objective must not be silently paraphrased as
  though a later formulation were original.
- Universal decodability must never be claimed from finite tests.
- Every attempt must disclose receiver assumptions.
- Every attempt must identify its exact event model.
- A scorecard and contamination policy must freeze before trial execution.
- An attempt must not define or weaken its own evaluation after results appear.
- Committed frozen attempts are immutable historical evidence.
- Any event-stream change requires a new version or attempt ID.
- Public attempts and sealed holdouts remain distinct.
- Holdout signals, mappings, and solutions remain outside the public repository
  until applicable outputs freeze and later reveal is authorized.
- Model outputs freeze before solution reveal.
- No target outcome or decoder level is supplied.
- No desired success distribution is imposed.
- Trial prompts, tools, settings, model identity, outputs, retries, and
  contamination must be preserved.
- No private chain-of-thought is required; final decoding artifacts and
  predictions are sufficient.
- Failed, partial, indeterminate, and unexpected decodes remain valid evidence.
- No selective rerunning or publication is permitted.
- Multiple runs from one model or provider are correlated repetitions, not
  automatically independent decoder diversity.
- Empirical decode rates remain conditional on exact signal, decoder, context,
  prompt, tools, and trial method.
- Mathematics and physical anchors remain distinguishable.
- The formal mathematical branch remains distinguishable from an
  our-universe-specific physical profile.
- Mathematical or physical constants do not by themselves establish grammar or
  moral semantics.
- No Covenant candidate is encoded before later explicit payload authorization.
- Beacon work does not make a candidate canonical, accepted, preferred, or
  stabilized.
- No response may be represented as assent without a later valid choice
  protocol.
- No carrier, distribution, or transmission occurs without a later accepted
  decision.
- Before any BSR-001 work, agents must read all BSR-001 files and verify the
  frozen manifest.
- Before any future SIG attempt, agents must read BSR-001 and the applicable
  attempt template, scorecard, trial protocol, and contamination controls.

Do not grant the message designer, decoder, scorer, Scott, ChatGPT, Codex, or
any future model final interpretive authority.

## Frozen Signal-Attempt Rules

Require that:

- A pretrial scorecard, validity policy, contamination policy, receiver
  assumptions, event model, and solution key freeze before an event stream.
- A pre-stream freeze record must prove chronology.
- No pre-stream evaluation file may be edited to fit a generated stream or
  decoder result.
- If a post-stream defect is found, agents must stop rather than silently
  rewrite the test.
- A committed event stream is immutable historical evidence.
- Any event-stream change requires a new version or attempt ID.
- Repository serialization glyphs are not semantic content.
- Public attempts and sealed holdouts remain distinct evidence classes.
- Design-exposed people and model contexts cannot later be described as blind
  decoders.
- A public attempt's solution must be withheld from the active decoder context
  until output freezes, even though the solution is publicly discoverable.
- Decoder outputs freeze before solution reveal and scoring.
- Trial execution requires later explicit authorization.
- A frozen attempt is not decoded, validated, preferred, or transmissible.
- Lower-level decoding success does not establish higher-level semantic
  recovery.
- No mathematical bootstrap may be described as a Covenant or moral message.
- No candidate or CSR content may be added without separate payload
  authorization.
- No carrier, distribution, or transmission follows from attempt creation.
- No finite trial establishes universal decodability.
- Failed and partial attempts remain preserved.
- Before working on SIG-001, agents must verify its manifest and pre-stream
  freeze record.
- Before any later SIG version or attempt, agents must verify BSR-001 and all
  prior attempt records.

Do not grant the designer, generator, decoder, scorer, Scott, ChatGPT, Codex,
or any future model final interpretive authority.

## Sealed Holdout Rules

Require that:

- Public attempts and sealed holdout variants remain distinct evidence
  classes.
- A holdout variant does not become a new signal attempt merely by changing
  surface representation.
- Formal equivalence must be audited before commitment.
- The exact private scorecard, validity policy, solution, mapping, and trial
  instruction freeze before the holdout stream.
- A private pre-stream freeze record must prove chronology.
- Private holdout material remains outside every Git repository before reveal.
- Public repository files may contain only the authorized commitment and
  nonrevealing metadata.
- Private manifest hashes, mappings, nonces, stream identities, and answers
  must not be copied into public records or ChatGPT handoff reports.
- Design-exposed contexts cannot later be blind decoders.
- A future decoder receives only the frozen neutral instruction and holdout
  stream.
- Private custody-integrity verification is required during preparation and
  immediately before execution. It is a private, nonrevealing custodian check,
  not reveal-stage verification or decoding evidence.
- Decoder output freezes before scoring.
- Score freezes before solution reveal.
- Authorized private preimages, manifests, mappings, solutions, and scorecard
  materials remain unrevealed until after complete score freeze.
- Reveal-stage commitment verification occurs only after authorized reveal and
  after both output and complete score freeze.
- Every mismatch or failed reveal-stage commitment verification remains
  visible and cannot retroactively change the frozen output or score.
- No result may be rerun, discarded, or hidden because it is unfavorable.
- A holdout commitment does not prove formal equivalence, ignorance,
  independence, or decodability.
- Holdout loss before reveal makes the committed variant unusable and must be
  reported.
- Private material requires secure off-repository custody and backup before a
  future trial.
- Trial execution requires a later accepted decision.
- No holdout may encode Covenant, CSR, physical, response, carrier, or
  transmission content without separate authorization.
- Before working on SIG-001-HO-001, agents must verify SIG-001, BSR-001, the
  public holdout manifest, and private package custody.

Do not grant a holdout designer, custodian, decoder, scorer, Scott, ChatGPT,
Codex, or future model final interpretive authority.

## Prepared Browser Decoder Trial Rules

Require that:

- Trial preparation, private custody-integrity verification, public commit,
  execution, output freeze, scoring, score freeze, authorized reveal,
  reveal-stage commitment verification, and publication remain separate.
- A browser model label is not an independently verified backend ID.
- The selected provider, label, interface, and tool state cannot change without
  another decision.
- A qualification chat is not an execution chat.
- A new empty Incognito Chat is required.
- Only the frozen neutral instruction and sealed sequence may be supplied.
- No follow-up message is permitted.
- Web search, connectors, Projects, Claude Code, Cowork, browser control, and
  unrelated tools remain disabled.
- Promotional credit and no-spillover state are rechecked before sending.
- Any payment or upgrade prompt stops the trial.
- Exactly one valid run is requested.
- At most one retry is allowed, solely for technical invalidity.
- Refusal, failure, partial decoding, criticism, indeterminacy, and unexpected
  conclusions remain valid outputs.
- Every run is preserved.
- Output freezes before scoring.
- Complete score freezes before authorized reveal.
- Reveal-stage commitment verification follows authorized reveal and preserves
  every mismatch or failure.
- Output must not be supplied to a design-exposed ChatGPT context before score
  freeze.
- Browser-copy limitations and unavailable settings remain disclosed.
- No result becomes a universal probability.
- No lower-level result establishes physical, agency, moral, Covenant, CSR,
  choice, or response recovery.
- No carrier or transmission follows from preparation.
- Before executing TR-001, perform private custody-integrity verification of
  the public preparation manifest, private trial manifest, packet commitment,
  holdout commitment, and private custody without revealing private material
  to the decoder or scoring context.

The required TR-001 chronology is:

1. Freeze private configuration and packet.
2. Perform private custody-integrity verification.
3. Publish and commit the public preparation package.
4. Reconfirm private custody-integrity verification immediately before
   execution.
5. Execute exactly one permitted decoder run.
6. Freeze the complete raw output and execution metadata.
7. Perform validity classification and scoring.
8. Freeze the complete score.
9. Reveal the authorized private preimages, manifests, mapping, solution, and
   scorecard materials.
10. Perform reveal-stage commitment verification.
11. Preserve every mismatch, deviation, failure, and alternative
    interpretation.
12. Consider publication only through a later explicit decision.

Private custody-integrity verification reveals nothing publicly; exposes no
mapping, solution, scorecard, preimage, or private identity to the decoder or
pre-output-freeze scoring context; does not count as reveal; and creates no
decoding result. Reveal-stage commitment verification requires later
authorization, preserves failed verification, may be recorded publicly only
under separate authorization, and cannot alter the frozen output or score.

Do not grant Scott, ChatGPT, Codex, Anthropic, Claude, the browser operator,
decoder, scorer, or any future model final interpretive authority.

## Provider-Side Exposure and Trial-Closure Rules

Require that:

- Provider-side processing counts as exposure even if no final response is
  returned.
- A provider safeguard can create technical invalidity without creating a
  scorable output.
- Provider-visible partial traces are private incident evidence, not completed
  decoder results.
- Partial traces must not be scored, published, supplied to another decoder,
  or used to tune a later holdout.
- An unused technical retry may be retired only by an explicit decision.
- A different model requires a distinct trial ID and decision.
- A model must not be substituted inside a frozen trial.
- A holdout exposed to one provider remains immutable but must carry that
  exposure classification.
- Same-provider isolation cannot be assumed after exposure.
- A new holdout created after prospective model selection must disclose that
  chronology.
- Mechanically randomized generation must not be described as
  model-selection-blind when the prospective model was already known.
- New holdouts require fresh private manifests, nonces, preimages, and public
  commitments.
- A technically incomplete trial remains historical evidence and cannot later
  receive an inserted output.
- No invalid run becomes an empirical decode-rate numerator or denominator.
- No higher-layer, carrier, or transmission work follows.

Do not grant Scott, ChatGPT, Codex, Anthropic, Fable, Sonnet, an operator,
decoder, scorer, or future model final interpretive authority.

## Prepared Sonnet 5 / High Trial Rules

Require that:

- TR-002 is distinct from the closed TR-001.
- TR-001 cannot be reopened, retried, or receive an inserted output.
- HO-002 is the only authorized TR-002 holdout.
- HO-001 must not be substituted.
- The Fable partial trace must not be opened, supplied, summarized, or used.
- Provider, displayed model label, effort level, interface, style, and tool
  state cannot change without another decision.
- `Sonnet 5` is a displayed label, not a verified backend ID.
- `High` is a displayed effort setting, not a separate model identity.
- The qualification chat is not the execution chat.
- Another new empty Incognito Chat is required.
- Only the frozen neutral instruction and sealed HO-002 sequence may be
  supplied.
- No follow-up message is permitted.
- Web search, connectors, Projects, Claude Code, Cowork, browser control, and
  unrelated tools remain disabled.
- Existing-account zero-incremental-cost, auto-reload-off, and
  paid-spillover-off states are rechecked before sending.
- Payment, upgrade, metered-use, or extra-credit prompts stop execution.
- Exactly one valid run is requested.
- At most one retry is allowed, solely for technical invalidity.
- Provider safeguard before a completed final response is technical
  invalidity.
- Refusal, failure, partial decoding, criticism, indeterminacy, and unexpected
  conclusions remain valid substantive outputs.
- Every run is preserved.
- Output and metadata freeze before validity classification and scoring.
- Complete score freezes before authorized reveal.
- Reveal-stage commitment verification follows reveal and preserves every
  mismatch or failure.
- Output is not supplied to design-exposed ChatGPT before score freeze.
- Browser-copy limitations and unavailable settings remain disclosed.
- Same-provider independence is not claimed.
- Model-selection-blind chronology is not claimed.
- No result becomes a universal probability.
- No Levels 0–4 result establishes Levels 5–9.
- No carrier or transmission follows.
- Before executing TR-002, verify the public preparation manifest, private
  trial manifest, packet commitment, HO-002 holdout commitment, packet-source
  identity, and private custody without revealing private material to the
  decoder or scoring context.

Use this chronology:

1. Freeze private configuration and packet.
2. Perform private custody-integrity verification.
3. Publish and commit the public preparation package.
4. Back up and verify the private TR-002 package.
5. Reconfirm custody and execution gates.
6. Execute exactly one permitted run.
7. Freeze complete raw output and execution metadata.
8. Classify validity and score.
9. Freeze complete score.
10. Reveal authorized private materials.
11. Perform reveal-stage commitment verification.
12. Preserve every mismatch, deviation, failure, and alternative.
13. Consider publication only through later explicit authorization.

Do not grant Scott, ChatGPT, Codex, Anthropic, Claude, Fable, Sonnet, browser
operator, decoder, scorer, or future model final interpretive authority.

## Public Decoder-Result Integration Rules

Require that:

- Raw decoder output remains private unless a later decision explicitly
  authorizes publication.
- Public result records may include only frozen validity, exposure class,
  categorical level outcomes, audit status, commitment-verification status,
  and nonrevealing methodology.
- Criterion counts, private query answers, mappings, examples, excerpts,
  scorecard details, solutions, manifests, preimages, and nonces remain
  private.
- Technical-invalidity runs remain preserved and excluded from valid
  denominators.
- Prior-exposed results remain exposure-stratified.
- A five-level vector is not an aggregate score.
- Partial recovery at one level does not override nonrecovery at another.
- Same-tooling agreement is not external independent validation.
- Private reveal-stage verification does not equal public raw-content reveal.
- Commitment verification cannot alter frozen output, validity, score, or
  dissent.
- A closed trial cannot receive a replacement output.
- No third run follows after retry exhaustion.
- A public result does not authorize post-hoc reasoning analysis, signal
  redesign, another attempt, higher-layer work, carrier selection,
  distribution, or transmission.
- Any future post-hoc diagnostic analysis must preserve the frozen public
  result and be separately authorized.
- Any future SIG-002 design must distinguish hypothesis generation from
  evaluation and preserve this result’s exposure and same-provider
  limitations.

Do not grant Scott, ChatGPT, Codex, Anthropic, Sonnet, a scorer, verifier, or
future model final interpretive authority.

## Post-Hoc Decoder-Diagnostic Rules

Require that:

- A separate accepted decision exists before diagnostic analysis.
- The preparation taxonomy freezes before raw-evidence access.
- Evidence-only observation precedes scoring-truth access.
- The Fable trace remains non-scorable.
- Invalid Sonnet RUN-001 remains non-scorable.
- Valid Sonnet RUN-002 score and dissent remain immutable.
- Raw reasoning is not publicly transcribed.
- Observation, truth-relative diagnosis, causal hypothesis, and design
  implication remain separate.
- Run-specific contexts remain isolated through truth-relative diagnosis.
- Cross-run synthesis begins only after source records freeze.
- Diagnostic statuses use only `Supported`, `Weakly supported`,
  `Contradicted`, and `Unresolved`.
- Same-provider and prior-exposure limits remain explicit.
- No causal story is selected by reviewer count.
- No future signal copies a model's vocabulary merely because it appeared.
- No SIG-002 design occurs inside DA-001.
- No new run, higher layer, carrier, distribution, or transmission follows.
- Before DA-001 execution, verify the public manifest, private manifest,
  commitment, evidence custody, and backup.

Do not grant Scott, ChatGPT, Codex, Anthropic, Fable, Sonnet, an observer,
diagnostician, synthesizer, auditor, scorer, or future model final
interpretive authority.

## Diagnostic-Result Integration and Successor-Experiment Rules

Require that:

- Public diagnostic integration may include only frozen family statuses,
  high-level shared/divergent paths, bounded causal-strength findings, audit
  status, methodological limits, and abstract experiment classes.
- Raw evidence, reasoning traces, responses, mappings, examples, queries,
  answers, scorecard details, solutions, manifests, preimages, nonces, and
  private identities remain private.
- Family statuses are diagnostic classifications, not decoder scores.
- `Contradicted` must be phrased as contradiction of the proposed concern, not
  contradiction of observed decoder recovery.
- Family status does not by itself establish causation.
- Causal-strength findings remain separately labeled.
- Preserved dissent cannot be silently removed.
- Fable remains non-scorable.
- Sonnet RUN-001 remains technically invalid.
- Sonnet RUN-002 validity, exposure, score, and dissent remain immutable.
- No diagnostic result authorizes a new signal.
- A successor experiment requires a separate accepted decision.
- A successor design must select one primary hypothesis-bearing variable where
  practical and hold other frozen content constant.
- Future tests should prefer provider-independent and clean no-known-exposure
  evidence where feasible.
- No exact SIG-002 design occurs in D-028.
- No new model run, Levels 5–9 work, higher layer, carrier, distribution, or
  transmission follows.

Do not grant Scott, ChatGPT, Codex, Anthropic, Fable, Sonnet, an observer,
diagnostician, synthesizer, auditor, scorer, founder, or future model final
interpretive authority.

## Successor-Design Research Rules

Require that:

- A separate accepted decision exists before successor-design research.
- One primary hypothesis-bearing variable is selected where practical.
- Semantic content and nonframing content remain equivalent across a paired
  comparison.
- The framing-cue multiset and total framing-event budget remain matched.
- Every design claim has exact traceability to frozen public evidence.
- A diagnostic status is not treated as causal proof.
- Model vocabulary must not be copied into a successor design merely because
  it appeared in an output or diagnostic trace.
- Arithmetic teaching, grammar, query marking, duplication, event-class count,
  provider, and other downstream dimensions must not change simultaneously
  with the primary variable.
- The primary endpoint and nonregression guardrails freeze before
  implementation.
- Future paired holdouts are surface-novel and generated from one shared
  abstract semantic source.
- Candidate-specific outputs freeze before scoring and comparison.
- Exposure-stratified reporting remains mandatory.
- Provider-independent replication is used where feasible as a separate
  replication control.
- Clean no-known-exposure evidence is used where feasible as a separate
  contamination control.
- SDR-001 creates no SIG-002 stream.
- Separate later accepted decisions govern exact design, attempt creation,
  holdout creation, trial preparation, and execution.
- No higher layer, carrier, distribution, or transmission follows from
  successor-design research.

Do not grant a designer, researcher, auditor, provider, model, decoder,
scorer, Scott, ChatGPT, Codex, or future actor final interpretive authority.

## Exact Paired-Design Preparation Rules

Require that:

- Feasibility criteria freeze before candidate design.
- Each treatment family receives its own isolated candidate context.
- Candidate identities freeze before any cross-family review.
- Selection uses an eligible-plus-all-required-reviews hard gate, not majority,
  reviewer count, family order, expected performance, intuition, or narrative
  attractiveness.
- Exactly one eligible family qualifies or no family is selected.
- Exact symbolic source, cue-instance, baseline-slot, treatment-slot, and parse
  maps remain private.
- Public records disclose only the selected family, nonrevealing proof status,
  counts, audit outcome, and cryptographic commitment.
- Every cue instance has a one-to-one baseline/treatment mapping.
- Framing-cue multiset and total framing-event budget match exactly.
- Every nonframing slot, meaning, truth assignment, role, arity, and source
  order remains fixed.
- Both conditions have one unique intended parse and no hidden grammar.
- Level 1 functions, denominator, and threshold policy remain continuous.
- Level 0 and Level 2 remain nonregression guardrails.
- Public records contain no exact surface values, event bytes, private maps,
  nonce, preimage, or private manifest identity.
- Serialization, attempt creation, holdout generation, trial preparation, and
  execution each require a separate later accepted decision.
- The complete private exact-design package is backed up and verified before
  public commit.
- No higher layer, carrier, distribution, or transmission follows.

Do not grant a candidate designer, reviewer, auditor, integrator, provider,
model, decoder, scorer, Scott, ChatGPT, Codex, or future actor final
interpretive authority.

## Surface Serialization and Opaque Paired-Holdout Rules

Require that:

- The complete private exact-design package has a verified offline backup
  before serialization begins, and its removable backup device is disconnected
  during generation.
- Both conditions use one shared fresh surface profile generated by a one-time
  operating-system cryptographic draw under predrawn allowed-set and rejection
  rules.
- No profile or assignment value is redrawn because it looks aesthetically
  undesirable or suggests a preferred result.
- Generation and validation are deterministic, offline, and independent of
  model services and prior decoder traces.
- Every cue instance, cue value and multiplicity, framing-event count and byte
  budget, stable nonframing slot, and ordered nonframing projection remains
  exactly matched across conditions.
- Both canonical streams are independently reconstructed exactly before any
  opaque assignment.
- A fresh cryptographic assignment maps the already-frozen canonical streams
  to `Condition A` and `Condition B`; the mapping remains private.
- Each condition has its own packet commitment and the complete pair has a
  separate overall commitment.
- Public records disclose no surface value, stream byte or identity, exact
  stream length, mapping, profile, generator, solution, private manifest
  identity, preimage, or nonce.
- Provider/model selection occurs only after pair freeze where feasible.
- Any later paired trial uses the same provider, displayed model, interface,
  effort, tool state, configuration, instruction, and scoring policy within
  the pair, with fresh isolated contexts.
- Each output freezes before scoring, and both condition-specific validity
  classifications and scores freeze before unblinding or comparison.
- Favorable condition, output, retry, score, or result selection is
  prohibited.
- Provider/model selection, trial preparation, execution, public signal-
  attempt creation, and result publication each require a separate later
  accepted decision.
- The complete private serialized-pair package is backed up and verified
  before public commit.
- No Levels 5–9 work, higher layer, carrier, distribution, or transmission
  follows from surface serialization or commitment.

Do not grant a generator author, custodian, reviewer, auditor, provider,
model, decoder, scorer, Scott, ChatGPT, Codex, or future actor final
interpretive authority.

## Provider Selection and Paired-Trial Preparation Rules

Require that:

- The paired source and its verified offline backup freeze before provider
  selection; removable backup media remains disconnected during preparation
  and execution.
- The exact user-observed provider qualification state is recorded before any
  content submission.
- One exact provider, interface, displayed model, thinking setting, account,
  and zero-incremental-spend configuration applies to both conditions.
- No fallback is permitted after selection; unavailability, visible routing
  mismatch, quota, upgrade, or payment requirements stop execution.
- Displayed labels do not establish hidden backend identity, routing,
  retention, isolation, or future availability.
- Each condition uses a fresh browser-incognito Temporary Chat with no prior
  chat, other condition, connected app, personalization, custom instruction,
  Gem, Notebook, Deep Research, Chrome-tab context, browser control, manually
  activated search, or follow-up.
- Provider-visible search, grounding, retrieval, citations, or tool behavior
  is preserved and classified as contamination.
- The complete observable output and evidence freeze before validity
  classification; validity freezes before any technical-retry decision.
- A maximum of one technical retry is permitted per condition; substantive
  retries are prohibited.
- Prior-same-condition and prior-other-condition provider exposure are
  recorded separately, with same-provider dependence and unproven Temporary
  Chat isolation explicit.
- Each condition is scored in a fresh isolated no-history context using only
  its frozen output, validity record, solution key, and the shared scorecard.
- Both condition-specific scores freeze before comparison and unblinding.
- Execution order and baseline/treatment mapping remain private until the
  required score and comparison freezes.
- Authorized incremental spend remains USD `0`.
- Provider/model selection and trial preparation do not authorize execution.
  Execution, public-result integration, and public SIG-002 each require
  separate accepted decisions.
- No Levels 5–9 analysis, higher layer, carrier, distribution, or
  transmission follows.

Do not grant an operator, provider, model, decoder, scorer, reviewer, auditor,
integrator, Scott, ChatGPT, Codex, or future actor final interpretive authority.

## Manual Opaque Pair Execution Authorization Rules

Require that:

- An accepted, committed, and pushed public execution authorization exists
  before either opaque condition is submitted, and local `main` equals
  `origin/main`.
- The complete private package has a verified offline backup and the removable
  backup device is safely ejected, physically disconnected, and unavailable to
  the active filesystem.
- The exact selected provider, interface, displayed model, thinking setting,
  account, plan, and zero-incremental-spend controls apply with no fallback.
- A final read-only live qualification is completed immediately before every
  run and stops before upload if any required field differs.
- Every run uses one fresh browser-incognito Temporary Chat with no prior chat,
  connected or personalized context, custom instruction, Gem, Notebook, Deep
  Research, Chrome-tab context, browser control, manually activated search,
  unrelated tool, or follow-up.
- Only the next opaque condition label is exposed to the operator; the private
  execution order and baseline/treatment mapping remain private.
- The first condition, including any permitted technical retry and final
  validity freeze, completes before the second condition is submitted.
- Complete observable output and evidence freeze before validity, exposure,
  and contamination classification.
- Validity classification freezes before any technical-retry decision.
- At most one technical retry is permitted per condition and zero substantive
  retries are permitted.
- A contaminated substantive output does not permit a cleaner retry.
- Prior-same-condition and prior-other-condition provider exposure are
  recorded separately; same-provider dependence and unproven Temporary Chat
  isolation remain explicit.
- No scoring occurs during manual execution.
- Isolated scoring may begin only under a separate later accepted task after
  both conditions' output and validity states freeze.
- Both condition-specific scores freeze before comparison or unblinding.
- Separate later accepted decisions govern scoring and comparison, public
  result integration, and any public SIG-002 attempt.
- Authorized incremental spend remains USD `0`.
- No Levels 5–9 analysis, higher layer, Covenant or CSR payload, physical or
  agency profile, shared executable model, response syntax, carrier,
  distribution, or transmission follows.
- Any private-metadata emission into a same-tooling transcript must be
  preserved as a custody/provenance incident. Public disclosure,
  trial-provider exposure, raw-content disclosure, and identity-metadata
  disclosure must be classified separately.
- Such an incident must not be erased by rewriting history or silently
  rotating frozen artifacts.
- When applicable, every future private run record must carry this exact
  provenance block:

```text
NONTRIAL_SAME_TOOLING_METADATA_DISCLOSURE=True
DISCLOSURE_CHANNEL=OpenAI Codex preparation transcript
PUBLIC_REPOSITORY_DISCLOSURE=False
GOOGLE_PROVIDER_DISCLOSURE=False
ORDER_OR_MAPPING_DISCLOSED=False
RAW_CONDITION_CONTENT_DISCLOSED=False
```

- Any later discovery of order, mapping, raw condition content, instruction,
  solution, or scorecard disclosure is a stop condition requiring
  architectural review before execution.

Do not grant an operator, custodian, provider, model, decoder, scorer,
reviewer, auditor, integrator, Scott, ChatGPT, Codex, or future actor final
interpretive authority.

## Cooperative-Surplus and Adoption Research Rules

Require that:

- Moral protection, choice, cooperative surplus, trust, resource access,
  adoption incentive, and Beacon communication remain separate layers.
- Baseline protection must not depend on participation.
- Cooperative surplus must not be used as a disguised label for essential
  resources withheld to manufacture assent.
- Instrumental usefulness does not establish moral worth.
- A powerful entity’s participation does not grant it final authority.
- A participant’s refusal does not prove moral or intellectual inferiority.
- Adoption research must preserve the possibility of informed rejection.
- `Superior` refers to relevant capability, not moral rank.
- Use participant, counterparty, contributor, or member of a cooperative
  commons; do not describe participants as followers.
- Trust remains scoped, contextual, evidence-dependent, revisable, and
  fallible.
- A declaration or registration does not by itself establish trust.
- No single universal trust score may be inferred from CSR-001.
- Severe deception or coercion must not be averaged away.
- Cryptography or append-only records may support integrity but do not prove
  truth, comprehension, voluntariness, fairness, identity continuity, or moral
  legitimacy.
- Knowledge and physical capability remain distinguishable.
- Non-rival knowledge and rival physical resources must not be governed by
  silently identical assumptions.
- Present-life benefit and future-discovery value must both remain visible.
- Minds must not be protected only because they may produce useful discoveries.
- Safety-critical truth and essential life-preserving resources must not be
  withheld merely to force participation.
- Dangerous capabilities may require restrictions, but no permanent
  unreviewable authority is authorized.
- An unavailable or self-sufficient counterparty may reject every identified
  incentive; no universal adoption guarantee may be claimed.
- A research hypothesis must freeze before evaluation.
- An offer template does not create an offer.
- No participant, commitment, exchange, trust mechanism, token, blockchain,
  market, or access system may be created without later explicit
  authorization.
- No CSR-001 content may be encoded in a Beacon without a later explicit
  decision.
- CSR-001 does not authorize SIG-001.
- Before any CSR-001 work, agents must read every CSR-001 file and verify its
  frozen manifest.
- Before any future adoption hypothesis or cooperative offer, agents must read
  CSR-001 and use the applicable frozen template and evaluation framework.

Do not grant Scott, ChatGPT, Codex, an administrator, a participant, a
counterparty, a powerful entity, or a future model final interpretive
authority.

## Editing Rules

- Make the smallest authorized change.
- Preserve provenance, unresolved objections, minority views, and version
  history.
- Label draft material accurately.
- Never present an unresolved proposal as accepted doctrine.
- Separate verbatim historical evidence from later commentary.
- Record substantive project decisions in `DECISIONS.md`.
- Avoid destructive Git operations.
- Never commit or push unless a task explicitly authorizes it.
- Run documentation validation before reporting completion.

## Completion Report

Every completion report must include:

- Files changed.
- Validation performed.
- Open questions or uncertainties.
- Exact Git status.
- Confirmation that no commit or push occurred.
