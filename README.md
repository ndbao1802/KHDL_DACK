# CSC17104 – Programming for Data Science: Final Project

## Group Members:
- 22127152 - Lê Gia Huy
- 22127031 - Nguyễn Duy Bảo
- 22127203 - Võ Ngọc Khoa

## Project Planning
https://docs.google.com/spreadsheets/d/1wOe1QLV6qv9JPPtfo_QqdeWPaUOkSPMe1-wwxWyNneA

## Project Title
**Analyzing Mobile Device Usage and User Behavior**

## Overview
This repository contains the final project for **CSC17104 – Programming for Data Science**, where we perform a comprehensive analysis of the "Mobile Device Usage and User Behavior Dataset" obtained from Kaggle.

The goal of this project is to explore, analyze, and gain insights into mobile device usage patterns and user behaviors. The dataset allows us to examine relationships among key features, ask meaningful questions, and develop data preprocessing and analysis workflows to answer these questions effectively.

## Dataset Description
The **Mobile Device Usage and User Behavior Dataset** provides a detailed examination of smartphone usage patterns. It contains 700 user samples with metrics that offer insights into app usage, screen-on time, battery drain, data consumption, and more.

### Key Features:
- **User ID**: Unique identifier for each user.
- **Device Model**: Model of the user's smartphone.
- **Operating System**: The OS of the device (iOS or Android).
- **App Usage Time**: Daily time spent on mobile applications (in minutes).
- **Screen On Time**: Average hours per day the screen is active.
- **Battery Drain**: Daily battery consumption (in mAh).
- **Number of Apps Installed**: Total apps available on the device.
- **Data Usage**: Daily mobile data consumption (in megabytes).
- **Age**: Age of the user.
- **Gender**: Gender of the user (Male or Female).
- **User Behavior Class**: Categorization of user behavior based on usage patterns (1: Light usage to 5: Extreme usage).

This dataset serves as a foundation for exploring user behavior trends and implementing machine learning models to predict user categories.

## Project Components
The project is structured into the following key stages:

### 1. **Data Collection**
The dataset was sourced from [Kaggle](https://www.kaggle.com/). It was imported and stored in CSV format for easy preprocessing and analysis.

### 2. **Data Exploration and Preprocessing**
- Cleaned and transformed the dataset to handle missing values, normalize data, and ensure consistency.
- Performed exploratory data analysis (EDA) to identify patterns, trends, and correlations among features.
- Visualized key insights using charts and graphs to better understand user behavior.

### 3. **Asking Meaningful Questions**
We formulated the following research questions based on the dataset:
1. What factors influence battery drain the most?
2. How does app usage time vary across different age groups and genders?
3. Is there a significant correlation between the number of apps installed and the daily data usage and battery drain across different operating systems?
4. How does Age influence Battery Drain (mAh/day) and App Usage Time (min/day) across different Operating Systems? Is there a significant difference in these relationships for Android vs. iOS users?
5. How does the number of Apps Installed affect the Data Usage (MB/day)? Is there a non-linear relationship, and how does it differ across Operating Systems?
6. Which age group uses the most mobile data and what does it reflect?

### 5. **References**
- Course Materials: CSC17104 – Programming for Data Science Lecture Notes
- Linear Regression: https://www.geeksforgeeks.org/ml-linear-regression/
- Correlation: https://www.geeksforgeeks.org/what-is-correlation-analysis/
- Slope and Intercept: https://www.w3schools.com/datascience/ds_linear_slope.asp
- Seaborn plots: https://www.geeksforgeeks.org/types-of-seaborn-plots/


## Requirements
The project was implemented in Python using the following libraries:
- **Pandas**: Data manipulation and preprocessing
- **NumPy**: Numerical computations
- **Matplotlib/Seaborn**: Data visualization

## Acknowledgments
- Kaggle for providing the Mobile Device Usage and User Behavior Dataset.