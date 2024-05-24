# MLflow Experiment Tracking with Weather Data

This project demonstrates the use of MLflow to track machine learning experiments, using weather data as a sample. The goal is to identify which model achieves the highest R² score.

## Purpose

The purpose of this project is to showcase how MLflow can be used to manage and compare multiple machine learning experiments. We use historical weather data for London to predict future mean temperatures and evaluate model performance.

## Requirements

- `pandas`
- `numpy`
- `mlflow`
- `seaborn`
- `matplotlib`
- `scikit-learn`

Install the required packages using:
```pip install pandas numpy mlflow seaborn matplotlib scikit-learn```

## Steps

1) Load and Inspect Data:
- Load london_weather.csv and inspect the data.

2) Data Preprocessing:
- Convert date to datetime format.
- Group data by year and month.
- Handle missing values and scale features.

3) Exploratory Data Analysis (EDA):
- Visualize mean temperature and sunshine.
- Plot a heatmap of feature correlations.

4) Feature Selection:
- Select relevant features for the model.

5) Model Training and Tracking:
- Train Decision Tree and Random Forest models.
- Use MLflow to log experiments, hyperparameters, and metrics.

6) Model Evaluation:
- Compare models using R² score.

