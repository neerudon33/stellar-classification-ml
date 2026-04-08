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
- Confusion matrix = [[ 8 0 0 0 0 0] [ 0 7 0 0 0 0] [ 0 0 6 0 0 0] [ 0 0 0 8 0 0] [ 0 0 0 0 8 0] [ 0 0 0 0 0 11]]
### 4. Interpretation
- **Feature importance analysis to identify dominant physical parameters**

## Results
- Achieved strong classification accuracy on test data
- Feature importance indicates:
- Absolute Magnitude and Stellar Radius as dominant predictors
- Moderate influence from luminosity
- Minimal contribution from derived attributes such as star color
- **The high accuracy suggests that the selected physical parameters provide strong separability of stellar types in this dataset. However, given the limited dataset size and potential correlations among features, further validation on larger and more diverse datasets is necessary to assess generalization performance.**

## Key Insights

- Intrinsic brightness (absolute magnitude) and structural scale (radius) emerge as the dominant factors in stellar classification within the dataset  
- Derived attributes such as star color contribute minimally, indicating redundancy with underlying physical parameters  
- The model captures structured relationships consistent with established stellar classification frameworks

## Future Work

- Apply the model to large-scale astronomical surveys (e.g., Gaia, TESS) for improved generalization  
- Explore advanced models such as gradient boosting and neural networks for capturing complex feature interactions  
- Extend the framework to regression tasks for predicting continuous stellar properties  

## Conclusion

This project demonstrates the application of machine learning to astrophysical classification problems using structured observational data. The model achieves strong predictive performance while providing interpretable insights into the physical parameters governing stellar types.

The results highlight the effectiveness of data-driven approaches in reproducing known astrophysical relationships and underscore the importance of combining predictive modeling with domain-level interpretation.

