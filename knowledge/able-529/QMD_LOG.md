# QMD Log

## 2026-03-10 Hourly Run

### Q (Query)

Depth track:
1. Is the federal 529->ABLE rollover still sunset-limited, or is it now permanent after 2025 legislation?

Breadth track:
2. What does current state evidence suggest for recapture/add-back risk in CA, NY, NJ, PA, IL, and OH?

Adversarial check:
3. If statute and older IRS webpages conflict, which authority controls for advisor-safe guidance?

### M (Memory)

- **M8:** The sunset phrase "before January 1, 2026" was struck from §529(c)(3)(C)(i)(III) by P.L. 119-21 §70117(a), and the change applies to taxable years beginning after Dec. 31, 2025.  
  Confidence: **High**  
  Sources:
  - https://uscode.house.gov/view.xhtml?req=(title:26%20section:529%20edition:prelim)
  - https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm

- **M9 (Contrarian):** Older IRS newsroom language can remain sunset-era even after statutory text changes; statute + enacted law notes must control when sources conflict.  
  Confidence: **High**  
  Sources:
  - https://www.irs.gov/newsroom/tax-reform-affects-able-accounts-savers-credit-529-rollovers
  - https://uscode.house.gov/view.xhtml?req=(title:26%20section:529%20edition:prelim)

- **M10:** Early 6-state state-tax evidence is heterogeneous: PA currently shows strong conformity signal, while NY/NJ remain low-confidence for ABLE-specific recapture handling, and IL/OH show recapture-risk framing absent explicit carveouts.  
  Confidence: **Medium**  
  Sources:
  - https://www.pa.gov/content/dam/copapwp-pagov/en/revenue/documents/taxlawpoliciesbulletinsnotices/taxsummaries/documents/2024_tax_summary_aug.pdf
  - https://tax.ny.gov/forms/current-forms/it/it225i.htm
  - https://www.nj.gov/treasury/taxation/njgrosstax.shtml
  - https://tax.illinois.gov/content/dam/soi/en/web/tax/forms/incometax/documents/currentyear/individual/il-1040-schedule-m.pdf
  - https://tax.ohio.gov/faq-529

### D (Document updates)

- Updated `docs/FEDERAL_BASELINE.md` to close the post-2025 rollover sunset ambiguity and capture effective-date language.
- Expanded `docs/STATE_RECAPTURE_WATCHLIST.md` into a 6-state evidence matrix v0.1 (CA/NY/NJ/PA/IL/OH) with confidence and caveats.
- Updated `docs/KNOWLEDGE_FRONTIER.md` scores and recorded this run's failed assumption test.
- Expanded `docs/QUESTION_BANK.md` with new unknowns on IRS lag and low-confidence state authority hierarchy.
- Re-ranked `TASKLIST.md` to prioritize IRS artifact reconciliation and state matrix confidence upgrades.

### Assumption challenge

- Challenged assumption: "If IRS newsroom says it, implementation details are settled."
- Result: **Failed.** Current Code + public law notes indicate permanence, while legacy IRS pages still carry historical sunset framing.

### New unknowns created this run

1. Which IRS forms/instructions/publications still contain pre-2026 rollover sunset phrasing?
2. What exact advisor documentation should show authority hierarchy when IRS sub-regulatory guidance lags statute?
3. In NY and NJ, what is the highest-authority ABLE rollover recapture source (statute vs regulation vs form instruction)?

### Next run target

Produce an "authority ladder memo" (statute -> regulations -> IRS forms/publications -> plan materials) and raise NY/NJ from low-confidence to medium+ with primary state tax authority citations.

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
