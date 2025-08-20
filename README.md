# BMW Sales Data Analysis
## 1. Background and Overview

BMW, as a global automotive leader, generates significant sales data across multiple markets, models, and time periods. This project analyzes historical BMW sales transactions to identify patterns, quantify performance drivers, and uncover opportunities for revenue optimization.
The dataset contains transaction-level details including sales date, model, price, quantity, and market (country). The analysis focuses on trend discovery, market segmentation, and product performance evaluation, forming the basis for both strategic and operational decision-making.

![BMW Dashboard](https://github.com/KagisoSegobye/BMW-Data-Analysis/blob/7413cfc04e680427e2200aaa143f63fcd54fbabe/Screenshot%20(30).png)

## 2. Data Structure Overview

File Name: BMW_Sales_Data.csv

Records: 1,923

Fields: 8

Core Columns:

Date – Transaction date

Model – BMW model sold (e.g., X5, 3 Series)

Quantity – Number of units per transaction

Price – Unit selling price

Total Price – Total transaction value

Country – Country of sale

Time Coverage: January 2016 – December 2018

Data Type Mix:

Numerical: Price, Quantity, Total Price

Categorical: Model, Country

Temporal: Date

![Alt text](https://github.com/KagisoSegobye/BMW-Data-Analysis/blob/7413cfc04e680427e2200aaa143f63fcd54fbabe/Screenshot%20(29).png)

## 3. Executive Summary

Total Units Sold: 1,923

Total Revenue: ~$62.49M

Average Price per Unit: ~$32,490

Top Model (Revenue): BMW X5 (~$7.21M)

Top Market (Revenue): USA (~$17.40M)

Sales Pattern: Moderate seasonality observed, with higher peaks in mid-year months.

Product Mix Impact: Premium SUV models like the X5 and X6 contribute disproportionately to total revenue compared to entry-level sedans.

## 4. Insights Deep Dive

### 4.1 Time-Series Trends

Revenue and unit sales show cyclical fluctuations, with notable spikes in Q2 and Q3.

Year-over-year growth appears stable but lacks strong acceleration, suggesting consistent demand without aggressive market expansion.

### 4.2 Product Performance

High-margin SUV models (X5, X6) dominate revenue share.

Sedan lines (3 Series, 5 Series) maintain volume consistency but contribute less per unit due to lower price points.

### 4.3 Geographic Insights

USA is the leading market by both revenue and volume.

Secondary markets show strong niche demand but limited penetration, indicating room for growth with targeted marketing.

### 4.4 Pricing Analysis

The average price remains within the ~$30k–$35k band for most models.

Higher-end variants command premiums exceeding 20% above the median selling price.

## 5. Recommendations

Focus Marketing on High-Value Models: Allocate more budget to SUV promotion in high-revenue markets like the USA to capitalize on existing demand.

Expand in Underpenetrated Markets: Use targeted campaigns in regions with moderate sales but high growth potential.

Seasonal Campaign Optimization: Concentrate promotional activity ahead of Q2 and Q3 sales peaks to maximize returns.

Price Differentiation Strategy: Introduce limited editions or bundles for top models to increase per-unit revenue.

Data Integration: Combine sales data with after-sales/service data for a full customer lifecycle view.

## Caveats and Assumptions

Data Completeness: Assumes all recorded transactions are accurate and representative of total sales within the period. Missing or unrecorded sales could impact conclusions.

Currency Consistency: Revenue figures assumed to be in the same currency and without inflation adjustments.

Market Stability: Insights assume no major market disruptions (e.g., economic crisis, major competitor entry) during the period analyzed.

Power BI Integration: Visual narratives are based on the same dataset; differences in column naming or transformation could alter dashboard outputs.
