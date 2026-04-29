📊 HR Analytics Dashboard Project
📌 Project Overview

This project focuses on analyzing employee data to gain insights into workforce trends, employee attrition,
and organizational performance. The dashboard is built using Excel, SQL, and Power BI to transform raw HR
data into meaningful business insights.

🎯 Objectives
*Analyze employee demographics (age, gender, education)
*Identify key factors affecting employee attrition
*Track workforce distribution across departments and roles
*Measure employee satisfaction levels
*Build an interactive dashboard for decision-making

🎯 Objectives
*Analyze employee demographics (age, gender, education)
*Identify key factors affecting employee attrition
*Track workforce distribution across departments and roles
*Measure employee satisfaction levels
*Build an interactive dashboard for decision-making

📂 Dataset Description

The dataset contains HR-related information of employees:

Column Name    	      Description
emp_no	              Employee ID
gender	              Gender of employee
marital_status	      Marital status
age_band	            Age group
age	                  Exact age
department	          Department name
education	            Education level
education_field	      Field of study
job_role	            Job role
business_travel	      Travel frequency
employee_count	      Employee count
attrition	            Employee left or not
attrition_label	      Current/Ex employee
job_satisfaction	    Satisfaction rating (1–4)
active_employee	      Active status


🔄 Project Workflow
1. Data Cleaning (Excel)
Removed null and duplicate values
Standardized column names
Checked data consistency
Created derived columns (if needed)


2. Data Analysis (SQL)
Used queries for:
Attrition analysis
Department-wise employee count
Job satisfaction trends

Example:
SELECT department, COUNT(*) AS total_employees
FROM hrdata
GROUP BY department;

3. Data Visualization (Power BI)

Created an interactive dashboard with:

📌 KPI Cards (Total Employees, Attrition Rate)
📊 Bar Charts (Department-wise distribution)
📈 Trend Analysis
🧩 Slicers (Gender, Department, Age Band)


📊 Key Insights
Attrition is higher in certain departments (e.g., Sales/R&D)
Employees with lower job satisfaction are more likely to leave
Age group 25–34 shows higher turnover
Travel frequency impacts attrition


📷 Dashboard Features
Interactive filters (Department, Gender, Age)
Drill-down analysis
Real-time insights
Easy-to-understand visuals


🚀 How to Use
Open Excel file for raw data
Run SQL queries for analysis
Load cleaned data into Power BI
Explore the dashboard using filters
📌 Conclusion

This project demonstrates how data analytics can help HR teams:

Reduce employee attrition
Improve employee satisfaction
Make data-driven decisions


🔮 Future Improvements
Add predictive analysis (Attrition Prediction using ML)
Integrate real-time HR data
Enhance dashboard with advanced visuals


👨‍💻 Author
Sagar Tate
