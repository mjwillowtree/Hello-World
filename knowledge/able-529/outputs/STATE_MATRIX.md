# STATE_MATRIX (50 States + DC)

Updated: 2026-03-11

Primary data file: `outputs/STATE_MATRIX.csv`

## Coverage snapshot

- Jurisdictions tracked: **51 / 51**
- Substantively advanced rows (beyond placeholder): **12 / 51**
- High-confidence rows: **12 / 51**
- Latest state advancements: **New Jersey** (closure) and **Utah** (first-pass line mapping)

## New Jersey (advanced/closed this run)

### What is locked
- NJ-1040 instructions now provide line-level treatment relevant to 529/ABLE recapture logic.
- Instructions identify taxable interest treatment for earnings on nonqualified distributions from qualified tuition program accounts (including NJBEST) and qualified state 529A ABLE accounts.
- Instructions also flag distribution portions attributable to contributions previously deducted on New Jersey returns.

### Sources (Tier 1)
- https://www.njportal.com/Taxation/NJ1040/Content/Docs/Instructions/Current_NJ1040Instructions.pdf
- https://www.nj.gov/treasury/taxation/individuals/collegededuction.shtml

### Confidence
- **High**

## Utah (advanced this run)

### What is locked
- Utah TC-40A instructions provide explicit addback line mechanics for my529 withdrawals.
- TC-40A Part 1 code 54 (my529 addback) cites UCA Section 59-10-114(1)(d) and flows into TC-40 line 5.
- Addback applies where withdrawals are not for qualified education expenses and do not meet IRC 529(c)/530(d) exceptions.

### Sources (Tier 1)
- https://tax.utah.gov/forms/current/tc-40inst.pdf
- https://tax.utah.gov/forms/current/tc-40a.pdf

### Confidence
- **Medium-High** (line-level addback workflow is clear; explicit ABLE carveout text still open)

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
- New Jersey (High; line-level closure completed)
- Pennsylvania (Medium-Low; line-level closure pending)
- Oregon (Low)
- Colorado (Low)
- Virginia (Low)
- New York (Low)
- Utah (Medium-High)

## Priority closure queue (next)

1. **Pennsylvania**: PA-40 line-level treatment for 529->ABLE.
2. **Indiana**: first-pass Tier-1 row with code/line references.
3. **Minnesota**: explicit ABLE carveout confirmation vs current recapture inference.
4. **Utah**: close ABLE-specific treatment from conditional to explicit.

## Interpretation notes

- Federal qualified treatment is not enough to infer state no-recapture treatment.
- Confidence labels are legal-operational confidence for product design, not individualized tax advice certainty.
