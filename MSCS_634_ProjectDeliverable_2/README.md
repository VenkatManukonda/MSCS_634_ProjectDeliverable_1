# MSCS_634_ProjectDeliverable_2
## Regression Modeling and Performance Evaluation

### Dataset and Modeling Process

This deliverable continues the analysis using the cleaned CMS Medicare Quarterly Part B Spending by Drug dataset prepared in Deliverable 1. To improve prediction performance, I created additional features that describe utilization patterns, including claims per beneficiary, reporting year, reporting quarter, log-transformed claim counts, log-transformed beneficiary counts, and frequency-based features for brand and generic drug names.

After preparing the data, I split it into training and testing sets and applied preprocessing using median imputation, feature scaling, and one-hot encoding. Two regression models were then developed and compared: Linear Regression and Ridge Regression.

### Evaluation Results

Model performance was evaluated using Test R-squared (R²), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and five-fold cross-validation. The notebook also includes actual versus predicted plots, residual analysis, and model comparison charts to visualize prediction performance.

Ridge Regression produced the strongest overall results by achieving the highest R² while generating more stable predictions than the standard Linear Regression model.

### Key Insights

The comparison showed that feature engineering improved the ability of the models to capture Medicare spending patterns. Regularization also proved beneficial because it reduced the effect of correlated predictors and produced more consistent predictions. Although spending remained difficult to predict due to the large variation between drugs, Ridge Regression provided the best balance between prediction accuracy and model stability.

### Challenges

The greatest challenge during modeling was the highly skewed distribution of Medicare spending. A relatively small number of drugs account for exceptionally large expenditures, making prediction more difficult. Rather than removing these observations, I preserved them and relied on preprocessing, feature engineering, and Ridge Regression to improve model stability while maintaining the original characteristics of the data.
