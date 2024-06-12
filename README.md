![Example Image](Images/Credit_Card.png)

# Credit Card Approval Prediction

This project’s aim is to implement a credit card approval prediction by classifying that credit card approval can be predicted correctly based on the credit score column by finding the best model whose accuracy is best which will be used for prediction. For the prediction, complex data sets have been used to check which model will perform best by calculating the accuracy of the model on the dataset using the training and testing data obtained from the dataset.

## Authors

- [@Prakhar Singh](https://www.github.com/prakharsingh-08)

## Table of Content:

- <span style="color: blue; text-decoration: underline;">Introduction</span>
- <span style="color: blue; text-decoration: underline;">Key Steps</span>
- <span style="color: blue; text-decoration: underline;">Model Used</span>
- <span style="color: blue; text-decoration: underline;">Future Scopes</span>

## Introduction

This study applies modern machine learning approaches to the problem of credit card approval prediction. With a credit card, customers may borrow money from a financial institution to make purchases or withdraw cash up to a pre-established credit limit. The goal is to create a reliable model that, given a collection of important variables, reliably determines the chance of credit card acceptance. The dataset is derived from credit applicants and contains demographic data, financial history, and other important characteristics. The study takes a broad approach, combining selection, feature engineering, and many machine learning techniques, such as decision trees and linear regression, random forest. The results show a strong relationship between credit card acceptance and certain characteristics including income, debt-to-income ratio, and credit score. This project finds the best model for the credit card approval prediction which we can use for the outside world.

## Key Steps Involved in this Project

1. **Compiling and Setting Up Data** - This step ensures the data is extracted properly and data integrity is maintained also, the data is set up to be in a more easily understandable format.
2. **Data Sanitization** - Using various methods to maintain data integrity and consistency so that proper analysis can be done with the cleaned data is known as data sanitization. It is done by dealing with outliers and null values through various methods like using mean, median, or mode to get a better understanding of data.
3. **Engineering Features** - Creation and altering of various columns to be able to provide better insight and ease in calculation and analysis is called engineering features.
4. **Data Visualisation** - The graphical depiction of data to find trends, patterns, and insights is known as data visualization. It simplifies complicated datasets into visual representations, such as graphs or charts, so that people can comprehend and analyze the data more
easily.
5. **Data Preparation** - In the data preparation data is transformed according to the need of the method we want to apply to it. In our case, we used log transformation and label encoding for the application of correlation matrix using heatmap.
6. **Constructing and Evaluating Models** - Data is separated into training and testing sets. After training, the model's performance is assessed using the testing set. Various measures for accuracy are then implemented to check how well each model performs with any new data R^2, RMSE, and MSE are commonly used to evaluate the outcomes of a range of models.
7. **Hyperparameter Tuning** - Hyperparameter tuning is the process of adjusting a machine learning model's hyperparameters to improve performance. Hyperparameters are model-specific configuration choices that are unique to the model and are not learned from the training set of data.
8. **Application of the Model** - For deployment, the model with the best performance is chosen.
9. **Evaluation and Prediction** - After the model is chosen then it again evaluated using the metrics like accuracy, confusion matrix, and classification report along with credit score to predict whether the credit card is approved or not.

## Models Used

1. Linear Regression
2. Support Vector Machine(SVM)
3. Decision Tree
4. Random Forest
5. AdaBoost
6. XGBoost(Extreme Gradient Boosting)

