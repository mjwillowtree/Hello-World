# HUB (529 + ABLE Product Intelligence)

Updated: 2026-03-11

## What changed this week

### 2026-03-11 (hourly run)
- Advanced **Utah** from placeholder to substantive row using statute + instruction mapping:
  - Utah Code 59-10-114(1)(d) exception-aware addback trigger
  - TC-40A Part 1 code 54 -> TC-40 line 5 flow
- Upgraded **Pennsylvania** line-level closure for nonqualified distributions:
  - PA DOR Answer ID 2517 maps nonqualified 529 distributions to PA Schedule A and PA-40 line 2
  - PA Schedule O -> PA-40 line 10 deduction flow reaffirmed
- Added new competitor/workflow datapoint for **PA ABLE**:
  - Conditional Medallion/signature-guarantee step
  - Full-amount-as-earnings fallback pending source earnings/cost-basis certification
  - Rejection risk when rollover exceeds annual contribution or account balance limits
- Added product requirement/opportunity: **source-plan signature-guarantee rules service**.

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
- **State-by-state treatment:** Low-to-Medium overall (heterogeneous; Utah and PA improved this run)
- **Operational workflow understanding:** Medium-High for transfer failure controls
- **Product opportunity signal strength:** Medium-High

## KPI snapshot

- State matrix completion (substantive rows): **11 / 51**
- High-confidence states: **11 / 51 (21.6%)**
- Domain coverage score (10 domains): **6.5 / 10**
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

1. Close **NJ** with explicit NJ-1040 line-level treatment for 529->ABLE.
2. Advance **IN** with Tier-1 form/code references.
3. Expand transfer workflow lane with timing/SLA and rejection-code evidence.
