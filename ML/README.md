# Rice Variety Classifier

## Overview
This project aims to classify rice varieties into two classes: Cammeo and Osmancik, based on various features. The classification is done using several machine learning algorithms and techniques.

## Dataset
The dataset used in this project is stored in an Excel file named `Rice_Cammeo_Osmancik.xlsx`. It contains information about different rice samples including their features and corresponding classes.

## Requirements
- Python 3.x
- Pandas
- NumPy
- scikit-learn
- Matplotlib

## Usage

1. The script will read the dataset, preprocess it, split it into training and testing sets, and then train several classifiers including K-Nearest Neighbors, Support Vector Machine, Naive Bayes, Decision Tree, Random Forest, and AdaBoost.
2. Finally, it will print the accuracies of each classifier on the test set and perform hyperparameter tuning using GridSearchCV for the K-Nearest Neighbors classifier.
3. The best model found by GridSearchCV will be evaluated on the test set, and its accuracy will be printed.



