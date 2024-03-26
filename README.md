# Bigmart

The data was gotten fron Kaggle.


**About The Dataset**

**Description:**

This project delves into the vast sales data collected by BigMart in 2013. The data encompasses a diverse range of products across numerous stores located in various cities. Additionally, key characteristics associated with both products and stores have been identified.

**The Objective:**

The primary objective is to construct a robust predictive model that can accurately forecast the sales of individual products within specific stores. This model will empower BigMart to gain valuable insights into the critical factors, both product-related and store-specific, that significantly influence sales performance. By leveraging these insights, BigMart can optimize their operations and strategies to drive sales growth across their extensive network.

*Project Outline: Predicting BigMart Sales:*

**Data Exploration and Cleaning**

Understand the structure and content of the BigMart sales dataset.

Identify and address any missing values, outliers, or inconsistencies in the data.

Perform exploratory data analysis (EDA) to gain insights into the distribution of key variables and potential relationships between them.

**Model Building:**
 Predicting Product Sales

Develop and train regression models to predict the sales for each product. This might involve:

Feature engineering: Create additional features from existing data that might be relevant for predicting sales.

Model selection: Train and compare different regression models such as linear regression, decision trees, or ensemble methods.

Model hyperparameter tuning: Optimize the parameters of each model to improve its performance.

Model Evaluation and Comparison

Evaluate the performance of each model using appropriate metrics such as:

R-squared (R²) score: Measures how well the model explains the variance in the target variable (sales).

Root Mean Squared Error (RMSE): Represents the average difference between predicted and actual sales values.

Compare the models based on their evaluation metrics to identify the one with the best predictive performance.

**Conclusion and Recommendations**

Summarize the findings and insights gained from the analysis.

Based on the best-performing model, identify key factors related to product and store characteristics that significantly influence sales.

Recommend actionable strategies for BigMart to leverage these insights in maximizing their sales potential.


**Insights and findings.**
From the analysis, it is found that fruits and vegetables sell the most, followed by snack foods.

It is also noticed that Dairy, Meat and sea food have the highest mean Maximum Retail price.

In terms of fat content, Items of Low and Regular Fat sell the most.

The Item_MRP is the same regardless of the Outlet Type.


**Key factors related to the model**
Using a heatmap to visualise the correlation of all variables with the Item_Outlet_Sales, it is noticed that Item_MRP affects the Item_Outlet_Sales the most,followed by Outlet location type.


**Recommendations and actionable strategies for BigMart**

Big Mart should stalk more Items of Low and Regular fat content since they sell the most.

While making decisions on pricing, Big Mart should put into consideration the Item_MRP since it greatly affects sales.

And during expansion, big mart sales should go on putting oulets in places with the characteristics of Supermarket type 3, 1 and 2 respectively to maximise sales.

**Technology Used**

Python

