# Is San Diego a Sports Town?

### An Executive Overview of the San Diego Professional Sports Market Landscape

This project examines San Diego's professional sports ecosystem through franchise value, attendance, ticket pricing, and venue utilization.

I built the dataset from the ground up, combining publicly available team and league data with standardized estimates where reported figures were unavailable. The analysis was then modeled and visualized in Power BI.

![San Diego Sports Dashboard](dashboard/dashboard_preview.png)

## Project Overview

The goal of this project was to answer a deceptively simple question:

**Is San Diego really a sports town?**

Rather than answering the question with a single metric, the analysis looks across the city's professional sports landscape to evaluate:

- Franchise value
- Annual attendance
- Average ticket prices
- Venue utilization
- Differences in demand across teams and leagues

The 2026 snapshot includes nine professional teams competing in the San Diego market.

## Dashboard

The dashboard provides an executive-level view of the market while allowing individual teams to be cross-filtered for deeper comparison.

[View the full dashboard PDF](dashboard/san_diego_sports_dashboard.pdf)

## Data

The underlying dataset includes team-level information on attendance, venue capacity, ticket pricing, franchise valuation, and valuation methodology.

[View the project dataset](data/san_diego_sports_data.xlsx)

## Methodology

Publicly reported figures were used whenever reliable team-level data was available. Where data was unavailable, standardized estimation methods and comparable-market approaches were used.

Estimated values are identified in the underlying dataset and supported by documented assumptions and confidence levels.

[Read the full methodology](methodology/methodology.md)

## Tools Used

- Power BI
- Microsoft Excel
- DAX
- Deneb / Vega-Lite
- Data research and modeling

## Project Focus

This project was designed not only as a visualization exercise, but as an end-to-end business analytics project covering:

**Research → Data Collection → Data Cleaning → Modeling → Visualization → Interpretation**

The objective was to create an analysis that could communicate effectively at the executive level while still providing enough underlying methodology for the results to be evaluated and challenged.
