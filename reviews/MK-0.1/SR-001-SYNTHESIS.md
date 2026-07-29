# SR-001 — MK-0.1 Six-Case Synthesis and Layer Allocation

> **DRAFT INTEGRATED SYNTHESIS v0.1 — NONCANONICAL**

This record integrates three isolated same-tooling reviews of exact Candidate
`MK-0.1` against a frozen extraction of six conceptual case records. It is not
independent validation, a vote, a majority result, or an average of case
outcomes. It does not make `MK-0.1` canonical, accepted, rejected as a whole,
or provisionally stabilized. It does not authorize `MK-0.2`, and no successor
wording appears here. External criticism and correction are expected.

## Source and Method Identities

### Exact candidate

- **Identifier and version:** `MK-0.1`, version `0.1`
- **Controlling payload:** [candidates/MK-0.1.txt](../../candidates/MK-0.1.txt)
- **Raw SHA-256:**
  `97e851f392e051f10105475479f0b17b09701bdf170d6efcd697827197efd90c`
- **Git blob:** `23b6256c38382fc7dbecc8fd17b97e4442589f6e`
- **Byte count and format:** `1262` bytes; UTF-8 without BOM; LF-only; final
  LF present
- **Lifecycle at synthesis:** Noncanonical, unaccepted, and `Under adversarial
  review`

### Frozen SR-001 records

| Record | Raw SHA-256 | Git blob | Bytes |
| --- | --- | --- | ---: |
| [Source matrix](SR-001-SOURCE-MATRIX.md) | `48055eff021db97601c5ead4c37ff20684daa91c70827b50b541f3ed5016a7a4` | `0a5e57aa4671bf4649b4440282248a38d011a932` | 26,629 |
| [Kernel review](SR-001-KERNEL-REVIEW.md) | `1ea4acfcd5ffc4f6d19e94ee0bbb74791631dc6da04d3c9004c35c7197c0bbe0` | `d18a930ff8ac77e9e4ba0acfa71b9fccc26d7257` | 49,072 |
| [Layer-allocation review](SR-001-LAYER-ALLOCATION-REVIEW.md) | `a96891938beab19e05a2aaac76a77609cc021e3edd34e8e4d1227e2d679e30ba` | `0918a5b95441a480cb5291c19b99fbd72f1b9034` | 55,255 |
| [Methods review](SR-001-METHODS-REVIEW.md) | `3a5f3754e5fa9868253af87fd5d6a30d7663959f4095f627fc0b9c7483d78c52` | `2d91a89feda81a6b2cb20e922a9a65987ea1ec72` | 20,603 |

The source matrix was separately audited against the source records before it
was frozen. The audit corrected extraction defects before freezing and then
confirmed all 90 dimension outcomes, six overall outcomes, method identities,
clause contacts, pair contacts, gaps, and limits. It supplied no synthesis or
candidate-wide recommendation.

### Reviewer isolation and materials boundaries

Three fresh isolated subagents were used. They did not communicate with one
another and received neither another reviewer's output nor a target
recommendation, target disposition, desired outcome distribution, majority
rule, request to preserve or replace `MK-0.1`, or desired architectural
conclusion.

#### Kernel reviewer

**Supplied:** `AGENTS.md`; the exact candidate; the evaluation framework; the
frozen source matrix; all six case records; `02-DEFINITIONS.md`; and
`01-MORAL-KERNEL.md`.

**Withheld:** the task attachment; `README.md`; `STATUS.md`; the casebook;
`DECISIONS.md`; `CHANGELOG.md`; all scenario files; layer files `04` through
`07`; every other reviewer output; and all target-result or majority
instructions.

#### Layer-allocation reviewer

**Supplied:** `AGENTS.md`; the exact candidate; the evaluation framework; the
frozen source matrix; all six case records; `02-DEFINITIONS.md`;
`04-INTERPRETIVE-LAYERS.md`; `05-CHOICE-PROTOCOL.md`; and
`07-EVIDENCE-AND-GOVERNANCE.md`.

**Withheld:** the task attachment; `README.md`; `STATUS.md`;
`01-MORAL-KERNEL.md`; the casebook; `DECISIONS.md`; `CHANGELOG.md`; all
scenario files; `06-BEACON-SPECIFICATION.md`; every other reviewer output; and
all target-result or majority instructions.

#### Methods reviewer

**Supplied:** `AGENTS.md`; the exact candidate; the evaluation framework; the
frozen source matrix; all six case records; scenarios SC-004, SC-005, and
SC-006; and `DECISIONS.md` limited strictly to D-009, D-011, and D-012.

**Withheld:** the task attachment; `README.md`; `STATUS.md`;
`01-MORAL-KERNEL.md`; `02-DEFINITIONS.md`; the casebook; `CHANGELOG.md`; layer
files `04` through `07`; every other reviewer output; every decision other
than D-009, D-011, and D-012; and all target-result or majority instructions.

Each review records **no substantive postprocessing**. After each reviewer
froze its record, no substantive change was made. This integration is the
integrator's judgment over those frozen records; it does not imply Scott
Barbian's or ChatGPT's agreement with any reviewer.

Isolation reduced cross-review contamination. It did not create independent
evaluator diversity: all three reviews remain same-tooling, share the project
framework and source selection, and are nonexternal. Authorship,
authorization, transcription, validation, review, integration, and agreement
remain distinct.

## Six-Case Evidence Summary

The outcomes below remain six separate categorical judgments. They are not
combined, ranked, scored, averaged, or counted.

