# geo-dev-lab-project
An assessment of areas that are susceptible to flooding in Ndola District
### **My Project Brief**

### **The question** 

Which settlements and infrastructure in Ndola District are in low-lying areas at high risk of flooding based on elevation, proximity to watercourses, and seasonal water-flow patterns?

### **Why it matters**

Ndola's City Council planners need this to guide infrastructure and settlement planning; they'd restrict high-density development in flood-prone zones and prioritise drainage systems. The National Remote Sensing Centre could use it to support risk-informed urban development policy and disaster preparedness planning.

### **The Needed Dataset**

* Digital Elevation Model (DEM) with 30m resolution  
* Watercourse and river network shapefile for Ndola District  
* Rainfall/precipitation data (seasonal patterns, 10-year historical)  
* Soil permeability and infiltration rates by soil type  
* Land use/land cover classification (current)  
* Historical flood event locations and extents (satellite or local records)  
* Populated settlements and critical infrastructure locations (schools, hospitals, roads)

### **Where each dataset comes from**

| Dataset | Source |
| :---- | :---- |
| DEM | USGS Earth Explorer (Copernicus 30 m) |
| Watercourses | OSM (Waterways) |
| Rainfall | CHIRPS (Climate Hazards Group – https://www.chc.ucsb.edu/data/chirps)  |
| Soil Data | FAO HWSD or National soil survey reports from Zambia's Ministry of Agriculture |
| LULC | Copernicus Sentinel-2 Classification or USGS Landsat |
| Historical floods | Ndola Council Archives / Satellite imagery archives (Sentinel-1 SAR |
| Settlements | OSM Building data |

### 

### **What I would build**

An interactive GIS map that layers elevation, watercourse proximity, and soil permeability to highlight flood-susceptible zones. The map updates quarterly with rainfall monitoring data. A municipal dashboard flagging settlements in high-risk areas, usable by city planners and emergency response officers to guide development restrictions and early warning protocols.
