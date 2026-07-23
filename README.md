Dealer-360-Development-Dashboard-for-Consumer-Durables

## 📌 Project Overview

The **Dealer 360° Development Dashboard** is a comprehensive Power BI solution designed to provide a complete view of dealer performance across sales, inventory, service, finance, and customer engagement for the consumer durables industry. The dashboard enables business leaders, regional managers, and sales teams to monitor dealer performance, identify growth opportunities, and improve operational efficiency through interactive analytics.

---

# 🎯 Business Problem

Consumer durable companies manage a large network of dealers across multiple regions. Monitoring dealer performance manually is time-consuming and often leads to delayed decision-making. Business stakeholders require a centralized dashboard to track sales performance, inventory availability, service quality, customer satisfaction, and dealer profitability.

This dashboard consolidates dealer-related information into a single platform, enabling faster and data-driven business decisions.

---

# 🎯 Project Objectives

- Monitor dealer sales performance across regions.
- Analyze product-wise and category-wise sales.
- Track dealer inventory levels and stock movement.
- Measure service performance and warranty claims.
- Evaluate dealer profitability and revenue contribution.
- Identify top-performing and underperforming dealers.
- Improve dealer engagement and customer satisfaction.

---

# 📊 Key Performance Indicators (KPIs)

- Total Dealers
- Active Dealers
- Total Revenue
- Total Sales Quantity
- Average Dealer Revenue
- Monthly Sales Growth %
- Inventory Value
- Inventory Turnover
- Dealer Profit Margin
- Customer Satisfaction Score (CSAT)
- Warranty Claim Rate
- Service Completion Rate

---

# 📁 Dataset Information

The dataset includes dealer and business performance information such as:

- Dealer ID
- Dealer Name
- Dealer Category
- Dealer Type
- Region
- State
- City
- Sales Executive
- Product Category
- Product Name
- Invoice Date
- Sales Quantity
- Sales Value
- Revenue
- Profit
- Inventory Quantity
- Stock Value
- Warranty Claims
- Service Requests
- Customer Rating
- Dealer Status
- Payment Status

---

# 📈 Dashboard Pages

## 1. Executive Summary

Provides an overview of overall business performance including:

- Total Revenue
- Active Dealers
- Sales Growth
- Inventory Value
- Profit Margin

---

## 2. Dealer Performance

Displays:

- Dealer-wise Revenue
- Dealer Ranking
- Monthly Sales Performance
- Dealer Contribution %
- Target vs Achievement

---

## 3. Sales Analysis

Includes:

- Product Category Performance
- Brand-wise Sales
- Region-wise Revenue
- Monthly Sales Trend
- Top Selling Products

---

## 4. Inventory Dashboard

Shows:

- Available Stock
- Low Stock Products
- Inventory Turnover
- Product Availability
- Warehouse Distribution

---

## 5. Service & Warranty Analysis

Displays:

- Service Requests
- Warranty Claims
- Average Resolution Time
- Customer Satisfaction
- Service Performance by Dealer

---

## 6. Regional Performance

Provides:

- Revenue by State
- Revenue by Region
- Dealer Distribution
- Sales Growth by Region
- Market Share Analysis

---

# 📊 Power BI Features Used

- Power Query
- DAX Measures
- Star Schema Data Modeling
- Interactive KPI Cards
- Dynamic Titles
- Drill-through Reports
- Bookmarks
- Tooltips
- Conditional Formatting
- Slicers
- Map Visualizations

---

# 📐 Data Model

The dashboard follows a **Star Schema** data model.

### Fact Table

- Fact_DealerSales

### Dimension Tables

- Dim_Dealer
- Dim_Product
- Dim_Date
- Dim_Region
- Dim_Customer
- Dim_Service

---

# 📷 Dashboard Preview

Add screenshots inside the **Images** folder.

Example:

- Executive Dashboard
- Dealer Performance
- Sales Analysis
- Inventory Dashboard
- Service Dashboard
- Regional Analysis

---

# 📂 Repository Structure

```
Dealer-360-Development-Dashboard/
│
├── Dataset/
│   └── Dealer360_Data.xlsx
│
├── Dashboard/
│   └── Dealer360_Dashboard.pbix
│
├── Images/
│   ├── Executive Dashboard.png
│   ├── Dealer Performance.png
│   ├── Sales Analysis.png
│   ├── Inventory Dashboard.png
│   ├── Service Dashboard.png
│   └── Regional Dashboard.png
│
├── DAX/
│   └── Measures.md
│