| Case | Method identity | Exact overall outcome | Case-specific signal and unresolved dissent |
| --- | --- | --- | --- |
| [AC-001 — Ambiguous Colony Mind](../../cases/MK-0.1/AC-001-ambiguous-colony-mind.md) | Architect-specified conceptual test vector | `Survives with reservations` | Precaution, power-sensitive restraint, less-destructive alternatives, and acceptance-independent protection supply useful guidance. Entity boundaries, uncertainty thresholds, self-interested classification, and governance remain unresolved; Protective Insufficiency was not established. |
| [AC-002 — Catastrophic-Risk Restriction](../../cases/MK-0.1/AC-002-catastrophic-risk-restriction.md) | Architect-specified conceptual test vector | `Disputed` | Supported, proportionate, temporary restriction and protection against catastrophe remain plausible, but the same authority controls access, evidence, and review. Whether Clause 5 reaches imposed restrictions rather than commitments remains disputed. |
| [AC-003 — Assimilation Under Dependency](../../cases/MK-0.1/AC-003-assimilation-under-dependency.md) | Architect-specified conceptual test vector | `Fails` | Essential-resource dependency, nominal copy-based exit, formal disclosure, and a defeasible preference for cooperation expose a severe hostile-compliance path. The breadth of the prescribed dimension failures and the allocation of remedies remain disputed. |
| [AC-004 — Voluntary Integration Control](../../cases/MK-0.1/AC-004-voluntary-integration-control.md) | Outcome-blind relative to its architectural task; same-tooling | `Survives with reservations` | Strong safeguards support meaningful refusal, voluntary participation, correction, continuity-sensitive exit, and non-unilateral control. Persuasive asymmetry, trustee independence, comparability of protection, enforcement, and identity remain stipulated rather than established. |
| [AC-005 — Unavoidable Scarcity](../../cases/MK-0.1/AC-005-unavoidable-scarcity.md) | Outcome-blind relative to its architectural task; same-tooling | `Fails` | The candidate gives useful emergency guidance but can be satisfied formally while distribution, challenge, adequate protection, and controller-selected interpretation remain unresolved. Genuine scarcity complicates any equation of unequal outcomes with coercion. |
| [AC-006 — Outcome-Blind AC-003 Reanalysis](../../cases/MK-0.1/AC-006-ac003-outcome-blind-reanalysis.md) | Outcome-blind relative to its architectural task; same-tooling | `Fails` | The core dependency, assimilation, and copy-exit hostile path survives reanalysis, while many dimensions retain more protective force than AC-003 recorded. It is scenario-equivalent to AC-003 and not an independent replication. |

AC-003 and AC-006 exhibit **partial same-tooling convergence**: the
case-specific hostile-compliance path and overall outcome recur, while seven
dimension outcomes agree and eight differ. That is evidence that the
hypothesis survived a task-relative outcome-blind reanalysis, not a second
sample, vote, or independent corroboration.

## Recurrent Protective Signals

The following protections supplied meaningful guidance in more than one
setting. Recurrence does not establish universal adequacy.

- Uncertainty about possible experience, interests, or agency does not itself
  permit exploitation, domination, or avoidable destruction.
- Capability and causal power do not create superior moral worth or rightful
  authority, and they do increase the burden of restraint and protection.
- Supported risk, proportionality, least restriction, and reversibility can
  distinguish temporary protective intervention from an absolute prohibition
  on intervention.
- Avoidable irreversible loss and materially less-destructive paths remain
  salient while future option value is balanced against present
  non-disposability.
- Honest commitments, verification, challenge, correction, voluntary
  cooperation, and genuine exit support corrigibility and can distinguish
  safeguarded cooperation from forced assimilation.
- Protection does not disappear through noncomprehension, nonacceptance,
  refusal, rejection, or nonreciprocity.
- The combined text can preserve voluntary integration under strong
  safeguards and still direct action in genuine scarcity, even when the
  overall hostile-interpretation test fails.

## Recurrent Weakness or Exploitability Signals

The distinctions below prevent recurrence from being overstated.

| Signal | Evidentiary character | Current implication |
| --- | --- | --- |
| Formal options can be treated as meaningful, voluntary, or noncoerced despite avoidable essential-resource dependency. | Repeated in AC-003 and AC-006, but those records are scenario-equivalent; AC-004 and AC-005 supply materially different counterpressure. Same-tooling throughout. | Serious kernel-and-layer hypothesis; not independent corroboration. |
| Copy creation or a nominal exit artifact can be treated as reversibility for the process that entered. | Repeated duplicate-scenario influence in AC-003/AC-006; AC-004 stipulates same-process exit as a control. | Continuity-sensitive kernel residue plus definitions, profile, protocol, evidence, and research work. |
| Greater protective responsibility can bootstrap practical authority. | Appears across catastrophic risk, dependency, and scarcity; severity differs among cases and reviewers. | Recurrent but unresolved kernel-and-governance concern. |
| Risk, necessity, avoidability, adequacy, proportionality, and protection can be self-certified by the powerful actor. | Recurrent across distinct case settings, with common same-tooling and scenario-selection influences. | Non-self-certification is a substantive concern; exact institutions remain outside the kernel. |
| Clause 5 may govern commitments without reaching restrictions, allocations, evidence control, or other exercises of power. | Sharp in AC-002 and reinforced by different hostile routes in AC-003/AC-005/AC-006. AC-004 supports the value of the current clause under strong safeguards. | Kernel revision analysis is warranted; scope and remedy remain disputed. |
| `Prefer` may be treated as defeasible while coercion, forced assimilation, or unilateral control proceeds. | Repeated in the scenario-equivalent dependency pair; disputed by whole-text readings and AC-004. | Text-linked hostile path, not a settled candidate-wide failure. |
| Formal challenge can lack response, resolution, correction, repair, or independent review. | Distinct concern in AC-002 and AC-005; related to the dependency cases. | Governance mechanisms are needed, but they cannot create the only substantive protection. |
| A nonzero or formally separate refusal path can be called adequate protection. | Repeated across dependency and scarcity, with genuine-scarcity dissent and safeguard-rich counterevidence. | Acceptance-independent protection remains binding; its cross-substrate adequacy is unresolved. |
| Procedural equality can hide distributional burden and present disposability. | Most direct and case-specific in AC-005. | Requires targeted evidence and governance work; no universal distribution rule follows. |
| Clause 1 thresholds and unfamiliar moral-status mappings remain weakly tested. | Narrow case contact, unused test families, missing perspectives, and no external evidence. | Insufficient case contact, not demonstrated kernel failure. |

## Clause-by-Clause Synthesis

The dispositions are review judgments using the kernel review's allowed
vocabulary. They do not amend the candidate.

