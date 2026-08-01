# PTR-001 — Public Pair-Execution Authorization

> **PTR-001 v0.1 — MANUAL EXECUTION AUTHORIZED AFTER PUBLIC COMMIT — NO CONDITION SUBMITTED OR RESULT CREATED**

- Authorization lifecycle: `Manual paired execution authorized — not yet begun`
- Authorization records: `1`
- Prepared opaque conditions: `2`
- Conditions submitted: `0`
- Run attempts: `0`
- Outputs: `0`
- Validity classifications: `0`
- Technical retries used: `0`
- Scores: `0`
- Comparisons: `0`
- Unblindings: `0`
- SIG-002 attempts: `0`
- Incremental spend: `USD 0`

## Identity and parent freeze

- Paired-trial package: `PTR-001 v0.1`
- Full trial ID: `SDR-003-PH-001-PT-001`
- Parent pair ID: `SDR-003-PH-001`
- D-032 public checkpoint:
  `9d0882d848805a658c0e59d7738cf3ffb295acb5`
- PTR-001 public preparation commitment:
  `1de6dcbed650450b046a950d87e989370601249ac2bd7a98f6dffeddf9a5184a`
- PTR-001 public preparation-manifest identity:
  - Raw SHA-256:
    `abf3ddeada1e7859d636a0ba12e60de3992aa353f63fd40e3031a6e326eb4951`
  - No-filter Git blob:
    `3bdcee3a163e5f15d1fd3cb036998afc21615054`
  - Bytes: `3247`
  - Dependency rows: `4`
- Parent Condition A commitment:
  `e171c1d208e333b3c12025c8289c39d539d5126bcfffbfae859e442a946a5737`
- Parent Condition B commitment:
  `dfd5480bb9d87e8f9f612c627048258cfdbac0135273e0ec32078e626bbd8870`
- Parent overall pair commitment:
  `f140a6ac403a1183c56cedb4e2eeada4a4cd7d53be8979f5e2e21a88e3d2bd71`
- Previous lifecycle:
  `Provider/model selected and paired trial prepared — execution not authorized`
- Authorization lifecycle:
  `Manual paired execution authorized — not yet begun`

Every prior public and private frozen identity remains unchanged. This record
authorizes a later manual procedure; it is not an execution record or result.

## Authorized operator and role limits

- Scott Barbian is the private custodian and manual operator.
- Codex may prepare public records and validate frozen artifacts, but it may
  not operate the browser or provider, upload a condition, paste an
  instruction, submit a message, or execute a run.
- ChatGPT may provide architectural review and manual procedural guidance but
  must not receive condition bytes, the private execution order, the
  baseline/treatment mapping, raw output, or private scoring truth before the
  applicable freezes.
- Google/Gemini is the selected provider and interface, not an interpretive
  authority.
- No operator, custodian, provider, model, reviewer, scorer, Scott, ChatGPT,
  Codex, or other actor gains final authority.

## Exact configuration

The same exact displayed model, thinking setting, account, interface, and
context controls apply to both conditions and any permitted technical retry:

```text
PROVIDER=Google
INTERFACE=Gemini web app
DISPLAYED_MODEL_LABEL=3.1 Pro
EXTENDED_THINKING=True
BACKEND_MODEL_IDENTIFIER=Not exposed
BROWSER_INCOGNITO=True
TEMPORARY_CHAT=True
CURRENT_PLAN_LABEL=Google AI Plus (2TB)
INCREMENTAL_SPEND_USD=0
PAID_API_OR_CREDITS_ENABLED=False
PAID_SPILLOVER_POSSIBLE=Not exposed
FALLBACK_MODEL=None
```

No Flash option, other model, provider, interface, API, account, plan,
thinking setting, or paid configuration may be substituted. If the exact
displayed configuration is unavailable at execution time, this authorization
becomes dormant.

## Authorization

D-033 authorizes Scott, after the operational publication gate below, to
perform the already frozen private manual execution protocol within these
limits:

