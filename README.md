# MITSUI&CO. Commodity Prediction Challenge

**Multi-target commodity price prediction** using historical data from LME, JPX, US equities, and Forex markets.

This project develops robust models to predict **424 different targets** (single-asset returns and asset-pair differences) with a focus on accuracy and stability (Sharpe-ratio variant metric).

## Highlights
- Handles 424 targets simultaneously with target-specific feature engineering
- Advanced feature set: lags, rolling statistics, EWMA, cross-asset spreads/ratios, calendar features, interactions
- Models: LightGBM, XGBoost, CatBoost, Random Forest, Ridge
- Ensemble methods: averaging, weighted averaging, stacking
- Time-series cross-validation and Optuna hyperparameter tuning
- Competition-ready submission pipeline

## Tech Stack
- Python
- LightGBM, XGBoost, CatBoost, scikit-learn
- Pandas, NumPy
- Optuna (hyperparameter optimization)
- Jupyter for exploration

## Project Structure


## Quick Start
```bash
git clone https://github.com/Pedurabo/MITSUI-CO.-Commodity-Prediction-Challenge.git
cd MITSUI-CO.-Commodity-Prediction-Challenge
pip install -r requirements.txt
python setup_project.py          # checks environment & creates sample data
python run_baseline.py           # run baseline
# or
python run_competition.py        # full pipeline

jupyter notebook notebooks/eda.ipynb


