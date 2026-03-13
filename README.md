\# Telecom Customer Churn Analysis



\## Project Summary

This project analyzes telecom customer churn using machine learning to identify factors that influence customer retention. Using exploratory data analysis and a K-Nearest Neighbors (KNN) classification model, the project examines customer behavior patterns and predicts the likelihood of churn.

Customer churn represents a significant challenge for telecommunications companies because acquiring new customers is often much more expensive than retaining existing ones. By identifying the key drivers of churn, businesses can implement targeted retention strategies to improve customer satisfaction and reduce revenue loss.

\## Project Highlights
- Performed exploratory data analysis (EDA) to identify patterns related to customer churn
- Built a K-Nearest Neighbors (KNN) classification model
- Evaluated model performance using confusion matrix, classification report, and accuracy score
- Identified key churn drivers including daily usage charges and customer service interactions
- Provided business recommendations to improve customer retention



\## Business Problem

Telecommunications companies lose revenue when customers cancel their service. Understanding why customers leave can help organizations improve retention strategies.



This project explores customer usage data, service interactions, and billing information to determine which factors contribute most strongly to customer churn.



\## Dataset Overview

The dataset contains customer account information including usage statistics, service calls, and billing data.



Key variables used in the analysis include:



\- Total Day Minutes

\- Total Day Charge

\- Customer Service Calls

\- Churn (Target Variable)



The target variable \*\*Churn\*\* indicates whether a customer left the company.



\## Data Preparation

Initial preprocessing steps included:



\- Checking for missing values

\- Selecting features with meaningful correlation to churn

\- Removing variables with very low correlation



A correlation heatmap was used to identify the most relevant features for predicting churn.



\## Exploratory Data Analysis



\### Correlation Heatmap

!\[Correlation Heatmap](visualizations/correlation\_heatmap.png)



\### Feature Relationships

!\[Pairplot](visualizations/pairplot\_features.png)



\### Data Distribution

!\[Boxplot](visualizations/feature\_boxplot.png)



\### Model Optimization

!\[Optimal K](visualizations/knn\_optimization.png)



\## Machine Learning Model

A \*\*K-Nearest Neighbors (KNN)\*\* classification model was used to predict whether a customer will churn.



Steps included:



\- Splitting the dataset into training and testing sets

\- Standardizing feature values

\- Training a KNN classifier

\- Evaluating model performance using accuracy, confusion matrix, and classification report



\## Key Insights

The analysis identified several factors associated with higher churn probability:



\- Customers with frequent \*\*customer service calls\*\* show higher churn risk.

\- Customers with higher \*\*daily usage charges\*\* may be more likely to leave.

\- Usage patterns can provide early indicators of potential churn.



\## Business Recommendations

Based on these findings, telecom companies should consider:



\- Improving customer service interactions to resolve issues quickly

\- Monitoring customers with frequent support calls

\- Offering incentives or loyalty programs for high-usage customers



These strategies could help reduce churn and improve customer satisfaction.



\## Tools Used

\- Python

\- Pandas

\- Seaborn

\- Matplotlib

\- Scikit-learn

\- Google Colab



\## Future Work

Future improvements to this analysis could include:



\- Testing additional machine learning models such as Logistic Regression and Random Forest

\- Performing feature engineering to improve prediction accuracy

\- Developing an interactive dashboard to visualize churn risk



