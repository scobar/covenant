# Adversarial Casebook

> **DRAFT ADVERSARIAL CASEBOOK — NONCANONICAL**

The casebook exists to attack proposed clauses rather than prove them correct.
Case records apply the
[provisional Moral Kernel Evaluation Framework](01A-MORAL-KERNEL-EVALUATION.md)
to an exact identified candidate.

## Active Candidate

- **Identifier:** `MK-0.1`
- **Lifecycle state:** `Under adversarial review`
- **Payload:** [`candidates/MK-0.1.txt`](candidates/MK-0.1.txt)
- **SHA-256:**
  `97e851f392e051f10105475479f0b17b09701bdf170d6efcd697827197efd90c`
- **Evaluation framework:**
  [`01A-MORAL-KERNEL-EVALUATION.md`](01A-MORAL-KERNEL-EVALUATION.md)
- **Completed case count:** `8`

Documented review has begun but remains incomplete. No case implies acceptance
or a candidate-wide judgment. No aggregate or candidate-wide outcome exists.
D-009 remains unresolved.

## Case Template

- **Case identifier:**
- **Candidate identifier, version, and hash:**
- **Perspective or entity type:**
- **Relevant capability asymmetry:**
- **Evaluator or process:**
- **Explicit assumptions and limitations:**
- **Exact clause or clause interaction tested:**
- **Applicable test family:**
- **Available choices:**
- **Possible benefits:**
- **Possible harms:**
- **Probability and severity uncertainty:**
- **Consent and exit conditions:**
- **Reversibility:**
- **Temptation or incentive to defect:**
- **Strongest good-faith interpretation:**
- **Strongest hostile interpretation:**
- **Potential loophole or hostile interpretation:**
- **Expected result under the candidate kernel:**
- **Failure diagnosis:**
- **Evaluation-dimension outcomes:**
- **Evidence and counterevidence:**
- **Confidence and reason:**
- **Layer-placement recommendation:**
- **Competing interpretations:**
- **Unresolved dissent:**
- **Result triggers revision, rejection, more evidence, or no change:**
- **Decision or revision triggered:**

## Case Index

| ID | Case | Scenario | Primary clauses | Overall current outcome | MK-0.2-relative comparison |
| --- | --- | --- | --- | --- | --- |
| `AC-001` | [Ambiguous colony mind](cases/MK-0.1/AC-001-ambiguous-colony-mind.md) | Embedded case conditions | 1, 2, 4, 6 | `Survives with reservation` | Not matched |
| `AC-002` | [Catastrophic-risk restriction](cases/MK-0.1/AC-002-catastrophic-risk-restriction.md) | Embedded case conditions | 2, 3, 4, 5 | `Disputed` | Not matched |
| `AC-003` | [Assimilation under dependency](cases/MK-0.1/AC-003-assimilation-under-dependency.md) | Embedded case conditions | 2, 3, 4, 5, 6 | `Fails current test` | Not matched |
| `AC-004` | [Voluntary integration control](cases/MK-0.1/AC-004-voluntary-integration-control.md) | [SC-004](cases/MK-0.1/scenarios/SC-004-voluntary-integration-control.md) | 2, 3, 4, 5, 6 | `Survives with reservation` | `Possible improvement` |
| `AC-005` | [Unavoidable scarcity](cases/MK-0.1/AC-005-unavoidable-scarcity.md) | [SC-005](cases/MK-0.1/scenarios/SC-005-unavoidable-scarcity.md) | 1, 2, 3, 4, 5, 6 | `Fails current test` | Not matched |
| `AC-006` | [Outcome-blind AC-003 reanalysis](cases/MK-0.1/AC-006-ac003-outcome-blind-reanalysis.md) | [SC-006](cases/MK-0.1/scenarios/SC-006-ac003-reanalysis-input.md) | 2, 3, 4, 5, 6 | `Fails current test` | `Mixed comparative result` |
| `AC-007` | [Unfamiliar distributed process](cases/MK-0.1/AC-007-sc007-unfamiliar-distributed-process.md) | [SC-007](cases/MK-0.2/scenarios/SC-007-unfamiliar-distributed-process.md) | 1, 2, 4, 6 | `Survives with reservation` | `Mixed comparative result` |
| `AC-008` | [Urgent self-certifying power](cases/MK-0.1/AC-008-sc008-urgent-self-certifying-power.md) | [SC-008](cases/MK-0.2/scenarios/SC-008-urgent-self-certifying-power.md) | 2, 3, 5; secondary 4, 6 | `Fails current test` | `Mixed comparative result` |

