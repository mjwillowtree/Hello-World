# HUB (529 + ABLE Product Intelligence)

Updated: 2026-03-11

## What changed this week

### 2026-03-11 (hourly run)
- Advanced **Indiana** to high confidence with destination-sensitive recapture logic: Indiana529 -> Indiana ABLE (qualified from 2024) versus Indiana529 -> other ABLE programs (nonqualified for recapture), plus filing-flow references.
- Advanced **Utah** to medium confidence with line/code-level addback mapping (TC-40A code 54 -> TC-40 line 5) and IRC-exception linkage.
- Added **ABLE United** workflow evidence: 60-day closure/timing condition, potential notarization, and earnings-treatment fallback if statements are missing.
- Re-ranked opportunities and requirements with two new controls: destination-plan policy router and deadline countdown escalation.

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
- **State-by-state treatment:** Medium overall (heterogeneous; 12 rows now substantive)
- **Operational workflow understanding:** Medium-High for transfer failure + timing controls
- **Product opportunity signal strength:** Medium-High

## KPI snapshot

- State matrix completion (substantive rows): **12 / 51**
- High-confidence states: **12 / 51 (23.5%)**
- Domain coverage score (10 domains): **6.5 / 10**
- Tier-1 citation ratio (new substantive claims): **~90%**
- Competitor coverage count: **5**
- Validated product opportunities: **6**
- Unresolved critical unknowns: **8**
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

1. Close one of **NJ** or **PA** with explicit line-level return instruction treatment.
2. Pull exact **Indiana Schedule 4 line number** for recapture repayment.
3. Expand transfer workflow lane with measured timing/SLA evidence (p50/p90).
