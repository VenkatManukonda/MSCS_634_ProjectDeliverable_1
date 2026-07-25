# MSCS 634 Residency Project

## Authors
Asha Kilaru and Venkatappareddy Monukonda

## Medicare Quarterly Part B Spending by Drug Analysis

This repository presents a comprehensive analysis of the CMS Medicare Quarterly Part B Spending by Drug dataset using a range of data mining and machine learning techniques. The project was completed in multiple phases, with each deliverable building on the previous one to develop a deeper understanding of Medicare spending patterns and drug utilization.

Rather than focusing on a single modeling approach, the project combines data preparation, exploratory analysis, regression, classification, clustering, and association rule mining to examine the dataset from multiple perspectives. Each phase contributes different insights that together provide a more comprehensive understanding of spending behavior.

---

## Repository Structure

```
MSCS_634_Final_Project/
│
├── Dataset/
│   └── cms_healthcare_claims_cleaned.csv
│
├── MSCS_634_ProjectDeliverable_1/
│   ├── ProjectDeliverable1.ipynb
│   └── README.md
│
├── MSCS_634_ProjectDeliverable_2/
│   ├── ProjectDeliverable2.ipynb
│   └── README.md
│
├── MSCS_634_ProjectDeliverable_3/
│   ├── ProjectDeliverable3.ipynb
│   └── README.md
│
├── MSCS_634_ProjectDeliverable_4/
│   ├── Residency_Project_Report.docx
│
└── README.md
```

---

## Project Objectives

The primary objective of this project was to investigate factors associated with Medicare Part B drug spending by applying multiple data mining techniques. Throughout the project, we sought to:

- Prepare and clean the dataset for analysis.
- Explore spending and utilization patterns through exploratory data analysis.
- Develop predictive models using regression and classification.
- Identify natural groupings using clustering.
- Discover meaningful relationships through association rule mining.
- Interpret the results and provide practical recommendations based on the findings.

---

## Project Summary

### Deliverable 1
Focused on data preparation, including cleaning the dataset, handling missing values, performing exploratory data analysis, and creating features for subsequent modeling.

### Deliverable 2
Applied regression techniques to examine relationships between utilization measures and Medicare spending while comparing model performance.

### Deliverable 3
Expanded the analysis by implementing classification models, K-Means clustering, Principal Component Analysis (PCA), and association rule mining to uncover additional patterns within the data.

### Deliverable 4
Consolidated the complete project into a final report, integrated notebook, presentation, and project recommendations while discussing ethical considerations and future improvements.

---

## Technologies Used

- Python
- Jupyter Notebook
- pandas
- NumPy
- scikit-learn
- mlxtend
- Matplotlib
- Seaborn

---

## Dataset

The analysis is based on the CMS Medicare Quarterly Part B Spending by Drug dataset. A cleaned version of the dataset, created during Deliverable 1, is used throughout the project to ensure consistency across all analyses.

---

## Key Findings

- Data preparation and feature engineering improved the quality of the dataset for modeling.
- Regression models provided insight into factors associated with Medicare spending.
- Naive Bayes achieved the strongest overall classification performance based on the F1 score.
- K-Means clustering identified distinct utilization and spending groups within the data.
- Association rule mining revealed strong relationships among beneficiary counts, claim volumes, and spending characteristics.
- Combining multiple analytical techniques produced a broader understanding of Medicare drug utilization than any individual method alone.

---
