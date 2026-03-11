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
| PA ABLE | Incoming direct rollover workflow includes source-plan contact, optional/conditional medallion path, and strict contribution-limit checks | Missing principal/earnings statement can force full amount to earnings treatment; absent required medallion can delay transfer | Official incoming direct rollover form | High |

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

### PA ABLE
- Requires pre-existing account or concurrent enrollment before incoming direct rollover.
- Warns that if source program manager requires Medallion Signature Guarantee, missing guarantee can delay rollover.
- States transferred amount is treated as earnings until source plan provides principal/earnings breakdown statement.
- Source: https://www.paable.gov/pdf/Incoming-Direct-Rollover.pdf

## Product-intelligence implications

1. Form-first operations remain standard for rollover execution.
2. Beneficiary/family-member mapping is a core failure point.
3. Earnings-basis documentation is a repeated cross-provider risk control.
4. Signature/notarization/guarantee variance should be surfaced pre-submission.
5. Source-plan-specific requirements (including medallion triggers) should be modeled as plan-pair rules, not global rules.
