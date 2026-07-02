# 📊 Sales Performance Analytics Dashboard

> An interactive Business Intelligence solution built with **Power BI**, leveraging a **SQL Server Data Warehouse** to transform sales data into actionable business insights through executive reporting, advanced analytics, and interactive dashboards.

---

## 📖 Project Overview

This project presents an end-to-end **Sales Performance Analytics Dashboard** developed in **Power BI** to support strategic business decision-making through interactive reporting and data visualization.

The dashboard is built on top of a previously developed **SQL Server Data Warehouse**, utilizing the **Gold Layer** analytical tables (`fact_sales`, `dim_customers`, and `dim_products`) as the primary data source. While the SQL project focuses on data integration, ETL processes, and dimensional modeling, this repository demonstrates how curated business data can be transformed into meaningful insights through Business Intelligence.

The solution delivers a comprehensive analytical view of business performance across four key dimensions:

- 📈 Executive Performance
- 📦 Product Analytics
- 👥 Customer Analytics
- 🌍 Geographic Analytics

The dashboard was designed with a strong emphasis on **interactive analytics, business storytelling, and executive reporting**, enabling decision-makers to explore business performance from multiple perspectives through a clean and intuitive user experience.

---

# 🎯 Business Objectives

The primary objectives of this dashboard are to:

- Monitor overall business performance through executive-level KPI reporting.
- Analyze revenue trends and sales performance over time.
- Evaluate product performance and identify high-revenue products.
- Measure category-level revenue contribution and revenue concentration.
- Segment customers based on revenue contribution and purchasing frequency.
- Analyze customer distribution across different behavioral segments.
- Compare sales performance across geographic regions.
- Benchmark a selected country against the highest-performing market.
- Support strategic decision-making through interactive, data-driven analytics.

---

# 🏗️ Solution Architecture

This dashboard is part of an end-to-end Business Intelligence solution.

The analytical data model is powered by the **Gold Layer** of a previously developed SQL Server Data Warehouse. The SQL project is responsible for data integration, cleansing, transformation, and dimensional modeling, while this Power BI project focuses on business analytics, executive reporting, and interactive dashboard development.

```text
Source Systems
      │
      ▼
SQL Server Data Warehouse
(Bronze → Silver → Gold)
      │
      ▼
Gold Layer
(fact_sales, dim_customers, dim_products)
      │
      ▼
Power BI Semantic Model
      │
      ▼
Interactive Sales Analytics Dashboard
```

> **Related Project:** SQL Server Data Warehouse (https://github.com/Narges-Sh-89/SQL-Data-Warehouse-Project)

---

# 📑 Dashboard Pages

## 📈 Executive Overview

### Objective

Provide executives with a consolidated view of overall business performance through interactive KPIs and high-level sales analytics.

### Highlights

- Executive KPI Cards
- Revenue Trend Analysis
- Revenue by Product Category
- Revenue by Country
- Year-over-Year (YoY) Growth Analysis

### Business Value

This page serves as the executive dashboard of the solution, enabling stakeholders to monitor business performance, evaluate revenue trends, compare regional performance, and assess year-over-year growth from a single, interactive reporting interface.

---

## 📦 Product Analytics

### Objective

Analyze product performance to identify revenue-driving products, evaluate category performance, and understand revenue concentration across the product portfolio.

### Highlights

- Top 15 Best-Selling Products
- Revenue by Product Category
- Dynamic Pareto Analysis with configurable **Top N**
- Cumulative Revenue Share (%) Analysis
- Product Performance Segmentation Matrix (High / Medium / Low Revenue)

### Business Value

This page helps decision-makers identify the products generating the highest business value, evaluate category performance, understand revenue concentration using Pareto analysis, and classify products into performance tiers to support inventory planning, pricing strategies, and product portfolio optimization.

---

## 👥 Customer Analytics

### Objective

Analyze customer purchasing behavior by segmenting customers based on revenue contribution and purchase frequency, enabling business users to better understand customer distribution and revenue concentration.

### Highlights

- Customer Revenue Segmentation (High, Medium, Low)
- Purchase Frequency Segmentation
- Revenue Distribution by Revenue Segment
- Customer Count by Revenue Segment
- Revenue Distribution by Purchase Frequency Segment
- Customer Count by Purchase Frequency Segment
- Comparative Analysis of Customer Count vs Revenue

### Business Value

This page provides a comprehensive understanding of customer purchasing behavior by analyzing customers from two complementary perspectives: revenue contribution and purchase frequency. It enables stakeholders to evaluate customer distribution, identify revenue concentration across customer segments, and better understand purchasing patterns to support customer segmentation, marketing initiatives, and business planning.

---

## 🌍 Geographic Analytics

### Objective

Compare the highest-performing country with a user-selected country to evaluate revenue performance, market share, category contribution, and sales trends.

### Highlights

- Top Revenue Country Identification
- Selected Country Comparison
- Revenue Difference Analysis
- Revenue Share Comparison
- Revenue by Product Category
- Monthly Sales Trend Comparison

### Business Value

This page enables business users to benchmark regional performance by comparing a selected country against the highest revenue-generating market. It highlights performance gaps, market share differences, category-level revenue contribution, and monthly sales trends, helping stakeholders identify growth opportunities and regional strengths.

---

### 📊 Market Benchmark

#### Objective

Benchmark a selected country against all markets to evaluate revenue performance, market share, and competitive position.

#### Highlights

- Dynamic Country Selector
- Revenue Benchmark Analysis
- Revenue Difference vs Selected Country
- Revenue Share Analysis
- Market Position (Ranking)
- Year-based Performance Comparison

#### Business Value

This page enables business users to benchmark any selected market against all available countries, providing deeper insight into competitive positioning, revenue contribution, and market performance.
