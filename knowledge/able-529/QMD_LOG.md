# QMD Log

## 2026-03-10 Run (11:15 UTC)

### Q (Query)

Depth track:
1. Is the 529->ABLE rollover sunset still operative after 2025, or has it been removed in controlling law?

Breadth track:
2. What high-impact state recapture/conformity signals can be added now for CA, NJ, PA, IL, and OH?

Adversarial challenge:
3. Does older IRS wording ("before January 1, 2026") still control if current statutory text differs?

### M (Memory)

- **M8:** Current IRC §529 text (as presented on U.S. Code House site) includes 529->ABLE rollover operative language without the old sunset phrase, and the amendment notes explicitly state Pub. L. 119-21 §70117(a) struck out "before January 1, 2026."  
  Confidence: **High (Tier 1 statute + editorial amendment note)**  
  Sources:
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim

- **M9:** Historical IRS newsroom guidance still uses temporary-language framing, which is useful context but subordinate to amended statutory text when there is conflict.  
  Confidence: **High (authority hierarchy)**  
  Sources:
  - https://www.irs.gov/newsroom/tax-reform-affects-able-accounts-savers-credit-529-rollovers
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim

- **M10:** State recapture risk remains highly uneven; CA (no 529 deduction baseline) behaves differently from deduction states (NJ/PA/IL/OH), where add-back/recapture analysis remains central and often instruction-driven.  
  Confidence: **Medium (mixed Tier 1 completeness by state)**  
  Sources:
  - https://www.ftb.ca.gov/forms/2025/2025-3805p-instructions.html
  - https://www.nj.gov/treasury/taxation/individuals/collegededuction.shtml
  - https://tax.illinois.gov/forms/incometax/currentyear/individual/il-1040-schedule-m-instr.html
  - https://codes.ohio.gov/ohio-revised-code/section-5747.70
  - https://www.revenue.pa.gov/FormsandPublications/PAPersonalIncomeTaxGuide/Pages/Deductions-and-Credits.aspx

### D (Document updates)

- Added `docs/FEDERAL_529_TO_ABLE_POST_2025_STATUS.md` (advisor-safe permanence memo + authority hierarchy).
- Updated `docs/FEDERAL_BASELINE.md` to mark sunset/permanence ambiguity as resolved to a higher confidence level.
- Expanded `docs/STATE_RECAPTURE_WATCHLIST.md` with CA/NJ/PA/IL/OH risk-screening entries.
- Updated `docs/KNOWLEDGE_FRONTIER.md`, `docs/QUESTION_BANK.md`, and `TASKLIST.md` based on this run's findings.

### Assumption challenge result

- Challenged assumption: **"If IRS newsroom says it, implementation details are settled."**
- Result: **Assumption failed.** Older IRS newsroom language can lag later statutory amendments; statute remains controlling.

### New unknowns generated this run

1. Exactly which IRS forms/instructions still carry pre-2026 sunset phrasing and how should advisors document hierarchy-based override.
2. Pennsylvania line-cited authority for 529->ABLE state qualification and any recapture handling.
3. Ohio administrative guidance clarifying add-back treatment for 529->ABLE specifically.
4. Illinois direct Tier 1 classification of 529->ABLE relative to recapture trigger categories.
5. California explicit FTB sentence-level treatment of 529->ABLE under current conformity year.

### Next run target

Elevate state analysis from risk-screening to line-cited filing-grade positions for at least 3 additional states, while building the first draft of the 529 distribution vs 529->ABLE vs 529->Roth IRA adversarial comparison framework.

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
