# Disease Prediction Using ML

This project aims to predict diseases based on symptoms using machine learning models. Three classifiers (Support Vector Machine, Naive Bayes, and Random Forest) are trained on a dataset, and predictions are made by taking the mode of the predictions from all three models.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models](#models)
- [Results](#results)
- [Dependencies](#dependencies)

## Introduction

This project predicts diseases based on a given set of symptoms. The main goal is to develop an ensemble model that combines the predictions of three different classifiers to improve the accuracy of disease prediction.

## Dataset

The dataset used for this project consists of training and testing data with various symptoms and their corresponding diseases. The data is assumed to be in CSV format with symptom columns and a target disease column.

## Models

Three machine learning models are used in this project:
1. **Support Vector Machine (SVC)**
2. **Naive Bayes (GaussianNB)**
3. **Random Forest Classifier**

The final prediction is made by taking the mode of the predictions from these three models.

## Results

The ensemble model achieves a certain level of accuracy on the test dataset. The confusion matrix provides a detailed view of the model's performance across different classes.

## Dependencies

- Pyhton 3.x
- NumPy
- pandas
- scikit-learn
- seaborn
- matplotlib