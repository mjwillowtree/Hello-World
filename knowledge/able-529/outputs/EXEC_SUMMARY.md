# EXEC_SUMMARY

Updated: 2026-03-10

## Current truths (plain English)

1. **Federal 529->ABLE rollover authority continues after 2025.**  
   The sunset language was removed by Pub. L. 119-21, with an effective date for taxable years beginning after 2025.

2. **Operational transfer risk is often documentation-driven, not law-driven.**  
   Major plan forms warn that if earnings/principal support docs are missing, the full rollover amount may be treated as earnings.

3. **State treatment remains the biggest user-risk variance.**  
   Federal qualification does not automatically eliminate state recapture/add-back risk.

## Biggest risks

1. **State recapture surprise risk** in unresolved jurisdictions (especially where line-level instructions are not yet locked).
2. **Submission without required transfer documentation,** creating downstream tax/servicing exceptions.
3. **Guidance hierarchy errors** (teams relying on stale IRS or plan summaries over controlling law).

## Biggest opportunities

1. **Preflight Rollover Validator** to collect documents and enforce eligibility/limit checks before submission.
2. **State Risk Engine** with jurisdiction + tax-year confidence and form-line references.
3. **Audit-ready citation layer** that keeps product/support answers consistent and defensible.

## Decision posture now

- Safe to design onboarding around post-2025 federal rollover continuity.
- Unsafe to auto-assume no state recapture in unresolved states.
- High-leverage product investment: reduce transfer exception rate through evidence-first workflow design.

## Key citations

- Federal amendment/effective date:
  - https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm
  - https://www.congress.gov/119/plaws/publ21/PLAW-119publ21.pdf
- Plan workflow constraints:
  - https://www.fidelity.com/bin-public/060_www_fidelity_com/documents/customer-service/able-rollover.pdf
  - https://www.texasable.org/wp-content/uploads/dlm_uploads/2025/02/TxAble_IncomingRolloverForm_2.13.25_Fillable.pdf
- State example (Minnesota):
  - https://www.revenue.state.mn.us/education-savings-account-recapture-tax
  - https://www.revenue.state.mn.us/sites/default/files/2025-10/m1529-25-grid.pdf
