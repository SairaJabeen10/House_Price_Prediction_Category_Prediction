# House Price Prediction Using Machine Learning

## Overview

This project focuses on predicting house prices using Machine Learning techniques. The objective is to analyze housing features and build predictive models that can estimate property prices and classify houses into different price categories.

The project includes data preprocessing, exploratory data analysis, regression modeling, classification modeling, and performance evaluation.

---

## Objectives

* Clean and preprocess real-world housing data.
* Handle missing values and categorical features.
* Analyze relationships between housing attributes and sale prices.
* Predict house prices using Linear Regression.
* Classify houses into price categories using Random Forest Classifier.
* Evaluate model performance using appropriate metrics.

---

## Dataset

The project uses the **House Prices Dataset** (`train.csv`).

### Target Variable

* **SalePrice** – The selling price of a house.

### Important Features

* OverallQual
* GrLivArea
* GarageCars
* TotalBsmtSF
* FullBath

---

## Data Preprocessing

### 1. Missing Value Handling

* Numerical features filled using median values.
* Categorical features filled using mode values.

### 2. Feature Selection

* Removed the `Id` column as it does not contribute to prediction.

### 3. Label Encoding

* Converted categorical variables into numerical format.

### 4. Feature Scaling

* Standardized numerical features using `StandardScaler`.

---

## Exploratory Data Analysis (EDA)

### House Price Distribution

* Visualized using histograms.
* Identified the distribution of housing prices.

### Correlation Analysis

* Examined relationships between features and house prices.
* Selected highly correlated features for model development.

---

## Machine Learning Models

### 1. Linear Regression (Regression Task)

Used to predict continuous house prices.

#### Input Features

* OverallQual
* GrLivArea
* GarageCars
* TotalBsmtSF
* FullBath

#### Evaluation Metrics

* R² Score
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

---

### 2. Random Forest Classifier (Classification Task)

Used to classify houses into:

* Low Price
* Medium Price
* High Price

#### Evaluation Metrics

* Accuracy Score
* Classification Report
* Confusion Matrix

---

## Project Workflow

```text
Dataset Collection
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Label Encoding
        ↓
Feature Scaling
        ↓
Train-Test Split
        ↓
Linear Regression
        ↓
Random Forest Classification
        ↓
Performance Evaluation
```

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Results

### Linear Regression

* Successfully predicted house sale prices.
* Important housing features significantly influenced predictions.

### Random Forest Classifier

* Effectively classified houses into price categories.
* Achieved strong classification performance through ensemble learning.

---

## Future Improvements

* Hyperparameter tuning.
* Feature engineering using advanced techniques.
* Testing additional regression models such as:

  * Random Forest Regressor
  * XGBoost Regressor
  * Gradient Boosting Regressor
* Deploying the model as a web application.

---

## Conclusion

This project demonstrates a complete Machine Learning pipeline for housing price analysis. Through preprocessing, visualization, regression, and classification techniques, the system successfully predicts house prices and categorizes properties into different price ranges. The project highlights the practical application of Machine Learning in real-estate analytics.

---

## Author

**Saira Jabeen**
BS Artificial Intelligence – 5th Semester
Dawood University of Engineering & Technology
Roll No: 23-AI-10
