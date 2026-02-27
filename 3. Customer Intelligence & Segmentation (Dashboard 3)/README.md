# Customer Intelligence & Segmentation Dashboard

**Organization:** Amazon (Simulated Enterprise E-Commerce Model)  
**Tool:** Power BI  
**Dataset:** Synthetic Global E-Commerce Dataset – 100,000 Transaction Records  
**Dashboard Focus:** Customer Value, Loyalty, Segmentation, Geographic Distribution, and Behavioral Analytics  
**Date:** 13–16 February 2026  
**Created by:** Soham S. Amburle  

---

## Overview

The **Customer Intelligence & Segmentation Dashboard** delivers a comprehensive analytical view of customer behavior within a global e-commerce business model inspired by Amazon. Built using a synthetic dataset of 100,000 transaction-level records, this dashboard focuses on understanding customer value, loyalty patterns, subscription penetration, and geographic segmentation.

The primary objective of this dashboard is to help executive leadership, marketing teams, and customer strategy stakeholders answer critical questions:

- How many active customers do we have?  
- Are customers loyal and returning?  
- What is the lifetime value of our customer base?  
- How strong is Prime membership penetration?  
- Which customer segments drive the most value?  
- How does behavior vary across geography?  

By integrating KPI monitoring, behavioral segmentation visuals, value-based scatter analysis, and geographic breakdowns, the dashboard provides a strategic and executive-ready view of customer intelligence.

---

## Business Storyline & Analytical Flow

### 1. Executive Customer Snapshot – KPI Cards

The dashboard opens with six KPI cards providing an immediate overview of customer performance:

- **Total Customers:** Distinct count of active customers  
- **Total Orders:** Total transaction volume  
- **Average Order Value (AOV):** Revenue per order  
- **Customer Lifetime Value (LTV):** Revenue per customer  
- **Repeat Purchase Rate (%):** Percentage of customers with multiple orders  
- **Prime Customer (%):** Share of Prime customers within total customer base  

These KPIs establish a high-level understanding of customer growth, value, and loyalty before deeper behavioral analysis.

---

### 2. Interactive Filtering Controls – Slicers & Gauge

All visuals dynamically respond to the following slicers:

- **Date (Between Range Filter)**  
- **Customer Segment (Prime / Non-Prime)**  
- **Customer Country**

In addition, a **Gauge Visual** monitors:

- **Repeat Purchase Rate (%)** with a strategic benchmark target (~40%)

This section enables dynamic segmentation and instantly communicates overall customer retention health.

---

### 3. Behavioral Segmentation – Order Frequency Distribution

**Customer Order Frequency Distribution – Clustered Column Chart**

- Axis: Order Frequency Bands (1 Order, 2–3 Orders, 4–5 Orders, 6+ Orders)  
- Values: Total Customers  

This visual highlights:

- Proportion of one-time buyers  
- Strength of repeat purchasing behavior  
- Size of highly loyal customer segments  
- Potential retention improvement opportunities  

It provides actionable insight into customer loyalty structure.

---

### 4. Customer Value vs Loyalty Analysis – Scatter Plot

**Customer Value vs Loyalty – Scatter Plot**

- X-Axis: Orders per Customer  
- Y-Axis: Revenue per Customer  
- Details: Customer_ID  
- Legend: Customer Segment  

This visual identifies distinct customer groups:

- High frequency & high value (VIP customers)  
- High value but low frequency (at-risk customers)  
- Frequent but low-value buyers  
- Low engagement customers  

It enables strategic customer targeting, loyalty program optimization, and retention planning.

---

### 5. Strategic Segmentation Matrix – Geography & Segment Performance

**Customer Segment × Country – Matrix Visualization**

- Rows: Customer Segment  
- Columns: Customer Country  
- Values:
  - Total Customers  
  - Total Revenue  
  - Average Order Value (AOV)  
  - Repeat Purchase Rate (%)  

This matrix provides insight into:

- Prime penetration across countries  
- Geographic customer value comparison  
- Regional loyalty patterns  
- Segment-level revenue concentration  

It introduces a global strategic perspective to customer analytics.

---

### 6. Subscription Penetration – Pie Chart

**Prime vs Non-Prime Distribution – Pie Chart**

- Legend: Customer Segment  
- Values: Total Customers  

This visual provides a clear breakdown of subscription penetration within the customer base and supports strategic analysis of Prime membership impact.

---

## Key Takeaways

This dashboard enables executive and marketing teams to:

- Monitor customer growth and engagement at a glance  
- Measure loyalty and repeat purchasing behavior  
- Identify high-value customer segments  
- Evaluate Prime subscription penetration  
- Compare geographic customer performance  
- Support data-driven retention and segmentation strategies  

By combining executive KPIs, interactive filtering, behavioral banding, value-based scatter analysis, and geographic segmentation, the dashboard delivers a professional, enterprise-grade view of customer intelligence.

---

## Tools & Data

- **Visualization Tool:** Power BI  
- **Dataset:** Fully synthetic global e-commerce dataset  
- **Record Count:** 100,000 transaction-level records  
- **Time Period:** 2021–2024  
- **Model Design:** Star Schema (Fact_Orders with Dimension Tables for Date, Customer, Product, and Channel)  
- **Purpose:** Customer analytics demonstration, segmentation modeling, and enterprise BI portfolio development  

---

> **Note:** This project is not affiliated with Amazon. All data used in this dashboard is synthetic and created solely for learning, analysis, and portfolio demonstration purposes.

---

**Dashboard and Documentation by SOHAM S. AMBURLE**  
**13–16 February 2026**
