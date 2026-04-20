# ✈️ Flight Fare Prediction

A machine learning project that predicts flight ticket prices using advanced regression models and hyperparameter tuning techniques.

---

## 📌 Overview

This project analyzes flight data and builds predictive models to estimate ticket prices based on various features such as airline, route, duration, and stops. Multiple models were tested, and performance was improved using **RandomizedSearchCV** for hyperparameter tuning.

---

## 🧠 Models Used

* Linear Regression (baseline model)
* Random Forest Regressor (final model)
* Hyperparameter tuning using RandomizedSearchCV

---

## ⚙️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn

---

## 📊 Features Used

* Airline
* Source & Destination
* Journey Date
* Duration
* Total Stops

---

## 🔄 Workflow

1. Data Cleaning & Preprocessing
2. Feature Engineering
3. Feature Scaling using StandardScaler
4. Model Training
5. Model Evaluation (MAE, RMSE, R² Score)
6. Hyperparameter Tuning (RandomizedSearchCV)
7. Model Saving using Pickle

---

## 📈 Model Performance

* Evaluated using:

  * Mean Absolute Error (MAE)
  * Root Mean Squared Error (RMSE)
  * R² Score

(Random Forest with tuning performed best)

---

## 📊 Feature Importance

The model identifies key factors affecting flight prices:

* Duration
* Airline
* Total Stops

(Visualized using bar plots)

---

## 💾 Saved Files

* `flight_price_model.pkl` → Trained model
* `model_columns.pkl` → Feature columns

---

## 🚀 How to Run

```bash
git clone https://github.com/your-username/flight-price-prediction.git
cd flight-price-prediction
pip install -r requirements.txt
```

Run notebook or script:

```bash
jupyter notebook
```

---

## 📁 Project Structure

```
flight-price-prediction/
│
├── Flight_Fare_Prediction.ipynb
├── flight_price_model.pkl
├── model_columns.pkl
├── requirements.txt
└── README.md
```

---

## 🔮 Future Improvements

* Deploy as a web app (Streamlit)
* Use real-time flight APIs
* Try advanced models (XGBoost, Gradient Boosting)

---

## 💡 Key Insight

Flight ticket prices are strongly influenced by **duration, airline, and number of stops**. Ensemble models like Random Forest significantly improve prediction accuracy over linear models.

---
