# Email Spam Classifier Using NLP and Logistic Regression

## Introduction
In today's digital age, email communication has become an essential part of daily life. With the increase in email usage, there has been a significant rise in unsolicited and unwanted emails, commonly known as spam. These spam emails clutter inboxes, making it challenging to manage important communications efficiently. To address this issue, I developed a spam filter that can accurately classify emails as either spam or not spam (ham).

This project aims to build an effective spam filter using Natural Language Processing (NLP) techniques and Logistic Regression. By analyzing the textual content of emails, I identify patterns and features that distinguish spam from legitimate emails.

### Key Objectives:
1. **Data Preprocessing**: Cleaning and preparing the email dataset for analysis.
2. **Feature Extraction**: Using NLP techniques to extract meaningful features from the email text.
3. **Model Training**: Training a Logistic Regression model on the extracted features to classify emails.
4. **Model Evaluation**: Evaluating the performance of the trained model using appropriate metrics.

## Data
The dataset consists of email messages and their labels (0 for ham, 1 for spam). The labeled training dataset contains 8,348 labeled examples, and the unlabeled test set contains 1,000 unlabeled examples.

## Sections

### Section 1: Building a Simple Model
1. **Loading and Cleaning Data**: The dataset is loaded into a DataFrame and preprocessed to handle missing values.
2. **Exploratory Data Analysis (EDA)**: Visualization of word frequencies, email structures, punctuation, capitalization, and length of emails.
3. **Feature Engineering**: Creation of a function `words_in_texts` to generate numeric features from email text.
4. **Model Training**: Training a simple logistic regression model and evaluating its performance using various metrics such as accuracy, precision, recall, and false positive rate.

### Section 2: Building a Complex Model using Feature Engineering, Classification, and Cross-Validation
1. **Feature Engineering**: Identifying and extracting the most relevant features from the dataset by calculating the correlation between each potential feature and the spam/ham indicator.
2. **Visualization**: Using bar plots and heatmaps to visualize the correlation of features and identify potential multicollinearity issues.
3. **Model Training and Evaluation**: Implementing cross-validation to ensure that the chosen features do not overfit the dataset and are generalizable to unseen data. Building a more complex logistic regression model and plotting an ROC curve to understand the trade-off between false positives and false negatives.

## What I Learned
Throughout this project, I learned several key concepts and skills:
1. **Feature Engineering**: The process of extracting and selecting meaningful features from raw data to improve model performance.
2. **Data Visualization**: The importance of visualizing data to uncover patterns and insights that guide feature selection and model building.
3. **Model Evaluation**: Using various metrics to evaluate model performance and understand the trade-offs between different types of errors (e.g., false positives and false negatives).
4. **Cross-Validation**: The importance of cross-validation in ensuring that the model generalizes well to unseen data and does not overfit the training set.
5. **ROC Curve Analysis**: Understanding how to use ROC curves to analyze the trade-off between sensitivity and specificity and to select an appropriate threshold for classification.

## Conclusion
The final model achieved a training accuracy of 0.9170770664182084 (91%), demonstrating that the selected features and logistic regression approach were effective in classifying spam and ham emails. This project showcased the importance of feature engineering, proper evaluation metrics, and cross-validation in building a robust and accurate classifier. By carefully analyzing the data and refining the model, I was able to achieve a high level of accuracy in classifying spam and ham emails.