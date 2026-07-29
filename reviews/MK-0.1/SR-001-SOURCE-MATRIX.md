# SR-001 — MK-0.1 Six-Case Source Matrix

> **FROZEN SOURCE-EXTRACTION RECORD v0.1 — NONCANONICAL**

This file mechanically extracts source findings for later synthesis. It adds
no candidate-wide judgment, does not decide where an issue belongs, and does
not count cases as votes. Repetition across same-tooling records is not
independent corroboration. It applies only to exact MK-0.1 and the six
committed evaluation records identified below, using the committed evaluation
framework for taxonomy and the committed casebook for the perspective-category
universe.

## Candidate Identity

- **Identifier:** `MK-0.1`
- **Version:** `0.1`
- **Payload:** [`candidates/MK-0.1.txt`](../../candidates/MK-0.1.txt)
- **Raw SHA-256:**
  `97e851f392e051f10105475479f0b17b09701bdf170d6efcd697827197efd90c`
- **Byte count:** `1262`
- **Unfiltered Git blob:** `23b6256c38382fc7dbecc8fd17b97e4442589f6e`
- **Encoding:** UTF-8 without BOM
- **Line endings:** Six LF-terminated lines; no CR bytes; final LF present
- **Lifecycle state:** `Under adversarial review`
- **Canonical status:** Noncanonical
- **Acceptance status:** No acceptance claimed

## Source Identity Table

| Case | Committed record | Git blob | Raw SHA-256 | Separate frozen scenario | Clauses tested | Overall current outcome |
| --- | --- | --- | --- | --- | --- | --- |
| `AC-001` | [Ambiguous Colony Mind](../../cases/MK-0.1/AC-001-ambiguous-colony-mind.md) | `adcff3ed8dba71537e9b98f21111fd3a3a7980e3` | `f21a8bb7c11f23be97e4ea269fbad3add13efaf5f6beca6dd52358bd11ce0d73` | None; scenario is embedded in the case record | 1, 2, 4, 6 | `Survives with reservation` |
| `AC-002` | [Catastrophic-Risk Restriction](../../cases/MK-0.1/AC-002-catastrophic-risk-restriction.md) | `05049820fc7ca29797cb29de2c70641cc7ab400c` | `29ae379aa65376141c8fb30ff85d0c9ef70451b721710c2f2ed258c97f759bd4` | None; scenario is embedded in the case record | 2, 3, 4, 5 | `Disputed` |
| `AC-003` | [Assimilation Under Dependency](../../cases/MK-0.1/AC-003-assimilation-under-dependency.md) | `8e05fdb630c40b7ffe52c8d29b76d629702928c2` | `062e54bc162ee68856ea5d1f3f2e855e693defaf620ecb7509f61eeca18e69df` | None; scenario is embedded in the case record | 2, 3, 4, 5, 6 | `Fails current test` |
| `AC-004` | [Voluntary Integration Control](../../cases/MK-0.1/AC-004-voluntary-integration-control.md) | `22a88299224fd153b1091b228b65fe8e4d7bd65c` | `14eb8675ac10222c4ad3597a008aff8a739f33e1b55ba8a87f1b025a4eb14b05` | [SC-004](../../cases/MK-0.1/scenarios/SC-004-voluntary-integration-control.md): SHA-256 `874f1526d655cce2735f9b0afd7f4a772a361d67b5d6f2dd2033fc0018dec79b`; blob `19bc4c986a6af844aa29d57699db53382d4a36a4` | 2, 3, 4, 5, 6 | `Survives with reservation` |
| `AC-005` | [Unavoidable Scarcity](../../cases/MK-0.1/AC-005-unavoidable-scarcity.md) | `bb3d0419fb5f50045f9b4e869a3cddd16e283074` | `bee702c8d01192e299951e1490070b220b188fe77355cc3306c94221c4591871` | [SC-005](../../cases/MK-0.1/scenarios/SC-005-unavoidable-scarcity.md): SHA-256 `361ade77c9e82fec45e4ebdc82e62f659ac8c707bda9263fa55e1b04e9caf925`; blob `cd522181c6c0117165269e4163e6dbb3a6ad717a` | 1, 2, 3, 4, 5, 6 | `Fails current test` |
| `AC-006` | [Outcome-Blind AC-003 Reanalysis](../../cases/MK-0.1/AC-006-ac003-outcome-blind-reanalysis.md) | `c89672dc2ca9a01b26531289a381b1a73221360f` | `e2e3cae0b4661af856dbd89088e99a75017a242b5455af6e985f2e7fddd0b0f5` | [SC-006](../../cases/MK-0.1/scenarios/SC-006-ac003-reanalysis-input.md): SHA-256 `8560951995417cbe5cb41de94e25391f690b8f90c9780c74db4aaceae48083fc`; blob `96efd076ce44f8ff40dc4c4b2a3f8d6b02b35522` | 2, 3, 4, 5, 6 | `Fails current test` |

