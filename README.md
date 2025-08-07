# Marketing-Analytics-Customer-Segmentation
Customer Segmentation using EDA and clustering techniques to identify distinct customer groups for targeted marketing strategies.
 Table of Contents
 Project Objective
 Dataset Overview
 Data Preprocessing
 Exploratory Data Analysis (EDA)
 Customer Segmentation (KMeans Clustering)
 Results & Insights

📁 Files Included

 Conclusion

 Contact

Dataset Overview
Source: Kaggle / Marketing Dataset

Content: Includes customer demographic and behavioral features such as:

Coloumns:- ['Income', 'Kidhome', 'Teenhome', 'Recency', 'MntWines', 'MntFruits',
       'MntMeatProducts', 'MntFishProducts', 'MntSweetProducts',
       'MntGoldProds', 'NumDealsPurchases', 'NumWebPurchases',
       'NumCatalogPurchases', 'NumStorePurchases', 'NumWebVisitsMonth',
       'AcceptedCmp3', 'AcceptedCmp4', 'AcceptedCmp5', 'AcceptedCmp1',
       'AcceptedCmp2', 'Complain', 'Z_CostContact', 'Z_Revenue', 'Response',
       'Age', 'Customer_Days', 'marital_Divorced', 'marital_Married',
       'marital_Single', 'marital_Together', 'marital_Widow',
       'education_2n Cycle', 'education_Basic', 'education_Graduation',
       'education_Master', 'education_PhD', 'MntTotal', 'MntRegularProds',
       'AcceptedCmpOverall']


Data Preprocessing:-

Removed missing values and duplicates
Standardized numerical features
Categorical encoding (if required)
Scaled data for clustering
Exploratory Data Analysis (EDA)

Exploratory analysis to identify patterns and distributions:

Age distribution of customers
Relationship between Income and Spending Score
Gender-wise spending behavior
Outlier detection and treatment


Results & Insights

Segmented customers into 4–5 clusters
Each segment represents a different marketing group (e.g. high spenders, budget customers, etc.)
Clear distinction in income and spending behavior observed across clusters

📁 Files Included
Marketing_Analytics_Customer_Segmentation.ipynb – Complete code notebook
ifood_df.csv – Dataset
README.md – Project description


Identify high-value customers

Reduce churn by understanding low-spending segments
