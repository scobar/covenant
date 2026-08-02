# BBIL-001 — Research Manifest

> **FROZEN BBIL-001 ARCHITECTURE MANIFEST v0.1 — SYNTHETIC CAPABILITY PROBE ONLY — NO REAL BEACON CANDIDATE OR RESULT**

> **BBIL-001 v0.1 — DRAFT BLIND-ITERATION LAB ARCHITECTURE — SYNTHETIC CAPABILITY PROBE ONLY — NO REAL BEACON CANDIDATE, SCORE, HOLDOUT, OR RESULT**

> **Zero Beacon-specific context is intentionally supplied to the blind
> decoder; unavoidable system context, model-training priors, minimum interface
> instructions, hidden backend behavior, and any unproven workspace or
> provider isolation remain disclosed limitations.**

## Frozen dependencies

The manifest contains exactly seventeen dependencies. Raw SHA-256 identifies
the working-tree bytes. The no-filter Git blob is computed with
`git hash-object --no-filters`. Every dependency is strict UTF-8 without BOM,
uses LF only, has exactly one final LF, and is covered by `text: set` and
`eol: lf`.

| Relative path | Role | Raw SHA-256 | No-filter Git blob | Bytes | Encoding | Lines |
| --- | --- | --- | --- | ---: | --- | --- |
| `beacon/BBIL-001/00-PUBLIC-LAB-CHARTER.md` | Public lab charter and authority boundary | `5cfc6cf746131eec15dea2a794398c4f69ea56c52358a1638b3fb6c0b75cd930` | `3a26a5a082304ad2e7f26e9fe16744839393ab93` | `2623` | UTF-8 without BOM | LF only; one final LF |
| `beacon/BBIL-001/01-CONTEXT-HONESTY-AND-BLINDING.md` | Context-honesty ledger and control classification | `fe1bb1b7fa1943d46cb0606b396a6952ad7562e5f9b8ec7e3bb9aa520105baa4` | `72acd1708ce7b068b775322f1dfb4b7005930ce6` | `3793` | UTF-8 without BOM | LF only; one final LF |
| `beacon/BBIL-001/02-SUBAGENT-ROLES-AND-INFORMATION-FLOW.md` | Ten-role information-flow architecture | `59e7397062237bb9188b9e1fe2b71eb0248417bfa0a21f20aeeabb0c5103a62e` | `a5141bbab813547f08d572cb3dc5d2ac4def9bfc` | `4525` | UTF-8 without BOM | LF only; one final LF |
| `beacon/BBIL-001/03-ADAPTIVE-DEVELOPMENT-AND-SEALED-VALIDATION-LANES.md` | Adaptive-development and sealed-validation separation | `be54030211cb64077360d01990df780b3c5da6575bdddfbffec633131282ca1c` | `29ae384c6a22d1c5daafd1b590025278a70a9001` | `3403` | UTF-8 without BOM | LF only; one final LF |
| `beacon/BBIL-001/04-CANDIDATE-GENERATION-AND-EQUIVALENCE-GATES.md` | Candidate construction and equivalence gates | `c8c772057674b258adf0807c4b0bdf0a4e37314e1ae273e95d232b4636ba7961` | `fda4e71bfcc0c49af46645fcc49cd4ed26463089` | `2600` | UTF-8 without BOM | LF only; one final LF |
| `beacon/BBIL-001/05-BLIND-DECODER-VALIDITY-AND-CUSTODY-PROTOCOL.md` | Blind decoder, validity, and custody protocol | `91e456032ddf228db3a680b5e51e450eef5590abf41431d72a849a2428ec2968` | `544d79a5d797922e2ed5c7f115c09322350011c2` | `3364` | UTF-8 without BOM | LF only; one final LF |
| `beacon/BBIL-001/06-SCORING-AUDIT-SELECTION-AND-SUCCESSIVE-HALVING.md` | Scoring hierarchy, audit, selection, and run arithmetic | `d2e3fdf78480cd23c017c3dc68afc2257ac974d73f13e05eab4b6260ab4bb8f2` | `12e272685946fe70c33b46cc745492322c9b393c` | `3286` | UTF-8 without BOM | LF only; one final LF |
| `beacon/BBIL-001/07-CANARY-LEAKAGE-AND-TOOL-CONTROL.md` | Canary, leakage, source, tool, and network controls | `c40646efeef8774490e0c86911925f770d5fbec44b7ef567c029bcc2c50ec57a` | `169aa611056457c4ead9cec249c681b78059e668` | `2899` | UTF-8 without BOM | LF only; one final LF |
| `beacon/BBIL-001/08-SYNTHETIC-CAPABILITY-PROBE-RECORD.md` | Secrecy-safe synthetic probe record | `7c1a8a940c09bca3407a0d0a3a3dac2e1df2a40de2b9ee25eba233fb494fc12c` | `e1b5066646d6fdd5d98b4859ed7dd0b6248decdc` | `4420` | UTF-8 without BOM | LF only; one final LF |
| `beacon/BBIL-001/09-NEXT-GATE-AND-NONEXECUTION.md` | Later-gate sequence and nonexecution boundary | `c02ca6076118887f8b56b16258654233a4089a7ee05b2ceb9a458a53ec14a8cd` | `95ee8d631ba7307ffed96b3a46b8f2c634f0eafe` | `2295` | UTF-8 without BOM | LF only; one final LF |
| `beacon/BBIL-001/templates/CONTEXT-HONESTY-LEDGER-TEMPLATE.txt` | Blank context-honesty ledger | `6e723bcc2b79ac9c1552b0ca659a0cf81ee7248ab8a81349de2d5eacc4ff8bfa` | `6aaf14021c49e87c24438d8dd916dea6f4bc97ba` | `2879` | UTF-8 without BOM | LF only; one final LF |
| `beacon/BBIL-001/templates/CANDIDATE-RECORD-TEMPLATE.md` | Blank candidate record | `b9b967aa26525c0b68a69d2d3b9a8bf50b16cd79963f2e28137326d76ab6579f` | `71b83ca652895d0b36b20c39cd88513f36987e78` | `2146` | UTF-8 without BOM | LF only; one final LF |
| `beacon/BBIL-001/templates/BLIND-DECODER-RUN-TEMPLATE.md` | Blank blind-decoder run record | `a4de15c6cad3fc704db89b870f8f910443e63fc60d7466f14000788bbf2348fe` | `6e7dd1a6f8f08eee80b1c0f54f81a0597e551d14` | `2238` | UTF-8 without BOM | LF only; one final LF |
| `beacon/BBIL-001/templates/VALIDITY-CLASSIFICATION-TEMPLATE.md` | Blank validity classification | `0c76d1adc1f073841eb8aa201fe9e56637789a6405eb6b23b22e4ce372b057b6` | `de74839e0fb2ad97b4233f57982c13ba5cbc4efa` | `1866` | UTF-8 without BOM | LF only; one final LF |
| `beacon/BBIL-001/templates/SCORE-AND-AUDIT-TEMPLATE.md` | Blank categorical score and independent audit | `b23de45cdc00704caee9998cf70fa8fb30ad9fcc97fcc666bfe52ca6a4f1fe54` | `d98a69635bd42e6b251d77d061c03e7c456c9364` | `2241` | UTF-8 without BOM | LF only; one final LF |
| `beacon/BBIL-001/templates/GENERATION-SELECTION-TEMPLATE.md` | Blank anonymous generation selection | `e4f05c6bffbb8c818c7d7ce05ce329e8b8fc264da37182ddd218eec78f7951ac` | `14cb1706b6782f3bc88adba3b290dcef132ef563` | `2277` | UTF-8 without BOM | LF only; one final LF |
| `beacon/BBIL-001/skill/SKILL.md` | Portable workflow reference | `c965825efbb17c7f5f79e7a2e4082afd7fce249a3c87be57386350120e7bdf7b` | `0c4f49b157ec11aa193f1c341a3606e9ea6ae4f4` | `5943` | UTF-8 without BOM | LF only; one final LF |

