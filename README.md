# Analysis of Accessibility to Key Urban Amenities in Ottawa

A portfolio project demonstrating a full GIS workflow, from data acquisition and preparation to spatial analysis and final cartographic presentation using ArcGIS Pro.

---

## Final Map

![Ottawa Accessibility Map](https://github.com/jeelsgit/Ottawa-Accessibility-Analysis/blob/main/exports/Ottawa_Accessibility_Map.jpg) 

---

## Project Goal

The goal of this project was to identify and visualize "accessibility deserts" and "accessibility oases" within the City of Ottawa. Accessibility was defined by walking distance to three key amenity types: public parks, OC Transpo transit stops, and community facilities.

---

## Methodology

1.  **Data Acquisition:** All data was sourced from the City of Ottawa's Open Data Portal.
2.  **Preparation:** Layers were reprojected to NAD 1983 MTM Zone 8. Community facility layers were merged into a single dataset.
3.  **Analysis:**
    *   **Buffer Analysis:** Modeled walking distances (Parks: 500m, Transit: 400m, Facilities: 1500m).
    *   **Intersect Analysis:** Identified areas where all three buffer zones overlapped, creating the final "High Accessibility Zones" layer.

---

## Technologies Used
*   **Esri ArcGIS Pro:** For all spatial analysis and cartography.
*   **City of Ottawa Open Data Portal:** For data sourcing.
*   **Carleton University MacOdrum Library:** For data sourcing.

---

## Data Sources

*   **Parks and Greenspace:** https://open.ottawa.ca/datasets/cfb079e407494c33b038e86c7e05288e_24/explore?location=45.271425%2C-75.773591%2C1.31
*   **OC Transpo Stops:** https://library.carleton.ca/find/gis/geospatial-data/oc-transpo-transit-routes
*   **Community Centres:** https://open.ottawa.ca/datasets/97cc7fe0e2c04b878c82e0b1b8a38558_0/explore?location=45.248230%2C-75.800876%2C1.00
*   **Ward Boundaries:** https://open.ottawa.ca/datasets/8973061e1b0c4cd09b4495088c04c310_0/explore?location=45.248135%2C-75.801082%2C1.03
