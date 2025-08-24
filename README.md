# High Blood Pressure Prediction (Random Forest)

Predicting the likelihood of **High Blood Pressure (Hypertension)** using a complete ML pipeline: preprocessing, class imbalance handling, training, evaluation, visualization, and model persistence.

> Author: **Muhammad Faique Bin Shahid**

---

## 🚀 Key Features
- **End-to-end pipeline** with clean, modular steps.
- **Synthetic dataset** (replace with your CSV anytime).
- **Scaling** via `StandardScaler`.
- **Class imbalance** handled using `RandomOverSampler`.
- **Model**: `RandomForestClassifier`.
- **Metrics**: Accuracy, Precision, Recall, F1.
- **Artifacts saved**: model, scaler, feature list (`.pkl`).
- **Visualization**: class distribution after resampling.

---

## 🧠 Dataset (Synthetic Example)
Columns:
- `Age` (20–70)  
- `BMI` (normal ~ 27 ± 5)  
- `Cholesterol` in {150, 180, 200, 220, 250}  
- `Sodium` in {1200, 1500, 1800, 2000, 2300}  
- `PhysicalActivity` in {0, 1}  
- `Smoker` in {0, 1}  
- `HighBP` (target) in {0, 1}

> Replace the synthetic generator with your real CSV to train on actual data.

---

## 📦 Requirements
```bash
pip install pandas numpy seaborn matplotlib scikit-learn imbalanced-learn joblib
