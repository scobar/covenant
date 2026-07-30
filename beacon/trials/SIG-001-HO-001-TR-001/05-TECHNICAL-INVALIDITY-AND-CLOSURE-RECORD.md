# SIG-001-HO-001-TR-001 — Technical Invalidity and Closure Record

> **TR-001 CLOSED INCOMPLETE — ONE TECHNICAL-INVALIDITY RUN — NO VALID DECODER OUTPUT**

## Identity and Final State

- Trial ID: `SIG-001-HO-001-TR-001`
- Version: `0.1`
- Parent attempt: `SIG-001 v0.1`
- Parent holdout: `SIG-001-HO-001 v0.1`
- Provider: `Anthropic`
- Displayed model label: `Fable 5`
- Interface: `claude.ai standard Chat`
- Previous lifecycle: `Prepared and authorized — not executed`
- Final lifecycle: `Closed incomplete — technical invalidity`
- Run attempts: `1`
- Valid runs: `0`
- Technical-invalidity runs: `1`
- Final outputs: `0`
- Scorable outputs: `0`
- Scores: `0`
- Reveals: `0`
- Technical retries used: `0`
- Remaining retry: `Retired unused by D-024`
- Model substitutions: `0`
- Validity classification: `Invalid — technical`

## Incident Record

The exact frozen packet was submitted once. Anthropic’s provider safeguard
interrupted processing before a completed final response was produced. A
private provider-visible partial trace was preserved in nineteen screenshots.
The screenshots, their names, their identities, and their content remain
private.

The partial trace is private incident evidence, not a completed decoder
response. It is not scorable and was not used to alter SIG-001, HO-001, the
frozen scorecard, the trial policy, or SIG-001-HO-002. It was not supplied to
another decoder. No claim is made about how far Fable decoded the sequence,
and no claim is made that another Fable run would necessarily fail.

## Closure, Retry, and Exposure

D-024 retires the optional technical retry rather than exercising it. Sonnet
was not substituted into this trial, and no later output may be inserted into
the closed historical record.

HO-001 remains cryptographically committed, immutable, and publicly
unrevealed. Its exposure classification is now
`Known Anthropic provider-side exposure` because its exact sequence reached
Anthropic’s platform and received provider-side processing before
interruption.

That classification does not prove cross-session memory, cross-model
transfer, training ingestion, retrieval exposure, a successful decode, or
higher-level understanding. It does mean same-provider isolation cannot be
assumed and HO-001 is no longer the strongest contamination-reduced choice
for a later Anthropic trial.

## Evidence and Scope Boundary

No completed final response, valid decoder output, scorable output, score,
reveal, or empirical decode rate exists. The invalid run enters neither an
empirical numerator nor denominator.

The frozen preparation records 00 through 04 remain exact historical
preparation evidence. This closure changes no candidate, Founding Ethos,
signal-attempt stream, holdout commitment, preparation packet, scorecard,
case, scenario, review, BSR-001, CSR-001, ERX-001, or PX-001 record.

No physical, agency, moral, Covenant, CSR, response, carrier, distribution, or
transmission inference follows. No Scott, ChatGPT, Codex, Anthropic, Fable,
Sonnet, operator, decoder, scorer, or future model has final interpretive
authority.
