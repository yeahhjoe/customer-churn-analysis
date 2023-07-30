# customer-churn-analysis
Customer Churn Project using Machine Learning Model

Introduction

Welcome to the Customer Churn Prediction data science project! In this project, we analyze customer churn data using Python, apply Decision Trees and Random Forests machine learning algorithms to predict customer churn, and develop a simple Flask-based user interface to interact with the model.

Customer churn is a critical issue for businesses, and being able to predict whether a customer is likely to churn can help companies take proactive measures to retain their valuable customers.

Dataset

The dataset used in this project contains information about customers and whether they churned or not. The dataset includes various features that provide insights into customer behavior, demographics, and usage patterns. It is crucial to understand the dataset's structure and characteristics to perform effective data analysis and build accurate predictive models.

Data Analysis

Before applying machine learning algorithms, we conducted thorough data analysis to gain a better understanding of the dataset. This involved exploring the data, handling missing values, performing data preprocessing, and conducting visualizations to identify patterns and correlations.

Machine Learning Algorithms

To predict customer churn, we utilized two popular machine learning algorithms: Decision Trees and Random Forests. Both these algorithms are powerful and capable of capturing complex relationships within the data.

Decision Trees: Decision Trees are a simple yet effective model that creates a tree-like structure to make decisions based on feature values.
Random Forests: Random Forests is an ensemble learning method that combines multiple decision trees to improve the predictive accuracy and reduce overfitting.
We trained these models using the labeled dataset and evaluated their performance to select the best model for predicting customer churn.

Flask UI

To make the churn prediction model accessible and user-friendly, we built a simple Flask-based user interface. The UI prompts the user to enter relevant data, and upon submission, it provides the likelihood of the user churning based on the trained Random Forests model.

The Flask application acts as a bridge between the user's input and the predictive model, making it easier for non-technical users to interact with the machine learning algorithm and obtain churn predictions.

Dependencies

The project has been developed using Python and utilizes the following major libraries:

Pandas: Data manipulation and analysis
NumPy: Numerical operations and array processing
Scikit-learn: Machine learning algorithms and evaluation metrics
Flask: Web application framework for the user interface
