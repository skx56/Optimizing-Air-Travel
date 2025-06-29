# ✈️ Optimizing Air Travel: Flight Delay Prediction

This project focuses on predicting flight delays using historical flight and weather data through machine learning models. The goal is to enable airlines and passengers to better anticipate delays, optimize operational planning, and minimize disruptions.

## 📊 Problem Statement

Flight delays are a persistent challenge in the airline industry, affecting customer satisfaction and operational costs. By analyzing patterns in historical flight and weather data, we aim to forecast potential delays ahead of time.

## 🚀 Features

- Predicts flight delays using supervised ML models
- Handles class imbalance using resampling techniques
- Integrates weather and geospatial features for improved accuracy
- Evaluates performance using metrics like accuracy, AUC, and confusion matrix

## 🧠 Machine Learning Approach

- **Models Used**: Random Forest, XGBoost
- **Techniques**:
  - Data cleaning and preprocessing
  - Feature engineering (time-based, route, weather-related)
  - SMOTE for class imbalance
  - Hyperparameter tuning for optimization

## 🗂️ Dataset

- **Flight Data**: Historical flight records (airline, origin, destination, delay status, etc.)
- **Weather Data**: Temperature, wind speed, precipitation, and visibility
- Merged and cleaned for training and evaluation

## 📈 Results

- Achieved high precision and recall in predicting delayed flights
- Improved model interpretability through feature importance analysis
- Supports real-world use cases like proactive rebooking and resource planning

## 🛠️ Tech Stack

- Python
- pandas, numpy, scikit-learn
- XGBoost, imbalanced-learn
- matplotlib, seaborn

## 📌 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sakshamojha56/Optimizing-Air-Travel.git
   cd Optimizing-Air-Travel
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