The manifest does not include its own identity.

## Synthetic probe outcome

```text
PROBE_OUTCOME=PASS WITH LIMITATIONS — no detected leak; one or more isolation controls unverified
ABSOLUTE_ZERO_CONTEXT_CLAIM=False
REAL_CANDIDATE_READINESS=False
REAL_BEACON_RESULT=False
CLEAN_HOLDOUT_EVIDENCE=False
OPENAI_SAME_TOOLING_DEVELOPMENT_EVIDENCE=True
PARENT_CANARY_FOUND=False
WITHHELD_FILE_CANARY_FOUND=False
PROJECT_IDENTIFIER_FOUND=False
TECHNICAL_VALIDITY=Indeterminate
SYNTHETIC_SCORING_AUDIT=PASS — exact agreement
```

## Frozen audit outcomes

- Audit A — context honesty: `PASS`.
- Audit B — architecture and information flow: `PASS`.
- Audit C — scoring, selection, and overfitting: `PASS`.
- Audit D — protected evidence, scope, and nonexecution: `PASS`.

Audit D verified the pre-manifest boundary: exactly six authorized existing
files changed and exactly seventeen authorized dependencies had been created;
this authorized manifest would bring the final new-file count to eighteen.
All protected tracked files outside scope retained their recorded identities,
all thirty-four decision blocks remained exact, and the real Git index
remained clean.

## No later authority

D-035 does not exist and is not consumed by this package. D-034 isolated
scoring remains the next empirical gate. No real candidate, run, validity
classification, score, audit, comparison, mapping reveal, unblinding, public
result, SIG-002 attempt, Levels 5–9 analysis, higher layer, payload, holdout,
carrier, distribution, or transmission is created or authorized.

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
