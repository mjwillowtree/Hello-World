# REQUIREMENTS_BACKLOG

Updated: 2026-03-10

## P0 (ship-first requirements)

1. **Rollover preflight checklist service**
   - Validate required artifacts before submission:
     - distributing plan statement with earnings/principal split
     - beneficiary identity and relationship evidence
     - contribution-limit budget for current tax year
   - Block submission when required items are missing; generate remediation guidance.

2. **Evidence-attached decision record**
   - For each rollover decision, store:
     - jurisdiction + filing year
     - source URLs + retrieval date
     - confidence label + unresolved unknowns
   - Must support audit replay for support/compliance.

3. **State-treatment rules registry (versioned)**
   - Key by jurisdiction + filing year.
   - Fields: conformity notes, recapture trigger text, form line references, confidence.
   - Unknown states must route to manual review.

4. **Transfer packet generator**
   - Collect required source/destination metadata.
   - Produce completed handoff packet and checklist (including notarization/signature warnings).

5. **Good-order rules engine + SLA prediction band**
   - Compute a "good-order" score from required fields/docs/signatures.
   - Surface dependency warnings (for example, source-institution medallion requirement risk).
   - Show probabilistic completion band (not a guaranteed date) tied to packet completeness.

## P1

6. **Transfer journey status tracker**
   - Milestones: request created -> outbound plan contacted -> docs received -> compliance validated -> posted.
   - Exception states: missing earnings breakdown, signature mismatch, beneficiary mismatch.

7. **Beneficiary/family relationship wizard**
   - Guided questions that produce relationship eligibility output and attestation capture.

8. **Citation-backed FAQ service**
   - Every answer includes confidence and source tier badges.
   - Low-confidence answers include "what could change this".

9. **State filing helper**
   - Show line references when confidence is high; otherwise warn and route to review.

## Experiments (next 2 sprints)

1. **Doc-collection-before-transfer A/B**
   - Metric: transfer exception rate, time-to-fund, abandonment.
2. **State-risk warning interstitial**
   - Metric: post-filing issue tickets, warning acknowledgment.
3. **Good-order score visibility experiment**
   - Metric: p50 time-to-fund, % transfers entering exception queue, support-contact rate per transfer.