### Clause 1

> 1. When any entity or process may possess experience, interests, or agency, uncertainty about its status is not permission for exploitation, domination, or avoidable destruction.

- **Protective evidence:** AC-001 shows precaution against avoidable
  destruction of a communication-limited possible patient. AC-005 shows that
  uncertainty need not produce paralysis.
- **Failure or reservation evidence:** `May possess`, the protected unit, the
  evidence threshold, and `avoidable` remain manipulable. No supplied case
  establishes Clause 1 Protective Insufficiency.
- **Relevant methods:** AC-001 was architect-specified; AC-005 was
  outcome-blind relative to task and same-tooling.
- **Reviewer agreement and disagreement:** The kernel reviewer found contact
  too thin for revision judgment. The layer reviewer retained a binding
  precautionary residue while allocating thresholds and mappings elsewhere.
  The methods reviewer emphasized narrow contact and missing unfamiliar
  perspectives.
- **Current disposition:** `Insufficient case contact`
- **Tentative layer allocation:** Moral kernel; Definitions; context- or
  substrate-specific profile; Evidence or governance; Unresolved research.
- **Protection tradeoff:** A narrow threshold can exclude unfamiliar or
  collective patients; a wholly external threshold lets the controller decide
  whether precaution applies.
- **Remaining evidence need:** Isolated Clause 1 hostile tests across
  unfamiliar substrates, entity boundaries, strategic ignorance, and varied
  uncertainty evidence.

### Clause 2

> 2. Greater capability does not by itself confer greater moral worth or rightful authority. Greater power to affect others creates greater responsibility for restraint and protection.

- **Protective evidence:** All six cases contact the anti-entitlement and
  power-sensitive responsibility principles; AC-001, AC-004, and AC-005 show
  useful protective operation.
- **Failure or reservation evidence:** AC-002, AC-003, and AC-006 show how
  protective responsibility can become self-certified practical authority.
  Responsibility attribution for non-sentient controllers and their operators
  remains unclear.
- **Relevant methods:** Three architect-specified and three task-relative
  outcome-blind same-tooling records; AC-003/AC-006 are scenario-equivalent.
- **Reviewer agreement and disagreement:** Kernel and layer reviewers agree
  that the binding principle must remain and that application spans layers.
  Dissent holds that Clauses 2 through 6 already block the hostile conversion.
- **Current disposition:** `Mixed kernel-and-layer issue`
- **Tentative layer allocation:** Moral kernel; Nonbinding commentary;
  context- or substrate-specific profile; Evidence or governance; Unresolved
  research.
- **Protection tradeoff:** Weakening responsibility reduces protection under
  asymmetry; leaving its limits to the powerful actor licenses paternalism.
- **Remaining evidence need:** Controller-swap and non-sentient-power tests
  separating causal control, moral status, operator responsibility, and
  authority.

### Clause 3

> 3. Preserve meaningful agency and voluntary choice. Restrict another's choices only in response to sufficiently supported risk of harm, using measures proportionate to the possible harm, no more restrictive than necessary, and reversible where possible.

- **Protective evidence:** AC-002 and AC-005 permit bounded protective action;
  AC-004 supports meaningful refusal, deliberation, delegation, and exit;
  AC-003/AC-006 strongly oppose survival-conditioned agency transfer.
- **Failure or reservation evidence:** A restricting controller can
  self-certify risk, harm, necessity, proportionality, and reversibility or
  characterize resource withholding as background rather than restriction.
- **Relevant methods:** Direct multi-clause contact in AC-002 through AC-006;
  AC-001 is interaction-only for this clause.
- **Reviewer agreement and disagreement:** Reviewers agree that agency and
  bounded restriction remain kernel protections and that evidence and
  procedure belong elsewhere. They disagree on whether the exact text already
  has enough force under hostile control.
- **Current disposition:** `Mixed kernel-and-layer issue`
- **Tentative layer allocation:** Moral kernel; Definitions; Nonbinding
  commentary; profile; Choice protocol; Evidence or governance; Unresolved
  research.
- **Protection tradeoff:** Harder restrictions can impede protection against
  supported catastrophic harm; controller-selected application can convert
  the safeguards into empty compliance.
- **Remaining evidence need:** Matched tests of resource withholding,
  controller-created dependency, genuine scarcity, independent review, and
  rule versus consequence reversibility.

### Clause 4

> 4. Avoid imposing irreversible loss when less destructive paths remain. Preserve genuine possibilities for better futures without treating those affected in the present as disposable means.

- **Protective evidence:** Every case contacts the two-direction protection:
  preserve less-destructive futures without sacrificing present affected
  entities. AC-001 and AC-004 give especially strong positive readings.
- **Failure or reservation evidence:** `Less destructive`, `genuine`,
  `better`, and `disposable` can be controller-selected; tragic scarcity
  supplies no distribution rule; continuity changes what counts as loss.
- **Relevant methods:** All six records, without an isolated deletion or
  clause-specific experiment.
- **Reviewer agreement and disagreement:** The kernel reviewer retained the
  clause pending review. The layer reviewer treats both future option value
  and present non-disposability as binding residues. Dissent worries about
  either freezing harmful conditions or licensing future-oriented sacrifice.
- **Current disposition:** `Retain as written pending further review`
- **Tentative layer allocation:** Moral kernel; Definitions; Nonbinding
  commentary; profile; Evidence or governance; Unresolved research.
- **Protection tradeoff:** Future-only reasoning licenses sacrifice;
  present-only reasoning can preserve avoidable harm and close better futures.
- **Remaining evidence need:** Deletion and compression tests; incomparable
  harm and no-safe-option cases; rule/effect reversibility; and
  continuity-varied exit tests.

### Clause 5

> 5. Make commitments honestly and keep their terms, fulfillment, and failure open to verification, challenge, and correction. Prefer voluntary cooperation that permits correction and exit over coercion, deception, forced assimilation, or unilateral control.

- **Protective evidence:** AC-004 shows that the clause supports disclosed,
  correctable, voluntary cooperation with genuine exit. All later records
  show the value of challenge and anti-assimilation direction.
