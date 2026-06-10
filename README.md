# personal-loan-campaign-prediction
Classification model that predicts which liability customers of AllLife Bank are most likely to accept a personal loan offer, helping marketing target high-propensity segments.
AllLife Bank — Personal Loan Campaign Prediction

AllLife Bank's customer base is dominated by depositors (liability customers), while its borrower base remains small. To grow its loan business, the bank wants to convert more liability customers into personal loan customers without losing their deposits. A previous campaign achieved a ~9% conversion rate, and the marketing team is now looking for smarter targeting to push that number higher.

This project builds a supervised machine learning model to predict the probability that a liability customer will purchase a personal loan, and identifies the customer attributes and segments that drive conversion — enabling the marketing department to focus campaigns on high-propensity prospects.

Key objectives

Predict whether a liability customer will accept a personal loan offer
Identify the most significant attributes influencing loan purchase decisions
Recommend customer segments the bank should prioritize in future campaigns
Dataset features Customer demographics (Age, Experience, Family, Education), financial profile (Income, CCAvg, Mortgage), and existing relationship with the bank (Securities Account, CD Account, Online Banking, Credit Card usage), with Personal_Loan as the target variable.

Approach

Exploratory Data Analysis (EDA) and data cleaning
Feature engineering and treatment of outliers / anomalies (e.g., negative experience values)
Model building using Decision Tree / Logistic Regression classifiers
Hyperparameter tuning and pruning to control overfitting
Model evaluation using Recall, Precision, F1-score, and Confusion Matrix (with Recall prioritized — missing a likely buyer is costlier than a false positive)
Feature importance analysis to surface key drivers of conversion
Tech stack: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook

Deliverables: Cleaned dataset, EDA notebook, trained classification model, evaluation metrics, feature importance insights, and actionable recommendations for the marketing team.
