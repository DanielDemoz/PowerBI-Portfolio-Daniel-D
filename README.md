# Power BI Analytics Portfolio

Eight industry Power BI projects demonstrating dashboard design, DAX modeling, and business intelligence across transportation, construction, finance, manufacturing, retail, healthcare, and fitness.

## Problem

Employers and clients need evidence of end-to-end BI capability—multi-page dashboards, advanced visuals, and domain-specific KPIs—not just single-chart samples.

## Approach

Authored eight complete `.pbix` projects with supporting CSVs, PDF snapshots, and per-project READMEs. Covered chord diagrams (airport flows), Gantt/variance dashboards (construction), balanced scorecards (finance), SPC box plots (manufacturing), sales analytics (retail), patient flow (healthcare), and member retention (fitness).

## Results

- 8 projects across 7 industries with reusable DAX patterns and interactive filtering
- Documented key metrics per project (e.g., Electrohub $19.97M revenue / 25.08% margin; Greenview 5K admissions / 3.68 avg LOS; Pro Fit 86.88% retention)
- Techniques demonstrated: forecasting, cohort analysis, hierarchical drill-down, statistical distributions, network flow visualization

## About the data

All eight companies (Dominion Airlines, Atlas Builders, ABC Financial and the others) are fictional, and their datasets are practice data. Names of people in the member and patient tables are generated, not real. Key figures quoted in the project READMEs were re-checked against the CSV files in October 2026: for example, Electrohub revenue $19.97M at a 25.08% margin, Greenview 5,000 admissions with a 3.68-day average stay, and 695 of 800 Pro Fit members active (86.88%).

## Responsible use

The hospital and gym dashboards show how to report on personal data. With real records, they would need access controls, aggregation thresholds so small groups cannot be identified, and only the fields the report needs.

## Tech stack

Power BI Desktop, DAX, CSV data models, PDF export snapshots

## How to run

1. Install [Power BI Desktop](https://powerbi.microsoft.com) (free).
2. Open any `.pbix` file under project folders (`01-DominionAirlines/` through `08-ProFitGym/`).
3. Explore filters, drill-down, and data model relationships.
4. Review PDF snapshots for quick preview without Power BI installed.

Each folder includes source CSVs, measures reference files, and a project-specific README.

## Screenshot / demo

Static PDF snapshots included in each project folder (e.g., `01-DominionAirlines/`, `05-TransitForecast/`). See root `images/` and individual project directories for visual previews.

**Author:** Daniel S. Demoz — see `ABOUT_ME.md` for professional background.
