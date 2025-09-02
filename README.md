# 🧠 Body Fat Percentage Prediction using ML
An exploratory project on different scikit-learn regression models.
## 📌 Project Overview
This project explores how different machine learning regression models can be used to predict body fat percentage based on physiological measurements.
The dataset comes from an ARFF file (`bodyfat.arff`), and the goal is to compare models and find the one that achieves the highest accuracy.

The main purpose of this project is to personally familiarise myself with data preparation, visualisation and machine learning with the `scikit-learn` library.

## 📂 Repository Structure (incomplete...)
```bash
bodyfat-ml/
│
├── data/                 # Raw and preprocessed datasets
│   ├── bodyfat.arff
│   ├── clean_df.csv
│   └── README.md
│ 
│
├── notebooks/            # Jupyter Notebooks (Kaggle-friendly)
│   ├── 01_exploration.ipynb   # Data loading & EDA
│   ├── 02_preprocessing.ipynb # Cleaning, splitting, scaling
│   ├── 03_models.ipynb        # Training multiple regressors
│   └── 04_results.ipynb       # Evaluation & visualization
│
├── models/               # Saved ML models
│   └── best_model.pkl
│
├── results/              # Outputs & predictions
│   └── predictions.csv
│
└── README.md             # Project documentation
```
## 🔬 Methodology

1. Exploration: Load dataset, check for missing values, visualise distributions & correlations.
2. Preprocessing: Clean data, train-test split, apply feature scaling.
3. Model Training: Train and evaluate multiple regression models:
    - Linear Regression
    - Decision Tree Regressor
    - Random Forest Regressor
    - Gradient Boosting Regressor
    - XGBoost Regressor
    - Ridge Regression

4. Evaluation: Compare models using MAE, RMSE, and R².
5. Results: Save the best model and visualise predictions vs. actual values.

## 📊 Results

Best model: (to be updated after experiments, e.g., Random Forest)

Performance metrics :
MAE: `X.XXX`
RMSE: `X.XXX`
R²: `X.XXX`


