# COMPETITOR_LANDSCAPE (Onboarding + Plan-Management Focus)

Updated: 2026-03-10

Scope here is onboarding/servicing workflows (not portfolio performance).

## Snapshot table

| Provider / Program | Workflow signal | User friction / risk | Evidence | Confidence |
|---|---|---|---|---|
| Fidelity ABLE | Supports 60-day rollover and program-to-program transfer workflows for ABLE/529 into ABLE | **High operational risk:** if principal/earnings documentation is missing, full rollover amount is treated as earnings; signature complexity can increase abandonment | Fidelity "Rollover/Transfer Request - ABLE Account" form states documentation and treatment rules; also lists signature requirements and Medallion requirement thresholds | High |
| ABLE for ALL (National ABLE Alliance / Sumday) | Direct 529->ABLE rollover form with same-beneficiary or family-member certification | Relationship/eligibility attestation must be correct at submission; manual form path can introduce delays | ABLE for ALL "529 College Savings to ABLE Direct Rollover Form" beneficiary/family-member attestations and signer requirements | High |
| Texas ABLE | Distinguishes direct vs indirect rollovers and requires support docs for earnings/contributions | **Critical failure mode:** absent support docs, full rollover treated as earnings; 60-day timing and one-ABLE-account-at-a-time constraints raise error risk | Texas ABLE Incoming Rollover Form includes 60-day rules, documentation list, and full-amount-as-earnings warning | High |

## Detail notes

### Fidelity ABLE (official plan form)
- Form explicitly says 60-day rollover timing and once-per-12-month constraints for applicable rollover scenarios.
- For 529->ABLE and ABLE->ABLE rollovers, principal/earnings documentation is required; otherwise full amount is recorded as earnings until corrected.
- Signature operations include multi-signer requirements for certain 529 transfers; form indicates Medallion signature guarantee requirement in specified cases.
- Source: https://www.fidelity.com/bin-public/060_www_fidelity_com/documents/customer-service/able-rollover.pdf

### ABLE for ALL (official plan form)
- Direct rollover requires beneficiary identity matching or qualifying family-member relationship certification.
- Separate signatures required from ABLE beneficiary/ALR and 529 account owner.
- Source: https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf

### Texas ABLE (official plan form)
- Program states 60-day qualification rules and required support documentation.
- Form warns that without documentation breaking out earnings/contributions, entire rollover may be treated as earnings.
- Includes constraints around beneficiary mapping and rollover qualification language tied to IRC §529/§529A family-member concepts.
- Source: https://www.texasable.org/wp-content/uploads/dlm_uploads/2025/02/TxAble_IncomingRolloverForm_2.13.25_Fillable.pdf

## Product-intelligence implication (added this run)

Across multiple providers, the **same operational bottleneck** appears: missing earnings-basis documentation converts otherwise-valid rollovers into high-friction exception handling. Product onboarding should assume this is common and preemptively collect or route for these artifacts before transfer initiation.
