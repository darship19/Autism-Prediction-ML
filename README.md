# Autism Prediction

## Table of Contents
1. [Project Overview](#project-overview)
2. [Objective](#objective)
3. [Dataset](#dataset)
4. [Methodology](#methodology)
   - [Problem Definition](#problem-definition)
   - [Data Preprocessing](#data-preprocessing)
   - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
   - [Model Selection](#model-selection)
   - [Model Training](#model-training)
   - [Model Evaluation](#model-evaluation)
5. [Results](#results)
6. [Requirements](#requirements)
7. [How to Run the Project](#how-to-run-the-project)
8. [Contributors](#contributors)

## Project Overview
This project uses machine learning to predict the likelihood of an autism diagnosis based on survey data from over 700 individuals. By improving autism screening, the model helps healthcare professionals prioritize resources for early diagnosis and intervention.

## Objective
The aim of the project is to develop a machine learning model that can predict the likelihood of autism in individuals based on their survey responses, thus enhancing early diagnosis.

## Dataset
- The dataset contains survey responses from more than 700 individuals, including labels that indicate whether the individual received an autism diagnosis.
- Features include demographic, behavioral, and clinical data, such as scores from questions on social and behavioral abilities.

**Dataset Link:** [https://drive.google.com/drive/folders/1V9SDkYTRDClSIeiYg0NpNOE0TSCcUvHO?usp=sharing]

## Methodology

### Problem Definition
- Develop a machine learning model to predict the likelihood of an autism diagnosis based on survey responses.

### Data Preprocessing
- **Data Cleaning:**
  - Handled missing values using imputation or removal methods.
  - Removed duplicate data.
  
- **Feature Encoding:**
  - Categorical features like gender, ethnicity, and jaundice were encoded into numerical values using techniques like one-hot encoding or label encoding.
  
- **Feature Scaling:**
  - Normalized/standardized numerical features (e.g., A1_Score to A10_Score, age, result) for consistency in model training.

- **Data Splitting:**
  - The dataset was split into training and testing sets using an 80/20 ratio.

- **Feature Selection:**
  - Important features were selected using a correlation matrix and other statistical techniques.

### Exploratory Data Analysis (EDA)
- Visualized data distributions and relationships between features and target variables using histograms, box plots, and scatter plots.
- Performed statistical analysis to understand correlations between features and the autism diagnosis.

### Model Selection
Evaluated the following machine learning algorithms:
- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machines (SVM)
- XGBoost


### Model Evaluation
Evaluated the performance of models using:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC curve for binary classification


## Requirements
- Python 3.x
- Libraries: 
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - xgboost
  
[
