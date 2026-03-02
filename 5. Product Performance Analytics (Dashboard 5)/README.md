# Product Performance Analytics Dashboard

**Organization:** Amazon (Simulated Enterprise E-Commerce Model)  
**Tool:** Power BI  
**Dataset:** Synthetic Global E-Commerce Dataset – 100,000 Transaction Records  
**Dashboard Focus:** Product Revenue Performance, Profitability Benchmarking, SKU Analysis, and Geographic Distribution  
**Date:** 23–25 February 2026  
**Created by:** Soham S. Amburle  

---

## Overview

The **Product Performance Analytics Dashboard** provides a strategic and operational view of product-level performance within a global e-commerce business model inspired by Amazon. Built using a synthetic dataset of 100,000 transaction-level records, this dashboard focuses on evaluating product revenue, margin efficiency, category contribution, SKU dominance, geographic distribution, and demand trends.

The primary objective of this dashboard is to help executive leadership, category managers, and merchandising teams answer key strategic questions:

- Which products generate the highest revenue?
- Is overall product margin meeting the profitability target?
- Which categories dominate revenue contribution?
- Are discounts impacting margin efficiency?
- Which countries generate the highest product revenue?
- How is product revenue trending over time?

By combining executive KPI monitoring, profitability benchmarking, interactive filtering, geographic mapping, SKU ranking, and trend analysis, the dashboard delivers a comprehensive and executive-ready product performance view.

---

## Business Storyline & Analytical Flow

### 1. Executive Product Snapshot – KPI Cards

The dashboard opens with eight KPI cards providing a high-level summary of product performance:

- **Total Revenue**
- **Total Gross Profit**
- **Gross Margin (%)**
- **Total Quantity Sold**
- **Total Orders**
- **Average Order Value (AOV)**
- **Average Selling Price (ASP)**
- **Average Discount (%)**

These KPIs establish immediate visibility into product scale, profitability health, pricing efficiency, and promotional intensity.

---

### 2. Interactive Filtering Controls – Slicers

All visuals dynamically respond to the following slicers:

- **Product Category**
- **Sub Category**
- **Brand**
- **Date (Between Range Filter)**
- **Sales Channel (Web / Mobile App)**
- **Customer Segment (Prime / Non-Prime)**

These controls allow dynamic product analysis across brand, category, customer segment, channel, and time period.

---

### 3. Profitability Benchmark – Gross Margin vs Target (Gauge)

- Value: Gross Margin (%)
- Target: 40%

This visual provides an executive-level margin benchmark comparison, indicating whether product profitability meets strategic expectations.

---

### 4. Revenue Distribution by Category – Donut Chart

- Legend: Product Category  
- Values: Total Revenue  

This visual highlights category-level contribution share and revenue concentration risk.

---

### 5. Geographic Product Performance – Filled Map

- Location: Customer Country  
- Color Intensity: Total Revenue  
- Tooltips: Total Gross Profit, Gross Margin (%), Total Orders  

This visual identifies high-performing markets and geographic revenue concentration.

---

### 6. SKU Performance Ranking – Top 10 Products by Revenue

- Axis: Product Name  
- Values: Total Revenue  
- Tooltips: Gross Profit, Gross Margin (%), Total Quantity  

This visual enables SKU-level revenue comparison and concentration analysis.

---

### 7. Product Revenue Trend – Line Chart

- X-Axis: Date (Year-Month)  
- Y-Axis: Total Revenue  
- Optional Comparison: Gross Profit  

This visual illustrates seasonal patterns, demand growth, and profitability trajectory over time.

---

## Key Takeaways

This dashboard enables stakeholders to:

- Monitor product-driven revenue and profitability at a glance  
- Benchmark margin performance against strategic targets  
- Identify high-performing SKUs and category leaders  
- Assess discount dependency impact  
- Compare geographic revenue distribution  
- Track product demand momentum over time  

By integrating KPI cards, slicers, benchmarking visuals, geographic mapping, SKU ranking, and time-series analysis, the dashboard delivers a professional and enterprise-grade product intelligence solution.

---

## Tools & Data

- **Visualization Tool:** Power BI  
- **Dataset:** Fully synthetic global e-commerce dataset  
- **Record Count:** 100,000 transaction-level records  
- **Time Period:** 2021–2024  
- **Model Design:** Star Schema (Fact_Orders with Dimension Tables for Date, Customer, Product, and Channel)  
- **Purpose:** Product analytics demonstration and enterprise BI portfolio development  

---

> **Note:** This project is not affiliated with Amazon. All data used in this dashboard is synthetic and created solely for learning, analysis, and portfolio demonstration purposes.

---

**Dashboard and Documentation by SOHAM S. AMBURLE**  
**23–25 February 2026**
