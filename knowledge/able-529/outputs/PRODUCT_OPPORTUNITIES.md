# PRODUCT_OPPORTUNITIES (Ranked)

Updated: 2026-03-11

Scoring basis: user risk impact, decision value, feasibility, compliance defensibility, and evidence strength.

| Rank | Opportunity | User problem solved | Evidence | Impact | Feasibility | Compliance constraint | Confidence |
|---:|---|---|---|---:|---:|---|---|
| 1 | **Rollover Evidence Pack + Preflight Validator** | Users submit transfers without required docs and trigger downstream exceptions | Fidelity + Texas ABLE forms warn missing documentation can cause full amount to be treated as earnings | 5 | 4 | Must not misstate tax treatment; include jurisdiction-aware disclosures | High |
| 2 | **State-aware rollover qualification engine** | Federal-qualified transfer can still trigger state add-back/recapture risk | Ohio line-level evidence plus matrix variance across states | 5 | 3 | Requires versioned state rules with confidence labels | High |
| 3 | **Rollover clock + closure compliance monitor** | Users miss 60-day windows and old-account closure conditions that can break qualified status | ABLE United form sets 60-day funding/closure constraints and 12-month rollover cadence limits | 5 | 3 | Requires event timestamps, institution acknowledgments, and compliant warning language | High |
| 4 | **Beneficiary/family mapping wizard** | Relationship mistakes cause failed/nonqualified rollovers | ABLE for ALL, Texas ABLE, and ABLE United require explicit relationship certifications | 4 | 4 | Must encode IRC family logic accurately and store attestations | High |
| 5 | **Transfer ops tracker (SLA + exception queue)** | Users abandon when transfer status is opaque | Multi-step manual workflow across institutions plus closure-dependent qualification risk | 4 | 3 | Requires auditable event trail | Medium-High |
| 6 | **State recapture warning + filing-line helper** | Users miss state filing impacts after rollover | Ohio/Minnesota/NJ/PA style return-line mapping needs UX support | 4 | 3 | Do not overstate low-confidence states | Medium |

## Newly reinforced in latest run

- Cross-provider documentation risk became the strongest shared operational signal.
- 60-day rollover timing + source-account closure is now a first-class qualification control signal.
- State-aware logic remains critical because Utah still relies on IRC-exception inference and several states remain unresolved.
