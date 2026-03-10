# EXEC_SUMMARY

Updated: 2026-03-10

## Current truths (plain English)

1. **Federal 529->ABLE rollover authority continues after 2025.**
   - Pub. L. 119-21 removed sunset wording and applies for taxable years beginning after 2025.
   - IRS Publication 970 now reflects rollover treatment without the old pre-2026 sunset phrase.
2. **State treatment remains the biggest implementation risk.**
   - Federal qualification does not automatically remove state recapture/add-back risk.
   - Utah is now line-mapped (TC-40A code 54 -> TC-40 line 5), but NJ/PA remain unresolved.
3. **Operational transfer failure is often documentation-driven.**
   - Official provider forms warn missing principal/earnings support can create misclassification and exceptions.
4. **Indirect rollover timing and cap interactions are under-managed in current UX.**
   - CalABLE operational docs explicitly tie rollover validity to a 60-day redeposit window and annual-cap counting.

## Biggest risks

1. State recapture surprise risk in unresolved jurisdictions (especially NJ/PA until line-level closure).
2. Transfer submission without required documentation and attestations.
3. 60-day indirect rollover deadline misses and annual-cap overshoot.

## Biggest opportunities

1. Preflight rollover validator (eligibility + documentation + annual-cap checks).
2. State risk engine (jurisdiction + tax year + line references + confidence).
3. Deadline + cap guardrail service with countdown and proactive interventions.
4. Audit-ready citation layer for product/support consistency.

## Decision posture now

- Safe to design onboarding around post-2025 federal rollover continuity.
- Unsafe to auto-assume no state recapture in unresolved states.
- Highest leverage: reduce transfer exception rate through evidence-first workflow.

## Key citations

- Federal amendment/effective date:
  - https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm
  - https://www.congress.gov/119/plaws/publ21/PLAW-119publ21.pdf
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim
  - https://www.irs.gov/pub/irs-pdf/p970.pdf
- Operational forms:
  - https://www.fidelity.com/bin-public/060_www_fidelity_com/documents/customer-service/able-rollover.pdf
  - https://www.texasable.org/wp-content/uploads/dlm_uploads/2025/02/TxAble_IncomingRolloverForm_2.13.25_Fillable.pdf
  - https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf
  - https://calable.ca.gov/assets/docs/rollover-indirect-csp-to-able-form.pdf
- State examples:
  - https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/it1040-booklet.pdf
  - https://www.revenue.state.mn.us/sites/default/files/2025-10/m1529-25-grid.pdf
  - https://tax.utah.gov/forms/current/tc-40-fullpacket.pdf
