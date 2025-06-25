
# 🏗️ Bulldozer Price Prediction - End-to-End Machine Learning Project

This project aims to predict the **resale prices of used bulldozers** using machine learning techniques. The dataset is sourced from the [Blue Book for Bulldozers](https://www.kaggle.com/c/bluebook-for-bulldozers) Kaggle competition, and this repository demonstrates an end-to-end workflow—from data preprocessing to model deployment-ready code.

---

## 📌 Problem Statement

Predict the sale price of a bulldozer based on features such as usage hours, model ID, machine size, product group, etc. The model should be able to generalize to unseen data.

---

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 🔍 Key Features

* **Exploratory Data Analysis (EDA)** and data cleaning
* **Feature Engineering** to transform temporal and categorical features
* **Model Building** using `RandomForestRegressor`
* **Hyperparameter Tuning** using `RandomizedSearchCV`
* **Cross-Validation** for better generalization
* **Model Evaluation** using metrics such as RMSLE, MAE, R²
* **Saving the Trained Model** with `joblib` (optional for production)

---

## 📊 Data Files

* `Train.csv` Training Set
* `Valid.csv` — validation set
* `Test.csv` — testing set used for final predictions

---

## 📈 Model Performance

* **Model Used**: RandomForestRegressor
* **Evaluation Metrics on Validation Set**:

  * R² Score: `0.8818019502450094` 
  * MAE: `5951.247761444453`
  * RMSLE: `0.24524163989538328`

---

## 🤖 Future Improvements

* Try other models like XGBoost, LightGBM
* Build a Streamlit or Flask web app for live predictions
* Deploy the model using cloud platforms like AWS or Heroku

---
## Developer
Poorvi Gupta
