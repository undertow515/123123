# Hydrological and Meteorological Data Analysis Project

This repository contains analysis examples using meteorological and hydrological data from Korea. It covers various hydrological analysis techniques including precipitation analysis, dam inflow analysis, and flood frequency analysis.

## 📊 Data Files

### Meteorological Data
- **`GUNSAN_GWANGJU_PRCP.zip`** - Hourly and daily precipitation and meteorological data for Gunsan and Gwangju
- **`ks_1972_current_hourly_prcp_asos.csv`** - Hourly precipitation data from Gunsan ASOS station (1972 - September 2025)
  - Data source: Korea Meteorological Administration ASOS (Automated Synoptic Observing System)
  - Note: Missing values may exist
- **`ks_2000_2024_hourly_prcp_aws.csv`** - Hourly precipitation data from Gunsan AWS (2000-2024)
  - Data source: Korea Meteorological Administration AWS (Automated Weather Station)
  - Note: Missing values may exist
- **`ks_2025_hourly_prcp_aws.csv`** - Hourly precipitation data for Gunsan in 2025

### Hydrological Data
- **`daminflow.zip`** - Daily inflow data from 10 multipurpose dams in Korea
- **`soyanggang_dam.csv`** - Monthly inflow data for Soyanggang Dam (1975 - September 2025)
  - Monthly average inflow
  - Monthly maximum inflow
  - Monthly minimum inflow

### International Data
- **`flood_example_data.csv`** - Annual maximum peak streamflow data for Maurice River at Norma NJ, USA
  - Data source: [USGS NWIS](https://nwis.waterdata.usgs.gov/nwis/peak/?site_no=01411500)
  - Example data for flood frequency analysis

## 📈 Analysis Examples (Jupyter Notebooks)

### 1. Flow Duration Curve (FDC)
- **`fdc.ipynb`** - Example of creating flow duration curves
- Analysis of flow persistence characteristics
- Statistical characterization of river flow

### 2. Intensity-Duration-Frequency (IDF) Curve
- **`idf.ipynb`** - Example of creating rainfall intensity-duration-frequency curves
- Used for design rainfall estimation
- Foundation for urban disaster prevention planning

### 3. Gaussian Mixture Model (GMM)
- **`gmm_ex.ipynb`** - Example of distribution parameter estimation using GMM
- Application of EM algorithm
- Used for SPI (Standardized Precipitation Index) calculation

## 🖼️ Additional Files
- **`image.png`** - Supporting image file for analysis documentation

## 🚀 Getting Started

### Prerequisites
```bash
# Required Python packages
pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter
```

### Data Processing Notes
1. **Missing Values**: Some meteorological data files may contain missing values. Proper data cleaning and interpolation methods should be applied before analysis.

## 📚 References

- Korea Meteorological Administration: [www.kma.go.kr](https://www.kma.go.kr)
- Korea Water Resources Corporation: [www.kwater.or.kr](https://www.kwater.or.kr)
- USGS Water Resources: [waterdata.usgs.gov](https://waterdata.usgs.gov)

## 📄 License

Please ensure compliance with data usage terms from respective organizations (KMA, K-water, USGS) when using this data for research or commercial purposes.
