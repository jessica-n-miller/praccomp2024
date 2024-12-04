# praccomp2024
## PCA and GLM Analysis of Hurricane Effects on Oceanographic Data

This project applies Principal Component Analysis (PCA) and Generalized Linear Models (GLMs) to oceanographic buoy data and fish abundance data to investigate the influence of Hurricane Earl (2010).

---

## Purpose

This project demonstrates:
1. Dimensionality reduction using PCA to identify patterns in buoy data.
2. Aggregation and integration of fish abundance data with environmental data.
3. Application of GLMs to explore relationships between environmental variables and fish abundance.

---

## Data Sources

- Oceanographic buoy data: [NOAA Buoy Data Center](https://www.ndbc.noaa.gov/station_history.php?station=bftn7)
- Fish abundance data: *Provided as `bridgenet.csv`*

---

## Dependencies

Install the following R packages to run the analysis:

```R
install.packages(c("dplyr", "lubridate", "FactoMineR", "factoextra", "MASS"))
