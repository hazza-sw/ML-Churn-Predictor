# Churn Prediction Web App

[**Access the Web App**](https://ml-churn-predictor-hazzasw.streamlit.app/)

## Overview
The **Churn Prediction Web App** is an interactive platform that predicts whether a customer is likely to churn based on specific input features. Built using **Streamlit**, the app utilizes a pre-trained machine learning model to deliver accurate predictions, aiding businesses in enhancing customer retention strategies.

## Features

### **Interactive Input Form**
- Users can input details like:
  - **Age**
  - **Tenure**
  - **Monthly Charges**
  - **Gender**
- A clean and intuitive design makes it accessible for non-technical users.

![Input Form](input.jpg)

### **Data Analysis with Jupyter Notebook**
- A **Jupyter Notebook** (`notebook.ipynb`) is included for detailed data exploration and model development:
  - **Data Visualization**:
    - Pie charts to show churn distribution.
    - Histograms and bar charts for feature analysis.
  - **Feature Engineering**:
    - Data preprocessing and scaling using `scikit-learn`.
  - **Model Training**:
    - Logistic Regression and Decision Tree models trained using GridSearchCV for hyperparameter tuning.
  - **Performance Metrics**:
    - Models evaluated using accuracy scores and confusion matrices.

![Data Visualization - Churn Distribution](flow1.jpg)
![Data Visualization - Contract Type Analysis](flow2.jpg)
![Monthly Charges Histogram](flow3.jpg)
![Model Accuracy](flow4.jpg)
![GridSearchCV Tuning Results](flow5.jpg)

[**Explore the complete data analysis and model development process in the Jupyter Notebook**](https://github.com/hazza-sw/ML-Churn-Predictor/blob/main/notebook.ipynb)

### **Streamlit Dashboard**
- The dashboard provides predictions based on user inputs with a focus on simplicity and usability.
- Powered by a pre-trained logistic regression model (`model.pkl`) and scaled features using `scaler.pkl`.

![Full App View](full_pageview.jpg)

## Technologies Used
- **Python**: Core programming language for backend and model development.
- **Streamlit**: Framework for building the interactive web app.
- **scikit-learn**: For model training, hyperparameter tuning, and scaling.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For visualizations in the Jupyter Notebook.

## Files in the Repository
- **`app.py`**: Main Streamlit application script.
- **`customer_churn_data.csv`**: Dataset used for training the machine learning model.
- **`model.pkl`**: Pre-trained logistic regression model.
- **`scaler.pkl`**: Scaler for preprocessing input features.
- **`notebook.ipynb`**: Jupyter Notebook documenting the full machine learning workflow.
- **Images**: 
  - `flow1.jpg`, `flow2.jpg`, `flow3.jpg`, `flow4.jpg`, `flow5.jpg`: Visualizations from the Jupyter Notebook.
  - `input.jpg`, `full_pageview.jpg`: App interface screenshots.
