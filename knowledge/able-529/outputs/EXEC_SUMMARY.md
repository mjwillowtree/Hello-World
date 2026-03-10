# EXEC_SUMMARY

Updated: 2026-03-10

## Current truths (plain English)

1. **Federal 529->ABLE rollover authority continues after 2025.**
   - Pub. L. 119-21 removed sunset wording and applies for taxable years beginning after 2025.
   - Current IRS Pub 970/Pub 907 language checked this run appears conformed (no legacy sunset phrase found).
2. **State treatment remains the biggest implementation risk.**
   - Federal qualification does not automatically remove state recapture/add-back risk.
   - Indiana now shows destination-sensitive treatment (in-state ABLE vs other ABLE destinations) can change qualification outcomes.
3. **Operational transfer failure is often documentation-driven.**
   - Official provider forms warn missing principal/earnings support can create misclassification and exceptions.

## Biggest risks

1. State recapture surprise risk in unresolved jurisdictions.
2. Destination-plan choice made without state-specific tax logic in states with asymmetric treatment.
3. Transfer submission without required documentation and attestations.
4. Guidance hierarchy errors (stale summaries over controlling law).

## Biggest opportunities

1. Preflight rollover validator (eligibility + documentation + annual-cap checks).
2. State risk engine (jurisdiction + tax year + line references + confidence), including destination-sensitive routing.
3. Audit-ready citation layer for product/support consistency.

## Decision posture now

- Safe to design onboarding around post-2025 federal rollover continuity.
- Unsafe to auto-assume no state recapture in unresolved states.
- Highest leverage: reduce transfer exception rate through evidence-first workflow plus destination-aware state warnings.

## Key citations

- Federal amendment/effective date:
  - https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm
  - https://www.congress.gov/119/plaws/publ21/PLAW-119publ21.pdf
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim
- IRS publication status check:
  - https://www.irs.gov/pub/irs-pdf/p970.pdf
  - https://www.irs.gov/pub/irs-pdf/p907.pdf
- Operational forms:
  - https://www.fidelity.com/bin-public/060_www_fidelity_com/documents/customer-service/able-rollover.pdf
  - https://www.texasable.org/wp-content/uploads/dlm_uploads/2025/02/TxAble_IncomingRolloverForm_2.13.25_Fillable.pdf
  - https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf
  - https://www.paable.gov/pdf/Incoming-Direct-Rollover.pdf
- State examples:
  - https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/it1040-booklet.pdf
  - https://www.revenue.state.mn.us/sites/default/files/2025-10/m1529-25-grid.pdf
  - https://www.in.gov/dor/files/ib98.pdf
