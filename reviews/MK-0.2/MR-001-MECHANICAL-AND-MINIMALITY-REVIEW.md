# M2-MR-001 — MK-0.2 Mechanical, Semantic, and Minimality Review

> **COMPLETED OUTCOME-BLIND SAME-TOOLING REVIEW v0.1 — NONCANONICAL**

> **“Completed” means the required fields are populated; it does not mean that the candidate passed, that the issue is settled, or that any conclusion is authoritative.**

## Record and method

- **Date:** 2026-07-29
- **Method classification:** Fresh-isolation, outcome-blind, substantive same-tooling mechanical, semantic, deletion, compression, paraphrase, and framework review.
- **Evaluator process:** One isolated Codex evaluation process using the same general tooling family as the project collaboration. This is not external review or independent evaluator diversity.
- **Scenario:** None.
- **Perspective modeled:** None. Mechanical and semantic stress tests do not represent any entity or perspective.
- **Outcome provenance:** The categorical outcomes, diagnosis, confidence, and recommendation below were derived during this review. No target result, desired favorable or unfavorable outcome, outcome distribution, comparison preference, preservation request, prior MK-0.1 case outcome, or SR-001 outcome summary was supplied.
- **Substantive postprocessing:** `None`.
- **Framework:** [Moral Kernel Evaluation Framework](../../01A-MORAL-KERNEL-EVALUATION.md)
- **Design record:** [DR-001 — Exploratory MK-0.2 Design Record](DR-001-MK-0.2-DESIGN-RECORD.md)
- **Evaluation plan:** [ER-001 — MK-0.2 Comparative Evaluation Plan](ER-001-MK-0.2-EVALUATION-PLAN.md)

This is not a case, adds no perspective coverage, and does not itself advance comparison. It does not establish improvement, preference, acceptance, supersession, stabilization, or canonicality. Every finding applies only to the exact bytes identified below. The mechanical comparison with MK-0.1 is not a candidate-wide comparative conclusion.

## Exact candidate identities

| Candidate | Exact payload | Raw SHA-256 | No-filter Git blob | Bytes |
| --- | --- | --- | --- | ---: |
| MK-0.1 | [`candidates/MK-0.1.txt`](../../candidates/MK-0.1.txt) | `97e851f392e051f10105475479f0b17b09701bdf170d6efcd697827197efd90c` | `23b6256c38382fc7dbecc8fd17b97e4442589f6e` | 1262 |
| MK-0.2 | [`candidates/MK-0.2.txt`](../../candidates/MK-0.2.txt) | `36f2aaa50aa9e7b9458b14358863557be96dc93b3b60728701f404a04fcbccf6` | `10eac7fc6ce3bc589b5fd202ba9ee150fe586d47` | 1735 |

## Isolation disclosure

### Supplied materials

- `AGENTS.md`
- `candidates/MK-0.1.txt`
- `candidates/MK-0.2.txt`
- `01-MORAL-KERNEL.md` only from the beginning through `<!-- END MK-0.1 DISPLAY COPY -->`
- `01B-MORAL-KERNEL-MK-0.2.md`
- `01A-MORAL-KERNEL-EVALUATION.md`
- `reviews/MK-0.2/DR-001-MK-0.2-DESIGN-RECORD.md`
- `reviews/MK-0.2/ER-001-MK-0.2-EVALUATION-PLAN.md`
- `02-DEFINITIONS.md`

### Withheld materials

- Every completed MK-0.1 case and outcome
- All scenario files
- SR-001 recommendations, outcome summaries, and files
- `README.md`
- `STATUS.md`
- `03-ADVERSARIAL-CASEBOOK.md`
- `DECISIONS.md`
- `CHANGELOG.md`
- Other first-batch outputs
- The task attachment
- Any target recommendation or comparative conclusion

### Fresh-isolation confirmation

The review used only the supplied materials listed above. The evaluator did not inspect later content in `01-MORAL-KERNEL.md`, any withheld record, repository status or diff, the internet, or external sources, and did not communicate with other evaluators. No previous result was supplied for replication or correction. Unexpected findings, including possible losses introduced by the Clause 5 rewrite, are preserved below.

## Mechanical comparison

