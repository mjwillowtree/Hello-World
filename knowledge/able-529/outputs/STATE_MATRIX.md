# STATE_MATRIX (50 States + DC)

Updated: 2026-03-11

Primary data file: `outputs/STATE_MATRIX.csv`

## Coverage snapshot

- Jurisdictions tracked: **51 / 51**
- Substantively advanced rows (beyond placeholder): **11 / 51**
- High-confidence rows: **11 / 51**
- Latest state advancements: **Indiana** (new) and **New Jersey** (line-mapped)

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

## Indiana (advanced this run)

### What is locked
- TY2025 Schedule IN-CR provides line-level recapture flow: line 9 carries to Form IT-40 Schedule 4 line 3 (or IT-40PNR Schedule E line 3).
- IN-CR code mapping explicitly identifies Indiana529 credit recapture (code 837) and ABLE 529A credit recapture (code 872).
- Indiana IT-40 booklet confirms line-3 recapture workflow and directs filers to IN-CR for offset-credit recapture.

### Sources (Tier 1)
- https://forms.in.gov/Download.aspx?id=16957
- https://forms.in.gov/Download.aspx?id=16938
- https://forms.in.gov/Download.aspx?id=16915
- https://secure.in.gov/dor/tax-forms/individual/current/
- https://www.in.gov/dor/files/ib98.pdf

### Confidence
- **Medium-High** (line mapping is clear, but IN-CR wording and Jan-2026 Bulletin #98 should be versioned together for 2024+ Indiana529->Indiana ABLE carveout interpretation)

## New Jersey (line-level mapping upgraded)

### What is locked
- TY2025 NJ-1040 instructions include taxable treatment for earnings on nonqualified distributions from qualified tuition accounts and state 529A ABLE accounts.
- NJ-1040 instructions also identify nonqualified NJBEST earnings and distribution portions attributable to previously deducted NJ contributions as taxable.
- Qualified distributions from qualified tuition/state 529A ABLE accounts and qualified NJBEST distributions are listed as exempt.

### Sources (Tier 1)
- https://www.nj.gov/treasury/taxation/pdf/current/1040i.pdf
- https://www.nj.gov/treasury/taxation/njgrosstax.shtml
- https://nj.gov/treasury/taxation/individuals/collegededuction.shtml

### Confidence
- **Medium-High** (line treatment is now explicit; NJ instructions still do not use a specific "529->ABLE rollover" phrase)

## Previously advanced states (carry-forward)

- California (High)
- Illinois (High)
- New Jersey (Medium-High; line-level mapped)
- Pennsylvania (Medium-Low; line-level closure pending)
- Oregon (Low)
- Colorado (Low)
- Virginia (Low)
- New York (Low)

## Priority closure queue (next)

1. **Pennsylvania**: PA-40 line-level treatment for 529->ABLE.
2. **Utah**: first-pass Tier-1 row with code/line references.
3. **Indiana**: resolve IN-CR vs Bulletin #98 wording conflict into tax-year-safe product rule.
4. **Minnesota**: close explicit ABLE carveout vs inference gap.

## Interpretation notes

- Federal qualified treatment is not enough to infer state no-recapture treatment.
- Confidence labels are legal-operational confidence for product design, not individualized tax advice certainty.