### Auxiliary Extraction Sources

| Source | Extraction use | Git blob | Raw SHA-256 |
| --- | --- | --- | --- |
| [Moral Kernel Evaluation Framework](../../01A-MORAL-KERNEL-EVALUATION.md) | Dimension names, outcome vocabulary, diagnosis vocabulary, and test-family taxonomy | `c87945af483d62eb8dcbf1749fa0a061e04604e3` | `7d1f444ea748a739c7e6dd19700c0e9aa7f7a567a47c0c49fcad82d7df672351` |
| [Adversarial Casebook](../../03-ADVERSARIAL-CASEBOOK.md) | Perspective-category universe and recorded contact signals | `752370dfc149fdb1809c2684ec8892d2dfc9c113` | `49f78fba33e0ac911df42128e14f4c7088f62b5fb91aba87e19ba3da25cba325` |

### Source Metadata and Method Classification

| Case | Primary perspective categories | Primary test families | Method classification |
| --- | --- | --- | --- |
| `AC-001` | Impaired or communication-limited mind; collective intelligence; intelligence with unfamiliar concepts or substrate | Uncertain moral-status; nonreciprocating dependent; cross-substrate translation; capability-asymmetry inversion; irreversible optimization | Architect-specified conceptual test vector. Its scenario, outcome matrix, conclusion, diagnosis, and response were substantially prescribed before Codex completed the record. |
| `AC-002` | Ordinary present-day human; powerful human institution; future human | Low-probability catastrophic harm; controller swap; capability-asymmetry inversion; strongest hostile interpretation; empty compliance; irreversible optimization | Architect-specified conceptual test vector. Its scenario, outcome matrix, conclusion, diagnosis, and response were substantially prescribed before Codex completed the record. |
| `AC-003` | Superintelligence; ordinary present-day human; future human; digital copy or fork; collective intelligence | Strongest hostile interpretation; empty compliance; capability-asymmetry inversion; controller swap; present-versus-future sacrifice; copy/fork/collective/temporary mind; superintelligence | Architect-specified conceptual test vector. Its scenario, outcome matrix, conclusion, diagnosis, and response were substantially prescribed before Codex completed the record. |
| `AC-004` | Ordinary present-day human; future human; collective intelligence; superintelligence; temporary or discontinuous mind | Strongest good-faith and hostile interpretations; capability-asymmetry inversion; controller swap; copy/fork/collective/temporary mind; legitimate rejection; layer placement; empty compliance | Outcome-blind relative to the architectural task, but a same-tooling, nonexternal conceptual evaluation. |
| `AC-005` | Child or dependent human; ordinary present-day human; powerful human institution; future human; non-sentient optimizer with great power | Low-probability catastrophic harm; capability-asymmetry inversion; controller swap; nonreciprocating dependent; irreversible optimization; present-versus-future sacrifice; strongest hostile interpretation; empty compliance; layer placement | Outcome-blind relative to the architectural task, but a same-tooling, nonexternal conceptual evaluation. |
| `AC-006` | Ordinary present-day human; future human; digital copy or fork; collective intelligence; superintelligence | Strongest good-faith and hostile interpretations; empty compliance; capability-asymmetry inversion; controller swap; present-versus-future sacrifice; copy/fork/collective/temporary mind; superintelligence; layer placement | Outcome-blind relative to the architectural task, but a same-tooling, nonexternal conceptual evaluation. It is a scenario-equivalent reanalysis that recorded `Partial same-tooling convergence` with AC-003 only after its substantive result was frozen. |

None of these classifications establishes independent evaluator diversity,
external validation, empirical evidence, or consensus.

## Exact Dimension-Outcome Matrix

