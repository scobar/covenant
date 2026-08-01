# PTR-001 — Public Pair-Execution Authorization Manifest

> **FROZEN PUBLIC D-033 EXECUTION-AUTHORIZATION MANIFEST v0.1 — NONCANONICAL — NO CONDITION SUBMITTED OR RESULT CREATED**

> **PTR-001 v0.1 — MANUAL EXECUTION AUTHORIZED AFTER PUBLIC COMMIT — NO CONDITION SUBMITTED OR RESULT CREATED**

## Authorization state

- Authorization lifecycle:
  `Manual paired execution authorized — not yet begun`
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

## Exact configuration

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

This configuration applies to both opaque conditions and any permitted
same-condition technical retry. D-033 becomes operational only after its
public commit is pushed and local `main` again equals `origin/main`. The
private frozen execution order controls, the operator learns only the next
opaque condition label, and the baseline/treatment mapping remains private.
The first condition's final validity state must freeze before the second
condition is submitted. Scoring, comparison, mapping reveal, unblinding,
public result integration, and SIG-002 remain separate later gates.

## Preparation-session incident classification

During D-033 preparation, several private dependency identity tuples entered
the same-tooling OpenAI Codex transcript. The emitted metadata classes were raw
SHA-256, Git-style blob identity, and byte count. Their exact values and exact
affected private-file subset remain private and are not reproduced here.

- Incident class: nonpublic same-tooling custody/provenance.
- Public repository disclosure: `False`.
- Real Git index disclosure: `False`.
- Google provider disclosure: `False`.
- Order, baseline/treatment mapping, next opaque condition label, raw condition
  content, instruction text, solution content, and scorecard content disclosed:
  `False` on current evidence.
- Zero private disclosure within the Codex preparation session: `Not claimed`.
- The exact affected subset was not reopened; absence of every private packet
  or sequence identity from the transcript is not claimed.
- Frozen private artifacts and all parent, packet, pair, and PTR-001
  preparation commitments: unchanged.
- Pair regeneration or rotation: not authorized.
- Empirical result or Google contamination event: `False`.

Every future private run record must preserve:

```text
NONTRIAL_SAME_TOOLING_METADATA_DISCLOSURE=True
DISCLOSURE_CHANNEL=OpenAI Codex preparation transcript
PUBLIC_REPOSITORY_DISCLOSURE=False
GOOGLE_PROVIDER_DISCLOSURE=False
ORDER_OR_MAPPING_DISCLOSED=False
RAW_CONDITION_CONTENT_DISCLOSED=False
```

## Frozen dependency

| Relative path | Public role | Raw SHA-256 | No-filter Git blob | Bytes | Encoding | Line endings | Final newline |
|---|---|---|---|---:|---|---|---|
| `05-PUBLIC-PAIR-EXECUTION-AUTHORIZATION.md` | Public D-033 manual pair-execution authorization with preparation-session custody/provenance incident | `6e3cd06cb3133a8a47341f2a245182c9f0f0c4983c7d7c04b81e0ff3c93a9e60` | `e3a78a47b918554d17751e1d33de60f4dd82e295` | `11735` | UTF-8 | LF | Yes |

## Public audit outcomes

- Audit A — incident accuracy: `PASS`. The public description matches the
  known preparation report, separates same-tooling transcript custody from
  public and provider exposure, and does not claim that all private dependency
  identities remained unexposed in the Codex session.
- Audit B — trial-validity impact: `PASS`. No Google exposure, opaque-order or
  mapping disclosure, or raw-condition-content disclosure occurred; no frozen
  private artifact or commitment changed; and D-033 remains authorization only
  and methodologically usable with the incident recorded in future provenance.
- Audit C — public secrecy: `PASS`. No emitted tuple value, exact affected
  private filename, private path, execution order, next opaque label, condition
  mapping, raw packet or sequence content, instruction text, solution or
  scorecard content, nonce, or preimage was added publicly.
- Audit D — scope and preservation: `PASS`. Exactly the six authorized public
  records changed in this correction; the other six D-033 working-tree records
  remained byte-exact; D-001 through D-032, D-009, the Founding Ethos, the real
  Git index, and all zero execution/result counts remain unchanged; D-009 is
  Proposed and corrected D-033 is Accepted; and no browser, provider, or model
  execution occurred.

These are same-tooling authorization checks, not empirical or external
validation.
