# 📊 Uber Trip Data Analysis – Power BI Dashboard

## 🚀 Project Overview  
This Power BI project was developed to analyze Uber trip data and generate actionable insights into booking behavior, revenue patterns, geographic demand, and operational efficiency. The solution includes an interactive three-part dashboard—**Overview Analysis**, **Time-Based Analysis**, and **Details Tab**—to help stakeholders explore trends and make data-driven decisions.

Built on a structured data model that integrates trip-level data with location metadata, the dashboards feature dynamic measure selectors, heatmaps, drill-through capabilities, bookmarks, and raw data export options. The objective was to deliver a scalable, user-friendly business intelligence solution tailored for ride-share analytics.

---

## 📍 Situation  
With the ride-share industry experiencing rapid growth, understanding usage patterns, revenue drivers, and operational pain points has become crucial. A visual and interactive tool was needed to transform raw Uber trip data into meaningful insights.

---

## 🎯 Task  
Design and deploy a Power BI dashboard to analyze Uber trips across time, location, and vehicle type. The dashboard should enable users to identify trip frequency, peak hours, fare dynamics, and rider preferences.

---

## 🛠️ Action  

A **three-tier dashboard system** was developed using a structured data model composed of:

### 🔹 Data Model Components
- **Trip Details Table**: Captures fields like Trip ID, Pickup/Drop-off Time, Passenger Count, Trip Distance, Fare Amount, Surge Fee, Vehicle Type, and Payment Type.  
- **Location Table**: Maps LocationID values to area names and cities for spatial analysis.

---
![image alt](https://github.com/pratikd2605/Power-BI-UBER-TRIP/blob/61d51c193a0399fc39c9ea14f6862d199df59ba0/OverviewAnalysis.png)
### 📈 Dashboard 1: Overview Analysis  
- KPIs: Total Bookings, Total Booking Value, Avg. Trip Distance, Avg. Trip Time  
- Filters: Payment Type, Day vs. Night Trips, Vehicle Category  
- Visual Selector: Disconnected table to toggle dynamic metrics  
- Highlights:
  - Top Pickup/Drop-off Locations  
  - Longest Trips  
  - High-Performing Areas  
  - Conditional formatting and custom sorting for readability  

---
![image alt](https://github.com/pratikd2605/Power-BI-UBER-TRIP/blob/182349c4f56b58d68a463692f330d35193355332/TimeAnalysis.png)
### 🕒 Dashboard 2: Time-Based Analysis  
- Global dynamic measure filter across all visuals  
- Visuals:
  - Area chart: Pickup trends (10-minute intervals)  
  - Line chart: Weekday-wise booking patterns  
  - Heatmap: Hour × Day grid to identify peak/off-peak windows  

---
![image alt](https://github.com/pratikd2605/Power-BI-UBER-TRIP/blob/61d51c193a0399fc39c9ea14f6862d199df59ba0/OverviewAnalysis.png)
### 🔍 Dashboard 3: Drill-Through Details Tab  
- Tabular view with fields: Trip ID, Distance, Fare, Pickup/Drop-off Time  
- Drill-through enabled from summary visuals to detailed trip records  
- Features:
  - Bookmarks to toggle filtered/full views  
  - Slicer reset buttons  
  - Export options (Excel/CSV) for further analysis  

---

## ✅ Result  
- Identified peak demand hours, preferred routes, top vehicle categories  
- Gained visibility into surge pricing and high-demand zones  
- Delivered an intuitive, clean, and business-ready dashboard  
- Empowered users with self-service analytics tools for improved decision-making  
