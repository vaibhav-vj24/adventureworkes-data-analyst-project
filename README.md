# 📊 Adventure Works Sales Analysis Dashboard
![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow?logo=powerbi)
![Dataset](https://img.shields.io/badge/Dataset-AdventureWorks-blue?logo=microsoftsqlserver)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

> 📊 An interactive Power BI dashboard analyzing sales, profit,
> customers, products, and regional performance using the Adventure Works dataset.

📁 Adventure-Works-Sales-Analysis
│
├── 📊 Adventure Works Sales Analysis.pbix
├── 🖼️ Adventure Works Sales Analysis.png
├── 📁 Dataset
│   ├── FactInternetSales.xlsx
│   ├── DimCustomer.xlsx
│   ├── DimProduct.xlsx
│   ├── DimProductCategory.xlsx
│   ├── DimProductSubCategory.xlsx
│   ├── DimSalesTerritory.xlsx
│   └── DimDate.xlsx
│
└── 📄 README.md

## 📌 Project Overview

The **Adventure Works Sales Analysis Dashboard** is an interactive Power BI dashboard designed to analyze sales performance, profitability, customers, products, and geographical sales distribution.

The project transforms raw Adventure Works sales data into meaningful business insights using **Power Query, Data Modeling, DAX, and Power BI visualizations**.

The dashboard allows users to interact with the data using filters such as **Year, Month, Territory Region, and Product Category**.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Analyze overall sales performance
- Monitor total sales and profit
- Analyze product and customer performance
- Compare sales across different years
- Analyze monthly and quarterly sales trends
- Analyze sales by country/territory
- Identify high-performing products
- Identify high-value customers
- Create an interactive business dashboard
- Present complex sales data in an easy-to-understand format

---

## 🛠️ Tools & Technologies

- **Power BI**
- **Power Query**
- **DAX**
- **Microsoft Excel**
- **Data Modeling**
- **Data Visualization**

---

## 📂 Dataset

The project uses the **Adventure Works dataset**, which contains information related to:

- Sales transactions
- Products
- Customers
- Product categories
- Product subcategories
- Sales territories
- Order dates

The data was transformed and modeled before creating the dashboard.

---

## 🔄 Data Preparation

The following data preparation steps were performed using Power Query:

1. Imported the Adventure Works datasets.
2. Combined sales datasets where required.
3. Cleaned and transformed raw data.
4. Checked data types.
5. Created date-related fields.
6. Removed unnecessary columns.
7. Handled missing/null values.
8. Created relationships between fact and dimension tables.
9. Prepared the final data model for analysis.

---

## 🧮 Data Modeling

A relational data model was created to connect the sales fact table with the relevant dimension tables.

### Main Tables

- Fact Internet Sales
- Customer
- Product
- Product Category
- Product Subcategory
- Sales Territory
- Date/Calendar

The data model allows the dashboard to dynamically calculate sales, profit, customers, products, and other business metrics.

---


## ❓ Business Questions

This dashboard was created to answer the following business questions:

1. What is the overall sales and profit performance?
2. How do sales change from month to month?
3. Which years generated the highest sales?
4. Which quarter contributes the most to total sales?
5. Which countries generate the highest sales?
6. Which products contribute significantly to overall revenue?
7. Which customers generate higher sales?
8. What is the relationship between Sales Amount and Product Cost?
9. How does product category affect sales performance?
10. How can management use the dashboard to monitor business performance?

---

## 📈 Key Insights

Based on the dashboard analysis:

### 💰 Overall Performance

- Total Sales are approximately **29.36M**.
- Total Profit is approximately **12.08M**.
- The dashboard contains approximately **18.48K customers**.
- The analysis includes approximately **27.66K orders**.

### 📅 Time-Based Analysis

- Sales vary significantly across different months.
- The monthly sales trend helps identify periods of higher and lower sales performance.
- The highest monthly sales visible in the dashboard are approximately **3.2M**.
- The lowest monthly sales are approximately **1.7M**.

### 📊 Year-wise Performance

- Sales performance varies considerably across years.
- One year contributes significantly more sales than the other displayed years.
- Year-wise analysis helps identify changes in overall business performance over time.

### 🗓️ Quarterly Performance

- Quarterly sales are distributed across all four quarters.
- Q4 contributes approximately **9.11M**.
- Q3 contributes approximately **7.64M**.
- Q2 contributes approximately **7.09M**.
- Q1 contributes approximately **5.52M**.

### 🌍 Country-wise Performance

- The **United States** generates approximately **9.39M** in sales.
- **Australia** generates approximately **9.06M**.
- The **United Kingdom** contributes approximately **3.39M**.
- France, Germany, and Canada also contribute to overall international sales.

### 🏷️ Product Analysis

- Product-level analysis helps identify products generating significant sales.
- Products such as the **Mountain-200** series contribute substantially to the sales shown in the dashboard.
- Product-level performance can be further analyzed using the Product Category slicer.

### 👥 Customer Analysis

- Customer-level analysis allows the business to identify customers with higher sales contributions.
- The customer table can be filtered dynamically using the dashboard slicers.
- This analysis can help identify valuable customers for targeted marketing and retention strategies.

---

## 💡 Business Recommendations

Based on the dashboard analysis, the following areas could be considered:

- Focus on markets with consistently high sales while investigating opportunities in lower-performing regions.
- Analyze the reasons behind monthly sales fluctuations and use the findings for inventory and sales planning.
- Monitor high-performing products to maintain appropriate inventory levels.
- Identify high-value customers and develop appropriate customer retention strategies.
- Compare product cost and sales regularly to monitor profitability.
- Use quarterly and monthly trends for future sales and inventory planning.
- Continue monitoring regional performance to identify opportunities for market expansion.

---

## 🎯 Dashboard Usage

The dashboard provides interactive slicers that allow users to explore the data dynamically.

### Available Filters

- **Year**
- **Month Name**
- **Territory Region**
- **Product Category**

For example, selecting a specific year updates the relevant sales visualizations and allows users to analyze performance for that period.

---

## 📊 Key Metrics at a Glance

| Metric | Value |
|---|---:|
| Total Sales | 29.36M |
| Total Profit | 12.08M |
| Total Customers | 18.48K |
| Total Orders | 27.66K |
| Highest Monthly Sales | ~3.2M |
| Q4 Sales | ~9.11M |
| Q3 Sales | ~7.64M |
| Q2 Sales | ~7.09M |
| Q1 Sales | ~5.52M |

---

## 🔍 Analytical Approach

The project followed a structured data analytics workflow:

**Raw Data**

↓  

**Data Cleaning & Transformation**

↓

**Data Modeling**

↓

**DAX Calculations**

↓

**KPI Development**

↓

**Exploratory Analysis**

↓

**Data Visualization**

↓

**Interactive Dashboard**

↓

**Business Insights**

---

## 📌 Conclusion

The Adventure Works Sales Analysis Dashboard provides an interactive view of sales, profit, customers, products, and geographical performance.

The project demonstrates how Power BI can be used to transform raw business data into an interactive analytical solution that supports data-driven decision making.

This project also demonstrates practical skills in **Power Query, DAX, data modeling, data visualization, dashboard design, and business analysis**.

## 📊 Dashboard Preview

<p align="center">
  <img src="Adventure%20Works%20Sales%20Analysis.png" alt="Adventure Works Sales Dashboard" width="100%">
</p>
