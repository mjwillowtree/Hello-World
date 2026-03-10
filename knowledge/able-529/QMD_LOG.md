# QMD Log

## 2026-03-10 Run

### Q (Query)

1. **Depth:** Is the 529->ABLE rollover sunset actually gone for post-2025 years under controlling law?
2. **Adversarial:** If IRS newsroom language and examples are stale, what authority hierarchy should govern practitioner advice?
3. **Breadth:** Which high-impact states can be upgraded from watchlist hints to source-backed recapture/conformity rows this run?

### M (Memory)

- **M8:** The prior "before January 1, 2026" sunset language for 529->ABLE treatment was removed by Pub. L. 119-21 Sec. 70117(a), with post-2025 effective-date language in Sec. 70117(b).  
  Confidence: **High**  
  Sources:
  - https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm
  - https://uscode.house.gov/view.xhtml?edition=prelim&req=granuleid:USC-prelim-title26-section529

- **M9:** Related ABLE contribution-limit interaction text also had its "before January 1, 2026" phrasing removed in §529A(b)(2)(B)(ii) via Pub. L. 119-21 Sec. 70115(a)(2).  
  Confidence: **High**  
  Sources:
  - https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm
  - https://uscode.house.gov/view.xhtml?edition=prelim&req=granuleid:USC-prelim-title26-section529A

- **M10:** New York IT-225 instructions explicitly treat rollover to a qualified ABLE program as qualified for NY 529 distribution modification logic (A-103 section), reducing prior ambiguity.  
  Confidence: **High**  
  Source:
  - https://www.tax.ny.gov/forms/current-forms/it/it225i.htm

- **M11:** Illinois Schedule M instructions define recapture for transfers to out-of-state plans and for nonqualified withdrawals/refunds; this gives a clearer recapture framework for analyzing 529->ABLE events.  
  Confidence: **Medium-High**  
  Source:
  - https://tax.illinois.gov/forms/incometax/currentyear/individual/il-1040-schedule-m-instr.html

- **M12 (contrarian):** Legacy IRS newsroom content is useful background but can lag statutory updates; do not treat it as controlling when statute/public law text conflicts or has moved ahead.  
  Confidence: **High**  
  Sources:
  - https://www.irs.gov/newsroom/tax-reform-affects-able-accounts-savers-credit-529-rollovers
  - https://www.irs.gov/instructions/i1099qa
  - https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm

### Assumption challenge

- Challenged assumption: **"If IRS newsroom says it, implementation details are settled."**
- Result: **Failed.** Statutory/public-law text is the governing source; legacy newsroom examples lag and can anchor outdated thresholds/wording.

### D (Document updates)

- Added definitive memo: `docs/POST_2025_529_TO_ABLE_STATUS_MEMO.md`.
- Updated federal baseline: resolved post-2025 sunset ambiguity and linked controlling authority.
- Upgraded `docs/STATE_RECAPTURE_WATCHLIST.md` to matrix-style rows with confidence/open-issue fields.
- Updated `docs/KNOWLEDGE_FRONTIER.md` scores and next priorities.
- Updated `docs/QUESTION_BANK.md` (closed one unknown, added new unknowns).
- Re-ranked `TASKLIST.md` to reflect completed depth item and next highest-EVI work.

### New unknowns added this run

1. New York treatment differences, if any, for NY-plan versus out-of-state 529 sources rolling to ABLE.
2. Illinois direct DOR statement confirming 529->ABLE qualified treatment (beyond recapture inference).
3. Pennsylvania controlling text for rollover-specific recapture/add-back treatment.

### Next run target

Build the adversarial decision framework comparing 529 distribution vs 529->ABLE vs 529->Roth IRA, while expanding the state matrix to at least three additional high-priority states with line-level filing references.

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
