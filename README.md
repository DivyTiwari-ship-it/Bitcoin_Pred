# 🪙 Bitcoin Price Prediction

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![ML](https://img.shields.io/badge/ML-XGBoost-green)
![Accuracy](https://img.shields.io/badge/Accuracy-72.23%25-brightgreen)

## 📌 Overview
Predict kiya ki next hour Bitcoin price **badhega ya girega** 
using Machine Learning on hourly historical data.
Model ko current live Bitcoin price pe bhi test kiya!

---

## 📊 Results
| Model | Accuracy |
|-------|----------|
| Random Forest (baseline) | 58.77% |
| **XGBoost ✅** | **72.23%** |

---

## 🔧 Feature Engineering
| Feature | Description |
|---------|-------------|
| MA_10, MA_20, MA_30, MA_50 | Moving Averages |
| RSI | Relative Strength Index |
| BB_upper, BB_lower, BB_width | Bollinger Bands |
| Momentum | Price change in 5 hours |
| Volatility | Price std in 10 hours |
| MA_diff | MA_10 - MA_30 |
| price_change | % change per hour |

---


---

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/-Python-black?logo=python)
![Pandas](https://img.shields.io/badge/-Pandas-black?logo=pandas)
![XGBoost](https://img.shields.io/badge/-XGBoost-black)
![Seaborn](https://img.shields.io/badge/-Seaborn-black)
![yfinance](https://img.shields.io/badge/-yfinance-black)

---

## 🚀 How to Run
```bash
git clone https://github.com/DivyTiwari-ship-it/Bitcoin_Pred
pip install -r requirements.txt
jupyter notebook Bitcoin_Prediction.ipynb
```

---

## 💡 Key Learnings
- RSI aur Bollinger Bands ne accuracy improve ki
- Bitcoin market inherently random hai — 72% without data leakage genuine hai
- XGBoost outperformed RandomForest
- Model current live Bitcoin price pe bhi predict kar sakta hai!
