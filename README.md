# House Price Prediction

## Project Overview

This project develops an end-to-end Machine Learning Regression pipeline to predict residential house prices using the Ames Housing Dataset. The project demonstrates the complete supervised learning workflow from data preprocessing to model deployment.

The objective is to compare multiple regression algorithms and identify the best-performing model for predicting house prices.

---

## Dataset

- Dataset: Ames Housing Dataset
- Source: Kaggle - House Prices: Advanced Regression Techniques
- Records: 1460
- Features: 79
- Target Variable: SalePrice

---

## Objectives

- Perform Exploratory Data Analysis (EDA)
- Handle missing values and outliers
- Perform feature engineering
- Encode categorical variables
- Scale numerical variables
- Train multiple regression models
- Tune hyperparameters
- Compare model performance
- Perform residual analysis
- Save the final machine learning pipeline

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib

---

## Project Structure

house-price-regression-supervised-learning/

├── train.csv

├── test.csv

├── sample_submission.csv

├── data_description.txt

├── HousePrice_SupervisedLearning.ipynb

├── House_Price_Prediction.py

├── house_price_pipeline.pkl

├── summary_report.md

├── requirements.txt

└── README.md

---

## Machine Learning Workflow

### Step 1

- Problem Understanding
- Business Understanding

### Step 2

- Exploratory Data Analysis
- Distribution Analysis
- Correlation Analysis
- Missing Value Analysis

### Step 3

- Missing Value Handling
- Outlier Removal
- Feature Engineering
- Feature Encoding
- Feature Scaling
- Train-Test Split

### Step 4

Implemented Models

- Linear Regression
- Ridge Regression
- Lasso Regression

### Step 5

Advanced Models

- Random Forest Regressor
- XGBoost Regressor

Performed Hyperparameter Tuning using RandomizedSearchCV.

### Step 6

Compared models using

- RMSE
- MAE
- R² Score
- Cross Validation RMSE
- Training Time

### Step 7

Residual Analysis

- Residual Plot
- Histogram
- QQ Plot

### Step 8

Deployment

- Saved preprocessing pipeline
- Saved trained model using Joblib

---

## Feature Engineering

Created new features:

- TotalSF
- HouseAge
- RemodAge
- HasGarage
- HasPool

---

## Model Evaluation

Performance was evaluated using

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score
- 5-Fold Cross Validation

---

## Important Features

Top contributing features include

- OverallQual
- GrLivArea
- TotalBsmtSF
- GarageArea
- GarageCars
- Neighborhood
- YearBuilt
- TotalSF

---

## Business Applications

This model can be used by

- Real Estate Companies
- Property Buyers
- Property Sellers
- Banks
- Home Loan Providers
- Property Valuation Platforms

---

## Installation

Install required libraries

```bash
pip install -r requirements.txt
```

Run the project

```bash
python House_Price_Prediction.py
```

or

```bash
jupyter notebook HousePrice_SupervisedLearning.ipynb
```

---

## Future Improvements

- Feature Selection
- Bayesian Optimization
- Ensemble Learning
- Model Stacking
- Flask API Deployment
- Cloud Deployment

---

## Author

**Tirth Mevada**

B.Tech Computer Engineering

Machine Learning | Data Analytics | Python | SQL | Power BI

---

## License

Educational Project
