# FAQ (High-frequency + Adversarial)

Updated: 2026-03-10

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

## 9) Are IRS primary materials still universally stale on the old 2026 sunset?
**Answer:** No. Legacy newsroom pages still show old sunset language, but current IRS Publication 970 and 2025 Instructions for Forms 1099-QA/5498-QA include ongoing QTP-to-ABLE rollover treatment.  
**Confidence:** High  
**Sources:**  
- https://www.irs.gov/publications/p970  
- https://www.irs.gov/instructions/i1099qa  
- https://www.irs.gov/newsroom/tax-reform-affects-able-accounts-savers-credit-529-rollovers

## 10) What is Utah's current line-level pattern for my529 addback?
**Answer:** Utah maps my529 addback to TC-40A Part 1 code 54; Part 1 totals carry to TC-40 line 5. Utah Code §59-10-114(1)(d) ties addback to withdrawn amounts under defined conditions and references IRC §§529(c)/530(d) exceptions.  
**Confidence:** Medium-High  
**Sources:**  
- https://incometax.utah.gov/additions/my529-addback  
- https://le.utah.gov/xcode/Title59/Chapter10/C59-10-S114_2025101420251206.html  
- https://files.tax.utah.gov/tax/forms/current/tc-40.pdf

## 11) Can operational blackout windows materially affect transfer success?
**Answer:** Yes. ABLEnow's transition notice explicitly warns of a temporary blackout period with account/debit-card unavailability and delayed transactions, and its forms page reports temporary form unavailability during transition.  
**Confidence:** High  
**Sources:**  
- https://www.ablenow.com/transition  
- https://www.ablenow.com/resources/forms/
