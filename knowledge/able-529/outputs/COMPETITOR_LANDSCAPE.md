# COMPETITOR_LANDSCAPE (Onboarding + Plan-Management Focus)

Updated: 2026-03-11

Scope: onboarding/servicing workflows (not portfolio performance).

## Snapshot table

| Provider / Program | Workflow signal | User friction / risk | Evidence | Confidence |
|---|---|---|---|---|
| Fidelity ABLE | Supports 60-day rollover and program-to-program transfer workflows for ABLE/529 into ABLE | High operational risk if earnings/principal documentation is missing; signature complexity can increase abandonment | Official rollover/transfer request form | High |
| ABLE for ALL | Direct 529->ABLE rollover with same-beneficiary or family-member certification and multi-party signatures | Relationship/attestation errors can trigger rejection or nonqualified risk | Official direct rollover form | High |
| Texas ABLE | Distinguishes direct vs indirect rollovers and requires support docs for earnings/contributions | Without support docs, full rollover can be treated as earnings | Official incoming rollover form | High |
| ABLEnow | Public form resources for incoming 529->ABLE and indirect rollover flows | Form-first operational flow likely creates similar checklist/drop-off patterns | Forms + workflow pages | Medium |
| Invest529 (source 529 program) | Outbound transfer flow to ABLEnow is explicitly two-step and form-routed through ABLEnow incoming transfer paperwork | Users must open/verify destination ABLEnow first and submit the right transfer form; annual-limit and beneficiary-owner transition creates confusion risk | Official Invest529 transfer guidance page | High |

## Detail notes

### Fidelity ABLE
- Requires principal/earnings documentation for rollover classification; missing docs can force conservative earnings treatment until corrected.
- Includes signature operations and additional signature guarantee requirements in specified cases.
- Source: https://www.fidelity.com/bin-public/060_www_fidelity_com/documents/customer-service/able-rollover.pdf

### ABLE for ALL
- Requires beneficiary identity matching or qualifying family-member relationship certification.
- Separate signatures required for ABLE beneficiary/ALR and 529 account owner.
- Source: https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf

### ABLE for ALL (ABLE-to-ABLE operations detail)
- ABLE-to-ABLE form includes conditional Signature Medallion Guarantee/notarization path and explicit "one rollover per 12 months" attestation.
- Requires 60-day closure/transfer conditions and warns that missing principal/earnings certification can result in treating the full transfer as earnings for tax purposes.
- Source: https://ableforall.com/uploads/ableforall/attachments/cltymmi2b3wtj0jleeoig7lsi-able-for-all-rollover-able-to-able-form.pdf

### Texas ABLE
- States 60-day qualification rules and required support documentation.
- Warns that absent earnings/contributions documentation, the full rollover may be treated as earnings.
- Source: https://www.texasable.org/wp-content/uploads/dlm_uploads/2025/02/TxAble_IncomingRolloverForm_2.13.25_Fillable.pdf

### ABLEnow
- Public resources show dedicated forms/processes for direct and indirect rollover intake.
- Source: https://www.ablenow.com/resources/forms/ ; https://www.ablenow.com/blog/articles/how-to-transfer-529-funds-to-ablenow/

### Invest529 -> ABLEnow transfer flow
- Step 1: open/confirm ABLEnow account.
- Step 2: complete ABLEnow Incoming Program-to-Program Transfer request and send to Invest529.
- Guidance also highlights annual ABLE contribution-limit constraint and 60-day window for indirect rollover deposit paths.
- Source: https://www.invest529.com/articles-webinars/transfer-invest529-funds-to-ablenow/

## Product-intelligence implications

1. Form-first operations remain standard for rollover execution.
2. Beneficiary/family-member mapping is a core failure point.
3. Earnings-basis documentation is a repeated cross-provider risk control.
4. Signature/notarization/guarantee variance should be surfaced pre-submission.
5. Source-plan-to-destination-plan handoff instructions are often split across institutions; products need explicit "which form goes where" routing.
