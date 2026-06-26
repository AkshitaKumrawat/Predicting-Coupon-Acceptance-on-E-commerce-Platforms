# Predicting-Coupon-Acceptance-on-E-commerce-Platforms
In this project, I built an end-to-end Machine Learning pipeline to predict whether a customer will accept a coupon based on demographic information, driving conditions, customer behavior, and coupon attributes.

# 🎯 Coupon Acceptance Prediction Using Machine Learning

## Overview

Coupon-based promotions are widely used to increase customer engagement, but not every customer responds to these offers. This project focuses on predicting whether a customer is likely to accept a coupon using demographic details, customer behavior, and trip-related information. The objective is to help businesses improve marketing effectiveness by targeting the right audience.

---

## Dataset Summary

* **Records:** 12,684
* **Features:** 25
* **Prediction Target:** Coupon Acceptance (Yes/No)

The dataset includes customer demographics, travel information, coupon details, weather conditions, destination, income, occupation, and previous visit frequencies to places like restaurants, bars, and coffee houses.

---

## Data Preparation

To improve model performance, the dataset was carefully prepared through:

* Handling missing values using appropriate statistical techniques
* Detecting and treating outliers with the IQR method
* Encoding categorical variables
* Standardizing numerical features with StandardScaler
* Data validation and preprocessing

---

## Exploratory Data Analysis

The analysis included:

* Distribution of customer attributes
* Correlation analysis
* Feature relationship visualization
* Customer behavior exploration
* Feature importance evaluation

These analyses helped identify important patterns before model development.

---

## Machine Learning Models

Several classification algorithms were trained and evaluated, including:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost
* Gradient Boosting
* AdaBoost
* Support Vector Machine
* K-Nearest Neighbors
* Ridge Classifier
* Gaussian Naive Bayes
* Bernoulli Naive Bayes
* Perceptron

Model evaluation was performed using **10-fold Cross Validation** to ensure reliable performance.

---

## Results

Among all the models tested, **XGBoost** delivered the best performance with an accuracy of **74.25%**, followed by **Random Forest** with **72.95%**.

---

## Key Business Insights

* Coupon category is the strongest factor influencing customer decisions.
* Occupation and income significantly affect coupon acceptance.
* Customer lifestyle indicators such as restaurant, coffee house, and bar visits also contribute to prediction.
* Individual variables show weak linear relationships, making ensemble learning algorithms more suitable for this problem.
