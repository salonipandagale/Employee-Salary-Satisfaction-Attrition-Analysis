# Employee Salary, Satisfaction & Attrition Analysis
## Project Overview

This project focuses on analyzing employee data within the tech industry to understand compensation patterns, job satisfaction, and attrition behavior. It is divided into three key components:
Part 1. Salary Prediction (Regression)
Part 2. Attrition Prediction (Classification)
Part 3. Business Insights Extraction

The goal is to build data-driven solutions that help organizations make informed decisions regarding employee compensation and retention.

## Project Structure
├── Part 1: Salary Prediction
│   ├── EDA & Feature Engineering (Current Notebook)
│   ├── Model Building (Regression)

├── Part 2: Attrition Prediction
│   ├── Data Preparation
│   ├── Classification Models

├── Part 3: Business Insights
│   ├── Key Findings
│   ├── Recommendations

# Part 1: Salary Analysis & Prediction
## Objective

The primary objective of this phase is to analyze salary trends in the tech industry and prepare the dataset for predictive modeling.

## Key Questions Addressed
1. What factors influence employee salary?
2. How do experience and education impact compensation?
3. Do technical skills significantly affect salary levels?
4. How does salary vary across different tech domains?
5. Exploratory Data Analysis (EDA)

This notebook focuses on understanding the dataset through:
1. Distribution analysis of salary
2. Relationship between experience and salary
3. Impact of education level on compensation
4. Salary variation across job roles and tech fields
5. Influence of company size and work arrangement
6. Feature Engineering

## Key transformations performed:
1. Log transformation of salary to handle skewness
2. Encoding categorical variables using One-Hot Encoding
3. Scaling numerical features using StandardScaler
4. Creation of derived features

These steps ensure the dataset is suitable for machine learning models.

Dataset : https://www.kaggle.com/datasets/mabubakrsiddiq/salary-and-skills-ds-what-factors-increases-salary

EDA On kaggle : https://www.kaggle.com/code/salonipandagale/eda-for-annual-salary-prediction

--------------------------------------------------------------------------------------------

## Tools and Technologies
Python
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
XGBoost

## Next Steps
1. Build and evaluate regression models for salary prediction
2. Optimize model performance using hyperparameter tuning
3. Develop classification models for predicting employee attrition
4. Extract actionable business insights from model results

## Key Outcome (Part 1)
This phase establishes a strong foundation for predictive modeling by:
1. Identifying key salary drivers
2. Preparing clean and transformed data
3. Creating a reusable preprocessing pipeline

## How to Use
Clone the repository or open the notebook on Kaggle
Run the EDA notebook to understand data patterns
Proceed to the modeling notebooks for prediction tasks
Contribution

If you find this project useful, consider giving it an upvote or a star. Contributions and suggestions are welcome.
