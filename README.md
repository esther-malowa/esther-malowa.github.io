# Data Portfolio

This is my portfolio website

## Insights into Jobs Data 2024

## Table Of Contents
---
. [Project Overview](#project-overview)

. [Data Sources](#data-sources)

. [Tools](#tools)

. [Data Cleaning/Preparation](#data-cleaning/preparation)

. [Data Analysis](#data-analysis)

. [Results/Findings](#results/findings)

. [Recommendations](#recommendations)

. [Limitations](#limitations)





### Project Overview

The primary goal of this project is to analyze job market trends, identify key factors influencing employment, and provide actionable insights for job seekers, employers, and policymakers. The analysis will focus on various aspects such as job demand, salary trends,  and geographical distribution of job opportunities.


![Jobs_dashboard](https://github.com/user-attachments/assets/01647d26-c20b-4a73-a8a7-4a75f645f20a)

### Data Sources

Restaurant dataset: The primary dataset used  for this analysis is the "Restaurant dataset.csv" 

### Tools
- Excel - Data Cleaning [Download here](https://microsoft.com)
- MySQL - Data Analysis [Download here](https://microsoft.com) 
- PowerBI - Creating reports  [Download here](https://microsoft.com)

### Data Cleaning/Preparation
In the initial data preparation phase, I performed the following tasks;

1. Data loading and inspection

2. Handling missing values

3. Data cleaning and formatting

### Data Analysis
 
 ```SQL
select distinct experience_level,
employment_type,
job_title,
salary_in_usd,
employee_residence,
work_setting,
company_location,
company_size,
job_category 
from jobs_in_data_2024;
```

### Results/Findings
1. Machine learning has the highest average salary than other jobs.
2. Employees with the executive experience level earn more than other levels.
3. Full-time employees earn more than part-time, freelancers, and contracts.
4. Companies in Qatar pay the highest amount than other countries

### Recommendations
1.  Individuals looking to maximize their earning potential should consider specializing in machine learning. Pursuing advanced degrees or certifications in machine learning, data 
    science, or artificial intelligence can enhance employability and salary prospects.
2.  Educational institutions to offer specialized courses and programs in machine learning and related fields. Collaborate with industry partners to provide practical training and 
    internships.
3. Professionals aspiring to reach executive-level positions should focus on gaining relevant experience, leadership skills, and strategic thinking capabilities. Networking, mentorship, 
   and pursuing executive education programs (like MBAs) can also be beneficial.
4. Those seeking stability and higher income may prefer full-time employment. However, individuals who value flexibility or work-life balance might consider part-time, freelance, or 
   contract roles, even if they typically offer lower pay.
5. Professionals considering relocation or international opportunities may look into job prospects in Qatar, particularly in high-paying sectors. However, it's important to also consider 
   factors such as cost of living, cultural differences, and quality of life.

### Limitations
I had to remove work year,salary, and salary currency columns because they would have affected  the accuracy of my conclusion from the analysis.



    





