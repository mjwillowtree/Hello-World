# QMD Log

## 2026-03-10 Hourly Run (19:01 UTC trigger)

### Q (Query)

Frontier questions generated before execution:

1. Unknown: Are current IRS primary publications (Pub 970 / Pub 907) still using pre-2026 sunset wording for 529->ABLE rollovers?
2. Unknown: Can Indiana be advanced from placeholder to line-level treatment with explicit recapture flow on current forms?
3. Unknown: Does Indiana distinguish 529->ABLE treatment by destination plan (in-state ABLE vs other ABLE plans)?
4. Adversarial challenge: Is the "IRS guidance lag" assumption still valid across all IRS primary materials, or only in selected legacy pages?
5. Product/competition question: Which additional official rollover form provides explicit rejection controls (cap/signer constraints) not yet captured?
6. State-specific question: Can one priority row (IN or UT) be moved to high confidence with Tier-1 source text and return-line mapping?

### Prioritization by ROI

Priority = (User risk impact x Decision value x Reusability x Uncertainty reduction) / Effort

| Task | Score inputs (I,D,R,U,E) | Priority score | Decision |
|---|---|---:|---|
| Verify IRS publication conformity (Pub 970/907) | 5,5,5,4,1 | 500 | Execute |
| Advance Indiana with line-level return mapping | 5,5,4,4,1 | 400 | Execute |
| Add one new competitor workflow datapoint | 4,4,4,3,1 | 192 | Execute |
| Convert findings into ranked requirement/opportunity | 5,4,5,3,1 | 300 | Execute |

### M (Memory)

- **M17:** Current IRS Publication 970 (2025) and Publication 907 (2025) language available this run describes 529->ABLE rollovers without the old "before January 1, 2026" sunset phrase; this narrows (but does not eliminate) guidance-lag risk to legacy pages.  
  Confidence: **High**  
  Sources:
  - https://www.irs.gov/pub/irs-pdf/p970.pdf
  - https://www.irs.gov/pub/irs-pdf/p907.pdf
  - https://www.irs.gov/forms-pubs/about-publication-970

- **M18:** Indiana DOR Information Bulletin 98 (Jan 2026) is destination-sensitive: transfer from Indiana529 to Indiana ABLE is qualified beginning in 2024, while transfer to other ABLE programs is listed as nonqualified for 2024+; recapture reporting flows through IN-CR line 9 to IT-40 Schedule 4 line 3.  
  Confidence: **High**  
  Sources:
  - https://www.in.gov/dor/files/ib98.pdf
  - https://forms.in.gov/Download.aspx?id=16371
  - https://forms.in.gov/Download.aspx?id=16355

- **M19:** PA ABLE incoming direct rollover form explicitly states Section 529 rollover contributions are subject to ABLE contribution/account limits and may be rejected if limits are exceeded; it also flags potential signature-guarantee requirements.  
  Confidence: **High**  
  Source:
  - https://www.paable.gov/pdf/Incoming-Direct-Rollover.pdf

### Assumption challenged + outcome

- Challenged assumption: **"IRS lag is uniform across all IRS primary materials after statutory change."**
- Result: **Failed.** Legacy newsroom pages still contain stale language, but current Pub 970/Pub 907 appear conformed.

### D (Document updates)

- Updated `outputs/HUB.md`
- Updated `outputs/EXEC_SUMMARY.md`
- Updated `outputs/STATE_MATRIX.csv`
- Updated `outputs/STATE_MATRIX.md`
- Updated `outputs/LEGAL_BASELINE.md`
- Updated `outputs/COMPETITOR_LANDSCAPE.md`
- Updated `outputs/PRODUCT_OPPORTUNITIES.md`
- Updated `outputs/USER_JOURNEY_MAP.md`
- Updated `outputs/REQUIREMENTS_BACKLOG.md`
- Updated `outputs/FAQ.md`
- Updated `docs/KNOWLEDGE_FRONTIER.md`
- Updated `docs/QUESTION_BANK.md`
- Updated `TASKLIST.md`

### Hard quality gates check

