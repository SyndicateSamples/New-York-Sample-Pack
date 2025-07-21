# New-York-Sample-Pack

# 🗽 NYC DEVELOPMENT DATA PACK — 2025
**Curated by Syndicate**  
*“Making the Invisible Visible”*

---

Welcome, and thanks for checking out the Syndicate NYC Data Pack.

This bundle is a cleaned, enriched, and analysis-ready set of datasets built for:

- 🏙️ Urban planners  
- 🧱 Real estate developers  
- 🧮 Estimators and consultants  
- 🧠 Civic tech teams  
- 🗂️ Data analysts focused on NYC growth and zoning

It brings together public records from multiple NYC sources, pre-joined, normalized, and packaged to save **40+ hours of prep time.**

---

## 📊 What's Inside?

> This dataset includes ZIP-level overlays of:  
> ✅ DOB permit trends (2022–2025)  
> ✅ Parcel-level zoning, land use, and FAR usage  
> ✅ Property valuation shifts (YoY AVTOT)  
> ✅ Underbuilt parcel flags (FAR gap)  
> ✅ Contractor density + permit types  
> ✅ Demographics by borough/ZIP

All data is sourced from NYC Open Data portals and agencies:
- NYC Department of Buildings (DOB)
- Department of City Planning (DCP / PLUTO)
- Department of Finance (DOF)
- U.S. Census / ACS

---

## 🗂️ File Structure
📁 DATA_CSV/
│
├── 📁 New york DOB permits
│   • Cleaned NYC DOB permit filings (2022–2025) by borough, with added approval insights and contractor tagging
│
├── 📁 NYC_pluto
│   • NYC PLUTO v25.2 full dataset (zoning, land use, FAR, units, area)
│
├── 📁 Property Val and Assessment
│   • Raw tax roll + AVTOT data (2018–2025), includes YoY values
│
├── 📄 demographics_by_zip.xlsx
│   • Demographic snapshot

├── 📄 permit_value_uplift_by_zip.csv
│   • Average property value change per ZIP vs permits filed

├── 📄 underbuilt_zip_far_gap.csv
│   • FAR utilization % by ZIP (current FAR vs max allowed FAR)


📁 VISUALS/
│
├── avg_yearbuilt_by_zip.html
│   • Interactive map: average year buildings were constructed per ZIP
│
├── density_scatter_units_vs_lotarea.png
│   • Chart: residential units vs lot area, by land use type
│
├── land_use_breakdown_by_zip.html
│   • Choropleth: share of land zoned residential by ZIP code
│
├── permit_type_pie.png
│   • Pie chart: distribution of job types in DOB filings
