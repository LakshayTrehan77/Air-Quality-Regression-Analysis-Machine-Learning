# 🌍 Air Quality Index Regression & Forecasting (Delhi Region)

This project focuses on building a robust **Machine Learning regression pipeline** to predict **Delhi's Air Quality Index (AQI)** using real-world pollution and meteorological datasets. By incorporating advanced preprocessing and multiple regression techniques, it aims to assist environmental planning and public awareness efforts.

---

## 📊 Project Overview

- **Objective**: Predict AQI values based on environmental features such as PM2.5, NOx, wind speed, humidity, etc.
- **Scope**: Real data from Delhi over 5+ years — cleaned, visualized, and modeled.
- **Models Used**:
  - K-Nearest Neighbors (KNN)
  - Ridge Regression
  - XGBoost Regressor
  - CatBoost Regressor
  - SVR and Linear Regression (as baselines)

---

## 🛠 Features

- ✅ Data Cleaning, Null Handling & Merging
- ✅ Feature Engineering (cyclical encoding, normalization, log transform)
- ✅ Correlation Matrix + Outlier Detection
- ✅ Model Training + Comparison (MAE, MSE, RMSE, R²)
- ✅ Real Prediction Pipeline

---

## 📁 File Structure

| File | Description |
|------|-------------|
| `Project_Report_Endsem_20.pdf` | Final detailed report with visuals, metrics, and architecture |
| `Mid_Term_Report_ML.pdf` | Interim report describing preprocessing and early results |
| `Mid_Term_Presentation.pptx` | PowerPoint walkthrough of methodology and progress |
| `ML Group Project.zip` | Contains source code, datasets, and notebooks |
| `README.md` | Project summary and documentation |

---

## 📈 Results

| Model | R² Score | RMSE | MAE |
|-------|---------|------|-----|
| **KNN Regressor** | **0.967** | 9.45 | 6.84 |
| Ridge | 0.812 | 20.23 | 15.33 |
| XGBoost | 0.872 | 17.01 | 12.99 |
| SVR | 0.76 | 23.8 | 18.9 |

✅ KNN emerged as the most effective regressor for our dataset.

---

## 🧪 Tech Stack

- Python (Pandas, NumPy, Scikit-learn, XGBoost, CatBoost)
- Matplotlib, Seaborn (EDA & Plots)
- Jupyter Notebooks
- GitHub + Git LFS (for large file tracking)

---

## 📍 Future Improvements

- Deploy as a REST API for real-time AQI prediction
- Use LSTM for temporal AQI forecasting
- Integrate satellite-based or IoT sensor inputs

---

## 👨‍💻 Contributors

- Lakshay Trehan
- Sahil
- Yash Singh
- Shrey Yadav
- Karanjeet
  

---

## 📌 Note

If you wish to explore or extend this project:
- Unzip the `.zip` archive
- Start from the EDA notebook and proceed to modeling
- Refer to `Project_Report_Endsem_20.pdf` for a full walkthrough

---

> 🌱 _This project reflects real-world environmental impact through ML_.
