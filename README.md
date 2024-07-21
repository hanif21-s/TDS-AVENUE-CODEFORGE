# Titanic Survival Prediction

## Overview

This project aims to predict whether a passenger survived the Titanic disaster using machine learning. The dataset used includes information such as age, gender, ticket class, fare, cabin, and embarked port.

## Dataset

The dataset contains the following columns:

- **PassengerId**: Unique identifier for each passenger
- **Survived**: Whether the passenger survived (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1, 2, or 3)
- **Name**: Name of the passenger
- **Sex**: Gender of the passenger
- **Age**: Age of the passenger
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Ticket fare
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Model

The project utilizes a logistic regression model to predict survival. The data is preprocessed by handling missing values and encoding categorical features. The model is trained on the training set and evaluated on the test set.

## Installation

To run this project locally, you need to have the following packages installed:

- pandas
- numpy
- scikit-learn
- jupyter

You can install these using pip:

```bash
pip install pandas numpy scikit-learn jupyter
