# QMD Log

## 2026-03-10 Hourly Run

### Q (Query)

Frontier questions generated before research:

1. Did Congress remove the 529->ABLE "before January 1, 2026" sunset in controlling statutory text, and what is the effective date?
2. Which currently accessible IRS pages still carry legacy sunset wording, creating guidance-lag risk?
3. For breadth, what do CA/NJ/PA/IL official tax sources indicate about recapture/add-back risk for 529->ABLE pathways?
4. Adversarial check: if statute and IRS newsroom conflict, which authority should drive advisor recommendations?

### M (Memory)

- **M8:** Public Law 119-21 amended IRC §529(c)(3)(C)(i)(III) by striking `"before January 1, 2026,"`, with an effective-date clause applying to taxable years beginning after December 31, 2025.  
  Confidence: **High**  
  Sources:
  - https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm
  - https://www.congress.gov/119/plaws/publ21/PLAW-119publ21.pdf
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim

- **M9:** IRS legacy newsroom content still contains pre-2026 sunset language for 529->ABLE rollovers; this is a transition-risk artifact and not higher authority than later enacted statute.  
  Confidence: **High**  
  Sources:
  - https://www.irs.gov/newsroom/irs-issues-final-regulations-for-achieving-a-better-life-experience-accounts
  - https://www.irs.gov/newsroom/tax-reform-affects-able-accounts-savers-credit-529-rollovers

- **M10:** State confidence is heterogeneous: California and Illinois have stronger official instruction-level recapture framing, while New Jersey and Pennsylvania still require line-level confirmation for explicit 529->ABLE treatment in current individual return instructions.  
  Confidence: **Medium**  
  Sources:
  - https://www.ftb.ca.gov/forms/2018/18-3805P-instructions.html
  - https://www.ftb.ca.gov/forms/2019/2019-3805p-instructions.html
  - https://www.ftb.ca.gov/forms/2025/2025-3805p-instructions.html
  - https://tax.illinois.gov/forms/incometax/currentyear/individual/il-1040-schedule-m-instr.html
  - https://tax.illinois.gov/content/dam/soi/en/web/tax/forms/incometax/documents/currentyear/individual/il-1040-schedule-m.pdf
  - https://www.nj.gov/treasury/taxation/njgrosstax.shtml
  - https://nj.gov/treasury/taxation/individuals/collegededuction.shtml
  - https://revenue-pa.custhelp.com/app/answers/detail/a_id/2321/
  - https://revenue-pa.custhelp.com/app/answers/detail/a_id/2208/
  - https://www.pa.gov/content/dam/copapwp-pagov/en/revenue/documents/taxtypes/pit/documents/pa_able_qa.pdf

### Assumption challenge

- Challenged assumption: **"If IRS newsroom says it, implementation details are settled."**
- Result: **Failed.** Legacy IRS pages can remain stale after statutory change; authority ladder must prioritize enacted law and codified text.

### D (Document updates)

- Updated `docs/FEDERAL_BASELINE.md` with post-2025 rollover status upgrade and IRS lag warning.
- Expanded `docs/STATE_RECAPTURE_WATCHLIST.md` from a 4-state seed to an 8-state working list with confidence notes.
- Updated `docs/KNOWLEDGE_FRONTIER.md` scores and next-run priorities.
- Added new unresolved frontier questions to `docs/QUESTION_BANK.md` (items 26-30).
- Re-ranked `TASKLIST.md` with the highest-value next actions.

### New unknowns added this run

1. Which IRS 2026-cycle forms/publications remain unconformed on rollover sunset wording?
2. Exact NJ-1040 line-level handling for 529->ABLE rollover recapture/add-back (if any).
3. Exact PA-40 line-level handling for 529->ABLE rollover recapture/add-back (if any).
4. Whether Illinois has explicit in-state 529->ABLE anti-recapture language or only inference from general recapture triggers.

### Next run target

Complete the 12-state phase-1 matrix by adding OH/UT/IN/MN and close at least one of the two low-confidence states (NJ or PA) to high confidence with direct form-instruction text.

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
