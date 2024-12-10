# Predicting Flight Price Based on Flight Attributes ✈️💵

This machine learning project predicts flight ticket prices using flight attributes such as airline, destination, class, and departure time. 
By training models on historical data, the project aims to accurately forecast flight prices, helping airlines and customers make informed decisions.

## Overview 📊

The **Predicting Flight Price** project uses machine learning techniques to predict the price of airline tickets based on the following features:

- **Airline**
- **Destination**
- **Class** (Economy, Business, etc.)
- **Departure Time**
- **Flight Number** (optional)
- **Price ($)** (target variable)

The key steps involved in the project include:
1. **Data Preprocessing**: Cleaning and encoding categorical features.
2. **Feature Engineering**: Extracting and preparing features for modeling.
3. **Model Training**: Using regression models to train on the dataset.
4. **Evaluation**: Assessing model performance based on **R² score** and **Mean Squared Error**.

## Project Setup ⚙️

### Requirements 📋

To run the project, you need to install the following dependencies:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`

You can install the required libraries by running:

```bash
pip install -r requirements.txt
