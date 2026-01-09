# olist-ecommerce-powerbi-dashboard
Power BI dashboard analyzing sales, orders, and product performance using the Olist Brazilian e-commerce dataset.
#  Olist E-Commerce Analytics Dashboard (Power BI)

---

##  Project Overview

This project is a **Power BI dashboard** built using the **Olist Brazilian e-commerce dataset** to analyze sales performance, order behavior, and product and customer trends.

The objective of the dashboard is to present **reliable business metrics** and make overall performance easy to understand at a glance, while still allowing deeper exploration where needed.

---

##  Business Context

E-commerce data is typically stored at multiple levels of detail. In the Olist dataset, each order can contain several items, which means the same order appears multiple times in item-level data.

Without careful handling, this structure can lead to:
- Overstated revenue  
- Incorrect order counts  
- Misleading averages  

The dashboard was designed with this context in mind, focusing on **accuracy and clarity** rather than raw aggregation.

---

##  What the Dashboard Shows

The report is organized into **two pages** to support different levels of analysis.

---

### 1. Business Overview (2016–2018)

This page provides a consolidated view of overall performance:

- **Total Revenue**
- **Total Orders**
- **Average Order Value**
- **Total Items Sold**
- **Monthly trends** for revenue and order volume  

This view is intended for quickly assessing business performance over time and identifying broad patterns.

---

### 2. Product and Customer Insights

This page enables deeper analysis through:

- Orders and revenue by **product category**
- **Customer distribution** across states
- **Order status** breakdown  

Interactive filters allow comparisons across:
- Years  
- Product categories  
- States  
- Order statuses  

All without altering the underlying calculations.

---

##  Data Used

The analysis is based on the public **Olist Brazilian E-Commerce Dataset**, which includes:

- Orders  
- Order Items  
- Products  
- Customers  
- Payments  

Because order IDs repeat across item-level records, key metrics were defined using **Power BI measures** so that totals and averages represent actual business values rather than duplicated rows.

---

##  Tools Used

- **Power BI**  
  - Data modeling  
  - Measures  
  - Visualization  

- **CSV files** as the data source

---

##  Key Takeaways

- Revenue and order volume do not always move together, highlighting the importance of tracking both  
- Product categories contribute differently to revenue and order counts  
- Monthly trends reveal clear changes in business activity over time  
- Accurate metric definition is essential when working with item-level e-commerce data  

---

##  Summary

This project demonstrates the use of **Power BI** to work with real-world e-commerce data and transform it into a **clear, structured dashboard**.

The emphasis throughout was on:
- Presenting numbers that can be trusted  
- Designing visuals that support practical business analysis  

---
