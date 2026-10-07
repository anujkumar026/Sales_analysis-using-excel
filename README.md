# Sales_analysis-using-excel

# Sales Performance Analysis (Excel Dashboard)

An Excel-based sales analysis project: raw order data cleaned and summarised with Pivot Tables, and presented in an interactive dashboard with slicers.

## Workbook Structure

| Sheet | Purpose |
|-------|---------|
| `SalesRaw_Data` | Raw order-level data (1,155 orders, 2024) |
| `PIVOT TABLE` | Pivot tables that feed every chart |
| `VISUAL` | Interactive dashboard with KPIs, charts and slicers |

## Dataset

Columns: OrderID, OrderDate, Region, City, Category, Product, SalesRep, Quantity, UnitPrice, Discount%, PaymentMode, TotalSales, Month_Name, Performance.

- Regions: East, North, South, West
- Categories: Clothing, Electronics, Furniture, Grocery
- Payment modes: UPI, NetBanking, Card, Cash

## Dashboard Features

- **KPI cards:** Total Sales, Average Sales, Total Orders
- **Sales by City** (bar chart)
- **Orders by Payment Mode** (pie chart)
- **Monthly sales trend** (line chart)
- **Sales by Region** (bar chart)
- **Sales by Sales Rep** (bar chart)
- **Slicers:** Month, Category, Region (all charts update together)

![Dashboard](images/dashboard.png)

## Questions Answered

1. Total sales for the North region (SUMIFS)
2. Number of Electronics orders paid via UPI (COUNTIFS)
3. Average order value for the South region (AVERAGEIFS)
4. Looking up the TotalSales of any OrderID (lookup function)

## Approach

1. **Clean** the raw data
2. **Analyse** with SUMIFS, COUNTIFS and AVERAGEIFS
3. **Summarise** using Pivot Tables
4. **Visualise** in an interactive dashboard with slicers

## Skills Used

- **Data Cleaning:** fixed spelling errors, removed blank columns, standardised values
- **Formulas:** SUMIFS, COUNTIFS, AVERAGEIFS, lookup function
- **Pivot Tables & Pivot Charts** for summarising sales by city, region, category, payment mode, month and sales rep
- **Slicers & Dashboard Design** for interactive reporting

## Key Insights

- _Add 3-4 findings here, e.g. top city by sales, best sales rep, most used payment mode, month with the highest sales._

## How to Use

1. Download `SalesRaw_Data_Analysis.xlsx`
2. Open it in Excel and go to the `VISUAL` sheet
3. Use the slicers to filter by month, category and region

## Author

**Anuj Kumar** - [LinkedIn](https://linkedin.com/in/anuj-kumar-ssm)
