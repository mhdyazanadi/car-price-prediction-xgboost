# 🚗 Car Price Prediction using XGBoost

![Python](https://img.shields.io/badge/Python-3.x-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-XGBoost-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

A machine learning project that predicts used car prices using **Extreme Gradient Boosting (XGBoost)**.  
Built using real-world scraped data, feature engineering, and model optimization techniques.

---

## 📌 Overview

This project aims to automate car price estimation using machine learning.

The model predicts car prices based on:
- Mileage  
- Horsepower  
- Cylinder Volume  
- Transmission  
- Fuel Type  
- Number of Owners  

📊 Achieved performance:
- **R² Score:** ~0.83  
- **MAE:** ~11,700  
- **RMSE:** ~26,778  

---

## 🧠 Machine Learning Approach

- Algorithm: **XGBoost Regressor**
- Validation: **K-Fold Cross Validation**
- Optimization: **Randomized Search (Hyperparameter tuning)**

### Why XGBoost?
- High accuracy
- Handles missing data
- Built-in regularization
- Strong performance on tabular data

---

## 📊 Key Insights

- 🚀 **Horsepower** is the most important feature  
- 🔧 Engine-related features strongly impact price  
- 📉 Higher mileage → lower price  
- ⚙️ Automatic cars tend to be more expensive  

---

## 🗂️ Project Structure

```text
car-price-prediction/
├── GBMmodelFinal.ipynb   # Main notebook (model development)
├── data/                # Dataset (optional)
├── src/                 # Scripts (scraping, preprocessing)
├── README.md            # Project documentation
└── requirements.txt     # Dependencies
```

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/car-price-prediction.git
cd car-price-prediction
pip install -r requirements.txt
```

---

## ▶️ Usage

Run the notebook:

```bash
jupyter notebook GBMmodelFinal.ipynb
```

---

## 📦 Dependencies

- Python 3.x  
- pandas  
- numpy  
- scikit-learn  
- xgboost  
- matplotlib / seaborn  
- selenium  

---

## ⚠️ Challenges

- Web scraping limitations (CAPTCHA, delays)
- Data quality & missing values
- Potential overfitting (handled with tuning)

---

## 🔮 Future Improvements

- 📈 Larger dataset  
- 🌐 Deploy as web app  
- 🤖 Try deep learning models  
- ⚡ Real-time prediction API  

---

## 👤 Author

**Mohamad Yazan Adi**  
Computer Science – Swansea University  

---

