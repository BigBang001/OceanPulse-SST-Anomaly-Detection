# 🌊 OceanPulse – SST Anomaly Detection

This project analyzes **Sea Surface Temperature (SST) anomalies** by comparing satellite-based snapshot data from MODIS Aqua (April 2025) with historical climatological averages (1981–2010) provided by NOAA.

---

## Objective

To identify and visualize areas of anomalous warming or cooling in the oceans using open-source satellite datasets and climate archives.

---

## Key Features

* Combines CSV snapshot from MODIS Aqua with NetCDF climatology
* Calculates SST anomalies for April 2025
* Visualizes ocean anomalies on a global heatmap
* Uses nearest-neighbor interpolation to match different resolutions

---

## Technologies Used

* Python (pandas, xarray, netCDF4)
* seaborn and matplotlib for plotting
* Jupyter Notebook (`OceanPulse.ipynb`)

---

## Sample Outputs

### Global SST Anomaly Heatmap

![SST Anomaly Heatmap](https://github.com/user-attachments/assets/12e7b876-9484-414f-bbc7-2856538e21c3)
<br>
<br>

### Climatological SST vs April 2025 Snapshot

![SST Comparison](https://github.com/user-attachments/assets/7f6fb252-26f2-4eb5-ac68-d53e62a74a95)

---

## Data Sources

* [`MYD28M_2025-04-01_gs_250x125.SS.CSV`](https://oceancolor.gsfc.nasa.gov/) — MODIS Aqua snapshot
* [`sst.mnmean.nc`](https://www.psl.noaa.gov/data/gridded/data.noaa.oisst.v2.html) — NOAA monthly SST climatology

---

## Educational Value

Created for the **Data Science in Oceanography Undergraduate Summer Program** by the University of Washington, this project helps showcase:

* Interest in oceanography
* Skill with real-world climate datasets
* Capability with Python data science tools

---

## ✨ How to Use

1. Clone this repo or download the notebook.
2. Download the required datasets:
   - [MODIS Aqua SST Snapshot (April 2025)](https://oceancolor.gsfc.nasa.gov/)
   - [NOAA Monthly Climatology NetCDF (`sst.mnmean.nc`)](https://downloads.psl.noaa.gov/Datasets/noaa.oisst.v2/sst.mnmean.nc)
3. Place them in the same directory as the notebook.
4. Run `OceanPulse.ipynb` in Google Colab or Jupyter Lab.
5. Explore the SST anomaly plots!

---
