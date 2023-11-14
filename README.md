# Environmental Impact Calculator

## Overview

The Environmental Impact Calculator is a project designed to assess the Air Quality Index (AQI), Water Quality Index (WQI), and Soil Quality Index (SQI) by considering crucial factors affecting air, water, and soil quality. The project merges datasets from government sources and Kaggle to create a comprehensive dataset for a holistic environmental impact assessment.

## Features

- Calculation of AQI, WQI, and SQI based on essential environmental factors.
- Implementation of an Artificial Neural Network (ANN) model.
- Application of Machine Learning regression models:
  - Decision Tree Regressor
  - Random Forest Regressor
  - L1 (Lasso) Regressor
  - L2 (Ridge) Regressor
  - Gradient Boosting Regressor
- Comparative analysis of regression models based on Mean Squared Error (MSE) with the actual AQI, WQI, SQI.

## Data Sources

The project employs a comprehensive dataset derived from a merger of government-provided data and Kaggle datasets. This combined dataset ensures a holistic and detailed approach to environmental impact assessment.

## Machine Learning Models

The project leverages various regression models for predicting AQI, WQI, and SQI. Models are evaluated based on their Mean Squared Error (MSE) with the actual environmental quality indices. The models include:

- Artificial Neural Network (ANN)
- Decision Tree Regressor
- Random Forest Regressor
- L1 (Lasso) Regressor
- L2 (Ridge) Regressor
- Gradient Boosting Regressor

## Comparative Analysis

The performance of each regression model is evaluated through Mean Squared Error (MSE) analysis, providing insights into the predictive accuracy of the models. This metric quantifies the average squared difference between predicted and actual values, offering a robust measure of model performance.

## Visualization

Visualizations are employed to enhance the interpretability of results, including:

- Graphical representation of actual vs. predicted environmental quality indices.
- Comparative analysis charts illustrating MSE for each regression model.
- Visualizations highlighting key features impacting AQI, WQI, and SQI.


## Results

The project's results provide valuable insights into the environmental impact based on the selected factors. Users can refer to the visualizations and regression model analyses to understand the predicted indices and the models' performance.

## License

This project is licensed under the MIT License
