# QMD Log

## 2026-03-10 Hourly Run

### Q (Query)

1. Is the post-2025 529->ABLE sunset still in force, or removed in controlling statutory text?
2. Can NY/NJ/PA/IL/OH be moved from watchlist status to source-tiered recapture treatment with line references?
3. What ABLE-to-Work mechanics are still operationally ambiguous after reading statute + regs?
4. Adversarial check: which currently cited guidance is stale relative to current code text?

### M (Memory)

- **M8:** Current U.S. Code §529(c)(3)(C)(i)(III) retains 529->ABLE rollover language without prior pre-2026 cutoff; amendment notes attribute removal of "before January 1, 2026" to Pub. L. 119-21 sec. 70117(a).  
  Confidence: **High**  
  Sources:
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim

- **M9:** ABLE-to-Work additional contribution mechanics are now pinned to a practical 2026 formula: additional amount is min(compensation includible in gross income, prior-year one-person poverty line), subject to retirement-plan contribution disqualifier.  
  Confidence: **High (formula), Medium (edge operations)**  
  Sources:
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529A&num=0&edition=prelim
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section219&num=0&edition=prelim
  - https://www.ecfr.gov/current/title-26/chapter-I/subchapter-A/part-1/section-1.529A-2

- **M10:** Using 2025 poverty-line values for 2026 ABLE-to-Work calculations yields additional caps of $15,650 (48/DC), $19,550 (AK), and $17,990 (HI), implying total potential 2026 limits of $35,650 / $39,550 / $37,990 when base cap is $20,000.  
  Confidence: **High**  
  Sources:
  - https://aspe.hhs.gov/topics/poverty-economic-mobility/poverty-guidelines/prior-hhs-poverty-guidelines-federal-register-references/2025-poverty-guidelines-computations
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529A&num=0&edition=prelim

- **M11:** New York now has strong Tier 1 language relevant to 529->ABLE characterization: IT-225-I A-103 nonqualified withdrawal rules explicitly list ABLE rollovers in the exception set (i.e., treated as qualified for this purpose).  
  Confidence: **High**  
  Sources:
  - https://www.tax.ny.gov/forms/current-forms/it/it225i.htm

- **M12:** Illinois provides explicit line-level recapture controls for 529/ABLE in Schedule M (line 7 out-of-state transfer recapture; line 9 nonqualified/refund recapture), making IL one of the strongest states for operational guidance.  
  Confidence: **High**  
  Sources:
  - https://tax.illinois.gov/content/dam/soi/en/web/tax/forms/incometax/documents/currentyear/individual/il-1040-schedule-m.pdf

- **M13 (surprising):** IRS newsroom pages can remain materially stale for years and include their own warning that news items may not be updated; reliance hierarchy must place statute/regs/forms above newsroom examples.  
  Confidence: **High**  
  Sources:
  - https://www.irs.gov/newsroom/tax-reform-affects-able-accounts-savers-credit-529-rollovers

### Assumption challenge

- Challenged: **"If IRS newsroom says it, implementation details are settled."**
- Outcome: **Failed.** Newsroom language/examples are not a reliable current-law endpoint; controlling text and current form instructions must govern.

### D (Document updates)

- Updated `docs/FEDERAL_BASELINE.md`:
  - moved 529->ABLE sunset issue to resolved baseline,
  - added authority hierarchy and stale-guidance caution,
  - added ABLE-to-Work 2026 formula and operational ambiguity framing.
- Updated `docs/STATE_RECAPTURE_WATCHLIST.md` into source-tiered matrix with NY/IL upgrades and NJ/OH/PA gap framing.
- Updated `docs/KNOWLEDGE_FRONTIER.md` scores and next-run priorities.
- Expanded `docs/QUESTION_BANK.md` with unknowns 26-32.
- Re-ranked `TASKLIST.md` around NJ/OH closure, ABLE-to-Work memo completion, and stale-guidance tracker.

### Next run target

1. Close one state gap to Tier 1 explicitness (NJ or OH).
2. Produce ABLE-to-Work conservative example set (payroll timing, W-2c, true-up scenarios).
3. Start adversarial comparison framework: 529 distribution vs 529->ABLE vs 529->Roth IRA.

