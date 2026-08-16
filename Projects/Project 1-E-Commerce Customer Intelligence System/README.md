# 🛒 E-Commerce Customer Intelligence System

An end-to-end data analysis and customer intelligence project built using the Brazilian E-Commerce Public Dataset by Olist.

The project focuses on cleaning and integrating multiple e-commerce datasets, performing customer-level feature engineering, conducting exploratory data analysis (EDA), and extracting actionable business insights from customer purchasing and delivery behavior.

---

## 📌 Project Overview

E-commerce businesses generate large amounts of transactional data, but raw transaction data alone does not provide a clear understanding of customer behavior.

This project transforms raw e-commerce data into meaningful customer-level features that can be used to understand:

- Customer purchasing behavior
- Repeat purchase patterns
- Customer spending
- Product preferences
- Geographic behavior
- Delivery performance
- High-value customers
- Customer lifetime behavior

The final output consists of cleaned transaction-level data and customer-level analytical features.

---

## 🎯 Objectives

- Clean and validate raw e-commerce datasets
- Integrate multiple datasets using appropriate keys
- Perform data quality analysis
- Engineer meaningful customer-level features
- Analyze customer purchasing behavior
- Investigate delivery performance
- Identify highly skewed features and apply appropriate transformations
- Analyze relationships between numerical features
- Create meaningful visualizations
- Extract actionable business insights

---

## 📂 Dataset

This project uses the:

**Brazilian E-Commerce Public Dataset by Olist**

The dataset contains information about:

- Customers
- Orders
- Order items
- Products
- Product categories
- Payments
- Reviews
- Sellers
- Geographic information

### Datasets Used

This project primarily uses four datasets:

1. `customers_dataset.csv`
2. `orders_dataset.csv`
3. `order_items_dataset.csv`
4. `products_dataset.csv`

---

## 🔄 Data Processing Pipeline

```text
Raw Datasets
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Data Validation
     ↓
Dataset Merging
     ↓
Transaction-Level Dataset
     ↓
Customer-Level Feature Engineering
     ↓
EDA & Visualization
     ↓
Business Insights