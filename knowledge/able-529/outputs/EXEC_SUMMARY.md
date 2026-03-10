# EXEC_SUMMARY

Updated: 2026-03-10

## Current truths (plain English)

1. **Federal 529->ABLE rollover authority continues after 2025.**
   - Pub. L. 119-21 removed sunset wording and applies for taxable years beginning after 2025.
   - IRS 2025 Publication 970 and 1099-QA instructions are now aligned with ongoing rollover treatment.
2. **State treatment remains the biggest implementation risk.**
   - Federal qualification does not automatically remove state recapture/add-back risk.
3. **Operational transfer failure is documentation- and operations-window-driven.**
   - Official provider forms warn missing principal/earnings support can create misclassification and exceptions.
   - ABLEnow's March 2026 recordkeeper transition introduces a temporary blackout period and delayed transactions.

## Biggest risks

1. State recapture surprise risk in unresolved jurisdictions.
2. Transfer submission without required documentation and attestations.
3. Guidance hierarchy errors (stale summaries over controlling law).
4. Provider blackout/transition windows causing failed timing assumptions and delayed funding.

## Biggest opportunities

1. Preflight rollover validator (eligibility + documentation + annual-cap checks).
2. State risk engine (jurisdiction + tax year + line references + confidence).
3. Transition-aware transfer orchestration (blackout calendar + routing + customer messaging).
4. Audit-ready citation layer for product/support consistency.

## Decision posture now

- Safe to design onboarding around post-2025 federal rollover continuity.
- Unsafe to auto-assume no state recapture in unresolved states.
- Highest leverage: reduce transfer exceptions and timing failures through evidence-first plus transition-aware workflow controls.

## Key citations

- Federal amendment/effective date:
  - https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm
  - https://www.congress.gov/119/plaws/publ21/PLAW-119publ21.pdf
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim
- Federal implementation pages:
  - https://www.irs.gov/publications/p970
  - https://www.irs.gov/instructions/i1099qa
- Operational forms:
  - https://www.fidelity.com/bin-public/060_www_fidelity_com/documents/customer-service/able-rollover.pdf
  - https://www.texasable.org/wp-content/uploads/dlm_uploads/2025/02/TxAble_IncomingRolloverForm_2.13.25_Fillable.pdf
  - https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf
  - https://paable.gov/pdf/Incoming-Direct-Rollover.pdf
  - https://www.ablenow.com/transition
- State examples:
  - https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/it1040-booklet.pdf
  - https://www.revenue.state.mn.us/sites/default/files/2025-10/m1529-25-grid.pdf
  - https://incometax.utah.gov/additions/my529-addback
