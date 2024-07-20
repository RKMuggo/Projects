# Housing Price Prediction and Analysis

## Overview
This project explores an extensive housing dataset from Cook County, Illinois. The dataset contains over 500,000 records with 61 features, and an additional 62nd feature, `Sale Price`, which is the target variable for prediction. The project is divided into two parts: 

1. **Section 1**: Conducting Exploratory Data Analysis (EDA) and Feature Engineering.
2. **Section 2**: Building a Linear Model for prediction and analyzing the model's error to brainstorm improvements.

## Section 1: Exploratory Data Analysis (EDA) and Feature Engineering

### Objectives
- Understand the structure of the data.
- Clean the dataset and engineer new features.

### Steps
1. **Data Visualization**: Created various plots to visualize the distributions and relationships between different variables.
2. **Summary Statistics**: Calculated key statistics to understand central tendencies and variability within the dataset.
3. **Handling Missing Values**: Identified and dealt with missing data to prevent issues in the analysis.
4. **Feature Creation**: Developed new features based on existing ones to capture more information and improve model performance.

### EDA Highlights
- Verified the dataset's shape and consistency.
- Explored variables such as `Bedrooms`, `Building Square Feet`, and `Neighborhood Code`.
- Applied log transformation to `Sale Price` and `Building Square Feet`.
- Created a function to remove outliers based on threshold values.

## Section 2: Linear Modeling and Error Analysis

### Objectives
- Build a linear regression model for predicting housing prices.
- Analyze the model's performance and brainstorm improvements.

### Steps
1. **Model Specification**: Defined the structure of the linear model and selected predictor variables.
2. **Model Fitting**: Used statistical techniques to estimate model parameters.
3. **Error Analysis**: Evaluated the model's predictions and understood the sources of error.
4. **Model Improvement**: Considered additional features, transformations, and alternative models to enhance prediction accuracy.

### Key Points
- The dataset was split into training (80%) and validation (20%) sets.
- Developed two models: one using `Bedrooms` and another using `Bedrooms` and `Log Building Square Feet`.
- Evaluated model performance using Root Mean Squared Error (RMSE).
- Visualized residuals to understand model performance and appropriateness.

## Human Context and Ethics

Explored the social context of the housing dataset, considering historical racial discrimination in property valuation and taxation in Cook County. Emphasized the importance of fairness and accuracy in predictive modeling, especially in contexts with real-world implications.

## Conclusion

This project highlighted the importance of thorough data analysis and careful model development. By understanding the data's structure and relationships, I built a linear model to predict housing prices in Cook County. This process involved significant feature engineering, model evaluation, and ethical considerations, aiming to ensure fair and accurate property assessments.

## What I Learned

Throughout this project, I gained valuable insights and skills, including:
- **Data Analysis**: Learned to explore and visualize large datasets to uncover patterns and relationships.
- **Feature Engineering**: Developed new features from existing data to improve model performance.
- **Model Building**: Built and evaluated linear regression models, understanding the importance of model specification and error analysis.
- **Ethical Considerations**: Recognized the importance of fairness in predictive modeling, especially in contexts with significant real-world impacts, such as property taxation.
- **Problem Solving**: Enhanced my ability to approach complex problems methodically and systematically, from data cleaning to model evaluation.