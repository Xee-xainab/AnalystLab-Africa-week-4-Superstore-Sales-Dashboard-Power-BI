# 📊 Superstore Sales Performance Dashboard

## Overview

This project presents an interactive **Power BI dashboard** developed using the **Superstore Sales Dataset**. The dashboard transforms raw sales data into meaningful business insights, enabling stakeholders to monitor performance, identify trends, and make informed decisions.

The report was developed as part of **Week 4 – Data Visualization & Dashboarding** during my **Data Analytics Internship at AnalystLab Africa**.

> Where does Superstore make money, and where does it lose it? An interactive Power BI dashboard analysing 9,994 order lines from 2014 to 2017.

## Business Problem
Superstore sales are growing, but growth alone does not show whether the business is healthy. Management needs to know which regions, products and customers drive profit, and which ones quietly lose it, so pricing and discount decisions can be made with evidence.

## Dataset
- **Source:** Sample Superstore dataset (CSV)
- **Size:** 9,994 order lines, 5,009 orders, 793 customers, 1,862 products
- **Period:** 2014 to 2017
- **Coverage:** 4 regions, 3 categories, 17 sub-categories

## Dashboard Pages
| Page | Focus |
|------|-------|
| Superstore Sales Performance Dashboard | Sales, profit and margin overview with region, category and year filters |
| Product and Regional Performance | Sub-category profitability, sales by state, top 5 products |
| Customer Purchasing Behavior | Top customers, segments and shipping modes |

## Key Metrics
| Total Sales | Total Profit | Profit Margin | Total Orders | Customers |
|-------------|--------------|---------------|--------------|-----------|
| $2.30M | $286.40K | 12.47% | 5,009 | 793 |

## Key Insights
- Sales grew 51% from $484K (2014) to $733K (2017) and profit grew 89%, lifting margin from 10.2% to 12.7%.
- West leads with a 14.9% margin because it gives the smallest discounts (11% on average). Central earns only 7.9% because it discounts the most (24% on average).
- Furniture earns only a 2.5% margin ($18K profit) on $742K in sales, while Technology and Office Supplies earn about 17%.
- Tables lose $17.7K and Bookcases lose $3.5K. Tables are discounted by 26% on average.
- Discounts above 20% lose $135K in total, and 97% of those order lines are unprofitable.
- Texas, Ohio, Pennsylvania and Illinois are loss-making because they discount 32-39% on average.
- Consumers drive 50.6% of sales but have the lowest margin (11.6%), while Home Office has the best (14.0%).
- Standard Class carries 59% of sales, and the top 10 customers account for only 6.7% of sales.

## Recommendations
1. Cap discounts at 20%, starting with Central, Texas, Ohio, Pennsylvania and Illinois.
2. Review pricing and supplier costs for Tables, Bookcases and Furniture overall.
3. Promote high-margin lines such as Copiers, Accessories and Paper.
4. Grow Home Office and Corporate accounts, which earn better margins than Consumer.
5. Introduce loyalty offers to retain top customers.

## Tools Used
- Power BI (data modelling, DAX measures, slicers, interactive visuals)
- Excel / CSV (source data and validation)

## Repository Contents
- `Sample_-_Superstore.csv`: source dataset
- `Superstore_Dashboard.pbix`: Power BI file
- `Superstore_Report.pdf`: 2-page summary report
- `Superstore_Dashboard.PDF`: exported dashboard

## Author
**Zainab Danjuma**
Data Analyst Intern, AnalystLab Africa
