# QMD Log

## 2026-03-10 Run

### Q (Query)

Frontier questions generated before research:

1. **Depth:** What is the strongest Tier-1/Tier-2 authority for ABLE-to-Work when payroll events cross year-end (withholding date vs ABLE posting date)?
2. **Depth/adversarial:** Does "no contribution is made ... to a plan" under IRC 529A(b)(7)(A) effectively disqualify DB-only workers even without elective deferrals?
3. **Breadth:** Which new state rules/instructions most directly indicate whether 529->ABLE triggers recapture/add-back (MN, UT, IN)?
4. **Adversarial:** If federal law changed but state instructions still lag, which source hierarchy should control advisor recommendations?

### M (Memory)

- **M8:** Post-2025 529->ABLE sunset ambiguity is now resolved at high confidence. Current IRC 529 amendment notes show Pub. L. 119-21 section 70117(a) struck "before January 1, 2026," and effective-date text applies amendment to taxable years beginning after Dec. 31, 2025.  
  Confidence: **High**  
  Sources:
  - https://uscode.house.gov/view.xhtml?req=(title:26%20section:529%20edition:prelim)

- **M9:** ABLE-to-Work extra contribution mechanics are firmly anchored in IRC 529A: additional amount is capped by the lesser of compensation or one-person poverty-line amount; retirement-plan disqualifier is contribution-based and names 401(a)/403(a), 403(b), and 457(b)-related arrangements.  
  Confidence: **High**  
  Sources:
  - https://uscode.house.gov/view.xhtml?req=(title:26%20section:529A%20edition:prelim)
  - https://www.irs.gov/irb/2020-50_IRB#TD-9923

- **M10:** IRS 1099-QA/5498-QA instructions provide operational details that matter for ABLE-to-Work controls (poverty guideline by beneficiary residence state; beneficiary recordkeeping responsibility), but they do not fully close year-end timing edge cases.  
  Confidence: **Medium-High**  
  Sources:
  - https://www.irs.gov/instructions/i1099qa

- **M11:** State treatment can diverge sharply even when federal exceptions exist. Oregon has explicit 529/ABLE unqualified withdrawal recapture rule text; Minnesota recapture language is clear for nonqualified 529 withdrawals but does not explicitly resolve 529->ABLE carveout in the DOR page reviewed.  
  Confidence: **Medium**  
  Sources:
  - https://oregon.public.law/rules/oar_150-315-0065
  - https://www.revenue.state.mn.us/education-savings-account-recapture-tax

- **M12 (surprising/contrarian):** Utah addback instructions explicitly key off whether an IRC 529(c)/530(d) exception applies, implying that federal statutory exception changes can alter state addback outcomes without Utah rewriting every instruction each year.  
  Confidence: **Medium**  
  Sources:
  - https://incometax.utah.gov/additions/my529-addback
  - https://uscode.house.gov/view.xhtml?req=(title:26%20section:529%20edition:prelim)

### D (Document updates)

- Updated `docs/FEDERAL_BASELINE.md`:
  - closed rollover sunset ambiguity,
  - added authority hierarchy/conflict rule,
  - upgraded ABLE-to-Work core mechanics and narrowed remaining ambiguities.
- Updated `docs/STATE_RECAPTURE_WATCHLIST.md` with MN/UT/IN additions and confidence labels.
- Updated `docs/KNOWLEDGE_FRONTIER.md` confidence scores and refreshed top 3 priorities.
- Expanded `docs/QUESTION_BANK.md` with 5 new unknowns (items 26-30).
- Re-ranked `TASKLIST.md` around highest current value-of-information (ABLE-to-Work edge memo + line-level state mapping + implementation-lag tracker).

### Assumption challenge

- Challenged assumption: **"Federal conformity means state conformity."**  
  Outcome: **Failed / false.** Oregon and Minnesota language show recapture risk framing that is not automatically resolved by federal qualified treatment alone; Utah appears exception-driven but still needs line-level confirmation.

### Next run target

1. Lock down ABLE-to-Work year-end attribution and employer true-up guidance using highest-authority language available.
2. Convert NY/NJ/MN/UT from "signal-level" to exact line/code-level state matrix entries.
3. Start implementation-lag registry with at least five stale or potentially stale references.

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
