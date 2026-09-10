# Level 2 Task 1: Predicting House Prices with Linear Regression

## 📌 Project Overview

This project is part of my **Data Analytics Internship at Oasis Infobyte (OIBSIP)**.

The objective of this task is to build a **Linear Regression model** to predict house prices using different property-related features such as area, number of bedrooms, bathrooms, stories, parking, age, locality rating, and other categorical features.

The project covers the complete process from **exploratory data analysis and data preparation to model training, evaluation, and interpretation**.

## 🎯 Objective

To develop and evaluate a Linear Regression model that can predict house prices based on available property features.

## 📊 Dataset

The dataset was obtained from Kaggle.

[enhanced_house_price_dataset - Kaggle](https://www.kaggle.com/datasets/chershi/house-price-prediction-dataset-2000-rows?)

The dataset contains **2,000 house records** with **16 columns**.

Some of the important features include:

* Area
* Bedrooms
* Bathrooms
* Stories
* Parking
* Age
* City
* Furnishing
* Main Road
* Guest Room
* Basement
* Water Supply
* Air Conditioning
* Preferred Tenant
* Locality Rating

**Target variable:** `Price`

## 🔍 Steps Performed

### 1. Exploratory Data Analysis

* Checked the dataset shape and column names
* Examined data types
* Checked for missing values and duplicate rows
* Generated descriptive statistics
* Visualized the distribution of house prices

### 2. Feature Selection

Selected relevant property features as predictors and used `Price` as the target variable.

### 3. Data Cleaning

* Checked for missing values
* Used median values for missing numerical data
* Used mode values for missing categorical data
* Verified the dataset after handling missing values

### 4. Categorical Encoding

Categorical variables were converted into numerical form using **One-Hot Encoding** with `pd.get_dummies()`.

### 5. Correlation Analysis

* Calculated correlations between features and house prices
* Created a correlation heatmap
* Identified features having stronger positive or negative relationships with `Price`

### 6. Train-Test Split

The dataset was divided into:

* **80% training data**
* **20% testing data**

### 7. Linear Regression Model

A Linear Regression model from Scikit-learn was trained using the training dataset and then used to predict house prices for the test dataset.

### 8. Model Evaluation

The model was evaluated using:

* **Mean Squared Error (MSE)**
* **Root Mean Squared Error (RMSE)**
* **R² Score**

### 9. Prediction Analysis

Created an **Actual vs Predicted Price** plot to compare the model's predictions with the actual house prices.

### 10. Residual Analysis

A residual plot was created to understand the difference between actual and predicted prices and to observe the model's prediction errors.

### 11. Coefficient Analysis

The model coefficients were examined to understand how different features influence the predicted house price.

## 📈 Model Performance

The Linear Regression model achieved:

* **MSE:** 20,133,032,720.03
* **RMSE:** 141,890.92
* **R² Score:** 0.7779

The R² score indicates that the model explains approximately **77.79% of the variation in house prices** in the test data.

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook


## 💡 Conclusion

This project helped me understand the complete workflow of a **supervised machine learning regression problem**, including data exploration, data preparation, categorical encoding, model training, evaluation, visualization, and interpretation.

The Linear Regression model provided a reasonable prediction of house prices and achieved an **R² score of 0.7779** on the test data.

## 👩‍💻 Internship

**Oasis Infobyte — Data Analytics Internship**
**Level 2 | Task 1**
