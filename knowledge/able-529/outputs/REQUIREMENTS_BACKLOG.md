# REQUIREMENTS_BACKLOG

Updated: 2026-03-10

## P0 (ship-first requirements)

1. **Rollover preflight checklist service**
   - Validate required artifacts before submission:
     - distributing plan statement with earnings/principal split
     - beneficiary identity and relationship evidence
     - contribution-limit budget for current tax year
   - Block submission when required items are missing; generate user-readable remediation steps.
   - Evidence:
     - Fidelity and Texas ABLE forms warn missing documentation can cause full amount to be treated as earnings.

2. **Evidence-attached decision record**
   - For each rollover decision, store:
     - jurisdiction + tax year
     - source URLs and retrieval date
     - confidence label and unresolved unknowns
   - Must support audit replay in support/compliance workflows.

3. **State-treatment rules registry (versioned)**
   - State row key: jurisdiction + filing year.
   - Fields: conformity notes, recapture trigger text, form line references, confidence.
   - Expose unresolved states as "manual review required" instead of silent assumptions.

## P1

4. **Transfer journey status tracker**
   - Milestones: request created -> outbound plan contacted -> docs received -> compliance validated -> posted.
   - Exception states: missing earnings breakdown, signature mismatch, beneficiary mismatch.

5. **Beneficiary/family relationship wizard**
   - Guided questions translate to IRC family-member eligibility outputs.
   - Capture user attestation and evidence artifact.

6. **Citation-backed FAQ service**
   - Every answer includes confidence and source tier badges.
   - If confidence < High, include "what could change this answer" note.

## Experiments (next 2 sprints)

1. **Doc-collection-before-transfer A/B test**
   - Hypothesis: upfront evidence collection reduces exception rate and support contacts.
   - Metric: transfer exception rate, time-to-fund, transfer abandonment.

2. **State-risk interstitial test**
   - Hypothesis: explicit state recapture warning before submission reduces downstream complaint volume.
   - Metric: warning acknowledgment rate, post-filing issue tickets.

## Compliance constraints (must encode)

- Do not auto-assert state no-recapture unless row confidence is High and line-level authority is present.
- Distinguish legal authority from plan operational policy in all user-facing explanations.
- Preserve immutable timestamps and citation snapshots for decisions touching tax treatment.
