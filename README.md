# CS6220 Data Mining - Homework 1

**Student:** Mihir Mathur  
**Course:** CS6220 Data Mining  
**Assignment:** Homework 1

## Overview

This repository contains my solution for Homework 1. The assignment uses the Iris flower dataset to build and evaluate a Logistic Regression classification model.

The notebook includes:
- Loading and inspecting the Iris dataset
- Data visualization
- Training and test data splitting
- Feature standardization using StandardScaler
- Logistic Regression model training
- Training and testing runtime measurement
- Prediction accuracy evaluation
- Logistic Regression hyperparameter experiments
- Confusion matrix evaluation

## Environment

- Programming Language: Python
- Development Environment: Jupyter Notebook
- Python Distribution/Environment: Anaconda
- Machine Learning Library: scikit-learn
- Additional Libraries: pandas and matplotlib
- Execution Platform: Local Windows laptop

## Dataset

The Iris dataset contains 150 samples from three Iris flower classes:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

Four numerical features are used for classification:

- Sepal length
- Sepal width
- Petal length
- Petal width

## How to Run

1. Install Anaconda with Python and Jupyter Notebook.
2. Ensure the required Python libraries are installed: pandas, matplotlib, and scikit-learn.
3. Download or clone this repository.
4. Open `homework_1.ipynb` in Jupyter Notebook.
5. Make sure the Iris dataset files are in the same directory as the notebook.
6. Run all notebook cells from top to bottom.

## Main Results

Using an 80% training and 20% test split with `random_state=42` and stratified sampling:

- Training samples: 120
- Test samples: 30
- Baseline Logistic Regression test accuracy: 93.33%
- Correct baseline predictions: 28 out of 30
- Hyperparameter experiment: C = 10 and C = 100 achieved 100% test accuracy on this train-test split.

Runtime values are measured directly in the notebook using Python's `time.perf_counter()` and may vary slightly between executions.

## Repository Contents

- `homework_1.ipynb` - Jupyter Notebook containing the implementation, documentation, and executed results.
- `iris.data` - Iris dataset.
- `iris.names` - Iris dataset description and metadata.
- `README.md` - Setup, dependencies, execution instructions, and project overview.