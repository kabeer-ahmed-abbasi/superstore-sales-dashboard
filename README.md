# Superstore Sales Dashboard

Two-page interactive Power BI report on the Superstore retail dataset, tracking sales, profit and discounting.

## Pages
**Sales Overview**: KPI cards for total sales, profit, orders and profit margin; sales trend over time; sales by category and segment; profit by region and sub-category; slicers for date, region, category and segment.

**Product & Customer**: top and bottom products, top customers, a category matrix and a discount vs profit scatter chart to show how discounting affects profit.

## Data model
- `Orders` table loaded from `Sample - Superstore.xlsx`
- `Calendar` date table linked to Order Date
- DAX measures: Total Sales, Total Profit, Total Orders, Profit Margin, Total Quantity, Avg Discount

## How to open
1. Open `Superstore Sales Dashboard.pbip` in Power BI Desktop (2024 or newer).
2. Home > Transform data > Edit parameters > set `SourceFile` to the full path of `Sample - Superstore.xlsx`, then Refresh.

## Tools
Power BI Desktop, Power Query, DAX
