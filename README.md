📄 HR Data Analytics Project Documentation

Project Name: HR Data Analytics Project 

Tool Used: Using Power BI 

Date: November 1, 2025 

Instructor: Mahmoud Serag 


👥 Team Members

Maged 

Mahmoud Abdelkader 

Sandra 

Taher


🎯 1. Project Planning & Management

1.1 Project Proposal

Project Purpose: The goal is to develop an interactive HR analytics dashboard that provides clear, data-driven insights into employee demographics, salary distribution, performance ratings, education levels, and attrition trends.

Objectives:

Visualize key HR metrics to support strategic decision-making.

Identify patterns related to employee performance, turnover, and salary gaps.

Enhance the HR team’s ability to track changes over time.

Improve workforce planning and retention strategies.

Project Scope:

Data cleaning, preprocessing, and transformation.

Creating interactive visualizations using Power BI.

Delivering insights, recommendations, and documentation.

1.2 Project Plan (Timeline - Gantt Chart Described Textually)
Phase	Tasks	Duration
Phase 1	Requirements Gathering (Understanding HR needs, identifying KPIs)	
Week 1 

Phase 2	Data Preparation (Cleaning, validating, and transforming datasets)	
Week 2 

Phase 3	Dashboard Development (Building visuals and designing UI)	
Weeks 3–4 

Phase 4	Insights & Recommendations (Extracting insights from pages 1–6)	
Week 5 

Phase 5	Documentation & Review (Preparing reports, feedback revisions)	
Week 6 

Phase 6	Delivery & Presentation (Final dashboard presentation)	
Week 7
Key Deliverables:

Clean HR dataset 

Fully interactive Power BI dashboard 

Insights document 

Project report (full documentation) 

Final presentation 

1.4 KPIs (Key Performance Indicators)

Category	Key Performance Indicators (KPIs)

1. Attrition	
Overall Attrition Rate, Attrition Rate by Salary Range, Retention Percentage (Employees Who Stayed) 


2. Performance	
Average Self-Rating per Department, Average Manager Rating per Department, Self vs Manager Rating Gap 



3. Compensation	
Average Salary per Education Field, Total Salary per Job Role 


4. Demographics	
Employee Count by Marital Status, Gender Distribution 


5. Work Conditions
   
Average Distance From Home per Department

⚙️ 2. Requirements Gathering

2.1 Stakeholder Analysis
   Stakeholder Role Needs HR Manager Decision maker High-level insights on attrition, salary trends, overtime, and employee demographics39.HR Specialists, Daily users, Detailed filtering options, ability to track individual departments or employee groups40. 
   Top Management (CEO/Directors): Strategic oversight, summary metrics, trends over time, and key workforce challenges41.Data Analyst / BI Developer, System creator, Clean, structured dataset and clear functional requirements42.
   2.2 Functionalities & Features

Data & Visualization: Display KPIs, provide interactive charts, include slicers for department, age group, salary slab, job role, etc., and allow drill-down/cross-filtering.


Data Processing: Clean and transform raw HR data, implement DAX measures for calculated fields, and build a star schema data model.




Navigation: Provide multi-page dashboard navigation.

💡 3. HR Dashboard Insights

Page	Purpose	Key Insights	Recommendations
1. Employee Overview	
Show employee distribution by travel, departments, gender, marital status, overtime, and total salary.

Technology has the highest employee count; Married employees are the largest group (624); 72% do not work overtime.

Evaluate workload for departments with overtime levels; Enhance support programs for married employees.

2. Salary & Department Analytics	
Analyze salaries by gender, job role, yearly trend, and department.

Highest paying roles: Sales Executive (38M), Engineering Manager (21M); Salaries increased steadily toward 2020–2022.

Improve salary competitiveness in HR; Maintain investment in high-value roles such as Sales Executive.

3. Distance, Ratings & Allowances	
Show distance from home, employee and manager ratings, and transportation allowances.

HR employees live closest to work (21.7 KM); HR shows the biggest gap between self-rating and manager-rating.

Investigate rating gaps to reduce bias; Strengthen performance evaluation policies.

6. Attrition Overview	
Analyze attrition by department, salary range, and employee status.

Attrition Rate = 16%; Lowest salary range (0–100K) has the highest attrition (20%); Sales has the highest attrition rate (21%).

Increase salaries for the lowest ranges; Improve work conditions in Sales to reduce turnover; Conduct structured exit interviews.

🛠️ 4. Implementation (Execution)

4.2 Environment & Tools Used

Power BI Desktop: For data cleaning, modeling, and dashboard creation.


Power Query: Data transformation and cleaning.


DAX (Data Analysis Expressions): Creating measures and calculated columns.


Original Data Source: Excel / CSV Files (HR dataset).


4.3 Data Preparation & Cleaning
Removal of duplicates, incorrect values, and missing fields.

Standardizing data types (dates, categorical values, IDs).

Creating new calculated fields, such as attrition rate.

4.4 Data Modeling
Establishing relationships between fact and dimension tables.

Structuring the data model into a star schema for efficiency.

Building DAX measures to calculate KPIs, including:

Employee count 

Attrition count 

Attrition rate

📋 5. Final Presentation & Reports

5.2 Technical Documentation

Data Source: HR dataset (CSV/Excel).


Data Processing Layer: Power Query.


Data Model Layer: Fact and dimension tables with defined relationships.


Visualization Layer: Interactive Power BI Dashboard.

Database Schema (Star Schema):


Dimension Tables: Employees, Departments, Job Roles, Salary Levels.


Fact Table: Employee records including attrition status, performance, salary, etc..

API Documentation: No external APIs were integrated into this project. All data was processed locally within Power BI.

5.1 User Manual (How to Use the Dashboard)
Use the slicers on the left panel to filter the data by department, age, salary slab, or job role.


Hover over charts for detailed tooltips and insights.


Navigate through multiple dashboard pages to explore attrition, employee demographics, and KPIs.

Use export options if the user needs PDF or image versions of the charts.
