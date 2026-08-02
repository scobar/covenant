# BBIL-001 — Adaptive Development and Sealed Validation Lanes

> **BBIL-001 v0.1 — DRAFT BLIND-ITERATION LAB ARCHITECTURE — SYNTHETIC CAPABILITY PROBE ONLY — NO REAL BEACON CANDIDATE, SCORE, HOLDOUT, OR RESULT**

> **Zero Beacon-specific context is intentionally supplied to the blind
> decoder; unavoidable system context, model-training priors, minimum interface
> instructions, hidden backend behavior, and any unproven workspace or
> provider isolation remain disclosed limitations.**

## Lane separation

| Property | Adaptive development lane | Sealed validation lane |
| --- | --- | --- |
| Evidence class | Same-tooling OpenAI/Codex development evidence | Separately sealed validation evidence |
| Adaptation | Permitted only under frozen generation rules | Prohibited after design freeze |
| Candidate exposure | Every exposed candidate is provider-exposed | Fresh surface realization frozen before provider selection where feasible |
| Feedback | High-level frozen failure families and constraints may inform a later generation | No adaptive feedback returns to the tested design |
| Raw outputs | Withheld from later candidate designers where required | Preserved under separate custody and contamination records |
| Provider | Same tooling permitted and disclosed | Separate provider/model where practical |
| Scoring | Independent validity, scoring, and audit records | Independent scoring and contamination records |
| Reporting | Always labeled adaptive development evidence | Exposure-stratified; provider independence claimed only when established |

## Adaptive development lane

- Repeated adaptation is allowed only under rules frozen before the
  generation begins.
- Every candidate exposed to Codex or another provider is permanently marked
  provider-exposed.
- Adaptive results never count as clean holdout evidence.
- Raw confirmation outputs remain unavailable to later candidate-design
  subagents where the generation rule requires that separation.
- At most two adaptive generations may occur before an explicit later
  architectural review.
- A favorable output, majority, hidden scalar, or unregistered objective may
  not drive selection.

## Sealed validation lane

- Freeze a fresh surface realization before provider selection where
  feasible.
- Permit no adaptive feedback, candidate rewrite, or favorable retry after
  freeze.
- Use a separate provider/model where practical and preserve the exact
  configuration and exposure chronology.
- Preserve independent scoring, audit, commitment, and contamination records.
- Report evidence by exposure class rather than silently pooling it.
- Never infer universal decodability from finite validation.

The lanes may answer related questions, but their evidence is not
interchangeable. Passing the adaptive lane never creates sealed-validation
authority.

## Common status

- Lifecycle: `Architecture prepared — real-candidate execution not authorized`
- Real Beacon candidate designs: `0`
- Real blind-decoder runs: `0`
- Real validity classifications: `0`
- Real scores: `0`
- Real score audits: `0`
- Adaptive generations: `0`
- Confirmation rounds: `0`
- Sealed validations: `0`
- New holdouts: `0`
- Provider-independent replications: `0`
- SIG-002 attempts: `0`
- Levels 5–9 analyses: `0`
- Carriers: `0`
- Transmissions: `0`
- Synthetic capability probes: `1`
- Authorized incremental spend: `USD 0`
