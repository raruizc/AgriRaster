# AgriRaster: Raster Data Analysis - NDVI, Interpolation, and Clustering
Project Description
This repository contains a Jupyter notebook (AgriRaster.ipynb) that performs raster data analysis, focusing on the calculation of the Normalized Difference Vegetation Index (NDVI), interpolation, and clustering using unsupervised learning techniques. The project is designed to work with satellite or drone imagery and utilizes libraries such as rasterio, numpy, matplotlib, sklearn, and pykrige for data processing and analysis.

# Repository Contents
AgriRaster.ipynb: Jupyter notebook containing the code for raster data analysis. It includes loading images, calculating NDVI, data interpolation, and clustering using DBSCAN.


# Requirements
To run the Jupyter notebook, you will need to install the following Python libraries:


pip install rasterio numpy matplotlib scikit-learn pykrige requests

# Code Structure

1. Library Import: Necessary libraries for raster data analysis, visualization, and clustering are imported.

2. Image Download: A satellite image is downloaded from OpenAerialMap.

3. Raster Image Loading: The raster image is loaded from a local file.

4. Region of Interest (ROI) Definition: A region of interest (ROI) within the raster image is defined.

5. ROI Reading and Processing: The ROI is read and processed.

6. Image Visualization: The raster image is visualized using matplotlib.

7. NDVI Calculation: NDVI is calculated from the spectral bands of the image.

8. Interpolation: Data interpolation is performed using Kriging.

9. Clustering: The DBSCAN algorithm is applied to perform clustering on the raster data.
