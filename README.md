# Retail Revenue Prediction

## Overview
This project evaluates whether customer demographic and behavioral engagement data can accurately predict retail order value.

Using a dataset of 10,000 retail observations, multiple modeling approaches were tested to determine predictive performance and identify the most influential variables driving revenue.

---

## Business Question
Can retail revenue be accurately predicted using demographic and session-level behavioral data?

---

## Models Implemented
- Multiple Linear Regression
- Random Forest Regressor

An 80/20 train-test split was used to evaluate model performance on unseen data.

---

## Results

| Model | R² | RMSE | MAE |
|-------|------|------|------|
| Linear Regression | 0.046 | 22.80 | 18.61 |
| Random Forest | -0.078 | 24.24 | 19.66 |

Neither model achieved meaningful predictive accuracy.

---

## Key Findings
- Prior spending history and income were the most influential variables.
- Engagement metrics (pages viewed, cart additions) were less predictive than expected.
- Even nonlinear models failed to substantially improve performance.

These results suggest that commonly available demographic and session-level data are insufficient for forecasting retail revenue.

---

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib

---

## Future Improvements
- Incorporate product-level and pricing variables
- Apply gradient boosting models
- Explore feature engineering techniques
