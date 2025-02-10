Overview
This repository contains a generalized version of the predictive modeling approach used in the Humana Data Science Competition, where our team advanced to Round 2 as a Top 50 team out of 280+ teams.

The goal of the competition was to predict members under Local Preferred Provider Organization (LPPO) plans who were unlikely to engage in preventive care visits with their Primary Care Physicians (PCPs).

Approach & Methodology
1. Data Preprocessing
Handled 1.5M+ observations with 300 features
Applied one-hot encoding, low-variance feature removal, and feature engineering to improve data quality
Used SQLite for data management and Tableau for visualization
2. Model Selection & Training
Experimented with various models, with XGBoost providing the best performance
Used k-fold cross-validation to prevent overfitting
Optimized hyperparameters using Bayesian optimization
3. Model Evaluation
Assessed performance using AUC-ROC, precision-recall, and feature importance analysis
Fine-tuned thresholds to balance recall and precision for better predictions
Technologies Used
Python: pandas, numpy, scikit-learn, XGBoost
Data Visualization: matplotlib, seaborn, Tableau
Database Management: SQLite
Confidentiality Notice
🚨 This repository does NOT contain any proprietary Humana data, confidential information, or original competition datasets. All data-related elements have been replaced with synthetic examples to comply with the confidentiality agreement.

Next Steps
Explore additional feature engineering techniques
Experiment with deep learning models for improved performance
Optimize efficiency for deployment in a real-world healthcare setting
Acknowledgments
A huge thank you to my team members and the Humana competition organizers for this great learning experience!

