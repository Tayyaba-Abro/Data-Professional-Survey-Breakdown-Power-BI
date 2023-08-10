# Data Professional Survey Breakdown
<img width="700" alt="power bi dashboard" src="https://github.com/Tayyaba-Abro/Power-BI-Project/assets/47588244/d0ec431f-5785-48aa-96f0-757329a23474">

## Introduction: 
This project presents an analysis of a survey conducted among data professionals to understand various aspects of their careers, including career switches, salaries, industries, programming languages, and job satisfaction. The goal is to extract insights and trends from the survey data to gain a better understanding of the data professional landscape.

## Data Source 
The dataset used for this analysis was sourced from another analyst profile [Alex the Analyst](https://github.com/AlexTheAnalyst/Power-BI/blob/main/Power%20BI%20-%20Final%20Project.xlsx). It contains responses from data professionals in various fields, detailing their career journeys and preferences.

## Data Cleaning
Data Cleaning was done in Excel. 
1. Checked for data types i.e: for for date and time 
2. Filter out irrelavant data values by splitting values with delimiter:
   a. Remove row text other than word 'options'
   b. Delete irrelevant columns
3. As in each row current salary is provided with ranges so:
   a. Split values with delimiter
   b. Find average of two ranges with custom column
   c. Remove unwanted colunms

## Data Visualization 
To understand the data professional landscape, I created a comprehensive dashboard using Power BI. The dashboard showcases the results of Data Professional Survey Breakdown, providing fascinating insights into various aspects of the industry.

1. Cards to represent unique metrics like: Count of Survey Takers and Average Age of Survey Taker 
2. The Treemap to represents the distribution of survey takers across different countries
3. The stacked bar chart for average salary by job title sheds light on the earning potential within the field
4. A column chart that illustrates the distribution of votes for programming languages among different job titles
5. A donut chart to categorize the difficulties faced by aspiring data professionals
6. Gauges to measure happiness levels in current positions. One gauge evaluates work/life balance, while the other assesses satisfaction with salary
7. 
