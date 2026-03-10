# QMD Log

## 2026-03-10 09:00Z Run

### Q (Query)

1. Does federal authority for 529->ABLE rollovers continue after 2025, or did it sunset?
2. For New York, what exact resident-return instruction language governs whether 529->ABLE triggers recapture/add-back?
3. Which assumptions in the current system are most likely to fail under adversarial review?

### M (Memory)

- **M8:** Post-2025 federal 529->ABLE rollover authority is active because Pub. L. 119-21 Sec. 70117(a) amended IRC 529(c)(3)(C)(i)(III) by striking the phrase "before January 1, 2026,".  
  Confidence: **High (Tier 1)**  
  Sources:
  - https://www.congress.gov/119/plaws/publ21/PLAW-119publ21.pdf
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim

- **M9:** Current codified IRC 529(c)(3)(C)(i)(III) text contains no sunset language and still requires ABLE annual-cap coordination through cross-reference to 529A(b)(2)(B)(i).  
  Confidence: **High (Tier 1)**  
  Sources:
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim

- **M10:** NY resident instruction language (IT-201-I line 22) explicitly treats rollovers to a qualified ABLE program as qualified use (therefore not nonqualified for line-22 add-back).  
  Confidence: **High (Tier 1 state form instruction)**  
  Sources:
  - https://www.tax.ny.gov/pdf/current_forms/it/it201i.pdf
  - https://www.tax.ny.gov/pdf/current_forms/it/it201_fill_in.pdf

- **M11:** Assumption challenge result: "Federal updates automatically propagate into state treatment" remains false. Federal permanence does not eliminate state recapture risk analysis; state return instructions remain controlling for state add-back mechanics.  
  Confidence: **High (method + state/federal mismatch evidence)**  
  Sources:
  - https://www.congress.gov/119/plaws/publ21/PLAW-119publ21.pdf
  - https://www.tax.ny.gov/pdf/current_forms/it/it201i.pdf

### D (Document updates)

- Added `docs/POST_2025_529_TO_ABLE_STATUS_MEMO.md` with controlling federal quotes and advisor-safe hierarchy.
- Updated `docs/FEDERAL_BASELINE.md` to mark post-2025 rollover ambiguity as resolved.
- Upgraded `docs/STATE_RECAPTURE_WATCHLIST.md` with NY line-level authority and filing mechanics.
- Updated frontier scoring in `docs/KNOWLEDGE_FRONTIER.md`.
- Expanded `docs/QUESTION_BANK.md` with five new unknowns (26-30) and marked two questions as newly closed/partially closed.
- Re-ranked priorities in `TASKLIST.md`.

### Quality gate check

1. Depth ambiguity resolved: **Yes** (federal post-2025 rollover status).
2. Breadth area expanded: **Yes** (state lane with NY resident recapture mechanics).
3. New unknowns added: **Yes** (26-30 in question bank).
4. Core assumption challenged: **Yes** (federal-state conformity assumption failed again).

### Next run target

Close at least one additional Tier 1 state gap (NJ or OH) with direct form/instruction quotes, then start the adversarial 529 distribution vs 529->ABLE vs 529->Roth IRA comparison grid.

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
