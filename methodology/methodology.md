# Methodology

## Overview

This analysis evaluates the San Diego professional sports market using the most recent publicly available team-level data available for the 2026 analysis period.

The project combines reported data with standardized estimates where team-specific information was unavailable. The objective was not to create precise financial valuations of privately held sports organizations, but to develop a consistent and transparent framework for comparing teams across leagues with substantially different economics, operating models, and levels of public disclosure.

Whenever estimates were required, the methodology prioritized observable market data, comparable transactions, and consistent assumptions over subjective adjustments.

## Team Universe

The analysis includes nine professional teams that participated in an official season during the analysis period:

- San Diego Padres — MLB
- San Diego FC — MLS
- San Diego Wave FC — NWSL
- San Diego Seals — NLL
- San Diego Mojo — MLV
- San Diego Sockers — MASL
- San Diego Strike Force — IFL
- San Diego Gulls — AHL
- San Diego Clippers — NBA G League

Teams were included if they participated in an official professional season during the analysis period, regardless of subsequent changes in operating status.

## Data Hierarchy

When multiple sources or data types were available, the following hierarchy was used:

1. Team-reported actual data
2. League-reported actual data
3. Reputable third-party reported data
4. Team-specific modeled estimates
5. League-level averages or comparable-market estimates

Estimated observations are identified in the underlying dataset and should be interpreted accordingly.

## Venue Utilization

Venue utilization is calculated as:

**Average Home Attendance ÷ Venue Capacity**

Attendance and venue capacity are matched to the same operating season wherever possible. This prevents future venue changes from being applied retrospectively to historical attendance.

## Estimated Gate Receipts

Estimated regular-season gate receipts are calculated as:

**Annual Home Attendance × Average Ticket Price**

Estimated gate receipts are used as a standardized proxy for direct fan ticket spending and should not be interpreted as reported team revenue.

## Average Ticket Price

Reported average ticket prices were used when reliable team-level figures were available.

Where reported average ticket price was unavailable, ATP was estimated using the midpoint of the publicly available standard single-match ticket price range:

**Estimated ATP = [(Lowest Standard Single-Match Price + Highest Standard Single-Match Price) ÷ 2] × 0.75**

A standardized 25% downward adjustment was applied to account for season-ticket member preferred pricing and the estimated distribution of venue inventory across pricing tiers.

Premium hospitality, suites, resale inventory, and promotional pricing were excluded where identifiable.

## Franchise Valuation

Franchise valuation presented the largest methodological challenge in the analysis because public valuation data varies substantially across leagues.

Where credible published valuations or transaction-based values were available, those figures were used directly. Where they were unavailable, valuation methods were selected based on the operating model and available market evidence for each team.

The analysis therefore uses three valuation paths rather than applying a single methodology across all nine organizations.

### 1. Published or Observed Market Values

Published or transaction-based valuations were used where credible market evidence was available:

- San Diego Padres
- San Diego FC
- San Diego Wave FC

These values also provided a basis for evaluating the relationship between franchise value and estimated gate receipts within the San Diego market.

### 2. Gate-Receipts Valuation Model

For independent professional teams without published valuations, a standardized San Diego market multiple was developed using teams for which credible franchise values were available.

The model is calculated as:

**Franchise Value-to-Gate-Receipts Multiple = Franchise Value ÷ Estimated Regular-Season Gate Receipts**

The resulting multiples for the three benchmark teams were:

| Team | Franchise Value / Gate Receipts Multiple |
|---|---:|
| San Diego Padres | 23.70× |
| San Diego FC | 27.75× |
| San Diego Wave FC | 26.64× |
| **Average** | **26.03×** |

The standard modeled valuation is therefore:

**Estimated Franchise Value = Estimated Regular-Season Gate Receipts × 26.03**

This multiple is referred to throughout the analysis as the **San Diego Franchise Value / Gate Receipts Multiple**.

It should not be interpreted as a revenue multiple. Estimated gate receipts represent only a standardized proxy for direct regular-season ticket spending and exclude sponsorship, media rights, concessions, merchandise, premium hospitality, and other revenue streams.

This approach was used where the team's operating model was sufficiently comparable for gate receipts to provide a meaningful valuation input.

### 3. Comparable-Market Valuation

During model development, the gate-receipts methodology produced implausible results for several developmental, affiliate, or lower-tier organizations.

Rather than introducing arbitrary league-specific discounts to force those outputs into an expected range, the methodology was changed for these teams.

Comparable-market approaches were used for:

