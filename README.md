# 🍕 Pizza Sales Data Visualization – SQL & Power BI

## 🔎 Executive Summary
An end-to-end **SQL and Power BI analytics project** focused on analyzing pizza sales performance using validated KPIs and interactive dashboards.  
The project provides insights into **sales trends, customer behavior, and product performance**, enabling data-driven business decisions.

---

## 🛠 Tools & Technologies
- **Database:** Microsoft SQL Server
- **BI Tool:** Power BI Desktop
- **Spreadsheet:** Microsoft Excel

---

## 📊 Business Requirements

### Key Performance Indicators (KPIs)
- **Total Revenue**
- **Average Order Value**
- **Total Pizzas Sold**
- **Total Orders**
- **Average Pizzas per Order**

**KPI Implementation Approach**
1. Calculated first using **SQL**
2. Recreated using **DAX in Power BI**
3. **Cross-validated** to ensure accuracy and consistency

---

## 📈 Analytical Requirements
- Daily and monthly order trends  
- Sales contribution by **pizza category** and **pizza size**  
- Total pizzas sold by category  
- **Top & Bottom 5 pizzas** based on:
  - Revenue
  - Quantity sold
  - Total orders  

---

## 🏗 Project Architecture

| Layer | Technology | Purpose |
|------|------------|---------|
| Data Source | CSV | Raw transactional data |
| Database | SQL Server | Data cleaning and KPI logic |
| Logic Layer | SQL + DAX | Business rules and calculations |
| Visualization | Power BI | Dashboards and insights |

---

## 🧩 Project Workflow
1. **SQL Setup & Import** – Loaded CSV data into SQL Server and validated structure  
2. **KPI Queries** – Implemented and verified all KPIs using SQL  
3. **Analysis Queries** – Created queries for trends, category splits, and best/worst sellers  
4. **Documentation** – Stored SQL queries and results in [Pizza Sales Queries](sql/Pizza%20Sales%20Queries.md)
5. **Power BI Connection** – Connected Power BI directly to SQL Server  
6. **Power Query** – Applied data typing and date derivations  
7. **DAX Measures** – Recreated KPIs and validated results against SQL outputs  

---

## 📊 Dashboard Design

### 📌 Sales Overview Dashboard
- KPI cards (Revenue, Orders, AOV)
- Daily and monthly sales trends
- Category and size contribution analysis
- Interactive slicers with cross-filtering

### 📌 Best & Worst Sellers Dashboard
- Top & Bottom 5 pizzas by revenue, quantity, and orders
- Category-level filtering
- Business-focused insight summaries

---

## 🧭 Navigation & User Experience
- Left-side navigation buttons
- Clear separation of dashboard pages
- Highlighted active page for usability
- Smooth cross-filtering across visuals

---

## 💡 Business Insights Enabled
- Identification of peak demand periods  
- Optimization of staffing and inventory planning  
- Focused promotions on high-performing products  
- Early detection of underperforming pizzas  
- Support for pricing and menu optimization decisions  

---

## 🖼️ Dashboard Previews

Screenshots of both dashboards are available below for quick reference.

- 🏠 [Home](powerbi/Home.png)
- 📊 [Best & Worst Sellers](powerbi/Best_Worst_Sellers.png)


