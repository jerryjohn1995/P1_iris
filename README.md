# Iris Classification using Logistic Regression with MLflow

This project demonstrates a simple machine learning pipeline using **Logistic Regression** to classify iris flower species based on the classic **Iris dataset**. The experiment is tracked and logged using **MLflow**, an open-source platform for managing the ML lifecycle.

## Project Overview

- Dataset: Iris Dataset (from `sklearn.datasets`)
- Model: Logistic Regression
- ML Lifecycle Tracking: MLflow
- Environment: Python (with Conda)

## Project Structure

- iris_classifier.py # Main script to train and log model
- requirements.txt # Dependencies
- mlruns/ # MLflow experiment logs (auto-generated) (not included)
- README.md # Project documentation

## 🔧 Features

- Preprocessing of the Iris dataset
- Training using Logistic Regression
- Logging:
  - Model parameters
  - Accuracy metrics
  - Model signature
  - Input example
- Model versioning and registration using MLflow
- Load and make predictions from registered models

## 📌 MLflow Features Used

- `mlflow.set_experiment()` – To group runs
- `mlflow.log_params()` – Logs model parameters
- `mlflow.log_metric()` – Logs evaluation metrics
- `mlflow.sklearn.log_model()` – Logs the model
- `mlflow.pyfunc.load_model()` – Loads the model for prediction
- Model Registration

## 🖥️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/P1_iris.git
cd P1_iris
