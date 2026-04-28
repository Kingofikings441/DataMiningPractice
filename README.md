# Data Mining Practice Repository
# 🌍 Decoding the European Airbnb Market: Spatial Analysis & Pricing Anomalies

## Project Summary
This project applies spatial machine learning techniques—including clustering and anomaly detection—to uncover the hidden geographic structures driving Airbnb prices across multiple European cities.

## Research Questions
* What actually drives Airbnb prices, and can we detect patterns or anomalies in how hosts price their listings?
* Does geographic information improve our ability to predict Airbnb prices, and what specific type of spatial data matters most?

## Project Video
[\[video\]](https://www.youtube.com/watch?v=idLhEnTvfCw)

## Data
* **Source:** The raw data for this analysis was obtained from Zenodo:
  > Gyódi, K., & Nawaro, Ł. (2021). *Determinants of Airbnb prices in European cities: A spatial econometrics approach (Supplementary Material)* [Data set]. Zenodo. https://doi.org/10.5281/zenodo.4446043

* **Preprocessing:** Is handled inside of main notebook

## How to Reproduce
This project was developed locally using **VSCode**. To reproduce the analysis:
1. Clone this repository.
2. Download the raw CSV data files from Zenodo and place them inside the `data/` directory.
3. Install the required dependencies by running `pip install -r requirements.txt`.
4. Open `main_notebook.ipynb` in VSCode and execute the cells in sequential order. 
*(Note: The `checkpoints/` directory contains earlier progression files, but the final, curated analysis lives entirely in `main_notebook.ipynb`)*.

## Key Dependencies
* Python 3.10+
* pandas 
* numpy 
* scikit-learn 
* matplotlib 
* seaborn 
*(See `requirements.txt` for the full environment export).*

## Repository Structure
```text
├── checkpoints/          # Checkpoints from the semester 
│   ├── checkpoint_1.ipynb
│   └── checkpoint_2.ipynb
├── data/                 # Data directory (instructions for download)
├── main_notebook.ipynb   # Final curated analysis
├── requirements.txt      # Full environment export
├── .gitignore            # Excluded files
└── README.md             # Project documentation