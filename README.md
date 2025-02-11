### [Healthcare EDA with Python](https://www.kaggle.com/code/benitoitelewuver/healthcare-eda-with-python?scriptVersionId=221878175)

### Healthcare Dataset Overview
This dataset is designed to support the analysis of patient behavior, healthcare trends, and resource utilization in a hospital setting. It aligns with the responsibilities, goals, and processes outlined in the project structure.

## Responsibilities
As the data analyst for this project:

Analyze patient and hospital resource data

Identify and visualize key healthcare trends

Develop ETL processes for data integration

Create and maintain a healthcare dashboard

Generate insights and recommendations for improving patient care and resource allocation

## Project Goals
Visualize patient behavior and resource utilization through key metrics.

Identify and track healthcare trends over time (e.g., admission rates, diagnosis trends, resource usage).

Segment patients based on demographics, diagnosis, and treatment plans.

Provide actionable insights for improving hospital operations and patient outcomes.

## Data Sources
Internal Hospital Database: Primary source for patient records, admissions, diagnoses, treatments, and billing data.

Third-Party Healthcare Data: Supplementary data on regional healthcare trends, demographics, and disease prevalence.

## Data Analysis Process
**Data Extraction**: Extract data from internal hospital systems and third-party sources.

**Data Cleaning and Transformation**: Handle missing values, standardize formats, and merge datasets.

**Exploratory Data Analysis (EDA**): Explore patient demographics, admission trends, and resource utilization.

**Statistical Analysis**: Identify correlations, trends, and anomalies in the data.

**Visualization Creation**: Develop visualizations to represent key metrics and trends.

**Insight Generation**: Derive actionable insights for improving hospital operations and patient care.

## Key Deliverables
**Cleaned and Transformed Dataset**: A structured dataset ready for analysis.

**Interactive Dashboard**: A dashboard with visualizations for key metrics (e.g., admission trends, resource utilization, patient segmentation).

**Detailed Analysis Report**: A report summarizing findings, trends, and recommendations.

**Documentation of ETL Processes**: Documentation of data extraction, cleaning, and transformation steps.

**Presentation of Findings**: A presentation to stakeholders highlighting key insights and recommendations.

## Collaboration
This project requires close collaboration with:

**IT Department**: For data access, infrastructure, and ETL pipeline setup.

**Medical Staff**: For understanding patient care processes and validating insights.

**Hospital Administration**: For refining requirements and implementing recommendations.

**Third-Party Data Providers**: For integrating supplementary healthcare data.

## Dataset Structure
The dataset is divided into four main csv file, each focusing on a specific aspect of healthcare operations:

# 1. Patients Dataset (patients.csv)
This dataset contains information about patients, including demographics, admission details, diagnosis, and treatment plans.

**Columns:**
**Patient_ID**: Unique identifier for each patient.

**Name**: Name of the patient.

**Age**: Age of the patient.

**Gender**: Gender of the patient (M/F).

**Blood_Type**: Blood type of the patient.

**Admission_Date**: Date of admission to the hospital.

**Discharge_Date**: Date of discharge from the hospital (may contain missing values).

**Diagnosis**: Diagnosis of the patient.

**Treatment_Plan**: Treatment plan prescribed for the patient.

# 2. Hospital Resources Dataset (hospital_resources.csv)
This dataset tracks the utilization of hospital resources over time.

**Columns:**
**Date**: The date of resource utilization.

**Bed_Occupancy_Rate**: Percentage of beds occupied in the hospital.

**ICU_Available**: Number of available ICU beds.

**MRI_In_Use**: Number of MRI machines in use.

**Ventilators_In_Use**: Number of ventilators in use.

**Xray_In_Use**: Number of X-ray machines in use.

# 3. Medical Records Dataset (medical_records.csv)
This dataset contains detailed medical records for patients, including prescribed medications, tests ordered, and test results.

**Columns:**
**Patient_ID**: Unique identifier for each patient.

**Date**: Date of the medical record entry.

