# Email Spam Classification

This project involves building a machine learning model to classify emails as either spam or non-spam. The dataset used for this project was imported from Kaggle. The project encompasses data cleaning, exploratory data analysis (EDA), model training with various algorithms, and creating a graphical user interface (GUI) for classification using Tkinter.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Data Cleaning and EDA](#data-cleaning-and-eda)
- [Model Training](#model-training)
- [Best Model Selection](#best-model-selection)
- [GUI Application](#gui-application)

## Introduction
Email spam classification is a crucial task to ensure that unwanted and potentially harmful emails are filtered out. In this project, we explore various machine learning algorithms to build an effective spam filter. The project culminates in a user-friendly GUI application where users can input email text and get a classification result.

## Dataset
The dataset used for this project was sourced from [Kaggle](https://www.kaggle.com/). It contains labeled email data, with labels indicating whether an email is spam or non-spam.

## Installation
To run this project, you need to have Python installed along with the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tkinter

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib tkinter
```

## Data Cleaning and EDA
Data cleaning involves removing any irrelevant or missing data, and processing the text to make it suitable for analysis. Exploratory Data Analysis (EDA) helps in understanding the distribution of data and identifying key patterns and trends.

Key steps include:

Removing duplicates and null values
Text preprocessing: tokenization, stop words removal, stemming/lemmatization
Visualization of word frequencies and other relevant statistics

## Model Training
We experimented with several machine learning models to find the best one for this classification task:

Linear Regression
Logistic Regression
Decision Tree
Random Forest
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Each model was trained and evaluated based on its accuracy.

## Best Model Selection
After evaluating all models, we found that the Support Vector Machine (SVM) provided the highest accuracy. Therefore, we selected SVM as our final model for the email spam classification task.

## GUI Application
To make the classification tool user-friendly, we created a GUI using Tkinter. The GUI allows users to input the text of an email and receive a classification result indicating whether the email is spam or non-spam.

## Screenshot of the GUI 

![enail spam classification tkinter](https://github.com/prateek7204/Email-Spam-Classification-/assets/144140803/03340e80-f3b7-4a4d-a240-4e30157f6bd4)
