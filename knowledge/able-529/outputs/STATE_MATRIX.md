# STATE_MATRIX (50 States + DC)

Updated: 2026-03-11

Primary data file: `outputs/STATE_MATRIX.csv`

## Coverage snapshot

- Jurisdictions tracked: **51 / 51**
- Substantively advanced rows (beyond placeholder): **11 / 51**
- High-confidence rows: **12 / 51**
- Latest state advancement: **Indiana**

## Indiana (advanced)

### What is locked
- Indiana's 2025 Schedule IN-CR maps recapture to return filing lines (line 9 flows to IT-40 Schedule 4, line 3).
- Indiana DOR Information Bulletin #98 (Jan 2026) states that, for 2024 and later, transfer from Indiana529 to an **Indiana ABLE 529A** plan is treated as qualified, while transfer to other ABLE plans is nonqualified for credit-recapture purposes.
- Indiana Schedule IN-529 also excludes contributions intended for transfer to ABLE from credit-eligible contributions and maps the credit carry line (line 16 to Schedule 6, line 6).

### Sources (Tier 1)
- https://forms.in.gov/Download.aspx?id=16957
- https://forms.in.gov/Download.aspx?id=16915
- https://forms.in.gov/Download.aspx?id=16907
- https://www.in.gov/dor/files/ib98.pdf

### Confidence
- **High**

## Minnesota (advanced)

### What is locked
- Minnesota DOR indicates recapture tax may apply when 529 distributions are used for nonqualified expenses.
- TY2025 Schedule M1529 computes recapture on lines 7-15, and line 15 flows to Form M1 line 14.

### Sources (Tier 1)
- https://www.revenue.state.mn.us/education-savings-account-recapture-tax
- https://www.revenue.state.mn.us/education-savings-account-contribution-subtraction
- https://www.revenue.state.mn.us/sites/default/files/2025-10/m1529-25-grid.pdf

### Confidence
- **Medium-High** (line flow is clear; explicit ABLE carveout text still unresolved)

## Ohio (advanced)

### What is locked
- Schedule of Adjustments line mapping includes line 4 (nonqualified 529 addition), line 20 (STABLE deduction), and line 36 (529 deduction).
- 2024 booklet instruction text ties line-4 addition to specific nonqualified scenarios and prior Ohio deduction history.

### Sources (Tier 1)
- https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/scheduleofadjustments.pdf
- https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/it1040-booklet.pdf

### Confidence
- **High**

## Previously advanced states (carry-forward)

- California (High)
- Illinois (High)
- Indiana (High)
- New Jersey (Medium; line-level closure pending)
- Pennsylvania (Medium-Low; line-level closure pending)
- Oregon (Low)
- Colorado (Low)
- Virginia (Low)
- New York (Low)

## Priority closure queue (next)

1. **New Jersey**: NJ-1040 line-level treatment for 529->ABLE.
2. **Pennsylvania**: PA-40 line-level treatment for 529->ABLE.
3. **Utah**: first-pass Tier-1 row with code/line references.

## Interpretation notes

- Federal qualified treatment is not enough to infer state no-recapture treatment.
- Confidence labels are legal-operational confidence for product design, not individualized tax advice certainty.
