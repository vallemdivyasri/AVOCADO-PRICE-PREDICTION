# Avocado-Price-Prediction

This project focuses on predicting avocado prices using various regression algorithms, with Random Forest Regressor achieving the best performance. The goal is to accurately forecast avocado prices to aid stakeholders in the agriculture and retail sectors.

## Project Overview
Avocado prices can be influenced by several factors, including region, type, and seasonal trends. This project aims to build a predictive model to forecast the prices of avocados based on historical data.

## Dataset
The dataset used for this project is took from kaggle. [Dataset Link](https://www.kaggle.com/datasets/smokingkrils/avacado-price-prediction/data)
It contains historical data on avocado prices and sales volume across multiple regions in the United States. It includes features such as:

- Date
- Average Price
- Total Volume
- 4046 (PLU code for small Hass avocados)
- 4225 (PLU code for large Hass avocados)
- 4770 (PLU code for extra-large Hass avocados)
- Region
- Type (conventional or organic)
- Year
- Total Bags
- Small Bags
- Large Bags
- XLarge Bags
  
## Data Preprocessing
The preprocessing steps included:

**Handling Missing Values:** Checked for and handled any missing values.

**Feature Engineering:** Extracted additional features such as month and year from the date column to capture seasonal trends.

**Encoding Categorical Variables:** Applied one-hot encoding to the 'region' and 'type' columns.

## Modeling
Several regression models were trained and evaluated, including:

Linear Regression
SVM Regression
AdaBoost Regression
Decision Tree Regressor
Random Forest Regressor
The performance of each model was assessed using metrics such as R² score, RMSE (Root Mean Squared Error), MSE (Mean Squared Error), MAE (Mean Absolute Error).

Best Model: Random Forest Regressor
The Random Forest Regressor outperformed other models with the following metrics:

R² Score: 0.90
RMSE: 0.12
MAE: 0.09
MSE: 0.16

## Results
The Random Forest Regressor was able to capture the complex relationships in the data, providing accurate predictions of avocado prices.

## Conclusion
This project demonstrates the effectiveness of ensemble methods like Random Forest in predicting prices in the agricultural domain. The model can be further improved by incorporating more features and fine-tuning the hyperparameters.

## Future Work
Future enhancements to this project could include:

Incorporating additional features such as weather data and economic indicators.
Experimenting with more advanced models like Gradient Boosting Machines and Neural Networks.
Deploying the model as a web application for real-time price predictions.


