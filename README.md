# Customer Churn Prediction for XYZ Analytics

## Project Description
This project was part of a Data Science simulation for BCG, where the goal was to analyze customer churn for XYZ Analytics, a fictional company. The objective was to understand the factors influencing customer churn and predict the probability of churn using advanced data science techniques.

### Objective
The main objective of this project was to test the hypothesis that price sensitivity of customers is a key factor influencing their churn rate. Predictive models were built using historical data on customers and pricing to quantify the impact of price changes on customer behavior.

## Project Goals
- Understand the factors influencing customer churn for XYZ Analytics.
- Build predictive models to estimate the probability of churn.
- Analyze the impact of price sensitivity on churn and suggest strategies to improve customer retention.

## Dataset
The dataset used in this project contains information such as:
- Customer features (e.g., industry sector, historical electricity consumption).
- Churn data (whether the customer left or stayed).
- Historical pricing data for electricity and gas.

The dataset was preprocessed to ensure quality and relevance for modeling, and feature engineering techniques were applied to derive useful insights.

## Tools and Technologies
- **Python**: The primary programming language used for data analysis and modeling.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-learn**: For building and evaluating machine learning models (Logistic Regression, Random Forest, Gradient Boosting).
- **Jupyter Notebooks**: Used for exploratory data analysis and model development.

## Steps Involved

### 1. Data Collection and Preparation
- **Data Identification**: Extracted customer characteristics (e.g., sector, consumption history), churn data, and historical pricing data.
- **Data Cleaning**: Cleaned and preprocessed the data to ensure it was relevant and ready for modeling.

### 2. Feature Engineering
- **Price Sensitivity Calculation**: Created metrics to evaluate the impact of price variations on churn.
- **Feature Creation**: Transformed raw data and created new features to improve model performance.

### 3. Modeling and Evaluation
- **Model Development**: Built classification models using Logistic Regression, Random Forest, and Gradient Boosting.
- **Model Optimization**: Evaluated and optimized models in terms of accuracy, complexity, and interpretability.
- **Results**: The Random Forest model achieved a precision rate of 85% in predicting churn.

### 4. Insights and Recommendations
- **Executive Summary**: A report summarizing the findings and providing strategic recommendations for XYZ Analytics.
- **Recommendations**: Proposed targeted strategies for managing customers at risk of churn, including adjusting prices based on customer sensitivity.

## Results
- **Model Performance**: The Random Forest model predicted customer churn with an accuracy of 85%.
- **Price Sensitivity Insights**: Identified customers who are highly sensitive to price changes.
- **Actionable Recommendations**: Suggested specific approaches for improving customer retention by adjusting pricing strategies for sensitive customers.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/churn-prediction-xyz-analytics.git
