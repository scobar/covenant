# PTR-001 — Public Isolated-Scoring Authorization Manifest

> **FROZEN PUBLIC D-034 SCORING-AUTHORIZATION MANIFEST v0.1 — NONCANONICAL — NO SCORE, COMPARISON, OR UNBLINDING CREATED**

> **PTR-001 v0.1 — ISOLATED CONDITION SCORING AUTHORIZED AFTER PUBLIC COMMIT — NO SCORE, COMPARISON, OR UNBLINDING CREATED**

## Authorization state

- Authorization lifecycle:
  `Isolated condition scoring authorized — not yet begun`
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

The two immutable opaque outputs and their validity freezes exist privately.
This manifest freezes only the public authorization for a later, separately
bounded private scoring task after reviewed publication and clean
`main`/`origin/main` parity. It creates no score or result.

## Frozen dependency

| Relative path | Public role | Raw SHA-256 | No-filter Git blob | Bytes | Encoding | Line endings | Final newline |
|---|---|---|---|---:|---|---|---|
| `07-PUBLIC-ISOLATED-SCORING-AUTHORIZATION.md` | Public D-034 isolated opaque-condition scoring authorization and nonauthorization boundary | `615773a8e94c2f7a2f9da3977719a60c3e08a1f6ed93e2a8229566b5ae172587` | `d34aa9cb301d2459db0f5084e606a05ba62d2774` | `8928` | UTF-8 without BOM | LF only | Exactly one LF |

## Public audit outcomes

- Audit A — scoring authorization and chronology: `PASS`. Scoring remains
  gated on reviewed public commit, push, and clean parity; both conditions are
  valid and eligible with no retry; isolated primaries and separate auditors
  use scratch-before-comparison; both score freezes precede D-035 comparison;
  and mapping remains withheld.
- Audit B — secrecy: `PASS`. The changed public surface contains no private
  path, raw response, solution, scorecard detail, sequence, output identity,
  opaque score association, execution order, mapping, private manifest
  identity, nonce, preimage, or predicted or actual score.
- Audit C — lifecycle and registry consistency: `PASS`. The valid and eligible
  condition counts, zero-retry state, D-034 lifecycle, zero score/result state,
  decision statuses, and unchanged public-attempt count agree across the live
  public records.
- Audit D — protected evidence and non-scoring: `PASS`. Prior frozen public and
  private sources, D-001 through D-033, D-009, the Founding Ethos, and the real
  Git index remain unchanged; no private file changed; and no scoring,
  comparison, mapping access, unblinding, public result, SIG-002, Levels 5–9,
  higher-layer, carrier, distribution, or transmission work occurred.

These are same-tooling authorization checks, not scoring, empirical evidence,
or external validation.

## Frozen method boundary

Each condition requires one fresh no-history primary scorer and one different
fresh no-history auditor. Each auditor independently recomputes and freezes a
categorical Levels 0–4 scratch vector before reading its condition's primary
score record. No aggregate score is permitted. Both condition-specific score
freezes must complete before any cross-condition comparison. D-035 is required
for opaque comparison, and a later separate decision is required before
mapping reveal.

D-034 does not authorize scoring in this documentation task, comparison,
mapping access or reveal, unblinding, public result integration, SIG-002,
Levels 5–9, higher-layer work, carrier, distribution, or transmission.
