# Crop Yield Forecasting Using 'Random Forest Regression'

This project builds a machine learning model to predict crop yield based on environmental and input variables, using a 'Random Forest Regressor' trained on synthetic agricultural data. The model forecasts yield using three key features: rainfall, temperature, and fertilizer usage.

## Project Overview

- **Feature Selection**: rainfall (mm), temperature (°C), fertilizer (kg/ha)
- **Target Variable**: crop yield (tonnes per hectare)
- **Model Used**: Random Forest Regressor
- **Train/Test Split**: 80/20 for evaluation on unseen data
- **Performance Metrics**:
  - Mean Squared Error (MSE)
  - R² Score
- **Interpretability**: Feature importance analysis highlights most influential variables

## Key Features

- End-to-end notebook: data loading → EDA → model → evaluation
- Visualizations of:
  - Feature relationships
  - Actual vs predicted yields
  - Feature importance
- Suitable for adaptation with real-world agri-environmental datasets

## Tech Used

- **Python** (Jupyter Notebook)
- `pandas`, `matplotlib`, `seaborn`
- `scikit-learn` (Random Forest, metrics, train/test split)