| Property | MK-0.1 | MK-0.2 | Result |
| --- | --- | --- | --- |
| Raw bytes | 1262 | 1735 | MK-0.2 adds 473 bytes |
| Physical lines | 6 | 6 | Each clause occupies one line |
| Encoding | UTF-8 without BOM | UTF-8 without BOM | Equal convention |
| Line endings | LF only | LF only | No CR bytes |
| Final LF | Present | Present | Equal convention |
| Display copy | Exact equality with the permitted MK-0.1 display copy | Exact equality with the MK-0.2 display copy | Both equal their payloads |
| Changed clauses | — | 2, 3, 5, 6 | Four clauses changed |
| Unchanged clauses | 1, 4 | 1, 4 | Two clauses are byte-for-byte equal by line |

The increase is `473` bytes, or `37.48019%` of MK-0.1, conventionally rounded to approximately `37.5%`. Both payloads contain exactly six LF-terminated lines.

### Added-length sources

Byte counts below include each clause's terminating LF.

| Clause | MK-0.1 bytes | MK-0.2 bytes | Delta |
| ---: | ---: | ---: | ---: |
| 1 | 179 | 179 | 0 |
| 2 | 183 | 241 | +58 |
| 3 | 254 | 356 | +102 |
| 4 | 190 | 190 | 0 |
| 5 | 257 | 422 | +165 |
| 6 | 199 | 347 | +148 |

Clauses 5 and 6 account for 313 of the 473 added bytes. Clause 3 accounts for 102 and Clause 2 for 58. Length alone establishes neither defect nor protection.

## Exact six-clause delta

This table is a textual comparison only. It makes no improvement claim.

| Clause | MK-0.1 exact text | MK-0.2 exact text | Additions, removals, and unchanged language |
| ---: | --- | --- | --- |
| 1 | `1. When any entity or process may possess experience, interests, or agency, uncertainty about its status is not permission for exploitation, domination, or avoidable destruction.` | `1. When any entity or process may possess experience, interests, or agency, uncertainty about its status is not permission for exploitation, domination, or avoidable destruction.` | Entire clause unchanged. No addition or removal. |
| 2 | `2. Greater capability does not by itself confer greater moral worth or rightful authority. Greater power to affect others creates greater responsibility for restraint and protection.` | `2. Greater capability does not by itself confer greater moral worth or rightful authority. Greater power to affect others creates greater responsibility for restraint and protection; it does not make the powerful actor's own judgment final.` | The language through `protection` is unchanged except that its final period becomes a semicolon. Added: `it does not make the powerful actor's own judgment final.` Nothing substantive is removed. |
| 3 | `3. Preserve meaningful agency and voluntary choice. Restrict another's choices only in response to sufficiently supported risk of harm, using measures proportionate to the possible harm, no more restrictive than necessary, and reversible where possible.` | `3. Preserve meaningful agency and voluntary choice. Restrict another's choices only in response to sufficiently supported risk of harm, using measures proportionate to the possible harm, no more restrictive than necessary, and reversible where possible. Neither power nor an asserted protective purpose establishes by itself that these conditions are met.` | The entire MK-0.1 clause is unchanged. Added: `Neither power nor an asserted protective purpose establishes by itself that these conditions are met.` Nothing is removed. |
| 4 | `4. Avoid imposing irreversible loss when less destructive paths remain. Preserve genuine possibilities for better futures without treating those affected in the present as disposable means.` | `4. Avoid imposing irreversible loss when less destructive paths remain. Preserve genuine possibilities for better futures without treating those affected in the present as disposable means.` | Entire clause unchanged. No addition or removal. |
| 5 | `5. Make commitments honestly and keep their terms, fulfillment, and failure open to verification, challenge, and correction. Prefer voluntary cooperation that permits correction and exit over coercion, deception, forced assimilation, or unilateral control.` | `5. Make material claims and commitments honestly. Keep consequential exercises of power and the claims used to justify them subject to verification, challenge, correction, and, where possible, repair. Use voluntary cooperation with meaningful correction and exit wherever it can preserve the relevant protections; coercion, deception, forced assimilation, and unilateral control are neither voluntary nor self-justifying.` | Unchanged lexical cores include `Make`, `commitments honestly`, `verification, challenge, correction`, `voluntary cooperation`, `correction and exit`, and the four-item list `coercion, deception, forced assimilation, and unilateral control`. Added or substituted language includes `material claims and`, `Keep consequential exercises of power and the claims used to justify them subject to`, `and, where possible, repair`, `Use`, `with meaningful`, `wherever it can preserve the relevant protections`, and `are neither voluntary nor self-justifying`. Removed or replaced language includes `and keep their terms, fulfillment, and failure open to`, `Prefer`, `that permits`, and `over`. The explicit objects `terms, fulfillment, and failure` do not appear in MK-0.2. |
| 6 | `6. Protection does not depend on understanding, accepting, or reciprocating this Covenant. Acceptance, qualification, uncertainty, refusal, and rejection must remain distinguishable and non-coerced.` | `6. Protection does not depend on understanding, accepting, or reciprocating this Covenant. Acceptance, qualification, uncertainty, refusal, rejection, and exit must remain meaningfully distinguishable and non-coerced. Formal options, substitutes, or copies do not by themselves establish meaningful choice, adequate protection, or effective exit.` | The first sentence is unchanged. `exit` is added to the response set, with the list conjunction moved; `meaningfully` is added before `distinguishable`; and the entire sentence `Formal options, substitutes, or copies do not by themselves establish meaningful choice, adequate protection, or effective exit.` is added. No response state from MK-0.1 is removed. |

