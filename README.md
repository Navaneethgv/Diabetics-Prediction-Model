# Diabetics-Prediction-Model

## Overview
This project aims to predict the likelihood of diabetes in patients using a Random Forest classifier. The model is trained on clinical diagnostic measurements from the `diabetes.csv` dataset. The final accuracy achieved is **79.22%**.

## Features
The dataset includes the following features:
- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skinfold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (kg/m²)
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age in years
- **Outcome**: Target variable (1 = diabetic, 0 = non-diabetic)

## Dataset
- **Source**: [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database) (commonly used for diabetes prediction tasks).
- **Size**: 768 samples with 9 features.
- **Missing Values**: No null values detected.

##Usage
Open the Jupyter notebook Code.ipynb:

bash
Copy
jupyter notebook
Run all cells in the notebook to:

Load and explore the dataset.

Split data into training and testing sets.

Train the Random Forest model.

Evaluate accuracy on the test set.

##Results
Accuracy: 79.22% on the test set.

Example prediction output:

Copy
[0 1 1 1 0 0 1 0 0 1 1 0 0 1 1 0 0 0 0 1 1 0 1 1 1 0 1 0 0 0 0 1 0 0 0 0 0 ...]
