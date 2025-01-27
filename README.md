**eCommerce Transactions Analysis and Modeling**

Overview

This project involves analyzing eCommerce transaction data to extract insights, build predictive models, and segment customers for better business strategy development. The dataset contains customer profiles, product details, and transaction records, and the tasks focus on data exploration, similarity modeling, and clustering.

Key Objectives

Exploratory Data Analysis (EDA):

Perform data analysis to uncover patterns and trends in customer behavior, product preferences, and transaction history.
Provide actionable business insights.

Lookalike Model:

Develop a model to recommend 3 similar customers based on profile and transaction history.
Calculate similarity scores for recommendations.

Customer Segmentation:

Perform clustering on customers using profile and transaction data.
Evaluate the clusters using the Davies-Bouldin (DB) Index and visualize the results.

Dataset

The dataset consists of three files:

Customers.csv:
Customer profiles including CustomerID, Region, and SignupDate.

Products.csv:
Product details including ProductID, Category, and Price.

Transactions.csv:
Transaction data including TransactionID, TotalValue, and Quantity.

Tasks and Deliverables

Task 1: Exploratory Data Analysis (EDA)

Conducted EDA to summarize key metrics and generate 5 actionable insights.


Task 2: Lookalike Model

Built a model to recommend similar customers using profile and transaction data.
Used cosine similarity to rank recommendations with similarity scores.

Task 3: Customer Segmentation

Performed clustering using K-Means and evaluated clusters with the Davies-Bouldin Index.
Visualized clusters using PCA for dimensionality reduction.

Tools and Libraries

Programming Language: Python
Libraries:
Data Manipulation: pandas, numpy
Visualization: matplotlib, seaborn
Machine Learning: sklearn
Dimensionality Reduction: PCA
