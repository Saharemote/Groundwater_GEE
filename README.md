# 🌊 Groundwater Monitoring and Analysis for Bankura District, West Bengal, India (2003–2024)

This project uses **Google Earth Engine (GEE)** to monitor, visualize, and analyze groundwater storage variations over **Bankura District, West Bengal, India** from **2003 to 2024** using the **GLDAS (Global Land Data Assimilation System) CLSM V2.2 dataset**.

## 🔍 Project Summary
Groundwater is a critical resource for agriculture and livelihoods in Bankura. This project provides a spatiotemporal analysis of groundwater storage to support sustainable water management and early warning for groundwater depletion.

### Key Features
- **Study Area:** Bankura District, West Bengal, India
- **Dataset:** NASA GLDAS CLSM v2.2 Groundwater Storage (`GWS_tavg`)
- **Time Period:** January 2003 – January 2024 (Monthly scale)
- **Monitoring Points:** Four strategically selected locations across Bankura (North, South, East, West)

### Main Workflow
- Load administrative boundaries and set up the Bankura district region.
- Define groundwater monitoring points within the district.
- Access and process GLDAS daily groundwater storage data to generate monthly composites.
- Create time-series plots:
  - Overall groundwater trend for the entire district.
  - Point-specific groundwater trends.
- Visualize the median groundwater storage using a customized color palette and add an interactive legend.
- Export multi-band groundwater images for all months and monitoring points as shapefiles.

### Outputs
- 📈 **Time-Series Charts:**
  - District-wide mean groundwater storage trends (2003–2024) ![ee-chart (80)](https://github.com/user-attachments/assets/2e45a1dc-1568-4cfb-a7ae-7c49199ff4ea)
![ee-chart (80)](https://github.com/user-attachments/assets/2e45a1dc-1568-4cfb-a7ae-7c49199ff4ea)

  - Monitoring point-specific groundwater storage trends  ![ee-chart (81)](https://github.com/user-attachments/assets/ce20f67a-b2ce-4b01-be8c-f13a8e27d4d5)
![ee-chart (81)](https://github.com/user-attachments/assets/ce20f67a-b2ce-4b01-be8c-f13a8e27d4d5)

- 🗺️ **Spatiotemporal Groundwater Maps:**
  - Median groundwater storage map with intuitive color-coded legend
- 📂 **Data Exports:**
  - Monthly groundwater multi-band images (GeoTIFF)
  - Monitoring points as Shapefile

### Why This Project Matters
Groundwater depletion is a growing concern in semi-arid regions like Bankura. This project offers a scalable, automated approach to groundwater monitoring using freely available remote sensing datasets, which can support water resource planning, drought preparedness, and agricultural sustainability.


