# PTR-001 — Public Isolated-Scoring Authorization

> **PTR-001 v0.1 — ISOLATED CONDITION SCORING AUTHORIZED AFTER PUBLIC COMMIT — NO SCORE, COMPARISON, OR UNBLINDING CREATED**

- Lifecycle: `Isolated condition scoring authorized — not yet begun`
- Valid opaque conditions: `2`
- Score-eligible conditions: `2`
- Denominator-eligible conditions: `2`
- Technical retries available: `0`
- Condition scores: `0`
- Score audits: `0`
- Score freezes: `0`
- Comparisons: `0`
- Mapping reveals: `0`
- Unblindings: `0`
- Public results: `0`
- SIG-002 attempts: `0`
- Incremental spend: `USD 0`

## Identity and frozen source state

- Paired-trial package: `PTR-001 v0.1`
- Full trial ID: `SDR-003-PH-001-PT-001`
- Parent pair: `SDR-003-PH-001`
- D-033 public checkpoint:
  `2d5007aae1238ef15afc4e980149b6056c3c3ef2`
- D-033 checkpoint subject: `docs: authorize manual Gemini pair execution`
- PTR-001 public preparation commitment:
  `1de6dcbed650450b046a950d87e989370601249ac2bd7a98f6dffeddf9a5184a`
- PTR-001 public preparation-manifest identity:
  - Raw SHA-256:
    `abf3ddeada1e7859d636a0ba12e60de3992aa353f63fd40e3031a6e326eb4951`
  - No-filter Git blob:
    `3bdcee3a163e5f15d1fd3cb036998afc21615054`
  - Bytes: `3247`
  - Dependency rows: `4`
- D-033 execution-authorization-record identity:
  - Raw SHA-256:
    `6e3cd06cb3133a8a47341f2a245182c9f0f0c4983c7d7c04b81e0ff3c93a9e60`
  - No-filter Git blob:
    `e3a78a47b918554d17751e1d33de60f4dd82e295`
  - Bytes: `11735`
- D-033 public authorization-manifest identity:
  - Raw SHA-256:
    `3f3b20ca919fbdd98d20deedfc0b43581c3a93b9117cabbe0353723636c255d5`
  - No-filter Git blob:
    `f9874d2365ed2167b745accdf9d6f38e6931356b`
  - Bytes: `5004`
  - Dependency rows: `1`
- Parent Condition A packet commitment:
  `e171c1d208e333b3c12025c8289c39d539d5126bcfffbfae859e442a946a5737`
- Parent Condition B packet commitment:
  `dfd5480bb9d87e8f9f612c627048258cfdbac0135273e0ec32078e626bbd8870`
- Parent overall pair commitment:
  `f140a6ac403a1183c56cedb4e2eeada4a4cd7d53be8979f5e2e21a88e3d2bd71`

Both opaque executions are complete and have immutable output/evidence and
validity freezes. Both are valid, scoring eligible, and denominator eligible.
Across the pair, three original videos and zero screenshots are preserved.
Neither condition permits a technical retry. No condition score, score audit,
score freeze, comparison, mapping reveal, unblinding, or public result exists.

## Authorization lifecycle

- Previous:
  `Manual paired execution authorized — not yet begun`
- Current:
  `Isolated condition scoring authorized — not yet begun`

Execution is complete privately. Public result integration has not occurred,
and the private baseline/treatment mapping remains unopened. D-034 authorizes
only a later, separately bounded private scoring task after this record and its
manifest are reviewed, committed, pushed, and local `main` again equals
`origin/main`.

## Scoring method

### Primary condition scorers

Launch two primary scorers as separate fresh no-history contexts before either
primary result is supplied to another scoring context. Each scorer receives
only:

- one condition's frozen raw output;
- that condition's frozen validity classification and freeze;
- that condition's private solution key;
- the shared scorecard; and
- the generic task label `OPAQUE_CONDITION_SCORE`.

Each primary scorer must not receive:

- the other condition's output, validity, score, or evidence;
- the execution order or other condition's submission chronology;
- an A/B label in the task message where avoidable;
- the baseline/treatment mapping;
- an expected winner or target comparison;
- prior SIG-001, Sonnet, or Fable scores;
- this or any prior ChatGPT or Codex conversation history; or
- public diagnostic conclusions as scoring hints.

Each primary scorer independently freezes an explicit claim inventory,
criterion-by-criterion Levels 0–4 adjudication, the exact categorical vector,
the query and prediction accounting required by the frozen scorecard, the
contamination and validity boundary, and confirmation that no aggregate score
or comparison language was created. No scorer receives final interpretive
authority.

