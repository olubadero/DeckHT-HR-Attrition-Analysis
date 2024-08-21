# DeckHT-HR-Attrition-Analysis

## Case Study and Objective: 
DeckHT is experiencing a concerning increase in employee attrition rates, which is impacting productivity, morale and overall organizational performance. The objective of this Data Analytics project is to analyze HR and employee data including demographics, job roles, performance metrics and workplace satisfaction.
- To identify the underlying causes and predictors of employee attrition;
- By leveraging this data, we aim to develop predictive models that can help the HR department and management take proactive measures to reduce attrition, improve employee retention and create more stable and satisfied workforce.
  
The dataset provides for employee details i.e. age, gender, department, position, year of service, performance rating, satisfaction score, salary and attrition.

**Data cleaning and Transformation (Power Query: Extract, Transform and Load):** 
Utilising Power Query, a copy of the original dataset was extracted from the folder it was saved and loaded onto Power Query for transformation and cleaning for data analysis. 
**Exploratory Data Analysis (EDA):** The initial EDA done on the data to better understand the Data reveal the following information. 
- Employee ID is a primary key;
- Employee age is between 26-46yrs;
- Year of service is between 2-16yrs;
- Performance rating is between 5-9;
- Satisfaction score is between 3-4.8;
- Salary is 41000-78000.

**Data cleaning process included:**
- Checking for and removing duplicate data;
- Removing unwanted columns and rows;
- Splitting columns;
- Replacing header title;
- Trimming columns to ensure uniformity;
- Changing columns to their correct data types;
- Replacing incorrect values;
- Creating new columns to grade row data for easier analysis using IF statements e.g. ranking the satisfaction and performance scores; bucketing age groups etc.
  
After this process the cleaned data was loaded onto Excel worksheet for analysis.

**Descriptive Modelling:**
Various models were created to better organize and understand the data, then Pivot Table was utilized to summarize the data and show how different categories are affecting or influencing attrition with the Company. The following columns were modelled:
- Age and Gender (Demography)
- Job Roles, Year of Service and Department (Job Roles)
- Performance (Performance)
- Salary and Satisfaction Score (Satisfaction)
- KPI (Key Performance Indicators)
The summarized data were filtered using the attrition columns to establish if the above columns were influencing factors for the employees leaving the Company. Also, targets were created against some columns such as Performance Rating, Satisfaction Rating, Salary, which helps to further show this is the reason for attrition.

**Visualization:**
To further make it easier to understand and interpret the data and models created then visualization is very necessary. Thus, the following visualizations were created to represent the data and models:
- Bar Chart;
- Column Charts;
- Line Chart;
- Spiral Chart;
- Doughnut Chart;
- Pie Chart.

