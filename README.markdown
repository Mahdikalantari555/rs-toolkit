# rs-toolkit: Remote Sensing Learning Lab and Toolkit

## Description

The **rs-toolkit** is a personal learning lab and toolkit for remote sensing, focusing on Python and AI/ML applications. It contains Jupyter notebooks and scripts covering fundamental tasks in remote sensing, from basic raster and vector operations to advanced machine learning and deep learning techniques. This repository is designed to be educational, extensible, and a reference for remote sensing enthusiasts.

## Motivation

This repository serves as a personal learning hub to:
- Master remote sensing workflows using Python.
- Explore AI and machine learning applications in remote sensing, such as classification, segmentation, and change detection.
- Document and share reproducible code for common remote sensing tasks.
- Build a foundation for advanced geospatial analysis and research.

## Repository Structure

All Jupyter notebooks are located in the `notebooks/` folder, organized by topic for clarity. Other files include documentation and requirements.

| Folder/File | Description |
|-------------|-------------|
| **notebooks/** | Contains all Jupyter notebooks for remote sensing tasks (see table below). |
| **utils/** | Shared utility scripts for common functions (e.g., data loading, preprocessing). |
| **docs/** | Documentation including installation guides, tutorials, and useful links. |
| **requirements.txt** | Python libraries required for the notebooks. |
| **README.md** | Overview and setup instructions. |

### Notebooks Overview

| Notebook | Description |
|----------|-------------|
| **Basic Raster and Vector Operations** | |
| 01_open_raster_with_rasterio.ipynb | Open and read raster files using rasterio. |
| 02_visualize_raster_matplotlib.ipynb | Visualize raster data with matplotlib. |
| 03_clip_raster_with_shapefile.ipynb | Clip a raster using a vector shapefile. |
| 04_calculate_indices.ipynb | Compute remote sensing indices (e.g., NDVI, NDWI). |
| 05_basic_statistics_raster.ipynb | Calculate basic statistics for raster data. |
| 06_reproject_resample_raster.ipynb | Reproject and resample raster data. |
| 07_overlay_vector_on_raster.ipynb | Overlay vector data on raster for visualization. |
| **Data Preprocessing** | |
| 08_atmospheric_correction_snap.ipynb | Perform atmospheric correction using SNAP. |
| 09_cloud_masking.ipynb | Apply cloud masking to satellite imagery. |
| 10_mosaicking_rasters.ipynb | Combine multiple rasters into a mosaic. |
| 11_normalization_scaling.ipynb | Normalize and scale raster data for ML. |
| **Classical Machine Learning** | |
| 12_classification_rf_svm.ipynb | Implement Random Forest and SVM for classification. |
| 13_kmeans_clustering.ipynb | Perform K-means clustering on remote sensing data. |
| 14_feature_selection.ipynb | Select important features for ML models. |
| **Deep Learning** | |
| 15_unet_segmentation.ipynb | Use U-Net for semantic segmentation of imagery. |
| 16_landcover_classification_cnn.ipynb | Classify land cover using a CNN. |
| 17_change_detection_with_dl.ipynb | Detect changes using deep learning. |
| **Data Download** | |
| 18_download_sentinel_sentinelsat.ipynb | Download Sentinel data using sentinelsat. |
| 19_download_landsat_landsatxplore.ipynb | Access Landsat imagery with landsatxplore. |
| 20_gee_python_api.ipynb | Use Google Earth Engine’s Python API. |
| **Visualization** | |
| 21_folium_interactive_map.ipynb | Create interactive maps with Folium. |
| 22_geopandas_plotting.ipynb | Plot vector data with GeoPandas. |
| 23_kepler_gl_demo.ipynb | Visualize geospatial data with Kepler.gl. |

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/rs-toolkit.git
   cd rs-toolkit
   ```

2. **Set up a virtual environment** (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Install GDAL** (required for rasterio and geopandas):
   - **Ubuntu**:
     ```bash
     sudo apt-get install gdal-bin python3-gdal
     ```
   - **Windows**: Use pre-built binaries from [GDAL](https://gdal.org/download.html) or `conda`.
   - **MacOS**:
     ```bash
     brew install gdal
     ```

5. **Run Jupyter notebooks**:
   ```bash
   jupyter notebook
   ```

## Getting Started

- Check `docs/installation.md` for detailed setup instructions.
- Explore `docs/tutorials.md` for an overview of each notebook.
- Refer to `docs/useful_links.md` for external resources and datasets.
- Start with `notebooks/01_open_raster_with_rasterio.ipynb` to build foundational skills.

## Contributing

This is a personal learning project, but contributions are welcome! Submit issues or pull requests for improvements, additional notebooks, or bug fixes.

## License

This project is licensed under the MIT License.