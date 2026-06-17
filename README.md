# StockVision AI: Predictive Analysis of Stock Market Trends


## Project Overview


StockVision AI is a Machine Learning-based stock market forecasting system designed to analyze historical stock market data and predict the next day's closing stock price.

The project combines data preprocessing, exploratory data analysis, feature engineering, regression modeling, pipeline automation, and interactive deployment through Streamlit.

The final solution provides real-time stock price predictions using an automated machine learning pipeline and a user-friendly web interface.

## Objectives


- Analyze historical stock market trends and patterns.
- Identify relationships between stock market indicators.
- Build and compare multiple regression models.
- Select the best-performing model using evaluation metrics.
- Automate preprocessing and prediction using Scikit-learn Pipelines.
- Deploy the model through a Streamlit web application.

## Technologies Used


- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- Streamlit
- Joblib
- Jupyter Notebook



## Dataset Information


The dataset contains historical stock market information, including:

- Open Price
- High Price
- Low Price
- Close Price
- Volume
- Company Information
- Moving Averages (MA_7, MA_30)
- Daily Returns
- Date-Based Features


### Target Variable:


next_day_close


## Project Workflow


# Phase 1: Data Science Workflow

1.Problem Definition

2.Data Collection & Ingestion

3.Exploratory Data Analysis (EDA)

4.Data Cleaning & Preprocessing

5.Feature Engineering

6.Model Training

7.Hyperparameter Tuning

8.Model Evaluation

9.Unseen Data Prediction


# Phase 2: Pipeline Integration


ColumnTransformer

StandardScaler

Automated Preprocessing

Linear Regression Model

End-to-End Pipeline Creation

Pipeline Serialization using Joblib


# Phase 3: Streamlit Deployment


Interactive User Interface
Real-Time Predictions
Technical Indicators
Signal Analysis
Risk Assessment Dashboard


## Machine Learning Models


The following regression models were trained and evaluated:


#### Linear Regression
MAE: 2.2058
RMSE: 4.9901
R² Score: 0.999563
#### Random Forest Regressor
MAE: 2.1670
RMSE: 9.7514
R² Score: 0.998330
#### Decision Tree Regressor
MAE: 2.9198
RMSE: 23.0702
R² Score: 0.990652

#### ** Best Model**

Linear Regression achieved the highest R² score and lowest RMSE, making it the final model selected for deployment.

## Key Features


- Historical Trend Analysis
- Correlation Heatmap
- Candlestick Visualization
- Moving Average Analysis
- Model Comparison Dashboard
- Hyperparameter Tuning
- Unseen Data Prediction
- Automated ML Pipeline
- Interactive Streamlit Application

  
## Streamlit Application


The deployed application allows users to:

Select stock companies

Enter stock market indicators

Generate real-time stock price predictions

View technical signals

Analyze market trends

Explore confidence intervals and risk indicators


## Project Structure


```text
StockVision-AI/
│
├── Predictive Analysis of Stock Market Trends.ipynb
├── stock_app.py
├── stock_price_pipeline.pkl
├── requirements.txt
├── README.md
│
└── Dataset/
    └── stock_market_dataset.csv
```


    


    
## Conclusion


This project demonstrates how Machine Learning Regression techniques can be applied to stock market forecasting. By integrating data preprocessing, predictive modeling, automated pipelines, and Streamlit deployment, the solution provides a complete end-to-end workflow for stock price prediction and financial data analysis. 

## streamlit app link
https://stock-market-trend-prediction-7d5ttfspyebqbltkwjasix.streamlit.app/


## Author
Mohammed Sinan

Aspiring Data Analyst
