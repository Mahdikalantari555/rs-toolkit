rs-toolkit: Remote Sensing Learning Lab and Toolkit
Description
The rs-toolkit is a personal learning lab and toolkit for remote sensing, focusing on Python and AI/ML applications. It contains Jupyter notebooks and scripts covering fundamental tasks in remote sensing, from basic raster and vector operations to advanced machine learning and deep learning techniques. This repository is designed to be educational, extensible, and a reference for remote sensing enthusiasts.
Motivation
This repository serves as a personal learning hub to:

Master remote sensing workflows using Python.
Explore AI and machine learning applications in remote sensing, such as classification, segmentation, and change detection.
Document and share reproducible code for common remote sensing tasks.
Build a foundation for advanced geospatial analysis and research.

Repository Structure
The repository is organized into sections to cover different aspects of remote sensing:



Section
Description



1_basic_raster_vector
Core operations for raster and vector data (e.g., opening, visualizing, clipping, reprojecting).


2_data_preprocessing
Preprocessing techniques like atmospheric correction, cloud masking, and mosaicking.


3_classical_ml
Classical machine learning methods (e.g., Random Forest, SVM, K-means clustering).


4_deep_learning
Deep learning applications (e.g., U-Net segmentation, CNN-based classification).


5_data_download
Scripts to download satellite data from sources like Sentinel, Landsat, and Google Earth Engine.


6_visualization
Visualization techniques using Folium, GeoPandas, and Kepler.gl for interactive maps.


utils
Shared utility scripts for common functions (e.g., data loading, preprocessing).


docs
Documentation including installation guides, tutorials, and useful links.


Installation

Clone the repository:
git clone https://github.com/your-username/rs-toolkit.git
cd rs-toolkit


Set up a virtual environment (recommended):
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


Install dependencies:
pip install -r requirements.txt


Optional: For some notebooks (e.g., GDAL, rasterio), ensure you have GDAL installed on your system. On Ubuntu, use:
sudo apt-get install gdal-bin python3-gdal


Run Jupyter notebooks:
jupyter notebook



Getting Started

Check the docs/installation.md for detailed setup instructions.
Explore docs/tutorials.md for guided tutorials on each section.
Refer to docs/useful_links.md for external resources and datasets.
Start with the 1_basic_raster_vector section to build foundational skills.

Contributing
This is a personal learning project, but contributions are welcome! Feel free to submit issues or pull requests for improvements, additional notebooks, or bug fixes.
License
This project is licensed under the MIT License.
