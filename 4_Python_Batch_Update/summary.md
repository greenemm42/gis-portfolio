# 📍 Python Script: Batch Attribute Update in ArcGIS Pro

## 🔍 Objective
To automate the process of updating attribute values across multiple features in a feature class using a Python script and the `arcpy` library in ArcGIS Pro.

## 🧰 Tools & Techniques Used
- ArcGIS Pro
- Python 3.x (built into ArcGIS Pro)
- ArcPy cursor tools (`UpdateCursor`)
- Script editor and Python window

## 📊 Data Sources
- Sample feature class with a “Status” or “Category” field (e.g., parcels, hydrants, parks)
- Editable geodatabase (file or project-based)

## 📌 Key Steps
1. Opened a feature class in ArcGIS Pro
2. Used `UpdateCursor` in `arcpy` to loop through records
3. Applied logic to update field values (e.g., reclassifying status codes)
4. Tested script in Python window
5. Validated attribute table and saved edits

## 🖼️ Output
- `update_fields.py`: Python script that modifies values in a field
- Screenshot of script running in ArcGIS Pro Python window
- Before/after view of attribute table (optional)

## 🧠 Skills Demonstrated
- Basic Python scripting with `arcpy`
- Batch processing of spatial data
- Attribute automation and data cleaning
- Version control and script documentation

