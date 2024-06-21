# Consumer-Price-Index-Modeling

# Table of Contents
* Background & Purpose
* Dataset
* Workflow
* CPI Prediction Demo
* Conclusions

# Background & Dataset

The Consumer Price Index (CPI) is a measure of inflation, tracking changes in the prices of goods and services over time. It reflects the average expenditure of consumers and is used by policymakers, economists, and businesses to assess economic trends. CPI's components include a representative "market basket" of goods, weighted to reflect consumer spending patterns. In this project, I employed multiple linear regression to model and predict CPI prices, leveraging historical data and economic indicators to develop accurate forecasts. This endeavor enhances understanding of inflation dynamics and offers practical insights for economic forecasting and decision-making.

# Dataset

The dataset I analyzed included data starting from the 1950's and has columns for every basket of good. I will be using each of these baskets to make accurate predictions

<img width="979" alt="image" src="https://github.com/aathijmuthu/Consumer-Price-Index-Modeling/assets/65832367/af8f54f4-6250-4180-9e64-d044d62305ad">

# Workflow

* Importing Libraries
* Exploratory Data Analysis
* Data Preprocessing (Cleaning)
* Correlation Analysis & Visualization
* Regression Modeling and Analysis
* Drawing Conclusions

# CPI Prediction Demo

I developed a short demo of my model. This app is built with HTML, CSS, and Flask. Users can input a any year and the app will give CPI predictions and corresponding visualization based off of my model.

User input page:


<img width="846" alt="image" src="https://github.com/aathijmuthu/Consumer-Price-Index-Modeling/assets/65832367/89192232-9912-4068-b841-e8d20fd2fec8">


Output of Model:


<img width="923" alt="image" src="https://github.com/aathijmuthu/Consumer-Price-Index-Modeling/assets/65832367/dec273f6-a4e4-4b90-8d57-b2fa12f45dd7">

# Conclusions

1) The linear regression model received an accuracy of ~98-99% in predicting consumer price index values for the American economy.

2) The model had the following coefficients:
- Apparel: 0.203
- Energy: 0.035
- Food: 0.506
- Gas: 0.020
- Medical: 0.004
- Transportation: 0.291

3) Due to the linear trend of the data, our model had a very high accuracy with just multiple linear regression and without needing hyperparameter tuning. Our model shows that historically, food values have the strongest relationship to all items value, while medical and gas have the weakest relationship to all items value.


