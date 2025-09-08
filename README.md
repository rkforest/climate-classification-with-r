# Global Climate Classification Changes

 This project uses **ERA5 reanalysis climate data** to compare a *Recent Climate Period (2015–2024)* with the *WMO Climatological Standard Reference Period (1961-1990)*.  It will compute and visualize climate classification changes using the Köppen and Trewartha classification systems.

Author: Rick Forest  

![Positron IDE](https://img.shields.io/badge/Editor-Positron-blue?logo=rstudio)
![R](https://img.shields.io/badge/R-Programming-blue?logo=r)
![Python](https://img.shields.io/badge/Python-Programming-green?logo=python)
![Quarto](https://img.shields.io/badge/Quarto-Publishing-orange?logo=quarto)

---

## Overview

 The primary outputs of this project are:
  + tables summarizing:
    + recent and reference period temperature and precipitation data
    + derived climate classification metrics for each period
    + climate group classification results for each period
    + classification shifts, comparing recent and reference periods
  + global maps visualizing:
    + reference period climate data, and changes in the recent period
    + climate classification group results for each classification method
    + classifications shifts, comparing recent and reference periods

This project uses **ERA5 reanalysis climate data**.

---

## Workflow  

This project uses a multi-step pipeline::

1. **Download ERA5 Data** – 
  + Download and save ERA5 climate reanalysis datasets.
2. **Compute Climate Normals** – 
  + Compute climate period averages (temperature & precipitation).
3. **Derive Classification Metrics** – 
  + Derive aggregate seasonal/annual statistics required for classification.
4. **Apply Classification Systems**
  + Apply Koppen and Trewartha classification definitions to all grid cells.  
5. **Analyze Classification Shifts**
  + Compare zones across periods to identify changes.  

---

## Tools  

- **Python** – Downloading and import  
- **R** – Analysis and visualization  
- **Positron IDE** – Development environment  
- **Quarto** – Reproducible reporting and publishing  

---