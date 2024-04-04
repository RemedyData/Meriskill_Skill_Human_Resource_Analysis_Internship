# Meriskill_Skill_Human_Resource_Analysis_Internship
Meriskill Internship: HR Analytics; Delving into the world of human resources, with a keen eye  on data analysis to optimize talent management and organizational  performance.
(*The picture below is gotten from Meriskill Website*). 



![Meriskill-HR](https://github.com/RemedyData/Meriskill_Skill_Human_Resource_Analysis_Internship/assets/137626163/6881ab4e-1c87-4cf5-ab44-9a54af64e623)


***Disclaimer:*** This is not a real company as we know this is a dataset compiled by Meriskill for Internship purposes. 


## Introduction

This is a Human Resources performance analysis. It is done by analyzing data from the HR-Employee Attrition table which comprises of Age column, Attrition column, 

I used Excel to get an overview of the dataset before importing it into Power BI where the actual analysis was carried out. 

## Problem Statement

The goal of this analysis is to:

- Determine the demographics:
This entails employee statistics including age groups, gender, distance from home, marital status providing insight into workforce diversity and commuting patterns for informed-decision making.

- Determine the turn over analysis:
This section consolidates employee data featuring attrition by job level, departures by department, business travel impact, total years in current roles, overtime performance ratings, monthly income, attrition increase level offering critical insights for effective HR strategies and informed-decision making

- Know the employee well-being

- Finally, the goal is to create data-driven plans that can aid in increasing sales, improving customer satisfaction, and driving the company's growth

## Skills and Concepts Demonstrated:

- Power BI concepts like:
   - Creating key performance indicators (KPIs) and other business calculations
   - Developing general DAX calculations that deal with text and numbers,
   - Performed advanced DAX calculations for solving statistical measures and other mathematical formulas,
   - Data Modelling,
   - Measures,
   - Filters,
   - Tooltips,
   - Page buttons,
   - Data visualization
 
   ---
  ## Data Source:
  
The dataset for the work is gotten from Meriskill. It consist of 1,471 records and 35 fields of data. I studied the dataset well to gain proper insight into the dataset. You can find a link to download the dataset [here:](https://drive.google.com/drive/folders/1ZOfwcTEByzmRlYkhohozQ5Or-LYBq4-P?usp=drive_link)

   ---

## Data Transformation and Visualization::

## STEP 1:
I downloaded the dataset and uploaded the data using the "Get Data" option in 
Power BI. Then, I utilized the "Transform" option to check for any null values 
in the dataset.

## STEP 2:
I chose the card visual. Using the "Format Visual" option, I customized the design of the card as 
needed.

![Internship-1](https://github.com/RemedyData/Meriskill_Skill_Human_Resource_Analysis_Internship/assets/137626163/9f267f3f-5e6b-4ee8-b965-b3c96300837f)




## STEP 3: 
Total attrition by education field by clustered bar chart



## STEP 4:
I chose two donut charts, then dragged and dropped 
the provided columns. I applied different colours 
to distinguish between them.

To obtain the counts of 237 and 1233, I followed these steps: 
- I navigated to the table view
- I clicked "New Column," and apply the provided formula.


![Internship-3](https://github.com/RemedyData/Meriskill_Skill_Human_Resource_Analysis_Internship/assets/137626163/208b34c8-96ed-481b-a35c-141b667aa275)

This yielded the desired results: 

if "Attrition" is "Yes," the count is 1; 
if it's "No," the count is 0.

![Internship-3a](https://github.com/RemedyData/Meriskill_Skill_Human_Resource_Analysis_Internship/assets/137626163/fcc4fdcb-dae7-4294-a3d4-83ece98215a9)


Summing all the 1s gives the total attrition count that is 237 
And subtracting this from the employee count yields the count of active 
employees that is 1233

![Internship-3b](https://github.com/RemedyData/Meriskill_Skill_Human_Resource_Analysis_Internship/assets/137626163/31d8dcfa-acb4-418e-830b-98a759ec9f09)

By dragging and dropping it in the field I got the active employees


## STEP 4: 
Using data groups for making better visuals. Using groups, I aggregated certain values together to form meaningful subsets.
Furthermore, I created three visuals using the concept of grouping to organize and display the data effectively.

- Firstly, I choose the column I want to group

![Internship-4](https://github.com/RemedyData/Meriskill_Skill_Human_Resource_Analysis_Internship/assets/137626163/8ffbaf8e-766f-4a13-acc8-17572ca74ef8)

- Then, I changed the group type from BIN to LIST

![Internship-4a](https://github.com/RemedyData/Meriskill_Skill_Human_Resource_Analysis_Internship/assets/137626163/9fdfd66d-61cd-42d3-a891-3f72011a9972)

![Internship-4b](https://github.com/RemedyData/Meriskill_Skill_Human_Resource_Analysis_Internship/assets/137626163/0402cd39-6595-4249-a5e0-12e86e8d6a7d)


I grouped: 
- 1 as "Bad"
- 2 as "Average"
- 3 as "Good"
- 4 as "Excellent."

 
• Then, I dragged and dropped in the fields.
• I did the same grouping steps for “AGE” and distance from home.
• For distance from home, I grouped: 
- 1-10 as "near"
- 10-20 as "far"
- 20 – 30 as "very far".

## STEP 5: 
Total attrition by marital status using stacked column chart

## STEP 6: 
Gender count using donut chart.




---



## Data Analysis and Visualization:

Several expressions and functions were made to arrive at the desired KPI or Metrics.
I arrived at a report with a single dashboard consisting of different visuals such as bar chart, doughnut chart, clustered bar chart, and KPIs, giving the summary of the insights gained into the Human Resource performance.

## Features of the Report:
The dashboard conveys information about the following key areas:
- Age groups
- Gender
- Distance from home
- Marital status
- Attrition by job level
- Departures by department
- Business travel impact
- Total years in current roles
- Overtime performance ratings
- Monthly income
- Attrition increase level
- Employee well-being

![Meriskill-Internship-2nd-Project-Pics](https://github.com/RemedyData/Meriskill_Skill_Human_Resource_Analysis_Internship/assets/137626163/a661761f-ea12-4068-a733-ac8454fc0598)




## Analysis

Summary of the insights gained into the company's performance: 

▪︎There are 1,470 employees in total representing the human resources force of the company. 

▪︎84% (1,233) of the total employees are active leaving 16%(237) of the total employees attritted.

▪︎There is a higher rate of attrition in employees that are single than in married and divorced ones with the males gender leading with 26.49%.

▪︎53.59% of the employees that are being attritted have a good work life balance. While 10.55% of them have a bad work life balance. 

▪︎Sales executives, Research scientists and Laboratory technicians happens to be the top 3 educational professionals that are being attritted.

▪︎Employees above age 30 had the highest attrition rate follow by those in their twenties next to those near age 50 and above.
▪︎60.76% of the employees attritted live nearby the company location. 


## Recommendation

- There are no doubts that the Human Resource performancde is staggering  which definitely affects the company's returns.

-

- It is suggested that a friendly survey be conducted among the employees at certain intervals yearly so as give the management team a better understanding of their employees.

- Likewise, more incentives should be offered to the employees so as to retain them for a longer period. 


---

### Thank you for reading.

I am open for entry-level data analyst role.
