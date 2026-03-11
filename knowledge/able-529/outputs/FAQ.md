# FAQ (High-frequency + Adversarial)

Updated: 2026-03-11

## 1) Is 529->ABLE rollover still federally allowed after 2025?
**Answer:** Yes, based on Pub. L. 119-21 Sec. 70117 removing the sunset phrase and applying to taxable years beginning after 2025.  
**Confidence:** High  
**Sources:**  
- https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm  
- https://www.congress.gov/119/plaws/publ21/PLAW-119publ21.pdf  
- https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim

## 2) If an IRS newsroom page still shows the old sunset, which source controls?
**Answer:** Enacted statute/codified law controls over stale newsroom content.  
**Confidence:** High  
**Sources:**  
- https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm  
- https://www.irs.gov/newsroom/irs-issues-final-regulations-for-achieving-a-better-life-experience-accounts  
- https://www.irs.gov/newsroom/tax-reform-affects-able-accounts-savers-credit-529-rollovers

## 3) Does federal qualification guarantee no state recapture?
**Answer:** No. State treatment can diverge by jurisdiction and tax year.  
**Confidence:** High  
**Sources:**  
- `outputs/STATE_MATRIX.csv`  
- https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/it1040-booklet.pdf

## 4) What commonly causes rollover operational failure?
**Answer:** Missing earnings/principal documentation and relationship/signature errors.  
**Confidence:** High  
**Sources:**  
- https://www.fidelity.com/bin-public/060_www_fidelity_com/documents/customer-service/able-rollover.pdf  
- https://www.texasable.org/wp-content/uploads/dlm_uploads/2025/02/TxAble_IncomingRolloverForm_2.13.25_Fillable.pdf  
- https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf

## 5) Are same-beneficiary/family-member constraints operationally enforced?
**Answer:** Yes. Official forms require explicit attestation/certification fields.  
**Confidence:** High  
**Sources:**  
- https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf  
- https://www.texasable.org/wp-content/uploads/dlm_uploads/2025/02/TxAble_IncomingRolloverForm_2.13.25_Fillable.pdf

## 6) What line-level state examples are currently captured?
**Answer:** Ohio (Schedule of Adjustments line mapping) and Minnesota (M1529 flow to M1) are now represented as examples.  
**Confidence:** Medium-High  
**Sources:**  
- https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/scheduleofadjustments.pdf  
- https://www.revenue.state.mn.us/sites/default/files/2025-10/m1529-25-grid.pdf

## 7) Adversarial: Can we auto-approve transfers if names match?
**Answer:** No. Cap checks, relationship logic, documentation, and state treatment still must pass.  
**Confidence:** High  
**Sources:**  
- https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529A&num=0&edition=prelim  
- `outputs/STATE_MATRIX.csv`

## 8) Are all 50-state line-level rules complete?
**Answer:** No. Matrix coverage exists for all jurisdictions, but many rows are still low-confidence placeholders.  
**Confidence:** High  
**Sources:**  
- `outputs/HUB.md`  
- `outputs/STATE_MATRIX.csv`

## 9) Are there IRS primary materials (not just newsroom posts) that support 529->ABLE rollovers now?
**Answer:** Yes. IRS Publication 970 chapter content and current Form 1099-Q instructions both describe QTP->ABLE rollovers, including annual-limit and 60-day mechanics, and do not show the old sunset phrase in the extracted sections reviewed this run.  
**Confidence:** High  
**Sources:**  
- https://www.irs.gov/publications/p970/ch10.html  
- https://www.irs.gov/instructions/i1099q

## 10) What is New Jersey's current line-level treatment for nonqualified 529/ABLE distributions?
**Answer:** NJ-1040 instructions include earnings on nonqualified distributions from qualified tuition programs and qualified state 529A ABLE accounts in taxable interest (line 16a), and also include NJBEST nonqualified distribution portions attributable to prior deducted contributions.  
**Confidence:** High  
**Sources:**  
- https://www.njportal.com/Taxation/NJ1040/Content/Docs/Instructions/Current_NJ1040Instructions.pdf

## 11) What Pennsylvania line handles taxable non-educational 529 distributions?
**Answer:** PA-40 instructions route non-educational IRC 529 distributions to PA Schedule A line 13, while also stating federally exempt IRC 529 distribution rollovers are excluded from taxable income.  
**Confidence:** Medium-High  
**Sources:**  
- https://www.pa.gov/content/dam/copapwp-pagov/en/revenue/documents/formsandpublications/formsforindividuals/pit/documents/2024/2024_pa-40in.pdf

## 12) Why should product UX track 60-day rollover and source-account closure milestones?
**Answer:** Official ABLE United rollover instructions tie qualified treatment and means-tested-benefit treatment to 60-day timing and account-closure conditions, so missing these milestones is a legal/compliance failure mode.  
**Confidence:** High  
**Sources:**  
- https://www.ableunited.com/wp-content/uploads/able-united-rollover-able-to-able-1.8_ADA.pdf
