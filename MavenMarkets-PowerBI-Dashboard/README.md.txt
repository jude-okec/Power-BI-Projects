MavenMarkets Revenue & Transaction Performance Dashboard (Power BI)

Project Overview

This Power BI dashboard provides an executive-ready view of revenue, profit, transactions, and return behavior, combining YoY benchmarking, target tracking, and product-level profitability to support data-driven decision-making.

It is designed to answer:

Are we growing vs last year?

Are we hitting our revenue targets?

What is driving profit?

Is the return rate becoming a risk?

When do customers transact (weekday vs weekend)?


Dashboard Preview

Key Business Insights

$1.76M Total Revenue with $1.05M Profit → strong margin performance

Transactions increased significantly vs last year (269K vs 87K)

Return rate improved from 2.60% → 0.99%

Revenue exceeded target ($120.16K vs $119.48K)

Clear weekday transaction dominance (71%)

Profit contribution is concentrated among top products


Features Implemented

Executive KPI Band

Total Revenue

Total Profit

Total Transactions

Return Rate

YoY comparison embedded inside cards

Time Intelligence

YTD Revenue

Last Year Revenue / Profit / Transactions / Return Rate

Revenue trend vs YTD trend

Target vs Actual Tracking

Dynamic revenue target

Variance indicator with conditional formatting

Operational Insights

Transaction trend by month

Return trend monitoring

Weekday vs Weekend behavior

Product Performance

Top 10 products by profit

Interactive Filtering

Date

Region

Product

Data Model

Star Schema

Fact Table

Transactions

Dimension Tables

Date

Product

Region

This structure enables:

Scalable time intelligence

High-performance aggregations

Clean filter propagation

Core DAX Measures
Total Revenue
Total Revenue =
SUMX(
    Transactions,
    Transactions[Quantity] * RELATED(Products[Retail Price])
)

Profit
Profit = [Total Revenue] - [Total Cost]

Last Year Revenue
Last Year Revenue =
CALCULATE(
    [Total Revenue],
    SAMEPERIODLASTYEAR('Date'[Date])
)

Return Rate
Return Rate =
DIVIDE([Total Returns], [Total Transactions])

Revenue Target (5% MoM Lift)
Revenue Target =
[Last Month Revenue] * 1.05

🛠️ Tools & Skills Demonstrated

Power BI

DAX Time Intelligence

Data Modeling (Star Schema)

KPI & Executive Dashboard Design

Conditional Formatting

Target vs Actual Analytics

Business Insight Storytelling


Business Impact

This dashboard enables stakeholders to:

Track performance vs strategic targets

Identify profit-driving products

Monitor operational risks (returns)

Understand customer purchasing patterns

Make faster, insight-driven decisions