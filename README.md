# 🏦 Banking Customer & Financial Analytics

An end-to-end **Banking Data Analytics project** designed to analyse customer behaviour, deposits, loans, transactions and overall financial performance using **Excel, Python, MySQL and Power BI**.

The project demonstrates the complete data analytics workflow — from data cleaning and exploratory analysis to SQL-based business analysis, statistical analysis and interactive Power BI dashboards.

---

## 📌 Project Overview

Banks generate large amounts of customer and transaction data every day. Analysing this data can help financial institutions understand customer behaviour, monitor financial performance and identify opportunities for better products and services.

This project focuses on answering key business questions related to:

* Customer behaviour
* Account types
* Deposits
* Loans
* Transactions
* Customer segments
* Financial performance
* Trends and relationships within the data

The goal is to transform raw banking data into **meaningful business insights and actionable recommendations**.

---

## 🎯 Business Objectives

The main objectives of this project are:

1. Analyse customer demographics and account information.
2. Understand deposit and withdrawal patterns.
3. Analyse loan distribution and loan performance.
4. Identify high-value customer segments.
5. Analyse transaction trends over time.
6. Identify relationships between customer attributes and financial behaviour.
7. Develop interactive dashboards for business decision-making.
8. Provide data-driven recommendations for improving customer engagement and financial performance.

---

## 🛠️ Tools & Technologies

| Tool                | Purpose                                                     |
| ------------------- | ----------------------------------------------------------- |
| **Microsoft Excel** | Initial data inspection, cleaning and exploratory analysis  |
| **Python**          | Data cleaning, transformation, EDA and statistical analysis |
| **Pandas**          | Data manipulation and preparation                           |
| **NumPy**           | Numerical analysis                                          |
| **Matplotlib**      | Data visualization                                          |
| **Seaborn**         | Statistical visualization                                   |
| **MySQL**           | Database storage and SQL analysis                           |
| **SQL**             | Business queries, KPI calculations and customer analysis    |
| **Power BI**        | Interactive dashboards and business reporting               |
| **DAX**             | Measures and KPI calculations                               |

---

# 🔄 Project Workflow

```text
Raw Banking Data
       │
       ▼
    Microsoft Excel
       │
       │ Data inspection & initial cleaning
       ▼
      Python
       │
       │ Pandas + NumPy + EDA + Statistics
       ▼
     MySQL
       │
       │ SQL Analysis + KPIs
       ▼
    Power BI
       │
       │ Data Modelling + DAX
       ▼
Interactive Dashboard
       │
       ▼
Business Insights
       │
       ▼
Recommendations
```

---

# 📂 Dataset

The dataset contains banking-related customer, account, transaction, deposit and loan information.

### Main categories of information

* Customer information
* Account information
* Transaction information
* Deposit information
* Loan information
* Customer financial behaviour

> **Dataset Source:** [Add your dataset source here]

> **Dataset Size:** [Add number of rows/records]

---

# 🧹 1. Data Cleaning — Excel & Python

The raw dataset was first inspected and prepared for analysis.

### Cleaning activities

* Checked for missing values
* Identified duplicate records
* Standardized column names
* Corrected data types
* Standardized categorical values
* Checked date fields
* Identified potential outliers
* Validated numerical values
* Removed unnecessary columns

Python was then used to automate and reproduce the cleaning process.

### Python Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

# 📊 2. Exploratory Data Analysis

Exploratory Data Analysis was performed using Python to understand patterns and relationships in the banking data.

### Areas analysed

#### Customer Analysis

* Customer distribution
* Age groups
* Customer segments
* Account types
* Customer financial behaviour

#### Transaction Analysis

* Transaction volume
* Deposit trends
* Withdrawal trends
* Average transaction value
* Monthly transaction patterns

#### Loan Analysis

* Loan distribution
* Loan types
* Loan amounts
* Loan status
* Customer loan behaviour

---

# 📈 3. Statistical Analysis

Statistical techniques were applied to understand the characteristics and relationships within the dataset.

### Techniques used

* Mean
* Median
* Mode
* Variance
* Standard deviation
* Quartiles
* Percentiles
* Outlier analysis
* Correlation analysis
* Hypothesis testing

### Example Questions

**Question 1:**
Is there a relationship between customer income and deposit amount?

**Question 2:**
Is the average transaction value significantly different between customer segments?

**Question 3:**
Which customer characteristics are associated with higher financial activity?

Statistical results were interpreted from a **business perspective**, rather than focusing only on numerical outputs.

---

# 🗄️ 4. MySQL & SQL Analysis

The cleaned data was loaded into MySQL for structured analysis.

### SQL concepts used

```text
SELECT
WHERE
GROUP BY
ORDER BY
HAVING
CASE
JOIN
Subqueries
CTEs
Window Functions
Aggregate Functions
Date Functions
```

### Key Business Questions

