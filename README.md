👩‍💼 HR Analytics Dashboard

📌 Project Description

This project focuses on HR analytics using SQL, Power BI, Excel, and Tableau to analyze employee attrition, job satisfaction, and workforce demographics. The goal is to derive insights that help HR teams improve retention, enhance job satisfaction, and guide workforce planning.

🎯 Objectives

Track and analyze employee attrition trends across gender, department, education field, and age groups.

Evaluate job satisfaction by job roles.

Identify patterns across employee demographics, tenure, and engagement.

Build interactive dashboards for real-time HR reporting and decision-making.

🛠 Tools & Technologies

SQL (SSMS) – for data querying and transformation

Power BI – for dynamic and interactive dashboarding

Excel – for pivot-based visual summaries

Tableau – for story-style interactive data visualizations

🔍 SQL Analysis Overview

Key queries written in the project include:

Employee Count

sql

SELECT SUM(employee_count) AS Employee_Count FROM hrdata_sql;
Attrition Metrics

sql

SELECT COUNT(attrition) FROM hrdata_sql WHERE attrition = 'Yes';
Attrition Rate

sql

SELECT ROUND((COUNT(attrition='Yes') * 100.0) / SUM(employee_count), 2) AS Attrition_Rate FROM hrdata_sql;
Department-wise & Gender-wise Attrition

Attrition by Education Field

Attrition by Age Band and Gender

Job Satisfaction Ratings by Role

These queries helped in preparing data for dashboard integration and deriving deep HR insights.

📊 Dashboards

🟢 Power BI Dashboard

KPI Cards: Attrition Rate, Total Employees, Average Age

Slicers for gender, department, education field

Bar charts for attrition by role, age group, and job satisfaction

🔵 Tableau Dashboard

Story dashboard highlighting high attrition departments and gender-age group trends

Interactive views on satisfaction level and department-wise analysis

🟠 Excel Dashboard

Pivot charts and KPI summaries

Clean static visuals for quick HR reporting

📈 Key Insights

Highest attrition occurs in the Sales and R&D departments.

Younger age groups and males show higher attrition rates.

Job roles with low satisfaction ratings correlate strongly with higher attrition.

Education field and employment type impact overall attrition trends.

📁 File Structure

/SQL Query.docx                -- All SQL used for HR analysis

/HR_DASHBOARD_POWERBI.pbix     -- Power BI Dashboard file

/HR Analytics Dashboard.twbx   -- Tableau Workbook

/HR DATA_Excel_Dashboard.xlsx  -- Excel-based dashboard

/README.md                     -- Project documentation (this file)

🚀 Future Scope

Integrate machine learning to predict future attrition risk

Use Power BI service or Tableau Public for real-time publishing

Combine survey data for engagement analysis

🙋‍♀️ Author

Riya Joshi
