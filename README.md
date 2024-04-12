# Flight Fare Price Prediction Project

This repository contains code for a machine learning project aimed at predicting flight fare prices. The dataset used in this project consists of 11 columns and 10683 rows.

## Model Selection

Choosing the appropriate machine learning algorithm is crucial for achieving accurate predictions. For this flight fare prediction task, we experimented with several algorithms:

- **XGBoost**
- **Random Forest**
- **Linear Regression**
- **KNN**
- **Decision Tree**
- **Gradient Boosting**

## Cross-Validation

Cross-validation is essential for evaluating the performance of our models and ensuring they generalize well to unseen data. In this project, we employed k-fold cross-validation to assess model performance.

## Hyperparameter Tuning

Hyperparameter tuning is vital for optimizing model parameters to achieve the best performance. We utilized techniques such as grid search and random search to fine-tune the parameters of our models.

## Ensemble Techniques

Ensemble methods, such as stacking or blending multiple models, were explored to enhance predictive accuracy. We experimented with combinations of XGBoost, Random Forest, and Gradient Boost models.

## Feature Engineering for Categorical Data

Categorical variables, such as airline names, departure/arrival locations, and class types, were preprocessed using various techniques, including one-hot encoding, label encoding, and target encoding, to convert them into a suitable format for modeling.

## Challenges Faced

### Data Quality and Preprocessing

Cleaning and preprocessing the dataset posed challenges due to inaccurate or incomplete data. We addressed issues such as handling missing values, outliers, and ensuring consistency in data formats.

### Feature Engineering

Creating meaningful features from raw data required careful consideration and experimentation. We employed feature selection and extraction techniques to improve model performance.

### Categorical Variables

Handling categorical variables proved to be challenging. We utilized encoding techniques and feature engineering to transform categorical variables into a format suitable for machine learning models.

## Conclusion

Our XGBoost model achieved an impressive 84% R2 score, outperforming other models we experimented with. It provides valuable insights into the relationship between features and the target variable, making it a promising solution for flight fare price prediction. However, it's essential to use this model responsibly and consider its interpretability and practicality in real-world applications.
