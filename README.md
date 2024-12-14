# ECMWF Model Verification Project

This project analyzes the accuracy of ECMWF's 500mb geopotential height forecasts by comparing them against verification data and climatology.

## What We Did
We checked how good the ECMWF model is at predicting 500mb heights by:
- Looking at forecasts from 0 to 240 hours out
- Comparing different model runs
- Testing against climatology 
- Checking how temperature forecasts perform too

## Getting Started
You'll need these Python packages:
```
herbie
pandas
xarray
cartopy.crs
cartopy.feature
matplotlib.pyplot
numpy
cdsapi
os
matplotlib.colors import
LinearSegmentedColormap
ListedColormap
sklearn.metrics
math
```

## Data Sources
- ECMWF operational model data (using Herbie)
- ERA5 reanalysis and for climatology

## Key Features
- Downloads and processes ECMWF forecast data
- Makes nice plots showing how errors grow over time
- Compares different model runs
- Shows where the model does better or worse using maps
- Tests if the model beats climatology (spoiler: it does!)

## Example Plots
- RMSE over time
- Error distribution maps
- Model vs Climatology comparisons
- Multi-run analysis

## Project Structure
```
.
├── Submission1.ipynb         # Data acquisition and initial plots
├── Submission2.ipynb         # Analysis and visualization
└── README.md                 # You are here
```

## Authors
- Eric Zack
- Daniel Nour

## License
MIT License

## Acknowledgments
Thanks to the Herbie library for making ECMWF data access way easier!

---
Note: This is part of a class project for METEO 473.