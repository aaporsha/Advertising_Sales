# Advertising_Sales

## Overview
A Python machine learning application that predicts sales based on advertising spend across different media channels (TV, Radio, and Newspaper).

## Project Description
This application uses linear regression to analyze the relationship between advertising budgets and sales. It reads data from a CSV file, trains a predictive model, evaluates its performance, and visualizes the results.

## Project Structure
- `main.py` - Main application with ML model implementation
- `Advertising.csv` - Dataset containing advertising spend and sales data
- `pyproject.toml` - Project dependencies configuration
- `.gitignore` - Python-specific ignore patterns

## Features Implemented
- **Data Loading**: Reads advertising data from CSV file
- **Data Exploration**: Displays dataset statistics and information
- **Model Training**: Linear regression model using scikit-learn
- **Train/Test Split**: 80/20 split for model validation
- **Model Evaluation**: 
  - Mean Squared Error (MSE) calculation
  - R-squared score for model performance
- **Visualization**: Scatter plot showing actual vs predicted sales

## Dependencies
- Python 3.11
- matplotlib 3.9.3 - For data visualization
- numpy 2.1.3 - For numerical operations
- pandas 2.2.3 - For data manipulation
- scikit-learn 1.5.2 - For machine learning algorithms

## Running the Application
Execute `python main.py` to:
1. Load and analyze the advertising dataset
2. Train the linear regression model
3. Evaluate model performance
4. Display visualization of predictions

## Model Details
- **Input Features**: TV, Radio, and Newspaper advertising budgets
- **Target Variable**: Sales
- **Algorithm**: Linear Regression
- **Test Size**: 20% of data
- **Random State**: 42 (for reproducibility)

## Last Updated
October 09, 2025
