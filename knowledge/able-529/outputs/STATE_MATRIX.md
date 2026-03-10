# STATE_MATRIX (50 States + DC)

Updated: 2026-03-10

Primary data file: `outputs/STATE_MATRIX.csv`

## Coverage snapshot

- Jurisdictions tracked: **51 / 51**
- Substantively advanced rows (beyond placeholder): **11 / 51**
- High-confidence rows: **11 / 51**
- Latest state advancements: **Ohio** and **Indiana**

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

## Indiana (advanced)

### What is locked
- Indiana guidance ties 529 nonqualified withdrawals (including rollover/transfer scenarios in state guidance context) to credit recapture.
- Recapture workflow is form-structured: compute on IN-529R, then report through IN-CR to the individual return schedules.
- Indiana ABLE contribution credit is mapped separately through IN-ABLE line 14 to Schedule 6 line 6 (IT-40 path).

### Sources (Tier 1)
- https://www.in.gov/dor/files/ib98.pdf
- https://www.in.gov/tos/iesa/tax-credit/tax-credit-faq/
- https://forms.in.gov/Download.aspx?id=10171
- https://forms.in.gov/Download.aspx?id=16371
- https://forms.in.gov/Download.aspx?id=16956

### Confidence
- **Medium-High** (line workflow is usable; exact annual form-version line shifts still require periodic refresh)

## Previously advanced states (carry-forward)

- California (High)
- Illinois (High)
- New Jersey (Medium; line-level closure pending)
- Pennsylvania (Medium-Low; line-level closure pending)
- Oregon (Low)
- Colorado (Low)
- Virginia (Low)
- New York (Low)
- Minnesota (Medium-High)

## Priority closure queue (next)

1. **New Jersey**: NJ-1040 line-level treatment for 529->ABLE.
2. **Pennsylvania**: PA-40 line-level treatment for 529->ABLE.
3. **Utah**: first-pass Tier-1 row with code/line references.
4. **Minnesota**: explicit ABLE carveout confirmation vs current recapture inference.

## Interpretation notes

- Federal qualified treatment is not enough to infer state no-recapture treatment.
- Confidence labels are legal-operational confidence for product design, not individualized tax advice certainty.
