# Healthcare-Data-Analysis

**Project Overview**

Healthcare is a data-intensive domain where analytics plays a critical role in improving patient outcomes, optimizing hospital operations, and understanding disease trends.In this project, I performed Exploratory Data Analysis (EDA) on a synthetic healthcare dataset that simulates real-world hospital data. The analysis focuses on uncovering patterns related to patient demographics, medical conditions, hospital performance, and billing insights.

**Objectives**
- Perform data cleaning and preprocessing
- Analyze patient demographics and medical conditions
- Explore hospitalization patterns and billing trends
- Visualize data to generate actionable insights
- Identify key healthcare trends
  
**Dataset Description**
The dataset contains 10,000 patient records with the following features:
- Demographics: Age, Gender, Blood Type
- Medical Info: Medical Condition, Medication, Test Results
- Hospital Details: Doctor, Hospital, Admission Type
- Financial Data: Billing Amount, Insurance Provider
- Dates: Admission & Discharge
  
**Data Cleaning & Feature Engineering**
- Converted date columns to datetime format
- Created a new feature: Days Hospitalized
- Removed irrelevant columns (Name, Room Number, etc.)
- Checked for null values and duplicates (none found)

**Key Analysis & Insights**

**Patient Demographics**
- Nearly equal distribution of male and female patients
- Most patients fall in the 18–30 age group

**Medical Conditions**
- Most common condition: Asthma
- Followed by: Cancer, Hypertension, Arthritis

**Gender-Based Insights**
- Females show slightly higher counts across most conditions
- Cancer is more prominent among females
- Hypertension is slightly higher among males

**Billing Analysis**
- Billing ranges from $1,000 to $49,995
- Top hospitals and doctors contribute significantly to total billing
- Example: Smith and Sons recorded the highest billing

**Hospitalization Trends**
- Most patients are hospitalized for short durations (1–30 days)
- Weak correlation between age, billing, and hospitalization duration

**Insurance & Medication**
- Cigna is the most common insurance provider
- Penicillin is the most frequently prescribed medication

**Visualizations**
The project includes:
- Histograms for numerical distributions
- Bar charts & pie charts for categorical data
- Correlation heatmap
- Comparative analysis plots (e.g., gender vs medical conditions)

**Key Findings**
- Healthcare data shows balanced gender distribution but varying condition prevalence
- Billing is not strongly correlated with age or hospital stay duration
- Certain hospitals and doctors contribute disproportionately to revenue
- Data-driven insights can help improve resource allocation and decision-making

**Future Improvements**
- Apply machine learning models for prediction (e.g., billing or length of stay)
- Perform time-series analysis on admissions
- Build an interactive dashboard (Power BI / Tableau)
- Use real-world datasets for deeper insights

**Conclusion**

This project demonstrates how EDA can uncover meaningful insights from healthcare data, enabling better understanding of patient trends, hospital operations, and financial patterns. It highlights the importance of data-driven decision-making in healthcare analytics.
