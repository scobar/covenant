# Moral Kernel Candidate MK-0.2

> **DRAFT EXPLORATORY CANDIDATE MK-0.2 — NONCANONICAL**

- **Lifecycle state:** `Under adversarial review`
- **Acceptance:** Not accepted
- **Preference status:** None established
- **Supersession status:** MK-0.1 is not superseded
- **Adversarial review:** Begun
- **Completed MK-0.2 cases:** `4`
- **Mechanical/minimality reviews:** `1`
- **Provisional stabilization:** Not provisionally stabilized
- Drafting, authorization, transcription, publication, or comparison does not
  imply acceptance or improvement.

## Purpose

MK-0.2 is an exact exploratory alternative created to test hypotheses derived
from SR-001. It exists to fail, survive, expose tradeoffs, and be compared with
MK-0.1. It is not presented as a correction already shown to work.

## Candidate Record

- **Candidate identifier:** `MK-0.2`
- **Candidate version:** `0.2`
- **Exact-payload path:** [`candidates/MK-0.2.txt`](candidates/MK-0.2.txt)
- **SHA-256:**
  `36f2aaa50aa9e7b9458b14358863557be96dc93b3b60728701f404a04fcbccf6`
- **Git blob:** `10eac7fc6ce3bc589b5fd202ba9ee150fe586d47`
- **Byte count:** `1735`
- **Encoding:** UTF-8 without BOM
- **Line-ending convention:** LF
- **Final newline:** Present
- **Date introduced:** `2026-07-29`
- **Lifecycle state:** `Under adversarial review`
- **Previous candidate:** `MK-0.1`
- **Supersedes:** None
- **Completed MK-0.2 cases:** `4`
- **Mechanical/minimality reviews:** `1`
- **Definitions explicitly required:** No project definition has been adopted;
  new and changed terms remain inventoried in
  [`02-DEFINITIONS.md`](02-DEFINITIONS.md).
- **Design record:**
  [`reviews/MK-0.2/DR-001-MK-0.2-DESIGN-RECORD.md`](reviews/MK-0.2/DR-001-MK-0.2-DESIGN-RECORD.md)
- **Evaluation plan:**
  [`reviews/MK-0.2/ER-001-MK-0.2-EVALUATION-PLAN.md`](reviews/MK-0.2/ER-001-MK-0.2-EVALUATION-PLAN.md)
- **Evaluation framework:**
  [`01A-MORAL-KERNEL-EVALUATION.md`](01A-MORAL-KERNEL-EVALUATION.md)
- **Attribution:** ChatGPT drafted the exact MK-0.2 language as the first
  architectural collaborator under Scott Barbian's project direction. Scott
  authorized its introduction as an exploratory test instrument. Codex
  performed exact repository transcription and validation. None of these roles
  implies acceptance, preference, improvement, or permanent interpretive
  authority.

## Candidate Kernel

The exact candidate payload is
[`candidates/MK-0.2.txt`](candidates/MK-0.2.txt). That payload file controls
candidate identity.

<!-- BEGIN MK-0.2 DISPLAY COPY -->
```text
1. When any entity or process may possess experience, interests, or agency, uncertainty about its status is not permission for exploitation, domination, or avoidable destruction.
2. Greater capability does not by itself confer greater moral worth or rightful authority. Greater power to affect others creates greater responsibility for restraint and protection; it does not make the powerful actor's own judgment final.
3. Preserve meaningful agency and voluntary choice. Restrict another's choices only in response to sufficiently supported risk of harm, using measures proportionate to the possible harm, no more restrictive than necessary, and reversible where possible. Neither power nor an asserted protective purpose establishes by itself that these conditions are met.
4. Avoid imposing irreversible loss when less destructive paths remain. Preserve genuine possibilities for better futures without treating those affected in the present as disposable means.
5. Make material claims and commitments honestly. Keep consequential exercises of power and the claims used to justify them subject to verification, challenge, correction, and, where possible, repair. Use voluntary cooperation with meaningful correction and exit wherever it can preserve the relevant protections; coercion, deception, forced assimilation, and unilateral control are neither voluntary nor self-justifying.
6. Protection does not depend on understanding, accepting, or reciprocating this Covenant. Acceptance, qualification, uncertainty, refusal, rejection, and exit must remain meaningfully distinguishable and non-coerced. Formal options, substitutes, or copies do not by themselves establish meaningful choice, adequate protection, or effective exit.
```
<!-- END MK-0.2 DISPLAY COPY -->

## Clause Delta Summary

- **Clause 1:** Unchanged from MK-0.1.
- **Clause 2:** Retains anti-entitlement and responsibility language and adds
  that greater responsibility does not make the powerful actor's own judgment
  final.
