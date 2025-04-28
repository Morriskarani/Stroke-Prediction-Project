Project Overview
This project uses machine learning to predict whether a person is at risk of having a stroke based on various health factors. The model takes into account demographic information, lifestyle factors, and medical history to predict stroke risk.

Key Features:
Data Source: The dataset used in this project is from [Kenya Healthcare Stroke Data].

Tools Used:

Python

Scikit-learn

Pandas

Matplotlib

Jupyter Notebook

Problem Statement
Stroke prediction can significantly aid healthcare professionals in early diagnosis and preventive measures. By leveraging machine learning techniques, this project aims to predict the likelihood of a person experiencing a stroke based on their health-related data.

Data Overview
The dataset consists of several features, such as:

age: The age of the person.

gender: The gender of the person.

hypertension: Whether the person has hypertension (1 for yes, 0 for no).

heart_disease: Whether the person has heart disease (1 for yes, 0 for no).

smoking_status: The smoking status of the person.

bmi: The body mass index.

avg_glucose_level: Average glucose levels.

The target variable is stroke, where:

1 indicates the person had a stroke.

0 indicates the person did not have a stroke.

Methodology
Data Preprocessing:

Handle missing values.

Label encode categorical columns.

Scale the features for model training.

Model:

We used a Random Forest Classifier to predict stroke risk based on the input features.

The model was evaluated using accuracy and confusion matrix.

Prediction:

The model predicts whether a person is likely to have a stroke based on input health data.
