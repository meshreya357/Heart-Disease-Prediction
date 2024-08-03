# Heart-Disease-Prediction
The objective of this project was to develop a machine learning model to predict the likelihood of heart disease in individuals based on various health parameters using logistic regression.

# Heart Disease Prediction Using Logistic Regression

## Project Overview

This project aims to predict the likelihood of heart disease in individuals using a logistic regression model. The dataset contains various health parameters such as age, sex, chest pain type, resting blood pressure, cholesterol levels, and more.

## Dataset

The dataset contains the following features:
- **age**: Age of the patient
- **sex**: Gender of the patient
- **cp**: Chest pain type (4 values)
- **trestbps**: Resting blood pressure
- **chol**: Serum cholesterol in mg/dl
- **fbs**: Fasting blood sugar > 120 mg/dl
- **restecg**: Resting electrocardiographic results (values 0, 1, 2)
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise-induced angina
- **oldpeak**: ST depression induced by exercise relative to rest
- **slope**: The slope of the peak exercise ST segment
- **ca**: Number of major vessels (0-3) colored by fluoroscopy
- **thal**: Thalium stress test result
- **target**: Diagnosis of heart disease (1 = disease, 0 = no disease)

## Methodology

1. **Data Preprocessing**: Cleaning the data, handling missing values, and encoding categorical variables.
2. **Model Training**: Using logistic regression to train the model on the training set.
3. **Model Evaluation**: Evaluating the model's performance on the testing set.

## Results

- **Training Accuracy**: 86.79%
- **Testing Accuracy**: 86.81%

## Key Observations

1. **Chest Pain (cp)**: Higher likelihood of heart disease in individuals with cp types 1, 2, and 3.
2. **Resting EKG (restecg)**: Higher likelihood of heart disease in individuals with abnormal heart rhythms (restecg = 1).
3. **Exercise-induced Angina (exang)**: Higher likelihood of heart disease in individuals without exercise-induced angina (exang = 0).
4. **Slope of ST Segment (slope)**: Higher likelihood of heart disease in individuals with a downsloping ST segment (slope = 2).
5. **Number of Major Vessels (ca)**: Lower likelihood of heart disease with more major vessels stained by fluoroscopy.
6. **Thalium Stress Test (thal)**: Higher likelihood of heart disease in individuals with a corrected defect (thal = 2).

## How to Run
1. Install the required libraries
2. Open and run the code in Jupyter notebook
