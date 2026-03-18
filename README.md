🏠 House Price Prediction (Machine Learning Project)
📌 Project Overview

Predicting house prices is a key problem in real estate and data science. Accurate price estimation helps buyers, sellers, and investors make better decisions.

In this project, I performed Exploratory Data Analysis (EDA) and built multiple Machine Learning regression models on a housing dataset to predict median house values based on various features such as location, income, and housing characteristics.

🎯 Objectives

Perform EDA to understand patterns affecting house prices

Build and compare multiple regression models

Evaluate models using metrics like RMSE, MAE, and R²

Identify the most important features influencing house prices

Select the best-performing model for prediction

🗂 Dataset

Source: California Housing Dataset

File Used: housing.csv

Features:

Location: longitude, latitude

House Details: total_rooms, total_bedrooms, housing_median_age

Demographics: population, households

Income: median_income

Categorical: ocean_proximity

Target Variable: median_house_value

🛠 Tech Stack

Language: Python

Libraries:

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

🔎 Exploratory Data Analysis (EDA)

Key insights from the dataset:

Median income has a strong positive correlation with house prices

Houses near the ocean (e.g., NEAR BAY, NEAR OCEAN) are more expensive

Higher population density areas tend to have varied pricing

Missing values were present in total_bedrooms and handled using imputation

📊 Visualizations included:

Distribution of house prices

Correlation heatmap

Income vs House Price

Location-based price comparisons

⚙️ Data Preprocessing

Handled missing values using SimpleImputer

Scaled numerical features using StandardScaler

Encoded categorical features using OneHotEncoder

Used ColumnTransformer to combine preprocessing steps

🤖 Models Implemented
1. Linear Regression

Simple baseline model

Fast and interpretable

2. Ridge Regression

Handles multicollinearity

Better generalization than Linear Regression

3. Lasso Regression

Performs feature selection

Helps reduce overfitting

4. Random Forest Regressor

Captures non-linear relationships

Provides strong performance

5. Hist Gradient Boosting Regressor

Efficient and powerful boosting model

Often gives best accuracy

📈 Model Evaluation

Used Cross Validation (K-Fold) with metrics:

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

R² Score

👉 Models were compared and sorted based on lowest RMSE

🏆 Key Insights

Median income is the most important predictor of house prices

Location plays a major role in determining value

Tree-based models outperform linear models in accuracy

Proper preprocessing significantly improves performance
