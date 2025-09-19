# Project-Air-Quality-and-Health-Impacts
This project analyses the relation between air quality and public health using a dataset combining pollutant levels, weather factors, mobility patterns, and healthcare utilisation
in five different regions.
The Aim is to understand how air quality and weather conditions affect people’s respiratory health and to help healthcare providers and communities prepare for health risks related to pollution and changing weather.

## DATASET OVERVIEW
 3500 records and 26 columns Includes the Details of
- *Air Quality Indicators* (AQI,PM2.5,PM10,NO2,SO2,CO,O3)
- *Weather* (Temperature, Wind Speed, Precipitation)
- *Mobility and Lockdown*
- *Industrial, Construction activities and Healthcare utilizations*
- Source Url : https://www.kaggle.com/datasets/khushikyad001/air-quality-weather-and-respiratory-health
## CLEANING & PREPARATION
- Removed missing values
  - Categorical values with Mode
  - Numerical values with median and mean
- Corrected Datatypes and inconsistancies in the formats
- Removed anomalies and Capitalization
## EDA
- Relation between AQI and Respiratory Health
- Role of Industrial and Construction activities in AQI and Respiratory Health
- Mobility pattern affecting AQI and Health
- Weather impacts on AQI and Respiratory Health
- Regional changes in AQI and Hospital admissions
## VISUALISATIONS
- Barplot
- Lineplot
- Scatterplot
- Jointplot
- Pie Chart
- Pairplot
- Histogram
- Boxplot
- Violinplot
## INSIGHTS
- Eventhough regional differences are less, West shows higher AQI variation and more health stress.
- Central,East and South region need specific care as these regions shown severe case of health impact
- Industrial activity strongly affects SO₂; construction raises particulate matter also contributes to higher AQI.
- Health impact is mostly moderate but spikes reports in some regions
- No direct weather influences causes fluctuations in the Air pollution
- Mobility patterns doesn't make any big difference in AQI and health impacts
## CONCLUSION
- This analysis highlights the relationship between air quality indicators, industrial and construction activities,and respiratory health outcomes across different regions.
- AQI shows fluctuations slightly across different regions, also the respiratory admissions are high in the west and south regions
- Industrial activity was found to be a primary driver of SO₂ emissions, while construction activities contributed significantly to the Air Quality index, signalling that proper monitoring in these areas is  necessary.
- Overall, the majority of health impacts were moderate, but the presence of high and severe cases (Central, South and East region) suggests that vulnerable groups (Respiratory patients, allergic people,etc) remain at considerable risk.
