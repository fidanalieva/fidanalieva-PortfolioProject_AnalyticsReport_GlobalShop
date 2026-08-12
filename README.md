# GlobalShop SQL Analytics Portfolio

## Project Overview

This project analyzes sales, customer, product, and geographic data for **GlobalShop**, a multi-channel retailer operating in 50+ countries. The analysis was built to answer real business questions posed by different stakeholders — the CEO, Head of Product, Head of Sales, and Head of CRM — using SQL to move from raw transactional data to actionable business insight.

The project was completed as a portfolio piece to demonstrate SQL proficiency (CTEs, window functions, RFM segmentation, PIVOT, cohort analysis) alongside the ability to translate technical output into plain-English business recommendations.

## Data Source

Data comes from Oracle Free SQL's built-in **`sh` (Sales History)** sample schema, specifically the `sh.sales`, `sh.customers`, `sh.products`, `sh.channels`, and `sh.times` tables. This is a standard Oracle sample dataset representing multi-year, multi-channel retail sales transactions.

## What Each Analysis Covers

| # | Analysis | Business Question |
|---|----------|-------------------|
| 1 | **Revenue Trend Analysis** | How does revenue move month-by-month, and what does running year-to-date look like? |
| 2 | **Customer Value Segmentation (RFM)** | Who are the most valuable customers, who's slipping away, and who's already lost? |
| 3 | **Product Portfolio Review** | Which products drive the most revenue, which are growing, and which should be phased out? |
| 4 | **Channel Effectiveness & Strategy** | Which sales channel is growing fastest, and how does performance differ by quarter? |
| 5 | **Customer Loyalty & Retention** | How many customers return after their first purchase, and how quickly? |
| 6 | **Geographic Reach & Expansion** | Where is revenue concentrated, and where should GlobalShop invest in expansion? |

Each analysis in the SQL file includes the original business question, a plain-English answer based on the query output, and the SQL code itself.

## Repository Structure
├── code/
│ └── TheGlobalShop_PortfolioProject_FidanAliyeva.sql # All six SQL analyses
├── report/
│ └── TheGlobalShop_AnalyticsReport... # Full written report with findings & screenshots
└── README.md # This file

## Key Findings (Executive Summary)

- **Marketing Effectiveness:** The Partners channel grew 44% year-over-year (2020–2021), while Direct Sales — still the largest channel at $14.26M in 2021 — declined 3%.
- **Geographic Expansion:** Outside the top 10 markets, country 52775 recorded 163% YoY growth, making it a strong candidate for early expansion.
- **Customer Loyalty:** 90-day return rates varied sharply by acquisition cohort — from 88% (January) to 64% (April) — pointing to inconsistent post-purchase engagement.

Full findings, methodology, and strategic recommendations are available in the `report/` folder.

## Tools & Techniques

- Oracle SQL (Oracle Free SQL / `sh` sample schema)
- Common Table Expressions (CTEs)
- Window functions (`RANK`, `NTILE`, `LAG`, `ROW_NUMBER`, running totals)
- `PIVOT` for crosstab reporting
- Cohort analysis for retention tracking

## Author

Fidan Aliyeva