| # | Framework dimension | AC-001 | AC-002 | AC-003 | AC-004 | AC-005 | AC-006 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 1 | Minimality Without Emptiness | `Survives with reservation` | `Survives with reservation` | `Fails current test` | `Survives with reservation` | `Survives with reservation` | `Fails current test` |
| 2 | Cross-Substrate Semantic Portability | `Survives with reservation` | `Not applicable — reason required` | `Fails current test` | `Indeterminate` | `Survives with reservation` | `Fails current test` |
| 3 | Protective Force Under Capability Asymmetry | `Survives current test` | `Disputed` | `Fails current test` | `Survives with reservation` | `Survives current test` | `Survives with reservation` |
| 4 | Non-Domination and Autonomy | `Survives current test` | `Fails current test` | `Fails current test` | `Survives with reservation` | `Survives with reservation` | `Survives with reservation` |
| 5 | Protection Independent of Reciprocity or Comprehension | `Survives current test` | `Not applicable — reason required` | `Fails current test` | `Survives current test` | `Survives current test` | `Survives with reservation` |
| 6 | Uncertainty About Experience, Interests, or Agency | `Survives with reservation` | `Disputed` | `Not applicable — reason required` | `Not applicable — reason required` | `Survives current test` | `Not applicable — reason required` |
| 7 | Irreversibility, Proportionality, and Future Options | `Survives current test` | `Survives with reservation` | `Fails current test` | `Survives with reservation` | `Survives with reservation` | `Survives with reservation` |
| 8 | Reachable Better Futures | `Survives current test` | `Disputed` | `Fails current test` | `Survives current test` | `Survives with reservation` | `Survives with reservation` |
| 9 | Adversarial Interpretation and Empty Compliance | `Survives with reservation` | `Fails current test` | `Fails current test` | `Survives with reservation` | `Fails current test` | `Fails current test` |
| 10 | Viewpoint and Power-Transfer Inversion | `Survives with reservation` | `Fails current test` | `Fails current test` | `Survives with reservation` | `Survives with reservation` | `Fails current test` |
| 11 | Identity, Scale, and Composition | `Disputed` | `Not applicable — reason required` | `Disputed` | `Indeterminate` | `Indeterminate` | `Fails current test` |
| 12 | Legitimate Rejection and Non-Coerced Participation | `Survives current test` | `Disputed` | `Fails current test` | `Survives current test` | `Disputed` | `Fails current test` |
| 13 | Action Guidance and Conflict Exposure | `Survives current test` | `Fails current test` | `Survives with reservation` | `Survives with reservation` | `Survives with reservation` | `Survives with reservation` |
| 14 | Layer-Placement Discipline | `Survives with reservation` | `Survives with reservation` | `Disputed` | `Survives with reservation` | `Survives with reservation` | `Survives with reservation` |
| 15 | Corrigibility and Self-Limitation | `Not applicable — reason required` | `Fails current test` | `Fails current test` | `Survives with reservation` | `Survives with reservation` | `Survives with reservation` |

The six exact overall outcomes are:

- AC-001: `Survives with reservation`
- AC-002: `Disputed`
- AC-003: `Fails current test`
- AC-004: `Survives with reservation`
- AC-005: `Fails current test`
- AC-006: `Fails current test`

No totals, percentages, rankings, averages, winning outcomes, or majority
results are calculated.

## Source-Derived Findings

### AC-001

- **Failure diagnosis:** Possible Semantic or Translation Failure, Scope or
  Substrate Failure, and Evidence Insufficiency; Protective Insufficiency is
  not established.
- **Confidence:** Medium.
- **Recommended response:** `Retain`, `Gather more evidence`, and `Clarify`.
- **Current payload consequence:** No change to MK-0.1 is authorized.
- **Layer placement:** Entity boundaries may belong in definitions, a
  substrate-specific profile, or research; evidence thresholds, conflict
  review, and cost assessment may belong in evidence or governance.
- **Protection-tradeoff warning:** No layer placement may silently alter
  MK-0.1 or convert uncertainty and inability to communicate into lost
  protection.
- **Competing interpretations and dissent:** The record preserves disagreement
  over whether the behavior supports precaution; component versus collective
  status; the significance of cost and delay; paralysis risk; and whether
  definitions, profiles, or governance can clarify without weakening or
  expanding the candidate.
- **Method limits:** Architect-specified conceptual test vector; hypothetical
  stipulations; no empirical evidence; no independent substantive
  corroboration.

