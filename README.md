# 🌾 Deep Learning-Based Crop Yield Prediction System (Remote Sensing + Climate Data)

An **AI/ML system** that predicts crop yield at field/district level using **satellite remote sensing (NDVI, Sentinel-2)** and **climate data (Rainfall-CHIRPS, Temperature/Precipitation-ERA5)**.  
This project implements **deep learning (CNN/LSTM)** and **machine learning (XGBoost)** models with automated data extraction pipelines using **Google Earth Engine (GEE)**.

---

## 🚀 Features

- ✅ **Satellite-driven Vegetation Index Analysis (NDVI – Sentinel-2)**
- ✅ **Climate pattern modeling using CHIRPS (rainfall), ERA-5 (temperature, precipitation)**
- ✅ **Deep Learning models for sequential + spatial learning (CNN + LSTM)**
- ✅ **Tree-based ML model for yield regression (XGBoost)**
- ✅ **Automated feature extraction using Google Earth Engine API**
- ✅ **Scalable pipeline for large remote sensing datasets**
- ✅ **Flexible for multiple crops and geolocations**
- ✅ **Future-ready deployment option via REST API + dashboard**

---

## 🧠 Models Used

| Model | Purpose |
|-------|--------|
| **CNN (Convolutional Neural Network)** | Learns spatial crop health patterns from NDVI raster features |
| **LSTM (Long Short-Term Memory)** | Captures temporal dependencies from climate/weather sequences |
| **XGBoost (Extreme Gradient Boosting)** | Final yield regression using engineered features |

> 🔹 The hybrid learning approach improves prediction reliability compared to traditional methods.

---

## 🛰️ Data Sources

- **Sentinel-2 Satellite Imagery** → NDVI/Vegetation analysis
- **CHIRPS** → Historical rainfall data
- **ERA5** → Temperature, precipitation, pressure, and other climate variables
- **Google Earth Engine** → Data extraction & preprocessing pipeline

---

## 🛠️ Tech Stack

- **AI/ML:** TensorFlow / Keras, XGBoost, NumPy, Pandas, Scikit-Learn
- **Remote Sensing:** Google Earth Engine (Python API), Geemap, Geemap-ML
- **Visualization (optional):** Matplotlib (dashboard ready), Web Integration Ready
- **Tools:** Git, GitHub, Linux, Jupyter Notebook

---

## ⚙️ System Workflow

