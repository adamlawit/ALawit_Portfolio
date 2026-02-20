# Electricity Demand Analysis & Forecasting

### Author: Adam Lawit  

---

## Overview

This project develops multiple models to forecast hourly electricity demand using CAISO data.  
The models are designed to be flexible, allowing evaluation over any custom time window within the dataset.

---

## Objectives

- Capture daily seasonality (24-hour cycles)  
- Compare baseline and advanced forecasting models  
- Enable flexible evaluation over user-defined time periods  
- Analyze forecast accuracy by hour of day  

---

## Data

- Source: CAISO (California Independent System Operator)  
- Frequency: Hourly  
- Period: Jan 2024 – Dec 2025  
- Target: Electricity Demand (MW)  

---

## Models

- Baselines (Yesterday Naive & Last-Week Naive)  
- Prophet  
- SARIMAX  
- Hybrid (Last-Week Baseline + Prophet)  

---

## Tools & Technologies

- Python (Pandas, NumPy)  
- Statsmodels (SARIMAX)  
- Prophet  
- Scikit-learn  
- Matplotlib  

---

## Key Takeaway

This project demonstrates how multiple forecasting approaches can be implemented and evaluated flexibly to capture electricity demand patterns, highlighting seasonality and model comparison in a real-world dataset.
