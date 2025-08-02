# 🚗 Car Sharing Demand Prediction

This project aims to forecast the hourly demand for car sharing services using historical environmental and temporal data. Predictive insights from this model can help optimize fleet allocation and improve customer service for car-sharing platforms.

---

## 📊 Project Objective

To develop and evaluate machine learning models that predict the number of cars rented in an hour based on features like temperature, humidity, and time of day.

---

## 🧠 Techniques Used

- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Preprocessing and Normalization
- Regression Models:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting
- Deep Learning (Optional: if used)
- Hyperparameter Tuning
- Model Evaluation (RMSE, MAE, R² Score)

---

## 📁 Dataset

- File: `CarSharing.csv`
- Contains hourly records of environmental conditions and corresponding car sharing demand.

### Key Features:
- `date_time`: Timestamp of record
- `temperature`: Ambient temperature (°C)
- `humidity`: Relative humidity (%)
- `wind_speed`: Wind speed (m/s)
- `visibility`: Visibility in meters
- `solar_radiation`, `rainfall`, `snowfall`
- `car_count`: Target variable - Number of cars rented in that hour

---

