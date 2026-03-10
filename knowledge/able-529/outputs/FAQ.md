# FAQ (High-Frequency + Adversarial)

Updated: 2026-03-10

Format: answer + confidence + sources.

## 1) Is 529->ABLE rollover still allowed after 2025?

Yes, federal law was amended to remove the pre-2026 sunset and apply the change for taxable years beginning after 2025.  
**Confidence:** High  
**Sources:**  
- https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm  
- https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim

## 2) If a federal source page looks old, what should control?

Controlling hierarchy: statute and codified law first; legacy newsroom pages are secondary context.  
**Confidence:** High  
**Sources:**  
- https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm  
- https://www.irs.gov/newsroom/tax-reform-affects-able-accounts-savers-credit-529-rollovers

## 3) Does federal qualification guarantee no state tax recapture?

No. State rules can diverge and may require add-back/recapture logic even when federal treatment is qualified.  
**Confidence:** High  
**Sources:**  
- https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/it1040-booklet.pdf  
- https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/scheduleofadjustments.pdf

## 4) What line-level Ohio references matter for 529/ABLE treatment?

Ohio Schedule of Adjustments lines 4, 20, and 36; instructions detail triggers and deduction mechanics.  
**Confidence:** High  
**Sources:**  
- https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/scheduleofadjustments.pdf  
- https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/it1040-booklet.pdf

## 5) What commonly causes 529->ABLE transfer failure operationally?

Missing required account metadata, beneficiary/family-member mismatch, annual limit overshoot, and missing notarization/authorization conditions with source plans.  
**Confidence:** High  
**Source:**  
- https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf

## 6) Do users need an ABLE account open before requesting direct rollover?

In ABLE for ALL’s documented process, yes: account setup is required before completing the direct rollover form workflow.  
**Confidence:** High  
**Source:**  
- https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf

## 7) Are all state line-level recapture rules fully mapped already?

No. The matrix structure exists for all 50 states + DC, but only a subset has evidence-backed partial/complete treatment.  
**Confidence:** High  
**Source:**  
- ./STATE_MATRIX.csv

## 8) Adversarial: "Can we auto-approve all transfers if beneficiary names match?"

No. Matching names alone is insufficient; annual cap constraints, permitted family-member rules, and state tax treatment confidence still matter.  
**Confidence:** High  
**Sources:**  
- https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529A&num=0&edition=prelim  
- https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf

## 9) Adversarial: "Can we treat plan blogs as final authority?"

No. Plan pages are useful, but statute, regulations, IRS/SSA, and official state forms/instructions control.  
**Confidence:** High  
**Sources:**  
- https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm  
- https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/it1040-booklet.pdf

## 10) What should support agents say when state confidence is low?

Provide the best available citation-backed answer, clearly mark confidence as low/medium, and route to manual review rather than definitive tax-position language.  
**Confidence:** Medium-High  
**Sources:**  
- ./LEGAL_BASELINE.md  
- ./STATE_MATRIX.csv
