# STATE_MATRIX (50 States + DC)

Updated: 2026-03-10

Primary data file: `outputs/STATE_MATRIX.csv`

## Coverage snapshot

- Jurisdictions tracked: **51 / 51**
- Substantively advanced rows (beyond placeholder): **12 / 51**
- High-confidence rows: **12 / 51**
- Latest state advancements: **Indiana** and **Utah**

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
- Indiana Schedule IN-CR instructions explicitly define a non-qualified withdrawal to include a rollover/transfer from CollegeChoice 529 to another Code Sec. 529 plan or an ABLE account.
- Recapture workflow is line-linked: total recapture amount on Schedule IN-CR line 9 carries to IT-40 Schedule 4 line 3 (or IT-40PNR Schedule E line 3).

### Sources (Tier 1)
- https://forms.in.gov/Download.aspx?id=15824

### Confidence
- **High**

## Utah (advanced)

### What is locked
- Utah TC-40A instructions specify code 54 (my529 addback) for withdrawals not used for qualified education expenses and not meeting IRC 529(c)/530(d) exceptions.
- Part 1 additions are carried to TC-40 line 5, giving a clear filing-path control point for addback handling.

### Sources (Tier 1)
- https://incometax.utah.gov/additions/my529-addback
- https://files.tax.utah.gov/tax/forms/current/tc-40a.pdf

### Confidence
- **Medium-High** (explicit addback mechanics are clear; ABLE-specific carveout is inferred through IRC-exception cross-reference rather than named directly)

## Previously advanced states (carry-forward)

- California (High)
- Illinois (High)
- New Jersey (Medium; line-level closure pending)
- Pennsylvania (Medium-Low; line-level closure pending)
- Oregon (Low)
- Colorado (Low)
- Virginia (Low)
- New York (Low)
- Indiana (High)
- Utah (Medium-High)

## Priority closure queue (next)

1. **New Jersey**: NJ-1040 line-level treatment for 529->ABLE.
2. **Pennsylvania**: PA-40 line-level treatment for 529->ABLE.
3. **Minnesota**: explicit ABLE carveout confirmation vs current recapture inference.
4. **Illinois**: explicit in-state 529->ABLE anti-recapture text vs inferred treatment.

## Interpretation notes

- Federal qualified treatment is not enough to infer state no-recapture treatment.
- Confidence labels are legal-operational confidence for product design, not individualized tax advice certainty.
