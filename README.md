# Rainfall Prediction Project

## Introduction

This project is focused on predicting rainfall using advanced data science and machine learning techniques. The project demonstrates how to handle imbalanced datasets, label encoding for categorical variables, using advanced methods like MICE for data imputation, identifying and removing outliers, and feature selection using filter and wrapper methods. Additionally, it explores the balance between speed and performance for various popular models and evaluates the best metrics for performance assessment in imbalanced datasets, such as Accuracy, F1 Score, or Cohen's Kappa.

## Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Features](#features)
5. [Dependencies](#dependencies)
6. [Configuration](#configuration)
7. [Documentation](#documentation)
8. [Examples](#examples)
9. [Troubleshooting](#troubleshooting)
10. [Contributors](#contributors)
11. [License](#license)

## Installation

To use this project, first install the necessary dependencies:

```bash
pip install -r requirements.txt
```

## Usage

This project is structured as a Jupyter notebook, providing a hands-on, interactive environment for data analysis and model training. To use the project:

1. Install Jupyter Notebook or Jupyter Lab.
2. Open the `Rainfall_Prediction.ipynb` notebook.
3. Run the cells sequentially to understand the data processing, model training, and evaluation steps.


## Features

- Imbalance Handling in Datasets
- Label Encoding for Categorical Variables
- Data Imputation using MICE
- Outlier Identification and Removal
- Feature Selection using Filter and Wrapper Methods
- Comparison of Model Performance and Speed
- Performance Metrics for Imbalanced Datasets


### Example

The last cell in the notebook provides a comprehensive comparison of different machine learning models like CatBoost, XGBoost, and Random Forest. It includes code for training these models, evaluating their performance, and visualizing the results in terms of accuracy, ROC AUC, Cohen's Kappa, and execution time.

Here is a snippet from the final section:

```python
# Example of training an XGBoost model
import xgboost as xgb
params_xgb = {'n_estimators': 500, 'max_depth': 16}
model_xgb = xgb.XGBClassifier(**params_xgb)
model_xgb, accuracy_xgb, roc_auc_xgb, coh_kap_xgb, tt_xgb = run_model(model_xgb, X_train, y_train, X_test, y_test)
```


Last updated on: 2024-02-11

Last updated on: 2024-02-12

Last updated on: 2024-02-13

Last updated on: 2024-02-16

Last updated on: 2024-02-19

Last updated on: 2024-02-20

Last updated on: 2024-02-20

Last updated on: 2024-02-25

Last updated on: 2024-02-26

Last updated on: 2024-03-01

Last updated on: 2024-03-02

Last updated on: 2024-03-04