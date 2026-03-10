# State Recapture Watchlist (Seed)

Updated: 2026-03-10

Purpose: starter list for building a 50-state 529->ABLE recapture/add-back matrix.

## States flagged to date

| State | Risk Signal | Primary Source | Status |
|---|---|---|---|
| Oregon | Rule text references recapture mechanics in 529/ABLE context | https://oregon.public.law/rules/oar_150-315-0065 | Verify exact taxpayer scenarios |
| Colorado | DOR guidance indicates addition/recapture concepts for 529/ABLE treatment | https://tax.colorado.gov/income-tax-topics-able-contribution-subtraction | Verify rollover-specific handling |
| Virginia | Plan guidance warns on deduction recapture context for transfers | https://www.virginia529.com/blog/transfer-invest529-funds-to-ablenow | Confirm with state tax authority text |
| New York | Plan materials discuss state recapture triggers generally | https://www.ny529advisor.com/our-plan/state-tax-benefits | Confirm direct 529->ABLE treatment |
| Utah | my529 addback ties recapture to IRC section 529(c)/530(d) exceptions; no explicit ABLE naming | https://incometax.utah.gov/additions/my529-addback | Conditional, statute-cross-reference model (Medium confidence) |
| Indiana | DOR bulletin recognizes Indiana ABLE transfers as qualified (2024+), but form instructions still contain broader nonqualified language | https://www.in.gov/dor/files/ib98.pdf | Source conflict: bulletin vs form text (Medium confidence) |
| Minnesota | Recapture applies to nonqualified uses and excludes rollovers to other "qualified accounts" (section 529); no explicit ABLE language found | https://www.revisor.mn.gov/statutes/cite/290.06/pdf | Inferred likely recapture for ABLE unless clarified (Medium confidence) |

## Matrix schema to apply next runs

For each state, capture:

1. Prior-year deduction or credit allowed? (Y/N)
2. 529->ABLE treated as qualified for state tax? (Y/N/Conditional)
3. Recapture/add-back rule citation.
4. Effective tax year and conformity date.
5. Filing form or worksheet line reference.

## Immediate next expansion targets

- California, New Jersey, Pennsylvania, Illinois, Ohio.
- Citation hardening backlog: New York, Oregon, Colorado, Virginia (state tax authority/form-level upgrade).
