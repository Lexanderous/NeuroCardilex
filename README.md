# 🧠 NeuroCardilex

Machine Learning-based Cardiovascular Disease Prediction System using Ensemble Learning and SMOTE.

---

## 🚀 Overview
NeuroCardilex is a predictive healthcare system designed to detect cardiovascular disease using advanced machine learning techniques. It leverages ensemble models and data balancing to improve diagnostic accuracy and reliability.

---

## 🔥 Key Features
- Data preprocessing and normalization  
- SMOTE for handling class imbalance  
- Multiple ML models (Logistic, RF, GB, Extra Trees)  
- Stacking Ensemble (best-performing model)  
- Evaluation using Accuracy, Precision, Recall, F1-score, ROC-AUC  

---

## 📊 Results
- F1 Score: ~0.72  
- ROC-AUC: ~0.79  
- Improved sensitivity with reduced false negatives  

---

## 🧠 Important Insights
- Blood pressure (ap_hi, ap_lo) is the most influential feature  
- Cholesterol and age significantly impact prediction  
- Ensemble learning improves stability and generalization  

---

## 🛠 Tech Stack
- Python  
- Scikit-learn  
- Pandas, NumPy  
- Matplotlib, Seaborn  

---

## ▶️ How to Run
```bash
python cardio_analysis.py
