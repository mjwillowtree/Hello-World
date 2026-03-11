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

## 9) Has IRS primary publication text caught up on 529->ABLE rollover rules?
**Answer:** Current Publication 970 (2025) Chapter 7 describes rollovers from a QTP to an ABLE account and does not include the old pre-2026 sunset phrase in that rollover section.  
**Confidence:** Medium-High  
**Sources:**  
- https://www.irs.gov/pub/irs-pdf/p970.pdf  
- https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm

## 10) Does Indiana treat 529->ABLE rollover as non-qualified for state credit recapture?
**Answer:** Indiana Schedule IN-CR explicitly includes rollover/transfer from Indiana529 to another Section 529 plan or ABLE account in the non-qualified withdrawal definition, with recapture flowing to Schedule 4 line 3.  
**Confidence:** High  
**Sources:**  
- https://forms.in.gov/Download.aspx?id=16957  
- https://forms.in.gov/Download.aspx?id=16938  
- https://forms.in.gov/Download.aspx?id=16915

## 11) Can transferred amounts still earn Indiana contribution credits?
**Answer:** Indiana IN-529 and IN-ABLE instructions exclude transferred amounts (including transfers to/from 529/ABLE programs) from credit-eligible contributions.  
**Confidence:** High  
**Sources:**  
- https://forms.in.gov/Download.aspx?id=16907  
- https://forms.in.gov/Download.aspx?id=16956
