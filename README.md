# Company Bankruptcy Risk Prediction

## Overview
This project aims to build a machine learning model that predicts whether a company is at risk of bankruptcy based on its financial metrics. Early detection of bankruptcy can help mitigate losses for stakeholders and aid in decision-making for investors and analysts.

---

## Problem Statement
Bankruptcy prediction is critical in financial risk management. The objective is to develop a binary classification model that can accurately identify companies that are likely to go bankrupt based on historical financial data.

---

## Data Source 
https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction?select=data.csv

The dataset consists of financial indicators such as:
- Financial ratios (debt, equity, liquidity)
- Profitability metrics
- Cash flow and operational metrics

---

## Steps Performed
1. **Data Loading & Preprocessing**
   - Handled missing values
   - Feature scaling and transformation
   - Label encoding (if needed)

2. **Exploratory Data Analysis (EDA)**
   - Correlation matrix
   - Distribution of features
   - Class imbalance visualization

3. **Model Building**
   - Train/Test split
   - Trained models: Logistic Regression, Random Forest, etc.
   - Resampling techniques (SMOTE or similar) for imbalance

4. **Evaluation**
   - Confusion Matrix
   - Accuracy, Precision, Recall, F1 Score
   - ROC-AUC Curve

5. **Conclusion**
   - Model comparison
   - Feature importance analysis

---

## Tools & Libraries Used
- Python 3.x
- Jupyter Notebook
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `imbalanced-learn` (for SMOTE)

---

## 📦 Requirements

Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
