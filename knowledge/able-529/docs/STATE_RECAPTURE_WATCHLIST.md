# State Recapture Watchlist (Seed)

Updated: 2026-03-10

Purpose: evolving matrix for building a 50-state 529->ABLE recapture/add-back map.

## Phase 1 matrix snapshot (9 states)

| State | Prior deduction/credit | 529->ABLE state treatment | Recapture/add-back signal | Source(s) | Form/line status |
|---|---|---|---|---|---|
| Illinois | Yes (in-state deduction limits) | Explicitly supported (conditional, section 529A limits apply) | Explicit recapture for nonqualified/refund scenarios | https://tax.illinois.gov/forms/incometax/currentyear/individual/il-1040-schedule-m-instr.html ; https://tax.illinois.gov/content/dam/soi/en/web/tax/forms/incometax/documents/currentyear/individual/il-1040-schedule-m.pdf ; https://ilga.gov/legislation/ilcs/fulltext?DocName=001505050K16.5 | Schedule M line 9 recapture language captured |
| Ohio | Yes ($4,000 beneficiary-level deduction, carryforward) | Not explicit in located primary text | Explicit add-back for nonqualified distributions up to prior deductions | https://codes.ohio.gov/ohio-revised-code/section-5747.70 ; https://tax.ohio.gov/help-center/faqs/income-529-plan-account-deduction/income-529-plan-account-deduction ; https://tax.ohio.gov/static/ohio_individual/individual/supportingdocumentation/pages/a-3_529addition.html | Addition worksheet/form reference identified (A-3) |
| Pennsylvania | Yes (beneficiary-level deduction tied to federal annual gift exclusion) | Likely tracks federal exclusion when federally excludable | Nonqualified distributions reportable for PA PIT | https://www.pa.gov/agencies/revenue/forms-and-publications/pa-personal-income-tax-guide/deductions-and-credits.html ; https://www.pa.gov/content/dam/copapwp-pagov/en/revenue/documents/taxlawpoliciesbulletinsnotices/taxsummaries/documents/2024_tax_summary_aug.pdf ; https://revenue-pa.custhelp.com/app/answers/detail/a_id/2517/~/where-should-a-distribution-from-an-irc-section-529-college-and-career-saving | Need line-level PA-40 instruction capture |
| California | No current broad 529 deduction baseline | Ambiguous in located primary text | Nonqualified earnings additional tax framework exists | https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=RTC&sectionNum=17140.3. ; https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=RTC&sectionNum=17085. ; https://www.ftb.ca.gov/forms/2025/2025-3805p-instructions.html | Need explicit CA form handling for 529->ABLE |
| New York | Yes (state 529 deduction structure) | Ambiguous; historic NY decoupling from some federal 529 expansions is a risk signal | Recapture/add-back architecture exists via NY modifications | https://www.nysenate.gov/legislation/laws/TAX/612 ; https://www.tax.ny.gov/pdf/memos/income/m18-6i.pdf ; https://tax.ny.gov/forms/current-forms/it/it225i.htm | Need current-year modification code confirmation |
| New Jersey | Yes, limited (income and plan constraints) | Ambiguous in located primary text | Qualified distribution exclusion clear; recapture detail unresolved | https://www.nj.gov/treasury/taxation/individuals/collegededuction.shtml ; https://www.nj.gov/treasury/taxation/njgrosstax.shtml ; https://pub.njleg.state.nj.us/Bills/2020/PL21/128_.PDF | Need NJ-1040 instruction line proof for recapture |
| Oregon | Yes (state incentives and recapture framework) | Pending targeted 529->ABLE determination | Existing rule references recapture concepts | https://oregon.public.law/rules/oar_150-315-0065 | Need return line mapping |
| Colorado | Yes (state subtraction context) | Pending targeted 529->ABLE determination | DOR material indicates recapture/addition concepts | https://tax.colorado.gov/income-tax-topics-able-contribution-subtraction | Need direct rollover qualification citation |
| Virginia | Yes (in-state deduction subject to recapture triggers) | Pending state tax authority confirmation | Plan guidance warns of recapture context | https://www.virginia529.com/blog/transfer-invest529-funds-to-ablenow | Need Department of Taxation citation + line references |

## Matrix schema (still required for all states)

For each state, capture:

1. Prior-year deduction or credit allowed? (Y/N)
2. 529->ABLE treated as qualified for state tax? (Y/N/Conditional)
3. Recapture/add-back rule citation.
4. Effective tax year and conformity date.
5. Filing form or worksheet line reference.

## Immediate next expansion targets

- Complete first 12-state tranche by adding: Utah, Indiana, Minnesota.
- Upgrade NY/NJ/CA from medium/low confidence to high confidence using line-level form instructions or explicit statutory text.
