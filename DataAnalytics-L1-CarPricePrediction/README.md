# Car Price Prediction with Machine Learning

## OASIS INFOBYTE Data Analytics Internship — Task 3

## Project Overview

This project focuses on predicting the selling price of used cars using machine learning regression techniques.

The project uses the Vehicle Dataset from CarDekho and applies data preprocessing, exploratory data analysis, feature engineering, categorical encoding, regression modeling, model evaluation, and feature importance analysis.

## Objective

The objective is to develop a machine learning model that can predict used-car selling prices based on vehicle characteristics such as:

- Manufacturing Year
- Kilometres Driven
- Fuel Type
- Seller Type
- Transmission
- Owner Type
- Car Brand
- Car Age

## Dataset

The dataset used in this project is the CarDekho Used Car Dataset.

The original dataset contained:

- 4,340 records
- 8 columns

After removing duplicate records:

- 3,577 records remained

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Machine Learning Algorithms

The following regression algorithms were implemented:

1. Linear Regression
2. Random Forest Regressor
3. Gradient Boosting Regressor

## Project Workflow

### 1. Data Loading

The CarDekho dataset was loaded into a Pandas DataFrame.

### 2. Data Cleaning

The dataset was checked for:

- Missing values
- Duplicate records
- Categorical values

No missing values were found.

A total of 763 duplicate records were identified and removed.

### 3. Feature Engineering

Two additional features were created:

- `brand` — extracted from the car name
- `car_age` — calculated from the manufacturing year

### 4. Exploratory Data Analysis

The following visualizations were created:

- Selling price distribution
- Selling price by fuel type
- Selling price vs car age
- Selling price vs kilometres driven
- Top 15 car brands
- Average selling price by transmission
- Average selling price by fuel type
- Correlation heatmap

### 5. Data Preparation

Categorical variables were encoded using LabelEncoder.

The dataset was divided into:

- 80% Training Data
- 20% Testing Data

### 6. Model Training

Three regression models were trained:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## Model Performance

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | ₹214,459.00 | ₹444,901.43 | 0.3855 |
| Random Forest | ₹169,215.36 | ₹413,217.60 | 0.4699 |
| Gradient Boosting | ₹162,286.34 | ₹402,660.93 | 0.4967 |

Among the three tested models, Gradient Boosting achieved the highest R² score and the lowest MAE and RMSE on the test dataset.

## Best Model

### Gradient Boosting Regressor

Performance:

- MAE: ₹162,286.34
- RMSE: ₹402,660.93
- R² Score: 0.4967

## Feature Importance

The Gradient Boosting model identified the following features as relatively more influential:

- Transmission
- Brand
- Year
- Fuel
- Car Age
- Kilometres Driven

## Key Findings

- The dataset contained 4,340 original records.
- 763 duplicate records were removed.
- 3,577 records remained after cleaning.
- No missing values were found.
- Car brand and car age were created through feature engineering.
- Three regression models were compared.
- Gradient Boosting achieved the highest R² score among the tested models.
- Gradient Boosting also produced the lowest MAE and RMSE among the tested models.

## Conclusion

This project demonstrates a complete machine learning workflow for predicting used-car selling prices.

The project covered data cleaning, feature engineering, exploratory data analysis, categorical encoding, model training, model comparison, evaluation, and feature importance analysis.

Among the tested regression models, Gradient Boosting Regressor achieved an R² score of 0.4967 with an MAE of ₹162,286.34 and an RMSE of ₹402,660.93 on the test dataset.

## Project Files

- `Car_Price_Prediction.ipynb` — Complete Google Colab/Jupyter Notebook
- `README.md` — Project documentation
- `screenshots/` — Selected project outputs and visualizations

## Internship

**OASIS INFOBYTE Data Analytics Internship**

**Task 3 — Car Price Prediction with Machine Learning**
