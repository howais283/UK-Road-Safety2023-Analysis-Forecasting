# UK-Road-Safety2023-Analysis-Forecasting

**Data-driven analysis and predictive modelling of UK road accidents using Apriori association rules, clustering, and time series forecasting (ARIMA/ARMA).**  
The project identifies risk patterns, accident hotspots, and regional trends to support evidence-based road safety strategies.

---

## 🔍 Project Overview

This project explores road traffic accident data across the UK using advanced data mining and statistical modelling techniques. The dataset includes over 1.9 million records across four relational tables (accident, casualty, vehicle, and LSOA). The primary objectives include:

- Identifying high-risk patterns using the Apriori algorithm  
- Geospatial clustering to detect regional accident hotspots  
- Time series forecasting (ARIMA/ARMA) for predicting weekly and daily accident trends  
- Data cleaning & preprocessing of complex, incomplete, and encoded records  

---

## 📈 Key Highlights

- Achieved **RMSE of 47.77** on regional forecasts and **0.0 RMSE** on select local forecasts  
- Discovered frequent accident patterns under **favorable conditions** (dry roads, daylight, fine weather), suggesting human error as a key factor  
- Identified and visualized **high-incident zones** in Kingston upon Hull using clustering algorithms  
- Provided **policy and safety recommendations** based on location, timing, and accident type analyses  

---

## 🎯 Impact

This project supports **data-driven decision-making** in urban planning, traffic enforcement, and road infrastructure improvements. Insights from this work can assist government agencies in deploying timely, evidence-based safety interventions.

---

## 📂 Contents

- `notebooks/`: Jupyter Notebook with code and results  
- `reports/`: Final report with problem statement, methodology, and results  

---

## 📊 Dataset

The dataset used is the UK Accident Database, available for download [here](https://drive.google.com/file/d/1itlhKJyJnnfJYP-c6t5TwJPwL3ADqJ-f/view?usp=sharing).

---

## 🛠 Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Apriori (mlxtend)  
- Statsmodels (ARIMA/ARMA)  
- Scikit-learn (Clustering)  
- SQLite for relational data queries  

---