**Prescribed_Medication**: Medication prescribed to the patient.

**Test_Ordered**: Test ordered for the patient.

**Test_Result**: Result of the test (e.g., Normal, Abnormal, Critical).

# 4. Billing Dataset (billing.csv)
This dataset contains billing information for patients, including total bill amounts, insurance coverage, and out-of-pocket expenses.

**Columns**:
**Patient_ID**: Unique identifier for each patient.

**Billing_Date**: Date of the billing entry.

**Total_Bill**: Total bill amount.

**Insurance_Coverage_Percentage**: Percentage of the bill covered by insurance.

**Out_of_Pocket_Expenses**: Amount paid out-of-pocket by the patient.


### 1. Key Findings and Trends
### 1.1 Patient Demographics and Health Data
**Age Distribution:** The dataset includes patients ranging from 28 to 81 years old, with a significant number of elderly patients.

**Gender Distribution**: The sample shows a mix of male and female patients.

**Common Diagnoses**: Pneumonia, diabetes, hypertension, and flu are among the common diagnoses.

**Treatment Plans**: Include observation, surgery, lifestyle changes, and medication.

# 1.2 Hospital Resource Utilization
**Bed Occupancy Rate:** Ranges from 85.80% to 91.52%, indicating high utilization of hospital beds.

**ICU Availability:** Varies between 7 and 19 beds, with some dates showing higher demand.

**MRI and Ventilator Usage:** MRI usage ranges from 4 to 9, while ventilator usage ranges from 3 to 8, indicating fluctuating demand for these resources.

**X-ray Usage**: Ranges from 1 to 10, with some dates showing peak usage.

# 1.3 Medical Records
Prescribed Medications: Various medications are prescribed, with dosages typically around 500mg.

**Tests Ordered**: Common tests include MRI, ECG, blood tests, and urinalysis.

**Test Results:** Results range from normal to critical, indicating varying severity of patient conditions.

# 1.4 Billing Information
**Total Bill**: Ranges from 1,461 to 1,461to4,657, with significant variation in costs.

**Insurance Coverage:** Coverage percentages range from 61.53% to 93.88%, with out-of-pocket expenses ranging from 
126.68 to 126.68to1,789.81.

# 2. Data Quality and Missing Values
**Patients Table:** 116 missing discharge dates, indicating some patients are still admitted or data is incomplete.

**Hospital Resources, Medical Records, and Billing Tables**: No missing values, indicating complete data for these tables.

# 3. Trends and Insights
**High Bed Occupancy:** The hospital frequently operates near full capacity, suggesting a need for additional resources or better resource management.

**Variability in Resource Usage:** MRI and ventilator usage show significant variability, indicating fluctuating demand that could benefit from predictive modeling to optimize resource allocation.

**Common Diagnoses**: Pneumonia and diabetes are prevalent, suggesting a focus on respiratory and chronic disease management.

**Billing Variability**: High variability in billing amounts and insurance coverage indicates a need for standardized billing practices and potential financial assistance programs for patients with high out-of-pocket expenses.

### 4. Recommendations
**Resource Optimization**: Implement predictive analytics to forecast demand for ICU beds, MRI, and ventilators to optimize resource allocation and reduce wait times.

**Patient Management**: Focus on early intervention and management of chronic conditions like diabetes and hypertension to reduce hospital admissions.

**Data Completeness**: Address missing discharge dates in the Patients table to ensure accurate tracking of patient stays and resource utilization.

**Financial Assistance**: Develop programs to assist patients with high out-of-pocket expenses, potentially reducing financial stress and improving patient outcomes.

**Standardized Billing**: Review and standardize billing practices to reduce variability and ensure fair billing across all patients.

### 5. Conclusion
The dataset provides valuable insights into patient demographics, hospital resource utilization, medical treatments, and billing practices. By addressing the identified trends and data quality issues, the hospital can improve patient care, optimize resource usage, and enhance financial management. Predictive analytics and targeted interventions could further enhance operational efficiency and patient outcomes.

