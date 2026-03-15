# Health Risk Classification Using Physiological Data

This project focuses on predicting individual health risk levels using tabular physiological and behavioural data.

The goal is to build a binary classification model that estimates whether a person is at risk based on common medical indicators such as BMI, blood pressure, and glycemic status.

## Dataset

The dataset contains **61,983 observations** with multiple physiological indicators related to health conditions.

Key variables include:

- BMI (Body Mass Index)
- SBP_mean (Mean systolic blood pressure)
- DBP_mean (Mean diastolic blood pressure)
- Pulse_Pressure
- Glycemic_Risk

After preprocessing and feature engineering, the dataset contains **17 input features** used for model training.

The final label used for prediction is:

**Health_Risk**  
Binary variable representing whether the individual is at risk.

## Feature Engineering

Additional features were created to improve model performance, including:

- **Pulse Pressure**  
  Calculated as the difference between systolic and diastolic blood pressure.

- **Glycemic Risk Indicator**  
  A binary variable indicating elevated blood glucose risk.

These features were added based on findings from medical literature linking them to cardiovascular and metabolic risk.

## Methods

To evaluate predictive performance, **nine machine learning models** were trained and compared for this binary classification task.

The models include variants of:

- Gaussian Naïve Bayes
- Support Vector Machine
- Random Forest
- Neural Network models

## Data Processing

Data preprocessing steps included:

- Handling missing values
- Feature normalization
- Feature engineering
- Addressing class imbalance during model training

## Goal

The objective of this project is to compare multiple classification algorithms and identify the model that best predicts health risk based on physiological indicators.

This work demonstrates how machine learning can assist health risk prediction using tabular medical data.
