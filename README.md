Customer Segmentation Analysis in Python

Dataset Overview:
The repository contains an analysis of customer segmentation based on a dataset with 2240 rows and 29 columns. The dataset encompasses various aspects of customer information, product preferences, purchasing behavior, and responses to promotions.

Dataset Subsets:

Customer Information:

ID, Year of Birth, Education, Marital Status, Income, Number of Children at Home, Number of Teenagers at Home, Date of Customer Registration, Recency of Purchase
Product Preferences:

Wine Purchases, Fruit Purchases, Meat Product Purchases, Fish Product Purchases, Sweet Product Purchases, Gold Product Purchases
Purchase Locations:

Number of Web Purchases, Number of Catalog Purchases, Number of Store Purchases, Number of Web Visits per Month
Response to Promotions:

Number of Deals Purchased, Responses to Various Marketing Campaigns (Cmp1, Cmp2, Cmp3, Cmp4, Cmp5)
Analysis Approach:

Dimensionality Reduction:
The analysis commenced with dimensionality reduction using Principal Component Analysis (PCA). This technique was employed to minimize redundant features and enhance interpretability while minimizing information loss.

Clustering:
Clustering was carried out utilizing Agglomerative Clustering, a hierarchical method that involves merging examples until the desired number of clusters is achieved.

Steps Involved in Clustering:

Elbow Method: Determined the optimal number of clusters to be formed (4 clusters identified).
Clustering: Conducted clustering via Agglomerative Clustering.
Evaluation of the Model:
Since this is an unsupervised clustering task, traditional evaluation metrics are not applicable. Instead, the clusters' patterns were examined to understand customer segmentation better.

Key Insights:

The "Income vs Spending" plot revealed distinct cluster patterns:

Group 0: High spending & above-average income
Group 1: Low spending & low income
Group 2: High spending & high income
Group 3: Low spending & below-average income
Cluster profiling was performed to identify star customers and those requiring more attention from the marketing team.
