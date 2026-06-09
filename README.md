TASK 1
# Movie Genre Classification

A machine learning project that predicts movie genres from plot summaries.

## Technologies Used
- Python
- Pandas
- Scikit-Learn
- TF-IDF
- Multinomial Naive Bayes
- Gradio

## Accuracy
52.25%

## Features
- Predicts movie genres from plot descriptions
- Interactive Gradio UI
- Trained on 54,000+ movie records
TASK 2
 # Credit Card Fraud Detection Using Machine Learning

Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning. A Random Forest Classifier is trained to classify transactions as either legitimate or fraudulent based on transaction-related features.

Objective

The objective of this project is to build a reliable fraud detection system that can identify suspicious transactions and help reduce financial losses.

Dataset

Dataset Used: "fraudTrain.csv"

Target Variable:

- 0 → Legitimate Transaction
- 1 → Fraudulent Transaction

The dataset contains transaction-related information such as customer details, merchant information, transaction amount, location data, and fraud labels.

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Gradio
- Google Colab

Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Selection
5. Train-Test Split
6. Model Training using Random Forest Classifier
7. Model Evaluation
8. Fraud Prediction
9. Gradio User Interface Development

Machine Learning Model

Random Forest Classifier

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

Model Performance

- Accuracy Achieved: 99.42%
- Evaluated using:
  - Accuracy Score
  - Classification Report
  - Confusion Matrix


Features

- Fraud Detection using Machine Learning
- Data Visualization
- Model Evaluation Metrics
- Fast and Accurate Predictions

Future Enhancements

- Hyperparameter Tuning
- Advanced Feature Engineering
- Streamlit Web Application Deployment
- Real-Time Fraud Detection
- Deep Learning-Based Fraud Detection Models

Conclusion

This project demonstrates how Machine Learning can be applied to detect fraudulent credit card transactions effectively. The Random Forest model achieved high accuracy and successfully classified transactions as legitimate or fraudulent.

TASK 3
# Customer Churn Prediction

Overview

Customer Churn Prediction is a Machine Learning project that predicts whether a customer is likely to leave a company based on customer demographics and account-related information. The project helps businesses identify customers who may discontinue their services and take appropriate retention measures.

Objective

The objective of this project is to develop a machine learning model that can accurately predict customer churn using historical customer data.

Dataset

The dataset used in this project is Churn_Modelling.csv.

Features

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary

Target Variable

Exited

- 0 = Customer Stays
- 1 = Customer Churns

Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

Machine Learning Algorithm

Random Forest Classifier

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

Project Workflow

1. Data Collection

- Loaded the customer churn dataset.

2. Data Preprocessing

- Removed unnecessary columns:
  - RowNumber
  - CustomerId
  - Surname
- Encoded categorical features such as Gender and Geography.

3. Feature Selection

- Selected relevant customer attributes as input features.
- Used the Exited column as the target variable.

4. Data Splitting

- Split the dataset into training data (80%) and testing data (20%).

5. Model Training

- Trained the Random Forest Classifier using the training dataset.

6. Model Evaluation

- Evaluated the model using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

7. Prediction

- Predicted whether a customer is likely to churn or stay.

Results

The trained model successfully predicts customer churn and achieves high accuracy on the testing dataset.

Future Enhancements

- Hyperparameter Tuning
- Model Comparison with Other Algorithms
- Deployment as a Web Application
- Real-Time Prediction System

Conclusion

This project demonstrates how machine learning can be used to analyze customer behavior and predict customer churn. Such predictions help organizations improve customer retention and make data-driven business decisions.
