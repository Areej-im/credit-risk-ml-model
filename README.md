# Credit Risk ML Model  
This project predicts the credit risk of loan applicants using Machine Learning models (Logistic Regression & XGBoost).  
It simulates a real-world financial credit scoring system that estimates a customer's likelihood of default and converts it into a standardized credit score.  

---

##  Project Objective  
To help financial institutions assess whether a loan applicant is low-risk or high-risk based on their financial behavior, repayment history, and demographic factors  

---

## Machine Learning Workflow  

1. **Data Cleaning:** Handled missing values and outliers.  
2. **Exploratory Data Analysis (EDA):** Identified strong correlations between `Debt_to_Income` and default rates.  
3. **Feature Engineering:** Created derived ratios to capture financial behavior.  
4. **Model Training:**  
   - Logistic Regression (baseline)  
   - Random Forest (non-linear)  
   - **XGBoost** (final model with AUC = 0.94)  
5. **Evaluation Metrics:**  
   - ROC-AUC, Precision, Recall  
   - High Recall ensured the model correctly flags high-risk borrowers.  

---

### Live Demo  
Try the live Streamlit app here:  
 [Areej's Credit Risk Model](https://areejs-credit-risk-ml-model.streamlit.app/)

---

##  Insights  
- Clients with **Debt_to_Income > 0.5** had 3x higher default probability  
- **Credit_Utilization > 70%** flagged strong risk signals  
- Consistent income & longer tenure improved credit ratings  

---

## Tech Stack  
Python, Pandas, NumPy, Scikit-learn, XGBoost, Seaborn, Streamlit  




