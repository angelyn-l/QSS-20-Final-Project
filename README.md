

The dataset used for this project exists on Professor Chang's remote server for research. The file path is: /home/shared/Elections2024/Data/1_Processed_Raw/TikTok/master_tiktok_df.csv

Within the "code" directory:
 - Test.ipynb: contains exploratory code for potential analyses and visualizations.
 - Test_music_scraping.ipynb: will (soon) contain code for scraping soundtracks from the TikToks.

# QSS 20 Final Project

I am aiming to analyze a dataset of TikToks pertaining to the 2024 U.S. presidential election to discern whether music with clear political alignment can impact the virality of short-form content. Overall, my goal is to determine if music can be used to resonate with voters in a time where encouraging civic engagement is key to maintaining democracy. 

## Repository Structure

code/:

- 00_clean.ipynb
- 01_visualize.py
- 02_[short_name].ipynb

output/:

README.md


> **Note on data:** 
Download the data from Dropbox here: https://www.dropbox.com/scl/fo/aq8pk2qfo4s16vd5qzjo9/AG6hRhCf8bx9QXMbvQRczj0?rlkey=kk5q19jqz9oedr3htcfqf5oy0&st=qszsb9w9&dl=0 

## Scripts / Notebooks

Run in numerical order. Each script/notebook is listed below with what it needs, what it does, and what it produces.

### [00_clean](code/00_script_name.py)
- **Takes in:** [e.g., raw survey CSV from `data/raw/`; API key stored in `.env` as `API_KEY`]
- **Does:** [e.g., pulls job postings data from XYZ API and saves raw JSON responses]
- **Outputs:** [e.g., `data/raw/jobs_raw.json`]

### [01_visualize](code/01_script_name.py)
- **Takes in:** [e.g., `data/raw/jobs_raw.json`]
- **Does:** [e.g., cleans and merges job postings with firm-level data]
- **Outputs:** [e.g., `data/clean/jobs_clean.csv`]

### [02_script_name](code/02_script_name.py)
- **Takes in:** [e.g., `data/clean/jobs_clean.csv`]
- **Does:** [e.g., runs regression analysis and generates summary figures]
- **Outputs:** [e.g., `output/fig1_trends.png`, `output/table1_summary.pdf`]

## Requirements
Packages used: 
