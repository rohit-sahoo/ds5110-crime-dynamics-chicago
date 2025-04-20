# DS5110 IDMP: Exploring Crime Dynamics in Chicago: Patterns, Trends, and Insights


## Overview

This project explores crime patterns in Chicago between 2019 and 2025. We look at how crimes vary over time (days, months, years), where they tend to happen in the city, and how we can forecast future crime levels using machine learning and statistical methods.

## Authors
This project was completed by Group 14

Course: DS5110 – Introduction to Data Management and Preprocessing

Team: 

[Aishwarya Umesh Honap](honap.ai@northeastern.edu )		

[Elif-Selma Yilmaz](yilmaz.el@northeastern.edu )	

[Rohit Sisir Sahoo](sahoo.ro@northeastern.edu)

## Data
The dataset is based on Chicago crime data (2019–2025).

**Download the Dataset from the API:**

[City of Chicago API URL](https://data.cityofchicago.org/resource/crimes.json?$limit=1600000&$offset=1)

OR 

**Download the data from One Drive**:

[chicago_crimes_2018_2025.csv](https://northeastern-my.sharepoint.com/:x:/g/personal/sahoo_ro_northeastern_edu/ESxGC3oVmaxKm8EOvMe68QwBsbUntDwv0q1agKqREQZQow?e=RTTHC)


## Project 
```
ds-5110-crime-dynamics-chicago/
│
├── notebooks/
│   └── DS5110_Final_Project_Chicago_Crime_Group_14.ipynb
│
├── outputs/
│   ├── analysis/
│   │   └── (all EDA/plots images)
│   ├── forecasting/
│   │   └── (SARIMAX & XGBoost plots, predictions, etc.)
│   └── clustering/
│       └── crime_hotspots_dbscan.html
│
├── README.md
├── LICENSE  (MIT)
```
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
