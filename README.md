# 🚀 Smart Home Energy Optimization

## 📌 Project Overview  
This project focuses on analyzing energy consumption data collected from smart home devices. By identifying usage patterns and predicting future energy needs, we propose **actionable strategies** to optimize energy usage, reduce costs, and minimize environmental impact.

---

## 📂 Features  
✅ **Data Cleaning** – Handles missing values and converts data types for analysis.  
✅ **Exploratory Data Analysis (EDA)** – Visualizes trends, identifies correlations, and detects anomalies.  
✅ **Feature Engineering** – Extracts time-based features such as hour, day, and weekend/weekday classifications.  
✅ **Predictive Modeling**:  
   - **📉 Time-Series Forecasting** using **ARIMA**.  
   - **🧠 Random Forest Regression** for predictive modeling.  
✅ **Optimization Recommendations** – Identifies peak consumption periods and provides strategies to manage energy use.  

---

## 📊 Dataset Details  
The dataset contains energy consumption data with the following columns:

| Column                  | Description                                      |
|-------------------------|--------------------------------------------------|
| `Date`                  | Date of measurement                             |
| `Time`                  | Time of measurement                             |
| `Global_active_power`   | Total household power usage (kW)                |
| `Global_reactive_power` | Reactive power usage                            |
| `Voltage`               | Voltage measurements                            |
| `Global_intensity`      | Current intensity (A)                           |
| `Sub_metering_1-3`      | Energy usage in different household areas       |

🔗 **Dataset Source:** *(https://drive.google.com/file/d/15i7ykm1GwGkVI_7caZAZsiAKZVEDC5VF/view?usp=sharing)*  

---

## 📉 Model Performance & Results  

### 📌 **Time-Series Forecasting (ARIMA)**  
✔ Predicts **energy consumption for the next 7 days**.  
✔ Helps in anticipating peak demand for **optimized energy usage**.  

### 📌 **Random Forest Regression**  
✔ **Mean Absolute Error (MAE):** ~0.0024  
✔ **Root Mean Squared Error (RMSE):** ~0.0043  
✔ **R² Score:** ~0.9984 *(High accuracy!)*  

✅ *Highly accurate model for energy optimization!*  

---

## 📊 Key Visualizations  

### 📌 **Energy Consumption Trends Over Time**  
![Energy Consumption Trends](https://drive.google.com/uc?export=view&id=12U2V_Sgaun1XkfkTfYjgjHFC_wfdjnCA)  

 ### 📌 **Daily, Weekly, and Hourly Usage Patterns**  

#### 📅 **Daily Usage Pattern**  
![Daily Usage](https://drive.google.com/uc?export=view&id=1-xVgGbhIt_FPKYjuacJ0KvaV9_kFS2W0)  

#### 📆 **Weekly Usage Pattern**  
![Weekly Usage](https://drive.google.com/uc?export=view&id=1_Txk_MfNe2hEHNXhgMx_DeQ8bSKSrvk3)  

#### ⏳ **Hourly Usage Pattern**  
![Hourly Usage](https://drive.google.com/uc?export=view&id=1Ft_TIT3SF1vAzk8JT5kYVD_xEwdlxHXX)  

### 📌 **Heatmaps Showing Feature Correlations**  
![Feature Correlation Heatmap](https://drive.google.com/uc?export=view&id=1c01NIghe9m-uRNqTX8OGgL0BZKbR5IeO)  



 

---

## ⚡ **Optimization & Recommendations**  
🔹 **Peak Consumption Alerts** – Identifies high energy usage periods.  
🔹 **Cost-Saving Strategies** – Suggests optimal appliance usage times.  
🔹 **Smart Home Automation** – Insights for **automated energy-saving actions**.  

---

## 🏗 **Future Improvements**  
🔹 **Real-Time Energy Monitoring Dashboard** – Using **Streamlit or Power BI**.  
🔹 **Renewable Energy Integration** – Predicting solar/wind energy contribution.  
🔹 **User-Specific Recommendations** – Personalized energy-saving suggestions.  
🔹 **Cloud Deployment** – Hosting the model on a **web app** for accessibility.  

---

## 🛠 **How to Run the Project**  

### 🔧 **Prerequisites**  
Install the required dependencies:  
```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
