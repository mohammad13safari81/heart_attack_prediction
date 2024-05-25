# Heart Attack Prediction Project
## Overview
This machine learning project focuses on predicting heart attacks using data from 350 patients. The dataset includes several features, and our goal is to build a model that can accurately predict the likelihood of a heart attack based on these features.

## Project Structure
Data Analysis (EDA): In a separate file, we performed exploratory data analysis (EDA) on the patient data. This step involved understanding the data distribution, identifying missing values, and visualizing relationships between features.
#### Baseline Model with PyCaret:
We started by creating a baseline model using PyCaret’s AutoML capabilities. This allowed us to quickly establish a benchmark performance.
The baseline model serves as a reference point for evaluating subsequent improvements.
#### Feature Engineering:
We conducted feature engineering to enhance the predictive power of our models.
Outliers were handled appropriately to ensure robustness.
#### Model Training and Optimization:
We trained several models, including decision trees, random forests, and XGBoost.
Grid search was employed to fine-tune hyperparameters and optimize model performance.
## Final Model: GradientBoostingClassifier
After rigorous experimentation, we achieved a model with an accuracy exceeding 90% on the test data.
The GradientBoostingClassifier emerged as the top-performing model.
We used SHAP (SHapley Additive exPlanations) to identify the most influential factors for heart attack prediction.
