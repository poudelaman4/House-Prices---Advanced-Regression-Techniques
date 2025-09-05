# House Price Prediction (Project 3/14)

## 📌 Objective
Predict house prices based on various features (location, rooms, area, etc.) using machine learning regression models.

## 📂 Dataset
- Source: [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- Target variable: `SalePrice`

## ⚙️ Steps
1. Data loading (CSV files from Kaggle)
2. Data cleaning
   - Handle missing values
   - Encode categorical variables
3. Model training
   - Linear Regression
   - Random Forest Regressor
   - SVR
   - Greadient Boosting Regressors
4. Evaluation
   - Metrics: Mean Squared Error (MSE), R² Score

## 📊 Results
- Linear Regression R² ≈ 0.7–0.8 (depending on preprocessing)
- Random Forest Regressor R² ≈ 0.8+

## 🚀 How to Run
1. Download the dataset from Kaggle and place it in the project folder
2. Open `house_price_prediction.ipynb`
3. Run the notebook cells step by step

## 📝 Notes
- This project was done **without pipelines** for learning purposes.
- In future projects, pipelines and deployment will be a
