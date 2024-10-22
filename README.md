# Travel Agency Dataset - Holiday Package Purchase Prediction

## Project Overview
This project involves analyzing customer data from the "Trips & Travel.Com" company, which aims to expand its customer base and optimize marketing expenditure by leveraging existing customer data. The dataset used in this project was collected from Kaggle and contains information about customer behavior, preferences, and purchases related to different holiday packages.

The goal is to predict whether a customer will purchase a holiday package based on their demographics, past interactions, and other relevant factors, helping the company plan more targeted marketing strategies for its upcoming "Wellness Tourism Package."

## Dataset
The dataset is sourced from Kaggle: [Holiday Package Purchase Prediction](https://www.kaggle.com/datasets/susant4learning/holiday-package-purchase-prediction).

### Dataset Details:
- **Rows:** 4,888
- **Columns:** 20

### Key Features:
1. **Customer Details:** Information such as age, gender, occupation, and marital status.
2. **Travel History:** Number of trips, preferred travel destinations, previous holiday package purchases.
3. **Financial Information:** Annual income, family income, and expenditure on previous trips.
4. **Purchase Behavior:** Data on whether the customer has purchased any of the five available holiday packages:
   - Basic
   - Standard
   - Deluxe
   - Super Deluxe
   - King

### Target Variable:
- **Purchase:** Indicates whether the customer purchased a package (Yes/No).

## Business Problem
"Trips & Travel.Com" wants to introduce a new package offering, the **Wellness Tourism Package**. Wellness tourism is aimed at customers who want to travel for health, fitness, and well-being. However, the company has faced challenges in previous marketing campaigns due to inefficient targeting, leading to high costs with limited customer conversion (only 18% of customers purchased packages).

The goal of this project is to create a predictive model that helps the company identify potential customers more effectively, thereby reducing marketing costs and increasing the likelihood of customer engagement.

## Objectives
- **Predict package purchases:** Build a machine learning model to predict whether a customer will purchase a holiday package based on historical data.
- **Targeted marketing:** Identify potential customers for the new Wellness Tourism Package.
- **Improve marketing efficiency:** Optimize marketing efforts by focusing on customers with a higher probability of purchasing.

## Steps Involved
1. **Data Preprocessing:**
   - Handling missing values, outliers, and inconsistent data.
   - Encoding categorical variables (e.g., gender, occupation).
   - Normalizing and scaling numerical data.
   
2. **Exploratory Data Analysis (EDA):**
   - Understand key trends and patterns in the data.
   - Analyze correlations between customer attributes and purchase behavior.
   - Visualize customer segmentation based on demographics and financial data.

3. **Model Building:**
   - Train and evaluate various classification models such as:
     - Logistic Regression
     - Random Forest
     - Decision Trees
     - Support Vector Machines (SVM)
     - XGBoost
   - Hyperparameter tuning for optimal performance.
   
4. **Model Evaluation:**
   - Assess models using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC curve.
   - Compare model performance to select the best one for predicting package purchases.
