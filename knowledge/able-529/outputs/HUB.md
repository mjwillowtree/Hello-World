# HUB (529 + ABLE Product Intelligence)

Updated: 2026-03-11

## What changed this week

### 2026-03-11 (hourly run)
- Closed **New Jersey** to high confidence with NJ-1040 line-level treatment (qualified vs nonqualified 529/ABLE distribution handling).
- Advanced **Utah** from placeholder to code-level row (TC-40A Part 1 code 54 my529 addback -> TC-40 line 5).
- Added **STABLE Account** competitor workflow constraint: one rollover per 12 months plus 60-day prior-account closure controls.
- Added and promoted new product requirement/opportunity: cooldown + closure eligibility gate in preflight flow.

### 2026-03-10 (merged branch context)
- Resolved federal quote-ready authority block for post-2025 529->ABLE continuity (Pub. L. 119-21 Sec. 70117).
- Advanced **Minnesota** with line-level recapture flow (M1529 -> M1 line 14).
- Advanced **Ohio** with line-level Schedule of Adjustments treatment (lines 4, 20, 36 + instruction logic).
- Expanded competitor workflow evidence across **Fidelity, ABLE for ALL, Texas ABLE, ABLEnow**.
- Re-ranked opportunities toward evidence-first transfer controls (preflight + documentation + state-risk handling).

### Earlier this week
- Established QMD protocol and frontier-question engine.
- Built initial 50-state + DC matrix scaffold.
- Upgraded federal rollover legality confidence using enacted statute and codified-text checks.

## Confidence summary

- **Federal legal baseline:** High
- **State-by-state treatment:** Medium overall (heterogeneous; subset line-level closed with NJ upgrade)
- **Operational workflow understanding:** Medium-High for transfer failure controls
- **Product opportunity signal strength:** Medium-High

## KPI snapshot

- State matrix completion (substantive rows): **12 / 51**
- High-confidence states: **12 / 51 (23.5%)**
- Domain coverage score (10 domains): **6.5 / 10**
- Tier-1 citation ratio (new substantive claims): **~90%**
- Competitor coverage count: **5**
- Validated product opportunities: **6**
- Unresolved critical unknowns: **7**
- Time-to-answer test (top 25, citation-ready quickly): **16 / 25**

## Navigation

- Executive brief: `outputs/EXEC_SUMMARY.md`
- Legal baseline: `outputs/LEGAL_BASELINE.md`
- State matrix (full CSV): `outputs/STATE_MATRIX.csv`
- State matrix (human summary): `outputs/STATE_MATRIX.md`
- Competitor landscape: `outputs/COMPETITOR_LANDSCAPE.md`
- Product opportunities: `outputs/PRODUCT_OPPORTUNITIES.md`
- User journey map: `outputs/USER_JOURNEY_MAP.md`
- Requirements backlog: `outputs/REQUIREMENTS_BACKLOG.md`
- FAQ: `outputs/FAQ.md`
- Run audit log: `QMD_LOG.md`

## Immediate next-run targets

1. Close **Pennsylvania** with explicit PA-40 line-level treatment and Act 56 conformity implications.
2. Advance **Indiana** with Tier-1 form/code references.
3. Expand transfer workflow lane from form requirements to measured settlement timing/SLA evidence.
