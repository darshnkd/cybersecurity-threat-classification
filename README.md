# 🔐 Cybersecurity Threat Classification  
*A machine learning approach for detecting and classifying network intrusions using the CICIDS2017 dataset.*

---

## 📌 Overview

This project explores multiple machine learning models to detect and classify network threats using the **CICIDS2017** dataset. Among the models implemented, **Random Forest** achieved the highest performance with an accuracy of `98.19%`.

### ✅ Implemented Models:
- **Random Forest** (`Accuracy: 98.19%`)
- **XGBoost**
- **Multi-layer Perceptron (MLP)**

---

## 📂 Dataset

The [CICIDS2017 dataset](https://www.kaggle.com/datasets) contains labeled network traffic representing various attack types and normal behavior. Classes include:

- `Normal traffic`
- `DDoS attacks`
- `Port scanning`
- `Web attacks`
- `Infiltration attempts`

---

## 🔧 Features

- 🧹 **Data Preprocessing** and memory optimization
- 🎯 **Feature Selection** using `SelectKBest`
- ⚖️ **Class Imbalance Handling** using `SMOTE` and undersampling
- 🤖 **Model Training**, evaluation, and persistence
- 📊 **Result Visualization**

---

## 📈 Performance (Best Model - Random Forest)

| **Metric**   | **Score**  |
|--------------|------------|
| `Accuracy`   | `0.9819`   |
| `Precision`  | `0.9838`   |
| `Recall`     | `0.9819`   |
| `F1 Score`   | `0.9822`   |

---

## 🚀 Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/darshnkd/cybersecurity-threat-classification.git
   cd cybersecurity-threat-classification
