# -Healthcare-Provider-Analytics-Dashboard-
This Power BI project analyzes healthcare operations data to monitor patient visits, departmental efficiency, and insurance coverage trends
The dashboard enables healthcare management to:

Track patient admission and discharge trends

Monitor emergency vs scheduled visits

Analyze department performance

Evaluate insurance coverage distribution

Identify patient demographic patterns

The goal is to support data-driven decisions to improve operational efficiency and patient care quality

 * 📊 Dataset Details


Source: Kaggle

Domain: Healthcare Operations & Patient Visits

Data Model Type: Star Schema

Fact Table: Visits

Dimension Tables:

Patients

Providers

Departments

Diagnoses

Procedures

Insurance

* 🎯 Problem Statement


Healthcare management needs visibility into:

Patient flow trends over time

Emergency visit frequency

Department workload distribution

Insurance coverage impact

* Steps I Performed


1️⃣ Data Cleaning (Power Query)


Standardized date columns

Ensured proper data types

Removed inconsistencies

Structured Date table


2️⃣ Data Modeling


Designed a Star Schema

Created one-to-many relationships

Built a centralized fact table (Visits)

Connected Date table for time intelligence


3️⃣ DAX Development


Created KPIs and calculated measures

Built time intelligence calculations

Developed percentage and ratio metrics

* Key Insights 🔍

  
- Emergency visits can significantly impact department workload
- Insurance coverage affects patient distribution
- Demographic segmentation enables targeted operational improvements
- Time-based trends help forecast resource demand


* 🛠 Tools & Technologies Used


Microsoft Power BI Desktop

Power Query

DAX (Data Analysis Expressions)

Data Modeling (Star Schema Design)

Time Intelligence

Kaggle Dataset

Cities

DateTable
