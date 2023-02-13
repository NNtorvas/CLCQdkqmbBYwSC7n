# Happy Customers Project

## Background:

We are one of the fastest growing startups in the logistics and delivery domain. We work with several partners and make on-demand delivery to our customers. During the COVID-19 pandemic, we are facing several different challenges and everyday we are trying to address these challenges.

We thrive on making our customers happy. As a growing startup, with a global expansion strategy we know that we need to make our customers happy and the only way to do that is to measure how happy each customer is. If we can predict what makes our customers happy or unhappy, we can then take necessary actions.

Getting feedback from customers is not easy either, but we do our best to get constant feedback from our customers. This is a crucial function to improve our operations across all levels.

We recently did a survey to a select customer cohort. You are presented with a subset of this data. We will be using the remaining data as a private test set.

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
