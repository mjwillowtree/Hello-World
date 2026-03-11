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
- Indiana DOR Information Bulletin #98 (Jan 2026) states that, beginning in 2024, a transfer from Indiana529 to an **Indiana ABLE 529A savings plan** is treated as a qualified withdrawal.
- The same bulletin lists transfers to ABLE programs other than Indiana ABLE as nonqualified withdrawals for credit-recapture purposes (2024+).
- TY2025 Schedule IN-529 maps the 529 credit to a line-level filing flow (line 16 -> Schedule 6 line 6 for IT-40 / Schedule G line 6 for IT-40PNR).
- Recapture repayment is reported via Schedule IN-CR and listed on Schedule 4 (IT-40) or Schedule E (IT-40PNR).

### Sources (Tier 1)
- https://www.in.gov/dor/files/ib98.pdf
- https://forms.in.gov/Download.aspx?id=16907

### Confidence
- **High**

## Utah (advanced)

### What is locked
- TC-40 instructions list **code 54 my529 addback** and require addback where a my529 withdrawal was not used for qualified education expenses and did not meet an IRC 529(c) or 530(d) exception.
- The same instructions map TC-40A Part 1 totals to **TC-40 line 5** and include **code 20 my529 credit** in TC-40A Part 3 (carried to TC-40 line 24).
- Utah instructions also include ABLE program credit coding (code 63), confirming ABLE appears in the same filing architecture.

### Sources (Tier 1)
- https://tax.utah.gov/forms/current/tc-40inst.pdf
- https://tax.utah.gov/forms/current/tc-40a.pdf

### Confidence
- **Medium** (explicit addback mechanics are clear; 529->ABLE treatment relies on IRC-exception interpretation in instruction text)

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
- Utah (Medium)
- Virginia (Low)
- New York (Low)

## Priority closure queue (next)

1. **New Jersey**: NJ-1040 line-level treatment for 529->ABLE.
2. **Pennsylvania**: PA-40 line-level treatment for 529->ABLE.
3. **Minnesota**: explicit ABLE carveout confirmation vs recapture inference.
4. **Indiana**: pull exact Schedule 4 line number for recapture repayment entry.

## Interpretation notes

- Federal qualified treatment is not enough to infer state no-recapture treatment.
- Confidence labels are legal-operational confidence for product design, not individualized tax advice certainty.
