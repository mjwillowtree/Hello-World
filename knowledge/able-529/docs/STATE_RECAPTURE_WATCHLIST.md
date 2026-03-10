# State Recapture Watchlist (Seed)

Updated: 2026-03-10

Purpose: build a 50-state 529->ABLE recapture/add-back matrix with state-tax authority citations.

## Matrix snapshot (working rows)

| State | 529 deduction/credit | 529->ABLE treatment snapshot | Key authority | Confidence | Open issue |
|---|---|---|---|---|---|
| California | No state income tax deduction for 529 contributions (per ScholarShare FAQ) | CA generally conforms to ABLE treatment; FTB instructions note TCJA rule allowing 529->ABLE rollover without penalty and separately impose 2.5% additional tax on nonqualified 529 earnings distributions. | https://www.scholarshare529.com/resources/faq/ ; https://www.ftb.ca.gov/forms/2025/2025-3805p-instructions.html ; https://calable.ca.gov/faqs/can-i-roll-over-a-529-college-savings-plan-account-into-my-calable-account | Medium | Confirm CA FTB line-level treatment on resident return instructions for every 529->ABLE path variant. |
| New York | Deduction available (NY 529 program) | NY IT-225I explicitly treats rollover to a qualified ABLE program as qualified (not nonqualified) for A-103 logic. | https://www.nysaves.org/home/why-ny-529-direct-plan/tax-benefits.html ; https://www.tax.ny.gov/forms/current-forms/it/it225i.htm | High | Validate treatment symmetry for all NY 529 plan variants and any non-NY plan edge cases. |
| Illinois | Deduction/subtraction available via Schedule M | Schedule M instructions define recapture for out-of-state plan transfers and nonqualified withdrawals/refunds; this implies in-scope qualified 529->ABLE treatment is not a recapture event when it does not fit those recapture categories. | https://tax.illinois.gov/forms/incometax/currentyear/individual/il-1040-schedule-m-instr.html | Medium-High | Confirm explicit IL DOR statement naming 529->ABLE as qualified/no-recapture. |
| Pennsylvania | Deduction available for IRC 529 and PA ABLE contributions | No definitive rollover-specific recapture rule confirmed in this run from PA DOR guidance reviewed. | https://www.pa.gov/agencies/revenue/forms-and-publications/pa-personal-income-tax-guide/deductions-and-credits ; https://www.paable.gov/benefits/ | Low-Medium | Find PA statute/regulation/instructions explicitly addressing 529->ABLE rollover recapture/add-back treatment. |
| Oregon | Recapture mechanics exist in OR rule framework | Prior seed shows potential 529/ABLE recapture interaction risk. | https://oregon.public.law/rules/oar_150-315-0065 | Medium | Pin exact taxpayer scenarios and form-line mechanics. |
| Colorado | DOR guidance indicates ABLE subtraction topics with possible recapture/add-back implications | Rollover-specific treatment still needs direct confirmation. | https://tax.colorado.gov/income-tax-topics-able-contribution-subtraction | Medium | Confirm 529->ABLE rollover handling in CO forms/instructions. |
| Virginia | Plan guidance warns about recapture context | Need direct VA tax authority text for definitive state treatment. | https://www.virginia529.com/blog/transfer-invest529-funds-to-ablenow | Low-Medium | Replace plan guidance with controlling VA tax authority. |

## Matrix schema to apply next runs

For each state, capture:

1. Prior-year deduction or credit allowed? (Y/N)
2. 529->ABLE treated as qualified for state tax? (Y/N/Conditional)
3. Recapture/add-back rule citation.
4. Effective tax year and conformity date.
5. Filing form or worksheet line reference.

## Immediate next expansion targets

- New Jersey, Ohio, Utah, Indiana, Minnesota, Oregon (line-level confirmation), Colorado (line-level confirmation), Virginia (tax-authority replacement).
