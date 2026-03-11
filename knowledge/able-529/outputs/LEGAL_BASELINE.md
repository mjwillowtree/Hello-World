# LEGAL_BASELINE (Federal + State Authority Ladder)

Updated: 2026-03-11

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

## 3) Conflict log (explicit)

### Conflict C-2026-03-10-01
- Higher authority: Pub. L. 119-21 Sec. 70117 + current USC text.
- Lower authority artifact: IRS legacy newsroom pages still carrying pre-amendment sunset wording.
- Resolution: statute/codified law controls; treat legacy newsroom wording as stale transition content.
- Sources:
  - https://www.irs.gov/newsroom/irs-issues-final-regulations-for-achieving-a-better-life-experience-accounts
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

### Indiana (destination-sensitive qualified treatment)
- Indiana DOR Information Bulletin #98 (Jan 2026) defines transfers to an **Indiana ABLE 529A savings plan** (beginning in 2024) as qualified withdrawals.
- The same bulletin states that, for 2024 and later, transfers from Indiana529 to an ABLE account **other than Indiana ABLE 529A** are nonqualified for credit-recapture purposes.
- Recapture repayment reporting is mapped to Schedule IN-CR and then to Schedule 4 (IT-40) / Schedule E (IT-40PNR).
- Sources:
  - https://www.in.gov/dor/files/ib98.pdf
  - https://forms.in.gov/Download.aspx?id=16907

### Utah (addback logic keyed to IRC exceptions)
- TY2025 Utah TC-40 instructions include TC-40A Part 1 code 54 (my529 addback) and direct filers to add back withdrawals not used for qualified education expenses that do not meet IRC 529(c)/530(d) exceptions.
- This forms a state implementation pattern where treatment depends on whether the rollover fits IRC-qualified exceptions.
- Sources:
  - https://tax.utah.gov/forms/current/tc-40inst.pdf
  - https://tax.utah.gov/forms/current/tc-40a.pdf

## 5) State-law handling posture

Federal qualified treatment does **not** guarantee state conformity or no-recapture treatment. For implementation, consult `outputs/STATE_MATRIX.csv` by jurisdiction and filing year, with form-level references.

## 6) Open legal unknowns (next closure targets)

1. NJ line-level NJ-1040 instruction treatment for 529->ABLE recapture/add-back.
2. PA line-level PA-40 instruction treatment for 529->ABLE recapture/add-back.
3. Minnesota explicit ABLE carveout confirmation (if any) vs current recapture framework inference.
4. Indiana exact Schedule 4 line number for 529 recapture repayment entry (IB98 names schedule, not line).
