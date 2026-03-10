# PRODUCT_OPPORTUNITIES (Ranked)

Updated: 2026-03-10

Scoring basis: user risk impact, decision value, feasibility, compliance defensibility, and evidence strength.

| Rank | Opportunity | User problem solved | Evidence | Impact | Feasibility | Compliance constraint | Confidence |
|---:|---|---|---|---:|---:|---|---|
| 1 | **Rollover Evidence Pack + Preflight Validator** | Users submit transfers without required docs and trigger downstream exceptions | Fidelity + Texas ABLE forms warn missing documentation can cause full amount to be treated as earnings | 5 | 4 | Must not misstate tax treatment; include jurisdiction-aware disclosures | High |
| 2 | **State-aware rollover qualification engine** | Federal-qualified transfer can still trigger state add-back/recapture risk | Ohio line-level evidence plus matrix variance across states | 5 | 3 | Requires versioned state rules with confidence labels | High |
| 3 | **Beneficiary/family mapping wizard** | Relationship mistakes cause failed/nonqualified rollovers | ABLE for ALL and Texas ABLE require explicit relationship certifications | 4 | 4 | Must encode IRC family logic accurately and store attestations | High |
| 4 | **Destination-sensitive state routing guardrail** | Users assume all 529->ABLE destinations are equivalent even when state credit recapture differs by destination plan | Indiana IB98 differentiates Indiana ABLE destination vs other ABLE programs for qualified/nonqualified treatment | 5 | 3 | Requires state-specific destination logic and tax-year versioning | High |
| 5 | **Transfer ops tracker (SLA + exception queue)** | Users abandon when transfer status is opaque | Multi-step manual workflow across institutions | 4 | 3 | Requires auditable event trail | Medium |
| 6 | **State recapture warning + filing-line helper** | Users miss state filing impacts after rollover | Ohio/Minnesota/Indiana line-level return mapping needs UX support | 4 | 3 | Do not overstate low-confidence states | Medium |

## Newly reinforced by merge

- Cross-provider documentation risk became the strongest shared operational signal.
- State-aware logic remains critical due unresolved NJ/PA line-level treatment.
- Indiana now adds a new pattern: destination plan choice itself can change recapture outcome.
