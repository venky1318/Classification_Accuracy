# Task 38 — Classification Accuracy Using Python

## Project Overview

This project demonstrates how to calculate the accuracy of a classification model and compare predicted values with actual target values using Python and Scikit-learn.

The Breast Cancer Wisconsin Diagnostic Dataset is used to perform binary classification using a Decision Tree Classifier.

The project focuses on generating predictions, comparing actual and predicted values, calculating classification accuracy, and evaluating model performance.

## Objectives

- Understand classification accuracy.
- Load and prepare a classification dataset.
- Identify input features and target variables.
- Split data into training and testing sets.
- Train a Decision Tree classification model.
- Generate predictions using the trained model.
- Compare actual and predicted values.
- Calculate accuracy score and percentage.
- Generate a confusion matrix.
- Understand classification evaluation metrics.

## Dataset Description

The project uses the Breast Cancer Wisconsin Diagnostic Dataset available through Scikit-learn.

- Total records: 569
- Numerical input features: 30
- Target classes: 2

### Target Classes

| Target Code | Diagnosis |
|---|---|
| 0 | Benign |
| 1 | Malignant |

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Google Colab
- Jupyter Notebook

## Model Used

**Algorithm:** Decision Tree Classifier

**Classification Type:** Binary Classification

**Input:** 30 numerical features.

**Target:** Diagnosis.

The dataset is divided into training and testing sets using an 80:20 split.

The model is trained using the `fit()` method and generates predictions using the `predict()` method.

## Accuracy Calculation

Classification accuracy measures the proportion of correctly predicted observations among all predictions.

**Formula:**

Accuracy = Correct Predictions / Total Predictions

Accuracy Percentage = Accuracy × 100

Scikit-learn's `accuracy_score()` function is used to calculate the accuracy.

## Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Classification Report

The actual results are available in `evaluation_summary.csv`.

## Project Workflow

1. Dataset collection.
2. Data exploration.
3. Feature and target selection.
4. Training and testing split.
5. Decision Tree model initialization.
6. Model training.
7. Prediction generation.
8. Actual versus predicted comparison.
9. Accuracy calculation.
10. Model evaluation.
11. Exporting project files.

## Project Files

- `Task_38_Classification_Accuracy.ipynb` — Complete notebook.
- `breast_cancer_dataset.csv` — Original dataset with diagnosis labels.
- `prepared_classification_dataset.csv` — Prepared dataset.
- `classification_features.csv` — Input features.
- `classification_target.csv` — Target variable.
- `classification_predictions.csv` — Actual and predicted values.
- `evaluation_summary.csv` — Accuracy and evaluation metrics.
- `classification_report.csv` — Detailed classification report.
- `confusion_matrix.csv` — Confusion matrix values.
- `classification_accuracy_model.joblib` — Saved trained model.
- `requirements.txt` — Required Python libraries.
- `project_report.pdf` — Project report.
- `charts/confusion_matrix.png` — Confusion matrix visualization.
- `screenshots/` — Project execution screenshots.

## How to Run

1. Install the required libraries using `pip install -r requirements.txt`.
2. Open the Jupyter Notebook.
3. Run all notebook cells sequentially.
4. Check the prediction results and accuracy.
5. Review the generated evaluation files.

## Results

The classification model generates predicted values for the testing dataset.

The actual accuracy score, accuracy percentage, and other evaluation metrics are stored in `evaluation_summary.csv`.

## Conclusion

This project demonstrates how classification accuracy is calculated using Python and Scikit-learn.

It provides practical experience in classification model training, prediction comparison, accuracy calculation, and model performance evaluation.

**Note:** This is an educational machine-learning exercise and is not intended for medical diagnosis.
