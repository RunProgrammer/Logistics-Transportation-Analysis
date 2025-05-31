# 🚚 Logistics Data Analytics Dashboard

This project transforms raw logistics and supply chain data into actionable insights using **Python** for data analysis and **Power BI** for dynamic visualization. The goal is to help stakeholders make data-driven decisions around delivery efficiency, route risk, and operational performance.

---

## 📦 Dataset Overview

The dataset includes the following key features:

- `vehicle_gps_latitude`, `vehicle_gps_longitude` – Real-time vehicle positions  
- `fuel_consumption_rate` – Fuel usage per unit distance/time  
- `eta_variation_hours` – Delay in expected delivery (converted to duration format)  
- `traffic_congestion_level` – Traffic status (categorical or numerical)  
- `warehouse_inventory_level`, `loading_unloading_time`, `handling_equipment_availability` – Operational factors  
- `order_fulfillment_status` – Binary or categorical (Fulfilled / Not Fulfilled)  
- `weather_condition_severity`, `shipping_costs`, `supplier_reliability_score`, `lead_time_days`  
- `iot_temperature`, `cargo_condition_status`, `driver_behavior_score`, `route_risk_level`, `risk_classification`  

---

## 🧰 Tools & Technologies

- **Python**  
  - `pandas` for data cleaning and wrangling  
  - `matplotlib` & `seaborn` for EDA and trend visualization

- **Power BI**  
  - Power Query (M) for data transformation  
  - DAX and custom visuals for interactivity  
  - KPI cards, slicers, maps, trend lines, and categorized filters

---

## 📊 Power BI Dashboard Features

- **KPI Cards** – Real-time indicators for ETA delay, risk level, shipping costs, driver score  
- **Line Charts** – Trends of ETA variation, risk over time, and fuel efficiency  
- **Donut/Bar Charts** – Category-wise distribution of risk classifications, order statuses  
- **Geo Maps** – Delivery vehicle positions overlaid with risk levels  
- **Slicers** – Interactive filtering by traffic level, weather, and classification  
- **Tables with Conditional Formatting** – Highlight high-risk or delayed shipments  

---

## 🔍 EDA Workflow (Python)

1. Load and inspect dataset using `pandas`
2. Visualize key metrics and correlations using `seaborn` and `matplotlib`
3. Preprocess fields (e.g., convert ETA variation from hours to readable duration)
4. Export cleaned data for Power BI integration (`.csv`)

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Power BI Desktop

### Setup Instructions

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/logistics-dashboard.git
   cd logistics-dashboard

   pip install pandas matplotlib seaborn