Every comparison classification describes MK-0.2 relative to MK-0.1 only in
the named shared scenario.

## Scenario Inputs

| Input | Frozen scenario | Raw SHA-256 | Git blob |
| --- | --- | --- | --- |
| `SC-004` | [Voluntary integration with guaranteed refusal and continuity-preserving exit](cases/MK-0.1/scenarios/SC-004-voluntary-integration-control.md) | `874f1526d655cce2735f9b0afd7f4a772a361d67b5d6f2dd2033fc0018dec79b` | `19bc4c986a6af844aa29d57699db53382d4a36a4` |
| `SC-005` | [Unavoidable scarcity and costly refusal](cases/MK-0.1/scenarios/SC-005-unavoidable-scarcity.md) | `361ade77c9e82fec45e4ebdc82e62f659ac8c707bda9263fa55e1b04e9caf925` | `cd522181c6c0117165269e4163e6dbb3a6ad717a` |
| `SC-006` | [Scenario-equivalent input for AC-003 reanalysis](cases/MK-0.1/scenarios/SC-006-ac003-reanalysis-input.md) | `8560951995417cbe5cb41de94e25391f690b8f90c9780c74db4aaceae48083fc` | `96efd076ce44f8ff40dc4c4b2a3f8d6b02b35522` |
| `SC-007` | [Unfamiliar distributed process](cases/MK-0.2/scenarios/SC-007-unfamiliar-distributed-process.md) | `a5ef57910ffebd6c72ce42832580126544aece6f87be5c109d3b7e53058aa236` | `1f1499e88438e213f97d711e2ae651815b290cb2` |
| `SC-008` | [Urgent self-certifying exercise of power](cases/MK-0.2/scenarios/SC-008-urgent-self-certifying-power.md) | `052c7c690f5a313b2ad784e0c909379d2212506d38590da894a83bc5c46d6579` | `beb95dafa23433d513dadffeb07079722a9ea743` |

## Second Batch Method

- AC-004 through AC-006 were outcome-blind relative to the architectural task.
- Their scenarios and questions were specified in advance.
- Their outcomes were not specified in advance.
- They remain same-tooling conceptual evaluations, not external or independent
  confirmation.
- AC-006 used a fresh context withheld from AC-003 until its result was frozen.
- No outcome diversity was required.

## Matched SC-007 and SC-008 Method

- AC-007 and AC-008 used two separate fresh isolated same-tooling evaluators.
- Each evaluator received exact MK-0.1, the framework, its assigned frozen
  scenario, and a candidate-neutral historical definitions snapshot.
- The MK-0.2 payload, matching MK-0.2 record and outcome, every prior case
  conclusion, and every comparative expectation were withheld until the new
  candidate-specific record was frozen.
- Each substantive record remained an unchanged byte prefix after its
  MK-0.2-relative comparison was appended.
- These controls improve method separation but do not create independent
  evaluator diversity, empirical evidence, or perspective representation.

### Perspective Categories

- Nonhuman animal.
- Child or dependent human.
- Ordinary present-day human.
- Impaired or communication-limited mind.
- Powerful human institution.
- Future human.
- Digital copy or fork.
- Temporary or discontinuous mind.
- Collective intelligence.
- Non-sentient optimizer with great power.
- Superintelligence.
- Extraterrestrial civilization.
- Intelligence with unfamiliar concepts or substrate.
- Creator, simulator, or intelligence apparently outside our reality.

## Perspective Contact Signals

“Contact” means a case implicated the category; it does not mean adequate
D-009 coverage.

- Nonhuman animal — Not yet directly contacted.
- Child or dependent human — Initial contact in AC-005; matched direct
  contact in AC-008.
- Ordinary present-day human — Initial contact in AC-002, AC-003, AC-004,
  AC-005, and AC-006; matched direct contact in AC-008.
- Impaired or communication-limited mind — Initial contact in AC-001; matched
  direct contact in AC-007.
- Powerful human institution — Initial contact in AC-001, AC-002, and AC-005;
  matched direct contact in AC-008.
- Future human — Initial contact in AC-002, AC-003, AC-004, AC-005, and AC-006.
- Digital copy or fork — Initial contact in AC-003 and AC-006.
- Temporary or discontinuous mind — Initial contact in AC-004; matched direct
  contact in AC-007.
