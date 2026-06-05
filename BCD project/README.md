# Breast Cancer Detection using Machine Learning

## Project Overview
This project predicts whether a breast tumor is **Malignant (M)** or **Benign (B)** using machine learning algorithms.

## Dataset
- Dataset: `breast_cancer_wisconsin_cleaned.csv`
- Target column: `diagnosis`
- Mapping:
  - Malignant (M) -> 1
  - Benign (B) -> 0

## Libraries Used
- pandas
- numpy
- scikit-learn

## Models Implemented
1. K-Nearest Neighbors (KNN)
2. Logistic Regression
3. Gaussian Naive Bayes

## Workflow
1. Load dataset
2. Data preprocessing
3. Train-test split
4. Train models
5. Evaluate accuracy
6. Perform 10-fold cross validation

## Run
```bash
pip install -r requirements.txt
jupyter notebook
```

Open the notebook and run all cells.
