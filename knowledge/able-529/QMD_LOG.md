# QMD Log

## 2026-03-09 Hourly Run (Federal correction + state breadth)

### Q (Query)

1. Is the 529->ABLE rollover sunset ("before January 1, 2026") still controlling federal law, or was it removed?
2. Which state recapture positions can be upgraded from signal-level to source-backed status in one run?
3. Adversarial check: does current code text conflict with legacy IRS-era wording in common summaries?

### M (Memory)

- **M8:** Pub. L. 119-21 sec. 70117(a) removed the sunset phrase from IRC 529(c)(3)(C)(i)(III) by striking "before January 1, 2026," and sec. 70117(b) applies this amendment to taxable years beginning after Dec. 31, 2025.  
  Confidence: **High**  
  Sources:
  - https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim

- **M9:** New York IT-225-I A-103 explicitly treats rollover to a qualified ABLE program as a qualified use (i.e., not nonqualified withdrawal under that rule set).  
  Confidence: **High**  
  Source:
  - https://tax.ny.gov/forms/current-forms/it/it225i.htm

- **M10:** Illinois provides line-level recapture mechanics (Schedule M Line 7 and Line 9), making IL one of the highest-clarity states for operational recapture analysis.  
  Confidence: **High**  
  Source:
  - https://tax.illinois.gov/forms/incometax/currentyear/individual/il-1040-schedule-m-instr.html

- **M11:** California FTB instructions indicate conformity language allowing 529 plan rollover to ABLE without penalty for TY 2019+, while continuing to tax nonqualified distributions with an additional 2.5% tax.  
  Confidence: **Medium-High**  
  Source:
  - https://www.ftb.ca.gov/forms/2025/2025-3805p-instructions.html

### D (Document updates)

- Updated `docs/FEDERAL_BASELINE.md` to resolve sunset/permanence ambiguity and replace it with implementation-lag ambiguity.
- Expanded `docs/STATE_RECAPTURE_WATCHLIST.md` into a Phase 1 matrix (CA, IL, NY, NJ plus unresolved states).
- Updated `docs/KNOWLEDGE_FRONTIER.md` scores and added explicit assumption test outcome.
- Added 5 new high-value unknowns to `docs/QUESTION_BANK.md`.
- Re-ranked `TASKLIST.md` around authority hierarchy + implementation lag as top priority.

### Assumption challenge result

- Challenged: "If IRS newsroom says it, implementation details are settled."
- Outcome: **Failed as a blanket assumption.**
- Reason: enacted law and current USC notes showed the sunset phrase was removed; legacy wording can persist in secondary summaries or stale implementation artifacts.

### Next run target

Build the authority hierarchy memo with specific IRS artifacts (forms/pubs/instructions/newsroom) classified as updated vs stale for 529->ABLE post-2025 treatment, then add 4 more states with form-line recapture mapping.

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
