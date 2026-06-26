# 📊 Retail Sales Customer Analytics Dashboard

### End-to-End Business Intelligence Solution using Python & Power BI

> **Transforming raw retail transaction data into actionable business insights through data cleaning, exploratory data analysis, customer segmentation, and interactive business intelligence reporting.**

<p align="left">

<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/DAX-0078D4?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge"/>

</p>

---

# 🎯 Executive Summary

This project presents an end-to-end Retail Sales Analytics solution developed using **Python** and **Power BI** to transform raw transactional data into meaningful business insights.

The solution follows a complete analytics workflow, beginning with **data quality assessment**, **data cleaning**, **feature engineering**, and **exploratory data analysis (EDA)** in Python, followed by **RFM customer segmentation**, **Power BI data modeling**, **DAX-based KPI development**, and interactive dashboard creation.

The final dashboard enables business stakeholders to monitor organizational performance, identify revenue drivers, evaluate customer behavior, analyze product performance, and support data-driven business decisions through an intuitive and interactive reporting experience.

---

# 🚀 Project Highlights

✔ End-to-End Retail Sales Analytics Solution

✔ Data Cleaning & Quality Assessment using Python

✔ Feature Engineering for Business-Oriented Metrics

✔ Exploratory Data Analysis (EDA) to Identify Revenue and Customer Trends

✔ RFM-Based Customer Segmentation for Customer Value Analysis

✔ Interactive Power BI Dashboard with Dynamic DAX Measures

✔ Business-Focused KPI Development and Performance Monitoring

✔ Actionable Insights and Strategic Business Recommendations

---
# 📊 Dashboard Preview

The Power BI solution is designed across three analytical pages, enabling business stakeholders to monitor organizational performance, analyze sales trends, and evaluate customer behavior through interactive and data-driven reporting.

---

## 📈 Business Performance Overview

Provides a high-level view of business performance through executive KPIs, revenue trends, product performance, country analysis, and year-over-year growth indicators.

![Business Overview](dashboard/notebooks/screenshots/Business_Performance_Overview_Page.png)

### Key Business Insights

- Generated an overall revenue of approximately **8.8M** from retail transactions.
- **United Kingdom** emerged as the highest revenue-generating market.
- **November** recorded the highest monthly sales, highlighting seasonal demand.
- Identified the top-performing products contributing significantly to overall revenue.
- Monitored business performance using dynamic KPIs and Year-over-Year growth analysis.

---

## 💰 Sales & Revenue Analysis

Provides detailed analysis of sales performance across products, countries, and time periods using revenue trends, Pareto analysis, contribution analysis, and seasonal patterns.

![Sales & Revenue Analysis](dashboard/notebooks/screenshots/Sales_and_Revenue_Analysis_Page.png)

### Key Business Insights

- Identified products contributing the highest share of total revenue.
- Pareto analysis highlighted that a small percentage of products generated the majority of sales.
- Revenue trends revealed clear seasonal purchasing patterns across different months.
- Country-level analysis helped identify high-performing and low-performing markets.
- Dynamic time intelligence enabled comparison of sales performance across different periods.

---

## 👥 Customer Analytics

Evaluates customer behavior through revenue contribution, order frequency, RFM segmentation, customer concentration, and value-based customer analysis.

![Customer Analytics](dashboard/notebooks/screenshots/Customer_Analysis_Page.png)

### Key Business Insights

- Identified the **Top 10 customers** contributing the highest revenue.
- RFM analysis classified customers into actionable business segments such as **Champions**, **Potential Customers**, and **Lost Customers**.
- Champion customers contributed the highest share of overall revenue.
- Potential Customers represented the largest customer group, indicating strong opportunities for customer growth and retention.
- Customer concentration analysis helped identify the percentage of customers driving the majority of business revenue.
- 
---
# 📂 Dataset Overview

The analysis is based on the **Online Retail** transactional dataset containing customer purchase records from a UK-based online retail business. The dataset captures detailed sales transactions, enabling comprehensive analysis of revenue performance, customer purchasing behavior, and product-level trends.

### Dataset Characteristics

- **Domain:** Retail / E-Commerce
- **Granularity:** Transaction Level
- **Time Period:** December 2010 – December 2011
- **Primary Market:** United Kingdom (with transactions from multiple countries)

### Key Business Entities

| Entity | Description |
|---------|-------------|
| Invoice | Unique sales transaction identifier |
| Customer | Customer making the purchase |
| Product | Item purchased by the customer |
| Quantity | Number of units purchased |
| Unit Price | Selling price per product |
| Revenue | Calculated as Quantity × Unit Price |
| Invoice Date | Date and time of transaction |
| Country | Customer's country |

### Business Value of the Dataset

The dataset provides sufficient transactional detail to perform sales analysis, customer segmentation, product performance evaluation, geographic analysis, and business intelligence reporting through an end-to-end analytics workflow.

---
# 💼 Business Problem

Retail businesses generate thousands of sales transactions every day across products, customers, and geographic locations. While this transactional data contains valuable business information, it is often stored as raw records, making it difficult for decision-makers to extract meaningful insights.

The absence of a centralized analytical solution limits the ability to answer critical business questions, such as:

- How is the business performing overall?
- Which products generate the highest revenue?
- Which countries contribute most to sales?
- Who are the most valuable customers?
- Which customer segments should be targeted for retention and growth?
- What sales trends can support future business planning?

To address these challenges, this project develops an end-to-end analytics solution that transforms raw retail transaction data into interactive dashboards and actionable business insights, enabling stakeholders to make informed, data-driven decisions.

---
# 🎯 Business Objectives

The primary objective of this project was to develop an interactive Business Intelligence solution that enables stakeholders to monitor business performance and support strategic decision-making through data-driven insights.

The solution was designed to achieve the following objectives:

- Monitor overall business performance using executive-level KPIs.
- Identify high-performing products and major revenue contributors.
- Analyze sales performance across different countries and time periods.
- Understand customer purchasing behavior and buying patterns.
- Segment customers using RFM analysis to support targeted business strategies.
- Identify high-value customers and potential customer growth opportunities.
- Develop interactive dashboards for real-time business monitoring.
- Generate actionable insights to support revenue growth and customer retention initiatives.

---
## 🎯 Project Summary

This project focuses on analyzing retail sales data to uncover key business insights such as:

- Identifying high-value customer segments
- Understanding revenue contribution patterns
- Tracking sales performance over time
- Detecting churn and lost customers
- Supporting data-driven business decisions

The entire workflow follows an **end-to-end analytics pipeline** from raw data → cleaned dataset → insights → interactive dashboard.

---

## 📌 Business Problem Statement

Retail companies generate large volumes of transactional data, but struggle with:

- Lack of visibility into customer behavior
- Difficulty identifying top-performing customers/products
- No clear understanding of revenue drivers
- Reactive instead of proactive decision-making

👉 This project solves these challenges by building a structured analytics solution using Python + Power BI.
