# 🚕 Taxi Demand Prediction (2018)

## Project Overview
This project was developed as part of the Data Science Bootcamp (TripleTen).  
The goal is to forecast hourly taxi demand at airports using historical data, improving resource allocation for drivers during peak hours.

---

## Problem Statement
Airports face fluctuating passenger demand throughout the day, making it difficult for taxi services to allocate drivers efficiently. Predicting hourly demand allows for better scheduling and reduced passenger wait times.

---

## Dataset
- Source: Historical hourly taxi orders at airports (2018).  
- Size: ~4,400 records.  
- Features: Date, time, weather conditions, order counts.  
- Target: Number of taxi orders per hour.  

---

## Tech Stack
- **Languages/Libraries**: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, LightGBM  
- **Techniques**: Time series analysis, regression models, cross-validation  

---

## Key Results / KPIs
- Compared multiple models: **Linear Regression**, **Random Forest**, **LightGBM**.  
- Final model: **LightGBM** achieved **RMSE = 39.6**, outperforming project target (<48).  
- Improved prediction accuracy helps optimize driver availability during peak demand hours.  

---

## Visualisations
The project includes:
- Time series plots of taxi demand.  
- Demand distribution by day of week and time of day.  
- Model performance comparison (RMSE).  

---

## How to Reproduce
1. Clone the repository:
   ```bash
   git clone https://github.com/SantiagoPulidoH/prediccion-pedidos-taxi-2018.git
   cd prediccion-pedidos-taxi-2018