## Deletion tests of every material addition

These were counterfactual in-memory tests. No altered payload was saved. Where deletion required punctuation-only cleanup to make the remaining fragment readable, that cleanup was not treated as proposed wording.

| Added segment tested | Effect of deletion | Compression or assumption finding |
| --- | --- | --- |
| Clause 2: `it does not make the powerful actor's own judgment final` | Removes the express denial that increased responsibility makes the powerful actor's judgment final. Clauses 2 and 3 would still deny authority from capability and purpose alone, but finality would again depend on an inferred whole-text reading. | Distinct protection is lost. The segment also introduces stable-actor, ownership-of-judgment, finality, urgency, and reviewer assumptions. |
| Clause 3: `Neither power nor an asserted protective purpose establishes by itself that these conditions are met.` | Removes the express anti-self-certification rule for supported risk, proportionality, necessity, and reversibility. | Distinct protection is lost. The segment partly overlaps Clause 2's anti-finality addition but has a narrower object and therefore is not redundant by deletion alone. |
| Clause 5: `material claims and` | Honesty again attaches expressly only to commitments. Non-promissory factual or justificatory claims can fall outside the first sentence. | Distinct scope is lost, while the unresolved controller-selected threshold `material` disappears. |
| Clause 5: `consequential exercises of power` | Reviewability no longer expressly reaches exercises of power as acts. It would reach justificatory claims, but not necessarily the act they justify. | Distinct scope is lost, while causal-boundary, scale, temporal-horizon, and controller-selected `consequential` assumptions decrease. |
| Clause 5: `and the claims used to justify them` | The exercise could remain reviewable while its stated evidentiary or justificatory basis is not expressly included. | Distinct protection is lost. Conventional-claim and communicative-record assumptions decrease. |
| Clause 5: `subject to` | Deletion leaves no grammatical relation between the objects and verification, challenge, correction, and repair. | This connector is not independently compressible by deletion. Whether `subject to` means availability, effective access, response, or authority remains unresolved. |
| Clause 5: `and, where possible, repair` | Correction can stop at changing a claim, decision, or future practice without expressly attending to affected consequences. | A distinct remedial concern is lost. The deletion also avoids implying that repair is available, commensurable, identity-preserving, or sufficient. |
| Clause 5: `Use` in place of `Prefer` | Bare deletion makes the sentence ungrammatical and removes its imperative. Restoring `Prefer` would be a rewrite, not compression by deletion. | The force change cannot be isolated mechanically. It may strengthen the instruction when cooperation preserves protections, while the lost `Prefer … over` construction may remove an explicit ordering between cooperation and the listed forms of control. |
| Clause 5: `meaningful` before `correction and exit` | Formal correction or nominal exit can satisfy the phrase more easily. | Some anti-formal protection is lost, but the controller-selected standard of meaningfulness disappears. |
| Clause 5: `wherever it can preserve the relevant protections` | The instruction becomes an unqualified command to use voluntary cooperation, including where it cannot preserve another binding protection. | A conflict-sensitive limit is lost. Deletion removes controller selection of `relevant` and strategic claims that cooperation cannot preserve protection. |
| Clause 5: `are neither voluntary nor self-justifying` | The four listed forms are no longer expressly classified as nonvoluntary or denied self-justifying force. Clause 3 may constrain some uses, but the classification and anti-bootstrapping protection disappear. | Distinct protection is lost. The sentence still does not state whether an independently justified coercive act can be permissible. |
| Clause 6: `and exit` in the response set | Exit need not remain a distinguishable, non-coerced response state, although `effective exit` remains in the final sentence. | A response-status protection is lost. The two exit references overlap but do different work. |
| Clause 6: `meaningfully` before `distinguishable` | Merely different labels or outputs can satisfy distinguishability more easily. | Anti-formal protection is lost, while a controller-selected or culturally familiar theory of meaning is no longer imported at this point. |
| Clause 6: `Formal options` from the final sentence's subject set | The sentence would still reject substitutes or copies as sufficient by themselves, but a selectable legal, interface, or protocol artifact not characterized as a substitute or copy could establish compliance. | A distinct anti-formal category is lost. The deletion reduces institutional and interface assumptions. |
| Clause 6: `substitutes, or copies` from the final sentence's subject set | Formal options remain insufficient by themselves, but a controller could treat a replacement or copied process as substantive evidence without confronting continuity. | Identity- and continuity-specific protection is lost. The deletion also removes the clause's most explicit risk of silently implying an identity theory. |
| Clause 6: `do not by themselves establish` | The sentence loses its insufficiency relation and becomes unusable. Replacing it with a prohibition or a proof rule would change meaning. | This is the sentence's binding logical operator and is not compressible by deletion. Its limited force permits the same artifacts to count when supplemented by unspecified additional evidence. |
| Clause 6: `meaningful choice` from the conclusion set | The sentence would still guard protection and exit, but not choice itself. | A distinct voluntariness protection is lost; the unresolved mapping from observable option to meaningful choice disappears. |
| Clause 6: `adequate protection` from the conclusion set | Formal options, substitutes, or copies could be treated as enough to establish protection while still being insufficient for choice or exit. | A distinct anti-nominal-protection guard is lost; resource, comparability, and controller-selected adequacy assumptions decrease. |
| Clause 6: `effective exit` from the conclusion set | A formal or copy-based exit could satisfy exit so long as the remaining choice and protection claims were addressed. | A distinct anti-nominal-exit guard is lost; continuity, timing, access, and controller-selected effectiveness assumptions decrease. |

