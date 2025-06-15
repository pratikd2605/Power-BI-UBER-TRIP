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

**Purpose:**  
Provides a summary view of overall trip performance, customer usage patterns, and comparative metrics by vehicle and payment types.

**Key Features:**  
⭐ Core KPIs: Total Bookings, Total Booking Value, Avg Trip Distance, Avg Trip Time  
⭐ Dynamic Measure Toggle: Switch between KPIs without changing visuals  
⭐ Breakdown filters for: Payment Type, Day vs. Night, Vehicle Category  
⭐ Location Insights:
- Most common pickup/drop-off zones  
- Longest trips by distance  
- Top booking locations by volume  
- Preferred vehicles by area  

**User Experience Enhancements:**  
- Tooltips with contextual metrics (e.g., average value per trip)  
- Bookmark for data dictionary and model details  
- Reset filters button  
- CSV/Excel export functionality
 

---
![image alt](https://github.com/pratikd2605/Power-BI-UBER-TRIP/blob/182349c4f56b58d68a463692f330d35193355332/TimeAnalysis.png)
### 🕒 Dashboard 2: Time-Based Analysis  

**Purpose:**  
Analyzes when trips are taken to support decisions around staffing, scheduling, and surge pricing.

**Visual Highlights:**  
⭐ Pickup trends over 10-minute intervals (Area Chart)  
⭐ Weekday comparison (Line Chart: Monday–Sunday)  
⭐ Hour × Day Heatmap to identify busiest hours and low-demand windows

**Dynamic Measure Selector:**  
All visuals update based on selected metric:  
- Total Bookings  
- Total Booking Value  
- Total Trip Distance

---
![image alt](https://github.com/pratikd2605/Power-BI-UBER-TRIP/blob/12ef798c5e534b902fd624b13b45547cb5ca7432/Details.png)
### 🔍 Dashboard 3: Drill-Through Details Tab  

**Purpose:**  
Supports granular analysis by allowing users to explore individual trip records.

**Features:**  
⭐ Table view with fields like Trip ID, Fare, Distance, Pickup & Drop-off Time  
⭐ Drill-through from high-level visuals for detailed investigation  
⭐ Bookmark toggles between filtered and full views  
⭐ Slicer reset options and export to CSV/Excel for deeper offline analysis

---
## ✅ Conclusion  
- Identified peak demand hours, preferred routes, top vehicle categories  
- Gained visibility into surge pricing and high-demand zones  
- Delivered an intuitive, clean, and business-ready dashboard  
- Empowered users with self-service analytics tools for improved decision-making 

This Power BI dashboard solution offers a scalable and interactive way to analyze Uber trip data from multiple perspectives. Its modular structure supports both quick overviews and in-depth exploration, making it a practical tool for operations, planning, and executive decision-making.

Through clear visual storytelling and smart filters, the project enhances user engagement and helps turn raw data into meaningful insights—empowering stakeholders to take proactive actions based on real trends.

---



 
