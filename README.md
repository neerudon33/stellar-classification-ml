# Machine Learning Classification of Stellar Types

## OVERVIEW

This project implements a supervised machine learning pipeline to classify stars based on their physical and spectral properties. Using parameters such as temperature, luminosity, radius, absolute magnitude, color, and spectral class, a Random Forest classifier is trained to predict stellar type.
The project simulates a data-driven astrophysical classification workflow, where observable quantities are used to infer intrinsic stellar categories.

## OBJECTIVE

Develop a predictive model for stellar classification.
Analyze the relationship between observable parameters and star types.
Interpret model behavior using feature importance analysis.

## Dataset

### The dataset consists of stellar observations with the following features:

- Temperature (K)
- Luminosity (L/Lo)
- Radius (R/Ro)
- Absolute Magnitude (Mv)
- Star Color
- Spectral Class
- Star Type (target variable)

- ## Methodology
### 1. Data Preprocessing
- Handled structured astrophysical data
- Encoded categorical variables (star color, spectral class)
- Separated features and target variable
### 2. Model Development
- Applied Random Forest Classifier
- Trained on 80% of the dataset
- Tested on 20% unseen data
### 3. Evaluation
- Accuracy score = **1.0**
- Confusion matrix
### 4. Interpretation
- **Feature importance analysis to identify dominant physical parameters**
