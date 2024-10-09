# Titanic Survival Prediction

## Overview
This project aims to predict the survival of passengers on the Titanic using a machine learning model. By analyzing a dataset containing various features of the passengers (e.g., age, sex, ticket class), the model attempts to classify whether a passenger survived or not.

## Dataset
The dataset used in this project is the famous Titanic dataset, which is publicly available and widely used for classification problems in machine learning. It contains features such as:
- PassengerId
- Pclass (Ticket class)
- Name
- Sex
- Age
- SibSp (Number of siblings or spouses aboard)
- Parch (Number of parents or children aboard)
- Ticket number
- Fare
- Cabin
- Embarked (Port of Embarkation)

## Project Structure
- **data**: This folder contains the Titanic dataset in CSV format.
- **notebooks**: This folder contains the Jupyter notebook used to build the model and evaluate its performance.
- **models**: Saved versions of trained machine learning models.

## Key Features
- **Data Cleaning**: Handling missing values, feature selection, and engineering new features from existing ones.
- **Exploratory Data Analysis (EDA)**: Visualizing relationships between passenger characteristics and survival.
- **Modeling**: Multiple machine learning algorithms such as Logistic Regression, Decision Trees, Random Forests, and others were tested.
- **Model Evaluation**: Accuracy, precision, recall, and F1-score were used to assess the performance of each model.

## Installation 
 Clone the repository:
   ```bash
   git clone https://github.com/yourusername/titanic_survival_prediction.git
   cd titanic_survival_prediction
   ```