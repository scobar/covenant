# BBIL-001 — Context Honesty and Blinding

> **BBIL-001 v0.1 — DRAFT BLIND-ITERATION LAB ARCHITECTURE — SYNTHETIC CAPABILITY PROBE ONLY — NO REAL BEACON CANDIDATE, SCORE, HOLDOUT, OR RESULT**

> **Zero Beacon-specific context is intentionally supplied to the blind
> decoder; unavoidable system context, model-training priors, minimum interface
> instructions, hidden backend behavior, and any unproven workspace or
> provider isolation remain disclosed limitations.**

## Context-honesty distinctions

Every later run record must distinguish:

1. context intentionally supplied in the run packet;
2. context withheld by instruction;
3. context technically prevented by an exposed control;
4. context whose absence is merely requested;
5. context whose absence is unverified; and
6. unavoidable system context and model-training priors.

Requested absence is not enforced absence. An unavailable or unverified
control must stay labeled unavailable or unverified. A clean canary scan is
evidence of no detected leak, not proof of absolute isolation.

## Frozen context-honesty ledger vocabulary

```text
BEACON_PROJECT_CONTEXT_INTENTIONALLY_SUPPLIED=False
COVENANT_CONTEXT_INTENTIONALLY_SUPPLIED=False
REPOSITORY_CONTEXT_INTENTIONALLY_SUPPLIED=False
PARENT_CONVERSATION_CONTEXT_INTENTIONALLY_SUPPLIED=False
PRIOR_RUN_CONTEXT_INTENTIONALLY_SUPPLIED=False
OTHER_CANDIDATE_CONTEXT_INTENTIONALLY_SUPPLIED=False
OTHER_DECODER_OUTPUT_CONTEXT_INTENTIONALLY_SUPPLIED=False
SCORECARD_CONTEXT_INTENTIONALLY_SUPPLIED=False
SOLUTION_CONTEXT_INTENTIONALLY_SUPPLIED=False
EXPECTED_OUTCOME_CONTEXT_INTENTIONALLY_SUPPLIED=False
TREATMENT_IDENTITY_CONTEXT_INTENTIONALLY_SUPPLIED=False
BASELINE_TREATMENT_MAPPING_CONTEXT_INTENTIONALLY_SUPPLIED=False
WEB_CONTEXT_INTENTIONALLY_SUPPLIED=False
CONNECTED_SOURCE_CONTEXT_INTENTIONALLY_SUPPLIED=False
MEMORY_CONTEXT_INTENTIONALLY_SUPPLIED=False
TOOLS_INTENTIONALLY_SUPPLIED=False

SYSTEM_CONTEXT_PRESENT=True
MODEL_TRAINING_PRIORS_PRESENT=True
MINIMUM_INTERFACE_INSTRUCTION_PRESENT=True
BACKEND_IDENTITY_UNPROVEN=True
PROVIDER_RETENTION_UNPROVEN=True
FRESH_NO_HISTORY_CONTEXT_REQUESTED=True
ABSOLUTE_ZERO_CONTEXT_CLAIM=False
```

## Exposed mechanism fields at preparation time

```text
SUBAGENT_MECHANISM=collaboration.spawn_agent
NO_HISTORY_CONTROL=fork_turns="none" explicit exposed control
PARENT_TURN_INHERITANCE=disabled by exposed control
REPOSITORY_ACCESS_CONTROL=unavailable
TOOL_ACCESS_CONTROL=unavailable
NETWORK_ACCESS_CONTROL=unavailable
WORKSPACE_ISOLATION_UNPROVEN=True
PROVIDER_ISOLATION_UNPROVEN=True
REAL_CANDIDATE_READINESS=False
```

`fork_turns="none"` technically prevents parent-turn inheritance through the
exposed spawn control. The exposed mechanism has no per-agent repository
allowlist and no per-agent tool or network disable field. Instructions can
request nonuse, but this package does not relabel that request as enforcement.

## Run-level requirements

Each run freezes its complete ledger before interpretation. Any supplied
source, unavoidable interface instruction, exposed control, requested
restriction, unverified absence, or detected leak is recorded separately.
Later discovery of exposure amends contamination classification without
rewriting the frozen output.

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
