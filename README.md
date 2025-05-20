# 🚗 Predictive Maintenance for Vehicles | AI Project

### 🧠 Project Type: Supervised Learning (Classification + Regression)  
**Contributor:** Abhishek Raveendran c t (Individual Project)

---

## 📝 Problem Statement

Unplanned vehicle breakdowns lead to operational losses, safety issues, and increased costs. This project aims to develop a machine learning-based predictive maintenance system that anticipates vehicle component failures before they happen.

---

## 🏭 Industry Context

- **Industries:** Automotive, IoT, Fleet Management, Smart Vehicles  
- **Problem Type:**  
  - **Classification:** Predict if a failure will occur soon (Yes/No)  
  - **Regression (Future Scope):** Estimate the Remaining Useful Life (RUL) of components  

---

## 🎯 Business Objective

- 🚫 Reduce unexpected breakdowns  
- 💰 Optimize maintenance schedules and cut costs  
- ✅ Improve safety and operational efficiency  
- ⏱ Shift from reactive/time-based to predictive maintenance  

---

## 📊 Dataset Overview

- **Source:** Open-source vehicle sensor datasets (public)  
- **Features:**  
  - Engine temperature, torque, speed, vibration, fuel use, and wear indicators  
  - Time-stamped logs with binary failure labels (0: No Failure, 1: Failure)

---

## 🔍 Workflow

### 📌 1. Exploratory Data Analysis (EDA)
- Identified sensor trends before failures
- Correlation analysis to understand failure patterns

### 🧹 2. Data Preprocessing
- Feature engineering (e.g., power consumption, wear rate)
- Normalization & scaling
- Handling missing values and noise
- Addressing class imbalance using SMOTE

### 🤖 3. Model Building
- **Classification Models Used:**
  - Logistic Regression (Baseline)
  - Random Forest Classifier
  - XGBoost Classifier (Best performance)
- **Future Scope (Regression):**
  - Predict Remaining Useful Life (RUL) using models like XGBoost Regressor

### 🧪 4. Model Evaluation
- Metrics:  
  - Precision, Recall, F1-Score  
  - ROC-AUC  
  - Confusion Matrix  

---

## 📈 Results & Insights

- **Best Model:** XGBoost Classifier  
- **Focus Metric:** Recall – To catch more failures, even with some false positives  
- **Business Impact:**  
  - Helps schedule preventive maintenance  
  - Reduces downtime and repair costs  
  - Improves fleet reliability  

---

## 🚧 Constraints & Limitations

| Area | Limitation |
|------|------------|
| 💻 Computational Power | Free tier (Google Colab) |
| 💾 Data | No real-time sensor feed yet |
| 🔍 Accuracy | Requires strong feature engineering |
| 📡 Deployment | Real-time sensor integration needed |

---

## 🛠️ Tech Stack

- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn  
- **Tools:** Google Colab 
- **Future Deployment:** Flask/FastAPI for inference, optional cloud APIs

---

## 🚀 Future Scope

- Real-time failure prediction using IoT sensors
- Regression model for estimating RUL
- Integration with vehicle dashboards or fleet apps
- Real-world deployment via APIs and dashboards

---
