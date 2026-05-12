# Afghanistan Relief Operations GIS Analysis

## Overview

This project evaluates geospatial datasets and terrain analysis products used to support humanitarian relief and operational planning in Afghanistan. The analysis focuses on terrain visualization, transportation infrastructure, seismic hazards, land cover, and airfield suitability for disaster response operations.

---

# Objectives

* Evaluate multiple geospatial datasets for operational suitability
* Analyze terrain and seismic hazards
* Assess transportation and airfield infrastructure
* Support disaster relief planning and logistics operations
* Compare operational strengths and limitations of available GIS products

---

# Geospatial Data Sources

| Dataset                      | Coordinate System            | Coverage / Creation Date          | Scale                        | Analytical Use                                                                        |
| ---------------------------- | ---------------------------- | --------------------------------- | ---------------------------- | ------------------------------------------------------------------------------------- |
| **Earthquake Data**          | Undefined                    | Afghanistan/Pakistan region; 2010 | Varies                       | Historical earthquake analysis and seismic hazard prediction                          |
| **SRTM 3**                   | GCS WGS 1984                 | 5x5 degree cells; 2000            | 1:3,186,195                  | Elevation analysis, hillshade generation, slope/aspect analysis, landslide assessment |
| **50K Topographic Maps**     | Undefined                    | 15x15 minute cells; ~1985–1991    | 1:50K                        | Land navigation, topographic analysis, built-up area identification                   |
| **200K Topographic Maps**    | GCS WGS 1984                 | 1x1 degree cells; ~1985–1991      | 1:200K                       | Regional basemap analysis, terrain visualization, settlement identification           |
| **VMAP Level 1 Data**        | GCS WGS 1984                 | Afghanistan-focused; 1993         | Derived from 1:250K JOG      | Transportation network analysis, road networks, boundaries, built-up areas            |
| **Landsat Geocover Imagery** | WGS 1984 UTM Zone 42N        | 5x6 degree cells; 2000            | 1:3,166,497                  | Basemap imagery, vegetation analysis, urban growth assessment                         |
| **USGS Fault Data**          | WGS 1984 Transverse Mercator | Afghanistan; 2007                 | Varies                       | Fault line analysis and seismic hazard assessment                                     |
| **Landcover Data**           | GCS WGS 1984                 | Afghanistan; 1993                 | Intended for 1:250K analysis | Vegetation, cultivation, soil, marshland, and terrain analysis                        |

## Earthquake Data Analysis


<img width="1000" alt="image" src="https://github.com/JamesA-usa/vector-raster/blob/main/C_5Map.png">

---

# Operational Assessment

## VMAP Data Limitations

The VMAP Level 1 dataset was identified as outdated for operational use. Some airfield attribution information was incomplete or obsolete, creating potential risks for relief operations.

### Key Concerns

* Runway operational status may be outdated
* Runway length data may be inaccurate
* Construction material information may be missing
* Older transportation data can impact route planning

### Recommendation

Replace the existing VMAP Level 1 data with updated transportation and airfield datasets to improve operational accuracy and mission planning reliability.

---

# Airfield Suitability Analysis

## Chaman Airfield

| Category              | Assessment                                  |
| --------------------- | ------------------------------------------- |
| Type                  | Minor Airport                               |
| Operational Status    | Operational (limited information available) |
| Distance to Epicenter | 111 km                                      |

### Advantages

* Closest airfield to the earthquake epicenter
* Majority of access route uses paved roads/highways

### Disadvantages

* Pakistan could restrict access
* Unknown aircraft handling capability
* Located near active fault lines

---

## Kandahar Airfield

| Category              | Assessment              |
| --------------------- | ----------------------- |
| Type                  | Major Military Airfield |
| Operational Status    | Fully Operational       |
| Distance to Epicenter | 202 km                  |

### Advantages

* Can support large military and cargo aircraft
* Strong transportation infrastructure
* Military logistical support available
* Lower seismic risk compared to other locations

### Disadvantages

* Further from the epicenter than Chaman

### Assessment

Kandahar was identified as the best overall operational airfield due to infrastructure capability, logistics support, and aircraft capacity.

---

## Bost Airfield

| Category              | Assessment    |
| --------------------- | ------------- |
| Type                  | Minor Airport |
| Operational Status    | Operational   |
| Distance to Epicenter | 365 km        |

### Advantages

* Access to paved transportation routes
* Reduced seismic hazard exposure

### Disadvantages

* Limited airfield capability information
* Located within an insurgent-safe haven region
* Further from relief operations area

---

## Ghazni Airfield

| Category              | Assessment  |
| --------------------- | ----------- |
| Type                  | Heliport    |
| Operational Status    | Operational |
| Distance to Epicenter | 561 km      |

### Advantages

* Road access available
* Military operational support possible

### Disadvantages

* Limited to helicopter operations
* Located near historic earthquake zones and fault lines
* Farthest operational location from epicenter

### Assessment

This location was determined to be a poor choice for large-scale relief operations due to aircraft limitations and seismic risk.

---

# Key Findings

* Updated transportation and airfield data are critical for disaster response operations.
* Kandahar Airfield provides the strongest operational capability for sustained relief operations.
* SRTM and Landsat datasets provide valuable terrain and environmental analysis support.
* Seismic and fault line datasets are essential for risk-aware operational planning.
* GIS-based infrastructure analysis significantly improves humanitarian logistics and mission planning.

---

# Technologies Used

* ArcGIS
* Terrain Analysis
* SRTM Elevation Data
* Landsat Imagery
* VMAP Transportation Data
* USGS Fault Data
* GIS Spatial Analysis

---

# Conclusion

This project demonstrates how geospatial intelligence and GIS analysis support humanitarian relief planning and operational decision-making. By integrating elevation data, transportation infrastructure, landcover analysis, and seismic hazard datasets, analysts can improve route planning, airfield selection, and disaster response effectiveness in complex operational environments.

---
