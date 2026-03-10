# USER_JOURNEY_MAP (Onboarding + Plan Management)

Updated: 2026-03-10

## End-to-end journey

1. **Intent discovery**
   - User goal: fund disability-related expenses via ABLE, often using existing 529 assets.
   - Early confusion: "federally qualified" vs "state tax consequences."

2. **Eligibility + actor mapping**
   - Determine ABLE eligibility, designated beneficiary, and who has legal authority to act.
   - Failure mode: wrong beneficiary/family-member mapping.

3. **Funding path selection**
   - Options: direct rollover, indirect (60-day) rollover, or standard contribution.
   - Failure mode: choosing path without understanding documentation/timing requirements.

4. **Pre-transfer compliance check**
   - Collect required documentation:
     - distributing account earnings/principal statement
     - ownership/beneficiary details
   - Failure mode: submission without earnings breakdown.

5. **Transfer execution**
   - Forms/signatures submitted; external plan coordination begins.
   - Failure mode: signature defects, missing medallion requirements, transfer delays.

6. **Posting + contribution-limit validation**
   - Confirm amount posted and annual cap interactions.
   - Failure mode: over-limit contributions when other contributions already made.

7. **Ongoing plan management**
   - Contributions, distributions, record retention, year-end tax docs.
   - Failure mode: insufficient documentation for qualified-expense substantiation.

## Highest-risk drop-off points

1. **Documentation gap before transfer submission** (very high)
2. **Beneficiary/family-member mismatch** (high)
3. **Opaque transfer status and delays** (high)
4. **State-specific recapture surprise at tax filing** (high)

## Control recommendations

- Add preflight gating at step 4 with hard-stop rules.
- Surface state-confidence badge at step 3 before funds move.
- Provide exception-aware status tracking at step 5.
- Attach citations and confidence to all tax-sensitive explanations.

## Evidence anchors

- Fidelity rollover form: documentation, timing, signer requirements
  - https://www.fidelity.com/bin-public/060_www_fidelity_com/documents/customer-service/able-rollover.pdf
- Texas ABLE rollover form: support-doc requirement and earnings treatment warning
  - https://www.texasable.org/wp-content/uploads/dlm_uploads/2025/02/TxAble_IncomingRolloverForm_2.13.25_Fillable.pdf
- ABLE for ALL direct rollover form: same-beneficiary/family-member certification
  - https://ableforall.com/uploads/ableforall/attachments/cltymmoe43wtu0jlefxjj1v5q-able-for-all-rollover-direct-csp-to-able-form.pdf
