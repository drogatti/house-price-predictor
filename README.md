# House Price Prediction Project
Project Overview
This project focuses on predicting house prices using data from a variety of features such as property characteristics, neighborhood information, and other influential factors. The goal was to develop a model with improved accuracy over baseline predictions by applying advanced regression techniques and blending models. The project includes extensive data preprocessing, feature engineering, and model evaluation to provide reliable predictions for house prices.

Problem Statement

To develop a predictive model that accurately estimates house prices based on a range of input features. The project aims to achieve an RMSE improvement of at least 5% compared to baseline models by leveraging a blended approach.

Repository Structure

- Notebooks/: Contains Jupyter notebooks used for data preprocessing, model training, and evaluation.
   - 02_data_wrangling: Notebook for data cleaning.
   - 03_exploratory_data_analysis: Notebook for feature engineering.
   - 04_preprocessing_and_training.ipynb: Notebook for preprocessing steps.
   - 05_modeling.ipynb: Notebook for training and evaluating multiple models, including Ridge Regression, Random Forest, and the blended model.
- data/: Folder for processed datasets (e.g. cleaned_train.csv).
- models/: Contains serialized model files.
   - ridge_model.pkl: Saved Ridge Regression model.
   - blended_model.pkl: Blended model combining Ridge and Random Forest predictions.
- images/: Contains evaluation metrics and visualizations generated during the project.
   - visualizations/: Key plots and graphs used in the analysis and final report.
- raw_data/: Folder for raw dataset (train.csv).
- reports/: Contains final report and slide deck for project documentation.
   - Capstone_Final_Report: Final project report.
   - Capstone_Presentation: Project slide deck (pptx and pdf formats).
- README.md: Project overview and instructions (this file).
