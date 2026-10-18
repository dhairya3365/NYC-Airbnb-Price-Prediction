# NYC Airbnb Price Prediction

A machine learning project that uses Linear Regression to estimate nightly Airbnb listing prices in New York City.

## Project Overview

This project explores Airbnb listing data and builds a Linear Regression model to predict nightly prices using features such as borough, room type, minimum nights, availability, and review activity.

## Dataset

- Dataset: AB_NYC_2019.csv
- Source: NYC Airbnb listings dataset
- Training data: 45,748 listings, according to the project report

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Model Performance

| Metric | Result |
|---|---:|
| R-squared (R²) | 0.487 |
| Mean Absolute Error (MAE) | $38.32 |
| Root Mean Squared Error (RMSE) | $52.54 |

## Key Findings

- The model performs better on budget and mid-range listings.
- High-priced listings have larger prediction errors.
- Additional features, such as location proximity and host ratings, could improve predictions.

## How to Run

1. Install the dependencies:

   `pip install -r requirements.txt`

2. Open `NYC_Airbnb_Linear_Regression.ipynb` in Jupyter Notebook.
3. Run the cells in order.

## Limitations

The model does not capture every factor that influences Airbnb prices. Predictions for premium listings should be treated as estimates rather than exact prices.

## Author

Dhairya Chovatiya
