# STATE_MATRIX (50 States + DC)

Updated: 2026-03-11

Primary data file: `outputs/STATE_MATRIX.csv`

## Coverage snapshot

- Jurisdictions tracked: **51 / 51**
- Substantively advanced rows (beyond placeholder): **12 / 51**
- High-confidence rows: **12 / 51**
- Latest state advancements: **Indiana** and **Utah**

## Indiana (advanced)

### What is locked
- IN-CR instructions state that a non-qualified Indiana529 withdrawal includes a rollover/transfer from Indiana529 to any other Code Section 529 plan or ABLE account.
- IN-CR total recapture flows to IT-40 Schedule 4 line 3 (or IT-40PNR Schedule E line 3), and Schedule 4 line 3 is the recapture line.

### Sources (Tier 1)
- https://forms.in.gov/Download.aspx?id=16957
- https://forms.in.gov/Download.aspx?id=16938
- https://forms.in.gov/Download.aspx?id=16915
- https://secure.iot.in.gov/dor/7101.htm

### Confidence
- **High**

## Utah (advanced)

### What is locked
- Utah TC-40A instructions identify my529 addback as code 54 in Part 1 and carry total additions to TC-40 line 5.
- The my529 addback trigger applies when a withdrawal was not used for qualified education expenses and did not meet an exception under IRC Section 529(c) or 530(d).

### Sources (Tier 1)
- https://incometax.utah.gov/additions/my529-addback
- https://incometax.utah.gov/tc-40a/

### Confidence
- **Medium-High**

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

## Ohio (advanced, prior run)

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
3. **Minnesota**: explicit ABLE carveout confirmation vs inference.
4. **Year-over-year drift checks**: verify TY2026 carry-forward wording in newly advanced states.

## Interpretation notes

- Federal qualified treatment is not enough to infer state no-recapture treatment.
- Confidence labels are legal-operational confidence for product design, not individualized tax advice certainty.