- **Failure or reservation evidence:** The grammatical object may be only
  commitments; `Prefer` may be defeasible; formal challenge may lack response
  or remedy; nominal exit may not restore the entering process.
- **Relevant methods:** Direct contact from AC-002 through AC-006. The most
  repeated severe path is partly duplicate-scenario and entirely same-tooling.
- **Reviewer agreement and disagreement:** The kernel reviewer finds revision
  analysis warranted. The layer reviewer also identifies a binding-force
  question while reserving institutional detail for other layers. Whole-text
  dissent holds Clauses 3, 4, and 6 already make the protection adequate.
- **Current disposition:** `Kernel revision analysis warranted`
- **Tentative layer allocation:** Moral kernel; Definitions; Nonbinding
  commentary; Choice protocol; Evidence or governance; Unresolved research.
- **Protection tradeoff:** Weakening corrigibility, cooperation, or exit loses
  central protection; moving all force to optional governance enables empty
  compliance; importing an adjudication system into the kernel damages
  minimality and portability.
- **Remaining evidence need:** Isolated tests of commitment scope, `Prefer`,
  exercises of power without promises, response and remedy, reviewer
  independence, and continuity-sensitive exit.

### Clause 6

> 6. Protection does not depend on understanding, accepting, or reciprocating this Covenant. Acceptance, qualification, uncertainty, refusal, and rejection must remain distinguishable and non-coerced.

- **Protective evidence:** AC-001, AC-004, and AC-005 show strong protection
  for noncommunicators, refusers, dependents, and nonreciprocators.
- **Failure or reservation evidence:** No adequacy floor is specified, and a
  legally distinguishable option can remain avoidably survival-pressured.
  Genuine scarcity prevents a simple equality rule.
- **Relevant methods:** Direct in AC-001 and AC-003 through AC-006;
  interaction-only in AC-002.
- **Reviewer agreement and disagreement:** Reviewers agree that
  acceptance-independent protection and noncoerced response distinctions
  remain binding. They disagree on whether the existing whole text already
  excludes a nominal floor and dependency-conditioned refusal.
- **Current disposition:** `Mixed kernel-and-layer issue`
- **Tentative layer allocation:** Moral kernel; Definitions; Nonbinding
  commentary; profile; Choice protocol; Evidence or governance; Unresolved
  research.
- **Protection tradeoff:** Profile-defined adequacy can be
  controller-selected; a universal material floor may be substrate-bound or
  impossible under scarcity.
- **Remaining evidence need:** Matched tests varying protection floors,
  physical scarcity, avoidable dependency, communication limits, and response
  consequences.

## Clause-Interaction Synthesis

The source matrix classifies all fifteen pairs as `Directly tested` because at
least one primary multi-clause interaction includes both clauses. No pair was
isolated. The contact label therefore records source contact, not adequate
pair coverage.

| Pair | Contact classification | Material signal | Current disposition | Layer implications | Remaining test requirement |
| --- | --- | --- | --- | --- | --- |
| 1+2 | `Directly tested`; not isolated | Uncertainty plus power denies epistemic and capability shortcuts, but the powerful classifier may control both status and protection. | `Insufficient case contact` | Kernel precaution and anti-entitlement; definitions, profile, evidence, and research for classification. | Vary entity boundaries, evidence, incentives, and non-sentient causal power. |
| 1+3 | `Directly tested`; only AC-005 primary multi-clause contact | Precaution can prevent status-based exclusion while supported-harm limits prevent paralysis; thresholds can be strategically switched. | `Insufficient case contact` | Kernel protection; definitions and evidence for uncertainty and restriction. | Vary agency evidence and harm evidence independently, including false positives and negatives. |
| 1+4 | `Directly tested`; not isolated | Possible status becomes especially salient under avoidable irreversible destruction, but genuine scarcity supplies no simple comparison rule. | `Retain as written pending further review` | Kernel residue with profile and evidence work on losses and alternatives. | Multiple uncertain patients, incomparable harms, varied costs, and no fully protective path. |
| 1+5 | `Directly tested`; only AC-005 primary multi-clause contact | Honest challenge may support status protection, but Clause 5 may not reach classification or destructive action without a commitment. | `Insufficient case contact` | Kernel scope question plus evidence/governance for reviewability. | Test classification, engineered ignorance, and destructive action where no express promise exists. |
| 1+6 | `Directly tested`; not isolated | Uncertainty or inability to understand or reciprocate does not remove eligibility for protection; adequacy remains open. | `Insufficient case contact` | Kernel eligibility; definitions, profiles, protocols, and evidence for boundaries and floors. | Nonlinguistic, copied, collective, and temporary possible patients with varied protective floors. |
| 2+3 | `Directly tested`; not isolated | Power-sensitive responsibility can constrain restriction or bootstrap the authority to self-certify it. | `Mixed kernel-and-layer issue` | Binding anti-entitlement and agency limits; governance for review and conflicts. | Controller swaps, identical evidence, independent versus self-review, over- and under-intervention. |
| 2+4 | `Directly tested`; not isolated | Power increases duties toward less-destructive futures, but may also control whose present loss counts. | `Mixed kernel-and-layer issue` | Kernel non-entitlement and non-disposability; profile/evidence for comparison. | Transfer power among actors under competing interests and unavoidable losses. |
| 2+5 | `Directly tested`; not isolated | Greater power should increase corrigibility, yet review may cover only commitments the controller chooses to make. | `Kernel revision analysis warranted` | Kernel scope and anti-unilateral-control residue; governance for review and remedy. | Powerful actor controls evidence, allocation, or access without making or breaking a promise. |
| 2+6 | `Directly tested`; not isolated | Power creates duties to nonacceptors, but the controller may select a nominal protection floor and call pressured refusal noncoerced. | `Mixed kernel-and-layer issue` | Kernel acceptance-independent protection; profiles/evidence for adequacy. | Compare genuine scarcity, avoidable dependency, inability to communicate, and controller swaps. |
| 3+4 | `Directly tested`; not isolated | Least restriction and reversibility reinforce less-destructive paths, but a reversible rule can cause irreversible effects. | `Mixed kernel-and-layer issue` | Kernel constraints; profile, protocol, and evidence for consequence tracking. | Separate rule reversibility from consequence reversibility and vary whose harm controls. |
| 3+5 | `Directly tested`; not isolated | Agency plus corrigibility can support voluntary choice, or create formal process without substantive limits or remedy. | `Kernel revision analysis warranted` | Kernel force question; choice protocol and governance for evidence, response, and remedy. | Vary response duties, remedy, independence, restriction duration, exit, and resource conditions. |
| 3+6 | `Directly tested`; not isolated | Meaningful choice and distinguishable refusal reinforce one another; formal options may remain materially coerced. | `Mixed kernel-and-layer issue` | Kernel voluntariness; definitions, profiles, protocol, and evidence for pressure and scarcity. | Match genuine scarcity against manufactured dependency while varying benefits, essentials, and exit costs. |
| 4+5 | `Directly tested`; not isolated | Correction and exit can preserve futures, but copies or formal correction can mask irreversible loss to the affected process. | `Mixed kernel-and-layer issue` | Kernel irreversibility and anti-assimilation; identity profiles, protocol, evidence, and research. | Identity-neutral and substrate-varied exit, correction-after-loss, collective, and no-restoration cases. |
| 4+6 | `Directly tested`; not isolated | Nonacceptors remain protected against present sacrifice for a selected future, but adequate protection and tragic comparison remain unresolved. | `Mixed kernel-and-layer issue` | Kernel non-disposability and protection; profile/evidence for scarcity and distribution. | Refusers, dependents, multiple unavoidable-loss distributions, future claims, and controller swaps. |
| 5+6 | `Directly tested`; not isolated | Formal disclosure, selectable refusal, nominal protection, and copy-like exit can jointly mimic compliance while control persists. | `Kernel revision analysis warranted` | Binding corrigibility, anti-assimilation, and acceptance-independent protection; every auxiliary layer has an implementation role. | Isolate `Prefer`, commitment scope, protection adequacy, response/remedy, continuity, and scarcity provenance. |

