NDVI Visualization for Pakistan using Google Earth Engine
This script generates an animated time series of NDVI (Normalized Difference Vegetation Index) from MODIS data for Pakistan, using Google Earth Engine. Key functionalities include:

Mask Creation: Filters spatial data to the boundaries of Pakistan.
NDVI Data Processing: Retrieves MODIS NDVI images from 2018 to 2020, extracting day-of-year (DOY) metadata for temporal analysis.
Image Clipping and Visualization: Clips NDVI images to Pakistan's boundary and applies a color palette to represent vegetation health, from very low to very high NDVI levels.
Animated Thumbnail: Generates an animated GIF of the NDVI time series for the selected time range.
Legend Creation: Adds a legend panel to display NDVI levels with color codes.
