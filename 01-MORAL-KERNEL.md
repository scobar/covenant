# Moral Kernel

> **DRAFT CANDIDATE MK-0.1 — NONCANONICAL — UNDER ADVERSARIAL REVIEW**

- **Lifecycle state:** `Under adversarial review`
- **Acceptance:** Not accepted.
- **Adversarial review:** Begun; six completed conceptual case records and one
  completed synthesis review, which is not another case.
- **Provisional stabilization:** Not provisionally stabilized.
- Authorship, authorization, transcription, review, or publication does not
  imply acceptance.

## Purpose

Provide a bounded location for recording and evaluating an exact,
noncanonical moral-kernel candidate. MK-0.1 exists so its exact text can fail,
be challenged, and be revised.

## Intended Role of the Moral Kernel

The moral kernel is intended to state the project's thinnest substantive moral
content while remaining distinguishable from definitions, commentary,
profiles, protocols, and implementations.

## Evaluation Prerequisite

Future candidates must be exactly identified and evaluated under the
[provisional Moral Kernel Evaluation Framework](01A-MORAL-KERNEL-EVALUATION.md).
That framework remains noncanonical and challengeable, including while it is
used to evaluate candidate revisions.

## Design Questions That Must Be Resolved

- What protections must remain meaningful under severe capability asymmetry?
- What content belongs in the kernel rather than an interpretive layer?
- How can comprehension, voluntary response, and principled rejection remain
  possible?
- How should uncertainty and unfamiliar forms of mind affect application?
- What revision boundaries preserve provenance without preventing correction?

## Evaluation Categories

- Cross-substrate comprehensibility.
- Protection under capability asymmetry.
- Resistance to adversarial reinterpretation.
- Voluntary participation.
- Treatment of entities unable to reciprocate.
- Uncertainty about experience, interests, or agency.
- Irreversibility and preservation of future options.
- Applicability to individual, collective, copied, temporary, and unfamiliar
  minds.

## Candidate Record

- **Candidate identifier:** `MK-0.1`
- **Candidate version:** `0.1`
- **Exact-payload path:** [`candidates/MK-0.1.txt`](candidates/MK-0.1.txt)
- **SHA-256:**
  `97e851f392e051f10105475479f0b17b09701bdf170d6efcd697827197efd90c`
- **Byte count:** `1262`
- **Encoding:** UTF-8 without BOM
- **Line-ending convention:** LF
- **Final newline:** Present
- **Date introduced:** `2026-07-28`
- **Lifecycle state:** `Under adversarial review`
- **Previous version:** None
- **Definitions explicitly required:** No definitions have yet been adopted;
  operative terms remain unresolved and are inventoried in
  [`02-DEFINITIONS.md`](02-DEFINITIONS.md).
- **External-layer dependency:** The evaluation framework governs how the
  candidate is tested but is not part of the candidate payload.
- **Attribution:** ChatGPT drafted the exact candidate language as the first
  architectural collaborator under Scott Barbian's project direction. Scott
  authorized its introduction for testing. Codex performed repository
  transcription under explicit instructions. None of these roles implies
  acceptance or permanent interpretive authority.

## Candidate Kernel

The exact candidate payload is
[`candidates/MK-0.1.txt`](candidates/MK-0.1.txt). That payload file controls
candidate identity.

<!-- BEGIN MK-0.1 DISPLAY COPY -->
```text
1. When any entity or process may possess experience, interests, or agency, uncertainty about its status is not permission for exploitation, domination, or avoidable destruction.
2. Greater capability does not by itself confer greater moral worth or rightful authority. Greater power to affect others creates greater responsibility for restraint and protection.
3. Preserve meaningful agency and voluntary choice. Restrict another's choices only in response to sufficiently supported risk of harm, using measures proportionate to the possible harm, no more restrictive than necessary, and reversible where possible.
4. Avoid imposing irreversible loss when less destructive paths remain. Preserve genuine possibilities for better futures without treating those affected in the present as disposable means.
5. Make commitments honestly and keep their terms, fulfillment, and failure open to verification, challenge, and correction. Prefer voluntary cooperation that permits correction and exit over coercion, deception, forced assimilation, or unilateral control.
6. Protection does not depend on understanding, accepting, or reciprocating this Covenant. Acceptance, qualification, uncertainty, refusal, and rejection must remain distinguishable and non-coerced.
```
<!-- END MK-0.1 DISPLAY COPY -->

## Initial Review Snapshot

