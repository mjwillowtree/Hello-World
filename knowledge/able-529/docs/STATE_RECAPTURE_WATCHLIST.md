# State Recapture Watchlist (Seed -> Evidence Matrix)

Updated: 2026-03-10

Purpose: build a 50-state 529->ABLE recapture/add-back matrix with evidence tiering and line-item reporting references.

## Current state matrix snapshot

| State | Treatment signal for 529->ABLE | Best source | Evidence tier | Confidence | Form/line notes | Remaining gap |
|---|---|---|---|---|---|---|
| New York | Explicitly treated as not nonqualified in A-103 framework: nonqualified withdrawal list excludes rollovers to ABLE by listing ABLE rollover as a qualified use in the exception list. | https://www.tax.ny.gov/forms/current-forms/it/it225i.htm | Tier 1 | High | IT-225-I, A-103 discussion; addition modification generally flows to IT-201/IT-203 lines as instructed by form year. | Pin exact 2026 return line crosswalk for resident vs part-year with screenshot-level citations. |
| Illinois | Strong recapture architecture: transfer to out-of-state plan and nonqualified withdrawals trigger add-backs. | https://tax.illinois.gov/content/dam/soi/en/web/tax/forms/incometax/documents/currentyear/individual/il-1040-schedule-m.pdf | Tier 1 | High | Schedule M line 7 (out-of-state transfer recapture), line 9 (nonqualified/refund recapture). | Obtain explicit IL DOR statement on IL 529 -> IL ABLE in-state treatment (currently inferred from line structure). |
| New Jersey | Nonqualified NJBEST distributions taxable after prior deduction, but no explicit 529->ABLE treatment found in state authority text collected. | https://www.nj.gov/njbonds/treasury/taxation/new2022.shtml | Tier 1 (proxy) | Medium-Low | NJ 2022 changes page states nonqualified distribution taxability after deductions. | Locate NJ statute/instruction text explicitly classifying 529->ABLE and identifying current NJ-1040 line behavior. |
| Pennsylvania | PA ABLE contributions deductible; rollovers are not deductible contributions (for ABLE deduction claim). No explicit PA recapture language found yet for 529->ABLE. | https://revenue-pa.custhelp.com/app/answers/detail/a_id/3400/~/what-are-the-tax-benefits-or-consequences-of-contributing-to-a-pennsylvania | Tier 1 | Medium | PA DOR answer (updated 2025-12-19) references PA Schedule O deduction mechanics. | Need PA PIT authority that directly states whether 529->ABLE causes add-back/recapture or remains neutral. |
| Ohio | Recapture/addition framework known, but direct state page access for cited A-3 support doc returned 403 during this run. | https://tax.ohio.gov/static/ohio_individual/individual/supportingdocumentation/pages/a-3_529addition.html | Tier 1 (blocked access) | Low | Unable to verify line-level content from source in this environment. | Retrieve equivalent accessible Ohio instructions PDF/page confirming 529->ABLE classification and line/code. |
| Oregon | Rule text references recapture mechanics in 529/ABLE context. | https://oregon.public.law/rules/oar_150-315-0065 | Tier 1 | Medium | Rule-level signal retained from prior run. | Add return-line reporting references and tax-year applicability. |
| Colorado | DOR guidance indicates addition/recapture concepts for 529/ABLE treatment. | https://tax.colorado.gov/income-tax-topics-able-contribution-subtraction | Tier 1 | Medium | Guidance-level state source retained from prior run. | Verify rollover-specific handling and line-item reporting. |
| Virginia | Plan guidance warns on deduction recapture context for transfers. | https://www.virginia529.com/blog/transfer-invest529-funds-to-ablenow | Tier 2 | Medium-Low | Plan-level warning only. | Replace with Virginia Tax authority text and form-line references. |

## Matrix schema to enforce each run

For each state, capture:
1. Prior-year deduction or credit allowed? (Y/N)
2. 529->ABLE treated as qualified for state tax? (Y/N/Conditional/Silent)
3. Recapture/add-back citation (Tier 1 preferred).
4. Effective tax year and conformity date.
5. Filing form or worksheet line reference.
6. Confidence and unresolved gap.

## Immediate next expansion targets

- Close NJ and OH explicit-authority gaps.
- Add Utah, Indiana, Minnesota.
- Recheck New York and Illinois for 2026 form-year line renumbering drift.
