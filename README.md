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

### **Jupyter Notebook**
- The repository includes a detailed **Jupyter Notebook** (`notebook.ipynb`) that documents the entire machine learning pipeline:
  - **Data Exploration**: Initial exploration and visualization of the dataset.
  - **Feature Engineering**: Transforming raw data into meaningful inputs for the model.
  - **Model Training**: Training a classification model to predict churn.
  - **Evaluation**: Assessing model performance using metrics such as accuracy and precision.

![Jupyter Notebook Workflow](images/jupyter_notebook_workflow.png)

### **Clean Dashboard Design**
- Built with **Streamlit**, the app offers an intuitive and visually appealing layout.
- Input fields and output results are displayed in a structured format for ease of use.

![App Dashboard](images/app_dashboard.png)

## Technologies Used
- **Python**: Backend programming language.
- **Streamlit**: Framework for creating the interactive web app.
- **scikit-learn**: For model training and feature preprocessing.
- **Pandas**: For data manipulation and preprocessing.
- **Jupyter Notebook**: For prototyping, data exploration, and model training.

## Files in the Repository
- **`app.py`**: The main script for running the Streamlit app.
- **`customer_churn_data.csv`**: Dataset used for training the machine learning model.
- **`model.pkl`**: Trained machine learning model.
- **`scaler.pkl`**: Scaler for feature preprocessing.
- **`notebook.ipynb`**: Jupyter Notebook documenting the machine learning pipeline.

## Screenshot
![Churn Prediction Web App](images/app_screenshot.png)
