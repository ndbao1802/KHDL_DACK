# CSC17104 – Programming for Data Science: Final Project

## Group Members:
- 22127152 - Lê Gia Huy
- 22127031 - Nguyễn Duy Bảo
- 22127203 - Võ Ngọc Khoa

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
1. What is the relationship between screen-on time and app usage time across different user behavior classes?
2. How does battery drain vary with the number of apps installed?
3. Can we predict a user's behavior class based on key features like app usage time, screen-on time, and data usage?
4. Are there notable differences in usage patterns between iOS and Android users?
5. Does gender or age significantly influence user behavior categories?

### 4. **Analysis and Model Building**
- Applied statistical analysis to answer questions and validate hypotheses.
- Implemented machine learning models (e.g., Decision Trees, Random Forests, and Logistic Regression) to predict user behavior classes.
- Evaluated model performance using metrics like accuracy, precision, recall, and F1-score.

### 5. **Reflection**
- Summarized key findings and insights.
- Discussed the strengths and limitations of the dataset and analysis methods.
- Highlighted potential applications of this work in designing user-centric mobile applications.

### 6. **References**
- Kaggle Dataset: [Mobile Device Usage and User Behavior Dataset](https://www.kaggle.com/)
- Course Materials: CSC17104 – Programming for Data Science Lecture Notes

## Repository Structure
|-- data/
|-- mobile_device_usage.csv # Dataset file
|-- notebooks/
|-- data_exploration.ipynb # Jupyter Notebook for data exploration and preprocessing
|-- analysis.ipynb # Notebook for answering questions and model building
|-- results/
|-- visualizations/ # Charts and graphs generated during analysis
|-- models/ # Saved machine learning models
|-- README.md # Project description and details

## Requirements
The project was implemented in Python using the following libraries:
- **Pandas**: Data manipulation and preprocessing
- **NumPy**: Numerical computations
- **Matplotlib/Seaborn**: Data visualization
- **Scikit-learn**: Machine learning model development

## Usage
- Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your_username/mobile-usage-analysis.git

## Acknowledgments
- Kaggle for providing the Mobile Device Usage and User Behavior Dataset.