# Employee Attrition Analysis

## Overview
This project focuses on analyzing employee attrition data to help organizations understand factors contributing to employee turnover. By leveraging data analysis and machine learning techniques, the project aims to identify patterns and predictors of attrition, enabling companies to take proactive measures for employee retention.

The dataset includes various employee attributes such as age, job role, salary, job satisfaction, and more. The analysis involves data cleaning, exploratory data analysis (EDA), and preprocessing steps to prepare the data for predictive modeling.

### Business Process
The business process includes:
- **Recruitment and Hiring**: Understanding which demographic or educational profiles are associated with longer tenure helps optimize recruitment strategies.
- **Employee Retention**: Identifying factors causing attrition enables companies to design policies to retain employees, such as salary adjustments, career development programs, or improved work-life balance.
- **Cost Management**: High attrition leads to increased costs in hiring, onboarding, and training new employees. Predicting and reducing attrition minimizes these expenses.
- **Performance Management**: Insights from attrition data can inform HR policies to foster employee engagement and productivity.

By analyzing this dataset, organizations can enhance their human resource management processes, reduce attrition rates, and improve overall workforce stability and efficiency.

### Types of Analytics Performed on This Dataset
The dataset allows for the application of several types of analytics, including **descriptive**, **diagnostic**, **predictive**, and **prescriptive analytics**, to gain actionable insights into employee attrition.

1. **Descriptive Analytics**:
   - **Objective**: Summarize historical data to understand trends and patterns.
   - **Examples**:
     - Analyze the distribution of employees across payment tiers, cities, and educational levels.
     - Calculate attrition rates across demographic groups (age, gender, city, etc.).
     - Identify the most common profiles of employees who leave the company.
   - **Usefulness**: Provides an overview of attrition trends and highlights high-risk groups for targeted interventions.

2. **Diagnostic Analytics**:
   - **Objective**: Understand the reasons behind observed patterns or trends.
   - **Examples**:
     - Correlate variables like payment tier, experience, and being benched with attrition rates.
     - Explore whether younger employees or employees with specific education levels are more likely to leave.
   - **Usefulness**: Pinpoints underlying factors driving attrition, such as dissatisfaction with salary, location, or lack of career growth.

3. **Predictive Analytics**:
   - **Objective**: Use historical data to predict future outcomes.
   - **Examples**:
     - Build machine learning models to predict whether an employee will leave the company based on their attributes (e.g., gender, age, experience, etc.).
     - Predict the probability of attrition for specific employee profiles.
   - **Usefulness**: Enables proactive measures to retain employees at risk of leaving.

4. **Prescriptive Analytics**:
   - **Objective**: Recommend actions to reduce attrition based on insights from the data.
   - **Examples**:
     - Suggest targeted interventions for high-risk employee groups.
     - Recommend policy changes to improve employee satisfaction and retention.
   - **Usefulness**: Provides actionable recommendations to HR and management for reducing attrition.

## Libraries and Tools Used
- **Jupyter Notebook**: The primary environment for writing and executing the analysis code.
- **Pandas**: Used for data manipulation, cleaning, and analysis.
  - Data import and loading into Pandas DataFrame.
  - Handling missing values.
  - Changing data types.
  - Exploratory Data Analysis (EDA).
- **Matplotlib & Seaborn**: Libraries for data visualization.
  - Creating plots and charts to visualize trends and patterns.
- **Scikit-learn**: Used for preprocessing and machine learning.
  - Feature discretization, normalization, and encoding.
  - Train-test split for model evaluation.

## Files
- **main.ipynb**: Jupyter Notebook containing all the code and analysis.
- **Employees_dataset.csv**: The dataset used for analysis, downloaded from Kaggle. Errors were intentionally introduced to the dataset for data cleaning practice.
- **requirements.txt**: List of dependencies required to run the project.
