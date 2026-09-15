# CAR_PRICE_PREDICTION-MODEL-ML-
A Machine Learning model built to predict used car prices based on features like brand, mileage, fuel type, engine capacity, and manufacturing year. Includes data preprocessing, feature engineering, and model evaluation.
# Used Car Price Prediction Model

An end-to-end Machine Learning project that predicts the resale price of used cars based on key specifications like fuel type, ownership history, age, and engine power.

---

## 📌 Project Overview

Determining the fair market value of a pre-owned vehicle can be tricky. This project builds a regression-based Machine Learning model to automate price estimation, analyzing historical car sales data to help buyers and sellers make data-driven decisions.

---

## 🎯 Features Used for Prediction

The model uses the following key inputs to estimate car prices:

* **Years Used / Vehicle Age:** Age of the car derived from the manufacturing year.
* **Fuel Type:** Type of fuel (e.g., Petrol, Diesel, CNG, Electric).
* **Ownership:** Number of previous owners (e.g., First Owner, Second Owner).
* **Power:** Engine output measured in brake horsepower (bhp).

---

## 🛠️ Tech Stack & Libraries

* **Language:** Python
* **Data Processing:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Linear Regression / Random Forest / XGBoost)
* **Model Evaluation:** Mean Absolute Error (MAE), Mean Squared Error (MSE), R² Score

---

## 🚀 Workflow

1. **Data Cleaning & Preprocessing:** Handling missing values, removing outliers, and encoding categorical variables (Fuel Type, Ownership).
2. **Feature Engineering:** Calculating total years used and scaling numeric features like Power.
3. **Model Selection:** Training multiple regression algorithms to compare performance.
4. **Evaluation:** Assessing prediction accuracy using $R^2$ score and error metrics.

---

## 📊 Results

The trained model achieves reliable price predictions by capturing the non-linear relationship between engine power, vehicle depreciation over time, and ownership impact.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit a pull request.
