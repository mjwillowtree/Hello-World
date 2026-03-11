# State Recapture Matrix (Phase 1 Working Draft)

Updated: 2026-03-11

Purpose: convert watchlist signals into a decision-usable matrix with confidence labels and direct source handles.

| State | Prior 529 deduction/credit? | 529->ABLE state treatment | Recapture/add-back signal | Tax year/conformity note | Form line reference | Confidence | Primary authority |
|---|---|---|---|---|---|---|---|
| California | No deduction/credit | Qualified treatment appears aligned for 2019+; 2018 instructions reflected nonconformity | Additional tax framework in FTB 3805P for nonqualified events | Conformity shift visible from 2018 to 2019+ instructions | FTB 3805P Part II (including additional-tax lines) | High | https://www.ftb.ca.gov/forms/2018/18-3805P-instructions.html ; https://www.ftb.ca.gov/forms/2019/2019-3805p-instructions.html ; https://www.ftb.ca.gov/forms/2025/2025-3805p-instructions.html |
| Illinois | Yes (state subtraction framework) | Conditional; treatment depends on whether transfer triggers statutory recapture conditions | Explicit recapture for out-of-state transfer/nonqualified or refunded use | Annual Schedule M instructions govern return-year reporting | Schedule M line 7 / line 9 recapture references | High | https://tax.illinois.gov/forms/incometax/currentyear/individual/il-1040-schedule-m-instr.html ; https://tax.illinois.gov/content/dam/soi/en/web/tax/forms/incometax/documents/currentyear/individual/il-1040-schedule-m.pdf |
| New Jersey | Yes (income-limited deduction) | Qualified distributions from qualified tuition and qualified state 529A ABLE accounts listed as exempt; nonqualified earnings taxable | NJ-1040 instructions include taxable-interest treatment for nonqualified earnings + previously deducted contribution portions | TY2025 instruction-level treatment confirmed | NJ-1040 line 16a context + exempt-income examples | High | https://www.njportal.com/Taxation/NJ1040/Content/Docs/Instructions/Current_NJ1040Instructions.pdf ; https://www.nj.gov/treasury/taxation/individuals/collegededuction.shtml |
| Pennsylvania | Yes | Unclear in currently indexed snippets; PA ABLE guidance confirms rollover mechanics but not full PIT recapture consequence | Potentially qualified if federally qualified, but not yet locked with line-level PIT instruction quote | Needs current PA-40 instruction extraction | PA-40 schedule line mapping pending verification | Medium-Low | https://revenue-pa.custhelp.com/app/answers/detail/a_id/2321/ ; https://revenue-pa.custhelp.com/app/answers/detail/a_id/2208/ ; https://www.pa.gov/content/dam/copapwp-pagov/en/revenue/documents/taxtypes/pit/documents/pa_able_qa.pdf |
| Oregon | Unknown (not yet fully mapped in matrix schema) | Watchlist only | Recapture mechanics referenced in rule text | To be verified | Pending | Low | https://oregon.public.law/rules/oar_150-315-0065 |
| Colorado | Unknown (not yet fully mapped in matrix schema) | Watchlist only | Addition/recapture concepts indicated by DOR guidance | To be verified | Pending | Low | https://tax.colorado.gov/income-tax-topics-able-contribution-subtraction |
| Virginia | Unknown (not yet fully mapped in matrix schema) | Watchlist only | Recapture warning seen in plan guidance; needs state tax authority citation | To be verified | Pending | Low | https://www.virginia529.com/blog/transfer-invest529-funds-to-ablenow |
| New York | Yes (general 529 deduction context) | Watchlist only | Recapture trigger language needs direct tax authority confirmation for 529->ABLE path | To be verified | Pending | Low | https://www.ny529advisor.com/our-plan/state-tax-benefits |
| Utah | Yes (my529 credit/addback framework) | Conditional; relies on IRC 529(c)/530(d) exception handling in addback instruction | TC-40A code 54 my529 addback for nonqualified withdrawals, carrying to TC-40 line 5 | TY2025 instruction-level mapping confirmed; ABLE carveout text still open | TC-40A Part 1 code 54; TC-40 line 5 | Medium-High | https://tax.utah.gov/forms/current/tc-40inst.pdf ; https://tax.utah.gov/forms/current/tc-40a.pdf |

## Priority closure targets (next run)

1. Pennsylvania: PA-40 instruction quote for rollover treatment and recapture implications.
2. Indiana: add first-pass row with at least one Tier 1 source and line references.
3. Utah/Minnesota: close explicit ABLE carveout uncertainty.
