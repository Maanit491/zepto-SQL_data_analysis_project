# 📊 Zepto E-commerce SQL Data Analyst Portfolio Project

This project is a complete **real-world data analyst portfolio project** based on a dataset scraped from **Zepto** — one of India's fastest-growing quick-commerce startups. It replicates the end-to-end workflow of a data analyst, from **raw data exploration** to **business-driven insights**.

---

## 🧠 Project Objective

To perform **exploratory data analysis (EDA)** and answer critical **business questions** using **SQL** on a real e-commerce dataset. The focus is on:

- Understanding product distribution
- Analyzing pricing strategies
- Uncovering business opportunities

---

## 📁 Dataset

**Source:** [Kaggle - Zepto Inventory Dataset](https://www.kaggle.com/datasets/palvinder2006/zepto-inventory-dataset/data?select=zepto_v2.csv)  
**File Used:** `zepto_v2.csv`

### 📌 Columns in the Dataset:

sku_id: Unique identifier for each product entry (Synthetic Primary Key)
name: Product name as it appears on the app
category: Product category like Fruits, Snacks, Beverages, etc.
mrp: Maximum Retail Price (originally in paise, converted to ₹)
discountPercent: Discount applied on MRP
discountedSellingPrice: Final price after discount (also converted to ₹)
availableQuantity: Units available in inventory
weightInGms: Product weight in grams
outOfStock: Boolean flag indicating stock availability
quantity: Number of units per package (mixed with grams for loose produce)

---

## 🛠️ Tools Used

- **MySQL**
- **Spreadsheet (Optional for initial inspection)**

---

## 🧪 Key Analyses Performed

Row Count: Calculated total number of products in the dataset.
Sample View: Displayed the first 10 product records.
Missing Values: Identified nulls across all key columns.
Category Diversity: Listed all unique product categories.
Stock Status: Counted in-stock vs out-of-stock products.
Duplicate Product Names: Found product names listed under multiple SKUs.
Zero Price Cleanup: Detected and removed products with zero MRP.
Unit Conversion: Converted prices from paise to rupees.
Top Discounts: Listed top 10 products with highest discount percentages.
Out-of-Stock Premium Items: Found high-MRP products that were out of stock.
Revenue Estimation: Estimated total revenue per category.
Low Discount High MRP: Filtered products with high MRP and minimal discounts.
Best Discounted Categories: Identified categories with highest average discounts.
Value per Gram: Calculated and sorted products by price per gram.
Weight Classification: Grouped products into Low, Medium, and Bulk weight classes.
Total Inventory Weight: Computed total stock weight per category.
