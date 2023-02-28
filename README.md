# Happy Customers Project

## Background:

This project is about creating a model that predicts if a customer is happy or unhappy with the companies and its services.

## Summary of the Project:

### Process:
Our Analysis was conducted following these steps:

1) Import Libraries and Load Data
2) Data preprocessing
3) EDA and Visualization of each feature to understand our features and dataset
4) Create a base model using LazyPredict library to test multiple models
5) Select the model with the best accuracy to move forward
6) Feature Selection
7) Train Final model
8) SHAP analysis on our final model

### Insights:
* In the data we saw no missing or null values. The range of values for each feature was correct. The dataset was quite balanced.

* The 'delivered on time' and 'app makes ordering easy' are the most advantages services of the company with high rating (>3) and the company should focus on them to continue to do well and also,
try to improve all the other features we saw in the survey in order to get better with outmost focus the 'contents as expected' which was the lowest rated (<3) feature of the survey.

### Conclusion:
* The best performed model was RandomForest with 62% accuracy at first and 81% accuracy as our final model after hyperpatameter tuning and feature selection.
