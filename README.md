# Global Earthquake Analysis Dashboard (1900–2013)

<img width="1831" height="1026" alt="image" src="https://github.com/user-attachments/assets/589cef8e-14fd-41df-b1fb-e1dddbaa9994" />

## Overview
This project presents an **interactive Tableau dashboard** analyzing global earthquakes with a magnitude of **6.0 and above** recorded between **1900 and 2013**.  

The dashboard enables users to explore earthquake activity across **time, geography, depth, magnitude, and seismic measurement types**, using dynamic filters and KPIs to uncover meaningful patterns and trends.

The project covers the **entire analytics workflow**:
- Data exploration in Excel
- Parameter creation and calculated fields in Tableau
- KPI design
- Advanced visualizations
- Interactive dashboard assembly

---

## Dataset
- **Source:** USGS earthquake records (Magnitude ≥ 6)
- **Time period:** 1900 – 2013
- **Rows:** 8,000+ earthquake events
- **Key fields:**
  - Date / Time
  - Latitude & Longitude
  - Depth (km)
  - Magnitude
  - Magnitude Type (Mw, Ms, Mb, etc.)
  - NST (Number of seismic stations)
  - Gap, Dmin, RMS
  - Location (Place)

---

## Key Features

### 🔹 Interactive Date Parameters
- **Start Date** and **End Date** parameters
- Dynamically filter the entire dashboard for focused analysis

### 🔹 KPI Section
- Total Earthquakes
- Average Dmin
- Average Gap
- Average NST
- Average Depth
- Average RMS
- Maximum Gap

These KPIs automatically update based on selected date ranges.

---

## Visualizations Included

### 1. Total Earthquakes by Year and Magnitude Type
- Area chart
- Shows long-term seismic activity trends
- Includes reference line for average activity

### 2. Total Earthquakes by Month and Type
- Stacked bar chart
- Highlights seasonal and magnitude-type patterns
- Identifies the most active months

### 3. Magnitude Histogram
- Distribution of earthquake magnitudes
- Bin size optimized for granular insight

### 4. Depth (km) Histogram
- Shows how earthquakes are distributed by depth
- Clear dominance of shallow earthquakes

### 5. Depth vs Magnitude Relationship
- Scatter plot
- Reveals inverse relationship between depth and magnitude

### 6. Earthquake Map (Geographical Analysis)
- World map with size and color encoding
- Identifies global seismic hotspots:
  - Japan
  - Pacific Ring of Fire
  - West Coast of the Americas

### 7. Earthquake Details Table
- Event-level view including:
  - Date
  - Location
  - Magnitude
  - Depth
  - Total NST
- Fully responsive to filters

---

## Key Insights

- Most earthquakes fall between **magnitude 6.0–6.25**
- Shallow earthquakes (**0–50 km**) are the most frequent
- Higher magnitudes are more common at **lower depths**
- **March** is the most active month globally
- **Ms magnitude type** is the most frequently recorded
- The **Pacific Ring of Fire** is the most seismically active region

---

## Tools Used
- **Tableau Desktop**
- **Microsoft Excel**
- Calculated Fields & Parameters
- Dashboard Actions & Filters
- Mapbox (Dark theme)

---

## Files Included
- `earthquakes_mag6plus_1900_2013.xlsx` – Raw dataset
- `global_earthquake_analysis_dashboard.twbx` – Final Tableau dashboard (packaged workbook with embedded data)
- `global_earthquake_analysis_dashboard.twb` – Tableau workbook file (uses external data source)
- `global_earthquake_dashboard_preview.png` – Dashboard snapshot

---

## Notes
This project built by implementing:
- Custom layout decisions
- Formatting refinements
- KPI structuring
- Interaction logic
- Dashboard polish for portfolio presentation

---
