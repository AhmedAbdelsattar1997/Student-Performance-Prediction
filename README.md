# Student Performance Prediction Using Machine Learning

This project applies machine learning techniques to analyze and predict student academic performance based on demographic, social, and study-related features.

## Overview
The project demonstrates a full data science workflow, including data cleaning, preprocessing, feature encoding, model training, and evaluation. It predicts:
- Math scores
- Reading scores
- Writing scores  
using **Linear Regression**, and classifies overall performance using a **Random Forest Classifier**.

## Dataset
The dataset contains student-related features such as:
- Study hours
- Number of siblings
- Parental education
- Test preparation
- Transport means
- Sports practice
- Family and demographic information

Missing values and categorical data are handled before modeling.

## Data Preprocessing
- Dropping irrelevant columns
- Handling missing values using mean and mode imputation
- Converting categorical features using Label Encoding
- Transforming weekly study hours into numerical values
- Splitting data into training and testing sets

## Models Used
- **Linear Regression** for predicting exam scores
- **Random Forest Classifier** for performance classification

## Evaluation Metrics
- Mean Squared Error (MSE)
- R² Score
- Accuracy Score
- Classification Report (Precision, Recall, F1-score)

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn

Install dependencies:
```bash
pip install pandas numpy scikit-learn
