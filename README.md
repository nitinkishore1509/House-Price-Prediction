# 🏠 Housing Price Prediction using Linear Regression

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Overview
This repository demonstrates a **Linear Regression**-based approach to predict housing prices using historical housing market data.  
The notebook walks through **data exploration**, **feature engineering**, **model training**, and **evaluation**, ensuring the process is well-structured, reproducible, and scalable.

---

## 📂 Dataset
- **File:** `USA_Housing.csv`
- **Description:** Contains demographic and housing market data for different locations.
- **Features:**
  - `Avg. Area Income` – Average income of residents in the area  
  - `Avg. Area House Age` – Average age of houses in the area  
  - `Avg. Area Number of Rooms` – Average number of rooms per house  
  - `Avg. Area Number of Bedrooms` – Average number of bedrooms per house  
  - `Area Population` – Population of the area  
  - `Price` – **Target variable**, price of the house  
  - `Address` – Address of the house (not used in model training)  

---

## 🛠 Tech Stack
- **Language:** Python  
- **Libraries:**
  - `pandas` – Data manipulation  
  - `numpy` – Numerical computation  
  - `matplotlib` / `seaborn` – Data visualization  
  - `scikit-learn` – Machine learning model building & evaluation  

---

## 📊 Workflow
### 1️⃣ Data Exploration & Cleaning
- Loaded dataset into Pandas DataFrame
- Checked for missing values and inconsistencies
- Conducted statistical and correlation analysis

### 2️⃣ Data Visualization
- **Pairplot** for relationships between variables
- **Heatmap** for correlation analysis

### 3️⃣ Feature Selection & Splitting
- Selected relevant numerical features
- Split data into **Training (60%)** and **Testing (40%)**

### 4️⃣ Model Training
- Implemented **Linear Regression** with `scikit-learn`
- Fitted the model on the training dataset

### 5️⃣ Predictions & Evaluation
- Predicted test set prices
- Evaluated with:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)

### 6️⃣ Result Visualization
- Scatter plot: Predicted vs. Actual prices
- Residual distribution plot to validate model assumptions

---
# Example input
user_data = [[65000, 5, 7, 4, 30000]]  # [Income, Age, Rooms, Bedrooms, Population]

predicted_price = lm.predict(user_data)
print(f"Predicted House Price: ${predicted_price[0]:,.2f}")



---


