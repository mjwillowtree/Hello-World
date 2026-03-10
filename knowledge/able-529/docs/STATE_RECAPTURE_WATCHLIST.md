# State Recapture Watchlist (Seed)

Updated: 2026-03-10

Purpose: starter list for building a 50-state 529->ABLE recapture/add-back matrix.

## States flagged (Phase 1 batch)

| State | Risk Signal | Primary Source | Status |
|---|---|---|---|
| Oregon | Rule text references recapture mechanics in 529/ABLE context | https://oregon.public.law/rules/oar_150-315-0065 | Verify exact taxpayer scenarios |
| Colorado | DOR guidance indicates addition/recapture concepts for 529/ABLE treatment | https://tax.colorado.gov/income-tax-topics-able-contribution-subtraction | Verify rollover-specific handling |
| Virginia | Plan guidance warns on deduction recapture context for transfers | https://www.virginia529.com/blog/transfer-invest529-funds-to-ablenow | Confirm with state tax authority text |
| California | No state 529 deduction reduces recapture exposure; conformity changed after initial TCJA nonconformity year | https://www.ftb.ca.gov/forms/2019/2019-3805p-instructions.html | Medium confidence; verify current-year form handling |
| New York | Has explicit 529 add-back/deduction machinery (A-103/S-103), but 529->ABLE treatment still needs direct NY tax-department statement | https://www.tax.ny.gov/forms/current-forms/it/it225i.htm | High importance gap (Tier 1 clarification needed) |
| New Jersey | State has deduction/nonqualified-withdrawal framework; direct 529->ABLE classification not yet located | https://www.nj.gov/treasury/taxation/individuals/collegededuction.shtml | Medium confidence, unresolved |
| Pennsylvania | Broad 529 deduction regime; rollover-to-ABLE appears supported but form-level treatment needs tighter citation | https://revenue-pa.custhelp.com/app/answers/detail/a_id/2208 | Medium confidence, unresolved |
| Illinois | Schedule M has explicit recapture lines for out-of-state transfer/nonqualified withdrawals (529 + ABLE references) | https://tax.illinois.gov/content/dam/soi/en/web/tax/forms/incometax/documents/currentyear/individual/il-1040-schedule-m.pdf | Medium-high confidence; still need direct 529->ABLE classification memo |
| Ohio | Statutory add-back language appears strict; risk that 529->ABLE may trigger Ohio addition without explicit exception | https://codes.ohio.gov/ohio-revised-code/section-5747.70 | High-risk interpretation; verify with Ohio DOR clarification |

## Matrix schema to apply next runs

For each state, capture:

1. Prior-year deduction or credit allowed? (Y/N)
2. 529->ABLE treated as qualified for state tax? (Y/N/Conditional)
3. Recapture/add-back rule citation.
4. Effective tax year and conformity date.
5. Filing form or worksheet line reference.

## Immediate next expansion targets

- Utah, Indiana, Minnesota, New York (closure), New Jersey (closure), Ohio (closure).

## Closure checklist for each unresolved state

1. State tax-department form instruction or bulletin explicitly naming 529->ABLE treatment.
2. Recapture/add-back line mapping (return + worksheet line if applicable).
3. Effective date and conformity year note.
4. "If silent" fallback position language with confidence downgrade.
