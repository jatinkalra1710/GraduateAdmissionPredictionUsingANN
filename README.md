# 🎓 Graduate Admission Prediction using ANN

This project uses an **Artificial Neural Network (ANN)** built with **TensorFlow/Keras** to predict the **Chance of Admission** for graduate applicants.  
The model achieves a strong performance with:

### ✅ **R² Score: 0.808**

---

## 📁 Dataset

Kaggle Dataset — *Graduate Admission Prediction*

Features used:

- GRE Score  
- TOEFL Score  
- University Rating  
- SOP  
- LOR  
- CGPA  
- Research  
- Chance of Admit (Target)

---

## 🧠 Model Architecture

The ANN consists of:

- Dense(64, ReLU)  
- Dropout(0.1)  
- Dense(32, ReLU)  
- Dense(16, ReLU)  
- Dense(1, Linear)

Loss: **MSE**  
Metrics: **RMSE, MAE**

---

## 🚀 Model Performance

| Metric | Score |
|--------|--------|
| **R² Score** | **0.808** |
| **RMSE** | 0.05 (typical) |
| **MAE** | 0.03–0.04 |

---