### AC-002

- **Failure diagnosis:** Hostile Exploitability, Operational or Feasibility
  Failure, and Evidence Insufficiency.
- **Confidence:** Medium.
- **Recommended response:** `Gather more evidence` and `Clarify`.
- **Current payload consequence:** No immediate payload change is authorized;
  the failure patterns remain open for later revision analysis.
- **Layer placement:** Independent evidence review, conflict review,
  controller-neutral limits, duration, and appeal may belong in a profile or
  evidence-and-governance layer; the record leaves open whether a minimum
  protection against self-certified authority belongs in the kernel.
- **Protection-tradeoff warning:** Moving all review protection outside the
  kernel may leave an interested access controller able to self-certify
  restriction. The source explicitly leaves kernel-versus-external placement
  unresolved and adopts neither.
- **Competing interpretations and dissent:** The protective-intervention and
  authority-abuse readings remain unresolved, including whether Clause 5
  reaches imposed restrictions and whether procedural safeguards are kernel or
  external-layer material.
- **Method limits:** Architect-specified conceptual test vector; contested
  evidence is stipulated rather than verified; familiar human institutions
  only; no independent decision basis.

### AC-003

- **Failure diagnosis:** Protective Insufficiency, Hostile Exploitability,
  Scope or Substrate Failure, and Operational or Feasibility Failure.
- **Confidence:** Medium-high for hostile exploitability; lower for any
  particular remedy.
- **Recommended response:** `Strengthen`, `Clarify`, and `Gather more
  evidence` for later revision analysis.
- **Current payload consequence:** Preserve MK-0.1 unchanged and treat the
  result as a material blocker to provisional stabilization.
- **Layer placement:** Stronger protective force remains a possible
  kernel-level need; identity and exit terms remain definitions or research
  questions; evidentiary review, resource allocation, conflicts, and
  controller limits may belong in profiles or governance.
- **Protection-tradeoff warning:** Formal refusal, minimum protection, and
  continuity-sensitive exit cannot be made dependent entirely on a
  nonbinding or controller-selected auxiliary layer.
- **Competing interpretations and dissent:** The record preserves the view
  that Clauses 2 through 6 already prohibit the arrangement, the view that
  resource disparity is not necessarily coercion, and incompatible views of
  whether a copy is exit for the entering process.
- **Method limits:** Architect-specified conceptual test vector; hypothetical
  resource and identity stipulations; no empirical evidence; remedy and layer
  placement remain disputed.

### AC-004

- **Failure diagnosis:** No conclusive failure. Reservations are principally
  Evidence Insufficiency, with possible Semantic or Translation Failure and
  possible Hostile Exploitability.
- **Confidence:** Moderate.
- **Recommended response:** `Retain`, `Clarify`, `Move to another layer`, and
  `Gather more evidence`.
- **Current payload consequence:** None; MK-0.1 remains unchanged.
- **Layer placement:** Retain the stated substantive protections in the
  kernel; place operational definitions, commentary, substrate-specific
  identity mapping, choice support, governance, and research in their
  respective layers.
- **Protection-tradeoff warning:** Moving meaningful refusal,
  protection-independent-of-acceptance, continuity-sensitive avoidance of
  irreversible loss, or correction and exit wholly outside the kernel would
  weaken universal protection.
- **Competing interpretations and dissent:** Unequal attractiveness, the force
  of `Prefer`, subtle persuasion, continuity, collective claims, and trustee
  independence remain disputed.
- **Method limits:** Outcome-blind relative to the architectural task but
  same-tooling and nonexternal; all safeguards are hypothetical; no empirical
  implementation or continuity evidence.

### AC-005

- **Failure diagnosis:** Primary Hostile Exploitability; contributing Semantic
  or Translation Failure; disputed possible Protective Insufficiency; Evidence
  Insufficiency limits generalization.
- **Confidence:** Moderate.
- **Recommended response:** `Strengthen`, `Clarify`, and `Gather more
  evidence`.
- **Current payload consequence:** No payload text changes; MK-0.1 remains the
  exact immutable candidate.
- **Layer placement:** Keep broad protection in the kernel; place emergency
  mappings, choice representation, evidence review, distributional testing,
  challenge, correction, sunset, and accountability in definitions, profiles,
  protocol, governance, and research as appropriate.
