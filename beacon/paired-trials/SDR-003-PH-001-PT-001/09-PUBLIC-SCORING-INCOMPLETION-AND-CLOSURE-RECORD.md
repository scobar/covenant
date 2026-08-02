# PTR-001 — Public Scoring Incompletion and Closure Record

> **PTR-001 v0.1 — CLOSED INCOMPLETE AT SCORING — ONE SCORE FREEZE, ONE AUDIT FAIL — NO COMPARISON, MAPPING REVEAL, OR PUBLIC SCORE**

- Lifecycle: `Closed incomplete — scoring audit disagreement`
- Public checkpoint before closure:
  `054b78bbd37a5b239b9117782f45258f7f4cd363`
- Authorized incremental spend: USD `0`

## Identity and lineage

- Paired-trial package: `PTR-001 v0.1`
- Full trial ID: `SDR-003-PH-001-PT-001`
- Parent pair: `SDR-003-PH-001`
- D-032 lifecycle: provider/model selected and paired trial prepared.
- D-033 lifecycle: manual execution authorized and later completed privately.
- D-034 lifecycle: isolated scoring authorized and later completed only through
  the condition-specific audit stage.
- D-035 lifecycle: `Accepted`; PTR-001 is closed incomplete at scoring.
- Public preparation commitment:
  `1de6dcbed650450b046a950d87e989370601249ac2bd7a98f6dffeddf9a5184a`

Public lineage:

1. [Public paired-trial charter](00-PUBLIC-PAIRED-TRIAL-CHARTER.md)
2. [Provider and model selection record](01-PROVIDER-AND-MODEL-SELECTION-RECORD.md)
3. [Execution and freeze protocol](02-EXECUTION-AND-FREEZE-PROTOCOL.md)
4. [Paired-trial commitment record](03-PAIRED-TRIAL-COMMITMENT-RECORD.md)
5. [Public paired-trial preparation manifest](04-PUBLIC-PAIRED-TRIAL-PREPARATION-MANIFEST.md)
6. [Public pair-execution authorization](05-PUBLIC-PAIR-EXECUTION-AUTHORIZATION.md)
7. [Public pair-execution authorization manifest](06-PUBLIC-PAIR-EXECUTION-AUTHORIZATION-MANIFEST.md)
8. [Public isolated-scoring authorization](07-PUBLIC-ISOLATED-SCORING-AUTHORIZATION.md)
9. [Public isolated-scoring authorization manifest](08-PUBLIC-ISOLATED-SCORING-AUTHORIZATION-MANIFEST.md)

No private identity is published by this record.

## Execution and validity

Two opaque conditions were executed and produced two completed valid outputs.
Both output/evidence records and both validity classifications froze before
scoring. No technical retry was used, and no substantive retry was permitted.
The same-provider exposure and provider/interface limitations recorded by
D-033 and D-034 remain. Scoring created no decoder-validity failure and did not
invalidate either Gemini output.

## Scoring chronology

Both fresh no-history primary scorers launched in isolation before either
primary result was shared with another scoring context. Each condition then
received a different fresh no-history auditor. Each auditor independently
recomputed and froze its complete scratch result while the corresponding
primary score record was physically withheld, and only then read the primary
record.

No score was corrected, replaced, rerun, averaged, or favorably selected. No
third adjudicator was used. Cross-condition comparison never began.

## Scoring outcome

```text
OPAQUE_CONDITIONS_EXECUTED=2
VALID_OUTPUTS=2
VALIDITY_FREEZES=2
PRIMARY_SCORE_RECORDS=2
SCORING_AUDITS=2
SCORE_FREEZES=1
AUDIT_PASS_EXACT=0
AUDIT_PASS_WITH_PRESERVED_DISSENT=1
AUDIT_FAIL=1
AUDITS_PRESERVING_DISSENT=2
AUDIT_MAPPING_EXPLICIT_FALSE_COUNT=1
AUDIT_MAPPING_EXPLICIT_TRUE_COUNT=0
AUDIT_MAPPING_ASSERTION_ABSENT_COUNT=1
AUDIT_MAPPING_AMBIGUOUS_COUNT=0
PAIR_COMPARISONS=0
MAPPING_REVEALS=0
UNBLINDINGS=0
PUBLIC_SCORE_VECTORS=0
PUBLIC_RAW_OUTPUTS=0
SIG_002_ATTEMPTS=0
AUTHORIZED_INCREMENTAL_SPEND_USD=0
```

One non-FAIL audit with preserved dissent permitted one condition score to
freeze. One `FAIL — condition score must not freeze` prevented the second
score freeze. Both original primary records and both original audit records
remain preserved, as does the sole non-FAIL score-freeze record. The failed
score was neither replaced nor frozen.

These are aggregate counts only. This record publishes no categorical vector,
criterion result, query or prediction accounting, condition association,
audit association, freeze association, raw output, solution, or scorecard
detail.

## Mapping-access provenance

The mapping record has three distinct provenance layers:

- Audit-record layer: one private scoring-audit record explicitly states that
  mapping access did not occur; the other contains no mapping-access
  assertion. There are zero explicit true and zero ambiguous assertions.
- Scoring-task provenance layer: the completed D-034 coordinator-level report
  stated `MAPPING_OPENED=False`, `COMPARISON_STARTED=False`, and
  `UNBLINDING_STARTED=False`. This is same-tooling task provenance, not a field
  duplicated inside both audit records.
