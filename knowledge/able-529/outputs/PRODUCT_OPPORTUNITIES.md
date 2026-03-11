# PRODUCT_OPPORTUNITIES (Ranked)

Updated: 2026-03-11

Scoring basis: user risk impact, decision value, feasibility, compliance defensibility, and evidence strength.

| Rank | Opportunity | User problem solved | Evidence | Impact | Feasibility | Compliance constraint | Confidence |
|---:|---|---|---|---:|---:|---|---|
| 1 | **Rollover Evidence Pack + Preflight Validator** | Users submit transfers without required docs and trigger downstream exceptions | Fidelity + Texas ABLE forms warn missing documentation can cause full amount to be treated as earnings | 5 | 4 | Must not misstate tax treatment; include jurisdiction-aware disclosures | High |
| 2 | **State-aware rollover qualification engine** | Federal-qualified transfer can still trigger state add-back/recapture risk | Indiana DOR Bulletin #98 destination-specific rule + Ohio line-level evidence + matrix variance | 5 | 3 | Requires versioned state rules with destination-plan logic and confidence labels | High |
| 3 | **Beneficiary/family mapping wizard** | Relationship mistakes cause failed/nonqualified rollovers | ABLE for ALL and ABLEnow require explicit family-member attestations | 4 | 4 | Must encode IRC family logic accurately and store attestations | High |
| 4 | **Signature-guarantee and limits gate** | Users hit avoidable rejects/delays due source-plan guarantee requirements or destination limits | PA ABLE direct rollover form documents Medallion-trigger path and destination limit rejection behavior | 4 | 4 | Must display conditional requirements without overstating universal rules | High |
| 5 | **Transfer ops tracker (SLA + exception queue)** | Users abandon when transfer status is opaque | Multi-step manual workflow across institutions | 4 | 3 | Requires auditable event trail | Medium |
| 6 | **State recapture warning + filing-line helper** | Users miss state filing impacts after rollover | Indiana/Ohio/Minnesota line-level return mapping needs UX support | 4 | 3 | Do not overstate low-confidence states | Medium |

## Newly reinforced this run

- Cross-provider documentation risk became the strongest shared operational signal.
- Destination-specific state logic (Indiana in-state ABLE exception) is now validated as a live product requirement.
- Signature-guarantee and destination-limit checks now have Tier-1 workflow evidence (PA ABLE).
