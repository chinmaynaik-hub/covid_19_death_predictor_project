# COVID-19 Death Prediction Project

## Project Overview
This project aims to predict the number of deaths from COVID-19 based on country-wise dataset statistics. It utilizes various regression models to find the most accurate prediction method.

## Prerequisites
- Dataset: Country-wise COVID-19 dataset from Kaggle
- Programming Language: Python
- Task Type: Regression

## Features Used for Prediction
- Confirmed Cases
- Recovered Cases
- Active Cases
- New Cases
- New Deaths
- New Recovered

## Models Implemented
1. Linear Regression
2. K-Nearest Neighbors (KNN) Regressor
3. Decision Tree Regressor

## Results and Conclusion
- Linear Regression: Achieved the highest accuracy with an R2 score of 1.0 on the test set.
- KNN Regressor: Produced a significantly lower R2 score (approximately 0.37).
- Decision Tree Regressor: Resulted in an inaccurate/negative R2 score for this specific dataset split.

Conclusion: Linear Regression is the most suitable model for predicting deaths in this dataset.

## How to Use
1. The project includes a Gradio interface. Users can input the required statistics into the web UI to get an immediate prediction of the potential death count based on the Linear Regression model.

2. Download and run notebook locally
   - Download the file from GitHub GUI or pull using git command
   - Download the [Covid 19 dataset](https://www.kaggle.com/datasets/imdevskp/corona-virus-report) in your PC.
   - upload the notebook in Jupyter notebook or Google colab and paste the path of the dataset correctly
   - use Run all button to run all project
   - the Gradio frontend link will be generated
   - predict the death by inserting new values
---
### Creator : Chinmay Naik
