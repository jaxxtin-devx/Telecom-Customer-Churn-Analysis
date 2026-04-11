# Telecom Customer Churn Analysis & Retention Strategy

**End-to-End Exploratory Data Analysis (EDA)** on Telecom Customer Churn for Retention Strategy

### 📋 Problem Statement
A leading telecom company is facing high customer churn, resulting in significant revenue loss. This project aims to identify key churn drivers and provide actionable retention strategies.

### 🎯 Business Objective
- Understand major factors causing customer churn
- Identify high-risk customers
- Deliver data-driven recommendations to reduce churn

### 🛠️ Tools & Technologies
- **Python** | **Pandas** | **NumPy** | **Seaborn** | **Matplotlib**
- Google Colab

### 🔥 Key Insights
- Month-to-month contracts have **~42.7%** churn rate
- 2-year contracts have only **~2.8%** churn rate
- Fiber Optic users churn more than DSL
- New customers (0-12 months) have very high churn
- Tech Support, Online Security & Online Backup significantly reduce churn

### 📊 Important Visualizations

![Churn by Contract](plots/1_churn_by_contract.png)
![Churn by Internet](plots/2_churn_by_internet.png)
![Churn by Tenure Group](plots/3_churn_by_tenure_group.png)
![Protective Services](plots/4_protective_services.png)

### 💡 Business Recommendations
1. Convert Month-to-Month customers to annual contracts with discounts
2. Review Fiber Optic pricing and service quality
3. Focus retention efforts on new customers (first 12 months)
4. Promote Tech Support and Security add-ons
5. Incentivize better payment methods (avoid Electronic Check)

### 📁 Project Structure
- `Telecom_Customer_Churn_Analysis.ipynb` → Main Analysis Notebook
- `plots/` → All visualizations
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` → Dataset

---

**Made for Data Analyst Portfolio**  
Analyzed 7043 customer records using Python
