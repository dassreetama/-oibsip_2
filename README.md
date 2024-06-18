Marketing Analytics: Customer Segmentation
Table of Contents
Introduction
Data
Data Preparation and Cleaning
Data Exploration
Feature Engineering
K-Means Clustering
Exploration of Clusters
Results
Recommendations
Introduction
Customer segmentation is a powerful marketing technique used to divide a customer base into distinct groups based on shared characteristics, behaviors, or demographics. The main goal is to understand and serve customers better with personalized and targeted strategies. This project leverages exploratory data analysis (EDA) and K-means clustering to identify customer segments based on their purchasing behavior.

Data
The dataset consists of 2,205 observations and 39 columns. It includes various features such as customer acceptance of marketing campaigns, complaints, income, spending on different products, and more. The dataset was reviewed to ensure it matched the actual columns and their descriptions.

Data Preparation and Cleaning
This section involves:

Reviewing data columns and comparing them to the dataset description.
Checking for missing values and ensuring there are none.
Verifying column types and ensuring they are appropriate.
Assessing unique values in each column and removing columns with the same values.
Data Exploration
In this section:

Box plots for the total amount spent on all products (MntTotal) and income.
Histograms for age distribution.
Correlation matrix to understand relationships between features.
Point-Biserial correlations for binary variables.
Feature Engineering
New features were created to enhance the dataset:

Marital: Combined marital status into a single column.
In_relationship: Indicates if a customer is in a relationship (married or together).
K-Means Clustering
Steps involved in clustering:

Standardizing data to ensure features have a similar scale.
Applying Principal Component Analysis (PCA) for dimensionality reduction.
Using the Elbow Method and Silhouette Score to determine the optimal number of clusters.
Implementing K-means clustering with the optimal number of clusters (k=4).
Exploration of Clusters
Analysis of clusters includes:

Visualizing clusters using scatter plots.
Examining mean consumption of different product types by cluster.
Analyzing cluster sizes.
Investigating income distribution and relationship status by cluster.
Results
The clustering analysis identified four distinct customer segments:

High value customers in relationship: High income, in a relationship, represent 26% of the customer base.
Low value single customers: Low income, single, represent 21% of the customer base.
High value single customers: High income, single, represent 15% of the customer base.
Low value customers in relationship: Low income, in a relationship, represent 39% of the customer base.
Recommendations
Tailored marketing strategies for each cluster:

Cluster 0: Focus on high-quality wines and family-oriented promo images.
Cluster 1: Use discounts, coupons, and loyalty programs.
Cluster 2: Promote wines and fruits with friend-oriented and party-themed promo images.
Cluster 3: Family offers and discounts to encourage more purchases.
Opportunities for Further Analysis
Explore the influence of children and education on purchasing behavior.
Analyze frequent buyers and sales channels.
Assess responses to marketing campaigns.
Consider adding gender data to the dataset.
Test different clustering algorithms for better segmentation.
Conclusion
This project demonstrates how customer segmentation can provide valuable insights for personalized marketing strategies. By understanding distinct customer groups, businesses can tailor their marketing efforts to meet specific needs and preferences, ultimately enhancing customer satisfaction and loyalty.

