# Sansone-Diabetes-Prediction-Challenge

## 📌 Project Overview
This project is part of the **2025 Kaggle Playground Series**, specifically Season 5, Episode 12 ([link](https://www.kaggle.com/competitions/playground-series-s5e12)). The goal of this competition is to leverage machine learning techniques to predict the probability that a patient will be diagnosed with diabetes based on various clinical and demographic features.

## 🗂️ Dataset
The dataset provided for this challenge is **synthetically generated** from real-world data, ensuring a balance between realistic feature relationships and the security of test labels.
The dataset for this competition (both train and test) was generated from a deep learning model trained on the Diabetes Health Indicators Dataset. Feature distributions are close to, but not exactly the same, as the original. 

The target is *diagnosed_diabetes* and for the testing data you should predict the probability of *diagnosed_diabetes*.

## 🎯 Objectives
- **Predictive Modeling:** Build a robust binary classification model to estimate the probability of a diabetes diagnosis.
- **Skill Development:** Practice tabular data processing, feature engineering, and hyperparameter tuning.
- **Performance Optimization:** Maximize the model's performance as measured by the ROC AUC metric.

## 📊 Evaluation Metric
Submissions are evaluated based on the **Area Under the ROC Curve (AUC-ROC)** between the predicted probability and the observed target.

### Submission Format
The submission file must be a CSV file with a header and the following format:
```csv
id,diagnosed_diabetes
700000,0.2
700001,0.4
700002,0.5
...
