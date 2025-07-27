# GIS + Remote Sensing + GeoAI Lab

A hands-on portfolio showcasing smart geospatial annotation, segmentation, and AI-driven mapping using open-source tools and remote sensing data.

---

## Overview

This lab brings together GIS, remote sensing, and GeoAI techniques using Python libraries and cloud-native tools. It includes:
- Automated segmentation using Segment Anything (SAM)
- LiDAR point cloud annotation with PDAL
- Satellite image classification with PyTorch + TorchGeo
- Remote sensing visualization using geemap and Google Earth Engine (Python API)
- Digital image processing with OpenCV

---

## Tools & Libraries Used

- `geemap`, `earthengine-api`
- `samgeo`, `segment-geospatial`, `segmentation-models-pytorch`
- `torchgeo`, `pytorch`, `rasterio`, `xarray`, `rioxarray`
- `PDAL`, `OpenCV`, `geopandas`, `leafmap`, `duckdb`
- Google Colab & Jupyter

---

## Notebooks will include

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
