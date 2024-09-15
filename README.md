# Customer Churn Prediction Project

The main objective of the project is to analyze the account information of bank customers, including factors like account age, payment method, subscription method, and more, in order to predict whether a customer will leave the bank or not. 

## Project Structure

- **Package Installation and Setup**: The project starts by installing necessary packages: `sqlalchemy`, `pandasql`, and others.
  
- **Data Preprocessing**: Preprocessing steps are made to handle categorical data and feature scaling.

- **Machine Learning Models**:
  - **Logistic Regression**
  - **Random Forest Classifier**
  - **Deep Learning with PyTorch**

- **Evaluation Metrics**: The models are evaluated using multiple performance metrics, including:
  - Accuracy
  - F1-Score
  - Precision and Recall
  - ROC-AUC Score

- **Handling Imbalanced Data**: The project uses techniques such as:
  - **Random Under Sampling**: To balance the classes by reducing the majority class.
  - **SMOTE (Synthetic Minority Over-sampling Technique)**: To generate synthetic samples for the minority class.

## Requirements

The following Python packages are required to run this project:

```bash
pip install pandas numpy matplotlib seaborn sklearn torch sqlalchemy pandasql imblearn
