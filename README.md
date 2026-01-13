# TechCrush-Capstone-Project
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

<img src="Screenshot 2026-01-12 221411.png" width="300">

2. Question : Which department have highest and lowest turnover rates?

   Ans : Highest turnover → Sales (20.6%). More than 1 in 5 Sales employees leave
         Lowest turnover → Research & Development (13.8%)

<img src="Screenshot 2026-01-13 004205.png" width="400">

3. Question : How does attrition vary by employee age group and tenure?

   Ans : Attrition by Age group
   
|Age Group                  | Attrition Pattern|
|---------------------------|----------|
|Under 25                   | 39.2% Highest attrition|
|25 - 34                    | 20.2% High attrition|
|35 - 44                    | 10.1% Lowest attrition|
|45 - 55                    | 10.5% Low attrition|
|Over 55                    | 17% Moderate attrition|

<img src="Screenshot 2026-01-13 023421.png" width="400">

So, this means that employee under 25 are most likely to leave the organization likewise those withing the age band 25 - 34 Years. The 2 age groups has a high attrition rate, the have 59.4% attrition rate combined.

    Attrition by Tenure

|Years at Company            | Attrition Risk |
|----------------------------|----------------|
|0-1 Year                    | 34.9% Very high|
|2-3 Years                   | 18.4% High |
|4-5 Years                   | 13.1% Moderate |
|6-10 Years                  | 12.3% Low |
|10+ Years                   | 8.1% Lowest |

<img src="Screenshot 2026-01-13 023709.png" width="600">

The first year is the danger zone. Most people who leave do so before completing 12 months.
Once employees reach 3+ years, they become significantly more stable.
Long-tenured employees (6+ years) are very unlikely to leave.

- How Age and Tenure work together

  The highest attrition happens when both are low:

  Young employees (under 25 and 25-34) in their first 1–2 years are the most likely to quit.

  <img src="Screenshot 2026-01-13 024533.png" width="600">


4. Question : What is the relationship between salary levels and attrition?

   Ans :
       The relationship between salary levels and attrition is strong, clear, and negative.
       As salary increases, attrition decreases.

   |Salary Band                    | Attrition behaviour|
   |-------------------------------|--------------------|
   |High                           | Low (5.6%)|
   |Low                            | Extremely High (28.6%)|

    <img src="Screenshot 2026-01-13 030456.png" width="400">


    5. Question : How do job satisfaction rating correlate with employee retention?
  
       Ans : 