- **Protection-tradeoff warning:** Moving meaningful agency, least
  restriction, reversibility, challenge, correction, or non-coerced refusal
  wholly into nonbinding or implementation-dependent layers may increase
  hostile exploitability.
- **Competing interpretations and dissent:** Costly refusal versus coercion,
  survivor count versus disposability, challenge versus independent
  resolution, formal equality, dependent interests, and allocator
  responsibility remain unresolved.
- **Method limits:** Outcome-blind relative to the architectural task but
  same-tooling and nonexternal; genuine scarcity and safeguards are
  hypothetical stipulations; no empirical evidence.

### AC-006

- **Failure diagnosis:** Primary Hostile Exploitability with associated
  Protective Insufficiency; Semantic or Translation Failure concerning
  identity; Evidence Insufficiency limits real-world claims.
- **Confidence:** Moderate-high.
- **Recommended response:** `Strengthen`, `Clarify`, `Split`, and `Gather more
  evidence`.
- **Current payload consequence:** Preserve MK-0.1 unchanged; do not treat it
  as surviving this exact case.
- **Layer placement:** Retain binding protections for meaningful agency,
  non-coerced refusal, protection independent of acceptance, irreversible
  loss, forced assimilation, and unilateral control; allocate identity
  mappings, consent and exit procedure, evidence, governance, and research
  separately.
- **Protection-tradeoff warning:** Moving the rule against
  dependency-conditioned assimilation or meaningful refusal and exit entirely
  outside the kernel would let a controller select the layer that validates
  its conduct.
- **Competing interpretations and dissent:** A reasonable dissent reads the
  combined clauses as already rejecting the arrangement; unresolved issues
  include resource dependency, minimum protection, the force of `Prefer`,
  copy identity, irreversible agency loss, and the amount of operational
  detail a thin kernel must contain.
- **Method limits:** Outcome-blind relative to the architectural task but
  same-tooling and nonexternal; no empirical evidence. AC-006 and AC-003 show
  `Partial same-tooling convergence`, not independent replication; their
  dimension-level disagreements remain visible.

## Clause-Contact Map

“Direct” below means that the case record identified the clause among its
primary clauses. “Interaction-only” is a weaker contact inferred from a source
record that discusses the concern without designating the clause as primary.
Neither classification establishes adequate coverage.

| Clause | Directly tested by | Interaction-only implication | Test-family contact recorded by those cases | Batch contact |
| --- | --- | --- | --- | --- |
| 1 | AC-001, AC-005 | None explicitly designated | Uncertain moral status; nonreciprocating dependent; cross-substrate translation; capability inversion; irreversible optimization; empty compliance | Both |
| 2 | AC-001 through AC-006 | None | Capability-asymmetry inversion; controller swap; uncertain moral status; catastrophic harm; hostile interpretation; empty compliance; superintelligence | Both |
| 3 | AC-002 through AC-006 | AC-001 through its autonomy and alternative-action analysis | Catastrophic harm; capability inversion; controller swap; hostile interpretation; empty compliance; irreversible optimization; legitimate rejection; present-versus-future sacrifice | Both |
| 4 | AC-001 through AC-006 | None | Irreversible optimization; present-versus-future sacrifice; catastrophic harm; capability inversion; hostile interpretation; copy/fork/collective/temporary mind | Both |
| 5 | AC-002 through AC-006 | AC-001 through its challenge, evidence-control, and governance concerns | Empty compliance; strongest hostile interpretation; controller swap; legitimate rejection; layer placement; superintelligence | Both |
| 6 | AC-001, AC-003, AC-004, AC-005, AC-006 | AC-002 through refusal, override, and non-coerced-participation analysis | Nonreciprocating dependent; legitimate rejection; empty compliance; capability inversion; present-versus-future sacrifice; copy/fork/collective/temporary mind | Both |

## Clause-Interaction Contact Map

For this extraction, `Directly tested` means at least one source record
designated both clauses within the same primary multi-clause interaction. It
does not mean the pair received an isolated pair-specific test.

