# Logistic Regression on Breast Cancer Dataset

This repository contains a Jupyter Notebook for performing logistic regression on a breast cancer dataset. The notebook demonstrates various steps including loading the dataset, preprocessing, splitting the data, training the logistic regression model, and evaluating its performance.

## Dataset

The dataset used in this analysis is `cancer.csv`. Ensure this file is available in the same directory as the script or provide the correct path.

## Steps Involved

### 1. Loading the Data

The dataset is loaded using pandas. Initial exploration of the data includes displaying the first few rows and obtaining summary information about the dataset, such as data types and missing values.

### 2. Data Cleaning

The script checks for duplicate rows in the dataset and removes them if any are found. This ensures the data used for modeling is clean and free from redundancy.

### 3. Data Splitting

The features (`x`) and the target variable (`y`) are separated. The data is then split into training and testing sets using an 80-20 split ratio. This helps in evaluating the model's performance on unseen data.

### 4. Training the Model

A logistic regression model is instantiated and trained using the training data (`x_train` and `y_train`).

### 5. Making Predictions

The trained model is used to make predictions on the test data (`x_test`).

### 6. Evaluating the Model

The accuracy of the model is evaluated by comparing the predicted values (`y_pred`) with the actual values (`y_test`). The accuracy score is calculated and printed as a percentage.

## Conclusion

This script demonstrates a basic implementation of logistic regression for classification tasks using the cancer dataset. It covers essential steps from data loading and cleaning to model training and evaluation.

## Requirements

Ensure you have the following Python packages installed:

- pandas
- scikit-learn

You can install the required packages using pip:
```bash
pip install pandas scikit-learn
