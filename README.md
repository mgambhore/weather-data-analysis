#  Weather Data Analysis Using Python

##  Project Overview

This project explores historical weather data to identify trends, patterns, and relationships between different weather variables.

The analysis uses Python to investigate temperature, humidity, wind speed, visibility, atmospheric pressure, and weather conditions across time.

The project focuses on turning raw weather observations into meaningful analytical insights through data cleaning, exploratory data analysis, visualization, and correlation analysis.

---

##  Objectives

The main objectives of this project are:

- Understand the structure and quality of the weather dataset
- Analyze temperature and humidity patterns
- Identify common weather conditions
- Investigate low-visibility conditions
- Analyze hourly, monthly, and seasonal temperature patterns
- Examine relationships between numerical weather variables
- Generate meaningful insights from historical weather observations

---

##  Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab 
---

##  Dataset

The dataset contains **8,784 hourly weather observations** with the following variables:

- Date/Time
- Temperature
- Dew Point Temperature
- Relative Humidity
- Wind Speed
- Visibility
- Atmospheric Pressure
- Weather Condition

---

##  Analysis Performed

### 1. Data Understanding

- Dataset dimensions
- Column inspection
- Data types
- Descriptive statistics
- Data quality checks

### 2. Data Preparation

- Date/Time conversion
- Time-based feature extraction
- Year, Month, Day and Hour creation
- Day-of-week analysis
- Season classification
- Data validation

### 3. Exploratory Data Analysis

- Temperature distribution
- Extreme temperature analysis
- Humidity analysis
- Weather-condition frequency
- Visibility analysis
- Wind-speed analysis
- Hourly temperature patterns
- Monthly temperature trends
- Seasonal analysis
- Correlation analysis

---

##  Key Insights

- Temperature ranged from **-23.3°C to 33.0°C**, with an average of approximately **8.8°C**.
- Approximately **5.6%** of hourly observations recorded temperatures below **-10°C**, while only **0.76%** exceeded **30°C**.
- The four most frequent weather conditions accounted for approximately **82.3%** of all observations.
- Only around **1.12%** of observations had visibility below **2 km**.
- Snow was the most common condition among the low-visibility observations.
- Average temperature followed a clear daily cycle, reaching its lowest level around **5 AM** and peaking around **3 PM**.
- July recorded the highest monthly average temperature at approximately **22.8°C**.
- Temperature and dew point showed a very strong positive correlation (**r = 0.933**).
- Relative humidity and visibility showed a moderate negative correlation (**r = -0.634**).

---

##  Practical Implications

The findings can support weather-sensitive decision-making in areas such as:

- Transportation and logistics planning
- Outdoor activity planning
- Tourism and travel planning
- Operational planning
- Weather monitoring

In particular, low-visibility conditions associated with snow and fog can be relevant for transportation planning and operational decision-making.

---

##  Project Highlights

This project demonstrates my ability to:

- Clean and prepare real-world datasets
- Use Pandas for data manipulation
- Perform exploratory data analysis
- Create meaningful visualizations
- Analyze time-series patterns
- Interpret correlations
- Translate analytical results into practical insights

---

##  Repository Structure

```text
weather-data-analysis-python/
│
├── README.md
├── notebook/
│   └── Weather_Data_Analysis.ipynb
├── data/
│   └── Project_1_Weather_Dataset.csv
└── images/
