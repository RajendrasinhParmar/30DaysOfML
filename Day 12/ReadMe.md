---
Title: Day 12 of 30 Day Of ML Code Event
Author: Rajendrasinh Parmar
Date: August 14, 2021
---

# Day 12 of 30 Days Of ML Code

## Intermediate Machine Learning Lesson 1

### Introduction

This is a lesson to provide overview about the course.

Follow the notebook [Introduction](./introduction.ipynb) for lesson details.

As part of the exercise for the first lesson we've created 5 Random Forest Regressor models using different values for parameters.

We changes values for `n_estimators`, `criterion`, `min_samples_split`, `max_depth`. 

After that we evaluated all the models and found the best model that have minimum value of MAE(Mean Absolute Error).

#### Exercise

As a part of the exercise for the first lesson we have predicted the values of house prices using the best model we decided from the 5 models defined in previous steps.
Data used for the exercise is available under the folder [home-data-for-ml-course](./home-data-for-ml-course)

The associated exercise with the first lesson of the course is provided in [Exercise: Introduction](./exercise-introduction.ipynb)

Submission for the exercise is available in [submission_introduction.csv](./home-data-for-ml-course/submission.csv)

### Missing Values

In this tutorial, you will learn three approaches to dealing with missing values. Then you'll compare the effectiveness of these approaches on a real-world dataset.

There are three approach to handle missing values
1. Drop columns with missing values
2. Imputation
3. An Extension to Imputation

Follow the notebook [Missing Values](./missing-values.ipynb) for lesson details.

#### Exercise

As a part of the exercise for the second lesson I used different approaches to handle missing values.
Then for the final exercise I've used `An Extension to Imputation` approach to train my model and predict the values.

The associated exercise with the second lesson of the course is provided in [Exercise: Missing Values](./exercise-missing-values.ipynb)

Submission for the exercise is available in [submission_missing_values.csv](./home-data-for-ml-course/submission_missing_values.csv)