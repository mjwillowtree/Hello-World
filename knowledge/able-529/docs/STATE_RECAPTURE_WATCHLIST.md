# State Recapture Watchlist (Seed)

Updated: 2026-03-10

Purpose: starter list for building a 50-state 529->ABLE recapture/add-back matrix.

## States flagged in this run

| State | Risk Signal | Primary Source | Status |
|---|---|---|---|
| Oregon | Explicit rule text says unqualified withdrawals from 529 or ABLE accounts trigger forfeiture/recapture mechanics. | https://oregon.public.law/rules/oar_150-315-0065 | Strong signal; still need exact filing line pinning by tax year. |
| Minnesota | DOR page defines recapture for 529 withdrawals used for expenses other than qualified post-secondary expenses; no ABLE carveout found on page. | https://www.revenue.state.mn.us/education-savings-account-recapture-tax | Medium confidence risk flag; needs direct 529->ABLE treatment confirmation. |
| Utah | TC-40A code 54 addback language references withdrawals not used for qualified education expenses unless IRC 529(c)/530(d) exception applies, suggesting federal exceptions may matter directly. | https://incometax.utah.gov/additions/my529-addback | Medium confidence conditional treatment; verify return-line execution and any ABLE-specific Utah guidance. |
| Indiana | DOR bulletin identified as likely source for recapture treatment signals; extraction reliability needs manual verification in current-year forms/instructions. | https://www.in.gov/dor/files/ib98.pdf | Needs tighter citation pinning before advisor-grade output. |
| Colorado | Existing state guidance indicates subtraction/addition interactions can diverge for 529 and ABLE pathways. | https://tax.colorado.gov/income-tax-topics-able-contribution-subtraction | Access limitations in this run; keep open with medium confidence. |
| Virginia | ABLE deduction recapture is explicit in Virginia tax guidance; direct Virginia tax text for 529->ABLE treatment still not pinned. | https://www.tax.virginia.gov/deductions | ABLE side confirmed; 529 rollover recapture treatment still open. |
| New York | Plan-level recapture signals exist, but direct state form line and treatment for 529->ABLE remains unpinned. | https://www.ny529advisor.com/our-plan/state-tax-benefits | Still open; prioritize form-code citation. |

## Matrix schema to apply next runs

For each state, capture:

1. Prior-year deduction or credit allowed? (Y/N)
2. 529->ABLE treated as qualified for state tax? (Y/N/Conditional/Unclear)
3. Recapture/add-back rule citation.
4. Effective tax year and conformity date.
5. Filing form or worksheet line reference.
6. Confidence + unresolved ambiguity note.

## Immediate next expansion targets

- California, New Jersey, Pennsylvania, Illinois, Ohio.
- Move MN and UT from "risk signal" to "line-level mapped."
