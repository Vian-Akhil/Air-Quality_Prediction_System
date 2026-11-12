# Air-Quality_Prediction_System
# PG191 AIML Project
# Beijing Air Quality Prediction Pipeline

## Overview
This project focuses on building a complete **data processing and analysis pipeline** for the Beijing Multi-Site Air Quality dataset. The pipeline integrates **data preprocessing, target creation, feature selection, dimensionality reduction (PCA), and exploratory data analysis (EDA)** into a single workflow. The output is a ready-to-use dataset for machine learning tasks predicting Air Quality Index (AQI) categories.

---

## Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Beijing+Multi-Site+Air-Quality+Data)
- **Period:** March 2013 – February 2017
- **Key Features:** PM2.5, PM10, SO2, NO2, CO, O3, TEMP, PRES, DEWP, RAIN, WSPM, WD (wind direction)
- **Target Variable:** `AQI_Category`
  - 0 → Good (0–50)
  - 1 → Moderate (51–100)
  - 2 → Unhealthy (101+)

---

## Group Member Roles
- **Member 1:** Data cleaning, outlier handling, missing value treatment
- **Member 2:** Target creation, encoding categorical features
- **Member 3:** Feature selection, PCA, EDA visualizations
- **Member 4:** Integration into group pipeline, final CSV preparation

---
