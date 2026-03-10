# STATE_MATRIX (50 States + DC)

Updated: 2026-03-10

Primary data file: `outputs/STATE_MATRIX.csv`

## Coverage snapshot

- Jurisdictions tracked: **51 / 51**
- Substantively advanced rows (beyond placeholder): **11 / 51**
- High-confidence rows: **11 / 51**
- Latest state advancements: **Utah** (with Minnesota and Ohio carried forward)

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

## Utah (advanced)

### What is locked
- Utah TC-40A instructions map **my529 addback** to Part 1, code 54, and state that Part 1 totals carry to TC-40 line 5.
- Utah Code §59-10-114(1)(d) codifies addback mechanics for withdrawn my529 amounts when amounts are not used for qualifying purposes and links exceptions to IRC §§529(c) and 530(d).

### Sources (Tier 1)
- https://incometax.utah.gov/additions/my529-addback
- https://le.utah.gov/xcode/Title59/Chapter10/C59-10-S114_2025101420251206.html
- https://files.tax.utah.gov/tax/forms/current/tc-40.pdf

### Confidence
- **Medium-High** (line mapping is clear; explicit Utah instruction text naming 529->ABLE remains unresolved)

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
3. **Indiana**: first-pass Tier-1 row with code/line references.
4. **Minnesota**: close explicit ABLE carveout question (if any) from Tier-1 text.

## Interpretation notes

- Federal qualified treatment is not enough to infer state no-recapture treatment.
- Confidence labels are legal-operational confidence for product design, not individualized tax advice certainty.
