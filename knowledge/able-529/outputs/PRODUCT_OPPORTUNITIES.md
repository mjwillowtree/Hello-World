# PRODUCT_OPPORTUNITIES (Ranked)

Updated: 2026-03-10

Scoring used: Impact (1-5), Feasibility (1-5), Compliance risk if wrong (1-5, higher = riskier), Evidence strength (1-5).

| Rank | Opportunity | User problem solved | Evidence | Impact | Feasibility | Compliance constraint | Confidence |
|---:|---|---|---|---:|---:|---|---|
| 1 | **Rollover Evidence Pack + Preflight Validator** | Users initiate 529->ABLE transfers without required earnings/principal docs and hit tax-risk exceptions | Fidelity and Texas ABLE forms both warn that without documentation full rollover may be treated as earnings | 5 | 4 | Must not misstate tax treatment; need jurisdiction-aware disclosures | High |
| 2 | **State-Specific Recapture Guardrails Engine** | Federal-qualified transfer can still trigger state add-back/recapture uncertainty | State matrix shows high variance and unresolved line-level treatment in NJ/PA/etc. | 5 | 3 | Requires continuously updated state forms/instructions and versioning | Medium-High |
| 3 | **Beneficiary/Family Mapping Wizard** | Errors in family-member eligibility relationships create failed or nonqualified rollovers | ABLE for ALL and Texas ABLE forms require explicit same-beneficiary/family-member certifications | 4 | 4 | Must encode IRC family relationship logic correctly and capture attestations | High |
| 4 | **Transfer Ops Tracker (SLA + exception queue)** | Users abandon when transfers stall and status is opaque | Multi-step manual forms/signatures and external custodian dependencies create long opaque wait states | 4 | 3 | Need auditable event log and privacy controls | Medium |
| 5 | **Advisor-safe Citation Pack API** | Teams answer legal questions inconsistently and slowly | Statute vs stale IRS page conflict shows need for authoritative citation blocks | 3 | 4 | Must distinguish controlling vs non-controlling sources in UI | High |

## Opportunity added/re-ranked this run

### Added: Rollover Evidence Pack + Preflight Validator (now Rank #1)
- Why now: confirmed cross-provider operational failure mode where missing documentation causes earnings misclassification risk.
- Product implication: onboarding should gate transfer submission on required doc checklist, with conditional routing (direct rollover vs 60-day path), and explicit warnings on annual contribution limit interactions.

### Core evidence
- Fidelity official ABLE rollover form:
  - https://www.fidelity.com/bin-public/060_www_fidelity_com/documents/customer-service/able-rollover.pdf
- Texas ABLE incoming rollover form:
  - https://www.texasable.org/wp-content/uploads/dlm_uploads/2025/02/TxAble_IncomingRolloverForm_2.13.25_Fillable.pdf
- ABLE for ALL direct rollover form:
  - https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf
