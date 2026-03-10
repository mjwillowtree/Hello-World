# LEGAL_BASELINE (Federal + State Authority Ladder)

Updated: 2026-03-10

## 1) Authority hierarchy for this knowledge system

When sources conflict, resolve using this order:

1. **Tier 1 (controlling/primary):** statutes, regulations, IRS/SSA/Treasury primary materials, state DOR forms/instructions, official plan disclosure/forms.
2. **Tier 2:** ABLE NRC, major administrators, institutional explainers.
3. **Tier 3:** blogs/forums/secondary commentary.

Implementation rule: if Tier 2/3 conflicts with Tier 1, **Tier 1 controls** and the lower-tier item is logged as stale/conflicting guidance.

## 2) Federal baseline: post-2025 529->ABLE legality

### Quote-ready authority block

From Pub. L. 119-21 (One Big Beautiful Bill Act), Sec. 70117:

> "(a) In General.--Section 529(c)(3)(C)(i)(III) is amended by striking `before January 1, 2026,`."  
> "(b) Effective Date.--The amendment made by this section shall apply to taxable years beginning after December 31, 2025."

Primary source:
- https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm
- https://www.congress.gov/119/plaws/publ21/PLAW-119publ21.pdf

Current codified text cross-check:
- IRC 529 (prelim): https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim
- IRC 529A (prelim): https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529A&num=0&edition=prelim

**Operational interpretation (confidence: High):**
Federal 529->ABLE rollover authority continues after 2025, subject to existing same-beneficiary/family-member and annual ABLE contribution-limit mechanics.

### IRS publication-status check (2025-cycle)
- IRS Publication 970 (2025 web version) currently states that QTP assets can be rolled over to an ABLE account and does not include the former "before January 1, 2026" sunset phrase.
- IRS Instructions for Forms 1099-QA/5498-QA (2025) also include section 529-to-ABLE contribution language without the former sunset date.
- Sources:
  - https://www.irs.gov/publications/p970
  - https://www.irs.gov/instructions/i1099qa

## 3) Conflict log (explicit)

### Conflict C-2026-03-10-01
- Higher authority: Pub. L. 119-21 Sec. 70117 + current USC text.
- Lower authority artifact: IRS legacy newsroom pages still carrying pre-amendment sunset wording.
- Resolution: statute/codified law controls; treat legacy newsroom wording as stale transition content.
- Sources:
  - https://www.irs.gov/newsroom/irs-issues-final-regulations-for-achieving-a-better-life-experience-accounts
  - https://www.irs.gov/newsroom/tax-reform-affects-able-accounts-savers-credit-529-rollovers

### Conflict C-2026-03-10-02
- Apparent conflict: some IRS newsroom pages remain stale, while current IRS publication/instruction pages reflect ongoing 529->ABLE rollover treatment.
- Resolution: prefer statute/codified text first; treat publication/instructions as supportive Tier-1 implementation evidence; isolate newsroom pages as lagging communication artifacts.
- Sources:
  - https://www.irs.gov/publications/p970
  - https://www.irs.gov/instructions/i1099qa
  - https://www.irs.gov/newsroom/tax-reform-affects-able-accounts-savers-credit-529-rollovers

## 4) State baseline examples

### Ohio (line-level pattern)
- Schedule of Adjustments line 4 (addition), line 20 (STABLE deduction), and line 36 (529 deduction) provide explicit state return mapping.
- 2024 instruction text ties addition mechanics to nonqualified distributions and prior deduction history.
- Sources:
  - https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/scheduleofadjustments.pdf
  - https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/it1040-booklet.pdf

### Minnesota (line-flow pattern)
- DOR recapture framework plus TY2025 M1529 line flow provides form-level mapping to return line.
- Sources:
  - https://www.revenue.state.mn.us/education-savings-account-recapture-tax
  - https://www.revenue.state.mn.us/sites/default/files/2025-10/m1529-25-grid.pdf

### Utah (line-code + statute pattern)
- TC-40A instructions map my529 addback to Part 1 code 54 and route total additions to TC-40 line 5.
- Utah Code §59-10-114(1)(d) codifies addback for withdrawn my529 amounts where conditions are met, including reference to IRC §§529(c)/530(d) exceptions.
- Sources:
  - https://incometax.utah.gov/additions/my529-addback
  - https://le.utah.gov/xcode/Title59/Chapter10/C59-10-S114_2025101420251206.html
  - https://files.tax.utah.gov/tax/forms/current/tc-40.pdf

## 5) State-law handling posture

Federal qualified treatment does **not** guarantee state conformity or no-recapture treatment. For implementation, consult `outputs/STATE_MATRIX.csv` by jurisdiction and filing year, with form-level references.

## 6) Open legal unknowns (next closure targets)

1. NJ line-level NJ-1040 instruction treatment for 529->ABLE recapture/add-back.
2. PA line-level PA-40 instruction treatment for 529->ABLE recapture/add-back.
3. Minnesota explicit ABLE carveout confirmation (if any) vs current recapture framework inference.
4. Indiana first-pass line-level mapping for 529/ABLE recapture or add-back treatment.
