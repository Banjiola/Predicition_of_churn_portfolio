# Predicition_of_churn_portfolio
In this project, we aim to predict customer churn using various features such as payment methods, contract type, and whether a customer streams TV or movies. This task is crucial for companies to identify potential 'churners' and take actions to retain them.

## Dataset
The dataset contains customer information with the following features:

- Gender (Male, Female)
- Senior Citizen (Indicates if the customer is a senior citizen)
- Partner (Whether the customer has a partner)
- Dependents (Whether the customer has dependents)
- Tenure (Number of months the customer has stayed with the company)
- Phone Service (Yes/No)
- Multiple Lines (Whether the customer has multiple lines)
- Internet Service (DSL, Fiber optic, No)
- Online Security (Yes/No)
- Online Backup (Yes/No)
- Device Protection (Yes/No)
- Tech Support (Yes/No)
- Streaming TV (Yes/No)
- Streaming Movies (Yes/No)
- Contract (Month-to-month, One year, Two years)
- Paperless Billing (Yes/No)
- Payment Method (Electronic check, Mailed check, Bank transfer, Credit card)
- Monthly Charges (Customer's monthly spending)
- Total Charges (Cumulative charges paid by the customer

## Models
1. Logistic Regression
2. Support Vector Machines
3. Feedforward Neural Network 

## Evaluation of Models
The models were evaluated using average recall, a robust metric that effectively handles class imbalance.
- Logistic Regression ** Average recall** : 0.73 
- Support Vector Machines ** Average recall** : 0.72
- Feedforward Neural Network  ** Average recall** : 0.68
