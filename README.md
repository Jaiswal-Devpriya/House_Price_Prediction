# House_Price_Prediction
Predicting house prices using feature engineering and Lasso regression (Kaggle competition).

## Approach

- Log1p transformation of target (SalePrice)
- Missing value handling (domain-aware imputation)
- Feature engineering:
  - Total square footage
  - Total bathrooms
  - House age
  - Interaction terms
- Skewness correction on numeric features
- One-hot encoding for categorical variables
- Lasso regression (alpha=0.0005)

## Validation

5-fold cross-validation  
CV RMSE (log scale): ~0.125

## Kaggle Score

Public leaderboard score: 671

## Technologies Used

- Python
- Pandas
- Scikit-learn
- NumPy