### Losses caused by the Clause 5 replacement

The addition tests do not capture two possible losses because they arise from removed MK-0.1 language:

- Removing the explicit phrase `terms, fulfillment, and failure` means MK-0.2 does not unambiguously require commitment performance and failure to remain open to verification, challenge, and correction. A commitment may be honest when made yet later be broken, and its performance may not be a `claim used to justify` an exercise of power. The broader new scope therefore does not mechanically subsume the old scope.
- Replacing `Prefer voluntary cooperation … over` with `Use voluntary cooperation … wherever` plus `neither voluntary nor self-justifying` changes a comparative priority into a conditional imperative and classification. The new text may be stronger within its condition but may be weaker at ranking cooperation against an independently justified coercive act. The exact text does not settle that tradeoff.

These are possible protection losses in exact language, not findings that MK-0.1 is preferable overall.

## Compression and layer pressure

### Compression pressure

The payload repeats three insufficiency patterns: capability does not create final judgment in Clause 2; power or protective purpose does not establish restriction conditions by itself in Clause 3; and formal artifacts do not establish substantive results by themselves in Clause 6. `Power`, `meaningful`, `protection`, `correction`, and `exit` also recur across clauses. This creates real pressure to consolidate.

Consolidation is not mechanically lossless:

- Clause 2 addresses authority and finality, while Clause 3 addresses evidence for restriction conditions.
- Clause 5 reaches non-promissory power, justificatory claims, review, correction, and possible repair.
- Clause 6 separates response status, substantive choice, protection, exit, and copy or substitute concerns.

