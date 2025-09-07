

# Sensitivity Analysis of LSTM Model for Stock Price Forecasting and Market Regime Classification #

This repository contains code, notebooks, and results for my MSc project 

## Project Structure

This project implements a baseline LSTM model for stock price forecasting and market regime classification, followed by sensitivity analysis.

## Structure

- `data/`        - Raw and processed datasets
- `models/`      - Saved and checkpointed models
- `artifacts/`   - Exported arrays, model artifacts, etc.
- `results/`     - Output results which include Figures, metrics, attributions
- `configs/`     - Config files used for experiments
- `requirements.txt` - Python dependencies

## Notebooks

- `notebooks/RQ1_RQ2.ipynb`: Data prep, baseline LSTM, forecasting, and classification
- `notebooks/RQ3.ipynb`: SHAP feature importance
- `notebooks/RQ4.ipynb`: Architectural Sensitivity Analysis
- `notebooks/RQ5.ipynb`: Input Robustness

## Setup

## How to Run

1. **Clone the repo**:
git clone https://github.com/Devividyks/sensitivity_analysis_lstm.git
cd sensitivity_analysis_lstm
3. **Install dependencies**:
  pip install -r requirements.txt
4. **Open the .ipynb notebooks** using Jupyter or VS Code and follow the cells in order for each RQ.

## Requirements

See `requirements.txt` for the full list. Main libraries include:
- numpy, pandas, matplotlib, seaborn
- scikit-learn, tensorflow, keras
- shap, joblib, yfinance

## Notes

- Results (plots/metrics) are saved to the `results/` directory.
- Artifacts (saved models, scalers, numpy arrays) are saved to `artifacts/`.
- All paths are relative—no hardcoding to Google Drive or Colab paths.

## License



---

*Created by [Devi Vidya K S], MSc Project, 2025.*
