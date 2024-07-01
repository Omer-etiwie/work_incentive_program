# work_incentive_program

### Project Overview

This data analysis project aims to provide insights into the Absenteeism performance  over the work. By analyzing various aspects of data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the company's performance.

![Dashboard](https://github.com/Omer-etiwie/work_incentive_program/assets/171517937/8f7b3ace-1d5a-43dd-8da1-4ca98552da11)


### Data Sources

Data: The primary dataset used for this analysis is the "Absenteeism_at_work.csv", "compensation.csv" and "Reasons.csv"

### Tools

- SQL Server - Data cleaning & Analysis
-  PowerBI - Creating reports

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting

![screenshot](https://github.com/Omer-etiwie/work_incentive_program/assets/171517937/a75ee726-36da-4dd7-ac60-8a6eceea89ea)


### Exploratory Data Analysis

EDA involved exploring the data to answer key questions, such as:
1. Find the healthiest
2. Compensation rate increase for non-smokers

### Data Analysis

Include some interesting code/features worked with
  
  ```sql
select count(*) as nonsmoker
from Absenteeism_at_work
where Social_smoker = 0;
  ```

### Results/Findings

The analysis results are summarized as follows:
1. Across all 5 Day_of_the_week, Sum of Absenteeism_time_in_hours ranged from 553 to 1,489.
2. Average of Absenteeism_time_in_hours is 6.9








