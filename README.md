# Hospital Emergency Room Dashboard (HERD) - Excel Project
This project delivers a comprehensive, interactive Hospital Emergency Room Dashboard (HERD) built entirely in Microsoft Excel. The dashboard is designed to provide hospital stakeholders, administrators, and emergency room managers with real-time, actionable insights into ER operations, patient flow, and service quality.

## Purpose
The primary purpose of this dashboard is to improve operational efficiency, reduce wait times, and enhance overall patient experience by facilitating data-driven decision-making.

## Dataset Used
- <a href="https://github.com/Anuj122Mishra/Hospital_Emergency_Room_Dashboard/blob/main/Hospital_Emergency_Room_Data.csv.xlsx">Dataset</a>

##  Key Features and Technologies Used
### Interactive Design:
The dashboard features a clean, professional, and dark-themed design with interactive monthly selectors (January to December) and a year selector (2023 vs. 2024), allowing users to dynamically filter and analyze performance data.

### Key Performance Indicators (KPIs):
The dashboard prominently tracks three crucial KPIs to monitor ER performance:

Number of Patients: Total volume of patients served.

Average Wait Time: Measure of efficiency and patient service delivery.

Patient Satisfaction Score: Metric for the quality of service.

### Data Transformation with Power Query:

Utilized Power Query (Get & Transform) for robust data import, cleaning, and quality checks. This ensures the source data is consistently structured and error-free before analysis.

### Advanced Calculation with DAX:

Leveraged the DAX (Data Analysis Expressions) formula language within the Excel Data Model (Power Pivot) to create complex measures and calculated columns, enabling advanced analysis.

### Visual Data Storytelling:
The dashboard incorporates various visualization types to present insights:

Patient Attended Status: Pie chart showing the percentage of patients attended On Time vs. those experiencing a Delay.

Gender Wise Analysis: Pie chart illustrating the male vs. female patient ratio.

Number of Patients by Age Group: Bar chart providing a breakdown of patient volume across different age demographics (0-09, 10-19, etc.).

Department Referral Analysis: Bar chart showing the volume of patients referred to specific departments (e.g., General Practice, Orthopedics, Cardiology).

Admission Status: Table and bar chart displaying the split of patients Admitted vs. Not Admitted.

## Process:

Data Acquisition: Imported raw patient data into the Excel environment.

Power Query Transformation: Used Power Query for robust data cleaning, standardization, and quality checking.

Data Modeling: Loaded cleaned data into the Excel Data Model (Power Pivot) and defined necessary table relationships.

DAX Calculations: Created DAX measures to calculate the core KPIs.

Dashboard Design: Structured the layout and integrated dynamic visuals (Bar charts, Pie charts, KPI cards).

Interactivity: Implemented Slicers (Month, Year) to enable dynamic filtering and analysis of the data.

Review: Tested all visualizations and calculations for accuracy and responsiveness.

## Dashboard Interaction - <a href = "https://github.com/Anuj122Mishra/Hospital_Emergency_Room_Dashboard/blob/main/HERD.png">View Dashboard</a>

## Dashoard: 
<img width="1425" height="640" alt="HERD" src="https://github.com/user-attachments/assets/a0de10e8-afdd-475a-b8f1-202f72473f4f" />

##  Dashboard Impact and Use Cases:

By visualizing key metrics and trends, this HERD enables stakeholders to:

Monitor Performance: Quickly assess current operational status against targets.

Identify Bottlenecks: Pinpoint specific areas contributing to delays (e.g., peak age groups, high-demand referral departments, or specific months).

Allocate Resources: Make informed decisions on staffing levels, equipment needs, and scheduling based on patient volume and wait time trends.

Improve Quality: Track satisfaction scores to validate service improvements and prioritize areas for staff training.
