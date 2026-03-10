# Federal Baseline (ABLE + 529 Interaction)

Updated: 2026-03-10

## Confirmed baseline rules

1. **Eligibility expansion in 2026**
   - Disability onset test shifts to before age 46 (from before age 26), effective 2026-01-01.
   - Sources:
     - SECURE 2.0 statute: https://www.congress.gov/117/plaws/publ328/PLAW-117publ328.pdf
     - SSA POMS: https://secure.ssa.gov/POMS.NSF/lnx/0501130740

2. **SSI resource treatment**
   - ABLE balances are excluded for SSI resource purposes up to $100,000.
   - Excess above $100,000 can suspend SSI cash payments when countable resources exceed thresholds.
   - Sources:
     - https://www.ssa.gov/ssi/spotlights/spot-able.html
     - https://secure.ssa.gov/POMS.NSF/lnx/0501130740

3. **Post-2025 529->ABLE rollover sunset language has been removed in current code text**
   - Current §529(c)(3)(C)(i)(III) contains the ABLE rollover pathway without the prior "before January 1, 2026" qualifier.
   - U.S. Code amendment note shows: Pub. L. 119-21, sec. 70117(a), struck out "before January 1, 2026," before "to an ABLE account."
   - Sources:
     - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim

4. **529->ABLE rollover mechanics remain bounded by beneficiary and annual-cap rules**
   - Rollover must be to the designated beneficiary or a member of the family.
   - Rollover amount counts toward annual ABLE contribution limitation under §529A(b)(2)(B)(i).
   - Sources:
     - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim
     - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529A&num=0&edition=prelim

5. **2026 ABLE base annual contribution interpretation**
   - Best current legal reading is **$20,000** for 2026.
   - Reason: §529A(b)(2)(B)(i) applies ABLE-specific indexing language substituting "1996" for "1997" when applying §2503(b)(2)(B).
   - Sources:
     - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529A&num=0&edition=prelim
     - https://uscode.house.gov/quicksearch/get.plx?section=2503&title=26
     - https://www.irs.gov/newsroom/irs-releases-tax-inflation-adjustments-for-tax-year-2026-including-amendments-from-the-one-big-beautiful-bill
     - https://www.irs.gov/pub/irs-drop/rp-25-32.pdf

6. **ABLE-to-Work additional contribution formula (2026 operations)**
   - Additional amount is the lesser of:
     - compensation includible in gross income for the taxable year, or
     - one-person poverty line for the preceding calendar year.
   - Additional amount is unavailable if any contribution is made for the year to 401(a), 403(a), 403(b), governmental 457(b), or 457(b) plan on behalf of the beneficiary.
   - Using 2025 poverty-line figures for 2026:
     - 48 states + DC: $15,650 (total potential cap $35,650),
     - Alaska: $19,550 (total potential cap $39,550),
     - Hawaii: $17,990 (total potential cap $37,990).
   - Sources:
     - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529A&num=0&edition=prelim
     - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section219&num=0&edition=prelim
     - https://www.ecfr.gov/current/title-26/chapter-I/subchapter-A/part-1/section-1.529A-2
     - https://aspe.hhs.gov/topics/poverty-economic-mobility/poverty-guidelines/prior-hhs-poverty-guidelines-federal-register-references/2025-poverty-guidelines-computations

## Implementation hierarchy (advisor rule)

If sources conflict, apply:
1. Statute (U.S. Code),
2. Final regulations,
3. Official IRS forms/instructions/publications,
4. IRS newsroom/plan marketing pages.

Use IRS newsroom pages as directional only; those pages explicitly warn that news items may not be updated after release.

## Known ambiguities (must resolve)

1. **ABLE-to-Work compensation timing**
   - How to handle W-2 corrections, late-year payroll corrections, and self-employment measurement in real workflows.
   - Current conservative stance: cap additional contributions at clearly documented compensation already includible for the taxable year.

2. **Retirement-plan participation test edge cases**
   - Need explicit year-attribution treatment when employer contributions are posted late in year or as true-ups.
   - Current conservative stance: if any qualifying employer contribution is made on behalf of beneficiary for the year, treat additional ABLE-to-Work amount as unavailable pending contrary authority.

3. **Stale guidance risk management**
   - Sub-regulatory sources still show legacy examples (for example, outdated $15,000 illustrations) even when statute has changed.
   - Action: maintain a stale-guidance tracker and cite controlling text in client-facing memos.

4. **Federal-to-state disconnect risk**
   - Federal qualified treatment does not guarantee state non-recapture treatment.
   - Action: pair every federal recommendation with state-line-item check from the state matrix.

## Research discipline

- Use Tier 1 sources to resolve numeric limits and legal applicability.
- Treat Tier 2 summaries as directional until matched to controlling authority.
- Treat unresolved questions as first-class artifacts; each run should either close one or refine it into narrower testable questions.
