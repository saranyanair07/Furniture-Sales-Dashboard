# 🪑 FurniturePro Sales & Customer Insights Analysis

## 📌 Project Overview

FurniturePro Sales & Customer Insights Analysis is an interactive Power BI analytics project designed to provide a comprehensive view of sales performance, customer behavior, product performance, regional performance, and profitability.

The objective of the project was to transform sales and customer data into actionable business insights that can help stakeholders understand revenue drivers, identify underperforming areas, evaluate customer value, and support data-driven decision-making.

---

## 🎯 Business Objectives

The analysis focuses on:

- Monitoring overall sales and profitability
- Understanding sales performance across regions and customer segments
- Identifying top-performing products and customers
- Tracking sales trends and year-over-year performance
- Comparing actual sales against targets
- Analyzing product returns
- Identifying high-value and at-risk customers
- Performing RFM-based customer segmentation
- Understanding customer acquisition trends
- Evaluating the impact of discounts on profitability
- Identifying customers contributing significantly to revenue using Pareto analysis

---

## 📊 Dashboard Pages

The Power BI solution consists of the following major analytical areas:

### 1. Executive Summary

Provides a high-level overview of business performance through key KPIs and interactive visualizations.

Key metrics include:

- Total Net Sales
- Total Profit
- Profit Margin
- Total Customers
- Total Products
- Return Rate
- Target Achievement

The dashboard helps stakeholders quickly understand overall business performance and identify major trends.

---

### 2. Segment, Category & Region Analysis

Provides deeper analysis across:

- Customer segments
- Product categories
- Sub-categories
- Regions
- States

Users can compare sales contribution, profitability, returns, and performance across different business dimensions.

---

### 3. Sales Performance Analysis

The sales performance section analyzes:

- Overall sales trends
- Product performance
- Customer performance
- Year-over-year comparison
- Sales anomalies
- Regional performance

The analysis includes anomaly detection to highlight unusual sales spikes or patterns that may indicate promotions, demand changes, or operational issues.

---

### 4. Target & Benchmark Analysis

This section compares actual sales against predefined targets.

Key analysis includes:

- Actual Sales vs Target
- Target Achievement %
- Region-wise performance
- State-wise performance
- Geographic target performance

This helps identify regions and states that are meeting or falling below their targets.

---

### 5. What-If Analysis

An interactive scenario analysis was developed to understand how changes in discount levels could affect profitability.

Users can adjust the discount percentage and dynamically evaluate:

- Predicted Profit
- Profit Margin
- Profit impact by customer segment
- Profit sensitivity to discount changes

This allows stakeholders to evaluate pricing and discount scenarios before making business decisions.

---

### 6. Pareto Analysis

A Pareto analysis was implemented to identify the customers contributing the majority of sales.

The analysis ranks customers based on sales contribution and uses a cumulative percentage to identify high-value customers following the 80/20 principle.

The analysis includes:

- Customer Sales Contribution
- Cumulative Sales %
- Top Customers
- Customer Profit
- Customer Margin %

---

### 7. Customer Analysis

The customer analytics section provides insights into:

- Total customers
- Average revenue per customer
- Customer distribution by segment
- Top customers by revenue
- Salesperson performance
- Revenue contribution by customer segment

This helps identify high-value customers and understand the overall customer base.

---

### 8. Customer Segmentation – RFM Analysis

RFM analysis was used to segment customers based on:

- **Recency** – How recently the customer purchased
- **Frequency** – How frequently the customer purchased
- **Monetary** – How much revenue the customer generated

Customers were categorized into segments such as:

- Champions
- Loyal Customers
- Potential Loyalists
- At Risk
- Low Value

The segmentation helps identify customers requiring retention strategies and customers with strong future potential.

---

### 9. Customer Acquisition & Sales

This section focuses on new customer acquisition and its contribution to overall revenue.

Key metrics include:

- New Customers
- Sales from New Customers
- New Customer Quantity
- Average Discount Offered
- Existing vs New Customer Revenue
- New Customer Acquisition Trend
- Salesperson Performance

---

## 🔍 Key Business Insights

Based on the analysis:

- Total net sales were approximately **$2.12M**.
- The business generated sales from **793 customers** and **1,862 products**.
- Overall profit margin was approximately **12.47%**.
- The return rate was approximately **8.53%**, highlighting an opportunity for improvement.
- The **Consumer segment** contributed the highest sales compared with Corporate and Home Office.
- Sales showed a decline after 2020, indicating a potential slowdown in demand.

---

## 💡 Business Value

The dashboard enables business stakeholders to:

- Quickly identify high-performing and underperforming regions
- Monitor sales against targets
- Identify high-value customers
- Detect unusual sales patterns
- Understand customer behavior
- Evaluate discount and pricing scenarios
- Identify customer retention opportunities
- Support data-driven sales and product strategies

---

## 🛠️ Tools & Technologies

- **Power BI** – Dashboard development and visualization
- **DAX** – KPI calculations, dynamic measures and business logic
- **Power Query** – Data transformation and preparation
- **Data Modeling** – Relationships and analytical data model
- **Excel / Structured Data** – Data source and analysis

---

## 📈 Key Power BI Features Used

- Interactive slicers
- KPI Cards
- Drill-down
- Drill-through
- Maps
- Anomaly Detection
- What-If Parameters
- Pareto Analysis
- RFM Segmentation
- Dynamic filtering
- Year-over-Year analysis
- Conditional analysis
- Interactive navigation

---

## 📁 Project Structure

```text
FurniturePro-Sales-Customer-Insights/
│
├── README.md
│
├── Dashboard/
│   └── FurniturePro_Sales_Customer_Insights.pbix
│
├── Documentation/
│   └── FurniturePro_Dashboard_Guide.pptx
│
├── Screenshots/
│   ├── Executive_Summary.png
│   ├── Sales_Performance.png
│   ├── Customer_Analysis.png
│   ├── RFM_Segmentation.png
│   └── What_If_Analysis.png
│
└── Data/
    └── Dataset.xlsx
