# Maven-Analytics-July-Hospital-Challenge

This report is a part of the Data challenges held by Maven Analytics every month on their website.

## Challenge Objective

For the Maven Hospital Challenge, I'm playing the role of an Analytics Consultant for Massachusetts General Hospital (MGH).

I've been asked to build a high-level KPI report for the executive team, based on a subset of patient records. The purpose of the report is to give stakeholders visibility into the hospital's recent performance, and answer the following questions:

How many patients have been admitted or readmitted over time?

How long are patients staying in the hospital, on average?

How much is the average cost per visit?

How many procedures are covered by insurance?

**The Stakeholder:** The CEO of the hospital.

**Tools used:** Excel and Power BI

## About This Project

**Maven Hospital Challenge**

This project offers an in-depth analysis of patient encounters, procedures, and financial performance at Massachusetts General Hospital. Utilizing Power BI dashboards for data visualization, delivers valuable insights into key hospital metrics, including total encounters, procedures, patient demographics, and financial claims.

The analysis uncovers trends in patient encounters and procedures, identifies the most frequent and costly procedures, and examines the relationship between payer coverage and total claims. Additionally, it explores demographic factors such as age, race, and marital status that influence procedure frequency and hospital revenue. These findings are crucial for strategic planning, optimizing resource allocation, and enhancing patient care services at the hospital.

## 1. Patient Encounter Status and Financial Analysis

### Overview:

This dashboard provides a comprehensive view of patient encounters, procedures, financial claims, and patient demographics at Massachusetts General Hospital. Key metrics include total encounters, procedures, patients, claims, and the mortality rate.

### Key Metrics:

**- Total Encounters: 27,891**

**- Total Procedures: 47,701**

**- Total Patients: 974**

**- Total Claims: $102 million**

**- Mortality Rate: 15.81%**

### Patient Encounter and Procedures Trending:

**- Trend Analysis:** Patient encounters **peaked around 2014 with approximately 3.8K encounters**, followed by a decline and stabilization at around **2.2K to 2.4K encounters per year from 2015 onwards**. The **number of patients** undergoing procedures has remained stable, ranging from **82 to 448 patients per year.**

### Patient Class Analysis:

**- Ambulatory Patients:** Nearly 12.5K patients, indicating a high reliance on non-emergency, walk-in services.

**- Inpatient Encounters:** The low number of inpatient encounters could indicate efficient outpatient services reducing the need for hospital admissions.

### Revenue by Encounter Class:

**- Highest Revenue Generators:**

**- Ambulatory:** $15 million (covered) and $21 million (not covered)
 
**- Urgent Care:** $4 million (covered) and $19 million (not covered)
 
**- Outpatient:** $5 million (covered) and $9 million (not covered)
 
**- Lower Revenue Generators:** Emergency, inpatient, and wellness encounters generate significantly lower revenues.

### Claim Payers:

**- Top Payers:**

 **- Medicare: 24.28%**
 
 **- Medicaid: 16.31%**
 
 **- Humana: 3.49%**
 
 **- Anthem: 2.94%**
 
 **- No Insurance: 48.52% of claims are from patients without insurance.**
 
**- Coverage Analysis:** 37.85% of claims are covered by insurance.

### Top 100 Patients:

**- Services Received:**

 - Kimberly627: 1,380 encounters, 1,167 procedures (Renal dialysis)
 
 - Mariano761: 1,261 encounters, 713 procedures (Renal dialysis)
 
 - Shani239: 887 encounters, 694 procedures (Renal dialysis)
 
 - Other Notable Services: Electrical cardioversion and hospice care.
 
## 2. Patient Procedure Analysis

## Overview:

This dashboard focuses on the analysis of patient procedures, including the number of procedures, costly procedures, demographic breakdowns, and procedure frequency.

### Top 10 Procedures:

**- Most Frequent Procedures:**
 
 - Assessment of health: 4.6K
 
 - Hospice care: 4.1K
 
 - Depression screening: 3.6K

**- Costly Procedures (Average):**
 
 - Admit to ICU: $206K
 
 - Coronary artery bypass graft: $47K
 
 - Lumpectomy of the breast: $29K

### Procedures by Age Group:

- Age 90–99: 13.1K procedures

- Age 80–89: 11.5K procedures

- Age 70–79: 4.4K procedures

### Procedures by Race:

- White: 70.87%

- Black: 16.1%

- Asian: 8.45%

### Procedures by Ethnic Group:

- Hispanic: 81.57% of procedures

### Marital Status:

- Married Patients: 81.43% of procedures

## 3. Organizational Performance

### Overview: 

This dashboard evaluates the relationship between payer coverage and total claims, average coverage by gender, encounter classes, and revenue from encounters and procedures.

### Encounter Class Analysis:

- Average Hospital Stay (Hours):

  - Inpatient: 36.83 hours

  - Ambulatory: 9.48 hours

  - Outpatient: 5.88 hours

### Revenue by Encounter Class:

- Outpatient: Generates 9.578% of total revenue.

- Ambulatory: Generates 18.211% of total revenue.

## 4. Patient Outcomes

### Top 20 Procedures by Volume and Revenue:

### Key Observations:

**- Assessment of Health and Social Care:**

4.6K procedures, the most frequently performed procedure.

**- Hospice Care Service:** 

Generates the highest revenue, significantly peaking at around $36 million, despite having 4.1K procedures.

**- Depression Screening:** 

3.6K procedures performed.

**- Renal Disease Screening and Other Assessments:** 

Each with around 2.4K to 2.9K procedures.

**- Medication Reconciliation:** 

1.4K procedures, generating around $6 million in revenue.

**- Auscultation of Fetus:** 

1.1K procedures, with lower revenue.

**- Catheterization and Bone Density Scan:** 

Lower volumes (0.5K to 0.2K) and correspondingly lower revenue.

### Insight:

- The most frequent procedure is the Assessment of Health and Social Care, while Electric Cardioversion generates the highest revenue.

- There is a diverse range of procedures with varying volumes and revenue impacts, indicating a broad scope of services offered.
Class of Patients Encountered

### Key Observations:

- Ambulatory: 12.5K encounters, indicating heavy reliance on non-emergency, walk-in services.

- Outpatient: 6.3K encounters.

- Urgent Care: 3.7K encounters.

- Emergency: 2.3K encounters, indicating critical care services are a smaller portion.

- Wellness and Inpatient: 1.9K and 1.1K encounters respectively, the least number of encounters.

### Insight:

- The majority of patient encounters are ambulatory, suggesting efficient outpatient services that reduce the need for hospital admissions.

- Lower inpatient encounters indicate effective preventive care and outpatient management strategies.

### Number of Encounters per Hour Over the Week

### Heatmap Key Observations:

- Peak Hours: Highest encounters between 10:00 AM and 2:00 PM.

- Busiest Days: Monday and Wednesday show the highest total encounters at 4,441 and 4,535 respectively.

- Weekend Activity: Though lower than weekdays, Saturday and Sunday still see considerable activity.

### Insight:

- The hospital experiences the highest patient influx during the midweek, with Monday and Wednesday being the busiest.

- After midnight till morning is the peak period for patient encounters, indicating optimal times for staffing and resource allocation.
## Conclusion

The dashboards provide a comprehensive overview of patient encounters, procedures, financial claims, and organizational performance at Massachusetts General Hospital. Key insights include the high reliance on ambulatory services, significant revenue generation from prenatal and follow-up visits, and the positive correlation between payer coverage and total claims. This analysis can help the hospital in strategic planning and improving patient care services.
