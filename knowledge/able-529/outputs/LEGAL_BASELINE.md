# Legal Baseline and Authority Hierarchy (Federal + State)

Updated: 2026-03-10

## 1) Authority hierarchy (must control conflicts)

1. **Tier 1 (controlling):** statute, regulations, IRS/SSA/Treasury primary guidance, official state DOR forms/instructions, official program disclosure docs.
2. **Tier 2 (strong secondary):** ABLE NRC, major administrators/plan operators.
3. **Tier 3 (verification targets):** blogs/forums/commentary.

Conflict rule: when Tier 2/3 conflicts with Tier 1, follow Tier 1 and explicitly log the conflict.

## 2) Federal baseline (quote-ready references)

### Federal rollover continuity after 2025

- Public Law 119-21 amended IRC 529(c)(3)(C)(i)(III) by removing the pre-2026 sunset phrase and includes an effective-date rule for taxable years beginning after 2025.
- Practical consequence: federally qualified 529->ABLE rollover pathway remains available post-2025, subject to IRC conditions (beneficiary relationship and annual ABLE contribution limit interaction).

Primary citations:
- https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm
- https://www.congress.gov/119/plaws/publ21/PLAW-119publ21.pdf
- https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim
- https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529A&num=0&edition=prelim

### Guidance-lag control

- Some IRS newsroom pages still contain legacy pre-2026 sunset framing. These pages are informative but not controlling over later-enacted statute.

Supporting citations:
- https://www.irs.gov/newsroom/irs-issues-final-regulations-for-achieving-a-better-life-experience-accounts
- https://www.irs.gov/newsroom/tax-reform-affects-able-accounts-savers-credit-529-rollovers

## 3) State baseline pattern (example: Ohio, line-level)

Ohio Schedule of Adjustments structure confirms state-level mechanics are explicit and line-dependent:

- Form line mapping:
  - Additions line 4: "529 plan funds used for non-qualified expenses."
  - Deductions line 20: "Amounts contributed to a STABLE account: Ohio's ABLE plan."
  - Deductions line 36: "Amounts contributed to a 529 Plan."

Sources:
- Ohio Schedule of Adjustments (2024):  
  https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/scheduleofadjustments.pdf

Instruction-level trigger language (2024 booklet):

- Line 4 addition applies to 1099-Q 529 distributions where (a) amount not otherwise in federal AGI, (b) not used for qualified higher-education expenses and not death/disability/scholarship exception, and (c) amount was previously deducted as a 529 contribution/tuition credit purchase on Ohio Schedule of Adjustments in prior year(s).
- Line 20 allows STABLE contribution deduction up to annual stated limits/carryforward framework.
- Line 36 allows 529 contribution deduction and carryforward framework.

Source:
- Ohio IT 1040/SD 100 Instruction Booklet (2024):  
  https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/it1040-booklet.pdf

## 4) Compliance implementation note

Do not map federal "qualified rollover" directly into state treatment. Product logic must run:

1. Federal eligibility checks (relationship, limit interaction, timing), then
2. State-specific recapture/add-back and line-level reporting checks, with confidence labels.
