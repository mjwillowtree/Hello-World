# HUB (529 + ABLE Product Intelligence)

Updated: 2026-03-11

## What changed this week

### 2026-03-11 (hourly cron run)
- Advanced **Indiana** from placeholder to substantive treatment with line-level recapture flow and a destination-sensitive rule (Indiana ABLE 529A vs other ABLE programs).
- Logged an explicit Indiana authority-synchronization conflict (newer Bulletin 98 vs broad IN-CR wording) and set implementation posture to Medium-High confidence pending form synchronization.
- Added a new operational datapoint from official ABLE Utah/STABLE direct rollover form: conditional notarization and full rejection risk for over-limit contributions.
- Added and prioritized a new ship-critical requirement: **annual-limit reservation ledger** to prevent all-or-nothing transfer failures.

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
- **State-by-state treatment:** Low-to-Medium overall (heterogeneous; 11 substantive rows, Indiana destination-rule nuance now captured)
- **Operational workflow understanding:** Medium-High for transfer failure controls
- **Product opportunity signal strength:** Medium-High

## KPI snapshot

- State matrix completion (substantive rows): **11 / 51**
- High-confidence states: **11 / 51 (21.6%)**
- Domain coverage score (10 domains): **6.4 / 10**
- Tier-1 citation ratio (new substantive claims): **~92%**
- Competitor coverage count: **5**
- Validated product opportunities: **6**
- Unresolved critical unknowns: **9**
- Time-to-answer test (top 25, citation-ready quickly): **15 / 25**

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
2. Advance **UT** with Tier-1 form/code references.
3. Quantify operational timing/SLA evidence (p50/p90 transfer completion + exception reasons) from official/admin sources.
