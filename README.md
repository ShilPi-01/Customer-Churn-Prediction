# Customer-Churn-Prediction

This project implements a Customer Churn Prediction system using Python, Machine Learning, and a Flask web application.
The goal of this project is to predict whether a customer is likely to leave (churn) a service, helping businesses make data-driven decisions to retain customers.

Project Overview
-> Data Analysis & Model Building
-> The project starts in Jupyter Notebook where data is cleaned, explored, and preprocessed.
-> A Random Forest Classifier is used as the baseline model.
-> XGBoost is implemented to improve performance, achieving higher accuracy and better predictive results.
-> The model predicts whether a customer will churn or stay based on input features like tenure, services subscribed, payment method, monthly charges, and more.

Web Application with Flask
A user-friendly web interface is built using Flask and Bootstrap.Users can input customer details through a form. On submission, the application predicts if the customer will churn and displays the prediction along with probability.
The app demonstrates the deployment of a machine learning model into a real-world, interactive environment.

Features
1. Predict customer churn with high accuracy using XGBoost.
2. Interactive web interface for easy user input.
3. Responsive design with Bootstrap for seamless experience across devices.
4. Provides both the prediction and probability of churn.

Tools & Technologies
- Python: Data preprocessing, modeling.
- Jupyter Notebook: Exploratory Data Analysis (EDA) and model training.
- Scikit-learn: Random Forest and preprocessing tools.
- XGBoost: Optimized model for better accuracy.

Flask: Web application framework.
- Bootstrap: Frontend styling.

How It Works :-
1. The ML model is trained on historical customer data.
2. Users provide customer information via a web form.
3. The Flask app sends input to the trained model.
4. The model predicts whether the customer will churn and returns the result.
