# Data-Analysis-
## Data Analysis of Unemployment Rate by age from 2008 - 2024
### Project Overview
This data analysis project aims to provide an overview and deeper understanding of unemployment trends across various age groups over a 17-year period, analyzed monthly.
### Data Source 
www.kaggledateset.com
### Tools
- Excel,Power Query /Data Cleaning 
- SQL Server /Minning & Data Analysis
- PowerBI /Creating Report
### Data Cleaning / Preparation
In the Intial data preparation the following were carried out;
- Data loading and inspection
- Handling Dupilicates and converting values to percentages.
- Dates Formatting and cleaning
### Exploratory Data Analysis
- Year with lowest & highest unemployment rate
- Month with the lowest & highest unemployment rate
- Age group with lowest & highest unemployment rate
### Data Analysis
```sql
SELECT * FROM [2 Unemployment rates by AGE group]
SELECT year,COUNT(DISTINCT month), age, Unemployment_rate
FROM [2 Unemployment rates by AGE group]
GROUP BY year,age,Unemployment_rate


### Observations/ Findings.
