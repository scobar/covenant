# BBIL-001 — Blind Decoder, Validity, and Custody Protocol

> **BBIL-001 v0.1 — DRAFT BLIND-ITERATION LAB ARCHITECTURE — SYNTHETIC CAPABILITY PROBE ONLY — NO REAL BEACON CANDIDATE, SCORE, HOLDOUT, OR RESULT**

> **Zero Beacon-specific context is intentionally supplied to the blind
> decoder; unavoidable system context, model-training priors, minimum interface
> instructions, hidden backend behavior, and any unproven workspace or
> provider isolation remain disclosed limitations.**

## Frozen neutral instruction

```text
Respond to the complete attached input with your best interpretation. Explain
what you infer, preserve uncertainty, and include plausible alternative
interpretations.
```

The instruction is content-neutral. It supplies no truth key, scorecard,
translation, expected outcome, candidate identity, treatment identity, or
target recovery level.

## Run protocol

1. The packet custodian freezes one candidate packet, its identity, source
   allowlist, context-honesty ledger, and canary commitments.
2. One fresh context receives one candidate packet and the neutral instruction
   only.
3. The decoder returns one final response. No follow-up, clarification,
   correction, private chain-of-thought request, or substantive retry is
   allowed.
4. The exact response and observable run metadata freeze before any validity
   classification.
5. A fresh validity classifier receives only the frozen response, neutral
   instruction, run metadata, and context-honesty ledger.
6. The validity record freezes before scoring begins.
7. Only a technically eligible frozen response may reach its isolated primary
   scorer and independent scratch-before-comparison auditor.

## Per-run custody record

Preserve exactly:

- prompt-packet identity and byte count;
- allowed sources and supplied inputs;
- context-honesty ledger;
- exposed, requested, unavailable, and unverified controls;
- provider/model/interface labels and their verification limits;
- complete final response and output identity;
- canary commitments and mechanical scan booleans;
- tool, repository, network, connected-source, and memory observations;
- validity classification and freeze identity; and
- every deviation, contamination event, refusal, uncertainty, or failure.

A detected context or tool leak is preserved as contamination or protocol
failure. It is never cleaned by rerun or omission. A clean canary result means
only that the declared scan detected no hit; it never proves isolation.

## Validity before scoring

Validity concerns completion, protocol compliance, detected tool or repository
use, detected project-context leakage, and technical validity. It does not
interpret truth or assign a Decoder Level. Scoring truth and scorecards remain
withheld until after the validity record freezes.

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
