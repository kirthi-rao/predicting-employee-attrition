# Employee Attrition Analysis
This project analyzes employee attrition patterns using machine learning techniques. The code provided performs exploratory data analysis, data preprocessing, model training, and model evaluation to identify key factors influencing employee turnover.


## Project Overview
The main objectives of this project are:

1. Analyze patterns in employee attrition

2. Identify key drivers of employee turnover

3. Develop predictive models for attrition risk


## Data Description
The dataset contains employee information including:

- Demographic data (age, gender, marital status)

- Job-related attributes (department, job role, years at company)

- Satisfaction metrics (job satisfaction, work-life balance)

- Compensation details (salary, stock options)


## Project Workflow
1. Data loading and initial exploration

2. Exploratory data analysis with visualizations

3. Handling of missing values and duplicates

4. Model development

5. Model evaluation


## Libraries Used
The project utilizes the following Python libraries:

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- imbalanced-learn (imblearn)
- xgboost
- catboost


## Future Work

To further refine this analysis and enhance predictive accuracy, future work will focus on:

**Feature Engineering:** 
- Implementing targeted feature engineering techniques to derive potentially more informative features from the existing dataset.

**Feature Selection:** 
- Evaluating the impact of various feature selection methods (e.g., Recursive Feature Elimination, SelectFromModel) on model performance.

**Data Preprocessing:** 
- Refining the data preprocessing pipeline by splitting the data into training and testing sets *before* imputing missing values, mitigating data leakage.

**Class Balancing:** 
- Experimenting with class weighting strategies (assigning higher weights to the minority class) as an alternative to SMOTE for addressing class imbalance.
