# 🏡 House Price Prediction using Machine Learning

## 📌 Project Overview

This project focuses on predicting house prices using Machine Learning techniques. It uses the California Housing Dataset and implements an **XGBoost Regression model** to predict median house values based on different housing and geographical features.

The project demonstrates the complete Machine Learning workflow, including data preprocessing, exploratory data analysis, model training, and performance evaluation.

## 🎯 Objectives

- Understand and explore the California Housing Dataset.
- Perform Exploratory Data Analysis (EDA).
- Analyze relationships between different features.
- Train a Machine Learning regression model.
- Evaluate the model's prediction performance.

## 📊 Dataset

**California Housing Dataset**

- Total Instances: 20,640
- Number of Features: 8
- Target Variable: Median House Value

### Features Used

| Feature | Description |
|---|---|
| MedInc | Median Income |
| HouseAge | Median House Age |
| AveRooms | Average Rooms |
| AveBedrms | Average Bedrooms |
| Population | Population |
| AveOccup | Average Occupancy |
| Latitude | Latitude |
| Longitude | Longitude |

## 🛠️ Technologies & Libraries Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## ⚙️ Project Workflow

1. **Importing Dependencies:** Imported the required Python libraries.
2. **Dataset Collection:** Loaded the California Housing Dataset.
3. **Data Exploration:** Examined the dataset and its statistical information.
4. **Data Analysis:** Performed correlation analysis and visualized relationships using a heatmap.
5. **Feature Selection:** Separated input features and the target variable.
6. **Data Splitting:** Divided the dataset into 80% training data and 20% testing data.
7. **Model Training:** Implemented the XGBoost Regressor.
8. **Model Evaluation:** Evaluated predictions using R² Score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

## 📈 Model Used

**XGBoost Regressor**

XGBoost is a powerful gradient boosting algorithm that builds multiple decision trees sequentially to improve prediction performance.

It is used here to predict median house values based on the available housing features.

## 📏 Evaluation Metrics

The model performance is evaluated using:

- **R² Score:** Measures how well the model explains variations in the target values.
- **Mean Absolute Error (MAE):** Measures the average absolute difference between actual and predicted values.
- **Root Mean Squared Error (RMSE):** Measures prediction errors while giving more weight to larger errors.

## 📂 Project Structure