- San Diego Gulls
- San Diego Clippers
- San Diego Strike Force

Depending on the available evidence, these estimates incorporate comparable franchise transactions or market values, inflation adjustments, attendance differences, and observable changes in league scale.

This approach preserves a consistent principle across the analysis:

> **Use observable market evidence when available, model only where necessary, and avoid adding unsupported adjustments solely to produce a more intuitive result.**

## Team-Level Valuation Methods

| Team | Selected Franchise Value | Valuation Approach | Confidence |
|---|---:|---|---|
| San Diego Padres | $3.90B | Published / Transaction-Based Value | High |
| San Diego FC | $765M | Published Value | High |
| San Diego Wave FC | $225M | Published Value | Medium |
| San Diego Seals | $34.8M | Modeled Gate-Receipts Valuation | Low |
| San Diego Sockers | ~$31.0M | Modeled Gate-Receipts Valuation | Low |
| San Diego Mojo | ~$17.0M | Modeled Valuation with League Benchmark Validation | Low |
| San Diego Gulls | ~$17.6M | Inflation + Attendance Adjusted Comparable | Low |
| San Diego Clippers | ~$5.9M | Inflation-Adjusted Transaction Comparable | Low |
| San Diego Strike Force | ~$2.36M | Inflation + League Expansion Adjusted Comparable | Low |

## Confidence and Interpretation

Estimated franchise values should be interpreted as directional market estimates rather than formal financial valuations.

A **Low** confidence designation is intentionally assigned to teams without credible published valuations. This reflects limitations in publicly available financial information and the difficulty of comparing organizations operating across different league structures.

The estimates are designed to provide a transparent basis for market-level analysis while making the uncertainty surrounding privately held franchise values explicit.

## Limitations and Analytical Decisions

This analysis is intended to provide a transparent, directional view of San Diego's professional sports market rather than a formal financial valuation of individual franchises.

Several limitations should be considered when interpreting the results.

### 2026 Snapshot

The dashboard is structured as a 2026 market snapshot using the most recent relevant data available for each team. Because professional sports leagues operate on different calendars and public reporting schedules, not every observation represents the exact same reporting period.

Where applicable, the season or year associated with each observation is documented in the underlying dataset.

### Venue Utilization

Venue utilization pairs average home attendance with the capacity of the venue in which that attendance was recorded.

Future venue changes are not applied retrospectively to historical attendance. For example, a team's announced move to a different venue does not affect utilization calculations until attendance from that venue is available.

### San Diego Mojo

The San Diego Mojo are included because the team participated in the analysis period and therefore formed part of San Diego's professional sports landscape during the 2026 snapshot.

The analysis does not retrospectively remove teams based on subsequent operating changes.

### Franchise Valuation

Franchise values for privately held organizations are particularly difficult to estimate because detailed financial statements, transaction data, and league economics are often unavailable.

Published values are therefore preferred whenever credible evidence exists. Modeled values are explicitly identified and assigned lower confidence levels.

Expansion fees, asking prices, and comparable transactions are treated as market evidence rather than automatically assumed to represent equivalent franchise value.

### Ticket Pricing

Estimated average ticket prices are designed to create a standardized comparison across teams where reported ATP is unavailable.

Actual realized ticket revenue may differ because of season-ticket discounts, promotional inventory, premium seating, dynamic pricing, resale activity, complimentary tickets, and differences in venue inventory.

### Gate Receipts

Estimated gate receipts represent:

**Annual Home Attendance × Average Ticket Price**

This metric is a standardized analytical proxy and should not be interpreted as reported team revenue.

It excludes media rights, sponsorship, concessions, merchandise, parking, premium hospitality, postseason revenue, and other sources of team economics.

### Cross-League Comparability

The nine teams in this analysis operate across leagues with substantially different business models, media economics, venue structures, ownership models, and competitive levels.

As a result, comparisons across teams are intended to illustrate the structure and scale of the San Diego sports market rather than imply that all franchises are economically equivalent.

## Analytical Principles

Throughout the project, the following principles guided methodological decisions:

1. **Prefer reported data over estimates.**
2. **Use observable market evidence when available.**
3. **Clearly identify modeled values and assumptions.**
4. **Avoid unsupported adjustments designed solely to produce intuitive results.**
5. **Change the methodology when the model is inappropriate rather than forcing every team through the same framework.**
6. **Match attendance and venue data to the same operating period wherever possible.**
7. **Preserve uncertainty rather than imply false precision.**

These principles were used to balance comparability across teams with the limitations inherent in analyzing privately held sports organizations.
