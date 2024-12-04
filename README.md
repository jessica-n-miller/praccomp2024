# praccomp2024
## PCA and GLM Analysis of Hurricane Effects on Oceanographic Data

This project applies Principal Component Analysis (PCA) and Generalized Linear Models (GLMs) to oceanographic buoy data and fish abundance data to investigate the influence of Hurricane Earl (2010).

---

## Data Sources

- Oceanographic buoy data: [NOAA Buoy Data Center](https://www.ndbc.noaa.gov/station_history.php?station=bftn7)

---

## Dependencies

Install the following R packages to run the analysis:

```R
install.packages(c("dplyr", "lubridate", "FactoMineR", "factoextra", "MASS"))
```

## Usage

- Clone or download the repository.
- Ensure the `bftn7h2010.txt` file is in the working directory.
- Knit the .Rmd file to an HTML or PDF report for a full analysis.
- Data can be changed out for other buoy data .txt files provided the headers match. For each change in storm, the selected weeks before/after each storm must be changed in the code to account for the new storm date (lines 81-96).

## Steps

1. Data Preparation
- Load and filter buoy data for valid environmental readings.
- Assign weeks to the dataset and filter periods before and after Hurricane Earl.

2. Dimensionality Reduction (PCA)
- Perform PCA on the buoy data to reduce variables.
- Generate visualizations for PCA results (e.g., biplots and scree plots).
- Analyze data separately for periods before and after the hurricane.
