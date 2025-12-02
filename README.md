🌍 Satellite Analysis — CartoDEM & NDVI

A complete geospatial analysis workflow using CartoDEM (Digital Elevation Model) and NDVI (Vegetation Index) datasets.
This project demonstrates terrain modeling, vegetation health assessment, and satellite-based environmental insights using Python and modern GIS tools.

📌 Overview

This repository contains Jupyter notebooks and scripts for analyzing two key satellite datasets:

1. CartoDEM (Terrain Analysis)

Extracting elevation values

Generating hillshade

Creating slope and aspect maps

Understanding terrain characteristics

Interpreting landform features

2. NDVI (Vegetation Analysis)

Preprocessing satellite bands

Computing NDVI using Red & NIR bands

Classifying vegetation health

Visualizing spatial vegetation patterns

All raw .tif files are excluded from GitHub due to large size — only analysis notebooks, scripts, and documentation are included.

📁 Repository Structure
satellite_analysis/
│
├── data/
│   ├── cartodem/        ← Raw CartoDEM files (local only, ignored by Git)
│   ├── ndvi/            ← Raw NDVI files (local only, ignored by Git)
│   └── README.md
│
├── notebooks/
│   ├── CartoDEM_Analysis.ipynb
│   ├── ndvi.ipynb
│
├── results/
│   └── (empty for now — generated maps will be stored here)
│
├── docs/
│   ├── policy.txt
│   ├── readme.txt
│
├── scripts/
│   ├── (processing scripts if added later)
│
├── .gitignore
└── README.md

🛠 Technologies & Libraries

Python 3.x

Rasterio

GDAL

NumPy / Pandas

Matplotlib / Plotly

Jupyter Notebook

GIS & Remote Sensing Concepts

🚀 How to Run the Project
1. Clone the Repository
git clone https://github.com/Nish232003/satellite_analysis.git
cd satellite_analysis

2. Install Dependencies
pip install -r requirements.txt

3. Add Raw Satellite Data

Place your .tif or dataset folders inside:

data/cartodem/
data/ndvi/


These files are ignored by GitHub automatically.

4. Run Jupyter Notebooks
jupyter notebook


Open:

CartoDEM_Analysis.ipynb

ndvi.ipynb

📊 Outputs

Generated maps and figures (such as):

Hillshade

Elevation model

Slope & aspect maps

NDVI map

Vegetation classification

will be saved into the results/ folder.

🔍 Data Sources

CartoDEM: ISRO / NRSC (Bhuvan Portal)

NDVI: Landsat / Sentinel-2 (USGS Earth Explorer / Copernicus Open Data)

Raw data is not stored in this repository due to size limits and licensing restrictions.

🎯 Purpose of This Project

This project showcases real-world satellite analytics including:

Terrain interpretation

Environmental monitoring

Vegetation health analysis

Remote sensing workflow

GIS-based decision making

It serves as a strong portfolio piece for roles in:
GIS, Remote Sensing, Data Science, Geospatial Analytics, and Research.