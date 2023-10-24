Here is a README.md for your Tehran house price prediction project:

# Tehran House Price Prediction

This project aims to predict house prices in Tehran based on features like area, number of rooms, parking, etc.

## Data

The data is loaded from `housePrice.csv`. It contains the following columns:

- Area - Total area of the house in sqft
- Rooms - Number of bedrooms
- Parking - Boolean indicating if parking spot is available
- Warehouse - Boolean indicating if storage warehouse is available  
- Elevator - Boolean indicating if elevator is present
- Address - General location in Tehran
- Price - House price in Iranian Rials
- Price(USD) - House price converted to USD 

## Notebook

`housePrice.ipynb` loads the data, analyzes correlations between features, trains regression models, and evaluates predictions.

Key contents:

- Exploratory data analysis
- Feature correlation plots
- Linear regression model
- Regularized regression models (Ridge, Lasso)
- Model evaluation and comparison

## Results

The regularized models like Ridge achieve lowest RMSE of around $15,000 on test data. Top positive predictors are area, number of rooms and presence of elevator. Presence of parking influences price negatively.

## Requirements

Python 3.x
Common data science libraries like Pandas, NumPy, Scikit-Learn, Matplotlib.

## Next Steps

Some ideas for improving the model:

- Add geographical coordinates to train geospatial models
- Neighborhood specific models
- Ensemble modeling
- Automated hyperparameter tuning

Let me know if you would like me to modify or expand this README!
