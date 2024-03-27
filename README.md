# UCB Data 100: 1st Place Solution for Machine Learning Model Project

## Overview

Welcome to the GitHub repository for the first-place solution in the UC Berkeley Data 100 course's Project A2. This project aimed to develop a sophisticated machine learning model to predict housing prices, leveraging advanced data preprocessing and feature engineering techniques.

## Project Highlights

- **Target Encoding for Categorical Data**: Utilized target encoding on nominal data (e.g., town and neighborhood codes) to reduce the curse of dimensionality, enhancing model accuracy by calculating the average housing price for each category.

- **Mitigating Multicollinearity**:
  - Eliminated features with high correlation to others to prevent multicollinearity, ensuring our model's predictors remain independent.
  - Carefully selected features with even minimal correlations to housing prices to keep our model comprehensive and robust.

- **Outlier Management**: Removed extreme outliers based on 1.5 * IQR and values under 500, which are considered abnormal for housing prices, while maintaining a balance to avoid overfitting and preserve model robustness.

- **Textual Data Insights**: Extracted key numerical data from text using regex, including bedroom count, number of stories, and bathroom count, providing our model with more nuanced predictors.

- **Data Transformation & Standardization**: 
  - Applied logarithmic transformations to qualitative features and employed standard scaling to normalize the dataset, substantially improving our model's predictive accuracy and interpretability.

## About

This repository represents a milestone achievement in the Data 100 course at UC Berkeley, distinguishing itself by addressing the intricate challenges of predicting housing prices with an innovative and effective machine learning model.
