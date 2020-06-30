# Comparison_of_ML_algorithm_for_diabetes_diagnosis

### Overview

Comparison of several ML algorithms for diabetes diagnosis.

- a SVM model with a polynomial kernel
- a SVM model with a radial basis function kernel
- a Gaussian Naive Bayes Model
- a K-Nearest Neighbors model

### Results

The KNN model reaches 74% of accuracy.
The Gaussian Naive Bayes model reaches an accuracy of 78% on the test set.
Both SVM model with a polynomial kernel and with a radial basis function kernel reach 79% of accuracy on the test set.

### Dataset

The Dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases: https://www.kaggle.com/uciml/pima-indians-diabetes-database.
It consists of several medical predictor variables: the number of pregnancies the patient has had, their BMI, insulin level, age, and so on, and one target variable: whether or not the patient has diabetes.

### Dependencies

- pandas
- numpy
- matplotlib
- scikit-learn

### Usage

Run this using jupyter notebook. Just type jupyter notebook in the main directory and the code will pop up in a browser window.
