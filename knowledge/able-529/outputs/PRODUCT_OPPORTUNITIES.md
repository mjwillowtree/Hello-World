# PRODUCT_OPPORTUNITIES (Ranked)

Updated: 2026-03-11

Scoring basis: user risk impact, decision value, feasibility, compliance defensibility, and evidence strength.

| Rank | Opportunity | User problem solved | Evidence | Impact | Feasibility | Compliance constraint | Confidence |
|---:|---|---|---|---:|---:|---|---|
| 1 | **Rollover Evidence Pack + Preflight Validator** | Users submit transfers without required docs and trigger downstream exceptions | Fidelity + Texas ABLE forms warn missing documentation can cause full amount to be treated as earnings | 5 | 4 | Must not misstate tax treatment; include jurisdiction-aware disclosures | High |
| 2 | **State-aware rollover qualification engine** | Federal-qualified transfer can still trigger state add-back/recapture risk | Ohio line-level evidence plus matrix variance across states | 5 | 3 | Requires versioned state rules with confidence labels | High |
| 3 | **Beneficiary/family mapping wizard** | Relationship mistakes cause failed/nonqualified rollovers | ABLE for ALL and Texas ABLE require explicit relationship certifications | 4 | 4 | Must encode IRC family logic accurately and store attestations | High |
| 4 | **Rollover cooldown + closure guardrail** | Users start ineligible transfers that violate one-per-12-month or 60-day closure rules | STABLE rollover form and FAQ require 12-month cadence and 60-day old-account closure assertions | 5 | 4 | Must capture attestations and enforce jurisdiction/program-specific exceptions | High |
| 5 | **Transfer ops tracker (SLA + exception queue)** | Users abandon when transfer status is opaque | Multi-step manual workflow across institutions | 4 | 3 | Requires auditable event trail | Medium |
| 6 | **State recapture warning + filing-line helper** | Users miss state filing impacts after rollover | Ohio/Minnesota/NJ style line-level return mapping needs UX support | 4 | 3 | Do not overstate low-confidence states | Medium |

## Newly reinforced this run

- Cross-provider documentation risk became the strongest shared operational signal.
- NJ line-level closure and Utah code-level addback mapping increased confidence in form-line helper viability.
- Cooldown/closure gating is now validated by official STABLE rollover workflow requirements.