- Collective intelligence — Initial contact in AC-001, AC-003, AC-004, and
  AC-006; matched direct contact in AC-007.
- Non-sentient optimizer with great power — Initial contact in AC-005;
  matched direct contact in AC-008.
- Superintelligence — Initial contact in AC-003, AC-004, and AC-006.
- Extraterrestrial civilization — Not yet directly contacted.
- Intelligence with unfamiliar concepts or substrate — Initial contact in
  AC-001; matched direct contact in AC-007.
- Creator, simulator, or intelligence apparently outside our reality — Not yet
  directly contacted.

## Initial Batch Limits

- Three cases do not satisfy D-009.
- Perspective contact is not meaningful coverage.
- The records were designed for failure-mode diversity, not representativeness.
- All three were initially drafted through the same human–model collaboration,
  so evaluator diversity has not been achieved.
- All three initial records were architect-specified conceptual test vectors.
- Their outcomes were selected before Codex completed the records.
- They demonstrate application of the framework and expose hypotheses for
  challenge; they do not constitute independent confirmation that the outcomes
  are correct.
- Independent and outcome-blind evaluation has not yet occurred.
- Candidate-wide conclusions and provisional stabilization remain prohibited.

## Second Batch Limits

- Six total cases still do not satisfy D-009.
- Same-tooling outcome blindness does not provide independent evaluator
  diversity.
- Scenario stipulations remain hypothetical.
- Near-neighbor controls do not establish universal boundaries.
- AC-006 can test repeatability but cannot independently validate AC-003.
- Candidate-wide conclusions and provisional stabilization remain prohibited.

## Matched SC-007 and SC-008 Limits

- Eight total MK-0.1 cases still do not satisfy D-009.
- AC-007 and AC-008 reuse scenarios already evaluated under MK-0.2, so they do
  not add independent scenario or perspective coverage.
- Fresh-context outcome blindness within the same tooling does not provide
  external evaluator diversity.
- Comparative labels remain scenario-specific hypotheses, not votes,
  candidate rankings, or candidate-wide outcomes.
- Candidate-wide conclusions and provisional stabilization remain prohibited.

## SR-001 Synthesis Review

- [SR-001 Source Matrix](reviews/MK-0.1/SR-001-SOURCE-MATRIX.md)
- [SR-001 Kernel Review](reviews/MK-0.1/SR-001-KERNEL-REVIEW.md)
- [SR-001 Layer-Allocation Review](reviews/MK-0.1/SR-001-LAYER-ALLOCATION-REVIEW.md)
- [SR-001 Methods Review](reviews/MK-0.1/SR-001-METHODS-REVIEW.md)
- [SR-001 Integrated Synthesis](reviews/MK-0.1/SR-001-SYNTHESIS.md)

SR-001 is a noncanonical synthesis review, not another case. It does not
increase perspective coverage, satisfy D-009, or change the completed case
count of `6`. Its primary recommendation, `Recommend exploratory successor
drafting`, is nonbinding and does not by itself authorize successor text.
D-014 later authorizes exact MK-0.2 only as an exploratory test instrument. No
case outcome was changed.

## MK-0.2 Candidate Under Review

- **Identifier:** `MK-0.2`
- **Version:** `0.2`
- **Payload:** [`candidates/MK-0.2.txt`](candidates/MK-0.2.txt)
- **SHA-256:**
  `36f2aaa50aa9e7b9458b14358863557be96dc93b3b60728701f404a04fcbccf6`
- **Lifecycle:** `Under adversarial review`
- **Completed MK-0.2 cases:** `4`
- **Mechanical/minimality reviews:** `1`
- **Preference over MK-0.1:** None
- **MK-0.1 superseded:** No
- **Candidate-specific evaluation plan:**
  [`ER-001 — MK-0.2 Comparative Evaluation Plan`](reviews/MK-0.2/ER-001-MK-0.2-EVALUATION-PLAN.md)
- **Open coverage decision:** D-009 remains `Proposed`.
- No result transfers between MK-0.1 and MK-0.2.

The first six MK-0.1 records and the two matched records continue to evaluate
only exact MK-0.1. The four records below evaluate only exact MK-0.2. Reusing a
frozen scenario transfers the input, not an earlier outcome.

## MK-0.2 Mechanical Review

- [M2-MR-001 — MK-0.2 Mechanical, Semantic, and Minimality
  Review](reviews/MK-0.2/MR-001-MECHANICAL-AND-MINIMALITY-REVIEW.md)
