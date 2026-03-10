# Executive Summary: 529 + ABLE (Onboarding and Plan-Management Focus)

Updated: 2026-03-10

## Current truths (plain English)

1. **Federal 529->ABLE rollovers continue after 2025 under amended law.**  
   Controlling statute was amended to remove the sunset phrase and applies for taxable years beginning after 2025.  
   Sources: Pub. L. 119-21 and updated USC text for IRC 529/529A.  
   - https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm  
   - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim  
   - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529A&num=0&edition=prelim

2. **State treatment remains the biggest implementation risk.**  
   Ohio’s 2024 instructions explicitly require an addition for nonqualified 529 distributions **only when amounts were previously deducted/credited on Ohio returns**, and provide separate deduction lines for STABLE and 529 contributions. This confirms the need for state-specific recapture logic, not generic federal logic.  
   Source: Ohio IT 1040/SD 100 Instruction Booklet (2024), Schedule of Adjustments lines 4, 20, 36.  
   - https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/it1040-booklet.pdf  
   - https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/scheduleofadjustments.pdf

3. **Operational workflows can block users even when legally eligible.**  
   Official rollover forms require data coordination across both plans, potential notarization, and contribution-limit checks before acceptance, creating high abandonment and error risk in DIY flows.  
   Source: ABLE for ALL "529 College Savings to ABLE Direct Rollover Form."  
   - https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf

## Biggest risks right now

- **False certainty from stale federal guidance pages** (authority-order errors).
- **State recapture/add-back misclassification** causing avoidable tax exposure.
- **Transfer workflow failure** (beneficiary mismatch, cap overrun, missing notarization, missing account metadata).
- **Product over-automation without confidence labels** for low-confidence states.

## Biggest opportunities

1. **State-aware transfer precheck engine** (beneficiary relationship + annual-cap + state recapture warning).
2. **Guided rollover packet generation** (form-fill, signature routing, and document checklist).
3. **Confidence-scored answer layer** for high-frequency support questions with citation links.
4. **Exception dashboard** for stuck transfers and reason codes (missing fields, plan rejection, cap issues).

## What to do next (next 1-2 runs)

1. Close one unresolved high-value state (NJ or PA) with line-level current-year instructions.
2. Expand matrix coverage in priority states (UT, IN, MN).
3. Add at least one additional competitor transfer/onboarding workflow with primary source forms.
4. Ship MVP requirement: pre-submit "is this rollover likely to be qualified and operationally accepted?" checker.
