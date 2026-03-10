# ABLE + 529 Product Intelligence HUB

Last updated: 2026-03-10 (hourly run)

## What changed this week

- Built the full `outputs/` artifact set for human navigation and decision support.
- Advanced **Ohio** in the state matrix to higher confidence using line-level 2024 Ohio IT 1040 Schedule of Adjustments instructions and form lines.
- Added one operational competitor datapoint from an official 529->ABLE direct rollover form (ABLE for ALL), including workflow constraints (pre-open account, annual-limit gating, same-beneficiary/family-member checks, potential notarization, paper/fax channels).
- Converted the prior "state watchlist" into a durable 50-state + DC matrix structure with confidence and citations.
- Added product requirements focused on pre-submit compliance checks, state recapture logic, and transfer-document orchestration.

## Confidence summary (current)

- Federal baseline (core mechanics): **High**
- State tax treatment (50-state+DC completeness): **Low-Medium overall**
- Operational transfer workflows: **Low-Medium**
- Product opportunity confidence: **Medium**

## KPI snapshot (this run)

- State matrix completion: **9 / 51**
- % high-confidence states: **33%** (3/9 completed states)
- Domain coverage score (10 domains): **6.1 / 10**
- Tier-1 citation ratio (new substantive claims this run): **80%**
- Competitor coverage count: **2**
- Validated product opportunities: **5**
- Unresolved critical unknowns: **9**
- Time-to-answer test (top 25 questions): **13/25 answerable quickly with citations**

## Documents

- [EXEC_SUMMARY.md](./EXEC_SUMMARY.md)
- [LEGAL_BASELINE.md](./LEGAL_BASELINE.md)
- [STATE_MATRIX.md](./STATE_MATRIX.md)
- [STATE_MATRIX.csv](./STATE_MATRIX.csv)
- [COMPETITOR_LANDSCAPE.md](./COMPETITOR_LANDSCAPE.md)
- [USER_JOURNEY_MAP.md](./USER_JOURNEY_MAP.md)
- [PRODUCT_OPPORTUNITIES.md](./PRODUCT_OPPORTUNITIES.md)
- [REQUIREMENTS_BACKLOG.md](./REQUIREMENTS_BACKLOG.md)
- [FAQ.md](./FAQ.md)

## Known conflicts requiring explicit handling

1. Federal statutory updates may outpace IRS newsroom/page refreshes.
2. Federal "qualified" treatment does not guarantee state non-recapture treatment.
3. Plan workflow forms may include operational constraints not obvious from tax law summaries.
