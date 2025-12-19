# pizza_data_visualization

## 🔎 Executive Summary

An end-to-end **SQL and Power BI analytics project** analyzing pizza sales performance through validated KPIs and interactive dashboards.  
The solution delivers insights into **sales trends, customer behavior, and product performance**, supporting data-driven business decisions.

## 🛠 Tools & Technologies

- **Database:** Microsoft SQL Server + SSMS 19.x  
- **BI Tool:** Power BI Desktop (June 2023 – New Card Visual)  
- **Spreadsheet:** Microsoft Excel 2021 (initial exploration only)

---

## 📊 Business Requirements

### KPI Requirements

| KPI | 
|---|---|
| Total Revenue | 
| Average Order Value | 
| Total Pizzas Sold |
| Total Orders |
| Average Pizzas per Order |

All KPIs are:
1. First calculated in **SQL**
2. Recreated in **Power BI using DAX**
3. Cross-validated for exact match

---

## 📈 Analytical Requirements

- Daily trend of total orders  
- Monthly trend of orders  
- % of sales by pizza category  
- % of sales by pizza size  
- Total pizzas sold by category  
- Top 5 and Bottom 5 pizzas by:
  - Revenue  
  - Quantity  
  - Total orders  

---

## 🏗 Project Architecture

| Layer | Technology | Purpose |
|---|---|---|
| Data Source | CSV | Raw transactional data |
| Database | SQL Server | Cleaning, KPIs, analytics |
| Logic Layer | SQL + DAX | Business rules & metrics |
| Visualization | Power BI | Dashboards & interactivity |

---

## 🧩 Project Workflow

### Step 1 – SQL Server Setup & Data Import
- Created database `PizzaDB`
- Imported CSV into table `pizza_sales`
- Validated row count and data types

### Step 2 – SQL KPI Queries
- Implemented all KPIs using SQL
- Used `CAST` to control decimal precision
- Saved queries and outputs for validation

### Step 3 – SQL Analytical Queries
- Daily and monthly trends
- Sales contribution by category and size
- Best and worst sellers using aggregations and ranking

### Step 4 – SQL Documentation
- Maintained SQL documentation with:
  - Requirement
  - Query
  - Result snapshot  

📁 `docs/sql_queries.md`

### Step 5 – Power BI Data Connection
- Connected Power BI directly to SQL Server
- Alternative CSV load option supported

### Step 6 – Power Query Data Cleaning
- Data type corrections
- Date derivations (year, month, weekday)
- Validation of numeric fields

### Step 7 – DAX Measures
- Created DAX measures mirroring SQL logic
- Verified Power BI numbers against SQL results

---

## 📊 Dashboard Design

### 1️⃣ Sales Overview Dashboard
- KPI Cards (Revenue, Orders, AOV, Pizzas Sold)
- Daily & monthly order trends
- Sales distribution by category & size
- Funnel chart for pizzas sold
- Interactive slicers and cross-filtering

---

### 2️⃣ Best & Worst Sellers Dashboard
- Top 5 & Bottom 5 pizzas by:
  - Revenue
  - Quantity
  - Orders
- Category-level filtering
- Business insight summaries

---

## 🧭 Navigation & UX

- Left-side navigation buttons
- Clear page switching
- Active page highlighting
- Smooth cross-filtering across visuals

---

## 💡 Business Insights Enabled

- Identify peak demand days and hours  
- Optimize staffing and inventory  
- Focus marketing on high-performing pizzas  
- Detect underperforming products  
- Support pricing and menu optimization decisions  

---

## 📁 Repository Structure

