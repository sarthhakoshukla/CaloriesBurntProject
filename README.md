# 🔥 Calories Burnt Prediction

This project predicts the number of calories burned based on user input parameters such as age, gender, height, weight, duration, heart rate, and body temperature. The dataset was preprocessed and multiple machine learning models were trained to identify the best performing one.

---

## 📌 Project Overview

- Applied data preprocessing techniques like missing value handling and categorical encoding
- Performed detailed exploratory data analysis (EDA) to uncover key relationships between variables
- Trained and compared multiple ML models to predict calorie burn
- Achieved high accuracy with ensemble models like XGBoost and Random Forest

---

## 🧰 Tools & Technologies

- **Languages**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost  
- **Modeling Techniques**: RandomForest, KNN, SVR, ElasticNet, Gradient Boosting, XGBoost

---

## 📊 Key Highlights

- ✅ Cleaned and preprocessed raw exercise and biometric data
- 🔍 Performed EDA to visualize distributions, correlations, and feature importance
- 📈 Achieved **R² score of ~0.98**, showing strong model accuracy
- ⚙️ Tested and evaluated using cross-validation and regression metrics

---

## 📁 Dataset

The dataset includes the following features:
- `Gender`, `Age`, `Height`, `Weight`, `Duration`
- `Heart Rate`, `Body Temperature`
- `Calories` (Target variable)

---

## 📌 Results Snapshot

| Model            | R² Score  |
|------------------|-----------|
| Random Forest    | 0.9795    |
| XGBoost          | 0.9787    |
| Gradient Boosting| 0.9771    |
| SVR              | 0.9678    |

---

## 📚 Learnings

- Hands-on experience with multiple regression models
- Understanding feature relationships affecting calorie burn
- Importance of preprocessing for model performance

---

## ✅ Future Improvements

- Deploy model as a web app using **Streamlit**
- Add real-time input prediction feature

---

## 🚀 How to Run

```bash
git clone https://github.com/sarthhakoshukla/CaloriesBurntProject.git
cd CaloriesBurntProject
python model_training.py
