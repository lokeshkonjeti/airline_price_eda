# airline_price_eda

This project focuses on predicting flight ticket prices based on historical data using machine learning techniques. It demonstrates a complete data science pipeline — from data preprocessing and visualization to feature engineering and model training.

The project uses two CSV files:

Data_Train.csv: Training dataset with features like airline, source, destination, departure/arrival times, duration, etc.

Test_set.csv: Test dataset without the target column (Price) for which predictions are made.

# Project Steps
1. Data Loading and Preprocessing
Read both training and test datasets using pandas.

Concatenate them for unified preprocessing and export to combined_data.csv.

2. Feature Engineering
Extracted features like journey day/month, departure/arrival hours/minutes, and duration in hours/minutes from datetime columns.

Encoded categorical variables using both Label Encoding and One-Hot Encoding.

3. Exploratory Data Analysis (EDA)
Plotted distributions and correlations using seaborn and matplotlib to understand feature-target relationships.

Analyzed trends based on airline, number of stops, source/destination, etc.

4. Model Building
Trained multiple regression models including:

Linear Regression

Random Forest Regressor

XGBoost Regressor

Used cross-validation and grid search for hyperparameter tuning.

Evaluated models using RMSE, R² Score, and visualized prediction errors.

5. Prediction & Output
Made predictions on the test set using the best-performing model.

Exported results to submission.csv for further evaluation.
