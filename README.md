# SaaS Customer Churn Prediction – Telco Dataset

## Project Overview

This project analyzes a real-world telecommunications dataset to predict customer churn and extract actionable business insights. It was designed to simulate the type of product analytics and modeling work often required by SaaS and subscription-based companies.

The goal is to:
- Predict churn using machine learning models
- Identify key features that influence customer retention
- Provide data-informed recommendations for reducing churn

## Dataset Description

The dataset contains demographic, account, and service usage information for over 7,000 customers. Key variables include:

- Contract type (month-to-month, one year, two year)
- Internet service and optional features (e.g., OnlineSecurity, TechSupport)
- Payment method and billing information
- Customer tenure and total charges
- Churn status (target variable)

## Key Findings

- Month-to-month contract users had a churn rate of 42%, compared to 11% (one year) and 2.8% (two year).
- Customers with Online Security and Tech Support were significantly more likely to stay.
- Churn was highest among customers using electronic check as a payment method.
- Auto-payment methods (bank transfer or credit card) were associated with lower churn.

## Modeling Approach

Two models were trained and evaluated:
- Logistic Regression
- Random Forest Classifier

Both were evaluated on accuracy, precision, recall, and F1-score.

| Model               | Accuracy | Precision (Churn) | Recall (Churn) | F1 Score |
|--------------------|----------|-------------------|----------------|----------|
| Logistic Regression| 78.7%    | 61.8%             | 52.4%          | 56.7%    |
| Random Forest      | 79.2%    | 64.4%             | 48.9%          | 55.6%    |

## Tools and Libraries

- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebook
- Matplotlib and Seaborn for data visualization

## File Structure
/saas-churn-prediction
│
├── data/
│ └── telco_churn_clean.csv
│
├── notebooks/
│ └── churn_modeling_analysis.ipynb
│
├── visuals/
│ └── churn_by_contract.png
│ └── feature_importance_rf.png
│
├── slides/
│ └── churn_insights_summary.pdf
│
└── README.md


## About the Author

Jeff Charles  
Data science graduate student focused on analytics, product strategy, and behavior-driven insights.  
Passionate about using data to solve high-impact business problems.

[LinkedIn](https://www.linkedin.com/in/charlesjeff)

