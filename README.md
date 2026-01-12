# TechCrush-
TechCrush project on GlobalCorp Nigeria Human Resource Attrition Analysis

### Project Overview

This project focuses on understanding employee attrition patterns using the GlobalCorp HR Analytics dataset. The goal is to identify how employee turnover evolves overtime during employment and to uncover the key workforce dynamics driving retention and exits.

The analysis evaluates how likely employees are to leave during their early, mid, and later stages of employment, helping HR leaders determine when attrition risk is highest and what interventions are most needed.

### Data Source

The data set used for this analysis is 'GlobalCorp Nigeria' HR dataset

### Tools

PowerBI - For data cleaning, creating reports and visualization
-  [Download Here](https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads?ocid=ORSEARCH_Bing&msockid=0739cabe1905633c0ca7de41184262b6)

PowerPoint - For designing the dashboard canvas
-  [Download Here](https://www.microsoft.com/en-us/microsoft-365/powerpoint?ocid=ORSEARCH_Bing&msockid=0739cabe1905633c0ca7de41184262b6)

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:

1. Data loading and inspection.
2. Data cleaning and formatting.
3. Visualization.

### Exploratory Data Analysis

- EDA involved exploring the HR data to answer key questions, such as:

- Dataset Overview
  The dataset contains 1,470 employee records with 35 variables describing demographic, job-related, compensation, performance, and satisfaction attributes.
The target variable is Attrition, indicating whether an employee has left the organization.

The dataset shows that attrition is mainly driven by:
  1. Low pay
  2. Poor job and environment satisfaction
  3. High workload and overtime
  4. Lack of promotions
  5. Early-career instability

### Data Analysis

Include some interesting DAX (Data Analysis Expression) functions e.g
```DAX
Total Employee= COUNTROWS('GlobalCorp Nigeria')
```
Creating new calculated/conditional columns e,g Attrition Count

### Findings

1. Question : What is the overall employee attrition rate across the organization?

   Ans : Using the dataset (GlobalCorp Nigeria):
   Total employees: 1,470
    Employees who left (Attrition = Yes): 237
    Overall Employee Attrition Rate
    Attrition Rate = 237 / 1470 × 100 = 16.12%

An attrition rate of 16.1% means that about 1 out of every 6 employees in the organization left.
    So this organization is experiencing moderately high attrition
 
  [Screenshot 2026-01-12 221411.png](https://github.com/slimayo/TechCrush-/blob/3d5b0bcdf6c7a7b04b501f2911b5587b1ddf60c2/Screenshot%202026-01-12%20221411.png)



