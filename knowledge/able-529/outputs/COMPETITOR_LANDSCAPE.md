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
| STABLE Account | ABLE->ABLE rollover form enforces 60-day closure/settlement controls plus frequency and ALR continuity checks | Users can fail qualification if prior ABLE account is not closed within 60 days; one-rollover-per-12-month rule creates hard eligibility gate | Official rollover form + official FAQ | High |

## Detail notes

### Fidelity ABLE
- Requires principal/earnings documentation for rollover classification; missing docs can force conservative earnings treatment until corrected.
- Includes signature operations and additional signature guarantee requirements in specified cases.
- Source: https://www.fidelity.com/bin-public/060_www_fidelity_com/documents/customer-service/able-rollover.pdf

### ABLE for ALL
- Requires beneficiary identity matching or qualifying family-member relationship certification.
- Separate signatures required for ABLE beneficiary/ALR and 529 account owner.
- Source: https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf

### Texas ABLE
- States 60-day qualification rules and required support documentation.
- Warns that absent earnings/contributions documentation, the full rollover may be treated as earnings.
- Source: https://www.texasable.org/wp-content/uploads/dlm_uploads/2025/02/TxAble_IncomingRolloverForm_2.13.25_Fillable.pdf

### ABLEnow
- Public resources show dedicated forms/processes for direct and indirect rollover intake.
- Source: https://www.ablenow.com/resources/forms/ ; https://www.ablenow.com/blog/articles/how-to-transfer-529-funds-to-ablenow/

### STABLE Account
- ABLE-to-ABLE rollover form requires closure of the prior ABLE account within 60 days or rollover treatment can fail qualified handling.
- Form also requires one-rollover-per-12-month certification and continuity/attestation handling for Authorized Legal Representatives.
- Sources:
  - https://stableaccount.com/assets/docs/rollover-able-to-able-form.pdf
  - https://stableaccount.com/faqs/can-i-transfer-an-existing-able-account-into-my-stable-account

## Product-intelligence implications

1. Form-first operations remain standard for rollover execution.
2. Beneficiary/family-member mapping is a core failure point.
3. Earnings-basis documentation is a repeated cross-provider risk control.
4. Signature/notarization/guarantee variance should be surfaced pre-submission.
5. Cooldown/closure constraints (12-month rollover frequency + 60-day account closure) need explicit gating before users start paperwork.
