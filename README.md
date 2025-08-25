# 🌾 Crop Yield Prediction using Machine Learning

<p align="center">
  <img src="https://img.shields.io/badge/Domain-Agriculture-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/ML-Regression-blue?style=for-the-badge&logo=scikitlearn" />
  <img src="https://img.shields.io/badge/Language-Python-yellow?style=for-the-badge&logo=python" />
</p>

---

## 📌 Project Overview
This project predicts **crop yield (tons per hectare)** using environmental and agricultural features such as region, soil type, rainfall, temperature, fertilizer usage, irrigation, and weather conditions.  

The dataset (`crop.csv`) contains **1,000,000 rows and 10 features**. A **Linear Regression model** was implemented as a baseline for yield prediction.

---

## 📂 Dataset Details
- **Rows:** 1,000,000  
- **Columns:** 10  
- **Target Variable:** `Yield_tons_per_hectare`  

### Features:
- `Region` 🌍 (North, South, East, West)  
- `Soil_Type` 🏞 (Sandy, Clay, Loam, Silt)  
- `Crop` 🌱 (Wheat, Rice, Cotton, etc.)  
- `Rainfall_mm` 🌧  
- `Temperature_Celsius` 🌡  
- `Fertilizer_Used` (True/False)  
- `Irrigation_Used` (True/False)  
- `Weather_Condition` (Sunny, Rainy, Cloudy)  
- `Days_to_Harvest` 📅  

---

## ⚙️ Workflow
1. **Data Preprocessing**
   - Checked dataset info, duplicates, missing values  
   - Converted categorical features using **One-Hot Encoding**  
   - Split dataset into **80% training & 20% testing**  

2. **Model Training**
   - Model: **Linear Regression** (baseline)  
   - Trained using scikit-learn  

3. **Evaluation**
   - Metrics:
     - ✅ **Mean Squared Error (MSE)**
     - ✅ **R² Score**  
   - Sample predictions on new data  

---

## 📊 Results
- **Model:** Linear Regression  
- **Evaluation Metrics:**  
  - Mean Squared Error (MSE): **0.2508**  
  - R-squared (R²) Score: **0.9130**  

👉 The model explains about **91% of the variance** in crop yield, which is a very strong baseline result.  

---
## 📈 Future Improvements

Use Random Forest / Gradient Boosting for better accuracy

Perform feature importance analysis

Apply cross-validation for robust evaluation

Deploy model with Flask/Django Streamlit

## 🏆 Author

👩‍💻 Humera Shaik

🌐 Data Science & Machine Learning Enthusiast

📊 Passionate about Agriculture + AI

⭐ If you found this project helpful, consider giving it a star on GitHub! ⭐
