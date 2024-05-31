# Hourly Energy Consumption Prediction

This project focuses on predicting hourly energy consumption using time series forecasting techniques. The dataset used for this project contains hourly energy consumption data and spans multiple years.

## Overview

The project utilizes XGBoost, a popular gradient boosting library, to develop a regression model for predicting energy consumption. It involves the following steps:

1. **Data Exploration:** The initial step involves loading and visualizing the hourly energy consumption data to gain insights into patterns and trends.
2. **Train/Test Split:** The dataset is split into training and testing sets to evaluate the performance of the predictive model.
3. **Feature Engineering:** Time series features such as hour of the day, day of the week, month, etc., are created to enhance the predictive power of the model.
4. **Model Training:** XGBoost regressor is trained on the training data using the engineered features.
5. **Model Evaluation:** The trained model is evaluated on the testing set using root mean squared error (RMSE) as the evaluation metric.
6. **Prediction Visualization:** Predictions made by the model are visualized alongside the actual energy consumption data to assess model performance.

## Repository Structure

- `data/`: Contains the dataset used for training and testing.
- `notebooks/`: Jupyter notebooks for data exploration, feature engineering, model training, and evaluation.
- `scripts/`: Python scripts for data preprocessing, feature engineering, and model training.
- `models/`: Saved trained models for future use.
- `results/`: Visualizations and evaluation metrics generated during model evaluation.
- `README.md`: Overview of the project, instructions, and documentation.
- `requirements.txt`: Dependencies required to run the project.

## Setup Instructions

1. **Clone the repository:** `git clone <repository_url>`
2. **Install dependencies:** `pip install -r requirements.txt`
3. **Run the notebooks/scripts:** Explore the data, train the model, and evaluate predictions.

## Usage

- `notebooks/`: Open Jupyter notebooks to interactively explore the data and execute code cells.
- `scripts/`: Execute Python scripts from the command line to preprocess data, train models, or make predictions.

## Contributors

- [Ankur Shah](https://www.linkedin.com/in/ankurshah02/)

## Acknowledgements

We would like to express our gratitude to Rob Mulla for providing access to the dataset and resources necessary for this project.
