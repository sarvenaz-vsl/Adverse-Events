# Predicting Adverse Events

## Project Overview
This project aims to predict adverse events associated with Apixaban, a widely-used anticoagulant, employing machine learning to enhance patient safety in healthcare settings.

## Adverse Events Targeted
- **Cerebrovascular Accident (Stroke)**
- **Thrombosis**
- **Atrial Fibrillation**
- **Cardiac Disorder**

## Dataset
Data from **OpenFDA**, spanning 2014 to 2023, was analyzed to identify trends and patterns in Apixaban-related adverse events.

## Modeling Approach
- **Random Forest Classifier**: Selected for its robustness in handling non-linear data and extracting feature importance.
- **SMOTE**: Employed to address class imbalance in the dataset.
- **Hyperparameter Tuning**: Performed using GridSearchCV to refine model parameters for optimal performance.

## Results
The developed models achieved high accuracy and F1-scores, proving effective for clinical support and decision-making.

## Key Features
Critical predictors identified include **age**, **existing cardiovascular conditions**, and **drug interactions**.

## Tools & Libraries
- **Python**: Core programming language.
- **Pandas**, **Scikit-learn**: Primary libraries for data manipulation and machine learning.
- **SMOTE**: Technique for balancing dataset.
- **Data Cleaning and Feature Engineering**: Essential steps to prepare the dataset for modeling.
