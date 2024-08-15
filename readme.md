# Customer Churn Prediction

This project aims to predict customer churn using historical data from a telecommunications company. The goal is to identify customers who are likely to discontinue using the service, enabling the business to take proactive measures to retain them.

## Table of Contents
- [Project Overview](#project-overview)
- [Data](#data)
- [Project Steps](#project-steps)
  - [1. Problem Definition](#1-problem-definition)
  - [2. Data Collection](#2-data-collection)
  - [3. Data Preprocessing](#3-data-preprocessing)
  - [4. Exploratory Data Analysis (EDA)](#4-exploratory-data-analysis-eda)
  - [5. Feature Engineering](#5-feature-engineering)
  - [6. Model Selection](#6-model-selection)
  - [7. Model Training](#7-model-training)
  - [8. Model Evaluation](#8-model-evaluation)
  - [9. Conclusion](#9-conclusion)
- [How to Use](#how-to-use)
- [Results](#results)
- [References](#references)

## Project Overview
Customer churn prediction is vital for businesses that rely on subscription-based models. By predicting which customers are likely to churn, companies can implement targeted interventions to retain them, ultimately improving customer satisfaction and revenue.

## Data
The dataset used in this project comes from a telecommunications company and includes customer demographic data, account information, and service usage details.

## Project Steps

### 1. Problem Definition
The goal is to predict whether a customer will churn based on historical data. The problem is formulated as a binary classification task.

### 2. Data Collection
The data was sourced from a sample telecommunications dataset, which includes customer demographics, account details, and service usage information.

### 3. Data Preprocessing
- Handled missing values and formatted columns appropriately.
- Encoded categorical variables using one-hot encoding.
- Scaled numerical features using `StandardScaler`.

### 4. Exploratory Data Analysis (EDA)
- Analyzed distribution of features.
- Identified correlations between features.
- Visualized churn rates across various customer segments.

### 5. Feature Engineering
- Created new features that could help improve the model's prediction accuracy.
- Selected relevant features for model training.

### 6. Model Selection
- Several machine learning algorithms were considered. Logistic Regression was chosen for its simplicity and effectiveness in binary classification.

### 7. Model Training
- The model was trained on the preprocessed dataset.
- Hyperparameters were tuned to optimize model performance.

### 8. Model Evaluation
- The model achieved an accuracy of 82%.
- Detailed classification report highlighting precision, recall, and F1-score for both churn and non-churn classes.

### 9. Conclusion
The model performs well overall, especially in predicting non-churn customers. However, there's room for improvement in identifying churned customers, which can be achieved through techniques like resampling, hyperparameter tuning, or experimenting with different models.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/SOliyhan/customer-churn-prediction.git
