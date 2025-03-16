**Overview**

This repository contains a machine learning pipeline that processes hyperspectral imaging data to predict mycotoxin levels (DON concentration) in corn samples. The project involves data preprocessing, outlier removal, regression modeling, hyperparameter tuning, API deployment, unit testing, and visualization.

**Features**

Data Preprocessing: Cleans and prepares hyperspectral imaging data.

Outlier Removal: Uses an optimal method to remove outliers.

Feature Scaling: Standardizes features for better model performance.

Model Training: Includes Neural Networks, Gradient Boosting, and LightGBM.

Hyperparameter Tuning: Uses Optuna for optimizing model parameters.

Model Evaluation: Implements K-Fold cross-validation and SHAP for interpretability.

API Integration: Deploys the trained model as an API using FastAPI.

Unit Testing: Ensures correctness of core functionalities.

**Installation**
To set up the project, follow these steps:
**STEP 1** run the ML_Model.ipynb file
**STEP 2 ** RUN THE api.ipynb file for fastapi of Ml_Model
