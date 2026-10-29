# Gold Rate Prediction Using Machine Learning

## Project Overview
This project uses historical gold futures prices and USD/INR exchange-rate data to estimate gold prices for the next 30 weekdays using a Random Forest Regression model.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas and NumPy
- Scikit-learn
- Matplotlib
- yfinance

## Workflow
1. Download historical gold futures and USD/INR data.
2. Convert the benchmark price to approximate INR per 10 grams.
3. Create lag features and rolling averages.
4. Train and evaluate a Random Forest Regression model.
5. Generate a 30-weekday forecast.
6. Visualize historical and predicted prices and export predictions to CSV.

## Model Evaluation
The notebook reports Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) on a chronological holdout period.

## How to Run
Install the dependencies:

```bash
pip install -r requirements.txt
```

Open `gold_rate_prediction.ipynb` in Jupyter Notebook and run the cells in order.

## Important Limitations
This is an educational forecasting project, not financial advice. Predictions are estimates and are not guaranteed to match future market prices.

The input data represents global gold futures and USD/INR exchange rates. The converted price is an approximate benchmark in INR per 10 grams, not an official Indian retail 22K or 24K jewellery rate. Local taxes, premiums, duties, and other market factors are not fully included.

## Author
Created as a machine-learning learning project.

