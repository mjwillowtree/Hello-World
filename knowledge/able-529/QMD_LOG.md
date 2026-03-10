# QMD Log

## 2026-03-10 Hourly Run

### Q (Query)

Depth track:
1. Is the federal 529->ABLE rollover sunset still operative after 2025, or has it been removed by enacted law?

Breadth track:
2. What is the best current primary-authority read for 529->ABLE recapture/conformity in Ohio, Utah, Indiana, and Minnesota?

Generated frontier questions:
3. Which states explicitly name 529A/ABLE in tax form instructions versus generic "nonqualified withdrawal" language?
4. Where do official state forms conflict with program marketing summaries?
5. Adversarial: if federal law is settled, what is the strongest way state treatment can still produce taxpayer harm?

### M (Memory)

- **M8:** Federal sunset language for 529->ABLE was removed by statute: enrolled text for Sec. 70117 amends IRC 529(c)(3)(C)(i)(III) by striking "before January 1, 2026," with effective date for taxable years beginning after December 31, 2025.  
  Confidence: **High**  
  Sources:
  - https://www.congress.gov/119/bills/hr1/generated/BILLS-119hr1enr.html
  - https://www.congress.gov/119/plaws/publ21/PLAW-119publ21.pdf

- **M9:** Current U.S. Code editorial notes for IRC 529 show Pub. L. 119-21, Sec. 70117(a) struck out "before January 1, 2026," before "to an ABLE account," confirming permanence in codified notes.  
  Confidence: **High**  
  Source:
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim

- **M10:** State treatment remains materially non-uniform/unclear even with federal permanence: Utah appears more likely to conform through IRC exception framing, while Indiana appears recapture-oriented and Ohio/Minnesota remain unresolved for explicit 529->ABLE treatment.  
  Confidence: **Medium**  
  Sources:
  - https://incometax.utah.gov/additions/my529-addback
  - https://codes.ohio.gov/ohio-revised-code/section-5747.70
  - https://www.in.gov/tos/iesa/tax-credit/tax-credit-faq/
  - https://www.revenue.state.mn.us/recapture-tax

- **M11 (assumption stress):** "Federal conformity means state conformity" is a failed assumption in this domain; federal certainty does not eliminate state recapture risk.  
  Confidence: **High (methodological + current evidence)**

### D (Document updates)

- Updated `docs/FEDERAL_BASELINE.md` to mark post-2025 rollover permanence as resolved and citation-backed.
- Added `docs/STATE_RECAPTURE_MATRIX_PHASE1.md` with OH/UT/IN/MN entries and confidence labels.
- Updated `docs/KNOWLEDGE_FRONTIER.md` confidence scores and assumption stress-test outcome.
- Expanded `docs/QUESTION_BANK.md` with five new unknowns (26-30).
- Re-ranked `TASKLIST.md` around authority-hierarchy memo + state matrix expansion.
- Updated `docs/STATE_RECAPTURE_WATCHLIST.md` to align with matrix workflow.

### Surprising / contrarian finding

The highest-risk unanswered questions are no longer mainly federal; they are state implementation and filing-line interpretation issues where legal ambiguity can persist despite federal statutory clarity.

### Next run target

1. Add 4 more high-impact states (CA, NY, NJ, PA) to the matrix with form-line citations.
2. Produce the authority-hierarchy memo with conflict-resolution examples.
3. Close one low-confidence state (NJ or PA) to high confidence.

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
