# bank-customer-segmentation-recommendation

**Project Overview**

This project builds a customer segmentation and product recommendation system for a retail bank using real public banking data. Customers are grouped based on demographic, behavioral, and macroeconomic indicators to support personalized product offerings and CRM decision-making.

**Business Objective**

To identify distinct customer segments and recommend appropriate banking products for each group to improve customer engagement, retention, and revenue generation.

**Dataset**

Source: UCI Machine Learning Repository – Bank Marketing Dataset
File: bank-additional-full.csv
Records: 41,188 customers

**Features used:**

Age
Campaign contact behavior
Previous interactions
Interest rate environment (euribor3m)
Macroeconomic indicators
Employment & confidence indexes

**Methodology**

Data cleaning and preprocessing
Feature scaling
PCA for dimensionality reduction
K-Means clustering
Hierarchical clustering for validation
Cluster profiling
Rule-based product recommendation engine

**Product Recommendation Logic**

0:	High-confidence, stable customers	Time Deposit + Investment
1:	Active high-frequency contacts	Credit Card growth
2:	Low-activity dormant customers	Re-activation campaign
3:	Economically stressed customers	Controlled Personal Loan

**Results**

The model successfully segments customers into four meaningful clusters and assigns tailored banking products, forming a complete CRM decision support system.
