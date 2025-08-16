# Installation Guide

This guide provides detailed steps to set up the **rs-toolkit** repository on your local machine.

## Prerequisites
- **Python**: Version 3.8 or higher.
- **Git**: For cloning the repository.
- **System dependencies**: GDAL for geospatial operations (see below for installation).

## Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/rs-toolkit.git
   cd rs-toolkit
   ```

2. **Create a virtual environment** (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Python dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Install GDAL** (required for rasterio and geopandas):
   - **Ubuntu**:
     ```bash
     sudo apt-get install gdal-bin python3-gdal
     ```
   - **Windows**: Download pre-built binaries from [GDAL](https://gdal.org/download.html) or use a package manager like `conda`.
   - **MacOS**:
     ```bash
     brew install gdal
     ```

5. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

## Troubleshooting
- If `rasterio` fails to find GDAL, ensure the GDAL binaries are in your system’s PATH.
- For Google Earth Engine (GEE), authenticate using:
  ```bash
  earthengine authenticate
  ```

Refer to `tutorials.md` for guidance on running specific notebooks.