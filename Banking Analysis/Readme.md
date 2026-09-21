# Banking Analytics & Power BI Dashboard

An end-to-end banking data analysis project designed to evaluate customer profiles, credit exposures, deposit trends, and account balances. The project combines **Python** for exploratory data analysis, **SQL** for relational querying, and **Power BI & DAX** to deliver an interactive business intelligence solution.

---

## Tech Stack & Tools

* **Data Processing & Analysis:** Python (`Pandas`, `NumPy`, `Matplotlib`, `Seaborn`)
* **Database Management:** SQL / MySQL
* **Business Intelligence & Visualization:** Power BI, DAX (Data Analysis Expressions)
* **Documentation & Reporting:** Microsoft Word, Jupyter Notebook

---

## Project Workflow & Key Analysis

1. **Data Cleaning & Preprocessing:**
   * Handled missing values, standardized data types, and prepared clean relational tables.
2. **Exploratory Data Analysis (EDA):**
   * Identified underlying distributions, outliers, and patterns across banking products.
3. **Customer Segmentation:**
   * Segmented account holders using dynamic `Income Bands` to uncover target demographics.
4. **Loan & Deposit Analysis:**
   * Examined product adoption, average exposure per band, and nationality-wise variation.
5. **Correlation & Financial Modeling:**
   * Analyzed statistical relationships between checking/savings balances, deposits, and loan amounts.

---

## Key Business Insights

* **Target Loan Segment:** **Medium-income customers** account for the highest total loan volume in the analyzed dataset, representing a primary growth driver.
* **Deposit Correlations:** Bank Deposits exhibit a strong positive correlation with:
  * **Checking Account Balances:** $r = 0.84$
  * **Savings Account Balances:** $r = 0.75$
* **Demographic Variance:** Both loan utilization and deposit volumes show significant variance across distinct customer nationality groups.

---

## Power BI Dashboard Overview

The interactive Power BI report (`Banking_Dashboard.pbix`) is structured into four targeted views:

1. **Overview View:** High-level executive KPIs (Total Deposits, Total Loans, Active Customers, Average Balances).
2. **Loan Analysis View:** Granular breakdown of loan distribution by income band, customer risk profile, and loan type.
3. **Deposit Analysis View:** Deep-dive into savings vs. checking behavior and liquidity patterns.
4. **Summary View:** Executive insights, correlation matrix summary, and cross-filter demographic breakdowns.
king_Dashboard.pbix     # Interactive PDetailed project documentation and final report
└── README.md                  # Project overview and technical summary
