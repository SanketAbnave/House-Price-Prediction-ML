# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict house prices using machine learning techniques based on various features such as area, location, number of bedrooms, and other factors.

---

## 📊 Dataset
- Source: Kaggle
- Records: 20,000+
- Features: 20+

---

## 🧠 Steps Performed

1. Data Cleaning
   - Removed duplicates
   - Dropped unnecessary columns

2. Outlier Removal
   - Used 99th percentile method

3. Feature Engineering
   - Created house_age
   - Created renovated feature

4. Exploratory Data Analysis (EDA)
   - Distribution plots
   - Scatter plots
   - Heatmap

5. Model Building
   - Linear Regression
   - Random Forest

6. Model Evaluation
   - R² Score
   - RMSE
   - MAE

---

## 📈 Results

| Model | R² Score |
|------|---------|
| Linear Regression | ~0.68 |
| Random Forest | ~0.86 |

👉 Random Forest performed better.

---

## 🔍 Key Insights

- House price depends strongly on area (sqft_living)
- Grade and location are major factors
- Outliers affect model performance
- Random Forest handles complex data better

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🚀 Future Improvements

- Use XGBoost
- Hyperparameter tuning
- Deployment using Streamlit


