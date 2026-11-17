# NYC Airbnb Market Analysis | Power BI

<p align="center">
  <strong>Interactive business-intelligence analysis of 36,445 NYC Airbnb listings, combining Power BI dashboards, DAX measures, market segmentation, and an investment recommendation.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-DAX-F2C811?logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/Listings-36%2C445-4B8BBE" alt="Listings">
  <img src="https://img.shields.io/badge/Focus-Business%20Intelligence-2E8B57" alt="BI">
</p>

<p align="center">
  <img src="screenshots/market_overview.png" alt="NYC Airbnb market overview dashboard" width="900">
</p>

## Business Question

Where should a small real-estate investor focus within the NYC short-term-rental market, and what property / host profile appears most attractive based on the available listing data?

The analysis evaluates:

- borough-level market size
- room-type mix
- host profile
- superhost performance
- guest-rating proxies
- estimated booking activity
- time-based listing activity

Because the dataset does **not** include revenue, profit, true occupancy, property acquisition cost, or operating expense, the analysis treats ratings, reviews, and estimated nights booked as **decision-support proxies rather than profitability measures**.

## Dashboard

The Power BI report contains two pages:

1. **Market Overview** - executive KPIs, borough comparison, room-type mix, map, filters, and time-based activity.
2. **Superhost Deep Dive** - superhost KPIs, borough distribution, top operators, and performance by host size.

<p align="center">
  <img src="screenshots/superhost_deep_dive.png" alt="NYC Airbnb superhost analysis dashboard" width="900">
</p>

## Key Findings

- The dataset contains approximately **36K listings** with an overall average rating of **4.72**.
- Roughly **19%** of listings are associated with superhosts.
- Manhattan has the largest listing count, but Brooklyn offers a more balanced combination of scale, guest ratings, and estimated booking activity.
- Brooklyn contains **13,254 listings** versus Manhattan's **16,355**, while showing a higher average rating (**4.76 vs. 4.67**) and higher average estimated nights booked (**46.55 vs. 41.74**).
- On the superhost deep-dive page, small hosts (1-2 listings) show the strongest proxy performance, including an average rating of **4.89** and average estimated nights booked of **175.81**.

## Recommendation

The analysis recommends **Brooklyn entire-home / apartment listings** as the strongest initial market direction and suggests a **small-host operating model** as the most attractive service benchmark.

This is a directional recommendation rather than a profitability conclusion. A final investment decision would require revenue, nightly pricing, acquisition cost, operating expense, neighborhood-level regulation, and true occupancy data.

## Power BI Features

- custom DAX measures
- KPI cards
- map visualization with borough segmentation
- date hierarchy / drill-down
- slicers
- page-level filtering
- Top-N filtering
- conditional formatting
- host-profile segmentation
- two-page executive / deep-dive layout

## Repository Structure

```text
nyc-airbnb-power-bi/
├── README.md
├── screenshots/
│   ├── market_overview.png
│   └── superhost_deep_dive.png
├── report/
│   └── business_memo.md
└── data/
    └── README.md
```

## Data

The project uses an Inside Airbnb NYC listings dataset with **36,445 observations**.

The raw CSV and PBIX working file are intentionally not required to understand the portfolio artifact; the dashboard screenshots and memo capture the analytical design and conclusions.

## Limitations

- No direct revenue, profit, or acquisition-cost fields.
- Estimated nights booked is a proxy rather than observed occupancy.
- Listing-level analysis does not establish property-level investment returns.
- Regulation and neighborhood-specific operating constraints require separate analysis.

---

<sub>Graduate business-intelligence project, 2026.</sub>
