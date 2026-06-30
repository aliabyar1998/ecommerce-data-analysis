# E-Commerce Data Analysis Project

## 📌 Overview
This project is a complete data analysis of an E-Commerce dataset. 
It includes data cleaning, exploratory data analysis (EDA), customer segmentation using RFM analysis,
and Market Basket Analysis for product association discovery.

## 📊 Project Objectives
- Clean and preprocess raw transactional data
- Perform exploratory data analysis (EDA)
- Analyze sales performance by time, country, and product
- Segment customers using RFM (Recency, Frequency, Monetary) analysis
- Discover product associations using Market Basket Analysis

## 🧹 Data Cleaning
- Removed cancelled and invalid transactions
- Handled missing values
- Filtered out negative quantities and prices
- Created a Revenue column (Quantity × UnitPrice)

## 📈 Exploratory Data Analysis (EDA)
- Total revenue, orders, and customers
- Monthly revenue trends
- Top countries by revenue
- Top-selling products

## 👥 RFM Analysis
Customers were segmented based on:
- Recency: How recently a customer purchased
- Frequency: How often a customer purchased
- Monetary: How much a customer spent

Segments include:
- Champions
- Loyal Customers
- New Customers
- Big Spender Lost
- Lost Customers

## 🛒 Market Basket Analysis
Association rule mining was applied to identify products frequently purchased together using the Apriori algorithm and lift metric.

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- mlxtend

## 🎯 Conclusion
This project demonstrates end-to-end data analysis skills including data preprocessing, visualization, customer segmentation, and association rule mining.

---

## 👤 Author
Ali Abyar
