# Flight Price Prediction

## Overview
This project predicts flight prices using machine learning. It uses the **Random Forest Regressor** algorithm to predict the price of flights based on features such as airline, departure date, source, destination, and flight duration. The model is integrated with a **Flask web application**, allowing users to interact with it and get flight price predictions.

## Features
- **Flight Price Prediction**: Predicts flight prices based on input features.
- **Flask Web Interface**: Users can input flight details and receive predictions.

## Project Structure
├── app.py                   # Flask app to serve predictions
├── flight_rf.pkl             # Trained Random Forest model
├── data_train.csv            # Training data
├── data_test.csv             # Test data
├── requirements.txt          # Dependencies
└── README.md                 # Project documentation

## How to Use

1. **Clone the repository**:
   ```
   git clone https://github.com/yourusername/flight-price-prediction.git
   cd flight-price-prediction
   ```

2. **Install dependencies**:
   ```
   pip install -r requirements.txt
   ```

3. **Run the Flask app**:
   ```
   python app.py
   ```

4. **Open your browser** and go to `http://localhost:5000` to interact with the app.

## Model
- **Algorithm**: Random Forest Regressor
- **Evaluation**: The model is evaluated using R² score, RMSE (Root Mean Squared Error).
- **Hyperparameter Tuning**: Optimized using **RandomizedSearchCV** for better accuracy.

## Dependencies
- pandas
- numpy
- scikit-learn
- flask
- pickle

Install dependencies using:

```bash
pip install -r requirements.txt
```

