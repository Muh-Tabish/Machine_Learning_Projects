# Breast Cancer Prediction using Logistic Regression

## Project Overview

This project implements a Logistic Regression model to classify breast cancer tumors as malignant or benign using the Breast Cancer Wisconsin dataset available in Scikit-Learn. The project demonstrates a complete machine learning workflow, including data preprocessing, feature scaling, model training, prediction, and performance evaluation.

## Dataset

* Dataset: Breast Cancer Wisconsin Dataset
* Source: Scikit-Learn (`load_breast_cancer`)
* Total Samples: 569
* Features: 30 numerical features
* Target Classes:

  * 0 = Malignant
  * 1 = Benign

## Technologies Used

* Python
* Pandas
* Scikit-Learn

## Machine Learning Workflow

1. Load the Breast Cancer dataset.
2. Perform train-test split.
3. Apply feature scaling using StandardScaler.
4. Train a Logistic Regression classifier.
5. Make predictions on the test set.
6. Evaluate model performance using:

   * Accuracy Score
   * Classification Report
   * Confusion Matrix

## Results

### Model Performance

| Metric   | Score  |
| -------- | ------ |
| Accuracy | 98.25% |

### Classification Report

| Class         | Precision | Recall | F1-Score |
| ------------- | --------- | ------ | -------- |
| Malignant (0) | 1.00      | 0.95   | 0.98     |
| Benign (1)    | 0.97      | 1.00   | 0.99     |

## Key Learning Outcomes

* Binary Classification
* Logistic Regression
* Data Preprocessing
* Feature Scaling
* Model Evaluation
* Healthcare Data Analysis

## Project Structure

```text
Breast_Cancer_Logistic_Regression/
│
├── logistic_regression.py
├── README.md

```


## License

This project is intended for educational and portfolio purposes.
