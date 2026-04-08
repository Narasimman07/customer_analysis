# 📊 Telecom Customer Churn Analysis

## 📌 Project Overview
This project focuses on analyzing customer churn behavior in a telecom dataset. The goal is to identify patterns and factors that contribute to customer churn and provide actionable business insights.

---

## 📂 Dataset
- Total Records: 3333
- Features: 11 (before feature engineering)
- Target Variable: `Churn` (0 = No, 1 = Yes)

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🔍 Data Analysis Steps

### 1. Data Exploration
- Checked data types and structure
- Verified missing values
- Generated statistical summary

### 2. Data Cleaning
- Removed duplicates
- Ensured dataset consistency

### 3. Feature Engineering
Created new meaningful features:
- AvgCallDuration
- TotalUsage
- CostPerMin
- HighServiceCalls (≥3 calls)
- HeavyUser (above median usage)

---

## 📊 Key Visualizations
- Churn Distribution
- Monthly Charges vs Churn
- Contract Renewal Impact
- Service Calls vs Churn

---

## 📈 Key Insights

- 📉 Overall churn rate: **14.49%**
- 📄 Customers without contract renewal:
  - Churn Rate ≈ **42%**
- 📞 High customer service calls increase churn probability
- 💰 Medium-paying customers churn more than high-paying customers
- 📊 High usage customers show higher churn trends

---

## 🧠 Business Recommendations

- Improve customer support experience
- Provide incentives for contract renewal
- Target medium-value customers with retention strategies
- Monitor high-usage customers proactively

---

## 🚀 Future Improvements

- Build Machine Learning model for churn prediction
- Deploy dashboard using Power BI / Tableau
- Perform feature importance analysis

---

## 📬 Contact
If you like this project, feel free to connect with me on LinkedIn!# customer_analysis
