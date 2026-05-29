# Payments App Churn Prediction — Product Case Study

A machine learning project predicting customer churn for a payments app, 
framed as a product management case study.

## Executive Summary
Optimised XGBoost model reduces missed churners by 37%, saving ~$116,000 
per 10,000 customers in retained revenue.

## Key Findings
- **Contract type** is the strongest churn predictor — month-to-month users 
  churn at 4x the rate of annual subscribers
- **New users in first year** churn at 48% — critical onboarding intervention window
- **High-value users ($70+/month)** churn at 38% — counterintuitive and highest revenue risk

## Product Recommendations
1. Annual contract incentive program with tiered rewards
2. Early lifecycle retention program targeting first 12 months
3. High-value customer relationship program for $70+ monthly spenders
4. Friction reduction — nudge electronic check users toward auto-debit

## Models
| Model | Accuracy | Precision | Recall | AUC |
|-------|---------|-----------|--------|-----|
| Random Forest | 79.8% | 67.0% | 46.9% | 0.838 |
| Logistic Regression | 74.9% | 51.6% | 82.3% | 0.862 |
| XGBoost (selected) | 81.4% | 68.6% | 55.0% | 0.862 |
| XGBoost (optimised, t=0.10) | 69.2% | 40.0% | 94.9% | 0.862 |

## Tools
Python, Pandas, Scikit-learn, XGBoost, Plotnine, Matplotlib

## Background
Built by a former corporate banking relationship manager transitioning 
to fintech product management — combining domain expertise with ML 
to derive actionable product insights from customer data.
