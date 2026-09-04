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

## Project Insights

The analysis generated total sales of **£8.28 million**, with an average transaction value of **£20.61**. The **United Kingdom** was the dominant market, generating **£6.75 million**, which accounted for approximately **81.5% of total sales**. The highest-revenue product was **REGENCY CAKESTAND 3 TIER**, generating **£132,567.70**, while **WORLD WAR 2 GLIDERS ASSTD DESIGNS** recorded the highest quantity sold with **53,119 units**. Customer analysis showed that **Customer 14646** was the highest-spending customer, with total purchases of **£279,489.02**. **459 customers** placed more than 10 orders, with **Customer 14911** placing the highest number of orders at **248**. Monthly analysis showed that **November 2011** was the highest-performing month, generating **£1,126,815.07** in sales.


## 🔎 Key Takeaway

The analysis shows that the **United Kingdom was the company's strongest market**, contributing approximately 81.5% of total sales. A small group of high-value and frequent customers contributed significantly to overall revenue, while products such as **REGENCY CAKESTAND 3 TIER** and **WORLD WAR 2 GLIDERS ASSTD DESIGNS** performed particularly well. Sales also increased significantly toward the end of 2011, with **November 2011** recording the highest monthly revenue.


