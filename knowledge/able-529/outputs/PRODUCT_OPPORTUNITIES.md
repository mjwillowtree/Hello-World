# Product Opportunities (Ranked)

Updated: 2026-03-10

Scoring basis: impact on user risk + conversion + operational feasibility + compliance defensibility.

## Ranked opportunities

| Rank | Opportunity | Evidence | Impact | Feasibility | Compliance constraints | Confidence |
|---:|---|---|---|---|---|---|
| 1 | State-aware rollover qualification engine | Ohio line-level rules and existing multi-state recapture variance show federal-only logic is insufficient. | Very High (risk reduction + trust + fewer tax errors) | Medium | Must show confidence labels and citation links by state; no silent auto-advice in low-confidence states. | High |
| 2 | Transfer packet builder (form orchestration + preflight checks) | ABLE for ALL form requires structured data from both accounts, relationship certification, and possible notarization. | High (drop-off reduction and faster successful transfer) | High | Capture attestations and generated artifacts for audit trail. | High |
| 3 | Contribution-cap collision detector | ABLE rollover forms explicitly warn that contributions above allowed annual amount can be rejected. | High (prevents failed transfers, user frustration) | Medium | Must align with annual limit logic and ABLE-to-Work edge cases. | Medium |
| 4 | Confidence-scored answer center | Guidance lag and state variance require transparent evidence and confidence scoring. | Medium-High (support deflection + compliance) | High | Must preserve source lineage and versioning. | Medium-High |
| 5 | State recapture warning + filing-line helper | Ohio shows explicit line-level tax return mapping that users rarely know. | Medium-High | Medium | Should present "information support" not tax-advice overreach where confidence is low. | Medium |

## Newly validated this run

- Opportunity #1 strengthened by Ohio line-level evidence.
- Opportunity #2 strengthened by official form-driven competitor workflow evidence.
- Opportunity #5 added as a distinct requirement (line-reference guidance in post-transfer UX).

## Deprioritized for now

- Advanced personalization based on household scenario archetypes (blocked by incomplete state matrix and insufficient operational timing data).
