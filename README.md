# pokerstars-tilt

Project to analyze “tilt” behavior after a big loss in PokerStars cash games, using anonymized hand histories.

## Repository structure
- `notebooks/` : Google Colab notebooks (data cleaning, EDA, machine learning)
- `outputs/` : exported figures/tables 
- `reports/` : report documents (PDF)
- `data/` : data instructions only (large dataset stored on Google Drive)

## Data (Google Drive)
The full dataset is too large for GitHub (several GB) and is stored on Google Drive.

- Download link: (https://drive.google.com/drive/folders/1TX9ygOr8ompO3Mt2H607s-LVGbYkALuQ?usp=sharing)
- After downloading, follow the instructions in `data/README_data.md`.

## How to run (Google Colab)
1. Open the notebooks from `notebooks/` in Google Colab.
2. Mount Google Drive.
3. Download the dataset from Google Drive (link above) and keep the same folder structure.
4. Run notebooks in this order:
   1) `notebooks/data_cleaning_final.ipynb`  
   2) `notebooks/EDA_final.ipynb`  
   3) `notebooks/ML_final.ipynb`


