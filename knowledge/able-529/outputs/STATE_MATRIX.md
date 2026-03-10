# STATE_MATRIX (50 States + DC)

Updated: 2026-03-10

Primary data file: `outputs/STATE_MATRIX.csv`

## Coverage snapshot

- Jurisdictions tracked: **51 / 51**
- Substantively advanced rows (beyond placeholder): **11 / 51**
- High-confidence rows: **11 / 51**
- Latest state advancements: **Utah** (new), plus prior **Minnesota** and **Ohio**

## Utah (advanced this run)

### What is locked
- Utah TC-40 instructions explicitly include a **my529 addback** category and route all additions through TC-40A Part 1 to TC-40 line 5.
- The code-specific instruction block states `(54) my529 Addback` applies when a my529 withdrawal is not used for qualified education expenses and does not meet an exception under IRC §529(c) or §530(d), limited to previously deducted/credited amounts.

### Sources (Tier 1)
- https://tax.utah.gov/forms/current/tc-40-fullpacket.pdf
- https://incometax.utah.gov/additions/my529-addback
- https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim

### Confidence
- **Medium-High** (line/code treatment is explicit; remaining open item is filing-year conformity mechanics for amended federal sunset language)

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
3. **Indiana**: first-pass Tier-1 row with code/line references.
4. **Minnesota**: explicit ABLE carveout confirmation (if any) vs nonqualified-distribution inference.

## Interpretation notes

- Federal qualified treatment is not enough to infer state no-recapture treatment.
- Confidence labels are legal-operational confidence for product design, not individualized tax advice certainty.
