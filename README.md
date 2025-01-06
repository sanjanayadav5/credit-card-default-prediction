# credit-card-default-prediction

## Overview

This project focuses on predicting whether a customer will default on their credit card payment in the next month using a supervised machine learning model. The dataset used for this project is the UCI Credit Card dataset, which includes customer demographic information, payment history, and bill statements.

## Project Workflow

The project follows a structured pipeline to ensure accurate predictions and meaningful insights:

1. Data Collection:

- Dataset: UCI Credit Card Default Dataset.

- Features: Demographic details (age, gender, education), credit limit, payment history, and default status.

2. Data Preprocessing:

- Handle missing values.
- Normalize numerical features.
- Encode categorical variables.

3. Exploratory Data Analysis (EDA):

- Analyze distributions and trends.
- Visualize correlations using heatmaps and plots.
- Identify key predictors of default.

Model Development:

- Train/Test Split.
- Train models including Logistic Regression, Random Forest, and Gradient Boosting.
- Evaluate performance using metrics such as accuracy, precision, recall, and F1-score.

Model Deployment:

- Save the trained model.
- Implement a Streamlit web app for user interaction and prediction.
## Data Flow Diagram

Below is the data flow for the project:

Input Data:

- Raw credit card data.
- Demographics, payment history, and billing details.

Data Preprocessing:

- Handle missing values, outliers, and normalization.

Model Training:

- Train/Test split.
- Model training with validation.

Prediction & Output:

- Predict default status (0 or 1).
- Output probabilities for user understanding.
## diagram
graph LR
    A[Raw Dataset] --> B[Data Preprocessing]
    B --> C[EDA]
    C --> D[Model Training]
    D --> E[Predictions]
    E --> F[Streamlit App Deployment]

## Features

- Demographics: Age, gender, education, marital status.

- Financial Details: Credit limit, bill statements, and payment amounts.

- Payment History: Delay in payments across six months.

## Setup

To run this project locally:

1. Clone the repository:

       git clone https://github.com/yourusername/credit-card-default-prediction.git

2. Install dependencies:

       pip install -r requirements.txt

3. Run the Streamlit app:

        streamlit run app.py

## Results

- Best Model: Random Forest with an accuracy of 85%.

- Key Insights:

  -- Payment delays significantly impact default predictions.

  -- Credit limit and payment amounts are strong predictors.

## Future Improvements

- Implement hyperparameter tuning for models.
 
- Add more features to improve prediction accuracy.

- Deploy on a cloud platform like AWS or Heroku for broader access.
     
