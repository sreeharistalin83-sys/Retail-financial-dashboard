 Retail-financial-dashboard
End to end finance analytics project using Python, MySQL, Excel and Power BI
 📊 Retail Financial Performance Dashboard

An end-to-end finance analytics project built to demonstrate real-world skills in Python, MySQL, Excel, and Power BI — the core toolkit of a Finance Business Analyst / FP&A Analyst.

---

 🎯 Project Objective

To build a complete financial data pipeline — from raw data generation and cleaning, through SQL-based KPI analysis, to an interactive Power BI dashboard — simulating the workflow of a Finance Business Analyst in a retail organisation.

---

 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python (Pandas, NumPy, Faker) | Data generation, cleaning, transformation |
| MySQL | Database design, data loading, KPI queries |
| Excel (openpyxl) | Automated KPI report generation |
| Power BI | Interactive financial dashboard |

---

 📁 Project Files

| File | Description |
|------|-------------|
| `Project 2.ipynb` | Full Python notebook — data generation, cleaning, MySQL load, Excel export |
| `retail_sales_clean.csv` | Clean dataset — 2,400 retail transactions across 2023–2024 |
| `retail_kpi_report.xlsx` | Auto-generated Excel report with 5 KPI sheets |
| `Retail Financial Dashboard.pbix` | Power BI dashboard file |

---

 🔄 Project Workflow

```
Python → Generate & Clean Data → MySQL → KPI Queries → Excel Report → Power BI Dashboard
```

 Phase 1 — Python: Data Generation & Cleaning
- Generated 2,400 realistic retail transactions across 2 years (2023–2024)
- Dimensions: 5 regions, 5 product categories, 25 products, 20 sales reps
- Intentionally introduced 3% null values to simulate real-world data quality issues
- Cleaned nulls, fixed data types, engineered key financial columns:
  - `gross_margin_pct` — profit as % of revenue
  - `budget_variance` — actual vs budget difference
  - `variance_pct` — variance as a percentage

 Phase 2 — MySQL: Database & KPI Queries
Designed and loaded a structured MySQL database (`retail_db`) and wrote 5 business KPI queries:

1. Revenue by Region — total revenue, profit, and average margin per region
2. Month-on-Month Trend — monthly revenue, profit, budget, and variance for 2023–2024
3. Top 10 Products — ranked by total revenue with units sold
4. Gross Margin by Category — profitability analysis across 5 product categories
5. Actual vs Budget Variance by Quarter — financial performance against targets

 Phase 3 — Python + Excel: Automated KPI Report
- Connected Python to MySQL using `mysql-connector-python`
- Executed all 5 KPI queries and loaded results into Pandas DataFrames
- Auto-generated a formatted Excel workbook with 5 sheets using `openpyxl`
- Applied professional styling: blue headers, auto-column widths

 Phase 4 — Power BI: Interactive Dashboard
Connected Power BI to the Excel KPI report and built 5 visuals:
- Bar Chart — Revenue by Region
- Line Chart — Monthly Revenue Trend (2023 vs 2024)
- Donut Chart — Margin by Category
- Horizontal Bar Chart — Top 10 Products by Revenue
- Clustered Column Chart — Actual vs Budget Revenue by Quarter

---

 📈 Key Insights

- West region leads with €3.7M total revenue across 2023–2024
- Gross margin is consistent at ~40% across all regions — healthy retail performance
- Budget variance within ±3% across all quarters — strong financial planning accuracy
- Headphones is the top-performing product by revenue

---

 💼 Skills Demonstrated

- Financial data modelling and KPI design
- SQL database creation, data loading, and analytical querying
- Python automation for data pipelines and report generation
- Power BI dashboard development
- Budgeting and variance analysis — core FP&A competency
- Data quality management (null handling, type correction, derived columns)

---

 👤 About

**Sree Hari Stalin**
MSc Global Business Management (Finance & Analytics) — ESSCA School of Management, Paris
BIDA® Candidate — Corporate Finance Institute (CFI)
6+ years in financial analysis, budgeting, and MIS reporting

🔗 [LinkedIn](https://www.linkedin.com/in/sreehari-stalin) | 📧 Available for Finance Business Analyst / FP&A roles in Paris

---

*This project is part of a portfolio series demonstrating Finance + Analytics skills for BA and FP&A roles.