- Execute the two opaque conditions in the already frozen private order.
- Request one valid output per condition.
- Use at most one technical retry per condition under the frozen invalidity
  rules.
- Use zero substantive retries and incur zero incremental spend.
- Preserve private execution evidence and freeze the complete observable
  output exactly.
- Classify validity, exposure, and contamination privately after each run.
- Complete the first opaque condition, including any allowed technical retry
  and its final frozen validity state, before submitting the second condition.
- Conduct no scoring during manual execution. A separate later task may
  authorize isolated condition-specific scoring only after both conditions'
  output and validity records freeze.
- Conduct opaque comparison and mapping reveal only after both
  condition-specific scores freeze and a separate task authorizes that stage.

This authorization becomes operational only after D-033 and its public
authorization manifest are reviewed, committed, pushed, and local `main`
again equals `origin/main`. No run follows automatically. The private frozen
execution order controls, and the operator learns only the next opaque
condition label required for execution. The baseline/treatment mapping remains
private, and no inference about that mapping is authorized. Any condition may
remain dormant indefinitely.

## Sequential condition-completion rule

For the first opaque condition:

1. Perform its first run only after the final live qualification gate passes.
2. Freeze the complete observable output and evidence.
3. In a separate later task, classify validity, exposure, and contamination.
4. If and only if the classification is `Invalid — technical`, determine
   whether the one frozen technical retry remains available.
5. If a retry is used, execute and freeze it before submitting the second
   opaque condition.
6. Freeze the first condition's final validity state.
7. Only then may the second opaque condition be submitted.

The second opaque condition follows the same sequence. This rule prevents a
possible same-condition technical retry from following provider exposure to
the other condition.

## Live qualification gate

Immediately before each future condition submission, the operator must
perform and preserve this read-only live interface check without submitting
content or uploading a file:

```text
PROVIDER=Google
INTERFACE=Gemini web app
BROWSER_INCOGNITO=True
TEMPORARY_CHAT=True
SELECTED_MODEL_LABEL=3.1 Pro
EXTENDED_THINKING=True
BACKEND_MODEL_IDENTIFIER=Not exposed
PERSONAL_CONTEXT=False
PAST_CHAT_MEMORY=False
CONNECTED_APPS=False
CUSTOM_INSTRUCTIONS=False
GEM_OR_CUSTOM_WORKFLOW=False
NOTEBOOK=False
DEEP_RESEARCH=False
CHROME_TAB_CONTEXT=False
BROWSER_CONTROL=False
MANUALLY_ACTIVATED_WEB_SEARCH=False
FILE_UPLOAD_AVAILABLE=True
CURRENT_PLAN_LABEL=Google AI Plus (2TB)
UPGRADE_OR_PAYMENT_REQUIRED=False
INCREMENTAL_SPEND_USD=0
NO_CONTENT_SUBMITTED_BEFORE_PACKET=True
NO_FILE_UPLOADED_BEFORE_PACKET=True
```

If any exact required field differs, stop that run before upload. This gate is
a future operator action and was not performed as part of D-033.

`WEB_SEARCH` was not explicitly controllable in the observed interface. Any
visible search, retrieval, grounding, citation, connected-app behavior, or
other external tool behavior after submission must be preserved and
classified as contamination. It does not authorize a cleaner retry.

## Exposure chronology

Every future valid or contaminated run must record these fields separately:

```text
PRIOR_SAME_CONDITION_PROVIDER_EXPOSURE=<True or False>
PRIOR_OTHER_CONDITION_PROVIDER_EXPOSURE=<True or False>
SAME_PROVIDER_PAIR_DEPENDENCE=True
TEMPORARY_CHAT_ISOLATION_UNPROVEN=True
BACKEND_IDENTITY_UNPROVEN=True
```

Expected chronology:

- First condition, first run: both prior-exposure fields may be `False`.
- First condition technical retry: prior-same-condition exposure is `True`;
  prior-other-condition exposure remains `False`.
