# 🌫️ Air-Quality-Index (AQI) Prediction

A machine learning project to **predict the Air Quality Index (AQI)** based on concentrations of various environmental pollutants. The goal is to help with **environmental monitoring** and promote **public health awareness** by estimating AQI from real-world pollution data.

---

## 📌 Objective

To build a regression-based model that predicts the **Air Quality Index (AQI)** using air pollutant measurements such as:

- PM2.5  
- PM10  
- NO  
- NO2  
- NOx  
- NH3  
- CO  
- SO2  
- O3  
- Benzene  
- Toluene  
- Xylene

---

## 📂 Dataset

- **Source:** CSV file (local or from a public source)  
- **Type:** Tabular data containing pollutant readings and AQI  
- **Target Variable:** `AQI` (Air Quality Index)

> 💡 Ensure the dataset is placed in the same directory as the notebook, or provide a proper link/source in the repo.

---

## 🛠️ Technologies Used

- **Language:** Python  
- **Environment:** Jupyter Notebook  
- **Libraries:**
  - `scikit-learn`
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

---

## 🔍 Exploratory Data Analysis (EDA)

Performed steps include:

- Checking for **null values**
- Verifying **data types**
- Plotting **distribution graphs**
- Creating **correlation matrix heatmaps**

These help to understand data quality and relationships between features and the target.

---

## 📈 Model Building

### 🔧 Algorithms Used:
- **Linear Regression**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree Regressor**
- **Random Forest Regressor**

### 🚀 Workflow:
1. Load and explore the dataset  
2. Handle missing values (if any)  
3. Select features and target  
4. Split data into **training** and **testing** sets  
5. Train models on the training set  
6. Evaluate using metrics:
   - **R² Score**
   - **Mean Absolute Error (MAE)**
   - **Root Mean Square Error (RMSE)**

---

## 📊 Results

| Model                    | R² Score (Test) |
|--------------------------|-----------------|
| Linear Regression         | **0.65**        |
| K-Nearest Neighbors       | **0.76**        |
| Decision Tree Regressor  | **0.69**        |
| Random Forest Regressor  | **0.84**        |

✅ The **Random Forest Regressor** delivered the best performance, showing excellent generalization and prediction accuracy on test data.

---

## 📎 Conclusion

This project demonstrates how various regression algorithms can be applied to **predict AQI from pollutant data**. Among all, **Random Forest Regressor** gave the most accurate results. Such models can be integrated into real-world **air quality monitoring systems**, **smart city platforms**, and **health alert services** to support better environmental decisions and public safety.

---