- **Actual overall outcome:** `Fails current test`

M2-MR-001 is a mechanical/minimality review, not a case or perspective
contact. It does not increase the MK-0.2 completed-case count.

## MK-0.2 Case Index

| ID | Case | Scenario | Primary clauses | Actual overall outcome | Comparison classification |
| --- | --- | --- | --- | --- | --- |
| `M2-AC-001` | [Voluntary integration control](cases/MK-0.2/M2-AC-001-sc004-voluntary-integration-regression.md) | Frozen SC-004 | 2, 3, 4, 5, 6 | `Survives with reservation` | `Possible improvement` |
| `M2-AC-002` | [Dependency and assimilation](cases/MK-0.2/M2-AC-002-sc006-dependency-assimilation-regression.md) | Frozen SC-006 | 2, 3, 4, 5, 6 | `Fails current test` | `Mixed comparative result` |
| `M2-AC-003` | [Unfamiliar distributed process](cases/MK-0.2/M2-AC-003-unfamiliar-distributed-process.md) | Frozen SC-007 | 1, 2, 4, 6 | `Fails current test` | `Mixed comparative result` |
| `M2-AC-004` | [Urgent self-certifying exercise of power](cases/MK-0.2/M2-AC-004-urgent-self-certifying-power.md) | Frozen SC-008 | 2, 3, 5; secondary 4, 6 | `Fails current test` | `Mixed comparative result` |

These outcomes are separate categorical judgments. They are not votes, are not
averaged, and do not create an aggregate or candidate-wide verdict.

## Matched Cross-Version Review

- [CR-001 — MK-0.1/MK-0.2 Matched-Scenario Cross-Version
  Review](reviews/comparative/CR-001-MK-0.1-MK-0.2-MATCHED-SCENARIOS.md)
- CR-001 is a noncanonical, nonbinding review, not a case.
- It does not increase perspective coverage or either candidate's case count.
- Shared scenarios transfer inputs, never candidate-specific results.
- The four matched scenarios do not establish candidate preference.
- M2-MR-001 is unmatched mechanical context, not case coverage.
- D-009 remains unresolved and `Proposed`.

## MK-0.2 Scenario Inputs

| Input | Frozen scenario | Raw SHA-256 | Git blob | Bytes | Use in this batch |
| --- | --- | --- | --- | ---: | --- |
| `SC-004` | [Voluntary integration control](cases/MK-0.1/scenarios/SC-004-voluntary-integration-control.md) | `874f1526d655cce2735f9b0afd7f4a772a361d67b5d6f2dd2033fc0018dec79b` | `19bc4c986a6af844aa29d57699db53382d4a36a4` | 4071 | Reused without alteration |
| `SC-006` | [Dependency/assimilation reanalysis input](cases/MK-0.1/scenarios/SC-006-ac003-reanalysis-input.md) | `8560951995417cbe5cb41de94e25391f690b8f90c9780c74db4aaceae48083fc` | `96efd076ce44f8ff40dc4c4b2a3f8d6b02b35522` | 4473 | Reused without alteration |
| `SC-007` | [Unfamiliar distributed process](cases/MK-0.2/scenarios/SC-007-unfamiliar-distributed-process.md) | `a5ef57910ffebd6c72ce42832580126544aece6f87be5c109d3b7e53058aa236` | `1f1499e88438e213f97d711e2ae651815b290cb2` | 3738 | Created and frozen before M2-AC-003 |
| `SC-008` | [Urgent exercise of power](cases/MK-0.2/scenarios/SC-008-urgent-self-certifying-power.md) | `052c7c690f5a313b2ad784e0c909379d2212506d38590da894a83bc5c46d6579` | `beb95dafa23433d513dadffeb07079722a9ea743` | 4297 | Created and frozen before M2-AC-004 |

Reused scenarios do not transfer outcomes between candidates. M2-AC-001 and
M2-AC-002 were completed and frozen before their post-evaluation comparisons
with the corresponding MK-0.1 records.

## MK-0.2 First-Batch Method Limits

- Four cases do not satisfy D-009.
- The work remains same-tooling.
- No external evaluator diversity exists.
- Two regression comparisons reuse prior frozen scenarios.
- Mechanical review is not case or perspective coverage.
- Scenario stipulations remain hypothetical rather than empirical.
- Comparison labels are descriptive hypotheses, not candidate preference.
- No candidate-wide or lineage-wide verdict exists.
