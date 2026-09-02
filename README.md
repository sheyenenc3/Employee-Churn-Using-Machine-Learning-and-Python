# Predicting Employee Turnover: Salifort Motors Project

## Overview

This repository contains an end-to-end machine learning project designed to predict employee turnover at Salifort Motors. By analyzing historical employee data and performance metrics, this project builds predictive classification models to help HR leadership identify key drivers of attrition and proactively retain top talent.

## Project Pipeline & Methodology
 - Data Cleaning & Preparation: Inspected 14,999 initial employee records, verified data types, addressed missing values, and streamlined column names for clarity. Removed 3,008 duplicate rows to ensure model integrity.
 - Exploratory Data Analysis (EDA): Visualized distributions and detected outliers in employee tenure using the Interquartile Range (IQR) method (identifying an upper limit threshold of 5.5 years). Analyzed baseline churn rates (~16.6% post-deduplication).
 - Feature Engineering & Modeling Framework: Prepared features for high-performance machine learning algorithms including XGBoost, Random Forest, Decision Trees, and Logistic Regression.
 - Evaluation & Optimization: Leveraged cross-validation and hyperparameter tuning (GridSearchCV) optimized across comprehensive metrics including Precision, Recall, F1-Score, and ROC-AUC.
 
## Key Technical Stack
- Language: Python
- Data Manipulation & Analysis: Pandas, NumPy
- Machine Learning: Scikit-learn, XGBoost
- Data Visualization: Matplotlib, Seaborn
- Business Impact: The insights and predictive models derived from this pipeline empower human resources teams to transition from reactive responses to proactive talent management, ultimately reducing recruitment costs and stabilizing organizational productivity.
      
## Insights and Next Steps
1. Limit project assignments so employees aren’t overloaded.
2. Review promotion opportunities for employees with four or more years of tenure, or investigate why satisfaction drops around the four‑year mark.
3. Avoid requiring excessive hours and consider offering meaningful incentives when longer hours are necessary.
4. Clarify overtime policies and ensure expectations around workload, time off, and compensation are clearly communicated.
5. Facilitate discussions on work culture at both company and team levels to identify issues and improve the environment.
6. Use a fair evaluation scale rather than tying top performance scores to extremely high monthly hours; reward efficiency and meaningful contribution instead.
