# Customer Churn Prediction

## Overview
A logistic regression model to predict customer churn for a telecom company, achieving ~80% accuracy. Includes business intelligence insights like churn drivers and retention strategies.

## Dataset
Telco Customer Churn from Kaggle: [https://www.kaggle.com/datasets/blastchar/telco-customer-churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Installation
1. Clone the repo: `git clone https://github.com/tekena-manuel/customer-churn-prediction.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebook: `jupyter notebook Customer Churn Prediction Project.ipynb` (or your notebook name)

## Key Results
- **Accuracy**: ~80%
- **Churn Rate**: 26.54%
- **Top Churn Drivers**: High MonthlyCharges, Fiber optic plans (positive coefficients).
- **Retention Insights**: Longer tenure and two-year contracts reduce churn.

## Business Intelligence Angle
Targeting high-risk customers (e.g., expensive plans) with discounts could reduce churn by 10%, saving ~$157,000 annually (based on avg. $70/month charge).

## Visualization
![Feature Importance](feature_importance.png)

## Usage
Open the notebook in Jupyter to explore the code, from data loading to modeling.

Built as part of an MSc AI for Business Intelligence portfolio. 🚀
