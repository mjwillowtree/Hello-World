# STATE_MATRIX (50 States + DC)

Updated: 2026-03-10

Primary data file: `outputs/STATE_MATRIX.csv`

## Coverage snapshot

- Jurisdictions tracked: **51/51**
- Substantively advanced rows (beyond placeholder): **9/51**
- High-confidence rows: **10/51** (includes no-income-tax jurisdictions where recapture is N/A)
- This run's state advancement: **Minnesota** (new recapture workflow + line-level form flow captured)

## Minnesota (advanced this run)

### What is newly locked
- Minnesota DOR states recapture tax may apply when a 529 distribution is used for nonqualified expenses (including K-12 or expenses other than post-secondary attendance).
- TY2025 Schedule M1529 directs recapture computation on lines 7-15, and line 15 flows to Form M1 line 14.

### Sources (Tier 1)
- https://www.revenue.state.mn.us/education-savings-account-recapture-tax
- https://www.revenue.state.mn.us/education-savings-account-contribution-subtraction
- https://www.revenue.state.mn.us/sites/default/files/2025-10/m1529-25-grid.pdf

### Confidence
- **Medium-High** (explicit recapture mechanics and line flow are clear; explicit ABLE carveout language not yet found).

## Previously advanced states (carry-forward)

- California (High)
- Illinois (High)
- New Jersey (Medium; line-level closure pending)
- Pennsylvania (Medium-Low; line-level closure pending)
- Oregon (Low)
- Colorado (Low)
- Virginia (Low)
- New York (Low)

## Priority closure queue (next)

1. **New Jersey**: NJ-1040 line-level treatment for 529->ABLE.
2. **Pennsylvania**: PA-40 line-level treatment for 529->ABLE.
3. **Ohio**: first-pass Tier-1 row with form-line references.
4. **Utah**: first-pass Tier-1 row with code/line references.

## Notes on interpretation

- Federal qualified status is not sufficient to infer state no-recapture treatment.
- Confidence labels are legal-operational confidence for product design, not personalized tax advice certainty.
