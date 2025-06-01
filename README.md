# Customer Churn Prediction Project

This project is focused on predicting customer churn using machine learning techniques. The dataset is based on telecom customer data and includes information such as customer demographics, services signed up for, and account information.

## Dataset
The dataset contains columns such as:
- `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- `tenure`, `PhoneService`, `InternetService`, `Contract`
- `MonthlyCharges`, `TotalCharges`, and `Churn` (target variable)

## Steps Performed
1. Data Cleaning and Preprocessing
2. Encoding Categorical Variables
3. Feature Scaling
4. Model Training using Logistic Regression
5. Evaluation using Accuracy, Classification Report, and Confusion Matrix

## Results
The model achieved good performance using basic preprocessing and logistic regression.

## Confusion Matrix Example
![Confusion Matrix](confusion_matrix_example.png)

## Requirements
```bash
pip install -r requirements.txt
```

## Run in Colab
You can also open the `.ipynb` notebook in Google Colab for easy execution.
