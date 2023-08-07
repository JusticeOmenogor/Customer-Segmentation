# Customer Segmentation (Marketing Department)

This project aims to perform market segmentation  for a bank by trying to divide their customers to at least 3 distinct groups. This will help the marketing team understand their customers spending habits and patterns and this will help team launch a targeted marketing campaign.

The goal for marketing team is to;

Empower business Growth
Educate and communicate value proposition to customers
Drive sales 
Create engagement


Actions
- Performed Exploratory data analysis and some visualisations to look for some trends and patterns amongst the customers and get a feel of their spending habits.
- Found a lot of missing values in 2 columns. I dealt with this by replacing the missing values with the mean of their columns
- Drop columns that are not useful
- Visualise to investigate more patterns and trends (Distplots and correlation matrix)
- Applied K-Means clustering to perform market segmentation dividing the customers into 4 distinct groups
- Applied Principal Component Analysis for dimensionality reduction and performed some visualisations
- Built and trained Auto encoder


Impact

Successfully performed market segmentation dividing the customers into 4 distinct groups

1. Transactors: Those are customers who pay least amount of interest charges and careful with their money, Cluster with lowest balance 104 USD and cash advance 303 USD, Percentage of full payment = 23%
2. Revolvers: who use credit card as a loan (most lucrative sector): highest balance 5000 USD and cash advance ~5000 USD, low purchase frequency, high cash advance frequency (0.5), high cash advance transactions (16) and low percentage of full payment (3%)
3. VIP/Prime: high credit limit $16K and highest percentage of full payment, target for increase credit limit and increase spending habits
4. Low tenure : these are customers with low tenure (7 years), low balance





## Tech Stack
![Logo](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Logo](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Logo](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Logo](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)


