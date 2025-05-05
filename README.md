# Data Mining and Machine Learning Project

This repository contains Jupyter notebooks for analyzing electricity consumption/production data and node power distribution patterns.

## Files Overview

- **MES_test.ipynb**: Time series analysis and forecasting of monthly electricity data
  - Performs data preprocessing, feature engineering
  - Implements Random Forest and XGBoost models
  - Generates 12-month forecasts with confidence intervals
  - Includes detailed model evaluation and visualization

- **Butter-E.ipynb**: Clustering analysis of node power consumption profiles
  - Analyzes power distribution patterns across nodes
  - Implements K-means and Gaussian Mixture Model clustering
  - Evaluates cluster stability and characteristics
  - Visualizes cluster distributions and node type patterns

- **data/**
  - `MES_0125.csv`: Monthly electricity statistics data
  - `node_power_dist.csv`: Node power distribution data

## Setup & Installation

1. Required Python packages:
```python
numpy>=1.21.0
pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0
scikit-learn>=0.24.0
xgboost>=1.4.0
statsmodels>=0.12.0
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

## Running the Analysis

1. Start Jupyter Lab/Notebook:
```bash
jupyter lab
```
or
```bash 
jupyter notebook
```

2. Navigate to and open the desired notebook:
   - Open `MES_test.ipynb` for time series analysis
   - Open `Butter-E.ipynb` for clustering analysis

3. Run the notebooks:
   - Use Shift + Enter to execute cells sequentially
   - Or use the "Run All" button in the toolbar
