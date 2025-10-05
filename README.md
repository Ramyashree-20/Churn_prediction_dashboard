🧠 Customer Churn Prediction Using Machine Learning
📋 Project Overview

This project aims to predict whether a customer will churn (discontinue a service) using machine learning techniques. By analyzing customer behavior, demographics, and account information, the model helps businesses identify at-risk customers and improve retention strategies.

🎯 Objectives

Analyze and understand customer churn patterns.

Clean, preprocess, and engineer meaningful features.

Build and compare multiple ML models to predict churn.

Visualize insights through interactive Power BI dashboards.

Recommend business strategies to reduce customer churn.

🧩 Dataset

Source: Telco Customer Churn dataset

Format: CSV file (WA_Fn-UseC_-Telco-Customer-Churn.csv)

Size: ~7,000 customer records

Key Columns:

gender, SeniorCitizen, Partner, Dependents

tenure, Contract, PaymentMethod, MonthlyCharges

Churn (Target Variable: Yes / No)

⚙️ Project Workflow

Data Collection & Loading

Imported CSV data using pandas

Checked data structure, types, and missing values

Exploratory Data Analysis (EDA)

Used Seaborn and Matplotlib to visualize churn trends

Correlation heatmaps, countplots, and distribution plots

Identified key factors affecting churn: tenure, contract type, payment method

Data Preprocessing

Handled missing values and categorical encoding

Performed feature scaling using StandardScaler

Split dataset into training and testing sets

Feature Engineering

Created meaningful derived features to improve model performance

Used correlation analysis to drop redundant variables

Model Building & Comparison

Implemented and evaluated the following models:

Logistic Regression

Decision Tree

Random Forest

XGBoost

Best Model: Logistic Regression with 80% accuracy

Model Evaluation Metrics

Accuracy, Precision, Recall, F1-Score, ROC-AUC Curve

Confusion matrix to interpret churn predictions

Model Saving

Saved trained model as churn_prediction_model.pkl

Saved scaler and feature list for future deployment

Visualization (Power BI)

Designed interactive Power BI dashboard

Showed churn percentage by contract type, tenure, and payment method

Provided insights for decision-makers

💻 Tech Stack
Category	Tools / Libraries
Programming	Python
Data Analysis	Pandas, NumPy
Visualization	Matplotlib, Seaborn, Power BI
Machine Learning	Scikit-learn, XGBoost
Environment	Jupyter Notebook, VS Code
📊 Results

Achieved 80% accuracy using Logistic Regression model.

Identified top churn indicators:

Short tenure

Month-to-month contracts

Electronic check payments

Insights can help target high-risk customer groups and design retention campaigns.

🏆 Key Skills Demonstrated

Data Cleaning & Feature Engineering

Model Training & Evaluation

Business Insights from Data

Data Visualization & Dashboarding

End-to-End ML Pipeline
