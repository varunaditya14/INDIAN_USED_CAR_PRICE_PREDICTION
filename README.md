# INDIAN_USED_CAR_PRICE_PREDICTION
# 🚗 Indian Used Car Price Prediction

This project aims to predict the selling price of used cars in the Indian market using machine learning techniques. It is designed to assist users, car dealers, and data enthusiasts in understanding how various factors influence the resale value of vehicles.

---

## 📊 Dataset

The dataset used contains the following features:

- **Car Name**
- **Year**
- **Selling Price**
- **Present Price**
- **Kms Driven**
- **Fuel Type**
- **Seller Type**
- **Transmission**
- **Owner**

> The dataset was preprocessed to handle categorical variables, remove outliers, and normalize data before feeding into models.

---

## ⚙️ Techniques Used

- Data Cleaning & Encoding
- Feature Selection
- Exploratory Data Analysis (EDA)
- Model Training:
  - Linear Regression
  - Random Forest Regressor
  - Decision Tree
- Performance Metrics: R² Score, MAE, RMSE

---

## 🛠️ How to Run

1. Clone the repo:
```bash
git clone https://github.com/your-username/used-car-price-prediction.git
cd used-car-price-prediction

2.Install requirements:
pip install -r requirements.txt

3.Open the notebook:
jupyter notebook indian_used_car_prediction.ipynb

Results
The Random Forest Regressor gave the best performance with an R² score above 0.90.

Important features: Present Price, Year, Fuel Type, and Kms Driven.

 Use Cases
Sellers can estimate a fair price for their vehicle.
Buyers can avoid overpaying for used cars.
Dealers can analyze market trends.

Future Work
Include car brands and locations for regional price variations.
Deploy as a web app using Streamlit or Flask.
Integrate live scraping of used car platforms for real-time predictions.

 Acknowledgements
Dataset Source: Provided in CSV format (uploaded)
Inspired by the Indian automotive resale market




