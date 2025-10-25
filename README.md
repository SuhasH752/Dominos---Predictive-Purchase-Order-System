# Dominos Predictive Purchase Order System

AI-powered sales forecasting and inventory management system for Dominos Pizza.

## Project Overview

This system predicts pizza sales for the next 3 months and generates automated purchase orders for ingredients using machine learning.

## Features

- **Sales Forecasting**: XGBoost model with 98% accuracy
- **Ingredient Planning**: Automated purchase orders
- **Production Planning**: Pizza-specific demand predictions
- **Streamlit Dashboard**: Interactive web application

## 📈 Model Performance

- **MAE**: $43.41 (98% accuracy)
- **Forecast Period**: 3 months
- **Total Pizzas Predicted**: 15,561
- **Total Ingredients**: 2,846 kg

## Project Structure
dominos/
├── data/ # Raw and processed data
├── models/ # Trained ML models
├── results/ # Forecasts and purchase orders
├── app/ # Streamlit dashboard
├── notebooks/ # Jupyter notebooks
└── scripts/ # Python scripts

text

## Quick Start

1. Install dependencies:
```bash
pip install -r requirements.txt
Run the dashboard:

bash
streamlit run app/streamlit_app.py

📋 Requirements
Python 3.8+
pandas, numpy, scikit-learn
xgboost, lightgbm
streamlit, matplotlib