- One high-impact ambiguity confidence increased: **Yes** (IRS primary-publication conformity status moved from unresolved to high-confidence nuanced view).
- One new/updated state entry with source + line-level form reference: **Yes** (Indiana: IB98 + IN-CR line 9 -> IT-40 Schedule 4 line 3).
- One competition/workflow insight added: **Yes** (PA ABLE explicit limit-rejection and signature-guarantee process signal).
- One product requirement/opportunity added or re-ranked: **Yes** (destination-sensitive routing gate added; opportunity table re-ranked).
- Tier-1 citation ratio for new substantive claims >=70%: **Yes (~92%)**.
- HUB updated with fresh "what changed": **Yes**.
- At least one assumption challenged: **Yes**.

### KPI snapshot

- State matrix completion: **11 / 51** substantive rows
- % high-confidence states: **23.5%** (12/51)
- Domain coverage score (10 domains): **6.6 / 10**
- Tier-1 citation ratio: **~92%**
- Competitor coverage count: **5**
- Validated product opportunities: **6**
- Unresolved critical unknowns: **7**
- Time-to-answer test (top 25): **16 / 25 citation-ready**

### Next run target

1. Close **NJ** or **PA** with DOR/return-instruction line-level tax treatment (not program-form inference).
2. Advance **UT** with directly retrievable Tier-1 line/code evidence from accessible sources.
3. Start transfer-ops quant track: gather any published timing/rejection distributions and map to instrumentation requirements.

## 2026-03-10 Hourly Run (13:34 UTC trigger)

### Q (Query)

Frontier questions generated before research (minimum set met):

1. Unknown: What is the exact quote-ready amendatory + effective-date text confirming post-2025 529->ABLE continuity?
2. Unknown: Does Minnesota's current recapture framework imply 529->ABLE state-benefit recapture risk, and where is the line-level filing flow?
3. Unknown: Which rollover workflows across major providers create preventable documentation failures?
4. Adversarial challenge: If IRS legacy newsroom language conflicts with later-enacted statute, can a product safely rely on the newsroom text?
5. Product/competition question: Which providers require additional signer guarantees or supporting documentation that likely increases abandonment?
6. State-specific question: Can we advance one priority state row (MN/OH/UT/IN queue) with Tier-1 evidence and form-line references?

### Prioritization by ROI

Formula used:

Priority = (User risk impact x Decision value x Reusability x Uncertainty reduction) / Effort

| Task | Score inputs (I,D,R,U,E) | Priority score | Decision |
|---|---|---:|---|
| Lock quote-ready federal authority block | 5,5,5,4,1 | 500 | Execute |
| Advance one state row with form-line mapping (MN) | 5,5,4,4,2 | 200 | Execute |
| Extract competitor workflow constraints from official forms | 4,4,4,4,2 | 128 | Execute |
| Build one new requirement/opportunity from evidence | 5,4,5,3,2 | 150 | Execute |

### M (Memory)

- **M11:** Pub. L. 119-21 Sec. 70117 contains explicit amendatory text removing the 529->ABLE sunset phrase and an effective-date clause for taxable years beginning after 2025, suitable for advisor quote blocks.  
  Confidence: **High**  
  Sources:
  - https://www.govinfo.gov/content/pkg/PLAW-119publ21/html/PLAW-119publ21.htm
  - https://www.congress.gov/119/plaws/publ21/PLAW-119publ21.pdf
  - https://uscode.house.gov/view.xhtml?req=granuleid:USC-prelim-title26-section529&num=0&edition=prelim

- **M12:** Minnesota DOR recapture materials plus TY2025 Schedule M1529 create a line-level workflow where nonqualified 529 distributions trigger recapture computation and flow to Form M1 line 14; explicit ABLE carveout text remains unconfirmed.  
  Confidence: **Medium-High**  
  Sources:
  - https://www.revenue.state.mn.us/education-savings-account-recapture-tax
  - https://www.revenue.state.mn.us/education-savings-account-contribution-subtraction
  - https://www.revenue.state.mn.us/sites/default/files/2025-10/m1529-25-grid.pdf

- **M13:** Across multiple official plan forms, missing earnings/contribution support documentation is a repeat operational failure mode that can cause full rollover amount to be treated as earnings.  
  Confidence: **High**  
  Sources:
  - https://www.fidelity.com/bin-public/060_www_fidelity_com/documents/customer-service/able-rollover.pdf
  - https://www.texasable.org/wp-content/uploads/dlm_uploads/2025/02/TxAble_IncomingRolloverForm_2.13.25_Fillable.pdf
  - https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf

### Assumption challenged + outcome

