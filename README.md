# 📊 Credit Risk Assessment & Recovery Dashboard

## 🔍 Project Overview
This project focuses on identifying high-risk borrowers and improving financial decision-making through data analysis and visualization.  

A complete workflow was built to analyze borrower behavior, generate risk scores, and present insights using a dashboard for better monitoring and recovery planning.

---

## 🎯 Objective
- Identify high-risk borrowers based on financial and behavioral data  
- Analyze key factors contributing to loan default  
- Provide actionable insights through dashboards for better decision-making  

---

## 🛠 Tech Stack
- **Python** (Pandas, NumPy, Scikit-learn)  
- **SQL**  
- **Power BI**  
- **Excel (Data Handling)**  

---

## 📊 Dataset
- Simulated dataset of **500 borrowers**
- Features include:
  - Age, Income, Loan Amount  
  - Credit Score, Delinquent Payments  
  - Loan Term, Region  

---

## 🔄 Approach

### 1. Data Preparation
- Generated and cleaned borrower dataset  
- Created new feature:
  - **Debt-to-Income Ratio** = LoanAmount / Income  

### 2. Exploratory Data Analysis (EDA)
- Analyzed distributions of credit score, income, and loan amount  
- Identified patterns between:
  - Credit score vs default  
  - Delinquent payments vs risk  

### 3. Risk Analysis & Modeling
- Built classification models:
  - Random Forest  
  - Gradient Boosting  
- Generated **Risk Score (probability of default)** for each borrower  

### 4. Insight Generation
- Segmented borrowers into:
  - High Risk  
  - Low/Moderate Risk  
- Identified top high-risk borrowers for proactive action  

### 5. Dashboard Integration
- Exported processed data to CSV  
- Connected dataset to **Power BI**  
- Built dashboard for:
  - Risk distribution  
  - Regional analysis  
  - Loan exposure  

---

## 📈 Key Results

- Achieved **~99–100% model accuracy** on test data *(due to simulated dataset)*  
- Successfully generated **risk scores for all borrowers**  
- Identified **top high-risk borrowers** using probability-based scoring  
- Created a structured dataset ready for dashboard visualization  

---

## 📊 Dashboard Insights

- Borrowers with:
  - **Low credit score (<600)**  
  - **Higher delinquent payments (>3)**  
  → Show significantly higher default risk  

- **Debt-to-Income ratio** is a strong indicator of financial stress  

- Certain regions show higher concentration of risky borrowers  

---

## 📁 Output
- Final dataset exported:  
  `credit_risk_dashboard.csv`  
- Used for Power BI dashboard creation  

---

## 🚀 Business Impact

- Enables early identification of risky borrowers  
- Supports better loan approval decisions  
- Improves recovery planning and monitoring  
- Reduces manual analysis effort through automation  

---

## ⚠️ Note
- Dataset is simulated for demonstration purposes  
- Accuracy is high due to controlled data conditions  

---
