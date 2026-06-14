# Heart Disease Prediction — ML Pipeline

TTTC2453 Machine Learning (AI) Final Group Project  
Dataset: D7 — Heart Disease (Cleveland), UCI ML Repository

## Overview
End-to-end machine learning pipeline comparing three model families:
1. **Logistic Regression** (baseline/classical model)
2. **Random Forest** (ensemble model with hyperparameter tuning)
3. **MLP Classifier** (deep learning model)

Includes data audit, EDA, SMOTE imbalance handling, and full performance analysis.

## How to Run

```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2. Open the notebook
jupyter notebook "Heart Disease Prediction.ipynb"
```

Run all cells sequentially. The dataset is loaded directly from the UCI repository URL — no manual download needed.

## Requirements
- Python 3.9+
- See `requirements.txt` for full dependency list
