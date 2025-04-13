# Air-Quality-Index-Prediction
AQI Prediction Model
This project focuses on building a machine learning model to predict the Air Quality Index (AQI) based on various air pollutants. It uses regression techniques to estimate the AQI, which can help in environmental monitoring and public health awareness.

📌 Objective
To predict the Air Quality Index (AQI) using various environmental pollutant measurements such as NO, NO2, PM2.5, CO, SO2, and others.

📂 Dataset
Source: The dataset appears to be a CSV file containing various pollutant metrics.

Features Used:

PM2.5, PM10, NO, NO2, NOx, NH3, CO, SO2, O3, Benzene, Toluene, Xylene

Target Variable:

AQI (Air Quality Index)

Note: The dataset is assumed to be pre-cleaned and available in the same directory as the notebook. If not, make sure to include the dataset or link its source in your repository.

🛠️ Technologies Used
Python

Jupyter Notebook

Scikit-learn

Pandas

NumPy

Matplotlib

Seaborn

🔍 Exploratory Data Analysis (EDA)
The notebook performs:

Checking for null values

Data type verification

Distribution plots

Correlation matrix heatmap

These steps help in understanding the relationship between pollutants and AQI.

📈 Model Building
Algorithms Used:
Linear Regression

Random Forest Regressor

Workflow:
Load and explore the data.

Handle missing values.

Feature and target selection.

Split the data into training and test sets.

Model training using Linear Regression and Random Forest.

Evaluate models using metrics like R² score, MAE, and RMSE.

📊 Results
Model	R² Score (Test)
Linear Regression	~0.72
Random Forest	~0.91
Random Forest Regressor outperformed Linear Regression with better generalization and accuracy.

