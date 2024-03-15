# **Customer Segmentation Analysis**

## **Dataset Overview:**
The repository contains an analysis of customer segmentation based on a dataset with 2240 rows and 29 columns. The dataset encompasses various aspects of customer information, product preferences, purchasing behavior, and responses to promotions.

### **Dataset Subsets:**

1. **Customer Information**: 
   - ID, Year of Birth, Education, Marital Status, Income, Number of Children at Home, Number of Teenagers at Home, Date of Customer Registration, Recency of Purchase

2. **Product Preferences**:
   - Wine Purchases, Fruit Purchases, Meat Product Purchases, Fish Product Purchases, Sweet Product Purchases, Gold Product Purchases

3. **Purchase Locations**:
   - Number of Web Purchases, Number of Catalog Purchases, Number of Store Purchases, Number of Web Visits per Month

4. **Response to Promotions**:
   - Number of Deals Purchased, Responses to Various Marketing Campaigns (Cmp1, Cmp2, Cmp3, Cmp4, Cmp5)

## **Analysis Approach:**

**Dimensionality Reduction:**
The analysis commenced with dimensionality reduction using Principal Component Analysis (PCA). This technique was employed to minimize redundant features and enhance interpretability while minimizing information loss.

**Clustering:**
Clustering was carried out utilizing Agglomerative Clustering, a hierarchical method that involves merging examples until the desired number of clusters is achieved.

**Steps Involved in Clustering:**

1. **Elbow Method:** Determined the optimal number of clusters to be formed (4 clusters identified).
2. **Clustering:** Conducted clustering via Agglomerative Clustering.

**Evaluation of the Model:**
Since this is an unsupervised clustering task, traditional evaluation metrics are not applicable. Instead, the clusters' patterns were examined to understand customer segmentation better.

## **Key Insights:**

**Group 0:**
- Middle-aged individuals with no young adults
- Typically have 1 or 2 children
- All are either married or living together
- All are parents 

**Group 1:**
- Includes young adults (mid to late 20’s) through individuals in their 80’s
- Have either 0 or 1 child
- Can either be parents or not
- Mostly do not have teenagers; have younger kids
- Belong to the low-income group

**Group 2:**
- People ranging from their 30’s through their 80’s
- Are definitely not parents
- Belong to the high-income group
- Belong to the high-spending group

**Group 3:**
- Have children (either 1, 2, or 3)
- Mostly have teenagers and rarely younger kids
- Include older individuals - late 30’s through their 80’s
- Belong to the low-income group

Cluster profiling was performed to identify star customers and those requiring more attention from the marketing team.
Check the plots below for understanding the profiling into groups

## **Profiling**

- ![Teenhome_plot](https://github.com/makoli20/customer_segmentation/assets/128938502/107b0b8d-745d-424f-bcc2-8eab4a1f6856)
-![Kidhome_plot](https://github.com/makoli20/customer_segmentation/assets/128938502/dd138fd4-304b-4249-b17c-efa97d7acf0a)

- ![Living_With_plot](https://github.com/makoli20/customer_segmentation/assets/128938502/125c1fb2-82cd-4ca0-8645-2d442072980e)
- ![Is_Parent_plot](https://github.com/makoli20/customer_segmentation/assets/128938502/93350479-d0c9-492f-a497-b4f616168e6a)
- ![Family_Size_plot](https://github.com/makoli20/customer_segmentation/assets/128938502/633a7019-9ea1-4025-a1d9-39090641c894)
- ![Education_plot](https://github.com/makoli20/customer_segmentation/assets/128938502/ad0d8cb3-eed9-47f9-9686-e9a4f883d2ad)
- ![customer_days_plot](https://github.com/makoli20/customer_segmentation/assets/128938502/ce79d41b-80fe-46ab-8fc5-a8e8ec5fd27a)
- ![Children_plot](https://github.com/makoli20/customer_segmentation/assets/128938502/3ff06eeb-02ee-42ca-8845-8d10fc7243d8)
- ![Age_plot](https://github.com/makoli20/customer_segmentation/assets/128938502/40251e4d-3892-4c29-b663-081ad991b964)

  








