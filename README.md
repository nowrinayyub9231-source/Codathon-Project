# 🏠 Home Appliances Sales Dashboard — Codathon Project

An interactive **Power BI** dashboard built during a data analytics codathon to analyze home appliance sales performance, product trends, and regional distribution — translating raw sales data into clear, actionable business insights under time pressure.

[Dashboard Screenshot](https://github.com/nowrinayyub9231-source/Codathon-Project/blob/main/Dashboard%20Overview.png)

---

## 📌 Overview

This project simulates a real-world business scenario: a home appliances company needs a sales performance report for management, built from a dataset containing **1,000 rows with real-world data quality issues** (missing values, inconsistent formatting, etc.). The dashboard was built end-to-end — from data cleaning to DAX measures to a 3-page interactive report with a final insights layer — within a fixed codathon time limit.

## 🗂 Dataset

- **Source file:** `SalesData_1000Rows_WithIssues`
- **Size:** ~1,000 rows
- **Fields:** Order ID, Product, Category, Region, Sales, Profit, Quantity Sold, Order Date
- **Challenges handled:** missing/inconsistent values, data type corrections, and derived helper columns for time intelligence (Year, YTD)

## 📊 Dashboard Pages

### 1. Sales Performance Dashboard
- **KPI Cards:** Total Sales, Total Profit, YTD Sales
- **Gauge Chart:** YTD Sales vs. Yearly Target
- **Line Chart:** Profit trend by year
- **Clustered Column Chart:** Sales by category
- **Map:** Regional sales & quantity sold
- **Slicers:** Year, Product

### 2. Product Analysis Dashboard
- **KPI Cards:** Total Products, Total Quantity Sold, Total Orders
- **Column Chart:** Order count by product
- **Pie Chart:** Order distribution by region
- **Slicers:** Year, Product

### 3. Insights & Recommendations
A narrative summary page translating the visuals into business takeaways, including:
- YTD sales trailing target by ~24K (**95.2%** target attainment)
- Sales fairly balanced across product categories, with a recommendation to evaluate **profit margins** rather than sales volume alone
- Category- and product-level performance patterns worth further investigation

## 🧮 Key DAX Measures

| Measure | Purpose |
|---|---|
| `Total Sales` | Sum of all sales revenue |
| `Total Profit` | Sum of all profit |
| `YTD Sales` | Year-to-date cumulative sales using time intelligence |
| `Target of Year` / `Max value` | Reference values driving the sales gauge |
| `Total Quantity Sold` | Sum of units sold |
| `Total Orders` / `Count of Orders` | Distinct/total order counts |

## 🛠 Tools & Skills Used

- **Power BI Desktop** — data modeling, DAX, report design
- **Power Query** — data cleaning and transformation
- **DAX** — KPI, time-intelligence (YTD), and target-tracking measures
- Interactive elements: slicers, cross-filtering, navigation action buttons

## 🎯 What This Project Demonstrates

- Cleaning and modeling messy, real-world-style data under time constraints
- Writing DAX measures for KPIs, targets, and time intelligence
- Designing a multi-page, stakeholder-ready dashboard
- Turning metrics into narrative business insights and recommendations

## 📁 Repository Contents

```
Codathon_Project.pbix     # Power BI report file
README.md                 # Project documentation
```

## 🚀 How to View

1. Download `Codathon_Project.pbix`
2. Open with **Power BI Desktop** (free download from Microsoft)
3. Explore the three report pages using the tabs at the bottom

## 👤 Author

Built by **Nowrin** as part of a data analytics portfolio, focused on bridging domain expertise with data analytics through hands-on Power BI and Excel projects.

---

⭐ Feel free to explore, fork, or reach out with feedback!
