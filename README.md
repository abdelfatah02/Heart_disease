#  Heart Disease Prediction Project
This repository contains a complete machine learning pipeline for predicting heart disease based on clinical features, using the UCI Heart Disease dataset. The project is structured into modular notebooks that handle data preparation, dimensionality reduction, feature selection, model training, evaluation, and optimization.

Project Structure
data/: Contains the raw dataset (heart_disease.csv)

notebooks/: Step-by-step implementation of the pipeline

01_data_preprocessing.ipynb

02_pca_analysis.ipynb

03_feature_selection.ipynb

04_supervised_learning.ipynb

05_unsupervised_learning.ipynb

06_hyperparameter_tuning.ipynb

models/: Stores the final trained model (final_model.pkl)

Pipeline Overview
Preprocessing: Handling missing values, encoding categorical features, and feature scaling.

PCA Analysis: Reducing dimensionality to improve model performance and visual clarity.

Feature Selection: Identifying the most relevant features using multiple methods.

Supervised Learning: Training classifiers such as Logistic Regression and Random Forest.

Unsupervised Learning: Exploring data structure using clustering techniques.

Hyperparameter Tuning: Optimizing models using GridSearchCV and RandomizedSearchCV.

Model Export: Saving the best-performing model for deployment.

## Final Output
The final model is saved in models/final_model.pkl and can be reused for real-time prediction or deployed in a production environment.
