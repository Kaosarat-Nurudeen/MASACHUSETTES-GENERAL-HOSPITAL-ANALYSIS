# MASACHUSETTES-GENERAL-HOSPITAL-ANALYSIS
Power BI project revealing key patterns in hospital utilization, costs, and patient readmissions to support data-driven healthcare decisions.
## 1. Introduction
This project analyzes hospital patient encounters and readmissions data to uncover patterns in claim costs, payer contributions, and demographic influences on readmission rates. The insights support data-driven healthcare decision-making, helping hospitals optimize resource allocation and improve patient outcomes.

---

## 2. Project Description
The project covers data collection, cleaning, modeling, analysis, and visualization using Power BI. Interactive dashboards were created to address key hospital performance questions, such as total claims, encounter trends, readmission rates, and demographic patterns. The dashboards leverage multiple DAX measures to provide detailed insights for hospital management.

---

## 3. Project Aim
To analyze hospital patient data to identify trends in encounters, claim costs, and readmission patterns, providing actionable insights for healthcare stakeholders.

---

## 4. About the Dataset
- **Source:** Massachusetts Hospital internal records  
- **Rows/Columns:** 28,000 encounters, 974 patients, multiple columns including demographic, encounter, payer, procedure, and readmission details  
- **Key Fields/Columns:**  
  - Patient ID  
  - Encounter ID  
  - Encounter Type & Class  
  - Payer  
  - Procedure Codes  
  - Claim Cost  
  - Readmission Status  
  - Demographics: Gender, Race, Ethnicity, Marital Status, County, City  
  - Length of Stay (LOS)

---

## 5. Tools Used
- Power BI  
- Excel (for initial data review)  

---

## 6. Importing the Dataset
Imported hospital datasets into Power BI and cleaned using Power Query. Relationships between tables (encounters, payers, diagnoses, procedures) were created using encounter codes.

---

## 7. Data Cleaning & Transformation
- Removed duplicate entries  
- Fixed missing values in key columns  
- Standardized column names  
- Corrected data types (numeric for costs, categorical for encounter types)  
- Resolved many-to-many relationships between encounter and procedural data by creating unique keys

---

## 8. Data Modeling
- Multiple DAX measures were developed to calculate:  
  - Average Length of Stay (LOS)  
  - Average Cost per Encounter  
  - Average Cost per Procedure  
  - 16 Patients Payer Coverage  
  - Procedure Total Cost  
  - Readmissions Count  
  - Total Claim Costs  
  - Total Encounters  
  - Total Procedure Costs  
  - Total Procedures  
- These measures were used to summarize, filter, and analyze data dynamically in dashboards.  
- Relationships between tables were carefully modeled to ensure accurate aggregations across encounters, procedures, and payers.

---

## 9. Data Analysis
Key metrics analyzed:  
- Total patients and encounters  
- Claim costs by encounter type, procedure, and payer  
- Readmission rates by encounter class and demographics  
- Geographic distribution of readmissions  
- Procedure utilization and cost trends  

---

## 10. Data Visualization
**Dashboard/Page 1: Hospital Encounters and Claims Overview**  
- KPI Cards: Total Patients, Total Encounters, Total Claim Cost, Average LOS, Readmission Rate  
- Combo Chart: Encounters & Claim Cost over Time  
- Horizontal Bar Chart: Top Encounter Types by Claim Cost  
- Bar Chart: Top Payers  

**Dashboard/Page 2: Readmission Analysis by Demographics**  
- Bar Charts: Readmission Rates by Encounter Class  
- Donut Charts: Readmission Rates by Gender, Marital Status, Ethnicity, Race  
- Bar Charts: Readmission Rates by City & County  

---

## 11. Key Insights
- Total claim cost: $101.5M, with urgent care and prenatal visits contributing most  
- Medicare contributed $25M to claim costs, followed by Medicaid and Humana  
- Readmission rates highest for urgent care (74%) and inpatient encounters (71%)  
- Demographics: Hispanic patients had higher readmission rates (63.5%), White patients had highest racial readmission rates (65.5%), single patients slightly higher than married  
- Geographic hotspots: Hull City (91%) and Plymouth County (80%)  
- Procedural costs and utilization also contributed to overall claim cost insights  

---

## 12. Recommendations
- Prioritize follow-up care for high-risk encounter types (urgent care & inpatient)  
- Monitor Medicare and Medicaid-related costs and optimize resource allocation  
- Implement targeted interventions in Hull City and Plymouth County to reduce readmissions  
- Tailor healthcare programs considering demographic trends  
- Analyze procedural efficiency to optimize costs  
- Conduct patient education programs to reduce readmissions  
- Regularly update dashboards for continuous monitoring of claims and readmissions  
- Engage payers in collaborative programs to reduce unnecessary costs  

---

## 13. Conclusion
The analysis provides actionable insights into hospital utilization, claim costs, and readmission patterns. Multiple DAX measures and interactive dashboards enable dynamic exploration of patient and procedural data, supporting hospital management in improving care quality and operational efficiency.

---

## 14. Contact Information
- **LinkedIn:** [www.linkedin.com/in/kaosarat-nurudeen-89471a2a4](https://www.linkedin.com/in/kaosarat-nurudeen-89471a2a4)  
- **Email:** kaosaranurudeen513@gmail.com


