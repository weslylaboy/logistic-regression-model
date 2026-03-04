# Employee Workload and Attrition Analysis

This project aims to build a logistic regression model to predict whether an employee will leave the company (attrition) based on their workload, performance, satisfaction, and other factors. This is a binary classification problem that provides actionable insights for HR and management to improve employee retention.

## Project Goals
- **Predict Attrition:** Identify employees at risk of leaving the company.
- **Identify Key Factors:** Determine which factors (e.g., workload, salary, satisfaction) most significantly contribute to attrition.
- **Support Business Decisions:** Provide data-driven recommendations for retention strategies, workload management, and cost reduction.

## Dataset
The dataset used in this analysis is `employee_performance_workload_attrition.csv`. It contains 2,800 observations and 10 features.

**Source:** [Kaggle - Employee Workload and Attrition Analysis](https://www.kaggle.com/datasets/jayjoshi37/employee-workload-and-attrition-analysis)

### Key Features:
- **employee_id:** Unique identifier for each employee (removed during preprocessing).
- **department:** Department where the employee works (HR, Engineering, Finance, Sales, Operations, Marketing).
- **role_level:** Job seniority level (Junior, Mid, Senior).
- **monthly_salary:** Monthly salary of the employee.
- **avg_weekly_hours:** Average number of hours worked per week.
- **projects_handled:** Number of active projects currently handled.
- **performance_rating:** Annual performance rating (scale 1-5).
- **absences_days:** Number of days the employee was absent during the year.
- **job_satisfaction:** Job satisfaction score (scale 1-5).
- **attrition (Target):** Indicates whether the employee left the organization (Yes) or stayed (No).

## Project Workflow
1. **Data Preparation:** Loading the data, handling missing values, and initial exploration.
2. **Exploratory Data Analysis (EDA):** Visualizing distributions and relationships between features and attrition using box plots, count plots, and correlation heatmaps.
3. **Data Transformation:** Encoding categorical variables (One-Hot and Label Encoding) and scaling numerical features.
4. **Modeling:** Building and training a Logistic Regression model.
5. **Evaluation:** Assessing model performance using metrics like accuracy, precision, recall, and F1-score.
