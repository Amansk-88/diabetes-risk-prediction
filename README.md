Diabetes Risk Prediction System
An end-to-end machine learning project that predicts multi-class diabetes health risks (Low, Moderate, High) using clinical and demographic patient data.

Project Overview
This project processes a dataset of over 50,000 patient health records, implements data cleaning and feature engineering pipelines, and builds a robust ensemble classification model to assist in proactive health risk evaluation.

Key Features & Workflow
Data Preprocessing: Handled missing values via median imputation, encoded categorical variables using LabelEncoder, and standardized numerical features with StandardScaler.

Exploratory Data Analysis (EDA): Visualized feature correlations, class distributions, and key clinical biomarkers using Seaborn and Matplotlib.

Model Training & Evaluation: Trained a tuned Random Forest Classifier achieving 90% overall accuracy, utilizing multi-class weighting to effectively handle class imbalance.

Feature Importance Analysis: Extracted and ranked critical health predictors—such as Fasting Blood Sugar and HbA1c—to interpret clinical risk drivers.

Tech Stack
Language: Python

Libraries: Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib

Environment: Jupyter Notebook