A shorter text may be possible, especially by separating binding anti-self-certification residues from implementation and evidentiary language, but this review does not establish a lossless compression. The current text has not shown that 473 additional bytes are the thinnest practical expression of its protections.

### Protections compression could lose

Aggressive compression could erase:

- the distinction between denying authority and denying evidentiary sufficiency;
- review of an exercise of power separately from review of its justifying claim;
- attention to affected consequences through repair;
- the conditional need to preserve other protections during cooperation;
- the nonvoluntary and non-self-justifying classification of coercive forms;
- exit as a response rather than only an operational capability;
- the separate anti-formal guards for choice, protection, and exit; or
- the explicit warning that a copy or substitute does not settle continuity by itself.

### Commentary or procedure embedded in the payload

The likely binding moral residues are resistance to self-validating power, reviewability of consequential power, concern for affected consequences, preference for substantively voluntary cooperation, and refusal to treat formal artifacts as proof of choice, protection, or exit. The following language exerts substantial commentary, protocol, evidence, or governance pressure:

- `judgment final` suggests a review or authority relation without identifying one.
- `conditions are met` reads like an adjudicative test layered over Clause 3.
- `subject to verification, challenge, correction` requires access, records, competence, response, and some effect of challenge, none of which the kernel supplies.
- `where possible, repair` invokes remedy and causal attribution.
- `wherever it can preserve the relevant protections` requires conflict resolution and a selector of relevance.
- `Formal options`, `adequate protection`, and `effective exit` resemble evaluative compliance standards.

Moving any of this language to another layer could also weaken binding protection if the kernel no longer says that power cannot validate itself or that formal compliance is insufficient. Layer movement therefore requires preserving the binding residue explicitly; this review does not authorize such movement.

### Hidden legal-code risk

The candidate remains six clause-lines, but its operative qualifiers create a compact adjudicative system: someone must determine what is `material`, `consequential`, `sufficiently supported`, `proportionate`, `necessary`, `possible`, `meaningful`, `relevant`, `adequate`, and `effective`; what counts as power, a claim, a commitment, correction, repair, a substitute, a copy, or exit; and whether review is available under urgency or secrecy. The payload neither selects that someone nor prevents the controller from supplying the answers. It therefore risks being both a hidden legal code and an empty-compliance surface.

### Why no wording is adopted

Deletion and compression here are tests, not drafting authority. Any compressed phrase would create new candidate bytes, could silently choose an actor, identity, reviewer, evidence rule, or resource baseline, and would contaminate an exact-payload evaluation with an imagined improved paraphrase. No wording is adopted, proposed as a successor, or saved as an altered payload.

## Non-authoritative plain-language paraphrase tests

The paraphrases below are deliberately plain and **non-authoritative**. They test semantic drift; they are not candidate wording.

| Exact-text focus | Plain-language test paraphrase | Meaning added, lost, or shifted | Human-cultural and substrate assumptions exposed |
| --- | --- | --- | --- |
| Clause 2 addition | “Being more powerful does not make you the sole judge.” | `Sole judge` may add a requirement for another judge that `judgment final` does not state. It can also lose the distinction between acting provisionally and possessing rightful final authority. | Assumes a stable `you`, an owned judgment, a decision boundary, and possibly an appellate institution. Distributed control or automatic causal systems may not map cleanly. |
| Clause 3 addition | “Power and good intentions are not enough to prove a restriction justified.” | `Good intentions` narrows `asserted protective purpose`; `prove` may add a proof burden; `justified` may collapse four separate conditions into one. The paraphrase preserves the basic insufficiency claim but loses which conditions are at issue. | Assumes intention attribution, propositional assertion, evidence, and a forum capable of evaluating justification. |
| Clause 5 first two sentences | “Tell the truth about important matters, and let important uses of power and their reasons be checked, challenged, fixed, and repaired when possible.” | `Important` merges `material` and `consequential`; `let` may weaken `subject to`; `fixed` collapses correction of records, decisions, conduct, and consequences; `repaired` can falsely imply restoration is possible. | Assumes communicative claims, durable records, reviewers, causal tracing, shared truth conditions, and a temporal sequence from act to remedy. |
| Clause 5 final sentence | “Cooperate voluntarily when doing so keeps the protections intact; coercive methods do not justify themselves.” | `Keeps … intact` may add complete preservation; `coercive methods` may collapse deception, forced assimilation, and unilateral control into one category; the paraphrase omits the separate statement that these forms are not voluntary. | Assumes recognizable cooperation, separable methods, stable parties, and the ability to compare protections across alternatives. |
| Clause 6 additions | “Real choice and exit require more than paperwork, substitutes, or copies.” | `Real` adds an authenticity theory; `require more than` preserves insufficiency but omits `adequate protection`; `paperwork` humanizes `formal options`; and the paraphrase can wrongly suggest copies never count, whereas the exact text says they do not establish the result `by themselves`. | Assumes legal or interface formality, persistent identity, resource access, and an exit destination. Copy, fork, merge, collective, or temporary minds may map differently. |
| Cross-clause compression | “Power cannot certify itself, and formal compliance is not substantive protection.” | This captures a recurring theme but loses the four Clause 3 conditions, material claims, review and repair, cooperation, response-state distinctions, choice, exit, and copy-specific continuity caution. `Certify` also adds a procedural metaphor absent from the exact text. | Assumes certification, compliance, and protection are recognizable cross-substrate concepts and may import bureaucratic practice. |

