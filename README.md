# Logistic Regression for MAGIC Gamma Telescope

This project applies **logistic regression** to classify events recorded by the MAGIC Gamma Telescope as gamma rays or hadrons. The workflow includes data preprocessing, feature scaling, polynomial feature generation, hyperparameter tuning, model evaluation, and visualization.

## Features

- Cleans and preprocesses MAGIC dataset
- Scales features and generates polynomial/interactions
- Grid search for best hyperparameters (C, solver, class weights)
- Model evaluation with accuracy, confusion matrix, and classification report
- Feature importance ranking and visualizations

## Usage

1. Place `MAGIC Gamma Telescope.csv` in the project directory.
2. Run the provided Python script or notebook.
3. Review output accuracy, confusion matrix, and feature importance plots.

## Requirements

- pandas
- scikit-learn
- numpy
- matplotlib
- seaborn

## Reference

Data: [UCI ML Repository: MAGIC Gamma Telescope Data Set](https://archive.ics.uci.edu/ml/datasets/magic+gamma+telescope)
