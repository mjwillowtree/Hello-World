# State Recapture Watchlist (Phase 1 Matrix Seed)

Updated: 2026-03-10

Purpose: build an evidence-graded 50-state 529->ABLE recapture/add-back matrix.

Legend:
- **Explicit:** direct state authority text classifying 529->ABLE treatment.
- **Proxy:** no explicit 529->ABLE text found; only general nonqualified distribution rules or plan-level warnings.

## Current matrix seed (citation-first)

| State | In-state 529 deduction/credit | 529->ABLE state treatment signal | Filing reference | Evidence tier | Confidence |
|---|---|---|---|---|---|
| CA | No state deduction generally indicated | No recapture regime identified (likely low recapture risk because no deduction) | Need FTB line-level citation | Proxy | Medium |
| NY | Deduction available (up to plan limits) | NY 529 plan tax update states rollovers to NY ABLE are treated as nonqualified for NY law | IT-225 addition/subtraction codes (line-level ABLE wording still unpinned) | Explicit (plan-admin); partial tax-form support | Medium-High |
| NJ | Deduction available subject to income limits | Nonqualified distribution taxability/recapture logic exists; explicit 529->ABLE classification not found | NJ-1040 instructions line 37a for deduction; recapture line still unpinned | Proxy | Medium |
| PA | Deduction available; out-of-state 529 support documented | Non-educational 529 distributions are reported on PA schedules; explicit 529->ABLE classification not found | PA-40 Schedule A line 13 (non-educational distributions) | Proxy | Medium-Low |
| OR | Rule text references recapture mechanics in 529/ABLE context | Direct rule signal exists | Form/line extraction pending | Explicit (reg text) | Medium |
| CO | DOR guidance indicates addition/recapture concepts for 529/ABLE treatment | Rollover-specific treatment still needs form-level pinning | Form/line extraction pending | Proxy-to-Explicit (pending) | Medium-Low |
| VA | Plan guidance warns on deduction recapture in transfer context | Need direct VA tax authority text for final position | Form/line extraction pending | Proxy | Low-Medium |

## Sources captured in this phase

- California:
  - https://www.scholarshare529.com/resources/faq/
  - https://www.scholarshare529.com/media/hzfasdpr/ca_plan_description.pdf
  - https://leginfo.legislature.ca.gov/faces/codes_displaySection.xhtml?lawCode=RTC&sectionNum=17140
- New York:
  - https://www.nysaves.org/home/why-ny-529-direct-plan/tax-benefits.html
  - https://www.nysaves.org/home/federal-tax-update.html
  - https://www.tax.ny.gov/forms/current-forms/it/it225i.htm
  - https://www.tax.ny.gov/pdf/memos/income/m18-6i.pdf
- New Jersey:
  - https://www.nj.gov/treasury/taxation/individuals/collegededuction.shtml
  - https://www.nj.gov/njbonds/treasury/taxation/pdf/current/1040i.pdf
  - https://www.nj.gov/njbonds/treasury/taxation/new2022.shtml
  - https://www.nj.gov/treasury/taxation/njgrosstax.shtml
- Pennsylvania:
  - https://www.revenue.pa.gov/FormsandPublications/PAPersonalIncomeTaxGuide/Pages/Deductions-and-Credits.aspx
  - https://revenue-pa.custhelp.com/app/answers/detail/a_id/2321/~/can-i-deduct-contributions-made-to-a-college-tuition-program-of-another-state%3F
  - https://www.pa.gov/content/dam/copapwp-pagov/en/revenue/documents/formsandpublications/formsforindividuals/pit/documents/2024/2024_pa-40in.pdf
  - https://www.pa.gov/content/dam/copapwp-pagov/en/revenue/documents/formsandpublications/formsforindividuals/pit/documents/2024/2024_pa-40a.pdf
  - https://revenue-pa.custhelp.com/app/answers/detail/a_id/2517/~/where-should-a-distribution-from-an-irc-section-529-college-and-career-saving
- Prior-seed states:
  - https://oregon.public.law/rules/oar_150-315-0065
  - https://tax.colorado.gov/income-tax-topics-able-contribution-subtraction
  - https://www.virginia529.com/blog/transfer-invest529-funds-to-ablenow

## Immediate next expansion targets

1. Pin NY/NJ/PA form-line wording with direct tax-authority text for 529->ABLE (or document absence explicitly).
2. Add Illinois and Ohio with deduction + recapture mechanics.
3. Add Utah, Indiana, and Minnesota with conformity-year notes.
