# REQUIREMENTS_BACKLOG

Updated: 2026-03-11

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

5. **Authority-conflict detector (Tier-1 drift control)**
   - Detect when same-jurisdiction primary sources disagree (e.g., form text vs bulletin).
   - Mark rule as "conflict-open," downgrade automation confidence, and require compliance-review override.
   - Store side-by-side citation snippets and effective-date metadata.

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

10. **Cross-institution form router**
   - For each rollover path, show exact "download from X, submit to Y" instructions.
   - Include path-specific branching: direct transfer vs indirect rollover 60-day path.

## Experiments (next 2 sprints)

1. **Doc-collection-before-transfer A/B**
   - Metric: transfer exception rate, time-to-fund, abandonment.
2. **State-risk warning interstitial**
   - Metric: post-filing issue tickets, warning acknowledgment.
3. **Conflict-open escalation UX test**
   - Metric: false auto-approvals avoided, manual-review turnaround, user trust score.
