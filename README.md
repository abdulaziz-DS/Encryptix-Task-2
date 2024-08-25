# Encryptix Task 2: Sales Prediction

## Overview
This project focuses on building a predictive model that forecasts the sales of products based on various features such as advertising expenditure, target audience segmentation, and advertising platform selection. The primary goal is to analyze historical sales data and develop a machine learning model that accurately predicts future sales, enabling businesses to optimize their marketing strategies.

## Dataset
The dataset used in this project is based on advertising and sales data and includes features such as TV, radio, and newspaper advertising budgets, along with the corresponding sales figures. The dataset was provided in CSV format, and necessary preprocessing steps were applied to prepare it for modeling.

## Project Structure
- **Data Preprocessing:** The dataset was cleaned and preprocessed to handle missing values and irrelevant columns. Numerical features were retained, and any necessary transformations were applied.
  
- **Feature Engineering:** The features were analyzed and used directly in the model, given their numerical nature and relevance to the prediction task.

- **Modeling:** A linear regression model was built to predict sales. The model was trained using historical advertising data and then evaluated on a test set.

- **Evaluation:** The model's performance was assessed using metrics such as Mean Squared Error (MSE) and R-squared.

## Model and Results
The model used was a linear regression model trained and evaluated on the preprocessed data. The performance of the model was measured using the Mean Squared Error (MSE) and R-squared metrics. The results are as follows:

- **Mean Squared Error (MSE):** 2.23 (example value)
- **R-squared:** 0.90 (example value)

## Insight
The strong correlation between actual and predicted sales suggests that the model has a good predictive ability. However, the presence of some deviations indicates that there is room for further improvement, such as exploring more complex models or additional features.
