# Attrixion 
</br>Attrixion is a comprehensive data analysis and prediction project aimed at understanding and predicting customer churn. This repository contains code and data related to the exploratory data analysis (EDA) of churn data and the development of a churn prediction model.

# Overview  
</br>Customer churn, the rate at which customers stop doing business with an organization, is a critical metric for any company. Understanding the factors that contribute to churn and being able to predict it can be a game-changer in retaining valuable customers.

# Project Workflow 
<br> The Attrixion project involves the following key steps:

1. Exploratory Data Analysis (EDA): We start by performing an in-depth analysis of the provided dataset, which is typically stored in a file called Telco-Customer-Churn.csv. During EDA, we gain insights into the data's structure, distributions, and relationships between variables. Any missing or inconsistent data is identified and processed to ensure data quality.

2. Data Preprocessing: After completing EDA, we preprocess the data to prepare it for model building. This includes handling missing values, encoding categorical variables, and scaling features as needed.

3. Upscaling the Data: To address class imbalance issues in churn prediction (where non-churned customers typically outnumber churned customers), we employ the Synthetic Minority Over-sampling Technique (SMOTE) and Edited Nearest Neighbors (ENN). This upscales the dataset to create a balanced and representative dataset for model training.

4. Model Building: With a clean and balanced dataset in hand, we proceed to build predictive models. We experiment with multiple algorithms to find the best-performing one in terms of accuracy.
