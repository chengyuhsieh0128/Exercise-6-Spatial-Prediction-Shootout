# Exercise-6-Spatial-Prediction-Shootout

Week 6 assignment for spatial rainfall prediction using four interpolation methods:

- Ordinary Kriging
- Random Forest
- Nearest Neighbor
- Inverse Distance Weighting (IDW)

## Contents

- `Week6-Student.ipynb`: completed notebook
- `fungwong_202511.json`: rainfall station data
- `interpolation_shootout.png`: 4-method comparison
- `kriging_vs_rf.png`: Kriging vs Random Forest comparison
- `sigma_map.png`: Kriging estimate and uncertainty map
- `nugget_comparison.png`: nugget effect comparison
- `kriging_rainfall.tif`, `kriging_variance.tif`, `rf_rainfall.tif`: raster outputs
- `鄉(鎮、市、區)界線1140318/`: township boundary shapefile used for zonal statistics

## Main Tasks

1. Parse rainfall station data and filter the Hualien-Yilan study area.
2. Build variograms and compare raw rainfall vs log-transformed rainfall.
3. Generate rainfall surfaces with Kriging, Random Forest, NN, and IDW.
4. Compare interpolation patterns and analyze Kriging uncertainty.
5. Export GeoTIFF rasters and summarize township-level statistics.

## How to Run

Open `Week6-Student.ipynb` in Jupyter Notebook or JupyterLab, install the required packages in the first code cell, then run all cells from top to bottom.
