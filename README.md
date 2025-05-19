

# Big Mart Sales Prediction using CatBoost

## About
This project implements a machine learning model using **CatBoost Regressor** to predict sales for Big Mart items based on various features like Item MRP, Outlet details, and establishment year. The model handles data preprocessing, missing value imputation, feature engineering, and provides a user-friendly Tkinter GUI for real-time sales prediction.

---

## Features
- Data cleaning and imputation (linear interpolation, KNN imputer)
- Feature engineering and selection
- Model training and evaluation with CatBoost Regressor
- Cross-validation and performance metrics (R² score, Mean Absolute Error)
- Feature importance analysis
- GUI application for easy input and prediction display

---

---

## How to Use

1. **Train the model:**
   - Run the notebook `BigMart_Sales_Prediction.ipynb` to preprocess data, train the CatBoost model, and save it as `bigmart_model`.
   
2. **Run the GUI application:**
   - Use `sales_prediction_gui.py` to load the saved model and input features via a simple interface.
   - The GUI predicts and displays the sales value.

---

## Requirements

- Python 3.x
- Libraries:
  - pandas
  - numpy
  - seaborn
  - matplotlib
  - scikit-learn
  - catboost
  - joblib
  - tkinter (usually included with Python)

Install dependencies via:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn catboost joblib


