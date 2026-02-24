# HW #1 - Reproducible Time-Series Analysis, Temporal Scaling, and Visualizations

## Overview

This repository contains a reproducible time-series analysis of daily USGS streamflow data from four Utah gaging stations. The project evaluates how temporal aggregation (daily, weekly, monthly) affects interpretation of snowmelt-driven hydrologic behavior.

Study period: Water Years 2015–2020 (Oct 2014 – Sept 2020).

This repository contains data of streamflow from:

- Lake Fork River at/above Moon Lake, UT
(North of Duchesne, UT)
USGS Site Number 09289500

- Green River near Jensen, UT
(East of Vernal, UT)
USGS Site Number 09261000

- Colorado River at Potash, UT
(West of Moab, UT)
USGS Site Number 09185600

- Colorado River near Cisco, UT
(East of Moab, UT)
USGS Site Number 09180500

---

## Repository Structure

reproducible-streamflow-analysis/

── data/

   └── 09289500_1980_2020.csv

   └── 09261000_1980_2020.csv

   └── 09185600_1980_2020.csv

   └── 09180500_1980_2020.csv

── notebooks/

   └── Reproducible_Streamflow_Analysis.ipynb

── Py310_HW1.yml

── README.md

── .gitignore

---

## Environment Setup

Create the Conda environment:

### On CHPC

```bash
module load miniconda3
conda env create -f Py310_HW1.yml
conda activate Py310_HW1
```

### Local Machine

```bash
conda env create -f Py310_HW1.yml
conda activate Py310_HW1
```

---

## Required Packages

- Python 3.10
- pandas
- matplotlib
- ipykernel

All dependencies are specified in `Py310_HW1.yml`.

---

## Running the Analysis

1. Activate the environment:

```bash
conda activate Py310_HW1
```

2. Open:

notebooks/Reproducible_Streamflow_Analysis.ipynb

3. Select kernel:

Py310_HW1

4. Run all cells sequentially to reproduce figures and results.

---

## Author

Magnus Tveit  
CVEEN 6920 – Hydroinformatics  
University of Utah
