# Global Superstore Executive Dashboard (Power BI)

**AnalystLab Africa Data Analytics Internship | Week 2: Business Intelligence & Interactive Dashboard Development**

Author: Georgewill Stephanie Alaye

## Business Problem

A national retail company needs an executive dashboard that lets management monitor **sales performance, profitability, customer behaviour and regional performance**, and turn raw business data into decisions. This project builds that dashboard in Microsoft Power BI and backs it with written insights and recommendations.

The dashboard answers seven business questions:

1. What is the overall sales performance of the company?
2. Which regions generate the highest sales and profit?
3. Which customer segments contribute the most revenue?
4. Which product categories perform best?
5. Which products are the most profitable?
6. What trends can be observed over time?
7. What recommendations should management implement to improve business performance?

## Dataset

- **Global Superstore Dataset** (Kaggle): https://www.kaggle.com/datasets/apoorvaappz/global-super-store-dataset
- Order-level retail data: order dates, ship modes, customer segments, regions and countries, product categories and products, sales, profit and quantity.

## Tools Used

- Microsoft Power BI (data modelling, DAX measures, visuals, slicers)
- Power Query (data preparation: structure review, missing values, duplicates, data types)

## Dashboard Overview

**Page 1: Executive Dashboard**

- **5 KPI cards:** Total Sales, Total Profit, Total Orders, Average Sales, Profit Margin %
- **Visuals:** Sales by Ship Mode (pie), Sales/Profit Trend over time (column and line), Customer Segment Revenue (column), Product Category Performance (column), Top 10 Products by Profit (bar), Sales by Region (bar), Regional Performance Breakdown (matrix with conditional formatting on margin)
- **Slicers:** Year, Region, Segment

**Page 2: Executive Summary**

- Key insights, risks, opportunities and recommendations
- Profit Margin % by Month (line chart)

## Key Insights

1. The business made **$12.6M in sales and $1.47M in profit**, a margin of about **12%**, across roughly 25K orders.
2. **Central** leads with $2.8M sales and $311K profit; margins range from **27% in Canada** down to **2% in Southeast Asia**.
3. **Consumer** customers bring in about **$6.5M (51%)** of revenue, followed by Corporate ($3.8M) and Home Office ($2.3M).
4. **Technology** products lead the profit ranking, topped by the Canon imageCLASS 2200 Advanced Copier.
5. Sales **rise through the year and peak late in the year**, with a dip in July.

## Risks and Opportunities

- **Risks:** very low margin in Southeast Asia (2%), below-average margins in EMEA (5%) and South (9%), and about 60% of sales relying on Standard Class shipping.
- **Opportunities:** high-margin regions (Canada, North Asia, North), late-year demand, and growth in Corporate and Home Office segments.

## Recommendations

1. Review pricing, discounts and costs in Southeast Asia, EMEA and South.
2. Invest in marketing and distribution in high-margin regions.
3. Plan stock and promotions around the late-year peak and lift July sales.
4. Launch targeted offers for Corporate and Home Office customers.
5. Promote high-profit Technology products and reduce reliance on Standard Class shipping.

## Screenshots



![Executive Dashboard](screenshots/dashboard-page-1.png)





![Executive Summary](screenshots/dashboard-page-2.png)



## Repository Contents

| File | Description |
|------|-------------|
| `Global_Superstore.pbix` | Power BI project file |
| `Dashboard_Export.pdf` | Dashboard export (both pages) |
| `BI_Overview_Report_Global_Superstore.pdf` | Business Intelligence Overview Report |
| `Executive_Summary_Report_Global_Superstore.pdf` | Executive Summary Report |
| `screenshots/` | Dashboard screenshots |

## Skills Developed

Data import and cleaning in Power Query, KPI design, interactive dashboard design in Power BI, data storytelling, and writing business insights and recommendations.

## Connect

- LinkedIn: https://www.linkedin.com/in/stephanie-georgewill-9852342b4
- #AnalystLabAfrica