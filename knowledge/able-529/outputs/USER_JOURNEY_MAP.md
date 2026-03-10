# User Journey Map (Onboarding -> Plan Management)

Updated: 2026-03-10

## Journey stages

| Stage | User goal | Typical friction | Failure modes | Control points |
|---|---|---|---|---|
| 1. Discover eligibility | Confirm ABLE eligibility and who can fund/own | Confusion on onset age rules and beneficiary relationships | Ineligible user proceeds; wrong owner/beneficiary assumptions | Eligibility explainer + hard gate questions + citation links |
| 2. Open ABLE account | Create account successfully | Identity steps, representative authorization, document readiness | Abandonment during KYC/identity, legal rep mismatch | Progressive save, explicit ALR flow, checklist |
| 3. Plan a 529->ABLE transfer | Determine if transfer is legal and tax-safe | Federal/state rule mismatch, annual limit uncertainty | Nonqualified transfer, state recapture surprise | Preflight engine: relationship + annual-cap + state confidence |
| 4. Submit rollover | Execute transfer with both institutions | Form complexity, missing account numbers, notarization uncertainty | Rejection due to missing fields/cap/relationship errors | Guided packet builder + field validation + source-plan specific prompts |
| 5. Track transfer status | Know what is happening | Manual handoffs, no unified status visibility | Repeated support calls, user distrust | Status timeline + reason codes + escalation paths |
| 6. Ongoing contributions | Continue funding safely | Cap management across contributors | Accidental annual overfunding | Real-time contribution budget meter + alerts |
| 7. Distribution/documentation | Use funds and retain records | Unclear qualified expense substantiation | Audit/documentation gaps | Document vault + transaction tagging + exportable evidence pack |
| 8. Tax season support | File correctly | State line references and recapture questions | Wrong lines filed, missed add-back | State-specific filing helper with confidence badge |

## Major drop-off points (highest product urgency)

1. **Transfer preflight ambiguity** (qualified vs nonqualified, state consequences).
2. **Form completion burden** for direct rollovers.
3. **Post-submission silence** while plans coordinate manually.

## Instrumentation recommendations

- Funnel metrics by stage and reason code:
  - eligibility_started -> eligibility_passed
  - transfer_intent -> packet_complete -> packet_submitted -> transfer_completed
  - failure_reason distribution (cap, relationship, missing docs, source-plan rejection)
- Time metrics:
  - median time-to-open
  - median time-to-first-fund
  - median transfer cycle time
- Compliance metrics:
  - % transfers with archived attestation packet
  - % low-confidence state flows surfaced with warning
