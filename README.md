# Ethereum Price Prediction using Generalized Linear Models (GLM)

## Overview

This project predicts Ethereum (ETH) closing prices using historical OHLCV (Open, High, Low, Close, Volume) market data.

Three regression models were implemented and compared:

- Generalized Linear Model (GLM)
- Linear Regression
- Ridge Regression

The models were evaluated using multiple regression metrics to identify the most effective approach for predicting Ethereum closing prices.

---

## Dataset

The dataset contains historical Ethereum market data including:

- Open Price
- High Price
- Low Price
- Close Price
- Volume

Dataset file:

```
data/ETH_Historical_Data.csv
```

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn

---

## Machine Learning Workflow

1. Data Loading
2. Data Cleaning
3. Exploratory Data Analysis
4. Outlier Detection
5. Outlier Removal
6. Feature Scaling
7. Train/Test Split
8. GLM Model
9. Linear Regression
10. Ridge Regression
11. Model Evaluation
12. Performance Comparison

---

## Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- Mean Absolute Percentage Error (MAPE)

---

## Visualizations

### Histogram

![Histogram](images/histogram.png)

### KDE Plot

![KDE Plot](images/kde_plot.png)

### Violin Plot

![Violin Plot](images/violin_plot.png)

### Pair Plot

![Pair Plot](images/pair_plot.png)

### Pie Chart

![Pie Chart](images/pie_chart.png)

### Outliers Before Removal

![Outliers Before](images/outliers_before.png)

### Outliers After Removal

![Outliers After](images/outliers_after.png)

---

## Model Performance

The project compares:

- Generalized Linear Model (GLM)
- Linear Regression
- Ridge Regression

using:

- MAE
- RMSE
- R² Score
- MAPE

The models achieved excellent predictive performance with an **R² score of approximately 0.99** on the test dataset.

---

## Project Structure

```text
ethereum-price-prediction-glm/
│
├── data/
│   └── ETH_Historical_Data.csv
│
├── notebook/
│   └── Ethereum_Price_Prediction_GLM.ipynb
│
├── images/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/m33rab-ch/ethereum-price-prediction-glm.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Open the notebook:

```
notebook/Ethereum_Price_Prediction_GLM.ipynb
```

Run all cells.

---

## Author

**Meerab Chaudhary**

BS Computer Science

Machine Learning Project