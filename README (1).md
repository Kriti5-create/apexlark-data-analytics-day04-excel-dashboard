# ApexLark Data Analytics Internship — Day 04
## Advanced Excel Analysis with Summary Tables, Charts & an Interactive Dashboard

### Dataset
Cleaned Sample Superstore data from Day 02/03 (9,993 records after removing 1 duplicate; 0 missing values), stored as an Excel Table (`SalesData`).

### Deliverables
- `ApexLark_Day04_Interactive_Dashboard.xlsx` — workbook with the interactive dashboard
- `ApexLark_Day04_Business_Insights_Report.pdf` — one-page business insights report
- `README.md` — this file

### Workbook structure
| Sheet | Purpose |
|---|---|
| Dashboard | Header, filter dropdowns (Region, Category, Month, Year), 4 KPI cards, 4 charts, Top 10 customers, key insights |
| Pivot Analysis | Total Sales by Region, Total Sales by Category, Monthly Sales Performance, Profit by Category, Quantity Sold by Product (top 10), Top 10 Customers by Sales |
| Cleaned Data | Cleaned dataset as an Excel Table plus helper columns (Year, Month, Month Year, order flags) |
| Lists | Filter criteria cells and the customer list used for the unique-customer KPI |

### How the interactivity works
The four yellow dropdowns on the Dashboard feed every summary table, KPI card and chart through `SUMIFS` / `COUNTIFS` formulas. Pick a value (or `All`) and the whole dashboard updates.

### Charts
Sales by Region (column), Monthly Sales Trend (line), Profit by Category (bar), Sales Distribution by Category (pie) — each with a title, axis labels and data labels where applicable.

### Key results
- Total Sales $2,296,919 · Total Profit $286,409 · Orders 5,009 · Customers 793
- Top region: West ($725,458) · Top category: Technology ($836,154)
- Best month: November 2017 ($118,448) · Top customer: SM-20320 ($25,043)
