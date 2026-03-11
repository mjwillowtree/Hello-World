# STATE_MATRIX (50 States + DC)

Updated: 2026-03-11

Primary data file: `outputs/STATE_MATRIX.csv`

## Coverage snapshot

- Jurisdictions tracked: **51 / 51**
- Substantively advanced rows (beyond placeholder): **11 / 51**
- High-confidence rows: **12 / 51**
- Latest state advancements: **Utah** (new) and **New Jersey/Pennsylvania** confidence upgrades

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

## New Jersey (upgraded)

### What is locked
- NJ-1040 instructions include earnings on nonqualified distributions from both qualified tuition programs and qualified state 529A ABLE accounts in taxable interest.
- NJ-1040 instructions also include earnings on nonqualified NJBEST distributions and portions attributable to contributions previously deducted on a New Jersey return.
- NJ College Affordability deduction lines are explicitly identified (lines 37a-37c), including NJBEST contribution deductions on line 37a.

### Sources (Tier 1)
- https://www.njportal.com/Taxation/NJ1040/Content/Docs/Instructions/Current_NJ1040Instructions.pdf
- https://nj.gov/treasury/taxation/individuals/collegededuction.shtml

### Confidence
- **High**

## Pennsylvania (upgraded)

### What is locked
- PA-40 instructions treat federally exempt IRC 529 distribution rollovers as excluded from taxable income.
- PA-40 instructions route non-educational IRC 529 distributions to PA Schedule A line 13 (taxable amount mechanics included).
- PA Schedule O remains the deduction schedule for IRC 529 and 529A contribution deductions (feeding PA-40 line 10).

### Sources (Tier 1)
- https://www.pa.gov/content/dam/copapwp-pagov/en/revenue/documents/formsandpublications/formsforindividuals/pit/documents/2024/2024_pa-40in.pdf

### Confidence
- **Medium-High** (rollover exclusion is clear; filing-year reconfirmation still needed for 2025/2026 packets)

## Utah (newly advanced)

### What is locked
- Utah TC-40A Part 1 code 54 requires my529 addback where withdrawal is not for qualified education expenses and does not meet an IRC 529(c)/530(d) exception.
- TC-40A Part 1 totals carry to TC-40 line 5, creating return-level recapture/addback flow.
- Utah also has a separate ABLE contribution credit framework (TC-40A Part 4 code 63), useful for product eligibility/tax-benefit messaging.

### Sources (Tier 1)
- https://incometax.utah.gov/additions/my529-addback
- https://tax.utah.gov/forms/current/tc-40inst.pdf

### Confidence
- **Medium** (explicit 529->ABLE carveout text still not found in the extracted lines)

## Previously advanced states (carry-forward)

- California (High)
- Illinois (High)
- New Jersey (High)
- Pennsylvania (Medium-High)
- Oregon (Low)
- Colorado (Low)
- Virginia (Low)
- New York (Low)

## Priority closure queue (next)

1. **Indiana**: first-pass Tier-1 row with code/line references.
2. **Minnesota**: explicit ABLE carveout confirmation (if any) versus recapture-framework inference.
3. **Pennsylvania**: verify TY2025/TY2026 instruction packets preserve current rollover/non-educational line treatment.
4. **Utah**: verify explicit 529->ABLE treatment language (currently inferred via IRC exception reference).

## Interpretation notes

- Federal qualified treatment is not enough to infer state no-recapture treatment.
- Confidence labels are legal-operational confidence for product design, not individualized tax advice certainty.
