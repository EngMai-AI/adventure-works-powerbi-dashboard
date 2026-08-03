# Adventure Works Sales Analytics Dashboard

An end-to-end Power BI project built on the Adventure Works dataset, covering data modeling, DAX measure development, and interactive report design.

## Overview

This dashboard analyzes sales performance, product profitability, customer behavior, and sales team achievement across regions. It was built following PL-300 (Microsoft Power BI Data Analyst) best practices for data modeling and DAX.

## Data Model

- Built a full star-schema data model with Fact/Dimension tables: `Fact_Sales`, `Dim_Product`, `Dim_Region`, `Dim_Reseller`, `Salesperson`, `SalespersonRegion`, `Targets`
- Created a dedicated DAX-based `Calendar` table for time intelligence
- Resolved relationship issues including missing relationships, incorrect cardinality, and ambiguous/circular paths
- Established a `_Measures` table to organize all DAX measures as best practice

## DAX Measures

Total Sales, Total Profit, Profit Margin %, Total Target, Achievement %, Sales LY, Sales Growth %, YTD Sales, and more.

## Report Pages

1. **Home** — themed banner and navigation
2. **Sales Overview** — KPI cards for Total Sales, Total Profit, Profit Margin %, Total Resellers
3. **Products** — product-level performance breakdown
4. **Customers** — customer analysis
5. **Sales Team Performance** — Total Target, Achievement %, Total Salespersons, Average Sales Growth %, Target Achievement Gap, Sales by Team Member

## Tools

Power BI Desktop, Power Query, DAX

## Demo

[(https://www.linkedin.com/posts/mai-reda-74477423b_powerbi-dataanalysis-dax-ugcPost-7489415080363663360-v82S/?utm_source=share&utm_medium=member_desktop&rcm=ACoAADu8WiQByLPNjw-Qp-TZvyuaaHtQh83u1sU)
](https://www.linkedin.com/posts/mai-reda-74477423b_powerbi-dataanalysis-dax-ugcPost-7489415080363663360-v82S/?utm_source=share&utm_medium=member_desktop&rcm=ACoAADu8WiQByLPNjw-Qp-TZvyuaaHtQh83u1sU)

