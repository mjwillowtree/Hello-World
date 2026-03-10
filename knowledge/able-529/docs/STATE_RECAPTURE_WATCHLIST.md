# State Recapture Matrix (Working)

Updated: 2026-03-10

Purpose: evolving matrix for building a 50-state 529->ABLE recapture/add-back map.

## Evidence matrix v0.1 (priority states)

| State | Prior 529 state tax benefit | 529->ABLE state signal | Citation(s) | Form line refs | Confidence | Caveat |
|---|---|---|---|---|---|---|
| CA | None (no CA deduction/credit for 529 contributions) | No deduction recapture exposure from prior CA 529 benefit (because none exists) | https://www.scholarshare529.com/resources/faq/ ; https://calable.ca.gov/faqs/can-i-roll-over-a-529-college-savings-plan-account-into-my-calable-account | N/A | Medium | Need FTB text explicitly addressing treatment framing; current signal is practical rather than code-cited. |
| NY | Deduction available (subject to NY rules) | Unclear for 529->ABLE-specific recapture handling | https://www.nysaves.org/home/federal-tax-update.html ; https://tax.ny.gov/forms/current-forms/it/it225i.htm | IT-225 modification codes (A-114/S-103 mechanism) | Low | NY decoupling history creates risk; need direct DTF statement for ABLE rollover scenario. |
| NJ | Deduction available (income-limited under NJBEST framework) | Unclear for 529->ABLE-specific treatment | https://www.nj.gov/treasury/taxation/njgrosstax.shtml ; https://pub.njleg.state.nj.us/Bills/2020/PL21/128_.PDF | Not pinned yet | Low | Need NJ-1040 instruction-level citation that explicitly addresses ABLE rollovers. |
| PA | Deduction available | Strong signal of conformity: federally excludable 529 distributions excluded for PA PIT (TY2024+) | https://www.pa.gov/content/dam/copapwp-pagov/en/revenue/documents/taxlawpoliciesbulletinsnotices/taxsummaries/documents/2024_tax_summary_aug.pdf | PA-40 Schedule A context for non-educational distributions | High | Confirm there is no contrary PA form instruction for ABLE rollover fact pattern. |
| IL | Deduction/subtraction available | Recapture/add-back risk unless carveout exists (no carveout pinned yet) | https://tax.illinois.gov/content/dam/soi/en/web/tax/forms/incometax/documents/currentyear/individual/il-1040-schedule-m.pdf ; https://tax.illinois.gov/forms/incometax/currentyear/individual/il-1040-schedule-m-instr.html | Schedule M Line 9 (and related recapture logic) | Medium | Must verify if IDOR has ABLE-specific exception guidance outside Schedule M text. |
| OH | Deduction available | Recapture/add-back risk appears present when not in explicit exceptions | https://tax.ohio.gov/faq-529 ; https://codes.ohio.gov/ohio-revised-code/section-5747.70 ; https://tax.ohio.gov/static/ohio_individual/individual/supportingdocumentation/pages/a-3_529addition.html | A-3 addition support (line reference varies by year) | Medium | Need current-year ORC/form tie-out specifically naming 529->ABLE pathway. |

## Matrix schema to apply next runs

For each state, capture:

1. Prior-year deduction or credit allowed? (Y/N)
2. 529->ABLE treated as qualified for state tax? (Y/N/Conditional)
3. Recapture/add-back rule citation.
4. Effective tax year and conformity date.
5. Filing form or worksheet line reference.
6. Confidence + "why not higher."

## Immediate next expansion targets

- Utah, Indiana, Minnesota, Oregon, Colorado, Virginia.
- Then expand to: Connecticut, Iowa, Kansas, Nebraska, Missouri, Wisconsin.
