# Investigating Regional and Temporal Responses of Vegetation Optical Depth to Precipitation Anomalies in Northern Australia and the Sahel

## Question / Hypotheses
**Research Question:** How seasonal precipitation anomalies influence vegetation optical depth (VOD) across two climatically contrasting regions: the tropical savannas of northern Australia and the Sahel region of northern Africa? 

**Hypothesis 1:** The strength and pattern of the VOD response to precipitation anomalies differ between these two regions due to differences in ecosystem structure and rainfall seasonality.  
**Hypothesis 2:** VOD exhibits a lagged response to precipitation anomalies, and the optimal lag period varies between regions.

## Datasets Used
1. **GLAB-VOD Vegetation Optical Depth (2002–2020)**  
   - Format: Zarr  
   - Access: `gs://leap-persistent/data-library/GLAB-VOD/GLAB-VOD.zarr`  
   - Period used: **2002–2020**
2. **CHIRPS Daily Global Precipitation (1981–present)**  
   - Format: Zarr  
   - Access: `https://nyu1.osn.mghpcc.org/leap-pangeo-pipeline/chirps_feedstock/chirps-global-daily.zarr`  
   - Period used: **2002–2020** (to match GLAB-VOD)

## Project Summary
We will subset and analyze CHIRPS and GLAB-VOD datasets for the period 2002–2020, focusing on two study regions—northern Australia and the African Sahel. Monthly precipitation anomalies will be computed based on a 2002–2011 climatology, and compared with VOD to quantify their statistical relationships. The analysis will include inter-regional comparisons and lagged correlation analyses to determine the temporal dynamics of vegetation response to hydrological variability.
