# QMD Log

## 2026-03-10 Hourly Run

### Q (Query)

Frontier questions generated before research:

1. **Depth:** Did enacted law after 2025 actually remove the 529->ABLE sunset, or does any controlling authority still preserve a cutoff?
2. **Depth/adversarial:** If statute and IRS sub-regulatory artifacts conflict, which authority should govern advisor recommendations in 2026?
3. **Breadth:** What do Utah, Indiana, and Minnesota actually do on 529->ABLE recapture/add-back, and where do form-line instructions diverge from higher-level guidance?
4. **Breadth/adversarial:** Could a taxpayer be technically correct under statute but still face filing friction because state forms and program operations lag?

### M (Memory)

- **M8:** The federal "before January 1, 2026" sunset for 529->ABLE rollovers was removed by Pub. L. 119-21 sec. 70117(a), with an effective-date rule for taxable years beginning after 2025-12-31.  
  Confidence: **High**  
  Sources:
  - https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim

- **M9:** Older IRS artifacts (Notice 2018-58, pre-amendment form instructions/publications, preamble language) can remain operationally useful but legally stale after statutory amendments.  
  Confidence: **High**  
  Sources:
  - https://www.irs.gov/pub/irs-drop/n-18-58.pdf
  - https://www.irs.gov/pub/irs-drop/td-9923.pdf
  - https://www.irs.gov/pub/irs-pdf/p907.pdf
  - https://www.irs.gov/pub/irs-pdf/i1099q.pdf
  - https://www.irs.gov/pub/irs-pdf/i1099qa.pdf

- **M10:** Utah recapture/addback signaling is primarily statute cross-reference based (IRC section 529(c)/530(d) exception structure) rather than explicit ABLE naming.  
  Confidence: **Medium**  
  Sources:
  - https://incometax.utah.gov/additions/my529-addback
  - https://le.utah.gov/xcode/Title59/Chapter10/C59-10-S114_2025101420251206.html

- **M11:** Indiana currently shows a guidance-layer conflict: Bulletin 98 (newer) provides nuanced ABLE treatment, while Schedule IN-CR instruction text remains broader and potentially inconsistent.  
  Confidence: **Medium**  
  Sources:
  - https://www.in.gov/dor/files/ib98.pdf
  - https://forms.in.gov/Download.aspx?id=16371

- **M12:** Minnesota recapture framework is explicit for section 529 qualified vs nonqualified uses, but ABLE-specific treatment is mostly inferential (not clearly named in primary authority reviewed this run).  
  Confidence: **Medium**  
  Sources:
  - https://www.revisor.mn.gov/statutes/cite/290.06/pdf
  - https://www.revisor.mn.gov/statutes/cite/290.0684/pdf
  - https://www.revisor.mn.gov/statutes/cite/290.0132/pdf
  - https://www.revenue.state.mn.us/education-savings-account-recapture-tax
  - https://www.revenue.state.mn.us/sites/default/files/2024-12/m1529-24.pdf

### D (Document updates)

- Updated `docs/FEDERAL_BASELINE.md` to resolve the post-2025 sunset ambiguity with controlling authority and effective-date language.
- Expanded `docs/STATE_RECAPTURE_WATCHLIST.md` with UT, IN, and MN entries plus confidence annotations.
- Re-ranked priorities in `TASKLIST.md` (state matrix + implementation-lag tracker now top in-progress items).
- Updated `docs/KNOWLEDGE_FRONTIER.md` scores and recorded assumption stress-test outcomes.
- Added new unknowns to `docs/QUESTION_BANK.md` focused on guidance conflicts and lag-risk operations.

### Assumption challenge (mandatory)

- Challenged assumption: **"If IRS/plan guidance says it, implementation details are settled."**
- Result: **Failed.** Statute moved first; operational guidance can lag materially.
- Practical implication: maintain explicit authority ladder and conservative fallback script for stale forms/guidance.

### Surprising/contrarian finding

- Indiana currently appears to have internally inconsistent taxpayer-facing artifacts (newer bulletin vs form instruction wording), which means "official source" is not always singular and requires conflict triage.

### Next run target

1. Build a formal authority hierarchy memo with citation templates for advisor use when statute and forms diverge.
2. Add five more Phase-1 states (CA, NJ, PA, IL, OH) with form-line citations.
3. Start adversarial comparison model: 529 distribution vs 529->ABLE vs 529->Roth IRA under constrained annual caps.

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
