# Formula 1 Race Intelligence Dashboard (2010–2026)

An educational Formula 1 data analytics project built with Tableau Public. The dashboard and guided story explore driver and constructor performance, race participation, driver nationality, podium achievements, and race completion patterns across seasons.

> **Project scope:** This is a descriptive analytics and data-visualization project, not an official Formula 1 performance system.

## Table of Contents

- [Project Objectives](#project-objectives)
- [Dataset](#dataset)
- [Dashboard and Story](#tableau-dashboard-and-story)
- [Worksheets](#worksheets)
- [Tools and Technologies](#tools-and-technologies)
- [Performance Testing](#performance-testing)
- [Limitations](#limitations)
- [Repository Structure](#repository-structure)
- [Demo Video](#demo-video)
- [Conclusion](#conclusion)

## Project Objectives

- Compare driver and constructor points.
- Explore driver DNFs and race-completion patterns.
- Review race participation by season.
- Explore driver nationalities and Grand Prix rounds by host country.
- Compare constructor points across seasons.
- Summarize podium achievements by driver and team.
- Publish an interactive dashboard and a guided story through Tableau Public.

## Dataset

**Source repository:** [formula-one-datasets on GitHub](https://github.com/muharsyad/formula-one-datasets)

The project uses relevant Formula 1 data tables—such as race results, races, drivers, and circuits—where available in the connected data source. Confirm the exact tables, joins, relationships, filters, and date coverage in the final Tableau workbook before publishing.

### Data coverage

The project is described as covering **2010–2026**. Verify that the connected dataset contains the intended seasons and that the dashboard's filters and titles reflect the actual available data.

### Data limitation

The dataset used for this project did not provide the tyre-compound fields needed for a reliable tyre-strategy analysis. Therefore, this project does not make tyre-compound or tyre-strategy conclusions.

## Tableau Dashboard and Story

- **Dashboard title:** Formula 1 Race Intelligence Dashboard
- **Dashboard:** [View the interactive dashboard on Tableau Public](https://public.tableau.com/views/Formula1Dashboard_17932570104390/Formula1RaceIntelligenceDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
- **Story title:** Formula 1 Race Intelligence Story
- **Story link:** Add the published Tableau Public story URL when available.

The dashboard brings together multiple views of historical Formula 1 data to support interactive exploration and descriptive comparisons across seasons.

## Worksheets

1. **Driver Points Leaderboard** — compares driver points.
2. **Constructor Points Leaderboard** — compares constructor points.
3. **Driver DNF Analysis** — explores recorded non-finishes by driver.
4. **Race Participation by Season** — reviews participation across seasons.
5. **Driver Nationality Distribution** — shows the distribution of driver nationalities represented in the data.
6. **Grand Prix Rounds by Host Country** — explores race rounds by host country.
7. **Constructor Points by Season** — compares constructor points over time.
8. **Podium Achievements by Driver and Team** — summarizes podium achievements.
9. **Race Completion Rate by Season** — compares race-completion patterns across seasons.

*Interpret charts using the fields, filters, definitions, and values shown in the published workbook. In particular, confirm how DNFs, participation, podiums, and completion rates are defined.*

## Tools and Technologies

- **Tableau Public** — dashboard authoring, visualization, and publication.
- **CSV-based Formula 1 dataset** — source data from the repository linked above.

## Performance Testing

Performance testing has been completed, as reported by the project owner. Numerical load-time benchmarks are not included because no measured values have been recorded in this report.

## Limitations

- Tyre-compound data was unavailable in the dataset used, so tyre-strategy analysis is outside the scope of this project.
- DNF counts alone do not establish mechanical failure, driver error, or any other cause.
- Data coverage and exact table relationships should be verified in the final Tableau workbook.
- Findings should be based on the actual published charts and verified data values.
- Exact validation totals and measured performance benchmarks are not reported unless separately recorded.
- The project is intended for educational and exploratory analysis and should not be treated as an official Formula 1 source.

## Repository Structure

A suggested repository layout:

```text
formula-1-race-intelligence/
├── README.md
├── Formula_1_Race_Intelligence_Report.pdf
├── data/                 # Include only if redistribution is permitted
├── screenshots/          # Optional dashboard/story screenshots
└── video/                # Optional demo video, or add a link below
```

Only include dataset files in the repository if redistribution is permitted by the source's terms.

## Demo Video

**Demo video:** Add the demonstration video URL or submission location here.

The demo can briefly introduce the dashboard, demonstrate its filters and interactions, and walk through the guided story.

## Conclusion

The Formula 1 Race Intelligence Dashboard brings multiple perspectives on Formula 1 history into one interactive dashboard and narrative story. It demonstrates how data visualization can support exploratory performance comparisons and communicate patterns across drivers, constructors, races, and seasons while making the project's data limitations explicit.
