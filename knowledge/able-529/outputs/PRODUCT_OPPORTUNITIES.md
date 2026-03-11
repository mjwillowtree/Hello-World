# PRODUCT_OPPORTUNITIES (Ranked)

Updated: 2026-03-11

Scoring basis: user risk impact, decision value, feasibility, compliance defensibility, and evidence strength.

| Rank | Opportunity | User problem solved | Evidence | Impact | Feasibility | Compliance constraint | Confidence |
|---:|---|---|---|---:|---:|---|---|
| 1 | **Rollover Evidence Pack + Preflight Validator** | Users submit transfers without required docs and trigger downstream exceptions | Fidelity + Texas ABLE forms warn missing documentation can cause full amount to be treated as earnings | 5 | 4 | Must not misstate tax treatment; include jurisdiction-aware disclosures | High |
| 2 | **State-aware rollover qualification engine** | Federal-qualified transfer can still trigger state add-back/recapture risk | Ohio line-level evidence plus matrix variance across states | 5 | 3 | Requires versioned state rules with confidence labels | High |
| 3 | **Destination-plan routing guardrail (state-specific)** | Users unknowingly choose rollover destinations that trigger state credit recapture | Indiana IB98 distinguishes transfers to Indiana ABLE vs other ABLE programs for recapture treatment | 5 | 3 | Must show state-year caveats and avoid individualized tax advice claims | High |
| 4 | **Beneficiary/family mapping wizard** | Relationship mistakes cause failed/nonqualified rollovers | ABLE for ALL and Texas ABLE require explicit relationship certifications | 4 | 4 | Must encode IRC family logic accurately and store attestations | High |
| 5 | **Transfer ops tracker (SLA + exception queue + 60-day clock)** | Users abandon when transfer status is opaque and can miss closure deadlines | ABLE United imposes 60-day closure condition and documentation-dependent earnings treatment | 4 | 3 | Requires auditable event trail and deadline escalation | Medium-High |
| 6 | **State recapture warning + filing-line helper** | Users miss state filing impacts after rollover | Ohio/Minnesota/Indiana line-level return mapping needs UX support | 4 | 3 | Do not overstate low-confidence states | Medium |

## Newly reinforced this run

- Cross-provider documentation risk became the strongest shared operational signal.
- State-aware logic remains critical due unresolved NJ/PA line-level treatment.
- Indiana shows a high-value destination-specific recapture branch (Indiana ABLE vs non-Indiana ABLE).
- ABLE United confirms a hard 60-day closure timer as a product-control requirement, not just education copy.
