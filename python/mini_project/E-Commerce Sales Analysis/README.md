# 🛒 E-Commerce Sales Analysis using Pandas

## 📌 Project Overview

This project analyzes an e-commerce transaction dataset using **Python and Pandas**. The objective was to clean the raw transaction data, perform exploratory data analysis, and identify useful business insights related to **sales, products, customers, countries, and time-based trends**.

---

## 📊 Dataset Information

| Attribute | Details |
|---|---|
| **Dataset** | Online Retail |
| **Source** | Kaggle |
| **Original Dataset Size** | 541,909 rows × 8 columns |
| **Time Period** | 1 December 2010 – 9 December 2011 |
| **Business Type** | UK-based non-store online retailer |
| **Original Columns** | 8 |
| **Analysis Tool** | Pandas |

---

## 🧹 Data Cleaning

The raw dataset was cleaned before performing the analysis. The cleaning process included:

- Handling missing values
- Removing duplicate records
- Creating a **Sales** column using Quantity × Unit Price
- Converting date-related columns into appropriate datetime formats
- Preparing the dataset for exploratory analysis

After cleaning, the dataset contained:

- **401,604 transactions**
- **22,190 unique orders**
- **4,372 customers**
- **3,684 products**
- **37 countries**

---

## 💡 Project Insights

### 💰 Overall Sales

- **Total Sales:** £8.28 million
- **Average Transaction Value:** £20.61

### 🌍 Top Market

The **United Kingdom** was the dominant market:

- **Revenue:** £6.75 million
- **Contribution:** Approximately **81.5%** of total sales

### 🏆 Top Product by Revenue

**REGENCY CAKESTAND 3 TIER**

- Revenue: **£132,567.70**

### 📦 Top Product by Quantity

**WORLD WAR 2 GLIDERS ASSTD DESIGNS**

- Quantity Sold: **53,119 units**

### 👤 Top Customer by Spending

**Customer 14646**

- Total Purchases: **£279,489.02**

### 🔄 Customer Ordering Behavior

- **459 customers** placed more than 10 orders.
- **Customer 14911** placed the highest number of orders.
- Total Orders by Customer 14911: **248**

### 📅 Best-Performing Month

**November 2011** was the highest-performing month:

- Sales: **£1,126,815.07**

---

## 🔎 Key Takeaway

The analysis shows that the **United Kingdom was the company's strongest market**, contributing approximately 81.5% of total sales. A small group of high-value and frequent customers contributed significantly to overall revenue, while products such as **REGENCY CAKESTAND 3 TIER** and **WORLD WAR 2 GLIDERS ASSTD DESIGNS** performed particularly well. Sales also increased significantly toward the end of 2011, with **November 2011** recording the highest monthly revenue.


