# MSCS 634 Residency Project

## Medicare Part B Drug Spending Analysis Using Data Mining Techniques

This repository contains our work for the MSCS 634 Residency Project. The project analyzes the CMS Medicare Quarterly Part B Spending by Drug dataset using a combination of supervised and unsupervised learning techniques. Rather than relying on a single analytical approach, the project explores the data through regression, classification, clustering, and association rule mining to better understand spending patterns and utilization behavior.

The project was completed in three deliverables, with each phase building on the work completed in the previous stage.

## Repository Structure

```
MSCS_634_Residency_Project/
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
└── README.md
```

## Deliverables

**Deliverable 1**
- Data cleaning and preprocessing
- Exploratory data analysis
- Feature preparation
- Creation of the cleaned dataset

**Deliverable 2**
- Regression modeling
- Model comparison and evaluation
- Analysis of Medicare spending trends

**Deliverable 3**
- Classification of high-spending records
- K-Means clustering
- Principal Component Analysis (PCA)
- Association Rule Mining using Apriori
- Model evaluation and interpretation

## Tools and Libraries

- Python
- Jupyter Notebook
- pandas
- NumPy
- scikit-learn
- mlxtend
- Matplotlib
- Seaborn

## Dataset

The project uses a cleaned version of the CMS Medicare Quarterly Part B Spending by Drug dataset prepared during Deliverable 1. The same dataset is used throughout all subsequent analyses to maintain consistency across the different modeling techniques.

## Summary

By combining predictive modeling, clustering, and pattern discovery, this project examines Medicare drug spending from multiple perspectives. Each deliverable contributes a different stage of the analysis, providing a broader understanding of utilization patterns and spending behavior than any single technique could offer on its own.
