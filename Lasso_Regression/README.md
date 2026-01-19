# Lasso-Regression-Baseball-Salary-Prediction
## Project Overview

This project predicts baseball player salaries using Lasso Regression.
The goal is to identify the most important performance and experience factors affecting salary while reducing model complexity through regularization.

## Dataset

Hitters Dataset

322 player records

Performance, experience, and team-related features

Target variable: Salary

## Approach

Data loading and understanding

Handling missing salary values using median imputation

Converting categorical variables into numerical features

Train–test split

Lasso Regression modeling

Hyperparameter tuning using LassoCV

Model evaluation using RMSE and R²

Feature importance analysis

## Results

RMSE ≈ 346

R² ≈ 0.36

## Most important features: Hits, Walks, Home Runs

## Key Insights

Player performance metrics strongly influence salary

Lasso automatically removed less important features

Regularization helped simplify the model

## Tools Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib

## Conclusion

Lasso Regression provided a clear and interpretable approach for predicting baseball player salaries by performing automatic feature selection. While the model achieved moderate accuracy, it effectively demonstrated the importance of regularization in regression problems and provides a strong baseline for further improvements.
