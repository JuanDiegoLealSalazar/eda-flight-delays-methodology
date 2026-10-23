# US Air Traffic EDA: Methodology & Insights ✈️

## 📌 Project Overview
This repository contains a comprehensive Exploratory Data Analysis (EDA) of US Airport Traffic data (February 2011). The goal is to demonstrate a structured data analysis methodology, from initial data inspection to geospatial visualization and business insights.

## 📊 Dataset
- **Source:** Plotly Open Datasets
- **Variables:** Airport IATA code, Airport name, City, State, Latitude, Longitude, and Traffic Volume (cnt).

## 🛠️ Technologies Used
- **Python** (pandas, numpy)
- **Visualization** (matplotlib, seaborn, plotly)
- **Jupyter Notebooks**

## 📈 Methodology & Key Findings
1. **Data Cleaning:** Handled missing values and validated data types.
2. **Univariate Analysis:** Identified the top 10 airports by traffic volume.
3. **Geospatial Analysis:** Created an interactive Choropleth map to visualize traffic concentration by state. States like California (CA), Texas (TX), and New York (NY) lead the traffic volume.
4. **Conclusions:** Air traffic is highly concentrated in major economic hubs, showing no strong linear correlation with geographic coordinates.

## 🖼️ Visualizations

### 1. Top 10 Airports
![Top Airports](reports/01_top_airports.png)

### 2. Geospatial Distribution (States)
![Airport Map](reports/02_airport_map.png)

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/JuanDiegoLealSalazar/eda-flight-delays-methodology.git