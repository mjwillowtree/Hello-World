# State Recapture Watchlist (Seed)

Updated: 2026-03-10

Purpose: starter list for building a 50-state 529->ABLE recapture/add-back matrix.

## States flagged in this run (expanded Phase 1)

| State | Prior 529 deduction/credit | 529->ABLE treatment signal | Recapture/add-back risk | Primary source(s) | Confidence |
|---|---|---|---|---|---:|
| Oregon | Yes | Previously flagged as recapture-sensitive | Conditional | https://oregon.public.law/rules/oar_150-315-0065 | 2 |
| Colorado | Yes | Previously flagged as recapture-sensitive | Conditional | https://tax.colorado.gov/income-tax-topics-able-contribution-subtraction | 2 |
| Virginia | Yes | Plan-level warning exists | Conditional | https://www.virginia529.com/blog/transfer-invest529-funds-to-ablenow | 1 |
| New York | Yes | Plan materials discuss recapture triggers generally | Conditional | https://www.ny529advisor.com/our-plan/state-tax-benefits | 1 |
| California | No state 529 deduction baseline | Appears qualified in current conformity framework; year-specific validation still required | Low recapture (no deduction to recapture), but qualification characterization still matters | https://www.ftb.ca.gov/forms/2025/2025-3805p-instructions.html ; https://leginfo.legislature.ca.gov/faces/codes_displayText.xhtml?article=3.&chapter=3.&division=2.&lawCode=RTC&part=10.&title= | 3 |
| New Jersey | Yes (income-limited) | Appears qualified if rollover remains within qualified pathways | Conditional (nonqualified treatment can pull back prior benefit) | https://www.nj.gov/treasury/taxation/individuals/collegededuction.shtml ; https://pub.njleg.state.nj.us/Bills/2020/PL21/128_.PDF | 4 |
| Pennsylvania | Yes | Unclear-to-likely-qualified, but needs direct current DOR text extraction | Conditional/unclear | https://www.revenue.pa.gov/FormsandPublications/PAPersonalIncomeTaxGuide/Pages/Deductions-and-Credits.aspx ; https://revenue-pa.custhelp.com/app/answers/detail/a_id/2208 | 2 |
| Illinois | Yes | Explicit recapture triggers are clear; direct 529->ABLE classification less explicit | Conditional (material) | https://tax.illinois.gov/forms/incometax/currentyear/individual/il-1040-schedule-m-instr.html ; https://www.ilga.gov/legislation/ilcs/documents/003500050K203.htm | 4 |
| Ohio | Yes | No clear explicit carve-out located for 529->ABLE in recapture exception list | Conditional (potentially material) | https://codes.ohio.gov/ohio-revised-code/section-5747.70 ; https://tax.ohio.gov/faq-529 | 3 |

## Matrix schema to apply next runs

For each state, capture:

1. Prior-year deduction or credit allowed? (Y/N)
2. 529->ABLE treated as qualified for state tax? (Y/N/Conditional)
3. Recapture/add-back rule citation.
4. Effective tax year and conformity date.
5. Filing form or worksheet line reference.

## Immediate next expansion targets

- Utah, Indiana, Minnesota, New Jersey (line-level cites), Pennsylvania (line-level cites), Ohio (administrative clarification).

## Critical caveat

Current table entries are risk-screening signals, not final filing conclusions.  
Before taxpayer advice, elevate each state to line-cited statute/regulation + current form-instruction level.