## 2026-03-09 Curiosity Upgrade Run

### Q (Query)

1. How do we redesign the system so each hourly run must expand curiosity (not just append notes)?
2. What structural controls ensure both depth and breadth growth toward ABLE/529 mastery?

### M (Memory)

- **M6:** A research system stagnates when it tracks only current tasks; it must also track unknowns, assumptions, and frontier confidence scores.  
  Confidence: **High (methodological)**  
  Source:
  - Internal process redesign for this repository (QMD protocol revision)

- **M7:** Curiosity can be operationalized with hard run gates: one depth upgrade, one breadth expansion, new unknown generation, and assumption challenge.  
  Confidence: **High (methodological)**  
  Source:
  - Internal process redesign for this repository (QMD protocol revision)

### D (Document updates)

- Updated `README.md` to QMD+ with a mandatory curiosity engine.
- Added `docs/KNOWLEDGE_FRONTIER.md` with domain coverage/confidence scoring and assumption stress tests.
- Added `docs/QUESTION_BANK.md` to continuously generate and prioritize unanswered questions.
- Rewrote `TASKLIST.md` to include mandatory quality gates and value-of-information prioritization.

### Next run target

Execute the new protocol on substance: resolve the 529->ABLE post-2025 legal status using Tier 1 authorities and simultaneously expand the state recapture matrix to at least 4 additional states.

## 2026-03-09 Run

### Q (Query)

1. What are the most important federal ABLE rules to lock down in 2026?
2. What are the highest-risk mistakes when doing 529->ABLE rollovers?

### M (Memory)

- **M1:** ABLE age-of-onset eligibility expands from "before 26" to "before 46" effective 2026-01-01.  
  Confidence: **High**  
  Sources:
  - https://www.congress.gov/117/plaws/publ328/PLAW-117publ328.pdf
  - https://secure.ssa.gov/POMS.NSF/lnx/0501130740

- **M2:** SSI ignores ABLE balances up to $100,000; amounts above can suspend SSI cash benefits while Medicaid can continue.  
  Confidence: **High**  
  Sources:
  - https://www.ssa.gov/ssi/spotlights/spot-able.html
  - https://secure.ssa.gov/POMS.NSF/lnx/0501130740

- **M3:** 529->ABLE rollover must be to the same beneficiary or qualifying family member and counts toward annual ABLE contribution limits.  
  Confidence: **High**  
  Sources:
  - https://www.irs.gov/newsroom/tax-reform-affects-able-accounts-savers-credit-529-rollovers
  - https://www.law.cornell.edu/uscode/text/26/529A

- **M4:** State tax treatment may differ from federal treatment; recapture/add-back risk can still apply on prior state deductions.  
  Confidence: **Medium**  
  Sources:
  - https://oregon.public.law/rules/oar_150-315-0065
  - https://tax.colorado.gov/income-tax-topics-able-contribution-subtraction
  - https://www.virginia529.com/blog/transfer-invest529-funds-to-ablenow

- **M5:** 2026 ABLE base annual contribution limit is best interpreted as **$20,000** because §529A(b)(2)(B)(i) applies an ABLE-specific indexing substitution ("1996" for "1997") over the general §2503(b) amount.  
  Confidence: **Medium-High**  
  Sources:
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529A&num=0&edition=prelim
  - https://uscode.house.gov/quicksearch/get.plx?section=2503&title=26
  - https://www.irs.gov/newsroom/irs-releases-tax-inflation-adjustments-for-tax-year-2026-including-amendments-from-the-one-big-beautiful-bill
  - https://www.irs.gov/pub/irs-drop/rp-25-32.pdf
  - https://www.ablenrc.org/millions-more-can-start-their-able-account-journey-in-2026/

### D (Document updates)

- Created `docs/FEDERAL_BASELINE.md` with core federal rule snapshots and unresolved questions.
- Created `docs/STATE_RECAPTURE_WATCHLIST.md` as seed list for the 50-state matrix build.

### Next run target

Verify post-2025 federal legal status of 529->ABLE rollover sunset/permanence and capture advisor-safe interpretation language.
