# 🐟 Forecasting Produksi Ikan Nila Jawa Tengah  
Forecasting using Single Exponential Smoothing (SES)

---

## 📊 Overview
This project forecasts the production of **Ikan Nila (Tilapia)** in Central Java using **Single Exponential Smoothing (SES)**.  
The dataset contains annual production data from **all regencies/cities (kabupaten/kota)** in Central Java for the years **2019–2022**.

The forecasting model is implemented using **Python**, allowing flexible analysis and customizable smoothing parameters.

---

## 🗂 Data Source
- **Provider**: Dinas Kelautan dan Perikanan Provinsi Jawa Tengah  
- **Format**: Excel  
- **Coverage**:  
  - All kabupaten/kota in Central Java  
  - Annual fish production data (2019–2022)  

---

## 🧮 Methodology

### **📘 Single Exponential Smoothing (SES)**
Single Exponential Smoothing is used to produce short-term forecasts based on weighted averages of past observations, where more recent data receives higher weight.

Steps performed:
1. Loading and cleaning data  
2. Exploratory Data Analysis (EDA)  
3. Applying SES for trend estimation  
4. Tuning smoothing constant (α)  
5. Generating forecasts  
6. Evaluating accuracy (optional: MAPE, MAE, RMSE)  
7. Plotting actual vs predicted values

### **📈 Accuracy Evaluation**
Although SES is simple, accuracy evaluation is included to assess how well the model fits existing data.  
Metrics such as **MAPE**, **MAE**, or **RMSE** can be generated using Python.

---

## 🛠 Tools Used
- **Python**  
  - pandas  
  - statsmodels  
  - matplotlib / seaborn (for visualization)  
- **Excel** (data source)

---

## 📂 Output
The project provides:
- Forecasted Ikan Nila production for each kabupaten/kota  
- SES model output and smoothing parameter  
- Accuracy metrics (if applied)  
- Plots showing forecast trends  
- Python script (notebook or `.py`) used for calculation  

---

## 🎯 Purpose
This forecasting analysis aims to:
- Provide short-term projections of Ikan Nila production in Central Java  
- Help inform fisheries planning, monitoring, and decision-making  
- Demonstrate the use of SES as a simple and effective forecasting method using Python  

---

Explore the project files to view the SES implementation, results, and visualizations.

