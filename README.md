# 🏠 Housing Price Prediction Model

This project focuses on predicting housing prices using machine learning models, based on the 1990 California Census dataset. The dataset is featured in Chapter 2 of *Aurélien Géron's Hands-On Machine Learning with Scikit-Learn and TensorFlow* and sourced from [Kaggle](https://www.kaggle.com).

---

## 📊 Dataset Overview

The dataset contains information on:
- Median house value
- Median income
- Housing and demographic features
- Geographic location (latitude and longitude)
- Ocean proximity

---

## 🛠️ Data Preprocessing

Before modeling, we prepared the data by:
- Removing duplicates
- Handling missing values
- Fixing data type mismatches
- Performing feature engineering to address multicollinearity
- Encoding categorical variables
- Scaling numerical features

---

## 📈 Model Evaluation

Our primary metric for model evaluation is the **R² Score**, which indicates how much of the variance in housing prices is explained by the model.

We experimented with multiple models:
- Linear Regression
- Random Forest
- Gradient Boosting (XGBoost)

**Gradient Boosting** emerged as the most effective model with the highest R² score.

---

## 🔍 Key Insights

- **Median Income** is the strongest predictor of house prices — higher income areas generally have higher home values.
- **ocean_proximity_INLAND** is another influential factor, confirming that inland properties are typically cheaper than coastal ones.
- **population_per_household** and **bedrooms_per_room** also show significant impact, indicating that crowding and room distribution matter.
- **Latitude and Longitude** carry moderate importance, suggesting geographical location (like proximity to cities or amenities) still plays a role.

---

## 💡 Recommendations

1. **Target High-Income Areas**:  
   Real estate developers and marketers should prioritize high-income neighborhoods for investments or advertising, as they correlate with higher housing prices.

2. **Affordable Housing in Inland Areas**:  
   Inland properties are generally less expensive — making them ideal for:
   - Affordable housing projects
   - First-time home buyers

3. **Design for Livability**:  
   A balanced ratio of bedrooms to overall room count enhances livability. Developers should aim for practical layouts to appeal to buyers.

---

## 📂 Project Structure

- `data/` – Raw and cleaned datasets
- `notebooks/` – EDA and model training notebooks
- `models/` – Saved model files
- `results/` – Visualizations and output files

---

## 📌 Conclusion

This project demonstrates how machine learning can effectively be used to predict housing prices and inform data-driven decision-making in real estate markets.

---

