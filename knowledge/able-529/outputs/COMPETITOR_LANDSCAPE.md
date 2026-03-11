# COMPETITOR_LANDSCAPE (Onboarding + Plan-Management Focus)

Updated: 2026-03-11

Scope: onboarding/servicing workflows (not portfolio performance).

## Snapshot table

| Provider / Program | Workflow signal | User friction / risk | Evidence | Confidence |
|---|---|---|---|---|
| Fidelity ABLE | Supports 60-day rollover and program-to-program transfer workflows for ABLE/529 into ABLE | High operational risk if earnings/principal documentation is missing; signature complexity can increase abandonment | Official rollover/transfer request form | High |
| ABLE for ALL | Direct 529->ABLE rollover with same-beneficiary or family-member certification and multi-party signatures | Relationship/attestation errors can trigger rejection or nonqualified risk | Official direct rollover form | High |
| Texas ABLE | Distinguishes direct vs indirect rollovers and requires support docs for earnings/contributions | Without support docs, full rollover can be treated as earnings | Official incoming rollover form | High |
| ABLEnow | Indirect rollover form enforces 60-day deposit, one-ABLE-account rule context, family-member attestations, and basis/earnings statement requirement | Entire deposit is treated as earnings until supporting statement is received; signature source differs for ABLE vs 529 origin | Official incoming indirect rollover form | High |
| PA ABLE | Direct rollover form includes destination limits, external-plan documentation dependency, and conditional Medallion Signature Guarantee path | Missing principal/earnings statement causes full-earnings treatment; absent required signature guarantee can delay transfer | Official incoming direct rollover form | High |

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
- Indirect rollover requires deposit within 60 days and statement showing basis/earnings breakdown.
- Until statement is received, the entire deposit is treated as earnings.
- For 529-origin indirect rollover, signature is required from the 529 account owner.
- Source: https://www.ablenow.com/uploads/documents/ABLEnow_Incoming_Rollover_Indirect.pdf

### PA ABLE
- 529 rollover contributions are checked against annual contribution and account balance limits; over-limit contributions are rejected.
- Program manager must provide principal/earnings statement; absent statement, transfer is treated as earnings.
- If source program requires it, Medallion Signature Guarantee is mandatory; notary is insufficient.
- Source: https://www.paable.gov/pdf/Incoming-Direct-Rollover.pdf

## Product-intelligence implications

1. Form-first operations remain standard for rollover execution.
2. Beneficiary/family-member mapping is a core failure point.
3. Earnings-basis documentation is a repeated cross-provider risk control.
4. Signature/notarization/guarantee variance should be surfaced pre-submission.
5. Destination-plan contribution and balance-limit checks can create hard rejects even when transfer paperwork is complete.
