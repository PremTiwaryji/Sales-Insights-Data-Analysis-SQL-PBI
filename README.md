# 📊 Sales Insights: Data Analysis & Visualization Project

## 🔍 Project Overview

This project focuses on analyzing sales data for AtliQ Hardware, a company providing computer hardware and peripherals. The goal was to transform raw data into actionable insights to help the sales director monitor revenue trends, identify declining markets, and make data-driven decisions. 

The dashboard provides a comprehensive view of sales performance across different cities, customers, and products from 2017 to 2020.

---
## 📸 Dashboard Preview

![Project Thumbnail]()


---

## 🎯 Problem Statement

The sales director was facing challenges in tracking business performance across different regions in India. The reports provided by regional managers were often complex and didn't clearly show the:

* Revenue trends over time
* Top-performing markets and customers
* Product performance
* Sales quantity distribution

There was no centralized dashboard for quick decision-making.

---

## 🛠️ Tools & Technologies Used

* SQL (MySQL): For data extraction, cleaning, and initial exploratory data analysis (EDA).
* Power BI Desktop: For data modeling, ETL (Power Query), and creating the interactive dashboard.
* DAX (Data Analysis Expressions): To create calculated measures like Total Revenue and Sales Quantity.

---

## 📂 Dataset Description

The dataset consists of multiple tables:

* **customers**: Contains customer details (name, type)
* **transactions**: Contains sales transactions
* **date**: Date dimension table for time-based analysis
* **products**: Product-related information
* **markets**: Market/city information

---

## ⚙️ Data Preparation Steps

1. **Data Discovery**: Performed initial data analysis in MySQL to understand the database schema and table relationships.

2. **Data Cleaning**: Imported data into Power BI and used Power Query to:
   * Remove null values and "garbage" data.
   * Normalize currency (Converted USD transactions to INR for uniform reporting).
   * Filter out irrelevant records (e.g., zero sales amount).

3. **Data Modeling**: Established a Star Schema by connecting the transactions fact table with dimension tables like customers, products, markets, and date.

4. **Dashboard Creation**: Developed an interactive visual interface to track KPIs.

---

## 📊 Key Dashboard Features

* Total Revenue: **984.81M**
* Total Sales Quantity: **2M**
* Revenue trend over time
* Revenue by market (city-wise analysis)
* Sales quantity by market
* Top 5 customers
* Top 5 products
* Year and month filters (interactive slicers)

---

## 📈 Key Insights

* Delhi NCR generates the highest revenue (~519M)
* Sales show fluctuations with a declining trend in later years
* A few customers contribute a major portion of revenue
* Certain products dominate overall sales
* Some cities have very low contribution and can be targeted for growth

---

## 💼 Business Impact

* Revenue Optimization: The company can now see which specific markets (like Delhi, Mumbai, etc.) are contributing the most and which ones need more marketing focus.
* Real-time Tracking: Replaces manual, static Excel reports with a dynamic dashboard that updates automatically with new data.
* Cost Reduction: By identifying low-performing products and regions, the company can save costs on ineffective sales strategies.
* Data-Driven Decisions: Provides a single source of truth for the Sales Director to make strategic moves based on facts rather than gut feeling.

---

## 🚀 What I Learned

* Writing complex SQL queries for data analysis
* Data cleaning and transformation using Power Query
* Building interactive dashboards in Power BI
* Data modeling and relationships
* Business problem solving using data

---

## ⚡ How to Run This Project

1. Import `db_dump.sql` into MySQL
2. Open Power BI file (.pbix)
3. Connect to database
4. Refresh data
5. Explore dashboard

---

## 📌 Conclusion

This project demonstrates how raw data can be transformed into meaningful insights using SQL and Power BI. It highlights the importance of data visualization in business decision-making.

---

## 🔗 Author 
**Name:** Prem Tiwary  
**Email:** premtiwary7050@gmail.com 
**LinkedIn:** www.linkedin.com/in/prem-tiwary

---

## License
This repository is for demonstration and learning purposes. Feel free to reuse the code with attribution.

