# Flight-Price-Prediction-ML

# Flight Price Prediction using Machine Learning

## Project Overview

This project analyses flight booking data collected from the EaseMyTrip platform to understand airfare pricing behaviour and predict flight ticket prices using Machine Learning regression models.

The project was developed as part of the COM7022 Machine Learning module at Arden University.

---

## Objectives

- Perform data preprocessing and cleaning
- Conduct Exploratory Data Analysis (EDA)
- Perform statistical hypothesis testing
- Build regression models for airfare prediction
- Compare model performance using evaluation metrics
- Generate business insights and recommendations

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- Jupyter Notebook

---

## Machine Learning Models

### 1. Linear Regression
- R² Score: 0.9045
- RMSE: 7014.09
- MAPE: 0.4335

### 2. Random Forest Regressor
- R² Score: 0.9899
- RMSE: 2286.33
- MAPE: 0.0578

---

## Key Findings

- Business class tickets are significantly more expensive.
- Ticket prices increase closer to departure dates.
- Airline choice strongly impacts airfare pricing.
- Random Forest performed significantly better than Linear Regression.

---

## Dataset Features

- Airline
- Source City
- Destination City
- Departure Time
- Arrival Time
- Stops
- Duration
- Days Left
- Class
- Price

---

## Project Structure

```plaintext
data/           -> Dataset
notebooks/      -> Jupyter Notebook
report/         -> Final Report
images/         -> Visualizations
```

---

## Future Improvements

- Add seasonal and holiday trends
- Use XGBoost and Gradient Boosting
- Deploy using Streamlit
- Integrate real-time airfare APIs

---

## Author

Bala Srinivas Kadali

Machine Learning & Data Analytics Project