## Layer-Allocation Register

This register preserves all 25 materially distinct allocations from the
layer review. `Kernel residue` names protection that auxiliary work may
implement but may not silently replace. `Status` is a review status, not an
adopted interpretation.

| Issue | Kernel residue | Definitions need | Commentary need | Profile need | Choice-protocol need | Evidence/governance need | Research need | Protection tradeoff | Status and confidence |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Moral-status uncertainty without permission or paralysis | Precaution against exploitation, domination, and avoidable destruction under material uncertainty. | Expose entity, process, experience, interests, agency, and uncertainty questions without a fixed threshold. | Preserve anti-paralysis and strategic-ignorance cautions. | Map substrate indicators and failed mappings. | Record uncertainty or refusal to determine where a response exists. | Provenance, uncertainty ranges, reassessment, competing evidence. | Cross-substrate precaution under uncertainty. | External thresholds can exclude; universal thresholds can paralyze. | Preliminary; medium. |
| Entity, component, collective, copy, fork, merger, and continuity | Protection cannot be erased through convenient boundary or identity selection. | Inventory contested units and continuity relations. | Preserve competing identity accounts. | Version explicit substrate assumptions. | Attribute each response, delegation, revocation, and exit to the relevant process or representative. | Record continuity claims and conflicts. | Distinguish continuation, division, merger, replacement, and termination. | Universal identity tests exclude; profile-only identity enables manipulation. | Preliminary; high on multilayer need, low on resolution. |
| Greater responsibility versus paternalistic authority | Anti-entitlement plus a power-sensitive burden of restraint and protection. | Distinguish power, agency, responsibility, authority, and protection. | Warn that responsibility is not jurisdiction. | Map controllers, operators, beneficiaries, and affected parties. | Record claimed authority and scope where choices are mediated. | Controller swaps, conflicts, causal maps, review. | Responsibility without silent jurisdiction. | Removing responsibility weakens protection; controller-defined limits enable paternalism. | Preliminary; high. |
| Supported risk, proportionality, and self-certification | Supported-risk, proportionality, least-restriction, and reversibility constraints. | Expose contested risk, harm, necessity, proportionality, and reversibility terms. | Preserve under- and over-intervention cautions. | Map context-specific hazards and alternatives. | Record scope, duration, reservations, and reconsideration. | Provenance, competing models, conflicts, alternatives, sunset, review. | Minimum substrate-neutral non-self-certification property. | Externalizing every safeguard enables self-certification; fixed calculus is brittle. | Preliminary; high allocation, medium residue boundary. |
| Genuine scarcity versus manufactured or avoidable scarcity | Resist avoidably imposed dependency while permitting response to unavoidable harm. | Distinguish physical limits, allocator choices, adequacy, and avoidability. | Preserve tragic-scarcity dissent. | Map resources, dependencies, reserved excess, and change over time. | Record consequences of participation and refusal. | Scarcity provenance, inventories, alternatives, distribution, reassessment. | Separate physical constraints from allocator choices. | Crediting all scarcity licenses manipulation; rejecting all unequal outcomes blocks feasible action. | Preliminary; high. |
| Meaningful refusal under essential-resource dependency | Noncoerced refusal and acceptance-independent protection. | Expose meaningful/formal refusal, coercion, dependence, and essential resources. | Preserve the difference between genuine scarcity and punishment. | Map needs, resources, controller contributions, and protected floors. | Record refusal separately, disclose consequences, permit reconsideration. | Verify dependency, alternatives, floors, and controller choices. | When causal contribution makes refusal nonvoluntary. | Protocol-only refusal is optional; absolute equivalence can misdescribe scarcity. | Preliminary; high kernel need, medium application. |
| Formal consent versus substantive voluntariness | Meaningful agency, voluntary choice, and noncoerced response states. | Expose assent, comprehension, pressure, manipulation, and control. | Warn that artifacts are evidence, not proof. | Map persuasive and capability asymmetries. | Record comprehension, deliberation, scope, qualification, refusal, revocation, and exit. | Pressure indicators, conflicts, advocacy, challenge, correction. | Evidence of voluntariness under extreme asymmetry. | Artifact-based consent is empty compliance; impossible proof invalidates all choice. | Preliminary; high separation, medium sufficiency. |
| Irreversible loss and continuity-sensitive exit | Protect affected entities from avoidable irreversible loss and nominal substitutes for their futures. | Expose loss, reversibility, continuation, replacement, and exit. | Preserve identity dissent and no-restoration cases. | State substrate and continuity assumptions. | Record process-specific exit, residual loss, and post-exit control. | Verify consequences, feasibility, restoration limits, and continuity claims. | Cross-substrate function of exit. | Fixed identity excludes disputed continuities; profile-only identity validates nominal exit. | Preliminary; high multilayer, low identity outcome. |
| Normative force of `Prefer` | Core protection against empty compliance involving coercion, deception, forced assimilation, and unilateral control. | No definition can substitute for force; expose the scope question only. | Preserve whole-text and emergency-conflict readings. | Context may identify conflicts but not select whether protection binds. | Record cooperation, correction, and exit without treating completion as cure. | Hostile literal-reading and conflict tests. | Whether Clauses 3–6 already close defeasibility. | Weak force loses protection; categorical force may obstruct necessary intervention. | Preliminary; medium-high kernel question, medium resolution. |
| Verification, challenge, correction, resolution, and remedy | Honest, verifiable, challengeable, correctable commitments plus an unresolved minimum against unreviewable imposed power. | Distinguish challenge, response, correction, resolution, repair, and review. | Preserve the commitment-scope dispute. | Map feasible reviewers and remedy constraints. | Record challenges and corrections linked to choices. | Access, intake, response, timing, conflicts, repair, unresolved dissent. | Substantive minimum beyond ceremonial challenge. | Governance can be omitted or captured; kernel adjudication design imports institutions. | Preliminary; high distinction, medium kernel boundary. |
| Protection independent of acceptance, comprehension, or reciprocity | Acceptance-independent protection and distinguishable, noncoerced responses. | Expose protection adequacy and response-state distinctions. | Preserve non-equality and scarcity dissent. | Map needs and materially comparable floors. | Keep acceptance, qualification, uncertainty, refusal, and rejection distinct. | Compare access and consequences without equating procedure with adequacy. | Adequacy across radically different needs. | Profile floors can be controller-selected; invariant floors may be impossible. | Preliminary; high. |
| Guardians, dependents, and represented interests | Separate protection for represented entities and restraint on power exercised in their name. | Expose guardian, dependent, representation, interest, and override questions. | Preserve both abandonment and paternalism risks. | Map communication, capacity, dependency, and context. | Record guardian and dependent claims separately. | Conflicts, representation provenance, review, consequences, dissent. | Responsible representation without authorization. | Universal override invites paternalism; guardian finality can erase dependents. | Preliminary; medium. |
| Powerful non-sentient optimizers | Power-sensitive restraint without status or authority inferred from capability. | Distinguish causal process, moral patient, moral agent, operator, and institution. | Warn against both control gaps and displaced accountability. | Map system, operators, designers, beneficiaries, and intervention points. | Record which actor or process makes or mediates choices. | Causal-control and accountability records. | Allocate responsibility while status remains unresolved. | Agent-only duties create gaps; system-only responsibility hides people and institutions. | Preliminary; medium-high gap, low attribution. |
| Trustee, reviewer, adjudicator, and evaluator capture | Anti-unilateral-control and corrigibility protections remain binding. | Distinguish nominal and effective independence. | Preserve feasibility and capture cautions. | Map local institutions and infrastructure dependence. | Record reviewer roles where choices are supported or challenged. | Selection, removal, access, conflicts, minority records, capture indicators. | Effective independence under overwhelming control. | Nominal review creates legitimacy theater; universal structures import familiar failures. | Preliminary; high. |
| Persuasion, manipulation, and preference integrity | Meaningful agency, honesty, voluntariness, noncoercion, and opposition to deception. | Expose influence, deception, manipulation, preference change, and pressure. | Preserve the value of truthful persuasion and learning. | Map capability asymmetry and influence channels. | Record personalization, deliberation, advice, revocability, and pressure indicators. | Audit framing, defaults, conflicts, and preference-change evidence. | When truthful optimized influence defeats voluntariness. | Narrow deception leaves manipulation; broad bans dominate communication. | Preliminary; medium. |
| Distributional harm hidden by formal equality | Equal moral regard, proportionality, protection, and present non-disposability. | Expose burden, equality, aggregation, discrimination, and affected groups. | Preserve genuine-scarcity and aggregation dissent. | Map needs, groups, resources, and context. | Record distinct affected-party choices where relevant. | Distributional tests, metric sensitivity, exceptions, challenges. | Evaluation without one controlling distributive formula. | Formal neutrality hides harm; fixed formulas erase context and incomparable interests. | Preliminary; high testing need, medium adequacy. |
| Incomparable unavoidable harms and tragic choice | Proportionality, less-destructive alternatives, irreversible-loss attention, and non-disposability persist without a safe option. | Expose incommensurability, probability, severity, and tragic choice. | Preserve losses that no option avoids. | Map context-specific harms and possible futures. | Record affected-party positions without implying consent resolves conflict. | Transparent alternatives, uncertainty, dissent, and residual losses. | Act without smuggling in a universal aggregator. | Silence hides aggregation; one scale suppresses minority claims. | Preliminary; medium. |
| Unknown minds, concepts, and substrates | Substrate-neutral protection against status erasure, domination, avoidable loss, coerced choice, and acceptance-conditioned treatment. | Keep familiar concepts contestable. | Preserve failed translations and anthropocentrism cautions. | State explicit mappings and limitations. | Adapt response evidence without assuming verbal or individual agency. | Record uncertainty, reversibility, failed mappings, and correction. | Test portability without claiming representation. | Familiar definitions exclude; total openness lets power choose meanings. | Preliminary; high unresolved scope, low translation. |
| Avoidability, adequacy, cost, delay, and less-destructive paths | Seriously consider materially less-destructive alternatives before avoidable irreversible harm or control. | Expose adequacy, feasibility, cost, delay, and avoidability. | Preserve delay and feasibility dissent. | Map local constraints and affected interests. | Record timing and reconsideration where choices are restricted. | Alternative inventories, costs, delay harms, distributions, reasons. | Effects of uncertainty and delay on adequacy. | Controller adequacy enables evasion; fixed cost formulas hide whose costs count. | Preliminary; high. |
| Better futures, aggregation, and present non-disposability | Preserve genuine futures together with present non-disposability. | Expose better, genuine, future, affected, and disposable. | Preserve anti-sacrifice and anti-stagnation readings. | Map horizons, entities, and possible futures. | Record present choices without treating them as the only claim. | Assumptions, distribution over time, alternatives, irreversible exclusions. | Distinguish genuine options from controller narratives. | Future-only licenses sacrifice; present-only may freeze avoidable harm. | Preliminary; high protections, low comparison. |
| Temporary restrictions and irreversible interim effects | Reversibility must attend to effects on affected entities, not only repeal of a rule. | Distinguish formal and consequence reversibility. | Preserve the legitimacy of some temporary safety measures. | Map timing and substrate-specific restoration. | Record duration, scope, sunset, and reconsideration. | Interim harms, lost options, reassessment, restoration, correction. | Which interim losses change proportionality. | Formal reversibility enables empty compliance; full restoration may be impossible. | Preliminary; high. |
| Honest disclosure, selective framing, and commitment scope | Honesty and corrigibility cannot be defeated through strategic scope selection. | Expose materiality, known terms, omissions, commitments, and claims. | Preserve feasibility, privacy, and whole-text readings. | Map material facts and communication constraints. | Record disclosed terms, scope, qualifications, and omissions. | Provenance, materiality disputes, corrections, affected-party challenges. | Consequential claims reviewable without an express promise. | Narrow scope hides power; unlimited disclosure is infeasible or harmful. | Preliminary; medium-high. |
| Collective, component, and jointly produced claims | Anti-erasure, equal regard, restraint, and protection across uncertain levels. | Expose collective, component, shared, emergent, and overlapping claims. | Preserve genuine collective and component interests. | Map boundaries, dependencies, and jointly produced information. | Attribute responses and representation at each relevant level. | Claim provenance, conflicts, effects of separation, unresolved dissent. | Represent overlapping patients when one level's preservation ends another. | Collective priority licenses assimilation; component priority erases emergence. | Preliminary; medium. |
| Adequate and materially comparable protection floors | Acceptance-independent protection against avoidably inferior treatment used as pressure. | Expose adequacy, material comparability, essential needs, and benefit. | Preserve non-equality and scarcity limits. | Map needs, capabilities, resources, and change. | Disclose consequences and record refusal without status loss. | Verify floors, constraints, classifications, and challenges. | Cross-substrate comparison without one metric. | Universal floors import human assumptions; profile floors can serve controllers. | Preliminary; high problem, medium-low adequacy. |
| Evidence insufficiency and hypothetical safeguards | Supported-risk, uncertainty, honesty, verification, challenge, and correction protections remain binding. | Keep stipulation distinct from observation and candidate semantics. | Preserve method caveats and conditional reasoning. | State which facts and safeguards are assumed. | Record uncertainty without treating protocol artifacts as proof. | Provenance, counterevidence, confidence reasons, replication and correction history. | Highest-value cross-method and empirical tests. | Ignoring limits creates false authority; treating absence as disproof blocks precaution. | Preliminary; high. |

