# Cyclistic Bike-Share Analysis
A complete data analysis project that explores the behavioral differences between Cyclistic annual members and casual riders using SQL and Tableau. The objective is to generate business insights and marketing recommendations to increase membership conversions.

![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-2563EB?style=for-the-badge)
![Data Visualization](https://img.shields.io/badge/Data%20Visualization-14B8A6?style=for-the-badge)

## Project Overview
Cyclistic is a bike-share company based in Chicago that wants to increase the number of annual memberships. This project analyzes one year of historical trip data to understand how annual members and casual riders use the service differently.

The analysis follows the complete data analysis process, including data cleaning, validation, exploratory analysis, visualization, and business recommendations.

## Business Problem
Cyclistic's marketing team wants to answer the following question:
How do annual members and casual riders use Cyclistic bikes differently?
The insights obtained from this analysis are intended to support marketing strategies that encourage casual riders to purchase annual memberships.

## Dataset
Source: Cyclistic Historical Bike Trip Data (Public Dataset)
Period: June 2025 – May 2026
Records analyzed: 5,666,094 trips
Bike stations: 692
Bicycles: 5,824
Customer Types: Casual Riders & Annual Members

## Tools & Technologies
- SQL (SQLite)
- Tableau
- Jupyter Notebook
- GitHub

## Data Cleaning
The dataset was validated before analysis to ensure data quality.

- Combined 12 monthly datasets into a single database
- Removed 35 duplicate records
- Removed one corrupted record with missing values
- Investigated 29 rides with negative durations caused by the daylight saving time transition
- Preserved records with missing station names for behavioral analysis while excluding them from station-specific analyses

## Key Findings
Metric	Member	Casual
Total Trips	3,646,524	2,019,570
Average Ride Duration	12.46 min	22.22 min

## Main Insights
### Members ride more frequently
Annual members generated approximately 64% of all trips, indicating consistent and routine use throughout the year.

### Casual riders take longer trips
Average ride duration for casual riders was almost 80% longer than for members, suggesting recreational rather than commuting usage.

### Riding patterns differ by weekday
- Members ride mostly on weekdays.
- Casual riders peak during weekends.
This indicates that members primarily use the service for commuting, while casual riders use it for leisure.

### Riding patterns differ throughout the day
Members show clear commuting peaks during the morning and afternoon.
Casual riders concentrate their trips during afternoons and evenings.

### Casual riders are highly seasonal
Ride activity increases significantly during spring and summer, while members maintain relatively stable usage throughout the year.

### Popular stations differ
- Casual riders concentrate around recreational and tourist areas.
- Members use a broader network of stations associated with daily transportation.

## Dashboard
https://public.tableau.com/views/Cyclistic_17816742028100/CyclisticUserBehaviorAnalysis?:language=es-ES&:sid=&:display_count=n&:origin=viz_share_link

## Business Recommendations
Based on the analysis, the following recommendations could help increase membership conversions:

### 1. Launch seasonal membership campaigns
Target casual riders during spring and summer when demand is highest.

### 2. Promote memberships at high-traffic stations
Use QR codes, digital signage, and promotional offers at stations frequently used by casual riders.

### 3. Highlight membership savings
Show users how much they could save annually compared to purchasing individual rides.

### 4. Create weekend-focused promotions
Offer weekend membership trials and limited-time discounts to attract recreational riders.

## Business Impact
This analysis demonstrates how data can be transformed into actionable business decisions.

## The findings help Cyclistic:

- Better understand customer behavior.
- Identify opportunities for customer segmentation.
- Improve marketing strategies.
- Increase membership conversion.
- Support data-driven decision-making.

## Skills Demonstrated
- SQL
- SQLite
- Data Cleaning
- Data Validation
- Exploratory Data Analysis (EDA)
- Data Visualization
- Tableau
- Business Analysis
- Marketing Analytics
- Storytelling with Data
- Git & GitHub

## Author
Jose Manuel Sanchez Jimenez

Industrial Engineer | Aspiring Data Analyst

jose.manuel.sanchez.jimenez0@gmail.com
