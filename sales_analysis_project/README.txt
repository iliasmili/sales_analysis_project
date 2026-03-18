# 🛒 Superstore Sales Analysis — End to End Data Analysis Project

## 📌 Project Overview
An end-to-end data analysis project using Python and PostgreSQL to analyze 
retail sales data from a US Superstore. The project covers the full data 
analysis pipeline: cleaning, preparing, transforming, analyzing, and 
communicating results through visualizations.

---

## 🛠️ Tools & Technologies
- **Python** (pandas, matplotlib, seaborn)
- **PostgreSQL** (database storage & SQL queries)
- **SQLAlchemy** (Python-PostgreSQL connection)
- **Jupyter Notebook** (VSCode)

---

## 📂 Project Structure
```
sales_analysis_project/
│
├── data/
│   ├── superstore.csv              ← Raw dataset
│   ├── sales_by_region.png         ← Chart 1
│   ├── sales_by_category.png       ← Chart 2
│   ├── yearly_sales_trend.png      ← Chart 3
│   ├── monthly_sales_trend.png     ← Chart 4
│   └── top_customers.png           ← Chart 5
│
├── notebooks/
│   └── analysis.ipynb              ← Full analysis notebook
│
└── README.md
```

---

## 🔄 Project Steps

### 1️⃣ Clean
- Checked for missing values and duplicates
- Fixed data types for Order Date and Ship Date
- Converted Postal Code from number to text

### 2️⃣ Prepare
- Extracted Order Year, Order Month, Order Month Name
- Calculated Days to Ship for each order

### 3️⃣ Transform (SQL)
- Loaded cleaned data into PostgreSQL database
- Wrote SQL queries to aggregate data by Region, Category, Customer

### 4️⃣ Analyse
- Identified top performing regions and categories
- Discovered unprofitable customers despite high revenue
- Analysed yearly and monthly sales trends

### 5️⃣ Communicate
- Built 5 professional charts using matplotlib & seaborn

---

## 📊 Key Findings

- 🌍 **West region** is the top performer with $725,458 in sales
- 💻 **Technology** is the most profitable category ($145,454 profit)
- 🪑 **Furniture** has high sales but very low profit — potential cost issue
- ⚠️ **Sean Miller** is the #1 customer by sales but generates negative profit (-$1,980)
- 📈 Sales grew consistently from **$484,247 (2014) to $733,215 (2017)**
- 🎄 **November** is the peak sales month ($352,461) — driven by holiday season

---

## 📁 Dataset
- **Source:** Kaggle — Superstore Dataset
- **Rows:** 9,994
- **Columns:** 21
- **Period:** 2014 — 2017

---

## 👤 Author
Your Name  
[LinkedIn Profile](#) | [GitHub Profile](#)