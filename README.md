# 🛠️ Anomaly Detection and Predictive Maintenance of Machines

## 📌 Project Title
**Anomaly Detection and Predictive Maintenance of Machines with Prioritization and Maintenance Scheduling using Machine Learning**

---

## 📖 Overview

This project addresses the growing need for intelligent industrial maintenance systems. By applying machine learning techniques, we aim to detect anomalies in machine behavior, predict machine failures, estimate Remaining Useful Life (RUL), and schedule maintenance tasks based on priority—enhancing reliability and minimizing downtime.

---

## 🎯 Objectives

- Detect potential machine failures using anomaly detection.
- Predict Remaining Useful Life (RUL) with regression models.
- Prioritize machines based on failure risk and urgency.
- Schedule maintenance efficiently to reduce operational delays.

---

## 📂 Dataset

**Source:** [Microsoft Azure Predictive Maintenance Dataset](https://www.kaggle.com/datasets/arnabbiswas1/microsoft-azure-predictive-maintenance)

**Components:**
- `PdM_telemetry.csv` — Sensor data (temperature, pressure, etc.)
- `PdM_maint.csv` — Maintenance records
- `PdM_failures.csv` — Failure history
- `PdM_errors.csv` — Error logs
- `PdM_machines.csv` — Machine details

---

## 📌 Methodology

### 1. 🔍 Data Collection
- Downloaded using `opendatasets` library from Kaggle.
- Loaded and merged relevant CSV files for analysis.

### 2. 📊 Exploratory Data Analysis (EDA)
- Visualized sensor readings over time.
- Identified patterns and correlations between telemetry and failures.

### 3. 🧠 Failure Detection
- Implemented classification models:
  - Random Forest
  - XGBoost
- Trained models to classify failure vs. non-failure instances.

### 4. 🛠️ Feature Engineering
- Rolling means, standard deviations, and time-based lag features.
- Encoding machine type and error categories.

### 5. 📉 RUL Prediction
- Calculated RUL from failure logs.
- Applied regression models (Random Forest Regressor, XGBoost Regressor).

### 6. ⚙️ Maintenance Prioritization & Scheduling
- Ranked machines based on:
  - Predicted RUL
  - Probability of failure
- Developed a scheduling logic to handle priority and available maintenance windows.

---

## 🧰 Tools & Technologies

| Category       | Tools / Libraries                                |
|----------------|--------------------------------------------------|
| Programming    | Python                                           |
| Data Handling  | Pandas, NumPy                                    |
| Visualization  | Matplotlib, Seaborn                              |
| ML Models      | Scikit-learn, XGBoost                            |
| Notebook       | Jupyter Notebook                                 |
| Dataset Source | Kaggle                                           |

---

## 💡 Results

- Achieved high precision in early failure detection.
- RUL models delivered consistent regression metrics.
- Prioritization effectively flagged critical machines.
- Scheduling logic improved decision-making for preventive maintenance.

## 🔮 Future Scope

- Integration with IoT for real-time predictive maintenance.
- Web-based dashboard for live anomaly monitoring.
- Implementation of reinforcement learning for dynamic maintenance strategies.

---

## 👥 Contributors

- 👨‍💻 Member 1 — Rushikesh More
- 👩‍💻 Member 2 — Usman Shaikh
- 👨‍🔬 Member 3 — Aditya Parade
- 👨‍💼 Member 4 — Tushar Patil

---