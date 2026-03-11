# EXEC_SUMMARY

Updated: 2026-03-11

## Current truths (plain English)

1. **Federal 529->ABLE rollover authority continues after 2025.**
   - Pub. L. 119-21 removed sunset wording and applies for taxable years beginning after 2025.
2. **New Jersey now has line-level instruction clarity for qualified vs nonqualified 529/ABLE distribution treatment.**
   - NJ-1040 line 16a instructions explicitly treat earnings on nonqualified distributions as taxable interest and separately list qualified 529/529A distributions as exempt.
3. **State treatment remains the biggest implementation risk overall.**
   - Federal qualification still does not automatically remove state recapture/add-back risk (Utah remains conditional for ABLE inference).
4. **Operational transfer failure is documentation + timing-rule driven.**
   - Official plan forms include 60-day closure/settlement, one-per-12-month rollover cadence, and earnings/principal evidence constraints.

## Biggest risks

1. State recapture/addback surprise risk in unresolved jurisdictions (especially where ABLE carveouts are implied but not explicit).
2. Transfer submission without required documentation, closure attestations, or rollover-frequency eligibility checks.
3. Guidance hierarchy errors (stale summaries over controlling law).

## Biggest opportunities

1. Preflight rollover validator (eligibility + documentation + annual-cap checks).
2. Cooldown/closure guardrails (one-per-12-month + 60-day prior-account closure).
3. State risk engine (jurisdiction + tax year + line references + confidence).

## Decision posture now

- Safe to design onboarding around post-2025 federal rollover continuity.
- Safer to implement New Jersey line-level filing guidance directly in UX.
- Unsafe to auto-assume no state recapture in unresolved states.
- Highest leverage: reduce transfer exception rate through evidence-first workflow plus eligibility gating.

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
  - https://www.njportal.com/Taxation/NJ1040/Content/Docs/Instructions/Current_NJ1040Instructions.pdf
  - https://tax.utah.gov/forms/current/tc-40inst.pdf
  - https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/it1040-booklet.pdf
  - https://www.revenue.state.mn.us/sites/default/files/2025-10/m1529-25-grid.pdf
- Additional workflow constraint:
  - https://stableaccount.com/assets/docs/rollover-able-to-able-form.pdf
