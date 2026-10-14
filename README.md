# Databel Customer Churn Analysis (Excel)

An Excel dashboard and set of PivotTables looking at why customers leave Databel, a telecom provider. The focus is on customers lost to competitors, since they are the largest group.

Databel has 6,687 customers in the data and 1,796 of them churned, a churn rate of 26.9%.

[Download the workbook](https://github.com/BalajiSriramareddy/databel-customer-churn-analysis/raw/main/Databel_Customer_Churn_Analysis.xlsx) and start on the Overview sheet.

## Findings

Competitors account for 45% of all churn. Within that group, a better offer (38%) and better devices (37%) are the main reasons, well ahead of more data (14%) and faster download speeds (12%). The single biggest reason outside competitors is the attitude of support staff, at 11% of all churned customers.

Customers on unlimited data plans churn at 32.1%, double the 16.1% on capped plans. The gap is widest among light users: customers using under 5 GB a month churn at 34.7% on an unlimited plan and 12.3% on a capped one. They are paying for data they don't use, so a cheaper competitor offer is easy to accept.

Month-to-month customers churn at over 70% in every tenure band up to four years, and at 82% in their first year. One- and two-year contracts mostly stay below 20%, so contract type separates churners far more than tenure does.

Seniors churn at 38.5% against 24.5% for other adults and 23.0% for under-30s. By age band, churn climbs from 22% (19 to 28) to 44% (79 to 88).

International-plan churn varies a lot by state. California's international-plan customers churn at 75%, with Indiana at 67% and New Hampshire at 63%. These groups are small, so the figures need checking before anyone acts on them.

## What's in the workbook

| Sheet | Contents |
|---|---|
| Overview | Dashboard: total customers, churned customers, churn rate, and charts of churn drivers and competitor churn |
| Churn Analysis | PivotTables by demographic group, age band, data plan and usage, international plan by state, and tenure by contract type |
| Customer Pivots | Churn by category and reason, with the competitor reasons broken down |
| Databel - Aggregate | The analysis table, with added fields `Churned` (1/0), `Demographics` (Under 30 / Senior / Other) and `Grouped Consumption` (<5 GB / 5 to 10 GB / 10+ GB) |
| Databel - Customer | Customer-level source data, 6,687 rows |

If Excel opens it in Protected View, click Enable Editing. If a PivotTable looks out of date, use Data > Refresh All. New rows need to go inside the Aggregate table for the pivots to pick them up.

## Tools

Microsoft Excel: tables, PivotTables, calculated fields, PivotCharts and conditional formatting.

Balaji Manjulamma Sriramareddy · MSc Data Science, University of Hertfordshire · [LinkedIn](https://www.linkedin.com/in/balaji-sriramareddy/) · [Portfolio](https://balajisriramareddy.github.io/)
