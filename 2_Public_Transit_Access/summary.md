# 📍 Public Transit Access Mapping

## 🔍 Objective
To evaluate the spatial coverage of public transit stops and identify underserved areas based on walking distance thresholds in an urban environment.

## 🧰 Tools & Techniques Used
- ArcGIS Pro
- Buffer analysis (e.g. 400m or 800m walk distance)
- Select Layer By Location
- Map symbology and labeling
- Layout view for PDF map export

## 📊 Data Sources
- Transit stops: Local transit agency (GTFS) or open data portal
- Population or land use data: U.S. Census TIGER/Line or city open data
- Basemap: OpenStreetMap or Esri default basemap

## 📌 Key Steps
1. Imported point feature layer of public transit stops
2. Generated buffers to represent a 5 or 10-minute walk radius
3. Overlaid buffers with population or land use layers
4. Highlighted areas lacking transit coverage
5. Designed map layout with legend, scale, and north arrow

## 🖼️ Output
- `Public_Transit_Accessibility.pdf`: Map visualizing transit buffer coverage
- Screenshot of buffer tool dialog and map layout
- (Optional) Table summarizing population coverage

## 🧠 Skills Demonstrated
- Geoprocessing with buffers and spatial queries
- Visual storytelling with map design
- Understanding of accessibility planning
- Exporting and presenting GIS findings professionally
