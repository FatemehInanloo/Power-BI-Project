# 🏘️ Airbnb Market & Pricing Analysis – Vancouver, Canada

This project is a comprehensive **Power BI analytics solution** focused on the **Airbnb market in Vancouver, Canada**, designed to analyze **pricing, demand, occupancy, revenue efficiency, and guest experience** using professional, executive-style dashboards.

The goal of this project is to simulate a **real-world short-term rental performance analysis**, combining **advanced data modeling, DAX measures, Python-based data preparation**, and **interactive storytelling visuals**.

---

## 🔍 Project Scope

This analysis covers:
- Listing performance and booking demand
- Pricing strategy and price segmentation
- Occupancy and revenue efficiency
- Review quality, superhost performance, and guest experience
- Neighborhood-level insights across Vancouver

The entire report is built with a **dark, professional design**, optimized for insights discovery and executive-level decision making.

---

## 📊 Report Pages Overview

### 1️⃣ Occupancy & Demand
- Booking Count, Booking Growth %, and Occupancy Rate
- Booking trends by month and seasonality
- Property type distribution (Entire home, Private room, Condo, etc.)
- Geographic analysis using neighborhood-level maps
- Top neighborhoods by bookings and revenue

---

### 2️⃣ Guest Experience & Reviews
- Average Review Score and Response Rate
- Superhost vs Non-Superhost performance
- Review quality by response time
- Correlation between responsiveness and review ratings
- Scatter and radar visuals for qualitative performance comparison

---

### 3️⃣ Revenue Performance
- Actual Revenue vs Estimated & Potential Revenue
- Revenue Capture Rate & Revenue Efficiency %
- Revenue contribution by price segment (Luxury, Standard, Economy, Budget)
- Booking vs Price analysis to support pricing strategy decisions
- Violin and bubble charts to analyze price dispersion and demand elasticity

---

## 🧠 Key Analytical Techniques Used

- **Advanced DAX Measures**
  - Revenue Efficiency %
  - Booking Growth %
  - Revenue Gap %
  - Dynamic Ranking (Booking Rank, Price Rank, Review Rank)
  - Occupancy & Revenue KPIs with contextual insights

- **Heavy Tooltip Usage**
  - KPI tooltips with expanded explanations and breakdowns
  - Ranking tooltips to explain why a listing or neighborhood ranks higher
  - Contextual tooltips designed for exploratory analysis  
  *(Users are encouraged to hover over KPIs and visuals to unlock deeper insights)*

- **Dynamic Drill-Down & Slicers**
  - Year, Quarter, and Time slicing
  - Property type, neighborhood, and host-type filtering
  - Consistent filtering behavior across pages

---

## 🐍 Python & Data Preparation

The Airbnb dataset was **loaded and transformed using Python (Pandas)** before modeling in Power BI.

Key steps include:
- Reading raw CSV data using Pandas
- Parsing semi-structured fields (amenities) using `ast.literal_eval`
- Creating binary indicator columns for amenities (wifi, kitchen, parking, etc.)
- Cleaning and standardizing text-based fields
- Preparing the dataset for efficient analytical modeling

> Python was used inside Power BI (Python Script) to simulate real-world data engineering workflows.

---

## 🗺️ Geographic Analysis

- Neighborhood-level choropleth maps
- Revenue and booking distribution by area
- Spatial comparison of occupancy and pricing efficiency
- Visual storytelling through map-driven insights

---

## 🛠 Tools & Technologies

- Power BI Desktop  
- DAX (Advanced Calculations & Ranking Logic)  
- Python (Pandas, AST)  
- Data Modeling & Performance Optimization  
- Power BI Tooltips & Interactive UX Design  

---
## 📸 Dashboard Screenshots
<p align="center">
  <img src="./Images/Occupancy_Demand.jpg" width="90%" />
</p>

<p align="center">
  <img src="./Images/Guest_Experience_Review.jpg" width="90%" />
</p>

<p align="center">
  <img src="./Images/Revenue_Performance.jpg" width="90%" />
</p>

