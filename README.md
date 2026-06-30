# telco-customer-churn-prediction
Machine Learning project for predicting customer churn using the Telco Customer Churn dataset with data preprocessing, EDA, visualization, and Random Forest classification.
# Customer Churn Prediction Using Machine Learning

## Project Overview

Customer churn prediction is a machine learning project that identifies customers who are likely to leave a company's services. By analyzing customer demographics, subscription details, and usage patterns, the model predicts whether a customer will churn or remain with the company.

This project uses the Telco Customer Churn dataset and applies machine learning techniques to build a predictive model that helps businesses improve customer retention strategies.

## Objectives

* Analyze customer behavior and subscription patterns.
* Perform data cleaning and preprocessing.
* Visualize key insights through Exploratory Data Analysis (EDA).
* Build a machine learning model for churn prediction.
* Evaluate model performance using standard metrics.
* Identify the most important factors influencing customer churn.

## Dataset

Dataset: Telco Customer Churn Dataset

The dataset contains information such as:

* Gender
* Senior Citizen Status
* Tenure
* Internet Service
* Online Security
* Online Backup
* Contract Type
* Payment Method
* Monthly Charges
* Total Charges
* Churn Status

Target Variable:

* Churn

  * 0 = Customer Stays
  * 1 = Customer Leaves

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab / Jupyter Notebook

## Project Workflow

### 1. Data Collection

* Loaded the Telco Customer Churn dataset.

### 2. Data Preprocessing

* Removed unnecessary columns.
* Handled missing values.
* Converted data types.
* Encoded categorical variables.

### 3. Exploratory Data Analysis

* Churn distribution analysis.
* Correlation analysis.
* Customer behavior visualization.

### 4. Model Building

* Split dataset into training and testing sets.
* Trained a Random Forest Classifier.
* Generated predictions on test data.

### 5. Model Evaluation

* Accuracy Score
* Confusion Matrix
* Classification Report

### 6. Feature Importance Analysis

Identified the most influential features affecting customer churn, including:

* Total Charges
* Monthly Charges
* Tenure
* Contract Type
* Payment Method

## Results

The model successfully predicts customer churn and highlights key business factors that contribute to customer retention and attrition.

Key Findings:

* Customers with higher monthly charges are more likely to churn.
* Contract type significantly impacts customer retention.
* Customers with shorter tenure are more likely to leave.
* Total charges and payment methods influence churn behavior.


## Future Improvements

* Hyperparameter tuning for better accuracy.
* Compare multiple machine learning models.
* Deploy the model using Flask or Streamlit.
* Create an interactive dashboard for business users.

## Conclusion

This project demonstrates an end-to-end machine learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, and interpretation. The churn prediction model can help businesses identify at-risk customers and take proactive measures to improve customer retention.

## Author

swapna meesala

B.Tech Student | Data Science & Machine Learning Enthusiast

GitHub: https://github.com/swapna-design/telco-customer-churn-prediction

LinkedIn: https://www.linkedin.com/in/swapna-meesala-1203b1416/
