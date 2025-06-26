# 📦 E-commerce Return Rate Reduction Analysis

## 🎯 Objective
Identify why customers return products and how return rates vary by **category**, **geography**, and **marketing channel**. Use data-driven insights to reduce return rates and flag high-risk products.

---

## 🛠️ Tools Used
- **Python** (Pandas, Scikit-learn)
- **Power BI**
- **SQL** 

---

## 📚 Mini Guide

### ✅ Step 1: Data Cleaning & Preparation
- Loaded `Supplement.csv` dataset containing order, product, location, and return details.
- Created `Return_Flag` to identify whether a product was returned.

### ✅ Step 2: Exploratory Data Analysis (EDA)
- Analyzed **return percentages** by:
  - Product `Category`
  - Sales `Platform`
  - `Location` (Geography)
- Identified top returned products.
- Visualized return risk factors using **Power BI dashboards**.

### ✅ Step 3: Predictive Modeling
- Used **Logistic Regression** to predict the probability of return.
- Features used: `Category`, `Platform`, `Location`, `Price`, and `Discount`.
- Added a new column `Return_Prob` to store predicted probability scores.

### ✅ Step 4: High-Risk Product Extraction
- Filtered products with `Return_Prob > 0.7` as high-risk.
- Saved these products into a separate file: `high_risk_products.csv`.

### ✅ Step 5: Power BI Dashboard
- Built an **interactive dashboard** with:
  - KPIs: Total Orders, High-Risk Orders, Average Return Probability
  - Return % by Category, Platform, Location
  - Scatter plot of Discount vs Return Risk
  - Drill-through filters and slicers
  - Table of top high-risk products with return probabilities

---

## 📁 Files Included

| File |
|-------------|
| Raw dataset used for analysis |
| Products with return probability > 0.7 |
| Python code for data processing and prediction |
| Power BI Dashboard (if applicable) |
| Project documentation |

---

## 📌 Key Deliverables

- ✅ **Interactive Power BI Dashboard** with drill-through filters  
- ✅ **Python Codebase** for data preparation and prediction  
- ✅ **CSV of High-Risk Products** based on model output

---

## 🧠 Insights Gained
- Categories like `<insert category>` showed the highest return rates.
- Platforms such as `<insert platform>` had elevated return risk.
- Locations like `<insert region>` showed significantly higher return probabilities.
- Discounts correlated with a slight increase in return probability.

---

## ✨ Conclusion
This project successfully combined Python modeling and Power BI visualizations to identify and reduce e-commerce return rates through targeted risk analysis.

