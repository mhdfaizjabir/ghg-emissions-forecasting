#  GHG Emissions Forecasting with ARIMA & Random Forest

A data science project focused on forecasting global greenhouse gas (GHG) emissions using traditional time series models and machine learning.  
We focus on the **top 5 emitting countries** (China, India, Russia, United States, Brazil) and **Qatar** — a high-emissions-per-capita country.

---

##  Objective

- Analyze global GHG emissions data (1990–2021)
- Engineer features such as **growth rate**, **region**, and **lags**
- Forecast future emissions (next 5 years)
- Compare forecasting models: **ARIMA vs Random Forest**
- Provide country-specific insights (with Qatar as a focus)
- Visualize emission trends and perform clustering

---


##  Models Used

### 1. ARIMA (1,1,1)
- Traditional time series model
- Learns from full historical trend
- Best for stable countries (e.g., Qatar)
- Error: MAPE ≈ 6.3%

### 2. Random Forest with Lag Features
- ML model using `Lag_1`, `Lag_2` (previous emissions)
- Learns short-term behavior for better accuracy
- Error: MAPE ≈ 2.0%

---

##  Key Features

- `Growth_Rate`: Year-over-year change in emissions
- `Region`: Continent mapped to each country
- `Lag_1`, `Lag_2`: Past emissions used for forecasting
- Clustering (K-Means): Country grouping by emissions & trends

---

##  Visualizations

- Line plots (country-wise emissions trends)
- Bar charts (top emitters)
- Radar charts (1990 vs 2000 vs 2021)
- Forecast graphs (2022–2026)
- Heatmaps, boxplots
- Feature importance analysis

---

##  Use Case

> Countries need short-term forecasting tools to make **data-driven environmental decisions**.

This project helps:
- Governments monitor emission risks
- Policymakers identify emerging polluters
- NGOs prioritize regions needing green investments

---

