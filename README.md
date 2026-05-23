[BITCOIN_README.md](https://github.com/user-attachments/files/28179141/BITCOIN_README.md)
# Bitcoin_Pred# 🪙 Bitcoin Price Prediction

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![ML](https://img.shields.io/badge/ML-XGBoost-green)
![Accuracy](https://img.shields.io/badge/Accuracy-78.69%25-brightgreen)

## 📌 Overview
Predict kiya ki next hour Bitcoin price **badhega ya girega** 
using Machine Learning on 88,000+ historical records.

---

## 📊 Results
| Model | Accuracy |
|-------|----------|
| Random Forest (baseline) | 74.60% |
| Random Forest (tuned) | 76.68% |
| **XGBoost ✅** | **78.69%** |

---

## 🔧 Feature Engineering
| Feature | Description |
|---------|-------------|
| MA_10 | 10 min moving average |
| MA_30 | 30 min moving average |
| MA_50 | 50 min moving average |
| Momentum | Price change in 5 mins |

---

## 📈 Visualizations
- Confusion Matrix
- Feature Importance
- Bitcoin Price — Model Predictions (Stock Chart)

---

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/-Python-black?logo=python)
![Pandas](https://img.shields.io/badge/-Pandas-black?logo=pandas)
![XGBoost](https://img.shields.io/badge/-XGBoost-black)
![Seaborn](https://img.shields.io/badge/-Seaborn-black)

---

## 🚀 How to Run
```bash
git clone https://github.com/DivyTiwari-ship-it/ml-projects
pip install -r requirements.txt
jupyter notebook Bitcoin_Prediction.ipynb
```

---

## 💡 Key Learnings
- Moving Averages sabse important feature nikle
- Imbalanced data handle karna zaroori tha
- XGBoost outperformed RandomForest