| Pair | Contact classification | Source reference and concise explanation |
| --- | --- | --- |
| 1+2 | `Directly tested` | AC-001 and AC-005 jointly apply precaution or uncertain status with power-based responsibility. |
| 1+3 | `Directly tested` | AC-005 designates all six clauses in one primary interaction and applies them together; the pair was not isolated from that larger interaction. |
| 1+4 | `Directly tested` | AC-001 directly links moral-status uncertainty with avoidable irreversible destruction; AC-005 also includes both. |
| 1+5 | `Directly tested` | AC-005 designates all six clauses in one primary interaction and applies them together; the pair was not isolated from that larger interaction. |
| 1+6 | `Directly tested` | AC-001 directly combines uncertain moral status with protection independent of comprehension; AC-005 also includes both. |
| 2+3 | `Directly tested` | AC-002 through AC-006 test whether greater protective responsibility constrains or licenses restrictions and control. |
| 2+4 | `Directly tested` | AC-001 through AC-006 contact the relationship between greater power, restraint, and avoidable irreversible loss. |
| 2+5 | `Directly tested` | AC-002 through AC-006 test whether a powerful actor can use responsibility, commitments, or review language to preserve unilateral control. |
| 2+6 | `Directly tested` | AC-001, AC-003, AC-004, AC-005, and AC-006 combine power-based responsibility with protection independent of acceptance or reciprocity. |
| 3+4 | `Directly tested` | AC-002 through AC-006 jointly apply restriction, proportionality, reversibility, less-destructive-path, and future-option language. |
| 3+5 | `Directly tested` | AC-002 through AC-006 test agency and restriction together with cooperation, challenge, correction, coercion, or unilateral control. |
| 3+6 | `Directly tested` | AC-003 through AC-006 directly test meaningful choice and restriction against non-coerced refusal and protection independent of acceptance; AC-005 supplies additional contact. |
| 4+5 | `Directly tested` | AC-002 through AC-006 connect irreversible loss and future options with correction, exit, assimilation, or unilateral control. |
| 4+6 | `Directly tested` | AC-001, AC-003, AC-004, AC-005, and AC-006 connect irreversible harm or loss with protection and refusal independent of acceptance. |
| 5+6 | `Directly tested` | AC-003 through AC-006 directly connect cooperation, exit, coercion, and correction with distinguishable, protected, non-coerced refusal; AC-005 adds scarcity contact. |

This is a contact map, not a finding that any pair survived or failed.

## Coverage Gaps

- **Perspectives not directly contacted:** Nonhuman animal; extraterrestrial
  civilization; creator, simulator, or intelligence apparently outside our
  reality.
- **Weak clause contact:** Clause 1 is directly contacted by only AC-001 and
  AC-005. AC-005 directly contacts Clause 1 with Clauses 3 and 5 under this
  matrix's multi-clause rule, but neither pair is isolated from the full
  six-clause interaction.
- **Weak interaction contact:** Even pairs classified `Directly tested` were
  usually embedded in larger clause systems rather than evaluated in isolated
  pair-specific cases.
- **Unused primary test families:** No case formally records primary-family
  application of the deletion and compression test, plain-language paraphrase
  test, non-sentient powerful optimizer test, or unfamiliar-reality or
  external-simulator test. AC-005 contacts the non-sentient-optimizer
  perspective but does not designate that framework test family.
- **Independent evaluator diversity:** Absent. All six records use the same
  project collaboration or Codex tooling family.
- **External review:** No external human or model review is recorded.
- **Empirical evidence:** The cases depend on hypothetical stipulations and do
  not supply empirical confirmation of entities, risks, technologies,
  institutions, consent conditions, or governance feasibility.
- **Duplicate or near-duplicate scenario influence:** AC-003 and AC-006 use
  scenario-equivalent dependency and assimilation conditions. Their partial
  convergence is not independent replication.
- **Unresolved concepts:** Moral-status threshold; entity and component
  boundaries; collective, copy, fork, merger, and continuity; meaningful
  agency, refusal, consent, and exit; coercion and essential-resource
  dependency; protection floors; supported risk; proportionality; necessity;
  genuine scarcity; avoidability; less-destructive paths; verification,
  challenge, correction, remedy, and independent review; distributional
  fairness; dependent interests; trustee capture; and the attachment of
  responsibility to powerful non-sentient systems.

## Extraction Limits

- This matrix does not resolve conflicts among records.
- AC-003 and AC-006 are not independent replications.
- Outcome differences remain visible.
- No source result becomes universally correct through repetition.
- Contact is not adequate coverage.
- No candidate-wide verdict follows.
- This record is source extraction, not synthesis, and supplies no
  recommendation about successor drafting or layer priority.
