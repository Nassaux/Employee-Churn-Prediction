# 📊 Employee Churn Prediction – HR Analytics Capstone  
**Salifort Motors | February 2026**  
**Author:** Antoine Nassaux  

---

## 🔎 Project Overview

This project develops a machine learning solution to help HR proactively reduce employee turnover at **Salifort Motors**.

The objective was to predict which employees are most likely to leave the company (binary target variable: `left`) and identify the key drivers of churn to support targeted retention strategies.

This project demonstrates an end-to-end applied data analytics workflow, from exploratory data analysis to model evaluation and business recommendations.

---

## 🎯 Business Objective

Employee turnover leads to:

- Recruitment and onboarding costs  
- Productivity disruption  
- Loss of institutional knowledge  

The goal of this analysis was to:

1. Predict attrition risk using supervised learning  
2. Understand what drives employee churn  
3. Provide actionable HR recommendations  

---

## 🛠 Methods & Technical Approach

### Data Preparation
- Selected business-relevant features (satisfaction, evaluation, workload, tenure, promotions, salary, department, etc.)
- Built preprocessing pipelines using:
  - `ColumnTransformer`
  - `OneHotEncoder`
- Performed an 80/20 stratified train-test split  

### Models Evaluated
- Logistic Regression (baseline)
- Decision Tree
- Random Forest (final selected model)

### Evaluation Metrics
- ROC AUC  
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

---

## 🚀 Final Model Performance (Random Forest)

- **ROC AUC:** ~0.98  
- **Accuracy:** ~98.5%  
- **Precision (leavers):** ~0.99  
- **Recall (leavers):** ~0.92  

The model correctly identifies approximately **92% of employees who leave** while maintaining very low false positive rates.

This balance enables proactive intervention with minimal operational disruption.

---

## 🔑 Key Drivers of Employee Churn

Feature importance analysis revealed:

1. Employee satisfaction (strongest predictor)
2. Tenure
3. Number of projects
4. Average monthly hours
5. Performance evaluation
6. Salary level
7. Department

Employees are most at risk when they:

- Report low satisfaction  
- Carry heavy workloads  
- Have mid-to-long tenure  
- Are high-performing but under sustained pressure  

---

## 💡 Business Recommendations

Based on model insights:

- Implement regular satisfaction pulse surveys  
- Monitor and rebalance workloads  
- Develop clearer career progression paths  
- Target retention efforts toward high-risk, high-performing employees  
- Integrate churn risk scoring into HR dashboards  

---

## 🧠 Skills Demonstrated

- End-to-end supervised machine learning workflow  
- Feature engineering & preprocessing pipelines  
- Model comparison and selection  
- Interpretation of precision vs recall tradeoffs  
- Translation of technical findings into business strategy  
- Executive-level communication of insights  

---

## 🎓 Project Goal

Use employee data to build predictive models that identify churn risk and support data-driven HR decision-making.
