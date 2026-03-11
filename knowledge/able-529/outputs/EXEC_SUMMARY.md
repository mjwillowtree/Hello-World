# EXEC_SUMMARY

Updated: 2026-03-11

## Current truths (plain English)

1. **Federal 529->ABLE rollover authority continues after 2025.**
   - Pub. L. 119-21 removed sunset wording and applies for taxable years beginning after 2025.
2. **State treatment remains the biggest implementation risk.**
   - Federal qualification does not automatically remove state recapture/add-back risk.
3. **Indiana now has line-level filing clarity, but substantive source conflict remains.**
   - IN-CR gives explicit recapture filing lines, while Bulletin #98 introduces a carve-in for Indiana529->Indiana ABLE beginning 2024.
4. **Operational transfer failure is often documentation-driven.**
   - Official provider forms warn missing principal/earnings support can create misclassification and exceptions.

## Biggest risks

1. State recapture surprise risk in unresolved jurisdictions.
2. Intra-state primary-source conflict risk (form vs bulletin drift) causing wrong automation outcomes.
3. Transfer submission without required documentation and attestations.
4. Guidance hierarchy errors (stale summaries over controlling law).

## Biggest opportunities

1. Preflight rollover validator (eligibility + documentation + annual-cap checks).
2. State risk engine (jurisdiction + tax year + line references + confidence).
3. Authority-conflict sentinel with automatic escalation for ambiguous states.
4. Audit-ready citation layer for product/support consistency.

## Decision posture now

- Safe to design onboarding around post-2025 federal rollover continuity.
- Unsafe to auto-assume no state recapture in unresolved states.
- Unsafe to auto-assume Indiana rollover treatment without source-version logic, despite improved line-level filing clarity.
- Highest leverage: reduce transfer exception rate through evidence-first workflow.

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
  - https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/it1040-booklet.pdf
  - https://www.revenue.state.mn.us/sites/default/files/2025-10/m1529-25-grid.pdf
  - https://forms.in.gov/Download.aspx?id=16957
  - https://forms.in.gov/Download.aspx?id=16915
  - https://www.in.gov/dor/files/ib98.pdf
- Workflow handoff evidence:
  - https://www.invest529.com/articles-webinars/transfer-invest529-funds-to-ablenow/
  - https://ableforall.com/uploads/ableforall/attachments/cltymmi2b3wtj0jleeoig7lsi-able-for-all-rollover-able-to-able-form.pdf
