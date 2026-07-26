# MSCS_634_ProjectDeliverable_3


### Project Overview

This project analyzes the CMS Medicare Quarterly Part B Drug Spending dataset using several data mining and machine learning techniques. The objective was to better understand Medicare drug utilization and spending patterns while applying the concepts covered throughout the course. The project followed a complete workflow beginning with data preparation and ending with predictive modeling, pattern discovery, and interpretation of the results.

---

## Dataset

The analysis used the CMS Medicare Quarterly Part B Drug Spending dataset, which contains information about Medicare beneficiaries, claim volume, total drug spending, average spending per beneficiary, and average spending per claim. This dataset was selected because it provides both numerical and categorical variables that support regression, classification, clustering, and association rule mining. It also represents a real healthcare problem where data-driven analysis can provide meaningful insights into spending patterns.

---

## Project Summary

The project began by cleaning the dataset, handling missing values, verifying duplicate records, and exploring the data through visualizations. Exploratory analysis helped identify spending distributions, relationships between variables, and potential outliers that influenced later modeling.

Feature engineering was then performed to create additional variables, including reporting year, reporting quarter, and claims per beneficiary. These features were used to improve the predictive models developed during the project.

For regression, Linear Regression and Ridge Regression models were compared to predict Medicare spending. Ridge Regression produced the most consistent overall performance after evaluating R-squared, RMSE, MSE, and cross-validation results.

The classification phase focused on identifying high-spending drugs. Multiple classification algorithms were evaluated, followed by hyperparameter tuning of the Decision Tree model. Model performance was assessed using Accuracy, Precision, Recall, F1 Score, confusion matrices, and ROC curves.

K-Means clustering was used to group drugs with similar utilization characteristics, while the Apriori algorithm identified association rules describing relationships among spending, claims, and beneficiary counts.

---

## Key Findings

The analysis showed that Medicare spending is closely associated with beneficiary counts and claim volume. Ridge Regression provided the most stable regression performance for predicting spending, while Naive Bayes achieved the strongest balance between precision and recall during classification. The clustering analysis identified meaningful utilization groups, and association rule mining revealed strong relationships among high spending, high claims, and high beneficiary counts.

---

## Conclusion

This project combined multiple analytical techniques to examine Medicare Part B drug spending from different perspectives. Each method contributed unique insights, and together they provided a better understanding of healthcare utilization patterns. The project also demonstrated how combining predictive modeling with pattern discovery can support more informed, data-driven decision making.
