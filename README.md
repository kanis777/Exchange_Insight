# Foreign Currency Exchange Prediction Project

## Overview

This project aims to predict foreign currency exchange rates using machine learning techniques. The data was obtained from the Free Currency API (https://freecurrencyapi.com/) and processed to clean outliers, missing and null values. A Random Forest Regression model was trained on the preprocessed data, and hyperparameter tuning was performed to optimize the model's performance. The model's predictions were evaluated using accuracy metrics, and privacy was ensured using the Privacy-Aware Training Environments (PATE) framework for security.

## Libraries Used

- ![H2O](https://img.shields.io/badge/H2O-000000?style=for-the-badge&logo=h2o)
- ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
- ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy)
- ![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)
- ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
- ![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=python&logoColor=white)
- ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
- ![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

## Steps

### 1. Data Extraction

Data is extracted from freecurrencyapi.com to obtain historical currency exchange rates.

### 2. Data Cleaning and Preprocessing

- Duplicate values are removed to ensure data integrity.
- Missing and null values are handled through imputation or removal based on the data characteristics.
- Outliers are detected and treated using the Interquartile Range (IQR) method.

### 3. Model Selection

A Random Forest Regression model is chosen for its ability to handle nonlinear relationships and robustness against overfitting.

### 4. Model Training

The Random Forest Regression model is trained on the preprocessed data to learn the underlying patterns and relationships.

### 5. Hyperparameter Tuning

Hyperparameters of the Random Forest Regression model are optimized using techniques like Grid Search or Random Search to enhance performance.

### 6. Currency Prediction

The trained model is used to predict future currency exchange rates based on historical data.

### 7. Evaluation

Model predictions are evaluated using accuracy metrics such as mean squared error (MSE), R-squared (R2) score, and mean absolute error (MAE) to assess predictive performance.

### 8. Security with PATE

Privacy-Aware Training Environments (PATE) framework is implemented to ensure the security and privacy of sensitive data used in the project.

## Usage

1. **Data Collection**: Run the data extraction script to obtain currency exchange rate data from freecurrencyapi.com.

2. **Preprocessing**: Clean the data, handle missing values, and remove outliers using the preprocessing script.

3. **Model Training**: Train the Random Forest Regression model on the preprocessed data.

4. **Hyperparameter Tuning**: Optimize the model's hyperparameters to improve performance.

5. **Currency Prediction**: Use the trained model to predict future currency exchange rates.

6. **Evaluation**: Evaluate the model's performance using accuracy metrics.

7. **Security Implementation**: Implement the PATE framework to ensure data security and privacy.
