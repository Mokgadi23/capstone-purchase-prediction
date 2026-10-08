# Capstone Project: Predicting Purchase Conversion and Segmenting Customers

- **Student:** Mokgadi Morupane (202202179)
- **Institution:** Sol Plaatje University, Department of Computer Science & Information Technology
- **Lecturer:** Mrs Nthabiseng Modiba

## Overview
This project uses one month of e-commerce clickstream data (99,884 events, 21,365 users) to:
1. Predict whether a browsing event ends in a purchase, using Logistic Regression, Decision Tree, Random Forest and SVM.
2. Segment customers by behaviour using K-Means clustering.

## Key results
- Best model: Random Forest, ROC-AUC 0.680 (target 0.65)
- Top predictors: price, brand, category
- Four K-Means clusters: Casual Browsers, Window Shoppers, Active Buyers and one outlier account

## Files
- `analysis_notebook.ipynb`: full analysis (cleaning, EDA, feature engineering, modelling, clustering)
- `cleaned_recentdata.csv`: dataset used

## How to run
1. Download all files into one folder.
2. Install the libraries the notebook imports (pandas, numpy, scikit-learn, matplotlib, seaborn).
3. Open the notebook in Jupyter and choose Run All.
