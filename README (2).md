# Principles of Machine Learning 🤖

This repository contains my learning materials and lab exercises for ECS7020P Principles of Machine Learning.


## About ECS7020P Principles of Machine Learning ❓

ECS7020P introduces the core ideas behind machine learning and how to apply them in practice. The labs follow the path from representing and manipulating data, through regression and model validation, to building and evaluating classifiers.

For practical implementation, Python and its libraries for scientific computing, data analysis, visualisation and machine learning are used in Jupyter notebooks on Google Colab.


## Environment 👩🏻‍💻

<p align="center">
  <img src="https://img.shields.io/badge/jupyter-F37626?style=flat&logo=jupyter&logoColor=white" alt="Jupyter"/>
  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=flat&logo=googlecolab&logoColor=white" alt="Google Colab"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub"/>
</p>


## Stack 🛠️

<p align="center">
  <img src="https://img.shields.io/badge/python-3776AB?style=flat&logo=python&logoColor=white" alt="Python"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/numpy-013243?style=flat&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white" alt="pandas"/>
  <img src="https://img.shields.io/badge/matplotlib-11557C?style=flat" alt="matplotlib"/>
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white" alt="SciPy"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
</p>


## Overview of Lab Materials 🔬

### Lab 1
**Introduction to the Python environment**
- Running code cells and writing markdown cells
- Creating variables and printing values
- Uploading data files to Google Colab
- Importing libraries
- Loading a CSV file into a Pandas DataFrame
- Plotting a simple dataset (body mass vs heart rate of animal species)

### Lab 2
**Representing data in Python**
- Basic data types: integers, floats, booleans and strings
- Sequence types: lists and lists of lists, indexing and slicing
- NumPy arrays: creating, indexing, slicing, and saving/loading `.npy` files
- Representing a dataset as a 3-tensor (handwritten digits, MNIST-style) and plotting it with Matplotlib
- Pandas Series and DataFrames: custom indices, `loc`, `iloc` and `iat`

### Lab 3
**Operations on NumPy arrays**
- Making predictions with a polynomial model
- Vectorised arithmetic operations (elementwise)
- Row and column vectors, transposition and column stacking
- Building a design matrix and using matrix multiplication (`np.dot`) for predictions
- Least squares solution with the normal equation
- Fitting linear, quadratic, cubic and degree-4 polynomial models

### Lab 4
**Overfitting, validation and regularisation in regression**
- Least squares fit with `polyfit` and `poly1d`
- Mean squared error (MSE) as a quality metric
- Model complexity and training MSE (polynomials of increasing degree)
- Overfitting vs underfitting using a validation dataset
- Training MSE vs validation MSE curves
- Regularisation (ridge-style least squares) and the effect of lambda
- Challenge: repeated random train/validation splits

### Lab 5
**Exploring classification**
- Linear classifiers, decision boundaries and decision regions
- Design matrices and predicting labels
- The logistic function as a measure of classifier certainty
- Likelihood and negative log-likelihood
- Accuracy and error rate
- Comparing classifiers on a training dataset
- Logistic regression optimisation: exhaustive search and gradient descent (`scipy.optimize`)
- Visualising the error surface

### Lab 6
**Exploring classification II**
- The Iris dataset: predictors, labels and train/validation split
- k-Nearest Neighbours (kNN) and the effect of the hyperparameter k
- Logistic regression with scikit-learn for multi-class problems
- Confusion matrices for class-aware evaluation
- Imbalanced datasets and how decision boundaries change
- Bayes rule, priors and Naive Bayes classifiers


## Repository Structure 🌲

```
.
├── README.md
├── W1 - Lab1
│   └── Lab_1.ipynb
├── W2 - Lab2
│   └── Lab_2.ipynb
├── W3 - Lab3
│   └── Lab_3.ipynb
├── W4 - Lab4
│   └── Lab04.ipynb
├── W5 - Lab5
│   └── Lab_5.ipynb
└── W6 - Lab6
    └── ECS7020P_Lab06.ipynb
```


## Reflection 🪞

Across these labs I built up the foundations of machine learning step by step. I started with data representation in Python using NumPy and Pandas, then used array operations to implement least squares regression from scratch. Exploring overfitting, validation and regularisation showed me why a model that fits the training data perfectly can still predict poorly on new data.

In the classification labs I moved from linear classifiers and the logistic function to optimising logistic regression with gradient descent, and then compared kNN, logistic regression and Naive Bayes on the Iris dataset. Working with confusion matrices and imbalanced datasets taught me that accuracy alone can be misleading, and that the right evaluation metric depends on the population a model will be used on.

Looking ahead, I want to apply these ideas to larger, real-world datasets and explore more advanced models and evaluation techniques.
