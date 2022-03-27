# Databricks Tutorial

This repository provides a quick overview of machine learning model training on Databricks. To train models, you can use libraries like scikit-learn that are preinstalled on the Databricks Runtime for Machine Learning. In addition, you can use MLflow to track the trained models, and Hyperopt with SparkTrials to scale hyperparameter tuning.

This tutorial covers:
- Part 1: Training a simple classification model with MLflow tracking
- Part 2: Hyperparameter tuning a better performing model with Hyperopt

## Notebook Organization 
The notebook is organized in the following manner:

1. Load the dataset
2. Feature preprocessing
3. Define the model
4. Build the pipeline
5. Evaluate the model
6. Hyperpamrameter tuning
7. Make predictions and evaluate model performance

## Requirements
- Cluster running Databricks Runtime 7.5 ML or above
