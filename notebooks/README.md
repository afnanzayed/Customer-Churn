# Customer Churn Prediction

This repository contains a comprehensive analysis and machine learning pipeline for predicting customer churn. Through this project, we utilize multiple machine learning algorithms, tune model parameters, and evaluate performance to accurately predict which customers are likely to churn.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
4. [Feature Engineering & Scaling](#feature-engineering--scaling)
5. [Models](#models)
6. [Results](#results)
7. [Conclusion](#conclusion)

## Project Overview
The goal of this project is to predict customer churn in the telecom sector using various machine learning models. By analyzing account details, usage patterns, and customer service interactions, we aim to identify the best-performing model to help businesses improve customer retention.

## Dataset
The dataset includes customer account information, service usage, and engagement data, with a target variable indicating whether each customer has churned.

**Key Features**:
- Account Details: Information on account tenure (weeks with the service) and contract renewal status.
- Service Usage: Data plan subscription, data usage volume, and monthly charges.
- Customer Service Interaction: Number of calls to customer service, which may indicate dissatisfaction.
- Call Activity Metrics: Metrics such as daytime minutes, number of calls, overage fees, and roaming minutes.

## Exploratory Data Analysis (EDA)
In the EDA phase, we conducted an in-depth analysis, including customer segmentation and random under-sampling:
- Customer Segmentation: Grouped customers based on behavioral and demographic attributes to identify patterns associated with churn.
- Random Under-Sampling: Balanced the dataset by reducing instances from the majority class, helping improve model performance on imbalanced data.
- Feature Distribution: Visualized key features like DayMins, MonthlyCharge, and CustServCalls for churned vs. non-churned customers.
- Correlation Check: Analyzed feature correlations to identify significant relationships impacting churn.

## Feature Engineering & Scaling
Feature engineering techniques were applied to prepare the data for modeling, including:
- Encoding categorical variables
- Scaling numerical features
- Creating new features based on domain insights

## Models
The following models were tested:
- **Decision Tree**
- **Random Forest**
- **Gradient Boosting**
- **XGBoost**
- **K-Nearest Neighbors (KNN)**

## Results
The models were evaluated and compared, with **Random Forest** emerging as the top performer based on its ability to distinguish between churn and non-churn customers effectively.

**Summary of Model Performance**:
| Model               | AUC Score |
|---------------------|-----------|
| Decision Tree       | 0.8589    |
| Random Forest       | 0.8818    |
| Gradient Boosting   | 0.8714    |
| XGBoost             | 0.8798    |
| K-Nearest Neighbors | 0.8599    |

## Conclusion
The Random Forest model provided the best performance, making it the most suitable choice for predicting customer churn in this dataset. This model can help businesses identify high-risk customers and take action to retain them, ultimately reducing churn rates.
