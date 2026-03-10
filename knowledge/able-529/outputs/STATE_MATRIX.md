# State Matrix (50 States + DC)

Updated: 2026-03-10

Canonical machine-readable matrix: [STATE_MATRIX.csv](./STATE_MATRIX.csv)

## This run's state advancement (quality gate)

### Ohio (advanced to High confidence)

Evidence locked from official Ohio sources:

1. **Form line mapping** (Schedule of Adjustments):
   - Line 4 (addition): "529 plan funds used for non-qualified expenses"
   - Line 20 (deduction): STABLE contributions
   - Line 36 (deduction): 529 contributions
   Source: https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/scheduleofadjustments.pdf

2. **Instruction trigger detail** (line-level):
   - Line 4 addition ties to nonqualified 529 distributions and prior Ohio deduction history.
   - Line 20 and line 36 define deduction/carryforward mechanics for STABLE and 529 contributions.
   Source: https://dam.assets.ohio.gov/image/upload/tax.ohio.gov/forms/ohio_individual/individual/2024/it1040-booklet.pdf

## Coverage tracker (all jurisdictions)

| Jurisdiction | Status | Confidence |
|---|---|---|
| Alabama | Not started | Low |
| Alaska | Not started (no state income tax context) | Medium |
| Arizona | Not started | Low |
| Arkansas | Not started | Low |
| California | Partial | High |
| Colorado | Partial | Low |
| Connecticut | Not started | Low |
| Delaware | Not started | Low |
| District of Columbia | Not started | Low |
| Florida | Not started (no state income tax context) | Medium |
| Georgia | Not started | Low |
| Hawaii | Not started | Low |
| Idaho | Not started | Low |
| Illinois | Partial | High |
| Indiana | Not started | Low |
| Iowa | Not started | Low |
| Kansas | Not started | Low |
| Kentucky | Not started | Low |
| Louisiana | Not started | Low |
| Maine | Not started | Low |
| Maryland | Not started | Low |
| Massachusetts | Not started | Low |
| Michigan | Not started | Low |
| Minnesota | Not started | Low |
| Mississippi | Not started | Low |
| Missouri | Not started | Low |
| Montana | Not started | Low |
| Nebraska | Not started | Low |
| Nevada | Not started (no state income tax context) | Medium |
| New Hampshire | Not started (no broad wage income tax context) | Medium |
| New Jersey | Partial | Medium |
| New Mexico | Not started | Low |
| New York | Partial | Low |
| North Carolina | Not started | Low |
| North Dakota | Not started | Low |
| Ohio | Complete | High |
| Oklahoma | Not started | Low |
| Oregon | Partial | Low |
| Pennsylvania | Partial | Medium-Low |
| Rhode Island | Not started | Low |
| South Carolina | Not started | Low |
| South Dakota | Not started (no state income tax context) | Medium |
| Tennessee | Not started (no broad wage income tax context) | Medium |
| Texas | Not started (no state income tax context) | Medium |
| Utah | Not started | Low |
| Vermont | Not started | Low |
| Virginia | Partial | Low |
| Washington | Not started (no state income tax context) | Medium |
| West Virginia | Not started | Low |
| Wisconsin | Not started | Low |
| Wyoming | Not started (no state income tax context) | Medium |

## Current completed/partial evidence rows

| State | Treatment snapshot | Recapture/add-back signal | Conformity/effective note | Form line reference | Confidence | Primary sources |
|---|---|---|---|---|---|---|
| OH | Conditional (explicit line logic) | Line 4 addition for specified nonqualified 529 distributions tied to prior Ohio deduction history | 2024 booklet+form verified | Schedule of Adjustments lines 4, 20, 36 | High | Ohio IT 1040 booklet + Schedule of Adjustments |
| CA | 2019+ qualified directional | Additional-tax framework for nonqualified events | 2018 nonconformity then 2019+ conformity signal | FTB 3805P Part II | High | 2018/2019/2025 FTB 3805P instructions |
| IL | Conditional | Explicit recapture triggers for out-of-state transfer/nonqualified withdrawal | Annual Schedule M controls | Schedule M lines 7 and 9 | High | IL Schedule M instructions + form |
| NJ | Likely qualified, unresolved line text | Recapture for this pathway not fully locked | TY2022+ deduction context visible | NJ-1040 line mapping pending | Medium | NJ taxation pages |
| PA | Partial unclear | Line-level treatment not yet locked | Needs current PA-40 extract | PA-40 line mapping pending | Medium-Low | PA DOR FAQ + PA ABLE Q&A |
| OR | Watchlist only | Rule text references recapture mechanics | Needs current form-level extraction | Pending | Low | OAR 150-315-0065 |
| CO | Watchlist only | DOR guidance signals addition/recapture concepts | Needs line-level extract | Pending | Low | Colorado DOR ABLE topic page |
| VA | Watchlist only | Plan guidance indicates recapture context | Needs DOR authority text | Pending | Low | Virginia529 plan guidance |
| NY | Watchlist only | General recapture context; needs direct authority for 529->ABLE path | Pending | Pending | Low | NY 529 plan page |
