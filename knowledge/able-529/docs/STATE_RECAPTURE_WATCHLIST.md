# State Recapture Watchlist (Seed)

Updated: 2026-03-10

Purpose: staged build toward a 50-state 529->ABLE recapture/add-back matrix.

## Phase 1 matrix (priority states)

| State | Deduction/Credit | 529->ABLE signal from state authority | Filing mechanism signal | Confidence | Primary sources |
|---|---|---|---|---|---|
| California | No current 529 contribution deduction regime | No explicit FTB statement located for 529->ABLE; no deduction recapture structure currently expected | N/A for deduction recapture; still monitor nonconformity areas | Medium | https://www.ftb.ca.gov/tax-pros/law/legislation/2025-2026/SB529-022025.pdf |
| New York | Yes | NY decouples from some federal 529 expansions; recapture risk framework exists, but explicit current 529->ABLE form coding still needs pinning | IT-201/IT-225 modification pathway likely, code confirmation pending | Medium | https://www.tax.ny.gov/pdf/memos/income/m18-6i.pdf ; https://www.tax.ny.gov/forms/current-forms/it/it225i.htm |
| New Jersey | Yes (income-limited program deduction context) | Qualified-distribution exclusion structure likely controls; explicit 529->ABLE line-level instruction still unresolved | NJ-1040 instruction-level line confirmation pending | Medium-Low | https://www.nj.gov/treasury/taxation/njgrosstax.shtml ; https://www.nj.gov/treasury/taxation/individuals/collegededuction.shtml |
| Pennsylvania | Yes | PA indicates federally excludable IRC §529 distributions are excluded for PA PIT (TY 2024+) | Nonqualified reporting appears on PA-40 Schedule A line 13 | High | https://www.pa.gov/content/dam/copapwp-pagov/en/revenue/documents/taxlawpoliciesbulletinsnotices/taxsummaries/documents/2024_tax_summary_aug.pdf ; https://www.pa.gov/content/dam/copapwp-pagov/en/revenue/documents/formsandpublications/formsforindividuals/pit/documents/2024/2024_pa-40a.pdf |
| Illinois | Yes | No explicit IL statement found for 529->ABLE characterization, but recapture/add-back mechanics are clear | IL-1040 Schedule M recapture lines 7 and 9 | High (mechanics) / Medium (rollover characterization) | https://tax.illinois.gov/forms/incometax/currentyear/individual/il-1040-schedule-m-instr.html |
| Ohio | Yes | No explicit OH statement found for 529->ABLE characterization; nonqualified addition mechanics are explicit | A-3 (addition), A-31 (529 deduction), A-18 (STABLE deduction) | Medium | https://tax.ohio.gov/faq-529 ; https://tax.ohio.gov/static/ohio_individual/individual/supportingdocumentation/pages/a-3_529addition.html |
| Oregon | Yes | Oregon rule text references recapture mechanics in 529/ABLE context | Rule-level recapture language; form-line mapping pending | Medium | https://oregon.public.law/rules/oar_150-315-0065 |
| Colorado | Yes | DOR guidance indicates addition/recapture concepts for 529/ABLE treatment | Form-line mapping pending | Medium | https://tax.colorado.gov/income-tax-topics-able-contribution-subtraction |
| Virginia | Yes | Program guidance warns of recapture context for transfers; DOR-level confirmation still needed | Form-line mapping pending | Medium-Low | https://www.virginia529.com/blog/transfer-invest529-funds-to-ablenow |

## Matrix schema (still required before "done")

For each state, capture:

1. Prior-year deduction or credit allowed? (Y/N)
2. 529->ABLE treated as qualified for state tax? (Y/N/Conditional)
3. Recapture/add-back rule citation.
4. Effective tax year and conformity date.
5. Filing form or worksheet line reference.

## Immediate next expansion targets

- Pin exact line/code references for NY and NJ from current-year forms/instructions.
- Add Utah, Indiana, Minnesota with primary tax authority + form lines.
- Validate VA signals against Virginia Department of Taxation primary text.
