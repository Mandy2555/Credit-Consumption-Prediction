# 📊 Credit Consumption Prediction - Capstone Project

## 🔍 Project Overview
This machine learning project aims to predict the average **credit card consumption** of banking customers over the next three months. The data, sourced from a leading bank, includes detailed information on **customer demographics**, **behavioral patterns**, and **transactional histories**. The model can help the bank better understand customer spending behavior and tailor financial products accordingly.

---

## 🎯 Objective

- Predict the average future 3-month **credit card spending** for customers with missing target values.
- Build and validate regression models using **demographic** and **behavioral** features.
- Evaluate performance using **Root Mean Square Percentage Error (RMSPE)**.

---

## 📁 Dataset Description

1. **CustomerDemographics.csv**
   - Gender, Age, Income Level
   - Account Type, Employment & Bank Tenure
   - Region, NetBanking Usage

2. **CustomerBehaviorData.csv**
   - Monthly Credit/Debit Card Spend & Count (April–June)
   - Loan Status & EMI Activity
   - Monthly Investment Data
   - Monthly Debit/Credit Amounts & Frequency

3. **CreditConsumptionData.csv**
   - `cc_cons`: Target Variable (average credit card spend in next 3 months)
   - Missing values exist in target column; model will predict for these entries.

---

## 🧰 Tools & Technologies

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Scikit-learn** for regression modeling
- **Jupyter Notebook** for development & analysis

---

## 🧪 Approach

1. **Data Preprocessing**
   - Merged multiple datasets on customer ID
   - Handled missing values and type conversions
   - Outlier detection and treatment

2. **Exploratory Data Analysis (EDA)**
   - Visualized patterns in card usage, income, and investments
   - Analyzed correlations between features and target variable

3. **Feature Engineering**
   - Created new variables like total transactions, total spend, and financial ratios
   - Normalized skewed features

4. **Model Development**
   - Trained multiple models: Linear Regression, Decision Tree, Random Forest
   - Selected best model based on RMSPE

5. **Prediction**
   - Generated predicted credit consumption values for customers with missing targets

---

## 📈 Results

- Achieved optimized **RMSPE** performance using tuned regression models
- Provided a complete prediction set for business application
- Enabled bank to better segment and serve customers based on predicted spend

---

## 📂 Repository Structure

