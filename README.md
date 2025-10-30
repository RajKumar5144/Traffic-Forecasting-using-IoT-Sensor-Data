# 🚦 Traffic Forecasting using IoT Sensor Data

## 🧠 Project Overview
This project focuses on **predicting future traffic patterns** across four major junctions in a city using **IoT sensor data**.  
The goal is to support the government’s **Smart City** initiative by providing accurate traffic forecasts for better infrastructure and congestion management.

By analyzing **20 months of historical traffic data**, the objective is to forecast the **number of vehicles** for the **next 4 months**.

---

## 📍 Context
The government aims to transform the city into a **digital and intelligent ecosystem**. One major challenge is traffic congestion.  
You are part of the data science team responsible for developing a **robust traffic forecasting model**.

Traffic patterns vary significantly due to:
- Holidays and festivals  
- Weekdays vs. weekends  
- Seasonal and temporal variations  

These factors are important to consider while building the forecasting model.

---

## 📂 Dataset
**Source:** [Kaggle - ML IoT Traffic Data](https://www.kaggle.com/datasets/vetrirah/ml-iot/data)

### Variable Description
| Column Name | Description |
|--------------|-------------|
| `ID` | Unique ID for each reading |
| `DateTime` | Timestamp in hourly intervals |
| `Junction` | Junction number (1–4) |
| `Vehicles` | Number of vehicles (Target variable) |

> Note: Each junction’s data is recorded for different time periods, and some datasets are sparse or incomplete.

---

## 🎯 Objective
To **forecast the number of vehicles** passing through each of the four junctions for the **next 4 months** using machine learning techniques.

---

## 🧩 Approach

1. **Data Preprocessing**
   - Handled missing and sparse data  
   - Extracted time-based features (`Year`, `Month`, `WeekOfYear`, `DayOfWeek`, `Hour`, etc.)  
   - Scaled and structured data for time-series analysis  

2. **Exploratory Data Analysis (EDA)**
   - Visualized traffic patterns and trends  
   - Compared junction-wise vehicle counts  
   - Identified peak hours and seasonal effects  

3. **Model Building**
   - Implemented models like **Random Forest**, **XGBoost**, and **RFE-based feature selection**  
   - Performed hyperparameter tuning using **GridSearchCV**  

4. **Evaluation**
   - Evaluated models using **RMSE**, **MAE**, and **R² Score**  
   - Compared actual vs predicted traffic trends  

---

## 📊 Tools & Technologies
- **Python** 🐍  
- **Pandas**, **NumPy** – Data handling  
- **Matplotlib**, **Seaborn** – Visualization  
- **Scikit-learn**, **XGBoost** – Machine Learning  
- **Jupyter Notebook / VS Code** – Development environment  

---

## 🚀 Results
- Built accurate predictive models for all four junctions.  
- Successfully forecasted traffic volume for the next 4 months.  
- Identified meaningful temporal traffic patterns useful for city planning.  

---

## 📅 Future Scope
- Integrate external data such as **weather** or **public events**.  
- Experiment with **LSTM/ARIMA** for advanced time-series modeling.  
- Deploy the model for **real-time traffic monitoring**.  

---

## 👨‍💻 Author
**Raj Kumar**  
NIT Warangal | Data Science & Machine Learning Enthusiast
