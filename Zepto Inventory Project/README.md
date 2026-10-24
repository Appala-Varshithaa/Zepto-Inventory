# 🛒 Zepto Inventory Data Analysis using PostgreSQL

## 📌 Project Overview

This project analyzes Zepto's product inventory data using PostgreSQL. The goal is to perform data exploration, cleaning, and business analysis to extract meaningful insights about product pricing, discounts, inventory availability, and category-wise performance.

The project demonstrates SQL skills commonly used by Data Analysts, including filtering, aggregation, grouping, sorting, data cleaning, and conditional logic.

---

## 🎯 Objectives

- Explore the inventory dataset
- Perform data quality checks
- Clean inconsistent data
- Analyze discounts and pricing
- Identify inventory trends
- Generate business insights using SQL

---

## 🛠️ Tools & Technologies

- PostgreSQL
- pgAdmin 4
- SQL
- Git & GitHub

---

## 📂 Dataset

The dataset contains Zepto inventory information with the following attributes:

| Column | Description |
|---------|-------------|
| sku_id | Unique Product ID |
| category | Product Category |
| name | Product Name |
| mrp | Maximum Retail Price |
| discountPercent | Discount Percentage |
| availableQuantity | Available Stock |
| discountedSellingPrice | Selling Price |
| weightInGms | Product Weight |
| outOfStock | Stock Status |
| quantity | Quantity |

---

## 🧹 Data Cleaning

The following cleaning operations were performed:

- Checked for NULL values
- Identified duplicate product names
- Removed products with MRP = 0
- Converted prices from paise to rupees
- Validated stock availability

---

## 📊 SQL Analysis Performed

### Data Exploration

- Count total records
- View sample records
- Find NULL values
- Identify unique categories
- Count in-stock vs out-of-stock products
- Detect duplicate product names

### Business Questions Solved

1. Top 10 products with the highest discounts
2. High-value products currently out of stock
3. Estimated revenue by category
4. Products with high MRP and low discounts
5. Top 5 categories with the highest average discounts
6. Best value products based on price per gram
7. Product classification by weight (Low, Medium, Bulk)
8. Total inventory weight for each category

---

## 💡 Key SQL Concepts Used

- SELECT
- WHERE
- ORDER BY
- GROUP BY
- HAVING
- DISTINCT
- Aggregate Functions
  - COUNT()
  - SUM()
  - AVG()
- CASE Statement
- ROUND()
- DELETE
- UPDATE

---

## 📈 Key Insights

- Identified the categories providing the highest average discounts.
- Estimated inventory revenue based on selling price and available quantity.
- Found premium products that are currently out of stock.
- Compared products using price-per-gram analysis to determine the best value.
- Classified products into weight segments for easier inventory analysis.

---

## 📁 Project Structure

```
Zepto-SQL-Data-Analysis/
│
├── README.md
├── zepto_analysis.sql
├── requirements.txt
├── dataset/
│   └── zepto.csv
├── screenshots/
│   ├── query_results.png
│   └── database_schema.png
└── .gitignore
```

---

## 🚀 How to Run

1. Install PostgreSQL.
2. Open pgAdmin 4.
3. Create a new database.
4. Execute the SQL script.
5. Import the dataset (CSV).
6. Run the analysis queries.

---

## 📷 Sample Output

Add screenshots of your query results inside the `screenshots` folder.

---