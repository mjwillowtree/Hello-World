# HUB (529 + ABLE Product Intelligence)

Updated: 2026-03-10

## What changed this week

### 2026-03-10 (19:01 UTC cron run)
- Closed **Indiana** from placeholder to high-confidence with destination-sensitive rule: 529->Indiana ABLE (qualified in 2024+) vs 529->other ABLE (nonqualified in 2024+), plus return-line flow (IN-CR line 9 -> IT-40 Schedule 4 line 3).
- Challenged and refined IRS-guidance-lag assumption: current **Pub 970/Pub 907** language checked this run appears conformed (no sunset phrase found), while legacy IRS newsroom pages remain stale.
- Added new competitor workflow datapoint: **PA ABLE** incoming direct rollover form explicitly warns that over-limit rollover contributions will be rejected and may require signature-guarantee handling.
- Added new product requirement/opportunity: destination-sensitive routing gate keyed to state/tax-year rules.

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
- **State-by-state treatment:** Low-to-Medium overall (heterogeneous; Indiana advanced to destination-sensitive High confidence)
- **Operational workflow understanding:** Medium-High for transfer failure controls
- **Product opportunity signal strength:** Medium-High

## KPI snapshot

- State matrix completion (substantive rows): **11 / 51**
- High-confidence states: **12 / 51 (23.5%)**
- Domain coverage score (10 domains): **6.6 / 10**
- Tier-1 citation ratio (new substantive claims): **~92%**
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

1. Close one of **NJ** or **PA** with explicit line-level return instruction treatment (DOR/return instructions, not plan forms).
2. Advance **UT** with a directly retrievable Tier-1 line/code citation (current Utah tax site blocked from this environment).
3. Quantify transfer timing distributions (p50/p90) and top rejection codes from administrator-facing evidence.
