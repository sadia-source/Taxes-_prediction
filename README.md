 
# Internship Project: Analyzing and Predicting Salaries for Texas State Employees

# Context
The Texas state government employs a diverse workforce across various agencies, each with unique job classifications, pay scales, and demographic characteristics. Understanding the salary structure and trends within this workforce is essential for informed decision-making regarding budget allocations, equity in compensation, and overall workforce management.

# The Problem
While the Texas state government has access to payroll data, there is a need for a comprehensive analysis to identify trends, disparities, and predictions related to employee salaries. Specifically, the government requires insights into salary outliers, the wage disparities between different roles and departments, and how salaries and total compensations have evolved over time.

# Impact
Without a thorough understanding of these factors, the Texas state government may struggle to address pay equity issues, manage budgets effectively, and retain talent. Disparities in salaries can lead to dissatisfaction among employees, decreased morale, and challenges in workforce management. A predictive model can empower the government team to make data-driven decisions that enhance transparency and fairness in employee compensation.

# Objectives
This project aims to fulfill the following objectives:

Data Analysis Report: Prepare a complete data analysis report on the provided payroll data. This will include:
Identification of outliers in salaries.
Analysis of wage disparities between managers and employees across different departments and roles.
Exploration of trends in salaries and total compensations for various roles, departments, and headcount over time.
Predictive Modeling: Create a predictive model that will assist the Texas state government team in forecasting payroll information for employees. This model should be able to predict individual employee salaries based on various attributes such as job classification, agency, and demographics.

# Attribute Information
The dataset contains the following attributes:

1. AGENCY: Unique identifier for the agency employing the individual.
2. AGENCY NAME: Name of the employing agency.
3. LAST NAME: Last name of the individual.
4. FIRST NAME: First name of the individual.
5. MI: Middle initial of the individual, if available.
6. CLASS CODE: Code representing the job classification.
7. CLASS TITLE: Title or position associated with the classification code.
8. ETHNICITY: Ethnicity category of the individual.
9. GENDER: Gender of the individual.
10. STATUS: Employment status, indicating position type (e.g., full-time, part-time).
11. HRLY RATE: Hourly rate of pay for the individual.
12. HRS PER WK: Hours worked per week by the individual.
13. MONTHLY: Monthly salary or earnings calculated for the individual.
14. ANNUAL: Annual salary or earnings calculated for the individual.
15. STATE NUMBER: Unique state identifier for the individual.
16. duplicated: Boolean indicating if the entry is duplicated across records.
17. multiple_full_time_jobs: Indicator if the individual has multiple full-time roles.
18. combined_multiple_jobs: Indicator if multiple jobs are combined for salary purposes.
19. summed_annual_salary: Total annual salary combined across multiple jobs, if applicable.
hide_from_search: Boolean indicating if the record should be hidden from searches.
