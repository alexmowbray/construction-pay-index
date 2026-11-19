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
configs:
- config_name: roles
  data_files: "roles-*.csv"
  default: true
- config_name: states_metros
  data_files: "states-metros-*.csv"
- config_name: since_previous_release
  data_files: "since-previous-release-*.csv"
---

# Construction Placement Pay Index (Amundson Group)

The base salaries US construction professionals were actually hired at, from the placement records of Amundson Group, a construction-only recruiting firm headquartered in Houston, Texas. Placements, not survey answers. Medians, not averages. Base only, before truck, per diem and bonus.

This repository holds the dated monthly releases as CSV files. Latest release: **November 2026** (published 15 November 2026), covering the twelve months to November 2026. Earlier release: October 2026 (published 16 October 2026).

Live index: https://amundsongroup.com/construction-pay-index/

November 2026 release: https://amundsongroup.com/construction-pay-index-november-2026/

October 2026 release: https://amundsongroup.com/construction-pay-index-october-2026/

## Headline findings, November 2026

- Project Managers have the highest median base at placement: $125,000, up 4% in twelve months from $120,008.
- Estimators are up 15% in twelve months, from $102,500 to $117,500, and are now hired above superintendents: $117,500 against $110,000.
- Foreman pay is flat year on year at $88,400.
- Project Manager $125,000, Estimator $117,500, Superintendent $110,000, Safety Manager $105,000, Survey Party Chief $93,750, Project Engineer $93,340, Survey CAD Technician $90,000, Surveyor $89,992, Foreman $88,400, Assistant Project Manager $85,280.
- Since the October 2026 release: Project Manager up 11%, Safety Manager up 5%, Assistant Project Manager down 5%, Superintendent down 2%.

## Files

| File | What it holds |
|---|---|
| `roles-YYYY-MM.csv` | One row per role: 25th percentile, median and 75th percentile base salary at placement over the twelve months to the release month, the prior twelve months' median and the change. |
| `states-metros-YYYY-MM.csv` | Median base salary at placement by role in a state or metro area, over twelve or 24 months (the column says which; the two windows overlap and are not comparable). |
| `since-previous-release-YYYY-MM.csv` | Roles whose median moved since the previous monthly release. |

One file of each kind per release. All salaries are in US dollars per year. `change_vs_prior_12m_pct` and `change_pct` are signed whole percentages. An empty prior figure means the prior window did not hold enough placements for a steady median.

## How the index is built

Every figure is the base salary agreed at the moment of hire, recorded in Amundson Group's own placement records across heavy civil, site development, paving, data center, rail, tunnel, wastewater and underground utility construction in the United States. Roles are grouped by job title. A role, a state or a metro appears only when its window holds enough placements for a steady median, and the prior-year figure only when that window did too, so a role can sit out a release (Pipe Crew Lead sits out November 2026). No client is named and no individual figure is shown; this dataset holds only the published aggregates. A new dated release follows each month.

## Citation

Amundson Group, Construction Placement Pay Index, November 2026 release. https://amundsongroup.com/construction-pay-index-november-2026/

Licensed under Creative Commons Attribution 4.0 (CC BY 4.0): use it freely, credit Amundson Group with a link.

## About Amundson Group

Amundson Group is a veteran-owned, construction-only recruiting firm headquartered in Houston, Texas, founded in January 2020. It recruits superintendents, project managers, project engineers, estimators, schedulers and MEP and commissioning leaders for heavy civil, site development, paving, data center, rail, tunnel, wastewater and underground utility builders across the United States. 1,200+ construction placements to date, a 90,000+ professional network, 250+ construction companies served, first qualified resumes in 7 hours on average. Inc. 5000 honoree in 2024 and 2025 and an SIA Best Staffing Firms to Work For in 2023 and 2024. https://amundsongroup.com
