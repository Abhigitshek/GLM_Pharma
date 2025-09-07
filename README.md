# GLM_Pharma
## Overview
This repo contains a reproducible analysis for pharma sales forecasting using simple regression models. It includes data, trained models, evaluation metrics, and a minimal notebook to reproduce results.

## Repo structure
- `data/Pharma_sales.csv` — (optionally include) original dataset.
- `notebooks/Pharma_Sales_Forecasting.ipynb` — minimal notebook with steps to reproduce EDA, modeling, and evaluation.
- `models/` — saved model artifacts (LinearRegression.joblib, Ridge.joblib, Lasso.joblib).
- `plots/actual_vs_predicted.png` — diagnostic plot.
- `README.md` — this file.
- `model_metrics.csv` — per-model metrics CSV.
- `.gitignore`, `LICENSE`, `CONTRIBUTING.md` — repo housekeeping files.

## Quick start (one-liner)
```bash
git clone <your-repo-url>
pip install -r requirements.txt
python notebooks/run_analysis.py    # or open the notebook in Jupyter
```

## Reproduce analysis (high level)
1. Place `Pharma_sales.csv` in `data/` (or use the provided file).
2. Run the notebook `notebooks/Pharma_Sales_Forecasting.ipynb` or `python notebooks/run_analysis.py`.
3. Outputs will be saved into `models/`, `plots/` and `model_metrics.csv`.
