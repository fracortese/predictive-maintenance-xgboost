# predictive-maintenance-xgboost
 Predictive Maintenance App with Machine Learning and Gradio
# 🛠️ Predictive Maintenance App with XGBoost and Gradio

This project is a machine learning application for **Predictive Maintenance**, designed to predict whether a machine is at risk of failure based on input parameters provided by the user.

---

## 📌 Project Overview

- **Type**: Binary classification (Failure / No Failure)
- **Model**: Trained using **XGBoost**
- **Interface**: Built with **Gradio** for ease of use
- **User Input**: Real-time parameters inserted manually

---

## 🧠 Machine Learning Model

- The model was trained on historical sensor and maintenance data.
- It uses the following features:
  - Air temperature [K]
  - Process temperature [K]
  - Rotational speed [rpm]
  - Torque [Nm]
  - Tool wear [min]
- Target variable: Machine failure (0 = No, 1 = Yes)

The trained model is saved as:
best_xgboost_model.pkl