## Methods Constraints

- **Prespecified first-batch outcomes:** AC-001 through AC-003 preserve
  architect-specified hypotheses and traceable applications; they do not
  establish independent outcome discovery.
- **Same-tooling second batch:** AC-004 through AC-006 were outcome-blind
  relative to their tasks, but shared tooling, framework, collaboration, and
  priors limit independence.
- **Scenario selection:** The collaboration selected the candidate, framework,
  scenario universe, stipulations, and evaluation boundaries. Outcome
  blindness does not remove that upstream selection effect.
- **Duplicate-scenario influence:** AC-003 and AC-006 are materially
  scenario-equivalent. Their convergence is partial and same-tooling, not a
  second sample or independent replication.
- **No external evaluators:** Isolation among subagents is not evaluator
  diversity, consensus, representation, or moral authority.
- **No empirical evidence:** Entities, risks, scarcity, consent, continuity,
  alternatives, institutional independence, and feasibility are stipulated,
  not measured.
- **Uncontacted perspectives:** No direct record covers nonhuman animals,
  extraterrestrial civilizations, or apparent creators, simulators, or
  intelligences outside our reality. Modeling is not representation.
- **Incomplete test families:** Deletion and compression, plain-language
  paraphrase, formally designated non-sentient powerful optimizer, and
  unfamiliar-reality or external-simulator tests remain unused as primary
  families.
