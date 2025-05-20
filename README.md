📁 Repository: Social Network Ads - Logistic Regression with Standardization
Author: Yash Shandilya

This project demonstrates a complete machine learning pipeline using the Social_Network_Ads.csv dataset from Kaggle. The goal is to understand the impact of feature standardization on the performance of a logistic regression classifier.

📊 Dataset Overview
The dataset contains simulated user information and whether they purchased a product after seeing a social network ad. The key columns are:

User ID: Unique identifier for each user (not used for training)

Gender: Categorical feature (Male/Female)

Age: Numerical feature representing the age of the user

EstimatedSalary: Numerical feature for user’s salary estimate

Purchased: Target variable (0 = No, 1 = Yes)

🔍 Workflow Summary
Exploratory Data Analysis (EDA)

Visualized feature distributions, correlations, and purchase behavior.

Checked for outliers, class balance, and feature relevance.

Data Preprocessing & Standardization

Applied StandardScaler to normalize Age and EstimatedSalary.

Gender was label encoded (if used in modeling).

Comparison of Standardization Effect

Plotted feature space before and after scaling using scatter plots.

Observed how feature distribution changed due to standardization.

Model Training: Logistic Regression

Trained logistic regression models on:

Raw (unstandardized) features

Standardized features

Evaluated and compared both models using accuracy scores.

📈 Key Insights
Standardization significantly improved model convergence and classification boundary.

Logistic regression performs better on standardized data due to better handling of feature scale.

Visualization confirms how scaling brings features to a comparable scale, aiding in model performance.

📂 Files in This Repository
Social_Network_Ads.csv – Dataset from Kaggle

eda_visualization.ipynb – EDA & visualization notebook

logistic_regression_comparison.ipynb – Model training and evaluation

README.md – Project overview (this file)
