# Credit Risk and Financial Stability Analysis

## Overview

This project presents a comprehensive analysis of credit risk and financial stability using machine learning and quantitative risk assessment techniques. The study focuses on predicting borrower default risk, evaluating model performance, estimating expected losses, and assessing the impact of adverse economic conditions on financial stability.

The project integrates borrower-level credit data with financial risk management concepts to demonstrate how data analytics can support decision-making in banking and financial institutions.

---

## Objectives

* Understand the fundamentals of credit risk and financial stability.
* Identify key factors influencing borrower default behavior.
* Develop predictive models for credit risk classification.
* Compare the performance of multiple machine learning algorithms.
* Estimate Probability of Default (PD), Loss Given Default (LGD), and Exposure at Default (EAD).
* Conduct stress testing under adverse macroeconomic scenarios.
* Assess the impact of economic shocks on financial stability.

---

## Dataset

**Dataset:** German Credit Dataset

The dataset contains borrower-level information including:

* Age
* Gender
* Housing Status
* Employment Information
* Savings Account Status
* Checking Account Status
* Credit Amount
* Loan Duration
* Loan Purpose
* Credit Risk Classification

Target Variable:

* Good Risk
* Bad Risk

---

## Methodology

### Data Preprocessing

* Missing Value Treatment
* Duplicate Record Analysis
* Categorical Encoding
* Feature Scaling
* Feature Engineering

### Exploratory Data Analysis

* Risk Distribution Analysis
* Demographic Analysis
* Credit Amount Analysis
* Loan Duration Analysis
* Correlation Analysis
* Borrower Segmentation

### Machine Learning Models

1. Logistic Regression
2. Random Forest Classifier
3. Gradient Boosting Classifier

### Model Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix

---

## Financial Stability Analysis

The project extends beyond borrower-level risk prediction by incorporating financial stability assessment.

### Stress Testing Scenarios

* Normal Economic Conditions
* Mild Recession Scenario
* Severe Economic Crisis Scenario

### Risk Metrics

Expected Loss is estimated using:

EL = PD × LGD × EAD

Where:

* PD = Probability of Default
* LGD = Loss Given Default
* EAD = Exposure at Default

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Jupyter Notebook
* SQL
* Power BI

---

## Project Structure

```text
credit-risk-financial-stability-analysis/
│
├── data/
├── notebooks/
├── src/
├── images/
├── reports/
├── powerbi/
├── requirements.txt
└── README.md
```

---

## Key Findings

* Machine learning models can effectively predict borrower default risk.
* Ensemble models such as Random Forest and Gradient Boosting provide strong predictive performance.
* Credit amount, loan duration, and financial profile significantly influence default probability.
* Economic stress scenarios increase expected losses and financial vulnerability.
* Data-driven risk assessment improves credit risk management and financial resilience.

---

## Business Applications

This project can support:

* Credit Risk Management
* Loan Approval Systems
* Portfolio Risk Monitoring
* Banking Analytics
* Financial Stability Assessment
* Regulatory Stress Testing
* Risk-Based Decision Making

---

## Future Enhancements

* Integration of XGBoost and LightGBM models
* Hyperparameter optimization
* Explainable AI (SHAP Analysis)
* Real-time credit scoring dashboard
* Advanced macroeconomic stress testing
* MLOps deployment pipeline

---

## Author

**Abhay Kumar Mandal**

PGDM (Business Analytics)

Project: Credit Risk and Financial Stability Analysis

Academic Year: 2024–2026

---

## License

This project is intended for academic, educational, and portfolio purposes.

