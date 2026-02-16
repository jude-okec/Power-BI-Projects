AdventureWorks Executive Analytics Dashboard (Power BI)

Project Overview

This project delivers an end-to-end business intelligence solution built in Power BI to analyze sales performance, product profitability, and customer behavior for AdventureWorks.

The report is designed for executive decision-making, enabling stakeholders to:

Track revenue, profit, and order trends

Identify top-performing products

Analyze return rates

Segment high-value customers

Simulate pricing impact using a What-If parameter


Business Objectives

Monitor overall business performance with dynamic KPIs

Identify revenue growth drivers and underperforming areas

Reduce product return rate

Understand customer value and demographics

Enable data-driven pricing decisions


Dashboard Pages

1. Executive Overview

Provides a high-level snapshot of business performance.

Key Features:

Revenue, Profit, Orders, and Return Rate KPIs with YoY comparison

Revenue trend with forecast baseline

Orders by product category

Top 10 products by revenue with return %

Monthly performance indicators

Business Value:
Quickly helps leadership assess whether the business is growing, where performance gaps exist, and which products drive the most revenue.


2. Product Performance & What-If Analysis

A deep dive into individual product performance.

Key Features:

Dynamic product selection

Monthly Orders, Revenue, and Profit vs target

Price adjustment What-If parameter

Adjusted Profit simulation

Metric selector (Revenue / Profit / Orders / Returns / Return %)

Business Value:
Supports pricing strategy by showing how price changes impact profitability before implementation.


3. Customer Insights Dashboard

Focuses on customer segmentation and value analysis.

Key Features:

Total unique customers

Revenue per customer

Customer growth trend

Top 100 customers by revenue

Customer segmentation by:

Income level

Occupation

Top customer highlight

Business Value:
Helps identify high-value customer groups and supports targeted marketing strategies.


Technologies

Power BI Desktop

Power Query (Data transformation & cleaning)

DAX (Data modeling & calculations)

Data Modeling (Star schema)

What-If Parameters

Interactive visual design


Data Model

The report uses a star schema with:

Fact Tables:

Sales

Dimension Tables:

Date

Product

Customer

Geography

This structure ensures:

High performance

Accurate time intelligence

Scalable analytics



Key DAX Measures

Examples of implemented logic:

Total Revenue

Total Profit

Profit Margin

Return Rate

YoY Growth

Revenue per Customer

Adjusted Profit (What-If simulation)


Insights Generated

Strong Year-over-Year revenue and profit growth

Accessories drive the highest order volume

Certain high-revenue products also have elevated return rates

High-income customers generate the largest share of revenue

Pricing adjustments have a direct and measurable impact on profit