# TechCrush-Capstone-Project
TechCrush project on GlobalCorp Nigeria Human Resource Attrition Analysis

### Project Overview

This project focuses on understanding employee attrition patterns using the GlobalCorp HR Analytics dataset. The goal is to identify how employee turnover evolves overtime during employment and to uncover the key workforce dynamics driving retention and exits.

The analysis evaluates how likely employees are to leave during their early, mid, and later stages of employment, helping HR leaders determine when attrition risk is highest and what interventions are most needed.

### Data Source

The data set used for this analysis is 'GlobalCorp Nigeria.csv' HR dataset

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
  
      Ans : As Job satisfaction increases, attrition drops sharply.

   |Job Satisfaction              | Attrition pattern |
   |------------------------------|-------------------|
   | Low                          | Very High (22.3%) |
   |High                          | Moderate (16.5%) |
   | Medium                       | Moderate (16.4%) |
   | High                         | Lowest attrition (11.3%) |

    <img src="Screenshot 2026-01-13 032237.png" width="400">


  6. Question : Which job roles experience the most frequent departures?

     Ans :

       |Job Role                  | Attrition Pattern  |
       |--------------------------|--------------------|
       |Sales Reprensative        | Highest turnover (39.8%)  |
       |Laboratoty Technician     | Very High (23.9%) |
       |Human Resources           | Very High (23.1%) |
       |Sales Executive           | High (17.5%) |
       |Research Scientist        | Moderate (16.1) |

       These 5 Job roles experience the most employee turnover

        <img src="Screenshot 2026-01-13 041018.png" width="400">


    7. Question : What is the average tenure of the employees who leave vs those who stay?
      
       Ans : Average tenure of employees who leave is 5.1 Years

          <img src="Screenshot 2026-01-13 041636.png" width="300">

          Average tenure of employees who stay is 7.4 Years

           <img src="Screenshot 2026-01-13 042017.png" width="300">


      8. Question : How does work-life balance rating affect attrition?
       
          Ans :           

  |Work-Life balance                 | Attrition Pattern  |
  |----------------------------------|--------------------|
  |Bad                               | Extremele High attrition (31.3%)  |
  | Excellent                        | High (17.6%) |
  |Fair                              | High (18.9%)   |
  |Good                              | Moderate (14.2%)   |

  Employees who rated their work–life balance as “Bad” are several times more likely to quit.

   <img src="Screenshot 2026-01-13 205054.png" width="300">

   9. Question : What percentage of high performers leave the organization?

       Ans : The Percentage of High Performers that lesve is 16.4%

      <img src="Screenshot 2026-01-13 205808.png" width="400">

  10. Question : How do promotion rates differ between retained and departed employees?

      Ans :

 |Promotion Rates                 | Attrition Pattern  |
 |----------------------------------|--------------------|
 |Promotion rates (Left)            |92.5%  |
 |Promotion rates (Stay)            |7.5%    |

 Promotion Rate Gap is 85%

  <img src="Screenshot 2026-01-13 214531.png" width="400">


11. Question : What does business travels has to do with attrition rates?

    Ans :

    |Business Travel Level	          |Attrition Pattern          |
    |---------------------------------|---------------------------|
    |Travel frequently               | Highest attrition (24.9%)  |
    |Travel rarely                   | Moderate (15%)              |
    |Non travel                      | Low (8%)                    |

    Employee who travels frequently are most like to leave the organization at thrice the rate of those who do not travel.

 <img src="Screenshot 2026-01-13 220246.png" width="400">

    12. Question : How do overtime frequency relate to employee turnover?

        Ans :

  |Overtime              	        |Attrition Pattern            |
  |---------------------------------|---------------------------|
  | Yes                             | Extremely High (30.5%)    |
  | No                              | Low (10.4%)               |

Employees with Yes leave at almost thrice the rate of employees who do not work overtime.

<img src="Screenshot 2026-01-13 222044.png" width="400">

13. Question : What is the gender distribution in attrition pattern?

    Ans :

     |Gender              	        |Attrition Pattern              |
     |------------------------------|------------------------|
     | Male                         | 17% Slightly High      |
     |Female                        | 14.8% Moderate         |

Attrition is fairly evenly distributed across gender, attrition in this organization is not primarily driven by the difference in gendeer distribution

<img src="Screenshot 2026-01-14 043027.png" width="400">

14. Question : How does distance from home and enviroment satisfaction correlate with team attrition?

    Ans :

    The strongest attrition risk appears when both conditions are unfavorable. People may tolerate a long commute or a bad environment  but rarely both.

    The team that has long distance from home low environment satisfaction are at high risk of attrition.

    <img src="Screenshot 2026-01-14 044412.png" width="400">





