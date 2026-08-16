# 📊 Sales Data Visualization & Business Analytics

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA), Data Visualization, and Business Analytics** on a Superstore sales dataset.

The objective is to understand sales performance, profitability, customer behavior, product performance, geographic trends, and time-based business patterns using **Python, Pandas, Seaborn, and Matplotlib**.

---

## 🎯 Objectives

- Analyze overall sales and profitability
- Identify high-performing and loss-making products
- Analyze sales and profit across categories and sub-categories
- Understand customer purchasing behavior
- Analyze regional and state-level performance
- Identify monthly and yearly sales trends
- Calculate Year-over-Year (YoY) growth
- Analyze the relationship between discounts and profitability
- Generate actionable business insights

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset

The project uses a Superstore sales dataset containing information about:

- Orders
- Customers
- Products
- Categories
- Sales
- Quantity
- Discounts
- Profit
- Regions
- States
- Order Dates
- Shipping information

---

## 🔍 Analysis Performed

### 1. Sales Analysis

- Total Sales
- Total Quantity Sold
- Average Order Value
- Sales by Year
- Sales by Month
- Sales by Category
- Sales by Sub-Category

### 2. Profitability Analysis

- Total Profit
- Overall Profit Margin
- Profit by Category
- Profit by Sub-Category
- Loss-making products
- High-sales, low-profit products
- Profit margin analysis

### 3. Customer Analysis

- Total unique customers
- Top customers by sales
- Top customers by profit
- Customer order frequency
- Average customer spending
- Customer segment analysis

### 4. Geographic Analysis

- Sales by Region
- Profit by Region
- State-level profitability
- Identification of loss-making states

### 5. Time-Series Analysis

- Yearly Sales and Profit
- Monthly Sales and Profit
- Monthly Profit Margin
- Year-over-Year Sales Growth
- Year-over-Year Profit Growth

### 6. Discount Analysis

- Sales by Discount Level
- Profit by Discount Level
- Investigation of high-discount loss-making products

### 7. Correlation Analysis

Correlation analysis was performed on relevant numerical variables to understand relationships between:

- Sales
- Quantity
- Discount
- Profit
- Shipping Days
- Sales per Quantity
- Profit Margin

---

## 📈 Key Business Insights

- **Technology is the strongest overall category** in terms of both sales and profit.
- **Furniture generates high sales but comparatively low profit.**
- **Tables are the biggest loss-making sub-category.**
- **301 products have negative overall profit.**
- Several products generate **high sales while still producing losses**.
- **Copiers generate the highest profit** among the sub-categories.
- **West is the strongest region** in both sales and profit.
- **Consumer is the largest customer segment** and generates the highest sales and profit.
- **February has the highest profit margin**, while April has the lowest.
- Sales and profit showed significant growth after 2015.
- Excessive discounting can negatively affect profitability.

---

## 💡 Business Recommendations

- Investigate **Furniture and Tables** to improve profitability.
- Review **high-sales but loss-making products**.
- Optimize discount strategies for products with low or negative margins.
- Focus on highly profitable sub-categories such as **Copiers, Phones, and Accessories**.
- Investigate states with persistent negative profit.
- Consider **profitability along with sales** when evaluating customers and products.
- Use monthly and yearly trends for better inventory and marketing planning.
- Prioritize **profitable growth rather than sales growth alone**.

---

## 📊 Project Structure

```text
Sales-Data-Visualization-Business-Analytics/
│
├── Sales Data Visualization & Business Analytics.ipynb
│
├── data/
│   ├── raw/
│   │   └── Sample-Superstore.csv
│   │
│   └── processed/
│
└── README.md