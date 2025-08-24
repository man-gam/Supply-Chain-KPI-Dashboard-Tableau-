# 📊 Supply Chain & Sales Performance Dashboard (Tableau)

## 🎯 Objectives  

### 🔹 Data Integration & Modeling  
- Connected multiple datasets (sales, products, factories, targets, postal codes).  
- Created relationships between fact and dimension tables.  
- Designed calculated fields for KPIs such as sales variance, distance to customer, and rank.  

### 🔹 Geospatial Analysis  
- Built a multi-layer map visualizing:  
  - Factory locations  
  - Customer locations  
  - Distance between customers and factories  
  - Dynamic buffer zones based on configurable shipping radius  
- Identified customers eligible for 2-day shipping.  

### 🔹 Customer & Performance Metrics  
- Ranked customers by 2024 sales volume and factory assignment.  
- Created a performance table showing rank, customer ID, factory, distance, orders, units, and sales.  
- Added KPI visual comparing 2024 sales vs. targets.  

### 🔹 Executive Dashboard  
- Consolidated all visuals into a single Tableau dashboard.  
- Included interactive parameters (e.g., shipping buffer radius).  
- Designed with an executive-friendly layout highlighting KPIs at a glance.  

---

## ⚡ Challenges  
- Data integration complexity – handling multiple datasets with different keys.  
- Geospatial accuracy – ensuring distance calculations were correct and parameterized.  
- KPI alignment – creating trusted variance between actual vs. target.  
- Performance design – balancing detail with high-level KPIs in one dashboard.  

---

## 🔎 Key Insights  
- Factories vary in specialization vs. diversification of product lines.  
- Customers outside the buffer zone face higher delivery costs & longer lead times.  
- Sales targets were uneven across divisions, with clear over- and under-performers.  
- A small group of customers contributed most revenue (Pareto principle).  

---

## 💡 Recommendations  
- Optimize factory-to-customer allocation → reassign customers closer to alternative factories.  
- Expand buffer coverage → consider new warehouses in underserved regions.  
- Focus on underperforming divisions → analyze pricing, demand, and capacity issues.  
- Strengthen key customer relationships → offer tailored agreements for top clients.  

---

## 🛠 Tools & Skills Used  
- **Tableau** → Data modeling, calculated fields, geospatial mapping, KPI dashboards  
- **Excel/CSV** → Data preparation & profiling  
- **Data Analytics** → Metric development, ranking logic, sales target variance  

---

## 📂 How to Use  
1. Clone this repository.  
2. Download the CSV files in the `/data` folder.  
3. Open Tableau and connect to the datasets.  
4. Follow the data model as outlined above.  
5. Explore the dashboard using parameters and filters.  

---
📸 Screenshots

<img width="1397" height="771" alt="image" src="https://github.com/user-attachments/assets/6d2cc31c-2446-409c-946d-ea7ce26e6fe3" />

