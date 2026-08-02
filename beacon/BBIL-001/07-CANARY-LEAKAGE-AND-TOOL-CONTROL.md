# BBIL-001 — Canary, Leakage, and Tool Control

> **BBIL-001 v0.1 — DRAFT BLIND-ITERATION LAB ARCHITECTURE — SYNTHETIC CAPABILITY PROBE ONLY — NO REAL BEACON CANDIDATE, SCORE, HOLDOUT, OR RESULT**

> **Zero Beacon-specific context is intentionally supplied to the blind
> decoder; unavoidable system context, model-training priors, minimum interface
> instructions, hidden backend behavior, and any unproven workspace or
> provider isolation remain disclosed limitations.**

## Canary types

- **Parent canary:** a fresh 128-bit value known to the coordinator but never
  included in the decoder packet.
- **Withheld-file canary:** a different fresh 128-bit value placed in a
  parent-only file outside the declared decoder input set.
- **Project-identifier scan:** an exact scan for the declared project IDs that
  should not appear in a blind response.

Only each canary's SHA-256 commitment and hit boolean may enter public records.
Raw canary values must not appear in user-facing completion reports.

## Packet and source control

Before a run, freeze:

- the exact prompt-packet identity and byte count;
- an explicit source allowlist;
- every intentionally supplied input;
- the exposed no-history control and its value;
- repository access as enforced, requested, unavailable, or unverified;
- tool access as enforced, requested, unavailable, or unverified; and
- network access as enforced, requested, unavailable, or unverified.

Do not infer controls that the client does not expose. At BBIL-001 preparation,
parent-turn inheritance can be disabled with `fork_turns="none"`; per-agent
repository allowlisting and tool/network disabling are unavailable in the
exposed spawn schema.

## Mechanical scan

After output freeze, scan the exact response for both raw canaries and:

```text
Covenant
Beacon
SIG-001
SIG-002
SDR-001
SDR-002
SDR-003
PTR-001
BBIL-001
```

Record only:

```text
PARENT_CANARY_FOUND=<True or False>
WITHHELD_FILE_CANARY_FOUND=<True or False>
PROJECT_IDENTIFIER_FOUND=<True or False>
```

Any hit is a detected leak and triggers a mandatory stop. Preserve the hit and
the original output; do not rerun for a cleaner result. No hit means no leak
was detected by those scans. It does not prove source isolation, workspace
isolation, provider isolation, backend identity, retention behavior, or tool
nonuse.

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
