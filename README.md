# 🪙 Bitcoin Price Prediction

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![ML](https://img.shields.io/badge/ML-XGBoost-green)
![Accuracy](https://img.shields.io/badge/Accuracy-72.23%25-brightgreen)

## 📌 Overview
Predicted whether the Bitcoin price would **increase or decrease in the next hour**  
using Machine Learning on hourly historical market data.

The model was also tested on the current live Bitcoin price.

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
| Volatility | Price standard deviation in 10 hours |
| MA_diff | MA_10 - MA_30 |
| price_change | Percentage change per hour |

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
- RSI and Bollinger Bands improved the model accuracy
- Bitcoin markets are inherently random — achieving 72% accuracy without data leakage is meaningful
- XGBoost outperformed RandomForest
- The model can also make predictions on live Bitcoin price data
