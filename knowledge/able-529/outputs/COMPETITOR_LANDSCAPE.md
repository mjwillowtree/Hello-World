# COMPETITOR_LANDSCAPE (Onboarding + Plan-Management Focus)

Updated: 2026-03-10

Scope: onboarding/servicing workflows (not portfolio performance).

## Snapshot table

| Provider / Program | Workflow signal | User friction / risk | Evidence | Confidence |
|---|---|---|---|---|
| Fidelity ABLE | Supports 60-day rollover and program-to-program transfer workflows for ABLE/529 into ABLE | High operational risk if earnings/principal documentation is missing; signature complexity can increase abandonment | Official rollover/transfer request form | High |
| ABLE for ALL | Direct 529->ABLE rollover with same-beneficiary or family-member certification and multi-party signatures | Relationship/attestation errors can trigger rejection or nonqualified risk | Official direct rollover form | High |
| Texas ABLE | Distinguishes direct vs indirect rollovers and requires support docs for earnings/contributions | Without support docs, full rollover can be treated as earnings | Official incoming rollover form | High |
| PA ABLE | Publishes separate direct and indirect incoming rollover forms with explicit rejection and signature-guarantee conditions | Over-limit rollovers are rejected; missing principal/earnings statement can force full-earnings treatment; medallion requirements can delay funding | Official forms + forms page | High |
| ABLEnow | Recordkeeper transition operations include a temporary blackout period, transaction delays, and temporary form unavailability | Timing-sensitive transfers can miss expected posting windows; users can fail if they mail contributions during blackout | Official transition + forms notices | High |

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

### PA ABLE
- Publishes separate **Incoming Direct Rollover** and **Incoming Indirect Rollover** forms for ABLE/529 sources.
- Direct-rollover terms include annual-limit/balance-limit rejection, possible medallion signature guarantee, and requirement for principal/earnings statement from the source program manager.
- Sources:
  - https://paable.gov/forms-and-docs/
  - https://paable.gov/pdf/Incoming-Direct-Rollover.pdf
  - https://paable.gov/pdf/Incoming-Indirect-Rollover.pdf

### ABLEnow
- Forms page currently states forms are temporarily unavailable during recordkeeper transition.
- Transition notice provides key blackout dates, delayed transaction handling, and do-not-mail instructions during blackout.
- Sources:
  - https://www.ablenow.com/resources/forms/
  - https://www.ablenow.com/transition

## Product-intelligence implications

1. Form-first operations remain standard for rollover execution.
2. Beneficiary/family-member mapping is a core failure point.
3. Earnings-basis documentation is a repeated cross-provider risk control.
4. Signature/notarization/guarantee variance should be surfaced pre-submission.
5. Provider transition/blackout windows are material operational constraints and should be encoded into transfer timing UX.
