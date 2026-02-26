# 🚲 Urban Bike Share Demand Analysis & Forecasting

## 📌 Project Overview
The global shift toward eco-friendly transportation has led to explosive growth in the bike-sharing sector. This project provides a data-driven strategy for a major American city's bike-sharing network to predict usage patterns based on changing environmental and temporal conditions. The goal is to maximize operations, guarantee adequate bike availability during peak hours, and efficiently manage fleet maintenance.

## 🎯 Objectives
* **Exploratory Data Analysis (EDA):** Visualize and understand correlations between rental counts, weather conditions, and time of day.
* **Predictive Modeling:** Construct a Machine Learning model (Decision Tree Regressor) to forecast the number of bike rentals given specific daily and hourly conditions.
* **Actionable Insights:** Determine the essential factors that most strongly influence bike rental demand to optimize fleet deployment.

## 📊 Dataset Description
The dataset contains **1,029 historical records** with 15 columns, combining temporal and meteorological data. 
* **Target Variable:** `RENTALS` (number of bikes rented).
* **Temporal Features:** Seasons, Holidays, Months, Days of the Week, Hours.
* **Weather Features:** Temperature, Humidity, Wind Speed, Visibility, Dew Point Temperature, UV Index, Rainfall, Snowfall.

## 🛠️ Tech Stack
* **Language:** Python 3
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning & Statistics:** Scikit-Learn (`DecisionTreeRegressor`, `linear_model`), Statsmodels

## 📈 Key Insights & Business Recommendations
* **Temperature Thresholds:** Rentals drop significantly in extreme weather (avoided below 8°C and above 30°C). Optimum deployment temperature is between 15°C and 30°C.
* **Humidity Impact:** Higher humidity reduces rental demand due to rider discomfort. 
* **Peak Commute Windows:** Fleet deployment should be maximized on non-holidays during peak commute hours: **7:00 AM - 9:00 AM** and **5:00 PM - 7:00 PM**.
* **Seasonality:** Spring and Summer yield the highest demand, driven by a mix of standard commuting, leisure, and exercise.

## 🚀 How to Run
1. Clone the repository: `git clone https://github.com/yourusername/bike-rental-demand.git`
2. Install the required dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn statsmodels`
3. Open `A1_Jainam_Gogree_final.ipynb` in Jupyter Notebook or Google Colab.
4. Ensure `bike_rentals.xlsx` is in the correct directory and run the cells to view the analysis and model evaluation.
