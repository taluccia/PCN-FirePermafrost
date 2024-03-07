# PCN-FirePermafrost

## Overview


## Scripts

### Data prep Steps

1. `DataCleanToPointCombine.Rmd` --- This script takes each data contribution and checks abnormalities and formatting issues. It fixes any issues. Data is then combines into a single data frame and converted in to a spatial data set and saved as a shapefile. 
2. `SpatialAddsDatacube.Rmd` ---This scripts takes the output from step 1 and adds some spatial attributes including ecozones from 
3. `ERA5GeeScript.Rmd` --- GEE Script for pulling ERA5 data using JavaScript Code editor.
4. `ERA5CleanOrganizeData.Rmd` --- Take EE ERA5 Land Temperature data and organize it into a single csv
 
### QAQC
1. 

### Analysis

5. `PredictAltMeasurements.Rmd` --- Take

### Figures

1. `FigureOverviewMap.Rmd` --- overview map with permafrost distribution and data site contribution summaries
2. `FigurePredictedVsMeasured.Rmd` --- figures looking at the distribution of measured versus predited active layer thickness


## Methods