- Challenged assumption: **"If federal rollover legality is settled, operational errors are mostly solved."**
- Result: **Failed.** Official provider forms show documentation and signer workflow friction can still create nonqualified-risk outcomes even when legal eligibility exists.

### D (Document updates)

- Created `outputs/HUB.md`
- Created `outputs/EXEC_SUMMARY.md`
- Created `outputs/STATE_MATRIX.csv`
- Created `outputs/STATE_MATRIX.md`
- Created `outputs/LEGAL_BASELINE.md`
- Created `outputs/COMPETITOR_LANDSCAPE.md`
- Created `outputs/PRODUCT_OPPORTUNITIES.md`
- Created `outputs/USER_JOURNEY_MAP.md`
- Created `outputs/REQUIREMENTS_BACKLOG.md`
- Created `outputs/FAQ.md`

### Hard quality gates check

- One high-impact ambiguity confidence increased: **Yes** (federal quote-ready authority block upgraded to High).
- One new/updated state entry with source + line-level form reference: **Yes** (Minnesota, Schedule M1529 lines 7-15 -> Form M1 line 14).
- One competition/workflow insight added: **Yes** (cross-provider documentation failure mode).
- One product requirement/opportunity added or re-ranked: **Yes** (Rollover Evidence Pack + Preflight Validator to rank #1).
- Tier-1 citation ratio for new substantive claims >=70%: **Yes (~86%)**.
- HUB updated with fresh "what changed": **Yes**.
- At least one assumption challenged: **Yes**.

### KPI snapshot

- State matrix completion: **9 / 51** substantive rows
- % high-confidence states: **19.6%** (10/51)
- Domain coverage score (10 domains): **6.1 / 10**
- Tier-1 citation ratio: **~86%**
- Competitor coverage count: **3**
- Validated product opportunities: **5**
- Unresolved critical unknowns: **8**
- Time-to-answer test (top 25): **14 / 25 citation-ready**

### Next run target

1. Resolve one of NJ or PA to line-level high-confidence treatment.
2. Add one new priority state (OH or UT) with Tier-1 form-line mapping.
3. Add one more competitor admin workflow datapoint and update conversion-risk controls in requirements backlog.

## 2026-03-10 Hourly Run (14:00 UTC trigger)

### Q (Query)

Frontier questions generated before execution:

1. In Ohio, is 529 recapture/add-back triggered for any nonqualified 1099-Q amount, or only where prior Ohio deduction/credit history exists?
2. Which exact Ohio form lines should product UX reference for 529/STABLE deductions and nonqualified additions?
3. What operational handoff constraints in real rollover forms most predict transfer failures (missing metadata, notarization, cap overrun)?
4. Adversarial challenge: If federal law is updated but IRS legacy newsroom text is stale, can product safely rely on newsroom wording?
5. Product/competition: Which competitor workflow constraints should be built into preflight UX first to reduce avoidable rejection?
6. State-specific: Can Ohio be advanced to high confidence with line-level authority this run?

### M (Memory)

- **M14:** Ohio 2024 Schedule of Adjustments explicitly separates 529 nonqualified addition (line 4) from STABLE deduction (line 20) and 529 contribution deduction (line 36).  
  Confidence: **High**  
  Sources:
  - https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/scheduleofadjustments.pdf
  - https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/it1040-booklet.pdf

- **M15:** Ohio line-4 instructions tie addition to nonqualified 529 distributions and prior Ohio deduction/credit history; this invalidates a blanket recapture assumption.  
  Confidence: **High**  
  Source:
  - https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/it1040-booklet.pdf

- **M16:** ABLE for ALL direct rollover operations require destination account pre-existence, source-plan metadata, relationship certification, annual-limit compliance, and possible notarization.  
  Confidence: **High**  
  Source:
  - https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf

### Assumption challenged + outcome

- Challenged assumption: **"Any nonqualified 529 distribution always triggers state recapture in the same way."**
- Result: **Failed.** Ohio instructions condition line-4 addition on defined criteria including prior deduction/credit linkage.

### KPI snapshot

- State matrix completion: **10 / 51** substantive rows
- % high-confidence states: **21.6%** (11/51)
- Tier-1 citation ratio: **~85%**
- Competitor coverage count: **4**

### Next run target

1. Resolve NJ or PA with explicit line-level return instruction treatment.
2. Advance UT or IN using Tier-1 form/code references.
3. Expand workflow lane with transfer SLA/rejection-code evidence.

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
