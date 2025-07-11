# 🧠 Mental Health Prediction from Smartphone Data

## 🔍 Overview
This project uses behavioral smartphone data to predict early signs of **depression** in students using machine learning. It focuses on model interpretability with **SHAP**, ensuring ethical and transparent decision-making.

---

## 📌 Problem Statement
Can we detect early signs of **depression** based on smartphone usage patterns like screen time, unlock frequency, and app usage?

---

## 🛠 Tools & Technologies
- Python  
- Scikit-learn  
- Pandas, NumPy, Matplotlib  
- SHAP (SHapley Additive exPlanations)  
- StudentLife Dataset

---

## 📈 Approach
1. **Data Preparation**
   - Extracted behavioral features from smartphone logs (e.g., screen usage, app duration).
2. **Model Building**
   - Trained a **Random Forest Classifier** to predict depression indicators.
3. **Explainability**
   - Applied SHAP to highlight key contributors like screen time and PHQ-9 history.
4. **Evaluation**
   - Used ROC AUC to measure performance.

---

## ✅ Results
- Achieved **1.0 ROC AUC**
- Top features: screen duration, PHQ-9 score, phone unlocks
- Enhanced trust with SHAP summary and beeswarm plots

---

## 📂 Dataset
- **StudentLife Dataset**: Behavioral data from Dartmouth College students
  - Includes phone usage, sensor logs, PHQ-9, and daily surveys  
  - More info: [StudentLife Dataset](https://studentlife.cs.dartmouth.edu/dataset.html)

---
