# ShipCast - Delivery Time Prediction

## Project Overview

ShipCast is a Machine Learning project that predicts the expected number of days required to deliver an e-commerce order.

The model uses order details, product information, shipping methods, distance, weather conditions, and other features to estimate delivery time.

## Dataset

The dataset contains information such as:
- Product Category and Weight
- Shipping Method
- Customer and Seller Region
- Distance (KM)
- Weather Condition
- Warehouse Load
- Order Date and Time

**Target Variable:** `Delivery_Days`

## Machine Learning Models

The following regression models were trained and compared:

- Linear Regression
- K-Nearest Neighbors (KNN)
- Random Forest Regressor
- Gradient Boosting Regressor

**Best Model:** Gradient Boosting Regressor

**Model Performance:**
- MAE: 0.73 days
- R² Score: 0.62

## Technologies Used

- Python
- Jupyter Notebook
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn

## How to Run

1. Clone this repository.
2. Install the required Python libraries.
3. Open `ship_cast.ipynb` in Jupyter Notebook or VS Code.
4. Make sure the dataset `ecommerce_delivery_prediction.csv` is available.
5. Run all cells.

---

This project was created as part of my Machine Learning learning journey.