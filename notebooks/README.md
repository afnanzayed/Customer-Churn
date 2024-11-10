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
The goal of this project is to predict customer churn using various machine learning models. By analyzing customer demographics, account details, and engagement metrics, we aim to identify the best-performing model to help businesses improve customer retention.

## Dataset
The dataset includes demographic information, account details, and engagement data for each customer, with a target variable indicating churn.

**Key Features**:
- Demographic data (e.g., age, gender)
- Account information (e.g., tenure, subscription type)
- Engagement metrics (e.g., number of logins, usage patterns)

## Exploratory Data Analysis (EDA)
The EDA phase visualizes and examines relationships between features and their correlation with churn. Key analyses include:
- Distribution of churn by demographic groups
- Correlation between features
- Visualizations to understand feature distributions and potential outliers

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
