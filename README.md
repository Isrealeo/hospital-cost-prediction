# 🏥 Hospital Treatment Cost Prediction

## Project Overview
This project uses machine learning to predict hospital treatment costs based on patient demographics, clinical conditions, and operational hospital data.

The goal is to identify key drivers of healthcare cost and build a predictive regression model.

---

## Problem Statement
Hospitals need to understand and predict treatment costs in order to:
- Improve resource allocation
- Optimize operational efficiency
- Identify high-cost drivers in patient care

This project builds a regression model to predict `total_cost_€`.

---

## Dataset Description
- 3,000 patient records
- 15 features
- Target variable: `total_cost_€`

### Feature Categories:
- Patient demographics (age, gender)
- Clinical conditions (chronic_condition, complications)
- Treatment factors (procedures_count, medication_count)
- Operational metrics (length_of_stay_days, admission_type, department)

---

## 📊 Power BI Dashboard

An interactive dashboard was created using Power BI to visualize hospital cost patterns and operational insights.

### Key Visual Insights:
- Cost distribution across departments
- Key drivers of hospital treatment cost
- Patient clinical intensity analysis
- Operational efficiency trends

### Dashboard Report

📄 [View Power BI Report](powerbi/hospital_dashboard.pdf)
---
## Machine Learning Models
Two regression models were used:

- Linear Regression (baseline model)
- Random Forest Regressor (feature importance analysis)

---

## Key Results
- Linear Regression achieved strong predictive performance on structured healthcare data
- Random Forest confirmed feature importance rankings
- Model demonstrated high interpretability due to structured feature relationships

---

## Key Cost Drivers
The most important factors influencing hospital treatment cost are:

- Length of stay (strongest driver)
- Number of procedures
- Medication usage

These variables reflect overall clinical workload and resource utilization.

---

## Key Insight
Hospital treatment cost is primarily driven by **clinical intensity and duration of care**, rather than patient demographics.

---

## Conclusion
This project demonstrates that hospital cost prediction can be effectively modeled using structured clinical and operational data.

It highlights how healthcare costs are strongly influenced by treatment complexity and hospital resource usage.

---

## Tools & Technologies
- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Google Colab / Jupyter Notebook
- Power BI

---

## Notebook
Full analysis is available in the Jupyter Notebook:
`Hospital_Cost_Project.ipynb`

Includes:
- Data cleaning
- Exploratory Data Analysis
- Feature engineering
- Machine learning models
- Evaluation metrics
- Feature importance analysis

---

## Author
NNWAMINOGBE ISREAL OHUNMAEHUNI

Data Science & Analytics Project
