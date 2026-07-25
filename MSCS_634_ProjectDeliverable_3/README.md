# MSCS_634_ProjectDeliverable_3

## Purpose

The purpose of this deliverable was to explore the CMS Medicare Quarterly Part B Spending by Drug dataset using multiple data mining techniques rather than relying on a single predictive model. We applied classification, clustering, and association rule mining to understand the data from different perspectives. This approach allowed us to identify high-spending drugs, discover natural groups with similar utilization patterns, and uncover relationships among spending and beneficiary characteristics.

## What We Did

We began by loading the cleaned dataset from Deliverable 1 and creating a binary target variable that identified high-spending records based on the 75th percentile of total Medicare spending. Additional features, including the reporting year, quarter, and claims per beneficiary, were created to improve the predictive models while avoiding target leakage.

For the classification task, we compared four machine learning algorithms: Decision Tree, K-Nearest Neighbors, Naive Bayes, and Support Vector Machine. Each model was trained using the same preprocessing pipeline that handled missing values, standardized numerical features, and encoded categorical variables. Model performance was evaluated using accuracy, precision, recall, and F1 score before selecting the best-performing classifier.

The selected model was then examined using a confusion matrix and ROC curve to understand better its ability to distinguish between regular- and high-spending records.

For unsupervised learning, we applied K-Means clustering using spending and utilization variables. Cluster quality was evaluated with the silhouette score, and Principal Component Analysis (PCA) was used to visualize the resulting clusters in two dimensions.

Finally, association rule mining was performed using the Apriori algorithm after transforming selected numerical variables into categorical indicators. Frequent itemsets and association rules were analyzed using support, confidence, and lift to identify meaningful relationships within the Medicare spending data.

## Key Results

Among the classification models, Naive Bayes achieved the highest F1 score and was selected as the final classifier. Although its overall accuracy was moderate, it was the most effective model for identifying high-spending records.

K-Means clustering produced three distinct groups with a silhouette score of approximately 0.663, indicating reasonably well-separated clusters. Most observations belonged to one large cluster, while two much smaller clusters represented drugs with noticeably different spending and utilization behavior.

Association rule mining identified several strong relationships among beneficiaries, claims, and spending measures. The highest lift values showed that drugs with a large number of beneficiaries were also likely to generate a high number of claims and higher average spending per beneficiary.

## What We Learned

This deliverable demonstrated that different data mining techniques provide complementary insights when applied to the same dataset. Classification helped identify records associated with high Medicare spending, clustering revealed hidden utilization patterns, and association rule mining highlighted relationships that were not immediately visible through predictive modeling alone. Combining these techniques produced a more complete understanding of Medicare drug utilization and spending behavior than any individual method could provide by itself.
