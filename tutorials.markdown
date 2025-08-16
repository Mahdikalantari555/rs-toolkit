# Tutorials

This document provides an overview of tutorials available in the **rs-toolkit** repository. Each section corresponds to a folder in the repository, with notebooks designed to teach specific remote sensing tasks.

## 1. Basic Raster and Vector Operations
- **01_open_raster_with_rasterio.ipynb**: Learn to open and read raster files using rasterio.
- **02_visualize_raster_matplotlib.ipynb**: Visualize raster data with matplotlib.
- **03_clip_raster_with_shapefile.ipynb**: Clip a raster using a vector shapefile.
- **04_calculate_indices.ipynb**: Compute common remote sensing indices (e.g., NDVI, NDWI).
- **05_basic_statistics_raster.ipynb**: Calculate basic statistics (mean, std, etc.) for raster data.
- **06_reproject_resample_raster.ipynb**: Reproject and resample raster data to different CRS or resolutions.
- **07_overlay_vector_on_raster.ipynb**: Overlay vector data on raster for visualization.

## 2. Data Preprocessing
- **atmospheric_correction_snap.ipynb**: Perform atmospheric correction using SNAP.
- **cloud_masking.ipynb**: Apply cloud masking to satellite imagery.
- **mosaicking_rasters.ipynb**: Combine multiple rasters into a single mosaic.
- **normalization_scaling.ipynb**: Normalize and scale raster data for ML.

## 3. Classical Machine Learning
- **classification_rf_svm.ipynb**: Implement Random Forest and SVM for classification.
- **kmeans_clustering.ipynb**: Perform K-means clustering on remote sensing data.
- **feature_selection.ipynb**: Select important features for ML models.

## 4. Deep Learning
- **unet_segmentation.ipynb**: Use U-Net for semantic segmentation of satellite imagery.
- **landcover_classification_cnn.ipynb**: Classify land cover using a convolutional neural network.
- **change_detection_with_dl.ipynb**: Detect changes in imagery using deep learning.

## 5. Data Download
- **download_sentinel_sentinelsat.ipynb**: Download Sentinel data using sentinelsat.
- **download_landsat_landsatxplore.ipynb**: Access Landsat imagery with landsatxplore.
- **gee_python_api.ipynb**: Use Google Earth Engine’s Python API to access datasets.

## 6. Visualization
- **folium_interactive_map.ipynb**: Create interactive maps with Folium.
- **geopandas_plotting.ipynb**: Plot vector data with GeoPandas.
- **kepler_gl_demo.ipynb**: Visualize geospatial data with Kepler.gl.

## Next Steps
- Start with the `1_basic_raster_vector` section to build foundational skills.
- Check `useful_links.md` for datasets and resources to practice with.