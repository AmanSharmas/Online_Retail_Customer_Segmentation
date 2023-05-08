# Online_Retail_Customer_Segmentation

## Problem Statement:
In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers. 

## Data Description:
A transnational data set with transactions occurring between 1st December 2010 and 9th December 2011 for a UK-based online retailer. The company mainly sells unique all-occasion gifts. and Many customers of the company are wholesalers.

## Attribute Information :

**InvoiceNo**: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.

**StockCode**: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.

**Description**: Product (item) name. Nominal.

**Quantity**: The quantities of each product (item) per transaction. Numeric.

**InvoiceDate**: Invice Date and time. Numeric, the day and time when each transaction was generated.

**UnitPrice**: Unit price. Numeric, Product price per unit in sterling.

**CustomerID**: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.

**Country**: Country name. Nominal, the name of the country where each customer resides.

# Project Summary :

This project is about customer segmentation for a UK-based online retail business that specializes in unique all-occasion gifts. The main steps and objectives of the project are:

* Using a transaction data set that contains customer ID, country, StockCode, description, quantity, unit price, invoice number, and invoice date.

* Applying RFM analysis, a technique that segments customers based on three factors: recency (how recently they purchased), frequency (how often they purchased), and monetary value (how much they spent).

* Identifying different customer segments based on their RFM values and their purchasing behavior and characteristics.

* Using various clustering models in Python, such as k-means, hierarchical clustering (Agglomerative), DBSCAN, and GMM, to group the customers into clusters based on their RFM values.Comparing the performance of these models using metrics such as silhouette score.

* Providing insights into the characteristics and preferences of each customer segment and suggesting marketing and sales strategies to target them effectively.

* Aiming to help the business improve customer satisfaction and increase revenue by offering personalized and relevant products and services to each customer segment.


## Libraries used in EDA & Machine Learning:
1. Pandas
2. Numpy
3. Matplotib
4. Seaborn
5. Plotly
6. Sklearn
7. Scipy


## Graphs used for representation:
1. Bar plot
2. Pie plot
3. Correlation Plot
6. Heatmap
7. Pair plot


## ML Models used for training & testing:
1. K means Clustering	
2. Hierarchial Clustering		
3. DBSCAN	
4. Gaussian Mixture Model

## Steps involved in building a ML Model:

 Step 1: Data gathering and Understanding

 Step 2: Data preparation

 Step 3: Data Cleaning

 Step 4: Exploratory data analysis

 Step 5: Feature engineering and selection

 Step 6: ML Model assumption and checks

 Step 7: Data preparation for modelling

 Step 8: Model Building

 Step 9: Model Validation & Evaluation

 Step 10: Predictions & Saving model using pickel library.
