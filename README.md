# GIS + Remote Sensing + GeoAI Lab

A hands-on portfolio showcasing smart geospatial annotation, segmentation, and AI-driven mapping using open-source tools and remote sensing data.

---

## Overview

This lab brings together GIS, remote sensing, and GeoAI techniques using Python libraries and cloud-native tools. It includes:
- Automated segmentation using Segment Anything (SAM)
- LiDAR point cloud annotation with PDAL
- Satellite image classification with PyTorch + TorchGeo
- Remote sensing visualization using geemap and Google Earth Engine (Python API)
- Classic digital image processing with OpenCV

---

## Tools & Libraries Used

- `geemap`, `earthengine-api`
- `samgeo`, `segment-geospatial`, `segmentation-models-pytorch`
- `torchgeo`, `pytorch`, `rasterio`, `xarray`, `rioxarray`
- `PDAL`, `OpenCV`, `geopandas`, `leafmap`, `duckdb`
- Google Colab & Jupyter

---

## Project Structure

| Folder | Description |
|--------|-------------|
|`notebooks/`|Main GeoAI workflows in Colab notebooks|
|`scripts/`|Python helper functions and pipelines|
|`data/`|Links or instructions to download sample datasets|
|`outputs/`|Predictions, segmented images, and maps|
|`models/`|Saved model files (optional download links)|
|`docs/`|Project writeups, QA checklists, and resources|

---

## Notebooks Included

- `geemap_workflow.ipynb`: Visualizing and preparing RS data using geemap & GEE Python API  
- `samgeo_segmentation.ipynb`: Auto-labeling with Segment Anything on satellite images  
- `geoai_model_training.ipynb`: Training a UNet model using TorchGeo  
- `lidar_annotation_pdal.ipynb`: Ground/vegetation classification using PDAL  
- `opencv_rs_image_processing.ipynb`: Traditional image enhancement for RS workflows
  
---

## Learning Sources

This repo is built using knowledge and techniques from:
- [AI for Good 2025 – samgeo workshop](https://samgeo.gishub.org/workshops/AIforGood_2025/)
- [OpenGeoAI Workshop 2025](https://opengeoai.org/workshops/GeoAI_Workshop_2025/)
- [geemap documentation](https://geog-312.gishub.org/book/geospatial/geemap.html#overview)
- [PDAL Workshop](https://pdal.io/en/stable/workshop/agenda.html)
- [Geo.University - DIP with OpenCV](https://www.geo.university/courses/digital-image-processing-with-opencv-in-python)

---

## Goals

- Build pixel-perfect labels using automated and manual methods
- Train & validate segmentation models on open RS datasets
- Deliver reproducible pipelines using open-source GeoAI tools

---

# Folder Structure
```
gis-rs-geoai-lab/
│
├── notebooks/                        # Colab or Jupyter notebooks for each workflow
│   ├── geemap_workflow.ipynb
│   ├── samgeo_segmentation.ipynb
│   ├── geoai_model_training.ipynb
│   ├── lidar_annotation_pdal.ipynb
│   └── opencv_rs_image_processing.ipynb
│
├── data/                             # Sample or linked data sources (small test sets or links)
│   └── README.md                        # Instructions to download data (e.g., GEE, open LiDAR sets)
│
├── scripts/                          # Python scripts or utility functions
│   ├── preprocess_utils.py
│   ├── annotation_pipeline.py
│   └── model_utils.py
│
├── outputs/                          # Sample outputs like maps, model predictions, or masks
│   ├── segmented_buildings.png
│   └── lidar_ground_classification.laz
│
├── models/                           # Saved model files or links to Google Drive/Weights
│   └── unet_building_segmentation.pt
│
├── docs/                             # Diagrams, markdown files, design notes
│   └── annotation_QA_checklist.md
│
├── requirements.txt                  # All required packages and versions
├── environment.yml                   # Optional conda env (if applicable)
├── README.md                         # Project overview and guide
└── LICENSE                           # Optional (MIT or CC-BY recommended)
```
