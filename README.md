# 🚧 Road Accidents and Weather Analysis – Victoria, Australia

This project explores the relationship between **weather conditions** (e.g. temperature, precipitation, and heatwaves) and **road traffic accidents** in Victoria, Australia. It applies statistical analysis and predictive modeling to help inform **emergency services** planning and response.

## 📌 Project Overview

- **Course**: SIT741 – Data Wrangling & Visualisation
- **Language**: R
- **Focus**: Modeling road accidents using weather data and statistical techniques

## 🎯 Objectives

- Clean and tidy accident and weather data
- Fit and compare statistical distributions to accident counts
- Integrate weather data (including Excess Heat Factor – EHF)
- Build predictive models (Linear Models, GAMs)
- Assess model performance using residuals and AIC
- Reflect on model design, missing values, and overfitting

## 🗂️ Project Structure

- `project_report.Rmd`: Full R Markdown report including code, analysis, and visualizations
- `car_accidents_victoria.csv`: Raw accident data (BI-generated, two-row header)
- `weather_data.csv`: External weather data sourced from NOAA or Bureau of Meteorology
- `README.md`: Project documentation

## 📊 Key Features

- ✅ Data cleaning (multi-header CSV, data types, missing values)
- 📈 Distribution fitting: Poisson, Negative Binomial, Gamma
- 🌡️ EHF calculation based on NOAA data
- 📉 Model fitting: Linear Regression, Generalized Additive Models (GAMs)
- 📊 AIC-based model comparison and residual diagnostics

## 🛠 Tools & Libraries

- `tidyverse` – Data manipulation and visualization
- `fitdistrplus` – Distribution fitting
- `mgcv` – Generalized additive models
- `lubridate` – Date handling
- API integration for weather data (NOAA)

## 📈 Example Output

- Time series plots of accidents and weather trends
- EHF visualization
- Model comparison tables
- Residual plots and AIC scores



