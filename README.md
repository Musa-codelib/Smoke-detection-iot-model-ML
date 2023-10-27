# Exploring Machine Learning Techniques for Smoke Detection in IoT Environments

The rapid growth of Internet of Things (IoT) devices has ushered in a new era of environmental interaction and data acquisition. This repository hosts research and code related to the exploration of machine learning techniques for improving smoke detection in IoT environments, a critical aspect of safety and security.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Machine Learning Models](#machine-learning-models)
- [Summary](#summary)

## Introduction

In this project, we embark on a comprehensive study of the application of machine learning methods to enhance smoke detection in IoT settings. The study focuses on analyzing a dedicated dataset, "Smoke detection iot.csv," designed for investigating smoke and fire incident detection in IoT environments.

## Dataset

In the initial stages of the project, a thorough exploration of the dataset's nature is conducted. This exploration provides human insights into the dataset's properties, which serve as the foundation for making informed decisions regarding subsequent machine learning techniques. The dataset includes various features such as temperature, humidity, TVOC (Total Volatile Organic Compounds), eCO2 (CO2 Equivalent Concentration), and various particulate matter concentrations. These factors are analyzed for their potential impact on smoke detection in IoT environments.

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) techniques are employed to gain a preliminary understanding of the dataset's structure and contents. Feature selection is undertaken to ensure the dataset includes only relevant variables, enhancing the accuracy and efficiency of subsequent analyses. A correlation heatmap is generated to visualize relationships and dependencies between features, aiding in the identification of patterns and associations.

## Machine Learning Models

The primary focus of this project is the evaluation of a Decision Tree Classifier for predicting 'FireAlarm' values. The classifier's performance is assessed using a confusion matrix, accuracy, F1 Score, recall, precision, and a Receiver Operating Characteristic (ROC) curve. These evaluations provide insights into the model's ability to distinguish between true and false alarms.

In addition to the Decision Tree Classifier, the project evaluates several other machine learning models, including Logistic Regression, Random Forest, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), Naive Bayes, and Multi-layer Perceptron (MLP). Each model is trained, evaluated, and compared using a common set of metrics, enabling a comprehensive assessment of their suitability for predicting 'FireAlarm' values.

Furthermore, a diverse selection of classification models is explored, including GradientBoostingClassifier, AdaBoostClassifier, Ridge Classifier, SGDClassifier, LinearDiscriminantAnalysis, QuadraticDiscriminantAnalysis, BaggingClassifier, ExtraTreesClassifier, HistGradientBoostingClassifier, GaussianProcessClassifier, and MLPClassifier. This extensive range of models encompasses various classification methodologies, offering a comprehensive performance evaluation and aiding in the identification of the most suitable approach for smoke detection in IoT environments.

## Summary

In summary, this project delves into the realm of machine learning and IoT to enhance smoke detection. It provides a comprehensive study of dataset features, the evaluation of multiple classification models, and insights into the intricate dynamics of smoke detection in IoT environments.

---

Feel free to explore the code and findings in this repository to gain a deeper understanding of the project conducted in the domain of smoke detection in IoT environments using machine learning techniques.
