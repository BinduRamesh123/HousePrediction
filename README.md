# House Price Prediction using Linear Regression

##  Project Overview
This project focuses on predicting house prices using the California Housing dataset. It involves data preprocessing, exploratory data analysis (EDA), feature selection, and building a regression model using Ordinary Least Squares (OLS).

---

##  Objectives
- Analyze housing dataset and identify key influencing features
- Perform data cleaning and handle missing values
- Remove outliers using IQR method
- Build a regression model to predict house prices
- Evaluate model performance using appropriate metrics

---

##  Dataset
- Dataset: California Housing Dataset (Scikit-learn)
- Features include:
  - Median Income
  - House Age
  - Average Rooms
  - Population
  - Location (Latitude & Longitude)

---

##  Exploratory Data Analysis
- Pairplot visualization for feature relationships
- Correlation heatmap to identify strong predictors
- Scatter plots for key features (e.g., MedInc vs HousePrice)

---

##  Data Preprocessing
- Handled missing values
- Checked multicollinearity using VIF
- Removed less important features (Latitude, Longitude)
- Applied outlier treatment using IQR method

---

##  Model Used
- Ordinary Least Squares (OLS) Linear Regression using Statsmodels

---

##  Model Evaluation
The model was evaluated using:
- R² Score
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

**Final Results:**
- RMSE: 0.7161  
- MAE: 0.5323  

---

##  Key Insights
- Median Income (MedInc) is highly correlated with house price
- Model shows stable performance (RMSE slightly higher than MAE)
- Outlier removal improved model reliability

---

##  Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Statsmodels

---

## 📁 Project Structure