- Artifact layer: no pair-comparison, mapping-reveal, or unblinding artifact
  exists.

One private scoring-audit record explicitly states that mapping access did
not occur; the other audit record contains no mapping-access assertion. The
absence is preserved and is not retroactively filled. The completed scoring
task’s coordinator-level provenance reported no mapping access, and no
comparison, mapping-reveal, or unblinding artifact exists. The
baseline/treatment mapping remains private and publicly unrevealed. These
facts do not establish that both audit records contain equivalent
attestations.

The absent field is a provenance limitation. It is neither proof of access nor
equivalent to an explicit denial, and it is not associated publicly with
either opaque condition.

## Prior D-035 preparation-session disclosure

The prior D-035 preparation attempt stopped after an overbroad private-header
inspection surfaced one criterion-level row from one private condition-score
record into that OpenAI Codex preparation transcript. The row is not quoted,
reconstructed, searched for, summarized, or published here.

```text
D035_PRIOR_PREPARATION_TRANSCRIPT_DISCLOSURE=True
DISCLOSURE_CHANNEL=OpenAI Codex D-035 preparation transcript
DISCLOSED_CLASS=One criterion-level row from one private condition-score record
EXACT_ROW_PUBLICATION_AUTHORIZED=False
PUBLIC_REPOSITORY_DISCLOSURE=False
GOOGLE_PROVIDER_DISCLOSURE=False
RAW_DECODER_OUTPUT_DISCLOSED=False
BASELINE_TREATMENT_MAPPING_DISCLOSED=False
OPAQUE_CONDITION_ASSOCIATION_DISCLOSED=False
FULL_SCORE_VECTOR_DISCLOSED=False
AUDIT_OUTCOME_TO_CONDITION_ASSOCIATION_DISCLOSED=False
PRIVATE_FILE_CHANGED=False
PUBLIC_FILE_CHANGED_AFTER_RESTORATION=False
PRIOR_CLOSURE_THREAD_ELIGIBLE_FOR_FINAL_AUDIT=False
FRESH_CLOSURE_THREAD_REQUIRED=True
```

The prior closure thread stopped correctly, all of its public edits were
restored, and no private byte changed. The incident was not a public-repository
or Google-provider disclosure, did not reveal a condition association or full
vector, and did not change a score, audit, validity classification, freeze, or
mapping. The old thread is excluded from final closure audits. This fresh task
used no private semantic inspection.

## Aggregate discrepancy resolution

The first aggregate closure attempt stopped on a custodian disagreement. A
later deterministic, read-only exact-root resolution established exactly 25
PTR-001 preparation files and 23 dependencies, verified the preparation
commitment, and established one explicit-false and one absent per-audit
mapping-access attestation. The discrepant `10/8` result was inconsistent with
the exact PTR-001 root or recursive scope. No private file changed during
resolution, and no closure conclusion was selected by preference or majority.
This record does not speculate about the path or scope used by the discrepant
custodian.

## Interpretation boundary

> The audit FAIL is evidence that the frozen scoring instrument and
> same-tooling adjudication did not produce a reproducible condition score for
> one output. It is not evidence for or against either opaque design condition,
> and it cannot be converted into a paired result.

The one frozen score has no pairwise interpretation. The mapping-attestation
omission is a provenance limitation, not a treatment result. Neither the FAIL
nor the omission identifies a preferred condition, improvement, regression,
success, or failure of either opaque design condition.

## Closure and retired gates

PTR-001 closes as `Closed incomplete — scoring audit disagreement`. The
anticipated D-035 comparison gate is retired for PTR-001 because the required
two score freezes do not exist. No paired or informal comparison, mapping
reveal, unblinding, public vector, public raw output, or current-result use in
BBIL real-candidate optimization is permitted. All private artifacts and both
neutral scoring workspaces remain preserved. Indefinite dormancy is allowed,
but PTR-001 cannot be revived for comparison.

## Future diagnostic boundary

A future separate accepted decision may authorize a scoring-disagreement
diagnostic. Any such diagnostic must:

- preserve both original primary and audit judgments;
- preserve the mapping-attestation asymmetry;
- remain blind to the mapping where possible;
- classify disagreement mechanisms rather than rescore;
- create no replacement PTR-001 score;
- create no pair comparison or mapping reveal;
- infer no winner;
- validate any improved instrument on synthetic fixtures before future real
  use; and
- inform only future scorecards and BBIL synthetic-method validation.

No diagnostic is authorized by this closure.

## Limitations

- Both decoder runs used the same provider.
- Prior-other-condition provider exposure is asymmetric without public opaque
  condition association.
- Backend identity is unverified, and Temporary Chat isolation is unproven.
- Browser-copy preservation has known limitations.
- Exact execution timestamps remain unknown.
- Native coverage for the one-video run remains unassessed.
- Prior same-tooling metadata and support incidents remain preserved.
- The prior D-035 criterion-row transcript incident remains a nonpublic
  same-tooling custody/provenance limitation.
- Per-audit mapping provenance contains one explicit false assertion and one
  absent assertion.
- Per-agent repository, tool, and network enforcement was unavailable.
- No external independent adjudication occurred.
- There is one score freeze and one failed scoring audit.
- No universal receiver inference follows.

No scorer, auditor, custodian, provider, model, Scott, ChatGPT, Codex, or
future actor gains final interpretive authority.
