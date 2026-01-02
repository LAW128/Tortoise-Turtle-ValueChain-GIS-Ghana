# Tortoise/Turtle Value Chain GIS Analysis in Ghana

**Author:** Lawrence Kofi Amoako  
**Date:** January 2026

## Overview
This GIS project maps the value chain of tortoise and turtle products in Ghana, based on primary field survey data collected from respondents in three ecologically distinct locations:
- Half Assin (High Rainforest zone)
- Nkawkaw (Semi-Deciduous Forest zone)
- Tamale (Savannah zone)

The analysis visualizes:
- Origin-destination flows from sourcing areas to local communities, roadside markets, and urban markets
- Exploitation pressure (total annual volume per location)
- Differences in value chain structure across habitat zones
- Key intervention leverage points (convergence at roadside and urban markets)

**Important Note on Data Privacy**  
The raw survey data (CSV/Excel) used in this project is third-party primary data and **is not shared** in this repository due to confidentiality and ethical considerations. All results, maps, and diagrams are derived from aggregated and anonymized processing of the original data.

## Key Outputs
- **ValueChain_Flows_Layout.pdf / .png**: High-resolution composite thematic map (QGIS Print Layout) showing flows, pressure (point size/color), habitat zones, and labeled destinations
- **ValueChain_Flows_Final.png**: Standalone thematic map with flows, habitat colors, and key findings annotation
- **ValueChain_Flows_Sankey.png**: Sankey diagram illustrating proportional flows by habitat and chain stage

## Processed Data (Included)
GeoJSON files in `02_Processed_Data/`:
- Aggregated origin points (mean coordinates, total volume)
- Destination points (markets/roadside)
- Ghana administrative boundaries
- Agro-ecological zones

## Base Layers (Included)
Shapefiles in `03_Base_Layers/`:
- Administrative boundaries (GADM/HDX)
- Roads (OpenStreetMap via HOT)
- Agro-ecological zones (ICPAC Geoportal)

## QGIS Project
- `04_QGIS_Project/Tortoise_Turtle_ValueChain_Gis_Project.qgz`: Full QGIS project file with all styling, flows (Geometry Generator), and labels

## Tools Used
- QGIS 3.34 for spatial analysis and mapping
- Python (geopandas, matplotlib) for standalone map generation
- SankeyMATIC.com for proportional flow diagram

## Project Structure