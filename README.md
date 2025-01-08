# Churn Prediction Web App

[**Access the Web App**](https://ml-churn-predictor-hazzasw.streamlit.app/)

## Overview
The **Churn Prediction Web App** is an interactive tool developed using **Streamlit** to predict whether a customer is likely to churn. The app utilizes a pre-trained machine learning model to provide quick and actionable insights for businesses to improve customer retention strategies.

## Features

### **Interactive Input Form**
- Users can enter customer details such as:
  - **Age**
  - **Tenure** (number of months the customer has been with the company).
  - **Monthly Charges**.
  - **Gender** (Male/Female).
- The interface is simple and user-friendly, making it accessible for non-technical users.

![Input Form](images/input_form.png)

### **Machine Learning Predictions**
- **Pre-trained Model**: The app uses a machine learning model (`model.pkl`) trained on customer churn data to make accurate predictions.
- **Feature Scaling**: Inputs are standardized using a pre-saved scaler (`scaler.pkl`) for consistency with the training data.
- **Binary Output**:
  - **"Yes"**: Indicates the customer is likely to churn.
  - **"No"**: Indicates the customer is unlikely to churn.

![Prediction Output](images/prediction_output.png)

### **Clean Dashboard Design**
- Built with **Streamlit**, the app offers an intuitive and visually appealing layout.
- Input fields and output results are displayed in a structured format for ease of use.

![App Dashboard](images/app_dashboard.png)

## Technologies Used
- **Python**: Backend programming language.
- **Streamlit**: Framework for creating the interactive web app.
- **scikit-learn**: For model training and feature preprocessing.
- **Pandas**: For data manipulation and preprocessing.

## Files in the Repository
- **`app.py`**: The main script for running the Streamlit app.
- **`customer_churn_data.csv`**: Dataset used for training the machine learning model.
- **`model.pkl`**: Pre-trained machine learning model.
- **`scaler.pkl`**: Pre-saved scaler for feature preprocessing.
- **`notebook.ipynb`**: Jupyter Notebook for data exploration, preprocessing, and model training.

## Screenshot
![Churn Prediction Web App](images/app_screenshot.png)
