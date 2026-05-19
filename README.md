# 🛡️ Women Safety Analysis Dashboard

## 📌 Project Overview
This project focuses on analyzing women safety-related incidents using SQL and Power BI to identify unsafe locations, incident trends, risk levels, and city-wise safety analysis. The project helps in understanding critical safety concerns and provides data-driven insights for improving public safety.

---

## 🎯 Objectives
- Analyze women safety incidents across different cities
- Identify high-risk and low-risk areas
- Track incident trends and severity
- Generate insights using SQL queries
- Visualize findings through an interactive Power BI dashboard

---

## 🛠️ Tools Used
- SQL
- Power BI
- Excel
- GitHub

---

## 📊 Dataset Features
The dataset includes:
incident_id	city	area	latitude	longitude	crime_type	crime_count	time_of_day	lighting_score	police_station_distance_km	crowd_density	weather_condition	safety_score	risk_level	incident_date	Time

- Incident ID
- City
- Area
- Latitude
- Longitude
- Crime_type
- Crime_count
- Time_of_day
- Lighting_score
- Police_station_distance_km
- Crowd_density
- Weather_condition
- Safety_score
- Risk_level
- Incident_date
- Time

---

## 🔥 SQL Concepts Used
- SELECT Statements
- WHERE Clause
- GROUP BY
- HAVING
- ORDER BY
- Aggregate Functions
- Joins
- Subqueries
- Correlated Subqueries
- Data Cleaning
- KPI Analysis

---

## 📈 Key Analysis Performed

### 1️⃣ Total Incidents Analysis
Calculated total reported incidents across all cities.

### 2️⃣ City-wise Safety Analysis
Compared safety scores and incident counts city-wise.

### 3️⃣ High Risk Area Identification
Identified locations with maximum critical incidents.

### 4️⃣ Incident Trend Analysis
Analyzed incident patterns based on date and time.

### 5️⃣ Severity Level Distribution
Studied low, medium, and critical severity incidents.

### 6️⃣ KPI Metrics
Created KPI cards for:
- Total Incidents
- Average Safety Score
- Critical Incidents
- High Risk Areas

---

## 📊 Power BI Dashboard Features
- Interactive Filters
- KPI Cards
- City-wise Charts
- Risk Level Analysis
- Trend Visualization
- Incident Severity Breakdown

---

## 💡 Key Insights
- Certain cities reported significantly higher incident counts.
- Critical incidents were concentrated in specific high-risk zones.
- Night-time incidents showed higher severity levels.
- Safety scores varied greatly across locations.

---

## 📌 Sample SQL Query

```sql
select city, count(*) as total_incidents
from women_safety
group by city
order by total_incidents desc;
```

---

## 🚀 Project Outcome
This project improved skills in:
- SQL Query Writing
- Data Cleaning
- Data Analysis
- Dashboard Development
- Business Insight Generation

---

## 👨‍💻 Author
Boobalan
