# QMD Log

## 2026-03-10 Hourly Run (06:00Z)

### Q (Query)

Frontier questions generated before research:
1. What exact authority resolves the 2026 ABLE base limit when section 2503(b) is $19,000 but ABLE references modified indexing text?
2. For ABLE-to-Work, which constraints create the highest real-world compliance failure risk (compensation year, retirement plan timing, geography)?
3. Which high-impact states already have enough authority to classify 529->ABLE recapture treatment with confidence tags?
4. Adversarial check: does "ABLE annual limit equals gift-tax annual exclusion" still hold after post-2025 statutory changes?

### M (Memory)

- **M8:** For 2026, ABLE base annual contribution amount is **$20,000** even though section 2503(b) annual gift exclusion is **$19,000**.  
  Confidence: **High**  
  Why: section 529A applies section 2503(b) with a post-2025 indexing substitution ("1996" for "1997"), producing a different inflation path.  
  Sources:
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529A&num=0&edition=prelim
  - https://uscode.house.gov/view.xhtml?req=%28title%3A26+section%3A2503+edition%3Aprelim%29
  - https://www.irs.gov/pub/irs-drop/rp-25-32.pdf
  - https://www.irs.gov/newsroom/irs-releases-tax-inflation-adjustments-for-tax-year-2026-including-amendments-from-the-one-big-beautiful-bill

- **M9:** ABLE-to-Work additional contribution is limited to the lesser of compensation or the prior-year 1-person poverty-line amount.  
  Confidence: **High**  
  Sources:
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529A&num=0&edition=prelim
  - https://www.irs.gov/pub/irs-drop/n-18-62.pdf

- **M10:** For tax year 2026, the ABLE-to-Work poverty-line reference year is 2025; 1-person amount for 48 states/DC is $15,650 (AK/HI higher).  
  Confidence: **High**  
  Sources:
  - https://www.federalregister.gov/citation/90-FR-5917
  - https://aspe.hhs.gov/topics/poverty-economic-mobility/poverty-guidelines/prior-hhs-poverty-guidelines-federal-register-references/2025-poverty-guidelines-computations
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529A&num=0&edition=prelim

- **M11:** NY has explicit plan-admin language treating rollovers to NY ABLE as nonqualified withdrawals under NY law, while NJ/PA evidence is currently proxy-level (general nonqualified distribution rules without explicit 529->ABLE classification).  
  Confidence: **Medium**  
  Sources:
  - https://www.nysaves.org/home/federal-tax-update.html
  - https://www.tax.ny.gov/forms/current-forms/it/it225i.htm
  - https://www.nj.gov/njbonds/treasury/taxation/new2022.shtml
  - https://www.pa.gov/content/dam/copapwp-pagov/en/revenue/documents/formsandpublications/formsforindividuals/pit/documents/2024/2024_pa-40a.pdf

### D (Document updates)

- Updated `docs/FEDERAL_BASELINE.md`:
  - added ABLE-to-Work 2026 mechanics with authority citations,
  - added hierarchy/conflict protocol for stale or lower-tier guidance,
  - narrowed remaining ABLE-to-Work edge ambiguities.
- Updated `docs/STATE_RECAPTURE_WATCHLIST.md`:
  - expanded to CA/NY/NJ/PA with filing-reference tracking and confidence labels,
  - preserved OR/CO/VA seed states and marked evidence quality explicitly.
- Updated `docs/KNOWLEDGE_FRONTIER.md`:
  - raised confidence in federal mechanics and rollover legality,
  - re-prioritized next three runs.
- Updated `docs/QUESTION_BANK.md`:
  - added 5 new frontier questions (26-30) focused on ABLE-to-Work attribution and state-form explicitness gaps.
- Updated `TASKLIST.md`:
  - moved unresolved-highest-value work to ABLE-to-Work implementation memo + state evidence-hardening.

### Assumption challenge

- Challenged assumption: **"ABLE annual limit always equals section 2503(b) annual exclusion."**
- Result: **Failed**. Post-2025 section 529A indexing substitution can produce a higher ABLE amount than section 2503(b).

### Next run target

1. Hard-pin NY/NJ/PA line-level return instructions for recapture/add-back where available; explicitly document "silent" where not.
2. Add Illinois and Ohio to the matrix with conformity year + reporting line references.
3. Draft ABLE-to-Work conservative compliance examples for payroll year attribution and retirement contribution timing.

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
