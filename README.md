# 📊 Sales Performance Analytics Dashboard

## 📌 Project Overview
An interactive Business Intelligence (BI) dashboard designed to monitor and analyze sales performance, order operations, and regional metrics. 

The underlying data was sourced from **Excel Datasets**, transformed, and structured into a **Data Warehouse using a Star Schema model** (Fact & Dimension tables). This data model powers the dashboard to provide executive-level visibility into financial KPIs, category volume, order statuses, and sales territories.

---

## 🏗️ Data Architecture & Modeling
- **Data Source:** Raw sales data exported from Excel sheets.
- **Data Warehouse Model:** **Star Schema Design**
  - **Fact Table:** Orders Fact table containing numerical measures (Order Quantities, Sub-Total, Tax, Freight, Total Due).
  - **Dimension Tables:** Standardized lookup tables for Date, Product/Category, Order Status, and Territory.

---

## 📈 Executive Summary (Key KPIs)
- **Total Orders (#order):** 1K+
- **Order Line Items (#OrderDetail):** 24K+
- **Sub-Total Revenue:** $30M
- **Total Tax:** $3M
- **Total Freight Cost:** $916K
- **Total Due Revenue:** $34M

---

## 🔍 Key Dashboard Insights & Visuals

1. **Order Trends Over Time (`order by Date`):**
   - Historical tracking of order volumes from **2012 to 2014**, identifying seasonal peaks and trend fluctuations.

2. **Category Volume Breakdown (`OrderQty by Category`):**
   - Tree-map visual representing product demand across key retail categories: **Bikes**, **Components**, **Clothing**, and **Accessories**.

3. **Order Status Tracking (`order by Status`):**
   - Operational breakdown tracking fulfillment flow across **Approved**, **In Process**, **Shipped**, **Cancelled**, **Rejected**, and **Backordered** orders.

4. **Regional Sales Analysis (`order and Total_Due by Territory`):**
   - Dual-axis visual comparing order counts and total revenue across international sales territories, highlighting top markets like **Canada**, **Northwest**, and **France**.

---

## 🛠️ Tech Stack
- **Data Source:** Excel Sheets
- **Data Modeling:** Data Warehouse (Star Schema Architecture)
- **BI & Visualization:** Power BI

---
