# House Price Prediction 🏠📊

A machine learning project that predicts house sale prices using the **Home Data for ML Course** dataset from Kaggle (based on the Ames Housing dataset).

This project was built as part of Kaggle's *Intro to Machine Learning* course and competition.

## 📂 Dataset
- Source: [Home Data for ML Course – Kaggle Competition](https://www.kaggle.com/c/home-data-for-ml-course)
- Target variable: `SalePrice`
- Files used: `train.csv`, `test.csv`

## 🛠️ Tools & Libraries
- Python
- pandas
- scikit-learn (`RandomForestRegressor`, `train_test_split`, `mean_absolute_error`)

## 🔍 Approach
1. Loaded the training data and separated the target variable (`SalePrice`).
2. Selected key numeric features:
   - `LotArea`, `YearBuilt`, `1stFlrSF`, `2ndFlrSF`, `FullBath`, `BedroomAbvGr`, `TotRmsAbvGrd`
3. Split the data into training and validation sets.
4. Trained a **Random Forest Regressor** model.
5. Retrained the final model on the **full training dataset** to maximize learning before prediction.
6. Used the trained model to predict house prices on the test dataset.
7. Generated a `submission.csv` file in the format required for Kaggle competition scoring.

## 📈 Results
- Model: Random Forest Regressor
- Submission file generated and validated for Kaggle's competition format

## 🚀 Future Improvements
- Add exploratory data analysis (EDA) with visualizations (correlation heatmaps, price distribution, etc.)
- Engineer additional features from categorical and numeric columns
- Compare multiple models (Linear Regression, XGBoost, Gradient Boosting)
- Perform hyperparameter tuning for better accuracy
- Report validation metrics (MAE/RMSE) for model comparison

## 📎 Links
- Kaggle Notebook: *[add your notebook link here]*
- Competition Page: [Home Data for ML Course](https://www.kaggle.com/c/home-data-for-ml-course)

## 🙋 About
This project is part of my journey learning Machine Learning through Kaggle's Intro to Machine Learning course.
