# Requirements Backlog (Prioritized for Shipping)

Updated: 2026-03-10

Prioritization rubric: risk reduction, decision value, user impact, implementation effort.

## P0 (next sprint candidates)

1. **Rollover Preflight Checker**
   - Checks:
     - Beneficiary relationship validity (same beneficiary/family-member logic)
     - Remaining annual contribution headroom
     - State confidence + recapture warning state
   - Acceptance:
     - Blocks obviously invalid submissions.
     - Shows citations and confidence label.
   - Evidence:
     - Ohio line-level recapture logic and ABLE for ALL form constraints.

2. **Transfer Packet Generator**
   - Features:
     - Collects required source and destination account metadata.
     - Produces completed handoff packet and checklist (including notarization warning where applicable).
   - Acceptance:
     - Packet completeness score >= 95%.
     - Missing-field rejection rate reduced.

3. **Transfer Status + Reason Codes**
   - Features:
     - User-visible status timeline.
     - Standardized reason codes for delays/rejections.
   - Acceptance:
     - Reduction in "where is my transfer?" support contacts.

## P1

4. **State Filing Helper**
   - Shows state-specific line references and whether recapture/add-back may apply.
   - Warns when state confidence is low and routes to manual review.

5. **Evidence Vault**
   - Store signed attestations, submitted forms, and source citations per transfer.
   - Exportable audit package for support/compliance.

## P2

6. **FAQ Auto-Answer Layer**
   - High-frequency answers with confidence + source links.
   - Escalate to specialist when confidence < threshold.

7. **Experiment: Dynamic Confidence UX**
   - A/B test confidence-badge designs to reduce false certainty while preserving conversion.

## Experiments queue

| Experiment | Hypothesis | Primary metric | Guardrail |
|---|---|---|---|
| Preflight checker before form stage | Early compliance checks reduce failed submissions | transfer_success_rate | no drop in eligibility_passed_rate > 5% |
| Auto-generated document checklist | Checklist reduces missing-info rejects | packet_rejection_rate | support_contact_rate |
| State warning banner in low-confidence states | Transparent uncertainty increases trust | user_trust_score | completion_rate |
