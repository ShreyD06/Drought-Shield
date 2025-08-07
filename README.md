# 🌎 Drought Shield

**Drought Shield** is a machine learning-driven drought forecasting system designed to help **policy makers, researchers, and environmental managers** anticipate and mitigate the effects of droughts.  

Leveraging **remote sensing data**, **deep learning architectures**, and **time-series forecasting**, Drought Shield predicts drought conditions up to **3 months in advance**. This project demonstrates the power of combining **environmental science** and **AI/ML** to tackle pressing climate challenges.

---

## 📖 Project Overview

- **Goal:** Predict 3-month-ahead drought severity (SPEI-6) for Northern California.
- **Method:** Leverages historical satellite-derived environmental indicators including:
  - **NDVI (Normalized Difference Vegetation Index)** – vegetation health  
  - **LST (Land Surface Temperature)** – surface heat stress  
  - **ET & PET (Evapotranspiration metrics)** – soil moisture and water balance  
- **Approach:**  
  1. Preprocessed remote sensing data from **MODIS** and **GRIDMET** (2000–2023).  
  2. Developed and compared **three models**:
      - **LSTM (Long Short-Term Memory)** for temporal forecasting
      - **ConvLSTM** for spatial-temporal learning  
      - **XGBoost baseline** for comparison  
  3. Evaluated models using **RMSE** and **MAE**.

**Key Result:**  
Both LSTM and ConvLSTM significantly outperformed the XGBoost baseline (RMSE ↓ from 0.800 → 0.268).

---

## 💡 Real-World Impact

- **Early warning for water management:** 3-month lead time provides actionable insights for policymakers and farmers.  
- **Climate resilience:** Helps anticipate and mitigate **wildfire risks**, **agricultural losses**, and **ecosystem damage**.  
- **Global adaptability:** Methodology can be extended to **other regions** and **climate zones** for broader drought monitoring.

---

## 🛠️ Technical Highlights

- **Languages & Tools:** Python, Google Colab, TensorFlow/Keras, NumPy, Pandas  
- **Machine Learning Models:** LSTM, ConvLSTM, XGBoost  
- **Geospatial & Remote Sensing:** MODIS (NDVI, LST, ET/PET), GRIDMET (SPEI)  
- **Data Engineering:**  
  - Spatial resolution adjustments and interpolation  
  - Handling missing data via imputation  
  - Temporal alignment for multi-source satellite data  
- **Time Series Forecasting & Evaluation:** RMSE, MAE, curriculum learning for sequential predictions

---

## 📊 Performance Summary

| Model        | RMSE   | MAE   |
|-------------|-------|-------|
| **LSTM**     | 0.268 | 0.211 |
| **ConvLSTM** | 0.291 | 0.238 |
| **XGBoost**  | 0.800 | 0.681 |

---

## 🚀 Future Work

- Expand to **multi-region/global** datasets for broader applicability.  
- Explore **transformers** and **graph neural networks** for more efficient spatial-temporal modeling.  
- Implement a **web dashboard** for real-time drought risk visualization.  
- Integrate **longer lead times** to enhance early warning capability.

---

## 👨‍💻 Skills Demonstrated

- **Machine Learning & Deep Learning** (LSTM, ConvLSTM, XGBoost)
- **Data Engineering & Preprocessing for Time-Series and Remote Sensing**
- **Geospatial Analysis**
- **Model Evaluation and Research Communication**
- **Applied AI for Climate Change Mitigation**

---


Drought Shield represents a **cross-disciplinary application** of AI in environmental science, showcasing the use of **data-driven decision-making** for real-world climate challenges.



