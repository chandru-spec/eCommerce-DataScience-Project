# eCommerce-DataScience-Project
This repository contains the completed tasks for an eCommerce Transactions Dataset Analysis project. The project focuses on exploratory data analysis, building a lookalike model, and customer segmentation.

Project Overview
This project aims to analyze eCommerce transaction data and deliver actionable insights to enhance business strategies. Key deliverables include:

Exploratory Data Analysis (EDA): Identifying trends and insights in the dataset.
Lookalike Model: Recommending similar customers based on profile and transaction history.
Customer Segmentation: Grouping customers into meaningful clusters for targeted marketing.
Dataset
The project uses three datasets:

Customers.csv: Customer profiles, including ID, region, and signup date.
Products.csv: Product details, including ID, category, and price.
Transactions.csv: Transaction records, including product purchased, quantity, and total value.
Deliverables
EDA and Insights:

Jupyter Notebook: Chandru_J_EDA.ipynb
PDF Report: Chandru_J_EDA.pdf
Lookalike Model:

Jupyter Notebook: Chandru_J_Lookalike.ipynb
CSV File: Chandru_J_Lookalike.csv
Customer Segmentation:

Jupyter Notebook: Chandru_J_Clustering.ipynb
PDF Report: Chandru_J_Clustering.pdf
Highlights
1. Exploratory Data Analysis
Insights on customer behavior, product popularity, and transaction trends.
Visualizations for better understanding of data patterns.
2. Lookalike Model
Recommends three similar customers for each user based on their profile and transaction history.
Similarity scores provided for recommendations.
3. Customer Segmentation
Methodology:

Merged datasets to create features like total expenditure, average transaction value, and recency.
Used K-Means clustering to group customers into 4 segments.
Key Metrics:

Davies-Bouldin Index: 0.85
Silhouette Score: 0.36
Clusters Identified:

High-Value Customers: Loyal and high spenders.
Occasional Shoppers: Moderate spenders, shop during promotions.
New Customers: Early-stage users with low engagement.
Inactive Customers: Rare shoppers requiring reactivation strategies.
Visualization Highlights:

Cluster distributions using pie charts.
Boxplots for feature comparison across clusters.

Tools and Libraries
Data Analysis: Pandas, NumPy
Visualization: Matplotlib, Seaborn
Machine Learning: Scikit-learn

Recommendations
Personalize marketing strategies for high-value customers to boost loyalty.
Engage occasional shoppers with promotions and reminders.
Improve onboarding for new customers through targeted offers.
Reactivate inactive customers using "We Miss You" campaigns.
