# HUB (529 + ABLE Product Intelligence)

Updated: 2026-03-11

## What changed this week

### 2026-03-11 (hourly cron run)
- Advanced **Indiana** to high confidence using Tier-1 forms + Jan 2026 DOR bulletin:
  - destination-specific recapture logic (Indiana ABLE 529A carveout vs other ABLE plans),
  - line-level filing map (IN-CR line 9 -> IT-40 Schedule 4 line 3).
- Added new operational competitor evidence from **PA ABLE** direct rollover form:
  - conditional Medallion Signature Guarantee path,
  - destination-limit rejection risk,
  - full-earnings default if basis/earnings statement missing.
- Upgraded **ABLEnow** workflow confidence to High with explicit basis/earnings and signature requirements from official indirect rollover form.
- Re-ranked opportunities/backlog to include a destination-rule decision layer and signature-guarantee gate.

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
- **State-by-state treatment:** Medium overall (heterogeneous; 11/51 substantive rows now closed)
- **Operational workflow understanding:** High for documentation/signature failure controls
- **Product opportunity signal strength:** Medium-High

## KPI snapshot

- State matrix completion (substantive rows): **11 / 51**
- High-confidence states: **12 / 51 (23.5%)**
- Domain coverage score (10 domains): **6.4 / 10**
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
2. Advance **UT** with Tier-1 form/code references.
3. Expand transfer workflow lane from form requirements to observed timing/SLA distribution evidence.
