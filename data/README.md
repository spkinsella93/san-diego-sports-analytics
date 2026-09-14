# San Diego Sports Dataset

This folder contains the underlying dataset used to build the **Is San Diego a Sports Town?** analysis and Power BI dashboard.

## Dataset

[Download the Excel dataset](san_diego_sports_data.xlsx)

The dataset was built from the ground up using publicly available team, league, venue, and market information. Reported data was used wherever reliable team-level information was available, while standardized estimates were developed where public data was unavailable.

## Key Data Fields

The dataset includes team-level information covering:

- Team and league
- Sport and competitive level
- Venue and venue capacity
- Home games
- Annual and average attendance
- Venue utilization
- Average ticket price
- Estimated gate receipts
- Published and estimated franchise values
- Selected franchise value
- Valuation methodology
- Franchise value / gate receipts multiple
- Data method
- Confidence level
- Supporting notes

## Data Classification

Observations are classified based on the type of information used:

- **Reported** — directly reported by a team, league, or primary source
- **Third-Party** — reported by a reputable external source
- **Estimated** — calculated using a documented project methodology
- **League Average / Comparable** — derived from league-level or comparable-market information when team-specific data was unavailable

## Estimated Values

Estimated values are intentionally identified rather than presented as reported figures.

Franchise valuations for teams without credible published values should be interpreted as directional estimates. These estimates were developed using either the project's standardized gate-receipts model or comparable-market approaches depending on the team's operating model and available evidence.

For detailed formulas, assumptions, valuation approaches, and limitations, see the [project methodology](../methodology/methodology.md).

## Data Usage

The dataset is provided to make the analysis transparent and reproducible. It allows users to inspect the underlying observations and assumptions used to construct the Power BI dashboard.

The dataset should not be interpreted as audited financial information or official franchise financial reporting.
