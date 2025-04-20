# DS5110 IDMP: Exploring Crime Dynamics in Chicago: Patterns, Trends, and Insights


## Overview

This project explores crime patterns in Chicago between 2019 and 2025. We look at how crimes vary over time (days, months, years), where they tend to happen in the city, and how we can forecast future crime levels using machine learning and statistical methods.

This work was submitted as the final project for **DS5110: Introduction to Data Management and Preprocessing**.

---

## Project 

ds-5110-crime-dynamics-chicago/
│
├── notebooks/
│   └── DS5110_Final_Project_Chicago_Crime_Group_14.ipynb
│
├── Outputs/
│   ├── Analysis/
│   │   └── (all EDA/plots images)
│   ├── Forecasting/
│   │   └── (SARIMAX & XGBoost plots, predictions, etc.)
│   └── Clustering/
│       └── crime_hotspots_dbscan.html
│
├── README.md
├── LICENSE  (MIT)

---

## What We Did

### 1. **Trends Over Time**
- Explored how crime types change by time of day, month, and year
- Analyzed arrest rates and domestic vs. non-domestic incidents

### 2. **Forecasting Daily Crime**
- Cleaned the data to remove outliers and prepare it for modeling
- Used **SARIMAX** (a statistical time series model) to forecast daily crime
- Built a more flexible **XGBoost** model to capture short-term fluctuations

### 3. **Clustering Crime Hotspots**
- Applied **DBSCAN**, a spatial clustering algorithm, to find crime hotspots in Chicago
- Assigned the most common crime type to each cluster
- Created an interactive **Folium map** to visualize where and what types of crimes occur

---

## Key Takeaways

- Crime in Chicago follows predictable **daily and seasonal** trends  
- **Short-term fluctuations** are harder to predict, but XGBoost performed well  
- Crimes tend to **cluster in specific neighborhoods**, and certain types dominate in each area


