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