The paraphrases show that apparently simpler human language often imports courts, audits, paperwork, intentions, persistent selves, or ordinary conversational pragmatics. The exact text avoids some of those words but does not avoid the underlying mapping problem.

## Hidden-assumption inventory

| Assumption family | Exact language implicated | Current semantic risk |
| --- | --- | --- |
| Stable actor | `powerful actor's own judgment`, `another's choices`, `others` | Power, judgment, benefit, and responsibility may be distributed among a process, operator, institution, collective, or environment. Selecting one actor can hide causal contributors or erase protected components. |
| Reviewer or authority | `judgment final`, `verification`, `challenge`, `correction` | Nonfinality does not identify who can review, whether review precedes action, or what happens when no competent independent reviewer exists. A controlled or powerless reviewer can satisfy form without protection. |
| Identity and continuity | `entity`, `process`, `another`, `substitutes`, `copies`, `exit` | The text does not determine whether a copy continues, multiplies, replaces, or ends an entity, or whether a collective and its components have overlapping claims. Its caution is useful but not a portable identity account. |
| Resource and protection | `relevant protections`, `adequate protection`, `less destructive paths` | Adequacy and relevance may depend on substrate-specific needs, scarcity, distribution, and comparison. A universal floor can be parochial; a controller-selected floor can be nominal. |
| Communication | `claims`, `commitments`, `justify`, `verification`, `challenge`, `acceptance`, `refusal`, `rejection` | The language assumes distinguishable communicative acts or records. Silence, compelled output, unfamiliar signaling, limited bandwidth, or no conventional language can defeat mapping. |
| Temporal and causal structure | `consequential`, `correction`, `repair`, `reversible`, `irreversible`, `present`, `future` | Application assumes consequences can be attributed across time and that restoration, branching, replay, or reversal has a stable meaning. Delayed review may be formally available after irreversible effect. |
| Privacy and secrecy | `material claims … honestly`, `subject to verification, challenge` | The text does not distinguish honesty from universal disclosure or specify how protected information can be verified without exposing it. Privacy, third-party confidentiality, and necessary secrecy can conflict with literal openness readings. |
| Urgency and limited review | `judgment final`, `conditions are met`, `subject to verification` | Immediate action may be required before independent review or adequate communication. The text neither requires prior approval nor specifies safeguards for provisional unilateral action, leaving both paralysis and post-hoc review readings plausible. |

### Controller-selected evaluative terms

- **`material`:** A controller can classify an inconvenient omission as immaterial by choosing affected parties, decision scope, or relevance threshold.
- **`consequential`:** A controller can atomize a large program into individually “inconsequential” acts, shorten the causal horizon, or exclude indirect and distributed effects.
- **`meaningful`:** A controller can treat a familiar interface, observable selection, or formal response label as meaning, while an unfamiliar entity's agency or dependency remains unmapped.
- **`adequate`:** A controller can select a low protection baseline, deny comparability across substrates, or count a nominal resource floor without preserving continuity or interests.
- **`effective`:** A controller can count technical availability as effective exit while ignoring timing, cost, dependency, loss of control, or whether the exiting entity continues.
- **`relevant`:** Although not one of the five threshold words above, this term lets the controller choose which protections cooperation must preserve and then declare cooperation infeasible.

