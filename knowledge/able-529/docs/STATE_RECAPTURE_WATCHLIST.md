# State Recapture Watchlist (Seed)

Updated: 2026-03-10

Purpose: staged buildout for a 50-state 529->ABLE recapture/add-back matrix.

## Current watchlist status (8 states touched)

| State | Risk Signal | Primary Source(s) | Status |
|---|---|---|---|
| Oregon | Rule text references recapture mechanics in 529/ABLE context | https://oregon.public.law/rules/oar_150-315-0065 | Verify exact taxpayer scenarios |
| Colorado | DOR guidance indicates addition/recapture concepts for 529/ABLE treatment | https://tax.colorado.gov/income-tax-topics-able-contribution-subtraction | Verify rollover-specific handling |
| Virginia | Plan guidance warns on deduction recapture context for transfers | https://www.virginia529.com/blog/transfer-invest529-funds-to-ablenow | Confirm with state tax authority text |
| New York | Plan materials discuss state recapture triggers generally | https://www.ny529advisor.com/our-plan/state-tax-benefits | Confirm direct 529->ABLE treatment with NY tax authority text |
| California | FTB instructions show 2018 nonconformity then 2019+ conformity on ABLE rollover treatment | https://www.ftb.ca.gov/forms/2018/18-3805P-instructions.html; https://www.ftb.ca.gov/forms/2019/2019-3805p-instructions.html; https://www.ftb.ca.gov/forms/2025/2025-3805p-instructions.html | High-confidence directional; extract line-level quote pack |
| New Jersey | NJ 529 deduction regime clear, but explicit published 529->ABLE recapture treatment still needs direct line confirmation | https://www.nj.gov/treasury/taxation/njgrosstax.shtml; https://nj.gov/treasury/taxation/individuals/collegededuction.shtml | Medium confidence; confirm NJ-1040 instructions line detail |
| Pennsylvania | PA deduction framework clear; explicit 529->ABLE qualified/nonqualified PIT handling still partially unclear in indexed sources | https://revenue-pa.custhelp.com/app/answers/detail/a_id/2321/; https://revenue-pa.custhelp.com/app/answers/detail/a_id/2208/; https://www.pa.gov/content/dam/copapwp-pagov/en/revenue/documents/taxtypes/pit/documents/pa_able_qa.pdf | Medium-Low; resolve via current PA-40 instructions + DOR FAQs |
| Illinois | Schedule M instructions define recapture triggers (out-of-state transfer/nonqualified withdrawal) with line-level references | https://tax.illinois.gov/forms/incometax/currentyear/individual/il-1040-schedule-m-instr.html; https://tax.illinois.gov/content/dam/soi/en/web/tax/forms/incometax/documents/currentyear/individual/il-1040-schedule-m.pdf | High on recapture mechanics; still confirm explicit in-state 529->ABLE pathway wording |

## Matrix schema to apply next runs

For each state, capture:

1. Prior-year deduction or credit allowed? (Y/N)
2. 529->ABLE treated as qualified for state tax? (Y/N/Conditional)
3. Recapture/add-back rule citation.
4. Effective tax year and conformity date.
5. Filing form or worksheet line reference.

## Immediate next expansion targets

- Ohio, Utah, Indiana, Minnesota (plus one West Coast and one Northeast state not yet sampled).

## Notes from this run

- Assumption challenged: "plan pages are enough for state treatment." Result: failed. State DOR forms/instructions materially change confidence.
- Confidence spread is now visible: CA/IL stronger than NJ/PA on direct recapture-language certainty.
