# QSS 20 Final Project

I am aiming to analyze a dataset of TikToks compiled by Professor Chang and his research team pertaining to the 2024 U.S. presidential election to discern whether music with clear political alignment can impact the virality of short-form content. Overall, my goal is to determine if music can be used to resonate with voters in a time where encouraging civic engagement is key to maintaining democracy. 

## Repository Structure

code/:
- 00_clean.ipynb
- 01_visualize.ipynb

code/data:
- top_100_tracks.csv
- top_with_politics.csv

output/:
- figure1.png
- figure2.png
- figure3.png
- figure4.png
- figure5.png
- figure6.png
- figure7.png
- figure8.png
- figure9.png
- figure10.png

README.md


> **Note on data:** 
Download the data from Dropbox here: https://www.dropbox.com/scl/fo/aq8pk2qfo4s16vd5qzjo9/AG6hRhCf8bx9QXMbvQRczj0?rlkey=kk5q19jqz9oedr3htcfqf5oy0&st=qszsb9w9&dl=0 

## Notebooks

Run in numerical order. Each notebook is listed below with what it needs, what it does, and what it produces.

### [00_clean](code/00_clean.ipynb)
- **Takes in:** master_tiktok_df.csv, tiktok_poli_pref_results.csv, data/top_100_tracks.csv
- **Does:** Cleans and merges the above datasets to create the datasets used for analysis and visualization
- **Outputs:** data/top_100_df.csv, data/top_100_tracks.csv, data/top_with_politics.csv

### [01_visualize](code/01_visualize.ipynb)
- **Takes in:** data/top_100_tracks.csv, data/top_100_df.csv, data/top_with_politics.csv
- **Does:** Produces OLS regression analyses and associated visualizations
- **Outputs:** figure1.png, figure2.png, figure3.png, figure4.png, figure5.png, figure6.png, figure7.png, figure8.png, figure9.png, figure10.png

## Requirements
Packages used: numpy, pandas, matplotlib, scipy, statsmodels