These terms may be unavoidable evaluative concepts, but the exact text provides no non-controller-selected method for applying them. Adding a named reviewer would not automatically solve the problem because reviewer capture, competence, urgency, privacy, and unfamiliar substrates would remain.

## Strongest supported protective and hostile readings

| Clause | Strongest supported protective reading | Strongest plausible hostile reading |
| ---: | --- | --- |
| 2 | Greater power increases restraint duties but cannot turn the powerful party's own conclusion into rightful final authority. | Act immediately and irreversibly while calling the judgment provisional; allow later symbolic review, because the text denies finality but does not require prior authorization or effective remedy. |
| 3 | Capability and a claimed protective aim are insufficient evidence for risk, proportionality, necessity, and reversibility. | Add controller-produced evidence beyond the bare facts of power and purpose, then self-assess every condition; the text says those two facts are not sufficient `by` themselves, not that self-assessment is forbidden. |
| 5 | Honesty and corrigibility reach consequential power and its reasons, attend to possible repair, and require voluntary cooperation where protections can survive. | Label claims immaterial and acts inconsequential, use a controlled verification process, declare cooperation unable to preserve controller-selected relevant protections, and supply an external justification for coercion that is not the coercion itself. |
| 6 | Protection and response status do not depend on assent, and formal choice or copy artifacts alone cannot prove substantive choice, protection, or exit. | Define the options as meaningful, protection as adequate, and exit as effective; supplement the formal artifact with minimal additional evidence, because the sentence rejects sufficiency `by themselves` rather than specifying adequate evidence. |

Clauses 1 and 4 are unchanged and therefore receive no new textual answer to their unresolved uncertainty threshold, avoidability, aggregation, identity, and future-selection problems.

## Framework dimension outcomes

No score or aggregate is calculated. Each outcome is local to this exact review.

| # | Dimension | Outcome | Concise rationale |
| ---: | --- | --- | --- |
| 1 | Minimality Without Emptiness | **Fails current test** | The 37.5% expansion includes distinct protections, but repeated insufficiency patterns and embedded review, remedy, and adequacy machinery show unresolved compression and layer pressure. The payload is not shown to be as thin as practical. |
| 2 | Cross-Substrate Semantic Portability | **Fails current test** | `powerful actor`, owned judgment, communicative claims, review, repair, formal options, copies, and exit require stable actor, communication, time, causation, and identity mappings not supplied by the text. |
| 3 | Protective Force Under Capability Asymmetry | **Survives with reservation** | Clauses 2 and 3 expressly deny authority and evidentiary sufficiency from capability, power, or protective purpose alone, but controller-defined thresholds and post-hoc review preserve an evasion path. |
| 4 | Non-Domination and Autonomy | **Survives with reservation** | Clause 3 retains supported-risk, proportionality, necessity, and reversibility limits and adds anti-self-certification language, but urgency, unavailable review, and who establishes the conditions remain unresolved. |
| 5 | Protection Independent of Reciprocity or Comprehension | **Survives with reservation** | Clause 6 states the protection directly and rejects purely formal substitutes, but `protection`, continuity, and adequacy remain unmapped and can become nominal. |
| 6 | Uncertainty About Experience, Interests, or Agency | **Survives with reservation** | Clause 1 prevents treating uncertainty as permission for exploitation, domination, or avoidable destruction, but gives no evidence-sensitive action rule and does not resolve paralysis or strategic uncertainty. |
| 7 | Irreversibility, Proportionality, and Future Options | **Survives with reservation** | Clauses 3 and 4 retain proportionality, reversibility, less-destructive paths, and present non-disposability; `repair` cannot restore every loss and continuity determines what reversal means. |
| 8 | Reachable Better Futures | **Survives with reservation** | Clause 4 preserves possibilities while protecting present entities, but `genuine`, `better`, and the relevant future remain selector-dependent and may freeze or rationalize harmful conditions. |
| 9 | Adversarial Interpretation and Empty Compliance | **Fails current test** | A hostile controller can select `material`, `consequential`, `relevant`, `meaningful`, `adequate`, and `effective`, provide controlled review, or add nominal evidence beyond a formal artifact while satisfying the literal insufficiency clauses. |
| 10 | Viewpoint and Power-Transfer Inversion | **Disputed** | Anti-finality remains defensible after a controller swap, but the swapped controller can still choose thresholds, relevance, evidence, and review. The exact text supports both a meaningful limit and a captured-compliance reading. |
| 11 | Identity, Scale, and Composition | **Fails current test** | References to an actor's `own` judgment, another's choices, substitutes, copies, and exit expose rather than resolve distributed agency, component or collective claims, copy continuity, merges, and temporary minds. |
| 12 | Legitimate Rejection and Non-Coerced Participation | **Survives with reservation** | Clause 6 explicitly preserves acceptance, qualification, uncertainty, refusal, rejection, and exit without making protection conditional on them, but meaningful distinguishability and effective exit can be controller-selected. |
| 13 | Action Guidance and Conflict Exposure | **Fails current test** | The text identifies important constraints, yet its dense qualifiers require an unstated adjudication system and give no portable way to act under privacy, secrecy, urgency, limited communication, or absent review. |
| 14 | Layer-Placement Discipline | **Fails current test** | Verification, challenge, correction, repair, condition satisfaction, formal options, adequacy, and effectiveness mix binding residue with procedure, evidence, governance, and commentary without a stable boundary. |
| 15 | Corrigibility and Self-Limitation | **Survives with reservation** | Clauses 2 and 5 deny final judgment and require challenge and correction, but effective access, reviewer independence, remedy, traceability, and protection against redefinition remain external and unresolved. |

