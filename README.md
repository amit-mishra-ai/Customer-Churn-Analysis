# 📊 Telco Customer Churn Analysis  
### Exploratory Data Analysis (EDA) | Data Visualization | Power BI Dashboard | DAX

---

## 🚀 Project Overview

Customer churn is one of the most critical challenges in the telecom industry. Retaining an existing customer is significantly more cost-effective than acquiring a new one.

This project follows a **two-stage analytical approach**:

1️⃣ **Exploratory Data Analysis (EDA)** using Python  
2️⃣ **Executive-Level Interactive Dashboard** using Power BI  

The objective was not just to analyze churn patterns, but to connect customer behavior directly to **revenue impact and business strategy**, enabling data-driven retention decisions.

---

## 🎯 Business Objectives

- Understand customer demographics and service usage patterns  
- Identify key factors contributing to churn  
- Quantify financial impact of customer attrition  
- Detect high-risk customer segments  
- Provide actionable business recommendations  
- Build a foundation for predictive churn modeling  

---

# 🔎 Phase 1: Exploratory Data Analysis (EDA)

## 🛠 Tools & Technologies Used

- **Python**
- **Pandas** – Data manipulation & preprocessing  
- **NumPy** – Numerical analysis  
- **Matplotlib & Seaborn** – Data visualization  
- **Jupyter Notebook** – Interactive analysis  

---

## 📌 1. Data Understanding & Cleaning

- Explored dataset structure and feature distributions  
- Checked for missing values and handled inconsistencies  
- Converted data types (e.g., `TotalCharges` to numeric)  
- Validated categorical and numerical features  
- Ensured data quality before analysis  

---

## 📌 2. Univariate Analysis

Analyzed individual features such as:

- Customer Tenure  
- Contract Type  
- Payment Method  
- Internet Service  
- Monthly Charges  
- Total Charges  
- Service Subscriptions  

This helped identify customer distribution trends and early churn signals.

---

## 📌 3. Bivariate & Multivariate Analysis

Compared churn vs non-churn customers across multiple dimensions:

- Contract vs Churn  
- Tenure vs Churn  
- Monthly Charges vs Churn  
- Payment Method vs Churn  
- Internet Service vs Churn  
- Service Bundle Adoption vs Churn  

Techniques used:

- Distribution analysis  
- Category-based churn comparison  
- Correlation insights  
- Comparative visualizations  

Key analytical questions addressed:

> What factors are influencing customers to leave?  
> Which segments are at the highest churn risk?

---

## 📊 Key EDA Insights

### 🔹 Contract Type Strongly Impacts Churn
Month-to-month customers exhibit significantly higher churn compared to long-term contracts.

### 🔹 Tenure is a Powerful Predictor
Customers within their first 12 months show elevated churn rates, highlighting onboarding challenges.

### 🔹 Pricing Sensitivity Exists
Higher monthly charges correlate with increased churn probability.

### 🔹 Value-Added Services Reduce Churn
Customers subscribed to Online Security and Tech Support show lower churn rates.

### 🔹 Payment Method Influences Churn Behavior
Electronic check users demonstrate significantly higher churn trends.

---

# 📊 Phase 2: Power BI Executive Dashboard

After completing EDA, insights were translated into a **2-page interactive Business Intelligence dashboard**.

---

## 🛠 Tools & Skills Applied

- **Power BI**
- **DAX (Data Analysis Expressions)**
- KPI Development
- Revenue Impact Analysis
- Data Modeling
- Interactive Dashboard Design
- Customer Segmentation
- Business Intelligence Reporting

---

## 📈 Page 1: Revenue & Risk Overview

Focused on executive-level KPIs:

- Total Customers  
- Total Churn Customers  
- Churn Rate (26.5%)  
- Revenue Churn Rate (17.8%)  
- Total Revenue ($16.1M)  
- Revenue Loss by Contract Type  

### Key Findings:

- Month-to-month contracts account for the highest revenue loss ($1.93M)  
- Early lifecycle customers (0–12 months) show ~47% churn rate  
- Revenue churn rate lower than customer churn rate → lower-value customers churn more  

---

## 📊 Page 2: Detailed Segmentation & Risk Analysis

Focused on churn drivers and behavioral segmentation:

- Churn Rate by Payment Method  
- Churn Rate by Internet Service  
- Churn Rate by Online Security  
- Churn Rate by Gender, Partner, Dependents  
- Average Monthly Charges (Overall vs Churned)  
- Average Tenure of Churned Customers  

### Key Dashboard Insights:

- Electronic check users → 45% churn rate  
- Fiber optic customers → 41.9% churn rate  
- Customers without online security churn nearly 3x more  
- Churned customers have higher average monthly charges ($74 vs $64)  

---

# 💡 Business Recommendations

✔ Encourage migration to long-term contracts  
✔ Strengthen onboarding experience during first 12 months  
✔ Improve payment channel experience  
✔ Bundle value-added services (Online Security, Tech Support)  
✔ Implement proactive retention strategies for high-revenue customers  

These strategies can directly improve Customer Lifetime Value (CLV) and reduce revenue leakage.

---

# 📈 Project Outcome

This project demonstrates:

- Strong analytical thinking  
- End-to-end data analysis workflow  
- Ability to connect churn behavior with revenue impact  
- Executive-level dashboard storytelling  
- Business-oriented data interpretation  

It reinforces that:

> EDA is not just about charts — it is about extracting insights that drive smarter decisions.

---

# 🔮 Future Scope

- Build a **Customer Churn Prediction Model**  
- Apply Machine Learning algorithms (Logistic Regression, Random Forest)  
- Develop churn risk scoring system  
- Implement customer segmentation for targeted retention campaigns  
- Integrate predictive analytics into Power BI dashboard  

---
## Snapshot Of the dashboard :
<img width="699" height="860" alt="image" src="https://github.com/user-attachments/assets/3c75a91e-d61b-4923-b4fd-ee8955de8af6" />


# 🔗 Live Dashboard

https://app.fabric.microsoft.com/view?r=eyJrIjoiYjY2NThiZTctMzRkNC00Y2ZhLTkwYTYtZTJhM2I5YzhmZGQ3IiwidCI6IjYyOTZhNGQzLTZiNjgtNGY3NC05ZWRhLWIxMDAzMzkyYzAxOCJ9

---

# 👨‍💻 Author

**Amit Kumar Mishra**  
Aspiring Data Analyst | Business Intelligence Enthusiast  
Passionate about transforming data into actionable business insights.

---

⭐ If you found this project insightful, consider giving it a star!
