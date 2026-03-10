# HUB (529 + ABLE Product Intelligence)

Updated: 2026-03-10

## What changed this week

### 2026-03-10 (merged branch context)
- Resolved federal quote-ready authority block for post-2025 529->ABLE continuity (Pub. L. 119-21 Sec. 70117).
- Advanced **Minnesota** with line-level recapture flow (M1529 -> M1 line 14).
- Advanced **Ohio** with line-level Schedule of Adjustments treatment (lines 4, 20, 36 + instruction logic).
- Expanded competitor workflow evidence across **Fidelity, ABLE for ALL, Texas ABLE, ABLEnow**.
- Re-ranked opportunities toward evidence-first transfer controls (preflight + documentation + state-risk handling).

### 2026-03-10 (23:01 UTC cron run)
- Advanced **Indiana** from placeholder to substantive row with recapture workflow references (IN-529R, IN-CR, Schedule 4 line routing) and ABLE credit line mapping (IN-ABLE line 14 -> Schedule 6 line 6).
- Added **STABLE Account** competitor workflow evidence: source-plan notarization may be required in direct 529->ABLE rollover process.
- Added new product lane: **credit-recapture calculator + form-router** and corresponding backlog requirement.
- Challenged assumption that "credit states generally mirror federal rollover friendliness"; Indiana evidence rejected that assumption.

### Earlier this week
- Established QMD protocol and frontier-question engine.
- Built initial 50-state + DC matrix scaffold.
- Upgraded federal rollover legality confidence using enacted statute and codified-text checks.

## Confidence summary

- **Federal legal baseline:** High
- **State-by-state treatment:** Low-to-Medium overall (heterogeneous; only subset line-level closed)
- **Operational workflow understanding:** Medium-High for transfer failure controls
- **Product opportunity signal strength:** Medium-High

## KPI snapshot

- State matrix completion (substantive rows): **11 / 51**
- High-confidence states: **11 / 51 (21.6%)**
- Domain coverage score (10 domains): **6.4 / 10**
- Tier-1 citation ratio (new substantive claims): **~90%**
- Competitor coverage count: **5**
- Validated product opportunities: **6**
- Unresolved critical unknowns: **8**
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
3. Expand transfer workflow lane with timing/SLA and rejection-code evidence.
