# Walmart Weekly Sales Forecasting (TSAC)

This is my TSAC 2025/2026 individual project on time-series forecasting using Walmart weekly sales data.

The notebook covers the full workflow in one place:
- data loading, cleaning, and weekly aggregation
- exploratory analysis (trend, seasonality, holiday effect)
- model comparison: ARIMA, SARIMA, and Prophet
- holdout validation on the last 26 weeks
- 20-week forecast with 95% confidence intervals

Dataset source: [Kaggle - Walmart Cleaned Sales Dataset](https://www.kaggle.com/datasets/ujjwalchowdhury/walmartcleaned)

## Project structure
- `data/` - input dataset (`walmart_cleaned.csv`)
- `notebooks/` - main analysis notebook (`TSAC_Walmart_Analysis.ipynb`)
- `results/` - exportable figures/tables (currently placeholder)
- `src/` - scripts (currently placeholder)
- `dataset.md` - dataset description
- `tsa workflow.md` - TSA workflow notes

## Quick start
1. Activate your virtual environment (optional).
2. Install dependencies with `pip install -r requirements.txt`.
3. Open and run `notebooks/TSAC_Walmart_Analysis.ipynb` from top to bottom.

Note:
- For local runs, use the dataset at `data/walmart_cleaned.csv`.
- For Colab runs, keep the Google Drive path used in the notebook.

## Author
Nacer Eddine Missouni