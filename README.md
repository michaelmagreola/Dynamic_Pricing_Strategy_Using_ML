# 🚕 Dynamic Pricing Strategy Using Machine Learning

This project demonstrates how machine learning can be used to optimize ride pricing dynamically based on customer behavior, location, time of day, and ride preferences.

## 📊 Dataset

The dataset is sourced from Kaggle and contains ride-related features such as:

- Number of Riders and Drivers
- Location Category (Urban, Suburban, Rural)
- Customer Loyalty Status
- Booking Time
- Vehicle Type
- Expected Ride Duration
- Historical Cost of Ride (Target Variable)

## 🎯 Objective

Predict the **historical cost of a ride** using ride features, allowing businesses to set optimal pricing strategies.

## 🛠️ ML Techniques

- One-Hot Encoding for categorical variables
- Train/test split
- Random Forest Regression
- MAE and RMSE Evaluation
- SHAP for explainability

## 📁 Project Structure

```
dynamic-pricing-ml/
│
├── data/
│   └── dynamic_pricing.csv
│
├── models/
│   └── best_model.joblib
│   └── preprocessor.joblib
│   └── processed_data.joblib
│
│
├── notebooks/
│   └── dynamic_pricing_model.ipynb
│
├── requirements.txt
└── README.md
```

## 🚀 How to Run

1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook: `notebooks/dynamic_pricing_model.ipynb`
4. Run all cells

## 🤖 Author

Built by Michael Magreola
