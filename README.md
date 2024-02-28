# Customer_Churn_Rate_Prediction
Overview
This project aims to predict customer churn for a telecommunications company. Customer churn, also known as customer attrition, refers to the phenomenon where customers stop doing business with a company. Predicting churn can help businesses understand and anticipate customer behavior, allowing them to take proactive measures to retain customers and mitigate revenue loss.

Dataset
The dataset used for this project contains information about telecom customers, including demographics, services subscribed, and churn status. The dataset includes the following columns:

customerID: Unique identifier for each customer
gender: Customer's gender (e.g., Male, Female)
SeniorCitizen: Whether the customer is a senior citizen (0: No, 1: Yes)
Partner: Whether the customer has a partner (Yes, No)
Dependents: Whether the customer has dependents (Yes, No)
tenure: Number of months the customer has been with the company
PhoneService: Whether the customer has phone service (Yes, No)
MultipleLines: Whether the customer has multiple lines (Yes, No, No phone service)
InternetService: Type of internet service subscribed (DSL, Fiber optic, No)
OnlineSecurity: Whether the customer has online security service (Yes, No, No internet service)
OnlineBackup: Whether the customer has online backup service (Yes, No, No internet service)
DeviceProtection: Whether the customer has device protection service (Yes, No, No internet service)
TechSupport: Whether the customer has tech support service (Yes, No, No internet service)
StreamingTV: Whether the customer has streaming TV service (Yes, No, No internet service)
StreamingMovies: Whether the customer has streaming movie service (Yes, No, No internet service)
Contract: The contract term of the customer (Month-to-month, One year, Two year)
PaperlessBilling: Whether the customer has paperless billing (Yes, No)
PaymentMethod: Payment method used by the customer (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic))
MonthlyCharges: The amount charged to the customer monthly
TotalCharges: The total amount charged to the customer
Churn: Whether the customer churned (Yes, No)
Goals
Perform Exploratory Data Analysis (EDA) to visualize and understand the distribution of features and the relationship between each feature and customer churn.
Predict customer churn using various machine learning models, including Logistic Regression, Random Forest, XGBoost, and CatBoost.
Understand how each feature impacts the predicted churn using feature importance and SHAP (SHapley Additive exPlanations).
Files
customer_churn_prediction.ipynb: Jupyter Notebook containing the code for EDA, model training, and evaluation.
your_dataset.csv: CSV file containing the dataset used in the project.
README.md: This README file providing an overview of the project.
Usage
Clone the repository to your local machine.
Install the required libraries listed in requirements.txt using pip install -r requirements.txt.
Open and run the Jupyter Notebook customer_churn_prediction.ipynb to explore the code and execute the analysis.
Dependencies
Python 3.x
Jupyter Notebook
pandas
scikit-learn
xgboost
shap
Credits
This project is created by [Your Name].
