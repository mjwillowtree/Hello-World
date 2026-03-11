# EXEC_SUMMARY

Updated: 2026-03-11

## Current truths (plain English)

1. **Federal 529->ABLE rollover authority continues after 2025.**
   - Pub. L. 119-21 removed sunset wording and applies for taxable years beginning after 2025.
2. **State treatment remains the biggest implementation risk.**
   - Federal qualification does not automatically remove state recapture/add-back risk.
3. **Indiana now provides an explicit adverse state example.**
   - Indiana IN-CR instructions classify Indiana529 rollover/transfer to an ABLE account as non-qualified for credit-recapture purposes.
4. **Operational transfer failure is often documentation-driven.**
   - Official provider forms warn missing principal/earnings support can create misclassification and exceptions.

## Biggest risks

1. State recapture surprise risk in unresolved jurisdictions (and in some resolved jurisdictions, such as Indiana, where rollover-to-ABLE is explicitly non-qualified for recapture logic).
2. Transfer submission without required documentation and attestations.
3. Annual-limit overflow and notarization/signature friction causing rejected or abandoned transfers.
4. Guidance hierarchy errors (stale summaries over controlling law).

## Biggest opportunities

1. State recapture tripwire engine (jurisdiction + tax year + form-line evidence + confidence).
2. Preflight rollover validator (eligibility + documentation + annual-cap checks).
3. Audit-ready citation layer for product/support consistency.

## Decision posture now

- Safe to design onboarding around post-2025 federal rollover continuity.
- Unsafe to auto-assume no state recapture, even when federal qualification appears satisfied.
- Highest leverage: combine state tripwire logic with evidence-first workflow before transfer submission.

## Key citations

- Federal amendment/effective date:
  - https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm
  - https://www.congress.gov/119/plaws/publ21/PLAW-119publ21.pdf
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim
- Operational forms:
  - https://www.fidelity.com/bin-public/060_www_fidelity_com/documents/customer-service/able-rollover.pdf
  - https://www.texasable.org/wp-content/uploads/dlm_uploads/2025/02/TxAble_IncomingRolloverForm_2.13.25_Fillable.pdf
  - https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf
- State examples:
  - https://forms.in.gov/Download.aspx?id=16957
  - https://forms.in.gov/Download.aspx?id=16938
  - https://forms.in.gov/Download.aspx?id=16915
  - https://incometax.utah.gov/additions/my529-addback
  - https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/it1040-booklet.pdf
  - https://www.revenue.state.mn.us/sites/default/files/2025-10/m1529-25-grid.pdf
