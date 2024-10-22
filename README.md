# Heart Disease Prediction Using Machine Learning

This project uses machine learning algorithms to predict heart disease. Both **Random Forest Classifier (RFC)** and **Logistic Regression (LR)** models are implemented and compared for their performance in predicting whether a patient has heart disease based on various health metrics.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Models](#models)
- [Technologies Used](#technologies-used)


## Overview
Heart disease is one of the leading causes of death globally, and early prediction is critical to patient outcomes. In this project, we build models to predict the presence of heart disease based on medical attributes such as age, cholesterol levels, and blood pressure.

Two machine learning models are used:
1. **Random Forest Classifier (RFC)**
2. **Logistic Regression (LR)**

The performance of these models is compared based on metrics such as accuracy, precision, and recall.

## Dataset
The dataset contains medical measurements and patient information. It includes the following features:
- **Age**: The patient's age.
- **Sex**: The patient's gender (1 = male, 0 = female).
- **CP (Chest Pain Type)**: The type of chest pain experienced.
- **Trestbps**: Resting blood pressure.
- **Chol (Cholesterol)**: Serum cholesterol levels.
- **FBS**: Fasting blood sugar levels.
- **Restecg**: Resting electrocardiographic results.
- **Thalach**: Maximum heart rate achieved.
- **Exang**: Exercise-induced angina (1 = yes, 0 = no).
- **Oldpeak**: Depression induced by exercise relative to rest.
- **Slope**: Slope of the peak exercise ST segment.
- **Ca**: Number of major vessels colored by fluoroscopy.
- **Thal**: A blood disorder that affects the ability to carry oxygen.

The target variable:
- **Target**: Presence of heart disease (1 = disease, 0 = no disease).

## Models
### 1. **Random Forest Classifier (RFC)**
Random Forest is an ensemble learning method that builds multiple decision trees and merges them to get a more accurate and stable prediction.

### 2. **Logistic Regression (LR)**
Logistic Regression is a statistical model that predicts the probability of a binary outcome (heart disease or no heart disease).

### Comparison of Models
Both models are trained on the dataset, and their performance is evaluated using metrics such as accuracy, precision, recall, and F1-score. Cross-validation is also used to ensure the robustness of the models.

## Technologies Used
- **Python**: Programming language
- **scikit-learn**: For building machine learning models and evaluation
- **pandas**: For data manipulation and analysis
- **NumPy**: For numerical computations
- **Matplotlib & Seaborn**: For data visualization

