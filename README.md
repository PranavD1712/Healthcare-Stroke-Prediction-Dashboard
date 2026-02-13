\# Healthcare Stroke Risk Analysis (SQL + Excel Dashboard)



This project analyzes stroke risk patterns using a healthcare dataset of \*\*5,110 patient records\*\*.  

The analysis was performed using \*\*SQL for data querying\*\* and \*\*Microsoft Excel (Pivot Tables + Slicers)\*\* for dashboard creation.



---



\## Objective:



To explore stroke occurrence patterns across different demographic and health factors and present insights through an interactive Excel dashboard.



---



\## Tools Used:



\- MySQL (Data aggregation \& analysis queries)

\- Microsoft Excel

&nbsp; - Pivot Tables

&nbsp; - Pivot Charts

&nbsp; - Slicers

&nbsp; - KPI Calculations



---



\## Dataset Overview:



\- Total Records: 5,110 patients

\- Target Variable: `stroke` (0 = No Stroke, 1 = Stroke)

\- Key Features Used:

&nbsp; - Age

&nbsp; - Gender

&nbsp; - Smoking Status

&nbsp; - Hypertension

&nbsp; - BMI

&nbsp; - Glucose Level



---



\## Analysis Performed:



\### Stroke Distribution by Age Group

\- Created Age Groups (Child, Middle Age, Senior, Young Adult)

\- Calculated total patients and stroke cases per group

\- Computed stroke rate percentage



\###  Smoking + Hypertension Risk Matrix

\- Analyzed stroke occurrence by smoking status

\- Compared risk across hypertension categories

\- Identified highest risk combination



\###  KPI Metrics Displayed

\- Stroke Rate %

\- Total Senior Patients

\- Highest Risk Group %



\###  Interactive Filtering

\- Added slicers for:

&nbsp; - Age Group

&nbsp; - Smoking Status

&nbsp; - Gender

\- Enabled dynamic dashboard updates



---



\##  Key Insights:



\- Senior patients represent approximately 30% of the total population.

\- Smoking combined with hypertension shows the highest stroke risk.

\- Stroke distribution varies significantly across age groups.

\- Interactive slicers allow demographic-based analysis.



---



\## Dashboard Preview:



!\[Dashboard Preview](dashboard/dashboard\_preview.png)



---



\##  What This Project Demonstrates:



\- SQL aggregation and grouping queries

\- Risk percentage calculation

\- Pivot-based data analysis

\- Dashboard structuring and KPI reporting

\- Data storytelling using Excel



---



\## Repository Structure:



```

Healthcare-Stroke-Risk-Analysis

│

├── data

│   ├── raw

│   │   └── StrokeData.csv

│   │

│   └── processed

│       └── StrokeData\_Cleaned.xlsx

│

├── sql

│   ├── 01\_data\_exploration.sql

│   ├── 02\_risk\_analysis.sql

│   └── 03\_kpi\_queries.sql

│

├── dashboard

│   ├── Healthcare\_Stroke\_Dashboard.xlsx

│   └── dashboard\_screenshot.png

│

└── README.md

```



---



\## Conclusion



This project demonstrates how healthcare data can be analyzed using SQL and visualized through Excel dashboards to identify stroke risk patterns across demographic and health-related factors.



