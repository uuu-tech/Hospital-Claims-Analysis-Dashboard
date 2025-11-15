# Hospital-Claims-Analysis-Dashboard


## Project Overview

This Power BI dashboard provides an analytical overview of hospital claims data, focusing on patient demographics, insurance coverage, encounter classes, claim costs, and re-admissions. The goal is to surface healthcare service patterns and support decision-making across hospitals and insurance providers.

---

##  Tools and Technologies

- **Power BI Desktop** – Report design & visual interactivity  
- **Power Query** – ETL for data shaping and cleansing  
- **DAX** – Measures for KPIs and breakdowns  
- **Git + GitHub** – Repository and versioning  

## Dataset Description

The dataset includes:
- Demographic attributes: race, age group, gender  
- Encounter-related metrics: time spent, readmission count  
- Claim financials: cost, coverage, and total encounter amount  
- Service classification: outpatient, inpatient, emergency, etc.  
- Year-wise trends and insurance details

## DAX Measures Developed

- Total Encounter Amount  
- Average Cost Per Visit  
- Readmitted Patients  
- Avg Time Spent  
- Total Claim Cost  
- Payer Coverage  
- Gender-wise Patient Count

##  Dashboard Structure
### Executive Summary

Key metrics include:
- Total Patients: **974**
- Avg Cost per Visit: **$3.64K**
- Total Encounter Amount: **$101.51M**
- Procedures Covered: **48K**
- Insurance Companies: **10**
- Avg Time Spent: **7.25 hours**
- Readmitted Patients: **854**

### Demographic Insights

- **Claims by Race**: White population accounts for 63M in claims, followed by Black (23M), Native and Asian (~7M)
- **Claims by Age Group**: Highest from **Very Old** age group (71M), followed by **Mature** and **Mid**

### Financial Insights

- Annual trends show a peak in claims during 2014 (~12M)  
- Total Payer Coverage across all years: **~31 Cr**  
- Outpatient and Urgent Care top the list in **claim cost** and **coverage**

## Key Insights

- Senior populations contribute the majority of claim value  
- Balanced gender distribution across patient records  
- Outpatient and urgent care services dominate costs  
- Payer coverage aligns with claim trends over time  
- Avg time spent per visit is ~7.25 hours 
