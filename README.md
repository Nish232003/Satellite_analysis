# 🌍 Satellite Analysis — CartoDEM & NDVI

A complete geospatial analysis workflow using **CartoDEM** (Digital Elevation Model) and **NDVI** (Vegetation Index) satellite datasets.  
This project covers terrain modelling, vegetation health assessment, preprocessing, and map generation using Python and modern GIS tools.

---

## 🔎 Overview

This repository contains Jupyter notebooks and scripts for analyzing two key satellite datasets:

### **1. CartoDEM (Terrain Analysis)**
- Extracting elevation values  
- Generating hillshade  
- Creating slope and aspect maps  
- Terrain interpretation  

### **2. NDVI (Vegetation Analysis)**
- Preprocessing satellite bands  
- Computing NDVI  
- Vegetation classification  
- NDVI visualization  

Raw satellite files are excluded due to large size.

---

## 🗂 Folder Structure

```text
satellite_analysis/
│
├── data/
│   ├── cartodem/            ← Raw CartoDEM data (local only)
│   └── ndvi/                ← Raw NDVI data (local only)
│
├── notebooks/
│   ├── CartoDEM_Analysis.ipynb
│   └── NDVI_Analysis.ipynb
│
│ 
│
├── docs/
│   ├── policy.txt
│   └── readme.txt
│
├── .gitignore
└── README.md
