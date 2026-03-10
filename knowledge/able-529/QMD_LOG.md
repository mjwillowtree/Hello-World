# QMD Log

## 2026-03-10 Hourly Run (Depth: ABLE-to-Work, Breadth: State matrix expansion)

### Q (Query)

1. What is the most defensible advisor-safe interpretation of ABLE-to-Work contribution eligibility when retirement-plan participation facts are messy?
2. Which high-impact states now have enough primary authority to classify 529->ABLE recapture/add-back risk with confidence?
3. Which assumptions fail when secondary guidance lags statutory amendments?

### M (Memory)

- **M8:** ABLE-to-Work analysis should use a strict authority ladder: IRC §529A first, then regulations/IRB notices, then IRS publications/newsroom summaries.  
  Confidence: **High (methodological + legal hierarchy)**  
  Sources:
  - https://uscode.house.gov/view.xhtml?req=(title:26%20section:529A%20edition:prelim)
  - https://www.irs.gov/irb/2018-34_IRB
  - https://www.irs.gov/publications/p907

- **M9:** ABLE-to-Work participation-test edges remain unresolved in public secondary guidance, especially DB-only coverage and tax-year attribution for employer true-ups; conservative practice is to decline extra contributions when facts are uncertain.  
  Confidence: **Medium**  
  Sources:
  - https://uscode.house.gov/view.xhtml?req=(title:26%20section:529A%20edition:prelim)
  - https://www.federalregister.gov/documents/2020/11/19/2020-22144/guidance-under-section-529a-qualified-able-programs
  - https://www.irs.gov/publications/p907

- **M10:** State mechanics vary sharply: PA/IL have stronger filing-level signals already; NY/NJ still require exact current form-code pinning before high-confidence practitioner guidance.  
  Confidence: **Medium-High**  
  Sources:
  - https://www.pa.gov/content/dam/copapwp-pagov/en/revenue/documents/taxlawpoliciesbulletinsnotices/taxsummaries/documents/2024_tax_summary_aug.pdf
  - https://www.pa.gov/content/dam/copapwp-pagov/en/revenue/documents/formsandpublications/formsforindividuals/pit/documents/2024/2024_pa-40a.pdf
  - https://tax.illinois.gov/forms/incometax/currentyear/individual/il-1040-schedule-m-instr.html
  - https://www.tax.ny.gov/pdf/memos/income/m18-6i.pdf
  - https://www.nj.gov/treasury/taxation/njgrosstax.shtml

### D (Document updates)

- Updated `docs/FEDERAL_BASELINE.md` with ABLE-to-Work authority hierarchy, conservative operating rule, and rollover-permanence status tracking.
- Expanded `docs/STATE_RECAPTURE_WATCHLIST.md` into a Phase 1 matrix covering CA, NY, NJ, PA, IL, OH, plus existing OR/CO/VA signals.
- Added six new unresolved questions to `docs/QUESTION_BANK.md` (ABLE-to-Work mechanics + NY/NJ filing-code gaps + stale-guidance tracker).
- Updated `docs/KNOWLEDGE_FRONTIER.md` scores and logged an explicit assumption challenge outcome.
- Re-ranked `TASKLIST.md` to prioritize ABLE-to-Work quote-backed memo and NY/NJ line-code closure.

### Assumption challenge

- Challenged: **"If IRS/newsroom or plan summaries mention a rule, implementation details are settled."**
- Result: **Failed** under stress. Secondary sources still lag in some places; primary-source conflict-resolution hierarchy remains mandatory.

### Next run target

1. Produce quote-backed ABLE-to-Work memo with explicit handling for DB-only and true-up timing scenarios.
2. Close NY/NJ exact line/modification-code references from current-year instructions/PDF code charts.

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
