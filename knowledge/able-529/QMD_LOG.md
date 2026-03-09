# QMD Log

## 2026-03-09 Hourly Run (23:01Z cron)

### Q (Query)

Frontier questions generated before research:

1. What is the current controlling text for 529->ABLE rollovers after 2025, and does any sunset remain?
2. Do current IRS implementation artifacts still use sunset language, or has sub-regulatory text caught up?
3. What is the highest-value new breadth lane outside prior runs? (selected: 529->Roth rollover mechanics and guidance gaps)
4. Adversarial: if two "official-looking" sources conflict (legacy IRS/news vs current U.S. Code), what should control advisor conclusions?

### M (Memory)

- **M8:** The 529->ABLE sunset is resolved at the codified-text level: U.S. Code amendment notes for IRC §529 show Pub. L. 119-21, §70117(a) struck out `"before January 1, 2026,"` from §529(c)(3)(C)(i)(III).  
  Confidence: **High (Tier 1)**  
  Sources:
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim

- **M9:** Parallel amendment-note evidence in IRC §529A shows Pub. L. 119-21, §70115(a)(2) struck out `"before January 1, 2026"` in §529A(b)(2)(B)(ii) introductory language.  
  Confidence: **High (Tier 1)**  
  Sources:
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529A&num=0&edition=prelim

- **M10:** IRS Publication 970 chapter text currently describes QTP rollovers to ABLE without pre-2026 sunset wording, supporting implementation alignment with amended statute (while still subordinate to statute).  
  Confidence: **Medium-High (Tier 1 IRS, sub-regulatory)**  
  Sources:
  - https://www.irs.gov/publications/p970/ch8.html

- **M11:** Breadth lane added: §529(c)(3)(E) 529->Roth rollover has high-confidence statutory constraints (same beneficiary Roth, 15-year period, 5-year lookback exclusion, annual Roth-framework limit, $35,000 aggregate cap) but still has operational ambiguities requiring conservative workflows.  
  Confidence: **High for statute / Medium for operations**  
  Sources:
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim
  - https://www.congress.gov/117/plaws/publ328/PLAW-117publ328.pdf

- **M12 (surprising/contrarian):** The biggest remaining risk is no longer federal sunset legality; it is **state conformity and stale-guidance conflict**, where official-seeming but older text can mislead planning.  
  Confidence: **Medium-High**  
  Sources:
  - https://www.ftb.ca.gov/forms/2025/2025-3805p-instructions.html
  - https://nj.gov/treasury/taxation/individuals/collegededuction.shtml
  - https://codes.ohio.gov/ohio-revised-code/section-5747.70

### Assumption challenge

- Challenged assumption #5 from frontier map: **"If legacy IRS text once contained a sunset, the rule still sunsets."**
- Result: **Failed.** Current codified text and amendment notes control; legacy wording is stale if not updated.

### D (Document updates)

- Updated `docs/FEDERAL_BASELINE.md`:
  - closed post-2025 rollover sunset ambiguity,
  - added 529->Roth breadth baseline,
  - reframed open ambiguity toward stale-guidance risk and authority hierarchy.
- Updated `docs/STATE_RECAPTURE_WATCHLIST.md` with CA/NJ/PA/OH reconnaissance entries and confidence framing.
- Updated `docs/KNOWLEDGE_FRONTIER.md` confidence scores and next-run priorities.
- Expanded `docs/QUESTION_BANK.md` with new unresolved federal/state adversarial questions (Q26-Q31).
- Re-ranked `TASKLIST.md` with new top priority: authority hierarchy memo.

### Next run target

1. Produce the authority hierarchy memo with direct citations and tie-break rules for conflicting guidance.
2. Convert watchlist into a state matrix (first 12 states) with **form-line-level** recapture/add-back handling.
3. Draft initial adversarial decision sheet for 529 distribution vs 529->ABLE vs 529->Roth.

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
