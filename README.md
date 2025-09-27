# House Prices Prediction System

## Overview
This project implements a machine learning model to predict house prices using the California Housing dataset. The system utilizes various regression techniques to provide accurate price predictions based on features such as location, number of rooms, and other housing attributes.

## Dataset
The project uses the California Housing dataset, which contains information about housing districts in California. The dataset includes the following features:

- **MedInc**: Median income in block group
- **HouseAge**: Median house age in block group
- **AveRooms**: Average number of rooms per household
- **AveBedrms**: Average number of bedrooms per household
- **Population**: Block group population
- **AveOccup**: Average number of household members
- **Latitude**: Latitude of the block group
- **Longitude**: Longitude of the block group
- **MedHouseVal**: Median house value for California districts (target variable)

## Requirements
To run this project, you'll need the following Python packages:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

You can install all required packages using:
pip install -r requirements.txt

## Implementation
1. **Data Loading and Exploration**
   - Load the California Housing dataset using scikit-learn
   - Perform exploratory data analysis
   - Visualize feature distributions and correlations

2. **Data Preprocessing**
   - Handle missing values (if any)
   - Feature scaling and normalization
   - Train-test split

3. **Model Training**
   - Train multiple regression models
   - Hyperparameter tuning
   - Model evaluation using cross-validation

4. **Model Evaluation**
   - Performance metrics (MSE, RMSE, R² Score)
   - Residual analysis
   - Feature importance

## How to Run
1. Clone this repository
2. Install the required packages
3. Open and run the Jupyter notebook `House Prices Prediction System.ipynb`
