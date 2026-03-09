# ABLE/529 Knowledge System (QMD+)

This directory tracks a long-running effort to become expert on ABLE (IRC 529A) and 529 plan interactions.

The objective is not "good notes." The objective is **full-spectrum mastery**:
- accurate legal/tax mechanics,
- operational edge cases,
- state-by-state implementation,
- planning tradeoffs across account types,
- ability to answer hard adversarial questions with sources.

## QMD method

- **Q (Query):** a concrete, high-value research question.
- **M (Memory):** short, reusable facts learned (with confidence + source tier).
- **D (Document):** durable notes/checklists that future runs can reuse.

## Curiosity engine (mandatory every hourly run, <= 30 min)

1. **Read control files first**
   - `TASKLIST.md`
   - `docs/KNOWLEDGE_FRONTIER.md`
   - `docs/QUESTION_BANK.md`
   - unresolved items in `docs/FEDERAL_BASELINE.md`

2. **Generate frontier questions before researching**
   - At least 3 "what don't I know?" questions.
   - At least 1 adversarial question that could break existing assumptions.
   - At least 1 breadth question outside the current in-progress lane.

3. **Run two tracks**
   - **Depth track:** resolve one high-impact ambiguity to a higher confidence tier.
   - **Breadth track:** add one new topic area, jurisdiction, or edge case not recently covered.

4. **Log QMD output**
   - Add a dated run section to `QMD_LOG.md`.
   - Include confidence labels and source URLs.
   - Record at least one "surprising/contrarian" finding if discovered.

5. **Evolve the system**
   - Update `docs/KNOWLEDGE_FRONTIER.md` confidence scores.
   - Expand `docs/QUESTION_BANK.md` with newly discovered unknowns.
   - Re-rank `TASKLIST.md` based on expected value of information.

6. **Quality gate before ending run**
   - If no new unknowns were identified, the run is incomplete.
   - If no assumption was challenged, the run is incomplete.
   - If only one topic lane was touched repeatedly, deprioritize it next run unless mission-critical.

## Source quality tiers

1. **Tier 1:** statute, regulations, IRS/SSA/Treasury, official state revenue/plan docs.
2. **Tier 2:** ABLE National Resource Center and major plan administrators.
3. **Tier 3:** advisor blogs/secondary summaries (verification targets, not final authority).

## Completion standard

Knowledge is never treated as complete unless:
- all major federal mechanics are high-confidence and citation-backed,
- all 50 states + DC recapture/conformity treatment is mapped and current,
- major planning comparisons (529, ABLE, Roth rollover, SSI/Medicaid interactions) are decision-ready,
- common and adversarial questions can be answered with controlling sources quickly.
