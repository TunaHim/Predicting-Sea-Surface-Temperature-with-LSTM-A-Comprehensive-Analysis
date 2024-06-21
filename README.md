# Predicting-Sea-Surface-Temperature-with-LSTM-A-Comprehensive-Analysis
(Satellite Data - 30 yrs - EDA - LSTM)

## Project Overview
This project involves the analysis and prediction of sea surface temperature (SST) using a Long Short-Term Memory (LSTM) model. The dataset used for this project comes from the CMEMS Data repository and contains monthly measurements of various oceanographic variables such as mixed layer temperature, sea surface salinity, and geopotential height for North West European Shelf region. The primary focus is on predicting the SST and analyzing its trends and anomalies over time.

## Outline of the Notebook
#####     Data Loading and Preprocessing
#####     Exploratory Data Analysis
#####     Time Series Analysis
#####     Anomaly Detection
#####     LSTM Model for SST Prediction
#####     Results

#### Installation: 
To run the code in this repository, you need to install the required dependencies. 
One can install them using pip: "pip install numpy xarray matplotlib seaborn cartopy cmocean tensorflow"

#### Data:
The data used in this project is available from the Copernicus Marine Environment Monitoring Service (CMEMS) 
The product is available at: https://data.marine.copernicus.eu/product/NWSHELF_MULTIYEAR_PHY_004_009/description
and can be downloaded from the following link:
https://data.marine.copernicus.eu/product/NWSHELF_MULTIYEAR_PHY_004_009/download?dataset=cmems_mod_nws_phy-sst_my_7km-2D_PT1H-i_202112
. This is also directly available as "dataset-armor-3d-rep-monthly_1717495414175.nc" in this repository.  

#### Future Work: 
Future enhancements could involve:
##### > Experimenting with different model architectures and hyperparameters.
##### > Incorporating additional oceanographic variables.
##### > Extending the prediction horizon and analyzing multi-step forecasts.
