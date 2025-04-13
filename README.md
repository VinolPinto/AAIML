# Predicting Stock Prices

This project uses a Long Short-Term Memory (LSTM) neural network to predict stock prices based on historical closing price data. Implemented in a Jupyter Notebook using Python, it utilizes libraries like `pandas`, `numpy`, `matplotlib`, `scikit-learn`, and `tensorflow`.

## Features

- Preprocessing of historical stock closing prices  
- Sequence generation using a sliding window approach (last 60 days)  
- LSTM-based deep learning model for stock price prediction  
- Visualization of actual vs predicted prices

## Requirements

- Python 3.x  
- Jupyter Notebook  
- Required packages:
  - pandas  
  - numpy  
  - matplotlib  
  - scikit-learn  
  - tensorflow  

You can install the requirements using pip:

```bash
pip install pandas numpy matplotlib scikit-learn tensorflow
```

## Usage

1. Open the notebook:

```bash
jupyter notebook Predicting-Stock-Prices.ipynb
```

2. Run the cells step by step to:
   - Load and preprocess data
   - Train the LSTM model
   - Make predictions
   - Visualize the results
