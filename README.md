# Customer Churn Prediction

## Introduction
The goal of this project is to predict customer churn based on customer attributes. The dataset used in this project contains information about customers, such as account age, subscription type, monthly charges, viewing habits, and more. The notebook walks through the data preprocessing steps, exploratory data analysis (EDA), and the training of multiple models, including Logistic Regression, Random Forest, and Feedforward Neural Networks (FNN).

## Features

- **Data Preprocessing**: Handles missing values, data normalization, feature engineering, and encoding categorical variables.
- **Exploratory Data Analysis (EDA)**: Provides visualizations of numerical and categorical features, as well as churn distribution.
- **Feature Engineering**: Segmentation of age and monthly charges, correlation analysis, and outlier detection.
- **Machine Learning Models**: Logistic Regression, Random Forest, and Feedforward Neural Networks (FNN) models are built and evaluated.
- **Resampling Techniques**: Address imbalanced data using SMOTE and Random Undersampling techniques.
- **Evaluation Metrics**: Includes accuracy, recall, F1-score, and confusion matrices.

## Models

The following models are implemented in the notebook:

- Logistic Regression: A basic classification model with hyperparameter tuning.
- Random Forest: A tree-based ensemble method for classification.
- Feedforward Neural Network (FNN): A deep learning model implemented using PyTorch.

## Dependencies
The following libraries are required to run the notebook:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `torch`
- `pandasql`
- `imblearn`
  
Install them via:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn torch pandasql imblearn
```

## Results

Our best model is a Random Forest Classifier with accuracy 0.637 and ROC AUC 0.677 after resampling.
