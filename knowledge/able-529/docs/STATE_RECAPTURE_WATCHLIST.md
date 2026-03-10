# State Recapture Watchlist (Seed)

Updated: 2026-03-10

Purpose: starter list for building a 50-state 529->ABLE recapture/add-back matrix.

## States flagged in this run

| State | Risk Signal | Primary Source | Status |
|---|---|---|---|
| Oregon | Rule text references recapture mechanics in 529/ABLE context | https://oregon.public.law/rules/oar_150-315-0065 | Verify exact taxpayer scenarios |
| Colorado | DOR guidance indicates addition/recapture concepts for 529/ABLE treatment | https://tax.colorado.gov/income-tax-topics-able-contribution-subtraction | Verify rollover-specific handling |
| Virginia | Plan guidance warns on deduction recapture context for transfers | https://www.virginia529.com/blog/transfer-invest529-funds-to-ablenow | Confirm with state tax authority text |
| New York | IT-201-I line 22 explicitly treats rollover to qualified ABLE program as qualified (not nonqualified) | https://www.tax.ny.gov/pdf/current_forms/it/it201i.pdf | High confidence for NY resident return mechanics |

## Matrix schema to apply next runs

For each state, capture:

1. Prior-year deduction or credit allowed? (Y/N)
2. 529->ABLE treated as qualified for state tax? (Y/N/Conditional)
3. Recapture/add-back rule citation.
4. Effective tax year and conformity date.
5. Filing form or worksheet line reference.

## New York evidence snapshot (resolved in this run)

- IT-201-I (2025), line 22 instruction:
  - "A withdrawal from a New York 529 college savings program is considered nonqualified unless it is used ... to make a rollover of some or all its assets, either contributions or earnings, to a qualified Achieving a Better Life Experience (ABLE) program."
- IT-201 line mapping:
  - "Line 22: New York's 529 college savings program distributions"
  - Line 22 worksheet computes current-year addition for nonqualified withdrawals.
- Sources:
  - https://www.tax.ny.gov/pdf/current_forms/it/it201i.pdf
  - https://www.tax.ny.gov/pdf/current_forms/it/it201_fill_in.pdf

## Immediate next expansion targets

- California, New Jersey, Pennsylvania, Illinois, Ohio, Utah, Indiana, Minnesota.