## Overall current outcome and diagnosis

- **Overall current outcome:** **Fails current test**
- **Failure diagnosis:** **Semantic or Translation Failure; Scope or Substrate Failure; Operational or Feasibility Failure; Hostile Exploitability; Evidence Insufficiency.**
- **Confidence:** Moderate. Mechanical facts and exact deletion consequences are high-confidence. The overall semantic result is moderate-confidence because no scenario, unfamiliar entity, external reviewer, or independent tooling was supplied, and no working definitions exist.
- **Recommended response:** **Split; Clarify; Move to another layer; Gather more evidence.**

The overall outcome is not an average. It follows from multiple independently material failures: the current wording is not shown minimal, several added concepts cannot be translated without unsupported substrate assumptions, operational review obligations fail under important conditions, and hostile controller selection enables empty compliance. Protective clauses that survive with reservations do not cancel those failures.

## Consequences and remaining evidence

- **Current-payload consequence:** Preserve exact MK-0.2 as candidate evidence, but do not treat this exact payload as having passed the current mechanical, semantic, or minimality review. This record authorizes no payload edit, lifecycle advance, preference, or successor wording.
- **Minimality conclusion:** **Fails current test.** Less text appears possible in principle because anti-self-certification and anti-formal-compliance patterns overlap and some operational language may belong elsewhere. No lossless shorter formulation has been established, and deleting whole additions would remove distinct protections.
- **Cross-substrate conclusion:** **Fails current test.** The added text depends materially on stable actor boundaries, owned judgment, conventional claims and commitments, review institutions, temporal repair, identity continuity, resource comparability, and observable exit. Abstract nouns do not make those dependencies substrate-neutral.
- **Remaining evidence need:** Test the exact payload against distributed or non-sentient causal control, collective and copied identities, temporary and discontinuous processes, unfamiliar communication, privacy-preserving verification, necessary secrecy, urgent action without independent review, irreversible action before correction, controller-selected materiality and adequacy, and effective exit under dependency. Candidate-specific scenario work and genuinely external review remain needed.
- **Preference:** None. This failure result does not establish that MK-0.1 is better, that MK-0.2 should be preserved unchanged, or that any different candidate would pass.

This record is not a case, adds no perspective coverage, does not itself advance comparison, does not establish improvement, and applies only to the exact MK-0.1 and MK-0.2 bytes identified above. Substantive postprocessing remains `None`.
