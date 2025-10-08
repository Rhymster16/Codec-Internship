
# Predictive Maintenance (Synthetic)
Goal: Predict machinery failure using sensor time-series data (vibration, temperature, pressure).

Contents:
- `sensor_data.csv` - synthetic sensor dataset with per-machine timesteps and failure labels.
- `predictive_maintenance_notebook.ipynb` - Jupyter notebook demonstrating EDA, feature engineering, RandomForest baseline, and LSTM sequence model.
- `requirements.txt` - Python dependencies.

How to run:
1. Create a virtual environment and install dependencies: `pip install -r requirements.txt`
2. Open the notebook: `jupyter notebook predictive_maintenance_notebook.ipynb`
3. Train models and export artifacts as needed.

Notes:
- Dataset is synthetic for demo purposes. For real data, replace `sensor_data.csv` with actual sensor logs and adjust sequence/window lengths.
