# credit-card-default-prediction

##Overview

This project focuses on predicting whether a customer will default on their credit card payment in the next month using a supervised machine learning model. The dataset used for this project is the UCI Credit Card dataset, which includes customer demographic information, payment history, and bill statements.

##Project Workflow

The project follows a structured pipeline to ensure accurate predictions and meaningful insights:

1. Data Collection:

-- Dataset: UCI Credit Card Default Dataset.

-- Features: Demographic details (age, gender, education), credit limit, payment history, and default status.

2. Data Preprocessing:

-- Handle missing values.

--Normalize numerical features.

Encode categorical variables.

Exploratory Data Analysis (EDA):

Analyze distributions and trends.

Visualize correlations using heatmaps and plots.

Identify key predictors of default.

Model Development:

Train/Test Split.

Train models including Logistic Regression, Random Forest, and Gradient Boosting.

Evaluate performance using metrics such as accuracy, precision, recall, and F1-score.

Model Deployment:

Save the trained model.

Implement a Streamlit web app for user interaction and prediction.
