# 🧠 Maven Market Power BI Report

## 📊 Project Overview
This Power BI project — **Maven Market Report** — provides a comprehensive analytics view of **sales, profitability, and customer performance** for the Maven Market retail business.  
It visualizes key performance metrics across regions, product categories, and time periods to support **data-driven business decisions**.

---

## 🧩 Objectives
- Analyze **sales trends** and **profitability** by region, product category, and customer segment.
- Track **top-performing products** and **sales representatives**.
- Identify **underperforming regions** or categories for strategic improvement.
- Enable management to explore data interactively using Power BI dashboards.

---

## 🗂️ Dataset Summary
| Table | Description |
|--------|--------------|
| **Sales** | Transactional sales data including quantity, revenue, and profit |
| **Products** | Product hierarchy with category, subcategory, and price info |
| **Customers** | Customer demographics and loyalty details |
| **Stores** | Store details (region, city, and sales team assignments) |
| **Calendar** | Date dimension for time-series analysis |

---

## 📈 Key Insights
- 🏆 **Top Region:** East Coast generated the highest total sales and profit.
- 📦 **Most Profitable Category:** “Household” and “Beverages” categories outperform others.
- 💸 **Seasonal Trend:** Q4 shows peak performance driven by holiday campaigns.
- 👥 **Customer Loyalty:** High-value customers account for 35% of total revenue.

---

## 🧠 Power BI Features Used
- **Data Modeling**: Star schema with fact (Sales) and dimension tables.
- **DAX Measures**:
  - `Total Sales = SUM(Sales[Revenue])`
  - `Profit Margin = DIVIDE([Profit], [Sales])`
  - `YoY Growth = CALCULATE([Total Sales], DATEADD(Calendar[Date], -1, YEAR))`
- **Visualizations**:
  - KPI cards, line charts, clustered bar charts, slicers, and interactive drill-throughs.
- **Dashboard Design**: Clean, professional layout with filters for Region, Product, and Date.

---

## 🧰 Tools & Technologies
| Tool | Purpose |
|------|----------|
| **Power BI Desktop** | Data modeling, visualization, and dashboard creation |
| **Excel / CSV Files** | Raw data sources |
| **DAX** | Business logic and calculations |
| **Power Query (M)** | Data cleaning and transformation |

---

## 🗃️ File Structure
