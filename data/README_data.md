# Data (Google Drive)

The full dataset is stored on Google Drive (large files, not suitable for GitHub).

## Link
https://drive.google.com/drive/folders/1TX9ygOr8ompO3Mt2H607s-LVGbYkALuQ?usp=sharing

## Expected structure
The Drive folder contains a `data/` directory with subfolders for each stake.

## Usage in Google Colab
1. Mount Google Drive.
2. Make sure your notebook reads the dataset from your Drive path, e.g.
   `/content/drive/MyDrive/.../data/`
3. Run notebooks in this order:
   1) `notebooks/data_cleaning_final.ipynb`
   2) `notebooks/EDA_final.ipynb`
   3) `notebooks/ML_final.ipynb`

