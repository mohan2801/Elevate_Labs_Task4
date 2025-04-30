# Logistic Regression - Breast Cancer Prediction

This project demonstrates how to use Logistic Regression to classify tumors as benign or malignant using the Breast Cancer Wisconsin dataset.

## What this project does

- Loads and preprocesses the dataset
- Splits the data into training and testing sets
- Scales the features using StandardScaler
- Trains a logistic regression model
- Evaluates the model using:
  - Confusion matrix
  - Precision
  - Recall
  - ROC-AUC score
- Tunes the classification threshold to improve performance
- Plots the ROC curve and sigmoid function

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Results

Evaluation metrics from the model:
- Confusion Matrix:
  [[70  1]
  [ 2 41]]
- Precision: 0.9761904761904762
- Recall: 0.9534883720930233
- ROC-AUC Score: 0.99737962659679

## Files Included

- `data.csv` - The dataset used
- `logistic_regression.ipynb` - The notebook with all code and output
- `README.md` - Project description

## How to Run

1. Make sure you have Python installed.
2. Install required libraries using pip:
