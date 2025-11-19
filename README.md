# MASACHUSETTES-GENERAL-HOSPITAL-ANALYSIS
Power BI project revealing key patterns in hospital utilization, costs, and patient readmissions to support data-driven healthcare decisions.


## Table of Contents
1. [Introduction](#1-introduction)
2. [Project Description](#2-project-description)
3. [Project Aim](#3-project-aim)
4. [About the Dataset](#4-about-the-dataset)
5. [Tools Used](#5-tools-used)
6. [Importing the Dataset](#6-importing-the-dataset)
7. [Data Cleaning & Transformation](#7-data-cleaning--transformation)
8. [Data Modeling](#8-data-modeling)
9. [Data Analysis](#9-data-analysis)
10. [Data Visualization](#10-data-visualization)
11. [Insights and Reccomendations](#11-Insights-and-Reccommendations)
12. [Conclusion](#12-conclusion)
13. [Contact Information](#13-contact-information)


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
  - Average LOS (Days) 
  - Average Cost per Encounter  
  - Average Cost per Procedure  
  - Patients Payer Coverage  
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

**Dashboards:**

![Dashboard 1 Overview]  ![WhatsApp Image 2025-11-07 at 21 46 53_ff731c60](https://github.com/user-attachments/assets/787ebe60-5b3d-4ba7-af14-8fbfc088d3bf)

![Dashboard 2 Demographics] ![WhatsApp Image 2025-11-07 at 21 46 40_269a0140](https://github.com/user-attachments/assets/78e2ee31-923f-4d0a-8bd2-258db033c5ae)

---

## 11 Insights & Recommendations

---

### **Insight 1**
**Insight:**  
Urgent care and inpatient encounter classes have the highest readmission rates (74.11% and 71.81% respectively).

**Recommendation:**  
Implement post-discharge follow-up programs and improve discharge planning for urgent and inpatient patients to minimize preventable readmissions.

**Stakeholder:**  
Hospital Management and Clinical Care Teams

---

### **Insight 2**
**Insight:**  
The total claim cost is **$101.5M**, with urgent care clinic procedures (**$23.3M**) and prenatal visits (**$11.9M**) being the top cost drivers.

**Recommendation:**  
Conduct a cost-benefit analysis of high-expense procedures, streamline billing processes, and explore telemedicine for follow-up visits to reduce total costs.

**Stakeholder:**  
Finance Department and Medical Operations Team

---

### **Insight 3**
**Insight:**  
Medicare (**$25M**) and Medicaid (**$9M**) account for the majority of total claims.

**Recommendation:**  
Strengthen payer relationships through improved claim accuracy, timely submission, and regular performance review meetings to minimize reimbursement delays.

**Stakeholder:**  
Claims Management and Finance Teams

---

### **Insight 4**
**Insight:**  
Cities such as **Hull (91.36%)** and **Weymouth (79.25%)** have disproportionately higher readmission rates compared to other areas.

**Recommendation:**  
Investigate healthcare delivery quality in these locations and introduce telehealth or outreach programs to support follow-up care.

**Stakeholder:**  
Regional Health Coordinators and Quality Assurance Unit

---

### **Insight 5**
**Insight:**  
Readmission rates are evenly distributed by gender (Male: 49.32%, Female: 50.68%) and marital status, but the **Hispanic group (63.53%)** shows higher readmission counts.

**Recommendation:**  
Introduce community-specific health education and culturally competent care initiatives to address demographic disparities.

**Stakeholder:**  
Public Health Department and Community Outreach Team

---

### **Insight 6**
**Insight:**  
Readmission rates vary significantly across counties, with **Plymouth County (80.11%)** being the highest.

**Recommendation:**  
Develop county-level intervention programs focusing on readmission prevention and enhanced coordination between hospitals and primary care providers.

**Stakeholder:**  
Hospital Administration and County Health Boards


---

## 12. Conclusion
The analysis provides actionable insights into hospital utilization, claim costs, and readmission patterns. Multiple DAX measures and interactive dashboards enable dynamic exploration of patient and procedural data, supporting hospital management in improving care quality and operational efficiency.

---

## 13. Contact Information
- **LinkedIn:** [www.linkedin.com/in/kaosarat-nurudeen-89471a2a4](https://www.linkedin.com/in/kaosarat-nurudeen-89471a2a4)  
- **Email:** kaosaranurudeen513@gmail.com

