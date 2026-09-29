# Gunnison County Assessor Website Audit

**Live dashboard:** https://eesterlein.github.io/gunnison-assessor-audit/

## Why this exists

I'm looking at reorganizing our office's website, and as part of my own **_independent_** research
into that project, I asked three separate AI systems — ChatGPT, Gemini, and Claude — to each
independently run a deep-research review comparing the Gunnison County Assessor's website to
other county assessor websites across Colorado, and to suggest concrete improvements. Each was
given the same rubric and the same three property-owner tasks (find a record, find the appeal
deadline, find an exemption/correction path) with no visibility into the others' work.

This is exploratory research I ran on my own time, not an official county work product, a legal
opinion, or a county-commissioned audit.

## What three independent reviews turned up

- Total scores came back **60–78 out of 100** (grades D–C) — a wide enough spread on the same
  rubric that the disagreement is itself informative about where the site is genuinely ambiguous.
- All three, working independently, converged on the same root problem from different angles:
  the site's **data tools are solid**, but its **published deadlines and forms have drifted out
  of date**.
- One review caught something the other two missed entirely: Colorado's **SB26-046** moved the
  real-property protest deadline from June 8 to June 1 (effective Aug 12, 2026), and the site
  still shows the old date — a legal-currency issue that's now flagged at the top of the
  dashboard.
- Gemini benchmarked 24 of Colorado's 64 counties on the identical rubric; Gunnison ranks
  **12th of 24** — squarely median, well behind counties with a working online appeal portal.
- The three reviews were merged into one **10-item, priority-ranked action plan** (2 critical,
  3 serious, 5 to monitor), so overlapping advice from different reviewers collapses into a
  single line item instead of being repeated three times.

## The time-to-insight was the real surprise

Each review took roughly **5 to 15 minutes** to run. For well under an hour of total AI time, the
process surfaced a specific, dated, statutory compliance gap (the SB26-046 deadline), a ranked
list of concrete fixes with effort estimates, and named working examples from other Colorado
counties to model each fix on. That's a meaningfully fast, low-cost way to get a second (and
third, and fourth) opinion before committing real staff time to a website reorganization.

## Who this is for

The rubric and every recommendation are written around the **property owner** — the person
actually trying to find a record, understand a value change, file an appeal, or apply for an
exemption on this site. Making that experience faster and less confusing is the whole point of
the reorganization project this research is feeding into.

## What's in this repo

- `index.html` — the dashboard (scores, category breakdown, statewide comparison, the
  consolidated action plan, and the full original research prompt sent to all three AIs).

---
*Independent research project — not an official Gunnison County publication. The statutory
deadline claim above should be confirmed with county counsel before any page copy changes.*
