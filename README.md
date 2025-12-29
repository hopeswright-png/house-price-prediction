# House Price Prediction

Machine learning project predicting house prices using regression models on the Ames Housing dataset.

## Overview
Built and compared Linear Regression and Random Forest models to predict house sale prices. The Random Forest model achieved 89% accuracy (R² = 0.89) with an average prediction error of $29,037.

## Key Results
- **Best Model**: Random Forest (R² = 0.89, RMSE = $29,037)
- **Top Predictor**: Overall Quality (58% feature importance)
- **Improvement**: 9 percentage point gain over Linear Regression baseline

## Dataset
Ames Housing Dataset: 1,460 houses with 79+ features including quality ratings, square footage, garage capacity, and more.

## Technologies
Python • pandas • scikit-learn • matplotlib • seaborn • Google Colab

## Files
- `house_price_prediction.ipynb` - Complete analysis and modeling notebook
- `train.csv` - Ames Housing dataset

## How to Run
1. Open the notebook in Google Colab
2. Upload the `train.csv` file
3. Run all cells
