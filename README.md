# Regression: Housing Price Predictions

---

## Context:
Kaggle competition with the objective of developing a model to predict housing prices in Ames Iowa based on historical data.  Only Regression models were allowed for competition, no neural nets.  This model achieved a <B>3rd place</B> leaderboard ranking (out of 123 competitors) based on RMSE.  This model is valid for price predictions.

## Key objectives:
 <B>

    - Create model to predict housing prices based on historical data
    - Evaluate model
    - Disseminate techniques, methods, results to technical audience and colleagues
 </B>
 
---

## Executive Summary

- Normal Distribution is an important factor for machine learning algorithms.  Addressing outliers and applying natural log can assist in normalizing and thereby improving prediction performance

- In addition, Understanding Variable Correlation and Feature Engineering can elevate model prediction performance

- Seasonality affected Ames sales volume but Average Sale Prices remained fairly consistent

- For the Ames Housing Dataset Ranking Neighborhoods reduced multicollinearity, improved SalePrice predictions and directly drove a substantial RSME score improvement

- Visualizing and identifying high mean variance within a variable can indicate degree of influence on Target (Sale Price)

- The model suggests that Gr Liv Area, Overall Quality, Age, Neighborhood Rank, Bathrooms, Total Sq Ft were leading features with impactful coefficients

- The value of the model is that it is accurate and can facilitate real estate agency decision making and housing price prediction

- <B>Key recommendation: trial first, then place model into production in order to drive operational/strategic real estate agency decision making.  Over time the model will continue to learn and increasingly become more accurate </B>

---

<img src=https://i.imgur.com/HhZDbQy.png>
