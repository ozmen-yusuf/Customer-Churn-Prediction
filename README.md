# Customer Churn Prediction for a Telecom Company

## Project Overview

This project focuses on one of the most critical challenges for subscription-based businesses: customer churn. Using a dataset of telecom customer data, this analysis aims to identify the key factors that lead to customers terminating their service. The ultimate goal is to build a predictive model that can flag customers at high risk of churning, allowing the business to take proactive retention measures.

## Analysis and Process

The project followed these key steps:

1.  **Data Loading and Initial Exploration:** The dataset was loaded using Pandas for an initial inspection of its features, structure, and to identify any immediate data quality issues.
2.  **Exploratory Data Analysis (EDA):** A deep dive into the data to uncover relationships between customer attributes and churn. This involved analyzing the impact of various services and customer demographics on the churn rate.
3.  **Data Visualization:** Created visualizations using Matplotlib and Seaborn to clearly present the findings from the EDA phase, such as comparing churn rates across different customer groups.
4.  **Predictive Modeling:**
    * The data was split into training and testing sets to ensure a reliable evaluation of the model.
    * A classification model (like `DecisionTreeClassifier` or `LogisticRegression`) was trained to learn the patterns of churning customers.
    * The model's performance was evaluated using metrics like the accuracy score to determine its predictive power.

## Key Insight & Personal Reflection

My initial hypothesis was that high monthly charges would be the primary driver of churn. However, the data revealed that other factors were significantly more influential. This project highlighted the importance of challenging initial assumptions and letting the data tell the story.

## Technologies Used

* **Language:** Python 3
* **Libraries:**
    * Pandas for data manipulation
    * Matplotlib & Seaborn for data visualization
    * Scikit-learn for machine learning modeling
