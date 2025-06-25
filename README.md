# Disease_prediction

This project was completed as part of an internship under YBI Foundation.

# Project Overview
The objective of this project is to predict the likelihood of disease occurrence based on various blood test parameters. It leverages classification-based machine learning techniques to analyze medical data and provide predictive insights.

# Dataset Description
The dataset includes several blood test parameters such as:

 Glucose level

 Cholesterol level

 Hemoglobin

 White Blood Cell (WBC) count

And other relevant biomarkers

# Exploratory Data Analysis (EDA)
To understand the dataset and its patterns, multiple data visualization techniques were used:

 Line plots

 Box plots

 Histogram plots

 Correlation heatmaps

# Feature Engineering
Key features were selected based on correlation and domain knowledge.

Label Encoding was used to handle categorical variables.

# Model Training
Several classification algorithms were trained and evaluated to find the best performing model. These include:

Logistic Regression

Decision Tree

K-Nearest Neighbors

Random Forest Classifier (Best performer)

# Results
Random Forest Classifier achieved the highest accuracy of 94%.

## Model Deployment
The trained model was saved in binary format using pickle for future inference and deployment.

