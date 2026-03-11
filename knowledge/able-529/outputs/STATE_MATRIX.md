# STATE_MATRIX (50 States + DC)

Updated: 2026-03-11

Primary data file: `outputs/STATE_MATRIX.csv`

## Coverage snapshot

- Jurisdictions tracked: **51 / 51**
- Substantively advanced rows (beyond placeholder): **11 / 51**
- High-confidence rows: **11 / 51**
- Latest state advancements: **Indiana** (plus prior Minnesota and Ohio)

## Indiana (advanced)

### What is locked
- Indiana DOR Bulletin 98 (Jan 2026) states that beginning in 2024, transfer of Indiana529 funds to an **Indiana ABLE 529A** plan is treated as a qualified withdrawal for credit-recapture purposes.
- The same bulletin states that for 2024+ transfers to ABLE accounts **other than Indiana ABLE 529A** are not qualified withdrawals for recapture purposes.
- Schedule IN-CR provides return-line flow for recapture amounts (line 9 to IT-40 Schedule 4 line 3 / IT-40PNR Schedule E line 3) and code mapping.

### Sources (Tier 1)
- https://www.in.gov/dor/files/ib98.pdf
- https://forms.in.gov/Download.aspx?id=16371
- https://forms.in.gov/Download.aspx?id=16907

### Confidence
- **Medium-High** (bulletin-level treatment is explicit; monitor for annual IN-CR instruction synchronization language)

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
4. **Minnesota closure**: explicit ABLE carveout confirmation (if any) versus recapture inference.

## Interpretation notes

- Federal qualified treatment is not enough to infer state no-recapture treatment.
- Confidence labels are legal-operational confidence for product design, not individualized tax advice certainty.
