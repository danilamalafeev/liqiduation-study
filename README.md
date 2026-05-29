# liqiduation-study

Exploratory analysis for Binance/Bybit liquidation, trade, and BBO data.

Files:

- `description.md` - task and data schema.
- `liquidation_eda_exploration.ipynb` - executed EDA notebook with initial observations.
- `baseline_signal.ipynb` - first sampled baseline for classifying toxic maker fills using liquidation clusters and L1 microstructure features.
- `logreg_6m_baseline.ipynb` - focused Logistic Regression baseline on the expanded 6-month dataset with sampled full-range train/validation metrics.

Raw parquet files are intentionally excluded from git via `.gitignore`.
