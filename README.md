# Equitable Post-Transplant Survival Prediction

This project predicts post-transplant survival for HCT patients using machine learning, focusing on fairness across racial groups.

## Contents

- `hct_nn.ipynb`: Neural network model for tabular data.
- `xgboost_and_catboost.ipynb`: XGBoost and CatBoost models with feature importance.
- Data files: `train.csv`, `test.csv` (Google Drive).

## Usage

1. Open notebooks in Colab or Jupyter.
2. Mount Google Drive for data access.
3. Install dependencies (`torch`, `xgboost`, `catboost`).
4. Run cells to preprocess, train, and evaluate.

## Evaluation

Models are assessed using a custom concordance index (C-index) across race groups for fairness