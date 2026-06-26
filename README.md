# house-price-prediction-ml
Predicting house prices using Random Forest on Kaggle's housing dataset

📂 Dataset


Source: Home Data for ML Course – Kaggle Competition
Target variable: SalePrice
Files used: train.csv, test.csv


🛠️ Tools & Libraries


Python
pandas
scikit-learn (RandomForestRegressor, train_test_split, mean_absolute_error)


🔍 Approach


Loaded the training data and separated the target variable (SalePrice).
Selected key numeric features:

LotArea, YearBuilt, 1stFlrSF, 2ndFlrSF, FullBath, BedroomAbvGr, TotRmsAbvGrd



Split the data into training and validation sets.
Trained a Random Forest Regressor model.
Retrained the final model on the full training dataset to maximize learning before prediction.
Used the trained model to predict house prices on the test dataset.
Generated a submission.csv file in the format required for Kaggle competition scoring.


📈 Results


Model: Random Forest Regressor
Submission file generated and validated for Kaggle's competition format


🚀 Future Improvements


Add exploratory data analysis (EDA) with visualizations (correlation heatmaps, price distribution, etc.)
Engineer additional features from categorical and numeric columns
Compare multiple models (Linear Regression, XGBoost, Gradient Boosting)
Perform hyperparameter tuning for better accuracy
Report validation metrics (MAE/RMSE) for model comparison


📎 Links


Kaggle Notebook: [add your notebook link here]
Competition Page: Home Data for ML Course


🙋 About

This project is part of my journey learning Machine Learning through Kaggle's Intro to Machine Learning course.
