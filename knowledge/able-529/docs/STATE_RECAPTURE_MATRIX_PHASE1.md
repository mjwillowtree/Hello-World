# State Recapture Matrix (Phase 1 Working Draft)

Updated: 2026-03-10

Purpose: convert watchlist signals into a decision-usable matrix with confidence labels and direct source handles.

| State | Prior 529 deduction/credit? | 529->ABLE state treatment | Recapture/add-back signal | Tax year/conformity note | Form line reference | Confidence | Primary authority |
|---|---|---|---|---|---|---|---|
| California | No deduction/credit | Qualified treatment appears aligned for 2019+; 2018 instructions reflected nonconformity | Additional tax framework in FTB 3805P for nonqualified events | Conformity shift visible from 2018 to 2019+ instructions | FTB 3805P Part II (including additional-tax lines) | High | https://www.ftb.ca.gov/forms/2018/18-3805P-instructions.html ; https://www.ftb.ca.gov/forms/2019/2019-3805p-instructions.html ; https://www.ftb.ca.gov/forms/2025/2025-3805p-instructions.html |
| Illinois | Yes (state subtraction framework) | Conditional; treatment depends on whether transfer triggers statutory recapture conditions | Explicit recapture for out-of-state transfer/nonqualified or refunded use | Annual Schedule M instructions govern return-year reporting | Schedule M line 7 / line 9 recapture references | High | https://tax.illinois.gov/forms/incometax/currentyear/individual/il-1040-schedule-m-instr.html ; https://tax.illinois.gov/content/dam/soi/en/web/tax/forms/incometax/documents/currentyear/individual/il-1040-schedule-m.pdf |
| New Jersey | Yes (income-limited deduction) | Likely qualified if tied to IRC-qualified treatment; direct explicit 529->ABLE line still needs confirmation | No definitive recapture line identified yet for this path | Deduction appears TY 2022+; confirm current-year instruction detail | NJ-1040 line-level mapping pending verification | Medium | https://www.nj.gov/treasury/taxation/njgrosstax.shtml ; https://nj.gov/treasury/taxation/individuals/collegededuction.shtml |
| Pennsylvania | Yes | Unclear in currently indexed snippets; PA ABLE guidance confirms rollover mechanics but not full PIT recapture consequence | Potentially qualified if federally qualified, but not yet locked with line-level PIT instruction quote | Needs current PA-40 instruction extraction | PA-40 schedule line mapping pending verification | Medium-Low | https://revenue-pa.custhelp.com/app/answers/detail/a_id/2321/ ; https://revenue-pa.custhelp.com/app/answers/detail/a_id/2208/ ; https://www.pa.gov/content/dam/copapwp-pagov/en/revenue/documents/taxtypes/pit/documents/pa_able_qa.pdf |
| Oregon | Unknown (not yet fully mapped in matrix schema) | Watchlist only | Recapture mechanics referenced in rule text | To be verified | Pending | Low | https://oregon.public.law/rules/oar_150-315-0065 |
| Colorado | Unknown (not yet fully mapped in matrix schema) | Watchlist only | Addition/recapture concepts indicated by DOR guidance | To be verified | Pending | Low | https://tax.colorado.gov/income-tax-topics-able-contribution-subtraction |
| Virginia | Unknown (not yet fully mapped in matrix schema) | Watchlist only | Recapture warning seen in plan guidance; needs state tax authority citation | To be verified | Pending | Low | https://www.virginia529.com/blog/transfer-invest529-funds-to-ablenow |
| New York | Yes (general 529 deduction context) | Watchlist only | Recapture trigger language needs direct tax authority confirmation for 529->ABLE path | To be verified | Pending | Low | https://www.ny529advisor.com/our-plan/state-tax-benefits |

## Priority closure targets (next run)

1. New Jersey: current NJ-1040 instruction quote for 529->ABLE qualified/nonqualified handling.
2. Pennsylvania: PA-40 instruction quote for rollover treatment and recapture implications.
3. Ohio/Utah/Indiana/Minnesota: add first-pass rows with at least one Tier 1 source each.