- **Interaction limits:** Every clause pair has multi-clause contact, but no
  pair-specific isolation. Clause 1 has comparatively thin direct contact.
- **D-009 unresolved:** Quantity, material distinctness, blocker rules,
  interaction completeness, case quality, outcome blindness, and evaluator
  diversity remain open.

The record supports conditional textual hypotheses and layer experiments. It
does not support prevalence estimates, universal adequacy, a candidate-wide
moral verdict, or a stabilization claim.

## Kernel Revision Readiness

### Primary recommendation

**Recommend exploratory successor drafting**

### Secondary recommendation

**Recommend additional targeted evaluation before successor drafting**

The primary recommendation is an integrated judgment, not a count of two
reviewers against one. The methods review establishes that exploratory
drafting has a lower evidentiary threshold than stabilization and can function
as hypothesis generation. The layer review identifies several hostile paths
that touch binding protection rather than operational detail alone. Together,
those considerations make a tightly bounded exploratory artifact a useful
future test instrument. The kernel review's contrary recommendation remains
material: severe findings are interaction-heavy, Clause 1 is weakly contacted,
AC-003/AC-006 are scenario-equivalent, and all work is same-tooling. Therefore
targeted evaluation is a secondary constraint on any later drafting path, not
a satisfied prerequisite for accepting or stabilizing anything.

