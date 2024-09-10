# Property Price Prediction with Ridge Regression

This project uses Ridge Regression to predict property prices based on features such as total square feet, number of bathrooms, and number of BHKs. The model is trained on sample data and can be used to estimate property prices given these features.

## Overview

The Ridge Regression model is created using the `Ridge` class from `sklearn.linear_model`. This model is trained on example data with features:

- `total_sqft`: Total square feet of the property
- `bath`: Number of bathrooms
- `bhk`: Number of bedrooms (BHK)

The model predicts the price of a property based on these inputs.

## Requirements

- Python 3.x
- NumPy
- scikit-learn

You can install the necessary packages using pip:

```bash
pip install numpy scikit-learn
