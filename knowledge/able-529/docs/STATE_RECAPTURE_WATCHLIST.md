# State Recapture Watchlist (Phase 1)

Updated: 2026-03-09

Purpose: build a citation-backed 50-state 529->ABLE recapture/add-back matrix with confidence labels.

## Working matrix (current run additions)

| State | Prior deduction/credit? | 529->ABLE state treatment | Recapture/add-back signal | Primary source(s) | Confidence |
|---|---|---|---|---|---|
| California | No practical personal PIT deduction for 529 contributions (recapture generally N/A) | Appears treated as allowed rollover to ABLE "without penalty" for TY 2019+ conformity language | Nonqualified distributions still taxed + 2.5% additional tax; CA explicitly nonconforms for some other federal expansions (example: 529->Roth) | https://www.ftb.ca.gov/forms/2025/2025-3805p-instructions.html | Medium-High |
| Illinois | Yes | Conditional qualified treatment; line-level recapture depends on out-of-state transfers and nonqualified withdrawals | Schedule M instructions explicitly define recapture on Line 7 (transfer to out-of-state) and Line 9 (nonqualified/refund) | https://tax.illinois.gov/forms/incometax/currentyear/individual/il-1040-schedule-m-instr.html | High |
| New York | Yes | Explicitly treated as qualified use in NY nonqualified-withdrawal definition | IT-225-I A-103 says withdrawal is nonqualified unless used for listed purposes, including rollover to a qualified ABLE program | https://tax.ny.gov/forms/current-forms/it/it225i.htm | High |
| New Jersey | Yes (NJBEST deduction for TY 2022+) | Likely qualified when rollover meets IRC 529(c)(3)(C)(i), but ABLE is not named explicitly on this page | NJ guidance says rollover from one account to another is qualified if it meets IRC 529(c)(3)(C)(i); interpretation depends on federal clause content for tax year | https://www.nj.gov/treasury/taxation/individuals/collegededuction.shtml | Medium |
| Oregon | Yes | Unknown | Existing recapture rule references require taxpayer-scenario mapping | https://oregon.public.law/rules/oar_150-315-0065 | Medium-Low |
| Colorado | Yes (ABLE subtraction regime) | Unknown | Addition/recapture concepts appear in DOR guidance, but rollover-specific treatment still unverified | https://tax.colorado.gov/income-tax-topics-able-contribution-subtraction | Medium-Low |
| Virginia | Yes | Unknown | Existing signal is plan-level warning; still need Virginia tax authority confirmation | https://www.virginia529.com/blog/transfer-invest529-funds-to-ablenow | Low |
| Pennsylvania | Yes | Unknown | PA DOR has clear nonqualified 529 distribution taxation guidance, but no confirmed direct 529->ABLE treatment citation yet | https://revenue-pa.custhelp.com/app/answers/detail/a_id/2517/~/where-should-a-distribution-from-an-irc-section-529-college-and-career-saving | Low |

## Matrix schema (enforced)

For each state, capture:

1. Prior-year deduction or credit allowed? (Y/N)
2. 529->ABLE treated as qualified for state tax? (Y/N/Conditional/Unknown)
3. Recapture/add-back rule citation.
4. Effective tax year and conformity date.
5. Filing form or worksheet line reference.
6. Confidence label + reason.

## Immediate next expansion targets

- Ohio, Utah, Indiana, Minnesota, New Jersey (line-level forms), Pennsylvania (direct 529->ABLE citation), Oregon, Colorado.
