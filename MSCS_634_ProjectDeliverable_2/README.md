# MSCS 634 Project Deliverable 2
## Regression Modeling and Performance Evaluation

### Dataset Summary

This deliverable continues the analysis using the cleaned CMS Medicare Part B Spending by Drug dataset prepared in Deliverable 1. Additional engineered features were created to improve predictive performance while maintaining the same cleaned dataset throughout the project.

### Modeling Process

The following steps were completed:

- Created additional engineered features including reporting year, reporting quarter, claims per beneficiary, log-transformed claim counts, log-transformed beneficiary counts, and frequency-based drug features.
- Split the dataset into training and testing subsets.
- Applied preprocessing using median imputation, standardization, and one-hot encoding.
- Built two regression models:
  - Linear Regression
  - Ridge Regression
- Evaluated both models using Test R², Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and five-fold cross-validation.

### Results

Ridge Regression achieved the strongest overall performance among the evaluated models. Regularization reduced the impact of correlated predictors and produced more stable predictions than standard Linear Regression.

The notebook includes:

- Actual versus predicted scatter plots
- Model comparison charts
- Residual analysis
- Cross-validation results

### Key Insights

Feature engineering improved the representation of Medicare utilization patterns and contributed to better predictive performance. Although healthcare spending remains difficult to predict because of its highly skewed distribution, Ridge Regression provided the best balance between prediction accuracy and model stability.

### Challenges

One of the main challenges was the extreme variation in Medicare drug spending, which produced several very large observations. Regularization and feature engineering helped reduce instability during model training while preserving the original characteristics of the dataset.
