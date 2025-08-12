
---

**`case_studies/01_titanic_survival/README.md`**


# Titanic Survival Prediction Case Study

This folder contains two implementations of the Titanic survival prediction problem using:

- **scikit-learn** (`titanic_survival_scikit.ipynb`)
- **Keras (TensorFlow)** (`titanic_survival_keras.ipynb`)

## Overview

The goal is to build a predictive model to determine whether a passenger survived the Titanic disaster based on various features. This case study demonstrates `Data Preprocessing`, `Exploratory Data Analysis (EDA)`, `Model Building`, and `evaluation techniques`.

## Implementations

- **Scikit-learn:** Uses preprocessing pipelines and a Multi-Layer Perceptron (MLP) classifier.
- **Keras:** Implements a neural network with dense layers trained using SGD or Adam optimizers.

## Dataset

The dataset is located in the `data/` folder (`Titanic-Dataset.csv`). It includes passenger details such as age, sex, ticket class, fare, and survival status.


## Key Highlights

- Data preprocessing including handling missing values, encoding categorical features, and feature scaling.
- Model building with MLP architectures in both scikit-learn and Keras.
- Usage of train-test splits, evaluation metrics like accuracy, classification report, and confusion matrix.
- Early stopping implemented in Keras to prevent overfitting.
- Comparison of classical ML vs deep learning approach on the same problem.

---

