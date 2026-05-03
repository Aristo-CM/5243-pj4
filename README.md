# 5243-pj4
# Music Genre Classification Project

## Project Overview
This project classifies music genres using machine learning.  
It uses the musicData.csv dataset and includes:  
- Data cleaning  
- Exploratory Data Analysis (EDA)  
- Feature engineering and PCA  
- Training and comparing 6 models (Random Forest, SVM, XGBoost, Neural Network, AdaBoost, Logistic Regression)  

The best model is chosen by macro F1-score.

## Main Files
- musicData.csv (original data)  
- music_cleaned.csv (cleaned data)  
- music_feature_engineered.csv.gz (feature-engineered data)  
- music_pca.csv (PCA results)  
- proj4_data_cleaning.ipynb  
- proj4_eda.ipynb  
- PCA.ipynb  
- music_models.ipynb  

## Requirements
Install these packages (Python 3.8 or higher):

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost joblib
```
## How to Run the Code

1. Put all files in the same folder.

2. Run proj4_data_cleaning.ipynb first (creates music_cleaned.csv).

3. (Optional) Run proj4_eda.ipynb to see data analysis.

4. Run PCA.ipynb (creates music_feature_engineered.csv.gz and music_pca.csv).

5. Run music_models.ipynb last (trains the models and shows results).

Run order: data cleaning → EDA (optional) → PCA → models

Note:

· SVM and Neural Network may take a few minutes.

· Output files (models, plots, reports) are saved automatically.

· If a file is missing, rerun the related notebook.
