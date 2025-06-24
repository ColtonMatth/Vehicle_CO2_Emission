# Vehicle CO₂ Emission Prediction

This project provides a complete data science workflow for analyzing and predicting vehicle CO₂ emissions using a real-world dataset. The analysis is performed in a Jupyter Notebook and covers data exploration, SQL-based querying, feature engineering, machine learning modeling, hyperparameter tuning, and model deployment.

---

## 📊 Project Overview

- **Goal:** Predict the CO₂ emissions (g/km) of vehicles based on their specifications and fuel consumption data.
- **Dataset:** [Vehicle CO₂ Emissions Dataset](https://www.kaggle.com/datasets/brsahan/vehicle-co2-emissions-dataset/data)
- **Techniques:** SQL queries, Exploratory Data Analysis (EDA), Feature Engineering, Random Forest Regression, Hyperparameter Tuning, Model Evaluation, and Deployment.

---

## 🗂️ Table of Contents

- [Vehicle CO₂ Emission Prediction](#vehicle-co-emission-prediction)
  - [📊 Project Overview](#-project-overview)
  - [🗂️ Table of Contents](#️-table-of-contents)
  - [About Dataset](#about-dataset)
  - [SQL Data Preparation \& Queries](#sql-data-preparation--queries)
  - [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Machine Learning Pipeline](#machine-learning-pipeline)
  - [Model Evaluation \& Deployment](#model-evaluation--deployment)
  - [Key Insights](#key-insights)
  - [How to Use](#how-to-use)
  - [Conclusion](#conclusion)

---

## About Dataset

The dataset contains information on:
- Vehicle make, model, and class
- Engine size, number of cylinders, transmission, and fuel type
- Fuel consumption (city, highway, combined)
- **Target:** CO₂ emissions (g/km)

---

## SQL Data Preparation & Queries

The project uses SQL within the notebook to:
- Identify makes/models with the highest and lowest CO₂ emissions
- Find the most fuel-efficient vehicles
- Compare emissions by fuel type and vehicle class
- Analyze trends between engine size and emissions
- Explore hybrid vehicle offerings and their emissions

---

## Exploratory Data Analysis

EDA includes:
- Distribution plots for CO₂ emissions and engine size
- Categorical analysis of vehicle class and fuel type
- Bivariate analysis (e.g., engine size vs. emissions)
- Correlation matrix to identify key drivers of emissions

---

## Machine Learning Pipeline

- **Data Preprocessing:** Handling missing values and encoding categorical features
- **Train-Test Split:** Ensuring robust model evaluation
- **Model Selection:** Random Forest Regressor chosen for its performance and interpretability
- **Model Tuning:** Hyperparameter optimization using GridSearchCV

---

## Model Evaluation & Deployment

- **Metrics:** MAE, RMSE, and R² are used to assess model performance
- **Deployment:** The best model is saved with `joblib` for future predictions

---

## Key Insights

- Engine size, fuel consumption, and vehicle class are major drivers of CO₂ emissions
- SQL queries provide rapid, actionable insights for both business and technical audiences
- The tuned Random Forest model delivers accurate predictions

---

## How to Use

1. Clone this repository.
2. Open `Vehicle_CO2_Emission.ipynb` in Jupyter Notebook or VS Code.
3. Run the notebook cells step by step to reproduce the analysis and modeling.
4. Use the saved model (`co2_rf_model.pkl`) to make predictions on new data.

---

## Conclusion

This project demonstrates a full data science workflow—from SQL-based data exploration to machine learning and deployment—for actionable vehicle CO₂ emission prediction. The approach can be adapted for similar regression problems in automotive or environmental domains.