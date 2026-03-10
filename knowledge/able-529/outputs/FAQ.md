# FAQ (High-frequency + Adversarial)

Updated: 2026-03-10

## 1) Is 529->ABLE rollover still federally allowed after 2025?
**Answer:** Yes, based on Pub. L. 119-21 Sec. 70117 removing the "before January 1, 2026" sunset phrase and applying the amendment to taxable years beginning after 2025.  
**Confidence:** High  
**Sources:**  
- https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm  
- https://www.congress.gov/119/plaws/publ21/PLAW-119publ21.pdf  
- https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim

## 2) If an IRS newsroom page still shows the old sunset, which source controls?
**Answer:** Enacted statute/codified law controls over stale newsroom content.  
**Confidence:** High  
**Sources:**  
- Statute: https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm  
- Legacy pages: https://www.irs.gov/newsroom/irs-issues-final-regulations-for-achieving-a-better-life-experience-accounts ; https://www.irs.gov/newsroom/tax-reform-affects-able-accounts-savers-credit-529-rollovers

## 3) Does federal qualification guarantee no state recapture?
**Answer:** No. State treatment can diverge and must be verified by jurisdiction and tax year.  
**Confidence:** High  
**Sources:**  
- `outputs/STATE_MATRIX.csv` Tier-1 entries (CA/IL/MN examples)

## 4) What is the most common rollover operational failure mode?
**Answer:** Missing earnings/principal documentation from the distributing plan; multiple official forms warn full rollover amount may be treated as earnings without it.  
**Confidence:** High  
**Sources:**  
- https://www.fidelity.com/bin-public/060_www_fidelity_com/documents/customer-service/able-rollover.pdf  
- https://www.texasable.org/wp-content/uploads/dlm_uploads/2025/02/TxAble_IncomingRolloverForm_2.13.25_Fillable.pdf

## 5) Are same-beneficiary/family-member constraints operationally enforced?
**Answer:** Yes, official forms include explicit certification/attestation fields for beneficiary matching or family-member qualification.  
**Confidence:** High  
**Sources:**  
- https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf  
- https://www.texasable.org/wp-content/uploads/dlm_uploads/2025/02/TxAble_IncomingRolloverForm_2.13.25_Fillable.pdf

## 6) What line-level Minnesota recapture workflow is currently known?
**Answer:** Schedule M1529 computes recapture on lines 7-15, and line 15 flows to Form M1 line 14 when distribution is not used for qualified expenses.  
**Confidence:** Medium-High  
**Sources:**  
- https://www.revenue.state.mn.us/education-savings-account-recapture-tax  
- https://www.revenue.state.mn.us/sites/default/files/2025-10/m1529-25-grid.pdf

## 7) Adversarial: "If a plan form says something, do we skip legal hierarchy checks?"
**Answer:** No. Plan forms are operationally critical but still must be interpreted under controlling federal/state law when legal conflict exists.  
**Confidence:** High  
**Sources:**  
- Federal statutory baseline in `outputs/LEGAL_BASELINE.md`  
- Official plan form examples in `outputs/COMPETITOR_LANDSCAPE.md`

## 8) Can this system already answer top user questions quickly with citations?
**Answer:** Partially. Federal baseline and several state/operational questions are answerable quickly; broad 50-state line-level treatment is still incomplete.  
**Confidence:** Medium  
**Sources:**  
- `outputs/HUB.md` KPI block  
- `outputs/STATE_MATRIX.csv`