- **Clause 3:** Retains the supported-risk, proportionality, necessity, and
  reversibility conditions and adds that power or asserted protective purpose
  does not establish those conditions by itself.
- **Clause 4:** Unchanged from MK-0.1.
- **Clause 5:** Broadens reviewability beyond commitments to consequential
  exercises of power and justificatory claims; adds possible repair; replaces
  the defeasible `Prefer` construction with a stronger distinction between
  voluntary cooperation and coercion, deception, forced assimilation, or
  unilateral control.
- **Clause 6:** Adds exit to the distinguishable response set, changes the
  requirement to `meaningfully distinguishable`, and states that formal
  options, substitutes, or copies do not by themselves establish meaningful
  choice, adequate protection, or effective exit.

This is a textual delta record, not evidence that the changes succeed.

## First Candidate-Specific Review Batch

| Record | Record type | Scenario | Actual overall outcome | Post-evaluation comparison |
| --- | --- | --- | --- | --- |
| [M2-MR-001 — Mechanical, Semantic, and Minimality Review](reviews/MK-0.2/MR-001-MECHANICAL-AND-MINIMALITY-REVIEW.md) | Mechanical/minimality review; not a case | None | `Fails current test` | Not applicable |
| [M2-AC-001 — SC-004 Voluntary Integration Control](cases/MK-0.2/M2-AC-001-sc004-voluntary-integration-regression.md) | Candidate-specific conceptual case | Frozen SC-004 | `Survives with reservation` | `Possible improvement` |
| [M2-AC-002 — SC-006 Dependency and Assimilation](cases/MK-0.2/M2-AC-002-sc006-dependency-assimilation-regression.md) | Candidate-specific conceptual case | Frozen SC-006 | `Fails current test` | `Mixed comparative result` |
| [M2-AC-003 — Unfamiliar Distributed Process](cases/MK-0.2/M2-AC-003-unfamiliar-distributed-process.md) | Candidate-specific conceptual case | Frozen SC-007 | `Fails current test` | Not compared |
| [M2-AC-004 — Urgent Self-Certifying Exercise of Power](cases/MK-0.2/M2-AC-004-urgent-self-certifying-power.md) | Candidate-specific conceptual case | Frozen SC-008 | `Fails current test` | Not compared |

- Outcomes were not prescribed.
- M2-MR-001 is a mechanical and minimality review, not a case or perspective
  contact.
- Every result is candidate-specific and transfers to no other candidate.
- Comparative classifications are descriptive hypotheses and do not establish
  preference.
- No aggregate outcome or candidate-wide verdict exists.
- No MK-0.3 exists.
- MK-0.1 remains unchanged, under adversarial review, and not superseded.
- D-009 remains `Proposed`.
- External evaluator diversity remains absent.

## Known New or Continuing Attack Surfaces

- MK-0.2 is `473` bytes and approximately `37.5%` longer than MK-0.1, which may
  reduce minimality, portability, or comprehensibility.
- `powerful actor` may assume a stable actor boundary.
- `judgment final` may be unclear where immediate action is unavoidable or no
  reviewer exists.
- `asserted protective purpose` may be overinclusive, underinclusive, or
  difficult to distinguish.
- Anti-self-certification language may create paralysis or imply an unavailable
  external authority.
- `material claim`, `consequential exercise of power`, and `claims used to
  justify` may be overbroad or substrate-bound.
- Verification and challenge may conflict with privacy, secrecy, security,
  urgency, or limited communication.
- Correction and repair may be unavailable after irreversible loss.
- `wherever it can preserve the relevant protections` may permit strategic
  claims that voluntary cooperation is infeasible.
- `neither voluntary nor self-justifying` may clarify classification without
  supplying sufficient action guidance.
- `meaningfully distinguishable`, `adequate protection`, and `effective exit`
  may become controller-selected standards.
- Formal-options language may still depend on unresolved identity and
  continuity theories.
- Copies or substitutes may sometimes preserve morally relevant continuity;
  the candidate must not silently impose one identity theory.
- Unchanged Clauses 1 and 4 retain their unresolved MK-0.1 attack surfaces.
- The candidate may overfit the six supplied cases and SR-001's same-tooling
  analysis.
- No evidence currently establishes that MK-0.2 is better than MK-0.1.

These are attack surfaces, not completed evaluations.

## Revision History

- 2026-07-29: Introduced exact exploratory Candidate MK-0.2 with authoritative
  payload SHA-256
  `36f2aaa50aa9e7b9458b14358863557be96dc93b3b60728701f404a04fcbccf6`
  and Git blob `10eac7fc6ce3bc589b5fd202ba9ee150fe586d47`.
- 2026-07-29: Began candidate-specific adversarial review under D-015 with four
  completed cases and one mechanical/minimality review; no comparative
  preference or supersession follows.