1. What is the total number of customers?
2. What is the total deposit amount?
3. What is the total loan amount?
4. Which account type has the highest number of customers?
5. Which customer segment has the highest deposit value?
6. What is the average transaction value?
7. Which month has the highest transaction volume?
8. Which customers have the highest total deposits?
9. Which loan type has the highest outstanding amount?
10. What is the month-over-month transaction growth?
11. What are the top customers by financial activity?
12. Which regions/branches generate the highest financial activity?

---

# 📊 5. Power BI Dashboard

The analysed data was connected to Power BI to create an interactive banking analytics dashboard.

## Dashboard Pages

### 🏠 Page 1 — Executive Overview

Key KPIs:

* Total Customers
* Total Deposits
* Total Loans
* Total Transactions
* Average Transaction Value
* Active Accounts

Visualizations:

* Financial performance trends
* Customer distribution
* Deposit trends
* Loan trends
* Account-type analysis

---

### 💰 Page 2 — Deposit Analysis

Analyses:

* Total deposits
* Deposits by customer segment
* Deposits by account type
* Monthly deposit trends
* Top depositors
* Deposit distribution

---

### 🏦 Page 3 — Loan Analysis

Analyses:

* Total loans
* Loan amount
* Loan types
* Loan status
* Loan trends
* Customer loan distribution

---

### 👥 Page 4 — Customer Analysis

Analyses:

* Customer demographics
* Customer segments
* Account ownership
* Customer financial activity
* High-value customers
* Customer behaviour

---

# 📌 Key KPIs

The dashboard tracks important banking KPIs such as:

```text
Total Customers
Total Deposits
Total Loans
Total Transactions
Average Transaction Value
Active Customers
Average Loan Amount
Deposit Growth
Loan Growth
Customer Activity
```

---

# 💡 Business Insights

The analysis aims to identify insights such as:

* Which customer segments contribute the highest financial value.
* Which account types have the strongest customer adoption.
* Which periods show increased transaction activity.
* Which customers demonstrate high financial engagement.
* Which loan categories contribute significantly to the loan portfolio.
* Where deposit and loan performance can be improved.

> **Note:** Final insights will be updated based on the actual analysis results.

---

# 🎯 Business Recommendations

Based on the analytical findings, potential recommendations include:

### 1. Customer Segmentation

Develop targeted financial products for high-value and high-engagement customer segments.

### 2. Deposit Growth

Use customer transaction and account behaviour to identify customers with potential for higher deposits.

### 3. Loan Strategy

Focus loan campaigns on customer segments with suitable financial characteristics and demand.

### 4. Customer Engagement

Use transaction behaviour to identify less-active customers and develop targeted engagement strategies.

### 5. Data-Driven Decision Making

Use the Power BI dashboard to continuously monitor key financial and customer KPIs.

---

# 🚀 How to Run the Project

## Step 1 — Download the Dataset

Place the raw dataset inside:

```text
data/raw_data.csv
```

## Step 2 — Excel Analysis

Open:

```text
excel/banking_analysis.xlsx
```

Review the data and perform initial cleaning and KPI analysis.

## Step 3 — Python Analysis

Open the Jupyter Notebook:

```text
python/banking_eda.ipynb
```

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

Run the notebook to perform data cleaning, EDA and statistical analysis.

## Step 4 — MySQL

Create the database and import the cleaned data.

Run:

```text
sql/database_schema.sql
```

Then execute:

```text
sql/analysis_queries.sql
```

for business analysis.

## Step 5 — Power BI

Open:

```text
powerbi/banking_dashboard.pbix
```

Connect the dashboard to the cleaned/analysed data and refresh the model.

---

# 📸 Dashboard Preview

Add screenshots of your Power BI dashboard here.

```text
[Dashboard Overview Screenshot]

[Deposit Analysis Screenshot]

[Loan Analysis Screenshot]

[Customer Analysis Screenshot]
```

---

# 📚 Skills Demonstrated

This project demonstrates practical knowledge of:

### Technical Skills

* Excel
* Python
* Pandas
* NumPy
* MySQL
* SQL
* Power BI
* DAX
* Data Cleaning
* Data Transformation
* Data Modelling
* Data Visualization

### Analytical Skills

* Exploratory Data Analysis
* Statistical Analysis
* Correlation Analysis
* Hypothesis Testing
* KPI Analysis
* Trend Analysis
* Customer Segmentation
* Business Analysis
* Data Storytelling

---

# 🎓 Key Learning Outcomes

Through this project, I developed practical experience in:

* Working with real-world structured datasets
* Cleaning and validating data
* Performing exploratory data analysis
* Writing SQL queries for business problems
* Applying statistical techniques to business data
* Creating meaningful KPIs
* Building Power BI dashboards
* Communicating analytical findings
* Translating data into business recommendations

---

# 👨‍💻 Author

**[Soumen]**

B.Tech — Computer Science & Business Systems
GMIT


## ⭐ Project Summary

> **Banking Customer & Financial Analytics** is an end-to-end data analytics project that combines **Excel, Python, Statistics, MySQL, SQL and Power BI** to transform raw banking data into actionable customer and financial insights.