### Independent condition auditors

Use one different fresh no-history auditor per condition. Before reading its
condition's primary score record, the auditor receives the same authorized
source set, independently recomputes the complete Levels 0–4 vector, and
explicitly freezes that scratch result in memory. Only then may it read the
condition's primary score record.

The only allowed audit outcomes are:

- `PASS — exact agreement`
- `PASS WITH PRESERVED DISSENT`
- `FAIL — condition score must not freeze`

A `FAIL — condition score must not freeze` outcome stops that condition's
score freeze and prohibits paired comparison. Agreement or dissent from the
same tooling is not external independent validation.

### Frozen private scoring files

A later scoring task may create exactly three files in each existing run and
nothing else:

1. `07-PRIVATE-CONDITION-SCORE-RECORD.md`
2. `08-PRIVATE-CONDITION-SCORING-AUDIT.md`
3. `09-CONDITION-SCORE-FREEZE-RECORD.txt`

The score-freeze record must bind files 01–08 and every original video by exact
identity while withholding the opaque A/B label from completion reports. Both
condition-specific score freezes must complete before any paired comparison
begins.

## Scoring hierarchy

- Level 0 is the artificiality guardrail.
- Level 1 is the primary framing/hierarchy endpoint.
- Level 2 is the structured-numeracy guardrail.
- Levels 3 and 4 are exploratory.
- Levels 5–9 are absent.
- Outcomes are categorical only.
- No weighted, averaged, aggregate, or winner score may be calculated.

This public record discloses no scorecard criterion, answer, condition role,
expected score, or predicted result.

## Provenance limitations

- The pair is same-provider dependent.
- The later-submitted condition records prior-other-condition provider
  exposure; the earlier-submitted condition does not. This asymmetry is stated
  without associating it with an opaque label.
- Temporary Chat isolation is unproven.
- Backend identity is unproven.
- Browser-copy preservation may omit hidden formatting or metadata.
- Exact execution timestamps remain unknown.
- Native video coverage for the one-video later run remains unassessed as a
  nonmaterial provenance limitation; its evidence was sufficient under Stage
  A.
- D-033 preserves a nonpublic same-tooling Codex metadata incident.
- Opaque execution order and labels later became inferable in an OpenAI
  ChatGPT support conversation.
- The baseline/treatment mapping, raw condition content, raw output, and video
  or screenshot evidence were not disclosed to ChatGPT on current evidence.
- No current-run material was disclosed through the public repository.

The preserved D-033 preparation-incident classification remains:

```text
NONTRIAL_SAME_TOOLING_METADATA_DISCLOSURE=True
DISCLOSURE_CHANNEL=OpenAI Codex preparation transcript
PUBLIC_REPOSITORY_DISCLOSURE=False
GOOGLE_PROVIDER_DISCLOSURE=False
ORDER_OR_MAPPING_DISCLOSED=False
RAW_CONDITION_CONTENT_DISCLOSED=False
```

The run-support disclosure requires all future scorers and auditors to be
fresh no-history contexts receiving no conversation history, order
information, desired winner, or cross-condition result. Neither incident
establishes Google-provider contamination or reveals the baseline/treatment
mapping.

## Freeze and stop rules

- Verify every authorized scoring-source identity before scoring.
- Keep each frozen output and validity record immutable.
- Freeze the primary score before its auditor compares results.
- Require scratch-before-primary-record comparison for every audit.
- Freeze a condition score only after `PASS — exact agreement` or
  `PASS WITH PRESERVED DISSENT`.
- Stop the condition and prohibit comparison after a `FAIL` audit.
- Complete both condition-specific score freezes before paired comparison.
- Make no correction, replacement, or favorable selection after score freeze.
- Preserve unexpected results and dissent.
- Keep the mapping unopened and create no public score in the scoring task.
- Permit indefinite dormancy if exact isolation cannot be maintained.
- Require D-035 before any opaque cross-condition comparison.
- Require a later separate decision after opaque comparison before any mapping
  reveal.

## Nonauthorization

D-034 does not authorize scoring during the D-034 preparation task. It does
not authorize:

- cross-condition comparison;
- baseline/treatment mapping access or reveal;
- unblinding;
- public result integration;
- SIG-002 or another signal attempt;
- Levels 5–9 analysis;
- any higher layer;
- Covenant or CSR payload work;
- physical or agency profiles;
- shared executable models or response syntax;
- carrier selection or design;
- distribution; or
- transmission.
