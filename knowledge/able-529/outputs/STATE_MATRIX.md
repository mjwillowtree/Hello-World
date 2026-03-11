# STATE_MATRIX (50 States + DC)

Updated: 2026-03-11

Primary data file: `outputs/STATE_MATRIX.csv`

## Coverage snapshot

- Jurisdictions tracked: **51 / 51**
- Substantively advanced rows (beyond placeholder): **10 / 51**
- High-confidence rows: **11 / 51**
- Latest state advancements: **Ohio (TY2025 reconfirmation)** and **Pennsylvania (line mapping partial closure)**

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
- TY2025 Schedule of Adjustments line mapping includes line 4 (nonqualified 529 addition), line 20 (STABLE deduction), and line 37 (529 deduction).
- TY2025 booklet instruction text still ties line-4 addition to specific nonqualified scenarios and prior Ohio deduction history.

### Sources (Tier 1)
- https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2025/scheduleofadjustments.pdf
- https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2025/it1040-booklet.pdf

### Confidence
- **High**

## Pennsylvania (advanced this run, partial closure)

### What is locked
- PA DOR states nonqualified IRC 529 distributions are taxable and reportable as interest income on **PA Schedule A** and **PA-40 line 2**.
- PA DOR references **PA-40 O** and **PA-40IN** for deduction workflow administration.

### What remains open
- Explicit line-level treatment for federally qualified **529->ABLE** rollovers in current PA-40 instruction text is still not fully locked.

### Sources (Tier 1)
- https://revenue-pa.custhelp.com/app/answers/detail/a_id/2517/
- https://revenue-pa.custhelp.com/app/answers/detail/a_id/3400/
- https://revenue-pa.custhelp.com/app/answers/detail/a_id/2321/

### Confidence
- **Medium**

## Previously advanced states (carry-forward)

- California (High)
- Illinois (High)
- New Jersey (Medium; line-level closure pending)
- Pennsylvania (Medium; qualified 529->ABLE line-level closure pending)
- Oregon (Low)
- Colorado (Low)
- Virginia (Low)
- New York (Low)

## Priority closure queue (next)

1. **New Jersey**: NJ-1040 line-level treatment for 529->ABLE.
2. **Pennsylvania**: explicit PA-40IN/PA-40 line treatment for federally qualified 529->ABLE rollover.
3. **Utah**: first-pass Tier-1 row with code/line references.
4. **Indiana**: first-pass Tier-1 row with code/line references.

## Interpretation notes

- Federal qualified treatment is not enough to infer state no-recapture treatment.
- Confidence labels are legal-operational confidence for product design, not individualized tax advice certainty.
