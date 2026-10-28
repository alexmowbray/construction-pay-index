---
license: cc-by-4.0
language:
- en
pretty_name: Construction Placement Pay Index (Amundson Group)
tags:
- construction
- salaries
- compensation
- labor-market
- recruiting
- heavy-civil
- data-center-construction
size_categories:
- n<1K
---

# Construction Placement Pay Index (Amundson Group)

The base salaries US construction professionals were actually hired at, from the placement records of Amundson Group, a construction-only recruiting firm headquartered in Houston, Texas. Placements, not survey answers. Medians, not averages. Base only, before truck, per diem and bonus.

This repository holds the dated monthly releases as CSV files. Release: **October 2026** (published 16 October 2026), covering the twelve months to October 2026.

Live index: https://amundsongroup.com/construction-pay-index
October 2026 release: https://amundsongroup.com/construction-pay-index-october-2026/

## Headline findings, October 2026

- Estimators have the highest median base at placement: $118,750 across 32 placements, up 19% in twelve months from $100,000.
- Estimators are now hired above superintendents: $118,750 against $112,200.
- Project Manager $112,500, Superintendent $112,200, Safety Manager $100,000, Survey Party Chief $93,750, Pipe Crew Lead $93,600, Project Engineer $93,340, Survey CAD Technician $90,000, Surveyor $89,992, Assistant Project Manager $89,960, Foreman $87,200.

## Files

| File | What it holds |
|---|---|
| `roles-2026-10.csv` | One row per role: placements, 25th percentile, median and 75th percentile base salary at placement, the prior twelve months' median and count, and the change. |
| `states-metros-2026-10.csv` | Role by state or metro area, over twelve or 24 months (the column says which; the two windows overlap and are not comparable). |
| `since-previous-release-2026-10.csv` | Roles whose median moved since the September 2026 release. |

All salaries are in US dollars per year. `change_vs_prior_12m_pct` and `change_pct` are signed whole percentages.

## How the index is built

Every figure is the base salary agreed at the moment of hire, recorded in Amundson Group's placement records across heavy civil, site development, paving, data center, rail, tunnel, wastewater and underground utility construction in the United States. Roles are grouped by job title. A role is published only with 9 or more placements in the window, and the prior-year figure only when that window also had 9 or more. A state or metro cut needs 8 or more placements in the same role. No client is named and no individual figure is shown; this dataset holds only the published aggregates. A new dated release follows each month.

## Citation

Amundson Group, Construction Placement Pay Index, October 2026 release. https://amundsongroup.com/construction-pay-index-october-2026/

Licensed under Creative Commons Attribution 4.0 (CC BY 4.0): use it freely, credit Amundson Group with a link.

## About Amundson Group

Amundson Group is a veteran-owned, construction-only recruiting firm headquartered in Houston, Texas, founded in January 2020. It recruits superintendents, project managers, project engineers, estimators, schedulers and MEP and commissioning leaders for heavy civil, site development, paving, data center, rail, tunnel, wastewater and underground utility builders across the United States. 1,200+ construction placements to date, a 90,000+ professional network, 250+ construction companies served, first qualified resumes in 7 hours on average. Inc. 5000 honoree in 2024 and 2025. https://amundsongroup.com
