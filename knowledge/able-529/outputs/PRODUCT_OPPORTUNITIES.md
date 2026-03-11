# PRODUCT_OPPORTUNITIES (Ranked)

Updated: 2026-03-11

Scoring basis: user risk impact, decision value, feasibility, compliance defensibility, and evidence strength.

| Rank | Opportunity | User problem solved | Evidence | Impact | Feasibility | Compliance constraint | Confidence |
|---:|---|---|---|---:|---:|---|---|
| 1 | **State recapture tripwire engine (jurisdiction + filing year)** | Federally qualified flow can still create state recapture tax surprise | Indiana IN-CR explicitly treats Indiana529->ABLE rollover as nonqualified recapture event; Ohio/Minnesota also show state-specific mechanics | 5 | 3 | Must track state form-year drift and confidence; route unresolved states to review | High |
| 2 | **Rollover Evidence Pack + Preflight Validator** | Users submit transfers without required docs and trigger downstream exceptions | Fidelity + Texas ABLE forms warn missing documentation can cause full amount to be treated as earnings | 5 | 4 | Must not misstate tax treatment; include jurisdiction-aware disclosures | High |
| 3 | **Beneficiary/family mapping wizard** | Relationship mistakes cause failed/nonqualified rollovers | ABLE for ALL and STABLE forms require same-beneficiary/family-member logic and attestations | 4 | 4 | Must encode IRC family logic accurately and store attestations | High |
| 4 | **Cap budget guardrail + over-limit rejection prevention** | Transfers can be rejected when annual limit headroom is insufficient | STABLE form states over-limit contributions are rejected in full | 4 | 4 | Must include contribution aggregation/attestation across external contributors | Medium-High |
| 5 | **Transfer ops tracker (SLA + exception queue)** | Users abandon when transfer status is opaque | Multi-step manual workflow across institutions | 4 | 3 | Requires auditable event trail | Medium |

## Newly reinforced this run

- Indiana introduced a hard evidence point that federal-qualified logic alone is unsafe for state outcomes.
- STABLE operational docs reinforced notarization and annual-limit rejection as pre-submit blockers.