- Second condition, first run: prior-other-condition exposure is `True`.
- Second condition technical retry: both prior-exposure fields are `True`.

These are no-known-exposure observations, not proof of provider isolation,
absence of hidden state, or lack of retention or cross-session effects.

## Provider limitations

- The displayed `3.1 Pro` label is not a verified backend identifier.
- Temporary Chat and browser incognito reduce known context channels but do
  not prove provider isolation.
- Retention, hidden routing, human review, paid spillover, and future
  availability remain unresolved.
- Web/search behavior is not explicitly controllable in the observed
  interface.
- Visible external retrieval, grounding, citations, connected-app behavior,
  or other tool use is contamination.
- Same-provider exposure asymmetry is unavoidable and must be recorded.
- No fallback, paid upgrade, API, or paid-credit route is authorized.

## Preparation-Session Custody Incident

During D-033 preparation, a read-only diagnostic command emitted several
private dependency identity tuples into the same-tooling OpenAI Codex
preparation transcript. The emitted metadata classes were raw SHA-256,
Git-style blob identity, and byte count. The exact tuple values and exact
affected private-file subset remain private and are not reproduced here.

- This is a nonpublic same-tooling custody/provenance incident.
- Public repository disclosure: `False`.
- Real Git index disclosure: `False`.
- Google provider disclosure: `False`.
- Order, baseline/treatment mapping, next opaque condition label, raw condition
  content, instruction text, solution content, and scorecard content were not
  disclosed on current evidence.
- Because private identity metadata entered the Codex transcript, zero private
  disclosure within the preparation session is not claimed. The exact affected
  subset was not reopened, so this record does not claim that all private
  packet or sequence identities remained absent from that transcript.
- One-way identity metadata does not by itself reconstruct the private
  surface-novel condition bytes.
- No frozen private artifact, parent commitment, packet commitment, pair
  commitment, PTR-001 preparation commitment, or backup changed.
- Regenerating or rotating the frozen pair would not erase the transcript and
  is not authorized.

Every future private run record must preserve:

```text
NONTRIAL_SAME_TOOLING_METADATA_DISCLOSURE=True
DISCLOSURE_CHANNEL=OpenAI Codex preparation transcript
PUBLIC_REPOSITORY_DISCLOSURE=False
GOOGLE_PROVIDER_DISCLOSURE=False
ORDER_OR_MAPPING_DISCLOSED=False
RAW_CONDITION_CONTENT_DISCLOSED=False
```

This incident is a methodological limitation, not an empirical result or a
Google contamination event. D-033 remains a manual-execution authorization
subject to clean public commit and every existing qualification, chronology,
retry, stop, and nonauthorization rule.

## Retry and stop rules

- Maximum technical retries: `1 per condition`.
- Substantive retries: `0`.
- Refusal, low score, uncertainty, criticism, indeterminacy, partial recovery,
  or an inconvenient or unfavorable output never authorizes a retry.
- A contaminated substantive response does not authorize a cleaner retry.
- A wrong visible configuration stops the run before submission.
- Exact-configuration unavailability makes the authorization dormant.
- A payment, upgrade, metered-use, or credit request requires stopping.
- A packet, dependency, or commitment mismatch requires stopping.
- Failure to preserve complete output or evidence requires stopping.
- Protocol ambiguity that cannot be resolved without changing a frozen rule
  requires stopping.

## Nonauthorization

D-033 does not itself execute a condition, create a run directory, create an
output or evidence record, classify validity, score, compare, unblind, publish
a result, or create SIG-002.

It does not authorize:

- scoring;
- comparison;
- mapping reveal;
- public result integration;
- SIG-002 or another signal attempt;
- Levels 5–9 analysis;
- Covenant or CSR payload work;
- physical or agency profiles;
- shared executable models or response syntax;
- any higher layer;
- carrier selection or design;
- distribution; or
- transmission.