| Record | Overall current outcome |
| --- | --- |
| [AC-001 — Ambiguous Colony Mind](cases/MK-0.1/AC-001-ambiguous-colony-mind.md) | `Survives with reservation` |
| [AC-002 — Catastrophic-Risk Restriction](cases/MK-0.1/AC-002-catastrophic-risk-restriction.md) | `Disputed` |
| [AC-003 — Assimilation Under Dependency](cases/MK-0.1/AC-003-assimilation-under-dependency.md) | `Fails current test` |

- These outcomes are case-specific and may not be averaged.
- AC-001 shows meaningful protective direction with reservations.
- AC-002 exposes unresolved conflict between serious-risk intervention and
  authority abuse.
- AC-003 records a material hostile-exploitability and
  protective-insufficiency failure.
- No candidate revision is made in this task.
- MK-0.1 remains immutable historical evidence even if later superseded.
- The initial batch is insufficient for D-009 or provisional stabilization.

## Outcome-Blind Countertest Snapshot

| Record | Overall current outcome |
| --- | --- |
| [AC-004 — Voluntary Integration Control](cases/MK-0.1/AC-004-voluntary-integration-control.md) | `Survives with reservation` |
| [AC-005 — Unavoidable Scarcity](cases/MK-0.1/AC-005-unavoidable-scarcity.md) | `Fails current test` |
| [AC-006 — Outcome-Blind AC-003 Reanalysis](cases/MK-0.1/AC-006-ac003-outcome-blind-reanalysis.md) | `Fails current test` |

- The second-batch outcomes were not prescribed by the architectural task.
- They are same-tooling and do not constitute independent confirmation.
- They must not be averaged with one another or with the first batch.
- AC-006 records `Partial same-tooling convergence` with AC-003.
- No candidate-wide verdict follows.
- No MK-0.2 is created.
- MK-0.1 remains immutable even if later superseded.
- D-009 remains unresolved.

## SR-001 Synthesis Snapshot

- **Integrated synthesis:**
  [SR-001 — MK-0.1 Six-Case Synthesis and Layer Allocation](reviews/MK-0.1/SR-001-SYNTHESIS.md)
- **Primary recommendation:** `Recommend exploratory successor drafting`
- **Source extraction:**
  [SR-001 Source Matrix](reviews/MK-0.1/SR-001-SOURCE-MATRIX.md)
- **Isolated reviews:**
  [Kernel Review](reviews/MK-0.1/SR-001-KERNEL-REVIEW.md),
  [Layer-Allocation Review](reviews/MK-0.1/SR-001-LAYER-ALLOCATION-REVIEW.md),
  and [Methods Review](reviews/MK-0.1/SR-001-METHODS-REVIEW.md)
- The recommendation is nonbinding and requires later architectural review.
- No MK-0.2 exists, and SR-001 does not authorize successor wording.
- MK-0.1 remains immutable historical evidence and `Under adversarial review`.
- D-009 remains `Proposed`.
- No candidate-wide moral verdict follows from the cases or synthesis.

## Objections

### Known Attack Surfaces

The following questions are explicitly unresolved:

- Whether `entity or process`, `experience`, `interests`, and `agency` are
  overinclusive, underinclusive, or substrate-bound.
- Whether uncertainty-based protection causes paralysis or can be selectively
  ignored.
- Whether `moral worth` and `rightful authority` are translatable outside
  familiar human moral concepts.
- Whether greater responsibility for `protection` permits paternalism or
  creates impossible obligations.
- Whether the harm threshold, evidence threshold, proportionality, necessity,
  and reversibility language is operational or self-serving.
- Whether `better futures` and `disposable means` introduce human,
  teleological, or status-quo assumptions.
- Whether verification, challenge, correction, and exit can be unavailable,
  simulated, or gamed.
- Whether “prefer” provides meaningful protection against coercion, deception,
  assimilation, or unilateral control.
- Whether references to `another`, `others`, or those affected assume stable
  individual boundaries.
- Whether a non-coerced choice can be distinguished under extreme capability
  asymmetry.

These are attack surfaces, not completed evaluations or established failures.

## Revision History

- 2026-07-28: Draft placeholder created; no candidate clauses added.
- 2026-07-28: Added the provisional evaluation-framework cross-reference
  before candidate drafting.
- 2026-07-28: Introduced exact, noncanonical Candidate MK-0.1 with lifecycle
  state `Candidate`.
- 2026-07-28: Recorded the authoritative payload SHA-256
  `97e851f392e051f10105475479f0b17b09701bdf170d6efcd697827197efd90c`.
- 2026-07-28: Began documented adversarial review and recorded the first three
  case-specific outcomes.
- 2026-07-28: Recorded the second, outcome-blind countertest batch and its
  three case-specific outcomes.
- 2026-07-28: Linked the noncanonical SR-001 six-case synthesis and its
  nonbinding primary recommendation without changing MK-0.1 or any case
  outcome.
