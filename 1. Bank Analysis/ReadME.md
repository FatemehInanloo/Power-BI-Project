# 🏦 Transaction Banking Report (Bank Analysis)

## 📌 Project Overview
A multi‑page Power BI solution to analyze transaction amounts, fees, customers, and revenue for a retail bank.  
Includes executive KPIs, trend charts, customer segmentation, currency switching (EUR/USD), and clean, business‑ready visuals.

---

## 🎯 Key Objectives
- Track overall transaction value, fees, and customer behavior over time  
- Compare current year vs prior year (YoY) for major KPIs  
- Drill into segments, channels, branches, and products to uncover performance drivers  
- Provide an executive dashboard that supports quick decision making

---

## 🧠 Advanced Techniques & Modeling

### ✅ Calculation Groups & Tabular Editor
- Used **Tabular Editor** to create calculation groups, keeping time‑intelligence logic reusable and the model tidy.  
- Calculation groups reduce redundant measures and apply common patterns (e.g., prior‑year logic) across many measures, making the model more scalable and maintainable. 
- Time‑intelligence and dynamic indicator logic kept centralized rather than duplicated across dozens of measures.

### ✅ Forecast / Rolling Logic
- Implemented **12‑month moving averages** and **forecast trends** to show expected future behavior along with actuals.  
- Gives stakeholders a forward‑looking view rather than only historical numbers.

### ✅ Key Influencers / Diagnostic Insight
- Added diagnostic analytics to highlight **which factors most influence performance** when needed—helpful for rapid root‑cause checks.  
- The Key Influencers visual in Power BI is designed to surface top factors that affect a chosen metric, ranking them for clearer interpretation.
- Enables teams to quickly see relevant drivers without building separate complex measures for each hypothesis.

### ✅ Measure‑Driven, Clean Model
- Central **Measure table** with structured display folders (Main, Revenue, Customer Behaviours, etc.)  
- Dynamic currency switch, YoY, and KPI formatting all driven by measures built once and reused everywhere.

---

## 📄 Report Pages
- **Overview** – High‑level KPIs, moving averages, YoY comparisons, and segment breakdowns  
- **Transaction Behaviours** – Product types, channels, geographic maps, and waterfall analysis  
- **Customer Behaviours** – Segment distribution, preferred offers, credit score segments, and customer trends  
- **Revenue Analysis** – Decomposition tree, product and channel revenue breakdowns, monthly trends

---

## 🎨 Design & UX
- Executive‑focused layout with clear cards, maps, and charts  
- Year and currency slicers, plus a reset button for quick navigation  
- Consistent visual theme for fast scanning by business users

---

## 🛠 Tools & Technologies
- Power BI Desktop  
- DAX, Calculation Groups  
- Tabular Editor for semantic organization  
- Key Influencers visual for rapid diagnostics  
- Forecast and moving‑average logic for future trends


## 📈 Dashboard Preview

<h3>📊 Dashboard Preview (Compact)</h3>

<p align="center">
  <img src="./Images/Overview.jpg" width="48%" />
  <img src="./Images/Transaction%20Behaviors.jpg" width="48%" />
</p>

<p align="center">
  <img src="./Images/Customer%20Behaviors.jpg" width="48%" />
  <img src="./Images/Revenue%20Analysis.jpg" width="48%" />
</p>
