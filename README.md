# SCT_ML_1
This repository contains a straightforward implementation of a linear regression model for predicting house prices. The model takes into account three key features: the square footage of the house, the number of bedrooms, and the number of bathrooms.

# House Price Prediction with Linear Regression

This project implements a linear regression model to predict house prices based on square footage, number of bedrooms, and number of bathrooms.

## Dataset

The dataset used for this project contains information about various features of houses and their corresponding sale prices. It includes features like:
- GrLivArea: Above grade (ground) living area square feet
- BedroomAbvGr: Number of bedrooms above grade (does NOT include basement bedrooms)
- FullBath: Number of full bathrooms above grade
- SalePrice: Sale price of the house in dollars

## Files

- `train.csv`: Training dataset containing features and target variables.
- `test.csv`: Testing dataset used for making predictions.
- `sample_submission.csv`: Sample submission file with the format required for submission.

## Dependencies

- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your/repository.git
   cd repository
