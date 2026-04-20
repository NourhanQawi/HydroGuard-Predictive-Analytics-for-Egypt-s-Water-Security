# Egypt Water Security Analysis | Power BI Project

## Project Overview
This project analyzes **water security and water quality in Egypt** with a focus on environmental sustainability and data-driven decision-making.  
The analysis explores water resources, water quality indicators, wastewater monitoring methodologies, and geographical distribution of pollution using **Power BI**.

The goal of the project is to help policymakers and environmental analysts better understand current challenges related to Egypt’s water resources and support informed strategic decisions.

---

## Objectives
- Analyze the evolution of water quality indicators in Egypt over time.
- Compare **old vs modern wastewater measurement methodologies** and evaluate their impact.
- Examine the relationship between the number of monitoring stations and data accuracy.
- Identify the most affected regions and lakes by water pollution.
- Transform complex environmental data into **clear interactive dashboards** for decision-makers.

---

## Data Sources
Data was collected from the **Central Agency for Public Mobilization and Statistics (CAPMAS)** and includes:
- Nile River water quality indicators
- Lake water quality measurements
- Total water resources by source
- Total water consumption by sector (agriculture, drinking, industry)
- Agricultural wastewater reuse quantities
- Number of wastewater treatment plants
- Number of water quality monitoring stations
- Old and modern wastewater measurement datasets
- Mediterranean Sea water quality monitoring locations

---

## Tools & Technologies
- **Microsoft Power BI**
- **Power Query** for data cleaning
- **DAX** for calculated measures
- Excel (legacy data format)

---

## Data Cleaning & Modeling
- Missing values (Nulls) were identified and analyzed; values were replaced with zero when data was not collected rather than missing.
- Outliers caused by total rows inside raw datasets were removed.
- A custom **Dim Year** table was created to enable time-based analysis due to the absence of explicit year columns.
- Measures were rebuilt using DAX to ensure accurate aggregations and comparisons.

---

## Key DAX Measures
- Difference between old and modern wastewater methodologies
- Average Nile water quality across multiple years
- Aggregated agricultural wastewater reuse volumes
- Temporal water resource indicators

---

## Key Insights
- Agricultural usage dominates water consumption compared to other sectors.
- The Nile River remains Egypt’s primary water source.
- Wastewater infrastructure shows limited growth despite population increase.
- Monitoring stations are concentrated in major lakes such as Manzala and Burullus.
- Water quality in the Mediterranean Sea varies significantly by location, with Alexandria being a major focus point.

---

## Dashboard Highlights
- Water resources by usage
- Water resources by source
- Wastewater treatment infrastructure trends
- Agricultural water consumption indicators
- Geographical distribution of wastewater
- Lake and sea water quality visualizations

---

## Additional Materials
Dashboard visuals and presentation file:
https://drive.google.com/file/d/1uODN4-i9MgprsqxwALKUH2wmbQwbGFWq/view
