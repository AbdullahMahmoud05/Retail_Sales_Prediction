# Retail Sales Forecasting System

A Machine Learning project that predicts retail sales (Total Spent) using customer transaction information.

## Project Overview

This project uses a Linear Regression model to forecast the total amount spent in a retail transaction based on product, customer, and transaction features.

The application is deployed using Streamlit and provides an interactive interface for real-time sales prediction.

---

## Features Used

- Category
- Price Per Unit
- Quantity
- Payment Method
- Location
- Discount Applied
- Year
- Month
- Day
- Weekday

### Target Variable

- Total Spent

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Streamlit

---

## Model

### Linear Regression

The model was trained using Scikit-learn's Linear Regression algorithm.

### Evaluation Metrics

- R² Score: ~0.89
- Mean Absolute Error (MAE): ~23
- Mean Squared Error (MSE): ~941

---

## Project Structure

```text
retail-sales-forecasting/
│
├── app.py
├── train.py
├── requirements.txt
├── README.md
│── retail_store_sales_cleaned.csv
├── data/
│   └── retail_store_sales_cleaned.csv
│   └── retail_store_sales.csv
│── sales_model.pkl
│── model_columns.pkl
│
└── notebooks/
    ├── retail_sales_forecasting_analysis.ipynb
    └── train.ipynb
```

## Installation

```bash
pip install -r requirements.txt
```

## Run Locally

```bash
streamlit run app.py
```

## Future Improvements

- Hyperparameter tuning
- Advanced regression models
- Feature engineering
- Model monitoring

## Contributors

- Abdullah Mahmoud Fathy
- Ahmed Abdelmonem Abdelfattah
- 

## License

This project is for educational purposes.
