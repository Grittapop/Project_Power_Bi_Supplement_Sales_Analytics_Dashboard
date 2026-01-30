# 📊 Supplement Sales Analytics Dashboard (Power BI)

## 📌 Project Overview
This project is an **end-to-end Power BI analytics dashboard** built to analyze supplement sales performance across products, categories, platforms, and locations.

The dashboard is designed with a **business and executive perspective**, focusing not only on sales performance but also on **operational risk and return behavior**.  
This project demonstrates skills in **data modeling, DAX, Power BI visualization, and analytical storytelling**.

---

## 🎯 Business Objectives
The main objectives of this project are to:
- Monitor overall sales performance and year-over-year trends
- Identify top-performing products, categories, and sales platforms
- Analyze customer return behavior and operational risk
- Understand the relationship between discount strategy and return rate
- Support data-driven business decision making

---

## 🧱 Data Source & Attribution

### Data Source
- **Dataset Name:** Supplement Sales Data  
- **Author:** Zahid Feroze  
- **Source:** Kaggle  
- **Link:** https://www.kaggle.com/datasets/zahidmughal2343/supplement-sales-data  
- **License:** Apache License 2.0  

### Dataset Description
The dataset contains **weekly sales data from January 2020 to April 2025**, covering:
- Health & wellness supplement products
- Multiple product categories (Protein, Vitamin, Omega, Amino Acids, Performance, etc.)
- Multiple e-commerce platforms (Amazon, Walmart, iHerb)
- Multiple locations (USA, UK, Canada)

### Data Usage Disclaimer
This project is created **for educational and portfolio purposes only**.  
The data is publicly available and does not represent any real company’s actual performance.

---

## 🗂 Data Model
The dashboard uses a **star schema data model** to ensure clarity, performance, and scalability.


![Screenshot 2026-01-30 222645](https://github.com/user-attachments/assets/3e831cf1-76c2-45bd-8289-9338b3899538)


### Fact Table
- **Fact_Sales**
  - Revenue
  - Units Sold
  - Units Returned
  - Price
  - Discount

### Dimension Tables
- **Dim_Date**
- **Dim_Product**
- **Dim_Category**
- **Dim_Platform**
- **Dim_Location**

This modeling approach allows clean filter propagation and flexible analysis across dimensions.

---

## 📐 Key Metrics (DAX Measures)
Key measures created using DAX include:
- Total Revenue
- Total Units Sold
- Total Returns
- Return Rate %
- Average Discount
- Year-over-Year (YoY) Revenue Growth
- Best Seller Product
- Highest Revenue Product
- Best Performing Platform
- Riskiest Product, Platform, and Location

---

## 📊 Dashboard Pages

### 1️⃣ Executive Overview

![executive_overview](https://github.com/user-attachments/assets/cc6f6a73-1e7d-464f-ac3a-a0cb1d1869ab)

Provides a high-level snapshot for decision-makers:
- Total Revenue with YoY comparison
- Total Units Sold
- Total Returns
- Monthly Revenue Trend
- Revenue by Category
- Revenue by Location

**Purpose:** Enable executives to quickly assess overall business performance.

---

### 2️⃣ Product & Category Performance

![product_category_performance](https://github.com/user-attachments/assets/a2ffac08-af1d-4132-b980-30f3f1c06185)

Focuses on identifying sales drivers:
- Best Seller Product
- Highest Revenue Product
- Best Performing Platform
- Top Products by Revenue
- Revenue Share by Category
- Category Performance by Platform
- Detailed Product Performance Table (Revenue, Units, Return Rate, Avg Discount)

**Purpose:** Identify growth opportunities and optimize product strategy.

---

### 3️⃣ Risk & Operational Insight

![risk_operational_insight](https://github.com/user-attachments/assets/2bb367a4-2986-445c-bd91-3960b636088f)

Analyzes operational risk and return behavior:
- Overall Return Rate %
- Highest Return Rate Product
- Riskiest Platform
- Riskiest Location
- High-Risk Products Table
- Return Rate by Category
- Discount vs Return Risk Analysis

**Purpose:** Detect risk patterns and support pricing & promotion decisions.

---

## 📈 Key Insights (Sample)
- Vitamin and Mineral categories contribute the largest share of total revenue
- Walmart is the best-performing platform by revenue
- Amazon shows the highest return rate among platforms
- Higher discount levels tend to increase return risk for certain product categories

---

## 🛠 Tools & Technologies
- Power BI
- DAX
- Power Query
- Star Schema Data Modeling
- Data Visualization & Analytical Storytelling

## 👤 Author
**Grittapop**  
Data Analyst | Data Engineer | Analytics Engineer 
Skills: Power BI • DAX • Data Modeling • Data Visualization