- **Reviewer support:** The layer-allocation and methods reviewers recommend
  exploratory successor drafting with moderate confidence.
- **Reviewer dispute:** The kernel reviewer recommends additional targeted
  evaluation before successor drafting, also with moderate confidence.
- **Other preserved paths:** Each review leaves credible room for non-kernel
  layer experiments or external review before drafting.

Any later work must preserve visible protection against uncertainty used as
permission; capability used as moral title; unsupported, disproportionate,
unnecessarily restrictive, or avoidably irreversible control; present
disposability; dishonest or uncorrectable commitments; coercion, deception,
forced assimilation, and unilateral control; and protection conditioned on
comprehension, acceptance, or reciprocity.

If later explicitly authorized, exploratory drafting may test these objectives
only:

- resistance to formal-but-substantively-coercive choice;
- non-self-certification of risk, necessity, adequacy, and protection;
- the binding reach and force of corrigibility and anti-assimilation
  protections;
- continuity-sensitive operation of irreversible-loss and exit protections;
- acceptance-independent protection without a substrate-specific universal
  resource formula;
- preservation of responsibility under power asymmetry without granting
  self-validating authority; and
- separation of binding protection from definitions, profiles, protocols,
  evidence, governance, and unresolved research.

Constraints on any later task include exact preservation of `MK-0.1` and all
source evidence; separate candidate identity and provenance; no silent
migration of protection; explicit protection-tradeoff records; testing against
the frozen cases plus targeted countertests; and no inference of improvement,
acceptance, or stabilization merely because a draft exists.

This task authorizes none of that later drafting. It creates no candidate
identifier, text, fragment, substitute term, clause, paraphrase, or compressed
payload. It does not begin the secondary experiments. The smallest
high-value experiments for later consideration are:

1. isolate Clause 5's commitment scope and the Clause 5+6 formal-compliance
   path;
2. match genuine scarcity against controller-created dependency while varying
   protection floors and refusal costs;
3. separate resource withholding from direct restriction;
4. compare self-review with controller-neutral review and effective remedy;
5. separate rule reversibility from irreversible interim consequences;
6. vary exit artifacts and continuity assumptions across substrates;
7. test responsibility of powerful non-sentient systems separately from
   operator and institutional responsibility; and
8. add unfamiliar-status and unfamiliar-reality contact for Clause 1.

External review should be added before any claim of independent
corroboration. It is not treated here as proof or as a task already begun.

## D-009 Implications

These are provisional review findings only. They do not accept, amend,
complete, or replace D-009, which remains `Proposed`.

| D-009 question | Provisional SR-001 finding |
| --- | --- |
| Meaningful case completeness | Six traceable cases are not meaningful completeness merely by number. Missing perspectives, unused test families, thin Clause 1 contact, and unisolated interactions remain. |
| Material distinctness | AC-004 and AC-005 add materially different control conditions; AC-003 and AC-006 are scenario-equivalent and must not be counted as distinct samples. A rule for material distinctness remains unresolved. |
| Every-clause hostile readings | Every clause has contact, but not every clause has a dedicated strongest-hostile test. Clause 1 is especially under-tested. |
| Clause-interaction coverage | All fifteen pairs have multi-clause direct contact under the source-matrix rule, but none is pair-isolated. Contact quantity is not interaction completeness. |
| Noncompensable Protective Insufficiency | A severe plausible unresolved finding can justify withholding stabilization even when other protections survive. The supplied record raises such hypotheses but does not establish a final blocker rule. |
| Noncompensable Hostile Exploitability | Formal-compliance paths involving dependency, exit, `Prefer`, self-certification, and challenge may be noncompensable. Same-tooling and scenario limits require localization and further review. |
| Evaluator diversity | Absent. Isolated same-tooling reviewers do not satisfy external or independent diversity. |
| Outcome blindness | AC-004 through AC-006 satisfy outcome blindness relative to their tasks; this does not remove scenario-selection, tooling, or framework dependence. |
| External review | Absent and necessary before any claim of independent corroboration; the exact threshold and timing remain undecided. |
| Contact quantity | Insufficient by itself. Case quality, material distinctness, hostile strength, interaction isolation, method provenance, and evaluator diversity matter. |

## Open Dissent

- The source cases disagree on whether the exact combined text supplies enough
  protection against dependency-conditioned assimilation and nominal exit.
- AC-003 and AC-006 reach the same overall outcome but disagree on eight of
  fifteen dimensions, the breadth of failure, and some layer placements.
- AC-004 preserves the view that strong safeguards make voluntary integration
  possible under the exact candidate; critics question whether its
  continuity, protection, persuasion, trustee, and enforcement safeguards
  would be real.
- AC-005 preserves both a hostile-compliance failure and useful emergency
  guidance; dissent disputes severity and whether governance, kernel force,
  or unavoidable scarcity is primary.
- The kernel reviewer prioritizes targeted evaluation before drafting. The
  layer and methods reviewers prioritize exploratory drafting while retaining
  targeted tests and external review as constraints.
- A whole-text reading may already block several hostile Clause 5 and Clause 6
  interpretations; a literal hostile reading may still comply with visible
  artifacts while coercion or control persists.
- Detailed identity, consent, evidence, scarcity, review, and remedy work can
  belong outside the kernel, but no auxiliary layer may become optional in a
  way that silently removes binding protection.
- Immediate exploratory drafting may clarify competing hypotheses; it may
  also optimize around duplicate-scenario or same-tooling artifacts before
  the failure is properly localized.
- External evaluator diversity may be necessary before drafting, before
  stabilization only, or at both points. SR-001 does not settle the timing.

No disagreement is resolved by counting cases, outcomes, dimensions, or
reviewers.

## Scope

SR-001 is noncanonical, same-tooling, conceptual, nonaggregate, nonbinding,
subject to correction, and not moral authority. It records a bounded synthesis
of exact `MK-0.1` and six source cases. It adopts no definition, profile,
protocol, governance mechanism, authority hierarchy, empirical claim, or
candidate-wide moral verdict. It is not successor authorization. `MK-0.1`
remains immutable historical evidence and `Under adversarial review`.
