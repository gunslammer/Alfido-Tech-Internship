# 🏦 Loan Prediction – Task 2

This project builds a supervised machine learning model to predict whether a loan application
will be approved or rejected based on borrower details such as income, credit history,
loan amount, and property area.

The dataset consists of 614 records with 12 features. Missing values were handled through
imputation, categorical variables were encoded, and SMOTE was applied to address the class
imbalance (~69% approved vs ~31% rejected). Six models were trained and compared —
Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, XGBoost, and LightGBM.
LightGBM achieved the best performance with a ROC-AUC of ~0.87. SHAP values were used to
interpret predictions, with Credit History and Total Income identified as the strongest
predictors. A decision threshold sweep was performed to find the optimal cut-off beyond
the default 0.5.

---

## 🛠 Tech Stack

Python, Scikit-Learn, XGBoost, LightGBM, SHAP, Imbalanced-Learn, Pandas, NumPy, Matplotlib, Seaborn

---

## 📎 Deliverables

| Deliverable | Link |
|-------------|------|
| 📓 Google Colab Notebook | [Open in Colab](https://colab.research.google.com/drive/11a8a3s9E0xhwAk5PzUn5_CV1giNsfp-2?usp=sharing) |
| 📄 Model Report (PDF) | [View Report](https://github.com/gunslammer/Alfido-Tech-Internship/blob/main/TASK-2/loan_prediction_report.pdf) |

---

> **Internship:** Alfido Tech | Virtual ML Implementation Intern
