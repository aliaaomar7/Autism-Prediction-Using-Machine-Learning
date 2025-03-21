# Autism-Prediction-Using-Machine-Learning
## This project focuses on predicting autism using machine learning techniques. The key steps include:

## Dataset:
### Sourced from https://www.kaggle.com/datasets/shivamshinde123/autismprediction, the dataset includes demographic and behavioral data essential for autism prediction.

## Data Preprocessing:
### Data cleaning, label encoding for categorical variables, and converting the age column to integer format. SMOTE is applied to handle data imbalance.

## Model Training:
### Multiple classifiers (Decision Tree, Random Forest, and XGBoost) are trained. Hyperparameter tuning is done using RandomizedSearchCV and cross-validation to optimize performance.

## Evaluation & Deployment:
### Models are evaluated using accuracy, confusion matrix, and classification reports. The best-performing model is serialized using pickle for later deployment.

## Project Structure & Usage:
### The repository includes a code with the full pipeline, the dataset in CSV format, and a requirements file for dependencies.
