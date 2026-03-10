# QMD Log

## 2026-03-10 Hourly Run

### Q (Query)

1. Is the federal 529->ABLE rollover sunset (pre-2026 window) still in force, or was it removed by later law?
2. What materially changed in ABLE-to-Work contribution mechanics for 2026 advisory practice?
3. Which state signals this run are strong enough to use, and which are still too weak/secondary?

### M (Memory)

- **M8:** Federal law now explicitly extends 529->ABLE rollovers beyond 2025 by removing the phrase `"before January 1, 2026,"` from IRC §529(c)(3)(C)(i)(III).  
  Confidence: **High**  
  Sources:
  - https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm (Pub. L. 119-21, §70117)
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim (2025 amendment note + current text)

- **M9:** The current U.S. Code text for §529(c)(3)(C)(i)(III) still permits rollover to an ABLE account and no longer contains the sunset phrase.  
  Confidence: **High**  
  Sources:
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim

- **M10:** ABLE-to-Work enhancement also continues post-2025: Pub. L. 119-21 §70115 removed the `"before January 1, 2026"` limiter in §529A(b)(2)(B)(ii), and §529A now shows the contribution formula as base amount plus additional amount for eligible workers.  
  Confidence: **High**  
  Sources:
  - https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm (Pub. L. 119-21, §70115)
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529A&num=0&edition=prelim

- **M11:** Illinois has explicit recapture/add-back mechanics for prior 529/ABLE deductions when transfers go to out-of-state plans or when withdrawals are nonqualified/refunded; 529->ABLE classification still needs direct state-law interpretation.  
  Confidence: **Medium-High**  
  Sources:
  - https://tax.illinois.gov/forms/incometax/currentyear/individual/il-1040-schedule-m-instr.html

- **M12 (surprising/contrarian):** California FTB 2025 instructions indicate California generally conforms to TCJA provisions that allow 529->ABLE rollover, contradicting simplistic assumptions that California is uniformly hostile to this pathway.  
  Confidence: **Medium**  
  Sources:
  - https://www.ftb.ca.gov/forms/2025/2025-3805p-instructions.html

### D (Document updates)

- Updated `docs/FEDERAL_BASELINE.md` to mark rollover permanence ambiguity as resolved and added ABLE-to-Work extension confirmation.
- Updated `docs/KNOWLEDGE_FRONTIER.md` confidence scores and recorded an explicit assumption challenge result.
- Updated `docs/QUESTION_BANK.md` with 6 new unknowns discovered this run.
- Updated `docs/STATE_RECAPTURE_WATCHLIST.md` with fresh CA/IL/PA evidence and a stricter source-quality requirement.
- Re-ranked `TASKLIST.md` to prioritize authority hierarchy + Tier-1 state matrix expansion.

### Assumption challenged

- Challenged assumption: "Older IRS/public summaries implying pre-2026 sunset are enough to conclude rollover expiry."
- Result: **Rejected.** Current enacted law and U.S. Code amendment notes show sunset removal.

### Next run target

Produce the authority-hierarchy memo (statute/regs/forms/publications/plan docs) and close 4 more state entries (NJ, OH, UT, IN) with at least one state tax authority citation each.

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
