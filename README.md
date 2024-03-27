# UCB Data 100: 1st Place Solution for Machine Learning Model Project

## Overview

This is the first-place solution for Project A2 in the Data 100 course at UC Berkeley, distinguished among submissions from over 1000 students. The challenge was to develop a machine learning model that predicts housing prices with high accuracy, employing advanced data preprocessing and feature engineering techniques.

<img width="999" alt="Screen Shot 2024-03-26 at 9 41 49 PM" src="https://github.com/ayumu0622/UCBData100-1stSolutionMLModel/assets/67722808/dddede96-b260-48be-a222-bf253b829150">

## Project Highlights

- **Target Encoding for Categorical Data**: Utilized target encoding on nominal data (e.g., town and neighborhood codes) to reduce the curse of dimensionality, enhancing model accuracy by calculating the average housing price for each category.

- **Mitigating Multicollinearity**:
  - Eliminated features with high correlation to others to prevent multicollinearity, ensuring our model's predictors remain independent.
  - Carefully selected features with even minimal correlations to housing prices to keep our model comprehensive and robust.

- **Outlier Management**: Removed extreme outliers based on 1.5 * IQR and values under 500, which are considered abnormal for housing prices, while maintaining a balance to avoid overfitting and preserve model robustness.

- **Textual Data Insights**: Extracted key numerical data from text using regex, including bedroom count, number of stories, and bathroom count, providing our model with more nuanced predictors.

- **Data Transformation & Standardization**: 
  - Applied logarithmic transformations to qualitative features and employed standard scaling to normalize the dataset, substantially improving our model's predictive accuracy and interpretability.
