# EXEC_SUMMARY

Updated: 2026-03-11

## Current truths (plain English)

1. **Federal 529->ABLE rollover authority continues after 2025.**
   - Pub. L. 119-21 removed sunset wording and applies for taxable years beginning after 2025.
2. **IRS Publication 970 (2025) appears conformed for QTP->ABLE rollover description.**
   - Current chapter text describes QTP-to-ABLE rollovers without the legacy sunset phrase.
3. **State treatment remains the biggest implementation risk.**
   - Indiana now has explicit non-qualified rollover language for state credit recapture, proving state variance can be material.
4. **Operational transfer failure is documentation + workflow-control driven.**
   - Official provider forms show failures from missing earnings support, signature-guarantee requirements, and contribution-limit overflow.

## Biggest risks

1. State recapture surprise risk in unresolved jurisdictions (NJ/PA/UT still open).
2. Transfer submission without required documentation, signature guarantees, and attestations.
3. Late-stage rejection when projected rollover exceeds ABLE contribution/balance constraints.
4. Guidance hierarchy errors (stale summaries over controlling law).

## Biggest opportunities

1. Preflight rollover validator (eligibility + documentation + annual-cap checks).
2. Signature/medallion + limit-fit orchestration layer before packet generation.
3. State risk engine (jurisdiction + tax year + line references + confidence).
4. Audit-ready citation layer for product/support consistency.

## Decision posture now

- Safe to design onboarding around post-2025 federal rollover continuity.
- Safe to reference current IRS Pub. 970 wording as supporting guidance, but statute remains controlling.
- Unsafe to auto-assume no state recapture in unresolved states.
- Highest leverage: reduce transfer exception rate through evidence-first workflow plus signature/limit guardrails.

## Key citations

- Federal amendment/effective date:
  - https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm
  - https://www.congress.gov/119/plaws/publ21/PLAW-119publ21.pdf
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim
- IRS primary publication:
  - https://www.irs.gov/pub/irs-pdf/p970.pdf
- Operational forms:
  - https://www.fidelity.com/bin-public/060_www_fidelity_com/documents/customer-service/able-rollover.pdf
  - https://www.texasable.org/wp-content/uploads/dlm_uploads/2025/02/TxAble_IncomingRolloverForm_2.13.25_Fillable.pdf
  - https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf
  - https://www.paable.gov/pdf/Incoming-Direct-Rollover.pdf
- State examples:
  - https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/it1040-booklet.pdf
  - https://www.revenue.state.mn.us/sites/default/files/2025-10/m1529-25-grid.pdf
  - https://forms.in.gov/Download.aspx?id=16957
