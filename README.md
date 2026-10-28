# 📊 Business Insight 360 – Power BI Dashboard

An interactive Power BI project that gives a **360° view of key business metrics** across Finance, Sales, Marketing, Supply Chain and Executive Management for a consumer goods company.

It helps analyse performance, track KPIs and turn raw data into clear visual insights for decision-making. Built as part of the Codebasics Power BI course (Business Insights 360) and later upgraded with advanced features from Power BI 4.0.

---

## 🚀 What's New (Power BI 4.0 Upgrade)

- **Data extended to FY2026:** loaded FY2023 to FY2026 data, bringing the model to roughly **3 million rows**.
- **Incremental refresh:** configured so only new and recent data is refreshed instead of reloading the full dataset every time.
- **Row-Level Security (RLS):** role-based access so users only see the data they are allowed to see.
- **Time Intelligence View:** a new view comparing YTD, YTG (year to go) and last year YTD, with change and change %, for Gross Sales, Net Invoice Sales, Net Sales, Gross Margin and Net Profit.

---

## 🏠 Home View

📌 File: [Home View](Home%20View.png)

The Home View is the gateway to the dashboard, with direct navigation to:

✅ Finance View

✅ Sales View

✅ Marketing View

✅ Supply Chain View

✅ Executive View

Users start from one central page and jump straight to the business area they need.

---

## 💰 Finance View

📌 File: [Finance View](Finance%20View.png)

Presents the **Profit & Loss (P&L) statement** and financial KPIs.

✅ Gross Sales, Net Invoice Sales and Post Deductions

✅ Total Manufacturing and Operational Costs

✅ Gross Margin % and Net Profit %

✅ Benchmark comparison against last year or targets

✅ Region-wise and category-wise performance breakdown

Helps finance teams keep track of financial health and profitability.

---

## 📈 Sales View

📌 File: [Sales View](Sales%20View.png)

Gives deep insights into **customer and product sales performance**.

✅ Net Sales (NS) and Gross Margin (GM) by customer and product

✅ Scatter plot comparing Gross Margin % against Net Sales

✅ Top and bottom performing customers such as Amazon, Walmart and Flipkart

✅ Contribution analysis across regions (APAC, NA, EU, LATAM)

✅ KPI cards showing total sales and gross margin trends

Helps the sales team identify revenue drivers and underperforming areas.

---

## 📊 Marketing View

📌 File: [Marketing View](Marketing%20View.png)

Focuses on **segment and product category analysis**.

✅ Net Sales and Gross Margin by segment (Notebook, Peripherals, Desktop, Storage, Accessories)

✅ Net Profit % and variance trends

✅ Bubble chart for market and product positioning

✅ Clear view of profitable vs underperforming categories

Helps marketing teams evaluate product performance and align campaigns with growth areas.

---

## 🚚 Supply Chain View

📌 File: [Supply Chain View](Supply%20Chain%20View.png)

Focuses on operational performance and demand forecasting.

✅ Forecast Accuracy % (FCA) with historical comparison

✅ Net and Absolute Error trends over time

✅ Key metrics by customer and product segment

✅ Risk indicators: Out of Stock (OOS) and Excess Inventory (EI)

Supports supply chain efficiency and risk monitoring.

---

## 🔎 Executive View

📌 File: [Executive View](Executive%20View.png)

A high-level summary of business performance for leadership.

✅ Net Sales, Gross Margin and Net Profit %

✅ Forecast Accuracy %

✅ Top customers and products by revenue contribution

✅ Sub-region performance with risk and market share analysis

Built for quick decision-making at the leadership level.

---

## ⏱ Time Intelligence View

📌 File: [Time Intelligence View](Time%20Intelligence%20View.png)

Added in the Power BI 4.0 upgrade. It compares current performance with last year and with what is still to come.

✅ YTD, YTG, LY YTD, Change and Change % in one table

✅ Covers Gross Sales (GS), Net Invoice Sales (NIS), Net Sales (NS), Gross Margin (GM) and Net Profit

✅ Year selector from 2018 to 2025, plus a 2026 estimate

✅ Built with DAX time intelligence measures

*YTD = Year to Date, YTG = Year to Go, LY = Last Year.*

---

## 🛠 Tech Stack and Skills

- **Power BI Desktop:** report design, interactive visuals, navigation
- **DAX:** measures, KPIs, time intelligence
- **Power Query:** data loading and transformation
- **Data Modeling:** star schema with fact and dimension tables
- **Row-Level Security (RLS):** role-based data access
- **Incremental Refresh:** efficient refresh of a ~3M-row dataset

---

## 📖 How to Use

1. Use the filters on the left panel to slice data by Year, Quarter, Region or Category.
2. Switch between views (Executive, Finance, Sales, Marketing, Supply Chain) using the top navigation bar.
3. Hover over charts and KPIs to see tooltips with detailed insights.
4. Use the interactive visuals (bar charts, line charts, tables) to drill down into customer, product or region-level performance.

---

## 🔗 Dashboard File

BI_360 Power BI Dashboard: https://drive.google.com/file/d/1KxgMn9QOKpQLxbgjr_hNpG-VjLhe0brh/view?usp=sharing
