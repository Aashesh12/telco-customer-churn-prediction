# Telco Customer Churn Prediction System

## Project Overview
This machine learning project predicts whether a telecom customer
is likely to leave the company (churn). It uses customer demographics,
service subscriptions, contract details, tenure, and billing information.

## Objectives
 Explore and clean customer data.
 Analyze churn patterns.
 Train and evaluate classification models.
 Predict churn risk for new customers.
 Save model outputs and evaluation reports.

## Dataset
The project uses the Telco Customer Churn dataset.
It contains 7,043 customer records and 21 original columns.

## Models
1. Logistic Regression
2. Random Forest Classifier

## Evaluation Results

 Metric  Logistic Regression | Random Forest 

 Accuracy       73.8%             77.0% 
 Precision      50.4%             55.9%
 Recall         78.3%             63.4%    
 F1-score       61.4%             59.4%

Logistic Regression identifies a larger proportion of customers
who churned in the test set, while Random Forest achieves higher accuracy.

## Tools and Technologies
 Python
 Pandas and NumPy
 Matplotlib
 Scikit-learn
 Jupyter Notebook
 Joblib

## Project Structure
 `data/raw/`    - Original dataset
 `notebooks/`   - Data analysis and model development
 `models/`      - Saved trained model
 `outputs/`     - Reports, charts, and evaluation results

## How to Use
1. Install the required Python packages.
2. Open the notebook in Jupyter.
3. Load the saved model with Joblib.
4. Provide customer data using the same 19 input features.
5. Generate a churn prediction.

## Limitations
Model predictions are estimates, not guarantees.
Performance may change on new customer data. The models have
not been externally validated or deployed in production.

## Author
Aashesh Kumar
cs241161
DHA Suffa Univeristy 
Aashesh.kumar000@gmail.coms