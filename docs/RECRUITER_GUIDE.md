# Recruiter evidence guide — Cyclistic Rider Behaviour Analysis

[**Full case study on Mulero Analytics**](https://tosinmulero.github.io/data-analytics-portfolio/case-studies/cyclistic-rider-behaviour-analysis.html) · [Repository README](../README.md) · [Main portfolio](https://tosinmulero.github.io/data-analytics-portfolio/projects.html)

> **Data provenance:** Twelve public bike-share monthly trip files (July 2025–June 2026); trip-level behaviour, not individual conversion outcomes.

## The question

What riding behaviours distinguish annual bike-share members from casual riders, and which membership-conversion hypotheses could be investigated?

## Technical approach

- Consolidate files and inspect duplicates, timestamps, incomplete fields and duration anomalies.
- Derive rider-type, hour, day, month, season and weekend aggregates.
- Create comparative Power BI behaviour reporting and testable campaign hypotheses.

## Documented results to review

- Approximately 5.93 million trips analysed across the twelve-month window.
- Members represent 64.36% of rides; casual users represent 35.64%.
- Casual rides last 18.57 minutes on average versus 12.06 minutes for member rides.

## Evidence map

| Review item | Source | What it supports |
|---|---|---|
| Recruiter summary | [Open](../docs/RECRUITER_PROJECT_SUMMARY.md) | Business purpose and demonstrated skills |
| Technical architecture | [Open](../docs/TECHNICAL_ARCHITECTURE.md) | Data preparation and reporting process |
| Power BI dashboard | [Open](../images/Cyclist_Powerbi_Dashboard.png) | Member versus casual ridership |
| Rider aggregation | [Open](../outputs/rider_summary.csv) | Supporting grouped outputs |

## Reproducibility and limitations

Follow the repository README for cleaning, notebooks and report construction. Usage patterns do not establish membership purchase intent; conversion recommendations should be treated as hypotheses requiring tests.

The repository README and linked source files remain the primary technical record. Figures in this guide summarise documented project artefacts, not independently verified third-party business outcomes.

## Suggested review path

1. Start with the [standalone case study](https://tosinmulero.github.io/data-analytics-portfolio/case-studies/cyclistic-rider-behaviour-analysis.html) for an accessible summary.
2. Inspect the linked screenshots and technical documentation.
3. Check the README and source files for workflow, caveats and reproduction guidance.
4. Inspect analytical code or quality workflows as required.

---

*Independent portfolio work by Oluwatosin Mulero. Project evidence is maintained in this repository.*
