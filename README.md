# Subscription-Forecasting-in-Bank-Marketing-Campaigns-ML-Approach-


##  Project Overview

This project applies machine learning techniques to predict whether a client will subscribe to a bank term deposit based on data from direct marketing campaigns conducted by a Portuguese bank. The goal is to build a predictive model to optimize future campaign targeting.

---

##  Dataset

- **Source**: UCI Bank Marketing Dataset
- **Observations**: 45,211
- **Features**: 17 (Numerical + Categorical)

---

##  Key Steps

- Data Cleaning: Removed nulls, treated "unknown" values, handled outliers
- EDA: Univariate, Bivariate, and Multivariate visualizations (Seaborn/Matplotlib)
- Feature Encoding: Label Encoding & One-Hot Encoding
- Imbalance Handling: SMOTE applied to handle class imbalance
- Scaling: MinMaxScaler
- Modeling: Multiple classification models
- Evaluation: Accuracy, Precision, Recall, F1, ROC-AUC
- Explainability: SHAP for model interpretability

---

##  ML Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting
- XGBoost  (Best Performing)
- KNN
- Naive Bayes
- SVM
- ANN

**Best Model**: XGBoost  
**Performance**:  
- Accuracy: 93%  
- Precision: 93%  
- Recall: 93%  
- F1 Score: 93%  
- ROC-AUC: 93%

##  Key Insights

- Clients without loans are more likely to subscribe
- May had the highest subscription rate
- Cell phone contact was more successful
- Subscription is more likely within 400 seconds of conversation
- Highly educated, debt-free, managerial clients are more likely to subscribe

---

##  Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- XGBoost
- SHAP
- SMOTE (Imbalanced-learn)
- Jupyter Notebook

---

## How to Run

```bash
git clone https://github.com/yourusername/bank-marketing-subscription-forecast.git
cd bank-marketing-subscription-forecast
pip install -r requirements.txt
jupyter notebook

