# PRODUCT_OPPORTUNITIES (Ranked)

Updated: 2026-03-10

Scoring basis: user risk impact, decision value, feasibility, compliance defensibility, and evidence strength.

| Rank | Opportunity | User problem solved | Evidence | Impact | Feasibility | Compliance constraint | Confidence |
|---:|---|---|---|---:|---:|---|---|
| 1 | **Rollover Evidence Pack + Preflight Validator** | Users submit transfers without required docs and trigger downstream exceptions | Fidelity + Texas ABLE forms warn missing documentation can cause full amount to be treated as earnings | 5 | 4 | Must not misstate tax treatment; include jurisdiction-aware disclosures | High |
| 2 | **State-aware rollover qualification engine** | Federal-qualified transfer can still trigger state add-back/recapture risk | Ohio line-level evidence plus matrix variance across states | 5 | 3 | Requires versioned state rules with confidence labels | High |
| 3 | **Good-order readiness score + SLA predictor** | Users do not know if submission quality will delay transfer completion | my529 Form 215 gives good-order timing baseline; Form 210 flags source medallion/dependency delays | 4 | 4 | Must avoid guaranteeing completion dates; show confidence ranges and dependency warnings | High |
| 4 | **Beneficiary/family mapping wizard** | Relationship mistakes cause failed/nonqualified rollovers | ABLE for ALL, Texas ABLE, and my529 require explicit family-member attestations | 4 | 4 | Must encode IRC family logic accurately and store attestations | High |
| 5 | **Transfer ops tracker (SLA + exception queue)** | Users abandon when transfer status is opaque | Multi-step manual workflow across institutions plus good-order evidence from my529 forms | 4 | 3 | Requires auditable event trail | Medium-High |
| 6 | **State recapture warning + filing-line helper** | Users miss state filing impacts after rollover | Ohio/Minnesota/Indiana line-level return mapping needs UX support | 4 | 3 | Do not overstate low-confidence states | Medium |

## Newly reinforced by merge

- Cross-provider documentation risk became the strongest shared operational signal.
- State-aware logic remains critical due unresolved NJ/PA line-level treatment.
- Good-order SLA instrumentation is now evidence-backed (my529 form-level timing statement).
