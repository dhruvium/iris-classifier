# Iris-classifier

A beginner-friendly machine learning project that classifies Iris flowers into one of three species — **Setosa**, **Versicolor**, or **Virginica** — using sepal and petal measurements.

## Overview

This project demonstrates a simple supervised machine learning workflow using the classic Iris dataset. The goal is to train a classification model that predicts the flower species from four numeric features.

## Problem Statement

Given the following measurements:

- Sepal length
- Sepal width
- Petal length
- Petal width

the model predicts which Iris species the sample belongs to.

## Dataset

The project uses the Iris dataset, which contains:

- 150 total samples
- 3 flower species:
  - Iris setosa
  - Iris versicolor
  - Iris virginica
- 4 input features:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width

## Features

- Predicts Iris flower species from four numeric measurements
- Beginner-friendly machine learning workflow
- Easy to understand and extend
- Useful for learning classification concepts

## Tech Stack

- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib / Seaborn

## Project Workflow

1. Load the dataset
2. Explore and clean the data
3. Split the data into training and testing sets
4. Train a classification model
5. Evaluate the model
6. Predict the species of new flower samples


## Installation

```bash
git clone https://github.com/dhruvium/iris-classifier.git
cd iris-classifier
pip install -r requirements.txt
```

The trained model should return one of the following labels:

- Setosa
- Versicolor
- Virginica

## Evaluation

The model can be evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

## Why This Project Matters

This project is a strong beginner machine learning project because it teaches the basics of classification without being too complex. It covers data loading, preprocessing, training, evaluation, and prediction in a simple and practical way.
