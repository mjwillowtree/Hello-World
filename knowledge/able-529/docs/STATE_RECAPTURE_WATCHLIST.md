# State Recapture Watchlist (Seed)

Updated: 2026-03-09

Purpose: starter list for building a 50-state 529->ABLE recapture/add-back matrix.

## States flagged in this run

| State | Risk Signal | Primary Source | Status |
|---|---|---|---|
| Oregon | Rule text references recapture mechanics in 529/ABLE context | https://oregon.public.law/rules/oar_150-315-0065 | Verify exact taxpayer scenarios |
| Colorado | DOR guidance indicates addition/recapture concepts for 529/ABLE treatment | https://tax.colorado.gov/income-tax-topics-able-contribution-subtraction | Verify rollover-specific handling |
| Virginia | Plan guidance warns on deduction recapture context for transfers | https://www.virginia529.com/blog/transfer-invest529-funds-to-ablenow | Confirm with state tax authority text |
| New York | Plan materials discuss state recapture triggers generally | https://www.ny529advisor.com/our-plan/state-tax-benefits | Confirm direct 529->ABLE treatment |
| California | FTB instructions frame additional tax on nonqualified treatment; CalABLE materials indicate rollover pathway but tax treatment needs explicit FTB statement | https://www.ftb.ca.gov/forms/2025/2025-3805p-instructions.html | **Open**: confirm whether federally qualified 529->ABLE is CA-qualified |
| New Jersey | NJ tax pages document deduction/nonqualified treatment; no clean Tier 1 statement found yet for 529->ABLE classification | https://nj.gov/treasury/taxation/individuals/collegededuction.shtml | **Open**: locate direct NJ authority for rollover treatment |
| Pennsylvania | PA official guidance indicates PIT exclusion for federally excludable 529 distributions; still need explicit 529->ABLE citation | https://revenue-pa.custhelp.com/app/answers/detail/a_id/3722/~/does-pa-impose-personal-income-tax-on-qualified-tuition-program-%28529-plan%29 | **Tentative favorable**, awaiting explicit ABLE crossover text |
| Ohio | ORC and DOR materials show add-back structure on nonqualified distributions; explicit 529->ABLE carveout not yet pinned | https://codes.ohio.gov/ohio-revised-code/section-5747.70 | **Likely recapture risk unless carveout found** |

## Matrix schema to apply next runs

For each state, capture:

1. Prior-year deduction or credit allowed? (Y/N)
2. 529->ABLE treated as qualified for state tax? (Y/N/Conditional)
3. Recapture/add-back rule citation.
4. Effective tax year and conformity date.
5. Filing form or worksheet line reference.

## Immediate next expansion targets

- Illinois, Utah, Indiana, Minnesota, plus explicit form-line extraction for CA/NJ/PA/OH.
