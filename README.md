# Machine Learning Project

This repository contains a machine learning exercise using the Titanic dataset. The goal is to predict passenger survival using various attributes provided in the dataset.

## Contents

- `Assignment2_supervised_learning_flow.ipynb` – Jupyter Notebook implementing the model training workflow.
- `titanic_train.csv` and `titanic_test.csv` – training and test data.
- `taitanic_description.txt` – short description of each column.
- `assignment2_ml_flow_instructions.pdf` – original assignment description.

## Running the Notebook

Make sure you have Python along with `pandas`, `numpy`, `matplotlib` and `scikit-learn` installed. Launch Jupyter and open the notebook:

```bash
jupyter notebook Assignment2_supervised_learning_flow.ipynb
```

Execute the cells sequentially to preprocess the data, train a logistic regression model and evaluate it with cross‑validation.

## Dataset Overview

The data represents Titanic passengers. Features include passenger class (`Pclass`), gender (`Sex`), age, number of siblings/spouses (`SibSp`), number of parents/children (`Parch`), fare and embarkation port (`Embarked`). The target variable `Survived` is 1 if the passenger lived and 0 otherwise. See `taitanic_description.txt` for the full feature list.
