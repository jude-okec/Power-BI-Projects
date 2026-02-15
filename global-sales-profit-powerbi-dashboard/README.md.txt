Case Study — Global Sales & Profit Performance Analytics (Power BI)

Business Problem

The organization lacked a unified view of revenue, cost, and profitability across countries and product categories.

Leadership could see top-line sales, but could not easily answer:

Which markets are truly profitable?

Is margin improving or declining over time?

What product mix drives financial performance?

Where should we focus for growth?

Reporting was:

Static

Regionally fragmented

Not margin-focused

Lacking time intelligence


Project Objective

Design an interactive executive dashboard that:

Tracks revenue and gross profit in one view

Monitors gross profit margin trend over time

Identifies top-performing countries and products

Shows category contribution to sales and profit

Enables YTD performance tracking


Solution Architecture

Data Modeling

Implemented a star schema for performance and scalability:

Fact Table

Sales transactions (Revenue, COGS, Quantity)

Dimension Tables

Date

Country

Product

Category

This enabled:

Fast aggregations

Reusable time intelligence

Clean filter behavior across visuals


Key DAX Measures
Gross Profit
Gross Profit = [Total Revenue] - [Total COGS]

Gross Profit Margin
Gross Profit Margin =
DIVIDE([Gross Profit], [Total Revenue])

YTD Gross Profit
YTD Gross Profit =
TOTALYTD([Gross Profit], 'Date'[Date])


These measures allowed dynamic period comparison and trend analysis.


Report Design
🔹 Sales Overview Page

Focused on top-line performance and volume drivers

KPIs

Total Revenue → $2.87bn

Total Quantity → 183M units

Visuals

Revenue by country → geographic performance benchmarking

Quantity by product → volume drivers

Revenue by category → product mix

Revenue trend over time → growth pattern & seasonality


🔹 Profit Overview Page

Focused on profitability and margin health

KPIs

YTD Gross Profit → 358.92M

YTD Gross Profit Margin → 40.15%

Visuals

Gross profit by country → high-value markets

Gross profit by category → margin contribution

Revenue vs COGS vs margin trend → cost control visibility


Key Insights Delivered

Revenue Concentration

A small number of countries generate the majority of revenue →

- Enables geo-focused growth strategy

Margin Visibility

Margin trend shows the relationship between:

Revenue growth

Cost increases

Profitability stability

- Helps leadership detect profit erosion early

Product Strategy

Category contribution highlights:


High-revenue vs high-margin segments
- Supports portfolio optimization



Business Impact

This dashboard enables stakeholders to:

Shift focus from revenue → profitability

Identify high-margin markets

Optimize product mix

Monitor financial performance in real time

Reduce reliance on manual reporting


Tools & Technologies

Power BI

DAX

Power Query

Star schema data modeling

Time intelligence functions