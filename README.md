Housing Price Predictor
A machine learning web application that predicts housing prices based on various property features using Random Forest Regression.

Overview
This project provides an interactive interface to estimate house prices by analyzing key property characteristics such as area, number of bedrooms, location preferences, and available amenities.
Features

Predictions: Uses Random Forest algorithm trained on keggle housing data
User-Friendly Interface: Simple web-based input form for property details
Instant Results: Get price predictions in seconds
Multiple Features: Considers multiple property attributes for analysis

Technologies Used

Backend: Python, Scikit-learn, Pandas, NumPy
Machine Learning: Random Forest Regressor with preprocessing pipeline
Frontend: HTML, CSS, JavaScript (hosted on Bolt)
Data Processing: StandardScaler for numerical features, OneHotEncoder for categorical features

Dataset Features
The model analyzes the following property characteristics:

Area (square feet)
Number of bedrooms
Number of bathrooms
Number of stories
Main road access
Guest room availability
Basement
Hot water heating
Air conditioning
Parking spaces
Preferred area location
Furnishing status


Installation & Usage
Prerequisites
bashPython 3.7+
pandas
numpy
scikit-learn
Setup


Install required packages

bashpip install -r requirements.txt

Run the model training script

bashpython housing_price_predictor.py

Access the web interface at: https://house-ml.bolt.host/

How It Works

Data Processing: The model preprocesses both numerical and categorical features
Feature Engineering: Applies scaling and one-hot encoding
Prediction: Random Forest model generates price estimates based on input features
Output: Returns predicted price for the specified property


