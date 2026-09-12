# Financial Health Dashboard (Excel)

An interactive **Financial Health Dashboard** built in Excel to analyze revenue, expenses, profitability, and cash-flow indicators for business performance reporting — designed to support budgeting and financial planning decisions.

## 📊 Overview

This dashboard tracks a company's financial health across 12 months using a fully formula-driven Excel model. It includes:

- **KPI Cards:** Total Revenue, Total Expenses, Net Profit, Average Profit Margin, and Ending Cash Position
- **Revenue vs Expenses Trend** (line chart) to visualize growth and cost patterns over time
- **Monthly Profit Margin %** (bar chart) to track profitability trends
- **Cumulative Cash Flow** (line chart) to monitor cash position over the year

## 🛠️ Tools & Skills Used

- **Microsoft Excel** — formulas (`SUM`, `SUMIFS`-style logic), KPI card design, conditional formatting
- **Data Modeling** — structured raw data sheet feeding a live dashboard sheet
- **Financial Analysis** — revenue, COGS, operating expenses, net profit, profit margin, and cash-flow calculations
- **Dashboard Design** — clean KPI-focused layout for management-style reporting

## 📁 Project Structure

```
Financial_Health_Dashboard.xlsx
├── Dashboard            → KPI cards + charts (main view)
├── Raw Data             → Monthly financial data + formulas
└── Notes & Assumptions  → Documentation of formulas and assumptions
```

## 🔑 Key Formulas

| Metric | Formula |
|---|---|
| Total Expenses | `= COGS + Operating Expenses` |
| Net Profit | `= Revenue - Total Expenses` |
| Profit Margin (%) | `= Net Profit / Revenue` |
| Cumulative Cash Flow | `= Previous Month's Cumulative + Current Month's Net Profit` |

All dashboard KPIs and charts pull dynamically from the Raw Data sheet — updating the input cells automatically refreshes the entire dashboard.

## 📈 Sample Insights

- Revenue grew steadily from **$420K (Jan)** to **$590K (Dec)**, a ~40% increase over the year.
- Profit margin improved from **27.4% to 31.4%**, indicating improving cost efficiency.
- Cumulative cash flow reached **$1.76M** by year-end, showing healthy cash generation.

*(Note: This project uses illustrative sample data to demonstrate the dashboard structure and formulas. It can be easily adapted to real company financial data.)*

## 🚀 How to Use

1. Download `Financial_Health_Dashboard.xlsx`
2. Open in Excel
3. Replace the sample figures in the **Raw Data** sheet (blue-colored input cells) with your own company's monthly Revenue, COGS, and Operating Expenses
4. The Dashboard sheet will automatically recalculate all KPIs and charts

## 👤 Author

**Purushottam Raut**
Aspiring Business Analyst / Data Analyst | Excel | SQL | Power BI | Python
📧 piyushraut9993@gmail.com
