
---

## 🔧 Methodology

### 1. Data Preprocessing
- Merged all datasets on `ID`
- Handled missing values using median/mode imputation
- Treated outliers using IQR capping
- Created derived features like `avg_cc_txn` and `total_cc_spend`
- One-hot encoded categorical variables

### 2. Modeling
- Model used: **Random Forest Regressor**
- Trained on 15,000 customers with known `cc_cons`
- Validated using **RMSPE (Root Mean Square Percentage Error)**

### 3. Prediction
- Predicted `cc_cons` for 5,000 customers with missing values
- Output saved as an Excel file

---

## 📈 Evaluation Metric

**Root Mean Square Percentage Error (RMSPE)**  
Used to compare predicted and actual values of credit card spend.

\[
\text{RMSPE} = \sqrt{ \frac{1}{n} \sum \left( \frac{y_{\text{true}} - y_{\text{pred}}}{y_{\text{true}}} \right)^2 }
\]

---

## ✅ Deliverables

- Cleaned dataset with feature engineering
- Exploratory data analysis (EDA)
- Predictive model with performance evaluation
- Predictions for customers with missing `cc_cons`
- Detailed documentation and code comments
