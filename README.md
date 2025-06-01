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
---

## 📌 Final Summary & Insights

This project successfully applies logistic regression to predict customer churn using real-world telecom data.

📈 **Key Results:**
- **Overall Accuracy:** 81.5%
- **High Precision for Non-Churned Customers (Class 0):** 0.86
- **Reasonable Precision for Churned Customers (Class 1):** 0.68

🎯 **Confusion Matrix Insights:**
- The model correctly predicted **933 loyal customers** (True Negatives)
- Detected **216 customers likely to churn** (True Positives)
- Misclassified **157 churned customers** as loyal (False Negatives)
- Only **103 loyal customers** were misclassified as churners (False Positives)

🧠 **Conclusion:**
- The logistic regression model demonstrates strong performance, especially for predicting non-churned customers.
- While the model performs reasonably for churn detection, future improvements may include:
  - Using ensemble methods like Random Forest or XGBoost
  - Handling class imbalance with techniques like SMOTE
  - Advanced feature selection or PCA

💡 This project lays a solid foundation for predictive churn modeling and can be enhanced further in a production environment.

---
