# 🚗 Car Price Prediction

Welcome to the **Car Price Prediction** project! 🎉 The goal of this project is to predict car prices using a **Decision Tree Regressor** machine learning model. The dataset used comes from the file `avito_car_dataset_ALL.csv`, which contains detailed information about cars, such as **brand**, **model**, **mileage**, **fuel type**, **transmission**, and more.

## 🎯 Objectives

- 🧹 **Prepare the data** for regression model compatibility.
- 🔮 **Train a regression model** to predict car prices.
- 📊 **Evaluate model performance** using standard metrics like Mean Absolute Error (MAE), R-squared, etc.

## 📊 Data

- **Source file:** `avito_car_dataset_ALL.csv`
- The dataset includes the following columns:
  - **Brand** 🏷️
  - **Model** 🚗
  - **Mileage** ⏳
  - **Fuel type** ⛽
  - **Transmission type** 🔧
  - **Price** (target to predict) 💵

## 🧹 Data Preprocessing

The following preprocessing steps were performed to prepare the data:

1. 🔄 **Convert non-numeric columns** to categorical types.
2. ❌ **Remove irrelevant columns**, such as the "Link" column.
3. 🔢 **Impute missing values**:
   - Use **median** for numeric columns.
   - Use **mode** for categorical columns.
4. 🔠 **One-Hot Encoding** for categorical columns (e.g., **City**, **Origin**, etc.).
5. 🧩 **Combine the Brand and Model columns** into a single column: `Brand_Model`.
6. 🎯 **Split the data** into features (X) and target (Price).

## 🤖 Model

- **Algorithm used:** **Decision Tree Regressor** 🌳
- **Library used:** `scikit-learn` 🧑‍💻

## 📦 Dependencies

To run this project, you will need the following libraries:

- `pandas` 📑
- `numpy` 🔢
- `scikit-learn` 🛠️

You can install the dependencies by running:

 ```bash
pip install pandas numpy scikit-learn
